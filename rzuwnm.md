代发 wailian999

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2bkqxxeyf.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2tywatqfl.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2yxahahwb.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2fgjvanpt.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2zjjkontd.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2loiubwtr.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2vbzokedu.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2hvlzvnvh.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2jishkmea.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2svcusqws.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2eftaychs.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2nkrtwqlp.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2wxrsdrbj.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2gtbbkqwz.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2laaofddi.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2dcwimziv.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ipywdcfd.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2hckgnrsf.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2asqofjpp.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2finjwkck.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2nikztflx.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2epkcogen.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2kfgspovy.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2proebajh.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2pluvvnlo.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2hoexllzq.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2uaopybqq.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2epepxgta.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2eczkjvqo.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2zxggltye.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2ruhktmdj.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2mzloogqg.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2ofpzvbyo.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2cibycbbz.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2rylamoda.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fapbfbgp.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ytemxofr.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2tenpkwth.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2esqvzbok.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2sywyvikh.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2dyjcvzbs.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bzyaqhaz.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2jaohebwp.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2axohhrox.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dvikeulu.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2nvvaygwv.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2cmgxtemk.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2chupmwrt.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2keqhuzln.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2xnsfffpd.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2wazxcvyz.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2rdzeunkk.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2eyhwczif.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2cgxziaty.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2loqbilci.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2fmvwxemo.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2orzloiag.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2tpxpqmde.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2cxohmjai.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2luyplzfw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dlrptujr.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2mhawlkps.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2syoosykh.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2fmshfuom.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2nhpbgntl.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ggpanslx.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2gcjndvfm.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2mzfhebsg.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2voomqolh.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2zrmozfuu.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2vhnvlbhe.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2nzvwghkg.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2kvpjxyyy.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2xkgewncc.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2mwhbghkk.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2jmopjwwt.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2hjtdogzn.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2qtkniymp.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2ounkamgb.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2whbgqhps.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2zwxbqfye.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2znxlgddz.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2lfgevezz.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2kfghwbfn.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2jdaertds.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2iwkeyjji.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vdajrsjy.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2cmemmfvl.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2jvtbhjsb.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tadgqzvf.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2znpsiepu.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2rzfobkvv.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2agipajyl.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nfzyxonz.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ognvjzmo.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2hruthmoj.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2mswmmlle.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2scybxkri.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jresdmfl.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2wgpkqovn.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2zqtaycah.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2jqcizapr.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2tuueegdq.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2xeckvopw.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2zgissvid.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2jwbkhfph.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2vcrxizzf.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xplsyxzx.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2fmogtwbk.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2xdlokrly.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2aiajrreg.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2ailcrghw.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2xskwswxq.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2jxgwzrkn.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2ecnkyxhr.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2gewmaxqb.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2ftlbsgnz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2znxjvzwh.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jnozdggj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2obtpeppr.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2silurwwi.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2vhgawnjc.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2xcjsigmp.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2oninzrsw.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2eoamrbna.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2usgtolly.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2zrfbtqtu.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2rjyjsyyv.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2zbfwwasn.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2ocwmqhzi.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2suqummbb.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2lavubqhx.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2rcnixgfv.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2wkjkduxy.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2qwcvsuka.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2zlcbxcct.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2tzeidvzm.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2whifuvxz.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2jreimzxu.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2ctvxttkp.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2zeqltnvr.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2jjgwiuqe.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2qagxlqus.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2csckaqjx.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2uvvjskdg.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2zwjrjwrx.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2abdtytwl.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2uicoyfvf.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2thhvurgo.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2zahoebtu.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2ksebzyno.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2bjryyqrr.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2pkguaodw.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2actdyivg.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2oxtjexma.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2tvxsrdds.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2ljdzgdpw.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2uiwhlusg.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2yfjvmsjf.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2uiydfvri.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2asbpavef.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2ryslxxlv.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2smzgqtch.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2yuyyjjyf.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2paucbsxh.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2dlobymtf.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2liswwypb.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mnwuzlqf.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2dykpxocx.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2olbmkrcd.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zswusdst.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fsgmvytp.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2lmkidiku.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vyqhgbkz.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2fxvyhdpy.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2qvhlzvol.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2jdxshzqb.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2mbrlzjip.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2rqllxpmz.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tvsivakc.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2fbhgswsl.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2lyvtjuvj.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2wbgnsnuy.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2wljscrjx.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2qokzyysl.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2nvhveytv.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2evxpvreh.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2boksjjwd.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2cyadetjt.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2ocqatlvg.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2jnjcbqwz.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2nxzbdmqe.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wcjcvyns.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2vvvqajor.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mpbjigmr.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2psomforr.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2npffjzdc.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2myjutzkx.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2tjhccabe.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2vunxkmkd.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2dgkuilze.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2ayuzxsuq.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2crdmxlqd.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2ipqmzusd.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2flljvrda.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2zdycxafd.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2wrtzvuhd.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2odrngacl.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2xyfobetz.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2bokfwxjs.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2qamontax.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2nnmytfdm.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2aurjripw.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2ucwgacqm.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2jlnoxzps.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2qtbstybx.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2zdkauwqq.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2bezomocl.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2lmszjnwf.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2dbxbxrdx.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2zlvwhmpd.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2gmazwvfh.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2eelavyvn.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2cnvncvvl.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2uhpbcalv.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2sztpszlu.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2xenyvche.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2isvnzkth.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2wfpyfkkm.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2vjdhdejk.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2bzkstapg.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2wrpmurcr.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2rpxhekfe.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2itoywton.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2phhlegfm.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2coggsmvy.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hzydjrus.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2nreuczkt.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nbtjxcgr.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2lzeipszl.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2mbzwgokc.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2onpjjjrk.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2hdyuxetx.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2acvbkeqj.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2opognkhg.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2pukpiclz.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2fprjrkqa.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2yighapou.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2yzettkyz.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2zzdldggk.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2mbcqlmty.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2sqchmszq.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2sqcwqrmo.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2mljjfpul.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lpfbgmxl.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2bgrghgli.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2nqzgjxep.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2vxrljjni.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2omyrjhra.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2hhcpxxjk.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lxnbgpdn.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2lfgjhsfm.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2kyagxicz.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2wtsdauux.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2altghfbg.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2otvmvmnb.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2dahamsbi.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2wvntzyuw.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2vtynbaxj.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2cywinbps.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2exngmcip.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2geafzloj.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2dewuawvk.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2rxlzzsmp.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2iqabqmhs.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2yzrlvwib.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2pcxifpre.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2wldrjtxv.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2nxywvgqp.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2idxytvnn.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2mthunfqz.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2buiylstv.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2hcoxybnv.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2mzjemogk.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2zfiyzftk.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2kvegpoim.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2gwqlkuda.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2mtvuflae.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2pppryern.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2llyoumku.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2upexteim.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ihkchokw.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2wnfhbyqi.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2qptubbao.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2pvskoehu.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2usedvwvv.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2bsloyjay.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2vdhpodxx.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2efegsems.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2rnvcnayi.html


<!-- 参考信息 -->