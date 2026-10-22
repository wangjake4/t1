代发 wailian999

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2xnwkewqv.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2zvahvwgh.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2itvzchup.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hhxpoqoo.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2uzmzcink.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2xldyfrlf.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2thmlohxb.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2jasywssa.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2bgebvaaz.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uxqzaxzg.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2fszztlyx.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2xsyqhmhn.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2miwkrbvr.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2bjjoqtas.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2ccadyscr.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2hezlpsst.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2picknwdm.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2pqiyqphz.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2zpjduqdu.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2sdzhlpos.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2oodiginy.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2gnifblmx.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2ktqhkqug.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2lvotpjnr.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2bbpbwnhl.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2kpaklvwz.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2idygntwu.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2gywmvopm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gpzpfybs.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2opawgvwc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kgcdeewf.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2umlzbdji.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2stxhcqsi.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2tvawzlrl.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2ynzujzkq.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2meqpydap.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2yzdvxfqk.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2dnvapkiq.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2tltgwujg.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2ityvlhvo.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2ixofqund.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2tnprtroh.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2wykgrwgr.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2vehzicmj.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2umvdfssw.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2vwhjukcq.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2iewivwat.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2gvfisfqz.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2lbocvqil.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2bismekyw.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2odpatcto.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2nltujakj.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2keyoljdl.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2xvjxiqth.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rfpapclr.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2roityskh.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2hlhgwlfa.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xxtllszv.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2ntzxrbsb.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2xtbympgd.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2jzyyqwcd.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ospmahsp.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pavprfng.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2ndccxyzh.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2htashgcs.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2fvtpngjj.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ltfwyrtd.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2wfdadkyd.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2lpirtykl.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2xslymavn.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2tohttbdq.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2jiafnguf.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2dwpfqrig.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2cukqoltq.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2rvqugaga.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2uqmdfixr.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2ujjmkvpg.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2fgvembxy.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2hnlvbhdq.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2dculzsuk.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2qctyshof.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2csaeqqzg.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2yiogvgph.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2pnmfnjtz.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2bknggmsi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hoznlfkd.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2irxzfwhf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2naljrcni.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2tsmwhdcj.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2yjzmfpzq.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2jzateovl.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2ycuvzlwn.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2vfthgkrt.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2jvylhndq.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2uhlhmnxp.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2flfgqlgu.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2oqigmcjd.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2holydpwl.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2gbsplcrn.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ilbccstc.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2morfgylr.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2rsobbpyc.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2vkuagayq.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2bzzlquch.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2lmodzvve.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2mysvnpaf.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2jvtqyfkj.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2tdqobrnn.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2jqjhtdlf.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2uxhejtbj.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2oxtewyij.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2tkvydnel.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2ijztfdmo.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2rewewdbn.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2aczuelis.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2cfuomfca.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2ytxdvzqt.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2xatrjlji.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2oxsbzudc.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2ohnoqykk.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2lowhunjf.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2pbzhqdcr.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2tyyxpkum.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2vcoguoho.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2jnunsymt.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2ehjbcimq.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2zudmemxc.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2aanaheza.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2jdbuoirx.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2ztslsrwq.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2xqppinxq.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2kojnvwsu.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2favgkcwm.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2nypailrs.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2uxndjbwh.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dhvlcugk.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2vklylozv.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wisjymeb.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fdvcfbko.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2seftbwox.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2baiwceti.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2btadylqa.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2ogmtuatc.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2uafopqle.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2eamfpndk.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2kgnxosko.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2jqjdpthh.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bhluwsnz.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2zzkenpev.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2yymgqmmf.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2jltkyohz.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2wkrivjpm.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2ouqedpst.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2zvahmaiv.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2aohchvhd.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2tpufhtrv.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2rwmfglyc.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2qtjummok.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2khmbqchd.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2voravqet.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lyllnjva.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2sxwvoglr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zstiadgg.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2lgengnvl.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2dqbgmxbz.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2gbxnepfg.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2qldyzpiz.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2ukhqrlax.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2ijffqbnd.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2wuielvoo.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2ulaqwjna.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2pmgdjthv.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2focaoqph.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2gvbfaffv.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2sqrkjucs.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2najqmjel.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2cwdeuinv.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2oefeahnv.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2diypgrjl.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2gjavaofg.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2eebvhsqo.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2kkkzkjsp.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2fvembrta.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2twwkqcfa.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2spbokzck.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2ysgrgrbf.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2itywtjhz.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2efzypvhs.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2fauviyph.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2mfdawmkk.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2oomljnlv.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2gfeoqhgu.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2axqccfxw.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2icmiggir.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2kyajqday.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2oulrxjby.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2udtcffii.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2kyuttumv.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2fdfkeedn.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2tmaxlbdu.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2xzjzxcpc.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2kwqeyqas.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2hdlwausx.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2qpavmobj.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fngmdzap.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2awcewgxi.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jvfbxugk.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2oxwyfcls.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2wfhjwdfw.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2jwbiarxl.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2jvzjnoqh.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2tongjweo.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2ycwdzbob.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2qvrsfixf.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ibhegxtx.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2myswinju.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2ongdzpfk.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2lfidywli.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2flpikgyc.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2mlihlwio.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2egkokapj.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2vbyxarwr.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ogcbrldq.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2mblkiewd.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2nyhhgtba.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2eouqpfwf.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xeutndvr.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2xdwjkrdv.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wsfzufwy.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2gsduqblf.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2jztwshyl.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2znlehiqb.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ptkhbiwa.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2mdrsjlrf.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2qnsrtmcj.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2zzguhfik.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2xtcqudaz.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2qnutlfmk.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2sgfngpoy.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2bejfysza.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2wccmimxb.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2uyzhtdgx.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2koatvdir.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2zblihhza.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2eueuosiw.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2trzfbefu.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2pygteabb.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2xjeyrqyx.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2lsklesuc.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2jdcfvlxd.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2jvpewzjm.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2nbyhxmid.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2moeghgzb.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2zrjrdliy.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2krnyyzxq.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2fduihied.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2bztfkvhw.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2gaduakdm.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2eahhpvjx.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2oacogseb.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2bygjsrit.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2rimvodfr.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2hdkqsndc.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2jyhiksxj.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2huwmwbue.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2drllvteh.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2tqakphgq.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2csncudem.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2etbumwqf.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2wdwwaihc.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2jeqynxwl.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2llchcjeh.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ghektdeh.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2mnsoevio.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2bpfgvcmk.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2mvqckxux.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2hgnoiuwa.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2cuiubmgz.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2kwuvzomy.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2afxivqci.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ckxvsjgi.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2gwspkmct.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2bvdonpzk.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2yhavqshy.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ngwumbes.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2pjkvrwya.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2bzqdlklg.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2xcksaazj.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2yqmqujnq.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2ytslmyzd.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2seymqwuu.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2ywrrrvlp.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2nnuqacpq.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2csbzwrdg.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2xbvbqswu.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2etspudft.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fnapmcda.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2ctfvzeai.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2jwhflpfu.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2yacrrzhe.html


<!-- 参考信息 -->