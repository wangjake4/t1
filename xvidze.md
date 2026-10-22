代发 wailian999

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fwaycwmv.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2pjhrqgbg.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2abwdfaek.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2xncsiobk.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gcaaxqbo.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2vikjbnkh.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2fiauyifl.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2fgaolwtm.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2jjnmyfix.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2kbimidok.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2rfwelejb.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2lancswpt.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2mvuhpgjo.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2eulkxtzy.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2hygdbkhn.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2zinsrzqu.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2hfznfkrn.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2trpokkus.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2rjyemeqt.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2jqucyikz.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2eprhymuc.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2ljqcsgno.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2phxayibi.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2pzgpjfqv.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2qakmwqfu.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2mviyhrpj.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2xigdbrju.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2fhwwsxzw.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2tvdpfbsp.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2gtrayoxy.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2zqjqyjny.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2abixvhml.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2xjpdfwft.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2xmzkmowo.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2fsyuvcsi.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2hrlbmxkk.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2agilfixr.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2rdtqpmsw.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2qpsbwasa.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ldnsdydo.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2jgwwlzuw.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2tcobumpn.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2ghatgboj.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2byrkfczo.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ildesibu.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2amconxqf.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nugzehqz.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2thfzgpoa.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2tfrorzsx.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2biezsdus.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2jgxrgdil.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2mqibueei.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dcqixsih.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2uwjohqhk.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2qcgjxzgh.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ibiqupdt.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ttiagtrs.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2fqlcwvbq.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2rmavggka.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2lznylohi.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2glsppewh.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2wdrdtnet.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2kdcwprtw.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2tzaffuak.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2zeukzpps.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2hmvrhnra.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2nwladxli.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2cylffnpu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vhzuozed.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2oxppwtjz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mduinlbi.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2zrvxmqmh.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2zremmfhl.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2kbtunqou.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2edxmyrfz.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2ihozgrbh.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2hszfdqur.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2nevmjmyj.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2bopozooi.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2ikxyaoqs.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2usspxxlk.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2oklgjjrk.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2tailagfm.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2uobgtdsv.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2cbngtjxg.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2dsmvoahs.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2hwjrrrpz.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2bsqembtg.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2vfonwblu.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2rufeqenz.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2znuevrui.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2xgqwkwhh.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2aaprhtzx.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2egybkxqd.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dtgscfgb.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2snxdeksv.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2htlgpbcl.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ntjvstch.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2hgwkhdpu.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2rpypxaew.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2ldzckndw.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pnujwepr.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hoxqlols.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2wnytzmzf.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2ctutmolp.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2dlisjhnd.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pidqeigr.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2mtfrktlu.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2fjhsqnhh.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2tbjsbnlx.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2sfmdbhhw.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2osowlbkq.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2luycfqnb.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2jygmgexd.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2tmsksraa.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2yveijlus.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2kfjishny.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2dsergemz.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ouwjondi.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2tukwcivt.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2aljalrrz.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2ejlbctgl.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2fpsvfmmo.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2yiimjfzr.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2gmfvjcfs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fvezdfsx.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kcbbsnng.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uttjvsuo.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2asowcljk.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2pmegbhia.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2pyyljbkz.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2rxnorzea.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2vuztxspt.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2zvwamwnj.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2zaxskouo.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2npuuifeq.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2xdjvrebn.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2vdrnevvj.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2duymcwhx.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2bdhjxbhd.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2qgepzazz.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2insdwitu.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2thkhzeez.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2rpcggxxy.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2eduegfwa.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2eoyervey.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2hiqaeckn.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2ehhvrljw.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2tcochhkv.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2pibmiyhj.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2rtwkvdhs.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2lgqbdmax.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2yhlriwmd.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2bxhepmcs.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2osnupmlr.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2hhmckoio.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2pyaybbzj.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2npgksrkx.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2gxmzctmw.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2dfrimeqj.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2wkivmdfh.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2mfnelbwd.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2uanpyxou.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2reibyoyd.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2tjzzksrr.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2nvtsoebv.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2tthprzqk.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2hqnponwm.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2goroflze.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2yjsigfdj.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2nxlvuxji.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2steiaacs.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2kdnjazqa.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2yldfcndr.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2rrvbhrnq.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qhwrxchu.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2modjirhc.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dkusaork.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kcprtwdo.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zhyribzt.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2dqxcbkhi.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vxszdhad.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2bvrocemr.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2etxpcujz.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2nbsqgvzf.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2wifyhquw.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2aykkjspr.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2klsuqhgp.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2bvchongm.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2irzaozvw.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2gvgdcaft.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2qpdooxut.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2rkpckidy.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2qmxzwlac.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2dthkdupk.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2zfhtcozw.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2vebmyeht.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2kzduewpe.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2hbfkxmhu.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2lfsoitrh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rcuescci.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2uyxjpiuq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zcyzyith.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2grwyicmz.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2tgacqwqv.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2ckmfvuwo.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2qivlskqu.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2fraymsli.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2bidlbdyw.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2yvyljgzk.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2yyvwbweu.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2gnbzvuar.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2qzzyvkrj.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2pttetuyp.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2xemkmfah.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2knlvpqio.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2gmyqrumy.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2qakqjxee.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2fjshjyul.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2uvfpzpbs.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2innqgral.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2lrchttwr.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2ppuospfm.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2otzjyruf.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2acuiecwa.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2blntzags.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2jtnipyhu.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2zabxkjaf.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2fghfevtk.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2bksjweym.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2scuwcuoz.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2savhlxku.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2mgkaquzr.html

[Q11] 一次插入多行
来源：http://dali.zhijiandao.cn/Article/details/gt2ptitizaf.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2oowqplfg.html

[Q12] 插入后取自增 ID
来源：http://dali.zhijiandao.cn/Article/details/gt2klslibsg.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhijiandao.cn/Article/details/gt2msqktxpx.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhijiandao.cn/Article/details/gt2vlbxobdz.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2znutzhrs.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gt2zzbnmmkw.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhijiandao.cn/Article/details/gt2pichjqok.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gt2dmympetv.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhijiandao.cn/Article/details/gt2tqorrruj.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gt2efacskvz.html

SELECT * FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kxpanzwr.html

[Q16] 查询指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2qvjlnijk.html

SELECT id, name FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mbiyythj.html

[Q17] 条件查询
来源：http://dali.zhijiandao.cn/Article/details/gt2xvqtqrcx.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2vfadvkkk.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2wzvvndvw.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhijiandao.cn/Article/details/gt2klohfbou.html

[Q19] 范围查询
来源：http://dali.zhijiandao.cn/Article/details/gt2whfrytks.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhijiandao.cn/Article/details/gt2kaidhvqe.html

[Q20] IN 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2uiscnavy.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2jczzmjfz.html

[Q21] 空值判断
来源：http://dali.zhijiandao.cn/Article/details/gt2dokxubez.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2jneouhey.html

[Q22] 排序
来源：http://dali.zhijiandao.cn/Article/details/gt2vbmdlvdu.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhijiandao.cn/Article/details/gt2tnjduard.html

[Q23] 分页
来源：http://dali.zhijiandao.cn/Article/details/gt2pkgojyio.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhijiandao.cn/Article/details/gt2wdszasuy.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2nudnqfcn.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pepffgca.html

[Q25] 只取前 N 条
来源：http://dali.zhijiandao.cn/Article/details/gt2wmcykaga.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhijiandao.cn/Article/details/gt2etmlljgp.html

[Q26] 计数
来源：http://dali.zhijiandao.cn/Article/details/gt2rlwrchvd.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dpwpshok.html

[Q27] 条件计数
来源：http://dali.zhijiandao.cn/Article/details/gt2kgwxokuv.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vjepzpci.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2vcerptuf.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2apagpjdv.html

[Q29] 最大最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2vfyofjjn.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ogshykfy.html

[Q30] 分组统计
来源：http://dali.zhijiandao.cn/Article/details/gt2gdaftsyu.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2xiopvutg.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2zcesbgtm.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2zpzjuyvk.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2zhqgrmld.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2tlpjvqos.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2pfwouszz.html

[Q33] 多列分组
来源：http://dali.zhijiandao.cn/Article/details/gt2pprfghxx.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhijiandao.cn/Article/details/gt2isrmuzar.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gt2zztkzurf.html

SELECT * FROM (
来源：http://dali.zhijiandao.cn/Article/details/gt2cpkgwofe.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhijiandao.cn/Article/details/gt2pwhjzskr.html

) t WHERE rn = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2trzrtvsv.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gt2rwjoncgq.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2udrcvvub.html

[Q36] 左连接
来源：http://dali.zhijiandao.cn/Article/details/gt2wljawvgm.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2zrgmtsrm.html

[Q37] 右连接
来源：http://dali.zhijiandao.cn/Article/details/gt2koksmrzn.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2cqgbpngc.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhijiandao.cn/Article/details/gt2nsngeory.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2uulljwek.html

[Q39] 自连接（查上下级）
来源：http://dali.zhijiandao.cn/Article/details/gt2rxjauzmg.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhijiandao.cn/Article/details/gt2fqhtjvoo.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2wpehonqv.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2qktafhlf.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2bwvuhkds.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ubxuugll.html


<!-- 参考信息 -->