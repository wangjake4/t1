代发 wailian999

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.hfpthk.cn/Article/details/gt2xnoljanp.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.cucudq.cn/Article/details/gt2ljrlskhm.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.xinyue.icu/Article/details/gt2nezjbfxf.html

Go:   slices.Sort(arr)
来源：http://dali.jyoumei.cn/Article/details/gt2hgxsrusj.html

Ruby: arr.sort
来源：http://dali.chenzaomai.com/Article/details/gt2upqlbmaa.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.cucudq.cn/Article/details/gt2dmvadwck.html

[N03] 快速排序（分治示例）
来源：http://dali.pycfn.com/Article/details/gt2ahinswvf.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhixingplan.top/Article/details/gt2jcfhxhpe.html

PHP:  // 递归实现，或用 usort
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ksbipskv.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jqgfzy.top/Article/details/gt2vsfivcie.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.nanxuanxn.top/Article/details/gt2puxlskmq.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.yongpay.top/Article/details/gt2dfuttfkm.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.fengsongda.top/Article/details/gt2vsvxgoyv.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.pengpengdd.cyou/Article/details/gt2hryukdrz.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.yuxming.cn/Article/details/gt2zbrzwmlp.html

[N04] 斐波那契数列
来源：http://dali.chenlongwang.top/Article/details/gt2jhugtstm.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.yueranfly.top/Article/details/gt2fmvjmmez.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.xuetiantiany.cn/Article/details/gt2tuixbswy.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.xinyue.icu/Article/details/gt2xdmnxeeh.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.aizwys.cn/Article/details/gt2ckejcpxn.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.yuanzhike.top/Article/details/gt2ixtjliir.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.mhx1999.top/Article/details/gt2nuikbjyo.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.yanxiufei.cn/Article/details/gt2fcycpmkg.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2unmjqekp.html

[N05] 最大公约数
来源：http://dali.zycfv.cn/Article/details/gt2aumsbofd.html

Py:   math.gcd(a, b)
来源：http://dali.haohaochexian.top/Article/details/gt2luoofdeo.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.chenzaomai.com/Article/details/gt2pqzbygul.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhoulong.xyz/Article/details/gt2tvpeggjn.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.daria6918.cn/Article/details/gt2nxqyuhny.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.yongpay.top/Article/details/gt2jwdfpzsw.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.aizwys.cn/Article/details/gt2hciklagc.html

Ruby: a.gcd(b)
来源：http://dali.yanxiufei.cn/Article/details/gt2lacefnpw.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.xziqi.cn/Article/details/gt2zmxcqkwn.html

[N06] 判断回文字符串
来源：http://dali.daxiang520.top/Article/details/gt2sjprulpu.html

Py:   s == s[::-1]
来源：http://dali.dashuyun.cn/Article/details/gt2tmmvhhls.html

PHP:  $s === strrev($s);
来源：http://dali.jyoumei.cn/Article/details/gt2umqihtza.html

JS:   s === [...s].reverse().join("")
来源：http://dali.shangyingyoupin.top/Article/details/gt2komakbiw.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhongyouzk.top/Article/details/gt2wtannfie.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.cheryme.top/Article/details/gt2nowhfmnx.html

Go:   // 双指针从两端比较
来源：http://dali.chenlongwang.top/Article/details/gt2fbdqzdps.html

Ruby: s == s.reverse
来源：http://dali.jqgfzy.top/Article/details/gt2exlnvhjs.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.bjfxy.top/Article/details/gt2txzshxnm.html

[N07] 两数之和（返回下标）
来源：http://dali.hongshengwenyu.top/Article/details/gt2nrktdfef.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.jyoumei.cn/Article/details/gt2gkrjughj.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.yvedp.cn/Article/details/gt2cfheokrx.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.fengsongda.top/Article/details/gt2jikhltdo.html

TS:   // 手写 Map<string, number>
来源：http://dali.hnqzz.top/Article/details/gt2caaptldm.html

Java: // 手写 HashMap
来源：http://dali.jqgufenzy.top/Article/details/gt2sgjtaqpp.html

Go:   // 手写 map[int]int
来源：http://dali.mhx1999.top/Article/details/gt2trhmomoh.html

Ruby: // 手写 Hash
来源：http://dali.xziqi.cn/Article/details/gt2wzmkmhzp.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.quarkkingdee.top/Article/details/gt2rbokrinu.html

[N08] 生成全排列
来源：http://dali.jyoumei.cn/Article/details/gt2btcautsk.html

Py:   itertools.permutations(arr)
来源：http://dali.ehwqpu.com/Article/details/gt2kqhitlgc.html

PHP:  // 手写递归交换
来源：http://dali.daxiang520.top/Article/details/gt2qxtfgxxe.html

JS:   // 手写回溯递归
来源：http://dali.sweek.top/Article/details/gt2lqhanozl.html

TS:   // 手写回溯递归
来源：http://dali.zhongyouzk.top/Article/details/gt2qiisstzn.html

Java: // 手写回溯递归
来源：http://dali.pengpengdd.cyou/Article/details/gt2qnfxlwfc.html

Go:   // 手写回溯递归
来源：http://dali.9152youxi.cn/Article/details/gt2liovdbtr.html

Ruby: arr.permutation.to_a
来源：http://dali.zhixingplan.top/Article/details/gt2qmihayir.html

C#:   // 手写回溯递归
来源：http://dali.chenlongwang.top/Article/details/gt2louwfnfi.html

[N09] 栈与队列
来源：http://dali.svipenyu.cn/Article/details/gt2wuynfqeq.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.nanxinkj.top/Article/details/gt2xgtjxgpa.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.ydzc1.top/Article/details/gt2bukjthlp.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.jianghu66.top/Article/details/gt2tidptqzu.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.yanxiufei.cn/Article/details/gt2dtzuxqxg.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.cucudq.cn/Article/details/gt2ksnbawnu.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.guannengcc.top/Article/details/gt2hbijrtws.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.cqqwz.cn/Article/details/gt2nctpifrh.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.jlsjyb.cn/Article/details/gt2bcymgrjh.html

[N10] 链表节点定义
来源：http://dali.aizwys.cn/Article/details/gt2omnitmfa.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.0kj1m.cn/Article/details/gt2eiphiddu.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.nwbrower.top/Article/details/gt2haefsymu.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.shzxlz.cn/Article/details/gt2nfzhtjph.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.svipenyu.cn/Article/details/gt2ztfpufht.html

Java: class Node { int v; Node next; }
来源：http://dali.jinqigufen.top/Article/details/gt2dktdbgba.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.pengpengdd.cyou/Article/details/gt2yztlsjls.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.gzhubu.top/Article/details/gt2husutlze.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.shuidangran.top/Article/details/gt2auxjrozz.html

[N11] 二叉树中序遍历
来源：http://dali.havefunace.top/Article/details/gt2thtdgkyh.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.0kj1m.cn/Article/details/gt2jsgyvoia.html

PHP:  // 手写递归函数
来源：http://dali.xziqi.cn/Article/details/gt2mozwczju.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.gogol.net.cn/Article/details/gt2kfliwldm.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.nanxinkj.top/Article/details/gt2tukdibbi.html

Java: // 手写递归
来源：http://dali.chenzaomai.com/Article/details/gt2bdewyafj.html

Go:   // 手写递归
来源：http://dali.tianlin.xyz/Article/details/gt2qmchlvfv.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.xziqi.cn/Article/details/gt2tqfclfjt.html

C#:   // 手写递归
来源：http://dali.shangyingyoupin.top/Article/details/gt2rnsbcwky.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.nanxinkj.top/Article/details/gt2vwbiyinh.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.tianlin.xyz/Article/details/gt2ebqzigrt.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.aibaodan.cn/Article/details/gt2dfcaomsb.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2swbjlndu.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.hfpthk.cn/Article/details/gt2sdxiflyi.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.svipenyu.cn/Article/details/gt2oijnexhy.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.meibo888.top/Article/details/gt2pyjixgtv.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.andypj.xyz/Article/details/gt2bnnufspq.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.wangdashe.top/Article/details/gt2bhcwzein.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gt2zvnljwpj.html

O. 并发与异步
来源：http://dali.yj202588.top/Article/details/gt2opcdwerb.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gt2jayevlyg.html

[O01] 启动一个线程
来源：http://dali.nwbrower.top/Article/details/gt2bqvjchog.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.ydzc1.top/Article/details/gt2nzcsjxyp.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.wangdashe.top/Article/details/gt2igrzdlgi.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.gzhubu.top/Article/details/gt2gxswmtmt.html

TS:   // 同 JS
来源：http://dali.hnqzz.top/Article/details/gt2wvehswew.html

Java: new Thread(() -> f()).start()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kszqkebw.html

Go:   go f()
来源：http://dali.cheryme.top/Article/details/gt2vanrjguf.html

Ruby: Thread.new { f }
来源：http://dali.snrcjt.cn/Article/details/gt2poxguwjf.html

C#:   Task.Run(() => F());
来源：http://dali.ppjwa.cn/Article/details/gt2lhcjgvju.html

[O02] 使用线程池
来源：http://dali.nanxinkj.top/Article/details/gt2cxtwbezc.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhiwuduotai.top/Article/details/gt2rsoflmhn.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.redwolf501.top/Article/details/gt2rnleqymq.html

JS:   // worker_threads 线程池
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cjisbiir.html

TS:   // worker_threads 线程池
来源：http://dali.sxryk.cn/Article/details/gt2ndtepdhq.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.9152youxi.cn/Article/details/gt2jcvyvfuq.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.aibaodan.cn/Article/details/gt2iqjgsyks.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.iojbl.cn/Article/details/gt2eveuepfj.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.yj202588.top/Article/details/gt2qgtdepip.html

[O03] 加锁保护共享数据
来源：http://dali.jinqigfzy.top/Article/details/gt2zayvutzq.html

Py:   with lock: shared += 1
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gfbviokx.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.yvedp.cn/Article/details/gt2ywwkrmkh.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.smart0.xyz/Article/details/gt2kysfuumx.html

TS:   // 同 JS
来源：http://dali.yongpay.top/Article/details/gt2qdayizwi.html

Java: synchronized (this) { shared++; }
来源：http://dali.ehwqpu.com/Article/details/gt2riqslafa.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.iojbl.cn/Article/details/gt2ippvdsxb.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.feifeiyinyue.top/Article/details/gt2dkqbnold.html

C#:   lock (gate) { shared++; }
来源：http://dali.shzxlz.cn/Article/details/gt2xaglsayy.html

[O04] 定义异步函数并等待
来源：http://dali.cashguo.top/Article/details/gt2itkphblu.html

Py:   async def f():⏎    await g()
来源：http://dali.tian-w.cn/Article/details/gt2upnzngpr.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.xylfe.cn/Article/details/gt2sprcbjbe.html

JS:   async function f() { await g(); }
来源：http://dali.cashguo.top/Article/details/gt2olbovhuf.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.haohaochexian.top/Article/details/gt2ymkxrgtb.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.wangdashe.top/Article/details/gt2zvnvntup.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.gzhubu.top/Article/details/gt2dhkkafuk.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.sxryk.cn/Article/details/gt2chrrflkk.html

C#:   async Task F() { await G(); }
来源：http://dali.jlsjyb.cn/Article/details/gt2entmdqom.html

[O05] 并发执行并等待全部完成
来源：http://dali.meibo888.top/Article/details/gt2bcxqgpeu.html

Py:   asyncio.gather(*tasks)
来源：http://dali.sweek.top/Article/details/gt2euhwkwll.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.snrcjt.cn/Article/details/gt2nsoslrst.html

JS:   await Promise.all(tasks)
来源：http://dali.jiagoushi.top/Article/details/gt2enbnoqmd.html

TS:   await Promise.all(tasks)
来源：http://dali.hywenlv.cn/Article/details/gt2cxpekzhm.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.hywenlv.cn/Article/details/gt2lmarzddl.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.sweek.top/Article/details/gt2jsqrakzt.html

Ruby: threads.map(&:join)
来源：http://dali.ydzc1.top/Article/details/gt2dfncjjbd.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.kuanghao11.cn/Article/details/gt2oybjhbls.html

[O06] 使用进程池
来源：http://dali.hywenlv.cn/Article/details/gt2czbiyqlr.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.gogol.net.cn/Article/details/gt2lfwvqbux.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.wangshuangyany.cn/Article/details/gt2mwwxolvj.html

JS:   // child_process / cluster 模块
来源：http://dali.316326.xyz/Article/details/gt2ezzieoct.html

TS:   // child_process / cluster 模块
来源：http://dali.ppjwa.cn/Article/details/gt2kfemdvjt.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.yonumen.top/Article/details/gt2wzyasgog.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.hywenlv.cn/Article/details/gt2pcuojkzs.html

Ruby: // fork 块
来源：http://dali.jqgufenzy.top/Article/details/gt2jwdkyswq.html

C#:   Parallel.For
来源：http://dali.gotoacloud.top/Article/details/gt2upicmnvg.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gt2ygerkiyv.html

P. 常用工具函数
来源：http://dali.guowangkeji.top/Article/details/gt2rkimrimi.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gt2vuxxcpox.html

[P01] 生成 UUID
来源：http://dali.jqgfzy.top/Article/details/gt2lynlbeqp.html

Py:   str(uuid.uuid4())
来源：http://dali.pengpengdd.cyou/Article/details/gt2pwuoyxyo.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.guowangkeji.top/Article/details/gt2uqmolwyk.html

JS:   crypto.randomUUID()
来源：http://dali.svipenyu.cn/Article/details/gt2kivvoscn.html

TS:   crypto.randomUUID()
来源：http://dali.fzhhl.top/Article/details/gt2hacxakmr.html

Java: UUID.randomUUID().toString()
来源：http://dali.jianghu66.top/Article/details/gt2ukefqoav.html

Go:   // 用 github.com/google/uuid
来源：http://dali.yvedp.cn/Article/details/gt2pvpbfwmx.html

Ruby: SecureRandom.uuid
来源：http://dali.wangdashe.top/Article/details/gt2bqyqpjyt.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.ybcxt.top/Article/details/gt2lsfyozql.html

[P02] MD5 / SHA256 摘要
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2eqyaiirv.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.xinyue.icu/Article/details/gt2mtalfrzq.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.jqgufenzy.top/Article/details/gt2cqvsniiz.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.shuidangran.top/Article/details/gt2oqtovhhl.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.cqqwz.cn/Article/details/gt2tlsgyoyl.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.hnxiangtu.top/Article/details/gt2kncovcfq.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.jyoumei.cn/Article/details/gt2sjcradzm.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.jyoumei.cn/Article/details/gt2mbqzbvlm.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.snrcjt.cn/Article/details/gt2koqkjiqg.html

[P03] 生成短随机字符串
来源：http://dali.birdmap.top/Article/details/gt2imnhfxex.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.jqgfzy.top/Article/details/gt2cfoxplys.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zycfv.cn/Article/details/gt2ldgunred.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.haohaochexian.top/Article/details/gt2ldrusytz.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2shoppdtj.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.yuanzhike.top/Article/details/gt2ecjbeijx.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.yvedp.cn/Article/details/gt2dyqjcndp.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.cqqwz.cn/Article/details/gt2sfjyqaui.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.ppjwa.cn/Article/details/gt2nnscoxfl.html

[P04] 求长度
来源：http://dali.hnxiangtu.top/Article/details/gt2gusoggsh.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2jvwgnvqp.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zdqjudy.top/Article/details/gt2meztuifa.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.ehwqpu.com/Article/details/gt2fqivhmxb.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.tanke756.top/Article/details/gt2izlxxyoi.html

Java: list.size();  map.size();  s.length()
来源：http://dali.yj20258.top/Article/details/gt2gzsowsjr.html

Go:   len(arr);  len(m)
来源：http://dali.zhongyouzk.top/Article/details/gt2jyzfscqo.html

Ruby: x.length;  x.size
来源：http://dali.wangdashe.top/Article/details/gt2mbxwgmjr.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.yueranfly.top/Article/details/gt2gocxglqr.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fcgdgoab.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.yuxming.cn/Article/details/gt2yfyfhzpf.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lkwfxvqw.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.hysaishi.cn/Article/details/gt2wymujuwn.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.jinqigfzy.top/Article/details/gt2jqzhtrdc.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.yangfankeji.com/Article/details/gt2onipcoqe.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.shangyingyoupin.top/Article/details/gt2uymeeprs.html

Ruby: a == b
来源：http://dali.cdnleiting.top/Article/details/gt2nykqwshv.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.andypj.xyz/Article/details/gt2fzdeywzs.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.bjfxy.top/Article/details/gt2gyqxfbho.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.havefunace.top/Article/details/gt2msmiqayz.html

PHP:  if (empty($x)) {}
来源：http://dali.yj202588.top/Article/details/gt2jspmytmn.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.ppjwa.cn/Article/details/gt2vfieollk.html

TS:   if (x == null) {}
来源：http://dali.haohaochexian.top/Article/details/gt2ijbieykb.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.ivvv.top/Article/details/gt2eypnltrv.html

Go:   if x == nil {}
来源：http://dali.jqgfzy.top/Article/details/gt2zqvdlkxo.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.ybcxt.top/Article/details/gt2dokcisox.html

C#:   if (x is null) {}
来源：http://dali.cheryme.top/Article/details/gt2hhwhxlgh.html

[P07] 防抖与节流
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2obkhvrib.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.gzhubu.top/Article/details/gt2hyedkjri.html

PHP:  // 手写时间戳比较
来源：http://dali.chenlongwang.top/Article/details/gt2hknouxil.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhoulong.xyz/Article/details/gt2bofjeyxb.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.feifeiyinyue.top/Article/details/gt2zrasidjq.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.yj20258888.top/Article/details/gt2gtzzlaop.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.yuxming.cn/Article/details/gt2rjvjamgf.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.chenlongwang.top/Article/details/gt2rqtbkoal.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.c1oappe.top/Article/details/gt2gnxlctqe.html

[P08] 处理浮点精度问题
来源：http://dali.cashguo.top/Article/details/gt2yinayigq.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.yj202588.top/Article/details/gt2kaimvafl.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.tianlin.xyz/Article/details/gt2skprkqex.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.gotoacloud.top/Article/details/gt2kibvtbgl.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.jiagoushi.top/Article/details/gt2pjylabgf.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.hysaishi.cn/Article/details/gt2fqxkarda.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.svipenyu.cn/Article/details/gt2jcormlhw.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.jlsjyb.cn/Article/details/gt2ikkcdyaj.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhoulong.xyz/Article/details/gt2wkxpqsxn.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gt2obmfdeix.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.wangdashe.top/Article/details/gt2gndboddi.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gt2vpsegpth.html

[Q01] 创建表
来源：http://dali.shuidangran.top/Article/details/gt2yqsuxoip.html

CREATE TABLE users (
来源：http://dali.kuanghao11.cn/Article/details/gt2shzunzpq.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.cqqwz.cn/Article/details/gt2mncwngas.html

name VARCHAR(50) NOT NULL,
来源：http://dali.jqgfzy.top/Article/details/gt2gppncmmg.html

email VARCHAR(100) UNIQUE,
来源：http://dali.ydzc1.top/Article/details/gt2bkxpotuk.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhixingplan.top/Article/details/gt2ymwapfdt.html

);
来源：http://dali.daria6918.cn/Article/details/gt2qwcdhxno.html

[Q02] 创建带外键的表
来源：http://dali.xinyue.icu/Article/details/gt2kqvvffbg.html

CREATE TABLE orders (
来源：http://dali.nanxuanxn.top/Article/details/gt2vfabtzpb.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.guowangkeji.top/Article/details/gt2vgvstyfw.html

user_id INT NOT NULL,
来源：http://dali.cqqwz.cn/Article/details/gt2qqxuvhzn.html

amount DECIMAL(10, 2),
来源：http://dali.tian-w.cn/Article/details/gt2ibyarwco.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.9152youxi.cn/Article/details/gt2xnsbgkml.html

);
来源：http://dali.zhiwuduotai.top/Article/details/gt2argvwwze.html

[Q03] 增加列
来源：http://dali.quarkkingdee.top/Article/details/gt2higvxywf.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zycfv.cn/Article/details/gt2ctpaszas.html

[Q04] 修改列类型
来源：http://dali.jianghu66.top/Article/details/gt2wrdqqouh.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.chenzaomai.com/Article/details/gt2plzriacu.html

[Q05] 重命名列
来源：http://dali.zhiwuduotai.top/Article/details/gt2cnjzyxgh.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.nwbrower.top/Article/details/gt2czrntciv.html

[Q06] 删除列
来源：http://dali.mhx1999.top/Article/details/gt2avujgkms.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.jqgufenzy.top/Article/details/gt2sqkvxqnu.html

[Q07] 删除表
来源：http://dali.hnxiangtu.top/Article/details/gt2asutyulx.html

DROP TABLE IF EXISTS orders;
来源：http://dali.iojbl.cn/Article/details/gt2zrpvrzxy.html

[Q08] 创建普通索引
来源：http://dali.jinqigufen.top/Article/details/gt2veckoacc.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.kuanghao11.cn/Article/details/gt2yafzprff.html

[Q09] 创建唯一索引
来源：http://dali.svipenyu.cn/Article/details/gt2lqvrmuxg.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.yj20258888.top/Article/details/gt2bfspnrlq.html

[Q10] 插入单行
来源：http://dali.316326.xyz/Article/details/gt2ujbtuhwj.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zycfv.cn/Article/details/gt2nhozhhkd.html

[Q11] 一次插入多行
来源：http://dali.0kj1m.cn/Article/details/gt2bkfpgxbi.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.hywenlv.cn/Article/details/gt2oejzdycw.html

[Q12] 插入后取自增 ID
来源：http://dali.dianchejie.cn/Article/details/gt2airqnpnk.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.shuidangran.top/Article/details/gt2tgbxywue.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.nanxuanxn.top/Article/details/gt2paqnkwjg.html

[Q13] 忽略重复插入
来源：http://dali.nanxuanxn.top/Article/details/gt2odlfhqcz.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zdqjudy.top/Article/details/gt2qcegnhng.html

[Q14] 存在则更新（upsert）
来源：http://dali.cheryme.top/Article/details/gt2nojaidrm.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.meibo888.top/Article/details/gt2wdxsquon.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.iojbl.cn/Article/details/gt2kbeqpsbp.html

[Q15] 查询全部
来源：http://dali.daxiang520.top/Article/details/gt2ndshxbyo.html

SELECT * FROM users;
来源：http://dali.jlsjyb.cn/Article/details/gt2nitytodi.html

[Q16] 查询指定列
来源：http://dali.feifeiyinyue.top/Article/details/gt2ghpsqlmz.html

SELECT id, name FROM users;
来源：http://dali.316326.xyz/Article/details/gt2wveykxrh.html

[Q17] 条件查询
来源：http://dali.hammf.cn/Article/details/gt2bcqosaup.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.smart0.xyz/Article/details/gt2czxlazoc.html

[Q18] 模糊匹配
来源：http://dali.jqgufenzy.top/Article/details/gt2yjsgybfv.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.yanxiufei.cn/Article/details/gt2mvtjmhgg.html

[Q19] 范围查询
来源：http://dali.redwolf501.top/Article/details/gt2gyqyvsik.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.hysaishi.cn/Article/details/gt2pfsomxxa.html

[Q20] IN 列表
来源：http://dali.jinqigfzy.top/Article/details/gt2qgrcgsnu.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.xuetiantiany.cn/Article/details/gt2elydxnaq.html

[Q21] 空值判断
来源：http://dali.cqqwz.cn/Article/details/gt2hxictfuc.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.pengpengdd.cyou/Article/details/gt2mqnyygsw.html

[Q22] 排序
来源：http://dali.zhongyouzk.top/Article/details/gt2hirldrkc.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.jinqigfzy.top/Article/details/gt2zedcuadt.html

[Q23] 分页
来源：http://dali.zycfv.cn/Article/details/gt2erznjerd.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.nwbrower.top/Article/details/gt2btnrhbti.html

[Q24] 去重
来源：http://dali.jyoumei.cn/Article/details/gt2nrlolzxc.html

SELECT DISTINCT city FROM users;
来源：http://dali.tanke756.top/Article/details/gt2zlzfffxx.html

[Q25] 只取前 N 条
来源：http://dali.xylfe.cn/Article/details/gt2uqazigne.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.hammf.cn/Article/details/gt2qxuitvqw.html

[Q26] 计数
来源：http://dali.sufxvd.cn/Article/details/gt2xfrckrgv.html

SELECT COUNT(*) FROM users;
来源：http://dali.xuanzx.com/Article/details/gt2ljcqocpo.html

[Q27] 条件计数
来源：http://dali.zdqjudy.top/Article/details/gt2jqebiult.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zycfv.cn/Article/details/gt2jxkpsviz.html

[Q28] 求和与平均
来源：http://dali.hnxiangtu.top/Article/details/gt2akcxmatu.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.havefunace.top/Article/details/gt2ahuppgge.html

[Q29] 最大最小值
来源：http://dali.guowangkeji.top/Article/details/gt2qvdqytei.html


<!-- 参考信息 -->