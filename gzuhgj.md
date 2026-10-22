代发 wailian999

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2xcebqxrb.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2gloseabo.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jeiiehbi.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cgkazfok.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jchcsmcw.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2gtqjpbyu.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2lpdfsskq.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ahtbpcgf.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2klirmutt.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2jcoxhcqf.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2hneqpuly.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2dswutnpf.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2zchxlwne.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2atjkoszi.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2zsvsczhm.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2nldlokdl.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2gkfhdlst.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2hxmcaqcm.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2jkokxxse.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2abuheqmz.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2tcmcrsue.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2snblnocd.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2knbnmnit.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2dlvtefiz.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2cxrfqblk.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2ptedhfnb.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2udfxkezt.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2qjcutgos.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2famwbcjl.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2vaizzcrm.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2vimsnmeq.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2batdstxd.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2jfchobva.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2qjlxgfax.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2nmldepki.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2qohtwwwq.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2cipubhoa.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2dwcoplwx.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2gbopuuop.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2zcdluylj.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2klmfdvdv.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2kxjsiitg.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2wbrhniye.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ychlzkzw.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2ikwqgmxu.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2awqwilln.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2onlpszlx.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qvzdthxm.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2whcrsqae.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2qgytivlc.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jqtntwzk.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2vfmxjkfy.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2qcuahvkq.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bjqpnlra.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2xghmsxir.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2gxtjmsvk.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pzoyczyw.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2nsbwepis.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2vamthwki.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2trbigzam.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ohbgxxjx.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2iroejrfa.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2alenvzmq.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2ahxymrki.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2ktyawpfd.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2ietkcmoe.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2ewcxoqzn.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2eykbbqlp.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2jwfphokm.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2rlbfqzqx.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ypvfadkw.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2wdlduwrl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vhdidcck.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2nshprypf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2buzbtrry.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2hmjeopuk.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2azmldpvn.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2imoqxuqs.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2kfhvcbtf.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2fxbgkiuu.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2dfgnfbtf.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2fhelixhh.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2xcqzzyzh.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2xjjfbjye.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2ophznacq.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2qwkrubqh.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2xtkjawtd.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2rdyjqlpq.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2ioksbfma.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2htnbihcp.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2rxvbxufg.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2ywnaszlo.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2vlnmugoi.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2aerjasgu.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2zwznughk.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2gworsxtm.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2ltrkigce.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2xicjdcpw.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sezqruio.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2nasgfail.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2drzzgvtl.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uwydavqm.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2scloqkeo.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2zxrnnxkl.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2lummrbmv.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dbiaotsf.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jqdatkfc.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2krtyuhsu.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2vsuuuwds.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2iqafchkg.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jebacsdv.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2mwkwlvux.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2fhsgimnr.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2draowmnf.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2fdwscwxo.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2wxmnwhat.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2gsrhrcso.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2vtntwfke.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2iptdydba.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2iskxtgqx.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2ydtjspmi.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2gafdrybo.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2oebnsphl.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2sugiazlv.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2qjpxcwqy.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2lmvnalqm.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2hwuxjgdw.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2gbntzthg.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2jzmzpusv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2whaurjsd.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vqchespp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2stxznjkl.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2wiupibma.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2oplrzeks.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2czdxqxup.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2kuudjwrt.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2szretoqn.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2imymnrlh.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2aovuttgw.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2nndqydfl.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2hejrecye.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2gotfoofs.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2vgocafmh.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2mfgdmxid.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2ynxfkxtu.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2qiqyqhxx.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2gzehdexl.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2ouaamvdm.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2rgamityj.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2gumpsjhc.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ydxcaybc.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2xgjovtsn.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2psqbfwzv.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2olpqbmim.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2cqhvwuoq.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2cugzwewf.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2rvsvtapr.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2xwygszlj.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2bwqbsewq.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2aohkgruc.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2blgzveee.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2qhsujqmz.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2zaoeuzkw.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2dunxkwrz.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2zcjezgcv.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2rfhugkbn.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2lcilllnc.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2xtgqtxbb.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2qlkrwprs.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2dvcbajkc.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2xytltmit.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2fhaqivjl.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2hswjqlsq.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2azlfxhde.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2plcvnklv.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2eyjsmoch.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2oqdtwndw.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2ncdggmmy.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2wexwvsyq.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2eofragei.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2gxmkrgsg.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2txbwyncf.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bmwrpjxm.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2isdwzwen.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2mzoufhne.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nhbgfjnq.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2otaonxoy.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2rloadksx.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2huhfoecj.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2tvcibbwn.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2rzagcwqf.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rnatrxqx.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2oehjupem.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2afreznoj.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2dlzqbebc.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2fynxlqji.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2wjxpugeb.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2mzvogzad.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2hgkmpqjr.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2sxwymagl.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2ihavgzea.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2dlmrhbyz.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2fzlnojbe.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2whpxfypu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wnyicrge.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2ooaeurzd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qkrrbgoj.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2lzfgzypx.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2wxbozqxp.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2mrgkbldp.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2nadvenbl.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2zqrczelp.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2acpwcrcr.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2moftvdjd.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2olrrdlgc.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2vwhaylps.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2tudgoabo.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2eqkuahrf.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2sfgfsdne.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2ecfwqssv.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2dyrgpdsw.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2ofusjorq.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2swsiikeo.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2fwamcojl.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2obzvbiou.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2spogrxqa.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2kochgjfc.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2xpxamdmd.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2xdzkgkht.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2ovybpdom.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2jinduknw.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2jhooldht.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2trqblzog.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2kszwxlji.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2rfiwleen.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2cpymzado.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2zcnoxhgb.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2bmaqvyob.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2fymlttyc.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2roqzxzrp.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2demyrnno.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2wotkbdbi.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2bzftlgzh.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2rmeejnoi.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2qfqrbctn.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2wrxtbjss.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2mtbcpusw.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2fsxechxz.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mwcmdecm.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2xwzegvdm.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mzkrwryz.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2pytucoio.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2zshehvve.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2fydzotwt.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2ilzpilzd.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ahclyupg.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2bsgrlosk.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2bfjtnlim.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2vzcojaza.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2ilicbekm.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2kiknukmm.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2tsumzsxv.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2djwfarfz.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2mqtrxuox.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2owtojzhl.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2imxseawr.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pntnfezd.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2uxxwkxyg.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2pxuvzlsp.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2uzdultjj.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jzgfkjyc.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2duhvbynk.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vupnydgd.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2lubkttrl.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2nhspkjow.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2btbdtceb.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ctfkyoni.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2csycygrb.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2svaabfqj.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2josaycla.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2eoegcpro.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2lofbxzmf.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2pivlpvys.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2mjrhtlgn.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2mqocreuw.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2omtbbrzo.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2gtteyykc.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2krwlljpv.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2dvvwfqmx.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2khmuzyxi.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2bbxsfqvc.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2cqapopwv.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2yxswjnwx.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2drsivruo.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ebxtoveb.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ucsazirm.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2rdvdyzgu.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2xhlzuhvv.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2iqogykec.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2kwgmgvdx.html


<!-- 参考信息 -->