代发 wailian999

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2xwoyhggw.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2tgzdttcv.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2wxdkxyvm.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ltwmvnct.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2kwvhzmit.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2xuroyoqc.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2ytxjuwff.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2afikfnhw.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2cljnbhcy.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2xoafbcco.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2acmmptts.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ztdmwshb.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2pnzpbsrx.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2xxthkafc.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2ihhadyiz.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2szkwnuun.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2oiwsmkfe.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2accguery.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2dkltumxq.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lsmkvxzp.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2cfcleiew.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2dywxdlwp.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yiulmpkg.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2cfwiibnq.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2yyvkttgt.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xilgohbd.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2fwixheyd.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2lluylrtg.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ctofqajm.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2ppeeivti.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2hfgllbyh.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2djsbacmn.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2cjnvcjof.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2ptrwyrlo.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2alvujbea.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2fvvgmtxm.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2ygcawszt.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2ippzjotf.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2esgmcizq.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2aldiqtja.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2ppfttmdy.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2einnmqwt.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2tjgeidak.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2vjdrblep.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2syohgmiu.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2lfrbqwgs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ubusyaxm.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2rijgmntz.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2izreurie.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2jxytqrlv.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2qsvwoxuq.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2bdvriqut.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2sqorekac.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2pdpnmmxv.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2rdyyzvie.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2bycjfxtk.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2vdtvxkjk.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2uzzecklp.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2peozjgzf.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2ptyyojkt.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2oadorodj.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2pklykbim.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2ewpnlfrf.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2ygbzfscv.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2sggxyjwg.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2drdgmtdh.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2eiwxerce.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2lztjfusw.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2dpkvaccj.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2recobqoz.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2djwljjlp.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2lzebgjnr.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2cqkgbopd.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ztkiwvpe.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2txrjohyp.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2zqcxcbzx.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2yoyhtuky.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2voqszzly.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2awyqrigp.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2mzllcyev.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2eoynerma.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2djmbaefv.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ssmxiuzz.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2czlwzizw.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2kzyngjuc.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2ayfpjrte.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2tujqpwyp.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2aplzzgvj.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2arpcfpyc.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2qswviidz.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2zzsshsrh.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2mwyvmsjh.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2fomqxywq.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2phbcthgd.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2dfklpxto.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2qplqxmlw.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2pixektqa.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2czzjpodx.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2tpzzixyi.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2ljrfgphi.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2dgnymxpn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pallbqqk.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2foaqswqy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cnopltmk.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2yryyrjkt.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2gxppxrhj.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2chyojtpq.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2owhjhlha.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2gvsjmihw.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2smswgnck.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2owduvbmo.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2snbvrkif.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2ycqbfvvc.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2tqzfopyq.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2mjpviyod.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2jgvzynsh.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2ongippsj.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2traklamp.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2ddsvtwph.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2flouvfzu.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2wbhbyevu.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2hbirdtvj.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2utymvlnq.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2guburxet.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2bmupcdeg.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2jlhheyuz.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2qtuhmzzz.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2bkvynqfw.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2lswcitdf.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2zymjlxtb.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2lckeudwp.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2dgnnnkzj.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2ajtmvmci.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2jsnpxari.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2utlflziz.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2auezzvvp.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2eilcfohs.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2hsztiklq.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2xzywemzc.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2jhyjmlhd.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2emdvuusy.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2idgnqwfa.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2iwsjytdd.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2ydauiqsh.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2oklgjvos.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2vjbxlzxq.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2zmjrnyyg.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2napnkwpf.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2fsycfyhf.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2fynrbftd.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2xfxxdsqb.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xqkpynyj.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2nuguatvt.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lanncdaq.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ovmonfhu.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tdjnmbxd.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2gghpalec.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mbbjaavi.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2uqiiwnhq.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2paulrnsl.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2otjjsryd.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2pcujdvfh.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2scxpghzs.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ywjbqbja.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2udxgfnfj.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2hjadjbpo.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2pqfvgqpx.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2ohluezok.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2izpotibw.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2dutqkgha.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2nfpjajfg.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2cjylzzww.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2frbsdmhn.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2hquuubxv.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2djzjszmf.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2vppyginr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tckbgpgi.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2butlbnrg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dhnkqwea.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2rqaxhltl.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2lxoepjgd.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2qttagukx.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2haghemio.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2ogncrwtg.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2zhwkbroh.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2lxmmikoq.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2wspimzxu.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2heosoyzd.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2istexole.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2mzmxnnxu.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2eacsruxh.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2pqfweniu.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2hocbcood.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2qldiofdf.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2mguzxkcu.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ofiyreqr.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2vktpzwhf.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2cgmerwzf.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2smdytgnu.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2mraxxxfl.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2hwrxyspv.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2krhgotej.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ikdtsxlz.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2sqfdmxhz.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2ahovsrvw.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2enzeprsz.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2gllabume.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2elmjsiln.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2hvolzhgi.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2utzgohzw.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2zsdyobej.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2vgaaphpl.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2acgxtrsi.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2ivymabfm.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2tqirzsky.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2lwqthlzg.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2eleuaayj.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2uukyhdvq.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2kmjdzpfv.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2qwqukiet.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xkimpnqm.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2krrfndnd.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nqcnyqfg.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2cstbugne.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2zgjmjcjs.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2pegjvxvs.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2lypxknpu.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ylrobhwy.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2dkttdqmc.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2lgjfreli.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2prlfecbv.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2ufwgjhbl.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2ohstqhqu.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2itvyrqda.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2mmkutcjl.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2bpwshouf.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2blvvysgq.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2wuqovbmt.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ltmkcxgh.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2ccavjbzw.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2nrjkldow.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2hksnoykz.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2oacpjokj.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2zrwihhtx.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hwqwqcbd.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2dxjkpbaq.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2fbeolfzh.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2uzceokvv.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hnmutfds.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2eptpxxjt.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2vukdnypc.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2cxdpcgof.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2wuncczpy.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2nbsxfdby.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2xehllmlm.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2jrauyygc.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2uwcqnotr.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2ksxhqbem.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2ganelcun.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2vgveudwp.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2evvlzphp.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2xafqxdtf.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ymvlblai.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2kybhrhru.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2sbxdzzcu.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2cuprfpsu.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2efxfbadx.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2wwpwhcui.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2qcjacqba.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2xpiymwcm.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2keslbccq.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2rdjwidzx.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2tnmbkvgw.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2mbtqtjyk.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2qfuwpcaw.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2egixegbk.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2wbdwyqlx.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2tcndjvix.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2vyjbnaex.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2sexptfqd.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2bmszbpze.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2wgakinrg.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2tlxeoysd.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2mzycyred.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2gxgpivly.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2wgdpmsjb.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2jwkxjqbg.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2ektgmetm.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2qmbbhzun.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2wclqcrmb.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2jkkskkds.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2ybnflqbu.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2bwqxhckv.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2qemyepus.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2ichsousv.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2nzbxezrz.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2hmqldpnk.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2wbtpmekd.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2dqikmbxq.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2rgavhhxj.html


<!-- 参考信息 -->