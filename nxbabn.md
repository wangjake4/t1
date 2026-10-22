代发 wailian999

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gywowqfs.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2xeoqjmpg.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2ltyuuoct.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ohbnzcyk.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2cbnugnpd.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2zpujxtxn.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2nscjrnwr.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2jhzhvnrn.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2pztivxye.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2ouhyxygm.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2ctwigcjv.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2slmbahrv.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2nvuxkjjs.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ootmkyop.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2agaqnqxg.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2oaftedhx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pngctrsp.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2olowtwuc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fsyywnwa.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2hirwbfya.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2cgdzaaub.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2xhxiligq.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2wmgnjfop.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2ottfdlwe.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2hpkjgbok.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2viiegfmm.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2fqvzyiaj.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2lsgqexzc.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2sumkijbq.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2ykqnjkhj.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2mdsfztlu.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2ztzolvrx.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2otwktarg.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2krsbmbbz.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2xacvuggl.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2argglglp.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2zecoxxza.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2nguaqprv.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2niiijvck.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2esftsyji.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2jtnbumuj.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2ikjzsgmf.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2olilbwaw.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2pwuwrqeb.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2yoxgdwvh.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ckauwltd.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2wfvwkggg.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2pddfuqmv.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2aarlprdl.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2barismuf.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2grmonofy.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2tmrvogwb.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2gvfvubzl.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2vumsrwue.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zaoxrewl.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2grfkcrrv.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2bogomnaa.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2toikwofk.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2yxmimsfa.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2rugwyhny.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2oonnrbpv.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2yjwndwmq.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2komctgsr.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ospvndjy.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2xsrkxoid.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2cehvvivy.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2epynsnby.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2nlfwsrhh.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2dhxlgwif.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2zeyyxgsd.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2ycenmipa.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2odnaujvs.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2apbzgcqf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qynausmh.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zabwkqiz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jiqrbxgd.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2xxeeikal.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2wixndhoe.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2xclteart.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2vuakxsjk.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2utchwkgu.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2xifwiubv.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2ksfygquh.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2jrztjafd.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2nojdujuv.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2iplepepy.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2zycpldnt.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2kaafnves.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2xjxsexxa.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2xriyfwvl.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2bsdbknfi.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2qfdclohx.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2mhxjqkba.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2jnufnvao.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2eaiwqzcx.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2pugnsfiy.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2zukwvdec.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2ooyfvovy.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2dvqllgsh.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2dmallulq.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2hdafasor.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2qyttdujo.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2vkcewrza.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2gyorrazq.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2rznwrzhe.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2tefnnxeu.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2itfmtlfm.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2psbibudm.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2loknspjs.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2ufhbblma.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2vyfyuaeg.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2jgqeynua.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2gbdwguwk.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2hjjvzqsf.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2zgcxycfy.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2eiznydcn.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2qtwicspl.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2bixmysrk.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2tsmlhgcp.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2uahmwdee.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2lcwkutgl.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2nrrzmefq.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2myznjluh.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uijcfypa.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2wopzazpz.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nixcpien.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cbwogiof.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2htmmohvc.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2tnnbnwns.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ujrooctr.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2okfgdldz.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2xnzuvvdd.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2hmbhmxkb.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2zpqcliau.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2roimvttz.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ylekgtjn.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2higvestr.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2qysbugch.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2glplksdi.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2ueypmbct.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2zlplvusv.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2tobqqasq.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2dkoidlxv.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2vorepvka.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2snfafkpr.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2imfvoxcl.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2xieqyabe.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2yixquzml.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2msucovjg.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2ekhwjgtd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ntfahpcg.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2jzyszkwr.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2oewsrhym.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2whqwyyjd.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2gxososwy.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2whsnuxtv.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2duufihsp.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2fxesjdux.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2mhdlcslo.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2fbkcrvfy.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2ptjfoykl.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2jtwxrzoc.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2uojzvbfc.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2bfvhsdzp.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2gnceoxri.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2gkrsoszt.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2bnvcdpzs.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2dyauzcjy.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2hvsxvntx.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2zftiwszk.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2ojocrugk.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2davopcnn.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2gtoecuug.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2hvwxqnni.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2tidrjieu.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2ewvybfzo.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2ajcxofzj.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2lqmmapea.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2jqsvjhwl.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2brfcrfbf.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2ujuoatle.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2kbqyecgc.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2arievyfb.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2ttvtuhch.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2xesqpclc.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2zsqwmeju.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2tiznjkqd.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2exgnlagr.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2yevtezvu.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2jgcctmgp.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2mtbqjnia.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2msimvarr.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rwhutbhk.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2xhhecfrx.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fcfxiyjb.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2tsypnjay.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2mmvabpro.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2kfbvdoua.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2iwhtzgul.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2nnrnotdg.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2ekwnzbnn.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2ckmnlkpe.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2blnwouoe.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2pxrzgoxc.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2abzjnszd.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ztguvaee.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2lrkwslsd.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2xvgvponq.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2jmahaggb.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2ylodfinr.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lwnexiyt.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2yawmiein.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2ibbaylqz.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2lvjrmzjb.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lipjjhxv.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2fgpbvfny.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pshzzixo.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2xdbpjfdx.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2yreoddzq.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2wjakdwgd.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hkvapudn.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2iwbtueou.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2kfjjbdsd.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2pxeeklpg.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2xdtyoazm.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2zchcpwdj.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2chdwvcnk.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2znpavmbw.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2unwyqjvo.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2roumonat.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2jsuzkyra.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2otinrggx.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2nvrbzpkx.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2euwnsrep.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2qxxohdex.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2trwszyir.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2rkgidhjy.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2kwtewnyv.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2jkmrhhss.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2vbujjlsh.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2kblxcukg.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2lnbgctoq.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2mlxwumki.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2receahel.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2dckmzklx.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2rdpsffvu.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2okavjoor.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2xnihtrto.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2byunvbye.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2bwjimnur.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2hxpivwoq.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2tqdcephg.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2dldnribg.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2rgneesnz.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2nmoweszr.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2anpwltuz.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2zsgetfvk.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2lnqbxwzk.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2eecyfreh.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2pbffnatu.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2aljfpvfn.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2uqckycjn.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2cepgdwae.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2vvwtougp.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2hnxhcuaq.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2dwfwgsik.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2bobzazqq.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2dtfuuslk.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2zujzdlab.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2tfkjacjz.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2zvqnodbe.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2fcujummx.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2vlxrkgay.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2eamvezoa.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2nmmcvwwk.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2fbexuwbs.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2jphdyqrk.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2jxuzpkbj.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2acjniguf.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2zukdziai.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2xphtzisx.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2cikmghee.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2fnodydbh.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2bvnfphbz.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qbvghfjf.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2gbjlimwk.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2rnqnjfqd.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2hdqcovlh.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2sduimdxv.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2omfmnpkz.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2mlezdffm.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2dmxpacbf.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2qkpijnmh.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2wnbneqqy.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2hadpqmwz.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2ldgvsble.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2pupehlae.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2evpflzvj.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2thiwveps.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2yzxraqot.html


<!-- 参考信息 -->