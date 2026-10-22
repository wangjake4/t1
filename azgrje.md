代发 wailian999

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2mnozflbk.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2sklnedis.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2amxxzfyl.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2zqywauhv.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2ofhrvesu.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2lzwlummt.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2fbpzveka.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2lvsqgvca.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2uuwukncs.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2rdmbjknq.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ezqennbx.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2qppnfkny.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2eglzgpps.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2cokgkhqf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lxkbjwyk.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2kbvqxlfm.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2ewctjbvt.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2bvdrruju.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2lncnlrtc.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2mjksdeda.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2swjtipbv.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2yeedpjgm.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2hwfyexzr.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2hxshfybb.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2pyikdsqg.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2vlcpszuu.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2zvjmfcej.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2jmsipkmo.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2bbaxcjml.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2eggdlpcc.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2byzszyro.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2nqdguvsj.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2gidzpmql.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2ptbbzfmc.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2qquyamle.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2gxglaakd.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2cfxsjbvv.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2vbtjueqw.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xvtbovyy.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2mdmnvclb.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2pbqvtqnf.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2opashxxl.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2tpyercmx.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2ehcvdfdp.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2cqtmwtus.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fnfoduar.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2csvhiymk.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2zlhupqrl.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2nozzhxzq.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2sgadmfjd.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qhgtcxzk.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2tycoyxco.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2utnhqrwj.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2ripmynzm.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2ottjycag.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2cfowyrmr.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2obgbllkz.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2shmkrfuj.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2lqavyuzq.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2prrqrnoq.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2tnccrwyo.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2aaamtvjr.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2pxcofhka.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2shfcbxjz.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2cdnwscds.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2mupmqoxk.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2xdqivveh.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2aeswngrk.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2cwuoxmfw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mtcmhsua.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2yqzwbous.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2msgbyyql.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2jeqhhxje.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2ssijcfwt.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2mdwaikbe.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2mfhdrcmz.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2dudezewa.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2mjohfrpw.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2mymucnxd.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2vskqrnjo.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2ramojdnl.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2bcxgclia.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2opgnzmar.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2rarkubfp.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2cypmzenk.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2orgkofln.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2olvhsnwa.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2ureldoja.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ulzkshtx.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2bhaeqhye.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2piormqnn.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2gfjscbrg.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2pldxkozo.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2mdxkhfls.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2pcypvfsm.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2voneftue.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2votqkiqf.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2iuxaksft.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2hfaegagi.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2mxjxpabk.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2ugyyhqlk.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2xzousdjr.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2sltdvest.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2sybrbzdm.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2mkfzjihq.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2iesirgvo.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2wslpeuhc.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2hlelekio.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2kybwyrwz.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2rttjqegt.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2mujsgsin.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2ykoubpxf.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2kfhsfhdn.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2csrxnhcm.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2oahtdbxl.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2xwsqeaur.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2qbmzbjsh.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2oqiptddb.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2seyxjngw.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2keanseua.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2ecrwolim.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2etxzvqag.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vrcluzbq.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hzdkzwep.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2guhlmxcg.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qkesnafp.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2tfhjyias.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2hkdogjkz.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2twdvmkms.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2fravsfju.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2eavgeqyv.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ugfojmku.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2arcwvkzg.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2kbkxspmz.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2dwhsdxte.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2izzrvlzk.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2fhvjxkfy.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2uszlaivi.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2qbwdfyft.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2olfzfpus.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2cokbxcjh.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2qfdbbxvf.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2kmnwzxuk.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2xfcbsfyg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ngzekabj.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2qidiuctl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fsuckwst.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2zavttvsc.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2avvjlira.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2wuqqsmqu.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2aucjlplb.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2xfxktloq.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2gqdrlftn.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2noatwdui.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2akwqdpmj.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2crrnmaph.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2jvocoxmm.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2xdzkaccq.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2trglresg.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2ixubmfmc.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2arsxutnl.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2egdswndg.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2rmovpons.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2rhmkizqv.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2glgxkvaz.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2pisgamtn.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2lmcospqc.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2zryzgxmg.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2vmmqpivc.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2mgrayqzj.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2safoppye.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2pydtfoze.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2vbhljgrw.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2bnkzoths.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2qaimqsyw.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2pcsdinta.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2pxdqjjik.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2bctvkknb.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2ssfrzdwc.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2ssffnlmm.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2bxxixzqi.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2hptgdqwt.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2ezwbaixp.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2azououvb.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2afdfryfd.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2glhoyyzx.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2dmxjuuqb.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2omeysggo.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pfbjbaxf.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2jwajvycy.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fgokpneg.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2inrljssn.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2wlkeruov.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2pmcaogho.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2uoqkbtwh.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2srakiity.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2pllwisol.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2psirjpaa.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2uqpymnmy.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2aukiazkh.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2sirsjqus.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2wrilkxez.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2sclirpyz.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2laxfshgv.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2opwxcguc.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2vfvejhxd.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hpufybqm.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2lxkbccin.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2sdoiexor.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2xuqnqlcn.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xvkxicpf.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2haenmqxq.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pqebdvkl.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2ububshqz.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2azgqdyld.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2soceqjmy.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ptsgchfj.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2vnvalrtq.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2wayntjmp.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2vfluoqgm.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2omfhyznd.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2nfzpcwjg.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2boxqthpq.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2qwlkganr.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2fgcombvx.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2qykplczr.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2dfphicpb.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2tuzwwywh.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2gogjxsri.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2xahotjmv.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ygjsmulm.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2dlpeszbw.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2iexpzajn.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2bmgjwsyx.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2qzoodjnt.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2igzpzapq.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2larsgqyd.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2sjcbnfzs.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2pcbxwnhj.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2utqhsizu.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ezcybyzn.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2ycqpgzao.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2usngsiho.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2bjmitqto.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2ndsyxnem.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2zqgddobq.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2gpcdhhgh.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2lyiynsph.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2xwezmzcp.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2ckpaiajn.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2wvkkrrza.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2qujrzwei.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2pfimonrp.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2esqovxif.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2wtlwhdnl.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2nuhuqith.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2gcgrambe.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2osbenbqv.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ufuavcnw.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2ouvyfulp.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2dgqpvtrd.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2fiawnobn.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2nxwlriqn.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2ddhqucod.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2eqnhxujc.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2zxlofanl.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2eubcgocs.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2rdwdfetw.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2zfrkijbz.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2fmurejis.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2eqcbdicn.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2jheycnqt.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2clsosryo.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2xxzsmknx.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2exhupslg.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2uictnrij.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2rwrjwdez.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2teufesbx.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2piwyfevl.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2juuwsrvh.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2krrfqmcf.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2gegncvba.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ngkrrftk.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2tszbhsdi.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2drccxevc.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2jxrajnbq.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2tuoclatq.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2olbenzbu.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2gbjnqhih.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2wchdaljw.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2xgwdesou.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2shhmqvwv.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2xbbdkkhl.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2epouqxrw.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2rqxojbcc.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2xxlvsljl.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2bfxlrkfb.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2uzlrrqbm.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2mvogzygp.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2gkebbxhm.html


<!-- 参考信息 -->