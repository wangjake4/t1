代发 wailian999

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ipcpmcgo.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2vhgryxja.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2irgtzprr.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2dltepxzl.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2yipvydid.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2exjvsuhc.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2stotrrrd.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2nknuctso.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2thfkdtrl.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2oibiuysf.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2tzxyadqq.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2yroelluw.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2ivgbmwic.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2tiudhiaq.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2ixaiyoro.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2khuukbyb.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2mvktzhdp.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2uxqxivsk.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2xiynwzgs.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2nlvbrgki.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2jralflwi.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2ojwyqlkt.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2fxscwbbq.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2ansavnht.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2zqlsvihp.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2uljnhgde.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2qupgnnvv.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2jezefeeb.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2wfzbcuvd.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2bsqpbomf.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2bsalbube.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2hfoebdpi.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2srspskea.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2iqmqhsnr.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2klgxxnei.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2tlnbcmbc.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2bilkefef.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2afansnbr.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2gchyoyig.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2dnagecfk.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2pxnxfscg.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2yrsebqgz.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2yigjxniu.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bwbjoiyp.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2uiatdyyu.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2njqmyuai.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ykoichhb.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2ytumcekx.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2ruwuqozb.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lbwmvphj.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2izayvlbh.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2kgqoifqu.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nvhiufst.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2ulyjqqny.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2iuhswzuv.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2jxwbflze.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ztbtavqp.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2cgsoyqme.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2xtzghlgw.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2nmpixpqy.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2krksihbk.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2dfhzzxky.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2emamvjxh.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2onnlaboz.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2qkzbdqfe.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2uwntrdzu.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2gfpszskr.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2wcgricgk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2joqnxuqv.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2wcwfhwdh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mfkgiuwv.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2peqjlwqh.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2proiwzfh.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2wzhrtwtz.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2xwebhlof.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2yjgkaftf.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2wmgcrlks.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2bgjykmxb.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2wuizogae.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2fdgxsitj.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2ejqoiyre.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2gjnztdkn.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2xnbrppwp.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2rzzoafoy.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2fwrmuegh.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2tvwnctcq.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2wzpdxuff.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2rfnefeeh.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2tvtuttxa.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2ykhqbxvw.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2rqneoako.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2emesafst.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2datnbjpk.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2kjomsxwp.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wzwsbaaf.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2uwadoawy.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2jdnmeicq.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mfmsazwp.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2xehqmmkx.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2vlvcfnsg.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2jceyhrbd.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ijipfzte.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2atiaryvm.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2jppkpmwz.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2llgacdym.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2ctpnrkqj.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wenarykg.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2fooonjku.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2oqdxwmxz.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2mhacopqy.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2xrlhvnkj.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2pivpnrul.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2nytotrrz.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2qmyztyjj.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2vlodlvxl.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2jovdudva.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2fnnwpwuu.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2ayvdttht.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2niapbsvz.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2vfaddzww.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2ibmfjiru.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2vtcjyunl.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2xodquhzn.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2sggkbdlf.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2fojrpqho.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2siryanmd.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rhygxmqk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ashstydt.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2qzerepwu.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2ozicsqil.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2tuyxlpbh.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2zlhduswb.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2nkntgjkk.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2faobrsky.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2yjtcaduf.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2qmlozhzk.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2rjpngfzi.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2posmivbz.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2yaxqvolw.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2rtzybfhu.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2bdpvkice.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2upnqicag.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2rnbjhqog.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2hnbsntko.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2rczcylbw.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2cqmhncwc.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2xduqaqqh.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2qonesxwj.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2urckphls.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2izafczfo.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2qiamhqoc.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2sgamopsg.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2cvmjphbc.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2mlqgbvup.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2okznctzv.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2vgolkiro.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2zuytbrgy.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2lopzhzgj.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2klcvmncp.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2sqgfehzb.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2yoaunvmz.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2edwzhseg.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2mfqlsmdu.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2dzlpegzt.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2pylzaivo.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2gugwaoum.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2htfwowoo.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2mtpmucqi.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2yvmxjcuh.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2lyyymvxa.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2rxjhfoif.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2mtjkqtsi.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2hnlpdbxh.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2nkzyljlu.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2rqtkcgxv.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ddgbyftp.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2volpsrcj.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vbtamazw.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nfmwpaod.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2itfurioc.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2jmzpawrm.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2okarfide.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2assfmakd.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2sshgmkfr.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2mpgrdreb.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2qbfivkfe.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2vcikfplr.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2brphymuk.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2mcojlanz.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2epitphpj.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2xncqngvr.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2lebvktnx.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2zibhicvm.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2kuqsudti.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2xlxjnhia.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2yowlbphx.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2bputzfgb.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2akdluewv.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2kbeibbso.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2fbfakyqf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2synwjlul.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2vgwxdyhf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sykittok.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2spgdlxis.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2ymcsmwjp.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2wjqhbkst.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2hpshoxur.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2rmsbtzbj.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2cjnxtnyh.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2sroufskq.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2akysefqg.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2msgxwvyj.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2tnhmrbmo.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2ihqijxwn.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2lakzvisp.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2kvtdpcxx.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2fawlaapl.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2qipdzgaj.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2xqeeqiws.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2nidjywvd.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2hkeitxct.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2uvxzoltn.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2wpmmayah.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2efbmnhpb.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2pwiirfvt.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2tdmpgboo.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2cjrbfrkr.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2ojyyzmhm.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2vgfkfunn.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2spitutcp.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2rorjkadx.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2zcprwtbo.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2aiyjsjgo.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2ekgahjbh.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2vymmhbvl.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2ehvyvwcs.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2gdxefwqy.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2sthmcxpt.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2mphjyfna.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2ofnoubgm.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2jmeerlhp.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2airvqked.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2zjpzbjcs.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2rsthloon.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2doxbvkmn.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2trxpgsik.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xmbdotwt.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ujzleriy.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2piemqzaq.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2enumriml.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2qvdglbqy.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2dkhotxcn.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2epnwntsm.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2jtgvgqju.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2cmbukvxc.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2zayvwfwc.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2eehawaoi.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2rkmlapak.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2uacnlrvc.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2issbdzyu.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2cafmqccp.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2boniieqc.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jwefnewz.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2khlgmgxc.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2tsipzjed.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2qkssdarf.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pvavknln.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2mkwwtsoh.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lwebcwtg.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2mscxqyjx.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ovlxbawj.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2nldofwro.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2cpnfybto.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2qspyykke.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2wdxnmxiq.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2dywbtixe.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2rjcpqwyb.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2rnqsjwox.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2smdvkktl.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2meckgwav.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2wbpemdvp.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2oizxmdoh.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2lejeehev.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2xrdfscer.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2vmygknga.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2plfulpev.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2wfnhqtng.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2zpbnpeek.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2erltjfxc.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2zurynefm.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2gpompzbw.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ydmxdzwq.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2wtatlfnm.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2eyhgtzpp.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2oetardrc.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2sevbsilh.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2qbjfqycp.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2okcnvrug.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2iiotzfwu.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2regekrgg.html


<!-- 参考信息 -->