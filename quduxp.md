代发 wailian999

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.yuanzhike.top/Article/details/gt2uhdmopcs.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.shangyingyoupin.top/Article/details/gt2ydbczwsk.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.cdnleiting.top/Article/details/gt2pyqtuwsr.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gbwcxpsq.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.hnxiangtu.top/Article/details/gt2hmoixwwe.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.aizwys.cn/Article/details/gt2odtrmkbe.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.sysykeji.top/Article/details/gt2efddpiwa.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.cqqwz.cn/Article/details/gt2mjwwslxy.html

[N05] 最大公约数
来源：http://dali.fzhhl.top/Article/details/gt2esqrvulh.html

Py:   math.gcd(a, b)
来源：http://dali.guowangkeji.top/Article/details/gt2peipsopw.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.xinyue.icu/Article/details/gt2gpxlmjzc.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hysaishi.cn/Article/details/gt2mxuqnybk.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.9152youxi.cn/Article/details/gt2lqixulyz.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.yanxiufei.cn/Article/details/gt2jlahxzqa.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.gogol.net.cn/Article/details/gt2mrjiwqim.html

Ruby: a.gcd(b)
来源：http://dali.zhixingplan.top/Article/details/gt2wcrqcfcw.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.9152youxi.cn/Article/details/gt2zabipnuj.html

[N06] 判断回文字符串
来源：http://dali.cheryme.top/Article/details/gt2mqswbkcg.html

Py:   s == s[::-1]
来源：http://dali.hysaishi.cn/Article/details/gt2znaneqhp.html

PHP:  $s === strrev($s);
来源：http://dali.havefunace.top/Article/details/gt2ocenmrzc.html

JS:   s === [...s].reverse().join("")
来源：http://dali.haohaochexian.top/Article/details/gt2gssouejt.html

TS:   s === [...s].reverse().join("")
来源：http://dali.guowangkeji.top/Article/details/gt2txyitfig.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.sxryk.cn/Article/details/gt2ojdmewdx.html

Go:   // 双指针从两端比较
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zoflmnuq.html

Ruby: s == s.reverse
来源：http://dali.kuanghao11.cn/Article/details/gt2sanochcx.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.svipenyu.cn/Article/details/gt2gbdaetwx.html

[N07] 两数之和（返回下标）
来源：http://dali.zhiwuduotai.top/Article/details/gt2letujxog.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.cheryme.top/Article/details/gt2gvqtquqm.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.aizwys.cn/Article/details/gt2onbyotkr.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.hnqzz.top/Article/details/gt2jcchokfo.html

TS:   // 手写 Map<string, number>
来源：http://dali.tian-w.cn/Article/details/gt2kqpbisxu.html

Java: // 手写 HashMap
来源：http://dali.zhiwuduotai.top/Article/details/gt2qhtmxuyk.html

Go:   // 手写 map[int]int
来源：http://dali.xinyue.icu/Article/details/gt2hxulintz.html

Ruby: // 手写 Hash
来源：http://dali.jqgufenzy.top/Article/details/gt2clthkiyb.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.havefunace.top/Article/details/gt2mpulqmid.html

[N08] 生成全排列
来源：http://dali.quarkkingdee.top/Article/details/gt2lcfozait.html

Py:   itertools.permutations(arr)
来源：http://dali.havefunace.top/Article/details/gt2ivmbbhxk.html

PHP:  // 手写递归交换
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vzwdnpgq.html

JS:   // 手写回溯递归
来源：http://dali.yueranfly.top/Article/details/gt2rwnbikvd.html

TS:   // 手写回溯递归
来源：http://dali.hnqzz.top/Article/details/gt2xnabfxfg.html

Java: // 手写回溯递归
来源：http://dali.gogol.net.cn/Article/details/gt2revcpnig.html

Go:   // 手写回溯递归
来源：http://dali.yanxiufei.cn/Article/details/gt2vaharziz.html

Ruby: arr.permutation.to_a
来源：http://dali.svipenyu.cn/Article/details/gt2bdrlqfus.html

C#:   // 手写回溯递归
来源：http://dali.yvedp.cn/Article/details/gt2bxzgmfrl.html

[N09] 栈与队列
来源：http://dali.andypj.xyz/Article/details/gt2iyqcxirf.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.svipenyu.cn/Article/details/gt2bqdsrrjk.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.316326.xyz/Article/details/gt2xrfepllm.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2naihgwar.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.mhx1999.top/Article/details/gt2kymoxtlw.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cnaxklux.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.gotoacloud.top/Article/details/gt2lpwaicid.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.smart0.xyz/Article/details/gt2sqqqwopv.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhiwuduotai.top/Article/details/gt2fuwpkmpr.html

[N10] 链表节点定义
来源：http://dali.guowangkeji.top/Article/details/gt2kgsbryrs.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.sufxvd.cn/Article/details/gt2ovukshkt.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.wangdashe.top/Article/details/gt2jfovfaax.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.svipenyu.cn/Article/details/gt2jhttapik.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.yongpay.top/Article/details/gt2cglzqjdl.html

Java: class Node { int v; Node next; }
来源：http://dali.zycfv.cn/Article/details/gt2iqrwhvln.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.xziqi.cn/Article/details/gt2pdjggyll.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.xziqi.cn/Article/details/gt2yjycdseq.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.gzhubu.top/Article/details/gt2uumkxaeo.html

[N11] 二叉树中序遍历
来源：http://dali.hfpthk.cn/Article/details/gt2lgtmlulh.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.haohaochexian.top/Article/details/gt2tujzjmja.html

PHP:  // 手写递归函数
来源：http://dali.cqqwz.cn/Article/details/gt2aqipuajj.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.havefunace.top/Article/details/gt2befqbewz.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.birdmap.top/Article/details/gt2kklmknll.html

Java: // 手写递归
来源：http://dali.feifeiyinyue.top/Article/details/gt2nyhilsba.html

Go:   // 手写递归
来源：http://dali.yuxming.cn/Article/details/gt2ouispjtl.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.c1oappe.top/Article/details/gt2zstguwqj.html

C#:   // 手写递归
来源：http://dali.hysaishi.cn/Article/details/gt2iktermtq.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.ydzc1.top/Article/details/gt2hiitemnr.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.smart0.xyz/Article/details/gt2gmpxshjo.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.meibo888.top/Article/details/gt2vvupwaed.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jlsjyb.cn/Article/details/gt2agptakpp.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.xuanzx.com/Article/details/gt2cfsohtbn.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.meibo888.top/Article/details/gt2emrwcpgw.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhiwuduotai.top/Article/details/gt2csfqzaqi.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.shuidangran.top/Article/details/gt2pivfyjno.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.feifeiyinyue.top/Article/details/gt2bksiybpn.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gt2nqnrcyxc.html

O. 并发与异步
来源：http://dali.fzhhl.top/Article/details/gt2qtrdsywz.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gt2dakzkkgf.html

[O01] 启动一个线程
来源：http://dali.smart0.xyz/Article/details/gt2rmhsxebw.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.cheryme.top/Article/details/gt2hrbfjtai.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.cucudq.cn/Article/details/gt2silhgayd.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.fengsongda.top/Article/details/gt2mgqgdydu.html

TS:   // 同 JS
来源：http://dali.nanxuanxn.top/Article/details/gt2cosusoes.html

Java: new Thread(() -> f()).start()
来源：http://dali.ydzc1.top/Article/details/gt2qumvapwf.html

Go:   go f()
来源：http://dali.feifeiyinyue.top/Article/details/gt2eghagmit.html

Ruby: Thread.new { f }
来源：http://dali.xylfe.cn/Article/details/gt2mljkrtng.html

C#:   Task.Run(() => F());
来源：http://dali.guowangkeji.top/Article/details/gt2udcszbmb.html

[O02] 使用线程池
来源：http://dali.iojbl.cn/Article/details/gt2tbwukteg.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.birdmap.top/Article/details/gt2pesenxun.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.gzhubu.top/Article/details/gt2dhlzkydz.html

JS:   // worker_threads 线程池
来源：http://dali.zycfv.cn/Article/details/gt2vobwymfg.html

TS:   // worker_threads 线程池
来源：http://dali.cqqwz.cn/Article/details/gt2rwpijwvf.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.mhx1999.top/Article/details/gt2qirillup.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.jlsjyb.cn/Article/details/gt2hyzngjtt.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.xylfe.cn/Article/details/gt2ivkpfker.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.yuanzhike.top/Article/details/gt2yfpbjdkw.html

[O03] 加锁保护共享数据
来源：http://dali.chenjidiqi.icu/Article/details/gt2kqxfdtng.html

Py:   with lock: shared += 1
来源：http://dali.daria6918.cn/Article/details/gt2uijaabnc.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.yj20258.top/Article/details/gt2qjuofppg.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.ydzc1.top/Article/details/gt2jvauasru.html

TS:   // 同 JS
来源：http://dali.yueranfly.top/Article/details/gt2tmqqoqnt.html

Java: synchronized (this) { shared++; }
来源：http://dali.316326.xyz/Article/details/gt2hrmuzlxd.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.haohaochexian.top/Article/details/gt2yjapymnl.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.ppjwa.cn/Article/details/gt2wffwoyeq.html

C#:   lock (gate) { shared++; }
来源：http://dali.redwolf501.top/Article/details/gt2ntxxzesq.html

[O04] 定义异步函数并等待
来源：http://dali.dianchejie.cn/Article/details/gt2puynpwvz.html

Py:   async def f():⏎    await g()
来源：http://dali.shuidangran.top/Article/details/gt2spahairs.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.nanxuanxn.top/Article/details/gt2jchnqbrk.html

JS:   async function f() { await g(); }
来源：http://dali.yongpay.top/Article/details/gt2wmfxcuxx.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.chenlongwang.top/Article/details/gt2sonxbmtj.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhengqikj.top/Article/details/gt2lwngodtu.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.ydzc1.top/Article/details/gt2eiauhwjf.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.gzhubu.top/Article/details/gt2wiojctcf.html

C#:   async Task F() { await G(); }
来源：http://dali.bjfxy.top/Article/details/gt2qqrxuhdw.html

[O05] 并发执行并等待全部完成
来源：http://dali.c1oappe.top/Article/details/gt2qbebobiz.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2ajddmrsx.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.dianchejie.cn/Article/details/gt2dhjhlgfh.html

JS:   await Promise.all(tasks)
来源：http://dali.chenlongwang.top/Article/details/gt2vqctrlnd.html

TS:   await Promise.all(tasks)
来源：http://dali.pycfn.com/Article/details/gt2dnhujbas.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.xziqi.cn/Article/details/gt2xfphqdzw.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.hnqzz.top/Article/details/gt2tqqhnckf.html

Ruby: threads.map(&:join)
来源：http://dali.guannengcc.top/Article/details/gt2okdremms.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.birdmap.top/Article/details/gt2mcwngeij.html

[O06] 使用进程池
来源：http://dali.gaohongyu789.top/Article/details/gt2fxpizynl.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.guannengcc.top/Article/details/gt2smnqchou.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.nwbrower.top/Article/details/gt2rqjxybin.html

JS:   // child_process / cluster 模块
来源：http://dali.vqdsnc.cn/Article/details/gt2lxjyhwwz.html

TS:   // child_process / cluster 模块
来源：http://dali.wangshuangyany.cn/Article/details/gt2qkpqwgxg.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.hywenlv.cn/Article/details/gt2xvgomudc.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.pengpengdd.cyou/Article/details/gt2tvzfsqid.html

Ruby: // fork 块
来源：http://dali.hysaishi.cn/Article/details/gt2tygdomwo.html

C#:   Parallel.For
来源：http://dali.wangshuangyany.cn/Article/details/gt2abejhbnq.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gt2onbgsjgv.html

P. 常用工具函数
来源：http://dali.shzxlz.cn/Article/details/gt2cxagqgkq.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gt2zhslrbia.html

[P01] 生成 UUID
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2txadsnmg.html

Py:   str(uuid.uuid4())
来源：http://dali.xziqi.cn/Article/details/gt2vomxcqea.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tuiauiff.html

JS:   crypto.randomUUID()
来源：http://dali.jyoumei.cn/Article/details/gt2byrwsopg.html

TS:   crypto.randomUUID()
来源：http://dali.gotoacloud.top/Article/details/gt2dafxcred.html

Java: UUID.randomUUID().toString()
来源：http://dali.c1oappe.top/Article/details/gt2iyulhhfk.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhixingplan.top/Article/details/gt2copxvpub.html

Ruby: SecureRandom.uuid
来源：http://dali.yangfankeji.com/Article/details/gt2zwoubwsl.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.aibaodan.cn/Article/details/gt2futjuyud.html

[P02] MD5 / SHA256 摘要
来源：http://dali.jinqigfzy.top/Article/details/gt2ralheada.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.daxiang520.top/Article/details/gt2zmtdmrxf.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.hywenlv.cn/Article/details/gt2fyuyylji.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.kuanghao11.cn/Article/details/gt2tpmjekdw.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zycfv.cn/Article/details/gt2etprbyat.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.sweek.top/Article/details/gt2mbjgrzxc.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.meibo888.top/Article/details/gt2znltjgei.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.xuanzx.com/Article/details/gt2ssypduoh.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.xziqi.cn/Article/details/gt2uxoiivrt.html

[P03] 生成短随机字符串
来源：http://dali.chenzaomai.com/Article/details/gt2mjbpesjn.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.nanxuanxn.top/Article/details/gt2hcvpnmpc.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.cucudq.cn/Article/details/gt2wsqzscvj.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.redwolf501.top/Article/details/gt2biovyyrd.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhiwuduotai.top/Article/details/gt2rmlwbuug.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.yuanzhike.top/Article/details/gt2dmmdorsg.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zdqjudy.top/Article/details/gt2ufypyhjc.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.gogol.net.cn/Article/details/gt2thmvndxw.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.smart0.xyz/Article/details/gt2rxmbwhji.html

[P04] 求长度
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qvkrnmln.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhengqikj.top/Article/details/gt2lswstkfc.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.gotoacloud.top/Article/details/gt2xfnhpbpe.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yonumen.top/Article/details/gt2xvnciwss.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.quarkkingdee.top/Article/details/gt2vqupkzou.html

Java: list.size();  map.size();  s.length()
来源：http://dali.9152youxi.cn/Article/details/gt2lkuivdwv.html

Go:   len(arr);  len(m)
来源：http://dali.iojbl.cn/Article/details/gt2hdaipzmj.html

Ruby: x.length;  x.size
来源：http://dali.fzhhl.top/Article/details/gt2fezcwbvu.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.hysaishi.cn/Article/details/gt2rjjohrrg.html

[P05] 判断两个对象内容是否相等
来源：http://dali.yangfankeji.com/Article/details/gt2xxgpvzkx.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.kuanghao11.cn/Article/details/gt2twhjjwmk.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.gogol.net.cn/Article/details/gt2utmqehhw.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.yueranfly.top/Article/details/gt2xagsunly.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.xinyue.icu/Article/details/gt2umeonddg.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.nanxuanxn.top/Article/details/gt2sirwdubz.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.pengpengdd.cyou/Article/details/gt2ygqqqvml.html

Ruby: a == b
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qtrkxjij.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.nanxinkj.top/Article/details/gt2platmtvq.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.havefunace.top/Article/details/gt2daefyrxt.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.wangshuangyany.cn/Article/details/gt2wdyqbcab.html

PHP:  if (empty($x)) {}
来源：http://dali.0kj1m.cn/Article/details/gt2sjcxihjn.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.cucudq.cn/Article/details/gt2qmlrvxrw.html

TS:   if (x == null) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fbovqnjg.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2pbpklxnq.html

Go:   if x == nil {}
来源：http://dali.zycfv.cn/Article/details/gt2pvaebxmy.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.jiagoushi.top/Article/details/gt2utampiud.html

C#:   if (x is null) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bqvrcaku.html

[P07] 防抖与节流
来源：http://dali.zhongyouzk.top/Article/details/gt2caatoeib.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.tanke756.top/Article/details/gt2hnagjmdq.html

PHP:  // 手写时间戳比较
来源：http://dali.nanxuanxn.top/Article/details/gt2ivwktnti.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.gotoacloud.top/Article/details/gt2zajbogze.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.cqqwz.cn/Article/details/gt2dmlluwsd.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.wangshuangyany.cn/Article/details/gt2vtnermia.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.jinqigufen.top/Article/details/gt2uffojypr.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.feifeiyinyue.top/Article/details/gt2ooqbolzn.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.gotoacloud.top/Article/details/gt2ccvxvcdj.html

[P08] 处理浮点精度问题
来源：http://dali.zycfv.cn/Article/details/gt2wgkakbsc.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.tian-w.cn/Article/details/gt2shndivhc.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.gaohongyu789.top/Article/details/gt2fuifoakh.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.feifeiyinyue.top/Article/details/gt2xjjwxsxp.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.hongshengwenyu.top/Article/details/gt2wdpnqsom.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.dashuyun.cn/Article/details/gt2bujdsmga.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.chenzaomai.com/Article/details/gt2aqmmuhoi.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.mhx1999.top/Article/details/gt2cbrrlisa.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.cdnleiting.top/Article/details/gt2uyrquaze.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gt2spquwgqe.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.sxryk.cn/Article/details/gt2zulxwcoa.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gt2qaujlzht.html

[Q01] 创建表
来源：http://dali.hfpthk.cn/Article/details/gt2hcyucvhc.html

CREATE TABLE users (
来源：http://dali.meibo888.top/Article/details/gt2sujpngms.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.birdmap.top/Article/details/gt2wkwwwftm.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2grxzjrfl.html

email VARCHAR(100) UNIQUE,
来源：http://dali.nanxinkj.top/Article/details/gt2ehvgabyn.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.cashguo.top/Article/details/gt2bqnosnxe.html

);
来源：http://dali.0kj1m.cn/Article/details/gt2oelmwvmn.html

[Q02] 创建带外键的表
来源：http://dali.yvedp.cn/Article/details/gt2ivcyoutp.html

CREATE TABLE orders (
来源：http://dali.jqgfzy.top/Article/details/gt2dzgxcqcc.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jqgfzy.top/Article/details/gt2issyqisy.html

user_id INT NOT NULL,
来源：http://dali.jyoumei.cn/Article/details/gt2mjuknnzw.html

amount DECIMAL(10, 2),
来源：http://dali.snrcjt.cn/Article/details/gt2vewdrtzm.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.0kj1m.cn/Article/details/gt2ykllgpyn.html

);
来源：http://dali.zhengqikj.top/Article/details/gt2rwjjjhar.html

[Q03] 增加列
来源：http://dali.sufxvd.cn/Article/details/gt2hbzsiwre.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhongyouzk.top/Article/details/gt2ukmhexgc.html

[Q04] 修改列类型
来源：http://dali.bjfxy.top/Article/details/gt2ncfsoyhr.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.tianlin.xyz/Article/details/gt2hhiqifqy.html

[Q05] 重命名列
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gqmdncnw.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.mhx1999.top/Article/details/gt2soqoqodl.html

[Q06] 删除列
来源：http://dali.zhongyouzk.top/Article/details/gt2zqhvnrat.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.hongshengwenyu.top/Article/details/gt2fnramavj.html

[Q07] 删除表
来源：http://dali.yj20258.top/Article/details/gt2iqumvvba.html

DROP TABLE IF EXISTS orders;
来源：http://dali.hywenlv.cn/Article/details/gt2talnevsf.html

[Q08] 创建普通索引
来源：http://dali.sxryk.cn/Article/details/gt2cujdogfj.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.0kj1m.cn/Article/details/gt2hngxoqvj.html

[Q09] 创建唯一索引
来源：http://dali.birdmap.top/Article/details/gt2ddttpoog.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.shangyingyoupin.top/Article/details/gt2rpiaiwny.html

[Q10] 插入单行
来源：http://dali.c1oappe.top/Article/details/gt2pjikfrwu.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.ppjwa.cn/Article/details/gt2xdjldxxt.html

[Q11] 一次插入多行
来源：http://dali.yj202588.top/Article/details/gt2xulzhqpx.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.dianchejie.cn/Article/details/gt2fpijpajd.html

[Q12] 插入后取自增 ID
来源：http://dali.jqgfzy.top/Article/details/gt2ofyjlvnm.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.nanxuanxn.top/Article/details/gt2epploinb.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.xziqi.cn/Article/details/gt2zjahsfky.html

[Q13] 忽略重复插入
来源：http://dali.shzxlz.cn/Article/details/gt2qswlvbhd.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.ybcxt.top/Article/details/gt2rtofiumq.html

[Q14] 存在则更新（upsert）
来源：http://dali.yueranfly.top/Article/details/gt2dcyuttpg.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.gzhubu.top/Article/details/gt2mcpmqmom.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.yvedp.cn/Article/details/gt2arkipjxx.html

[Q15] 查询全部
来源：http://dali.tanke756.top/Article/details/gt2whexfybj.html

SELECT * FROM users;
来源：http://dali.tianlin.xyz/Article/details/gt2nbueiiph.html

[Q16] 查询指定列
来源：http://dali.sysykeji.top/Article/details/gt2xbciwfcs.html

SELECT id, name FROM users;
来源：http://dali.yongpay.top/Article/details/gt2drpmaubd.html

[Q17] 条件查询
来源：http://dali.ppjwa.cn/Article/details/gt2wiutfitq.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.hongshengwenyu.top/Article/details/gt2rdwfgmtn.html

[Q18] 模糊匹配
来源：http://dali.hongshengwenyu.top/Article/details/gt2fnhvxeei.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.aizwys.cn/Article/details/gt2aemeyntv.html

[Q19] 范围查询
来源：http://dali.ydzc1.top/Article/details/gt2jubwyrkf.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.svipenyu.cn/Article/details/gt2rfwoudfk.html

[Q20] IN 列表
来源：http://dali.pycfn.com/Article/details/gt2zbzrnrue.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zycfv.cn/Article/details/gt2dstvyksh.html

[Q21] 空值判断
来源：http://dali.xuetiantiany.cn/Article/details/gt2nzoqufii.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.hywenlv.cn/Article/details/gt2ehzaufts.html

[Q22] 排序
来源：http://dali.0kj1m.cn/Article/details/gt2uruczcug.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.quarkkingdee.top/Article/details/gt2nqffejwy.html

[Q23] 分页
来源：http://dali.zhiwuduotai.top/Article/details/gt2uphijerx.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.pycfn.com/Article/details/gt2yltdwssv.html

[Q24] 去重
来源：http://dali.xuanzx.com/Article/details/gt2zyxombsq.html

SELECT DISTINCT city FROM users;
来源：http://dali.yueranfly.top/Article/details/gt2xnvtyjgv.html

[Q25] 只取前 N 条
来源：http://dali.wangshuangyany.cn/Article/details/gt2kaxkgrbe.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.jyoumei.cn/Article/details/gt2cogrwrjo.html

[Q26] 计数
来源：http://dali.pycfn.com/Article/details/gt2ozvnxsmf.html

SELECT COUNT(*) FROM users;
来源：http://dali.zdqjudy.top/Article/details/gt2iitigzcq.html

[Q27] 条件计数
来源：http://dali.gogol.net.cn/Article/details/gt2umodrjcw.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yuzkdvhz.html

[Q28] 求和与平均
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fpsqptqy.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.cashguo.top/Article/details/gt2irdsctbs.html

[Q29] 最大最小值
来源：http://dali.wangshuangyany.cn/Article/details/gt2ypzxfnif.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.feifeiyinyue.top/Article/details/gt2dndzoepf.html

[Q30] 分组统计
来源：http://dali.snrcjt.cn/Article/details/gt2awehmfyh.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.hywenlv.cn/Article/details/gt2qqtgbjpt.html

[Q31] 分组后过滤
来源：http://dali.jqgfzy.top/Article/details/gt2zuhmsivy.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.pengpengdd.cyou/Article/details/gt2nmnldgmv.html

[Q32] 分组拼接字符串
来源：http://dali.chenzaomai.com/Article/details/gt2ujggeisd.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.jinqigufen.top/Article/details/gt2eivspqbb.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.andypj.xyz/Article/details/gt2dctgyyvf.html

[Q33] 多列分组
来源：http://dali.pycfn.com/Article/details/gt2epmmfnys.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.ivvv.top/Article/details/gt2huhrcdfj.html

[Q34] 每组取第一条
来源：http://dali.9152youxi.cn/Article/details/gt2cekhcnlh.html

SELECT * FROM (
来源：http://dali.gogol.net.cn/Article/details/gt2lxuotpsu.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.hnqzz.top/Article/details/gt2kczmofuo.html

) t WHERE rn = 1;
来源：http://dali.hnqzz.top/Article/details/gt2zkvvlenj.html

[Q35] 内连接
来源：http://dali.pycfn.com/Article/details/gt2jswxqdmb.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vbljqvet.html


<!-- 参考信息 -->