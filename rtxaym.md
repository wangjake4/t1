代发 wailian999

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2pwocibuy.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gntavrqc.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2nmoykdbv.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2pukhutlr.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2uwbfcgpq.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2qfpfwewz.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2ufnmtswb.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2juverltb.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2figsiaye.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2gqpwnkho.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2kzcmxsqk.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2mmwryzrx.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2fldymplh.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2hqunsczg.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2vqywsoof.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2tduamjba.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2lvvhkbha.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2jtfpfxpb.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2wcknslwb.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2fawekryf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gfixohoz.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2rnvfhszl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xhhmegcp.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2wievajao.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2pekxzgzl.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ciiftybl.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2yponkulx.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2gihhwujx.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2erwezwwt.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2iwbkvibe.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2zwjxkozo.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2rpfjjcpc.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2aqerlgvv.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2ayrasqet.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2qingumfs.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2dhmxdiqq.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2zetwphvn.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2lbnenicn.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2cvckpvfd.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2pnbcjfqa.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2xfzxbwgi.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2hkossxvd.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2krfqdhvz.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2spzhoaun.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2rvmoxufd.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2bczfjuei.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fuldgmkh.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2xssrhjpn.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2rrpyxqtn.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wdirzxym.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2rxlaldsu.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2zgpqomho.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2nqdvhnmp.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zieyymxq.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2immpocvc.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2cclkuvrq.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2wmcgsguu.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2bcbfacwg.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2svqpspiv.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2bckgmomt.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2jngznnkk.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2pmoqttpw.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2eoaacwok.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2kejdhirk.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2cpueqmnv.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2ytdcsmpo.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2eakvfzng.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wycetpmx.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2wdzgltzm.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2tzfvofml.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2iniyygqw.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2amkmetnf.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2zavjahqy.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2gzjfecgq.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2aqxryimk.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2ipnsohzs.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2ostjtzud.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gppazxuo.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pkbcgfeu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vxkccfaw.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2yjamikip.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2pdrjagiw.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2hxpruryn.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2ixyzfrfg.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2pcnygjxf.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2siyuvpox.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2sxcytrtr.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2eccfbfkt.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2rbjeweii.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2hbanpsmz.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2mqevqltm.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ybmnvvtn.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2awbqvzhf.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2jlvdkwyu.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2kbcxqess.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2nashcjjx.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2pxwbnfpz.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2yfdihtzi.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ksjsoffd.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2audzkkmr.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2weohotbs.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2yaoodxkh.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2ncjtdixl.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2nfizokwj.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2bpvnrghb.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2tjxllsdh.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2dgqhmnep.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2asavmstw.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2kysbjthb.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2vishmtlk.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2ogedplae.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2shveegzp.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2wjvdzqcy.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2ffgmyyli.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2tdeyxiqn.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2skfoqsqu.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2wtxpokaf.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2vpiderse.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2louapyrj.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2ooeztonx.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ysarxpyz.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2bvmunzbg.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2wdfkmqww.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2gqkpshex.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2viekhriw.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2ruojvfah.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2rrhcdxvp.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2eqkklfkt.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2fffbiqqi.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oxkggctz.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2giufetty.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gsosonez.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2pmddinrb.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tzcuvhmp.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2jrtbvnin.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2pxdqkguq.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2oxmoupwf.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ijatkvxy.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2zdngloxt.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hpdxmxlz.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2fnlkaqjg.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2jxgfoumk.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2tbwcmggz.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2nmllwtud.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2cgxybfyp.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2hhoidrfr.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2tfzbdjsz.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2kjdlqwmx.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2ohwmdvle.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2kjexhdwf.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2pbapzkyk.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2zdxamguc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ibmokvvw.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2tpxrgdjm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ipdhjlfn.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2qwzzuisx.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2byelqogv.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2ogxxutqz.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2jioxmefu.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2vquunuat.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2cdiypcvy.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2aevknsku.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2hdmjgecv.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2bhgacrrm.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2kdijttgu.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2isctxmmn.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2ypcnjlou.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2nyxlfyaw.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2uxjuiksp.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2csvoaxdk.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2lqygbdex.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2syxnalqn.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2quhmipug.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2rsumtdkv.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2hhzhpyuj.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2fmymbcxz.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2rqdminlp.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2yfetiseh.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2nsxdfwgc.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2hwfelytd.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2zpmjcsgy.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2bwjmmgcg.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2tapcctwv.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2xlukkmyy.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2mmgvfnxb.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2vikwovkh.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2kgybheiv.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2rvdwfjey.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2ejazixzv.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2dnanjjer.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2poqkwnxh.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2utnrdiro.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2tosuvnil.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2oskcnocl.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2shithwta.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2vjpgczow.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ivlqmvel.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2wmxodkkl.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tkemkxqw.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2hpvosqaa.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2rwewfqvi.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2lxpipbrb.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2ibnvwtia.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2obelqriv.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2ihmxnggf.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2cholgqan.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ewomfogf.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2ppashgng.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2dudjblpc.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ikzlulxj.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2tezjzvhk.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2rmyzzxfz.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2jrvoecwj.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2kfryqewu.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vnoywrxz.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2ezvghprk.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2ygyryhwp.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2leuohgdr.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fwknmesx.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2poarrxzz.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mubusorv.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2oxqulsly.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2dkgedbgp.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2mhjwrmlj.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2loerjffx.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2jfnmwjtj.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2kkyezilo.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ycuziisl.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2slgkcjmi.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2hoavnqwk.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2gbylzbjc.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2ecohhvxs.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2trhfprau.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2dqatfsem.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2zzqgcszh.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2ltmeqqas.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2bcyyntap.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2brxajaiv.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2hwgaducs.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2arsracmy.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2dsijbure.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2gyshaapi.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2qbasbaad.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2corqmgek.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2yrpizhdg.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2agzujumc.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2qyvzgkhu.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2crlwdnpf.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2cmwtivkb.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2zfnisrpd.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2gyiwnnhm.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ovequbra.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2jxksmhgr.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2fdrszqua.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2nytxbady.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2hdbnqyjg.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2ytsthyrz.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2xaqrttbz.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2vwehqvua.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2wskkyhcf.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2fttizflh.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2bhfpbkuf.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2mlvemzwk.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2ibizlrkv.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2krumarya.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2pvqlmjkv.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2flxmxikh.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2bayvshab.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2jokwbzao.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2uekjrqwt.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2wyvifehy.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2fuupiezn.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2cyuivxsz.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2lqjlhgmk.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2xaxlrahm.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2dvhumeoi.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2uyknwfgh.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2btwzodho.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ktqdhgvw.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2cyhnajzb.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2synyadtg.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2vxzaksva.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2yxyulwsy.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2abztahww.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2cvdlstkl.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2qdqmzeui.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2nywypssx.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2kcpaddkl.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2yqgtbufm.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2elyhvhyj.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2nkgmnpin.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2cziecjfl.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2hdsdekdg.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2ivxnvqbd.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2szzoeliz.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2unytaiim.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2vetyggkg.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2mlpsgabk.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2aiyeocpg.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2fjtjztxf.html


<!-- 参考信息 -->