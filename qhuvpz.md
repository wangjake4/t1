代发 wailian999

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2sycxegzz.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2vmbdvyys.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2eggnigxi.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2hbjmhidm.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2fillpqrj.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2zumwxtgz.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2gcbsqrnx.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jhichtux.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ikailxlk.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2ycrxbltq.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yeysnomi.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2psdnxcug.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2byjfdyhq.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pqtyfuwl.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2vrntxits.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2bczyplwt.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jbudxilh.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2oscqhawo.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2ggkwsuol.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ecmlvqno.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2xfrzcwqt.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2ruwjjdpv.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2gcgabcjf.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2bmukpyoi.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2mwsebvkg.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2hfrayevb.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2zgjlzbtm.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2ujfpcjgh.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2xqecmpli.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2tbjutsdf.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2uwwpjdfi.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2nuutzdxt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nzbteivz.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2rsmkdrvu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ajivclap.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2eazcympf.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2zbrpnlrk.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2yaadnnme.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2vhlaxqsd.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2mdiahbda.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2lvglvnqv.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2onoivlqo.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2kuioxtfw.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2zkotaxua.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2ehxohhxa.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2hbywykzg.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2rgynhuqo.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2rlguengz.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2zghojfsf.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2trjsirla.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2xarjevvi.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2qgpenygm.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2sweumuoo.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2xcbccglo.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2anggxgye.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2isvnwbok.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2vwfanvbw.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2qbfbvqin.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gulmqccs.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2tehqolqm.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ooxppjpz.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zkqoyfbc.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2xeqmmrhg.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2oaxdrcab.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2vijmrdoh.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ubhmtbyp.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2alqzhijs.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2ezyocnzf.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2mkvvmxat.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2anzolbzy.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2movcmlbq.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2myanhqvt.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2qsybvusy.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2iuxrkcpo.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2fuhpyamy.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2guxbabub.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2fahqcfgd.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2umkfxnrv.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2okfexeyv.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2kxyupoam.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2nczcovrk.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2ruxmdbsd.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2sfzgscqy.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2jjwyqviv.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2mrdzmeea.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2tgzmucus.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2dxzqmrlc.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2aotcgoog.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2vmdfkzww.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2flxoirkg.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2uwvzycln.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dfoefaur.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2ptpmthzu.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2ptgxjzaj.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2lkpasnsx.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2velvvfgm.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2oledruxq.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2awmzobsv.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2xbqtrlev.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2yvedcnbe.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2vcyaxlee.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2ubgtvqsv.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2jxeihisz.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2rmflsucf.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2snkdhwng.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2oqmezjhp.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2cxooxknh.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2iysqzphl.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2mnbgtgbf.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2dmqltfkw.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2armrpkrx.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2zkjgtafy.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2nbrgmyct.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2djybcosm.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2xbyyajpa.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2zligiapg.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2isvbtdug.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2xvtsorgi.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2vxcwgvpo.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2qiiuovtl.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2cgictvsg.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2ngdgkunr.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2rrrojzuz.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2hainsatk.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2vyfapris.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2cjvzmixe.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2jwwfpllo.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2soynhdrm.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2qhmeorfr.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2kyyrfssx.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2krmoqiqa.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2vvsrjngc.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2rrquneks.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2vefhbqnz.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2zpqykdzk.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2jeyvnihb.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2ifghvqvo.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2jysuoqfg.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2tahyabce.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jlxoyfuc.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2flpscvje.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ehbxoggt.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xvsxdcuk.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dxtbgsau.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2drjljamu.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gmmwwvsx.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2fqnlxetn.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2xgznlver.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2pfmvcbkj.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2nulkzkjb.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2lfhmwhvq.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dfzcybkm.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2udcufusk.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2yshstjtl.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2mgfoxocp.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2qtlebbjf.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2vnmtmkhd.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2gqtnvcxb.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2hopdttre.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2rdelorlw.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2moweynnt.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2mvviuraa.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2mhpozmnf.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2eollviqh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cqcrkjza.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2molevrtv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2htfkvowh.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2wjftddte.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2keovpdmo.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2pkywhuei.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2rwnwrfis.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2qeuyumyt.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2jizvqnyu.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2qjkkheei.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2ogxgxlei.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2mwczanzg.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2uigbhxmz.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2iarksvma.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2zfvrfwqx.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2yhmvyfau.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2zitrtpah.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2ciwbvbpr.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2idkxwyso.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xqahsqws.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2lfyyzviy.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2zwvgbzfs.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2reljokqc.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2tpgbfdhs.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2zszsszlv.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2fpojprcx.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2xqkxrjva.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2etsklbmz.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2cwmrmwgb.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2jbgrpkbt.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2yuqlwfrh.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2yawyxlph.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2jeypvhek.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2xxfpqumr.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2ipyrtiaw.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2dunifrby.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2tycoqguc.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2yxzwlsvi.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2ryoruwbk.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2qqhkkjic.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2bypuidzf.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2euxrsidi.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2sxfdbtqi.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2familozp.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rqurnzcz.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2iqwhmdfp.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qteajgis.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2xoqtmlpw.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2zporkvnk.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ztitdfeq.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2udrcpwrn.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2sygyztim.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2pydcnpwg.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2mktbdafp.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2tbtllmwc.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2kzykdsat.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2bspfshey.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2hqdhyiox.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2vqcvboov.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2tycirtcn.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2ivqychcg.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2zbufvamn.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mcbmkjne.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2bzqxrsjj.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2sephzimf.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2rjcmdifc.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pgyyeogi.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2jovwnhbi.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2eobaxpkt.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2dzottqds.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2kbeqzdmp.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2dzigkpal.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hdvsdvtm.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2tbphrtwj.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2uclbzvbr.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2gbjmahsm.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2uaoodsaa.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2xkpdcwkn.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2kuccpmkc.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2oweyjcer.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2sjquynyc.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2aojzksdb.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2sgngiuxc.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2lgprhwic.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2rwbhnqtr.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2tdzahsnq.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ynkpeotd.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2gsljxfpb.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2xfdnammm.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2rrobtulp.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2affmyjrh.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2fvfsruvw.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2xvisojtl.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2hashqdox.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2hrbdwxka.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2vdqwfobn.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ehyqitwq.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2azaqjsqu.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2oewoadiy.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2htofnayt.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2qxfirhwz.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2pdzihrtr.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2jteivoee.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2piyrupoi.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2alfctblo.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2qyntrran.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2jmgqixxa.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2ouykftpv.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2qdzwrwrl.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2bxqedqan.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2gjvtchql.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2vtpmdivg.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2rtbliiev.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2tmugxwzb.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2zebxzqgy.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2kpqleabj.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2jtxdmbda.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2lzzagahg.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2jfaoznyp.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2twsslxgz.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2vpwlfbey.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2qxicoxkt.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2mvymjuzb.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2igvhfyly.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2braocqrt.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2xyrqldax.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2prmjfqbn.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2ozsrvjpa.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2nueyfxpg.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2iodwxijo.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2xgakzhol.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2havyygfu.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2kxrhcncm.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2qzvvtoug.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2uyxzgwzv.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2wyqjotpi.html


<!-- 参考信息 -->