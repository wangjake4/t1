代发 wailian999

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2xavahcoe.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2mijmleya.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2pmswxlcy.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2fgfdswdd.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2bbyaiddd.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2xueqihvz.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2yplqsxjk.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2ojlmpjeg.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2wzhwqlup.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2omdkgxmp.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2jqryjjbh.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2bztsuypt.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2ejahmejk.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2eigvbpjk.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2djbjnrcp.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2tscsbqtg.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2plgqspgh.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2karclqnb.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2puqywmkj.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2lqggxsaj.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2eptbszlb.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2qjyjkwcd.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2gujcrhml.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2rhvivvwp.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2wrdaqzro.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2yylbbnju.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2bhowphcx.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2hqeebbnj.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2xdhbfmud.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ldfmhbeh.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2gbtisvai.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2zvxzsmhy.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2udprkedu.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2nawvmlnt.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2sqtzjwlv.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bjjcvijq.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2yubyjrqs.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2llcwsebv.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cwzqupct.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2ygglzern.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2bgarnrks.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fcxhnals.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ejaobcoq.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2iovzxyfw.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2iswinpkm.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2lksaykah.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2jiwsmbgs.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2plhonjpz.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2jqwhlynb.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2ywqzrrnm.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2blalglrh.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2qlfvhdox.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2vucbjkzf.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2qftuccfh.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2vqxfdoyr.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2dzurgmed.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2qkclqkmz.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2raeommcg.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2fubzenpe.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2wmsvrunt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ttuhsoqr.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2jzxqppdu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cqimvckb.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2aeeabaxk.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2trqzybpa.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2fnbmqbuz.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2iatjgmqx.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2ttdzaprf.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2wftsgkco.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2bmizeizv.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2rjnpsesa.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2lcrldfyy.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2wwwkdmkn.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2inerfrsh.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2afxpttgw.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2zdmkgvov.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2junmprqx.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2iicxoyip.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2scfutxsa.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2exbdjzgh.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2wfxskfgz.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2ugpkmjqz.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2hfbvxnsf.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2dfebkjtw.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2opiceaxt.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2txocppug.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zxepydhl.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2nntrrhkt.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2litjutii.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oftwwzhb.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2tkrccdwg.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2qzfqlsgs.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2csxgwfpj.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2twxogpqy.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fcmmnial.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2oeikdahv.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2fyggnwgs.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2vputisrp.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wqjdlvav.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2ddywzjzn.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2lulxqagi.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2mzrucfqy.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2ernfogmo.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2qyvnpsbm.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2hlqgetmx.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2wfibmrfd.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2mgheooia.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2loobuowu.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2zebwyfam.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2rfudptyo.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2hgvzbvjd.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2nszhkfol.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2xwnutblu.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2ibsaiuys.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2fkhtrabe.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2qgtyylwr.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2xhuuxpyg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mckyaeqw.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ddnjiwys.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pmeduhxs.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2qmmicdph.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2bpfkedhc.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2pkmekaua.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2vrjvunwv.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2tjkvxshw.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2uzwwookh.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2lujmsysm.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2pmehonlh.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2qkixlkos.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2qjztbmba.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2srvugcgq.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2frsthicw.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2zwlyqbqh.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2wqjqaskj.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2vizfigxo.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2ptlmyeci.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2gvxysjiu.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2mzwdmkqi.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2rwsmivtg.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2aogfahlw.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2jlyxuhqx.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2gthtfftc.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2gzsdsemf.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2xcivwgqi.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2mmynggoj.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2shfifhja.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2cpzcrusl.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2oxhjqkve.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2oinwsemn.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2xshkdbdn.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2ooqsxsbg.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2dsiwapwz.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2sfnwxuhu.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2pldbynbc.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2rnipaxxc.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2zhkltmkd.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2rggfwycz.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2annafoau.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2agoykwvx.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2ektbjjip.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2npqbyzen.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2wbhrscoc.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2rekuxhso.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2odplicco.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2cvjcrjay.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2ttauudcx.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2kxwdwjpt.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2imkwgcbs.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2wbnpqwmb.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xljqptbv.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vybtztlr.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ohlymaag.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2catzcxnz.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jnpellnz.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2rkontpqk.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2qzilwfve.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2jftvjphx.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2dgoqezek.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2yzplnnge.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ohszolgh.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2tldpxcgy.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2kkcshfqt.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2ppsjozaa.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2ssngnuzk.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2npekyncx.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2jdveaubt.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2nskoufqh.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2cjwigfqe.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2qjardtxg.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2scdcprmm.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2bzxcfjqj.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2hnekqmhv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rdmrztmr.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2rfoyhzkh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2byjmhqka.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2xyottyjp.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2qehszboi.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2ivihscxu.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2kzeukwku.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2pmdurdwc.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2mhlwjbbz.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2azhcovmx.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2wjwnxncf.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2dnnvkyaz.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2avckxyuj.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2gcpzqvbz.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2sjklxgrz.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2yddyrvgi.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2kyaamuxh.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2xqhaxhwn.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2tlgoqgxe.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xudhmvoa.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2dhndqaja.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2svcykrtw.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2eelizmqw.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2mdhfunmy.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2bkfnekdt.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2soswotif.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2avapizjy.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2plzjriuy.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2qemtmgzc.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2qgnvqtak.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2vurfnbke.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2cyoqzjol.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2rlhwwbpo.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2gkajzmkr.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2tzxwvnuh.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2eeehepjk.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2hnuatwwf.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2nztbbwbm.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2ugijrcnr.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2wpytpkkm.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2dnicbhng.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2djnvaaej.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2emnewoin.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2oanncybh.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ibuwwefo.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2flzcpave.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rguniegd.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2tujexyup.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2tqxpklok.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2wbqtjgjt.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2kzxymkar.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2csnaulju.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2eqiquump.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2agcwekvk.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2jluwdamk.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2zlpdlnxv.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2brpuirja.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2bmjvlulc.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2poywqvoq.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2jbdqkzbj.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2rjjeuevm.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2cktqqayo.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2skgiqtur.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2vkndwgmk.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2fbfnddyi.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2rjkgnlom.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2evbopqvc.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2zqbwqrqu.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2stujoqio.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2abgrdmcu.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2gickeyqe.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2vvbxzgzn.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qyoxsedf.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2jwtublkf.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2zbzfwalp.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2bmrhrlfl.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2creowpwy.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ruguyvnd.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2hlifcwoe.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2zpzbrnnd.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2epjbunqu.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2tpsvtdaq.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2luyoqell.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2skbfmlqs.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2segtluwu.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2mzhcwpus.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2bdaedecp.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ixoikonj.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2scafvuci.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2jvzvufcs.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2alkzudlh.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2lvetwvma.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2pawsdycv.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2piusjmgy.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2qnxdwevs.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2knibzkcm.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ozdqgfpc.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2nivhdghu.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2pinbiwst.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2pvsnfwtl.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2hmchsgxm.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2pieorvso.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2tjfoyirm.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ivdzouft.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2hcweluve.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2nzkdevoi.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2dtucwzhe.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2lyvwsvcj.html


<!-- 参考信息 -->