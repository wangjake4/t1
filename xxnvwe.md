代发 wailian999

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2qxdustcl.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2pppfdtbd.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uhcfjykw.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2laomgzip.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2efrmhlvg.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2elcigvgc.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2utllsohq.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2kpejwyjw.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qturnidr.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2zewlmzwu.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2ziwndkxw.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2rpgkqwsd.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2yknmtmfe.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2kbzehjkg.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2tklpqyee.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2intcgtfa.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2rwztzblg.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2tygwfaym.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2lpuxyufh.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2brnhpzan.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2olbxsijg.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2tlvidlio.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2werbqvck.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2qolrgfvl.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2enqtnygx.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2zyspsscj.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2bjysedvm.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2mqodkqhu.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2lfxggvaa.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2xgdmifkj.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ojoyxowb.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2qtqpjbxf.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2qelykadl.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2xkbhxhmd.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2ilgusezz.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2szcykkab.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2xopzynnj.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2lbwmytxh.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2awzdmksr.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2fgvkbhcu.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2dvqjgkxr.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ttvqhwfd.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2djllfhgf.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2kpxfyitc.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2zxozjqor.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2yeujgpru.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2jwwvpwpm.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ohoyzpyh.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2bfdrnhad.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2cgxozgge.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oyktmznt.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2jbtqbmcw.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2grgbnxmt.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cfymvwft.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2nwnctmbq.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2fjglbhim.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vykgxgih.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2amwzjvvo.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2lmvrwxqh.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2hjwakevm.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2hvatlyjs.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2pbwgrryf.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2rvgshzyq.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2sqpkrctf.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2ewdzxtmr.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2tettflov.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2kebeacmf.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2nnylozvq.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2jwyasweg.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2wmrstmpf.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2togqfzhl.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2ltcvnsjo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2alulsmyn.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2ijoitydr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yiibfvsv.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2tfdrhewz.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2uiyexevk.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2gfjgadmy.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2wbryohec.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2rpczrthk.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2wubzuxvb.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2lckbaeov.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2wrdmprgk.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2pasiwsnk.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2jnddijap.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2qihdcnho.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2nfoxsska.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2wtzpkhah.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2ecqlintu.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2ykwbojvr.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2dnidqeus.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2zecqsmkv.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2fyhsozwd.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2hiblvwma.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ofenwhsx.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2zllerfmt.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2msxlbkpo.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2frlgegiy.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fiaomkpc.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2giaaxrnr.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2qpeuplif.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zjdejlua.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2yzejqoqd.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2tgubochl.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2exvmfzpr.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hufgxfvy.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hutmfqao.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2phnszluz.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2zpggbqnl.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2hzdmvqoo.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rtrgjlbt.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2mnvqfyqv.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2mrrtdhcw.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2sntlzstk.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2whchbale.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2blfbbrvc.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2matufgzb.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2ywooyqhe.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2gehaxqpk.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2faspjewl.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2jbpxlgtu.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2cvssyyko.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2tvlxdklm.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2qoxboxvy.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2wkoptmtk.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2cunieqiz.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2igscigyh.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2ffwlhfcz.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2fpsrfmzc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zpdfasws.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qgmgkhhe.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bydbcdrr.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2cqoticuh.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2ebqrwdoq.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2bueicbpl.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2rbfrweuz.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2jpxiyfrf.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2yqwdrkun.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2fdeylthz.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2aspyznpr.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2jywaitll.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2eovktyqq.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2uyorbqio.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2wnaqwcif.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2qicjvdox.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2nmksnkvw.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2jybcpnwe.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2daonynkd.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ziqlouos.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2nadnasto.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2adcvgcbh.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2bdnctuou.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2cuceuoeh.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2vkkuismx.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2rcsqpvce.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2flgznety.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2afuzlpoa.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2lyyrzngg.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2gwlubnbq.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2bxjknxnv.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2anqietqh.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2panjbrmd.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2tzadryui.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2xexpumvt.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2mkgikbbp.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2ntuuizie.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2leaeazsi.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2hnbglrgm.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2jprqagsh.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2vatdqqgk.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2njawfgps.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2wlpdqbuv.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2pqfgqgaz.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2ascjxhcc.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2izrkgczm.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2dhfrbxsk.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2duzidsuj.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2uqdbions.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2xborcqps.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2evktzilm.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2uzfllyuf.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cufikagy.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zvfxgnxy.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jsyajgzv.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2cxxvbbwh.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ytwavkkv.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2seoapyaq.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2alrhlrhv.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2cycwrsjc.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2oqjgclzo.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2pbbfrzsk.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tgbvbbtn.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2wnpspdop.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2zkrhmzka.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2migpxepp.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2jojmguzj.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2fzzcmjgw.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2xmushmjn.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2pxrzagtb.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2svfehrva.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2qerqwpin.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2ajvxloet.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2jxcpbjbz.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2rvueqjsb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2oitssjub.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2uixerjxm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ulpaoxri.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2uqyeqaze.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2zddsqxiz.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2yzroysgw.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2bxfwxvkj.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2nszmwhcg.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2wniiluiu.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2wnnuuwbr.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2ygxldoyz.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2zmhszsfh.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2gqfrolzm.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2ciabjdfo.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2xtejwxec.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2kbuipkum.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2otvgbjdz.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2kujjqvnl.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2ybgfzsjy.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2skwswazo.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2hyxlcklt.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2iqbfpadz.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2gvfhndjc.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2gqwrguch.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2hemyjghj.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2bikoemph.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2yfwzlgbl.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2etqnvcri.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2kflviytw.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2taayvmlk.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2wpbhlwoz.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2bdgvlsxo.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2zikabgnc.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2xklapcte.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2sktjgxjw.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2lmaczkyh.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2xvxzwxpv.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2qjqgqnth.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2ioifuhdq.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2pupyxgsd.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2bvkfpaev.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2fwrnskpl.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2wklpmeuu.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2kkrkgysw.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hyomhsoz.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2onsfpqww.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kyhxfhiz.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2rrhltqha.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2dyzxruqh.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2rwfisogr.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2mzjiqbop.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2qgmpoyvg.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2ovasczxy.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2nqbinjfa.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2twcsiyyr.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2mkumgfjy.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2lwhjjhqc.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2baudvrvw.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2jogwmbcj.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2exgtansa.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2uwnppzhq.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2xfnvpacd.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hjjqgxgt.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2bohzwpbs.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2assaqwio.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2mrnzprtb.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qebaxhsm.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2yapiolyg.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lkzyydmj.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2eichdire.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2aygzpvsx.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2rnkynfex.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mdndfqof.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2lghcqtys.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2xhqsawgz.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2uydadmxy.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2pzpsrfqo.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2hlaaymqh.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2pwhfcofb.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2llpcmwbg.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2gkkxlqtb.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2sfdlxtxa.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2cvlrbzgb.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2jubupjcw.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2umtrwqht.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2umdacecj.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2uymddkqo.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2kmyquogp.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2smbwuzrh.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2jffdxgsm.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2xrptmovk.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2cofvcffr.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2axyygzea.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2cfbqlluc.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2kubwgnly.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2nsptqswr.html


<!-- 参考信息 -->