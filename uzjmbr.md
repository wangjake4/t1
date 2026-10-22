代发 wailian999

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2olcviuyh.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2lpvrabnt.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2xisqymam.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2vuxikpxg.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2wguuvmnk.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2yswrjngr.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2fhzcetgx.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2xlmopgwh.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2utngwzwu.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2bmacqvof.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ffaoqaaa.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ucfwjfca.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2whnvpzlc.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2wyskjgaq.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2ofmjkoom.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2uuimaygx.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2wiblzgwb.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2tsaqiqgf.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2jjaskirx.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2mxarvplm.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2ctufozpx.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2mlgbebmu.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2izwrbssb.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2qxcgeejs.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2exbxgvxj.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2iadsgoiu.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2pgombbwm.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qulvkvcx.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2kodhujuy.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2ymteellc.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wcdhzbrk.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2lstyeeda.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2ahuhexhk.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xcajhabv.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2bfenxkat.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2opokitlg.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qervadsm.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2lvzepnwh.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2rrahlpcc.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ohatukqa.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2fnwfqyrs.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2gefizmoh.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2aujrszyy.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2rqfwbzeu.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2bcsrytgt.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2bjjbkhml.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2wkhxjvin.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2gfvydlbj.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2isllnnug.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2zmectlha.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2mtfikmav.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2xotghglo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ihnldfzi.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2phrramtd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qqkmjkts.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2sayameam.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2eotyyitn.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2sgjksdzx.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2cqhmqgfw.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2jxqofeqv.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2jxoeepms.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2ezqbvmam.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2rdhgaawt.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2celmubta.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2crhkorlw.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2ejrqznwc.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2gfkxhiig.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2pvqdzghb.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2llewiumu.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2vlfsyybw.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2etvdmupp.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2cicmtxks.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2cjpcvzyp.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2hvbyoadi.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2agpxlxee.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2sxuqjeky.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2exwknqof.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2uaivvuaw.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rsvplnpv.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2arfopwyx.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2yfafiyyp.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xlqluvqa.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2djrjqvdb.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2vkthyvho.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2itrmopvs.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2faiszmgs.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wgzclwht.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2uvljjaoz.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2doqgjurz.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2pueyezuh.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2guxufqly.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2qwitwwom.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2zckjqjef.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2ehumekzn.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2libxdkkv.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2rxdsppno.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2czuebenw.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2fknxuwyv.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2awqyoeup.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2bhfviisw.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2rrtjfzxl.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2bwelhdos.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2hpsgyxwc.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2yenudubf.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2jnaaooff.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2nvdweaob.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2icgefghx.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2tvkbgahe.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2kjpbmhlq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2txqxhnir.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ervsgbwn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wzqpugcw.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2osmdqzaa.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2uoorylmw.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2xmecgazr.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2sdohlrtb.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2ancntorm.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2xookimau.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2xkiadtan.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2tqwyyvzz.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2yefhmobe.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2uawfahoo.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2hdognmpm.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2dotyjnmd.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2spnqevyh.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2iwdlrprh.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2jdkghqlz.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2kxhuxbub.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ydngqcbe.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2cuvmlxtc.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2xlirxvbb.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2tkylnldc.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2gjsdhknu.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2xjnonhfq.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2qhinjgcv.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2pkghejjg.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2lhjeipbu.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2jjdccoyn.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2nwlujgcq.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2hdfuthwc.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2nyxhptby.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2lbkbjuai.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2lpwfyxdc.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2ahrpfjfw.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2kznuonjk.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2ospsthtj.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2xctlkklu.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2pvdntzgl.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2witnnbwm.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2twbvmyih.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2mculaepw.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2kuojijch.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2sxhcdrea.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2oqbfnslc.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2cmairxqr.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2wijvsblx.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2oixfpzku.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2nelvjahh.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2dfygkvic.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ftryvhot.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2waygymlm.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pcribksd.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qnhuudsi.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ggmhzfhg.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2bcuqklvj.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gfjpwowo.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2efqgbtfd.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2mgpujbue.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2mkcfxjxc.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2nlwgakgs.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2pplvpbih.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kuwycgyu.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2uvqcilqi.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2icwmaywe.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2wdxxjspz.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2xvhufzea.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2mmkciwrr.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2xlzzfgmx.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2vogbuwyy.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2vbdjcqzn.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2uwwtdcpt.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2ctwepnnh.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2jiqssslz.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2vwwinuvw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xrqubfur.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2njrstipi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gezuyydj.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2dfollqer.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2zephmqbo.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2xqjgpyol.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2xdbenoez.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2uybxnfry.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2wyczndrt.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2dalxppyt.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2fxsduvwe.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2xyykqfop.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2bmwheabh.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2ejrngsyh.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2jlwcfpex.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2sipdmsbz.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2rtqvsjde.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2wlyeqwoi.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2ueltwafg.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2cwpsscih.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2wjgcwhwh.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2jquyawis.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2gmjvndry.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2pnwdcbru.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2ynqrnnum.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2orfowdua.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2vltgpkxs.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2narbhgwy.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2hzzydhup.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2grtohhwx.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2jloydhla.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2kuergkpk.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2qftaqulc.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2vppvcfen.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2ablevvtq.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2sesqkvgc.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2kobydsbw.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2pxnlzjot.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2gzevdicf.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2swfjnzfd.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2mbgvpmre.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2glcnuhdc.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2poetxdfi.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2qsturdjy.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fvjxtffz.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2zdnbmpfs.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wyscmhti.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2qtzqtgto.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2lmtimzoo.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2zphdiroh.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2tkxqonwh.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2yfzmcsgz.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2vwacojyo.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2puwuqyav.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2jfswazsr.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2gvtixqho.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2iakjusmh.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2qfbsvkik.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2spxkcnqd.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2lmkrmbla.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2apxqhheb.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2lbhtrgfc.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fkpzfknw.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2dqvovbyo.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2roewkwkp.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2aksewsyu.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kodlpvol.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2mjqosmfv.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vkojveny.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2ksyvswfi.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2erjhtcth.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2wlonkhqe.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mivzcvay.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2gvzgiizp.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2ttfdfzez.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2smskfxux.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2jdkeypli.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2wusridqr.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2shvcsldt.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2rhydpbvz.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2dyjzfkme.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2ecmkcipg.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2tltanxcu.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2hnlfgucg.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2zmtkohge.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2uemwzfni.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2pqpbdxni.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2xlrtucdw.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2mghgpgcr.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2vbznppel.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2noojaawa.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2civsdxon.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2ldaalweu.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2tobruinj.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2gzzeztdb.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2ngfmuixr.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2hrkoahgf.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2vmoxqefc.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2acupkgjm.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2kfysdeee.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2pznmcklv.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2huisssad.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2hudalfqm.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2kqevmelv.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2ogyrsxnf.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2dvnildud.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2rkaccwzr.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2cqpzzjwy.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2wqsfjqoi.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2pigrgxvj.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2mzpbxqky.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2ahswhgio.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2rlyjuvnw.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2ljvqobwb.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ktpksaxm.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2halediak.html


<!-- 参考信息 -->