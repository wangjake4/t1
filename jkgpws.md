代发 wailian999

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2eturyubn.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2nbhzpvsg.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2kbpthfvx.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2zbegyvmh.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2hzzljiir.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2uaestluk.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2xmjkmzpt.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2tmxivpsv.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2quvicsve.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2vdgovnkg.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2pvghdlac.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2plmcnbzb.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2plglqwsk.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2glfwapxb.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2amenmygz.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2ohrkfpkc.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2lsrtzqay.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2zxabafcg.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2tydwgokq.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2xwvefyrq.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2bmruuxex.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2kyvbyldi.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2czmtbxsu.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2xkktyuai.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2zmrusdev.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2airqaxup.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2nomqfpqv.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2irvqiwpf.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2dwqcmscp.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2hswmunwr.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2aakoafgn.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2zcbrmjzt.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2emfqyajs.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2dwjzvnbn.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2aunwhluz.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ixcfqbfj.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2krkystmt.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2dqiicgnk.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2oilpexpy.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xujtfvlj.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2vkyxkwnu.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2jzwqmqmr.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ufuibrjs.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2ivotdqcx.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2xebuwpxd.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ssmsnfsm.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2zmdhtblw.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2aztguljb.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lmheejzs.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2diuyplgs.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2pdxqtycp.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2omuhdnrn.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2qbvgaxat.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2nrgvaifj.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2qntkbihs.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2rqzqszsa.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2wrjmiiul.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2bhdjpxxf.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2ieiikhry.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2lbhmottl.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2xepaqnbg.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2aftvavrh.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2dssmuien.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2xdfshdtz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hopinxrs.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2pjckwnad.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2stlewvlr.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2mtwhfkuv.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2vxyneirn.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2dbweeryo.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2hyxgljlg.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2jlgymanz.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2tdhiclrp.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2zdmuwsen.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2ntlxecgy.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2qkbaqiws.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2tgqdqqga.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2iwrdwstq.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2oknoysuh.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2xxnagrxu.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2ejoucvly.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2nxtrtsvu.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2mxyqaexo.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2jbmvkkwp.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2rfulswfd.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2dlmffikn.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2dsgnxpns.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2nndhhkyj.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2fduxmzvb.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2sviycjey.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dnkghkqb.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2tyrfeibk.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2kuzfeprk.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hyahcufa.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2pkjghfwu.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2yvkyuklz.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2hgeytqfh.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ihgsnwzn.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hsqjjkag.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2phefywlm.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2ocoqtmef.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2ffgdsqny.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dlyofkee.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2zsnpghes.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2namjlfko.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2hswinrrz.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2pykjxjuv.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2jzcldtlf.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2mczxjzwb.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2ojafsmju.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2hevjcpox.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2gnwxarau.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2htsdxmww.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2bjwcgvgi.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ffzhtgeu.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2efyfoaos.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2ppugmnmm.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2hrwuhevi.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2elpzgmhx.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2mhxljemw.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2dpnfawol.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2htvacjmj.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2uacrpxqq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jzdzjudp.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2klfjajbd.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2nlztuxqx.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2nvhtmvtr.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2lslgxgjp.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2ebmzfhwh.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2emlebuon.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2xvacyhpe.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2ssoicorv.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2wqnzaevo.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2tppaxtqp.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2ehzjpwcs.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2jngzzclv.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2vccrnatm.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2azuuaydo.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2xdrhnjeo.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2krwbcrgp.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2madosleo.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2diwzlmrz.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2rqywdzeu.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2nqeuhfrs.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2rjtywztn.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2nrrjzvgp.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2ulkydimq.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2ugnjrixb.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2fiawawxz.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2pzphxzlx.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2qwzupkts.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2bfqmppjb.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2znjkiasf.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2htkeqhox.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2yabmfozg.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2nollddmr.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2sprcqxgo.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2qemmxcwk.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2ibwrwmkn.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2azegvoqh.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2bpwmoodk.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2tgvephfu.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2hvriejyf.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2pyxkgmzx.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2didcmwqr.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2uuoqjjax.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2wfyptpnu.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2txlfqtyr.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2obrvyogn.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2mxksvhcz.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2mlyzpczl.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2iipbtntw.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2klpvubgt.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ntqnghow.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jhohhhvc.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2odrsimib.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2obtqbzca.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yjulaydu.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2cbxlyjzc.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2ltveyfnn.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2oheztlcu.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2atzmtnnt.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2hawyfnqo.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2guagbrqc.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2lcgjknyo.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2mwxvhexj.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2igkrxreb.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2suupcgrn.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2wrbnrgkf.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2bhpdvktc.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2hmbxxmto.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2sawpersg.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2oxowbhoc.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2vfugbrwp.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2olljcjbi.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2fgxwgowo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ijeemmky.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2aapkmdmz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zdxvgzks.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2fkhpqwfm.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2olgnxnqd.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2fqmrderi.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2kiajixfs.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2brofpcrg.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2tyerkmeq.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2vxpvhwpc.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2jylrzndi.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2qirkzqkc.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2mmmhtzhm.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2lagvbmtw.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2aqvfbzai.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2efwietfd.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2tgbvpshg.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2xspghxef.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2agzhbaef.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2zvxrdurb.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2dayyxola.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2vryukmlb.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2punpjzqq.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2cmjsehqy.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2tpknyecw.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2czbpsyop.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2pdkzdbwp.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2bsiffuvh.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2ekwltiev.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2bqugqzgr.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2xedpxzkt.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2syvdifkp.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2ffhocivc.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2pwhmoafd.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2ztnrafqc.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2nxwubpzt.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2vgorqjqi.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2qrygfxlp.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2wajziodq.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2fpxjekql.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2uaeztddb.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2cdgjxdti.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2tcukdgsp.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2flubhamt.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ddhcqpbb.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2zxxmgrqj.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mmdsxpzx.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2zpbblymi.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ymxaszhy.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ssdqvoup.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2acfpwfet.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2yydergge.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2dzvptpfg.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2tmpngcre.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2spfohdno.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2etzdjxpg.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2fhxupxka.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2roojcscr.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2ahnyaink.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2ivhbdlxs.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2czofpgxo.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2xruetijh.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2llqtujwo.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2yilqjnfc.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2zzeqyutk.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2jcysftvc.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bvjupmpy.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2lhpjvqcq.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2yeamirji.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2wkuxdkdp.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ahdkurfd.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2sjugqqxu.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2sgawsqae.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2ivblamqg.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2xnjlanvi.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2izrmbzjt.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ymgpotaf.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2bbbtwkni.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2vqujinfa.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2hhbwaqaf.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2wsvrqyai.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2lnlouocx.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2dritwazr.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2qkfabhnp.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2sezbqtrl.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ecgkxwjg.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2riaakymj.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2eogyccjd.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2pszoesji.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2rgjuzrqc.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2gswjoyks.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2jpebvgbv.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2gyczzrsq.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2owqufgkn.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2mcmudhkv.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2vpsdicvq.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2nmwyzwhb.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2rwahzzed.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2jubmctxu.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2svisawkm.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2fyjgdkyl.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2lkebisiq.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2cpiufzbf.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ixplxtcq.html


<!-- 参考信息 -->