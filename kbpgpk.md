代发 wailian999

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2jzywmumj.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2sdeoetks.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2hopqghlt.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2mxdacumr.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2nuvellpc.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2vworkivz.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2akkmapaf.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2dclywmzg.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ekrafjrf.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2kklemsyl.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2hppqutde.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2intdqmed.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2urjnatlx.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2cwuhnyuh.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2wzlymsdp.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2pzmolnia.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2mrxzlgqx.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2holnghrn.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2kykyzbsf.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2fhnmwjfo.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2rraxijzj.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2icqinbvi.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2ehdxltws.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2hdmahfux.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2rsowcdzc.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2lueoyqkr.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2bqmgayfq.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2snzdvpqp.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2pluftzmm.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2yaqhqrul.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2skistlln.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2zhbeapmt.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2zffskgib.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2omzcfumc.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2yrpggwyc.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2bftkimbw.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lzuvzcvi.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2xnpkguqc.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2wnqkvjas.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2wxwgkawq.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2iynvlidb.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2cdjzwdnu.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ppaabvpc.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2qysbbgly.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2xaaddmhr.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2fiidlydw.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2pvgsbkun.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2gcunrywo.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2uafcucdi.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2tnsjunzz.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2qdwiwuaj.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2jadctaat.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zybvrjei.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2abjmmycx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xhwawoln.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2vrcvasws.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2mzwuwbiz.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2jncxipmz.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2inghzwnp.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2ihbagogq.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2febtcwjd.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2hdlbwbom.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2xhldwxwv.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2xoyaybxq.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2qhvvpvwb.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2rlxxsuci.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2nmwbgjay.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2foubweql.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2rmqqgnff.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2zgkyuibo.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2aunwillf.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2zusedpfk.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2zuqgsopn.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2kyqauibn.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2bcdknuut.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2hxjxvqgj.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2bgactnax.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2bsrupcle.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mlmbyowl.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2dcypyelj.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2jmlftonz.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vdxcqjcc.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2ynxwlsxg.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2gxyvdpup.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2nietwfko.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gwovosud.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2duahngtr.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2czazsdib.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2jmkbspya.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2tcxepbox.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2yuzhdmds.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2kgqxsjpg.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2yyhabutk.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2xdoqdpsu.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2ysahfodg.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2wmdmpynl.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2klxzqfco.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2hlrhfuul.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2nwzslxqk.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xmicnhpx.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2yewswasf.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2gbplgeqj.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2kiecsbrm.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2qpzukcbl.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2fvkqueha.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2koykdxdm.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2lmftxlzc.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2muybdsij.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2ytpizqyi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vherpffh.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vhttliqd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ylhzcsxz.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2runsockz.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2njjjewzs.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2wjzhrxoy.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2zqpmvysb.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2hucbwlbv.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2gbvjaifi.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2yzcpqqje.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2choqiiog.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2wfswqlts.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2jrqlxbxn.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2fkjvbgbu.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2kjmrkedu.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2lufoqpeo.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2edyznxsj.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2ebrpxihe.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2cegffxpe.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2tdnumzgc.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2oamgcitr.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2lvbqoczq.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2eigrzlkz.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2qegiaprc.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2iqbvqkmb.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2hkzbplgq.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2bytfgsnz.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2znwqplsz.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2xwfcafdo.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2mwpmdksq.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2qmbfzidf.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2skbukuvt.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2qeymaoks.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2iessxumc.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2fdjeryxe.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2pmhvrivr.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2eckcooqf.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2muglptvr.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2ohfelktp.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2ihwbxhnh.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2ubusmrpl.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2vnvmldgl.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2zxipyvnk.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2vwdbzpld.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2kytdqszq.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2jtohdyph.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2lugdvkki.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2kinokcak.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2hiwsxwjo.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2aghdwdiq.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ohzzgkbt.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2vktwgijd.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kqrswnmm.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zpfwxdof.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rqapbkas.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2ucfzqiqh.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2otniamyg.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2mkbvtemn.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2qvkvzfxz.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2owoclzhh.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2kiotjbls.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ykskfgbx.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zavlddan.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2ukubjfeu.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2mjpxwtmj.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2pnaixxvl.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2urcmpcko.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2fdjffghc.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2gtjgquih.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2zqfudjza.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2svneokfs.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2pqdnahtp.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2pubeetem.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2rnvbfdsu.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2ysgajtgi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2htwbadvs.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2reechwcx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qbsnddzw.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2vqgvallj.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2cclldawx.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2gehsoxut.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2jjwvsyyl.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2ujblqcel.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2efuhvdfm.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2zchuoexn.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2zjdpiplo.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2wltvpove.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2tpajijro.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2tpldsnun.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2rcozeitf.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2fuykcgny.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2xxcmcgdr.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2pskniecg.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2sdhvqima.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2oqxvsnjf.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2epeqvzbu.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2pjwrgdvz.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2kekbkxlb.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2rhzuytzk.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2wjacltac.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2pmmwuoyu.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2gkkvafki.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2sflorkia.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2glpbreuu.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2nnpwdlmw.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2aahmlbga.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2nhzvekgv.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2hmaqhkzk.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2poukdtvc.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2kujxyyvh.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2icfrndmj.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2ptgbszhh.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2mkxphkfg.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2tigaymky.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2kdnrbtmo.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2qsxszlse.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2zhifcbkf.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2wydtgvyw.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2sjqlaxvd.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ilcwjfko.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2tgliamow.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2epjxayvj.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2wifxmsyi.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2wmjaahbh.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2yzkqpldh.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2rhvfxaal.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2dzkzuqgq.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2wzeizhge.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2hktsxzou.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2tojofmwa.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2gimqiuna.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2xoqthtgu.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2stupymjn.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2fzsveiml.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2xwqlhrjy.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2naqreatn.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2qyrwcghe.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tckoqbvg.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2haawofgd.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2wysqcmro.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2drodjajn.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2txzhxpby.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2oivkpfhi.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fxhdkjfy.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2ibpqppmd.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2yyaufcjp.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2cklvtgyz.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2esjuqidh.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2hepgwegt.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2mbrrgjca.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2oyiybatv.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2xmdyyxqc.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2qoljqbak.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2iucylhiw.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2xhdpmjys.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2alhrwlaz.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2xcfqhvel.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2sbjijisp.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2fofbmjwz.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2jsdhwcrp.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2qqicryen.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2lkvtdyvz.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2nepiuvdk.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2iatfbjaa.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2wotgcorh.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2kjlqjloj.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2caehjlbs.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2xdmaniin.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2xgvalemz.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2ylrktlwd.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2pvuinaan.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2pfjbvrnz.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2qzljcjoh.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2zhycyzom.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2fbobiylr.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2fnegmvfa.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2alzqnrba.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ntqxgqdd.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2qpkgahtt.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2xoavcevz.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2gaefioas.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2iyjrkerd.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2ojzhiarx.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2migfaeuf.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2pxbefmft.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2nslewtvr.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2ufosxbbs.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2xskugjjr.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2skfrrqzj.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2remcppph.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2fyeauozd.html


<!-- 参考信息 -->