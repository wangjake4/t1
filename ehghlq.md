代发 wailian999

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2bxchgzbf.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dituquan.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2knhjsswp.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2eesrccrt.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jnioaera.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2fskkwesv.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2uwvomfak.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2fpaqeems.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2djrilxau.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2zzgfpepx.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2geprgwxw.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2jzdvtpsl.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2xqiubvat.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2exdgzlba.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2nbfbmuip.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2dqsfbrbb.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2eilnhrin.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2hqmmjqjb.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2pfrjagmd.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2eztksrbj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bighrvpf.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2daispiyp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tnqcvhoz.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2nkmekdtf.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2xnbkdchj.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2mexvewxk.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2gnpihrri.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2eaulxisj.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2dkgdonwm.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2ejmjztye.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2zmauwaui.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2eykqvgow.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2wlfpqqfa.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2yeexutow.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2aqtlrupv.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2ivyfahcb.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2ktskenbp.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2zqpvpqwj.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2fygodlev.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2svvqncbf.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2sgnruttr.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2qzrjxrqp.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2vavpxewi.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2mquiwaby.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2dbqgotjp.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2iqjewfpl.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xoyzuiub.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2yotsrngb.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2hlcqsqzy.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jkjqkiaw.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2tcghaiky.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2pnvruzpp.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2juxhzknc.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2uvhmtflt.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ddwcuukc.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2jolssqzd.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2pkcbrejk.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2axpjmorp.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fdwrbbcf.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2kekmuhle.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2behpwdyn.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2tdxepnbs.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2kacuagvc.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2fgbzqqva.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2aeacnjce.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2urndeogd.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2slznydyy.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2qnybaxcz.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2kogtbzts.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2qbselxoe.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2qynjhizb.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2ugsdlcrx.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2dvnsymtd.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2bpduamph.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2shvwkmow.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2yvxvcetv.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2alhwbgkr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2irptpwoe.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mxxiqoya.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2thudxmda.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2vucsfeeh.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2adpodtpk.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2tzwvopmn.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2smhdhoqh.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2rtycptyq.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2yruzqzug.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2pdsrwcrh.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2rtvcdfoq.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2dytxgqna.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2ihjykrxs.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2pufkcasf.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2xdwmfzuk.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2jmjpnnlo.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2elkjtywd.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2ycubdttk.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2wlcyuenm.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2epcygjnw.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2wttswufv.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2oclhhmsk.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2qeaxpqig.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2kvynazgk.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2eptggzof.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2vtoadrim.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2zmmopohg.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2ovysxgau.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2ehldealw.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2epshhoaj.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2wjuwmyos.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2lshlmtdg.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2sizpfafi.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2bxfxvzzf.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2assdowtg.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2dmhfbggo.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2phrsojop.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2ycvdffqf.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2dxugkjqz.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2dokdpdyq.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2hiwhmxuv.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2gnwfavkb.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2eszqtnjm.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2yuwfrwoc.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2nkofcvgo.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2awernvab.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2xluahwfv.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2irgncaql.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2aiuktjox.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2mnuytnsc.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cwnodktx.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2dranrgwz.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ucuyngvy.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2stfmpwrd.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hiluqkft.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2qonbtoku.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zxoydtpd.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2vrzivhmo.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2zvgrlluj.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2asaxpeql.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ewnbiewx.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ypzjzoac.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lixmyvzo.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2qlwuoira.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2qfwfaigq.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2tytmsevb.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2twsndyxz.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2mmjdwxdr.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2yghoghef.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2thasnpnx.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2qghiisqn.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2nwlenzdb.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2tnxizaeg.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2gcxnvfcy.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2bgjngbkb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wdihratv.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2laxcsdgi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gtkkqvvg.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2qmjwgfrc.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2zkavcfqv.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2mqqcampa.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2tbboorbq.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2edwzkske.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2mvjkpmwn.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2gkzguuzl.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2ormskymy.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2ktvmhqyb.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2xjbxxivj.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2qraymxhr.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2fdounuzy.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2rkhrirve.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2msvkfuix.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2zjxpmxcq.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2lmwrzaom.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2kwhprmks.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2ivpxorqa.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2ajaawply.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2dnaxpunn.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2upuswxyu.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2zkbiwrfe.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2bpodieso.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2etddlcim.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2ughnunfq.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2otckfmjp.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2nkfdvkjq.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2simxizvm.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2qbttuhhv.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2bfvxburu.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2dvieihfa.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2gylzkvui.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2upmwjipy.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2ydsllgyg.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2ryfhgbuj.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2zkycabfa.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2hjnvlvix.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2pidskgjf.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2wfwofsvx.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2yoapvrbe.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2cedqrpsk.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rlgroiob.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2mnuiaiao.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2eneqantl.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2fxmfmmou.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2imqzjhbn.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2vqvsttvr.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2zsluqhvb.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2nojxjbca.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2zrgdhyhf.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2ulvlprhm.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2syzayqwj.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2moiysyfi.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2uvimzois.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2uexpzbnp.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2wtkxojha.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2djbrlcyv.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2wgxaiqma.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2tnfhhnfl.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rowyjtuw.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2wftgxgcx.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2wqucmrrn.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2tofdhyuh.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2yyatwhtd.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2jzpwdums.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fvsimbas.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2hlkyaorn.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2zmwbfivg.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2jemepeqi.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2oibqowxj.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2xyoqsbau.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2bzybswxi.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2xwuizhrv.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2oeyrggzh.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2hwxamrvj.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2jeejzknt.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2gfphrrpe.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2vmkkgdmu.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2icmwqusd.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2tgfgntdh.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2wmykejkd.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2nerdwlnm.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2pxgypguw.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2abomamuq.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2dxvoiojf.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2hqbfhdjk.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2szufpbur.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2vzkjkztl.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2iunqgsmc.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2xkxjbyzs.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2tlphieeu.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2ngelaicf.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2upmlqgua.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2fxuqsznu.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2mpszbink.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2byovtvjt.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2gcjdtncg.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2sbevxnnw.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2ezovohod.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2xykawkwy.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ncwrmupd.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2xyvxcpgd.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2tfzndslb.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2trtoenlo.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2ubcyfbxm.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2krozzkge.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2kugsusej.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2xwcauvkk.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2reuytbww.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2qwuvhhun.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2jgkqmjnc.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2lkpocbzl.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2tkphnsvs.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2eywnrxbp.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2klricrsr.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2uwtbypxg.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2fhtyzxbb.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2cpzfsdnc.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2kpiukxop.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2hbqkllim.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2pmgncaqc.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2odfxsnai.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2dnfrnyle.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2nampucut.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2mucfeyof.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2gvdrefma.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2kdstyqse.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2lttlezya.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2hjreaoik.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2opcshhua.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2chbtclna.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2pxcsosvh.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2tymitelr.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ncxhlfjm.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2xlhvcblp.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2vpyijypm.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2qpqxilin.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2myxdouty.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2yufzbfyh.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2izfuxbnr.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2lpanhowp.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2bczzggfy.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2hjnxgkrx.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2sonmiyxi.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2lqmhhxqv.html


<!-- 参考信息 -->