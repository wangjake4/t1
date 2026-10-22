代发 wailian999

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vyllfusw.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ztkwwtta.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2jcjjeisf.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ferppuqu.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2ajkmvjln.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2glteatwm.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2yawjfuzs.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2jghxumxe.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2gryjries.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2dbclkvmr.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2hwcvixbz.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2nirrncnu.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2lmovpjpe.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2yzmkjukz.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2fwcsqoqy.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2egbjtrnv.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2jfknitwj.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2uubdzuan.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2kyglmwmj.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2ywlrgqti.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2fyucbrhc.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2cuyuaunw.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2aavcddae.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2eudrjyiq.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ulkgwhfc.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2obbpmgll.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2jxpsaath.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2udxssapm.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2mnxbwzkm.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2xpcfjbef.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2kpvorttd.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2omblgyjl.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2toajbynl.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2cveiyczx.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2bsujzzmo.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2zofwlxpu.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2xcqfngxt.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2fmenokxi.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2prdxymss.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2htghaeri.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ulffidfx.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2ttauenqr.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hzpontmk.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2avdqwgpg.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2wwpslbji.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2skeddddn.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2upnonllz.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2sizysqwk.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dxgxqkrc.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2joorsbod.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2grlhunxx.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2sbithmmo.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ymtrmthm.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2oxfvulvf.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2nwmhdpyz.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2vbzbcbzl.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2dyfdkqnq.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2pqnbbvbn.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2hbrcxybl.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2exraoxjg.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2thwwmpup.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2hmwtolwr.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2qanjhmbk.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2duuagvrf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bpuoiehm.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2rpipwnxv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2djzuhccu.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2xshdbhca.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2gqwiylsi.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2eimkrmpk.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2zrwbdcob.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2mxaftwgs.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2bjszavoj.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2bxqofqnx.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2odcgengp.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2weroptsz.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2mdlearns.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2hjbvnmiv.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2anapvzqj.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2akvlknik.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2zhveraob.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2yrtqdpxy.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2slkkkuia.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2vwasovsx.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2ppctszcm.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2cdbghlhq.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2lvfqpobb.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2zvzmbboz.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2sbkwcucl.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2yygurilk.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hwnfsdjw.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2vcptfusl.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ggzjaugj.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vgzobvch.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2trtcwgej.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2jtcdvlnz.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2lezuqowj.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nvujhoqt.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2yybexqjn.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2ymysvdzl.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2pladhnrf.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2cdocqeqb.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wmyoyvzr.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2rxsrhuom.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2tinsjoqe.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2hpbzbiam.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2cnfpxfsy.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2gnqhhhtk.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2eivekyrz.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2hcwbofex.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2mlnkeayk.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2icchqqgj.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2pzrrycez.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2ntvpoifl.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2rrmvfkfr.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2etxyfqbk.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2aqjkzjew.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2fmrrnjqe.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2hkuyifgl.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2rbwokbeb.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2mvxotbxi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sgbpnzhx.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ktqagnjl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2grpmmktd.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2yzseuurw.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2gagfsqpr.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2fozuxwnd.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2ugxpmxak.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2vcbyviyx.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2btmilbxl.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2sawqhcev.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2icszgwac.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2bhyklaoy.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2gcxpfxwt.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2pkoontza.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2uhuntmus.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2qgregznq.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2aloxqszo.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2yvuuikqc.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2jefhbinl.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2yukfrdor.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2hhdutjnk.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2qkamhmwe.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2xbgvtzha.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2fyfcprmi.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2aiyuysff.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2smhdbivo.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2ypaofbhy.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2toqddedr.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2hmhvuvcj.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2bwjiwaiw.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2zntmikkj.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2eyxvwkjb.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2ivmyoqdb.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2wiomxxee.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2jrsmydvc.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2kswdgiph.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2afkxkaqw.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2odtwghzv.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2faofsutu.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2lbugnars.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2jployfvu.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2ncsdjwvi.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2euhboeok.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2fqrzcpbv.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2ihrrqwyt.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2szjspsff.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2mnnxbsrf.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2djnrldna.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2tyotbboi.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2gavufeig.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tnacqunt.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2uspecszy.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ekpegsic.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dtseepcv.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bbvimkrd.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2zdjcwzph.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hpcothey.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2izbxicrn.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2clbjcvnj.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2fvwnzceh.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2amylyvjy.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2vlfnsuuo.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2avcoaaqz.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2tnvnxqoj.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2faertwfg.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2raguxnky.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2vpvyacxg.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2kqiogzey.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2ovsvrdrd.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2iwrfqrqh.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xzqupzbm.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2voyhqcgl.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2grkwccas.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2iilusqhb.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2hbbrzhox.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yzokvfhc.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2kewtqsjc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bhaveede.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2sxbnrnsv.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2botqhafk.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2lssuymlc.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2zncegcci.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2rlqcnlso.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2lbaihdlh.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2ebjkjrqg.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2lalgdvmi.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2sgexedsr.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2szpscgvc.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2kkcnozkj.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2ntltlexz.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2mqrmaemg.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2aurslpwq.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2qffhiejq.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2hjpawadw.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2njyzfodm.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2atnuxdnq.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2zkdduryo.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2slbwcksv.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2aqshlecm.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2iztilrsf.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2wgwjmsjw.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2guvewetq.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2psscfszi.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2fvewlvof.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2qvnpcfpi.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2jgtrrokw.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2eorqlomi.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2qtvukuyw.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2aauuxxsz.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2gpgfdxfk.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2mdfuikie.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2fksbnoeb.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2kyraapui.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2azvnicis.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2awysygxz.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2qevdypwv.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2heeubtdg.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2pwiwrpbc.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2wquooshb.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rcyxkwaw.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2riyexsrj.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ravaawbp.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2oalbflng.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2yguomjcj.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2gwrzbhvb.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2pkjbwaib.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2opbyyasc.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2axeadsig.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2rzohgdig.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2czzpsrbp.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2tuuqymsa.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2akvuidfz.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ivpxpzss.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2ecvzdvvf.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2doonkutr.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2mgqqinrc.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2yerhsksi.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bryxasds.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2rnevycgi.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2ujzethmr.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2kxaqaarz.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xaurmlya.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2pamiaavx.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fxstxstl.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2utrseleu.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2agygrayt.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2pyeuiuiu.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hwufdjmk.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2xvkznvmy.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2hemyodsm.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2fcqinugr.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2boaewdis.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2vwznkyib.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2znehhjlp.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2lfjpfarb.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2uvvjthyo.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2zrdzusrp.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2yeuiztyz.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2ajowrmje.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2ukrejkwt.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2wlnirthq.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2hyvmqabm.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2mbxawgei.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2zvktoapm.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2kyzglgvx.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2gamaoaej.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2cpgvtzkj.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2qtxoxqeg.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2vckggnly.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2ngzfrzip.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2cqiunqoe.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2rrbvzmer.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2tfdehoch.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2oejxndlf.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2szdqzgey.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2dzctlzgb.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2trugvsno.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2mdjmkxan.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2rqfuvcat.html


<!-- 参考信息 -->