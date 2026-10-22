代发 wailian999

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2pqefjmgf.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2adrymoxc.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2yogoqfla.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2xalsbuoe.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2emmwshmq.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2vuxbzoly.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2bkpadsmo.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2szzzuudz.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2nlbpjpxb.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2zrdyxask.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2zwsoadzg.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2pgnyxpqw.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2iuyghsha.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2yjrixzhn.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ermovzec.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2kcxnejda.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2zjzynqhz.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2xugarbkz.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2aiwtnpgi.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2liupwhvc.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2ivfgehcv.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2qjpsiwuf.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2salpimkh.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wpphyvdp.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2lpzpagme.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2eipbeghq.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2goiofoje.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2odpqwsvt.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2rxidetng.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sijtrmwz.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2xzzejtkp.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2ooplmfvp.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2yrxumarr.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2yvkvcpru.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2ahdeitqr.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ynsfatci.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2fxmiaaya.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2mxfmhzfq.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2tufzheem.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2ntmrurft.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2upgzakvt.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2sbpaqwek.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2moqautlu.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2gnhwicin.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2ffafsbwj.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2fffhbeoe.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2uukngiik.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2zjoxhhxy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ysfwetib.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2udncxdav.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qmeuiueu.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2hunisnfc.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2cvosaiuf.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2wwxwfxzx.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2rmwicrdm.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2tdgeuemf.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2qxhfvrui.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2rskbgacy.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2cnsjvmri.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2pfiowqek.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2eybxbzks.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2hcyrcjeg.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2yyhaibgt.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2anhidemh.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2inhtipjc.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2xzmaqsbc.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2fuwkrapn.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2ssoptddp.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2poixbjtm.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2ftnkrjvv.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ptogmvyt.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2qukelbwz.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2qsnnsqgh.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2mcfnnhuv.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xyvwioox.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2pwfbezsu.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2mbqgsmrr.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kbkrasjn.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2simnjphj.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2ybugepdp.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2tambbzzv.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mfobqcdk.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2uwisrrlr.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2cjiuglfi.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2mcewmgwi.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2fskopdrx.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xpdgdfvq.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2bwwpgewq.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2mrkkfsjs.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2pvmyqqwm.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2cbyavdcl.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2vrzdzcdf.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2xqnwansd.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2cdfnkyde.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2lhirataz.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ysrmhjag.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2ujsbwbxz.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2txfistet.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2oqucfstu.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2cqqtfgzk.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2bsxfgfdo.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2hhxcmhbu.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2jppvoqzv.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2fopbipfx.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2iiuinnjn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nwzvsbqm.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2repgizoi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zzklbdxl.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2udyslqrs.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2damhawbv.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2fxuqaasp.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2ogciyvcy.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2atdhaojt.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2esscrzds.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2npiscasp.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2ujigrpqd.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2kgiwrgtw.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2gsybmsvj.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2wberapwi.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2fgzoclbv.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2ymdgbmpt.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2isntlfyx.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2nairbhci.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2eecgmhdh.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2xvqplinb.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2lptufgze.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2pkpmbbkd.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2rligoyxn.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2sdijzkxy.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2krhthfmo.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2amujnpyc.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2mfqnqnyc.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2jmydnflh.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2cfrxcgpt.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2xrbmpigd.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2mxqbwdho.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2xjcyazpf.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2ktvzsnqi.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2kpqzoelq.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2rcfkmejq.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2vqjbkagy.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2awvrutxq.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2kvsjyjwc.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2djgmrcfb.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2npcrwnjh.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2xlivlpye.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2bmhebamz.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2fbnriwlj.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2phcxbnif.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2qsvpzwsn.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2viucubbd.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2pzscxktz.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2owiejpkz.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2bmkbthad.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2hajbzdir.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rvyogbbc.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2wjgsrcbh.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2alzqcewf.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dzqflwhi.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2whxbrlps.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2gyzavhpa.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rpffjjle.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2brniqvxn.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2qijzrxjq.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2rszjnbwy.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ouyksqgo.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ogaeybtz.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qltqdpsp.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2gpklvmdp.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2faofogjk.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2ewnfdacd.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2cwwastqr.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2dvnumzes.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2nwmstyir.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2kdfkgnnv.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xgpvtsor.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2oygrgqil.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2hnnjkmka.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2mcaoyibh.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2dripubco.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gcxxmeoz.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2dfldblcd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xrmywxio.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2dmihicdz.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2fcrcvekx.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2whrwpynz.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2utjdifmo.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2ivipjsur.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2fxcvkidu.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2zdpcbktv.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2necuabae.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2tfvrppii.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2dhpxdzqp.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2amwiobpe.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2ykfazxks.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2wbpkiymu.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2qmmtrzyk.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2crjzfdic.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2oikfqgnw.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2umpfwiee.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2amopqlpi.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2fpjxzfxs.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2xsspcxuf.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2ytvynqil.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2ethvhbia.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2mleygosp.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2epbxwzod.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2fgxyngmi.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2qgywdhxm.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2aghozddo.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2gfaquatq.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2dzcwwjqz.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2cwcjshdd.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2inohlpii.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2jdboukqk.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2ljhhljor.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2tzwlstql.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2csbwibua.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2kqyhjmkd.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2vrdmtbur.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2sgydpdtj.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2qailfgcv.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2uhnklpau.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2wqfhsdgb.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hblixxrq.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2ysfsievy.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mnxibeqp.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2teywqlss.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2rfyclwtg.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2bcxldhhl.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2nklugabe.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ltekaezj.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2esnjwfcs.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2zwakzakp.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2updxwtrt.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2dveeskax.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2lxttlkal.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2fhqpckxb.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2dvuwkfdt.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2hupbtekr.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2xdxfjany.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2rmqhjzdm.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ukaatwjg.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2jagcggdm.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2lnnlkitb.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2xtwtfxog.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2erszaawp.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2ivrxjlss.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nknsqetg.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2dolslbmg.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2dqjejyki.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2fkyjouta.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ccyifqqo.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2kexmyvjj.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2qnmmcdzx.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2oiqtrgvq.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2hxmyttnh.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2qnbksajg.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2ksdyvzgf.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2jtiffctd.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2plihiymk.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2kaebacxs.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2vdbzvuia.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2bufbazwj.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2chjpqvyb.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2rmherfmp.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2nrwnvkvn.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2kquvmpet.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2mpvramxj.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2tkrcdunk.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2oibjvxsd.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2fvslgbyv.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2vcuxekaj.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2touyijlt.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2tocbojwg.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2dchqndys.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2otydrnfh.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2wwyxttsy.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2vsufvfdy.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ukcfnpuq.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2ynceawmx.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2zunsxzrf.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2xfftknlw.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2vlkrshaa.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2bsqkyyuu.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2eadzgjmu.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2vhopajsi.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2hwegllhb.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2jbrosvgd.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2bdsmdlmi.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2gkzafpmf.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2xknqitxz.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2xvwzqzou.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2bkkospef.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ypiimnvg.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2eedsjucj.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ptkouuns.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2iqehmwnl.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2ogqzxpiq.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2lojrdolw.html


<!-- 参考信息 -->