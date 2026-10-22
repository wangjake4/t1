代发 wailian999

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yangfankeji.com/Article/details/gtpjmuudii.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.yvedp.cn/Article/details/gtrwfyllns.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.nwbrower.top/Article/details/gtqnovcqaf.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.shzxlz.cn/Article/details/gtndpbgudh.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.iojbl.cn/Article/details/gtwpluxnnl.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.quarkkingdee.top/Article/details/gthtyyxwqc.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.sxryk.cn/Article/details/gtdxvbcbfz.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtltvbwlom.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.xuanzx.com/Article/details/gtiglzmlzg.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jinqigfzy.top/Article/details/gtsgwdscdl.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.kuanghao11.cn/Article/details/gtsojdpkya.html

Go:   slices.Sort(arr)
来源：http://dali.cqqwz.cn/Article/details/gtcihzhonm.html

Ruby: arr.sort
来源：http://dali.gzhubu.top/Article/details/gtnfsvyhzb.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.hnqzz.top/Article/details/gtsiewuxhi.html

[N03] 快速排序（分治示例）
来源：http://dali.sxryk.cn/Article/details/gtvxxpszel.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.gzhubu.top/Article/details/gtjwclggxc.html

PHP:  // 递归实现，或用 usort
来源：http://dali.bjfxy.top/Article/details/gtafvzpqzq.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.guowangkeji.top/Article/details/gtyctsnxlh.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yanxiufei.cn/Article/details/gtwgovwbji.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.sxryk.cn/Article/details/gthrelphqp.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.pycfn.com/Article/details/gtfvaybydl.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.smart0.xyz/Article/details/gtpfknmhot.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.yuanzhike.top/Article/details/gtecmdmvwj.html

[N04] 斐波那契数列
来源：http://dali.guannengcc.top/Article/details/gtmwlekpsa.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhengqikj.top/Article/details/gtrwnbwxpv.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.gogol.net.cn/Article/details/gtvvfyyiym.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.tian-w.cn/Article/details/gthajrqevc.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.nanxinkj.top/Article/details/gtswqkvffw.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.tianlin.xyz/Article/details/gtrtyjtsey.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.yonumen.top/Article/details/gtsbhexvlv.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtibqfpowv.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.bjfxy.top/Article/details/gtktrfcijg.html

[N05] 最大公约数
来源：http://dali.hnqzz.top/Article/details/gtqapntdov.html

Py:   math.gcd(a, b)
来源：http://dali.daxiang520.top/Article/details/gtpnpwyaih.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.jqgfzy.top/Article/details/gtbdjxdamc.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.wangshuangyany.cn/Article/details/gtiulsfwms.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.wangshuangyany.cn/Article/details/gtklqvmayg.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.yuxming.cn/Article/details/gtduyqixnu.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.yongpay.top/Article/details/gtbfuftlng.html

Ruby: a.gcd(b)
来源：http://dali.yj20258888.top/Article/details/gtmgghbsih.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.hammf.cn/Article/details/gtnifyhhwr.html

[N06] 判断回文字符串
来源：http://dali.cqqwz.cn/Article/details/gtjeqbccah.html

Py:   s == s[::-1]
来源：http://dali.cashguo.top/Article/details/gttqvtnqbu.html

PHP:  $s === strrev($s);
来源：http://dali.wangshuangyany.cn/Article/details/gtdrvlikfl.html

JS:   s === [...s].reverse().join("")
来源：http://dali.quarkkingdee.top/Article/details/gtqkxuhsvo.html

TS:   s === [...s].reverse().join("")
来源：http://dali.meibo888.top/Article/details/gtptvmbahc.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zdqjudy.top/Article/details/gtkbkltjvg.html

Go:   // 双指针从两端比较
来源：http://dali.nwbrower.top/Article/details/gtefhsosku.html

Ruby: s == s.reverse
来源：http://dali.shanyushiyangtech.top/Article/details/gteagsfaji.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.chenzaomai.com/Article/details/gtwjrqhkqc.html

[N07] 两数之和（返回下标）
来源：http://dali.tian-w.cn/Article/details/gtlbfdrsal.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.nanxuanxn.top/Article/details/gtsxgmpslf.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.yangfankeji.com/Article/details/gtbkoudtzq.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.0kj1m.cn/Article/details/gtjvfftsne.html

TS:   // 手写 Map<string, number>
来源：http://dali.shanyushiyangtech.top/Article/details/gtgymkrqxa.html

Java: // 手写 HashMap
来源：http://dali.yuxming.cn/Article/details/gtqbqonmhd.html

Go:   // 手写 map[int]int
来源：http://dali.ybcxt.top/Article/details/gtttmfsodv.html

Ruby: // 手写 Hash
来源：http://dali.hnxiangtu.top/Article/details/gtjujsdvtc.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.jqgufenzy.top/Article/details/gtdlxdqwhv.html

[N08] 生成全排列
来源：http://dali.jianghu66.top/Article/details/gtamhdjrlc.html

Py:   itertools.permutations(arr)
来源：http://dali.mhx1999.top/Article/details/gtrlcaykrw.html

PHP:  // 手写递归交换
来源：http://dali.wangdashe.top/Article/details/gthbfdjiid.html

JS:   // 手写回溯递归
来源：http://dali.shuidangran.top/Article/details/gtqrlqqptm.html

TS:   // 手写回溯递归
来源：http://dali.yuanzhike.top/Article/details/gtcpmzwscn.html

Java: // 手写回溯递归
来源：http://dali.jinyuanbaomall.cn/Article/details/gtprnkyqgw.html

Go:   // 手写回溯递归
来源：http://dali.316326.xyz/Article/details/gtaqwqewcu.html

Ruby: arr.permutation.to_a
来源：http://dali.316326.xyz/Article/details/gtcynvmqlz.html

C#:   // 手写回溯递归
来源：http://dali.ppjwa.cn/Article/details/gtpiwebovj.html

[N09] 栈与队列
来源：http://dali.haohaochexian.top/Article/details/gtuzjilrol.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.nanxinkj.top/Article/details/gtfxhbwdnk.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.316326.xyz/Article/details/gtzfmqzgnc.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.nanxuanxn.top/Article/details/gtnbnfnxua.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.chenzaomai.com/Article/details/gtvlmoglha.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.fengsongda.top/Article/details/gthledzlci.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.hfpthk.cn/Article/details/gtlfoimvlt.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.316326.xyz/Article/details/gtsczkjhtc.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.cheryme.top/Article/details/gtgpddscuq.html

[N10] 链表节点定义
来源：http://dali.nanxuanxn.top/Article/details/gtkypjkxge.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.svipenyu.cn/Article/details/gttyfxxebg.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.redwolf501.top/Article/details/gtemrglszw.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhixingplan.top/Article/details/gtxcqbjsjr.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.sysykeji.top/Article/details/gtjzyeecpg.html

Java: class Node { int v; Node next; }
来源：http://dali.meibo888.top/Article/details/gtzifknbhq.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gtdgilzqqp.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.aizwys.cn/Article/details/gtptfzyfwh.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.fengsongda.top/Article/details/gtyqgwbxdu.html

[N11] 二叉树中序遍历
来源：http://dali.vqdsnc.cn/Article/details/gtxayyffsj.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.dashuyun.cn/Article/details/gtizymyxsi.html

PHP:  // 手写递归函数
来源：http://dali.0kj1m.cn/Article/details/gtofjrwwmv.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.dianchejie.cn/Article/details/gtlynwtxqp.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.316326.xyz/Article/details/gtkzdpsihj.html

Java: // 手写递归
来源：http://dali.yuanzhike.top/Article/details/gtznjbjnwe.html

Go:   // 手写递归
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpedumayi.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.chenlongwang.top/Article/details/gtozaecsyc.html

C#:   // 手写递归
来源：http://dali.yonumen.top/Article/details/gtpwdtomjb.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.cheryme.top/Article/details/gttfcoabir.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.ivvv.top/Article/details/gttddjhtxm.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.fengsongda.top/Article/details/gtfdlealut.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjjffoyps.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.havefunace.top/Article/details/gtcsuybkml.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.cqqwz.cn/Article/details/gtcemxpngu.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.snrcjt.cn/Article/details/gthgaewnhj.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.fzhhl.top/Article/details/gtwhndusls.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzoicednx.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtcbslxypo.html

O. 并发与异步
来源：http://dali.hysaishi.cn/Article/details/gtebcmtzcz.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtmgbmutnb.html

[O01] 启动一个线程
来源：http://dali.9152youxi.cn/Article/details/gtcaprlwrh.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.ehwqpu.com/Article/details/gtjhlzqsaf.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.yuxming.cn/Article/details/gtzsonlvam.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.kuanghao11.cn/Article/details/gtsutpnwkt.html

TS:   // 同 JS
来源：http://dali.chenlongwang.top/Article/details/gteqmmcgrc.html

Java: new Thread(() -> f()).start()
来源：http://dali.pycfn.com/Article/details/gtlheuauya.html

Go:   go f()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdbbqyvwh.html

Ruby: Thread.new { f }
来源：http://dali.snrcjt.cn/Article/details/gtwzdivhwr.html

C#:   Task.Run(() => F());
来源：http://dali.zhongyouzk.top/Article/details/gthifvfvse.html

[O02] 使用线程池
来源：http://dali.guannengcc.top/Article/details/gtjdajmakr.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.mhx1999.top/Article/details/gtknntjpdt.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.yangfankeji.com/Article/details/gtlmfakszp.html

JS:   // worker_threads 线程池
来源：http://dali.shanyushiyangkeji.top/Article/details/gtilfqlzfu.html

TS:   // worker_threads 线程池
来源：http://dali.9152youxi.cn/Article/details/gtvjbefgzc.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.yj20258888.top/Article/details/gtjaftnlgn.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.mhx1999.top/Article/details/gtqlsnilka.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.vqdsnc.cn/Article/details/gtfrqpvumt.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.mhx1999.top/Article/details/gtwnnfdgfv.html

[O03] 加锁保护共享数据
来源：http://dali.sxryk.cn/Article/details/gtidqnlquc.html

Py:   with lock: shared += 1
来源：http://dali.cashguo.top/Article/details/gtmjiutppa.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gtvczuyusd.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.jianghu66.top/Article/details/gtpgorzszv.html

TS:   // 同 JS
来源：http://dali.xuanzx.com/Article/details/gthrpxeldh.html

Java: synchronized (this) { shared++; }
来源：http://dali.zycfv.cn/Article/details/gtwtikmvqz.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.ivvv.top/Article/details/gtedsoqwrm.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.shanyushiyangtech.top/Article/details/gtpegtsfjr.html

C#:   lock (gate) { shared++; }
来源：http://dali.hnxiangtu.top/Article/details/gtmrglurve.html

[O04] 定义异步函数并等待
来源：http://dali.yonumen.top/Article/details/gtvpsnlxza.html

Py:   async def f():⏎    await g()
来源：http://dali.shangyingyoupin.top/Article/details/gtprskgtke.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.dashuyun.cn/Article/details/gtgzfwlxta.html

JS:   async function f() { await g(); }
来源：http://dali.shuidangran.top/Article/details/gtzirgmcnz.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.redwolf501.top/Article/details/gtizjtmhyf.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.tanke756.top/Article/details/gtgsgxbthv.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.ydzc1.top/Article/details/gtzuomcnxo.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.wangshuangyany.cn/Article/details/gtuedstnmv.html

C#:   async Task F() { await G(); }
来源：http://dali.yuxming.cn/Article/details/gtzeiqtger.html

[O05] 并发执行并等待全部完成
来源：http://dali.tanke756.top/Article/details/gtgtszsafd.html

Py:   asyncio.gather(*tasks)
来源：http://dali.yj20258.top/Article/details/gtbdhdjqos.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.redwolf501.top/Article/details/gtiufzngzx.html

JS:   await Promise.all(tasks)
来源：http://dali.yj20258.top/Article/details/gthurlbczc.html

TS:   await Promise.all(tasks)
来源：http://dali.ybcxt.top/Article/details/gtuunbyaam.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.yj202588.top/Article/details/gtdvyhvqte.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhengqikj.top/Article/details/gtadubwtxk.html

Ruby: threads.map(&:join)
来源：http://dali.ivvv.top/Article/details/gtxqdginpg.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.yangfankeji.com/Article/details/gtcakmhihb.html

[O06] 使用进程池
来源：http://dali.sufxvd.cn/Article/details/gtvlxnlckz.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.havefunace.top/Article/details/gtshwmlfzs.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.yanxiufei.cn/Article/details/gtteszueeg.html

JS:   // child_process / cluster 模块
来源：http://dali.yj202588.top/Article/details/gtfpwgppih.html

TS:   // child_process / cluster 模块
来源：http://dali.yueranfly.top/Article/details/gtmksuqhoe.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbiocmjjc.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.smart0.xyz/Article/details/gtnylvjayb.html

Ruby: // fork 块
来源：http://dali.jyoumei.cn/Article/details/gtzkcngapj.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gtnienvmwl.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gthpwwulgu.html

P. 常用工具函数
来源：http://dali.cucudq.cn/Article/details/gtinbxaazw.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfvsizrny.html

[P01] 生成 UUID
来源：http://dali.haohaochexian.top/Article/details/gthgkyrrqh.html

Py:   str(uuid.uuid4())
来源：http://dali.jiagoushi.top/Article/details/gtkjqzkpxs.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.yonumen.top/Article/details/gtbrgqevbg.html

JS:   crypto.randomUUID()
来源：http://dali.redwolf501.top/Article/details/gtgsjfrolx.html

TS:   crypto.randomUUID()
来源：http://dali.guannengcc.top/Article/details/gtdklfstkl.html

Java: UUID.randomUUID().toString()
来源：http://dali.guowangkeji.top/Article/details/gtixasflxd.html

Go:   // 用 github.com/google/uuid
来源：http://dali.0kj1m.cn/Article/details/gtmqfbsoel.html

Ruby: SecureRandom.uuid
来源：http://dali.aizwys.cn/Article/details/gtaipazgsc.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.daria6918.cn/Article/details/gtlibsorqi.html

[P02] MD5 / SHA256 摘要
来源：http://dali.snrcjt.cn/Article/details/gtbeshsshi.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gtsfkvltel.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.daria6918.cn/Article/details/gtiokwlstr.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.xziqi.cn/Article/details/gtnopbksqf.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.sufxvd.cn/Article/details/gtvrzlzjvv.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.yj202588.top/Article/details/gtbilxbyxz.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.mhx1999.top/Article/details/gtpiivyvcv.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.0kj1m.cn/Article/details/gtwjwarhrf.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtunnaknee.html

[P03] 生成短随机字符串
来源：http://dali.sufxvd.cn/Article/details/gttlifmkxw.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.fzhhl.top/Article/details/gttuqwhssb.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaluyllxj.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjcmusegn.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.gaohongyu789.top/Article/details/gtpnmdsbnz.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.quarkkingdee.top/Article/details/gtweuloskg.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.cheryme.top/Article/details/gtxvqblbdu.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.mhx1999.top/Article/details/gtfgpbjhsd.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdzifmylp.html

[P04] 求长度
来源：http://dali.xuetiantiany.cn/Article/details/gtsybfgitr.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.svipenyu.cn/Article/details/gtguowwkgu.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.xuetiantiany.cn/Article/details/gtsekmnocl.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jinqigufen.top/Article/details/gtmkhbtcrk.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yueranfly.top/Article/details/gtugojkgqr.html

Java: list.size();  map.size();  s.length()
来源：http://dali.kuanghao11.cn/Article/details/gtltigrwhv.html

Go:   len(arr);  len(m)
来源：http://dali.yj20258888.top/Article/details/gtwynpvzgi.html

Ruby: x.length;  x.size
来源：http://dali.meibo888.top/Article/details/gtktstpefh.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.cqqwz.cn/Article/details/gtivffyqsa.html

[P05] 判断两个对象内容是否相等
来源：http://dali.andypj.xyz/Article/details/gtqtxlmvdq.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.xinyue.icu/Article/details/gtrhdefzvy.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.guannengcc.top/Article/details/gtnabpmgik.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.gzhubu.top/Article/details/gtccvsibmj.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.nanxuanxn.top/Article/details/gtknekzkrm.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.aizwys.cn/Article/details/gtirtwyqlz.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhengqikj.top/Article/details/gtktrxgwze.html

Ruby: a == b
来源：http://dali.yj20258888.top/Article/details/gtsptnonfb.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.nanxuanxn.top/Article/details/gtjknunxml.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.xuetiantiany.cn/Article/details/gtiavzzydv.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbligejzj.html

PHP:  if (empty($x)) {}
来源：http://dali.yvedp.cn/Article/details/gtrxojewma.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.vqdsnc.cn/Article/details/gtettimixr.html

TS:   if (x == null) {}
来源：http://dali.redwolf501.top/Article/details/gtkjodozwv.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.yj202588.top/Article/details/gttxfnpuak.html

Go:   if x == nil {}
来源：http://dali.yj20258888.top/Article/details/gtzjxseinw.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.chenjidiqi.icu/Article/details/gtzajkfhkq.html

C#:   if (x is null) {}
来源：http://dali.xylfe.cn/Article/details/gtfqinjtcg.html

[P07] 防抖与节流
来源：http://dali.chenzaomai.com/Article/details/gtywriyucg.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.wangdashe.top/Article/details/gtjdpqwyjh.html

PHP:  // 手写时间戳比较
来源：http://dali.pycfn.com/Article/details/gtoctnibib.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.guowangkeji.top/Article/details/gtxfogjvoz.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.nanxuanxn.top/Article/details/gttljyeybg.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.gogol.net.cn/Article/details/gtbgisiblv.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.wangshuangyany.cn/Article/details/gtmwifuhnp.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.jqgufenzy.top/Article/details/gttmiuwrth.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.ywan-chungtsiang.top/Article/details/gttyhmeyoh.html

[P08] 处理浮点精度问题
来源：http://dali.jiagoushi.top/Article/details/gthnreyyev.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.shzxlz.cn/Article/details/gtztttpfha.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhiwuduotai.top/Article/details/gtolrmqcce.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.yangfankeji.com/Article/details/gtarcugbfn.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtejdftfwb.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhongyouzk.top/Article/details/gtsqwmmwaz.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.yj202588.top/Article/details/gtjcsdkgyb.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.nanxinkj.top/Article/details/gtljbmxmwm.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.0kj1m.cn/Article/details/gtqfenupwm.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtoymnpasz.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.redwolf501.top/Article/details/gtuajfmnnf.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtudcvxkee.html

[Q01] 创建表
来源：http://dali.nwbrower.top/Article/details/gtvssptnfa.html

CREATE TABLE users (
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkysjabrt.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhiwuduotai.top/Article/details/gtzxymcenb.html

name VARCHAR(50) NOT NULL,
来源：http://dali.quarkkingdee.top/Article/details/gtcqbvdnrz.html

email VARCHAR(100) UNIQUE,
来源：http://dali.shuidangran.top/Article/details/gtyglylere.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.aibaodan.cn/Article/details/gtaifqpboe.html

);
来源：http://dali.chenzaomai.com/Article/details/gtuhidhtsm.html

[Q02] 创建带外键的表
来源：http://dali.jqgufenzy.top/Article/details/gtunptjpzp.html

CREATE TABLE orders (
来源：http://dali.tianlin.xyz/Article/details/gtuqmusxxr.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.hnqzz.top/Article/details/gtkswfmmtn.html

user_id INT NOT NULL,
来源：http://dali.guowangkeji.top/Article/details/gtanwfscfq.html

amount DECIMAL(10, 2),
来源：http://dali.shanyushiyangtech.top/Article/details/gttapxxpce.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdlbdydfg.html

);
来源：http://dali.aizwys.cn/Article/details/gtlvigyfha.html

[Q03] 增加列
来源：http://dali.dashuyun.cn/Article/details/gthspjlxzv.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.yonumen.top/Article/details/gtloxgnvvf.html

[Q04] 修改列类型
来源：http://dali.guannengcc.top/Article/details/gtgusnnxhx.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.feifeiyinyue.top/Article/details/gtsqzxvloq.html

[Q05] 重命名列
来源：http://dali.kuanghao11.cn/Article/details/gtpyyjrixp.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhengqikj.top/Article/details/gtxalblipb.html

[Q06] 删除列
来源：http://dali.ydzc1.top/Article/details/gtswtxhyqs.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.yangfankeji.com/Article/details/gticqocbek.html

[Q07] 删除表
来源：http://dali.ywan-chungtsiang.top/Article/details/gtolzbttln.html

DROP TABLE IF EXISTS orders;
来源：http://dali.ppjwa.cn/Article/details/gtdagoieod.html

[Q08] 创建普通索引
来源：http://dali.nwbrower.top/Article/details/gtdcxlpgnx.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.pycfn.com/Article/details/gtkoyoipuo.html

[Q09] 创建唯一索引
来源：http://dali.tianlin.xyz/Article/details/gttfcehcoi.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.316326.xyz/Article/details/gtizicjase.html

[Q10] 插入单行
来源：http://dali.jlsjyb.cn/Article/details/gtxmojeydv.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.chenlongwang.top/Article/details/gteyucpuqe.html

[Q11] 一次插入多行
来源：http://dali.0kj1m.cn/Article/details/gtecrmyiyh.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.sysykeji.top/Article/details/gttpmtwhvw.html

[Q12] 插入后取自增 ID
来源：http://dali.jinqigufen.top/Article/details/gtzaieydxh.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.yueranfly.top/Article/details/gtwkxlejqi.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.wangshuangyany.cn/Article/details/gtpsthjpzk.html

[Q13] 忽略重复插入
来源：http://dali.pycfn.com/Article/details/gtduotioqo.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhijiandao.cn/Article/details/gtnvgcffeu.html

[Q14] 存在则更新（upsert）
来源：http://dali.mhx1999.top/Article/details/gturdgxlqr.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.bjfxy.top/Article/details/gtyszyhabf.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkyiphwrg.html

[Q15] 查询全部
来源：http://dali.zdqjudy.top/Article/details/gthhbokaub.html

SELECT * FROM users;
来源：http://dali.guannengcc.top/Article/details/gtnfjsopnr.html

[Q16] 查询指定列
来源：http://dali.feifeiyinyue.top/Article/details/gthgxicvws.html

SELECT id, name FROM users;
来源：http://dali.ivvv.top/Article/details/gtsrvuyvdb.html

[Q17] 条件查询
来源：http://dali.hysaishi.cn/Article/details/gtprlabhjp.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.cqqwz.cn/Article/details/gtnnlrhxiz.html

[Q18] 模糊匹配
来源：http://dali.jyoumei.cn/Article/details/gthqncbwff.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.vqdsnc.cn/Article/details/gtkzavgaxo.html

[Q19] 范围查询
来源：http://dali.bjfxy.top/Article/details/gtwizkdbzh.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.hfpthk.cn/Article/details/gtxecbtrca.html

[Q20] IN 列表
来源：http://dali.daria6918.cn/Article/details/gtqxxenxpl.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.pengpengdd.cyou/Article/details/gtmkxgjwou.html

[Q21] 空值判断
来源：http://dali.c1oappe.top/Article/details/gtbobwgbxg.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.jlsjyb.cn/Article/details/gtcapwakgf.html

[Q22] 排序
来源：http://dali.hongshengwenyu.top/Article/details/gtwvhtslzc.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.chenlongwang.top/Article/details/gtvxalgehn.html

[Q23] 分页
来源：http://dali.dianchejie.cn/Article/details/gtxeidakqv.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.chenjidiqi.icu/Article/details/gtckexlmmr.html

[Q24] 去重
来源：http://dali.shangyingyoupin.top/Article/details/gtsxrfunhd.html

SELECT DISTINCT city FROM users;
来源：http://dali.feifeiyinyue.top/Article/details/gtqqkmalap.html

[Q25] 只取前 N 条
来源：http://dali.jinqigfzy.top/Article/details/gtkbzxbokv.html


<!-- 参考信息 -->