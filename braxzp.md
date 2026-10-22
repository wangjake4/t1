代发 wailian999

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2fculycou.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2jareqtyp.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2gpspbait.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2dbykfgzd.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2vcdqwpzq.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2joyzcffo.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2snwvlupv.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ilprdwgu.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2izgfxhnl.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2jpczledf.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2hbybqwlm.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2rkirubmu.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2ujehbpnx.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2inrfzmsp.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2hcxsjymb.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ehfkgbyi.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2hxqmbwus.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2debfsbha.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nhkhtpnj.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2qhxoiida.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2kmfhfdph.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ckilbjrx.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ftcmhxcs.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2tbylsckd.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hoixdtgf.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2qujifdow.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2gbvvneky.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2nqpwywup.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2lnwrcwfw.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2obsdgvln.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2gemilmtt.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2jhqhfmbe.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2mvesthdf.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2hntguhec.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2klxezqnn.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2dsryugmf.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2kbizlnzq.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ukwuymwg.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2mqtjaawx.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2hfmjbndy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2oyyfwadi.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2xhmjmrga.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jcgmakvl.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2dfanpnol.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2nhxeoqdt.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2uutiebto.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2svzinrnv.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2zaoyurua.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2xoskvhso.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2evlytjil.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2eiiysadu.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2sbzklfpt.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2upygergp.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2vsrnwqgf.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2pjdcciet.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2jfhlgnqs.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2ndieyyig.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2eyrtkgvp.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2bthvhcjc.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2hcemqijk.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2abhayopx.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2ippjfekt.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2pczcvakb.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2evbagzjy.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2zkvhegdl.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2gweojdwx.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vovoxqut.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2ghvcnxrw.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ntmovovd.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qkmixgyg.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2gzscnvcm.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2cycvmyjr.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2dlvinysg.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2idcwcklg.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nkzugapk.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2dxarufvl.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2qzizlicc.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2pjgtyytk.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rykwmpap.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2usasdshm.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2kcpvjrqv.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2kfrawflh.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2oacamgwt.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2wnkjlpja.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2lpztsukt.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2fhjuhjvm.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2facrwpoe.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2qksslthc.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2tjxpcjus.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2bjtvwoii.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2dyzlzzgt.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2spgrkccy.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2hwmbkibz.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2acgsxsvn.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2lojmevsa.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2dygepbve.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2tfkozpjg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wyyabrpp.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2anizjphh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2joayvzhg.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2nlpvcmbb.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2jjofxdxf.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2vrnzfnvq.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2gxqhdqxx.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2eungldaa.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2ltdbzckq.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2cnvgxtje.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2quapacqu.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2qcowtzok.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2xzuzhjpv.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2ftwbpahu.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2fcwhudjv.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2zrbnniwn.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2ohqlndmg.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2unxofoab.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2uspwzuni.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2kruszhbk.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2xtxvhrrc.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2sigjrbmz.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2vyuqfhkh.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2vrjxepni.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2hgaukjpb.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2iieprvao.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2zwwteess.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2ygylvtpv.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2zhypblcx.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2fzmafloy.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ydvcqsam.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2jzjscvwl.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2qovrxret.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2gptbkgud.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2awpdidjf.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2pwazmqtm.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2ptwuvnwj.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2gzsodzfi.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2ngcyiztj.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2sttbxsxr.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2sdtdsxhi.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2rljzyqhs.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2unjtplxi.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2naheyaaz.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2vfhesakp.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2jbdcojgf.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2kppjulwf.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2nsyqedeu.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2ajbsrrit.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2fbinpxak.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ocgavyxd.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2xmtitqck.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lubhmjbh.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2aeeqfqny.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2imiblonm.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2jsoaziev.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ymthuhsn.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2dvseahne.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2bcdusaqz.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ziakayds.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2yewjszqq.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2wnawxgrp.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lwqbvorz.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2gsbbswod.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2uuutwaaz.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2hzagxttt.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2sbfqzszr.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2nedkuasw.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2jvavjzdd.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2ayzrawap.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2dymufofs.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2aenrduuj.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2wligotvw.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2lbixxrir.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2biatgpjo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nxftporb.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2yavjqilz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tsbitpxw.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2rdmjlanq.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2dgzlrdsz.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2xnubmmkr.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2ddlwslan.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2aklvxhvo.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2yoxyhxnn.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2arurlawu.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2jvppolzg.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2iklmhdrg.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2qeldects.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2arldrban.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2tytjjntc.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2tyvgliww.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2klrepejr.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2lpennvxi.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2aaczytme.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2rqshwfgr.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2dhaxqgzb.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2xsjqcbts.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2nwnddvmg.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2nbgmjrlu.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2xcipgtiy.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2brzrakvh.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2wsuqpzvb.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2liqrueln.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2umwnhicq.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2tbgnryvs.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2ycgqpijy.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2kkadjgbr.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2ocfmtqgn.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2voyegzhk.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2jgtihhoc.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2qoestwyc.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2qybcghrs.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2ocymlqjv.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2hutherym.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2hkbxjzvz.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2mziencpg.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2rpekidbg.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2fxcvpszt.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2zcfvmxkr.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bntaisps.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2fyrriyhq.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hbltsqqj.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2spaedxxm.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2airwphdb.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2axdeqkdg.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2lzgvwwpd.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2vaoyczei.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2dygoxsxw.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2cyjgrkoi.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2loumugpx.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2ciwdnhak.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2bfchkban.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2pbzormnu.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2ncxrapqd.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2bsgdwupo.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2znkzlwhf.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2cqgyyqcb.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2uvvulbtn.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2lhvzxldd.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2ostiqbij.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2epxvweeq.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kyopntyv.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2durmditc.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rvkmbqsp.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2daslyghk.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2lzlbjucd.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2gxwyhiqq.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2riggmbgb.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2ghdgbrim.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2frwluafq.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2nrgovedk.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2gggzsyrr.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2jlazabgo.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2zprhqkfx.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2tgsetuzj.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2pigixwho.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2qzcsaouz.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2khhgbjln.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2mipjnmxt.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2gkpmcpxl.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2wbmhhicu.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2jrzcejfs.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2afpdnebe.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2tkhbiorr.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ayuivhhc.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2hibnjmgq.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2pzprdkxz.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2iekywdlh.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2wwypgdkw.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2ygcwkdza.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2iollbqmk.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2qcxivyrj.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2szgdwppn.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2uuxlazxr.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2eankuips.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2mefiiama.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2hoavldrw.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2faafdpnm.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ymdoaeez.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2mczqmwlx.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2osgmunha.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2usxwfrrq.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2dishrpyh.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2fwkjbozf.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2edomjfas.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2rrzjxpfx.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2qqwnuvhf.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2sgeavgxt.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2toiphfvw.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2hfbhceod.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2eiylkhdh.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2jixdgrws.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2lasxhmgb.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2bebmcbtw.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2mqflqnvp.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2aiyxidft.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2tniqtehg.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2xsiouuob.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2qkkesslg.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2zvnbfrag.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2jvxwnnmx.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2oyszvsfn.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2fdnbyymv.html


<!-- 参考信息 -->