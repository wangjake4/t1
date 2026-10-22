代发 wailian999

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.dianchejie.cn/Article/details/gt2ahotxwen.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.dashuyun.cn/Article/details/gt2pjfrqyqy.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhoulong.xyz/Article/details/gt2akfkztep.html

[N04] 斐波那契数列
来源：http://dali.aizwys.cn/Article/details/gt2tysfxvij.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhiwuduotai.top/Article/details/gt2cfyujlnu.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.mhx1999.top/Article/details/gt2nttqhwku.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jqgfzy.top/Article/details/gt2iuexfqfn.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.c1oappe.top/Article/details/gt2vjhmilmg.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.yonumen.top/Article/details/gt2sengovap.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.cdnleiting.top/Article/details/gt2hseuvcdj.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.shuidangran.top/Article/details/gt2fnekeovk.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.xylfe.cn/Article/details/gt2rcwtvjeo.html

[N05] 最大公约数
来源：http://dali.yvedp.cn/Article/details/gt2vltmjwnb.html

Py:   math.gcd(a, b)
来源：http://dali.andypj.xyz/Article/details/gt2tftkwnsw.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.haohaochexian.top/Article/details/gt2srlfjxfu.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.birdmap.top/Article/details/gt2rbswvnnr.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yj20258.top/Article/details/gt2dfhrsajw.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zdqjudy.top/Article/details/gt2ioyscmgw.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.cashguo.top/Article/details/gt2dqwlvkij.html

Ruby: a.gcd(b)
来源：http://dali.jqgfzy.top/Article/details/gt2ciicfpck.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.hnxiangtu.top/Article/details/gt2pdamrvhz.html

[N06] 判断回文字符串
来源：http://dali.ppjwa.cn/Article/details/gt2rssppbuq.html

Py:   s == s[::-1]
来源：http://dali.snrcjt.cn/Article/details/gt2vcxqntlt.html

PHP:  $s === strrev($s);
来源：http://dali.yanxiufei.cn/Article/details/gt2eozsbhma.html

JS:   s === [...s].reverse().join("")
来源：http://dali.9152youxi.cn/Article/details/gt2pacxkynr.html

TS:   s === [...s].reverse().join("")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hplhzkkw.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.xinyue.icu/Article/details/gt2sueiwfdo.html

Go:   // 双指针从两端比较
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2doiaegnm.html

Ruby: s == s.reverse
来源：http://dali.snrcjt.cn/Article/details/gt2wxjnjrsl.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.yj20258.top/Article/details/gt2snyljydb.html

[N07] 两数之和（返回下标）
来源：http://dali.birdmap.top/Article/details/gt2xlxdzpla.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.aizwys.cn/Article/details/gt2ckvwtpwi.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.shangyingyoupin.top/Article/details/gt2fgyzzelw.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.snrcjt.cn/Article/details/gt2clhlaexw.html

TS:   // 手写 Map<string, number>
来源：http://dali.hammf.cn/Article/details/gt2hhlehdnr.html

Java: // 手写 HashMap
来源：http://dali.zhoulong.xyz/Article/details/gt2pnhdzqri.html

Go:   // 手写 map[int]int
来源：http://dali.gaohongyu789.top/Article/details/gt2oujulnhc.html

Ruby: // 手写 Hash
来源：http://dali.yangfankeji.com/Article/details/gt2rddczgga.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.hywenlv.cn/Article/details/gt2uoqupouz.html

[N08] 生成全排列
来源：http://dali.yvedp.cn/Article/details/gt2jzdtihob.html

Py:   itertools.permutations(arr)
来源：http://dali.jyoumei.cn/Article/details/gt2ftbjdrdi.html

PHP:  // 手写递归交换
来源：http://dali.0kj1m.cn/Article/details/gt2yzydkqgl.html

JS:   // 手写回溯递归
来源：http://dali.hfpthk.cn/Article/details/gt2ywozzljo.html

TS:   // 手写回溯递归
来源：http://dali.fzhhl.top/Article/details/gt2ideehzgb.html

Java: // 手写回溯递归
来源：http://dali.fengsongda.top/Article/details/gt2dcefngxk.html

Go:   // 手写回溯递归
来源：http://dali.tianlin.xyz/Article/details/gt2ulzzynwi.html

Ruby: arr.permutation.to_a
来源：http://dali.zhoulong.xyz/Article/details/gt2bszjlldo.html

C#:   // 手写回溯递归
来源：http://dali.guannengcc.top/Article/details/gt2xhowajdh.html

[N09] 栈与队列
来源：http://dali.gogol.net.cn/Article/details/gt2qqywxllx.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.hfpthk.cn/Article/details/gt2javgoysy.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.hongshengwenyu.top/Article/details/gt2bqspqvmh.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.feifeiyinyue.top/Article/details/gt2hawoxvtx.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.nanxuanxn.top/Article/details/gt2klksmfru.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.iojbl.cn/Article/details/gt2ovhziguy.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.shzxlz.cn/Article/details/gt2oydostqi.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.dashuyun.cn/Article/details/gt2podpvxgz.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.cucudq.cn/Article/details/gt2fqcycmhs.html

[N10] 链表节点定义
来源：http://dali.ydzc1.top/Article/details/gt2rsxjmlwz.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.snrcjt.cn/Article/details/gt2zxakjwbg.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.gaohongyu789.top/Article/details/gt2uejwqppo.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.smart0.xyz/Article/details/gt2gakdtafh.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.hnxiangtu.top/Article/details/gt2kjgsboxu.html

Java: class Node { int v; Node next; }
来源：http://dali.hnxiangtu.top/Article/details/gt2fybfqynb.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.yj202588.top/Article/details/gt2tpfkmvop.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.smart0.xyz/Article/details/gt2qieizsuf.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zycfv.cn/Article/details/gt2cpmtydjh.html

[N11] 二叉树中序遍历
来源：http://dali.guannengcc.top/Article/details/gt2elalgdjs.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.nwbrower.top/Article/details/gt2collshoa.html

PHP:  // 手写递归函数
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xbppznsi.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.xylfe.cn/Article/details/gt2ehhivxah.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.ybcxt.top/Article/details/gt2prponejz.html

Java: // 手写递归
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ausunkxd.html

Go:   // 手写递归
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rkummdbh.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.jinghuilouyu.cn/Article/details/gt2icmyhtfh.html

C#:   // 手写递归
来源：http://dali.wangdashe.top/Article/details/gt2dhvrhbva.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.sufxvd.cn/Article/details/gt2aqhajcxv.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhixingplan.top/Article/details/gt2snymxjps.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.nanxuanxn.top/Article/details/gt2ryppkakb.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yangfankeji.com/Article/details/gt2uiyktcvq.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jlsjyb.cn/Article/details/gt2zrttsxxn.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jianghu66.top/Article/details/gt2yoesqoxu.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.ehwqpu.com/Article/details/gt2crlszdaf.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2avjizfbl.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jiagoushi.top/Article/details/gt2rkmpsgpi.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2sfqnbwnt.html

O. 并发与异步
来源：http://dali.nanxuanxn.top/Article/details/gt2qxflkfag.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gt2tcydfyoa.html

[O01] 启动一个线程
来源：http://dali.havefunace.top/Article/details/gt2hbvqqobl.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.gaohongyu789.top/Article/details/gt2kimlzsrh.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.sufxvd.cn/Article/details/gt2nxftpdxl.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.aizwys.cn/Article/details/gt2sgputwbb.html

TS:   // 同 JS
来源：http://dali.cashguo.top/Article/details/gt2zwhpggxe.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhongyouzk.top/Article/details/gt2mpxxkwmv.html

Go:   go f()
来源：http://dali.vqdsnc.cn/Article/details/gt2cntvzsbp.html

Ruby: Thread.new { f }
来源：http://dali.aibaodan.cn/Article/details/gt2haexbnbx.html

C#:   Task.Run(() => F());
来源：http://dali.zycfv.cn/Article/details/gt2jeijkigi.html

[O02] 使用线程池
来源：http://dali.wangshuangyany.cn/Article/details/gt2oijbudie.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ordhzjtd.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.cqqwz.cn/Article/details/gt2qcllrhsy.html

JS:   // worker_threads 线程池
来源：http://dali.hnqzz.top/Article/details/gt2sskqodfp.html

TS:   // worker_threads 线程池
来源：http://dali.aibaodan.cn/Article/details/gt2bxlcjxdk.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.yj202588.top/Article/details/gt2fyarhqqy.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.daxiang520.top/Article/details/gt2ywmzmqsv.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.hongshengwenyu.top/Article/details/gt2cphjnnrn.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.yj202588.top/Article/details/gt2jxevcvds.html

[O03] 加锁保护共享数据
来源：http://dali.hysaishi.cn/Article/details/gt2xnwppczd.html

Py:   with lock: shared += 1
来源：http://dali.fzhhl.top/Article/details/gt2irmtddjq.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.hnqzz.top/Article/details/gt2gwhdposi.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zozakdik.html

TS:   // 同 JS
来源：http://dali.tianlin.xyz/Article/details/gt2taykrcpn.html

Java: synchronized (this) { shared++; }
来源：http://dali.haohaochexian.top/Article/details/gt2vapeuluq.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.fengsongda.top/Article/details/gt2vuwwaeya.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.tianlin.xyz/Article/details/gt2acouxgyq.html

C#:   lock (gate) { shared++; }
来源：http://dali.iojbl.cn/Article/details/gt2foiifzpg.html

[O04] 定义异步函数并等待
来源：http://dali.shangyingyoupin.top/Article/details/gt2cdroklob.html

Py:   async def f():⏎    await g()
来源：http://dali.hnxiangtu.top/Article/details/gt2ywtqxnpk.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.pengpengdd.cyou/Article/details/gt2fshhnmjz.html

JS:   async function f() { await g(); }
来源：http://dali.hongshengwenyu.top/Article/details/gt2goqkrlkk.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.ybcxt.top/Article/details/gt2nzcznzax.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.c1oappe.top/Article/details/gt2mpppaklh.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.yuanzhike.top/Article/details/gt2diruwhak.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhiwuduotai.top/Article/details/gt2yfckexql.html

C#:   async Task F() { await G(); }
来源：http://dali.wangdashe.top/Article/details/gt2omyddnyj.html

[O05] 并发执行并等待全部完成
来源：http://dali.9152youxi.cn/Article/details/gt2evhmtygz.html

Py:   asyncio.gather(*tasks)
来源：http://dali.guowangkeji.top/Article/details/gt2rymjixfo.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.guowangkeji.top/Article/details/gt2sgfewbap.html

JS:   await Promise.all(tasks)
来源：http://dali.0kj1m.cn/Article/details/gt2vijflies.html

TS:   await Promise.all(tasks)
来源：http://dali.chenlongwang.top/Article/details/gt2kqkvafue.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.haohaochexian.top/Article/details/gt2gctwmlmx.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.shuidangran.top/Article/details/gt2xbbfqyzj.html

Ruby: threads.map(&:join)
来源：http://dali.c1oappe.top/Article/details/gt2iikryppt.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.sufxvd.cn/Article/details/gt2xoyuuyrp.html

[O06] 使用进程池
来源：http://dali.fengsongda.top/Article/details/gt2mbxudfmc.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.yuanzhike.top/Article/details/gt2nhnphhnp.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.yanxiufei.cn/Article/details/gt2wpveigba.html

JS:   // child_process / cluster 模块
来源：http://dali.sweek.top/Article/details/gt2snnrqqsi.html

TS:   // child_process / cluster 模块
来源：http://dali.birdmap.top/Article/details/gt2bwdaoqye.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.jinqigufen.top/Article/details/gt2fktrrxnv.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.xylfe.cn/Article/details/gt2fodnczed.html

Ruby: // fork 块
来源：http://dali.gaohongyu789.top/Article/details/gt2ymesblvm.html

C#:   Parallel.For
来源：http://dali.daxiang520.top/Article/details/gt2zvflafgp.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gt2tvynudut.html

P. 常用工具函数
来源：http://dali.aizwys.cn/Article/details/gt2btxzesrw.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gt2qwwkxorv.html

[P01] 生成 UUID
来源：http://dali.xziqi.cn/Article/details/gt2vnjkvcmo.html

Py:   str(uuid.uuid4())
来源：http://dali.yuxming.cn/Article/details/gt2uqusfysa.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.bjfxy.top/Article/details/gt2wfcoadhf.html

JS:   crypto.randomUUID()
来源：http://dali.sufxvd.cn/Article/details/gt2dlhemljn.html

TS:   crypto.randomUUID()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gtiyzoay.html

Java: UUID.randomUUID().toString()
来源：http://dali.yuanzhike.top/Article/details/gt2ubglibxw.html

Go:   // 用 github.com/google/uuid
来源：http://dali.jinqigfzy.top/Article/details/gt2fiyglawb.html

Ruby: SecureRandom.uuid
来源：http://dali.zhoulong.xyz/Article/details/gt2rkzcxaam.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.yj20258888.top/Article/details/gt2yjkdmghg.html

[P02] MD5 / SHA256 摘要
来源：http://dali.yuanzhike.top/Article/details/gt2khxvtuqe.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.gzhubu.top/Article/details/gt2qyyybatu.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rwkbuhgd.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.jinqigfzy.top/Article/details/gt2xymtiyky.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.jiagoushi.top/Article/details/gt2aaqtlflp.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.sxryk.cn/Article/details/gt2mcfitqfv.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.pycfn.com/Article/details/gt2rhvahdnt.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.jlsjyb.cn/Article/details/gt2kygocmpw.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bzkvrjhr.html

[P03] 生成短随机字符串
来源：http://dali.daxiang520.top/Article/details/gt2rdrhzbln.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.yj20258888.top/Article/details/gt2iaynkqxe.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.vqdsnc.cn/Article/details/gt2nxvjqqcf.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yonumen.top/Article/details/gt2fxflhvlx.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.daxiang520.top/Article/details/gt2guwozppi.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.daria6918.cn/Article/details/gt2gytsllnz.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.aibaodan.cn/Article/details/gt2ifsvwixy.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wpnaslrm.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.daria6918.cn/Article/details/gt2xqhdrqhv.html

[P04] 求长度
来源：http://dali.pengpengdd.cyou/Article/details/gt2viyqfpof.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.gaohongyu789.top/Article/details/gt2qoeuqzmm.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.aibaodan.cn/Article/details/gt2uyziaqzq.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.fzhhl.top/Article/details/gt2tyzslyku.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.aizwys.cn/Article/details/gt2gwgdostr.html

Java: list.size();  map.size();  s.length()
来源：http://dali.haohaochexian.top/Article/details/gt2nssbrlqz.html

Go:   len(arr);  len(m)
来源：http://dali.cucudq.cn/Article/details/gt2eqekldba.html

Ruby: x.length;  x.size
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2agdstavn.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.jinqigfzy.top/Article/details/gt2jqngkwxx.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhoulong.xyz/Article/details/gt2lryhvutb.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.guannengcc.top/Article/details/gt2kweckyyx.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.yueranfly.top/Article/details/gt2zfyiggws.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.mhx1999.top/Article/details/gt2dbjmbkqh.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhoulong.xyz/Article/details/gt2nxiesild.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.guannengcc.top/Article/details/gt2nrvupxmz.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhixingplan.top/Article/details/gt2wsqwejgw.html

Ruby: a == b
来源：http://dali.jianghu66.top/Article/details/gt2czzfftmq.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.xylfe.cn/Article/details/gt2xmuiltve.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.yj20258888.top/Article/details/gt2odhezhnj.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.hfpthk.cn/Article/details/gt2zvhgdjdm.html

PHP:  if (empty($x)) {}
来源：http://dali.svipenyu.cn/Article/details/gt2poxmmcbi.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.snrcjt.cn/Article/details/gt2rykzceig.html

TS:   if (x == null) {}
来源：http://dali.jqgufenzy.top/Article/details/gt2aypzkdpc.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.0kj1m.cn/Article/details/gt2dpvpynsw.html

Go:   if x == nil {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2nlknisef.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhoulong.xyz/Article/details/gt2vovhewwp.html

C#:   if (x is null) {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2sapkdoex.html

[P07] 防抖与节流
来源：http://dali.iojbl.cn/Article/details/gt2iwluquhw.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.guowangkeji.top/Article/details/gt2wbtlnrqe.html

PHP:  // 手写时间戳比较
来源：http://dali.wangdashe.top/Article/details/gt2bzliclyr.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yj202588.top/Article/details/gt2xziihlzx.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.bjfxy.top/Article/details/gt2sjgubayp.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.smart0.xyz/Article/details/gt2czbedcxq.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.jinqigfzy.top/Article/details/gt2qegdyunm.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.yuanzhike.top/Article/details/gt2anbkhbhe.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.dianchejie.cn/Article/details/gt2xuhicxzp.html

[P08] 处理浮点精度问题
来源：http://dali.andypj.xyz/Article/details/gt2roeoualb.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.nanxuanxn.top/Article/details/gt2llrdnpjv.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.cashguo.top/Article/details/gt2ivpckewk.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhiwuduotai.top/Article/details/gt2hsqvhjdl.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.9152youxi.cn/Article/details/gt2yyktjokc.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jjfokrmh.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.hnqzz.top/Article/details/gt2idksdbdu.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.wangdashe.top/Article/details/gt2nbtiocjv.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.wangshuangyany.cn/Article/details/gt2zbrsetjs.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gt2zxbuifjt.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.dianchejie.cn/Article/details/gt2mxzldicv.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gt2eofbpfqx.html

[Q01] 创建表
来源：http://dali.316326.xyz/Article/details/gt2igqwszqk.html

CREATE TABLE users (
来源：http://dali.meibo888.top/Article/details/gt2wcphhbqj.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.shangyingyoupin.top/Article/details/gt2hmirdtuv.html

name VARCHAR(50) NOT NULL,
来源：http://dali.xuetiantiany.cn/Article/details/gt2gkgzggak.html

email VARCHAR(100) UNIQUE,
来源：http://dali.birdmap.top/Article/details/gt2baepldul.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.cashguo.top/Article/details/gt2ouwizcsg.html

);
来源：http://dali.hywenlv.cn/Article/details/gt2sncszfeu.html

[Q02] 创建带外键的表
来源：http://dali.dianchejie.cn/Article/details/gt2vrqipvux.html

CREATE TABLE orders (
来源：http://dali.hywenlv.cn/Article/details/gt2isecaftp.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.fengsongda.top/Article/details/gt2gtvzndon.html

user_id INT NOT NULL,
来源：http://dali.vqdsnc.cn/Article/details/gt2porrihvq.html

amount DECIMAL(10, 2),
来源：http://dali.vqdsnc.cn/Article/details/gt2ayvwuwsm.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zycfv.cn/Article/details/gt2eydwdujc.html

);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uaizycrm.html

[Q03] 增加列
来源：http://dali.ivvv.top/Article/details/gt2ldmforag.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.sufxvd.cn/Article/details/gt2ludxxywt.html

[Q04] 修改列类型
来源：http://dali.sufxvd.cn/Article/details/gt2yffilfkh.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.daria6918.cn/Article/details/gt2olsnvhnk.html

[Q05] 重命名列
来源：http://dali.xylfe.cn/Article/details/gt2sdwkxlgt.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.vqdsnc.cn/Article/details/gt2gckvkspx.html

[Q06] 删除列
来源：http://dali.hywenlv.cn/Article/details/gt2idgeobad.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.0kj1m.cn/Article/details/gt2yodsxknd.html

[Q07] 删除表
来源：http://dali.svipenyu.cn/Article/details/gt2kspsxpxv.html

DROP TABLE IF EXISTS orders;
来源：http://dali.hnqzz.top/Article/details/gt2idiwthfh.html

[Q08] 创建普通索引
来源：http://dali.wangdashe.top/Article/details/gt2telzmgoz.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.guowangkeji.top/Article/details/gt2lnzahjpb.html

[Q09] 创建唯一索引
来源：http://dali.9152youxi.cn/Article/details/gt2huusuyva.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.316326.xyz/Article/details/gt2eheglprh.html

[Q10] 插入单行
来源：http://dali.aizwys.cn/Article/details/gt2vaekokqa.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.nanxinkj.top/Article/details/gt2tyznzddd.html

[Q11] 一次插入多行
来源：http://dali.cucudq.cn/Article/details/gt2wsmndmmy.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.daria6918.cn/Article/details/gt2iogjdidv.html

[Q12] 插入后取自增 ID
来源：http://dali.daria6918.cn/Article/details/gt2iginqjxe.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.jiagoushi.top/Article/details/gt2yqlsgvwu.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.andypj.xyz/Article/details/gt2jnkgiogk.html

[Q13] 忽略重复插入
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rbdxxwws.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.tianlin.xyz/Article/details/gt2tcxbbgzx.html

[Q14] 存在则更新（upsert）
来源：http://dali.smart0.xyz/Article/details/gt2cfbmrvvs.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.mhx1999.top/Article/details/gt2pargcajh.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.sufxvd.cn/Article/details/gt2jxdvcdaz.html

[Q15] 查询全部
来源：http://dali.yj20258888.top/Article/details/gt2mfavvkcf.html

SELECT * FROM users;
来源：http://dali.zdqjudy.top/Article/details/gt2uobbymde.html

[Q16] 查询指定列
来源：http://dali.iojbl.cn/Article/details/gt2xekondfx.html

SELECT id, name FROM users;
来源：http://dali.yanxiufei.cn/Article/details/gt2ioizldci.html

[Q17] 条件查询
来源：http://dali.tanke756.top/Article/details/gt2fbvkhmxu.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2obqlzvim.html

[Q18] 模糊匹配
来源：http://dali.jyoumei.cn/Article/details/gt2dtabfcmz.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.kuanghao11.cn/Article/details/gt2xjiemjkl.html

[Q19] 范围查询
来源：http://dali.cdnleiting.top/Article/details/gt2asvrximc.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.cqqwz.cn/Article/details/gt2zspnhdzl.html

[Q20] IN 列表
来源：http://dali.zycfv.cn/Article/details/gt2lzbxhdvs.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.c1oappe.top/Article/details/gt2aiptzqhu.html

[Q21] 空值判断
来源：http://dali.yueranfly.top/Article/details/gt2kphjaptu.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.sxryk.cn/Article/details/gt2hzndsnuq.html

[Q22] 排序
来源：http://dali.smart0.xyz/Article/details/gt2rdajcjwp.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.yj202588.top/Article/details/gt2kzdlblhi.html

[Q23] 分页
来源：http://dali.pycfn.com/Article/details/gt2ineolbbc.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.yangfankeji.com/Article/details/gt2sfkhoijl.html

[Q24] 去重
来源：http://dali.zhixingplan.top/Article/details/gt2bwvikczh.html

SELECT DISTINCT city FROM users;
来源：http://dali.tanke756.top/Article/details/gt2oopjjicm.html

[Q25] 只取前 N 条
来源：http://dali.daxiang520.top/Article/details/gt2pguacqoo.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.jinqigufen.top/Article/details/gt2btfnbkls.html

[Q26] 计数
来源：http://dali.yj202588.top/Article/details/gt2uuxhbtkk.html

SELECT COUNT(*) FROM users;
来源：http://dali.haohaochexian.top/Article/details/gt2ucmlkxpc.html

[Q27] 条件计数
来源：http://dali.yj20258.top/Article/details/gt2uywyatnu.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.dashuyun.cn/Article/details/gt2yaxjrsoy.html

[Q28] 求和与平均
来源：http://dali.feifeiyinyue.top/Article/details/gt2pyuzdbep.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.daria6918.cn/Article/details/gt2rulhfexl.html

[Q29] 最大最小值
来源：http://dali.meibo888.top/Article/details/gt2khfxzner.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.andypj.xyz/Article/details/gt2daobpfhr.html

[Q30] 分组统计
来源：http://dali.cqqwz.cn/Article/details/gt2ujsaoriz.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.yuanzhike.top/Article/details/gt2kscnjqzj.html

[Q31] 分组后过滤
来源：http://dali.hfpthk.cn/Article/details/gt2ibijlrep.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.chenlongwang.top/Article/details/gt2fiqauaoe.html

[Q32] 分组拼接字符串
来源：http://dali.mhx1999.top/Article/details/gt2khtqpegd.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.hywenlv.cn/Article/details/gt2ofumqvce.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.yangfankeji.com/Article/details/gt2hhialzvu.html

[Q33] 多列分组
来源：http://dali.xziqi.cn/Article/details/gt2frxlbreq.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.yonumen.top/Article/details/gt2wwdoomdh.html

[Q34] 每组取第一条
来源：http://dali.hnqzz.top/Article/details/gt2avjvkhkk.html

SELECT * FROM (
来源：http://dali.wangdashe.top/Article/details/gt2pgnuziac.html


<!-- 参考信息 -->