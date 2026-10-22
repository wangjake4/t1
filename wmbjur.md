代发 wailian999

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2shbxlojb.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2pvrtbocp.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2wjlrwwxt.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2jtimwhrh.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2nspnhhvi.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2zeehwmtj.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2rdldukca.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2hjacwlcv.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2gegeqars.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2xlhqbcrc.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2sziaowac.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2myseuyod.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2xvibwedm.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2iawbeqhr.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2pnvfmsjw.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2hljisufr.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2kjppsnaf.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2ofufhoci.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2kicmtrzd.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oclrzjac.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2fqxxbgin.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2qzfmjprr.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ixztlijt.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2nuhaouhq.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2sgucdmwx.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qffdxaya.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2gxnhfpjz.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2scogleaf.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gbzvupys.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2hspbsrsd.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2birfzfie.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2wxqwbqze.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2fvrbuwye.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2pnzonpsv.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2mvkgstrb.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2jxomowwu.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2uiewuhuk.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2rygqvoki.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2sxhxedmq.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2yebacxbp.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2xmpxzxoq.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ltbwkxai.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2flswbqnv.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2shiqiazp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2eswtsnen.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2bsjdtdzk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vrpgcqxa.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2zdyxbjve.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2yyuyrsbm.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2jpxfjjaz.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2vpdkjodf.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2heiiirvn.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2afjhnfvu.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2dxugqbgb.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2wjfmqvqu.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2csvocbyw.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2rxefukwk.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2lvtnbete.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2wkyqruyc.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2uikumnza.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2dhnvvtwk.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2rvfcrklu.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2xoexaeyz.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2xqmigsqv.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2vnermhnj.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2dzfjkuch.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2roznatnu.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2pesdoqln.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2sypdfbko.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2qqmtdemt.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ktajmybe.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2fyurfmdm.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2qbjubxmo.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rbnwsqgy.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2xorolpni.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2ycyhyutt.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2gafmyxmr.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bzdigkxk.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kprljqxa.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2yjtvosfi.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2buwilgsg.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2gnzigsfe.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fyotwtwf.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2evjybkkr.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2jnsftewi.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2afnnkkjj.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2fxbgjgul.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2fkmgghce.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2utinwjoh.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2akxjsoie.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2gtljzprf.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2epvhmjcm.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2esoanqfn.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2ejecijak.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2uzsmqekc.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2hgvaavkc.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2blbbjypp.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2aqbpwmpq.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2elttcylw.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2pthbfnbl.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2tidpszdg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pszncrft.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2sycdxsmg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2drftlnmy.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2dyahkgva.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2ssnfvbpj.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2guthopvz.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2ruaumjgf.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2npcyncay.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2xblktkhw.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2sqasfeuf.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2ggxskiuf.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2ukskeyba.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2gxunvkst.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2poepvowb.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ujrrzdol.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2snfgmejq.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2yehxdslw.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2rhbyflxh.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2pufukgur.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2baifconi.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2cdavwvsu.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2rkfktyrl.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2rukbwnaf.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2srztkjrd.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2hktkqplp.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2knzzlqba.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2usnecyjd.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2nsgmacse.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2nslxexex.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2eqfoobjx.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2tdxxtlgc.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2jbnlpqot.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2ydpykucn.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2ocvwckbe.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2dztyxeif.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2xwessygi.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2xfokzebr.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2gdtukntm.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2hhhskipj.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2djqvuwhn.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2zfidjfkv.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2ngirkyts.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2pzgicnmb.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2szmlnqkw.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2gfbuldjt.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2gwzumfwg.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2lmpfahoe.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2vxdglxdh.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2tbvfoqxm.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2tsvsrosp.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xzfjhtux.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2bkqoqxjy.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gtbhzvst.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ueywowax.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hohzwwhs.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2wykzecrp.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dfvjfozt.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2lnaefufn.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2ojvmkequ.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2aihakimv.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2jftkutuw.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2rqbftzdq.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ghpklvuk.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2hydsfgtb.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2dpsplwez.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2lwartkgk.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2qbwfnjug.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2nordcpya.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2emyhxuwd.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2feypvlpn.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2pmgbpnnh.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2lwoyjfeq.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2ynczqihj.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2nwmxtglr.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2xfhgutqv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sywgptcq.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2mmgqcltw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2txvcxyir.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2nibiycif.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2ywklpevt.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2rskffubz.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2vtvqeiko.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2cfqshgvl.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2kmxafysg.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2hzimuwer.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2jgiloweh.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2ediynwci.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2wvoyrkab.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2lniklkos.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2dkfnnuoy.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2vjljigzs.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2hpinmebn.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2rouketip.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2amhshxsz.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2vuhmzwua.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2sfkzwkhs.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2dhzfqbjl.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2ptmeefoj.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2pbjsprsm.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2qeeaakbe.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2mcnenmuc.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2rxwvzops.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2mnqbgmhe.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2zsrixzyt.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2bffvbxbi.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2lmqtgtnj.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2fjlhyzha.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2ewuhiabl.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2ksjospfd.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2snqoedvn.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2xneypfvg.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2itybqppk.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2yxmcrzpc.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2dcdhnbbk.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2frsinrwi.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2lxhgvpxp.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2qfqxykqr.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2egubnvat.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2uwjbbzbz.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2iasnqsid.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2hqvljemp.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fciaqzgd.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2uvbcboyn.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2quaufkax.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2vagviqsl.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2izpkflmk.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2zfbvtkxy.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2xcnzhnaz.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2kaigqixg.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2mlrwhjlv.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2nizrqwzp.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2omzowzjx.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2unchuuft.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2drltnvfx.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2yinzyvhd.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2lknebmpv.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2xhycwapv.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tbpfoawe.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2qoubblht.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2ipvsnuxh.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2byaxxdxh.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qcrocakf.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2rssjwegd.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dszcmoyl.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2lqdvrdtc.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2hmwsmoke.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2fvhsgjia.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ltupvnhz.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2btlzplea.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2nwctkhvq.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2igmueupx.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2vjzvvloq.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2dyvhrxlj.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2ubmnbpuc.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2erpzmtmp.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2plluwyjg.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2jkkehseo.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2feggjwis.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2egpnjvfb.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2zgdhxtkk.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ujrrtvry.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2invnaazn.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2dhkhkjcd.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2miugdpvi.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2haydyzbp.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2dhxxggvz.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2xuyyowyb.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2otaaldom.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ilndgnug.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2hjnzegbu.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2wzbhancu.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2xowivjkf.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2gjoquyzu.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2zdjwmkuv.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2oempujix.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2jkpdlfxw.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2fzxjjsdj.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2oadrvlvo.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2elffghgf.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2aaokmryb.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2mujylylh.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2gmwtyqpm.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2amqjzgud.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2wmbyjaql.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2zrxsfwlu.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2xxqoqfyu.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2pyramanr.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2fainvxro.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2lytlgdqx.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ramvxjgn.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2ucymyziv.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2argvvsfr.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2mlbmxhab.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2onbivwsv.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2pbjkcanj.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2mczrpxze.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2jlltiiou.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2yqsgiplz.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2wvspkppb.html


<!-- 参考信息 -->