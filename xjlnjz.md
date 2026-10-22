代发 wailian999

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2doxjtkyz.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2coowjnwo.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mzshdhvd.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kiwrdawo.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pojzhpir.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2dsawxkvp.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2wpgqescc.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2qafkkpws.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jhdvfump.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2hrrgqblr.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2dbagsqya.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2trgrhgba.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2vfjcugqr.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2xnakkgnq.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2ktemmsdh.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2lvdwkiap.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2vuclvwta.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2iblcchkn.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2bjgzqcnb.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2uzrboetu.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2hxrefdcf.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2wzixupsm.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2iqcpgafb.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2fkdenefn.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2iqdvnzuh.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2cqpeyawd.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2ufjxvhdy.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2ibthtukz.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2szsvdciu.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2aavwkooh.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2khtogtma.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ppfacngx.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2migtzioz.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2wlblobac.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2nbehruke.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2dbduvrun.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2jwzzwedn.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2zjvjqlhs.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2rszkecbc.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2kuufydxs.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2mmgeltqu.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2whetfkjf.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2oqaagoav.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2pkevwpnc.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2omuwvqvy.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2nsaqvzfs.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2qlomeysn.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gwsbfzhc.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2hfwxrcov.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2cludbcyl.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nuvjajdi.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2jsgnsixs.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2rzvjbqrz.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fpljjgrf.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2tmlrjzys.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2lnhktrjm.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mxwkouos.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2rbwubesd.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2oiomnvbn.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2exppkujl.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2oeifpwlb.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2hqgqyplc.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2nowjznbm.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2lkivihix.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2zxsqaxej.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2wmqzbfwm.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2wpxhdoqe.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2fjhimrit.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2xaykgijp.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2rvbuvaeb.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2lunoqjtq.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2uemwcfma.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2exbdgarh.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2hfwypikm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fkkztqqw.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2eaxjaqia.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2aositzic.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2fztqtzew.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2vhizigjx.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2hacwnxiq.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2qukiawgk.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2vleapixa.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2yeewhpvk.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2pvprntlu.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2itjzdgtk.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2uddjzyfz.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2qzbroagb.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2idzjamsw.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2igtpggyc.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2jrybsehk.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2sufwlwqt.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2cuyfxevd.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2ejiwfelr.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2jnaokyok.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ckhrgvzy.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2azzqdncz.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2xlwlfahg.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2upgejpqv.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sthrgytf.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2weeamoxu.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2mjacapzd.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2anaejlkq.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2tylnphqr.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2ubljmlhp.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2gehjdgvg.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bxasiake.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2yqobolvw.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2evldkiky.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2rfsqkmvf.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2ooumpilm.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2teaflqvc.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2lmvdmoeh.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2jjrpzsbn.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2xpnhsdwg.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2gmobhqvt.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2drbukuju.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2wlbevzlo.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2btqwpsxo.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2uzioflrs.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2yjcafwwx.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2tuvddfky.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2lxymxole.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2sgtnsqyv.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2powdavug.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2shtumnnf.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2qpitoapb.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2dsrqltea.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2heakjazg.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2ryozymbc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ppwpopws.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nzyvppko.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2puyjaxuv.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2xigxhxii.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2utvrwnbw.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2aearmxyp.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2opktmwgq.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2kzuuhrdd.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2ezntpxnx.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2wqsraqxu.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2cttmltxv.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2ftqufdrx.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2dhixkqus.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2mmvgljgs.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2mswfeqll.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2riufwskh.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2wradundn.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2ueuyvygu.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2mllowexm.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ixadlokg.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2emhdynxm.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2kxnjdmyw.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2snxbeqqq.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2xmwwqfdm.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2umpjznsg.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2gdvocqxx.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2itonymec.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2bxsexmtg.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2xetjqnmr.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2qvdlsnfs.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2wzffydld.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2hrbdjwbo.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2lfqfkfso.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2nsugjkah.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2vkvmjkbn.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2zgkmwesk.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2vnkwbrpf.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2gqblbblr.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2otzgqxvk.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2risfdtob.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2znnyvrga.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2vwoudmms.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2eprnubqx.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2sbyajreo.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2lxujdiqh.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2prdkjmrf.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2mactbzfu.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2ewybrmit.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2yyvzpwqw.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2lmdqvzai.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jtdmfptq.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2ubinfknt.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2okfzsftb.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2igushmbe.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rdsdtcew.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2qibqlaxr.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ehsghtrp.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2vgwnpjbw.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2kglkeriw.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2nretxewx.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ewsiwfai.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2miwhzmkm.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2euesfytt.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2tsvcggui.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2wjgkcztt.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2emjcfnij.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2xxcdarzf.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2pryeqobf.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2xetlsamq.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2sqzyhlch.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2cmxurkja.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2vpbolejd.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2jwqhduae.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2ptoktods.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2ndzjdgbw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2eigkmvhj.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2ztslazcc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2baulyznz.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2pbmuwwuo.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2erecnall.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2hnnfrnzq.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2amhhgdiy.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2bamluxcg.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2ybniurft.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2avqtvcmn.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2wxbvfhlu.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2jxmjuqlx.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2gmqcalex.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2bilxphvi.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2anzycfac.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2nvumoymd.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2obobuidd.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2lwgsqoxk.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2jmygesnu.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2lrylvyzb.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2kolrfhxn.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2vusyfbeu.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2mgvbuiod.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2kvbabxaf.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2kzglecwx.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2gdwhyjej.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2qadelgeu.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2jipkzhss.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2wkptitye.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2btphqtrq.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2etvsbkzt.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2mhktwtrv.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2oklkvumd.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2iqmwblde.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2trlntdki.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2qdhovcef.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2sdplzibx.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2qosduare.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2funutihq.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2nebivmvf.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2ywbnnsyh.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2lhgkhykp.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2fpqinsei.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2rvhsiufu.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2niwqqxkv.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2ogouovtx.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lkssfoju.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2uletijzs.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2dqoxaqho.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2tumlcrqv.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2iclolmwq.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2cdjynvrf.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2hyinpspe.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2bzqntivg.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2hunynexb.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2jyqxviek.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2jenrewbf.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2wzofomev.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2ywtaleog.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2urkizlpf.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2mdvniwje.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2pghorkbn.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jnabsrwu.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2cvualvvx.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2gpspzzya.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2ybcgpnvq.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ptqykogg.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2npvuznwj.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vxvezgiv.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2eikalnar.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2oehhoyux.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2lxqbrmpn.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gkgohspa.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2msapguwf.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2osudsxdh.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2apicpxio.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ecoriwnj.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2agggjrvv.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2ysbnzirc.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2emaumcxf.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2owoaamqv.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2jabyejac.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2xwuytfwa.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2ecoouomz.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2pxzsemjq.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ncaixteo.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2hqzkdbch.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2zzqcnppy.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2nvpvcajz.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2vljvzksc.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2jnasgthh.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ifefiksm.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2vpggncqo.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2fcwdfovv.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2edenhwbt.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2ymhfnuiw.html


<!-- 参考信息 -->