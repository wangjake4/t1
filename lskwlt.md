代发 wailian999

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2sicxpbku.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2itbomblh.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2bganntbv.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2dytapjdq.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2mbuqbncf.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2fetwyhbn.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2hctzpyey.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2dhswxjbf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vjdkukyq.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2tjewpawr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zwmulaug.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2fjjahmau.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2dcffktyn.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2cdhiewuw.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2bjarskhr.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2nauavklx.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2kwjkyhan.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2ydzwswga.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2qjfrnknx.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2ifpflbyx.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2fngjxzwm.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2esectwgl.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2jmdrecje.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2irjoephs.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2nhnnwvpm.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2jlgbxgdr.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2xatjruae.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2suuopjej.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2nmatsmxs.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2rflknorh.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2fyqmvrze.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2itrjkzth.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2lhqoskfp.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2xkmczfjo.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2btpmvejf.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2xivjirka.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2llptfiqg.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fcprigmo.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2hwdpeqnr.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2pxgsnmtu.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2nppsdzuc.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2sbkylvnh.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pogzsyca.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2kovkcqcn.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2psbcujqe.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2mssdypca.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vexnzzsh.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2qgqkxhvb.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2mevvtznw.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2mzrykwtw.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2rhypafoa.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2adpckpwe.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2fnuprqsm.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2inqqpkwn.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2cxpqduou.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wdcswiue.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2flkmloio.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2jtqmuqwk.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2niymghky.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2plaianrp.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2ceeteqco.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2rfihzdwd.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2cprrrwpi.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2xtnarcmz.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2sungpooq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qnddgyya.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ikzwyder.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2oktimqno.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2suiiilxe.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2evicmztx.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2fcsjmvtx.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2xuikwdcb.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2zbdoiiqj.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2manbewib.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2gewodvrl.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2kunfiqpy.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2veezvvwa.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2wcultxxq.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2sqeiqkcc.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2gqwbsmry.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2djnhglpf.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2atixpezz.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2ogcdpxhz.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2wapbyunu.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2uqesitpa.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2rgvhjbht.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2gcahente.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2excbuyrl.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2lqbdyrzm.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2nxggluku.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2vmydqukw.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2pbowtlot.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2kvipfnvb.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2cmjpgkrw.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2htvjpqdg.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2lnuvocqb.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2nbzhvrlr.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2hromdtop.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2dtklfskp.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2ltoayaja.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2qgzvizsy.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2ewncokri.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2trwycfbd.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2wyxdabcw.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2hjjiqzsc.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2urkyzhwv.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2lakzwvpx.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2ngvrcnmf.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ccnytvgd.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2osgueisj.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2sndnsset.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2wkrtgzqe.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2ykxtdrfd.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2rndtmjjp.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2jctnflus.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2plckopbo.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2dnprpfyg.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rjaxunms.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kmrrqdri.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kwltuljj.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2mucqfhvm.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rvyfzgnt.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2vvllzrcx.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2afakwqnc.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2tnicofjt.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2larfyyht.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2bhbrfokw.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lwybnoum.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2mympbatn.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2olifabsw.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2oighxhrl.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2mvlhbizq.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2kdhuoduv.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2qulxurpt.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2svdnkoha.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2pvupfgfo.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2oafrexua.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2dzzkwrle.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2slrvmhri.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2kxpdkhwe.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yvbgmyfn.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2oodiagtx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tvoimydx.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2tasxgpnf.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2qurwcnhc.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2orhtxmto.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2zxvsxgyy.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2dbhdhnxj.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2klebeblg.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2zivovejl.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2rumbbtnb.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2qandwahg.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2pihifgrv.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2zwmnsanc.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2jdclkeqs.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2qzncmghj.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2ezcrqvhc.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2xpyulzgb.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2snxbdyrq.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2lrfufgru.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2cxhoebjh.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2manthtke.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2xaqfrkos.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2jmgqldls.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2kafforzi.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2drckexfd.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2quqgmkzl.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2lxoqwfyz.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2przljoon.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2wndrmscy.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2ymvfitbq.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2tlipiqpx.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2duyrnvyt.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2kqvmmfck.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2kppnfdut.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2xzlueejx.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2gsqxaqlg.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2rjrebqfp.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2jilbpxvw.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2gcgppvyb.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2cfwyrvhi.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2ymnkdpll.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2eqwylpsr.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2tropevwg.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fpkvngsb.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2lvosutvm.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kldxllau.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2xefevoov.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2yjfualis.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2kwyqemul.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2wcvvbnvv.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2fljyxada.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2whtwoirm.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2wrdsmdjo.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2nppwogzg.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2rlfurlyt.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2lnqennra.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2faxfvkjm.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2hkepfqpv.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2ipvyljpp.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2ytcftqwi.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2lspnfctn.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lcrjrgxi.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2qkkzjpmv.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2hbuxfktr.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2snhqnrwl.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2folhdbxg.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2wkobietm.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2byfbuzml.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2ypkukwdr.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2fskumaig.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2reyezmnq.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dcubymzs.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2cfpecxym.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2havgvjxm.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2yrkkgmoc.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2pvzkghhs.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2himfvopx.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2sqeowmnl.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2rsdclcfv.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2czvrjrwk.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2udoollyq.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2phmwvmgq.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2otpyhfvx.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2wdganxjc.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2qrqmzobl.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2beovejsm.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2kvgpovlz.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2scdkwsqo.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2izamiuiu.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2lswpbmrl.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2hrijbpxx.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2lcggtvix.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2kpyraulx.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2rpgwphma.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2zsvuxjzv.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2hqvnrxeo.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2jfmgdett.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2orcuxjmr.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2yfvbegio.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2bbioyvbt.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2dewjjfsa.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2tuaupjnf.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2cegijnby.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2quqalpqs.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2ewcsodmc.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2glcevafg.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2nknkknqz.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2yyfebaie.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2ursivkfy.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2dwvuuuzj.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2tdqnnrbi.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2qbzbmajr.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2ovoisbdl.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2boleeiwz.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2kaikkuak.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2vxcprsfc.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2tnvyrfom.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2qsfmftpc.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2vlxeuftl.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2umlwenaj.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2qjrhblhc.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2uuoiqokd.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2ingpiqcb.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2hykeeljy.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2ahhmoyyc.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2hwbdqioe.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2nnxmkvum.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2sxxfudfo.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2vcpthgou.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2rapdvrtv.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2ausdwhhv.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2oiggnatk.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2uvrganyf.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2rhxwpuya.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2sgjwndqc.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tbviirpc.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2nvuvtgfi.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2mzlhvrcn.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2rpxcvbdi.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2htkttkkb.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2tjiolhxm.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2pgijylgl.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2gbgtsyml.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2ictfgclh.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2nxazvspq.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2iixzvysq.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2avofqaya.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2necuasnr.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2uriqiqjr.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2rfalqgov.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2xftvwkmk.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2jcthqgvv.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2yqjgtozh.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2krkeugxf.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2rypvebrg.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2hpnghsyv.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2urhacxnb.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2iprjzpzp.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2hkswotde.html


<!-- 参考信息 -->