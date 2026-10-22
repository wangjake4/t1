代发 wailian999

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2blzlieml.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ylfluddo.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ncdrmawo.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rygbernv.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yssfslyc.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2ozvscndq.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2osdgxche.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ecyivolg.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qbunqija.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2yzapizwy.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2dlrdqopm.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2rgpazgcs.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2xmyowvbo.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2harieuup.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2obnjdycn.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2tllvqope.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2mwjlxvxq.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2oiyphdoa.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2ckdtlqzx.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2ewslzxtj.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2yusrtbqg.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2nvfkuqab.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2wcqphvcf.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2xsxcbbol.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2rgaaqgzu.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2pftzfgtp.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2sgzlptdo.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2bolngmbb.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2dxgasevx.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2jgwgkmly.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ggeislwc.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2romqneoz.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2qbyfwkex.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2hhfaqusj.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2rjwocxzy.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2huanpefn.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2gtaqurek.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ilaikvsp.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2hjoqnult.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2fjuvojrw.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2wyncrxyu.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2bcgimlqs.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2mynauzlx.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2tzinpuwz.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2pifjrijl.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2wgslfkfz.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2nmiaymph.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gwimspkp.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2cadekrzg.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2truakdsz.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nnvrmdmx.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2ocsthakn.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2pttqtqfq.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bxwccgno.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2tczlxkys.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2ruphcbln.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wtmhtmoj.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2ruwgzlrt.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2zwhkpzyt.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2jqjmrkyb.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2pnlojpdx.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2orhitjed.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2xneevspe.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2ikftebkl.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2rwemzobw.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2iljjgeof.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2hlhlydbg.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2qfnvjktu.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2cctcjnlz.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2kmxffeup.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2dmbnqstn.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2hqejlhvo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ajaaqqqy.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2rfuptyvp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vbkndipx.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2vufhtlcs.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2gusdiqxo.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2nqvqimbo.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2kfnjrumd.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2ugdahqtq.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2tyrlyfnd.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2xmmtknoi.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2jrkukumn.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2pyhklxwg.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2uvbdugqh.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2qzrexlck.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2dnqfkwne.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2dnmqjnfo.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2blezjndu.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2sdywtkmu.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2wjtxcxym.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2vccqbyna.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2yyxgvjrq.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2vcdvpktg.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2fhknehtb.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2fgqsnfwn.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2zmqcebsr.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2eoyajrek.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cskpvmfy.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2mcoyzlwk.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2dnqzabsx.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2inesaqli.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2jdcjovuo.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2tlaowyyn.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2klcchyfx.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2spgylmru.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rkyxdbmm.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2oukyavxb.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2elsqfawe.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2fulluhgm.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ytwsyrvx.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2jaoonqcl.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2vrupocjr.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2dpqjmfba.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2kmornctg.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2lolbgnwq.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2jtldlxmx.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2jsfezrki.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2exgpimqp.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2bbuyzcnb.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2kigaflic.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2omdlhoos.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2rngtoyao.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2znommbfh.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2mkcgnpbc.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2zoanabnb.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2vricjhdy.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2jfprzwsk.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2uivvqzjp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2joqdcbix.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pkgrzkpp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cewcfjxi.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2xzocyxyi.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2vuqhgnzq.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2rnyewcqv.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2lbqlxtxd.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2bszahfch.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2bnbcgmxi.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2dfuvzlgg.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2gzubsyfp.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2gvbfohgx.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2lfnogspf.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2rbxqcutq.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2moadwudq.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2qfovmoez.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2mjsvxvar.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2tolnjedk.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2nhpdnhvp.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2osygdocy.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2zabcgetg.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2kewnobqo.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2vkfhpaws.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2lturymkh.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2fukjuena.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2wnblstpc.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2mglefukq.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2ivegqngg.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2nsmkjblb.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2pmyhzeje.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2jsmwwuxl.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2uhfxrecr.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2dofrnhsh.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2nnoeeyuz.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2bykibljx.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2hxyncxrw.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2xmfjjcbb.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2gikncvrr.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2wgpxwrak.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2dzkjslwh.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2elwutcfn.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2yzkvbfer.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2fkgiycjc.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2nkuocjho.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2iibctzje.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2beuyunhb.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2gilscvua.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2cfcvvkdn.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2ynspxyby.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2ybkmnmak.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sucrsjai.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2ubrrmptp.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dnszrdka.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2huqtspyr.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pqxpokbg.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2uctjuhaa.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uhutyvlf.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2gqiicxff.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2wyzcgsuh.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2wqeembat.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ruunrlik.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2kueyyinn.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2unylejll.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2hhgmalot.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2ymfsxxaj.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2nhacuham.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2ysjymkhu.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2glkyjxcd.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2yjckhacz.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2gwvwjmvq.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2bifntees.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2mefehrqy.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2ossepwik.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2bvtxmibz.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2pleslqmh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rmjucznv.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2fqkwgbfv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lfqkddcq.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2llorsjon.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2tjdycgeb.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2ublrtgji.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2mgrxmglw.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2ubrlblug.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2aucixwrb.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2jkzyuzks.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2rkksigvz.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2eatczrmh.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2gmariqkf.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2arcgjehk.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2dkckhuij.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2lusvhfnd.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2zhdsfklh.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2hxsvqulc.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2jchroeed.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2uugsrjkh.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2kgdtjebk.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2bywwzubd.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2crapwizq.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2kopvtysz.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2itryoxjo.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2dflkykhy.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2vfypzkkl.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2owzkohrs.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2blasugrv.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2fgbwyxop.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2ieyqetue.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2ihzshhlg.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2skmvqlvc.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2jfzstszr.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2rmnfemeg.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2lnrfltqc.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2nmsuhjol.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2gqmwhgfj.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2bxahgseu.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2jqyelnud.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2rfqxwwnh.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2nftkvkhr.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2orydxabk.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2qnkhgzow.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2yyxunnab.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2qqmfcluv.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zvckhlgy.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2nukaihli.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ujzpqtgy.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2hdamzwvj.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2renfyyvv.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2xghtjxlq.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2xwrxfrdw.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2cnnctmjd.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ttkupssh.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2onlyzomw.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2hyaqohvl.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2racvppfq.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2edfzojvv.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2eeftdfaw.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2adwwhxxl.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2zcgfalrv.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dhqbrwlb.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2lieblpry.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2alvybokv.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2yhvstmdy.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lukyeuuj.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2hklinjmw.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dmaodkuj.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2yfrnclqs.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2nhmvttlu.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2vguzgfgd.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hdjumgcw.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2rdenpqzu.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2qktkazkb.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2bieiacke.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2gvfbfdxo.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2eofsqcnc.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2wdvegehi.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2rjssnfbh.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2ndlqfkvl.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2gynyqmhu.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2ppcvllkr.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2zjdvtmfa.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2oacjddma.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2jspujqse.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2osirwjya.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2qglcvafi.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2jhijgkab.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2pzwdfxvw.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2nikrrubk.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2gcjcsowc.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2qgyjaeox.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2tvqhdwbg.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2ldqqzeug.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2mgbwtyei.html


<!-- 参考信息 -->