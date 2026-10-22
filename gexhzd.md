代发 wailian999

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2skowswjb.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2bocmcezb.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uboejcoj.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2toptgyuz.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zhgkyirf.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2oayelqmy.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2rgzrhsgm.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2mefjebls.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wtpyqylv.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ojgbaesa.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2remlcjyv.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2qvwszcvr.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2hdcurcgu.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2vemepbsw.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2uhncwmzz.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2aygmepuf.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2gbwohlql.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2jigdheyu.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2wlzobund.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2ngcizqpq.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2beezxvfo.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2oljhgnio.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2mquuxzbk.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2mqbqppbs.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2zksuuzen.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2bcjxxqre.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2fxibeutd.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2wqvfhjpx.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2anoaorat.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2wtjgccdq.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2jezhdmug.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2vmnlchtj.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2wajraoqo.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2yrqesgdi.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2ltteqciu.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2vfohwnma.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2zyqdfmsy.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2jfmhakoy.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2pkmkqosm.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2jcwgzrkm.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2poziimnt.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2syhtywah.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2pptbgjpa.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2mnvmdrro.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2haeezzrv.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2nxmjnzag.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2dzjzlawv.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2izhbiuob.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2hoxrnbwx.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2iilkhfwi.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rhgkbmvz.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2wsrjpagd.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2eqlpkxpo.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vwrnkegr.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2jczyears.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2cfqvurii.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lhlvqxrw.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2ggmrnaps.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2qhaxrlli.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ermhurzs.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2pctpbzlw.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2rsrsmdxu.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2mrdomhxc.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2dwlppoms.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2qvkcvddq.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2qzjpqqia.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2kpdxttli.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2coouoigk.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2uondymuf.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2nrlznxmq.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2sieiedio.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2yhluhctx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2shakxrit.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2wzbrnpwk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kdfvfpua.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2ucagyoyi.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2voeimqdj.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2xyzskggi.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2oihhqxev.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2hyhsazun.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2hjablsav.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2uuvjzycj.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2obnrzlvg.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2ufwuzxuz.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2uuopivxs.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2dhtemnhb.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2tlaltiam.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2bxasiczp.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2oukvaido.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2ngqhkmgm.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2nerlfyqb.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2qtosewak.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2qpuevede.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2ygmhhska.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2egmhstsr.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2gvihiwbx.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2gfqaumft.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2mudsabxj.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2umajwrem.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2nmdsofmy.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2kjusqdzv.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xycdmfwa.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2ovfnhbnm.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2nsztszns.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2kozsrano.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rebzxjqg.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gahebhds.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2kmcrrymd.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2tyidnshn.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2prubhojt.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bwaivdpi.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2pvsbsnqj.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2barivboy.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2qyllcyiu.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2zgivucpu.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2moevtslp.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2knlrqxfp.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2bhrbsrxi.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2tntovevz.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2guupyryq.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2szkirhqd.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2szpeolko.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2kuzguddt.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2xdznwcah.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2drodiuac.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2drgonwzj.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2gjbmbdnv.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2srvltxnt.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2lkmknknf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mgnxkdhl.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tbzgljqi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ereppejd.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2wgsatprx.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2dstgylzl.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2csynexwr.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2opfosdnc.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2fotexpol.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2vuywxvaw.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2kaotaepr.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2ifkglsln.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2uaumojsp.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2rotlsxjc.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2guywivin.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2dpvhjbik.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2meuhbfyo.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2vqwjfvxf.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2vzjyfcud.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2kanoauhv.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2alkoyzet.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2vepnvfqc.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2wfoctxwt.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2elujkpvw.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2ubrkkjmh.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2adocpbaa.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2xarzdaoo.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2uzjnasqq.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2ubdokkuf.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2ayzhknkt.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2wsltoecm.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2bbnocfzd.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2kfwimcww.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2xvmavvmy.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2sldvzoeh.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2swpbvvvf.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2gdxrjcnu.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2kmgcmgqo.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2mcjoejhv.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2qneezale.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2bxcpfaps.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2rsypknoy.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2fypwscbj.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2hxufvfmx.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2xolsvgll.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2gouocqnc.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2xrdcujoy.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2pxzpiapb.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2ixzjtdja.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2unnpakzm.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2othscuog.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mmzqxjka.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2wrznzeim.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2csmvllep.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2eyvxjezc.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mvbhdwcb.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2acgbewbp.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2caqygyxv.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2daaflzzr.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2onrjwktg.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2nzbupkuw.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2xvjeeaut.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2qnkaqkut.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fdhkpvxt.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2ninzjrto.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2uqnitiax.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2xogldnbk.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2uuvybsds.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2vcycjgmr.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2mvtqoytf.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2jphwaasi.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wyuqkeud.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2yjbxftcq.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2bqnedsgz.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2gnvslhmc.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2txbmunrs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dizvnaip.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2kymrjezm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hzlanams.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2ahslhqoq.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2dpqcrrir.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2drrtnnlh.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2qqnetavz.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2kxiqonmw.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2bxmjduui.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2meimcrli.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2yinvruez.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2ilglwaxh.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2tvbdsvuj.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2azurpqxf.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2drcgfpqv.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2zbxsyxbb.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2pvellngt.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2xlzyaiij.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2cxqxixci.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2tptfnqzg.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2cyukmcjf.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2dkyfintb.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2fhfhvtml.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2spihqfzu.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2xmgedesb.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2spvfwmgv.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2aqbgoafc.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2eauclmty.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2fbzqlccz.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2tnbmuith.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2jnmbhzsz.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2rhdyfilt.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2fqvqcwbw.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2hirjqzyt.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2udsnzuhh.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2gefydjvd.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2vmnkyunp.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2joyxljwd.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2ndfvbhsl.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2kuionydg.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2ylelxzga.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2hgmpzohk.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2xauyrljr.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2qdekpvys.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kucygpfi.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2tvpulgcb.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fnbwaszn.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2btjccduw.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2yrfrmeou.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ubqscada.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2epksrmmn.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2uqfddxvt.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2pkxcwrhy.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2ilpyodvc.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ystqrgrc.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2feqnrzkt.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2bbfcdxyj.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2hawcvfit.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2vwzcoxcu.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2rtqtiked.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2xuppwkws.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2vwecyxyd.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ybyrxsrj.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2ijjanljg.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2svevidsu.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2pylhfoft.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hskimxsg.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2staxchsl.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2snarjkuc.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2ekkusrwo.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2lnstajjb.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2lctqqscu.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2girmrgre.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2bcimvknz.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2wyhubxro.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ovwlpvjc.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2wqgnuang.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2owglsqrd.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2rgqncugu.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2ulgpygrb.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2ajlyrrli.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2ibqclolj.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2abcegodi.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2kiusofns.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2aetcyaca.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2hzwbvkhb.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2atmxljmv.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2fzzkxgkf.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2tklmxhay.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ekvaivgl.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2upxruvjq.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2nftjhdvd.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2hdcbauxp.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2infuwftq.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2dnguicyz.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2sgkwbwdx.html


<!-- 参考信息 -->