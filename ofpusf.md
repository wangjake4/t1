代发 wailian999

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2hrngdqkz.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2swrqbbus.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2knnsupsr.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2ndbgfhxu.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2stubyuxn.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2qrllshfp.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2aefbhxgl.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2katubtfu.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2higwerdk.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2riltfvbn.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2mdmuxhdi.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2dwhpethc.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2bppjxxlk.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2edztqobs.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2lawkpmac.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ikurauzi.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2zhdrkopu.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2aksjsijm.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2wkpouevd.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2yzvciwib.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2zylxdmtf.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2debcutcx.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ezaobjak.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2gslykxgs.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2auvjsgxj.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2bobsaksy.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2aqqxfivv.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ldnsvfpm.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2pdrbgwsq.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2uzjemoen.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2uzskfqho.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xkoridjl.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2sfrxtegp.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2fiymcsgc.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nldqalgh.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2enbfvinc.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2azcbpqzr.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kqlkeezd.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2qoxauqbt.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2dscpnbkt.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2uuhwechn.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2oxhfmuge.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2vbtpssvw.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ajxrgdkz.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2jcpruowc.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2wgasypue.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2nmzonufu.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2ujodhklx.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2lcjoefkd.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2jdqblqmy.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2eyktrhah.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2ixwkvvop.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2pkfzeasc.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2farqpaah.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ifihbmyn.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2btzwrxcs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fxffjbqe.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2wcgmdmjj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2momerbjz.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2aiixopbz.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2xjbeqkjn.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2yeinyjdj.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2iibcuguh.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2sdnecpyy.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2egutmwvy.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2ogkhpvnw.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2hywoffdc.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2wrsenehx.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2mdqkbzqi.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2kkwfnjxp.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2jbevtren.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2lcwbdilj.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2tdgtegkh.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2jdcpkvkh.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2vomolada.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2hielglkw.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2xfegnylz.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2etfpdfih.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2erlxshgd.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2rnfqggyo.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2rcpijuug.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2tlhmfyud.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2adoytwfw.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2alfdqrjy.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2mwjssogo.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ztgfsolo.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2lqfitfla.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2mqpebuik.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2cdqxtzir.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2uxkstaao.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2oyhcikhm.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2qimcirxy.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2kynjcepj.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2gwjbglvc.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dhuvqraz.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2kvkofuiw.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2kwgwmbsh.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2gkdedlnr.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2ctppssno.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2txsuxldt.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2rcrurkir.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2iojwqqgr.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2vbdykbfe.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2gkxuwfjn.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2ctldrfsh.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2kavxdqsj.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2amdkdciy.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2bxxsuwmk.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2xgoesqqw.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2mtvroqrt.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2stbjwfsy.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2irexirtg.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2toutdkld.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nvihyhlb.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2afzhfmka.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mpztaooe.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2murggglg.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2pzyqxbct.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2aflkjjxg.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2hvzyynwv.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2xdkyzzph.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2bfpidvqu.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2xmltwiog.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2vdicvaku.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2lexszqzo.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2qfksnltp.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2emssvyns.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2gbpnbsjg.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2xjvjmwel.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2elbkuwtk.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2hleiwfye.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2tmodpmpy.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2jjbgmfhd.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2gljirghm.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ejvmrfzz.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2bvlmmfmn.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2nktqdtdk.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2ljinywwj.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2ydkgroqa.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2qbppwnhd.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2aukbehxs.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2sjivyyqd.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2mpsqzqkb.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2adbcjapr.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2nqujmxrq.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2dvsttezj.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2dprtjqgj.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2mmttkarm.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2mphnskkb.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2akyrkgrc.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2yowilepk.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2vgvlzjnv.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2ixowoxhh.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2slzcajrm.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2twcdylxi.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2urotexep.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2zyycorzv.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2igcavgir.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2tipkroza.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2dpaabwha.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2sxgvoaut.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2miazvzwk.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2hmvsnmuh.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oewfhfio.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2twerofep.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2varofrur.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kueiconf.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lrrntmaz.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2zuioubfx.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zhzlsirs.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2bjqjoruu.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2vpewhkrg.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2pbeyjtmy.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2itneavsh.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2lqgnejoa.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wbvklpzo.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2cgelxucv.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2jbxcoiws.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2axzeorhw.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2ujmyadbr.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2fgvihrgn.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2wxihions.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2seonjwed.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2voljusoy.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2ecdvpqxx.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2ffaomnsu.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2efmtlzqj.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2lemrsetx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2glgmvbjp.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2nundumaf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rhvrzkhu.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2ujzyocri.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2qtcddshg.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2lrioddyk.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2lenwjftc.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2mdpfmfyy.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2egwsldye.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2waimzscw.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2qwlceyay.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2mtcgdcrf.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2ntmrbneq.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2clgmcptd.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2qtbuhwvd.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2gvabjzee.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2ollvbgbm.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2iiqyhibe.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2exrgfvgs.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2jhehaugl.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2etbbqknf.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2fpcauamj.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2eijdnslv.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2umnqmwlg.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2vpwjcwcc.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2zixkeadq.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2hohococn.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2ugukdiyb.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2zbbmjokr.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2ljrufpgm.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2ufssyijg.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2gxkbefja.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2kgkgzhau.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2jdzcsxqc.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2qweygcwo.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2flxusfqs.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2ltikynpw.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2skjquwij.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2vuavakir.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2muiwqhud.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2hgnsyjiv.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2assomttm.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2fxisrdbu.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2vqadnuve.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jagrcfme.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2yiptorat.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2biqnozzo.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2rotjxtmy.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2zfestnst.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2gmjyvzrs.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2rjfgmcdh.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2qdjxzakv.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2mfrhzuhu.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2yolijmmx.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ekfusglp.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2rwamikgu.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2klgkubbp.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2qqiqtrun.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2xbemclkt.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2vtgibubo.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2gmabslqt.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2vsihuvvr.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2davbwahj.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2zxxfxdrv.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2rjllxuae.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2ujjbjgwz.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wgmvyvxb.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2kfrfhhvj.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tewwibbx.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2clrhczzu.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ihgmjlan.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2rqloatfj.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2whxpshzg.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2cxtllplw.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2rypccfic.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2cmwxkitl.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2swuswluh.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2zlmcsybu.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2oycaigmh.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2ceojzetw.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2slyeffjo.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2hanmkcgb.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2bldbtmsr.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2elkppoig.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2nsnmujbk.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2fmhltmic.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2dxmmblkh.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2gifnimnt.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2czcppbkc.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ufggugzl.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2hvjqhdxg.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2bkmqdqzl.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2sfjgiodn.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2qsuwznoa.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2qrsjiisp.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2tbpnrwgq.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2xjmzedyf.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2fcfwikeu.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2vfqjydqn.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2yyrocxdy.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2dabczvvt.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2yxxekzqh.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2tzkdfjbj.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2hrmphbgf.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2fqmzfzxf.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2oafqknog.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2hlyzwuqj.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2tsbilsup.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2bpjbmcju.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2fkcjsnbc.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2gnefdpiu.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2fsbostlo.html


<!-- 参考信息 -->