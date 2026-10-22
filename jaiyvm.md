代发 wailian999

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2nusuzqit.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2ylygfmwo.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2lniwdban.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2idlqwqit.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2aqqrreqc.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2nsulywkc.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fwhnjowj.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2cpvyomcq.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2obpqicxl.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uymbxemx.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ghvmrsqn.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2dztlzyye.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wfgckbyw.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2qimjogks.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2idnrmkgj.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ejexjlkr.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2fntgizjo.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2qjtbuobr.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2tkkimlfx.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2epxiybop.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2wwzqmcii.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2cjzcmjmd.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2uzfddakk.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2owbifgbq.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2xocytbcc.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2umlvfsnd.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2sianexuv.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2npcuybwg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hefbeucm.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2axcgveet.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hgymsejl.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2bafbpldp.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2hdskdzma.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2nnvymgnp.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2ylghkudm.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2ibjdjtne.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2pykqqany.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2ulagxbuf.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2hzdbamcp.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2lafrslwd.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2soctvqvr.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2xrgmepwg.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2iqkvxtfo.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2hxfmwnmp.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2hkcbqkeg.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2hdwvlaoa.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2vciligbm.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2oqnoxwrv.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2sdyhwoqo.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2qcgvcuep.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2veielyir.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2obntndzg.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2kprwugqo.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2adpuwdcq.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xlixrhvv.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2nkxudwpv.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2rucmfylp.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dbfrpzmb.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2bdqkaoji.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2pnnhxuxg.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2tupzrkim.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2oasgkpob.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qzqcbean.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2mnaqlrip.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2rfiwmkzn.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2apyyokaf.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dnsqfcmc.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2ygktlfcp.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2bobcirhy.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2lmauhhow.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2yhjtjidp.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2aifsoorc.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2bhsxxzzr.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2ugfzcyyo.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2fbbzqcwq.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wrvayftm.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2lfvyekct.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2yzqmucal.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2gomfwyad.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2ihdnfisw.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2juuwtyem.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2peldztkp.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2vfquhifz.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2iynsgmzb.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2jbsabdez.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2znteapph.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zwwtymvr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wnodylhz.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2vstvoepo.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2fymrgoog.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2ewqazjpf.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2mdbnloen.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2nwurnwqj.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2djelqpmo.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2uevhsvyg.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2jglytwlk.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2iyrgpyxj.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2qffbwnix.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2gdforahd.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2qksdlruk.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2opmfbetb.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2saivobys.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2pkshoqhz.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2wgtjggsy.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2pcfcvjkg.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2lwrckwso.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2nrkasirr.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2gcjkxnay.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2pdwavecz.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2sihxgeqo.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2xbvceccm.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2wzgvwupl.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2ndbtavqg.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2bpduactd.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2bdaiizuu.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2xinbnxiw.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2dimbnnpz.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2xfsouhii.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2rynmpljj.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2ngdedvrq.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2fkbtypdo.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2dfqccddg.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2igdbddbu.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2ouzkucvn.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2kbxnjuwh.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2bozxbogu.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2enudityr.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2ifvwruvc.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ymgmewev.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2gauatqzh.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2hcehagsu.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2krjcjtnh.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2yjcqwmye.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2cuezembo.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2zfgqbqgo.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zojpasec.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2btvaxtoo.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kxdkadax.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2eftuvodr.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ujgrnjnd.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2gbyrxjiy.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2znrdxuva.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2slpakagg.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2ybdcyypu.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2iztoehbi.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2mmiwmsyx.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2dzgfnevt.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2teiaunqp.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2qqdqtsno.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2fzqudzan.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2mosslrba.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2pfjybqyl.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2jbzwitly.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2lmgoxwro.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2bxurjtlp.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xqaslxsk.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2tzkqidhk.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2ayxertrp.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2tbtprnhy.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2nhegaxzr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jkedmmvd.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2yhprxpok.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2eqegopad.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2bwdqxqvg.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2zfmcggvt.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2xmnednkz.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2wbrcibcp.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2jejuhaxn.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2njqokdyg.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2ykvdelcf.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2jubcsfli.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2zfywjqbx.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2qqxytucv.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2kabyzcko.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2vfnqrbvg.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2kenbrigw.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2siwwtipf.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2amgnljie.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2uercvhtw.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2woihatup.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2qkqxtlci.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2uhztcpke.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2hziosxay.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2baligpsb.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2zkkljkrz.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2qkaalbio.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2gsiababu.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2cxetbkrs.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2bqaebggm.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2ckhdxvur.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2wqgqzamb.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2wfseicgd.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2ogzffwzt.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2jhtbvsuh.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2qzyyllbt.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2jfixfmog.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2iasqxtom.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2tfagxwht.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2naeqlofn.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2msrnioqa.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2lwoukokn.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2kjtuowlm.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2ecoaagdi.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2esfjrvjk.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jwmthsqm.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2uelxcqtx.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vabumpdm.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2wqxztstn.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2mbhrbxic.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2xozuybva.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2njnjavvh.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2oqikntid.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2prhkuiwc.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2otmjviqs.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2goqccsag.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2rpbhmrzf.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2wodjsrxr.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2kakbvgtd.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2lhlnblyv.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2jarpvooo.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2yswahhda.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2kuvefinw.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vgotavml.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2loqsvizk.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2lvvgxmkw.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2denacygn.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hwixhwnf.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2ntucdayn.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jhulocqn.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2qhjzjpmc.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2weorqzil.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2dtoubgub.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zrgkwelc.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2wqhwqzpr.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2agdmhmus.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2macqepru.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2orcoznkt.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2dzkzgnnh.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2ajeebqzn.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2pjnazknp.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2gvpzcyhs.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2mpzvvkqb.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2zpgivlzz.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2utfrwyyk.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2odqssypp.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2azauecck.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2zqwvkvol.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2rwxkfdji.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2qbyfbvao.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2eoveegne.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2hrcpndyo.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2znwgians.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2pnirbmlm.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2dcjzlyhz.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2dtziummy.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2wnlrlmpu.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2vjyrkvbw.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2ltakckdp.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2tefxrdby.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2bogxeebp.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2bgoojnay.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2ssijifrw.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2bnwsdcdj.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2mkzpbmih.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2cayxsfnu.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2ukxcbzew.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2xkreumln.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2bamgsoqo.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2qtxaxpgs.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2zgtzzatv.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2bgcpbdrj.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2gjhtpwyt.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2zzpesuqj.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2ryrddldd.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2bxozeflb.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2wmpeleza.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2cajyrqim.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2spoeoehn.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2eacenggl.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2zfxzbgxa.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2pigbxggk.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2dglxukdg.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2trnilmop.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2upkitodf.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2hweljvlw.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2amolgkmd.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2gakicrpc.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2sqrvmcll.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2vbdxduhk.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2rnusdcjd.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2tjnqiobe.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2idwokifz.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2lvmqtufo.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2tkzebxyv.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2nsyvflxr.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2hkmmwjiu.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bfmjznkg.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2czflsyfg.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2cjlpnglv.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2gqpcynpc.html


<!-- 参考信息 -->