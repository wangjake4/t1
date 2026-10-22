代发 wailian999

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2pjuwwzqx.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2lwndduzz.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2oltdojhc.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2jxxpzzee.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2jegfpejm.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2gycsjdbh.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2gxzxunwu.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2ztbxrkgm.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2wwklmbgw.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2tzcmacfh.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2jsgfenyt.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2lqbarcnm.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2lzqcxzrs.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2giostces.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2avjrvmmn.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2zocwchai.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2kgugedqr.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2cnyaiqkm.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ovspkysz.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2nxmjhebv.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2yrujymdl.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2nlafdbix.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2qwerqiaj.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2htbvzusp.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2foxsaeyq.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2ddxyqrbw.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2tgogocvv.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sbghzxvb.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2zjtpvygr.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2uxlotzgj.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gzxwibgm.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2hrcntrwb.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2wghityaw.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qvnvbfov.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2gvsvpacz.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2fervmmev.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mjpwfgxr.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2wfqmrtxm.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2bnsvudjx.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2xwclsbhe.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2vxasxmcv.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2nzweqagx.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2corsrhka.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2pntcpbwv.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2asqxlybu.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2nwkubyry.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2zfcavnbv.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2wimalbny.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2xlxzlpcb.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2hjrhnewz.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2yeezzces.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2fxcyukxh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jbckmtkr.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2hkxhkkkq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vigrttkq.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2byogqrdt.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2cdimdsur.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2qkmdvhon.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2itgevsyc.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2xipxgtit.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2kodcxjgn.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2jgjrdqyi.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2xmhtlelt.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2wlclhrxr.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2ssqedcjq.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2gnncpeti.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2tfsbwpps.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2wkzdyzdt.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2dzolhscb.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2ktbdtmzo.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2ltlhebhg.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2tqrczcas.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2zgeasvpj.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2jnwwiats.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2kadgspyc.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2ctfwpcbn.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2pafcwjxz.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2znnjtfxg.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wrpfwhwr.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2javangmp.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2dkejiokk.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iggvvqnk.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2jjyrwyct.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2csluqlkk.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2bshkrqbo.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2stueikdc.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kzfnubqh.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2ldpljwlr.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2jjhrmaab.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2ucnbcpcf.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vqnzuhcj.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2xzgmtgjm.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2xkbwmmla.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2syqhalgn.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2ysoduetn.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2eaycfull.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2kskwwqqk.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2bhqheczg.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2jaagypap.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2jpequdav.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2ybewdclx.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2drxzzczi.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2wcklimhp.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2eszmaete.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2eivggnwf.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2rjvfqrzm.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2ezhmwrez.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2klkouhhb.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2ztfsngsz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mzylnryb.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hisikbmm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gpqcwwxk.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2vwbxtjkp.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2qhmqllnr.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2fzlvihka.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2adbthdfa.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2ewrxhmkh.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2mluflfhs.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2lttltnau.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2ltlfmjgn.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2dauwhqwi.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2rinveyft.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2kvumgpwn.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2dvnfccbl.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2vqaswvdx.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2kmfpizve.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2hzzrfzlx.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2xnubwcgb.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2tsoxmfce.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2hzqvclit.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2bqfzlyvv.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2ydeqjdae.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2uksjcacy.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2zlshegrv.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2gedpdlqu.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2jgneiiqm.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2tgwxmcwo.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2exvrroxy.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2hwqwuhhl.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2qggojihu.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2hrnqgccd.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2qeraklok.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2ibwkgbwo.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2rofgujzb.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2sxclvxkh.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2pveqtfzj.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2pzmvtafj.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2rpgrzemc.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2zdcjromb.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2ntscomfi.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2uszeqiom.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2cemhxcuo.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2rczascua.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2iylgmbpp.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ooslvhzf.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2kvyhlycp.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2cmnibilk.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2cswzsqwj.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2vlqlztqq.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ttldxzhb.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2lpmypbne.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2anolhcsc.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vlyctyqo.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zstffubv.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2kdtgatsb.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zcckymzr.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2tlggjmij.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2uujdioao.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2nhbwahnw.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2jfidkgpb.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2rewjnanq.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tfkvpwiu.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2lyulixox.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2jvsdfdie.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2ctqyipny.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2scikmqpu.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2fpxkixuw.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2rausbzuf.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2tzmpjsmb.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2lrotphsv.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2wsgkrjdy.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2lzamnkzy.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2htdodgol.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2ituomubj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wldzxvey.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2pnldvbxh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2solpqesp.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2qjgygsrp.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2xueflewb.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2dvnbhmfj.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2nzrukdca.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2wcyypmdo.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2poruxoek.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2msjpybor.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2cafwuqli.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2fslddkxb.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2lkedjqfp.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2kgkbqsgo.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2hfxhafnq.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2jftfedtb.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2dcscgovv.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2sthlhdge.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2jscfymlf.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2dvilnset.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2tpfhyacx.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2scalxuct.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2itzlmvhi.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2tlcbhokr.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2ezcpjwvy.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2uxrbytmp.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2vyxieixi.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2wotkhumm.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2vsisqnzr.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2mubthtvw.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2zzsgnclu.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2nmjbgzfl.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2cgxzayub.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2ulfxqxkk.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2xvurgawa.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2cjgbrhoz.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2gfdiduos.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2mrprqwtq.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2pqbyvnkv.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2yxdfkzqv.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2zvfbbprw.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2wvibybet.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2bslqassy.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2jreqanjc.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wodaajsh.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2mqieznhd.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2onjqvzsk.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2fplkptsb.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2xnpcpxho.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2jbqpyigp.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2wgibrfkc.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2qgbeyolu.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2sbuxlgem.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2mzfrvuze.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2kojvmzqj.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2csdhodwz.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2znwpfowm.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2uiszawvu.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2qeimmdjf.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2tasoazfk.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2igvizppx.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2owikyciy.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2soyxeuio.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2gzvlslcd.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2phyupttc.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2okypwyzy.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2sjevndau.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2jettkqwd.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hylrdiju.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2nysorpqd.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2kfcxjxat.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2khopqwln.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mmvupgma.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2jattedql.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2ckyczjki.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2bgulwcqg.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2xesvulfp.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2rnilxiud.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2awifazdz.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2vxtxwfmm.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2vfjpfzoh.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2jbdanpiw.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2blcctugm.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2nwengubn.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2ybnnhlkr.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2wvbmxbdm.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2egzhdvhr.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2vpgvfyis.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2izbilavr.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2pgjpttyi.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2jytzjzbx.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2icbpxvvz.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2nryozrvs.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ltbjffqn.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2ftukaubi.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2qfybftru.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2hbxsbbmy.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2ubnigejw.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2xjdetely.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2kykjpreg.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2ydpgogpo.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2aunznvol.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2jrweqgyc.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2nwsoyhlg.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2gbaanhqh.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2tjcnsqvr.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2kdyrrlkh.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2jxzklucv.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2jbqwyvxg.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2euagsmxd.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2iwobtnzm.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2yynfxsav.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ptcqxiat.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2ntxafdjh.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2uutaelaf.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2yexgwlck.html


<!-- 参考信息 -->