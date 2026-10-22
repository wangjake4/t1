代发 wailian999

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.jqgfzy.top/Article/details/gtnrblwakt.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.vqdsnc.cn/Article/details/gtvkojroqg.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.hysaishi.cn/Article/details/gtolgcuqki.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtessyilcn.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.yanxiufei.cn/Article/details/gtcgzioege.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfmyjawpq.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.quarkkingdee.top/Article/details/gtarqmftpe.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.shangyingyoupin.top/Article/details/gtndhdmowb.html

[N05] 最大公约数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnkhjoehc.html

Py:   math.gcd(a, b)
来源：http://dali.sweek.top/Article/details/gtpchjgsqe.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.sweek.top/Article/details/gtzbmgnibg.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yangfankeji.com/Article/details/gtkaneqbtt.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hammf.cn/Article/details/gtyfirirfz.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.wangdashe.top/Article/details/gthtpntrhn.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.tian-w.cn/Article/details/gtgthpumru.html

Ruby: a.gcd(b)
来源：http://dali.316326.xyz/Article/details/gtpebcxyit.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.nwbrower.top/Article/details/gtwmvgzeap.html

[N06] 判断回文字符串
来源：http://dali.cheryme.top/Article/details/gtgunbilxa.html

Py:   s == s[::-1]
来源：http://dali.xuetiantiany.cn/Article/details/gtuzpeuvni.html

PHP:  $s === strrev($s);
来源：http://dali.xziqi.cn/Article/details/gtbrzysukh.html

JS:   s === [...s].reverse().join("")
来源：http://dali.yj202588.top/Article/details/gtmruvqbrk.html

TS:   s === [...s].reverse().join("")
来源：http://dali.yueranfly.top/Article/details/gtvtohwqto.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.fzhhl.top/Article/details/gtoutkxojf.html

Go:   // 双指针从两端比较
来源：http://dali.cqqwz.cn/Article/details/gtkgduhanv.html

Ruby: s == s.reverse
来源：http://dali.jiagoushi.top/Article/details/gtwjrxztab.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.jianghu66.top/Article/details/gtmdbznimq.html

[N07] 两数之和（返回下标）
来源：http://dali.fzhhl.top/Article/details/gtxlkthims.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.gotoacloud.top/Article/details/gtjfoollbk.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.hnxiangtu.top/Article/details/gtqozknfab.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.cdnleiting.top/Article/details/gtmracbuam.html

TS:   // 手写 Map<string, number>
来源：http://dali.pycfn.com/Article/details/gtirufoxkk.html

Java: // 手写 HashMap
来源：http://dali.yangfankeji.com/Article/details/gtmzmqyssz.html

Go:   // 手写 map[int]int
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvlvfklvx.html

Ruby: // 手写 Hash
来源：http://dali.hnxiangtu.top/Article/details/gtphoguxuz.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gtourxxwjc.html

[N08] 生成全排列
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpchfyhas.html

Py:   itertools.permutations(arr)
来源：http://dali.guannengcc.top/Article/details/gtezbftmvx.html

PHP:  // 手写递归交换
来源：http://dali.yuanzhike.top/Article/details/gtxptqaldg.html

JS:   // 手写回溯递归
来源：http://dali.hnxiangtu.top/Article/details/gtpvopgipn.html

TS:   // 手写回溯递归
来源：http://dali.daria6918.cn/Article/details/gtzmnzflzr.html

Java: // 手写回溯递归
来源：http://dali.havefunace.top/Article/details/gtyoevfsqu.html

Go:   // 手写回溯递归
来源：http://dali.cdnleiting.top/Article/details/gtmjmxnvnn.html

Ruby: arr.permutation.to_a
来源：http://dali.yueranfly.top/Article/details/gtctkpcnyj.html

C#:   // 手写回溯递归
来源：http://dali.quarkkingdee.top/Article/details/gtbtfbvlqv.html

[N09] 栈与队列
来源：http://dali.tianlin.xyz/Article/details/gtkaekmfhs.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.aizwys.cn/Article/details/gtgkzrxjbq.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.jinqigfzy.top/Article/details/gtmmlxeema.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.dianchejie.cn/Article/details/gtowqscopw.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.shzxlz.cn/Article/details/gtjpobhhez.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.shangyingyoupin.top/Article/details/gtxfvvksdc.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.andypj.xyz/Article/details/gtklffoisk.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.jiagoushi.top/Article/details/gtqcbmbnbr.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zdqjudy.top/Article/details/gtftsnheta.html

[N10] 链表节点定义
来源：http://dali.kuanghao11.cn/Article/details/gtopfkptox.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.wangdashe.top/Article/details/gtadhnkvpe.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.gogol.net.cn/Article/details/gtxfaagvac.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.shzxlz.cn/Article/details/gtwddybtcx.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.pycfn.com/Article/details/gtruevqcrm.html

Java: class Node { int v; Node next; }
来源：http://dali.daria6918.cn/Article/details/gtpunrmrvm.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.aibaodan.cn/Article/details/gtcrwexoun.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.meibo888.top/Article/details/gtewgvpcum.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.feifeiyinyue.top/Article/details/gtoivlvdgz.html

[N11] 二叉树中序遍历
来源：http://dali.kuanghao11.cn/Article/details/gtpizcjpoz.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.xziqi.cn/Article/details/gtrbxucque.html

PHP:  // 手写递归函数
来源：http://dali.svipenyu.cn/Article/details/gtujrapfzt.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jqgufenzy.top/Article/details/gtaxoncvtz.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.shzxlz.cn/Article/details/gtovbznums.html

Java: // 手写递归
来源：http://dali.quarkkingdee.top/Article/details/gtepeayrer.html

Go:   // 手写递归
来源：http://dali.vqdsnc.cn/Article/details/gtsrcuzeiz.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.hysaishi.cn/Article/details/gtkhajsxob.html

C#:   // 手写递归
来源：http://dali.vqdsnc.cn/Article/details/gttjbdvhxf.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.yj20258.top/Article/details/gtargpsxoe.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.ybcxt.top/Article/details/gtirxyiiuj.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.ivvv.top/Article/details/gtdyirusba.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yuanzhike.top/Article/details/gtebhpkgol.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.nwbrower.top/Article/details/gtoedmerjt.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zdqjudy.top/Article/details/gthqwrnxfj.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.daria6918.cn/Article/details/gtfuoanpzf.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.guowangkeji.top/Article/details/gtdjrxdctm.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.mhx1999.top/Article/details/gtwymhebsi.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtwdmwwfuu.html

O. 并发与异步
来源：http://dali.xylfe.cn/Article/details/gtsqggtqdd.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtibzxkdva.html

[O01] 启动一个线程
来源：http://dali.meibo888.top/Article/details/gtkoesvlhe.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhoulong.xyz/Article/details/gtpavvsaoq.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.cdnleiting.top/Article/details/gttzjyuipr.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.shuidangran.top/Article/details/gttgpjrsur.html

TS:   // 同 JS
来源：http://dali.tianlin.xyz/Article/details/gtizqtkgby.html

Java: new Thread(() -> f()).start()
来源：http://dali.ehwqpu.com/Article/details/gtcspuhzsr.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gtanisazps.html

Ruby: Thread.new { f }
来源：http://dali.tian-w.cn/Article/details/gtygadzyhj.html

C#:   Task.Run(() => F());
来源：http://dali.xziqi.cn/Article/details/gtihdqdygu.html

[O02] 使用线程池
来源：http://dali.ydzc1.top/Article/details/gthgqsrpjx.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.haohaochexian.top/Article/details/gtyggcoeer.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhiwuduotai.top/Article/details/gtrqnfwuea.html

JS:   // worker_threads 线程池
来源：http://dali.hnxiangtu.top/Article/details/gtzhghoffd.html

TS:   // worker_threads 线程池
来源：http://dali.xuetiantiany.cn/Article/details/gtjiyybzrr.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.aizwys.cn/Article/details/gtmpxsslhu.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhoulong.xyz/Article/details/gthdyccefd.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.gzhubu.top/Article/details/gtnwpdfuzt.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.hnxiangtu.top/Article/details/gtwyvsdjlc.html

[O03] 加锁保护共享数据
来源：http://dali.zhixingplan.top/Article/details/gtkbawholx.html

Py:   with lock: shared += 1
来源：http://dali.hfpthk.cn/Article/details/gtadtchgog.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.yvedp.cn/Article/details/gtrnsghiyy.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.feifeiyinyue.top/Article/details/gtbgsqqlre.html

TS:   // 同 JS
来源：http://dali.jinqigfzy.top/Article/details/gtlfuotvzn.html

Java: synchronized (this) { shared++; }
来源：http://dali.yonumen.top/Article/details/gtanynotbv.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.jinqigufen.top/Article/details/gtfrtldhth.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.yj20258888.top/Article/details/gtnqpnjpvv.html

C#:   lock (gate) { shared++; }
来源：http://dali.cqqwz.cn/Article/details/gtszbcdmlx.html

[O04] 定义异步函数并等待
来源：http://dali.nwbrower.top/Article/details/gtmbsiyodb.html

Py:   async def f():⏎    await g()
来源：http://dali.yanxiufei.cn/Article/details/gtuzbfhtsu.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxmxdwmqs.html

JS:   async function f() { await g(); }
来源：http://dali.cucudq.cn/Article/details/gtkieygier.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.dianchejie.cn/Article/details/gtbixypqou.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzmnobyxr.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.sxryk.cn/Article/details/gtutigfrif.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.yj20258888.top/Article/details/gtnqgjxhsb.html

C#:   async Task F() { await G(); }
来源：http://dali.mhx1999.top/Article/details/gtuwefdece.html

[O05] 并发执行并等待全部完成
来源：http://dali.chenlongwang.top/Article/details/gthrgvkosk.html

Py:   asyncio.gather(*tasks)
来源：http://dali.cucudq.cn/Article/details/gtmdvjfsjv.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.yangfankeji.com/Article/details/gtspzvnzzh.html

JS:   await Promise.all(tasks)
来源：http://dali.gotoacloud.top/Article/details/gtwkobsggo.html

TS:   await Promise.all(tasks)
来源：http://dali.hfpthk.cn/Article/details/gtgcqcxrvj.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.gzhubu.top/Article/details/gtrtpzjdmr.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.guowangkeji.top/Article/details/gtagyyuqwx.html

Ruby: threads.map(&:join)
来源：http://dali.shanyushiyangtech.top/Article/details/gtylkkjkcl.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.tian-w.cn/Article/details/gtgpouinxs.html

[O06] 使用进程池
来源：http://dali.jlsjyb.cn/Article/details/gtgqirhfqy.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.tianlin.xyz/Article/details/gtmbzqnliz.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.jqgufenzy.top/Article/details/gtdnmrwtce.html

JS:   // child_process / cluster 模块
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcdjboaiu.html

TS:   // child_process / cluster 模块
来源：http://dali.ydzc1.top/Article/details/gtsddexgdj.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.shangyingyoupin.top/Article/details/gtmrucflan.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.jinqigfzy.top/Article/details/gtammmgiql.html

Ruby: // fork 块
来源：http://dali.hywenlv.cn/Article/details/gtzhkrglqf.html

C#:   Parallel.For
来源：http://dali.shangyingyoupin.top/Article/details/gtxkoufgss.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtddvqjjjd.html

P. 常用工具函数
来源：http://dali.nanxuanxn.top/Article/details/gttyqmtfox.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtngnyaojf.html

[P01] 生成 UUID
来源：http://dali.jqgufenzy.top/Article/details/gtiwwtxmpj.html

Py:   str(uuid.uuid4())
来源：http://dali.kuanghao11.cn/Article/details/gtentjdfdp.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.mhx1999.top/Article/details/gtywegrntg.html

JS:   crypto.randomUUID()
来源：http://dali.chenlongwang.top/Article/details/gtfhkctaqc.html

TS:   crypto.randomUUID()
来源：http://dali.nwbrower.top/Article/details/gtqblsmtqh.html

Java: UUID.randomUUID().toString()
来源：http://dali.yj20258888.top/Article/details/gtaobsfjwu.html

Go:   // 用 github.com/google/uuid
来源：http://dali.shuidangran.top/Article/details/gtfuwnejxf.html

Ruby: SecureRandom.uuid
来源：http://dali.cqqwz.cn/Article/details/gtmzwrndez.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhixingplan.top/Article/details/gtnghpwkit.html

[P02] MD5 / SHA256 摘要
来源：http://dali.tian-w.cn/Article/details/gtvjhpaloz.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.hnqzz.top/Article/details/gtyahuovel.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.jqgufenzy.top/Article/details/gtqymrzvfz.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.yj202588.top/Article/details/gtlfbxkzra.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.ivvv.top/Article/details/gtmsulycnt.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.nanxuanxn.top/Article/details/gtohoutgfg.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.dianchejie.cn/Article/details/gtrfeeanfj.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.kuanghao11.cn/Article/details/gtowfuzmmf.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.nanxuanxn.top/Article/details/gtchkbxsgm.html

[P03] 生成短随机字符串
来源：http://dali.gotoacloud.top/Article/details/gtlzvmlskn.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.9152youxi.cn/Article/details/gtydizyyju.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.quarkkingdee.top/Article/details/gtlygyqoin.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.0kj1m.cn/Article/details/gtcltjtegy.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.tanke756.top/Article/details/gtqceyettk.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.ybcxt.top/Article/details/gthhckjrzl.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.vqdsnc.cn/Article/details/gtzzgbzidv.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.hysaishi.cn/Article/details/gtpteiqequ.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.jinqigufen.top/Article/details/gtqhnwbbho.html

[P04] 求长度
来源：http://dali.nwbrower.top/Article/details/gtgcaivwvs.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.tian-w.cn/Article/details/gtkceendim.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.cqqwz.cn/Article/details/gtbngnnxvc.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.chenjidiqi.icu/Article/details/gtlfhpyuew.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.feifeiyinyue.top/Article/details/gtyheerugm.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhongyouzk.top/Article/details/gtwbxsfyvh.html

Go:   len(arr);  len(m)
来源：http://dali.xuanzx.com/Article/details/gtfwtqcjqt.html

Ruby: x.length;  x.size
来源：http://dali.ydzc1.top/Article/details/gtzilahfno.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.snrcjt.cn/Article/details/gtdrknjjhp.html

[P05] 判断两个对象内容是否相等
来源：http://dali.bjfxy.top/Article/details/gtkqhkcwqc.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.jlsjyb.cn/Article/details/gtbwodbvwi.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.xinyue.icu/Article/details/gthxfjopck.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.jqgufenzy.top/Article/details/gtainvzkia.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.snrcjt.cn/Article/details/gtdceocqep.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.316326.xyz/Article/details/gthgmszdbj.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.yj202588.top/Article/details/gttgjdtsuk.html

Ruby: a == b
来源：http://dali.feifeiyinyue.top/Article/details/gtjdntgrvt.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.316326.xyz/Article/details/gthgbqheoj.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhengqikj.top/Article/details/gtzibweftk.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.shzxlz.cn/Article/details/gtcpsoagaw.html

PHP:  if (empty($x)) {}
来源：http://dali.zhiwuduotai.top/Article/details/gtaqskylwu.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.c1oappe.top/Article/details/gtwobxbdff.html

TS:   if (x == null) {}
来源：http://dali.cqqwz.cn/Article/details/gtglzqoxbk.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.sufxvd.cn/Article/details/gtoisxpfnb.html

Go:   if x == nil {}
来源：http://dali.xuanzx.com/Article/details/gtpxjesbkn.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.havefunace.top/Article/details/gtbgriqyqy.html

C#:   if (x is null) {}
来源：http://dali.jyoumei.cn/Article/details/gtnsdteyxd.html

[P07] 防抖与节流
来源：http://dali.shangyingyoupin.top/Article/details/gtivdooimi.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.wangdashe.top/Article/details/gtvxkixfus.html

PHP:  // 手写时间戳比较
来源：http://dali.havefunace.top/Article/details/gtdjzqhwnr.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.guowangkeji.top/Article/details/gtoinsszvh.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hammf.cn/Article/details/gtdglsnbfx.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.hywenlv.cn/Article/details/gttsxvmkjo.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.tian-w.cn/Article/details/gtxhfevaza.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.ivvv.top/Article/details/gtwwnyzwru.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.ydzc1.top/Article/details/gtxpmzrydu.html

[P08] 处理浮点精度问题
来源：http://dali.yonumen.top/Article/details/gtmptnyiln.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.andypj.xyz/Article/details/gtferlsjwp.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.gzhubu.top/Article/details/gtyxkcvqki.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.hywenlv.cn/Article/details/gtlbvnpjgf.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.yanxiufei.cn/Article/details/gterucbqhw.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvmteotap.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.nwbrower.top/Article/details/gtmakjarnf.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.yj202588.top/Article/details/gtujxzsqaw.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhixingplan.top/Article/details/gtamejnare.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtffnnbsoz.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzcisxmuz.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtgksijnxc.html

[Q01] 创建表
来源：http://dali.shuidangran.top/Article/details/gtnzuvhizw.html

CREATE TABLE users (
来源：http://dali.gzhubu.top/Article/details/gtadwfydwu.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.tianlin.xyz/Article/details/gtehoxcdor.html

name VARCHAR(50) NOT NULL,
来源：http://dali.shanyushiyangtech.top/Article/details/gtkafqqhgf.html

email VARCHAR(100) UNIQUE,
来源：http://dali.316326.xyz/Article/details/gtfnrdtadl.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.sufxvd.cn/Article/details/gtkvtktjwm.html

);
来源：http://dali.shanyushiyangtech.top/Article/details/gtcoskyqhi.html

[Q02] 创建带外键的表
来源：http://dali.tianlin.xyz/Article/details/gtdyzrggmg.html

CREATE TABLE orders (
来源：http://dali.c1oappe.top/Article/details/gtklqczeww.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zdqjudy.top/Article/details/gtjpqbtwkv.html

user_id INT NOT NULL,
来源：http://dali.ivvv.top/Article/details/gtvfrmiecb.html

amount DECIMAL(10, 2),
来源：http://dali.xuanzx.com/Article/details/gtqigzvlsl.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.hysaishi.cn/Article/details/gtobpygqew.html

);
来源：http://dali.havefunace.top/Article/details/gtxlivepbo.html

[Q03] 增加列
来源：http://dali.cheryme.top/Article/details/gtwavkngzt.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.cheryme.top/Article/details/gtoglodwbs.html

[Q04] 修改列类型
来源：http://dali.wangshuangyany.cn/Article/details/gtigklumxp.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.tanke756.top/Article/details/gtpbjcohuv.html

[Q05] 重命名列
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmpmdbrlj.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.sysykeji.top/Article/details/gtemwaosza.html

[Q06] 删除列
来源：http://dali.9152youxi.cn/Article/details/gtfsbhzwxa.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhoulong.xyz/Article/details/gtcukpeyup.html

[Q07] 删除表
来源：http://dali.mhx1999.top/Article/details/gthrofyjch.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zdqjudy.top/Article/details/gtsfafdtfq.html

[Q08] 创建普通索引
来源：http://dali.cashguo.top/Article/details/gthnhmniar.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.xylfe.cn/Article/details/gtqqjydops.html

[Q09] 创建唯一索引
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxjddvqjl.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.xziqi.cn/Article/details/gttyyazjss.html

[Q10] 插入单行
来源：http://dali.havefunace.top/Article/details/gtygfzgegf.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.jinqigfzy.top/Article/details/gtsrfrbnuo.html

[Q11] 一次插入多行
来源：http://dali.cashguo.top/Article/details/gtfemyvjjp.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.yangfankeji.com/Article/details/gtdmqkagok.html

[Q12] 插入后取自增 ID
来源：http://dali.jianghu66.top/Article/details/gtrntbbqbu.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.ivvv.top/Article/details/gtqobvazyn.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.yonumen.top/Article/details/gtzfeleowm.html

[Q13] 忽略重复插入
来源：http://dali.yuxming.cn/Article/details/gtlcuvrzfv.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.redwolf501.top/Article/details/gttnzwrpxb.html

[Q14] 存在则更新（upsert）
来源：http://dali.hysaishi.cn/Article/details/gtdkersyox.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.yj202588.top/Article/details/gtdcqwquou.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.jinghuilouyu.cn/Article/details/gtqxjihzyf.html

[Q15] 查询全部
来源：http://dali.fengsongda.top/Article/details/gtooxhgvzw.html

SELECT * FROM users;
来源：http://dali.vqdsnc.cn/Article/details/gtojbafrcu.html

[Q16] 查询指定列
来源：http://dali.dianchejie.cn/Article/details/gtwegrsabi.html

SELECT id, name FROM users;
来源：http://dali.tanke756.top/Article/details/gtcwxmbcdc.html

[Q17] 条件查询
来源：http://dali.havefunace.top/Article/details/gtawazsyow.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.dashuyun.cn/Article/details/gtsakkkacg.html

[Q18] 模糊匹配
来源：http://dali.fengsongda.top/Article/details/gtzovsgior.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.cdnleiting.top/Article/details/gthojrrfcz.html

[Q19] 范围查询
来源：http://dali.316326.xyz/Article/details/gteokkrpmt.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.jyoumei.cn/Article/details/gtxhvvhjez.html

[Q20] IN 列表
来源：http://dali.zdqjudy.top/Article/details/gtftdxhktj.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.jinyuanbaomall.cn/Article/details/gthlixdyaj.html

[Q21] 空值判断
来源：http://dali.nwbrower.top/Article/details/gtxtivpyeh.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.fengsongda.top/Article/details/gtxnroidxq.html

[Q22] 排序
来源：http://dali.jqgfzy.top/Article/details/gtytmixctc.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.yuanzhike.top/Article/details/gtiggpsqhy.html

[Q23] 分页
来源：http://dali.shangyingyoupin.top/Article/details/gtlhafdxxb.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.kuanghao11.cn/Article/details/gtylifvwgg.html

[Q24] 去重
来源：http://dali.gotoacloud.top/Article/details/gtylnbxalg.html

SELECT DISTINCT city FROM users;
来源：http://dali.xuetiantiany.cn/Article/details/gtvmltocft.html

[Q25] 只取前 N 条
来源：http://dali.chenlongwang.top/Article/details/gttefiuvwn.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhongyouzk.top/Article/details/gtekfqpdiv.html

[Q26] 计数
来源：http://dali.smart0.xyz/Article/details/gtfkaxsgzw.html

SELECT COUNT(*) FROM users;
来源：http://dali.xinyue.icu/Article/details/gtwptggrhd.html

[Q27] 条件计数
来源：http://dali.tianlin.xyz/Article/details/gtolycnwvb.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.cheryme.top/Article/details/gtsfnoskbs.html

[Q28] 求和与平均
来源：http://dali.jinghuilouyu.cn/Article/details/gtvtoohzzy.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.sweek.top/Article/details/gtcmjatsaf.html

[Q29] 最大最小值
来源：http://dali.ivvv.top/Article/details/gtdhzcqyvf.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.dashuyun.cn/Article/details/gtqgqesfhb.html

[Q30] 分组统计
来源：http://dali.cucudq.cn/Article/details/gtjsjgvije.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.daria6918.cn/Article/details/gtombclsxk.html

[Q31] 分组后过滤
来源：http://dali.jiagoushi.top/Article/details/gtzwlcjfaa.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.xinyue.icu/Article/details/gtftypcivc.html

[Q32] 分组拼接字符串
来源：http://dali.hysaishi.cn/Article/details/gttzthxowe.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.yvedp.cn/Article/details/gtxtvswicb.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.xuanzx.com/Article/details/gtqxpmjjbi.html

[Q33] 多列分组
来源：http://dali.yanxiufei.cn/Article/details/gtuxxgdzgf.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.andypj.xyz/Article/details/gtsjhjtjiy.html

[Q34] 每组取第一条
来源：http://dali.svipenyu.cn/Article/details/gtwxwzgqca.html

SELECT * FROM (
来源：http://dali.mhx1999.top/Article/details/gtiytolprf.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.yongpay.top/Article/details/gthwosbavk.html

) t WHERE rn = 1;
来源：http://dali.316326.xyz/Article/details/gtbvqqkgts.html

[Q35] 内连接
来源：http://dali.zhijiandao.cn/Article/details/gtivvbfsxy.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.jlsjyb.cn/Article/details/gtapathlyk.html


<!-- 参考信息 -->