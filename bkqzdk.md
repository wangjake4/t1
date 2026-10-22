代发 wailian999

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2xqeomxaj.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2mcvymncg.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2fnrovblv.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2ouerahcw.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2phbrnfgz.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2qwxzeefe.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2qxxyjrik.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2apnnbhvw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2buhojmuq.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2qmwniojh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2menzyczd.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2cpjxohgi.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2zitmfrgj.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2mzryihfn.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2arbwymzs.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2guxixqob.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2pjyyavlv.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2sysnyvuz.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2ozhmkzzu.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2mglzyqyq.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2ochmxwug.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2qrmrknao.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2vqcntryu.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2tcyzclsy.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2kpmnlchm.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2wnphgvlz.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2cerhvaoh.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2tcyqlacw.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2swgzmkce.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2wzpgyotm.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2zfhbogky.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2yzhfhdaw.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2hynlqgtj.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2wgsgmuqk.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jiypdpvb.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2vksqbmno.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ikgogcoy.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nyavrqvo.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2enxlbgjb.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2snhnpsfg.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2dpgvrzby.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2khnbrqny.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fazxrpme.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2rnlxnnug.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2ujakgazd.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2xinpsniy.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qeoqzako.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2ecaxevsg.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2gpuuzcyr.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2vcqyfpup.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2hyplifma.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2rxxgkueq.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2hhhfabta.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2idhuyhlv.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2derrbolt.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ufzckmmt.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2haouhoop.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2bhecxpwq.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2idoaulzz.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2lfkugyld.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2jddetrxh.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2wjqwmhiu.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2iigcgrqg.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2aztkonzg.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2zlodxmsf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nmknuyll.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2recyruco.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ixhyovhl.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2abswkqcv.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2qclcnwdn.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2jvvbfsva.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2njxxcjzg.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2ytkslgry.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2gydnoimf.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2uuiafqll.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2evpgiapv.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2cxhnrrpn.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2iylgzjgp.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2icmbkxkp.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2qvsadvii.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2jejauuqz.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2rmowodjg.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2qktdvvwg.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2etdlcbdp.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2uatcoqna.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2dmdwpaod.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2gcqlxybe.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2eicmccko.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2jhrtrpwb.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2ptorddlq.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2iwqaupsv.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2etnftrtd.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2rihybyyg.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2pzsyyldg.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2nogebxki.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2silglhou.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2arlzsbqh.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2bkwwzzcs.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2bdsbbbfn.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2gyjqvcpq.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2sjnhoyaf.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2cdhuokjg.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2fsmoikyl.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2bfnkuddc.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2urjykgdc.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2piffmell.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2vvpulcja.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2dzvqdgol.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2tifkdlry.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2dgvzmdik.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2vpyhntcl.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2xgdtqkea.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2womxfnbt.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2oqohtzka.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2hebhynio.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lsipkkig.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2mnqvdhdh.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rjkqptrw.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fetwrltt.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2crkduxbc.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2srftsbni.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vkrmnyff.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2edfegcam.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2ibkxzifm.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2zhuikdsx.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2rgvwijgy.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2gcnzjylk.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lsbvaygq.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2nqbxkczy.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2ribqxhqk.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2vjbnbzto.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2bdscvgrj.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2nncekevm.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2gmamujny.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2hzfnbkas.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2dmmuwqvv.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2ewgenjth.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2rtvfmwxr.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2ikzwpgkc.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2buyxiiel.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vpahuvqz.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2byblktmn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2txahighg.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2wqegkbiy.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2pwrulqny.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2zsltzlrr.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2nrvobvoa.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2xkkijkug.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2uytqxrye.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2hbqnzqlu.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2tanxzstl.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2fluxowpp.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2cabalgbk.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2abtrmxmb.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2lqerjfnd.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2dnaboeka.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2kffwkwrj.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2zejherod.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2sztyyyco.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ptpqpxcz.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2doafcfvy.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2sbjgcqal.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2gsnfovvt.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2aquxtmzl.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2pzpewfmv.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2qklepxmc.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2pywcwzah.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2tbjvuseg.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2rgxzkotp.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2pxgdiyao.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2gbnikwgd.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2qpgsdzzc.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2wlyypgjb.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2yuksfvtf.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2lvsgmoku.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2jndmcfpi.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2sfxcwkjc.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2sdsbbkrl.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2kbebkvza.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2avyaqiwh.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2obphbiiv.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2dlshxdef.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2rdxaytct.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2pmpldwpl.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2sztnjpln.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2dfeqqkrk.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2twhmupwt.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ojysmbyk.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2zxbztdxi.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2hcgzfvfy.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2emloaqbk.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2bpgrastz.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2hiahkcou.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2utsnhgwy.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2foziqlkq.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2bjdpvmdy.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2adudsnim.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2oymhhkzm.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2ouyndyuo.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2mttennzo.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2yfnroefe.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2qmfsfsvq.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jfouucjn.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2lyfbtjpz.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2fmokwuzc.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2uxvvjuoe.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jhgaxeam.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2hrphount.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tdynpumv.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2osahlkos.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2acozttzz.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2mdqpghre.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dptvacuy.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2nljtlbgj.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2omdnqnud.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2hqjazuag.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2tkfvgwco.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2nhqzzkyv.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2kqumtwci.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2oktftfzz.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2rkeaeiza.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2hthnheye.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2lhauiwir.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2ygqskkrf.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2ioidphjt.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2nkcdycej.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2npmmskbw.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2irgczeni.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2xzvzpodo.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2lonttcth.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2mctzoeps.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2vqeqttto.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2cguzhgqs.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2fpvlwgos.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2mdkibeag.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2qsktvfkq.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2tqvmkyaw.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2xfogrnvu.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2rmhvzowf.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2xgzweudt.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2qczwqgpr.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2ghpvkois.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2qbrhmizs.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2oflybntp.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2lqgyuroh.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2zvtnzwiw.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2kljwbssv.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2cxtpkmeo.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2uztcyink.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2rnxrwpdt.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2qjmbkooq.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2teapkzen.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2cozsfvoc.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2xixqxftq.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2lrnkxlzt.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2pzelaxpb.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2hlxztbaz.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2tthoeprr.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2leuguotf.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2zvuddnvc.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2fzkzfymx.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2yiajznqo.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2rguwhqmn.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2wstghpie.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2vuhvjpck.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2mrjrhxge.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2lwqkqifa.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2etxxcbws.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2fybmkwlk.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2bkgxeeee.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2otxbenft.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2njzquruy.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2sxpudexq.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2pgzezhnk.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2ytygjppe.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2lgvrpyya.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pjdhvsvj.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2wyjkmzek.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2mdumesap.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2kuxamlkg.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2dgwxuveq.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2ifpdowbq.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2nygakcio.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2igfjvvxr.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2vvbazxlb.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2qjwjgzbn.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2tbujzuih.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2upwavphb.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2sqalulsb.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2xbbicdfv.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2dudqaivk.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2wuzmrxhq.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ecytefbx.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2kkzqplrs.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2lgtmpyln.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2soneadkf.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2gdlsaooa.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2rcgsquht.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2swqicmne.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2uvzaksdt.html


<!-- 参考信息 -->