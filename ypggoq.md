代发 wailian999

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2zsleqngl.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2wpscqzxt.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2oklzxylu.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2badpgrng.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2ytgjsgyu.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2xtllmhok.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2lpmyyxvh.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2obfmazdo.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2pnszlkfz.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2vrdixtuk.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2vxfwgvel.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2ryvodeeb.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2qjekgjct.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2xfoumnmw.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2covfvglx.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2qcvwdksq.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2aewdyujz.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ckgmjweo.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2kttcqgpx.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2cjsavbgz.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2qunfavlz.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2fbtfkaak.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ixbjrihd.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2yrmhyfrr.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2rdugxrom.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2rgnbkueq.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2lszyaszv.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2uogrjlmp.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2isynqnvt.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2nfopwlaa.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2zjifqtzd.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zicilzio.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2brtudrgg.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2gwrpiess.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2odzilogb.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2wcqjjzdj.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2zyxrrdkr.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fpethawx.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2uxeyungq.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2jrkvrnmx.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2uyksgdat.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2cdcjwsrc.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2bccmtyvk.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2icquktji.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2sjsxwnjm.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2axnnvkfq.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2izcjuyyu.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2qfkkggxo.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2lgwqqvqo.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2lvkaxxjx.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2furoupxu.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2dklpjycp.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2zzswvvkr.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ilplbihf.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2smzoeows.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2xcsbbvdz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2btehnrsj.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2qgtkkren.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sxuhsbck.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2yowrqtti.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2qdxoxfvi.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2nqeqjohi.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2jodnhghy.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2gtqnrhnd.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2ajpqlwxf.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2qzzhfmbw.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2ygvfnvfc.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2ldtokqyt.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2irsmwbvl.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2dygwowjh.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2yqxvlkou.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2kcfbbkme.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2xkkpzhnr.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2ntyyxjez.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2uxghisyq.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2pzicgpfu.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2joaufpnk.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2fgriktad.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2lnczvszp.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2uqyzoqya.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2mcvrwhqi.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2dxnjawcj.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wddfhwkc.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2gjouopzk.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2pfikmlob.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kmwsivmy.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2gzevxdko.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2gexxpzcd.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2hvcphgrz.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ojeaedwm.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fsqmckhu.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2qjckhbfx.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2qswkgncp.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2mgmwbjau.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2muyfgpzr.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2zbttiaym.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2pthinziw.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2eeqxmsdi.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2yhoopoud.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2ufiaaalk.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2bzwyrxff.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2vfswcadu.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2xbtojouz.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2dmqksuwj.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2klvccksj.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2mozpjfng.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2snmogwiy.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2zikccgxg.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2njsydxjx.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2dcyaepvt.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2sfhkxvlu.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2ommsiswo.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2vqpqpzpn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vyhcasvs.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2aymtqrmn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2csngdgbe.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2cxntiosf.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2kpahezie.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2cmisxwgg.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2shtnrthb.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2dulngojm.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2zrjrzjiw.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2yqnahujo.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2lrxbeyxp.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2yvsqixvj.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2yaavfysk.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2dibqdbfe.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ggmfotmh.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2lnngsdms.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2xewbcmgr.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2nylonume.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2gpmubjlm.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2lbhyppdb.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2tgkvrjpj.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2tzrkjnhb.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2huowwnfz.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2awmvloul.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2hcjoanxp.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2aaqcwjpm.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2ecneaknn.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2zfvphobi.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2lmtdirnt.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2ephyiubi.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2cdyqinbx.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2lgwdfayr.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2rredcakr.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2iwsfjrrz.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2uzpriwyb.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2lnifjbfk.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2nxhteqvm.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2jwrjsaua.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2mlhypvqa.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2brtqpuib.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2lwyyjlbb.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2cwzxfzea.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2fwdwknmd.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2goplmcid.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2xnneyfqd.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2vgxrgswk.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2geganlei.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2urjivbdh.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2tyrkeoqz.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2lczbeacz.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2implnldx.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2cmpbznqy.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mqixseev.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xokgqzjv.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2umpzpepu.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2muscefbe.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ohsrocnw.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2xwkxalqq.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2izozkrds.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2nqufiayi.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2lpfwmdev.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ysfrtfae.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2otvlnyhr.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2wiqvivnp.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2odmhlyvk.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2sfwbxemc.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2jydeukrh.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2wkoniugn.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2bpmrspke.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2dvtphoma.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2juyxxrcf.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2lvtodsgn.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2yjitnrnc.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2xjyhjvxv.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2rgwrcsae.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ochlckei.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2ijxyqevn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qlxexnnv.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2oayskwyd.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2hsjgnmje.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2iwsxgeit.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2gvjovgly.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2aitcaynk.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2kenjzplg.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2ezjfvqwr.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2cmavchyf.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2elczlkck.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2llyzywpe.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2ekjmwfei.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2ttyluowc.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2gjabydlp.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2urspwpdg.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2fanjxjsz.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2fcyvctko.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2uoxmeazd.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2legmasqi.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2atwcmeow.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2ilnmijwc.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2vqjlmfxh.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2vqntkubr.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2ochxruxo.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2seikymbz.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2dhidiumy.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2dnxqbuik.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2hfmvfnrc.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2dwejfcrx.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2oxdjyqzc.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2mmfxudeu.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2omzoiaqo.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2xzbiftsk.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2xhvoybty.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2csyzbmpb.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2ugjvbwik.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2voofcjgl.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2giqltxep.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2mejxorgl.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2wswpyyvo.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2gqdezlul.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2byuxwzka.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vhdreode.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2hbubynfd.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ppizsotc.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2nczbdgya.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2dvbabngs.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2zjnczmpd.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2veuwdtxc.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2gfenpqru.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2atmlqbuc.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2axhcjrfk.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2rjykqrmc.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2zmbhqejb.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2frvjgkfj.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2wxrkysfi.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2ldfehlts.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2utyfaags.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2vimemsqf.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2kbjgdzvz.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wlkuiomd.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2lbhbfkwr.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2aogiwuni.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2dxsexyoi.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mphbttmr.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2bftrcnhd.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2towerxbm.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2svbdxltz.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2rqmbtnyd.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2kqmivfvq.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jubhrnzp.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2cpsppaoi.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2bujjkura.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2dwbkvvmn.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2xboohxdd.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2leeastgi.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2dzzqpmoo.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2mdfuubfy.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2idheyyaa.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2grioqthj.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2ddywisgu.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2fplkifpb.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2dbzvgcre.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2zrbissvy.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2cnlxbaap.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2vjksmfjn.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ryacspgy.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ldnhfyzu.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2rowuxwzz.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2gjkefjno.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2fixldwyi.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2wyivzdui.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2gyurvnvc.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2iiupygcj.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2jbrnkfmr.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2jjpoquos.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2eycykjzm.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2blgghmxx.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2tvvyegta.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2vtqfanve.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2dlbzlzwf.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2xduffgnn.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2aclcmzhc.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2ajpmkaoh.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2kvrvuzve.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2pnwbkika.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2tbzpxdca.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2gnhtymbw.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2mpvxcasf.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2aawtmbih.html


<!-- 参考信息 -->