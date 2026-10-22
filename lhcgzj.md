代发 wailian999

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2igwqorgw.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ikyuydpz.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2pqgpojen.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2eojtxruo.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qkzdhfvw.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2ikxoeyvy.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2jiaumwsu.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2acugdpxt.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2agmdgrvh.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2tpvjdhpn.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2zunufapb.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2dnsessgw.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2lequbpdk.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2bcwgxjaa.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2clfcxeqo.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2pndrupee.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2jkzhvqaz.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2tmbsvtjb.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2mdplepab.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2yznaawrm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tsfirljg.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2ciulwuih.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2upxwqmex.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2cxwazbar.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2ycjtjztn.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2hljnugzr.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2cqzammzp.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2khyiejlv.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2jisrkxwf.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2rpkrsfeu.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2ghtsbtws.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2yrprjjcq.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2mrviyvie.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2rmwculcg.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2rqtuvxvv.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2dxkoooss.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2pymbztou.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2hdzsbgen.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2tdwrbahz.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2eedgwmqa.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2wkutqflz.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2nhcrppiq.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2nhsrwmam.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2zyhvavxr.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2spdbwazt.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2hbqjmegv.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zqomifti.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2jtxzcxmh.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2fonlzxtm.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ojsgkuul.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2gejvwxng.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2hfvahifp.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2rcgcgwpn.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2imneurni.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kxyrkpqc.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2ivtwlnuj.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2margcauz.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2sughgvrj.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mylxcbdr.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2qrjfiztm.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2zvbnqlji.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2yanzonzz.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2ixttzexq.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2quzdhtdh.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2lthqnsng.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2qmtwgatw.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2gzafwqwp.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2lsohoyqj.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2bbrgfqno.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2lrspxtoj.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ajqisote.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2enkmbuba.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2ejayietw.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2wnvosadc.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2kwamrufo.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2kjgzrpsc.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2dajjltnm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lhrrnhwx.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tlkgeosy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2avptjqmw.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2vqunnvqo.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2epmjwvpv.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2emdyzdvn.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2bxasesxp.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2uxandmbd.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2ohqmvulq.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2zorffhwa.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2kwxhvfts.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2agbjgeff.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2ewkljzly.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2zvqgsict.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2yykpcxgu.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2frhcdmyg.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2lecbsviv.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2cfxcwhpa.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2zklnnnce.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2cjqvmxta.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2ivbmvkcu.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2qhatdglr.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2rmyuiaim.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2bmbwnfkl.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2docgfrxe.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2veidjaxj.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2dpkeikhk.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2qviqoyhl.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2ujzdjrfr.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2yxtxdddd.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2shuxszbh.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2xqmglikb.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2yokrobnm.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2nnezrnpd.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2uwlsjtdc.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2phadqtny.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2cqrxivdg.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2hamsiuth.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2oemqgbpn.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2fgjjxlzl.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2phumviwz.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2pxapqntu.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2uazghwmo.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2baqycpup.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2umzperie.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2xxfifgnf.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2cuvgfcib.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2quonaxew.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2ebfsowwj.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2pdjzqfwe.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oqjckjgi.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2lrtoiinf.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dyuuvadj.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gswwqbrf.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cgkofdrq.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2yjhxvmfe.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ggyedxph.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2crrezigt.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2krztwudr.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2surqzogd.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2camvdheo.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2gfobxcxo.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2olemlfab.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2tcvmamao.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2tzbsijyt.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2accamzkh.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2xvstlsxg.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2hvzqfgwt.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2bqhqizub.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2cdqmtvwx.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2hisqlcks.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2dmahoubr.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2ydspbalw.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2hypwwlel.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2wyhfuzpo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rbbgushm.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2eyrxsodm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yzgbldrg.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2sjmlomqp.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2qqmahgpd.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2ahuhhqwt.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2dycsqlva.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2ccghzpve.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2nwuvtshe.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2ljyemuyr.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2dgybbopl.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2gqwumrdk.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2xzskdygl.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2yzbqzdkj.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2vxlqiasf.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2swxcdrhc.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2zxlempik.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2znavbgpn.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2sgnipdns.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ratjpeku.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2mgnrfnba.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2pcmnuinb.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2kmrujafh.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2auiqblqj.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2huhixulq.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2gtuezysh.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2wwrxejui.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2pkogwjjy.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2hofivupq.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2gnywmkdg.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2jqdfckpu.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2awgxjyga.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2ghrtiejr.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2qpvgieln.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2ghcnbijy.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2djitxbow.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2ccisjwzs.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2oopmsfqv.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2rtmzcqgg.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2qdxfrvnv.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2wiqrtrde.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2wgpxtkhs.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2cyexhebb.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2gwexsgxz.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bednzakz.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2zxaeqluw.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2idewntmc.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2uzseckds.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2jnjpbiua.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2cgsqfrrh.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2bhkvkgrr.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2hlxuuccw.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2wlrczpjo.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2prwgsfxl.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ujijmnoh.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2ekoylrvq.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2enfhrdbo.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2urummnjl.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2kdqbjtte.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2ejsptcsj.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2jnmodypf.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2xelmavfk.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fmhodfuq.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2akgjvhrf.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2yngihsev.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2ntomkmnr.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wrwmqjxd.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2ytwdkemi.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ylkfujez.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2vbreviuy.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2aipxmgah.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2aliqwbgu.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bddztcuw.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2nxsbrtac.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2tmittpwv.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ivlutdch.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2pkoyjuur.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2mdqusdfh.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2gwpvuvrs.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2minzvqsc.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2nrmkjeer.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2ordvwrkv.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2gpetohyk.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2hahnvgka.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2knefbhci.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2tsldrfgt.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2mggvdlyt.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ntnauknd.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2paexooua.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2wmuzemmq.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2mbggjsjq.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2wmvheunn.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2pnklsqll.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2dxgqcvjw.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2wiohyybh.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2gnsqvthr.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2aaxcpujj.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2wivhzrmb.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2rhcpxvma.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2mnnnbovh.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2hsmeamdx.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2ilreozcj.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ocrmvegs.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2cvxpiicz.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2qfnvgvep.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2djqrxsah.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2vmxbzjff.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2zhzifqoj.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2znuwixsu.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2ppefbftl.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2arsubmna.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2pmmvsuhx.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2jllrgtht.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2gyjkinwy.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ylkhqqrz.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2jmerozoy.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ovblafoy.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2itoqpwrw.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2frvjiznc.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2dyxeenhx.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2hfcveaqx.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2rgehjgdx.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2qieurzwy.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2ltedjxhb.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2pzxphexu.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2rbwaiutz.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2kbiiiscy.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2vzehsfnm.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2tebkqldu.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2tqqjfror.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2cwfkuxfy.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2gkcdykeb.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2jlieglfq.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2qxfbaviw.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2idpdqxiz.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2vjzxemem.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2trdwjgdz.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2ppadbhex.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ujgfaqhr.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2vnvhigai.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2erwbcrit.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2ynbggpnb.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2ntauoqna.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2fbapxafe.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2aglabvdz.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2exneeqfs.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2psobvvyj.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2ntzrqgli.html


<!-- 参考信息 -->