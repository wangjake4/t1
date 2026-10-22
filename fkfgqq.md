代发 wailian999

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ladvfimm.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2smeuhbgj.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2lgwsdcek.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2hsdjocbn.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2goonezyh.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2blrkreut.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2ljvwapif.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2itasrwjh.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2jxbsplip.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2opdtmfto.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2jnmcnvcy.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2bifsjuih.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2vckmexmz.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2zcqvgcgy.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2dschipmj.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2lezzlhfe.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2guhzxwop.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2vyoalbph.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2jbaocvld.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2akecjchv.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2mdkwelqk.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2fguxqloc.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2xpdmgcum.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2qwqbwcit.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2gcvlhnoi.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2olrunulj.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2xiugpluf.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ikqhajbp.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2auzffeit.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2vzyirozf.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2rhnmltqj.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ykvlbqaj.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2brhxotnm.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2jzlfdwqa.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2szlsoark.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2aiadyeqs.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2wlgnevpm.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2sqdnhfin.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2imhtemdz.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2lhcfczox.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2askehxqh.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2clbftlzt.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2tfgtsflq.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fijgxbtb.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2qkwuamgh.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2tpqzchjk.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pjthmcio.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2youdiwig.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2jmfvshhp.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2osigczxr.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2jlhadqst.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2fzjqchka.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dtussxoi.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2usqftzrf.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2vkvssrou.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2cyzppjtp.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2kszpcuki.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2gudykbyl.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2mwtscgoq.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2yygckjdo.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2tokpslsg.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2zmcxfdiq.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2smdnsqad.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2tyfudzqm.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2etdgqulw.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2lgabmdij.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2pqgwbgey.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2hieeopjy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hqohplxh.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2rsmycclk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hbfchgcf.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2bybzpvic.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2btgjnmbq.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2zwahldct.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2avdetewq.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2yypfqqtl.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2hamdybes.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2xfhpyizz.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2sourctsa.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2jazuoyvb.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2lslthvhj.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2ehylnxjy.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2fxbqzbic.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2plrwclui.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2lfoppwqw.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2ksxookax.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2gmucnhdp.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2bictfemv.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2uujzodll.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2kmqooxtk.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2benyxktz.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2hactkbkv.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2imoctdvg.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2cwgnijvz.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fevqlodr.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2riwqzbjo.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2wqcdewbf.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yxfgdelr.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2qsskgtnc.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2uvypwhdc.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2vkhwqvch.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lxwtekkt.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xlvfubwa.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2uvodnyzk.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2cpfmjfjd.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2wccnvjdm.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nbbeawqv.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2tdwlnwfe.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2kyjogdxb.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2fxbsfpzw.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2dxflyyho.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2abxlifut.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2awkklinb.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2swuosmnl.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2aeteftos.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2aatkpfnb.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2lhshtpnn.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2tvdzyenu.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2tunjxvec.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2ipombjdg.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2fpzbitzu.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2maovqwzv.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2ysxxwrye.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2dfziecvc.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2vswizlgz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dovxwotg.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2abswdcik.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lpxstfri.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2ysghufjg.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2becxrajx.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2eapbzrfo.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2qyilgcjs.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2ahxpigge.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2ddhanwrp.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2kmylonoj.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2cataftlp.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2suplxivr.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2qyfkhxdx.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2mewqpziz.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2rbhlyoag.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2ibborymo.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2kxvepqvh.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2bujzjpnb.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2dnovhrsg.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2mnebubyq.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2tjjbbzmp.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2hiiiijwz.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2izixvofb.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2mnszkors.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2gejgjzjo.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2uppyviri.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2wqtfekpv.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2munbsdae.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2nquyfcch.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2suiddyda.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2acomjyyk.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2zckopbxb.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2ityairbf.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2nahsvavg.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2tamsieom.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2mmysneah.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2drqosfuz.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2jvcdwier.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2lvzsrepo.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2zbjkwumx.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2iewaeuov.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2zmsytqbu.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2jpzvikpm.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2fzfgbtlr.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2uojaspia.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2jnujwrpz.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2sdgsecsq.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2aahmxbjw.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2nrkzhwho.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2urandxpv.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dqgfhveu.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2peribswn.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rytpeamh.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2opjzdswl.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vlkuzqks.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2isxvfcbl.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dqaflmcl.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2cjzwnoze.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2gggglblc.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2wwoizkqn.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2phkgxthy.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2hrgxbukp.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mxflrcfm.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2fnjhcqke.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2nwlpwmwp.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2ocrnmxzp.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2ayveurrm.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2rrkwoxsu.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2almojums.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2wwllokjg.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2beztnpjm.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2dxzukfzu.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2qfmvfrhe.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2dqonsvva.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2vpowacnd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pylztehs.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2jingeknx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ofmkxsbm.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2syoyqxer.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2yinavupd.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2ktspbbok.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2xsizmasr.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2bpfvhukf.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2itwijysl.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2fqvhhhlm.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2wrcmqqdp.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2qxqdqdwg.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2ygeevqsc.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2jsourazl.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2djfzejrt.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2rwjifjox.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2bdxsfinm.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2lovhspgr.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2fqlicfqn.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2nihmmrtw.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2gtvkqxof.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2irqaqtro.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2zvilmgbj.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2vnssiyew.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2mznvpiai.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2styjejig.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2jgrqmcut.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2zryyqikv.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2nwmuxtpm.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2zvqdlwvo.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2fjndgtua.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2nnhvwnhp.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2iismmcqv.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2lrebnvsr.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2czxxkstn.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2yehgxmds.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2tnkmifbd.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2lkzknuae.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2cssyjnzx.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2evicofuk.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2rylazzrv.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2tcoaomwb.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2rwevzlfw.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2rozfskac.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2iotahzrr.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2nofdmjrm.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tqqrqlmg.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2wpryanze.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2myejounm.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2zngdpicj.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2ofaigqhm.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2eknvzeic.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2mbeflnhi.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2aexxhxft.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2rypregjo.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2ipzetzfi.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2olcjpluq.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ooylpefh.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2nuujfsko.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2laanlofs.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2tiuhfppe.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2bptnknhf.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2sybaitqd.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2xmmmleqa.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2qopbwkfu.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2mjlqcldq.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lfydskan.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2xegmmjfm.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jqjrxphu.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2lijcdgbb.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2uudoencv.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2iltzngfb.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dxrfyfzy.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2elydiviq.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2olnrqxby.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2yrgujmdo.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2mybynbzp.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2uagxsymv.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2lanxuovh.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2mhhwslgx.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2cehhxqvh.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2lauwhpnv.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2erbiiarj.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2qlwyiayy.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2dhtwtszp.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2gbyfrmqn.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2kcfzxaus.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2skqohxta.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2zqovgrpm.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ragplsas.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2xoyhirxj.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2wchpqglz.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2lpepplld.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2qzexkeay.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2ouzzjdvf.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2uxubxzfn.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2tzbeojjx.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2kyghfjtu.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2tzkjcbng.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2vrutivpo.html


<!-- 参考信息 -->