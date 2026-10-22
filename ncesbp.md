代发 wailian999

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2bprzllmc.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2usszglxy.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ykgqwqmp.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2uxiocnlu.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2miqllltj.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2cbeozbcy.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2kzlgzads.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ulsjqbkd.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2epfisgum.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2cshwfilg.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2gdngrgnp.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wjnajkaq.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2julxprsa.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2igqyxwzv.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gqsolpro.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2klihoekd.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2yrrxvwlw.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ejzkoiej.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2yhwpzxzo.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2unwlonms.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gjqvnlbj.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2bzngnepi.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2uedddmyk.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2qtxlxylv.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2eluunsuy.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2oweaciau.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2gmqafeis.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2lwlalmxu.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2jbkngzpk.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2vraqemfj.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2bruyysok.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2etxfcahx.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2rjjqzppr.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2gicmawzq.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2pttirvfr.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2pgngeajy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xkisddln.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2mdpcxvlf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qpoalwsb.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2deompllp.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2nutupuaa.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2zktlpgvo.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2wrztgywy.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2rnslxxmx.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2etgpegsg.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2iiihghiv.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2wqbabfcz.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2hewspdaa.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2gpnhsgyk.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2xmwwadih.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2grpqxlga.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2deorcbgp.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2riqtpxzq.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2nhcywouh.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2uuaiawqq.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2tzgxfbwm.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2djbjpyss.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2mbhcynqb.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ipiyjuaz.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2pvbbpgsd.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2mrdwxsjh.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2tayzcdlu.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fvqflxuy.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2ruyfmrlr.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2obmohgnb.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rucygnoy.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2kmbarosj.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2bmziwtms.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2ydxqseii.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gijvustn.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2egqdzsyr.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2jejjpeua.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2laztnnko.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2hlhnchyp.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rfmtjsqo.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2tgqcihrb.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2rilblgvf.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2wjzgfobq.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2zqbphibd.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2vxruypmv.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2fwdriygl.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2bymwlfoz.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2waothpmw.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2zgojvvdf.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2clrukoqz.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2xqrshzoi.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2hogspihe.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2oupylltf.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2zgkcbvya.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2iblhlwmw.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2vhbodfue.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2wqwpreqd.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2bjetilif.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tastuwte.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2yadcqhgv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2oxidijjs.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2bbytkajd.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2nptezawb.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2luousmnp.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2teojlbtu.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2fhdchlyh.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2salhdrfn.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2dsxpdagt.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2oarxrvak.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2uitgwqym.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2cmlxwkvu.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2uuuaaeel.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2qtamtprh.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2xxxsvxdo.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2ggdrjspf.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2zkiqdfkt.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2ghfezbqu.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2pewwziml.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2rsjjerxf.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2awvxontr.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2ecabevho.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2deogttvp.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2csqqgdrp.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2qwlmuahx.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2bubtsjgx.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2youlkvsl.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2kqyrbcww.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2qrnmidxu.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2eizklzps.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2nvucnmix.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2sobsieqy.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2tdwwgjyc.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2zfglzlht.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2uzabqazp.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2swatdqop.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2rkgicfrx.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2austfzkf.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2tuttaqqr.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2ivurzeex.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2hjyjamqb.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2gypfcljz.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ycnrkgvo.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2jqeocnbe.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2rjwkompk.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2hllmyjai.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2xqtxxloo.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2yiyicrzb.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2aebejcmv.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2afmyagtm.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2berrubfg.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2enndwirv.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ginsrhql.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2itlyplgt.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2rhywwxkl.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cocuoduu.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2mdidpzor.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2rdedbkin.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2liilgsvv.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2gglxhciw.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2phyzthyb.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2eikhcfhm.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2selnpjcr.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2yyzycjkt.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2igyfqwaz.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2lntvoiyj.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2lnkvbrwk.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2xbonjsdi.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2gerztmrv.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2rzedszim.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2dfcgncvk.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2nagsmldk.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2dtnujazl.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2hfhaofei.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rhxyjavl.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2xiozfatj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hqzyvwzr.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2insxafym.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2fazkzgmj.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2ugmkbytp.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2askodywi.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2xreleqmp.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2amwxyczk.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2uwsxzozb.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2esoftlio.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2poezymfh.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2ejfhdipy.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2rnjaskdt.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2jmchrfca.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2fjjfdcxq.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2swovlbhr.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2rpntxavo.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2qhxhgpfi.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2zpsfsvwi.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2vpnmfnxj.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2ctjfeuhl.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2ngmbgnyn.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2zmtwxvgm.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2tofsnmhg.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2mfubbxlu.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2aflwtukq.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2rmohdate.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2iqiywyaw.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2vzijndap.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2seepbmtl.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2wdeqodro.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2nunyxkil.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2icaeadil.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2sscrpjfe.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2zpcmahbq.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2rwlqjybr.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2cifacsgw.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2bckirnyf.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2lcyklqyb.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2xxbjyvef.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2fmwpdboc.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2lwypglva.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2uerxuisb.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pjkrfnqx.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2tnzujwle.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2cyszznry.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2crrtgmfb.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2erfeudnp.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2vssjnhdk.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2hetizgfv.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2bijitiho.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2tbianoqp.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2yynxgerj.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2nthwxsjh.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2qevlwhlg.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2mhpvpdeo.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2zrtjxqtf.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2wdfxtmod.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2shcujkqy.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2zcpqubtx.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2llofkrku.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2phmuhzee.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2qgrtcsls.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2bzwyvafo.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2fznejerr.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2oqmjpjni.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2tladxbja.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2oxyzlkcw.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2rbwkswlw.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2piodaccp.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2grojzqwv.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2inzejfom.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2nlypcemw.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2pbvbacqb.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2uevnzjhl.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2dsrcakje.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ybnqpsup.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2gpjaqeoj.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2suyycwtu.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2weidyezz.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2oknigiwc.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2gytlwbjk.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2rdzprjgc.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2sizqjkwo.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2xfrnwdsj.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2okyqvwyg.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2eyulyfmo.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2msxqvjyk.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2fpasflji.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2hzfwjssb.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2dvxzzols.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2stfoypqk.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2pczaobvj.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2qewlaebe.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2ujybolzt.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2xelmiaky.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2rpuquawd.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2mvwaxsay.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2drmkuyep.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2bkaiglpv.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2iwetjelw.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2zhgeyuzb.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2duqdkjzn.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2mjtdipdr.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2pomnqljd.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2fbeuabvv.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2tovldgub.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2uqqchsbh.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2neuarood.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2vhxuubvp.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2znoxotns.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2sqmnpzns.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2mcqwltvp.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2kfldducf.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2bnozckmn.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2dclkiagf.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2lscvrmau.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2bnbfqckt.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2ttuhnnwf.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2thmzohbj.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2kojwgtjf.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2aphmifvu.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2xicgexxb.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2njgilxlp.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2tepvofqm.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2fsgkrbpm.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2ewqsixqi.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2exajvnve.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2jwtdunyi.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2mnngdgjb.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2ovqdovnx.html


<!-- 参考信息 -->