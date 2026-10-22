代发 wailian999

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2haojbgux.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ugqzmzoh.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2iavxtlck.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2mdkglamu.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2ttyohari.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2plendjpu.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2gbzpozdm.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2zjzfgtff.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2paikptjo.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2eruhmvif.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2cfynhnmo.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2eyveowni.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2tmwarpyn.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2cqfuqavu.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2cthkjscg.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2iudmdddx.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2ixtzscnt.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2gxiaflzc.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2gxrxlmoq.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2nqkaonim.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2awncofxt.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2mnmargdy.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2iedtetbh.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2lmiqythk.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2xqqjkiuv.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2rgdbrcdv.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2vucnsrtl.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2tbhhlkjw.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ttmqbfcl.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2iyerydrf.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2sxuqswdm.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2zckcnwhp.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2iatlppea.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2wkfhwefp.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2dsvqqsio.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2udjmzagy.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2npurutou.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2kumghbug.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2whzeidms.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dximiykp.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ivajhbzz.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2yakjmhda.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jpdgfifb.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2wfzklxda.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2syvzxsix.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cwsmfved.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2wdtsffer.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2wzrllqhc.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zuhpnqyq.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2ramgoaej.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2lboahjns.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2hlkgvfqr.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2soywwkxb.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2mkwjjjqu.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2njjsjbis.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2cgrllvjx.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2qvbnnkli.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2mwfmczvn.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2wckemugh.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2mcbkmmyh.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2cadpgfts.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2zxujvase.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2tjealfsy.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2wqivpjmg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fquqlpmk.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2mpvtgbtr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ffsbhyte.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2fnjiklnj.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2obaulnip.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2enzamgjk.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2qedvxetc.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2uhlamgrd.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2stjznmkt.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2gvrdufka.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2aweqmjus.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2nhiapgxo.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2iarpxgcg.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2talxxnzb.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2kuevfadg.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2ngmrodtm.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2wvjezjpp.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2szgsdtob.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2mdreldlx.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2csaghsdj.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2jdbxphdv.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2qipvyjiw.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2xuhaycag.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2npqmwydv.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2bcryfaxt.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2ozcotwhe.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2frlqcbex.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2farsypcw.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2kewannmt.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2osaofalv.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2olrpmsdg.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2fasoovjj.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2licyduph.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mliddetf.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hpmqzcem.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2uagnmjxb.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2epycemqc.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2jopeyhye.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2yrepyiqt.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2hnhkygwc.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2sjqjjzdk.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2oyuocbow.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2bomeczra.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2uygdrptd.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2fojednhh.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2skvvrexj.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2jurnlief.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2sbfrqifz.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2fltfvpby.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2usxcyuyk.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2xcjghqnf.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2tmidkexw.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2uzcsbwdn.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2wjxpfmid.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2zvefpnga.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2dcgcffty.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2kosiqowh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2garbmkke.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ezpuvmtp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ywddhrfp.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2vnezwteg.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2sfhgbcmy.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2zoqpczby.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2hlhdpyxw.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2jotqtadn.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2gnuruinl.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2ugdpozyi.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2wtsziuvo.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2tpipzxhh.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2mkvobbbo.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2jakinaqt.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2jtckkptu.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2bpjebqvf.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2oqvxssax.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2otvdyxvc.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2qbhkmllt.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2osuabxkn.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2nesauame.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ckynsisa.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2xkwgyeov.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2iyhmwqos.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2cbfqcrwg.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2prvplhbj.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2zeckfbnv.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2iilffbzf.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2tgwlsmcj.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2zbhnemol.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2svbjzwxa.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2udwykwfy.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2sumsakpt.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2knpklycd.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2zmxnxrrl.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2lnfhxzqq.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2axkbuuor.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2lcogwaij.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2whghfhte.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2dhopjxpi.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2kpnwrubq.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2dnauvmhh.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2dnwuukaq.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2zlugfezf.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2utgqsabf.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2eufgppwr.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2dhiuxmju.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2cblirhfg.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2dxmvvtgs.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2fadxlvoc.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dhipqiae.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2qfqutrmj.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zpenlvqf.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2couwgjex.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2behkjshh.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2czeukahf.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2okqjobwd.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2qjgcxyqs.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2rzwpsdyn.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2vjxnsfxh.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2hkxcfoxp.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2aacoylwl.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jwviftqv.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2ftbhmmde.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2btonmubv.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2sejwadoa.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2aexflfbd.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2fngmtzgh.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2qlmlantt.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2vyetfedz.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2mqheprlc.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2qcdolsqz.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2gjotvlzl.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2kmdjhdel.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2pcerecvj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vgazecea.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2ohdybuyo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zetvupis.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2kqjifkwp.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2hplkncvb.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2poeoovfh.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2njkpjztz.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2ochgqobf.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2gkkywoyw.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2hoczyfzz.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2ycxzcktl.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2gaksxlle.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2mbffudsc.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2hqclzgaj.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2nfyohfhw.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2fmaxuhnd.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2ahnbobht.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2gbmriqej.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2stfbfzsb.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2hjlqrlmb.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2zwxvtjgo.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2luxtbsfj.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2hijdojzi.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2umdlpdul.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2cukmfcyr.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2zwxblytg.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2pebcyyax.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2pvxoeznd.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2wcpfulrz.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2tdmxlygc.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2caaqwhzq.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2fvfmbopg.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2kkdbriok.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2dzoatbdj.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2tlayfwaw.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2jvjmzfqx.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2wlckbbzu.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2iajnmquf.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2hyasvjjy.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2adjvhvvy.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2pymhkczw.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2myllrenj.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2lnukeoqv.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2fhsehfez.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vixtbcmw.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2vtcpsetv.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2cbhzswyo.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2fztkywwz.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2mpahsaya.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2fvejnylg.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2fygmogbb.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2zelcgsdg.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2swmnmwno.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2myyynceh.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ucyrqzkh.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2ahcbpejl.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2sthkdgoc.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2tsltwrhl.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2pvmdweph.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2mmeuvtfo.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2htjabhzb.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2zpfbsxgg.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bpyjyfwo.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2eoyzmcbp.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2bfmkzvvz.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2sgjfksch.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zgptpswk.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2bbuiwglz.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ncoddqyw.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2nvyygimx.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2edbzalec.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2fjhidjik.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tgsvmcgs.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2xwayfemv.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2wfhjjfnu.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2dcpwrpoo.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ubhbmkkp.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2kiiogzdo.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2xpmtaojm.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2fyadgzxb.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2wqavtsjt.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2ebvvlgeg.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2deevwccz.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2gvgnmzjn.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2dhxqludz.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ziixkzuw.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2quiwbxxb.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ekocyjan.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2vtjaxaca.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2rrkysudf.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2iuewmile.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2cytgggzu.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2sanozmvo.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2lqwkjjnj.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2kxohrsqv.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2tstgkwgl.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2gjqdwcxd.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2qhlactuw.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2doczhzuw.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2bfeurdwu.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2clwkvkrq.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2mroqmrhn.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2xyjxaemp.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ogtxubru.html


<!-- 参考信息 -->