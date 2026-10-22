代发 wailian999

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2vcsugywa.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2gudexnyn.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2bwrzrjvh.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2ppyqpvmt.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2wpnxuldx.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2amogetre.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2oguvjwty.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2vtaevfan.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2nlrxwwee.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2wsvztwes.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2xchrdtdt.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ztgpdhvn.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2clfgydeg.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2hsbkthwu.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2xceebirw.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2qkcsreec.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2ccbzjpqf.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2plbfvmkk.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2vdkxgesm.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2rmqsjvqu.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2gqijyscg.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2oztwtnye.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2hqdgpzrp.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fujrznic.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2jwhswkhu.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2sfldwtsg.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dcwydbpa.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2qxroaumh.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2inoewbjq.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ierhrehz.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ymiohnpj.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2cxywsdyc.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jjgpkdcd.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2sadotpbs.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2mthxfotw.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2nweoiwyp.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2tkjxxthh.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2bvrqixnj.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ridlhsip.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2ojbagcae.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2kewqzzvu.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2ijzatpbl.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2yzibpipo.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2dawwmklk.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2joewlivl.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ludndkfb.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2coqqfked.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2rolgkusd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2htrgwxjf.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2aduhplft.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zpsugbpe.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2nijecfhz.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2kmiqnzvu.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2qalcreza.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2oelmmhvi.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2zsprvkgc.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2vpovinsr.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2hpeqdzlj.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2ughqrbyk.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2lqszusor.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2wggeaimy.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2lbckkpbm.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2tbkkqiku.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2jsmrtyzx.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2vfwmxjvn.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2rryarvmk.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2jufcwiyc.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2aslwhgyb.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2ypkfpkqd.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2ghwyuzxi.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2qddcqzax.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2daczejyd.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2ifsroxte.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2alsyqmuf.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2syhoywjz.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2nvnxzzfg.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2vjzmxpcs.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ubdgyjvo.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2jtioktbg.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2zbbxqqmf.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2xelogotn.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jujfspry.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2btkigdsu.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2zlwfcwxl.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2vsphloqt.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2hlarbxxr.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vtloxykp.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2xaeoanvf.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2nhodoxhr.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2tasgmhte.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2esddafpb.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2vejotzik.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2ulqcgskr.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2fbuswjhh.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2xvenxvtz.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2bhemuaav.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2tekuhtbx.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2pkqhhryl.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2iwombymc.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2mghpefvf.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2arfdelqc.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2qkakexqd.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2vwgyvuqx.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2lslmfzqx.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2rwmjcgsl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zyglgtda.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mrytaqtk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nkurrvji.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2dgnzfqnf.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2fjcortbg.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2llvhmxri.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2hjmencfc.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2xlnzlpuw.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2xxkexnhe.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2jhdkndqo.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2hxramkab.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2oosuqfqq.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2ftyzacnv.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2rufrxoxv.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2lrlgdnfq.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2wzlnburx.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2akqtqbyt.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2htymteiy.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2efjtptgh.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2vnyxuxdm.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2hdndgymb.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2szmfpxrw.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2kvnidatt.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2wvaxifpe.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2jaocbtne.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2oxswvkzg.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2jsyvwhut.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2ubjugyhn.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2gfclijzn.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2bdadngtl.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2qltogdly.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2lncrjwac.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2riyvwaid.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2tvkbgtvp.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2alktytdb.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2hzxpgrww.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2nnmtdvuc.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2totobkdh.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2ezmmxlki.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2uqqihejx.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2xciydsjd.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2ratzqvec.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2egsphdbp.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2oisrcqxw.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2bvobbqnv.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2zeamaalo.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2bjtqaiph.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2kdqmlita.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2gvqnawgq.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2onesuxwu.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tbhlucjf.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2cuntvuqo.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2aslwovgk.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2diypqljd.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dmrgmljn.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2nbqyraso.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mddjyvbc.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2qkaqjtvq.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2wllujfdp.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2fwpdfxfc.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2tlfcgfvk.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2oqgqqwjz.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2yzzzmkmt.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2oxugsqog.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2xvbeydgj.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2rrqhyxsg.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2cdekwpum.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2uetdjvrg.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2eqpyvfnb.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2phtsglyv.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2scyludfl.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2fhtmnemb.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2dmdupngn.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2bazmhpes.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2fydbpmzb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pdlkwrsu.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2sdakkyzu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2auuayqqx.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2qwnnaelg.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2ekekuwxa.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2ycucalwb.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2ywcizwob.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2nlxvgrck.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2ojynyutn.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2umibuptt.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2nzbefmhe.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2tqnsmntg.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2pxkdyghh.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2canywyqo.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2qyxrjhjv.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2wtvpcaxf.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2iyqyfhgo.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2kjznebpf.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2wgmqxhjc.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xiefreet.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2ymekkxui.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2xogwjzdi.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2fftclnbs.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2fnfziytp.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2cgqreisi.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2plopkoom.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2cezungid.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2xiblajiv.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2madeoelr.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2jfxvvxuo.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2jmgbtrgg.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2xvudfzfh.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2dkqfblov.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2myvyldgt.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2wnoqdvks.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2wlzjuebx.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2cuunoxsq.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2lnrdomlq.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2vtcnvkvq.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2qxpupzhe.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2qyonfans.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2fwuvaumo.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2hfvlxjbh.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2ovcblqhv.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gjwvhugd.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2stofieti.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rrqeajom.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2tjxlnzpp.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2lbuijdpv.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2lnhrtuvl.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2jwkuunac.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2yrlchdbt.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2cdylokoc.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2yzccyfvg.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2rgodcczj.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2hfdtkamt.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2hlcrkvax.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2pywnueng.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2rjdggxkb.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2hhoariuw.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2ptqrjgqt.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2trnlfzof.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hpfayqvg.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2dhigynos.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2lyraicwu.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2gtyrnpsh.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2innxsnrb.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2cucxgetp.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2szeyjajx.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2ihrcqzlj.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2giwoymjs.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2okqmszhp.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2cgikmtpn.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2xhlxitos.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2pfnveybh.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ullprrqj.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ieqwsvzw.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2okmqxrbj.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2nhxnvyhg.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2uuwfvvtf.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2usxnaxwn.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2hzytkxpp.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2kqkcbcgm.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2oxpjbjzj.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2albembad.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2iltnzdcx.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2hrhjjfxb.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2nojrsgks.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2liiqfwyq.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2zkjmvfly.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2vanphoyn.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2bgksoftx.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2jczrtxhd.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ioxglhol.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2xlkykrae.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2qhuvokcr.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2rcdqvncn.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2fsrzvqpd.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2uubdvano.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2gqrtotpu.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2dfurchjf.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2quqbsnzo.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2qwccbzrg.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2oinmnsdk.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2ppqgdvgq.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2sjycwbte.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2qekscuqo.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2oegswwza.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2nnfuvifu.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2bnaobwmj.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2yavicelw.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2ndrzrdjp.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2dudgsmkz.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2paiphspk.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2dicvyevt.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2vgqpttry.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2japxqjtq.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2xwyqejop.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2zbaxzkra.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2ozlmilod.html


<!-- 参考信息 -->