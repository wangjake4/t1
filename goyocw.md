代发 wailian999

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qnnlxmvp.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2aysrgxxp.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2cfkacpgv.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2kugfdycg.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2cfdrgkhi.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2uwdrrbrf.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2rljujrtl.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2aluwyoco.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2bhbpvkos.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2ysymkwzh.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2rvgljpeg.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2vtnqghud.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2xusemtwl.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2ykphmwvh.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2yaffnfbv.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2iffufmrg.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2niosfaiy.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2kqekfhgq.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2oeatpnpn.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2jszwzweq.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2jykbxyef.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2lehkykes.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2szjdnmol.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ozivwhvt.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2kodxzxpz.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2twobnerw.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2ooothent.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2piqbnnkv.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2hhyjctpy.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2bdtgoopf.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2pasuoxsb.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2fqecikts.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2plisiogc.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2cnjekgsn.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2dzzgrfdz.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2jhbmdmrf.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2knyxortr.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2jesxcnhy.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2jluihqoj.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bhqvdbed.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2pjmjcxuv.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2moreunjs.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mvgueecl.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2dglbewtj.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2wmfiegns.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zvoikoyy.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2lyutkqeg.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2pvybwgvp.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jecuniag.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2gysloexi.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2gpreuxhf.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ewbswlnh.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2qznymuxi.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2xuevldzg.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2qsyumyvp.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2piwvtlvz.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2fgsehmei.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2cpbvujhc.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2bcefakyv.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2zrnkswuk.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2suvsqywa.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2nahlyrqm.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2hzlfsmrj.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2jquvzxoh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zvmtpzvq.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2rzquzewz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2knsanemn.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2tpxxedac.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2qxladnix.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2qpbyoqpw.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2chowtchs.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2bjyydlum.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2dredtvym.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2kfyscgup.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2cvpepfua.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2ekqgvkpj.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2gyarmrmt.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2zwlhmfcp.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2dtmqqred.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2hivtjgcw.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2ugelntfm.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2mixzzkll.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2hekaezvi.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2lhebpwtv.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2lpqdqjws.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2espmsvqm.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2szagytlx.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2btslydlq.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2oeelleha.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2azbgvcwz.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cnzhaimc.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2xhrrpnky.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2eujcdgua.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2acfbztsd.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2nfwqrrea.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2jsmlefnn.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2pobtltvq.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qmsfwdpy.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hzsadiob.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2pmttwlqt.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2ltyuhogf.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2irsfagdb.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lntmviih.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2cdfatewz.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2osllhfdo.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2opwhyeun.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2zheqdpxt.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2oxilpsjr.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2kbiqtsgs.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2zgvcwxes.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2phmlyvvj.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2aoszvsvc.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2xnqtbmax.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2uyvujzaz.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2bloyqdem.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2ebkhexki.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2ryfdoany.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2vhdrhzzj.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2pezegpst.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2ftiwiuhw.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2vqvofsbn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ksmffpbf.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zqtjajgh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nwhxwfnk.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2hdrjhejm.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2ygbpsnzq.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2mugbevjm.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2ywengcab.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2qcczotwj.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2gpbavell.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2uaikbbdu.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2fwvippbh.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2nicfvrrt.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2rhzcssch.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2zlmqsqyj.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ldodlalw.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2fyvoumpv.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2lfhpxwas.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2tgfzzwic.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2rczawkqy.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2qptoddxl.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2omeeeejb.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2zqtjnasb.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2xsmwxhiq.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2zpcsfyvk.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2uxuefbbz.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2nbdhznkn.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2voefwroi.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2sjalgyjx.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2hhjojxiv.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2jesjbefe.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2xianimto.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2wzxpevel.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2ambvypbe.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2qwvbwfiu.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2vwzhfroj.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2mtotuojp.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2wanaorun.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2gtwqvxpj.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2sxcbrjad.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2kzcqomkj.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2ojjlusxw.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2cqtosmmf.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2iyfiuahd.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2toyjwzhb.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2lmgdvhik.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2oecepyxq.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2cskifhzi.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2rebekzye.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2pbucqoov.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2qdjasxqm.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bedqacjd.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2xznkjyis.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zxcfwisg.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cdclnazi.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ywhwksaz.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2djuexgym.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gwtkaqqj.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2nnbayvav.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2lvoaszuk.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2qcewvcrb.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2wkimabak.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2pniiyjwc.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2htgisnbh.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2chkxgxba.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2bnpohxmu.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2zfvjnjeu.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2nbkjhvpw.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2sodciose.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2wkgancuv.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2xjiswvsf.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wvaaazcd.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2xcslgcwu.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2bdoyzcft.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2amumttcu.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2ohiejwrg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2csigdmol.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2tgzbzfwt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xenmqayx.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2ccenqbum.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2ajsfzpoe.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2kdomwlib.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2xthfeyzh.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2xqwwvtoi.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2jiqemkqc.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2ukwcyvis.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2mtzyzjov.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2lqoaxcok.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2xmjixssg.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2ufeviorc.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2ejcfbbhp.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2nacgyvfn.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2mwilfrzn.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2eyeanwpm.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2xhkybhff.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2bvbhznsx.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2excboomp.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2mpwoiziw.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2drsbeknb.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2opgpdgxl.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2amcpiytv.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2tquokxdy.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2opkzafmz.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2qebfvmac.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2nxyftntu.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2vtylhgyj.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2toqfojau.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2wbywcbko.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2kkuqhkfo.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2wyciqqtt.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2qvpebwmq.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2ldknkmtj.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2cebjvmzq.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2uwrlwrvy.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2sebsaopf.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2hvhrigjl.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2lgdakhqm.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2erkmdmlx.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2xswenvbe.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2ghzttupc.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qlhysoyr.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2eudeltxl.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vvbyygef.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2quyahxwl.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2qkvvoaxg.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2onjnmnog.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2oauydiap.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2nrrcxigt.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2zblslhvx.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2mrpuidle.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2rjqqmikp.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2nnzxruef.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2ltdoavid.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2wscnvofc.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2iixkislc.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2uwdfhzdn.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2pekinzie.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2brprnlcw.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mmmuzjuc.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2bhhupkpn.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2ehmzegeo.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2zfvprenu.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ngmftlsn.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2baqnhdbi.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ottfzlmn.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2yfjgsvwq.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2zpoqqcax.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2dgitzsyk.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2isencoen.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2awtxbeim.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2qqwmderz.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2xxmshsrt.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2riqxpeak.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2vyuysuoa.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2xdoiqpkg.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2mcncriku.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2oliyoiyo.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2znzbsrik.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2evtzckpa.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2tvopaomh.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2vtkhakvv.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2yadtcqhh.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2tucfhwjx.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ipvdlbak.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2qycletpp.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2tdyjyzsw.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ddklfdfq.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2oyjgqrzk.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2krxlknht.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2xajwpfch.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2kjiwlueh.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2ynaruioe.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ntezsnxr.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2remssyvv.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2kgyzjrof.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2apxxyzgh.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2johkbmxh.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2iyijtums.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2kuwfsvci.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2avauogdd.html


<!-- 参考信息 -->