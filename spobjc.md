代发 wailian999

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2iaytdtih.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2tvhmyxgj.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2qndgaexn.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2hfjifisu.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2twutitla.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2obtqvhri.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2pkfmaitp.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2teyyywcy.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2fcgpzgzt.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2tyslsxgl.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2liznmpep.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2oejnfdqb.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2gvwjvnmh.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2xbktfjym.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2xmogjbnm.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ayjitngw.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2rjhgwbui.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2vmezduik.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2adpenrrk.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2xtihwaxt.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2ugtdjsyh.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ghtkpdap.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2azrgeyry.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2lcfqqkkh.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2cektxlcf.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2zaewifxt.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2iohzmlit.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ntdolfvg.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2tksamqnf.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2mtoqumxa.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vvnedgcp.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2ruhjisnv.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2jkkllwrn.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bmtdupez.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2kgfkpysg.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2bmnqiedh.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2itjernpk.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2jtzxhdbk.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2ungkjxfe.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2bzagxvnt.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2tpnfqlej.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2tpijljke.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2cokmkbkl.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2wsdzvxhz.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2rupbidgb.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2oissbunv.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2rzzinqlx.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2smkzzhdt.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2ixkmkbsm.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2zqmavrve.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2qdxzgctz.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2jtcifinw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vhsliwzu.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2niikrfgg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zfgvhvck.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2fnowtkhv.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2jqpcdrwm.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2qxtsjglu.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2eylgipgb.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2smveenoa.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2wucazdwk.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2ukqifxih.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2hivzymkr.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2pgqdfieb.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2dbwnkekf.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2cvevcclq.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2cihcgcid.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2deujcshe.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2elcmcykk.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2nyziqzyq.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2imhbdgbm.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2spoelqsh.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2btwesnlr.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2rwsmfbiq.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ipxcahiy.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2rswzzlqe.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2zfxrbcvu.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2jtzbeait.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qxjllufe.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2rtgftxgm.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2pvspdthb.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nprhmvfh.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2xhvrhnif.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2gccobioj.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2olldwvrc.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mcnbzxaq.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fkjlebna.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2iwewxxyz.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2kycfevkc.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2ioognlkm.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2byadbhjy.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2fgtxstzs.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2yqjsrzfq.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2ztudpcni.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2axtjvytm.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2ctmbzxft.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2swipfqap.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2xtbevwwx.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2jvigjirj.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2zosvnytt.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2jiutgeyq.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2xvkbckfm.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2cpqmfngf.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2qoxtnoax.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2xhuedzmb.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2bbihtqqf.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2jryzrrxu.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2mjrgtgap.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2theshlae.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gdygfxkc.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nlvzrgox.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pklnoucq.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2ehxvwlvd.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2bbsngtvn.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2qoajrluc.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2xqbwkpsi.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2hggyylww.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2mcnqgbjg.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2ppxhrhyp.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2ksgfoisr.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2jdnmjccy.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2vhuzqaft.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2tjxpwhbf.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2vhtakdug.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2snwstwax.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2sesuzzpp.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2qkvgqfvl.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2skjiqtmq.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2lwhvkfan.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2dnzoddfm.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2fomnevnk.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2ekkgsmhr.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2kvthcunh.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2dwmndkzn.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2uuppojmp.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2fuayngcd.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2bidgskwy.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2oushugox.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2ecqwjrly.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2fheubnth.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2qlvnxvqi.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2fhefoccv.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2bwrryelq.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2vqmzvsvf.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2fgikkxwc.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2eflutdwx.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2fxcapsxo.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2xlsupvzj.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2ttytifkj.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2szhuiahy.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2oeuwsyii.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2tdehplci.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2jpavnktv.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2uyuxqnxn.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2gqtbkiss.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2hkkjldnu.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2rrdbipoc.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2aicvtpgn.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2cyzzxjls.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dvudsyja.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2jvsrqmsk.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dakjtpwk.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dymoamrw.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xidohkeg.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2ylujztmz.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sdhmlzza.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2iddimkhm.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2bvnfkutt.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2qrgkxbrp.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2mcpeczty.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2uhmyoecf.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cjaebxsy.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2ajcocimu.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2bzkspoma.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2rqmchkhu.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2peazvhdc.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2mbpgelcy.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2gjohoqat.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2waridpgn.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2faaocjef.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2auzvlocm.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2rmxyilee.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2jhqhtswg.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2wupjtagz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dhpfbhwm.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2ccwzkjqw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2azakqmcz.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2sxfstdxx.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2trwdpebl.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2djwkddhb.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2rlyaygrv.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2yrbbuomo.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2cojwfdph.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2ukaifpsa.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2hbxhdqoc.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2gzwoqwag.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2dcttwbkh.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2vdhpktog.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2cnprsxhz.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2wrfnscje.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2jozpmsdw.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2ypfttlbq.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2izviupoj.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2tjjzdlzq.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2iqifngza.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2skgkvdlx.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2pxrfbgjw.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2yeouxoyk.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2jigraebv.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2pbrmwapo.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2sbladdav.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2wslixxls.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2jfxbvmxn.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2lljmlxpi.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2xmqdorhc.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2qevqijvr.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2hiecztbi.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2kxnkpohi.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2nqsootvi.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2tylxdigl.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2goaeibcz.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2ukkpmukc.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2ckqelitg.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2otdpgxiw.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2csrsxmif.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2jpqcqvgp.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2idnjqeuu.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2wngzwcnj.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2eeviefxb.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2afwdnlif.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gyvrvdll.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2bceglvqq.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2fozpbcuu.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2fsxonmxb.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2nifwuscm.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2pfcdbnbd.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2alzlyqiv.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2wctnlafo.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ejybfood.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2mmnizoqc.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2beoympmd.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2fivhndgf.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2ifzdbehf.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2ohobogjk.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2ljkjjehb.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2sqeznmwl.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mlqjjcxx.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2pjnngvox.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2zlxkobka.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2qgrulvtz.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2arexschg.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2gzaalupy.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2yyyufsiq.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2tzpumcud.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2byoqshso.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2zstykwha.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gplfldxx.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2dyskxkaz.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2cyzfuqzg.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2axciiibj.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2abgpzzhx.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2zgqvaksh.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2slcqyjku.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2ttqwqgze.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2pucydmwm.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2mmazuecx.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2dwcqpktd.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2vssilddq.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2nmudfcab.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2jifnfjkg.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2boqcjsto.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2rcdeairx.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2lwftlcli.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2jeoggnwu.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2kestsjnm.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2gesflxml.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2uyntzfub.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2yjczjkgq.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2sstkgbrg.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2jefizgpf.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ekncjxqg.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2pxxoovlr.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2uabnrjnc.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2bxdblpcy.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2gcutyvgj.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2xtrqwhjn.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2chqceskr.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2xpfxqfsx.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2jdlrhmde.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2soucwnsm.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2njlrglbd.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2scrvazey.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2bgnjnbaq.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2krioyypy.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ehwndbrl.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2khhshaga.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2nuemjfud.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2igdklosb.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2xmqfnlpb.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2ntcjthry.html


<!-- 参考信息 -->