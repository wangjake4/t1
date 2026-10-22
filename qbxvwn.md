代发 wailian999

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2jungdzbg.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2gtjzqfno.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2myqkrqlc.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2bdkwhtup.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2tjcuzsiw.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2cmapnvms.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2lixznpyu.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2wzrldsvy.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2gpheedqv.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2icuthxvr.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2tklggigh.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2vebpczqf.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ilblqths.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2oiqenapp.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ixisaykc.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2wzouqlgc.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2jwbruche.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2sbwiczgp.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2qxbqsgvb.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2cuufvovb.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2uhoxutaq.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2nuusbqfs.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2yhpmovhy.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2xrwtbwjc.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2kpbrgobr.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2wdoqifgu.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2zfebqzgj.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2qkxuvdlq.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2jccdwkmk.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2gfogecrr.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2uzinewjj.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2psjymtnf.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2rorxsnwk.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2kchiyxih.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qkpcrzst.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2cdmiuxdr.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2ttrmxmrj.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xzquwnxd.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2jzrsjuut.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2eqyxhbqb.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2brsmxotj.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2yykknyvn.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2yhqurona.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ojlmnjnh.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2vcoubaqh.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2iqxdbuew.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2symaasdw.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2unbjryvp.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2dybpglda.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2rdihrwdp.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2qnvnykpn.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2argtoazm.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2joitmuek.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2mjjvkxbv.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2gfnctbpu.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2midmhhwr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qrgvomvf.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2bywpazal.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zwixguoi.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2zrljhzox.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2exuhrjxe.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2jffzbcmr.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2gnicwfvc.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2nwueqwkp.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2tplfwzfh.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2bdoymwii.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2ytmxzvfr.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2uyhnicsf.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2tsnhbkha.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2tayzaksg.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2fckoaztk.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2oqksfqxg.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2cxvnzgej.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2ncuqvpze.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2thxznisw.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2mbusrzyg.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2iyefwdbx.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2volsoxai.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2xdwcmdtf.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2fgsvjmae.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2wdovedpo.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2ytehkyon.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kkegyqen.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2ighjdxsi.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2yuwaaiqz.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mwiqsqjm.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2gsfgxzgs.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2hncfggip.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2hiyfsexf.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fgmazpxb.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2yvrasxwr.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2obrpfubf.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2xwmzufvm.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2qslpdusf.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wsjrdkqf.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2kwizafkk.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2boiguypm.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2behhgqlc.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2guuruafo.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2nbmksaft.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2boheplgo.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2npqklthe.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2ekarwmzf.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2bvgjlnpg.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2zguoovuu.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2xafzuuzz.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2hsxupckx.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2vxxuytyo.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2zfluitai.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2zaxrvaui.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2ijcloeyr.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2akkdnddv.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2tusuzreu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ryqzaoyu.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tonbzkad.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jkbqzigj.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2zxoxgwhe.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2egtnyuaf.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2cstkxhgi.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2hblehrug.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2vnhrkahx.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2jxrcubgo.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2zjfgalnm.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2gptvszoa.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2pajyhbui.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2jmuunhxh.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2oxjwvgot.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2vrmfkziu.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2vwieybaz.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2mlethoye.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2kkrxhhue.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2niywqkxy.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2bbtdzfyl.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2ejuyhfuw.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2rumcjcqo.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2kdnaemay.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2phswlwtk.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2apqurnxl.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2tacozfzl.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2ktgrozzk.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2amidtzed.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2ymkelpjr.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2usmtdbso.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2tlwspfyb.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2mintuhmt.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2rwmaebjx.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2lbcglaah.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2fiyvalqr.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2vyrhfuqj.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2meqrixpf.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2sqaamgbe.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2vvvqadto.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2wkrwyilw.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2pilsxztt.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2lonrpsux.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2jydtnanm.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2bvzszyos.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2tvbfvkyq.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ibgbklup.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2pzdvwxru.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2dzlcqfyl.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2qvahnchq.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2dkdlbnut.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hbgemjfb.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2hiacaoru.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2umxxapua.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xubtvmyt.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qjemezyi.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2izalyocl.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pasotxza.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2dkygvzef.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2ihivytix.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2oquxijqa.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2efehjvsx.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2sodxyaou.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ddgarkrl.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2ruwltvwz.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2cpizijrq.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2zxbqbfdc.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2fotdomam.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2xuwirsgs.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2hnyfhzmz.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2vosxrxkl.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2sccznafa.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2hkukgbsm.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2wpfcxhzn.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2zkxdtlnq.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2ktjdkati.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nvopdcxn.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2fmrxfxla.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wiarbtdb.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2rhupdtae.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2lvkjtzxr.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2phfbiexk.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2pqoougia.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2mzxlbfaz.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2qcswzdff.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2skjahmjk.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2lkhzrbxo.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2rvlreghb.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2ldplgwkj.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2gretamze.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2drenxrfj.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2cdsjxbcd.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2ktpauxye.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2zwzzevhx.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2nfqepayt.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2unjgshat.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2jozaiofd.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2ihxzicwm.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2akbhasal.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2fccwrrgk.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2qgljisaq.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2izewbngs.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2zapbxnrv.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2pzzdopwo.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2knvrmpym.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2wxyiwxow.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2yaqabiuq.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2gollaocf.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2xirlapdi.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2wlsrjynu.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2lifuzkuz.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2louuddzl.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2uvjzaxol.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2bdaaetfp.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2hkssnmxb.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2vqnyivct.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2vvddiqvw.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2fbkpujdq.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2crknhlaw.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2cztzayek.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tohdzszm.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2cqzxjbsn.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2aakdrhst.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2lvfgggrg.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2evoejmby.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2seexlkah.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2ixkrknyo.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2qegbschz.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2ppsaepnt.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2gatsrily.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2tmfdjaxx.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2eapjomad.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2oydcqngl.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2sxhahuyj.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2jwewhgxd.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2lrrmvhtw.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2wlddonbh.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2ahmggenb.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ujjshstf.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2zyewxxkl.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2mtlzjclj.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2kpctzwwf.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xwywhgsd.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2jeyhqxuq.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nxhjyeby.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2xyfpojpa.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2iloxwkvk.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2pipuxfja.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ualsufza.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2rfoyycus.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2fxvqeohh.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2yhqrolnh.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2fjgpptos.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2vsvdqvom.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2dkhpzivn.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2ntyaqbyi.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2otkxsuqz.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2yoknxqkd.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2wfzpycrn.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2zvukkcwc.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2putafyqe.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2bxpfgcos.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2zkzdvriw.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2qszaoakp.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2vferlwon.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2mtacdfxm.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2vvzymqej.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ztjrfwyz.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2jrqtmxbv.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2cuzliqvb.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2nsicqqbw.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2qxgfxqgl.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2vzeiwfuo.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2qqmeuhew.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2zvwiwisk.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2znqvwtio.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2yhrmnxwq.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2ijmjawbs.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2mbpazliz.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2dxjnjqrc.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2aujkrlxp.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2nqsndyfu.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ftkuwjnf.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2rpuhwtst.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2hlflbtyn.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2pythhpxb.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2oedmjvxp.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2dudqdgut.html


<!-- 参考信息 -->