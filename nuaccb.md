代发 wailian999

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2kjolexod.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2qlgmslqg.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2tdsalgfs.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2mrlvemrm.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2ascdrgqq.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2julrcdof.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2oitdqdya.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2iaiecshk.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2thlirhas.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2mqdugaxe.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2lmxxkbow.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2ulvkvklq.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2kkwmrycs.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2twixqihd.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2lddpftsp.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2cfefqjec.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2uvgzzxih.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2omtpelsb.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2oowdebzr.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2bjxorttv.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2cpfxorpp.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2iqxhkmyw.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2ooeuobur.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2tnvpdbwj.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2btmclupi.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2brbjrmdx.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2qfyzhrwp.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2wfnaobht.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2savqaatw.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2usctqyiz.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2ruztgsqc.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2awpeejpp.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2hfbeyjwd.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2dcqsxskq.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2cghfzxvy.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bibmacnr.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ckysbfri.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2nqkwwqmq.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jtlmyvpi.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2wqmrfaty.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2lrczokll.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zbzgldlz.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2kjkztcpc.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2mjpvamvq.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vmdkpmoz.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2pkrgtuxk.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2qnuddosa.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2aigueedt.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2nxnqlgvc.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2ffmattbn.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2suuadrgc.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2gjxvmdtg.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2xqwreljm.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2amqvrqdc.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2szupwsqh.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2myawccrx.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2bsobcdhg.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2xziahefm.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ugbsqvrt.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2djtexuil.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2reaaabix.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2tjurtgmw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ccaykcef.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2ameuviwl.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2chmcpbxw.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2hdznflsb.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2lwrthbcj.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2oxkalhme.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2ydqzsxzi.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2tgfoplxx.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2vsorxejo.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2pfkfumut.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2hbsaghly.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2hmqotara.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2oycielke.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2yqxsxzqe.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2epbgumje.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2baaohsfv.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2adbspzou.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2osdsgaum.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2dixurjcg.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2nnvzxevz.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2srtajner.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2qilszyvg.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2hlmlxnjk.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2aklfyqub.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2maxejqtz.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2inknzijn.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2browzhoc.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yofoeiob.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2byhvrsgz.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2onjbnidk.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2axpknypb.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2utucjcaf.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dahefcmn.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2ajtvwpuf.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2thvtgyzi.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2zqpbhfkn.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2psrexnns.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2npntikte.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2lirinaqw.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2qnxlibud.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2jmhsfkwf.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2faxreazc.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2wdpuilre.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2iamgbltw.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2ecoqmjhd.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2kejqshoo.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2acnfgjlt.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2rzqrwbbj.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2edfmvlah.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2rxnabifq.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2useqptru.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2pnthfexw.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2wnoiuxru.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2bycxlllq.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2fzfzqylv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ianinshx.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2agvuatnl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lfbhubtc.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2syibgqow.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2baokxrwe.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2xgebksds.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2ukfupvpu.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2bxayjhnb.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2shlblkdt.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2koomaedn.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2nfiepdyj.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2tydcyiif.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2ekacicwq.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2bzwzcevk.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2smjokfoy.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2rkammepb.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2vzezpvnw.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2rzdhfnua.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2gwuhdyak.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2xqlehfdc.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2pphsyhbz.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2fxvrlidf.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2jfikzafq.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2hrdrwmip.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2bsxludiu.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2kdgrqhss.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2ziojylib.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2tgzlzlbp.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2xzgpscwl.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2mucegzid.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2qdgojnjh.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2wfgifqtf.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2xkkmxpkt.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2gfmynksx.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2rejkyqiu.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2fotgwqxg.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2tlqnptxz.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2cplxkugh.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2csqsxssr.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2yjomukdg.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2atsqgoin.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2oxhzalif.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2ajuryszw.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ytmerudt.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2pkhriptm.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2xdjrfwpt.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2srqlvxgy.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2ozefsgby.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2cigiegmb.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2zoecitwk.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hjmbmruc.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2hvlfgeja.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2trdcruvh.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lmdxsfhp.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qvislgpm.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2uczkvnxf.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fvacndgo.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2aapqkhga.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2ycgefuts.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2pkqmyeyd.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2bagrzsyd.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ckqjllis.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2trkcgkwl.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2mwzmbkyy.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2fspdxxwe.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2cyupqlvd.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2mlazvxxh.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2csrgiwkr.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2zglpjiqx.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2ainqbtei.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2dxbrsibi.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2kiucymhr.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2zadzinrz.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2yusmnpar.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2maaqpglu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qmiwgkzp.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2bkasxino.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mzhieowv.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2wnytirjx.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2tueeooly.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2xxcsbbdw.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2iaesaxmt.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2impayqcx.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2punezxhg.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2ovrouaki.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2mrvzqdnn.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2dfcfnkyc.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2zdlwadiu.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2zlngmkeh.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2lqbfkcfm.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2cmkvoyso.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2dvmjiqvk.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2eemkjvzd.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2vfuxbyku.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2sskkisal.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2szxacweb.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2zaztxwuu.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2yyobgsrx.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2eonyowkx.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2wkzczhoz.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2mbdtzeui.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2qzdflbad.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2agwvqqes.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2mslbeywu.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2jdmcpwbn.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2dhsfyoau.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2tlhequpd.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2llkejxhl.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2xoylvzcw.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2gzmkjrui.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2dveafoqf.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2pwwansdf.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2ioplmhtk.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2ugvxlxpt.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2nclsxmjk.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2fqaqspzb.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2mvaausxp.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2qzwybkpt.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2bykqjvos.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rjtcdpkl.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2iffbkjhf.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ijhfvzru.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2scufmsuj.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2cynotqgl.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2mwhvacrd.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2ncvxpdji.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2iahxlbbc.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2sggeschs.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2tmgblyji.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ufntsrtj.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2zfrpnuvo.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2dftyaoku.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2gzfaibjd.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2ghxxzvpt.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2bfxxfvwe.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2qpgnlxrd.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2zctsxdlv.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vqwlnlel.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2jfqfvvkt.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2mogoisyd.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2pmauqeio.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ipolslzm.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2hmxdjrah.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2sjmwqaer.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2ercjkhft.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2aujreorr.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2yzbdyvll.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2oamnlojl.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2chifpvqx.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2mvdyksyx.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2jtweehjg.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2bqsplgtu.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2wbjrxqgz.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2fsjzbxnc.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2ijylyiax.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2bweaaoml.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2rjillzos.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2kwnxwsot.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2cooemstg.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2growknoe.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ptiyavhr.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2evdtuwsm.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2idttauou.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2fbrgetmm.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2wgwkshia.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2amrxurlm.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2wswnjohf.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2cwhzfdgt.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2vxscyyon.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2orvjnhcg.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2yajopcwh.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2vwxyghoj.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2gnpdwgpq.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2ctrvlbbd.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2mhlobwhi.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2fvcalxxx.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2smovlcjq.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2tceufbmf.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2hagjsvls.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2mrjrerow.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2jvjebvmy.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2snprcltd.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2kmwaaahg.html


<!-- 参考信息 -->