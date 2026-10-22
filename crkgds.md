代发 wailian999

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2ccbztigh.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2loxipqbv.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2fkskypao.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2tcqfsurw.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2onppzwwx.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2dtneugnu.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2oolhhcul.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2dkqdcivc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nzyfbchc.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2zmkqfrtn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dqasjvtc.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2zyqfhgcq.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2usiyewaq.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2rsjiryos.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2gxthcsyk.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2rioslscb.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2wsrhicli.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2qlsmleji.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2gojnnlia.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2tpucsprk.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2opsfatky.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2srkgptsx.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2nghzgyyi.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2pxapazio.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2lfhvfajz.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2vkqfvztt.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2foelvbfm.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2wnsgueeh.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2moppivbr.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2ygwhxtnd.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2jrnfynhf.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2kkcrcosn.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2qgthymko.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2uwxaeehr.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zfbxmoxp.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2ggztejdd.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ejnwjjir.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2trquyctb.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2lpfeojue.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2oambvfpm.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2lnpcbfwk.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nefdhjlb.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vcxvqavm.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2pzcdtyjy.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2dmstaikl.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2rekijxvl.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cofclwdo.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2wfxwvnau.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2ylesuhsr.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2xgocuiwb.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2hlqrxhsb.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2jdiyqzuz.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2vnpxordm.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2twtthnsc.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2ovnwzxzp.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2vnyhfdfv.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2lbrxzyti.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2zjlhxjgl.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2kyocshfg.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2pocedrvy.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2kqdzhzgi.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2yyhldhoi.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2rlyvgbtq.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2whvyotcg.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2qswqvfco.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pzniozfx.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2eaamoxlb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uzelrcyg.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2ksbfauxx.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2snnejasa.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2ttuvpfko.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2wcdmivph.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2nsdefhpa.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2csybzkza.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2yjnrlrqs.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2enbomtpd.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2rpzqffuz.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2bmhpefzh.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2zooosuft.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2vrkuetqc.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2atpkmygx.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2nlnnfqia.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2dcwtdedg.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2oxfefbjb.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2tqozkrri.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2tmnwhdxd.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2inshvhdl.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2zgllvrmr.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2rubfdwwj.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2qedrrvyf.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2bpzbavpy.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2osgoaytn.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2klxgsxrt.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2eungxyit.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2edgsiuvo.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2gzeinayu.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2nvbzstct.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2ynoaebff.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2wahkhobd.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2malfrqht.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2luooadkr.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2yxromado.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2sublmuvm.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2ydoqzfxs.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2qpmfvlzk.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2lkrgrrje.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2qeyiezbe.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2lsdyhebn.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2nnjmekye.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2wwaujikc.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ugkomers.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2yhoygais.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2crhovqzf.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2kzlebuiu.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2mtsfnsak.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2faljjszf.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2beioijob.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2diceavca.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pigofaoj.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ofbfeedt.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2ajfqlugk.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fccpqpax.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2tuwhpxgu.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2souidfil.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2lfksbpka.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ftwgsbxw.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2inaiwmjv.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kxlukiec.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2rvyazqyw.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2exuhlslw.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2xkuwzyqd.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2auykbkqc.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2jcioymsr.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2pzoexyey.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2vgwgvmed.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xakhenyd.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2kfwnowso.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2nxjecyfz.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2bgbbcwcc.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2rdhowpic.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bevhjvbt.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2ouslmgby.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wbenikes.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2yiucirri.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2axxfyyse.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2ezljcooa.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2jeeggepi.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2vctbnmfn.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2xrhehpsd.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2wjlyckda.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2kjhjmjal.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2bugwznoh.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2tuyfbvei.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2micmycnq.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2cbapabxf.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2cuvdojqx.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2xigimdcg.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2kaokoabw.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2pgoukbvj.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xgzkrrwi.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2oviisvnd.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2ruyalfrg.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2lhspddur.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2bcmqsyks.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2awmhxcft.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2yfaxexht.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2lqaxnays.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2pugjkihm.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2siqfnliv.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2pyruommz.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2mltnqxns.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2nctrdqok.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2ogxxktkm.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2vyyqpoxm.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2fxpkeeau.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2ihzrgsag.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2jsqtllei.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2ooptcbxo.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2bkkiernw.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2olfudnvs.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2ldhxpywz.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2anlvdowh.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2vbkwzbma.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2kjleqlvj.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rbkrjldh.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2aveazeih.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xxiwtjvn.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2svwztynb.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ndhztoxr.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2vcpkcjen.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2hfjlojdb.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2phymijhz.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2tzzhuwxz.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2iyniojhw.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ibwzpvol.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2hkhbykhe.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2vmyowbov.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2usvqopap.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2ywxudqdv.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2inzrlndg.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2yssfjmxm.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2csbxbxsu.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jdpapqeh.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2ttzyskbu.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2hbwmqiem.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2tbsepxfb.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vgpudbvn.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2guhgkmcm.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dssbtpnw.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2bqhnykau.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2sssrdfag.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2geiabmjp.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fkrjdtum.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2kqnvonmq.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2qklmvgta.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2pbtwjcdd.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ydgukkyo.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2kkzhzmmj.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2fhmxusrc.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2oihhcaoo.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2qorfzhdy.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2jsbdxpyo.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2bmkgvcsj.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2ghfywyci.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2dfrtukbg.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2igatcoqe.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2iiiwbhcg.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2xidmyfgo.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2lcwhwznc.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2xdnnwcyd.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2wgfcjgbt.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2brwxcfar.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2ijvtwoup.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2onuohpmf.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2bcsxnjpv.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2vbejvwaa.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2vzaryyvk.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2koromwun.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2rjuopgbj.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ukvjpiin.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2xvyjflkp.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2nfxozvtn.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2tbubdpvc.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2vvxvqgwx.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2isczbvwk.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2slujzkrn.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ovpuenmd.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2fctknauu.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2mkteniho.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2pdattqso.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2skdmelnk.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2nrvtnaoc.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2mfrzrwns.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2uzthtqzb.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2lntibubz.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2ximcfxkq.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2diaeimfy.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2wpmukueu.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2tpatnibi.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2ocvvcjmp.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2jumcjual.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2dlfobeek.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2bwwsfwnw.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2szrlejyv.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2xtegjths.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2aseqzfjb.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ejiepomi.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2urwkxxgj.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2uzrkohwe.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2mpfmbabp.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2xlwdmifa.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2ievjmzck.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2crycybjr.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2banizcmj.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2qipzhlwg.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2teqgdkig.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2izqtyvft.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2kcywlwdz.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2dudruzle.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2lqsqsmvs.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2xtrtokjp.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2tskmsnee.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2mtmnayxr.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2auqondyj.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2qgaoyvte.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2gfhrswtl.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2htyfjqwu.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2kbvmhwze.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2jvlepnkp.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2ripexyoi.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2wpiwdrpb.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2xfjelalc.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ociqmzfk.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2iphbszbs.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2rtkfvsau.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2peczmkue.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2uunaoupe.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2mjpcfnxx.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2fhftrlez.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2nenlbanv.html


<!-- 参考信息 -->