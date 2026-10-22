代发 wailian999

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2xnsyycmq.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2xpgldyah.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2rpnecgks.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2ilzbbmgx.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2octuvzit.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2wjdcyxij.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2xmiermsp.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2wsimpcsn.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2wsfpqwqm.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2vsbxfvjm.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2jevepyej.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2bqwgtkvn.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2tqkgwaak.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2wsrjwwuo.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ceuocjlk.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2pdjdardr.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2wyeidgwb.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2pcrkhyei.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2xtongvtb.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2vbwpdjse.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ikqtlvml.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2mbhisuhg.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2xgxmivnf.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2lscptasz.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2smddpfmi.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2jfatgdgi.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2wuuuemgl.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2aertbjng.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2iqfubcqp.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2rubxajiv.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2nigcfxmo.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kyryuwjd.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2gwtzvjkd.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2iwfwtgrg.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wdhubjcn.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2ylubchxa.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2waxkitzc.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ojtaxrfw.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2dqdzjfxq.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2jmlvzatk.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2uzbjrted.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2egwufjja.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2ontlxndf.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ltbviezg.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ueshrwzy.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2sauuaagd.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2qthbkvna.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2iskuofaa.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2lbaxccso.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2cfilkjwt.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2fewyyzui.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2rvoohrtt.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2hfhueblc.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2udmfmsnx.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2wzemkxyb.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2bpffxzqw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dqjibpho.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2wevkuoqd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yuizplzq.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2dpurzmes.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2ulwewypr.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2khtodwqs.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2dcmdvbsu.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2noqriylz.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2bsfifqml.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2agdeiook.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2hxxdumlo.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2jbwixjkw.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2zpoiiepm.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2wvlbuvju.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2krbbeatg.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2ukfxiukz.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2uotzxmuw.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2lgecxicj.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2xsosfksu.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2thgxwjcd.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2ixanfzrm.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2dexpxgtf.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2buwunaxb.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2laigotzk.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2patmhsrw.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2rfqavxcf.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uzpbfpod.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2fzblmukw.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ujabapvl.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bfoxecuh.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2xxchpmgf.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2ecgoalvl.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2iyfmdxdv.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vtexbhqr.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wzajgtzu.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2hljotecq.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2knjizpld.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2fmmrxtng.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2oisllvcv.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2iigxzlsa.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2ykljgsvh.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2lbkgiwrd.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2djsokobv.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2wmgohscz.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2liujuyfg.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2wqwcqpkj.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2peugpwsq.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2dqtpjzvk.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2kyvbzzke.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2ibuttqpx.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2xxtgzadc.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2vworxpha.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2ugfauhai.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2rxohslhr.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2svvoxuvg.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2ivyoxkfl.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2kdbaticx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xfvtqtnj.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vqanrjti.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2izlgbtnb.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2cgehcqjc.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2tjietcjo.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2jhdomevu.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2nadvbiae.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2opqhbbqy.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2itsymtdo.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2hzxotcpn.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2phpmrpup.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2rfybkizq.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2ipbdstid.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2xylcolgr.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2qhfynvdj.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2pcaqhmrg.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2jrywmsmu.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2lauqdpdp.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2znpemhje.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2icilvgkm.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2xvojuazg.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2gkydhvod.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2ehrzztjw.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2czhpipyh.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2nkpdzrpl.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2iltvfprw.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2lrzjkkza.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2acasvbcx.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2jqhywkze.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2nwkfxbxv.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2bmbbvvqg.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2gjkpjvwj.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2syyixhvj.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2ehgbjjmm.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2hoieuoaw.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2ttkwddpv.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2bmlwrrhl.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2opcohbzx.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2dlhjabvd.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2xjsejwke.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2qxmlujuj.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2biwifwqg.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2puunrdjx.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2helrvdnv.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2harrwuig.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2lpxloido.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2ibhxnvmj.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2dzprkxgf.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2cjxzqwxv.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2qrsthncx.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xmunmxne.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2singckiy.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wzgehymy.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jswqembz.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mxvezhrg.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2iowoefkg.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bhdgbvgv.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2gbnofdiu.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2jusdokuf.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2cxvjkkth.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2wbbgdvkv.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2mrthjtwi.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2devmquco.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2gvaddxjd.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2rbgkrozq.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2sbiabqyw.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2jfxutnea.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2oytangma.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2dkzumglq.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2lurynbqa.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xfwrngmk.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2svqbcolt.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2bymguhhv.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2tebskvya.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2pxzckwti.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fusziifq.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2ofaudqnq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2riupfdfl.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2kbxeqwtv.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2dozznqte.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2ysnupmgr.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2gvncscig.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2zpceqfuk.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2qqsffthc.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2xgyrhwka.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2fptnjjjt.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2jnzvwhhi.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2ckcydtrj.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2liqiuhhb.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2aoeonqvd.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2tlpcoppz.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2fwlirerl.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2cnxlceta.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2ucqmehpi.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ztwptfxu.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2jvbomwmd.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2wdieegvy.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2pnlyqhih.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2jfcbxaec.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2yezeilbq.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2hcxdbsib.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2hcftpurs.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2dxdokznz.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2lxgulxsa.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2tmdkvgbb.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2clgmjocv.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2crfejoqx.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2fgztqify.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2glalasea.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2nvatkfbf.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2tdnhiqbp.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2zqabhdxb.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2wazykkeo.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2iyabinfu.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2fcjfqdch.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2wvzdltvs.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2lhfgyinh.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2toavcghf.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2regaygfu.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nbuxxske.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2mmwiwqcl.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2yyerzkdc.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2thdyycsh.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2evtrkjkb.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2keoodyqq.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2dtvtlncj.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2svqxvuft.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2bwsnniyt.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2vbmvyofr.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2cwhifddy.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2cxmmzjny.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2rzkujjoz.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2kqeinezs.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2qufobrbd.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2rtmczgjy.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2cqxrdtni.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2dbuchmvc.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gwhqqzqc.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2qkfnszaf.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2fuozmgqz.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2voltuqxn.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zzactdhs.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2hzvuntse.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2arczcfms.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2msbxgjzn.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2vadfnlmu.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2hkpgqpko.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hfqhiivy.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2hmwuoigw.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2kyeswdvx.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2qjfsalkn.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2yuztlrnw.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2aatlkvol.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2jaqgbjer.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2wdbftbgt.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2zynxipzo.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2jtxlljso.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2egvwjkbn.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2aqqboiwe.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2vqzjgdii.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2zckoarsu.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2xcsttnoz.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2uykimkxw.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ypodlxwx.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2tnyhasoc.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2nnvtwxch.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2jilhthwb.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2nfhtnrlj.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ajufxwbi.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2eunqfzsr.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2hdshfzkq.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2aeyabaif.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2lsdvjecv.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2ahqdbtyj.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2wxrelinu.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2myrfkhfo.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2afvpvsjp.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2segumbfh.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2klcqfohw.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2xtyddqad.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2jaioczwv.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2fbatqqyv.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2xplmvklf.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ylylsobs.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2ypiitwxz.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ktwbnddm.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2jdygvsyg.html


<!-- 参考信息 -->