代发 wailian999

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rqjycyxr.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2qwatkfel.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2jrsditpt.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2gtgeaups.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2uukltgmr.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2bvfnqupz.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2tqhnjogq.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2dtuhrpfp.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2avinumot.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2kqikrrnj.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2juerychd.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2zhruflnl.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2uqbxfwdx.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2nnetlitf.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2lkpoklaw.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2gkdgbxez.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fqxqmskj.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2bwgpxlka.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2shwixyjp.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2zszqxola.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2ldgicysx.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2krqrrqag.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2pfnzryrm.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2cdluzilz.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2egrjxpws.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2nuyoyygm.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2uzhdamov.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2dbemhsre.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2rirriyqj.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2cqgfgpkk.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2gfxooydm.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2vwmdbbii.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2xmhfovja.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2baqttxuj.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2lawzaxhh.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2dwufdesw.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2vnsnbzhg.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2ctyvsvhw.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2cmogwfxz.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2hyxuvqzw.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2ecvnfdwg.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2ylwhfqrj.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xbbmwgqh.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2svmgqwuj.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2wxznwqlx.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2deivnvkp.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2uqluevvl.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2lbifonaq.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2ikbdnxgp.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ncskhfzd.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vhnqxxti.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2dkmhgzjt.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2ifwqwpyd.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2fppozbfl.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ecvwjxvr.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2eotcashg.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2nhgzsiks.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2mqcifxwh.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2psljxkgu.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2wlkipsbp.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2mqacbnfi.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2undmnorp.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2zqusqvcp.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2rkvlwhgf.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2hpkgiwpu.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2ywzmjbxr.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2spopulna.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2hzubuufn.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2afiqjswz.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2noytduns.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2ljkkfojq.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2mxnimtwk.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2lpiodegn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zouhvbkg.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2etsendfm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ybbwcogs.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2vmyvdhvz.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2kyrxdcga.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2hvfjhpav.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2nhjdugqc.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2arcccnvw.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2djdmjqte.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2pgipqjln.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2txaauwyi.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2cmogjkir.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2rzhhpptl.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2hbvrbydx.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2yvjnxbqo.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2ngsfzvyq.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2gztoqdpt.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2pvqlndhx.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2dtkbcmcq.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2sqlqhfti.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2mxgjngsn.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2udhzaibx.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2jphckuvk.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2xtxmcfti.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2ypzwwtwn.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2mpgmalhs.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2fpndgknc.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2bhajkblg.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2oxgeoycm.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2qvzeeatt.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2fhhxybep.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2ewwsopez.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2ypdjagvv.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2wmjziqsh.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2njhomrgf.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2keifrqae.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2nsvtaant.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2ycusqbry.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2jokybnjs.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2prsndair.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2cngdrjom.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2hdyufync.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2malkktqm.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2chyvbbpq.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2cqpzmwnu.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2viskhzyg.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2uhgnngoc.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2vgyuqryz.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2otzxwdpg.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2gicprvzr.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mpwmepgf.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2bzmbxtdo.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2inbvmzbm.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jcwwrhoj.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gwzeeyeh.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2llqvnwyu.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ikrqusyo.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2snhpibwd.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2kziderqa.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2lhjmblzp.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2vyouurhz.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2tytbhuvl.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nsiurren.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2mhdekehm.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2izcqcicq.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2wrdcnejd.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2ktqlgxmt.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2gcxnglqw.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2ksljnezv.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2nzfqmofj.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2mvzubsmm.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2mzjcglwu.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2ywyfcaly.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2vwjdduyv.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2dqseugar.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wkemhfpw.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2vwfxpjak.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lcuurfng.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2oiqjbplo.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2mjngmwcr.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2bytqdxqr.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2ffdiully.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2ovnevogp.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2aplqpump.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2rdhoxpgr.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2hmzpvfcj.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2igpyeapy.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2krnedxjy.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2xibtjbhy.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2smhgxggm.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2uywedobo.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2miigdrao.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2dpnomxzn.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2ynvkkpnk.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2blvnymfg.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2uoiyergf.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2tvxervxc.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2xejvynsu.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2whjteeyz.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2fdwiynng.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2gtxljmzh.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2scvxdncd.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2pxrtdgrh.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2bvvdqign.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2bsopdssi.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2tpkaztqt.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2wbuymgjr.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2hjtehlxa.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2zpytungk.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2yvqmmedi.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2vzwkzwhh.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2vcqsfbjg.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2fivxbsxm.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2oonxafry.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2jdwljnuc.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2hdirbryf.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2cbfdsigs.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2wfimqyny.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2cypvessa.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2grhfxyls.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2oxfujsvm.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mnfztsdz.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2rmtvdtst.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2fgttljuv.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ybavffzf.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2nmwtnlqy.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2fokaqkbt.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2blrjiekd.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2xujzgync.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2pbkytzmx.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2yqqkeccb.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2gojquzgz.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2paztjruh.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2xejkuncn.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2ovtgbphn.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2llkuhsie.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2rbigymaj.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zhuadfam.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2spleunay.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2ickyvqvl.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2nxpvikna.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bedhdecj.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2kcomolfy.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wpqhhhyc.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2mlbsahdi.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2szqahjbr.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2cmjdqwse.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2sxutgdtb.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2qgfjkmoa.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2jggcoicl.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ioxpbdfe.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2pubmopan.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2lyekivrv.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2xxqjyfmj.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2nvpcdiya.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2xvnhnlob.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2mglyedfh.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2qnbybyge.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2ecthbquw.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2zciokbei.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2rxvmsfbz.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2kcoovotq.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2inlnllji.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2xczrhhvs.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2kwiqxneg.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2uspzftkt.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2qibufphx.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2rotceaco.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2tnegmsti.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2doicszoz.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2kflrhwrh.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2qslwfzgb.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2flguewlp.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2ykbsuhrp.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2reqpnpye.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2rurbpwmw.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2ijxhvpin.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2gbkzfewk.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2djjbfbkg.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2mkatvfgd.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2hioxjitz.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2zeqwhppb.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2juqqqgnd.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2uuygqrut.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2hkamsaty.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2xzttjmpb.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2drvvhlab.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2hnzcgegm.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2qqqedfzw.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ejdzwhwa.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2emwuybvf.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2kujlgrkl.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2ikxtsagr.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2tlzkarnz.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2pccojiyn.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2hjjyivzu.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2dworahya.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2whbmgzkq.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2uenmkgnm.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2sjyobbfm.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2iaugpbdz.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2erdvgmds.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2sjakrvlk.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2xmuoowgt.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2vklwqdpg.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2nyxjuzlh.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2emotvroi.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2hfqymudv.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2iitouxyu.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2esumonho.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2mtjbkwwr.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jwlrwuya.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2mhygmfct.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2leqzdtow.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2ncqptapg.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2shugnfsd.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2gawgprzc.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2tpcprzkv.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2zmzhmayw.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2dqznqntb.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2gwppmpln.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2hayqyrqm.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2rijzesob.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2rsyuheqq.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2uavojkey.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2pzcmfycd.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2rkuhmioa.html


<!-- 参考信息 -->