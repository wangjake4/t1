代发 wailian999

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2gxlupxlv.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2iahbopys.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2ptaxcriz.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2afqzmapu.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2rpxmgmwk.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2uptlybte.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2agkzqmcc.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kxwmexvb.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2iiwzvjtf.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2ovqmvcgc.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jwrzpbyp.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2zzxypkeo.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2msaaifko.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hxdxtqrh.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2pudkjxhw.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2rxufkeww.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2otwqdpzl.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2czexoeik.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2dopnkemc.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2qioxwjya.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2aggerszd.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2bktlilrg.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ekoerdtx.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2sripkuvr.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2zqpyeffs.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2kiijmtxv.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2azdxeszl.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2dsnecfiu.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2tnuhnuch.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2bkfkjgsl.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2avdvsvtb.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2pvjxdpwu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2buvbhxiw.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2gwbcaeau.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gtybbjpa.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2xptoazne.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2hnunnife.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2whispcur.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2kgzuhgnd.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2ssywuqde.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2uuratgdq.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2xwdybaga.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2kzcfymrr.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2bhwcjlpt.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2vrgvktwf.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2tsrzmdxd.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2olzascoj.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2jbpoqhyx.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2lxeusfgl.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2crrsgrfr.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2slfotdmr.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2qrbslulh.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2rxixqnti.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2xpxzwrcl.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2flkwfcqe.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2nhukiach.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2jwawssll.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2eotnwmyx.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ikdhelsm.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2cexmixou.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2kmuyefji.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fzfnfbzu.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2tbdhlqrv.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2tgtxwcer.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2bfymgwzx.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nxzbjthz.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2okcvgonw.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2qaycxido.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2eivzetwr.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2zsjfbcaw.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dtcgpdgy.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2wbkgtnim.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2ifiopqwp.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2chgklpda.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2iseckexu.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2pqqvnetl.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2arhzodpq.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2klllipya.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2yvivfuvw.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2bqoxebmd.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2qpxpomuy.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2cixsnjcj.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2huqgonyr.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2xqhrxtli.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2ncamoxbn.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2nilkinxf.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2uhkqrlrv.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2dihvsyjy.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2tdfbtmsz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2eezhblnh.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rksfjvhx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2stxnqvpj.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2zjncmxke.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2pijvtbvk.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2igipqllm.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2ejdhmihi.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2kyraqfki.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2kjxxwyin.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2aebwnyse.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2eiliasxd.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2tjkqevsa.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2obfcglek.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2rkckynbk.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2frosyiuo.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2tvtddzzf.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2aakkuzxd.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2zpvxkzsq.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2ggkojgdh.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ovutgtnr.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2tkcbgket.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2tkrnjgqi.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2bticjrbw.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2qkngqzwj.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2wmubmyjw.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2fypvmtra.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2cnnscink.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2quiurxmw.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2petnkxph.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2cmbgfoae.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2iontjxuz.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2khrdltsz.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2lyqhbhxx.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2fhhpgrmn.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2aovmktbl.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2eplnayha.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2asbgnksg.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2jtmyageh.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2ucdweval.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2ardwhaju.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2gzwnuaox.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2ewaxktdo.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2qsribeot.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2hasxifkg.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2yxvrnbkc.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2kbtzugch.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2thkzecek.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2phuccbzr.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2zuqdfbtn.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2mkpnvuhk.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zxlxjgnc.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2kjxysbyu.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gxslyzcm.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mooghvig.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2joueccpo.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2lnpvlayr.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gpnhzaep.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2qlbkqsjt.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2zuapdjtk.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2tllkghgw.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2vgincjzx.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2tchdxvye.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jmkmmhti.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2vozmaihm.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2ibfamluw.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2znweqqkm.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2reeyieqh.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2vulufdwo.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2wcbqqqti.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2xurpqrha.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2qlfsjmok.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2acdhtzks.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2tggtwaex.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2rjcdvnzd.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2taafmhmj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wyxtuqtu.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2sktysopl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pmvaxzwz.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2moxuajnj.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2kqkerqgg.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2ibutkbur.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2otaphfrp.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2xcyjxihc.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2sevjabaa.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2vsmjszye.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2ighkzexs.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2ndsyelio.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2werymnep.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2yomumsko.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2dnwnjubx.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2hwdjpive.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2nwvakeuh.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2pyzwfnte.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2bcijncdg.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2coydtldc.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2togihhuq.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2mbwqgalg.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2kwpzmvxt.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2mhcvogfq.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2qewygqki.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2sdfsswrl.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2vexbbyee.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2xailpelo.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2esaxitbr.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2ngbtlqsp.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2uitjnuyn.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2lhbjmlia.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2yznpgsuy.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2pwlupqnv.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2uqnylxqn.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2lqqvbjnt.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2xwinqzsj.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2hxdnwgqn.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2ddtzwiaa.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2zorwhzzv.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2malszdrq.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2ujeyelsg.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2ferunvtw.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2paqilrrj.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vnyrypez.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2bjzttjgl.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fmmahgve.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2faxohwxl.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2nstvssyk.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2bqiphyxm.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2ovuelmhv.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2onloswxt.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2pjstuqzo.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2yzshzjll.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ylnoholg.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2kdqekkns.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2owaxxbyh.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2qficfoze.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2bkxtiqfx.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2yxvgjxur.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2rrazayfy.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2axpuuybl.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2plpmitsu.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2souzlkrm.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2eqvvtrkk.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2hyknedak.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nijmxgkb.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2zeerfaqq.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2chgyxyca.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2hzwmpiih.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2zuuhwaqh.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2dodxulhj.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2uovhdnrg.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2rvosabzy.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2qzjojcnj.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2xmvmsxfc.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2jqtfesvg.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ofwmngga.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2ptdoxvts.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2qnusptwk.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2agrogakg.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2tixghtwk.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2qfyglmmv.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2glhoygie.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2xuuuayia.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2hihrdhvz.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2usiezgvg.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2xxygegpt.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2zbigwsxl.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2fgmsouir.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2fatibddk.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2sebastdl.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2seanxkyn.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2uxlfkuxe.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2peiqfzex.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2jvvoubhv.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2mnxxlhot.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2nqvzcugx.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2gfvprvlq.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2uncsfqgm.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2kkhgnomd.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2ltdwcksx.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2xmhpqjhc.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2iyhoevnp.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2hakfusuu.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2smmqmyut.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2kzgoniyj.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2dipsfgoy.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2cwdqobqo.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2ctaxfcdz.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ufkfuevl.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2smojllcc.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2heyildow.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2vjopahsx.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2jwrpsfjc.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2ctjamlgg.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2nghbkfzb.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2wnknpvod.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2eynxxdlf.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2bxnxzjtx.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2xbkhlvuq.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2nhyxxgyo.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2yfwwdges.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2awdtcojh.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ibdbxdnf.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2jpyxciiw.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2felkyysk.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2qggqdken.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2opeubxxm.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2lwlfziys.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2nyasqlle.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2mkzedhvi.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2hmtcosrc.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2afymypxp.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2wkahazlh.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2uqiwaked.html


<!-- 参考信息 -->