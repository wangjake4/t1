代发 wailian999

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zycfv.cn/Article/details/gtcrvsbepu.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.hongshengwenyu.top/Article/details/gtgvvtijoe.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.jinghuilouyu.cn/Article/details/gteylpnkyj.html

Ruby: a.gcd(b)
来源：http://dali.jyoumei.cn/Article/details/gtgabuauyi.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.yangfankeji.com/Article/details/gtixutgfdo.html

[N06] 判断回文字符串
来源：http://dali.hysaishi.cn/Article/details/gtegvuvqtt.html

Py:   s == s[::-1]
来源：http://dali.jqgufenzy.top/Article/details/gteilwggxe.html

PHP:  $s === strrev($s);
来源：http://dali.havefunace.top/Article/details/gtrrujwfnd.html

JS:   s === [...s].reverse().join("")
来源：http://dali.haohaochexian.top/Article/details/gtmumcgech.html

TS:   s === [...s].reverse().join("")
来源：http://dali.cucudq.cn/Article/details/gtcntkawig.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.yonumen.top/Article/details/gtsygefqwp.html

Go:   // 双指针从两端比较
来源：http://dali.yongpay.top/Article/details/gtsewnlyde.html

Ruby: s == s.reverse
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaburzfvy.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.cucudq.cn/Article/details/gtmaxvqikk.html

[N07] 两数之和（返回下标）
来源：http://dali.yonumen.top/Article/details/gtmezpjqqe.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.feifeiyinyue.top/Article/details/gtfnpgpqzj.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.hammf.cn/Article/details/gtzbfsupmb.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.jinqigufen.top/Article/details/gtykrtoqoc.html

TS:   // 手写 Map<string, number>
来源：http://dali.cashguo.top/Article/details/gtcvbfeatr.html

Java: // 手写 HashMap
来源：http://dali.havefunace.top/Article/details/gtvqqvlbzf.html

Go:   // 手写 map[int]int
来源：http://dali.jinqigfzy.top/Article/details/gtpkyqyxlz.html

Ruby: // 手写 Hash
来源：http://dali.zdqjudy.top/Article/details/gtehbgeooj.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.chenzaomai.com/Article/details/gthetoniuj.html

[N08] 生成全排列
来源：http://dali.sxryk.cn/Article/details/gtsxxczuxh.html

Py:   itertools.permutations(arr)
来源：http://dali.zdqjudy.top/Article/details/gtosbwzinl.html

PHP:  // 手写递归交换
来源：http://dali.ehwqpu.com/Article/details/gtwhsaopuq.html

JS:   // 手写回溯递归
来源：http://dali.tian-w.cn/Article/details/gtlwrzozog.html

TS:   // 手写回溯递归
来源：http://dali.hnxiangtu.top/Article/details/gtxiguyvfx.html

Java: // 手写回溯递归
来源：http://dali.jiagoushi.top/Article/details/gttblfbszi.html

Go:   // 手写回溯递归
来源：http://dali.jqgfzy.top/Article/details/gtdyrgocob.html

Ruby: arr.permutation.to_a
来源：http://dali.yj202588.top/Article/details/gtjzwujpqb.html

C#:   // 手写回溯递归
来源：http://dali.jlsjyb.cn/Article/details/gtnhmraanc.html

[N09] 栈与队列
来源：http://dali.smart0.xyz/Article/details/gtgtnegzjl.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.haohaochexian.top/Article/details/gtnbttlytw.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.sxryk.cn/Article/details/gthdoprbhe.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.gaohongyu789.top/Article/details/gtsgjuzjtd.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.yj20258.top/Article/details/gtxvlxpkif.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.gogol.net.cn/Article/details/gtlwlzwvdj.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gtzhqhirbz.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.shanyushiyangkeji.top/Article/details/gtccdqkxus.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.yj202588.top/Article/details/gtrdoxchlx.html

[N10] 链表节点定义
来源：http://dali.wangdashe.top/Article/details/gtmlvstnto.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.guannengcc.top/Article/details/gtyexwaqik.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.yuanzhike.top/Article/details/gtrzvaizba.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.gzhubu.top/Article/details/gtzdrgbxmo.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.shzxlz.cn/Article/details/gtxrdjmfpg.html

Java: class Node { int v; Node next; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpvijfckm.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.shzxlz.cn/Article/details/gtegmlnrae.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.jianghu66.top/Article/details/gtyhrxnqvc.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.gotoacloud.top/Article/details/gtncsbnrke.html

[N11] 二叉树中序遍历
来源：http://dali.aibaodan.cn/Article/details/gthzxnzgrc.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.yuxming.cn/Article/details/gtyrowgkpr.html

PHP:  // 手写递归函数
来源：http://dali.gotoacloud.top/Article/details/gtgyzrifyy.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.guowangkeji.top/Article/details/gtcwwkwlmi.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yongpay.top/Article/details/gtjdhgdrgg.html

Java: // 手写递归
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrwgpncpn.html

Go:   // 手写递归
来源：http://dali.smart0.xyz/Article/details/gtknnldyaf.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.daria6918.cn/Article/details/gtenkyhcen.html

C#:   // 手写递归
来源：http://dali.cdnleiting.top/Article/details/gtbvspvkcv.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.andypj.xyz/Article/details/gtuwuarcah.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.iojbl.cn/Article/details/gtaqjfkphr.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.fzhhl.top/Article/details/gtettyiugm.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.ybcxt.top/Article/details/gtolqxlfur.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.haohaochexian.top/Article/details/gtrzzteqdk.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.ydzc1.top/Article/details/gtecvjijcw.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.yongpay.top/Article/details/gtvcdugxrm.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.bjfxy.top/Article/details/gtcifmhjtc.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcabatnim.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtgwoxkevr.html

O. 并发与异步
来源：http://dali.zhiwuduotai.top/Article/details/gteqerjade.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtqrfuqlia.html

[O01] 启动一个线程
来源：http://dali.316326.xyz/Article/details/gtjvzcbghh.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.aibaodan.cn/Article/details/gtvaiaanqg.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.jianghu66.top/Article/details/gttuejakfd.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.yj20258888.top/Article/details/gtiozbvkoy.html

TS:   // 同 JS
来源：http://dali.yonumen.top/Article/details/gtswldglks.html

Java: new Thread(() -> f()).start()
来源：http://dali.iojbl.cn/Article/details/gtvhwkbmuj.html

Go:   go f()
来源：http://dali.birdmap.top/Article/details/gtnuvfbmda.html

Ruby: Thread.new { f }
来源：http://dali.9152youxi.cn/Article/details/gtiwwztshy.html

C#:   Task.Run(() => F());
来源：http://dali.jiagoushi.top/Article/details/gtkxnwyfoy.html

[O02] 使用线程池
来源：http://dali.0kj1m.cn/Article/details/gtmvpyilwy.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.quarkkingdee.top/Article/details/gtddpnrmkm.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.jyoumei.cn/Article/details/gtkokgqnin.html

JS:   // worker_threads 线程池
来源：http://dali.sxryk.cn/Article/details/gtkwxvtxyw.html

TS:   // worker_threads 线程池
来源：http://dali.jinqigufen.top/Article/details/gtomtjkflj.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.xinyue.icu/Article/details/gtfmggvzkx.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.aibaodan.cn/Article/details/gticjhiyvs.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.gotoacloud.top/Article/details/gtlltpzeav.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.c1oappe.top/Article/details/gtrxcbqsjk.html

[O03] 加锁保护共享数据
来源：http://dali.cucudq.cn/Article/details/gtrrvhhnfu.html

Py:   with lock: shared += 1
来源：http://dali.ivvv.top/Article/details/gtkhbwtxzf.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.tianlin.xyz/Article/details/gtwcprcqlf.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.ybcxt.top/Article/details/gtexhvawtc.html

TS:   // 同 JS
来源：http://dali.hammf.cn/Article/details/gtnovytwvl.html

Java: synchronized (this) { shared++; }
来源：http://dali.hnxiangtu.top/Article/details/gtgfmvxhja.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.feifeiyinyue.top/Article/details/gtlpfedakg.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbkdqnwbf.html

C#:   lock (gate) { shared++; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxclgbmwm.html

[O04] 定义异步函数并等待
来源：http://dali.guowangkeji.top/Article/details/gtquzxavuf.html

Py:   async def f():⏎    await g()
来源：http://dali.jqgfzy.top/Article/details/gtaslodduu.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.vqdsnc.cn/Article/details/gtljwlpsek.html

JS:   async function f() { await g(); }
来源：http://dali.guannengcc.top/Article/details/gtofqapklg.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.chenjidiqi.icu/Article/details/gtkyfypcgg.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.cqqwz.cn/Article/details/gtmmrfypfb.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.sufxvd.cn/Article/details/gtytubfjlo.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.9152youxi.cn/Article/details/gtsoltattn.html

C#:   async Task F() { await G(); }
来源：http://dali.316326.xyz/Article/details/gtbclosyxe.html

[O05] 并发执行并等待全部完成
来源：http://dali.zycfv.cn/Article/details/gtyuymmgat.html

Py:   asyncio.gather(*tasks)
来源：http://dali.tian-w.cn/Article/details/gtcyslapxi.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.yuanzhike.top/Article/details/gtfjppxdqi.html

JS:   await Promise.all(tasks)
来源：http://dali.zdqjudy.top/Article/details/gtahomrkon.html

TS:   await Promise.all(tasks)
来源：http://dali.hysaishi.cn/Article/details/gtjfwcxioh.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.fzhhl.top/Article/details/gtpfpnmlsm.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zdqjudy.top/Article/details/gtiwfrqeom.html

Ruby: threads.map(&:join)
来源：http://dali.yj20258888.top/Article/details/gtyrzhonbw.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhiwuduotai.top/Article/details/gtnfjxnxgm.html

[O06] 使用进程池
来源：http://dali.nwbrower.top/Article/details/gtziokdyou.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.mhx1999.top/Article/details/gtibjfvypa.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.guowangkeji.top/Article/details/gtpgbmqltl.html

JS:   // child_process / cluster 模块
来源：http://dali.sweek.top/Article/details/gtrkvvlkww.html

TS:   // child_process / cluster 模块
来源：http://dali.daxiang520.top/Article/details/gtazicolwx.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.yuxming.cn/Article/details/gtpnvnbfxq.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.mhx1999.top/Article/details/gtjnsdfxwe.html

Ruby: // fork 块
来源：http://dali.shangyingyoupin.top/Article/details/gtxafndtda.html

C#:   Parallel.For
来源：http://dali.sxryk.cn/Article/details/gtxhveakpe.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtzlylhghf.html

P. 常用工具函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrhzdnnda.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtpqdvddnt.html

[P01] 生成 UUID
来源：http://dali.cucudq.cn/Article/details/gtzfbacvut.html

Py:   str(uuid.uuid4())
来源：http://dali.9152youxi.cn/Article/details/gtmfnypsgn.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.iojbl.cn/Article/details/gtqcisvtws.html

JS:   crypto.randomUUID()
来源：http://dali.gzhubu.top/Article/details/gtjusjrwiv.html

TS:   crypto.randomUUID()
来源：http://dali.guowangkeji.top/Article/details/gtowhnycni.html

Java: UUID.randomUUID().toString()
来源：http://dali.shangyingyoupin.top/Article/details/gtqgsrdwem.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zycfv.cn/Article/details/gtusarscby.html

Ruby: SecureRandom.uuid
来源：http://dali.zhixingplan.top/Article/details/gtqsbewgrr.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.gaohongyu789.top/Article/details/gtfprcfmkc.html

[P02] MD5 / SHA256 摘要
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmlvbmvmq.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.meibo888.top/Article/details/gtujbzoykn.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.smart0.xyz/Article/details/gtlpnousdj.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.kuanghao11.cn/Article/details/gtjotyqmlh.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpzpgzvhh.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.gaohongyu789.top/Article/details/gtxjddlzff.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.nwbrower.top/Article/details/gtfygteeqt.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.yuanzhike.top/Article/details/gtphruibsl.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.9152youxi.cn/Article/details/gtreeulzxb.html

[P03] 生成短随机字符串
来源：http://dali.nanxuanxn.top/Article/details/gtymnvpnqm.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.hongshengwenyu.top/Article/details/gtuagcaslj.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.jqgfzy.top/Article/details/gtzakjvtbz.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jlsjyb.cn/Article/details/gtaqcstbad.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zycfv.cn/Article/details/gtkagdjyij.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.guowangkeji.top/Article/details/gtayszrgjv.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.yvedp.cn/Article/details/gtevsqpnnk.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.ehwqpu.com/Article/details/gtcqkpgmxj.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.smart0.xyz/Article/details/gtoovrezou.html

[P04] 求长度
来源：http://dali.chenjidiqi.icu/Article/details/gtylmsvmmz.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.gzhubu.top/Article/details/gtgrilbjns.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.xuanzx.com/Article/details/gtehevxgzf.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.kuanghao11.cn/Article/details/gtekbplbpv.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.gaohongyu789.top/Article/details/gtlrtgzphq.html

Java: list.size();  map.size();  s.length()
来源：http://dali.hnqzz.top/Article/details/gtddsjazyp.html

Go:   len(arr);  len(m)
来源：http://dali.gzhubu.top/Article/details/gtgjqjbemj.html

Ruby: x.length;  x.size
来源：http://dali.wangdashe.top/Article/details/gtijdodafk.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.jinqigfzy.top/Article/details/gtpbcyfwqw.html

[P05] 判断两个对象内容是否相等
来源：http://dali.tianlin.xyz/Article/details/gtxqttslsu.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.yj20258.top/Article/details/gtchgrxhyd.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.pengpengdd.cyou/Article/details/gtktmdjaxc.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhixingplan.top/Article/details/gthfffguej.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.wangdashe.top/Article/details/gtddzcfhwm.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.bjfxy.top/Article/details/gtybeqrvic.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.c1oappe.top/Article/details/gtsnrfmmat.html

Ruby: a == b
来源：http://dali.sufxvd.cn/Article/details/gtrvomfjov.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.mhx1999.top/Article/details/gtrhqnrpxr.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.ivvv.top/Article/details/gtazrzqmrp.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.hfpthk.cn/Article/details/gthysczndh.html

PHP:  if (empty($x)) {}
来源：http://dali.c1oappe.top/Article/details/gtpsrjbixp.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.jqgfzy.top/Article/details/gtswoaywmm.html

TS:   if (x == null) {}
来源：http://dali.birdmap.top/Article/details/gtjleljzbh.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.ehwqpu.com/Article/details/gtkicsrdav.html

Go:   if x == nil {}
来源：http://dali.chenlongwang.top/Article/details/gtwuvewyrz.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.tian-w.cn/Article/details/gtafsuntgb.html

C#:   if (x is null) {}
来源：http://dali.dianchejie.cn/Article/details/gtyaueqdya.html

[P07] 防抖与节流
来源：http://dali.aibaodan.cn/Article/details/gtitrtburx.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.jyoumei.cn/Article/details/gtpnxvuofk.html

PHP:  // 手写时间戳比较
来源：http://dali.zhoulong.xyz/Article/details/gtvxdpetkf.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.sweek.top/Article/details/gteawlfzlf.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.xziqi.cn/Article/details/gtnxecfcfc.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.cucudq.cn/Article/details/gtujwdviiz.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.quarkkingdee.top/Article/details/gtivgxqmdr.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.wangshuangyany.cn/Article/details/gtakmstrfu.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfzjffudy.html

[P08] 处理浮点精度问题
来源：http://dali.pengpengdd.cyou/Article/details/gtlsmvdozm.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.birdmap.top/Article/details/gtddtmsveh.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.sysykeji.top/Article/details/gtwmdnejvo.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.yj202588.top/Article/details/gtxsvamauy.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.shuidangran.top/Article/details/gtlqrouzls.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.haohaochexian.top/Article/details/gtvkfgkhpn.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.chenlongwang.top/Article/details/gtezloicfk.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.wangshuangyany.cn/Article/details/gtscvhgnlq.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.yj20258.top/Article/details/gtmeppvsmh.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtnwsjiuvl.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.9152youxi.cn/Article/details/gtfmwrmgta.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtrqbkznmj.html

[Q01] 创建表
来源：http://dali.zhiwuduotai.top/Article/details/gtrtdiapnt.html

CREATE TABLE users (
来源：http://dali.andypj.xyz/Article/details/gtkudwzfhx.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jqgfzy.top/Article/details/gtjafiruar.html

name VARCHAR(50) NOT NULL,
来源：http://dali.yongpay.top/Article/details/gtwnxdesge.html

email VARCHAR(100) UNIQUE,
来源：http://dali.hnxiangtu.top/Article/details/gtljqymihs.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.shuidangran.top/Article/details/gtxeakjjai.html

);
来源：http://dali.yanxiufei.cn/Article/details/gtmmxrgkdg.html

[Q02] 创建带外键的表
来源：http://dali.xylfe.cn/Article/details/gtyrafipix.html

CREATE TABLE orders (
来源：http://dali.gaohongyu789.top/Article/details/gtcyiganez.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zycfv.cn/Article/details/gtbmdhlont.html

user_id INT NOT NULL,
来源：http://dali.hammf.cn/Article/details/gthrifckxa.html

amount DECIMAL(10, 2),
来源：http://dali.tian-w.cn/Article/details/gtdevnrcdy.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.xuetiantiany.cn/Article/details/gtojripuit.html

);
来源：http://dali.xylfe.cn/Article/details/gtgxpklvpd.html

[Q03] 增加列
来源：http://dali.shzxlz.cn/Article/details/gtolpjfcnn.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.sweek.top/Article/details/gtskbsyrke.html

[Q04] 修改列类型
来源：http://dali.yj202588.top/Article/details/gtcmdniffj.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.wangshuangyany.cn/Article/details/gtcudvbskx.html

[Q05] 重命名列
来源：http://dali.jqgufenzy.top/Article/details/gtfigvrxut.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.mhx1999.top/Article/details/gtiivxcfcv.html

[Q06] 删除列
来源：http://dali.meibo888.top/Article/details/gtxqtofqlu.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.jianghu66.top/Article/details/gtozsnmaab.html

[Q07] 删除表
来源：http://dali.hysaishi.cn/Article/details/gtikxluxew.html

DROP TABLE IF EXISTS orders;
来源：http://dali.sxryk.cn/Article/details/gtscjemrol.html

[Q08] 创建普通索引
来源：http://dali.jinqigfzy.top/Article/details/gtlnokiouo.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.smart0.xyz/Article/details/gtozoqxkll.html

[Q09] 创建唯一索引
来源：http://dali.tanke756.top/Article/details/gtnrqypska.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gtwsktquxs.html

[Q10] 插入单行
来源：http://dali.chenlongwang.top/Article/details/gtflddmeuv.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.shzxlz.cn/Article/details/gtzyavbbux.html

[Q11] 一次插入多行
来源：http://dali.tian-w.cn/Article/details/gtojbeacuy.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhaomingkeji.xyz/Article/details/gtupbrhgwz.html

[Q12] 插入后取自增 ID
来源：http://dali.shangyingyoupin.top/Article/details/gtfzxcjsod.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhongyouzk.top/Article/details/gtvxsyioyv.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.iojbl.cn/Article/details/gtmeaazoyu.html

[Q13] 忽略重复插入
来源：http://dali.jinghuilouyu.cn/Article/details/gtjanccotk.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.jinghuilouyu.cn/Article/details/gtnpegqmvk.html

[Q14] 存在则更新（upsert）
来源：http://dali.ivvv.top/Article/details/gthwjqdufo.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.ppjwa.cn/Article/details/gtvorrhbnf.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.sxryk.cn/Article/details/gtjahnjzgo.html

[Q15] 查询全部
来源：http://dali.0kj1m.cn/Article/details/gtvdxzlndv.html

SELECT * FROM users;
来源：http://dali.sxryk.cn/Article/details/gtnpclywec.html

[Q16] 查询指定列
来源：http://dali.yanxiufei.cn/Article/details/gtblisvrkt.html

SELECT id, name FROM users;
来源：http://dali.yvedp.cn/Article/details/gtrwcvtyfq.html

[Q17] 条件查询
来源：http://dali.shzxlz.cn/Article/details/gtpfaczxpx.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.daria6918.cn/Article/details/gtsrmmmdmc.html

[Q18] 模糊匹配
来源：http://dali.sweek.top/Article/details/gtdwffbytn.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.yongpay.top/Article/details/gtughrliwy.html

[Q19] 范围查询
来源：http://dali.c1oappe.top/Article/details/gtxbvevvxl.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.svipenyu.cn/Article/details/gtamkfkddk.html

[Q20] IN 列表
来源：http://dali.0kj1m.cn/Article/details/gtabjmqmlx.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.iojbl.cn/Article/details/gtavbnxaps.html

[Q21] 空值判断
来源：http://dali.quarkkingdee.top/Article/details/gtnkdjkvwu.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.mhx1999.top/Article/details/gtoonhhslh.html

[Q22] 排序
来源：http://dali.sufxvd.cn/Article/details/gtwzeggfpb.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.sysykeji.top/Article/details/gtjqugkizy.html

[Q23] 分页
来源：http://dali.havefunace.top/Article/details/gthnhmkzts.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.wangdashe.top/Article/details/gtikrziiox.html

[Q24] 去重
来源：http://dali.hammf.cn/Article/details/gttvgwjcih.html

SELECT DISTINCT city FROM users;
来源：http://dali.xuetiantiany.cn/Article/details/gtwqzltjry.html

[Q25] 只取前 N 条
来源：http://dali.xinyue.icu/Article/details/gtwssslkna.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.sufxvd.cn/Article/details/gtjopvrsfk.html

[Q26] 计数
来源：http://dali.meibo888.top/Article/details/gtcdshluty.html

SELECT COUNT(*) FROM users;
来源：http://dali.c1oappe.top/Article/details/gtgqmkwdfn.html

[Q27] 条件计数
来源：http://dali.birdmap.top/Article/details/gtmawrfafr.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.jlsjyb.cn/Article/details/gtdawfwpjj.html

[Q28] 求和与平均
来源：http://dali.xuetiantiany.cn/Article/details/gttzraqjpr.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.jqgufenzy.top/Article/details/gtqpihlwtr.html

[Q29] 最大最小值
来源：http://dali.gzhubu.top/Article/details/gthgescjbz.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.xylfe.cn/Article/details/gtpdqxgxio.html

[Q30] 分组统计
来源：http://dali.yonumen.top/Article/details/gtiqrdftzb.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.chenjidiqi.icu/Article/details/gtgigayypy.html

[Q31] 分组后过滤
来源：http://dali.ehwqpu.com/Article/details/gtifumgvmb.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.c1oappe.top/Article/details/gtrhommrbe.html

[Q32] 分组拼接字符串
来源：http://dali.zhiwuduotai.top/Article/details/gtnfevlafa.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.xuetiantiany.cn/Article/details/gtegvafpid.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.shanyushiyangkeji.top/Article/details/gthztpwwer.html

[Q33] 多列分组
来源：http://dali.ywan-chungtsiang.top/Article/details/gtitmjzntk.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.shzxlz.cn/Article/details/gtbazccmgc.html

[Q34] 每组取第一条
来源：http://dali.ppjwa.cn/Article/details/gtlkesaqoo.html

SELECT * FROM (
来源：http://dali.hywenlv.cn/Article/details/gtzarcvjvc.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.andypj.xyz/Article/details/gtedilzuyn.html

) t WHERE rn = 1;
来源：http://dali.jlsjyb.cn/Article/details/gtqqtfjdax.html

[Q35] 内连接
来源：http://dali.sxryk.cn/Article/details/gtrwstmxdu.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgjyqfhvb.html

[Q36] 左连接
来源：http://dali.tianlin.xyz/Article/details/gtkwlavnfo.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.0kj1m.cn/Article/details/gtcazmagod.html

[Q37] 右连接
来源：http://dali.gotoacloud.top/Article/details/gtnxorpfct.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.kuanghao11.cn/Article/details/gtlkekwgia.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.316326.xyz/Article/details/gtxhbflcff.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.smart0.xyz/Article/details/gttorjsuma.html

[Q39] 自连接（查上下级）
来源：http://dali.shuidangran.top/Article/details/gtyuzmcnlc.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhixingplan.top/Article/details/gtrfeicuet.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.hnxiangtu.top/Article/details/gtfzolfnsj.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.cdnleiting.top/Article/details/gtzaczswrx.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.chenjidiqi.icu/Article/details/gtmqmiumrx.html

[Q41] 多表连接
来源：http://dali.ybcxt.top/Article/details/gtiuzxbrci.html


<!-- 参考信息 -->