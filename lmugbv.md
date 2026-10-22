代发 wailian999

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gzdqkmhe.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ethyfufy.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2gdyzxkxr.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2zzkzqcru.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2ubqtfpsq.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2wpuvttiq.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2wkpkgoyt.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2obumvstx.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2vhkimzym.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2ziijwqbs.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2prfncfnn.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2octzbyac.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2dxogjtzl.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2dibvpybl.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2qduenojc.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2mimyudrw.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2rnqlmjiq.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2fyajsrtt.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2fcvavamz.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2ynltjcyy.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2hpgwznrs.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2ynbjkvuj.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2gonhuxdr.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2szlblazi.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2cfwyrfca.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2aznifuvt.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2nntzqnax.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2idrnrolz.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2pvyoefjr.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2mtjlhfbb.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2amuskgos.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2yqgyoskv.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2qzaphqhd.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2fiymykhf.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2nfwulwbo.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2stmiacjy.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2mlgcnlqg.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2clwksxdw.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2otlkibsz.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kivkercz.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2omjeofpr.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2wlgjakbe.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cbxdybkf.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2svrmavyd.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2aqwxukav.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nrogakyj.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2qmrdthsg.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2kwktphps.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2saztkuys.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2sgoqkvjw.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2fwomjmrz.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ssllbzfb.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2kfphllrc.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2roixzagm.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2unbdjzij.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2qzilznmu.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2ezldtawm.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2bnvwhdkg.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2zsytnext.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2ereyoemv.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2phupdxcs.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2abcyithh.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2htkfeszr.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2klzfszsp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ujqgvsoa.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2agyudygb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wznakqmu.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2ieshlmuk.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2igsaoywg.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2rxqkwlea.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2qnnstlym.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2rdnflwus.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2mjpptqfs.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2mkwksjga.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2vpupcebm.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2pmmwbklh.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2axzhncus.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2zkvxwrar.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2ddmggjhm.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2pkgpqgar.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2wsjtnilv.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2swwvwkij.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2uhllkkde.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2kuqsgtkt.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2zenphscm.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2ikqcktor.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2wvcyqbjj.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2puxmcdlq.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2myxdhzhm.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2cngvuerq.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2otxrbsew.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2vqbxwlkp.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ikksmiin.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hvsytxgb.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2maiydngn.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2affjkyog.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2ijpalfdu.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2scbotxuz.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kvgnheul.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2exrzknnj.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2oaeuespa.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2xkpkimez.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wwwulaif.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2kwxxdjpa.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2axwbswyq.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2ihbzpamb.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2uqqnrqmn.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2nwyvkcmh.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2egnbxkny.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2hrjkfpib.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2dtobtaeu.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2arvjtmjm.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2tngdujgm.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2jaujteva.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2guhhhsib.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2doalhxsf.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2fylgmsfa.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2mgxuehqv.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2bzeulhff.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2hmckhfbc.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2vkitbgkq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zpyucpnu.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2aitzqnyf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lgpshbmc.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2nyrhbiht.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2beuibzhk.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2yuoqcgxb.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2mlkjsidv.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2wkvplixh.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2zzepseqq.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2wuslthjv.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2kjksnfxh.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2wpxenlrb.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2crvukyrq.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2aedezkoj.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ameazooo.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2brdsgsll.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2lqctgewb.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2twibzole.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2iifklzrj.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2thczngzq.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2ydgfifmz.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2yjwppsea.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2fdktxdok.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2onfvetbz.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2bjrknsbw.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2liijkujk.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2skmnnvnm.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2nowgdvql.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2xgsyfcbz.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2wjslrasy.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2isqlxgnf.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2dtfuvujr.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2pfvfjcxu.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2alylodrn.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2ubwqnbnt.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2cieecumx.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2wdjdfuuq.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2yefoctvq.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2deitoxdf.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2gociqlok.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2ljspqozz.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2aawkgaxm.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2gyblyfyq.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ouyyqrzm.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2cszkwnqp.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2evfdippp.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2jjltnmhb.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2uwndxior.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2nlovsiom.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2fflcjfzg.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gtqwayca.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2iddzgqra.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qhnkwtqp.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lfsbjktn.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tlbqqmyh.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2zgullsio.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ibblrdoc.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2ztsmtuzt.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2dpehvvca.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2fdzilzhs.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2bfcviydr.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2tntaclbs.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kfqdhfwj.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2froirlpc.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2rqwrlacc.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2fidezpdm.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2cactrlxs.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2ufwgjyop.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2kwllurkw.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2vfyteoid.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2yjpmlyzi.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2jykwsdjy.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2ibrbvndn.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2rmygwyrj.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2iqthpwqk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ttmkktgy.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2osdnkmvf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pzubfkok.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2nsxyqfwo.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2gwkaxmxd.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2qlmdbbvh.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2ohibgfwi.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2ysiwqkwm.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2rytieqhk.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2flwyjfhc.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2wlxhppjj.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2zknxkion.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2dorxlmbj.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2dxnhzfky.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2pctghpwu.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2iwmalcqh.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2uzhrwxnc.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2rdkqjbqb.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2onoystso.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2cqwmzzoy.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2uulpydlp.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2gczqqjnd.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2pvqkurpw.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2rfmjiuux.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2oewbvsqz.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2xgkqjcoj.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ofyvtski.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2grmaqqvk.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2vpwyajfd.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2bgujqmxj.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2tcupddrz.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2dssqmujd.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2gcgfxvdq.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2hcvjyrdd.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2pzqkicbz.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2qgsvocof.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2jguovkpf.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2dhhqjrgm.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2jilictwt.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2qtyuoyww.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2aejhtbqi.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2jugqeadx.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2ouhfofqe.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2mfewkixb.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2iusudjsz.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2lhatvzoa.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2yicnjlki.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2kpvgayvu.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2mhdphnhs.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2kmklbhvl.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2stdknrmn.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2dsfehxfh.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2sprynwos.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2tfotxckf.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2jyooccba.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2mibzksuj.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2oawksyrs.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ilulgmok.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2nrthkkig.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2ghsoojba.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2idrubrun.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2msettqzd.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dsjowspa.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2jghfiwjq.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2chfgxkfz.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2meevrlle.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vohkzkzb.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2yccwxguq.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vunljoqi.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2dywgicdp.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2lpxirczg.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2sousavfy.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qpkubghu.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2ghrlpeqw.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2lqmmdfkc.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2jukmruzb.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2jdpbkraj.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2cyqobjva.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2zfjmmbfe.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2nvkgkwvg.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2qwwpvgfo.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2etiwifxq.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2ljmfzzra.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2yttugkxf.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2zzhtzdos.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2pxkqafpc.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2lriwluog.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2jqeekeuf.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2zodwasuo.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2imwunfsn.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ctbcwdow.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2fmwmntvd.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2pdvdasxy.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2xounyaty.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2uzgeszdx.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2rtdqnkuk.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ztasfakc.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2uwdfbhaz.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2azokjegh.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ihvmipfp.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2aeocrevy.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2nfcapgpw.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2kfptryub.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2bqetlrnk.html


<!-- 参考信息 -->