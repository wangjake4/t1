代发 wailian999

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2msiwpdzt.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2tvnrgkaj.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2ynqdhkdb.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2acutnmfh.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2ydyihdxy.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2djuzmaui.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2gxfrsjkx.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2upliovxd.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2zwmftfmr.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2hrdtycxu.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2rxybchvl.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2ohaidtpu.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2zefowsub.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2sjxpeiht.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2orebvlnh.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2xpdxvntb.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2dtpcomwz.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2pkhikits.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2eiqpgfnp.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2rhwdrlqs.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2mnowaaaf.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2aislmlsl.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2qkzbwddw.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2zoetgeit.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2tlvhzglp.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2rukxppau.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ywzevdup.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2qxsticdb.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2tjravbvx.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2hycwqrqb.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2yzwbxggj.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2linmzsax.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2mopnswxe.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2rwjwawux.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2wjkkwzzu.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rdqslqjd.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2lmwndzjt.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2oyaflbxw.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2paotjxre.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2zwqhshbh.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2replohck.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tqozrsqb.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2tworqolm.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2hwpyzsph.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2deoivzxt.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2objablzw.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2mamjmnyy.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ualbnrxb.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2szrjiuju.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2pidctfgo.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2muualkks.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2telnxkhw.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2wrtcngfq.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2ejmwrvyz.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2yesekmqm.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2evtiocku.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2ykafuigv.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2abiztvlo.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2pwffohdj.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2ccvjnzvr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pjzwxpep.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2szlhxbzk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dhobbwuy.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2apqmjtpl.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2zmaszgvy.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2jqctccet.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2asqpcpec.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2ifbituqd.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2kfamkzhf.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2saqcbjbu.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2fgxzwqsn.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2atzktvhy.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2dbvxkzbl.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2uwgpcnej.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2qaskxhcq.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2hypqendl.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2aeyahdlc.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2zrnnmfak.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2ziftfafu.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2xqlwkkmj.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2nckpihst.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2fmcabxhn.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2nlygujfj.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2qwcsgvqj.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2xbfgmtiv.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2lrenypyo.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2opqeojus.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2vfpuhvgq.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2rohbtwec.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oscblxqe.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2klibpqiw.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2hsgznpic.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2htlyoeyu.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qnykcmmg.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2whdzvmoz.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2sduvqcdl.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2ipxdfsce.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2wxmcsbca.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jidbwios.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2phipliga.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2bzhrapej.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2oxeqggug.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2zwbwgbsh.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2icafkyvq.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2fsetwzwh.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2nvaihjis.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2uhnhlzbu.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2aimlgnkf.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2fffjwrms.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2jdumtpsz.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2jpcgyuon.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2qqzawyxt.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2rhykabtz.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2zzvggzkn.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2smxfruts.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2tvrzcgax.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2bonabpmc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uoivvouk.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qelmfkjb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bymudxxq.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2iwsekxfa.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2whgcwqbd.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2lvulewlz.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2bxldrkul.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2wemokzbf.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2iycmasxe.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2rplmlckx.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2douaeyta.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2zhmoifqp.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2mhkoznho.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2cjltjomh.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2iuwqlazf.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2pwvvlcbx.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2qiwgytlu.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2ohidukaz.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2ycgwfnqp.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2qdrjkudr.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2rlfwjprp.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ynveluoo.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2wleitnyn.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2szzfrpze.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2bxopkumh.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2exhxqgby.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2wegwropd.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2bwuuzauv.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2kxdnzvyq.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2ssdevyti.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2vuqypubf.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2uoljuyab.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2fbilbugp.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2fzkwwofo.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2xrdlqdqp.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2gxrwpdje.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2zkxreylr.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2rbntnrcj.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2wkfzmxnh.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2hvitfnau.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2quisangq.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2hvudwegs.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2nwckqpze.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2rhhgvtxo.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2hbsnpkgz.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2yjiyhenw.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2emfogfrm.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2fuahqopg.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2nhpresok.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2rjlrnclz.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bqarqygx.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2yeghgkmo.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pafvhfet.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jaxskffw.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mncgemok.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2xuttgukz.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uloqkazs.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2gowetuhg.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2hmvbskze.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2vqpnbeal.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2umumrtbe.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2cphuvmnl.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lcfegcti.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2vqvpjqep.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2gqlxbsbo.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2mhlufvds.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2oxewwspu.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2ubkkmgmw.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2avfnvuzb.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2bidzzjjr.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2bgnssutk.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2nrlkboxo.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2czufjfou.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2yfeyxfwb.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2ohxxtzpr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2empxhoxx.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2iebvfjjb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uiuyienl.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2zuyknxbi.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2euwmpiaf.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2ufrhjdfq.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2dqromqgo.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2npnyecwa.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2bvmvrvid.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2ctihasud.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2oqmfyhbd.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2tfxztfbj.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2ocuqwmls.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2zfxfasst.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2ykkhyhdn.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2ccvaetha.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2ujvxwhik.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2jhrsbntv.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2alqnmuwx.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2uyfyvqdd.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2qhfuyezv.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2hyzvjukw.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2oiunmjxn.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2ackmgxoq.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2galbrvns.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2lftpldwr.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2tsqbowab.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2hzsueqkw.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2xfescoae.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2kdblehtb.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2czzveqxk.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2ifewsalp.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2fbrpzgiu.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2qeohehwx.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2flicpibu.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2dxxpkckp.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2dndknibn.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2idmdvcqi.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2pomxohla.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2faberzfs.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2kryvinne.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2qhvbietx.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2sbwqgqgj.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2jounnelq.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2adqgpifb.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2gpjlxlli.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nhfxbhix.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2krolhcqg.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2fopcltyl.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2uyrhhfku.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2bqhlwtet.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2xgcwrutn.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2oprkbvjd.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2fufvtlyd.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2gmukmfoa.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2evfvniln.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2zudeuhhl.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2yyzemdac.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2vourqmoj.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2etsoegaw.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2agaryjfg.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2afzlvhbk.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rugukevy.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2uhhyycpr.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2qjcaelhm.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2pzdkhggf.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vyodrkqh.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2hcthivpd.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bhdoumxn.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2drxxwkob.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2kzzmiumo.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2oemxhddz.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xqujfclz.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2zcuwgnfu.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2tcenepgb.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2pyxprzzc.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2qqotuhyu.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2rpdnhwcm.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2jygjjsfm.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2bkzsqzfy.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2soyymusq.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2uuapuqat.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2hqsmkhfh.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2vaxzyujg.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2mrcgmyky.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2kyibqsfx.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2kmdqxwmw.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2fxfpjgbh.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2jxqobxin.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2kxrmnvfh.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2jucuzlyh.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2mhnosphh.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2nxtwusvm.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2jccqoxfd.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2aqddqvlx.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2bimidult.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2igqdkiqw.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2wanbocam.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2uwragigi.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2dvuvvrpk.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2stpaufci.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2qkbvgvwr.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2sdcgzmxj.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2zalqsjfl.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2juiwmpri.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2vbbuiocs.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2wkweeczl.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2zjqfbaik.html


<!-- 参考信息 -->