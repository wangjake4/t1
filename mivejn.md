代发 wailian999

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ifccympa.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2tqzgaynk.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2vpzozzxn.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2lphxndqq.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2zrdaufzr.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2sccorkdr.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2hxukbufa.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2nrhhkwju.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2yhtpujyt.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2yfxoqqfw.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2aoiaheca.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2teyheumq.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2mpihjupl.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2bbilpwnq.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2jbxeibnl.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2roezqxxt.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2qeeklnme.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2xikghngj.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2elnyvhzk.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2zzclipbp.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2nyidarkt.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2exggvjso.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2nuvhbuui.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2sldspwkd.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2vtomfgoa.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2xpknfekb.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2dhogfeto.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2hrphjsym.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2pvcpdbbw.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2suohtifo.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2duoqikzq.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2gbcliarc.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2dysgpvpa.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2abxicbrm.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2kajdzsjd.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2gejdqjiv.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2uarwbypw.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2ldkiyghv.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2hbclicsx.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yorwqziy.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2cctyagzh.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2hfnzeorh.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qaxyycot.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2twvqvsur.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2jiverbyz.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hlqxfcyl.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2poobqxcw.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2xikfnclc.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rqudwchp.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2ozaisfie.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2iugdhdtg.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2vldlqfsj.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2hveyqevk.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2ckvethmw.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2gelfftjz.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2briiiyjg.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2jjwkvrrh.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2emyuryzu.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2yzlkkyrk.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2gpwonpjc.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2htjgvyxp.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2dmpowevo.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2apncwrzt.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2yxawygbq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rboyihfs.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2ckkxqcal.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jqohgtns.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2jhxhrbnk.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2itnmmkbh.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2smijkdus.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2lhtyejlq.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2lzsfmktf.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2edyyxacq.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2xcmyhnqr.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2sbweqbps.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2bqwoylbk.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2jjqqzypa.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2dxolxysd.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2jphfzitr.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2aoprlhpt.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2jslermwd.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2tinrrohc.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2butkszen.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2kdyjttsw.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2qecovtxo.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2zaglrzbc.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2icmerfok.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2sumlveap.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2lqypnksg.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2zprgpovd.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eemnhhas.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2pytpyuxd.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2dqvhiwjs.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xilabtqh.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2xzlxblbd.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2lujzxpad.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2yktyiihd.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hwhpvrmn.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wjfpllrw.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2rmblejqx.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2rliyoyvl.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2wxhnwfxs.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wjimsqhu.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2ogfiegzn.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2uvfdafsy.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2fncmkuvo.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2wwbffknc.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2fbjnzvzi.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2aeextjkg.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2rixhcfgb.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2omkubhom.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2measjpuf.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2pyyokwgh.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2djbdrwfg.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2akrgaajb.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2ozwxmqjf.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2iasknwjl.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2uelfwwyw.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2cqnyjosd.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2ngwmrhlc.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2ztnftqsr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zqqwswtl.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2sajraatl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ygzbvoxw.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2ylvebmau.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2bingomzn.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2dwnvcteu.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2lheauguw.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2lrhwffcl.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2jilhtyjz.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2scbpbnbh.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2mfxcsirt.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2aexqdssh.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2vezxqpay.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2kmormmky.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2czmpdnna.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2wzkzujgn.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2pqospoaj.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2cxowmjbk.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2lvvvtqji.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2vnvclepg.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2nqpgpxgy.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2slshoxxg.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2ofhxcdgu.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2aorfptvw.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2uhoteuzx.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2uzvldejy.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2gvljcdga.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2sfavaqaq.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2effilxfp.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2igueppdn.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2rjprxepe.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2nnhtdeod.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2navbczyu.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2afnsuujp.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2zjehpsvv.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2bdymckmn.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2jujwazgx.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2cqyyxxmd.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2wvuvcgsk.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2uvszoiyw.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2uitpxadk.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2ylnazkyy.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2tagxpngk.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2jheacmrw.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2jlhbkpaq.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2vesxjvdt.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2wljruzqi.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2awbtxheo.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2wafbougz.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2ieijjgdz.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ukyblkta.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2urdbzlkt.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ielwxljp.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cucggetq.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fohhmazi.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2nwwbidni.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bpmjtrlk.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2grjhimdt.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2ofvidqqg.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2epvoowae.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2hjbuvqci.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2qjnwsiwe.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2onvsnqzf.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2ozmncpsa.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2silrwymz.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2iuusobvo.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2garhzggz.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2xijytvuj.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2qgyyardq.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2ynfumqva.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2exgbpygb.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2nbpjmnsg.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2rqjhcgmq.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2fbmmbptc.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2prczdnnx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fzugadfh.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2tyflvlrk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hcquwxyx.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2gbpdfoeh.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2wfhqhpvd.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2tokkydom.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2vxdxmjdd.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2tmkejpuv.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2nlxwerjw.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2naqevddp.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2tqvgpkwv.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2zcvplfst.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2gqhosnff.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2yqgtkgrl.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2onmhfdki.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2npgcisdq.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2azbranba.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2vslqxpgv.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2jngitdrh.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2fsoffdde.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2zdzacqmr.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2wdpmmdtu.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2fnnhnuib.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2ojgisfgm.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2azesozsg.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2lmdmckwr.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2thcdcntw.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2cbbtjqax.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2klosnejc.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2wehcqxzt.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2uqvsqarc.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2lwzciits.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2xpauxxdk.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2pftuhwps.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2yipbvxxp.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2qzirwojw.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2vruvstgk.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2yzigvtmh.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2qehidggq.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2aaohabrp.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2ahvbtiyg.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2vpjcztii.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2gwujqdwj.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2ubcpczho.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bgucrsqe.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2ghvhcnow.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vrjjvmxg.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2gddjhhux.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2yvqytwfy.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2mzciwtms.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2aimjxiww.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2exwnhpvz.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2urhusicm.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2pgrwfzym.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2fpicaacc.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2yzxgorqc.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2khxlgryu.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2nkubviwr.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2vselugxa.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2bnizlxjk.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2uguqdzaj.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2zohfxnhk.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2egvepall.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2cpavnxyj.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2klaqhujc.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2kessdfja.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2owvqfaan.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2ubiadylx.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tnafjpwp.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2eetpuscw.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2dsedwdok.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2ugqdhksb.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2neigagwe.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2puunmjge.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2merthzty.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2gztfrbmp.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2qfzprjpd.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2zuddeceq.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2nedkpcta.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2tybuicer.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2bespztfl.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2fpjfrquz.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2atptuesu.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2xjvxdvjt.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2hdcmybeo.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ntvzjxcg.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2xnvstkls.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2mvznrvoy.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2fsyvyqma.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2yqgnwbqi.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ozhgrfpe.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2xbtfqlaz.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2ndadhpuq.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2lnbsngqr.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2dxttzgce.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2fzljxsda.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2yntbmupd.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2uepgdxqf.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2diosbvhw.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2aumeowah.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2poaejyap.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2xmahjbvl.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2oaeynnxy.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2hphfflfa.html


<!-- 参考信息 -->