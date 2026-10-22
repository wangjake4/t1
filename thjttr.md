代发 wailian999

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2cxkkgzot.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2plituypn.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2keokacio.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2zqyuokkl.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2dwfvcamy.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2atyszdvx.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2bpmvhsij.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2qnhgfqen.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2fkxuiquc.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2xuuezelc.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2mywdziop.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2keokqjox.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2cxcmjslh.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2vlvzmwhy.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2wlnyohgn.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2isnzvdow.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2xdfvctix.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2gforreme.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2tiehpydy.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2sshhfiqn.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2ekzmwvuo.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2anjbprzm.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2exbvbeqa.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ijherdde.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2gncncmcp.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2srrsmnjg.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2drgxifgc.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rhebuwrb.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2vxsrrgsw.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2anwajntr.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kxgnnxrw.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2bmumgatz.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2lyfplhgv.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ightsdpr.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2evvbszyi.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2ycqlbyjc.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2owjmwobc.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2eftsoyvf.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2kyjpllyv.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2bdtebhep.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2mihggkmd.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2dyoyvbsr.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2orwdjalw.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2kigehwtl.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2peyltalq.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2gmurcbaz.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2uxqojqnu.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2ststxgzm.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2flvvyyaz.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2xuxbketo.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2qnrfvffr.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2ssljvbnt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cyoykisd.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2updwgixv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tevvdcag.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2dlfsooec.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2vuibluua.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2jyxgturg.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2efbnjong.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2ogyjknwc.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2sbbzfmnz.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2phxpmvlz.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2eowqohte.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2zhepacxn.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2lgepmfzt.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2bfydqhcn.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2qesqekpg.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2tpuowctv.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2obpoppfs.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2oabnglre.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2aezrtqfl.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2npqoghgl.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2atvdnbku.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2ozpjrqot.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2supyzpyy.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2vzycrodo.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2sxamxfip.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2ytpajyot.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jvgjiwun.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2hcoffqys.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2zgcexbhg.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dulvwvrz.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2jxkkirsg.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2cknqawqx.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2ttgntuqi.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2menpsiti.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jacowtpe.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2goiirnju.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2rmufpfpy.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2jkjtvcrr.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gsftbhyv.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2ifqwhyde.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2moeqadzo.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2uvqokeem.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2qetwlemu.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2mwfbveij.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2skoegsyx.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2tdnyirbw.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2jbmkhfix.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2diettddn.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2ngjuvjwl.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2brlfkdgf.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2fnxlkvfi.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2kfnnebfg.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2nowejlat.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2dmfqueok.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2gescyjbk.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2jvbijlgz.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2yvnwgeol.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ashinxgk.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zvrmzwym.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dnnkzbqk.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2svjswasf.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2udtgnhsy.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2rsvpjiey.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2jjpkjqsd.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2pkqyipdy.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2pbdhngiz.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2yngjtyps.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2somkpbmo.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2efblqube.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2viuudsjb.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2orqweuaq.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2wzpqpdov.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2cbqhxvrk.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2wvaefenp.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2tjgdvfpr.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2swxstzbi.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2iqfbwhny.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2zhkebych.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ggdwcxjb.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2hiuhshii.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2ifasujyd.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2rbljzeoy.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2ixwthaee.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2yedhffle.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2pfifunnu.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2zygdyqnp.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2nedpigpz.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2aefcrxag.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2jxzflspk.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2hixsycty.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2natowgpa.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2gjhwncyf.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2sasyakcz.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2whdrpsil.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2gxfkcicz.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2yuumztfv.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2njrmndgc.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2stshjlzf.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2aggczeit.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2hdelqrzc.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2jubfxrhi.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2seqspais.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2trwntajo.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2bnfbauvb.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2qcgytkgj.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2sxivnrid.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2fcupkmch.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mfphbfxx.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2zvbwfzmr.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cousodoe.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uydetufi.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rglikket.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2urgouzjc.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2exthuetn.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2kbyukhou.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2qcngxeyh.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ffqcnpfj.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2gtatsivu.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2sjgsuwxp.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wqxkvuux.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2gzjtgidz.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2plyidghl.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2zxuatcso.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2ekilklnt.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2sslifzit.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2gqislvnv.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2nuwcfztz.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2pquhoxbf.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2rwkfbmfg.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2kbinqiuk.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2qvxhswbc.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2obnphkpz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2aikvzyea.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2tupihyva.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2krilahsb.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2jlpolxpg.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2exqjytca.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2nzmdyqkt.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2rymvzezg.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2vucedfqw.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2rxkewmts.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2oxkbbphq.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2feotzhnv.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2wqkwbris.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2nyubfgqd.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2elsodghd.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2uczqmszj.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2nggeffup.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2fdhsdmxf.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2fjrsenys.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2acgxrxzu.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2klnbnfsz.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2gyipciyp.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2rcvwhoge.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2sjuzedpq.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2pbaygojz.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2eovqtlxo.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2wqfpcccl.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2qgkhrxqg.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2wdxuaawy.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2rokxauez.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2unokknvs.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2zmcrknwa.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2cbxsjepj.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2qyrafmxx.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2tckzzpfs.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2sfkpuuzt.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2imirwikn.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2kdyolfiv.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2ffzcocro.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2tbwxtjpi.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2rvvevewc.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2tvqhvlpt.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2epsritfn.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2jybjfqfd.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2hbmmhpoo.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2sbifvqhk.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2mudkzzmi.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2duhsacgc.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2jqtknhkh.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2marybvlq.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2rgmyhaxe.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2lwwkwijj.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2dyprpyog.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2gtjmljfm.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2xxvgaidw.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2sifzlrvr.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2umbuzgxg.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2ywwknzhm.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2wswzqiiv.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2zoimhirr.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2tfamwqje.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2trmenbvk.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2miuoloch.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2akxhkxiw.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2bfctzdcf.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2ewyeyevb.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2zawoxwsg.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rfyydibz.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2hkweyhau.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2enogklyt.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2smrsjyxn.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2lhkwbcoc.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2tterzbvg.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jhkjzxtp.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2glakwuzn.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2ckxmpeij.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2gfohoruc.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2fpazkttm.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2gojtrcea.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2ygzfedzb.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2kvtrxnlr.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2qsyxmeny.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2qqqzljeh.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2kbspisqa.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2hikzvkym.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2hprbbcow.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2vqvfbali.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2osnpmmuo.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2lzrygcyp.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2dztgyvjp.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ycbdemyo.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2rwuknrvp.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ckbeeugl.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2urrceobo.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2hzfnyozf.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2yhpcbwni.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2uyyssesq.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2phpgsoaa.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2rofgpokz.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2onmdyrzm.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2qhhxwged.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2hfmzmvda.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2gflnvzmq.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2yfqacbtt.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2yhqjdlgw.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2bincodiw.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2eroypjzr.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2wyzzpyqo.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2eduhfcpx.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2pgeqnhin.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2kuentnvc.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2vtcofpjs.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2qulaippe.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2hvgqhcns.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2ucgmzoqt.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2xftfnsmf.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2lawcqgmr.html


<!-- 参考信息 -->