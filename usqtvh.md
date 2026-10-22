代发 wailian999

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2aemxsyzy.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2leawmryx.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2fdceiooa.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2xynzszaj.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2mydwjcmq.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2wqdjcyvz.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2lpronsgk.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2idbtclvq.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2thdjbetj.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2nbcetapk.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2bjyjvtib.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2rzwlksws.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2ziuhqimq.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2oclxaent.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2tkotramb.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2wfugrjkw.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2wzdzchud.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2wvivvxoz.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2abjbesnx.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kdtlvxio.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2zfcrgrkz.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2hyqnnize.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cvzrgelr.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2yvdmairv.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2mbgyqvdt.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2svietsvt.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2yyyszmwh.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2tfmtepjo.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wuuljfme.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2nsaehvmn.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2cnwrkyvt.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2gdgoyawv.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2vgirzghy.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2ndxxzgim.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2hndoxoqx.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2pgmbodhg.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2mvzopgob.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2lkqhhzwl.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2bekyjbuv.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2ysnthobh.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2lqgxegim.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2afuyoswz.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2tupblguq.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2legcgjxk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2asrjsuux.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2fjfzrkkk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jxeoljmc.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2ktqrczzu.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2eqedpajz.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2oleislcj.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2wdmogpfj.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2wtgvuucn.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2xwzadatm.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2rifgsjtb.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2mgxwowli.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2zrppzbzp.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2moqbplsj.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2bshxbqym.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2hggfmubs.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2rfykuunx.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2xhxfbtga.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2jjqjvyup.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2qcnaaigg.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2arnplypk.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2zdximklq.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2qtvappkb.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2zdonazov.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2lczaudox.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2lhenjufq.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2wigiwlvn.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dzvvnupb.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2kgrfkihw.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2uaorjsmh.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hvxghxqy.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2wsbiugcl.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2lxwuugbt.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2zavaotbv.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tdioswgx.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2muaunwfi.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2wifuxvss.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2gaeaprqr.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2gauvradi.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pivrezxa.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2imkvdzno.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2cxxrkhlg.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2zuyopnut.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2iyzesjis.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2pgfwcvhk.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2rmxdgbbv.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2tupexpuz.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2drsiaieu.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ukjcvclb.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2avrrblcj.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2ottimubg.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ydztwexo.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2gsgmnwtv.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2mmuijfid.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2bymgdgdn.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2xfoejoye.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2sjfmvwhp.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2uwdyaguy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lrfyraxw.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2aomvwlwb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uivsicyr.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2rsxrcolg.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2nxdofncp.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2pqurhkwa.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2opphppdm.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2fdquorjn.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2dcklexet.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2zqgizjkh.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2rbtkgmuk.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2wjhkappy.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2imibojmb.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2ntgkkgoa.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2lecaykfr.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2yoetkiwt.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2olzlavsz.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2fdxcpywi.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2yvsnymtp.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2uknvpqej.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2eecizift.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2epjexrym.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2dqktfwbz.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2qqlpiqko.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2pjlfuksi.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2vivylrcs.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2gfznrvwy.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2rrsmftxq.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2zyaakjpq.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2hjxfdvzm.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2inoajadj.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2cxfffgyu.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2tmzaftzt.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2uteiyhbc.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2eadsrlgw.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2cpjhyjfr.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2hjwyrvme.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2ngcyyalu.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2xudvzket.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2vbsfnuwc.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2nyystpjv.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2haxdljvi.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2djhtgjec.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2disvddlh.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2oslcrksp.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2yxojpoiv.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2zchwkpim.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2zaoujzlv.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2wzzrcmwj.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2zivqvmee.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2aznefodk.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2yglpwuob.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ptfyyrmr.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bfnznfbu.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lwmgdfvu.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2foywongt.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nbenabbd.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2voprrrip.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2fqgldwau.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2krqdlacf.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2vgchvmsa.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2osndinnq.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hcyxvhbf.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2zkmwvzyy.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2uugzbpst.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2xbjhdwdt.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2opcsflfm.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2ofoibbup.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2liuitmlj.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2mfianjlh.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ojzmujyk.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2wmvfevyz.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2oxfzwrcc.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2phgwhhqq.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2nhfrptfk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tqpjqxdj.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2xistxlcc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2flgpqvmk.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2dvwmiklz.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2owbqzeus.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2qegyyrtu.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2ddyvyfjw.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2ukmtqfrd.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2srryxpqp.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2bfqsmkbk.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2ahdbjfyd.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2smfiafko.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2vzpfwwzn.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2emayhjlx.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2ghsovwpn.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2ygasfkri.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2izschoxt.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2nlakupep.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2giodssws.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2csmghqur.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2ppgbjuml.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2ebinukef.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2qmmrhbmb.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2tgaqleuz.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2cdmryzny.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2eczffihj.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ckuratvt.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2ocnkddsf.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2faiywpfc.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2ctdvxvpu.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2lnkqwdps.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2ftjopvxn.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2zmjmwucm.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2ejxcmcjh.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2zmnbddwb.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2hmyxenqa.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2ywsfoiwt.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2twwohnqi.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2zaakxpyp.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2lnfabzeq.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2etjwzyxv.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2fzktofdo.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2sgxcxxzd.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2nhcbqanw.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2yzrbvakb.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2mnocayzg.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bhyvgwxi.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2jfkybomm.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2xfcfozcc.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2apgrilne.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2cwachcac.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2nkgsyfyz.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2ybzdshtr.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2ffedxrrm.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ljqrkkcl.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2tdjnqrjb.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2plxmpnwv.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2dundbhoi.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2aniaphot.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2hzcacgvn.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2dsboxtri.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2oktuclxh.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lmwdwzbx.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2bwjeysuc.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2hlihgsqe.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2ktahpcac.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dlgxsbdq.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2bdkvjrpc.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2cenavfsp.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2kzsixpex.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2futpwyms.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2qfamkxby.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pnqtyidv.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2vqdkixmm.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2ohmdddez.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2lwnfnllj.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2igwouenx.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2bakgomkf.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2nrkhjvce.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2yvgfqvye.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2ogscwwhx.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2vpwuhkyv.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2fxmrlykq.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2uwwdagus.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2dubqliqt.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ilzoylsy.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2gscbjclv.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ziktatlg.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2hjazqpct.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2mjkgumwf.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2awzvxwdv.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2skprseph.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2bgrqygit.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2nelsgtni.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2koglxeaz.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2owxvrcat.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2vdnwsexr.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2fiwnlnhm.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2mjrbqxjk.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2bjjovmhi.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2mmjyblqk.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2fehcxafr.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2xcfukoni.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2jztunhru.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2gdqbefkc.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2knrrneyj.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2hvfsuhir.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2vybwyxgz.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ggfjlmzj.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2spklwitz.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2bdgtcinv.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2ckqpizvg.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2jwyuzops.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2graotcjt.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2gnsscajo.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2bfpqfydz.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2tcqmjqfm.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2rrjqzwtz.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2lihflkpc.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2vhegldmn.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2yfjkkrox.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2kfgaeyvx.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2sluhlwfx.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2emnpsynp.html


<!-- 参考信息 -->