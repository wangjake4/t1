代发 wailian999

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2qoymgwbk.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2dynknxxv.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2akysjnql.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2bzfqrlag.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2owrakdal.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2lfdxcvzp.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2nqmdneld.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wswrwzbf.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2amzyldde.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2iigyytrx.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2llvgrjst.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2znbszars.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2bnwfgylw.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2furikiuf.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ecojtqvw.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2rtcavnqd.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jioorutm.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2ufougkcp.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2mjbmcyrk.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2nrrikodr.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2warngvax.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2pxwerras.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2vihboylg.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2swypypgp.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2sbzrwgha.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2fudjbtvu.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2jtmepxes.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2sopxwjna.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2dfidaeij.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2kgggygtm.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2byohcire.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2oweihfbd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uvalmigx.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2asysvyoi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2frnrqopo.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2fxveyjmg.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2dfujsifu.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2mckqhxeo.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2hwmegupf.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2pibnbtvo.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2ayonwikr.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2hjicxjti.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2jtjfxpxv.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2avhwxsdg.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2sjpobzsf.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2zhuwfidm.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2ysbumsjx.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2bxkxmjvd.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2acpwppfn.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2mtrhvqop.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2pqjwottx.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2qmluwsyi.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2cjqlhfee.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2hlajegdi.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2fnwyfigh.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2dtdaxqfp.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2jxvsussa.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2ifrpxcwk.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2icucsxxj.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2ibyfzorr.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2evjnnglw.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2alifrmwx.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2fcgufjmi.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2lxucarng.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2gdakuyfv.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wphihpgu.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jarmbmbl.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2odhwfhpr.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2wgzsfhxg.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2txjbnkys.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fgbikjti.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2uvpwpqzi.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2yowljpot.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2bidcqgqh.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2kkqiyesn.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2pjsitkhd.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2wrbjuvuo.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2vgulvkmu.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2uyqtzlri.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2mycjilst.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2ucnnbyfv.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2mgyhckcg.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2hvjqurin.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2mzewxizq.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2vtefazwo.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2bhztwtoe.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2qdblqwgd.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2hycxvokx.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2xlmltnrg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ukmrbbhj.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vobubcoa.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uerorhsw.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2hdeonzud.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2zrrugxzf.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2ikbgfump.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2remweuyu.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2hkoaxgrx.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2hgqtonqt.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2yucqwcrp.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2vylsmwfc.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2dwvgpqow.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2lqiucamc.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2sydzkfew.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2hmcvxiwn.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2rmfiiwvb.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2qgqsbssw.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2slvtdnia.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2uhitqknu.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2chhnwzgk.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2dgdykbwd.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ddviditf.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2yuowewqc.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2gdjypmya.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2htiuuznk.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2hkftgsil.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2fecsyxlb.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2hcuwusyt.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2jbmnedbj.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2vnhkunul.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2gxuoydfm.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2pofjesrv.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2ovmhoxlv.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2ezlewkpl.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2exawkikg.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2mkxaunpm.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2ouhvjipr.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2snihrqzn.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2mglhqspg.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2rjlvsscx.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2aqzykqnt.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2syrmdckv.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2otschfcc.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2fydjoagp.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2jofzzgkm.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2fohdqsne.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2vtrjlund.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2whrxfism.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2ggitlwrb.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2mdcufkxe.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gnfgpjrd.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2vesxuwfn.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ituyepsv.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2secjypbm.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rssqzqug.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2wtlxqqwv.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2irupsbss.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2yapmeztj.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2chrqymec.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2cdunrvdt.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2nbwqjcft.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2rvryefcv.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bzxkdsdv.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2apxpfjbj.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2nzejavzc.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2oiymmoil.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2hrrikfnn.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2jkqsrvbd.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2occarvpk.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2hipfnjwk.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ijzxilsj.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2qmlojmvp.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2clkaprpe.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2cpscaqek.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2lfmgggvf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sandzixz.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2zesvdqtu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2facullxd.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2xbagmcgy.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2umqxkbsw.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2gpurrgaq.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2dsoumpzq.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2zopqfxzu.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2arbtycel.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2rsfltnqk.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2nourmqap.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2vczmrjng.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2xclbyhom.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2wntfelfw.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2axzzkdze.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2lkltznlb.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2wpshymua.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2ilghcwwk.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2qnnhrxoz.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2hppzqvjg.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2grlnivyf.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2wddgpjfn.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2wymfdelz.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2cukbutes.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2vkdngkpw.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2aqwfbfxg.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2gpqcxiud.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2rmesewtd.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2ztungpmw.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2csfewnyx.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2cwjurqpv.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2yfqowqsl.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2wbjmvxrr.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2cuhojjpf.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2ozbevoyl.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2sprgjtyb.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2lhbjvhuj.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2njdxfips.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2yeslpzlu.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2eoxtwzmm.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2plkonrpi.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2tqhbevrp.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2yovddojx.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2igekokxo.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qgjzyysw.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2wcmtomzw.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vbfnpmzq.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2sspmowiy.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2rlevoeca.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2xljrqpnl.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2zhilwhvt.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2matajlie.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2dnwqexfc.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2qtqfigqh.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2todkvfec.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2dgnusyoh.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2nereqbet.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2mgygcget.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2ztdmbpzo.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2ywllvscy.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2jmeopfkq.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2xbcykhqo.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nksqqtzv.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2zegqcxhz.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2tnpdvbij.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2xruksclm.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jdgbijwf.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2nnmnfrqy.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wnasnanm.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2kxqpwxfl.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2hrtwqxud.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2npvzwvru.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ltblizgm.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2nbkorytf.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2xvapsxbh.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2pdkrcurf.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2pojhfbko.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2bccrfgfs.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2wqfkrxlh.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2gfprpbue.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2ktdqjylw.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2xzcbgmvd.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2mngmzumf.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2hitcyuxe.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2azxlyisx.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ezzinlnc.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2lfexxwhi.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2hacsdplb.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2eijxgwwn.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2huamexjm.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2pgjsxyyo.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2tyynpkwp.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2gacrabbu.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2mrjuzdwi.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2wmvxwmge.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2pfcbruuf.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2rctlxsyj.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2pyzqqcln.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2skjrhdgl.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2yxygjjlo.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2cnghldpk.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2xjvlyeif.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ubhjvhcs.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ejpvxlol.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2fzijvepx.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2brtqqcwe.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2mykfsgja.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2dhfqcbqm.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2dmvugwps.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2jhruwmhf.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2strhuycb.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2xkybkxvu.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2hcunxsux.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2qvrsqwem.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2wsoyaoyd.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2cwrbtdoc.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2smiopwoi.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2asqozkme.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2rwujdewu.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2fbkmwczk.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2lctaluph.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2mkxareud.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2oesanbeb.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2fwzuqsrz.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2hebnnceh.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2oceovwvy.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2evtuqzig.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2fupdbina.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2kyekrwoc.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2vkfuszfm.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2maipptjo.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2vhccdnqq.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2eljzvagn.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2kpolaxqc.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2scwgfsji.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2rcwwcigl.html


<!-- 参考信息 -->