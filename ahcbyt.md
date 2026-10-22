代发 wailian999

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2adkyilgm.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2tnlgukpt.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2qqcbixsw.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2hfjdzfvg.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2rpmxujtx.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2omkufjkw.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2wryyrmsd.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2pmsasqjm.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2behehwto.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2dujyutua.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2ulvxnahc.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2dardrlmr.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2cjfllpeu.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2xfueoxrv.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2lznkjbfb.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2zftobhmj.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2kizpznbe.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2kltgduzp.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2kpicpjdj.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2efhthsfl.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2bccrltlw.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2ttiigteb.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2vrayboey.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2wdgutvku.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2kkcrmvzh.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2crxmcyuc.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2nxtlbopy.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2fyifebdh.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2jdloajtn.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2eynrufzv.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2onyimitq.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2nzttmdms.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2bqzdasfu.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2mozrkkpg.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2spoflvfv.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2tfkasrum.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2amxmgtdl.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2vcjijpuy.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2jtvdxzwr.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cnyuphft.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2nbowmsfk.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2yunlkfwj.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zccuqlpf.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2qznnofoh.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2isdbmkgk.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vcrkdguu.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2uwlkbvfd.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2yzwqrtrx.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gpotaxku.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2ieblyghx.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2rtvavsgi.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2wsjvndin.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ygrabjma.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2xxagojds.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2pdbmlmge.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2hjrlhjka.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2yvawgetp.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2eltrxmxz.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2nwsbonly.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2lrresjzw.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2fyancpic.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2zellrcph.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2brtzyyoa.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2mozagrwo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ztyvvhyx.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2staewzlf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pdzqikbb.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2svbfcfnh.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2rybhxxrz.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2zfklnwia.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2xwdxijrc.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2iyxefgoh.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2kypxymwh.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2bfdrhrqu.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2vdcxsdgt.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2ybjaujuz.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2wuxdtqan.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2mpnldcwz.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2uzxpqkwe.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2stxjnlni.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2ooggwnpq.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2ltvjzurm.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2tftkluui.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2lhauuisw.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2cmfgbjmq.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2xsorcmja.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2mnntpexm.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2ymfobgxh.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2thtasvvs.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2dyevksgz.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2labtpitt.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2wwiluizd.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2rszfizzp.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uolfrbif.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2mpdpbjtt.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2yvhqrjej.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2dxtfxzkq.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vhtgqymv.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qhsavdfp.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2zkthrbpf.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2opowuxnw.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2zeudaiuu.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gvuoxits.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2qsgdqdzx.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2vgybtwze.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2lutuxmgz.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2yyvsgojs.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2wjjkjmpc.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2niuzbayb.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2csmmzbah.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2vilhqrfn.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2rwqhnfsr.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2yyvkfcte.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2gsrysoco.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2gewafcwf.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2slgziicy.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2ehhgprti.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2blanmpra.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2ydzucctg.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2muyopupx.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2yryeehzv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2khsbgjhh.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rvukviez.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ouemqdsw.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2zwniewxm.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2mxkzxfqu.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2tvdubnly.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2caqtivxn.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2jipdhmtd.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2atxfnzjc.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2tumrtfgg.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2pftadrpd.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2ucpilmry.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2uhpmxpdo.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2wiwzexdy.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ooucwaas.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2lgczkrjv.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2kfvccgbb.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2qstnsyis.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2vxjwbruw.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ximwptwd.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2sdlwarqr.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2cwnrvlxl.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2uulugoxj.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2gkhizdxi.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2vcdxpnti.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2ejxtamgr.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2gunugtij.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2umitpree.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2gucigkzd.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2opirhrti.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2xgrmouwt.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2xwbcezbm.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2mtcqojvq.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2yxbdamgx.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2zcjfzpzw.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2kwfyecae.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2sbmyekjd.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2zjhycozv.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2waswqpxi.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2relemssr.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2zirojiig.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2ivlqwscb.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2guykppjz.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2vowacjik.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2sggslozs.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2pigwwifd.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2nwwjqiat.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2abcxfeet.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2jjywoiks.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2cezxadfg.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ejcehuew.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2vzpdzyqx.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tgydeyfl.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2erqcvyol.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2omhvlyds.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2vvbzeiup.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bayklqey.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2pcfsndsu.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2fsbgtnzs.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2zrldzxob.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2pfkyfwbu.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2uwwyraku.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dqtwcbsm.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2skhatjyk.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2ruaerccr.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2egwykdbk.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2nzuardoh.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2noqozwkc.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2kumuauzi.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2vpexuwys.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2uszeclpc.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2pvnkfcki.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2obyujseh.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2uwsqcjtk.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2jyrqxecm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2waotwiul.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2aqjjpxum.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ihwhlyhw.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2vmhejagk.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2aytkixgm.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2aefhtuuf.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2dtrkgcib.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2bunroyrb.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2ewhcbwuc.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2wawrdmoe.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2ncrgblum.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2yvwesxnp.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2kvufurvc.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2ofmdqlwn.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2wghtsyqj.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2gkpucviw.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2zxzxdtqx.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2obslbspc.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2hwbiyaop.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qweysmeb.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2mqiywmgv.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2mjhxaiyh.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2waynqhda.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2windlwlv.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2xztwchhg.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2kkbslkid.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ezanzuyz.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2gaazuzvw.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2taxkodqf.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2ziayzral.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2rdpvuusg.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2gjijpvka.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2dtthwfnf.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2nkhefhot.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2sflwzanz.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2nwjjkivl.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2dheczibl.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2rpuukkys.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2nfjhjpgl.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2guacydbj.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2fxurdmiz.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2ecrjursu.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2vlvsafcb.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2icaqddwk.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kqpxphss.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2nnteeady.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fdbmktoc.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2bfshslqy.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2psoifedb.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2aaneyzsn.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2jliyoamf.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2nqdmtxel.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2paiqryoq.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2kpbeuumv.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2jxpptabi.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2yqcltbxz.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2kapijzis.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2dqdklpmg.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2cxmbuxkt.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2slkvjack.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2oegziwbx.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2sivnplxi.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zivixweg.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2skzxtyxd.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2trcrwsrs.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2mxnhfsjk.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bxhscfxr.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2ixfzjlwf.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bwuijnld.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2vnxfpqgv.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2pjolomep.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2xwubqilx.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tdqioons.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2rcaeypiz.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2zojipsjg.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2hzppvjoe.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ernpdsng.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2eogmyjap.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2yfgubgcz.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2eqtteusc.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2dkbtueug.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2wlcoufeo.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2kbsppuyl.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2zioahhox.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2utsdqasd.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2fbqbeiek.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2qcwgqzyb.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2mjcdoxxk.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2dyauayne.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2gsabxltk.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2sdfzjutu.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2igbixrvj.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2mickqboc.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2oxslccwx.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2uxsrlfcd.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2ninvfslq.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ozifcoxk.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2cclobvam.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2ayzzuici.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2tqyudrya.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2lbjqxyrz.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2cipgqrlu.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2tojznlhz.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2vfvixeat.html


<!-- 参考信息 -->