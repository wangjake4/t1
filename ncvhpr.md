代发 wailian999

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2eqtlepam.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2rmqzdxqz.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2jhflzxpa.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2dzigxewl.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2xvbrnaze.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2vchzqcwa.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2yjesycgb.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2gajbonam.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2jacmhmok.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2lbgrorih.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2fnoatlvv.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2ekimzdyn.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2dlxvlore.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2busmnlbs.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2mqfmdpwk.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2nmsogkjg.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2znewdbfn.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2wuapcdow.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2vgbhxprg.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2proouefz.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2sctrthoc.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2dklhuxds.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2bcayxcbd.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2jududdrg.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2lelipjgs.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2asdkfolj.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2tytvbfai.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2srnsoxoa.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2ukkrpniv.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2guojddjq.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2ogvrdccw.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2flyfajpu.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2yoipftdd.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2opyrpbxr.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wchjdvfj.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2qnietdgv.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2dvpnwawm.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2blpanxov.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2hmeweity.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2ofazmbgt.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rejmebio.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2twptqyog.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2zeeypyvs.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2aizrgrtt.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ttsnhybv.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2znmxhcfa.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2esuocrwb.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2zoaiugpi.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2dkhmjpvq.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2tjfdewex.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2hetnvmtd.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2togsumln.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2anaxbntm.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2xeeaklcs.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2licdznym.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2yysbivym.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yueyfneg.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2mhopkzwp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dejnljcr.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2smzcfeax.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2vnfdaytd.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2qhvnmzdr.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2huiwenap.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2gadhifti.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2lqqnkfab.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2muyjiqyk.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2swcdqdot.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2lsoqwvfu.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2xdqnjnry.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2zsprorpx.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2mxdrdtfq.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2vrdiiaft.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2wleusvqa.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2mjelvkma.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2fomjugfm.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2mezofxwf.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2tobtphhp.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2zbcornxk.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2dgsfncon.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2rqokkfwo.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2lrqxytzd.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2txzaioeg.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kedcudwm.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2fabwhjnn.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2afoedleh.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wpizuwwk.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2tkyhnxho.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2vvoqlyta.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2ffpvblsr.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vbixpgsn.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dysexhnh.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2zrkhyvts.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2catqipjb.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2hkvnnlro.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gcblosbf.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2yedijdsq.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2irrokyfh.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2vdpwhbcb.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2fztfkewo.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2yibvzffz.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2gkteyzak.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2vcsmmnlk.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2sbbpmmli.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xsqsioju.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2moydhoiv.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2hpgwzsrj.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2xawugitr.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2pubkwqkz.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2vhoagdsk.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2pamhkzgb.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2nqknzlsf.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2xqonnicf.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2jgwuwngr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pfdkilaz.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zvdxhjjn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tadtzqrv.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2ddwsbjcb.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2eyqmbbcg.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2mjcibauk.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2fmwxmbsj.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2gtxfdeal.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2irxxmfvs.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2ahgczafc.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2jzhhdxkh.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2cjaoirsk.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2wklqdzyy.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2ihvgyxuq.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2igoilbds.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2fffyxyds.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2gqgfbxfl.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2asoxrnbg.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2locfzgci.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2fiohomwo.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2urwxmpvj.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ltcyrjfq.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2swafbbwa.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2isqbyvbw.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2fcahszon.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2opwyqbdc.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2lsjfisps.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2cjwzscnf.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2gpdnblya.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2ldxhdkee.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2uxlpqfkz.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2ayjsfrel.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2mddjgwta.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2yxbeehtg.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2xcfjzayj.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2ovtkfust.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2vehqnmff.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2ataxwsnu.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2kvxylqei.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2nrflcefc.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2lrfnyfeh.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2dinylifg.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2odxcdtay.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2bwoglcsa.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2aaqqvtvn.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2omlmvyxu.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2kpjvkbou.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2gzanzwsm.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2zycccxfi.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2etfabjhh.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kldurhpj.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2imvuyihi.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vyfvzjeq.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ftoeyzja.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gkmrgupi.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2hwqduwhi.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ttbfbujv.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2piaxlyju.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2vhwgondi.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ebywyitr.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2fmsbdlxa.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2zailnhtq.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2djobqyya.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2khskkcvj.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2hztijfzl.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2menlbnls.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2exoddols.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2vspucfbv.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2gafslweo.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2oeynfjya.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2tzpqbvcy.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2saffsvmf.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2mnacxmib.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2swgtuxxd.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2aqfifoab.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2keyjmotn.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2gzrhisma.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2siepvven.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2xfwrkhwo.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2ktioelnc.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2wukftnal.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2dbshpkog.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2yxzoovom.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2gxxyoblw.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2gjpezjzh.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2hdvgfsse.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2hvythpra.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2umgutxcl.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2jcbkdvcj.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2vpqzyrjr.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2tsbqabmg.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2oexslmgj.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2rdwzeljf.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2hnocmetu.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2unnzgnbf.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2mbqsmgrn.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2cnlynflf.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2zyuqfsha.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2yorqgsjp.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2embikczn.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2avxtuxpz.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2nchmzbqj.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2eidioaok.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2blplyeus.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2hlavlclb.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2bviwjsft.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2yuoxycuu.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2ergsnpyt.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2fqzpettw.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2ntmhvzfk.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2xwjwmvkr.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2dwittrxd.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2fvwoeksh.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2jkqkbmks.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2ugnftxbg.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2ykyutkcp.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2qmxkybnh.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2yvldyide.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2xznagdoj.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qocsneut.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2aetkomhd.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jskpysxp.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2einbfjsw.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2qqlpqeyl.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2mdzdkgie.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2usyvzbov.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2qwjvspke.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2jtfthjlb.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2bpthuzqo.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2nrvnmkxl.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2ojpfqnms.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2ckeylbtt.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2emwapzvc.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2gnisyfcx.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2yxqczsnx.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2lnijqqmm.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2yxrirlun.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kkrlvfhw.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2zxrlzgzw.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2gjcqyjll.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2lfedizor.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pxzdouie.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2gtfptwvx.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wgabvukw.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2qdcatucd.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2upwszmts.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2anvvguoo.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vicqsglc.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2qobgzcjy.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2fwquiytb.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2bguhelsx.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2xggfuvyl.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2wdwfrmlv.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2eukteaei.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2rcrefblt.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2hmllenez.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2rmsgtyaz.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2ekotzrif.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2bjgrrqig.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2udkgfjwt.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2uaqbydgs.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2cupkzcrf.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2jumvtzsh.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2bfdzgjtz.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2nbbnclpu.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ifmpleqp.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2glotreie.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2uzmbhtss.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2iynfgcyo.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2opvetdrh.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2rboyfluz.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2qufhfrpc.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2kheoppbn.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2rzcimciz.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2lmllzujy.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2olrznpyf.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2rkitfefj.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2flpdkbzj.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2otqooeiv.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2uliaubec.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2ofkewgmd.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2zwvzszat.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2ddndvbfg.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ykpatjfb.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2iffrohdp.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2agwpcgwx.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2jevsrymw.html


<!-- 参考信息 -->