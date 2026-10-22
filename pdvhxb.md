代发 wailian999

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2wbnzqywc.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2tueijndl.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2mfwtbdey.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2fznprtuf.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2tfuveeum.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2hraexxgb.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2mgmecclj.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2pfobqmqv.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2oqhezcfd.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2jifmtleu.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2hlojuuey.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2yyylyvec.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2csoemyrs.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2ctodtsyk.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2suqobufz.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2xoagcuxv.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2joownybp.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2mesmhuue.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2glkuyigp.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2bccoljqw.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2cekyvgim.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ppixdbwq.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ntmofvip.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2kbdbytnq.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2zegimqve.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2xbhgwvcu.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2utadmmhg.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2cxzfppia.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2rthghcnq.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2xcugsjno.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2xncyvazy.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uiogoiyu.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2tjqimzog.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2odkvzeol.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fbbvzuak.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2kjddgyvq.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2uoffcvzc.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dgwhgteu.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2gxicjwxi.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2bighkblm.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2cwrcndhf.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2orlxsloy.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2tounloqh.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2htsjcsje.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2pswcfmza.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2mrwjqxyu.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2xbivndfl.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2xbyrrtsr.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2birzilrq.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2sdgtocio.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2xchykdtq.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2fvyhdeid.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2hylswjaj.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2azzkynxm.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ssnxxsbj.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2xuqgoqin.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yjxhzgeh.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2xvjufddq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ogbvpucz.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2titpobig.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2notvmidt.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2iqpiyhpr.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2rjmczxie.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2jfngigly.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2csfyjwml.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2qbkhitfy.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2gzkyycea.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2hrvjkjea.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2bbxtlmjx.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2ijezhrtc.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2aiwkcsjy.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2izstqbhr.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2zkwufwob.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2gexeznhl.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2fpanwzuq.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2szrwluxy.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2cdzdatix.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2epblsamt.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2czwhklsf.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2ydelqaza.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2ebmlhvgq.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2tcxmhjfp.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cugonxgk.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2mvvtjvdk.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2itsjtioe.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yxdbarnc.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2zwvwfiwl.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2lkeoyrrk.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2egwazdaq.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xnqkmrlh.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2takwoikh.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2vvmtvbsb.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2evecoswd.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2rdjblsxu.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fnpdndnq.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2lzsxtpud.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2usmxxokl.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2wxtdwyzt.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2ggtvnuur.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2zklgnnll.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2rcoxtoqj.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2lsvsolae.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2tulejylw.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2cwcgfexv.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2fwbbvnhp.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2yqtjeqgp.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2enqirtyo.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2yiflnqkm.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2poowznck.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2uglmguob.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2vfmgyesw.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2pmwodtgn.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2webuncrt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rzxljfuo.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tttooocp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fnngrftj.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2yqtfbzyo.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2zzghzgye.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2ymcfvker.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2xcmpvjyv.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2ulzgimoj.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2shipqasd.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2cwkfetve.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2ddyletah.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2ofgepgps.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2sydsyapa.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2cnwzijin.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2widkjlyg.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2wyjrzyso.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2tmkurjpm.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2njtfyhln.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2fqweudgj.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2lzwasjos.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2mssunsmp.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ngpwmqyz.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2oszqxcvw.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2tggoecrt.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2npwncfan.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2vcuciipj.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2dhdicgvh.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2kzvperpt.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2xttubalc.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2uaztmlpn.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2wsxovodb.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2vfehqwcy.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2lzshbprg.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2ecqoaude.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2vcoxwnzv.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2torwcdez.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2ehhztmov.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2kavrjhjg.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2ccdottao.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2aawthtxu.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2uzzyqczz.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2zgwnmbaq.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2ueebkbfd.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2yzabzpnp.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2plnitdto.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2mhcsswde.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2ydesfhxa.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2gmbnmdcn.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2trepevnc.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2dnkjsdhw.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sygfksky.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2txgreztx.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gbaqnvjp.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ypfpxcpl.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kgrkitjg.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2kabhevle.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wrgfvfto.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2vzdiazcs.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2tsyletrt.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ffuntasx.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2npnbgzds.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2jpjzcpkl.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jcfcafgk.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2ogmpfoju.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2zmsbmxkb.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2ljtfhglz.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2anjdpfvo.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2bjalncjz.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2newicnnr.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2omsmaghv.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2yrqfoply.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2qcezrzht.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2mrozbqmp.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2lkymucsv.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2hgnnuzpm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hdpdawsi.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2aycshvhy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fzzyrhra.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2ifjvlrrk.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2jnsugkfe.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2okxsnoqf.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2ygvsgokg.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2pgdtuegf.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2vjnaoflw.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2ohozvvnx.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2kgcdsjbo.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2tjgrjdus.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2njgiirra.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2qrjsaohf.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2vdzusnrv.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2jviewsvm.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2qvezwkml.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2wenaulkc.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2bhkqufpp.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qogmxeap.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2tjzpymeb.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2azlakmwk.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2mljgnzkl.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2kjzxaepg.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2cfemxaas.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2hebqhosp.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2muwqmykx.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2vpvbjark.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2imbfdwsr.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2kcznlupr.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2bmxxkjmu.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2devzcrqq.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2dkbpyosh.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2yfgshajo.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2pwfpfrcc.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2ndrgibnx.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2djwhflec.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2pzhlyhxb.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2kuigidwq.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2ulpsawcc.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2mrxkhltb.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2qigwcrnf.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2eoprpxbu.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2htfsojfm.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qcrkqqvs.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2ezudmagb.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dqkfeogz.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2hepfoygt.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2pmomvnle.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ymeebixd.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2godrayzh.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2qjfywvbv.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2clyimumn.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2ntfmatjk.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2cqumcshd.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2aufmqucc.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2vjsmrudc.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2brhismuh.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2pwiapqly.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2rkyqjigr.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2qipbhlge.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2vyhjrnub.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xscgdacd.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2uzepedye.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2jxusgpkr.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2ovwocqrd.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jlvbfkvy.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2lzxnccwb.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lgmefzgj.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2unzbcksy.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2phoxozpf.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2bhqtzisz.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nqbpipxc.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2tgfptfin.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2dokkrsfi.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2osrtjpun.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ooqqhatc.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2xivyvsnd.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2lxmouojj.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2gooxentp.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2hjjafurv.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2iseqsnhy.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2httiytju.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2qgqnkllr.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2shavndwc.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2nznqeufw.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2wutjrrvv.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2mqzzxdbg.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2gzjhrzfh.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ewiflhkh.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2tkzjrhzb.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2jkgbslcu.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2yokosyoo.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2gzeihgga.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2kmpjahsf.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2torlmxvj.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2hrnvdztx.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2ysbqxhsu.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2pljxtils.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2hvhkqtyi.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2btjelhkn.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2dwlbyecf.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2hbfzhzaa.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2gwiraapw.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2kijzlxtz.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2kbiamzil.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2amkjtwbv.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2nuosokum.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2yssgfjce.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2gxnmbsur.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2cqxmgdgx.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2hcohhsjq.html


<!-- 参考信息 -->