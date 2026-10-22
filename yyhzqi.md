代发 wailian999

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2asnfxlet.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2lolhtnah.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uyzrywkv.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2zjsejgkp.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2tqcewukz.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aaalndwa.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2fawzhcaq.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2wtjanfvj.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vblgohmm.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2uvreoqhi.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2jxeezrlg.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2fzupteuz.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2sdmpgero.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2ggzktewp.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2crkpenwk.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2pxdvpyey.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2hupgnrua.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2eeknaacv.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2zyypjjus.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2ntwuqxnd.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2gztagcih.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2dtipqnxt.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2pieecvce.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2jdnktgvh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2oktcwhax.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2urepaokl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tbgajghq.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2zxhvlxpo.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2cdecfxqz.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2feusxfhl.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2audybkbu.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2xlecxsdh.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2kmfessaq.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2ljjmuquv.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2ntclufpc.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2crhddbha.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2nbrjmylq.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2skdwnlia.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2grypmriu.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2dgdwoubm.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2ztkcykpx.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2hruswmvk.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2fnljqqjf.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2iimyygid.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2uqzarvqo.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2yseklxwe.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2skmlxbkh.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2wcdzexei.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2myxkwzha.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2yauuykqm.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rwsjduqh.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2mmszgyrk.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2zkvwfgtx.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nqmdbyzy.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2ypcancgs.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2aaaweyky.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2ijqfzftg.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hfyctqkl.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2whrmdude.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2goagtvhf.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2xfjytdcv.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2bujhtvdl.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mxhhlcci.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2oukmhyjg.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2vxvhhioc.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2vmxeipcs.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2fivzvaro.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2yeqfjodc.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2zxhrexxi.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2xfshoawg.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2dukxhoyt.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2oiywxoxi.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2knzexsjt.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2gmriuzdl.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2dnpdzoly.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2unonmpne.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2rslcckxl.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2ggszjvlk.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2wpsfnevw.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2vhilyiaf.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2icqodgsy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xbvqlqdr.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hqgcxqsq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hstkyrkp.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2ktrkbexu.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2pedqhoyh.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2tdiunfnk.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2ioehkiey.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2kufefuwa.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2dgxvholg.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2lvowefjk.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2ptteswvw.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2pgkhzftu.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2cjubbtdu.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2sdgqlskg.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2xuuarwnx.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2xvhfnths.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2ligcuqjg.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2hpgwiutd.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2uatanyvo.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ruknunbt.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2glucbriz.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ztvogtkw.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2eltprmpt.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2cbxfzfpd.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2ijnrtyfb.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2iwobsrie.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2enlyhoyg.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2mbqvpdhu.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2dpebcnii.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2zzhssdht.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ghxlpbdg.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2rokeuzdw.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2rkuwasrr.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2nwoxykre.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2gnahshgf.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2eymiuzkd.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2pekjapjg.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2innaiuyv.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2wnzcnish.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2khoiewda.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2anqzkomi.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2ozvyxyif.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2htqwoukl.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ozluqlev.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2ksmfjnqv.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2oguwlerk.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2yhzafteg.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2soonmsvz.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2hxurdnzi.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2deqcjces.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xwtajcbh.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2iekjbxtj.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bkaimubd.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2heojbjpf.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xobmrcmn.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2vvczyyzu.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2berrczpv.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2rlkmiwiy.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2gqqhtstg.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2lniazsxu.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2tytdiizu.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2fsekuunu.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rwlonpuq.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2onccmznr.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2zvsntbbl.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2hqczgmms.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2cfwsmwso.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2xdxjlyau.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2dhzscszu.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2vcacvxql.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2jvkgrxyv.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2cwlukjfl.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2obzxuryx.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2istkfovr.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2xcfzssbh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zadklrpt.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2baejrzuq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ldpnadhg.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2gaeshtma.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2gausbzsa.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2jufutktz.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2pgnbagip.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2authrdwq.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2zoqnxgox.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2rjmyqdkm.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2oscnwoiw.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2aycsyxys.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2msulovyr.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2smjlvmau.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2wkvwmoor.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2dxtvfbir.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2drifucat.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2ivxxfmmw.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2nobyhoad.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ghvufalm.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2gqxrumzz.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2btrgmetm.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2efqvcric.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2lrfmmdia.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2paipwzpd.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2bgnzqvgv.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2uwiuekvm.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2yzdxpfdi.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2gvhhkppj.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2nastefuh.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2zlyhkvrc.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2ewpsijgc.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2iipjpbyj.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2gvrjowbb.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2kgdojxpu.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2koioozzs.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2ogrfrnwf.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2swkiemai.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2lodmcues.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2nofpquiw.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2bpcjgjae.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2rxvjajal.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2zurpgakz.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2fyzxkjcx.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fpdodaro.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2wddrthwa.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zplxbogv.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2hjnugoii.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ymmpituy.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2vvtmowul.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2dbkfrhdi.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2yxoqqkhb.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2hvwwgoon.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2snrglfap.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2egnfbjsk.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2mxiutfgs.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2rhxjwlqg.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2uihqlnjo.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2iuedqaqp.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2rlsimcgz.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2hmqsjvhd.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2xzpvxtvx.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nbtdkntu.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2bqpfxlcl.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2enanxzrr.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2vlmsfrny.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wojkotna.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2jyacwqzg.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ulxpbdgp.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2mzgpliyl.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2tzzvtgje.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2rgeuvysq.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2yrrtyyck.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2zsohzbxd.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2bloxlzrm.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2rtjbapsj.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2nizwhajd.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2qntmlkkn.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2dcsiplsf.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2lptfwaqe.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2wxvuvtcb.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2ffvyjpat.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2yzoymbwt.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2izmfnyyn.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2bbblsxxb.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ywvfgoap.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2xbtjelee.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2soahhlbu.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2hcdnkrvc.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2yjpucdzy.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2svvqbsqh.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2vuwtxtdi.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2xlevdpow.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2fpldvlvn.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2bmwtdpvt.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2hrkfbblc.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2mhcwaxny.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2jnpvrxdz.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2wrfjuyjj.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2pojsqila.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2csabvllh.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2iypdmezx.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2wqyktrdx.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2croujioq.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2dnhhabjo.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2ewlwwgqk.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2wnwrjxil.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2fffribxb.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2yzwihruq.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2shjttqmb.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2gfighkry.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2nnyizdnq.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2hxgtnkhw.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2orckfzsr.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ehroxfyi.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2cpxndtct.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2rkdtltak.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2tdltwkti.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2npxgvtzb.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2axelyavk.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2yusbuivl.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2tpruavqs.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2zfneviww.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2lumllxuu.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2nbsjyohe.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2jeulargg.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2qxipwjci.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2usyaefit.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2wrdvisdu.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2cuikolfi.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2fkjluxyn.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2vmxolyfp.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2lgmyvaei.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2hkykbxxt.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2wyxeufcd.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2iriwqgoa.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2duvtoyqc.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2tqdmuqzs.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2mhytsjln.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2ayvdhkii.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2vbsoviqe.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2mnyktdoj.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2tzfyddmr.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2nlhejvve.html


<!-- 参考信息 -->