代发 wailian999

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2dbqqdvjh.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2dqeetevs.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2acirhbgm.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ajqrxabk.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2hndbsffw.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2zksdkdnd.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2xgjnnnzo.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2mvvspuyw.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2khwuqtwt.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2locrxxvr.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2xtqxqjvn.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2glzsfisb.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2ockxggma.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2pbjvjlwx.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2tbjsxptk.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2ivlxmygl.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ovaxedvo.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2gzgwjzhj.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2hrbacuqd.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2muflajey.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ardcmvie.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2kbuicesx.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2kbatqxcy.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2xdmujuro.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2jjqelbaq.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2bvslocst.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2fftmitzk.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2zkvuzfev.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2ewgeqfsp.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2agjheysf.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2xyykkqvu.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ystpfwda.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2fvuemycd.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2brwjyyrs.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2uybgbcqr.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ffjwabmg.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2othceddo.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2xucctmzt.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bikcmilu.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2phdumdhx.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2prrdtbka.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jsvxayjf.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2znislico.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2wejlhlvl.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2yjgydcgt.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2fivpmpnl.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2lluoptcj.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2tsbuileb.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2vzyckpyx.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2ervbhjhn.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2qyajeigj.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2sfgflvuk.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2dvnqjhfm.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2coauuyme.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2xrlwvihr.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2lgebjzvf.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2dojgszem.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2slliidae.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2tfbgrpxo.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2jhefpewm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2panhrxnl.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2fhptdtdx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2piktvgbf.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2jpcaekxs.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2pkczelyt.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2mqsoczgr.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2difckzgz.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2wpnluqik.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2wfikrcju.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2dknpkqlj.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2fjiqyqux.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2iarvuzaj.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2ibwqehvl.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2euatupml.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2sdhhakms.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2ckkdbpqa.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2bzehdhgx.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2itrkynvu.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2cwpoilqi.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2esjbevak.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2nqhbidth.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2sxovmdef.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2sdgaiqeg.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2rolwejqs.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2uiiincrr.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2lrtyrczb.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ekcemnkz.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2bmyvqblq.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2uosvtaul.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zipnwxeq.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2uoobjohy.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2skqtjiun.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2ctmjljmo.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ozwfxpla.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cagubbwr.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2kmrmbezj.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2oshqqyqw.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2yjwoxtvy.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2uttyeans.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2rbbpyjls.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2igqanknq.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2pzafzcha.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2zmzdicta.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2meajapjm.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2wsthrcoe.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2itnonzhz.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2qxldwtkl.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2oblbpvih.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2cemeutrf.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2lnujromb.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2xsbddhsx.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2rouqtkpa.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2lwqdeyqy.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2ctgdgcwp.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2miomlcfo.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2bmqpbstr.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2aukliwab.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mzpshhja.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2orqfqhvh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cfsfusuk.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2lvkzsiuj.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2rjctosxw.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2tqdkrati.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2aracehoh.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2uraybxjw.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2dzbzyjyk.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2gyjbenjp.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2kmekiflf.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2tkijkovh.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2bmmynmrv.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2rdpjdyis.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2kibisytc.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2qvgqztyt.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2yyfqpzih.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2cofsiwcy.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2jxmoluek.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2tvvfkoox.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2qronutqc.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2znlolxiq.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2ehbbxuvz.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2iyxeawpy.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2vrsdmndz.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2hwzqhicj.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2ciemhbdz.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2owggxqbh.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2fermswwb.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2cyretazq.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2qhcqjysr.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2oeszpbvj.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2plbhkwxj.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2pqlespfe.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2bhzjbauq.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2vpxqxvhs.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2eyuibfzz.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2wiacobqu.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2ijxmexaw.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2kawkwvhe.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2ngawuqbn.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2pdxojoou.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2toitasww.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2xqxkhcji.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2gwaycdyp.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2krcfbrlu.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2xsgiyrcr.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2iigdmsyc.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2qvfbzgcu.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2atpkmduk.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vfubegbk.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2fjxilhlf.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nztvbrhh.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xgonnazm.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pzvfuljt.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2xufxbsrd.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qghrelsf.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2rvfjqluf.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2hbjlsvut.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2zotkojyb.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2eiucjgng.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2jkogqckz.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ahcmksxp.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2qgfiuhkp.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2qcbwqhgu.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2gznaacgf.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2yaybobng.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2cxikxkbi.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2wneoabfj.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2xlzukgyr.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2rnqkdbrt.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2geuhqvqe.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2znpdhdom.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2rsujbjqk.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2eemlpfzk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fbhtwoji.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2zpyawnmr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rrnlkhpt.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2mcskkldd.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2corfrjkb.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2utjphduv.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2lmuryhez.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2qdhvccnt.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2tfnouukc.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2wwtklnxs.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2rxhkvawh.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2mchblpmu.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2mtudigsy.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2ufevnvmi.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2yzcqiysx.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2egymcvud.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2smcikwzq.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2hnxdheri.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2kykgkjwv.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2olddxekf.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2lbfmcuvs.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2nrgoqmez.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2pttwpkzz.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2nmmzeout.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2mblzumtj.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2xbsasphf.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2lotyooxn.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2ksiuldlc.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2nacjxnvy.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2ufgtlupg.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2htzxdbug.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2pariefmq.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2celduiim.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2nbipcekl.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2hdwjckim.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2kedsseao.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2axzyvang.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2esmzxixy.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2ttxxqmpa.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2yksevegj.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2dxenfwkm.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2dfeiudfa.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2xlpukvir.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2xaiomuoh.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2yjiwvmcy.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2npsiyejn.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ywetdkkp.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2vmlhwexw.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2jopybuad.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2vgjabldj.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2yhijlgvw.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2vtbkcldv.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2ifzcopau.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2mplcgwnf.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ymntjroo.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2uoajfyij.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2hndhbbuc.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2nznvuepa.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2vqcqvjxm.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2sutcglxz.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2pdretctj.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2odvacaup.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2auvqpbhw.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2dkjxakjj.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2uwqtjrrm.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2xjzgskhq.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ymyohywj.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2bsgxzlxf.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nsiwsknz.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2taougrkg.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2vustdxcf.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2ukgiciwc.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2diqexpfi.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2kfnpunuv.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2djhccitm.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2qjiarfja.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ippcxyfk.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2kxdhqllh.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2ywwbvtfp.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2nuicbeev.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2tswjskbs.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2axttftwd.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2ptdtjkuv.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2gcmokiwx.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2pkmmaruk.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ttsrfcvr.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2pkjpcjci.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2qpnecoyy.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ufrcxkqt.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2sztsqkzd.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2fbdywxdz.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ylcudrfq.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2veqmwesu.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2wpypnavz.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2lrkmyktp.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2curcagub.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2kiceqpls.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2gfjktixo.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2gpcbbnbr.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2tgezcefx.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2izgmcyum.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2ptvdopro.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2evmgxwce.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2sxdttkpx.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2monxlfcx.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2wpmozkwn.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2lfjukfzw.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2jcfrgcxl.html


<!-- 参考信息 -->