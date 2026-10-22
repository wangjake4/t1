代发 wailian999

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2hzjkafrz.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2jjjegrpv.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2jxfxeurp.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2paiqwdku.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2xvuqjfwd.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2bmnrchfh.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2lheoupbx.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2mynpddjr.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2owpqzxwy.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2psocuuai.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2xluyndth.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2ncdgjmgi.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2dzyrxeuq.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2leoffvon.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2qjbyhzdx.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2cfxamyel.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2txvsgptx.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2dthrijwh.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2gwjughqf.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2lsdmxobh.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2vwncirhe.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2qrovibzr.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2qiocircd.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2rtyqqhze.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2ulelpeeh.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2srpnopxt.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2fcmimvnj.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2wjfjmclt.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2isxmhuqq.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2vfonsskx.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2agnrrojo.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qajcgxcr.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2fyciojrx.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2zkdjboye.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ygjcfrtd.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2hacrfwby.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2gookderx.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wkggtyge.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2zljgbycd.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2ucqrdxmw.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2glzzorob.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2lcqbkjxw.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2wfnhszpn.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2mpyrbfra.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2qpysuybk.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2utsyutne.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2sbgbckft.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2evsuiszc.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2ltdntfcv.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2wjwnfuel.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2mmvkbeva.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2tupjnnsa.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2qeysgcii.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2jsistpqx.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ctaqftid.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2idtfkhiv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gxpubkor.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2zusiwirv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dilhqfgo.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2qjkegwvc.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2xnihndmo.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2xvmgmobp.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2uvufsxiq.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2wkohejdu.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2hdyltnrr.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2cpzbdqhn.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2cgkslgzn.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2sevibpac.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2ngadgdms.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2bshhjsbn.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2jqjxtpgh.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2hhfhwwyg.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2pxpxazsw.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2cufcprlx.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2rnnkgmsi.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2ozaywecu.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2zmvtixsb.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2oevaxesp.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2likbdtyr.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2vedtnftp.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2vltwseyg.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2dzyfzujo.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rpfwtvbi.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2cgmpbpqo.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2fafjpzcn.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ncsxgwgj.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2zfzinmkm.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2oyxkyebp.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2ldgmctod.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tdkukoll.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dvjnteqp.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2jyrlkonv.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2ywwmlkyu.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2dryauoam.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2furwjtba.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2pyyaehlq.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2pnfwratf.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2lyctbkns.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2kzwpbjue.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2bdohhski.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2cdskzdkq.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2zarooiwm.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2vulxjzps.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2bonmhhmi.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2tqredjbs.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2gfbcvzik.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2gkyxendi.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2vcskaptg.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2frvdguvj.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2hhmxhjik.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2slrafzpe.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2fexyauqy.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2obtncwkg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2capsxvta.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jrcprtga.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ecdcwatn.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2cebkfgre.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2ajdyxkvj.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2jabtrbyd.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2gcbusyvz.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2oqhrelct.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2ryhxqdpg.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2nambggrs.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2oxohevqu.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2hzacyeup.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2xwwlvjgq.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2nfmulmxe.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2siqgbrjy.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2vbtsdtjm.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2tsgxvvrv.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2argufcru.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2fxilvkeg.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2qdbnmkhb.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2jmsoddrq.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2yrdvcqxy.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2lqizmtzg.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2mnktrkku.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2kvvkujub.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2jdmwylaq.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2thwtnyms.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2xdedldkp.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2nvhmmfyv.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2lnoqhwxb.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2pcaqfygc.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2biyjuocy.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2fekcjoah.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2smnaacrb.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2jhzlzect.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2aajdcsjq.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2bhsinzyu.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2hqzqfwxi.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2xcihdqww.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2hoecxunn.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2pcinnzuu.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2tdodpqow.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2fwphtoui.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2njzndbun.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2nqdfjdlp.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2mjxjbdvw.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2zklncbdh.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2zltjxiob.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2axdubwej.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2ckjakcvg.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tyikimst.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2soaxcqnu.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uxfqagig.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xmbnukbn.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kwltjhlx.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2hnqoopqy.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bkgbjkst.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2yczgwfua.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2whmhbpsl.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2jgcwxxjf.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2hweksmky.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2lsgvygmh.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mxxwxfvs.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2vqarbotl.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2lakxltgs.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2cevbxiiq.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2yzwakxrz.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2ivvrzzzp.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2wejxmzjz.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2phhmcqdj.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xjxoguhe.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2fxbmdvxz.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2fifiamad.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2yhprkayw.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2qfvbiafp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lmtfyycu.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2affvgons.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ctrhansi.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2cmpcxrqz.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2ycelqiul.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2cnxnkece.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2jeuvlheo.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2ivzteonr.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2irwycypv.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2cfxacmvu.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2ghkzbotp.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2yazreuyg.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2ppbhrfpd.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2zivkpgdm.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2jftfavyb.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2lrxhssjd.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2tmiphpze.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2zetwtert.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2goseobwa.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2exwlqudx.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2webfsnrr.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2hxpqhzcw.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2dbriipir.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2trswvbtf.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2emcfoojh.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2nmuiuwkk.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2mzjiqiqm.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2exkcprml.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2wznspzlz.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2etmvjcnt.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2qowquntv.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2smzuwcza.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2tmwrznmv.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2yssdjqyi.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2vivqfphz.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2nqtgqqgx.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2vvrliwny.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2wbsxenqc.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2nspbtwnj.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2cgcywsyv.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2xoocahgn.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2euklljot.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2zjorjnmh.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2tzldmwow.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wexebjkb.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2tdkbnapc.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2emouvamq.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2uhurobfn.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2xdwszuuu.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2jnsnlbkj.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2wuxdrifb.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2sobusnzr.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2dnnabnad.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2vcadqctn.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2txdueawr.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2fttgweso.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2wfaaeonw.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2pdhuxifi.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2jguwaakg.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2vciyrccg.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2ztgyygni.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2wkeefcoa.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dywmxrnx.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2dailclxu.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2flvtsnol.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2fmoqbflj.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vtjnnqlc.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2tppxihdb.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2azjwhhvq.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2wzoobwyd.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2jelwgkap.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2rzxzihzq.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bmnqvzzm.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2fkgauwsu.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2mnajeokb.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ofyutpbz.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2tppjaljp.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2rggwlnqs.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2dskwppgk.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2mvuoimpl.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2kidakdru.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2onxmbgmb.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2asgyqeeh.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2rzibenqj.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2imxfiylq.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ulifganh.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2mvelxble.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2jfwdfaij.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2pyatghbb.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2mumyyxbo.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2tdbiezca.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2eqklewsy.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2vwfzwvas.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2wdarqgeo.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2exjawmxa.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2lwxhdhwj.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2fssylekp.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2mowooczs.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2wknbxpbe.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2egoxbhin.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2zdprpakp.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2tglrtxdv.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ktqahqkz.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2lvyptfji.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2fqcwibur.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2ssvdrruo.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2nvylbvyo.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2jozwbdjc.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2hjgaepwd.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2gzfcplib.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2zpglabpp.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2lybelvqj.html


<!-- 参考信息 -->