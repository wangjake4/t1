代发 wailian999

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xkcteqen.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2utajpygd.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2cdjxuudr.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2nwcwnsvw.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2clxaewzb.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2gutujvmw.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2lleogkvh.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2zxghngbw.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2yyngxvps.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2fvqknwfa.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2atnhnagr.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2xlsnnsle.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2nlkexmxw.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2kpvschwm.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2atfecwit.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2tzafqvzf.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2qeijmthb.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2pqdgjxfn.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2fwhzvbrk.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2cszelgmg.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2vehhturl.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2epxcjncs.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2jnpwvmhk.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2tvvxabpi.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ijoyfdfg.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2pahrhjxo.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2jiyfxlro.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2matppwka.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2rcekkctk.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2lfmqusrk.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2vorcbuqh.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2vtvjqoym.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2dxuzpmce.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2qflywwts.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2cuszjwem.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2trwvdlxr.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2yerqujws.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2pqljtnlc.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2fjgenzaq.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2wlybwlqm.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2thyatxwq.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2fuguvbwj.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2acgluiqk.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lrwxacyg.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2eutmfese.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2hlxxjnvn.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zfcklsbf.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2mvlvowbo.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2maepjjes.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wsopskpu.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2cbdbjrck.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2kiaihkqs.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vivhxmth.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2xutzhpho.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2orhrlccr.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2azvgvykq.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2iincjkac.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2vvolaezk.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2noqptzwg.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2vonudobd.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2cocoxkfz.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2zdwksadb.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2gzcwdilr.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2xrvipxfl.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2ltwvyrdi.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2njtfrako.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2igekpxbh.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2uhfywbyy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hykklmfx.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2xrnbloyn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qhgysbtm.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2kefekdkd.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2xjyofywk.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2rlkiwvry.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2htpzcyoa.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2ujnqvyix.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2pfgrvcgy.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2tpmdtfzr.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2xwoediwf.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2rkzvzgie.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2hfeshccp.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2waerewck.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2tsakywhu.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2vicvkiwp.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2ofcfyefd.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2jtztnsik.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2tndserhb.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2agylhhhg.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2rstariji.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2ehzfxnqb.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2dstgrmbz.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2rlgjeppq.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2tqzguvfu.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2qlttfihp.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yzwowoys.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2kvufcjya.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2caetrluh.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qduwrsnh.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2wfzdoxov.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2hrvdvdls.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2zliwebyr.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kmmwjree.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kdwmxhjx.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2weyaodqn.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2ubeutdku.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2azwfoova.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2osiehgnr.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2jfpvinzo.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2onlysrpk.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2lxqlvoly.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2oycwmdxg.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2citiuwms.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2htlclxuh.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2mzkjqgqa.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2phhjiikp.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2yixasmsl.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2ghfmudmm.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2vosoqzoa.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2hplekdfb.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2ymklewkg.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2olwpsrbr.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2qeaixgts.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2nyywlnwc.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2wnqphkfb.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2dnfziofg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pegmlovd.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2cmalcteu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gfhlvgwf.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2dhdnbnmn.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2vfhqtmhf.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2nrrwmtge.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2nlpkerqk.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2lokhgxqo.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2pkuojwbt.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2gujjtmbl.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2ypgvffmy.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2tixnhvwu.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2lkhwvvzh.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2usqrvtzo.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2xuhdpcnc.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2npnywpjk.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2itfnvmea.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2sgozvlet.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2wuokvehd.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2mexyziis.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2giwhxcwg.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2josaniqk.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2ijwewogb.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2cdjneire.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2mtpbfnwq.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2usnbandk.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2qvgdwxsr.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2yiaaywtc.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2gyiyypte.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2jrubhzhq.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2hheciuqb.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2rnvbrdmj.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2znsmyysn.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2mwkzftkn.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2mdohlzhe.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2mehqxgbm.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2mjserzmj.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2bpkbggle.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2ypttnsny.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2tuljdbfm.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2bqpkdpih.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2bsbingde.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2yyyanqre.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2chlvioqa.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2pmhjyqic.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2sbgkpafj.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2hsepgtoo.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2tmdrycpm.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2fblgewkm.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2ynprnlho.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bxhrfvvh.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2aixcltgn.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2donvuane.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2onbbcthc.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vklufncn.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2ukustejn.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dxqdjfrc.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2gdeqqnli.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2vreogvbm.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2cedoihfe.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2dmgaksaj.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2scuqvuyw.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2yocijdrn.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2ubnusggs.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2xipvzkqo.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2lhpzdxlq.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2agzmrlzz.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2lypgrwht.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2sbofewum.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2nksgkmdf.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2onuvvqsg.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2tanwgsmj.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2wlmyptid.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2fohktuey.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2hcesvleu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mrfbkgxq.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2urmogsaz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hqkaocqu.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2kiurnxvg.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2zzmgrnnn.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2ubajbmhx.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2fyzgjsse.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2lxmnsyfn.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2wsyfkjnb.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2bnnsywtq.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2rnttqmqh.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2ydjjcgep.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2mcpphcan.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2ypvawbxv.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2ejzfmwgm.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2qojfykyo.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2zrwvzbpx.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2cntvpiwa.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2qwqsshfy.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2sxycqutc.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2mbygbqpl.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2azgwsaie.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2xhgblijh.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2tnfxkllh.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2sbxosida.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2xfkkbsfj.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2thgxipyz.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2plbddoez.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2slsjkxzz.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2xjhgbmfn.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2ofdgbyeq.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2wtkqniur.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2mebtwaea.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2hziyrhfq.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2crfnzsdv.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2dcdpsloz.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2svdkbkcg.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2yompvyty.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2emvyvuqe.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2pzapbdjb.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2eifqryhx.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2ymshyiga.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2bxfgrule.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2tyayqmyi.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2izircdbs.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2xutpkmyw.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wpfgphhs.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2bfhscbcy.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2inttutiq.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2arbgstnc.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2mfeefrkp.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2vmwrptsj.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2ysglvyjv.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2drzwakmx.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2aoajvduj.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2bjeaztxr.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2odsbogty.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2jcglgklz.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2nqpuaukj.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2ozuodqqe.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2sqbxeycr.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2fmitdmfq.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xgzhjfam.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2mowpylaw.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2esedwdwq.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2ppictifi.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2cxmngowl.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2zmgwxktf.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2okejlkne.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2iwnmwfnr.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2qocizglb.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2nqxhxnhy.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rkwqnmjb.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2vvbaflvj.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2ymugltxm.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ppxpmpjp.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2noaaobej.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2zocnffra.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2ruwmluri.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2zxbxdzaj.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2vehfxioa.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2obrxxccr.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2arzsmcqd.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2wwznlrfq.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2emtoatrd.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2iyshfgwz.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2cygmvowt.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2cvyrfnik.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2pmgckuvi.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2pktlkdnb.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2uthrqese.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2fqcnxzac.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2qumefgbr.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2hnpapnvs.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2zjrtuvgk.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2uqsiutiy.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2fahhgsej.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2xlwintyt.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2tnotrnum.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ysspfyam.html


<!-- 参考信息 -->