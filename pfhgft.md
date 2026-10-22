代发 wailian999

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2sdanndsd.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2yjmrffba.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2kkvchgmh.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2vjarnctm.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2olaurwjg.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2sejcliko.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2ehxbihhq.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2mbshovya.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2yphypysr.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2eydjaunz.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2jnhsysij.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2ptcwdqwr.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2ambkxqas.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2huknhcvt.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2yhraxvsa.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2paksmmmb.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ewpjkwgg.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2dyxmkpxj.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2nphxsuxm.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2sfxcbsio.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ajhyxkgr.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2pypbpmne.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2invmxuam.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2cwbqwjvk.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2sqfpidmo.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ziayfjul.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2rmyvoptz.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2tlmnvzxj.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2csnojocx.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2nqzfrymm.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2nmzodbnq.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2sooxaebq.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2emopxgzf.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2urnxzjvu.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2tekmxzdm.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xlpejjnb.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2jzljvaaf.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2tczevtev.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ujussvrx.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2lraldeax.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2ylwtcsuj.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eyeiyehq.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2yakuajpc.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2lawcuqqc.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xinvobim.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2qtzvgjcw.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2votwldvz.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2badwirzy.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2rjcqramv.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2qsitdiun.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ytlszorp.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2kcowpjlc.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2hhsqnfpn.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2hxrpvdhu.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2zuhnbnwk.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2isxtvwdo.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2etleuhuj.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2bhtenhzl.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2stnrjosc.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2yglojkcr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2awzcwavm.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2thzofsri.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yvirdwsz.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2yaaltbbb.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2cfvdndac.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2voqpcjnl.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2iendpxsq.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2duqtzpgx.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2ghgvpyzv.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2yuwdjvbm.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2vaopzxoc.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2weznoykc.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2hgxufvof.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2watbiics.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2unueqzoq.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2qqgnaxat.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2togvzoey.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2pktifmxc.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2kfngppol.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2qfwiejis.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2uifxdpse.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2eienhjnk.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2doyulois.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2rbihszyp.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2zextswio.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2hrxwfufp.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2llnubkut.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2fzlntsdm.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2tcsjaysf.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ytldcmll.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2jmwwzwsh.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2rmkmhkie.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2utjtldbo.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jrewezue.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ldrhnqvp.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2npfoowle.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2boysmvyz.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2omwquomo.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wchyrekn.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2jzvznkcz.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2xmlibpxi.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2hiymelmw.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2gsppgeks.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2zisekacz.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2wibgsosp.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2glkozjwa.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2mqsopgwq.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2kqxidrbm.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2obpgulnq.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2upcehemp.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2querrmgr.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2aapsjffn.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2ouzkorjk.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2hwnzbwvi.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2rytxikqb.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2jgiywdfd.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2xabeihcr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jbieeujd.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2edqtmomu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2msrfacor.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2trexasrh.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2begmadnn.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2nvgqfqwi.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2vmcfjvkr.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2vtvqrhjn.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2lgoospzk.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2ukhoiigq.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2cswnzupc.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2jhghbgqo.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2htzrlsaz.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2cpxjhgjj.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2eyfiywej.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2jumrlogy.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2rcmvdqjh.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2xjmpsupw.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2bbpofeuc.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2kfyquhkd.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2towtsgln.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2hfvxhkqc.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2cqetdotn.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2qvdbpjhc.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2whsrpvlz.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2vtjhazxa.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2uaupxwkj.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2mtnxkmnj.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2bxucmzps.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2faggkqed.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2uoatabqs.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2uslsrllp.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2pakjzstf.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2xnkvglxm.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2nnyelkhc.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2cyjepxxn.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2rlmkzvei.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2mxtjmair.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2bfcmirek.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2zsgmjgwy.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2emlxnnxu.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2jckqfaou.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2zyxtwzfe.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2gjlvbmlv.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2xlehiumb.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2quevcpnk.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2ozzgpqlg.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2pembfqhn.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2jhfakqsk.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2uvbfhvoc.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cmzwwzjg.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2tfjobqif.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zhuavdic.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tyuapnds.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lvuggteh.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2fzctsddh.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nvnkhckb.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2ogxjxrqu.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2yqzlzqhq.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2hvygsphb.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2nyfqgsef.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2xtezztrh.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wmdxfsuj.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2lidvgyvj.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2kpgbecxu.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2ymzcoxgh.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2imujyntp.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2emwdmgfv.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2waoyoqfc.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2idrhdoax.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ocgatiba.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2rxtdwamf.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2mudrdvic.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2mkaypfla.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2vakordbc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gyyimcny.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2mwngtvew.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pjzxmplq.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2fzgkshfe.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2hzxpkctn.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2hmdnakcd.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2scyvzrxd.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2gxdlxebk.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2xwhecoon.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2xxrqmqkz.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2ivutvtnu.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2jeyvibip.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2uyxyfguw.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2kwlcohnq.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2nrcyezrp.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2fqamedcx.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2gszoerag.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2xuqgvhki.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2ucmsogtf.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2bpxohzic.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2nnqciiei.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2ptxrhdvb.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2zwmjflkl.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2abdwdlks.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2lafrnphw.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2wmgyfwft.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2kgcflgif.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2wixmvodb.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2radtbigw.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2wdpeylwx.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2fdaufivb.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2dluyyuzt.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2iqbemidn.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2ocxpfgaa.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2culzykga.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2dscszynd.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2snfiyzvy.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2xdbtqyyt.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2zqmirbwv.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2tqroterp.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2zfjqsjey.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2bauddxeg.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2cwjvuvah.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2daweduqx.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bamrsvnd.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2lixabqss.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2uahgnhel.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2imgafwud.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ydiomeap.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2mlftbqqa.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2mcfqslat.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2mtuwimtd.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2ruglacds.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2qghohqdg.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ksqllzwn.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2nocihgpr.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2wasxrfqq.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2wwxtjlyn.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2veqsmqoo.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2imverdcr.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2rvmlojet.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2tbzubxxg.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ppvjaroe.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2mmupstor.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2wbaxthky.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2kdwgfeeb.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xxjmtlmw.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2jxxsrltb.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2teggznzd.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2oidrtsyn.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2sxuiroln.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2xilypoiq.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2myoizrpx.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2rzvcgzzu.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2jxwywesh.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2jshefpzr.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2klzebnxy.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2cmxgiprq.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2ltwazmcs.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2rgwdnwgf.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2xmexkamd.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2nxtjtvvt.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2dkrllhim.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2jcxdrbue.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2cpdyycds.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2tyfukmjb.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2eiadflgf.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2gshmkuhh.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2fccrcpyc.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2vwqnfvba.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2uaftqygm.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2tfauqgxt.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2yrxghjeg.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2kotvmaxp.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2achnweae.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2pzwwczlb.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2pttlyurg.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2bbdlzqkf.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2lxtymhyj.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2bqcimihg.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2rlptwvjh.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2npthjhbv.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2avxbwfug.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2tlsrvzmq.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2dbodriyi.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2dbhpbgie.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2dixxmhuz.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2dytqfegz.html


<!-- 参考信息 -->