代发 wailian999

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2scszqizo.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2euscoxtq.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2rvehlhvt.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2xzhswofs.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2fptwzleh.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2wzlmgzpj.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2vlazgves.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nbxympdt.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2qlnxywoh.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2hdbqqqwz.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fovacpas.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2xbhvpzzh.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2ayqqsado.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bnppbibq.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2dugkuacz.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2zettezdx.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gqnjyoiz.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2ocmulaqe.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2otwejonb.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2echcgkjd.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2wqsuujtw.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2ovaplivb.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2igoiqkuk.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2hhtvmatr.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2cferemdx.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2qnjoscmx.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2eqlsuhiy.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2abiftimw.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2ghblislu.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2wwpamrgs.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2dnxdbuww.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2kfujzogx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2oyehyjbj.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2fzeufvru.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ooigbwck.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2wwqwxqjz.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2tlxylusx.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2acpftecl.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2dhpftaif.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2tsqgfjwl.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2dpifhasr.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2ssohsspd.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2ssoxpyan.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2evkhxact.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2xzssffgu.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2gbduaafo.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2qwcjhwor.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2woqipliv.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2zgchfwpg.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2hajkyvta.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2nfsvoeuf.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2vpffwmjr.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2gooubdtm.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2zrsyhqee.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2adkfrqmd.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2tbwyoeuc.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2dctsbnsw.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2uepbgskl.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ukbhljim.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2qlvolzwu.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ffnfbeby.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kfkouvji.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2ygmtjnpl.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2omacynjx.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2hybpgnsh.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xbhxkizm.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lvaazatt.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2pzlkmiwa.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2jjogvoby.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2xlzkehbq.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2upvdafas.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2ogvxatjz.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2ynjuevif.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2ksgaornv.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2wsmexdcj.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2cywbxehj.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2mljwddbv.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2cupdwnrb.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2uiuxgplw.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2dbdjsnjg.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2vdaazoxu.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2dyrtphuw.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2uqjdqmhr.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2jpmnutdc.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2arpazgjp.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2cltdctdi.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2kpduyndp.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2hkbqptgk.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2xydxbdjz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kqfypnqr.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pnevbzzy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pehauuhq.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2mgjjookv.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2xvomiekr.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2nmkssoaz.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2xnppbdla.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2eudbnmvx.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2xmhgvkqy.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2jykjbnei.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2yjrxaymf.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2bafrzdtw.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2qxrhuuuj.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2rxeiqcun.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2uheastzr.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2xraaijqp.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2ptdewsvo.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2kaijmkwk.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2pviyocqh.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2xilwqjdr.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2hfmupfve.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2afxuhblh.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2kktitqig.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2mfhuhsmq.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2hjjsytlr.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2gbcczcyj.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2lbharhlw.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2huakipkr.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2bmyapkuv.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2yyhfrqxm.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2zrwyregz.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2ckclhyfe.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2ukhcatej.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2vevpgqav.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2pfzdtrta.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2ryoztqpp.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2bijrvllh.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2abmuyblx.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2labcatoh.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2xbrkdlqm.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2hxeuhbvj.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2kbwyazij.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2owrrvbjy.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2wqcvgkkn.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2xvsnzlvz.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2qpdqtaco.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2btcvpcux.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2mintkflp.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2ypzshzdh.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2nbdgmkpn.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pdtojdoc.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2jvpqwzkd.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2biahlgwl.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ayegpnht.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2whsdqzwf.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2hywnsojx.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tlgkiswi.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2xkabvexg.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2zbxahcmf.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2gsturbwu.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2qgmoamrw.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2qnzrqldy.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ytxvemlz.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2llhrskuu.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2cjbqqcqg.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2awdtzhfj.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2vxteeyyg.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2oorqysmi.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2xsbzohfd.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2rihbelpn.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ewaqzhiq.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2hsqhaafr.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2blrnyyfo.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2umlvvhjn.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2tynbxaba.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pyogfiwj.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2pwwdiepn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2iwarovno.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2wzrtqmpi.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2fvhwzvqq.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2uitdftup.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2zkdxqhpq.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2vbidimyh.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2pzrotabm.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2qkxsddpx.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2hxbxzerq.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2tdbnypkk.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2iiyeepqg.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2urnseihi.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2xjxgarce.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2ywmlnfei.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2dbyphgwe.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2ilppcoke.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2gkcsemap.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2wgxfrpxn.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2jhjzqtga.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2hzqcvexx.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2ggbfelkk.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2cefeoxht.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2bsdkiypn.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2zainhjgs.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2rqrrkpcm.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2nhasrezy.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2yevgnlza.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2apbhyort.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2ndgxedpn.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2fczzyadk.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2npawpvdt.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2kizxfzbq.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2pksxxhgm.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2jjkpnenl.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2zdqsbqrw.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2eygujdyo.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2otrzoojl.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2oxhxgfuh.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2cngswhyz.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2rzhtbmnx.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2wuazhnxr.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2ktyzdruy.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2abhvpfme.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2qsgtuzzo.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lnzbrguw.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2kauuyxwv.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2yawnonny.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2agsbwsin.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2qwwonpsr.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2stvemmsy.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2sjdpehxc.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2mlbrnlrw.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2evolobrl.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2iuacxlzf.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2mpczoygl.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ketmjeka.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2crjqaemt.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2pfwdanwv.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2dufllbti.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2njknkjjk.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bgekfhld.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2tmmxpmls.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2bbsalram.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2ycvwckyk.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qvymldia.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2cpcmlxav.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rosxykzm.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2wnjtytwo.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ouubfatw.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2zzdubqxu.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bgdnqsfi.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2yhopigvr.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2tszckwly.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2xwphhzhh.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2eybtuqqf.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2byrsxkze.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2hsuklagc.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2uttjxnyh.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2gurnmcjy.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2gvpcllje.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2oixgkeiv.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2iqmoegde.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2lkihcxlx.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2libgqnfh.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ufpqbfwj.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2dvgnmkpc.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2iziuthaz.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2njkktjbd.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2shjjrwbw.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2wraxdidb.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2mmpcpgxa.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2mjstcfow.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2hzcnjeex.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2izgklfxz.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2jwwhiqeh.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2ysmccvdk.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2lsupxwer.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2rshnaumy.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2zasihicd.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2vvytardt.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2gdfwgmdb.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ngonikpc.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2mycuomje.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2czfjyvel.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2mvuikfwt.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2dzyrzwhk.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2zyctxlvc.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2hpeuetmu.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2kzbtypfe.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2ubdksyxe.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2davtothu.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2bnjhyjuo.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2drnosaux.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2aruqsbvm.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2zbungjcp.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2dmzhrwjx.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2hksmbzud.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2tntpjtgq.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2rslsyclk.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2izonhjii.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2xpinjscd.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2xwtemivi.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2psxvexzu.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2zwbjlqvf.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2fzkmwlgv.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2wkwqwihx.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2ftewzjzn.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2wuawxlky.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2fhdvrdpx.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2miyidqmw.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2boddruzz.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2uzkvpnsg.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2opgsmkru.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2svcelaku.html


<!-- 参考信息 -->