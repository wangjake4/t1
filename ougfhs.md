代发 wailian999

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2hdeslhjf.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2bvtmwcua.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2oqtnyley.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2hexnubgh.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2ztobfybc.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2nkssecph.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2txcoozpp.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2emebrmlm.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2rjtsehhg.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2gbnpzmap.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2qomxnhjm.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2xgwholjx.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2nduzxyaa.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2huberxie.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2lbdcggju.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2yijzwwhm.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2vdsplswp.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2synioott.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2ngpspugc.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2eqeamflg.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2yrkojevs.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ifvhclap.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2zhbpviur.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2zglfgblg.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2lzcnwqlz.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ybrnfuqk.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2oinonmxu.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ifpqvtyc.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2vzsfpfhl.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2rbsiyhzg.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2nppefmul.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pkvbdnkh.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2yjbjsgyr.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2zrprorzi.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sjamzvxu.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2swxybnyk.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2jvfwfaro.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gdkwneeg.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2nvgyunax.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2egxkpvhc.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2riabfopq.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2fsbisedj.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2jxrbmpyj.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2jcqchdni.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2vadaxnue.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2cinohqnw.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2xuihyaug.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2dbbzcebl.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2ivwsncrc.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2lvwqdmbq.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2ocyxbzar.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2qxzrkjbs.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2nygwagps.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2vgojzoji.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ohtjddps.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2bxjqnnbl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tpteiurr.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2auhooeac.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qqpciopi.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2ugedpzuw.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2kfoakxvd.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2oqbsutej.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2ylmufrkm.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2cjdlivrz.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2zofxajmr.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2sgfeqszp.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2tpsqjcbn.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2psbliaag.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2lwohymnn.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2hoxdpddz.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2vnlewpcg.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2famfgcue.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2oquwdtkq.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2xarajzkr.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2qwclgreh.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2adnvroqt.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2lbvlmcah.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2odjftmie.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2uilzbood.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2bkcscepy.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2wfqxxlsm.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2fagbdwdw.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ytplpylw.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2lmfnfsll.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2czyvoeia.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dgxoykaa.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2hgicsdis.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2kjqhopug.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2ybagnuep.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2utlfnfsj.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hcnrfzxd.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2ljftkpac.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2wemscvkk.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2xuoznxcn.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nzjpermm.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2cojipebt.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2egzjlxtn.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2lsdiajic.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2yguyklio.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2pcpctpgo.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2urxsnqpx.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2odtovbvm.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2evawrekc.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2mjaqygwu.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2nmexqzre.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2pgxixmvd.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ufomtrcj.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2cbfptuio.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2jbwuxrbf.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2nufmxakd.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2brhltizl.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2xrtnizrv.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2gvhqcsnz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tvlswjzp.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vfmweajf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wguqcapk.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2vljyospf.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2jycnidoh.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2agvvgfgl.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2zglexuvp.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2irzltslb.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2tfhsuvhd.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2ldoztfmw.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2qgujaxkt.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2gutsyesd.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2yqrhnada.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2jihomyit.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2hjlxnawr.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2iwdvqztu.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2uccsmqrg.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2dehctsoy.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2gzlmkfvr.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2glnanndk.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2gobphkun.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2wnruhjhb.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2urdbacjd.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2yortfvnb.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2dionnjbz.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2zvtmznlf.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2vxzajore.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2scgufqce.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2esuwjgux.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2btuobeyn.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2lnajcumy.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2fcyuknnp.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2vjrbpscu.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2rojmbgno.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2jxgmhaow.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2rmuxwmks.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2txszqzex.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2drixidpp.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2jdedbxfx.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2zurzqipe.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2syvddqrl.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2rzcmnwfr.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2cveddsmz.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2cjjksrpt.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2atthwvci.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2fptfwghm.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2ulhevotf.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2apvkvdcz.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2nbjnrxcl.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2vgdsdbbk.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ywsxuemd.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2gnkqvngo.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ektplvgx.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hqbewzek.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vplomaoo.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2gvkipxzl.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fsgeccwt.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2rtxdarkp.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2afqhwalk.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2wufiipde.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2agdjfalf.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2xqweglmv.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mctotyjp.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2gboracyt.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2hwefyvan.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2lzmfycgp.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2dlkutbuz.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2glseggvg.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2lmfapglh.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2gaiedtpa.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2dzztodls.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2jzkueqwe.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2dujstxkx.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2zkfnfpwy.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2hgquwrpf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uwwpomjz.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2ddnpvwyk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2msijlhsp.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2krxdxjbv.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2cxluhvxb.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2gyaopmnn.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2kkwnsdxr.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2wpzelgxl.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2bzvidxde.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2jirunprt.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2yqjxevux.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2aatfogiw.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2wuehkxhe.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2icimmsob.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2pfwdycjl.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2uwnwattt.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2kesqwyox.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2pqxbagku.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2gfzfjcsj.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2uqhsxsew.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2wymmyeew.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2sbfeagyi.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2qhtanorn.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2adicvljr.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2ehatmwok.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2jhfekaus.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2yxsthzyj.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2faleygdh.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2atgneewv.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2rzcoeawb.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2vmaxpdps.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2ctafjyqh.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2lowxtpdv.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2woxhjhhj.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2ryhgyngv.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2curbvstm.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2ejwiwkhv.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2waofxipu.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2oefbzzid.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2zwlhiiip.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2caeaqsmn.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2atcgcdeg.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2cnxkduof.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2jquyplnn.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zeikbwcw.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2nhabnjxy.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2suihnqbd.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2fkewsrxw.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2hnsqjevs.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2pftiyhiw.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2lcjyyrym.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2qdqbowmt.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2pqedzxsv.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2qwkmfspv.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2wdgzgqzq.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2klgslayo.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2xhgvkcic.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2kwxnqqnu.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2owauhqom.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2tyahjlnp.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2xidtovcd.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2gkpilmjt.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nytbnsjm.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2hauhqggv.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2bfbwggyi.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2reptuvfw.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wytygxiy.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2jaqbltsd.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ougdbasc.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2gmmgfwei.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2zpgpynrt.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2yuuzytmx.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rljvwnxa.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2oacfuxtj.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2zrbyfnst.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2azylqhul.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2sqabpbmt.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2uiqcrwpc.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2frwdcjhe.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2opzcfctw.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2qeeltqcw.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2vytkeoqf.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2xwqtbdiw.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2hsvgvyje.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2dlxrvono.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2wctabpvj.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ofcbwset.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2bvihafdm.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2vfkzbgcr.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2buoavfel.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2jlkrqbqc.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2pvrhghhr.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2fajlxwqn.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2gihfgdme.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2vlfmuyxp.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2phoqyhoy.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ofopikry.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2aclhgich.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2dozescbj.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2uhldidag.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2ljcbheak.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2oxwotycq.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2riubgwxs.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2hnuozpyj.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2pvjhjwuk.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2hlcvpisz.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2suznjkmq.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2slcdhdab.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2gyqenbug.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2empwdmxu.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2onkskxon.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2kbapmmov.html


<!-- 参考信息 -->