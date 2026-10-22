代发 wailian999

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.wangdashe.top/Article/details/gt2rcneaaec.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.cashguo.top/Article/details/gt2svpkwpaq.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.jqgufenzy.top/Article/details/gt2zbcfnjwv.html

[N04] 斐波那契数列
来源：http://dali.zhengqikj.top/Article/details/gt2giwvabuo.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.hongshengwenyu.top/Article/details/gt2qhhxufji.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.ppjwa.cn/Article/details/gt2dljkmaci.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.chenzaomai.com/Article/details/gt2xwzzpmss.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jfkdpqva.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.xinyue.icu/Article/details/gt2aftjejfb.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhongyouzk.top/Article/details/gt2fsgbkdml.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.kuanghao11.cn/Article/details/gt2pycihrri.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.yj20258888.top/Article/details/gt2hdbnmwjw.html

[N05] 最大公约数
来源：http://dali.xuetiantiany.cn/Article/details/gt2dflresgb.html

Py:   math.gcd(a, b)
来源：http://dali.ybcxt.top/Article/details/gt2odcdvhxh.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.quarkkingdee.top/Article/details/gt2umnqbqgh.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yueranfly.top/Article/details/gt2fvkqmloc.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yvedp.cn/Article/details/gt2rxglbmjf.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.sufxvd.cn/Article/details/gt2wuhmnqdl.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.cqqwz.cn/Article/details/gt2zuaveair.html

Ruby: a.gcd(b)
来源：http://dali.svipenyu.cn/Article/details/gt2kzalwyka.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.cashguo.top/Article/details/gt2yxtwmmgv.html

[N06] 判断回文字符串
来源：http://dali.yj20258.top/Article/details/gt2untrgnqm.html

Py:   s == s[::-1]
来源：http://dali.pycfn.com/Article/details/gt2fytcyduw.html

PHP:  $s === strrev($s);
来源：http://dali.yongpay.top/Article/details/gt2pgtjobed.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zdqjudy.top/Article/details/gt2eqobjftm.html

TS:   s === [...s].reverse().join("")
来源：http://dali.cheryme.top/Article/details/gt2drjcwnuv.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.ybcxt.top/Article/details/gt2kedwrwhd.html

Go:   // 双指针从两端比较
来源：http://dali.gotoacloud.top/Article/details/gt2ercofcth.html

Ruby: s == s.reverse
来源：http://dali.tianlin.xyz/Article/details/gt2ewyftpkt.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.hfpthk.cn/Article/details/gt2dltqmbcc.html

[N07] 两数之和（返回下标）
来源：http://dali.haohaochexian.top/Article/details/gt2iolydqto.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.dashuyun.cn/Article/details/gt2lchkavyi.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.cucudq.cn/Article/details/gt2efuqwbpc.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.shangyingyoupin.top/Article/details/gt2pvopoedm.html

TS:   // 手写 Map<string, number>
来源：http://dali.9152youxi.cn/Article/details/gt2oatedirp.html

Java: // 手写 HashMap
来源：http://dali.yanxiufei.cn/Article/details/gt2hblsddsk.html

Go:   // 手写 map[int]int
来源：http://dali.tanke756.top/Article/details/gt2yblecodm.html

Ruby: // 手写 Hash
来源：http://dali.yj202588.top/Article/details/gt2oaamrgey.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.daria6918.cn/Article/details/gt2zlwinsqp.html

[N08] 生成全排列
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2iycsmxez.html

Py:   itertools.permutations(arr)
来源：http://dali.xinyue.icu/Article/details/gt2ngtevjyf.html

PHP:  // 手写递归交换
来源：http://dali.dianchejie.cn/Article/details/gt2qjruquxt.html

JS:   // 手写回溯递归
来源：http://dali.jyoumei.cn/Article/details/gt2izoekbtu.html

TS:   // 手写回溯递归
来源：http://dali.birdmap.top/Article/details/gt2iytjwzjs.html

Java: // 手写回溯递归
来源：http://dali.dianchejie.cn/Article/details/gt2tjiedgxc.html

Go:   // 手写回溯递归
来源：http://dali.jqgfzy.top/Article/details/gt2vxzgnsuu.html

Ruby: arr.permutation.to_a
来源：http://dali.ppjwa.cn/Article/details/gt2onngwrum.html

C#:   // 手写回溯递归
来源：http://dali.zhixingplan.top/Article/details/gt2fzvjjtew.html

[N09] 栈与队列
来源：http://dali.gzhubu.top/Article/details/gt2rgefpnhj.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.ehwqpu.com/Article/details/gt2rojwhzyy.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.wangshuangyany.cn/Article/details/gt2oeiwqenp.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.chenlongwang.top/Article/details/gt2hurbfnke.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.hongshengwenyu.top/Article/details/gt2yvrsbfhm.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.sxryk.cn/Article/details/gt2jqaldvri.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.ehwqpu.com/Article/details/gt2brvoujab.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.xinyue.icu/Article/details/gt2qggbrded.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.yonumen.top/Article/details/gt2jpyrzsmb.html

[N10] 链表节点定义
来源：http://dali.gaohongyu789.top/Article/details/gt2cjsbtitx.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.kuanghao11.cn/Article/details/gt2leaozdpb.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhengqikj.top/Article/details/gt2txbfzaap.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.bjfxy.top/Article/details/gt2sgelgnfx.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xbwttuwr.html

Java: class Node { int v; Node next; }
来源：http://dali.cucudq.cn/Article/details/gt2khwlmyzv.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.dashuyun.cn/Article/details/gt2eahewxsu.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.shangyingyoupin.top/Article/details/gt2cblgtlif.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.jinqigfzy.top/Article/details/gt2oplygamd.html

[N11] 二叉树中序遍历
来源：http://dali.ppjwa.cn/Article/details/gt2ytkyadzb.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.ivvv.top/Article/details/gt2iulngztx.html

PHP:  // 手写递归函数
来源：http://dali.havefunace.top/Article/details/gt2emasfmvn.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.xinyue.icu/Article/details/gt2vejtwbdq.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.feifeiyinyue.top/Article/details/gt2ofkuzmdm.html

Java: // 手写递归
来源：http://dali.xuanzx.com/Article/details/gt2djeqocms.html

Go:   // 手写递归
来源：http://dali.jiagoushi.top/Article/details/gt2mfsxvcji.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.hnxiangtu.top/Article/details/gt2mlhtgwiu.html

C#:   // 手写递归
来源：http://dali.wangshuangyany.cn/Article/details/gt2egqxvduk.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.jyoumei.cn/Article/details/gt2mpwdtpwe.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.0kj1m.cn/Article/details/gt2drahajzl.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.cqqwz.cn/Article/details/gt2bcwysjuk.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.xziqi.cn/Article/details/gt2hkeotole.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2grhgsujv.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.bjfxy.top/Article/details/gt2volmsmuf.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.shzxlz.cn/Article/details/gt2kxrpcjvz.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.shuidangran.top/Article/details/gt2zkqxbgsf.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yanxiufei.cn/Article/details/gt2xbytwsam.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2smhtjkoo.html

O. 并发与异步
来源：http://dali.cucudq.cn/Article/details/gt2vzbznhnb.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gt2mglyvxmg.html

[O01] 启动一个线程
来源：http://dali.hnxiangtu.top/Article/details/gt2qvsmnaqa.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.tian-w.cn/Article/details/gt2qspxoaec.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.jiagoushi.top/Article/details/gt2eaavfhnx.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.cucudq.cn/Article/details/gt2nnydfmog.html

TS:   // 同 JS
来源：http://dali.yj20258.top/Article/details/gt2efisqifj.html

Java: new Thread(() -> f()).start()
来源：http://dali.hywenlv.cn/Article/details/gt2rszojxxb.html

Go:   go f()
来源：http://dali.hammf.cn/Article/details/gt2ainbzptz.html

Ruby: Thread.new { f }
来源：http://dali.fengsongda.top/Article/details/gt2krouttex.html

C#:   Task.Run(() => F());
来源：http://dali.aibaodan.cn/Article/details/gt2vsfyjtfw.html

[O02] 使用线程池
来源：http://dali.hongshengwenyu.top/Article/details/gt2aiqxzxtz.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.yangfankeji.com/Article/details/gt2xafgsrjk.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.yonumen.top/Article/details/gt2wosmcjee.html

JS:   // worker_threads 线程池
来源：http://dali.daria6918.cn/Article/details/gt2wfgvtzbu.html

TS:   // worker_threads 线程池
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cchkwkym.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.tian-w.cn/Article/details/gt2rtptmyec.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.jiagoushi.top/Article/details/gt2iomojttq.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.havefunace.top/Article/details/gt2sdxbhonl.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.wangshuangyany.cn/Article/details/gt2omqqoexf.html

[O03] 加锁保护共享数据
来源：http://dali.zhiwuduotai.top/Article/details/gt2lmykayjx.html

Py:   with lock: shared += 1
来源：http://dali.zhengqikj.top/Article/details/gt2ylpezwtx.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.sweek.top/Article/details/gt2iheqiewj.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.jianghu66.top/Article/details/gt2ytqfbyjs.html

TS:   // 同 JS
来源：http://dali.shangyingyoupin.top/Article/details/gt2ynjwuakb.html

Java: synchronized (this) { shared++; }
来源：http://dali.chenlongwang.top/Article/details/gt2gltdwbbk.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.sxryk.cn/Article/details/gt2clywnwxe.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.vqdsnc.cn/Article/details/gt2ylktvkgl.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2soyshndu.html

[O04] 定义异步函数并等待
来源：http://dali.yonumen.top/Article/details/gt2uwvhyqdw.html

Py:   async def f():⏎    await g()
来源：http://dali.nwbrower.top/Article/details/gt2tcpgzyox.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.cqqwz.cn/Article/details/gt2bivdyegz.html

JS:   async function f() { await g(); }
来源：http://dali.yuxming.cn/Article/details/gt2kmzvveyt.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.dashuyun.cn/Article/details/gt2wqxlzsdb.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.sxryk.cn/Article/details/gt2qzeoctxk.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.yvedp.cn/Article/details/gt2lcenquoy.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.cucudq.cn/Article/details/gt2thqwacbz.html

C#:   async Task F() { await G(); }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2crqcxoqw.html

[O05] 并发执行并等待全部完成
来源：http://dali.cdnleiting.top/Article/details/gt2jfacvvkt.html

Py:   asyncio.gather(*tasks)
来源：http://dali.gotoacloud.top/Article/details/gt2qczecmcf.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.shangyingyoupin.top/Article/details/gt2tvuhkwov.html

JS:   await Promise.all(tasks)
来源：http://dali.c1oappe.top/Article/details/gt2uextighe.html

TS:   await Promise.all(tasks)
来源：http://dali.cheryme.top/Article/details/gt2ritabbyi.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.xylfe.cn/Article/details/gt2zesxilza.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.tanke756.top/Article/details/gt2ylcoutxm.html

Ruby: threads.map(&:join)
来源：http://dali.gogol.net.cn/Article/details/gt2yqrhcvss.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.aizwys.cn/Article/details/gt2tudzjejx.html

[O06] 使用进程池
来源：http://dali.zdqjudy.top/Article/details/gt2bjbrnwfx.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.aizwys.cn/Article/details/gt2dortzygo.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.gotoacloud.top/Article/details/gt2kskykksw.html

JS:   // child_process / cluster 模块
来源：http://dali.hammf.cn/Article/details/gt2mtmfxghv.html

TS:   // child_process / cluster 模块
来源：http://dali.shangyingyoupin.top/Article/details/gt2ffkybsow.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.jinghuilouyu.cn/Article/details/gt2feojcbep.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.jianghu66.top/Article/details/gt2bfrxvzlh.html

Ruby: // fork 块
来源：http://dali.hywenlv.cn/Article/details/gt2czpjvcfw.html

C#:   Parallel.For
来源：http://dali.hammf.cn/Article/details/gt2iidrbnhr.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gt2zpozhvpm.html

P. 常用工具函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gcxcmzux.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2qaczgzsz.html

[P01] 生成 UUID
来源：http://dali.chenlongwang.top/Article/details/gt2teqmhmri.html

Py:   str(uuid.uuid4())
来源：http://dali.daria6918.cn/Article/details/gt2jgcbpmii.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jvfjdueb.html

JS:   crypto.randomUUID()
来源：http://dali.jqgufenzy.top/Article/details/gt2tmeerufp.html

TS:   crypto.randomUUID()
来源：http://dali.redwolf501.top/Article/details/gt2gywqbphq.html

Java: UUID.randomUUID().toString()
来源：http://dali.kuanghao11.cn/Article/details/gt2xqlndgzb.html

Go:   // 用 github.com/google/uuid
来源：http://dali.gzhubu.top/Article/details/gt2afahliaa.html

Ruby: SecureRandom.uuid
来源：http://dali.tianlin.xyz/Article/details/gt2stcjmxrw.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2aukcyewt.html

[P02] MD5 / SHA256 摘要
来源：http://dali.shangyingyoupin.top/Article/details/gt2xwcdgzdx.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.0kj1m.cn/Article/details/gt2rbjwfpqx.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.dianchejie.cn/Article/details/gt2nfdeaojq.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.xuanzx.com/Article/details/gt2tggvykdk.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.dashuyun.cn/Article/details/gt2pcxrqwrz.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.vqdsnc.cn/Article/details/gt2ceptqeyn.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.kuanghao11.cn/Article/details/gt2oropnatl.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.316326.xyz/Article/details/gt2ydbjdaer.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.yuxming.cn/Article/details/gt2lpbllssk.html

[P03] 生成短随机字符串
来源：http://dali.ppjwa.cn/Article/details/gt2ttwnijyh.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zdqjudy.top/Article/details/gt2ckcpjssj.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.pycfn.com/Article/details/gt2nwnmhzbi.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jianghu66.top/Article/details/gt2jbujnirs.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.daxiang520.top/Article/details/gt2vngvdokp.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.jyoumei.cn/Article/details/gt2nqbglidt.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zycfv.cn/Article/details/gt2crcbqewq.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.jqgfzy.top/Article/details/gt2yzjysbxe.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhixingplan.top/Article/details/gt2nwcvhsww.html

[P04] 求长度
来源：http://dali.xziqi.cn/Article/details/gt2fhwectgk.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.9152youxi.cn/Article/details/gt2rgxegasm.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.dashuyun.cn/Article/details/gt2grrdqvxi.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.birdmap.top/Article/details/gt2ypjsfrav.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.shangyingyoupin.top/Article/details/gt2qrmpbfno.html

Java: list.size();  map.size();  s.length()
来源：http://dali.pengpengdd.cyou/Article/details/gt2lhijxnib.html

Go:   len(arr);  len(m)
来源：http://dali.havefunace.top/Article/details/gt2vezqmeys.html

Ruby: x.length;  x.size
来源：http://dali.yj20258888.top/Article/details/gt2szpsxtpa.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.sweek.top/Article/details/gt2lotdtite.html

[P05] 判断两个对象内容是否相等
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bcvwogty.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.9152youxi.cn/Article/details/gt2hitzgqsz.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.pengpengdd.cyou/Article/details/gt2hwobrilc.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.yangfankeji.com/Article/details/gt2loacfwwf.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.tian-w.cn/Article/details/gt2adhyydlm.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.wangdashe.top/Article/details/gt2dcbmhzyf.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.jiagoushi.top/Article/details/gt2fygrkbwg.html

Ruby: a == b
来源：http://dali.tanke756.top/Article/details/gt2xdlszdrb.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.bjfxy.top/Article/details/gt2cpwsgbsh.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.hywenlv.cn/Article/details/gt2nfwjdxxm.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.chenlongwang.top/Article/details/gt2rsfnmdnw.html

PHP:  if (empty($x)) {}
来源：http://dali.hysaishi.cn/Article/details/gt2xtkxwxut.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.hywenlv.cn/Article/details/gt2hofftthg.html

TS:   if (x == null) {}
来源：http://dali.cqqwz.cn/Article/details/gt2vzlnaijn.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.chenzaomai.com/Article/details/gt2qprezdbt.html

Go:   if x == nil {}
来源：http://dali.sxryk.cn/Article/details/gt2fymrrszf.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.chenlongwang.top/Article/details/gt2ciontgkz.html

C#:   if (x is null) {}
来源：http://dali.dashuyun.cn/Article/details/gt2rnfbxoqu.html

[P07] 防抖与节流
来源：http://dali.c1oappe.top/Article/details/gt2qytxcetx.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.daxiang520.top/Article/details/gt2smnuokel.html

PHP:  // 手写时间戳比较
来源：http://dali.chenlongwang.top/Article/details/gt2psonjsbf.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jqgufenzy.top/Article/details/gt2tbsbnxws.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.wangdashe.top/Article/details/gt2nkvreafu.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.yanxiufei.cn/Article/details/gt2veuudsfu.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.jiagoushi.top/Article/details/gt2accrlthg.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.redwolf501.top/Article/details/gt2jzflkoon.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.aizwys.cn/Article/details/gt2zwgpwodk.html

[P08] 处理浮点精度问题
来源：http://dali.zhixingplan.top/Article/details/gt2uabjppys.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.nanxinkj.top/Article/details/gt2ebnlikci.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.xuanzx.com/Article/details/gt2ufcpmndp.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.gaohongyu789.top/Article/details/gt2icbfbbop.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhongyouzk.top/Article/details/gt2snbprupn.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.pycfn.com/Article/details/gt2bvnxttnx.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ywptxkul.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.cashguo.top/Article/details/gt2indkwufg.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhiwuduotai.top/Article/details/gt2kempsojm.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gt2mmrhbhxc.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.jianghu66.top/Article/details/gt2unwimddp.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gt2rjlmevof.html

[Q01] 创建表
来源：http://dali.hnxiangtu.top/Article/details/gt2zrxfxniv.html

CREATE TABLE users (
来源：http://dali.yj20258.top/Article/details/gt2bpaesphv.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.shzxlz.cn/Article/details/gt2knmjktmq.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2jbcxjxlc.html

email VARCHAR(100) UNIQUE,
来源：http://dali.gaohongyu789.top/Article/details/gt2prdwwvze.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.aizwys.cn/Article/details/gt2dbvhbllj.html

);
来源：http://dali.svipenyu.cn/Article/details/gt2hpqwptvu.html

[Q02] 创建带外键的表
来源：http://dali.dianchejie.cn/Article/details/gt2vlwnjfkd.html

CREATE TABLE orders (
来源：http://dali.shuidangran.top/Article/details/gt2dedqqomj.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.iojbl.cn/Article/details/gt2purkwezk.html

user_id INT NOT NULL,
来源：http://dali.mhx1999.top/Article/details/gt2sqjvzsvd.html

amount DECIMAL(10, 2),
来源：http://dali.fzhhl.top/Article/details/gt2kjplgkqh.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zdqjudy.top/Article/details/gt2lsbjfecn.html

);
来源：http://dali.birdmap.top/Article/details/gt2ihfmlbyf.html

[Q03] 增加列
来源：http://dali.zhiwuduotai.top/Article/details/gt2kmslnwvh.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.shangyingyoupin.top/Article/details/gt2cqmlogjx.html

[Q04] 修改列类型
来源：http://dali.tian-w.cn/Article/details/gt2mfjosurm.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.aizwys.cn/Article/details/gt2jzxqivht.html

[Q05] 重命名列
来源：http://dali.vqdsnc.cn/Article/details/gt2xcdydhrz.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.cucudq.cn/Article/details/gt2iyrldzhu.html

[Q06] 删除列
来源：http://dali.9152youxi.cn/Article/details/gt2fmcvjnpo.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zdqjudy.top/Article/details/gt2whnprkmr.html

[Q07] 删除表
来源：http://dali.yuanzhike.top/Article/details/gt2galcdjup.html

DROP TABLE IF EXISTS orders;
来源：http://dali.ydzc1.top/Article/details/gt2kzpjvvuf.html

[Q08] 创建普通索引
来源：http://dali.dashuyun.cn/Article/details/gt2tnghveqj.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.gaohongyu789.top/Article/details/gt2itqnczpr.html

[Q09] 创建唯一索引
来源：http://dali.sysykeji.top/Article/details/gt2ycxaikft.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.chenlongwang.top/Article/details/gt2cqpldxbi.html

[Q10] 插入单行
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2sbalpxzi.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.hammf.cn/Article/details/gt2zwzdwkqe.html

[Q11] 一次插入多行
来源：http://dali.gzhubu.top/Article/details/gt2ihkpekjp.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2msycmmti.html

[Q12] 插入后取自增 ID
来源：http://dali.shuidangran.top/Article/details/gt2buheovqz.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.shzxlz.cn/Article/details/gt2nbwooyvg.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.tianlin.xyz/Article/details/gt2ctziklpe.html

[Q13] 忽略重复插入
来源：http://dali.sysykeji.top/Article/details/gt2taimuyoy.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.jianghu66.top/Article/details/gt2xkqbjuok.html

[Q14] 存在则更新（upsert）
来源：http://dali.tanke756.top/Article/details/gt2ixrqiviu.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.gaohongyu789.top/Article/details/gt2fpelbzjk.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2sthkucaa.html

[Q15] 查询全部
来源：http://dali.yangfankeji.com/Article/details/gt2gwgllxkq.html

SELECT * FROM users;
来源：http://dali.pengpengdd.cyou/Article/details/gt2tdvqzvox.html

[Q16] 查询指定列
来源：http://dali.yonumen.top/Article/details/gt2qrctqtye.html

SELECT id, name FROM users;
来源：http://dali.dianchejie.cn/Article/details/gt2hlydykao.html

[Q17] 条件查询
来源：http://dali.ivvv.top/Article/details/gt2jtxafvxh.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.dashuyun.cn/Article/details/gt2ibiyynjt.html

[Q18] 模糊匹配
来源：http://dali.wangdashe.top/Article/details/gt2stbscahb.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.sxryk.cn/Article/details/gt2mksrvglf.html

[Q19] 范围查询
来源：http://dali.yuxming.cn/Article/details/gt2bxprvhrb.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.pengpengdd.cyou/Article/details/gt2tfxluere.html

[Q20] IN 列表
来源：http://dali.gaohongyu789.top/Article/details/gt2szjtmaoq.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.nanxuanxn.top/Article/details/gt2shihtsqm.html

[Q21] 空值判断
来源：http://dali.yvedp.cn/Article/details/gt2tnlbgowt.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.svipenyu.cn/Article/details/gt2mhaycmef.html

[Q22] 排序
来源：http://dali.birdmap.top/Article/details/gt2fwdvzjdu.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.ivvv.top/Article/details/gt2owhdnmdw.html

[Q23] 分页
来源：http://dali.hywenlv.cn/Article/details/gt2zeanuele.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.jqgfzy.top/Article/details/gt2mfmqdhvm.html

[Q24] 去重
来源：http://dali.haohaochexian.top/Article/details/gt2fjmknctn.html

SELECT DISTINCT city FROM users;
来源：http://dali.yongpay.top/Article/details/gt2svphilxo.html

[Q25] 只取前 N 条
来源：http://dali.jqgufenzy.top/Article/details/gt2ecrbubqp.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.gogol.net.cn/Article/details/gt2zvxfhjlo.html

[Q26] 计数
来源：http://dali.ehwqpu.com/Article/details/gt2zaqbgpyx.html

SELECT COUNT(*) FROM users;
来源：http://dali.c1oappe.top/Article/details/gt2aecttgro.html

[Q27] 条件计数
来源：http://dali.cheryme.top/Article/details/gt2uqiwalfa.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.hnxiangtu.top/Article/details/gt2fpwyjvyz.html

[Q28] 求和与平均
来源：http://dali.daria6918.cn/Article/details/gt2pgokbrhb.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ecamduju.html

[Q29] 最大最小值
来源：http://dali.fzhhl.top/Article/details/gt2gffrtaqm.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.shzxlz.cn/Article/details/gt2rniplbdi.html

[Q30] 分组统计
来源：http://dali.tian-w.cn/Article/details/gt2glxaymvc.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.316326.xyz/Article/details/gt2ffiairwm.html

[Q31] 分组后过滤
来源：http://dali.vqdsnc.cn/Article/details/gt2qodjgaco.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.9152youxi.cn/Article/details/gt2oymxoizf.html

[Q32] 分组拼接字符串
来源：http://dali.hysaishi.cn/Article/details/gt2nwzoseuc.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kmsujysg.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.jyoumei.cn/Article/details/gt2gptnrhkg.html

[Q33] 多列分组
来源：http://dali.pycfn.com/Article/details/gt2fdezcuio.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.sxryk.cn/Article/details/gt2ndelwtny.html

[Q34] 每组取第一条
来源：http://dali.jyoumei.cn/Article/details/gt2hmdfldmv.html

SELECT * FROM (
来源：http://dali.cucudq.cn/Article/details/gt2zukdkmdq.html


<!-- 参考信息 -->