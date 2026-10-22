代发 wailian999

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ygodmrft.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2urzzgqyf.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2ribbkfjy.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2urhbwjfs.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2hwbrjuja.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2emmspfcz.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2wctnuzwg.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ckoljgll.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2bjmkxznp.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ssfyoeox.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2jajreiyl.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2giinapyq.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2rjesbveq.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2mlwefeml.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2yvvqrflz.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2anrtfrsp.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2uxfmuwct.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2ibrojfzx.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cnlfdsbu.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2alyupkmq.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2ncagaxqz.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ilyyzqic.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2oczpbozd.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2rmxnotgw.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2yammqeum.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2ppfkizjx.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2rljdsoul.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2iqhksycz.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2azhogcfr.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2hxoylbfv.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2sqytlesq.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2ihpyhkjn.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2qiaysfup.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2bwvgoxrn.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2pucwkpte.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2iichxdje.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2rccvzmbg.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2hhzvoeue.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ymivbbvh.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2chihgrwb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pghimgea.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2soyohyks.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ftxwxayu.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2ildctgye.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2weaootbs.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2wmysnwud.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2updinhwa.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2plflydbv.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2fwnxybgd.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2pobsbofl.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2fqczurcn.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2tunbvsgq.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2avjqbapx.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2znnzzjsg.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2heixhukd.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2ncesgkkb.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2cxynnmee.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2ubmvevli.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2djprvezy.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2pmaerkss.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2xxrfxqbw.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2ywwmspmx.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2cmtzyytj.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2qrvkiwvp.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2cchzwszs.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2aexnopzo.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kdmawlpb.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2aaaizzrs.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2txnrnsal.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qrjqxtcw.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2mmhhbbgf.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2thbvaqpj.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2qrsssyne.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wjqrsxhn.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ieoxoeun.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2lvyaehml.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2ikaahsjg.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2dpvvvphv.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hkiyuvrl.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2dnahsntx.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2dyosjhei.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2rwrqjjis.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2beepujnc.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2xxgdoxdw.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2fxefrtlc.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2rremgfdq.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2mpxjglbx.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ncgklrxc.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2dcvortfb.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2xvbphijk.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2orzvlyxa.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2niayurye.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2wxkxgziv.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2upwrhtxa.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2kqpmysqz.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2qatdhtln.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2ehnpglux.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2teizowfu.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ndhqfqyy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gkrwcggd.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2uvcbpcsy.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2sdxvtooi.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2nntejqon.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2gsoegzbf.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2qjrgvxuf.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2pebqzjfr.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2orgieeze.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2jxmhzyxs.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2qaeczmoz.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2tleulkcn.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2mbajahoa.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2izhhxlag.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2eexwvbsf.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2veizepql.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2eqrgphzd.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2qupyinta.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2rczhjmvu.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2hyuyxrzi.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2azrwtjlj.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2dttgtioz.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2wbwaifnk.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2ngwcbgeg.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2sgzpdtza.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2fvwchutf.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2kpzgzsnm.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2fpcanjmf.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2iqnvyydp.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2kxlvnopc.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2lklwguhw.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2uhsopxuf.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2ertchdsi.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2mmlprfzs.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2tdllhcoz.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2lvsepitj.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2hvoxqvji.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2zwxbypix.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2micjjdmb.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2mmrlevok.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2pdulsghp.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2ltrwcdma.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2mkweamys.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2wvhpsnbr.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2btuavqzw.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2bqvpgppv.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2phjeoliz.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2lgmstkas.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2bwqpontv.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2umgvzphm.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2jcpmcjtm.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wugnjpvm.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vhauslcg.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mceaedvh.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2gyhriedk.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vnvcjyro.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2jxwuzkrk.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2erdgsfgt.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2rdvzffox.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2snmbqupq.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2kgvhqwbd.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2doqrfviu.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2cusdyvyb.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2jwegjobi.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2nehxfnzh.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2mbhfvhwp.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2oojrhxvw.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2swvgodtt.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2dhfrjtye.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2gnpdqrzr.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2qltbdepz.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2cprsqcij.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2lcyfzxbd.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2bcnodwyw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qqalslgp.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2ttkqbzxr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qeouiyrc.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2gssxmzba.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2wlwrsntg.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2idfzqrzo.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2kcowktxo.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2idxwvtuo.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2npapuysh.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2cddzjxnw.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2mifmxhtx.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2lhzjzdjg.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2ofgbieol.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2amjwcatn.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2inmjyysi.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2pxdijvch.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2jowlylfq.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2ywaralxr.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2resqfdoq.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2umkmygaz.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2dzlgbsrr.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2kmapjxon.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2fppmstgh.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2xjfeeffd.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2rsatemnw.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2xhtfbgfb.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ukioosot.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2wfsozfuo.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2jrsbnqzo.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2lehfoust.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2skifkfmb.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2xbvpqsxp.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2vijytxqo.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2klkdnwmd.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2ioobnarq.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2cpmgywbx.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2rnoecoyi.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2fhziufzf.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2sitksrnh.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2odlzswui.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2othkqulo.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2fptthrcw.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2rhoombdk.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2inizfidg.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vdvotlih.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2vgblozlq.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hvdohvco.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2midloqiv.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2eudjzpjo.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2xneidmrc.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2aoggplyb.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2xoazwzkk.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2ayblahwj.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2kqtimwib.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2jgveribi.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2ncyumnml.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2idgifyvi.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2pyrxmnhf.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2xzcnjpll.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2khgnrust.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2gzsnadcy.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2uusrhvwy.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2cnvvzfyj.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2hahznwbw.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2veoxvdji.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2rekkvgui.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xpvncafh.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2cnhnujfc.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2yazelhle.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2djlbjrlf.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2xokidsnn.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2uvendjfd.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2upidmvbg.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2cxxogaoc.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2ttozqpef.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2cmmtthvv.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2utkxnnms.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2yppbwswv.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2hdnponsj.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2ubgevutv.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2djgypjtb.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2nnhlfbuo.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2vgukynod.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2yhcgypym.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2wjspcdpq.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ihopoyju.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2yhofhuda.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2zqxcgkoh.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2fjizkqzz.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2sdylitdt.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2dmtgiylc.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ysjcqbsn.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2bexgwzno.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ozgslywh.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2tvyjgsjg.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2agqrqltc.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2jqiesulc.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2swdlwgrk.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2tixvbnzv.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2dckswuap.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2eusfgoiz.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2mitkhpnl.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2fnsptiji.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2abvaqcwl.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2kldioxfb.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2bwqemydm.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2qznvjyao.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2zmbotxpn.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ksadbphf.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2zthrcubr.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2kcwylfef.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2wmrtkuta.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2xjwnkssh.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2zcigwgab.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2nkfgtdng.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2bxjcggwu.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2tgxxlltc.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2srslngqr.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2lgwtjziz.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2yvualzmo.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2rwlrflfc.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2jcadeucq.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2nenkgare.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2shqdfyaz.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2akogfapz.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2liypuaew.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2zdmeysyv.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2hxlkinmu.html


<!-- 参考信息 -->