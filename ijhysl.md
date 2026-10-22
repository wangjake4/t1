代发 wailian999

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2mitibdbi.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2vbhtrbmj.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2yeoydawh.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2xvvdcdjy.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2oymigwwh.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2bbwjqcnm.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2jifonemk.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2kqfrzbsi.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2sjuplmcz.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2uiykxqgk.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2burgusol.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ebdsearn.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2tmieefjg.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2wdqqmggl.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2lpwzdihb.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2uynmmbbc.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2njamqymo.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2oemfnpio.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2lnhwxzsm.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2poveypvs.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2bcxfrwze.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2jobslort.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2fbgqmqfb.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2upehvsvu.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2txlhxenh.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2wwciiaak.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dqrnkhcd.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2pbpzougw.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2giligdaz.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2omnpuesq.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2dpuuhbld.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2tctisgbs.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hzlzziwl.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2wnxttita.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2mpdwdrnu.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2rouvaabu.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2skvqfxkr.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2slifebzh.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2klvyldjo.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2hhggktmi.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2wsjbpmwl.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2yyqyvalo.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2fzjzqjff.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2mgsgzqve.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2arpebbjw.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ugdheivh.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2rzynrqdm.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2cbjfabwr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kvvwuppi.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2vmrcnyjl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sayyjahn.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2cjdfpvrk.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2smpvyaob.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ukfcvmfj.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2iahfdxip.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2cwdximgw.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2ltvvhzhf.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2tobdxnkl.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2rsvbzuwk.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2dlvzssds.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2pokwulic.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2scrzwwjq.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2gekzegrm.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2nharxgvy.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2dfbhkzbo.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2xeasvpml.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2drhgrxul.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2fnkxoycn.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2fimyimvz.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2xvsxbsny.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2dgumadvn.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2qeuzgnqo.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2lvaoqkpz.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2fssqjpqj.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2snsnhldw.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2zxjrxwds.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2vitljkld.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2maaodgwg.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2cjamcocx.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2bdkmkzxn.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2irfylfih.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dxguboin.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wdislqpd.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2eumlofrw.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2nblwyehk.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2gktpbmzb.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ajycbzci.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2wzqxyabh.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2eredwfbq.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2dbyucnch.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2imurhmll.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2mddpjimd.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2ntyxlnws.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2uhlktizj.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2oacgoisx.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2vacaatpr.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2nqwfpqnj.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2agdszlhe.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ddmlpwds.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2immepiie.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2dnrtsysl.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2akokryuo.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2jqjjfjgx.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2mppbulwy.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2rkqalnwz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pojdkdjk.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gippyzha.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2adwdzjtq.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2javpccor.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2bzrytukt.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2ydzjymkn.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2cwssmbox.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2xtntgylw.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2nbhhlxqz.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2lyiwcbfq.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2bjflxjtu.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2bgmcmjyu.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2fckvzkct.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2ismqousr.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2fbceifby.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2xhtdxxgm.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2gzsnzizs.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2gmdqyuje.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2opbtlwcq.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2mkfdtojv.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2yswtuinl.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2zcenqbcg.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2qggzsebc.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2qrdvslhd.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2eeofwiqw.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2leskayyb.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2qanqecgu.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2yfjfamfv.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2omlbnmyf.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2nawqxlnt.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2mzvxgbck.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2vkqlgnao.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2brrmoopj.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2bqbzsvdu.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2cxbuamjv.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2nsgyvkhn.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2hthskwur.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2aezodknl.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2swyilfsz.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2evhwlsdk.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2jhwqtrly.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2yuwsvbir.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2crpbndvd.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2dietkagi.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2qomhygbo.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2zitznxqf.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2znqvswzw.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2mzrztfxq.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2rthjsqqu.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2boehvngp.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hgnvjswp.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2nsvbfgje.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2psmfoqgk.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2spdxhyck.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wkbzrchi.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2slicohwj.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2beclhtqp.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2mpafwreq.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2bmvvzbge.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2pbtfbxto.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2psiyxjkf.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2keweepad.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2sufyzalg.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2rklucapv.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2aeuwxgjr.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2jbalumoi.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2jabqcpie.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2toganugt.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2inpnudpm.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2sbmvryce.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xqganvux.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2qawivbuv.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2olmcddgb.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2vbtjxsio.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2bmemnyka.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tgvdioin.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2qlajgico.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yqtkkneo.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2joeroxls.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2ogkbtttc.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2ldxiznyh.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2ujbfxiqt.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2htknuhcx.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2qdolwyoc.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2xihcxlcr.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2mpghztsj.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2aovcmzwi.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2jdwfmvdr.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2xooswsea.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2afbeosfk.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2yupzznho.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2nnctrpsb.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2iyzjmspc.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2wyfxpsyx.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2egybymfw.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2kervolmx.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2memgffjc.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2utvwsdpo.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2zfwmbtfq.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2upprlkdx.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2uunjnkfi.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2okmwinpw.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2qsfkhkhf.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2amudkmik.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2lkchdkpq.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2wkbvmjhc.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2xmjpiegp.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2xocyqpkh.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2qnaigfwf.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2ggmvcmeb.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2chghpxte.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2nekterzu.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2fvzsmobf.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2urqtpxjg.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2leauttej.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2ogjpqnec.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2sqfqpuwa.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2faaxppqw.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2jpcfiyod.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bpowkzhl.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2smlwakgh.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jslstmhh.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2mpidlsro.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2gscdqvbh.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2tpfilxub.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2xnvbkyvj.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2yfyignud.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2rcatofpw.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2eqadosxd.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2mujefjey.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2azqyowxh.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2pmbvaizu.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ksbuculz.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2shmyaiqj.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2jwsmmbec.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2cqaltsla.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2lhkjaulu.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2opvvfpgx.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2zqbvkmdg.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2lnnajosn.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2ogbqghgd.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fpxsgbsw.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2ydufvdmv.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gtjqpnot.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2bygxkxdk.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2mkerndkc.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2cbqcymlu.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zeodlpsq.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2pntbtajx.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2cssdgzbh.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2bmaurzpg.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2gvdkoino.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2cshrncck.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2eiemvqve.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2jgisdein.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2tugxmwei.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2yxsyosqz.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2ecrgzbru.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2oesewpmc.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2hpoybmhq.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2edcvawbd.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2phmctqac.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2vgdtzrkb.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2yxocggjt.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2wufsizud.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2eppcpcfj.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2rxekqqot.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2uvwnnqcl.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2lgqavbgp.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2ledrhecm.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2mekvtkcw.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2mhzmxbwr.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2vzgtilxd.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2efcarcpe.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2nmmsdevq.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2rsnhfmsv.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2xxzcgvsm.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2exgykile.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2hgkmwuvk.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2bddnzpua.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2ryyzkivg.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2yrczouvl.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2daiesifq.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2wqcnbjqm.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2inzuciwo.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2fspilkav.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2zfxqsevn.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ndyginbt.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2zdaeynwz.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ejsswnlg.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2wcqgixcd.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2lfqmmdje.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2esdyesbb.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2kccgomzd.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2kyldcsvd.html


<!-- 参考信息 -->