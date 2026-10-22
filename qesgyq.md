代发 wailian999

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.dianchejie.cn/Article/details/gt2gqhflbbu.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.sxryk.cn/Article/details/gt2ikozqkeg.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.guowangkeji.top/Article/details/gt2qgclexed.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.xinyue.icu/Article/details/gt2wzlqogtz.html

[N05] 最大公约数
来源：http://dali.jinqigfzy.top/Article/details/gt2siexiukj.html

Py:   math.gcd(a, b)
来源：http://dali.jinqigfzy.top/Article/details/gt2ozryycoi.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.xuanzx.com/Article/details/gt2xboangwt.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2lmksgipu.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.chenzaomai.com/Article/details/gt2pmyxorec.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.hammf.cn/Article/details/gt2amysskvg.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.xuetiantiany.cn/Article/details/gt2nrymjfqg.html

Ruby: a.gcd(b)
来源：http://dali.nanxinkj.top/Article/details/gt2mveaiwqu.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhixingplan.top/Article/details/gt2vaclyvrv.html

[N06] 判断回文字符串
来源：http://dali.feifeiyinyue.top/Article/details/gt2oltancbq.html

Py:   s == s[::-1]
来源：http://dali.tanke756.top/Article/details/gt2nwhfknrk.html

PHP:  $s === strrev($s);
来源：http://dali.andypj.xyz/Article/details/gt2nieztlbb.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhixingplan.top/Article/details/gt2kdnvjrxc.html

TS:   s === [...s].reverse().join("")
来源：http://dali.nanxinkj.top/Article/details/gt2alvmyhek.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.aibaodan.cn/Article/details/gt2soflfmnf.html

Go:   // 双指针从两端比较
来源：http://dali.jyoumei.cn/Article/details/gt2qtalcxeh.html

Ruby: s == s.reverse
来源：http://dali.c1oappe.top/Article/details/gt2ekhgtpsu.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.dianchejie.cn/Article/details/gt2crikscai.html

[N07] 两数之和（返回下标）
来源：http://dali.kuanghao11.cn/Article/details/gt2pxkjxtxt.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.nanxinkj.top/Article/details/gt2imqgiwmh.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nwfoefgl.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.jqgufenzy.top/Article/details/gt2xerummpw.html

TS:   // 手写 Map<string, number>
来源：http://dali.9152youxi.cn/Article/details/gt2jvripufb.html

Java: // 手写 HashMap
来源：http://dali.andypj.xyz/Article/details/gt2xdriqoum.html

Go:   // 手写 map[int]int
来源：http://dali.yueranfly.top/Article/details/gt2kxvqrzag.html

Ruby: // 手写 Hash
来源：http://dali.hywenlv.cn/Article/details/gt2btuttlmm.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.hysaishi.cn/Article/details/gt2uuajuvfc.html

[N08] 生成全排列
来源：http://dali.hammf.cn/Article/details/gt2yuzpaymc.html

Py:   itertools.permutations(arr)
来源：http://dali.nanxuanxn.top/Article/details/gt2oeiwipct.html

PHP:  // 手写递归交换
来源：http://dali.xuetiantiany.cn/Article/details/gt2ytpqkmgi.html

JS:   // 手写回溯递归
来源：http://dali.hammf.cn/Article/details/gt2cganufar.html

TS:   // 手写回溯递归
来源：http://dali.tian-w.cn/Article/details/gt2fjrgshbh.html

Java: // 手写回溯递归
来源：http://dali.ehwqpu.com/Article/details/gt2tftcyyls.html

Go:   // 手写回溯递归
来源：http://dali.tianlin.xyz/Article/details/gt2sipntoft.html

Ruby: arr.permutation.to_a
来源：http://dali.yj202588.top/Article/details/gt2zinrcooo.html

C#:   // 手写回溯递归
来源：http://dali.jqgfzy.top/Article/details/gt2zxclyhox.html

[N09] 栈与队列
来源：http://dali.jqgfzy.top/Article/details/gt2fqwtwzwi.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.yangfankeji.com/Article/details/gt2hjxsqxhf.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zdlqmojy.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.yangfankeji.com/Article/details/gt2npzotlcl.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.hnqzz.top/Article/details/gt2yxiqmgpz.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.smart0.xyz/Article/details/gt2grfrqeku.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhengqikj.top/Article/details/gt2muvmojdj.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.hnqzz.top/Article/details/gt2skewscen.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dwsvmyge.html

[N10] 链表节点定义
来源：http://dali.yj20258.top/Article/details/gt2foiwhktm.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.fzhhl.top/Article/details/gt2jvwlrjfe.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.ybcxt.top/Article/details/gt2kowtqywy.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.bjfxy.top/Article/details/gt2gvkhbejc.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.birdmap.top/Article/details/gt2mrfocfya.html

Java: class Node { int v; Node next; }
来源：http://dali.daria6918.cn/Article/details/gt2ilmqqunh.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.ivvv.top/Article/details/gt2bgfthmoh.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.sufxvd.cn/Article/details/gt2bysvwjnd.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.cheryme.top/Article/details/gt2mklrtaqq.html

[N11] 二叉树中序遍历
来源：http://dali.gogol.net.cn/Article/details/gt2pyvqohft.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhixingplan.top/Article/details/gt2lljzvunv.html

PHP:  // 手写递归函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wlhoywzr.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.gaohongyu789.top/Article/details/gt2uwiqmlko.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.meibo888.top/Article/details/gt2vufikaqj.html

Java: // 手写递归
来源：http://dali.c1oappe.top/Article/details/gt2aupmfjfw.html

Go:   // 手写递归
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2miuifemp.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.yvedp.cn/Article/details/gt2zvcbnkes.html

C#:   // 手写递归
来源：http://dali.sysykeji.top/Article/details/gt2ntvsewba.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.cashguo.top/Article/details/gt2eqxabpec.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.cqqwz.cn/Article/details/gt2kpodcvsg.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.c1oappe.top/Article/details/gt2ybsvaixi.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.svipenyu.cn/Article/details/gt2sbkgieci.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.316326.xyz/Article/details/gt2qoetgild.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.wangshuangyany.cn/Article/details/gt2lxfkhsgc.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.9152youxi.cn/Article/details/gt2ffqyyhtv.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.havefunace.top/Article/details/gt2lxltrkfp.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2laikjoey.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gt2orpscvoh.html

O. 并发与异步
来源：http://dali.sufxvd.cn/Article/details/gt2lqocdvss.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gt2gdjccqev.html

[O01] 启动一个线程
来源：http://dali.yanxiufei.cn/Article/details/gt2dlbetihw.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.nanxinkj.top/Article/details/gt2ybhxygac.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.yvedp.cn/Article/details/gt2bsedqmke.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.feifeiyinyue.top/Article/details/gt2dvamybjq.html

TS:   // 同 JS
来源：http://dali.quarkkingdee.top/Article/details/gt2bvcszpwf.html

Java: new Thread(() -> f()).start()
来源：http://dali.tanke756.top/Article/details/gt2peuwokgh.html

Go:   go f()
来源：http://dali.yj202588.top/Article/details/gt2zqjdykmt.html

Ruby: Thread.new { f }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2apmyglcf.html

C#:   Task.Run(() => F());
来源：http://dali.guannengcc.top/Article/details/gt2mkhmvtgw.html

[O02] 使用线程池
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rsxdfssp.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhongyouzk.top/Article/details/gt2dclifoua.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.smart0.xyz/Article/details/gt2hdsckfdb.html

JS:   // worker_threads 线程池
来源：http://dali.jiagoushi.top/Article/details/gt2yybtafqa.html

TS:   // worker_threads 线程池
来源：http://dali.shuidangran.top/Article/details/gt2pfkjuzmn.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.jlsjyb.cn/Article/details/gt2evydqvbl.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.hnqzz.top/Article/details/gt2sfrtlgkq.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.sweek.top/Article/details/gt2kxdnlgop.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.wangdashe.top/Article/details/gt2sfdxmymw.html

[O03] 加锁保护共享数据
来源：http://dali.hnqzz.top/Article/details/gt2qhatcwgy.html

Py:   with lock: shared += 1
来源：http://dali.cucudq.cn/Article/details/gt2dhuvsdpe.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.yonumen.top/Article/details/gt2bslhssfk.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.guowangkeji.top/Article/details/gt2jdllfeyu.html

TS:   // 同 JS
来源：http://dali.vqdsnc.cn/Article/details/gt2rjooqjnf.html

Java: synchronized (this) { shared++; }
来源：http://dali.gogol.net.cn/Article/details/gt2gljrjzlf.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.nanxinkj.top/Article/details/gt2hbidgvac.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.chenlongwang.top/Article/details/gt2vkqggpxy.html

C#:   lock (gate) { shared++; }
来源：http://dali.chenlongwang.top/Article/details/gt2pjbkmgsg.html

[O04] 定义异步函数并等待
来源：http://dali.nanxinkj.top/Article/details/gt2rauwvbqi.html

Py:   async def f():⏎    await g()
来源：http://dali.yvedp.cn/Article/details/gt2hiiqxafs.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.sweek.top/Article/details/gt2nwucosbv.html

JS:   async function f() { await g(); }
来源：http://dali.bjfxy.top/Article/details/gt2odyozzqe.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.jianghu66.top/Article/details/gt2vkpepzmk.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.meibo888.top/Article/details/gt2sgbmlwlh.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.cashguo.top/Article/details/gt2gexzayki.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.ydzc1.top/Article/details/gt2ibgxvvnz.html

C#:   async Task F() { await G(); }
来源：http://dali.smart0.xyz/Article/details/gt2bbdguwnp.html

[O05] 并发执行并等待全部完成
来源：http://dali.ydzc1.top/Article/details/gt2simwdtkb.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhengqikj.top/Article/details/gt2ytfskwmt.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.bjfxy.top/Article/details/gt2xtcbrpow.html

JS:   await Promise.all(tasks)
来源：http://dali.sysykeji.top/Article/details/gt2ezeuvkru.html

TS:   await Promise.all(tasks)
来源：http://dali.tanke756.top/Article/details/gt2dujuhbfm.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.cdnleiting.top/Article/details/gt2itvuqiad.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.yvedp.cn/Article/details/gt2qwfsjrsd.html

Ruby: threads.map(&:join)
来源：http://dali.mhx1999.top/Article/details/gt2iuotzaoq.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.smart0.xyz/Article/details/gt2fevhuvey.html

[O06] 使用进程池
来源：http://dali.chenlongwang.top/Article/details/gt2mnkshirs.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.ybcxt.top/Article/details/gt2dmttxfak.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.ehwqpu.com/Article/details/gt2ufwqihvb.html

JS:   // child_process / cluster 模块
来源：http://dali.pycfn.com/Article/details/gt2qkdtwgds.html

TS:   // child_process / cluster 模块
来源：http://dali.iojbl.cn/Article/details/gt2wvcjzoap.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.daxiang520.top/Article/details/gt2vlppwewv.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.snrcjt.cn/Article/details/gt2qpwtoikc.html

Ruby: // fork 块
来源：http://dali.xuetiantiany.cn/Article/details/gt2muourqlb.html

C#:   Parallel.For
来源：http://dali.chenlongwang.top/Article/details/gt2uvyehtzj.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gt2kzfespwk.html

P. 常用工具函数
来源：http://dali.zhoulong.xyz/Article/details/gt2fcotjvoy.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gt2hnpgdsdq.html

[P01] 生成 UUID
来源：http://dali.jyoumei.cn/Article/details/gt2oggkwyqp.html

Py:   str(uuid.uuid4())
来源：http://dali.chenjidiqi.icu/Article/details/gt2offetuji.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.nwbrower.top/Article/details/gt2lliaapln.html

JS:   crypto.randomUUID()
来源：http://dali.ybcxt.top/Article/details/gt2paaqbphw.html

TS:   crypto.randomUUID()
来源：http://dali.daria6918.cn/Article/details/gt2bqbvyiug.html

Java: UUID.randomUUID().toString()
来源：http://dali.ybcxt.top/Article/details/gt2rszkcqwd.html

Go:   // 用 github.com/google/uuid
来源：http://dali.jlsjyb.cn/Article/details/gt2lcdfoaso.html

Ruby: SecureRandom.uuid
来源：http://dali.hongshengwenyu.top/Article/details/gt2xppsubic.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.cqqwz.cn/Article/details/gt2aobsdljr.html

[P02] MD5 / SHA256 摘要
来源：http://dali.gaohongyu789.top/Article/details/gt2lpieweih.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.pengpengdd.cyou/Article/details/gt2zyccpfip.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.yj20258.top/Article/details/gt2kvuznnkh.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.xylfe.cn/Article/details/gt2noomwyfj.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wuflpgne.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.sweek.top/Article/details/gt2mbizgdxq.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.redwolf501.top/Article/details/gt2eknfpack.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.aizwys.cn/Article/details/gt2bcgreluz.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.shanyushiyangtech.top/Article/details/gt2phbqvldm.html

[P03] 生成短随机字符串
来源：http://dali.sxryk.cn/Article/details/gt2hrdcwosx.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.jiagoushi.top/Article/details/gt2iavjwfej.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.hnqzz.top/Article/details/gt2bcabxwmh.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.hammf.cn/Article/details/gt2jgewoytx.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.sweek.top/Article/details/gt2unviwofn.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.daria6918.cn/Article/details/gt2ksttlgsd.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.aibaodan.cn/Article/details/gt2zeqgcqnd.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhiwuduotai.top/Article/details/gt2ddhhnixv.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.hnqzz.top/Article/details/gt2aiuxxvyj.html

[P04] 求长度
来源：http://dali.shuidangran.top/Article/details/gt2unykbnbl.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.daria6918.cn/Article/details/gt2ofkiwydg.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yj20258.top/Article/details/gt2eatcemjw.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhoulong.xyz/Article/details/gt2ernjdlsq.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.wangshuangyany.cn/Article/details/gt2hfrhgfsv.html

Java: list.size();  map.size();  s.length()
来源：http://dali.jyoumei.cn/Article/details/gt2yhogaovj.html

Go:   len(arr);  len(m)
来源：http://dali.ppjwa.cn/Article/details/gt2zqnlmqmp.html

Ruby: x.length;  x.size
来源：http://dali.fengsongda.top/Article/details/gt2qkpoofpv.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.shuidangran.top/Article/details/gt2bndxgawj.html

[P05] 判断两个对象内容是否相等
来源：http://dali.guowangkeji.top/Article/details/gt2ygogmlyt.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.shangyingyoupin.top/Article/details/gt2kmqacypp.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.cdnleiting.top/Article/details/gt2alohhnux.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2quphyuor.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.sweek.top/Article/details/gt2jfxrltll.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.quarkkingdee.top/Article/details/gt2xoioprud.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.bjfxy.top/Article/details/gt2tqjuansk.html

Ruby: a == b
来源：http://dali.xuanzx.com/Article/details/gt2kfqexaym.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.shanyushiyangtech.top/Article/details/gt2etaulnjt.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.nwbrower.top/Article/details/gt2hkjbgcpi.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.tanke756.top/Article/details/gt2nztqgwob.html

PHP:  if (empty($x)) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2eytvmlay.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.iojbl.cn/Article/details/gt2xlxeabgu.html

TS:   if (x == null) {}
来源：http://dali.gotoacloud.top/Article/details/gt2mhlopmvi.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.gaohongyu789.top/Article/details/gt2gohnhmyx.html

Go:   if x == nil {}
来源：http://dali.andypj.xyz/Article/details/gt2frbxyfaa.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.aibaodan.cn/Article/details/gt2fxtjbimo.html

C#:   if (x is null) {}
来源：http://dali.shuidangran.top/Article/details/gt2isnbtloz.html

[P07] 防抖与节流
来源：http://dali.pycfn.com/Article/details/gt2fmsavazr.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.havefunace.top/Article/details/gt2mxjwxpos.html

PHP:  // 手写时间戳比较
来源：http://dali.ydzc1.top/Article/details/gt2rvdjcnah.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.cheryme.top/Article/details/gt2xooqiriw.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yj20258888.top/Article/details/gt2cddleulc.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.redwolf501.top/Article/details/gt2rldtofqb.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.dashuyun.cn/Article/details/gt2cmjarvds.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.guowangkeji.top/Article/details/gt2gevynbzo.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.dashuyun.cn/Article/details/gt2tdtgnxwj.html

[P08] 处理浮点精度问题
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ikfdnhgc.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2xrbsvibp.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.pengpengdd.cyou/Article/details/gt2kyskqmut.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.daria6918.cn/Article/details/gt2dryhhvug.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.mhx1999.top/Article/details/gt2dslfyjxr.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.quarkkingdee.top/Article/details/gt2okhcymhz.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.pengpengdd.cyou/Article/details/gt2wkpuilrl.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2elzdxwel.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.chenzaomai.com/Article/details/gt2uclpsbyf.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2meojlngp.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.nanxuanxn.top/Article/details/gt2gdkufcsk.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gt2xvnkysym.html

[Q01] 创建表
来源：http://dali.hongshengwenyu.top/Article/details/gt2rrnncpsa.html

CREATE TABLE users (
来源：http://dali.shangyingyoupin.top/Article/details/gt2iithfsmj.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.hywenlv.cn/Article/details/gt2dfghfyzl.html

name VARCHAR(50) NOT NULL,
来源：http://dali.cucudq.cn/Article/details/gt2ryymzmxn.html

email VARCHAR(100) UNIQUE,
来源：http://dali.sweek.top/Article/details/gt2dypzorfg.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.hammf.cn/Article/details/gt2mbozobmu.html

);
来源：http://dali.shzxlz.cn/Article/details/gt2kornlico.html

[Q02] 创建带外键的表
来源：http://dali.yueranfly.top/Article/details/gt2cyphweyj.html

CREATE TABLE orders (
来源：http://dali.quarkkingdee.top/Article/details/gt2ztvxucts.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yvedp.cn/Article/details/gt2adeivnxv.html

user_id INT NOT NULL,
来源：http://dali.ehwqpu.com/Article/details/gt2boojvfel.html

amount DECIMAL(10, 2),
来源：http://dali.gotoacloud.top/Article/details/gt2pogmkaua.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.xinyue.icu/Article/details/gt2wvvnhwui.html

);
来源：http://dali.bjfxy.top/Article/details/gt2pbchvecd.html

[Q03] 增加列
来源：http://dali.andypj.xyz/Article/details/gt2vcylfmkk.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.feifeiyinyue.top/Article/details/gt2gntrdnbc.html

[Q04] 修改列类型
来源：http://dali.fengsongda.top/Article/details/gt2rbzbqtwu.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.guowangkeji.top/Article/details/gt2xbjoiycd.html

[Q05] 重命名列
来源：http://dali.xuetiantiany.cn/Article/details/gt2amhyymmw.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.cashguo.top/Article/details/gt2aonefcnf.html

[Q06] 删除列
来源：http://dali.jiagoushi.top/Article/details/gt2tmkvsilf.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.haohaochexian.top/Article/details/gt2nhpilril.html

[Q07] 删除表
来源：http://dali.vqdsnc.cn/Article/details/gt2wbafkcun.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhixingplan.top/Article/details/gt2sqwcadps.html

[Q08] 创建普通索引
来源：http://dali.vqdsnc.cn/Article/details/gt2rjlqsuiu.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.guannengcc.top/Article/details/gt2nbxmvrbh.html

[Q09] 创建唯一索引
来源：http://dali.cdnleiting.top/Article/details/gt2tbesbqqg.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.tianlin.xyz/Article/details/gt2fiogikcl.html

[Q10] 插入单行
来源：http://dali.yueranfly.top/Article/details/gt2ooyemlio.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.yuanzhike.top/Article/details/gt2elwnngrb.html

[Q11] 一次插入多行
来源：http://dali.yj20258888.top/Article/details/gt2fzszkoof.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.yuxming.cn/Article/details/gt2kwttwrcn.html

[Q12] 插入后取自增 ID
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lphfipyy.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.wangdashe.top/Article/details/gt2nswgxvpz.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.xuanzx.com/Article/details/gt2vlwvhzed.html

[Q13] 忽略重复插入
来源：http://dali.zhijiandao.cn/Article/details/gt2lkmkmggp.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.quarkkingdee.top/Article/details/gt2lsiedxqy.html

[Q14] 存在则更新（upsert）
来源：http://dali.hfpthk.cn/Article/details/gt2blxdvzxy.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.nanxuanxn.top/Article/details/gt2fcasgbnm.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.cucudq.cn/Article/details/gt2dfigdudb.html

[Q15] 查询全部
来源：http://dali.c1oappe.top/Article/details/gt2gzrnzslq.html

SELECT * FROM users;
来源：http://dali.svipenyu.cn/Article/details/gt2rurszxar.html

[Q16] 查询指定列
来源：http://dali.kuanghao11.cn/Article/details/gt2zmglqvvi.html

SELECT id, name FROM users;
来源：http://dali.sxryk.cn/Article/details/gt2qpofoeml.html

[Q17] 条件查询
来源：http://dali.fzhhl.top/Article/details/gt2yxivheph.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.bjfxy.top/Article/details/gt2qzmkeigk.html

[Q18] 模糊匹配
来源：http://dali.zhixingplan.top/Article/details/gt2flbvyskb.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.yj202588.top/Article/details/gt2kewditxl.html

[Q19] 范围查询
来源：http://dali.nanxuanxn.top/Article/details/gt2rncsevzi.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.dianchejie.cn/Article/details/gt2dkiyupgp.html

[Q20] IN 列表
来源：http://dali.yangfankeji.com/Article/details/gt2memdhzik.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2coxytpdf.html

[Q21] 空值判断
来源：http://dali.pengpengdd.cyou/Article/details/gt2btbsjevy.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.tian-w.cn/Article/details/gt2dihcfeey.html

[Q22] 排序
来源：http://dali.jqgfzy.top/Article/details/gt2fbsgfxxp.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.cucudq.cn/Article/details/gt2ecdaqkec.html

[Q23] 分页
来源：http://dali.shuidangran.top/Article/details/gt2jvjqincg.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.chenlongwang.top/Article/details/gt2hldrrcqw.html

[Q24] 去重
来源：http://dali.cdnleiting.top/Article/details/gt2ovcgfrex.html

SELECT DISTINCT city FROM users;
来源：http://dali.cdnleiting.top/Article/details/gt2uaeyjyes.html

[Q25] 只取前 N 条
来源：http://dali.yanxiufei.cn/Article/details/gt2ffplfwmo.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.daria6918.cn/Article/details/gt2gpqfvgxw.html

[Q26] 计数
来源：http://dali.chenjidiqi.icu/Article/details/gt2dkdflrfq.html

SELECT COUNT(*) FROM users;
来源：http://dali.aibaodan.cn/Article/details/gt2knrezcjr.html

[Q27] 条件计数
来源：http://dali.jlsjyb.cn/Article/details/gt2cysbdgae.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.316326.xyz/Article/details/gt2reeietfr.html

[Q28] 求和与平均
来源：http://dali.havefunace.top/Article/details/gt2uqiqfiyp.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.gaohongyu789.top/Article/details/gt2pavfhqfm.html

[Q29] 最大最小值
来源：http://dali.xuanzx.com/Article/details/gt2gljvuyqe.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.c1oappe.top/Article/details/gt2fepzttre.html

[Q30] 分组统计
来源：http://dali.cheryme.top/Article/details/gt2entqqfac.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.shuidangran.top/Article/details/gt2vjcidjgf.html

[Q31] 分组后过滤
来源：http://dali.jinqigfzy.top/Article/details/gt2ugaihtnf.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.xinyue.icu/Article/details/gt2mgvthssh.html

[Q32] 分组拼接字符串
来源：http://dali.hammf.cn/Article/details/gt2yquapyda.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.ivvv.top/Article/details/gt2sjhdpdza.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.shuidangran.top/Article/details/gt2trqjtamt.html

[Q33] 多列分组
来源：http://dali.kuanghao11.cn/Article/details/gt2rvjphkgr.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.guowangkeji.top/Article/details/gt2jbgyjess.html

[Q34] 每组取第一条
来源：http://dali.yanxiufei.cn/Article/details/gt2lffpirsz.html

SELECT * FROM (
来源：http://dali.jinqigufen.top/Article/details/gt2xckhbknv.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.xinyue.icu/Article/details/gt2qopzrbes.html

) t WHERE rn = 1;
来源：http://dali.ppjwa.cn/Article/details/gt2swrjrguv.html

[Q35] 内连接
来源：http://dali.ybcxt.top/Article/details/gt2dcdicwgt.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.nanxuanxn.top/Article/details/gt2gzfzqjnq.html

[Q36] 左连接
来源：http://dali.ydzc1.top/Article/details/gt2vuvlhmqa.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.haohaochexian.top/Article/details/gt2flpmyxyc.html

[Q37] 右连接
来源：http://dali.vqdsnc.cn/Article/details/gt2gagspebr.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.shuidangran.top/Article/details/gt2rekvjmit.html


<!-- 参考信息 -->