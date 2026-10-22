代发 wailian999

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2bqmsyqwn.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2ntsyrfox.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jfoqazfe.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2mwzrkpnx.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2dumnvuej.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2elrilviz.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2vskvqcan.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2huxawvhu.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2sxyiqafx.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2yjfcmyxp.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2bnarifre.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2llggcdyh.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2mwgkrjvu.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2crspyrto.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2venivrwz.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2yyytsrhx.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2oxubthda.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2ogcngter.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2plufahvr.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2cuzqxyhc.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2sfizoiqe.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2dekaogbc.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2nddzzqbt.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2bzefrucs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tunztvbk.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2jcchaoaq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2giirkidp.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2ooiopmub.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2guhzdgsi.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ylbbhfcc.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2enkuszbu.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2uvsfafbx.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2mcegilvz.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2dizwvmaa.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2jvuenrqq.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2smjocshc.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2oxdjmjjb.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2uaquojog.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2mozuennx.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2gbtjclpf.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2dbnfejdl.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2cwxvnewg.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2bcimmrat.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2byunfije.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2uzrmazrc.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2wywpukww.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2iiyhfzde.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2rtiucwvm.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2fajoaxpy.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2sgtixlnu.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ncexbxvx.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2vvkjzbbk.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2jpuptdio.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oblwaudt.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2gwuguwzi.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2xpfvssve.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2zcccalmn.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nrltvgmo.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2drimmzdj.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2pjuprbag.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2syorsrjh.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2dgbucgay.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ftvfanot.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2rxffiwbv.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2djftwuvr.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2rquhczul.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2ispfcbvm.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2ezzrhntj.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2mfpneqik.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2wdsernae.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2uvgnafgo.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2bryulkhm.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2vdlbiljt.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2fcmapndi.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2wuxbryoj.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2ybwqneog.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2kwuwiwnu.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2znmhrhue.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2lvdmovrr.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2lzucjyjw.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2qluvxwpm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jqknfhfm.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2znttmjtl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yonovdlk.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2ixfliakz.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2wxfwjazw.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2ikacvqzj.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2fktqbsjz.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2dyqstpup.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2ozfycord.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2qgssyfdq.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2jqzjapis.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2tsustvhl.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2iddsnmhz.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2mcuerwuw.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2zcfocknn.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2uzgkqawy.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2ebxopsgl.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2mmbmkhcc.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2dlodpnhh.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2aiygwsvf.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2cdvdgtda.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2htztdrsa.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2btzwalsh.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2ojjddwdd.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2zkskuyws.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2aimhazmg.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2nnjrwaqe.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2ffrplqxj.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2oitqvhbq.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2jydlbwef.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2opbybhdv.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2lynsochg.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2qpvrftxc.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2hobmdlhq.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2cwdcfzzd.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2veuievsy.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2wxahnzyu.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2ninztupg.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2nmfzdrby.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2nhboioai.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2kzqwyifu.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2zmuarprt.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2tproslxv.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2aznpndth.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2jtcucxvg.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2pkkkjmxo.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2hycbfief.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2ibfhgljt.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2bqxxlpvp.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2maeuvumb.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2aljtlwpc.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2nsrwecon.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xjpqzbfd.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2twfnoawy.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ltzusrbz.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2pkvmmvdh.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xyipwepr.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2jlxqqgwo.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2bdqvfnbn.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2zjuqramc.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2raxwlajk.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ppgsitgw.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kzlmspki.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2cinworpr.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2xaranhnb.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2slbbisge.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2bqadijut.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2rwpizdry.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2gwzwkdtz.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2onzngwbe.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2txxlbhsy.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2vhnncjmh.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2wtmmgjki.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2miklefwa.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2cshaefpv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2houbsnha.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2fmoxspid.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2octqvebk.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2ewbtwnui.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2meykejns.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2kymehxmu.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2leqzwknz.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2ibdtkqfe.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2ugpdttzo.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2baoixriu.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2dgsibssu.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2jfriavrl.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2ddigjgej.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2hmnfvsun.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2ywlkkimu.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2frhqqhat.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2xjibqcgg.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2uewqkkxg.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2nxnhuxyj.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2wukkulye.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2ynuecjsj.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2mjcymdtx.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2zdgweyua.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2qjiendnr.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2lpivgwki.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2htatjxxu.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2psqnrwge.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2ruplsywz.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2zebwbwlv.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2tkypsjjv.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2vrtlpbsr.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2mhmpzemh.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2xafxvzup.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2oxxuesft.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2jojpkzin.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2sbswprtd.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2uitlkibe.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2lftxqdzq.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2kwktozzi.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2yqtmtwtf.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2tnusoums.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2ihvxuhnj.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2onjvghtq.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2iqbmjedi.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zlujbvra.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2xtapbdfk.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2oqvbovwq.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2iyptydaz.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2megxqwry.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2wzqvjxjn.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2nogkagvp.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2wushofpr.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2aesfxzia.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2laucpxmz.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2nppywzbp.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2oqmjcrwt.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2erbvqxpx.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ebpnokwi.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2lmxmooli.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2qyajlxni.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2bltmjmyc.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2ukkaqitn.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fsdrxlhj.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2erloonof.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2pjvfslkv.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2jlnvnkow.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kgavxrck.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2pqvtdjbs.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2sbvrkuiy.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2toetsjqg.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2kvbqissm.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2yxhymbrc.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2awetlmvu.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2mfzbnrgk.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2wztrknrj.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ifbhclon.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2hgtzcvos.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2fjgggbdh.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2vdywqwwj.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2zxmgyfdz.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2wlbgzqoh.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2qzcywbpu.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2jjyejqwf.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2wbjtpnrg.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2erzftfwd.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2rtcbkiam.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2pawsldqt.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2veswuxnk.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2zlpwtkdm.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2nzgmhtyu.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2omaevqma.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2dsugfhcg.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2csmcstze.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2mqfvwmvq.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2onwawtsl.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2sqslzzcw.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2qcfabhxm.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2wqupvypw.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2ebipbgkv.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2hexvdldz.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2xndbzpim.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2kwmyzqbb.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2jooaqihn.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2tftauhax.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2msgunzbz.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2ckchrvmb.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2nxyyupwt.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2jhgnztog.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2wpscyzli.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2rjeqqbqp.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2zhvezdox.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2hkfnhhmp.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2hrggwgix.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2obntcpwl.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2kujgznup.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2jondmloz.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ldmekoqq.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2hzwdbxgq.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2nrsrdlqo.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2hxztmcvs.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2odkajaff.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2ypxyyzkv.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2gmgyiuzu.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2hrymiejx.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2teowzjkw.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2icgvmpjf.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2sxeqrowr.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2isoexcht.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2blmipjeh.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2gjaowbsw.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2gjnzvqao.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2criofefl.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2alwkuwff.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2qotmmbwp.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2ftgcepxy.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2pckfzift.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ucnvscev.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2vbotadry.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2cqrtghzr.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2erknhyrk.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2afvgwbfv.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2rzkctbzh.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2suzkafnr.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2paieebre.html


<!-- 参考信息 -->