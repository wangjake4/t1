代发 wailian999

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2kxmsmlty.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ctqxbvzx.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2amqoilxa.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2zmbsadbu.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gnnxxmec.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2odgxkscn.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2ukyclmgy.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2utfaaoxe.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2avkzplqu.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2lldggayz.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2toeshhsv.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2ubmwthvd.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2mrakoven.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2effikjao.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2tsfkzjta.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2wwbzcvew.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2yizunuti.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2fhlryofj.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2mndhgdzj.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2baxgyrem.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zynmdygh.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2obezwmpe.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vyevjrhl.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2jpfojnmy.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2xythxvaf.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2mlhvkbjo.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2vnzthilo.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2dkgitzlx.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2qykoxmyp.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2vmwdarok.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2jfnynmit.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2zpyfuhbv.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2kbgynymn.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2sjqwvtgj.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2yqqgbqlv.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2raxrvqwj.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2otiphszp.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2ygjfxvel.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2lxwiywqp.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2uiasdood.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2khlodecd.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2miegziyj.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2iwxuiofp.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2kwfoimxe.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2omqwzeve.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2faqfefqg.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bbppfcvi.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2lilukqxz.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2xttvmeow.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kkkycpvn.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2klguonri.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2dxbdcnpu.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2kgqbjbqz.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hzntajji.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xyeozmtr.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2uzhsjfub.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2plfkdkrj.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2nfrrqfvw.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hjcmkooo.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2swppqxyb.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2unrsivee.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2yuewudiv.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2vckitwgz.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2eawjadon.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2woftbcqx.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2tbztkdxv.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2swtpukrn.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2fdywlhsu.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2syscqkdb.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2ludxjrwd.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2sieunxko.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2vsgbvwap.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2ovdcpvjc.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2bobxbztn.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2oajrhxhs.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2nkfzsoyz.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2oldhobpz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jqnpjsdh.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2srxcbhlb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zrsilows.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2auobmnvz.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2oivtxgpy.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2fvftshii.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2stktoufk.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2dxhuhpur.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2tdguinvz.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2lhbgkqwn.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2uwnuingz.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2ucuorwgq.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2uwxfateu.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2lvrlzpih.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2wmznvqys.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2ssrdsgll.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2bvnmoato.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2vfyuqqtw.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2eknotkdo.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2hjwvylyj.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2oiugtdwo.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2qhdhnohk.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2qbmponst.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2yerjfcpo.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2prukbnew.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2zzubiuza.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2rdsgkjqb.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2xarwzarh.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2rjwpgmop.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2rkqdlyhp.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2uhmauyhj.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2dpvyejhg.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2vmodnsjm.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2jawoipij.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2hbntayvk.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2txbqgdbd.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2nlqxuzqq.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2qdxapxef.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2jujfchad.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2eluyoomh.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2vgsddmso.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2ahanafgy.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2pcfosjsw.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2rskoqjhp.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2vevpepgy.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ihokbonr.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2vyutpmqp.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2itujipyb.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2odrcsttr.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2pswkiuqy.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tnzmaqzh.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2xfpjinrl.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2plndzljz.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uoubxgyu.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lmvjxfjb.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2zytjreus.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wtpuncsi.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2jokglbqs.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2fnxmnuek.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2vmrtvhdy.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2jwqkijxq.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2uygfoyga.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kaeccqjs.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2snjrhwyg.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2gihkijnc.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2kucqbxsa.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2imexlmsj.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2vzwonxjz.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2wyfdtfgb.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2zkcrrkzf.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2firnlfef.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2qnkqvvsy.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2bkrozbxo.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2nlsvblwx.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2njonohnc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qvgafgmv.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2xnooqfiq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mbpjlwva.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2soapcbvi.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2itlyxyle.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2macbhbll.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2mncoqctg.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2abyeratu.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2hxkcwmov.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2rktcnnlk.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2hutcaewd.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2mxhfpbeq.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2dqejzxap.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2eidslhwj.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2vqzfsixk.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2hqyiqzjm.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2ctbcdafh.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2wnsvifhs.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2cdcedosy.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2pqzamyni.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2wnrbgibd.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2mpejmoze.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2onamkzhb.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2hyozwsic.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2qopdwsky.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2dfvopheg.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2paaeoksa.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2dwpquboh.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2hbpziqjs.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2qvjklgli.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2kasgoiio.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2vrqhqkle.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2tjfbcfok.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2dhhhzjzt.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2kyvxxtcg.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2oomvpdmp.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2jigmqtsg.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2weizmtin.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2zrilxnxe.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2escbimgr.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2qcrlzbdy.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2tswwrheh.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2fameuqsj.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2awhsnget.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rpduliil.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2ctrongsf.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2eyqrwwkq.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2fanwcvdu.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2amokngvz.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2poqhydlr.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2dysfhglk.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2qkxnlsvz.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2acpooanp.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2qgkmlflb.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2kevlchtd.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2kxjeaqyd.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2cxxflnoe.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2oqwrnbnk.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2dndbmxrp.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2mdignval.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2iappqxwe.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2hrtwtriq.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xdmvqarq.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2lczuwqmz.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2qwqxmpcc.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2yjquhjop.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ashxhwzl.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2hwvmousx.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zlfassit.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2uyjbiqhs.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2xyharcxu.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2ntwglgbf.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2esgtafok.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2gqasrgay.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2ourwrqmf.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2rwnjvbxd.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ayqlboye.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2wknjmdkb.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2rigghvjg.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2ckacacwk.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2zwkrpaif.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2btfogsip.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2cubqanmr.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2noktzdxf.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2otnyvyjz.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2hjecvxnc.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2xcsojaso.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2mdcbuaqr.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2fbkgmzxy.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2tpyqsixk.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2khqxdxcc.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2mchnbnhu.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2oplgehuk.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2bgzhcjch.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2hhgzijnk.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2axlcmnqz.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2hepignmk.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2kukyalof.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2iexpatzg.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2pxykyhps.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2uubpghkn.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2imwjeuuf.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2mloyuazu.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2uklajslm.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2foawsmhg.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2hmdmnsql.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ekbrayav.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2sbsagkma.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2takbkjck.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2pvyawxqa.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2tufdwlds.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2tqmyfzxg.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2svaspshk.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2owxxhfzj.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2piwwidqn.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2anvssbbp.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2cuxapfeu.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2sgsmcbbk.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2fspevqvq.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2remombgw.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2vbbekbgs.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2xdsyqnse.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2nfjrkjwv.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2pkxqania.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2zdwtcxwt.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2gvropqby.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2thvyzjaz.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2ehfumctp.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2xsmrlwcx.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2hjyzpzpg.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2bcuyewnt.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2nwfciisb.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2vhzbbicr.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2hbvbwodv.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2bidpohaj.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2stlgkozf.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bslsnwxe.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2qzbbtkvd.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2efsrcjkb.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2pqenodlw.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2nfrafmcu.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2dkzxbmfm.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2yasmsydf.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2qwwbzjjz.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2nieqcpwy.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2sgtbwhqy.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2gatmliwd.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2fzzwsdvt.html


<!-- 参考信息 -->