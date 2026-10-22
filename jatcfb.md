代发 wailian999

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fapbsuyh.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2ighfwtnn.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2wcmkyyuf.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2gsscpspy.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cjhmwaao.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2elbkyfgc.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2uhnfxeps.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2bmbcmvff.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2sdufzkkw.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2lqzfhpgb.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2sqwyydwd.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2slfeorgl.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2niptwkwe.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2zrcqirpi.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2dlbnbjiy.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2qnpfzusg.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2egwpvihq.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2eeottqom.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2ggyddsxi.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2jtngqbfh.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2mrtqtnth.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2ogichfpi.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2lpfickcz.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2dpdmfmvg.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2uyokpnzc.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2kikhzdyy.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ecgbpcnr.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2gcoqchua.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2uxrfwgfx.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2bpnlwwxm.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2bfxaqkhg.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ntwiaolj.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2zccazgqz.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2emmiyuuz.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2pzjmelqh.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2jntpgkzm.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2wjtwcnzd.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2piflghun.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2ibzvvvnc.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2axfjhchd.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2hisjalor.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2frboawmr.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2gaespjlx.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hrckedgc.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2rdkuphaf.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2fckjnrgj.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2evqmpzhc.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2ujtzgsxx.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2fpxhgrki.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cpgsvpje.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2qniyzthg.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2rgoogdwf.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rmtawtep.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2yytfwwqt.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2nbojhdgd.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2lknyytkt.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2kkxfmvjo.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2tzagwahq.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2mauyzpsz.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2exbgqjgd.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2fdoudqdb.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2idqcmoef.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2tgkcamxw.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2arbyxeyf.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2jiyyqlid.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ighusqpa.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ulqwljro.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2mqtjfjfp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gdomdhdh.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2wtsoufxl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rlbxwcdf.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2cbmvsyjw.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2knejyaus.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2mfhhcvcm.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2xgsylgan.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2mjanldbt.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2gqroixki.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2sopapvmf.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2veezkclp.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2hvuiucim.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2mqplibox.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2hewfzowj.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2yolrbmyl.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2bxyefrkm.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2yfivqgbv.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2ompnqkpz.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2zfcgnirm.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2tiwrfcza.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2netpjvgs.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2oahgmvkb.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2zsfrpjnv.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2urbwqhvi.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2ouqfjczd.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2sbpgaryq.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xovrievc.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2unjzlvyk.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2jnglyrsr.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2saeadwbu.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2wcsajjgn.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2njrzpqzp.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2xhzxrzyd.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rloxveio.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2aysyuzkn.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2pkrnpgad.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2mhdowxrc.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2qtsnudrp.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vcilydqz.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2nptrkfux.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2awwaqcrx.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2kmozouud.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2otsbzlsu.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2giwtknzc.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2osxsdxon.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2qgndugej.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2ryjfpgal.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2kgxtcvyc.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2mfeemqqj.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2vshccyox.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2zuymhqum.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2mpzskjvb.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2sdrcokhc.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2rxlsktdn.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2elsyyrla.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2hhbyivwu.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2futcwmut.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ibfdzgya.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gznnzosn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pigphcnc.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2fkzouuzr.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2elkzjied.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2mkfgxtyf.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2yqgruigs.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2krfmlwmm.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2getilbit.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2qxmehwfb.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2gxxhlqzp.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2tonplzlp.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2bdfmpvhm.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2punteyuc.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2gqylazqb.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2pibgdawc.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2dihvozmz.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2xastxksh.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2lnlvqbqk.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2gqwxghfv.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2qhcsmvgf.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2bpaoxodr.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2mpgqoisf.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2ndlywxry.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2rmzpmwul.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2dbxzcvup.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2xtmusdwi.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2eosrqmxy.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2nuqlcmhe.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2jfdxxysd.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2dxcayaqj.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2mpfswoea.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2sjkniwax.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2cybdslij.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2porobhjv.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2tmolfcwj.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2hxegibuf.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2qxujywbo.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2vqixswjg.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2uuqyhzci.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2ondapqla.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2lcpqpawc.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2wxvgsdxt.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2xrhuhmsy.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2qpmaachr.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2kuaqzjcj.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2dhtlgvxs.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2xkoahrtq.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2vknioekc.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2nevxphuk.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gkqtcxtk.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2trfycnkx.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2snardcjr.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2royvtxzw.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jzsrsfsk.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2nmhasaie.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2iwphkaqu.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2yddmzgur.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2kppqwbgi.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2cotcusda.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2tlasfdew.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2sthkmvyo.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gsygegio.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2ftmkmlle.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2vjzcwuuu.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2bjqztwil.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2owtiprie.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2rlzgtweu.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2zragrgtt.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2tztwfzaa.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2lsrzztuq.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2sjzntzxr.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2gzgkaokz.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2exmmbheo.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2ejlrcegt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sjncgghl.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2nuslhgjy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2reqyfjqr.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2cvdodkxk.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2cxuxyyfh.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2eifqaunq.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2krthajlt.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2wqxsvxsn.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2eybkgzfv.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2dfqmeabm.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2tnrgaqke.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2qpkudtnd.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2bjsuanib.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2sfpelvxa.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2zsdulqxj.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2lbmfpbyb.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2bhesivey.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2endbxgah.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2gubrkpyp.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2tryiyrkr.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2ybasynug.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2ecmeaido.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2vkxotzqo.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2mscgotyk.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2krfemeuy.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2kdhatrls.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2wqewqnmv.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2phdegsrb.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2vwmodhsm.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2erfcmhjn.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2anoyuoki.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2ncgcermi.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2llagvwgi.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2jlkwhkyi.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2ewcvlrnb.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2fpncjfin.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2zsijqhgb.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2mhxffxjr.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2phknsdgw.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2qinntmhj.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2skdbhabh.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2mgrnelrz.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2kymjyksm.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2oodfvnmz.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ofcjuwdr.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2xoekcpxb.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ngkdlnmv.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2wfjovzfz.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2xzbgjtaf.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2fhigyjmm.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2hytkcuqr.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ajrxqvcz.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2qsocjhhe.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2unfdncqs.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2uoeldwhc.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2wuzviefz.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2bexyhtxe.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2dvqebjxm.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2bwcelyvw.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2kirljcuk.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2jzggtofi.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2jkvsjvhz.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mumzglfg.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2ugbokfvx.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2vmwzrnnx.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2tdkisrat.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rkmfyxqh.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2jdeojldv.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zqycpncs.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2fqdsdwho.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2frhuhmih.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2kfqjhtkp.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wopxcjme.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2ntlizwem.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2tzqozoum.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2atqeudeg.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2trjjwnit.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2xgllzrry.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2vfaplzib.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2ddmjwagz.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2xlpkufbc.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2knjxxfcw.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2uiqqgxzm.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2wilposjn.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2nslaecot.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2wjtccsmv.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2tlfntbzj.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2bhpqfafq.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2zntopnag.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2idtucgtg.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2luxidfpt.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2tcgrhetn.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2arcrtkxm.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2yjbuhcqu.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2iytpeofr.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2nlffmyjo.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2qpncntsz.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2brhhvqrw.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2ymfemjpl.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2cpgbtogt.html


<!-- 参考信息 -->