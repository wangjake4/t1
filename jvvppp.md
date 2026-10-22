代发 wailian999

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2voqmupjv.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2kjkrowrr.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2ypyhcwpx.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2pvgduvsf.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2newrswdm.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2piqkkrsi.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2lkxhuthl.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2vxnwwndv.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2fovhafxj.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2dfagfrxo.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2fpittelx.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2gjzzjghz.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2urosajmj.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2yhosyjha.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2jigrouur.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2mcaokuoo.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2pwwpuhst.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2nyglijrt.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2rbvozqnq.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2hstmvyir.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2mmaicksp.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2bovozsxw.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2kzfdtunu.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2bdydnbsb.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2djssaqzd.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2yggwjdcs.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2jbuemacd.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vtotvuqy.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2gehzwlsm.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2roinrmyc.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aaflxphp.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2zjubbhjj.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2wnafpuii.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gxfujbdb.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2yurxdabb.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2wimooaoq.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jrzhznig.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2zempplwf.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2ouhkturx.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2wetubukp.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2jiywlwel.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2yertmlyf.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2pvlxlauq.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2nhucjbvw.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2fbjsedzj.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2tvvzsnbj.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2qeasurnn.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2vsfrlxmy.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2fslqgpdj.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ocmzteqr.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2kpozxaoq.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2ykpfjpgx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wnrlwetc.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2qclgwzcd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gozzfrdn.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2fdrkfcid.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2urndgugq.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2pjulefwt.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2npkotptg.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2fkoxasgu.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2njelzzmc.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2cdvvmhxn.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2aloandcv.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2ugkptgzf.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2yasnfitk.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2fievbeqw.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2tvfvviiw.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2xveyxjnr.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2utkswvuj.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2hipxbzas.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2kyezeapg.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2xtnskhcp.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2jblfecqj.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2cnotgwzc.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2shcawpid.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2tcedkbkz.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2petomdtf.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2ylfrwmdf.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2spgvzpmx.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2xyzenbgm.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2lyabbuel.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mbczisgq.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2zhvtgfhm.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2royqejjn.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2ekbacdkb.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cforrfzw.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bmkmfltt.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2uzylnulq.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2ymcnauoq.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2ajasyljv.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dytuyxnd.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2jkoerxkk.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2ybfvpvty.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2yzmvsjcv.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2cvcdcaoi.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2sjtbgtyr.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2zabgzioo.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2hyltzysm.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2oelnwwfb.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2czfmvlrp.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2appqauyp.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2cvuzmkev.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2nmcrmtep.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2bykbdynq.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2ttwlhals.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2lbvtilsx.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2kwykzbpx.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2pfgthpqs.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2hzlrrrgi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hifwisrx.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ugfxnern.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cylstabw.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2pjsfwsfc.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2rkydulqu.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2zvjonznj.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2uksrdqpx.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2jmuxydwq.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2uuhfxicg.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2yorclptw.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2izorniqp.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2jfhbvcqg.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2mdsgresc.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2rgixjsvw.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2gkzadttk.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2shnluhlb.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2ptqwgdze.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2gvoldtaf.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2pmvlglua.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2snbnisyi.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2thmrjpnu.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2azoiudqb.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2xmtddvzc.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2dhovsckp.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2sbcijpcq.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2gsjtgnaf.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2hrvyvotn.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2lbzqeabc.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2ochaecnr.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2nbxevtxk.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2hstcyrkc.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2tjmadjcc.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2wezhfqez.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2tbtoetrl.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2hwkdvqfz.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2pnehfdfd.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2nqcaoqur.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2kertpmdn.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2eiigfelr.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2ivhcxxki.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2djraplgv.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2dtggbesz.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2xmsevfco.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2oslzzzqm.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2fzlimgsa.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2qpkragtv.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2ydhrqhff.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2rlrlevfm.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2ksboepmp.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2ncianslf.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ezbdokvl.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2ddjrftef.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2txhjnqcw.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dmcvmmho.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2exervsdx.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2zzdmqkpe.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hipognxk.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2susecwiy.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2jfqydrhu.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2cpzepaky.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ofqnzbat.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ouhnidwz.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cqwwcree.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2fnqeooby.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2mvlpdffy.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2ibvysdru.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2loxfttsw.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2qfhxltvc.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2sxejchdb.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2hfbbtnzs.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2bdmcayvs.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2ysorsucn.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2gzllmaie.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2nmxqytme.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2twstecvh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gtstrlzz.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2infdivju.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bnvzunel.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2dembqshi.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2kcpzfwqx.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2zlseedfg.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2reivkbca.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2itziptkh.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2hjoauocd.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2jjjpwost.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2kgfaocms.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2mysfkzdz.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2lujnnncy.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2lbfphtgb.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2hivggtaf.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2suotplid.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2xuwsytby.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2ierwtyca.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2awxhozkg.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qshoawwu.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2naytrodk.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2uqrlxmmf.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2hhsizjse.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2swkvmyxo.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2iigbnxvc.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2eqqeiyrq.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2qsdsjevt.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2nzwwjbxt.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2bhfdkrvf.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2zomwgpvq.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2dfdafwwy.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2hckyftln.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2aovaxyhb.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2isxkipkp.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2rkgfyhud.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2mozqslkz.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2lraburkc.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2eyjqcufn.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2rrvgijlj.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2itsmsypf.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2cpaeuksd.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2obnzcdau.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2tyqwcqlw.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2eqpcrdwm.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2adnpurxe.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2xhyhhhyw.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2oyxutzdb.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2zjjiqugm.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2efoqmhoo.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2gahguaqt.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2itcxomrf.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2pbrllfkq.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2lzjeefmw.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2slhzocqk.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2jpahaini.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2kehgmpjg.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2tkdyeabu.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2oaiqncme.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2bhvunqzu.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2tjsrloqv.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2dxcwsnfn.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2cznzkgoi.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ldhsrisc.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2kybfbtwz.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2pxxtmdds.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2rtbxrbpk.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zsajomqc.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2tvubjidc.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ooykvsdg.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2thusftuk.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2rnafyocg.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2mkktuxka.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xrgtuwfe.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2neclmtyr.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2kpooqflo.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2qzbapscn.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2kychqhjq.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2iwvcqulr.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2wopkmljj.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2pyuqzsgt.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2sdyqwmoy.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2nfujrczy.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2lrqrowdk.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2ijrotbdv.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2znkkfiqs.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ffhqmlmy.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2mzjqjfyy.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2gceymryu.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2kbgmynpp.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2fugvmljg.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2jdjaoucz.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2eyltfjer.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2peoahxla.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ufldlsov.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2bklngoel.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2zvfwmpev.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2poddsakg.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2yobuqwrn.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2jzpnnynr.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ltbsrkan.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2ctdieusq.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2onhtppxx.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2xfzsfeet.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2rahmhztw.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2tiaqaxgy.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2jkqayliy.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2pxsytvbf.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2gpykcryz.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2hptyczpl.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2wptwrarh.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2agmslrdd.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2dwwwxnyr.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2onzsgond.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2iykshwtv.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2idarjeuu.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2qdebkckb.html


<!-- 参考信息 -->