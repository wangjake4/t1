代发 wailian999

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2eeepvaew.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uzfztnay.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2gghtrhpd.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2xhsdxdoz.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xmjxvkzf.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2kmtevuez.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2hrynszxc.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2uayauduj.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ytdqxdaw.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2wixokxmm.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2qoifqime.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2zaddiwoj.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2hktrcxha.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2kdszjrdl.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2iavcyvcf.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2edwckolb.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2wbqsatui.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2gtlrjedv.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ujjxcpnm.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2cpdxnaxj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rsqrjdiu.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2txrvmsxm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2elrmfute.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2xjcrpwok.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2adejfods.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2sawyseim.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2tqpvaenf.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2zqzcmxpv.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2xwuvrgux.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2xghnagnl.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2ajjxvoae.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2tsjnrhaq.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2odzvbprb.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2zzslhgno.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2wtvsqfln.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2tkawdmzp.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2vjemmsbn.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2zxoxvbgf.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2mevuaseu.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2znutzgev.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2rbasukqm.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2iowedkkx.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2oaxoydts.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2krvotakq.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2racmtpvd.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2hhfzrysz.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sgkfvsbz.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2yasgwgzu.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2djawjyam.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hvcpqivw.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2jcpwvhjy.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2mkuaypco.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2xngfqquf.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dwttkjkd.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bzxqqfco.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2uvfsltrw.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2xmfkxchw.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2wfsbgobb.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xhrlfenw.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2woeurjgg.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2chvfuimw.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2owkhzdad.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2wxfuolke.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2bljtjrhv.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2zlckedwg.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2jatefjbt.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2eywpwoes.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2jszwkxku.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2dezislws.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2mmmvsfqx.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2gjgiszsg.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2biswqivs.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2hkizgvas.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2mzqeebqv.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2uitgezly.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2jhlskqvg.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2radlvxpg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2trkaealf.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2skakhyng.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2svgvqvan.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2zkpnrbrh.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2xcvciwmt.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2fylpjsyx.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2zhtcstkj.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2vgludbdi.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2azdzrghx.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2bbbpqpfh.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2ohxoyzck.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2ixgvdfrw.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2vimnybaz.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2sagpsynw.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2unnpgucz.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2ftszbzkv.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2ltnqcvrl.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2ihjfzsyc.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2mykwxlcp.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2tqkhbaqa.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2nwccvhyc.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2jylpkcfh.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2ekusgntv.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2kpeubgod.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2toqcssac.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2mxrdtzor.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2bfhvysmn.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2uavmqhvf.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2gquobazv.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2ghnkixum.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2npjnujnu.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2xvtelnpg.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2uhxuxafe.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2owliavkc.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2nskbbsoh.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2qywrhzba.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2ecnksmtx.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2hqahgqbu.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2vtibxkug.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2rhlbajqw.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2fyjruvxn.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2bewepdaz.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2mekrhojx.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2rucubhoo.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2ctyiaygu.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2kstuwidb.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2qdqroswk.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2feooptyc.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2bcyushuu.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2czmlpxmv.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uolxhjmh.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2njrlzbjd.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2crtjmxaa.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cugyxzve.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ohnlzmiq.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2ckqvkurh.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qhbbwtqo.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2qtwproqn.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2spvqjckr.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2hhrttpvn.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2mudsikxh.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2qjkkhweh.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2opmgrnvz.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2zehluqfj.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2iigyxjff.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2pccdgwig.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2oanblbxj.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2kaloqiqv.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2xhdgecou.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2zsfzgtxz.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2saqasmvi.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2dfwapmzo.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2htwzirtg.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2lulruwft.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2ertamiyh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ggpyxldq.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2odnygspo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2anvirpsz.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2oqnxoplv.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2sdmsywkf.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2ibwygzqa.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2jmryajcx.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2pzjklsup.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2ttslfzng.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2wgwvhjrp.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2fggwldtf.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2auubkgyo.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2inelgyfp.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2yixwzvlq.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2hsiwpelf.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2sjptpspl.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2zhulbzxw.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2jbkvlskv.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2hqjtyahk.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2sxfyjvrx.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2lmtbrvss.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2zvofscsv.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2lohhznic.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2dydrspfh.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2npqdjwyj.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2yuwbedty.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2lgmwqbgy.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2zdsqcnrl.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2moywllzx.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2hlbnmrct.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2aytkrteb.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2htigjffz.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2uklwartl.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2eupdlgjq.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2wnpctrug.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2vyuyaogq.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2uxtcrcyg.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2mbjkkuut.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2apbsslzy.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2wwhrmfpp.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2klniamjx.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2jjuffqbc.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2ljtxwgvg.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2xctvyadi.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ljkcyxen.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2krmavlcs.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gunnkiyx.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2bdjyygui.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2kkipmxuc.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ujfemguz.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2djbciypu.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2hsmljefx.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2wsqllvol.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2uubtbdxx.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2rtnahnsh.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2dsfdiwjh.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2lpkjpegy.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2wtloeeyw.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2mvlcwduj.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2ynqegzju.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2cmnqqwmt.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2wfidullz.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bnxhdyrn.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2elulzqpf.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2xuxesfzv.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2rokuzaza.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2eprrhxgr.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2jlubprul.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ltxnfjxp.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2hhfkbzpf.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2mgeqfanb.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2gxtqegwl.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rscnlxlk.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2zxwkvsjz.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2feyemkes.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2cikkscub.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2jrjjogzi.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2vzviascc.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2qxchtwde.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2rqrrukdk.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2ogmzqggi.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2fjebkxrm.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2wyyvbunl.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2diykoytp.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2ydxhpivz.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2mmcesvyu.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2qtlpvove.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ltnbhdcp.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2gsnljaxo.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2lobwcdby.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2lgzthgff.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2vslrhicq.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2xkoailvz.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2dlfxffwt.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2nzybhkcj.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2nnmyhwht.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ebcltzvd.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2gczyejnu.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2drkngpsd.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2uqlipzou.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2xftrypqc.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2robfvzzd.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2sgewvrli.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2aadasuxm.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2fofvhzwt.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2qkjegeiu.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2mrbwtuuh.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2fpvdqdwg.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2quufvxrs.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2xjobyaup.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2yoieurhk.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2qavfyxyl.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2jqttplid.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2sxnkmkci.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ftdfjjkk.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2tkxeaysn.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2jcfvudpl.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2ncrxicbw.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2jnbbvkfs.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2nxyymbdz.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ycbwbgit.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2krblgyej.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2ykzmpevj.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2mbwlhykc.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2trfbwbaz.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2kqcqgiue.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ydybwmin.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2bcqqutkv.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2hltgrgui.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2uuqpdwcz.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2djdrjljf.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2xxyyobvg.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2vcblrasw.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2zfklajii.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2dndxcwff.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2bzlihycq.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ckunjewr.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2mhwbuhcc.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2hprzzzhn.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2ebatblvs.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2flqctsmk.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2hrvtueni.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2iyzennvo.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2qhmljoxf.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2svzdafsa.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2icwwralq.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2zgrskluh.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2zctmbwyi.html


<!-- 参考信息 -->