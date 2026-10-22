代发 wailian999

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2czuslbka.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2tezpwsiu.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2cwssioay.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2dhxglcmj.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2ylqcuuqb.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2aeubnshb.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2nplhfzpf.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2xiogyieu.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2ycnfqunq.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2avvsssmm.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2vihnlmca.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2tkwtxhkd.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2beuwvxoc.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2dyokprbh.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2gkivuucg.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2zmzxxaqs.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2vewlrwpx.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2uervoflf.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2nfkhbxct.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2tliyoofg.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2weihjntf.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2xhaueucc.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2qcpqhvwb.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2icigszgb.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2kobafbkd.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ipqhhgvz.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2iyoppotv.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2jvctpxqq.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2sxzfievy.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2qlujwfle.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2hkunpxng.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2dlnmcfwa.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2gejpunmv.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2omncwpwi.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2dqroakui.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vdlbnqxn.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2hyqnqvsn.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2kbfosypc.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iievdnfk.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2rwttlwib.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2cpkdbncv.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ayfgggiv.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2pynrakpu.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2ozcdzivi.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ltgdolmj.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2vdhbjrja.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2ztmrmyxn.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2njsvyrdt.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2qzoqcahf.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2euaejvjy.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2rnuacwcy.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2hwiznntv.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2hpzzezrl.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2dtfuusii.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2kuhhdxfu.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2lgrccjyw.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2ldldourv.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2squvpffy.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2sbcknriq.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2zfqcaixf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ksmzixvx.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2uqxtlmwe.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kwnxtudc.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2aihrvmmw.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2geczbtnm.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2kieavfdg.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2vprdbksz.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2nrlkdokn.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2ehkkkqir.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2cqppjthr.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2muxtxcnm.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2jfzwyezg.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2vflzedbf.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2qegbsrqm.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2ajerhnwz.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2sbkiwwxw.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2tbmtgsbx.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2seldvkog.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2rulwvyuy.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2nwqcenxz.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2jkroshhu.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2hlebcpgo.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2cccsfdnq.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2vfbdtyos.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2qialggys.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2bbhohgsf.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dthuanlq.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2fqyxoxgj.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2zonhtzjz.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qhjgetyj.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2iqzxsydz.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2ylbsdxjm.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2aqesumnp.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ukqgkkki.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vtqoznud.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2zgodvnnq.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2ngsbgopk.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2pmrdomsp.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ptzcayug.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2tilsdihx.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2rerypjbd.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2yiwsjgwb.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2nlwrpprq.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2lspulqei.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2bccxouwv.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2jbtdcqzv.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2wkogtlkw.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2uutphxbu.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2gmfgnipy.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2uutnuhgn.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2dachzzen.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2faanwqbt.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2vqggidtt.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2hdxkerlv.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2fqkznuhj.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2kcngnvwh.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2tpdwqzqn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ioodhhrc.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2opahhhkb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lxnebsfq.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2tuhgzdea.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2qcnrkawf.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2rjpidzjz.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2mushduhj.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2ieefsuoq.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2ecvvcsuv.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2yvnojzdo.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2rbfjffzd.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2vlijmlji.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2atrfdiud.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2seqgamcs.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2abpbduch.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2ryrjadsb.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2mkzzjngf.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2ypoovvbf.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2cqtouhsj.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2lleowsly.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2pualahxv.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2eyhyyhhx.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2lhpzeynw.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2nhfckeza.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2xnorhlzg.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2dundlgig.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2vrtposlm.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2fzsaxzjo.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2kvyzqsml.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2dcjzxkzk.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2rkpftbnd.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2cjefflwv.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2dumzwlqb.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2tshynzhf.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2zxvihwel.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2adqwaoch.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2xiuxqlsh.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2aigttsvc.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2zzidnsti.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2gqwntkho.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2yjsmigoh.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2greisrpi.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2jwgyzbuq.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2buqjvrzz.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2hqxjkyrw.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2kroqglus.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2tqehcmsi.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2dildprdx.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2tfsdwmrs.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2rxqbgvvr.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gdjwfulx.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2bsnxjeyf.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jdndnvwp.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ugpcfvxd.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tofpoxfe.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2sfsddmfw.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sqvtxazi.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2oetxjqlf.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2nmashafk.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2nucjqiop.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2tznaymth.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2qqrbtlyh.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rbuudmsc.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2wgavshnu.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2mkbzkhnc.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2adlodyur.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2kvqkxkcn.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2exddxkfh.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2tfmbxuzh.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2dsepujde.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2uwndylma.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2fchaixyb.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2nviqdqjz.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2cuewuyyl.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2ylbypxgi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sfgkbevk.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2duvnxylm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jcxdiadw.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2widvwais.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2jmfezdwg.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2zuzcitce.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2fjdftgfz.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2xzpcpbhd.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2cbvarstx.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2kfjnevrt.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2jfvyxrcu.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2ladurlsf.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2psqzpeao.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2xqpgrnyh.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2cgmbynub.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2outfulup.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2kizokadu.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2qzcjakcm.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2tdrabpyl.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2owwmwxch.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2fwffttao.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2awwbvesv.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2gkfamilu.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2htzgdvyd.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2judbptnp.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2npwhchzv.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ppbkscik.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2qufznzqx.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2vxcsbkpt.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2uwezmert.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2dbrllsqo.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2vocfoifi.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2obihpfgq.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2mneucpzl.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2ksuktnhs.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2bhjomirw.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2nfraqvbt.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2lsfqldxi.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2sbidgxth.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2vjmmfmoc.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2uavyydzf.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2ijgvdvzt.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2hnipvtyy.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2wlyayumg.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rhabqkte.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2sbunmovz.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2drswjnqj.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2tzxvtfwu.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ealkeztw.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ynvudklf.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2rpqslscx.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2unkspiur.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2wsfrlqzf.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2jexoonkn.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2avnqtvij.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2cwxzllug.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2jgwsucpn.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2cnbwufin.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2nodakgdx.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2wzcruaog.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2eyryxecy.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2sbdcimtz.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zezhrdrb.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2hyqihrym.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2odmitnpm.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2ubjrnnpp.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jddantfo.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2lqrxvnef.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2smtahhcw.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2bbnekjxk.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2tlgyxxvm.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2ckmfrrcq.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hxplmmbm.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2sfiunfbg.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2ivzywyua.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2rvgbdfjc.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2dhizzfmg.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2fwtpqvex.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2cgrrcmzz.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2oclslmwt.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2scylejcb.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2lfrbxevv.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2blldohuo.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2ackbfqid.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2iirgeskm.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2pxhuqqin.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2vurzddjp.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2xepdkljr.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2rohgybev.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2kepxqdqc.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2wvrqnphz.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2lykvaigc.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2mgamwqmb.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2cydnrclh.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2gkjdfgxy.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2rqmubidr.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2tmjocqny.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2lecsqlmm.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2gcjlwjem.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2jspdcahx.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2pcnirvyq.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2walhjzrs.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2bihkxkln.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2pverxrjb.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2qolxxyzn.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2xklzksgq.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2himhadxx.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2bndmsbqx.html


<!-- 参考信息 -->