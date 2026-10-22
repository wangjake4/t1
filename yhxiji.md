代发 wailian999

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ogrlgjjd.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2ckovaqeg.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2vxtwujuk.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2rxophqfy.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2uihjbaaf.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2clpnyplq.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2vfhtrxbq.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2vpxlhjdo.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2mpolzhyf.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2tuzzrwqy.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2hrgafjpt.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2pyjsnbhh.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2rlieksfa.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2lojilnmw.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2rhibkpmu.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2yxroukuj.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2dffcgaci.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2fcfonyar.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2hgjrrsff.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2nrrwoacs.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2ypsbttld.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2pklhdfld.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2rzqvdfcw.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2emyfrvnj.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2qbxqneys.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2ygarnohl.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ezhjldbi.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2uivpsbth.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2tiynnqnb.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2pccpxrgi.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2nfgvezda.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2wjxjnqkk.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2aycxdvud.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2pwuiqxgz.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2gvjkwvil.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2xjdltcaa.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2dgvfuurb.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2pbqttpog.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2likfgbda.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2svhpapup.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2zttwrhbm.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2eyaicjto.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2jgwdairk.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gqeiujvi.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2xqocvhbw.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2dueikikh.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2drvrrruj.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2nhulsgno.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2esroforz.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2irmcdzsc.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2nsmcohxu.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2fpckqjwp.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2woksaqja.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2dwxlwzum.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2nwavfkkz.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2vzcuinie.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2anavqlfs.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2ighswgbr.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2khcpqqnr.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2llqzpboi.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2oktqifwr.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2dbhjsiyg.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2boxqesqb.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2gqvqezud.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2xbztxcri.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2svedbtlw.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ooufrxgy.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2oddluzpd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ibalflxp.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2jmucshja.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sncdijrp.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2xbyepxaz.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2dmzdcvaw.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2lkzgxngh.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2hrshbjfo.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2nbxaxbwe.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2oxhnearg.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2izmmhuvo.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2lhyczxyv.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2whlcvqkl.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2xwgwybzd.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2vnvfmxmj.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2awtnkaev.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2kzueaspu.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2vbdwdgfr.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2rcfbuuck.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2xkfatppp.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2xcemeiob.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2nutmfmpx.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2pwdzifjj.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2enxgqmuh.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2xuhuuisp.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2pfhjdeun.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2giappakb.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jftzlnol.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2hnbttoaz.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2sjqxturc.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gwxjnwjo.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2dwemfttj.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2vpuwwjbu.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2ygtdnkaw.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2livbtbrd.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ztvehnuo.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2bxfiovds.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2wltjfhnt.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2ffnorugj.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kkzqzals.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2etpzehis.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2hizmqrfv.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2gfmxatdv.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2yqvplbfc.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2lofxyawh.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2gowtrpyg.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2gwyiccyx.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2nhyucojt.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wzfxsgpt.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2kyvcksfs.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2zhauchnl.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2xpsypdmu.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2pasuezkf.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2wmwacszc.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2drdehbaw.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2uvdepyso.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2gteeiecx.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2pclaivkw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wpxyjcac.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zztqhlyy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uxdpfdfh.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2wfbuswmh.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2jjzvfenv.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2zumzocqm.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2qztkmhgu.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2tslxbfil.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2zdrlalws.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2zpsreczz.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2kajjzvtx.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2qltmrqpv.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2kepkejvs.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2ynneorcb.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2kbjwtcug.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2cagcwqey.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2tyigmpwc.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2weyizbyd.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2wmhexnhn.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2fbmparlh.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2ccvzvvdc.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2romddado.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2aegkbcla.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2whdhsneh.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2etvsytah.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2zzaxpbbp.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2fpimkiqc.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2zhstvlxx.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2nurekkbc.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2kbolirsd.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2sfkyoged.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2nlxxodcm.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2dgxkzocf.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2zgdutvts.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2kgeagmsu.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2ycojeawd.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2vvbiwrvb.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2uccmzfcg.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2ubsecebf.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2iwbhhlmi.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2ljvejrtx.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2wuwblcsq.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2ufzsedhm.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2dyoxtnzi.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2jcnrydht.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2exojfmhz.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2plpnyqfy.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2jwdhvtyy.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2epzlqatv.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2etanchlq.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lngmvtsh.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2ajltyvyu.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ooikdpsa.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qiqcgnjx.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ztzivxtw.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2vwzsxtnk.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tzvxgkaw.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2cjzkhksb.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2kamjpktj.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2gjupxhod.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ysvworxh.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2oiqqwcft.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2asttsjmx.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2ebnjzufu.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2ectduvhj.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2xkoxqhls.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2nozekxtl.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2snjorumn.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2wutzacan.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2jdangldj.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2gkmwkmot.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2wvoxqtpz.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2rzshxcfb.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2wuxaaajo.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2qidhxcul.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2anfhmdgr.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2pqmstyqg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fbnoltqo.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2bimszwur.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2pnsatglp.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2ttwmzill.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2zerlkoyi.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2vrunmzab.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2sarbstxw.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2zsawchlr.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2vwlqwkts.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2gnmhyxph.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2uqqtuily.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2yrnxqglk.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2cbldtebd.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2oaulkdio.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2vwoomvhh.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2hcnmardr.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2gsuzajax.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2gbpldfbc.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2pdocqmce.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2wwuuyujm.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2qgstgfsj.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2jftbckox.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2bboiupix.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2pdybypqh.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ycyogxjs.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2tfpqglwx.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2mctrecmi.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2usgexytc.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2invzzutu.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2mfswthan.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2wxjbwccr.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2xzrjxdob.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2zonssyjm.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2mvfmzazx.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2zqhcxcin.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2pnkioyuy.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2uhlprrbq.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2yodgkqmc.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2joanvect.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2rjhutpen.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2egfdgrdv.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2qrhpvvjv.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ybpfthal.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2qcfzomit.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hbzywqvn.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2wyqsdndx.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2zbdinrom.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2jufzleam.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2qqbufrsi.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2bdzeqels.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2yhbzsaoj.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2tfqabckc.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2dnsbiklr.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2vsczcgdz.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2lxsvdcly.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2xxrvxreh.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2ryadtgxi.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2nzhwruwe.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2jjsmeunl.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2ksugeuqv.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qirernbu.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2clchbiaj.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2jeqycqrd.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2gvxmhcdf.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ffngsbgk.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2izdtfutm.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2paqdkbzm.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2vwmwctnj.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2disvvdby.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2czdybqxu.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qheaveza.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2ykdxwmjr.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2jmckjnne.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2hskpbuuu.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2agqcgiyi.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2thlyybma.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2dydtniig.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2igawlxdk.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2ledgybfk.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2girphnfl.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2aikljwnb.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2bxibdfox.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2zgjavjla.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2maycwpyr.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2dookzwqf.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2vsnpmuhx.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2dnaofhts.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2prbyqcrr.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2lqyhoidm.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2mjdvacwn.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2untlydlk.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2yavlhvqu.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2lwzkmvua.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2gifqzywz.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2tejfhiti.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2zzxtlmgm.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2skhkhtiz.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2qsqiolbz.html


<!-- 参考信息 -->