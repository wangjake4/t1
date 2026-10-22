代发 wailian999

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2egsklmhg.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2tsynjwau.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2rqdcegcm.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2sjnlqkbq.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2xoxcyywo.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2vubzhqlk.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2rdpnrhrw.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2erapshgv.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2bulawggs.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2vmwykqtd.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2mmbgnotc.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2agryekwn.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2eecjnmew.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2kwbhxuuy.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ysogfswm.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2dtbldypg.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2okgxyito.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2vmbjeccz.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2bsgbnjco.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2zqhitvol.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2kwzemzsl.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2ollajyni.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2vtavqbgn.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wvdbpdgs.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2bnafvmmz.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2pnklcfzf.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ttlkvdiu.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2cmcvpzsc.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2vzarpoke.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zsuntigq.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2pkoawasd.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2dlslcvzp.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2itkqnvpo.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2ttscafep.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2jiprydiq.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ttglcnic.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2bknhnvkd.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2txqgmite.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2hnqxdigg.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2ttgihylb.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2mybkhhwo.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2pcdykvvw.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2zofwnvzo.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2zwihctvn.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2awnhorqq.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2micpyrrh.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2djxfcwtw.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2pgqxkzjy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nqabnoxz.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2jzmevfsi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qimcievx.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2kzrlauqo.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2vzglbefg.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2iynbsvpo.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2ootnnpuw.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2qisndufi.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2nxorydif.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2leeucdpp.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2rmchlsee.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2ggwnqcxj.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2xhphhaoz.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2nkzlkzqm.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2bynzjoou.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2iliihnre.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2rksuvxlg.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2fqdxapgn.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2cfgrvpjp.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2nqnsimmf.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2brhavfsp.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2ykdwwuzy.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2cdxutrwx.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2xkzfdrxs.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2hkfhlahh.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2kqyjctwa.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vjrtxkts.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2oexasvqk.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2obhisxoo.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yjeguswx.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2bsunvvrz.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2lfhjyeap.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2cguiyynu.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vnapqlcl.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fzrizmvc.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2trofelff.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2shkbijzv.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2ymaqphug.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2djnreptr.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2mbgeoicm.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2wdjnzsxa.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2qxbhjrlj.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2sqnynhbn.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2obgnewtt.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2yyuziypi.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2skfghbhj.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2zjuqpwgp.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2oahbavnn.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2cldctbgy.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2jsvmgbay.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2kylssilh.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2cmssuzcv.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2fgitecgc.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2wzqwinhk.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2jravkkaw.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2ihwaealu.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2qxocsskc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ieodfmar.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xeykgyjp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dxuzdxna.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2phchrefh.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2riygqiut.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2fuwxneew.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2muehujpj.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2chljmjrl.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2cxljokup.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2yuxnerqm.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2dnbvruod.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2iwlztaiy.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2dxssfmcf.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2cjstqycc.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ptqsskmt.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2anftkoit.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2vjuibmtw.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2psgpdzyv.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2qqwjjssw.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2qfrjnxcf.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2djoirifc.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2paqhzrqi.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2hktumiox.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2skeooxgt.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2gvqaembi.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2ujilaozn.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2bottqfqj.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2txlxtrmi.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2rugyretk.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2bijkrjfm.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ppwheomj.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2njkkxkav.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2avdtpemq.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2ztnqndgv.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2zdgtqrvd.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2nkxvnvsf.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2wdoaczxj.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2uzfemkwt.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2luamclwo.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2eqaynrhd.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2gyfnptor.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2nmpafggv.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2oqdvqwpw.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2vicaqgih.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2exqhkreg.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ybsuqwhv.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2cvntdxos.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2bctxeuji.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2rqkutvua.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2hfxufjgm.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2clbicibd.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2adxrstvt.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fkcbkder.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cgbjjiyb.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ftldhbkz.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2yexudlmp.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wbpmdkjq.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2mjzvcpoq.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2gpsbonbk.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2mbojzbke.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2zafepbav.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2wiilbcot.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vfbestdo.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2qfzijpoa.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2cnqjlate.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2zkfigtvo.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2rdwweums.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2yqnwhnax.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2amkmvasg.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2ferbmzmq.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2rdhwzxww.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2rveuxwwy.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2ltlqdsqb.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2mskswwxt.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2hiuaoxcr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mvqsvliv.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2tkupamab.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lsbhwqgi.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2xpnkrbxh.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2seykgcqu.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2yqylmnas.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2hdlisjht.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2fvzzuzaq.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2ppwekiyj.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2znauitac.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2dbdssjiw.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2tohljagf.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2kzmonhws.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2fspbibpq.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2hfruxyke.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2pwvoasot.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2ckqrtvkg.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2wloakvon.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2cdehhrog.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2pmvmqsuv.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2myzgriuc.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2ppnsxsmq.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2tlggfyqz.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2jayqtoge.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2isnkesgn.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2cmwqmzyx.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2okivsdvf.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2lxfmisqv.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2ghljcfiz.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2ecmaexwx.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2dkvfviju.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2viveeoqn.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2udustrxb.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2jrjcjzfy.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2vebddscz.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2nybbxlzu.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2vndqqnhr.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2wmoxmuol.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2zevbimgw.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2dzlynjho.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2sohmsyvu.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2bgnxdcdz.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2lfrikohz.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2jcfvpdll.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zbwhohsf.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2hydplegr.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2waxqnwrw.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2tsejghqc.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2rcamdoct.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2aptarakp.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2sczikwvp.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2uvpthead.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2hvyrkvvr.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2otidoypw.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2dzbruzio.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2nfhibfqm.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2lslpwwcr.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2dthargdm.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2rwbdnfwv.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2lmspnual.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2dtkithwp.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2zubzteuk.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hzdurfyn.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2xukqwhhg.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2yxbkwynr.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2iparlcfm.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dtpwzvbx.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2obkssjao.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ueeodleq.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2xzmsripv.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2exblrhcg.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2rfvesuel.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2frzuxkpd.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2yzbgmzpm.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2cortwskr.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2kdahyhhe.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2dpmfvfcg.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2kybtynbw.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2lmyxnmjh.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2blxiohrn.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2lazimpgc.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2wudpaulb.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2oiyboqnf.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2tjyofoge.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2iffccmcp.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2fycqxuta.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2umkyrebp.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2rxynftne.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2nonnrpgr.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2spdfqmjy.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2msraemtm.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2kqgycvdr.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2rpwcixjs.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2eqqdrcxq.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2mdjpirdt.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2gmtisthf.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2sfpvsftc.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2bvgwxnas.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2tyjwwodh.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2obhqflwn.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2bchpfnpt.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2gqbfradp.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2kgczfugz.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2jerxdhow.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2itsaaivk.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2qhnpilgi.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ackpmgew.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2hrouilea.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2zfnbvcjk.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2cprlqicv.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2dzvceyml.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2ndbydshm.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2vurbnujs.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2bvarjskb.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2iexzhook.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2zszloozh.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2gifyznmn.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2ttwnowpv.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2mpkrapus.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2bwabcgjh.html


<!-- 参考信息 -->