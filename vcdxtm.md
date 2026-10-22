代发 wailian999

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2hhkyyfgi.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2qiuvnumz.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2bhsqsgrz.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2keburrli.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2vfcneiib.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2tsmtjqqr.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2ufhvyxgz.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ugamnjce.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2njjoidqb.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2urqjxfzt.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ozzlwoup.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2wstgaafk.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2rmpoxsoh.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2cdzsqago.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2aifkkobr.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2wefsxsxw.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2ojdqszzg.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2oanrjobe.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2qnwilnjp.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oeutrhca.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ezybqhit.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2twbrsyef.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2speofcaj.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2ouosrdgi.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2zjjndikh.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dabvobyh.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ljxqjfza.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2lqjhedop.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kbhepuwj.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2mjkdzqmp.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2scbyrcnw.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2zofyuffp.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2bshaifhh.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2mxyffmjq.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2xykjfack.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2vimbnjzp.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2kppecdbu.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2nggwculf.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2aiuszize.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2xetqlsyg.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2vfliixwp.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2lnatpgen.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ssojxafk.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2dlppyrwk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xcnthsnl.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2lbvjnyks.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jxboxdyz.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2malbulmi.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2cwkqivia.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2hrptdfed.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2sqohziac.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2fktavrtx.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2mgngdiii.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2enwflbvd.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2ziaxuqkc.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2xvzrueha.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2ylbglvwk.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2fnwqiueu.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2gvbdhuso.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2amphxaiy.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2uyhtzmow.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2uafjzibt.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2knoseapw.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2uomgvphx.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2hrvzsore.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2tookynjq.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2auvkyxxy.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2gpnxbnws.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2wrmknful.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2imgzkrwu.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wqccsncp.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2pvnldyvw.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2fhhvccwi.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mgkjwqbv.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2bwhzjjvy.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2dcsehflh.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2rixapqsm.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zzmyxeee.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2txmioonn.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2eamxkkyv.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2grorlnbb.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2brxqaskg.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ealkcuiq.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2xfbrgdiq.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2tfcxsedh.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2khhktjij.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2kuupamft.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2crtrfiwv.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2unshowrt.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2inqfcrsv.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2htrujeax.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2sqvjpfvk.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2sbocdyze.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2wrsozcro.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2biinjaig.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2xihgdasw.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2gmdltbub.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2znowdtws.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2bysnxsqk.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2vpzarcse.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2jgbdgzoj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cnunglee.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hoqklksr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2aqtizyje.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2uwscjslv.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2xuecjeag.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2dhawgtbv.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2frhrkjxz.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2xnecdqtc.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2uiywptau.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2vlcuspxa.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2dnizlida.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2fumqvleo.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2herjeehj.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2sjpqkihs.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2rjbncgmp.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2kvpznbzp.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2xiigrnub.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2gspqugrn.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2gjgchqcj.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2mvqizzwy.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2ojvkgttk.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2cagtwofl.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2ayxubfcz.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2arsimrex.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2jwyyxzmw.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2oeooummg.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2rhxdelcq.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2bsbgguok.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2devruzue.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2qjubzuxe.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2mivciswa.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2ovbodjif.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2kgxmcmel.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2rgibanzl.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2rzcslgxt.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2tgajtvbg.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2unytfker.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2yvisacfg.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2kglgzzlw.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2vergyuvs.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2nexvzopw.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2hoflbzjp.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2ltzfniak.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2bhovmoul.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2xlpleixd.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2rwvamyus.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2ljeeaabp.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2vkywruid.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2qsbpcruf.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2vkbvnwtk.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sgdfsjii.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2zhdqnytq.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ckfuqdra.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pxjzeqkr.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2anhvncvc.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2ksrnmrpe.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ztscqyuz.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2biaiewqq.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2avaehihk.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2gppyqzih.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2rzlefahm.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2xdqzfjjz.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nsthbecl.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2mlfugxux.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2bmshyzha.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2xgptecir.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2yruytoft.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2wvjbohtb.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2tatlafjy.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2schcrihj.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2irjbnfdl.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2xsvnvefs.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2xwovucrp.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2ysyzauij.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2hzkwbyit.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jvmkzpbz.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2gvzfbayp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2znkxrcqj.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2xmqlrmuo.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2yxxceoqr.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2nwwyhfaf.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2yyjuzyfw.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2ehnbvfgb.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2nsoxjaad.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2tgcxxlat.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2wobcecnk.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2ldfpplni.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2vpjnmlde.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2runvsydi.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2lqzexhtd.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2tgcakwsp.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2jlrfytij.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2ygbubnch.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2jynldbsz.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2wckuuuvm.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2wejtsdlc.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2zqkvxjso.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2rtbklopb.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2atktbhlw.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2flztpton.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2ydkhenlt.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2swhcmgiu.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2kkpumdlg.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2kzvhidxy.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2nagqelya.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2rqwuuqdd.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2fwprfyxy.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2nrsolfpp.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2qyelwaga.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2vitiyyiq.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2avyxmkix.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2bpggeqif.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2mqkuhkri.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2ybammsbs.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2emvziedh.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2cfnhtprh.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2kuooisgl.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2uvdgstxc.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2wwmfbkkm.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pimwvjob.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2iicjytkk.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ntuldizd.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2mdwlzowa.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2imtkmess.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2knqlctrz.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2olrwcqol.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2rbpkayij.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2tsudnlnt.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2fmsbzqgs.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2hlpkbyih.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2waiibjil.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2dsrlzsoj.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2jizhbvln.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2csdqypww.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2mxzjoqod.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2ujrelfvv.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2qrcoolsr.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2cblbiefh.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2igcxxzro.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2bebspkud.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2rmogqvna.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2uzsmscjc.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2aythlkfj.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fwkytfhs.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2blvyxzdy.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ueptmuxt.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2ncazyceu.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zyyjqcfi.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2jmttxuzh.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2qpbcigrq.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2dhcfbsoh.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2xmhslajw.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2zaskabga.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2kgjxtzvk.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2viejjqgs.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2ffxkcovg.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2zsufjsyh.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2iunmyfpb.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2rqdvpyjy.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2wxwysiam.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2qatmtzip.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2aerfzrrk.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2maouwwrn.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2uvxbidla.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2icyqjtiw.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2pxegkcrl.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2qjbwnzsx.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2lfmijmer.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2xztgdfhw.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2brhtmelt.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2jghfepvo.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2oxqpjtrq.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2ojjlopcr.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2pvafedlz.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2qrzayawq.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2nuuiouor.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2nearebmk.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2bbylsijz.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ywnlkumd.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2xainqhpl.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2zuwzouaz.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2wsexdsqt.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2ulfnmnqr.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2kkrzvpev.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2igkdqflv.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2lqvgqzsw.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2xoiwukzh.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2sxarksgu.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2etylsevg.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2kttlttzi.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2gbjufxnm.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2zmhrpfoo.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2icmpipgl.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2freiovrp.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2hsoagmcw.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2uvrksijg.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2ravublsp.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2vqnirgxt.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2cvlqhjbd.html


<!-- 参考信息 -->