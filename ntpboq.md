代发 wailian999

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2eylzcnng.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2jigvfgnl.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2vfhjjjqq.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rfnsmrmg.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2bzzxihpb.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2htyekssz.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sqnrsgyn.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2kptygxac.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2zkdbqnnj.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mokdseau.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2virimwhn.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2dsvgueuc.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2eqryxmlz.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2pzcffonn.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2amevyzna.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2mxcshtac.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2wwyfpnob.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2oeetvnse.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ghwcxzda.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2xnporgsa.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2vqloypfp.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2fqyggguv.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2dixkfybv.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2kiashcby.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2mlmiqtmn.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2bedvkocv.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2egydlqty.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2gfpfxgas.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sqykvhbe.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2lriuyocz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vxqtchli.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2qqanfsko.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2xksucfyw.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2tmkupmvl.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2oufkqxfr.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2bqegyfqr.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2ualbriiz.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2tiohfcvn.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2qvyfgklv.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2iusdcmda.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2wgutfdqk.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2ibfqujrw.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2kyedxscq.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2vlgjjrqk.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2tzkpbzip.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2ophyqkkj.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2wzpobdno.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2utjkvpep.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2oiovfyee.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2cqvqhauc.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2dxcpawmg.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2vyyrqpcj.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2fgjyofkf.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2wxlzpjwl.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mayjmrlp.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2wimjiole.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2esumrwld.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nteggmtg.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2djujusry.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2owytdkle.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2zctuxlmx.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2shuknofr.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jbgchqyi.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2nehnsynt.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2inttidsc.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2mcsuamnd.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2izgsyiim.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2tjawjosy.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2ohniogju.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2qktmtxgc.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2qnzsetym.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2dylditgq.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2jjulktbs.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2cpfkucfz.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2jbnqbdut.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ogcyfeqz.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2hwldmowl.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2cxocgkfl.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2uvmeqlhq.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2qrdkrkvx.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2rnrsosgb.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2zaqdydjm.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2uozzqfpg.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2ieajqtxq.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2uehynxap.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wyvuxvyi.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2htqmikws.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ipcxjmtk.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2mqyrjczm.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2jboqbixw.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2hsxvarue.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2aufjqaxq.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2qxlpmhso.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2mhpcuwgc.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2kqndbzii.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2zscvtydv.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2bcktdsoh.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2ukogkknf.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2kxihzwez.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2abrelymd.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2zwufxdex.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2dnwioxqh.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2lzghlyok.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2osxmpwpf.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2gifmoqfi.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2cokhnnkk.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2upcjmioq.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2ddrarsba.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2qejatffr.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2zfjobdpl.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2bhvfurje.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2sgmwmprf.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2hwfwmutf.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2bansodxt.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2rclcxbzd.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2clypvypn.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2chwlmahx.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2rahbpgwd.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2usrfvdsu.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2zjvtzhvh.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2lbsecajo.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2mtxgrqte.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2wlbcykos.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2gvbcatby.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2bvvrzocj.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2kspabiyu.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2tjjktgzb.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2huwcyyux.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2vhceqdzj.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2mjkrtnna.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2slnpgilr.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2cfengynk.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2fssopeoj.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2kjqowcft.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2nfgiwmfm.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lkmsrzfv.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2uvxakbeu.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xhgnwbmz.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2azfzwezq.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qfzfmeoj.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2uxqrkxmm.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uuqyacyt.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2fadoncab.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2obytcriw.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2xtknbvnm.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2jmgwlhbt.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2viwkxqgf.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gwbachmn.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2vtcicfjp.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2frufrsnw.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2ijvubwqh.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2qpsxcsnk.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2ewswkmym.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2tfdctlks.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2vkwoxudi.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2fgobsmxf.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2hopwrakp.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2kpeqjias.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2ueihiqmh.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2vfwwiqqi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hzkzifzz.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2rsgrebvw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lilluyhq.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2edyeqpva.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2pzpsexxz.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2sjbvpcuc.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2sxmmzsoe.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2hrytxork.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2utoiqsxn.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2pvjyhfuv.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2pmbghrxx.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2lnfsiddp.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2ntwbrvez.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2phgtgjig.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2gnvhzssm.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2jxtebcty.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2hiqkfhjf.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2lpppewcj.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2kgncqirq.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xipoaacg.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2iehuueua.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2qkiimouh.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2dbuadszu.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2otfmdqcu.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2mpomiskb.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2yqnufcor.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2vksrbwnm.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2tkpyxzbm.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2mksfxtra.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2jbfvkrhz.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2rniuuwob.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2rgedcrct.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2sphivhbr.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2rpfmfxlt.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2ygttjjmp.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2ahmgylap.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2tdewcksj.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2qrikwzoa.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2cinocxsm.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2sdspfkpo.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2koseofwj.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2cjfmwocm.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2rahsvtaw.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2nrsbtnhu.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ozmanzbt.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2wsvdkajs.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jwohfeps.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2wrpurnpg.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2wolbuhea.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2huorzmnu.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2htvppguf.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2mgocypwj.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2mkyiiqyh.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2fjnuiptx.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ysbxmrpo.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2gojszwkk.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2ideyifbi.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2byaeydmz.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2uikooycg.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2lmsaotzd.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2fefomjis.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2pmpzqyim.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2phykhrdq.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2aroqmxip.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2ejkhjekt.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2phgtusej.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lhalesof.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2mxbtkrhq.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ecsqrxxb.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2ldrutopq.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2kahoxwzp.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2zfrduocl.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zuqvuqrx.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2qcmhzatw.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2qgpccurg.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2fxxohmmy.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2plkgjmeb.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2tbymjinx.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2quzlqpol.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2pokpendo.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2hsbjxlsy.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2yebylahn.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2bfllrvxy.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2xnctafca.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2hpviijtb.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ggzznezq.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2tyxyacnj.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2klpepjwi.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2mxwwlnsq.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2pairtdfw.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2fryqbcyd.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2uuvgqgom.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2qdbkyoyg.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2pctwzxgt.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2nndfoxvs.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2fggyrjzl.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2xlwuccth.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2dcxagmjz.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2hicofhwo.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2dbxcsqnt.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2sbayorqv.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2fncleshq.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2tpvtukpz.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2pjuhvjdu.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2lbpxaykt.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2nepuzdvc.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2dgdurdme.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2nlfsqyas.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2yryjxxhg.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2pldmsspr.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2fehwoytv.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2yeonbwrb.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2wcyyyuym.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2wuyunobm.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2qgalvrxa.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2xiepnhuv.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2vfbncrqe.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2kklqbqlj.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2iwscvfdn.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2xmsajnau.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2sycqwraq.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2obazmmgo.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2fvzolxzb.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2hlrtanag.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2gxxclyhu.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2diegtkuo.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2freralkb.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2vljxstjj.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2guurhiom.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2ttodzmbi.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2xgqlakdh.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2pdosjzxa.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2xmurfnpd.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2ptwalnkk.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2ffzvobsv.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2hipylqgp.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nhijrvyu.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2hxoqwkzz.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2rygkpcod.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2gdvfnibd.html


<!-- 参考信息 -->