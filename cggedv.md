代发 wailian999

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.sweek.top/Article/details/gtaoafpahl.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.havefunace.top/Article/details/gtyoicbaiw.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhongyouzk.top/Article/details/gttigtpdmq.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.yanxiufei.cn/Article/details/gtupaefnkz.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.vqdsnc.cn/Article/details/gttazcqasg.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.wangshuangyany.cn/Article/details/gthgatfsgi.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.nwbrower.top/Article/details/gtphsbdpwy.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.yuanzhike.top/Article/details/gtheozrucc.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.xuetiantiany.cn/Article/details/gtdwbdrdoa.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.cheryme.top/Article/details/gtfvvycsmi.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.birdmap.top/Article/details/gttugbltmq.html

Go:   slices.Sort(arr)
来源：http://dali.yvedp.cn/Article/details/gtqdinncrw.html

Ruby: arr.sort
来源：http://dali.zhengqikj.top/Article/details/gtmyokcqvc.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.guowangkeji.top/Article/details/gtivxzrrso.html

[N03] 快速排序（分治示例）
来源：http://dali.svipenyu.cn/Article/details/gtxarmkwoc.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.chenzaomai.com/Article/details/gtvaazzdkm.html

PHP:  // 递归实现，或用 usort
来源：http://dali.svipenyu.cn/Article/details/gtypfkultn.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.xuetiantiany.cn/Article/details/gtunshqjds.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.chenjidiqi.icu/Article/details/gtmtvabyfb.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.sxryk.cn/Article/details/gtoyeuuidz.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.xylfe.cn/Article/details/gtmbciwayf.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.havefunace.top/Article/details/gtivrkxraa.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zycfv.cn/Article/details/gtkdxbjjih.html

[N04] 斐波那契数列
来源：http://dali.shangyingyoupin.top/Article/details/gtjtowvfwv.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhiwuduotai.top/Article/details/gtmoghuacr.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.daxiang520.top/Article/details/gtezhkukmx.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcrslctcw.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.hnxiangtu.top/Article/details/gtnemjvdwf.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.cashguo.top/Article/details/gtgfhixper.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zycfv.cn/Article/details/gtpdvbcnts.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.jqgfzy.top/Article/details/gtuotrhfta.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.jinqigufen.top/Article/details/gtuivddlut.html

[N05] 最大公约数
来源：http://dali.vqdsnc.cn/Article/details/gtfzculmqb.html

Py:   math.gcd(a, b)
来源：http://dali.nwbrower.top/Article/details/gtvklepqgw.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.yuanzhike.top/Article/details/gtcvuuohcj.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.chenlongwang.top/Article/details/gtnznfrdpl.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.smart0.xyz/Article/details/gtrlfmgmpt.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.fzhhl.top/Article/details/gtvdrawwqc.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.kuanghao11.cn/Article/details/gttszhlyyb.html

Ruby: a.gcd(b)
来源：http://dali.chenjidiqi.icu/Article/details/gtahswwnao.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.0kj1m.cn/Article/details/gtlyryozmd.html

[N06] 判断回文字符串
来源：http://dali.jinqigfzy.top/Article/details/gtczasojpx.html

Py:   s == s[::-1]
来源：http://dali.xylfe.cn/Article/details/gtifhamdbx.html

PHP:  $s === strrev($s);
来源：http://dali.iojbl.cn/Article/details/gtqchcxlzf.html

JS:   s === [...s].reverse().join("")
来源：http://dali.cdnleiting.top/Article/details/gtamcpgjhy.html

TS:   s === [...s].reverse().join("")
来源：http://dali.bjfxy.top/Article/details/gtzmrmumcm.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.hywenlv.cn/Article/details/gtvsnyasso.html

Go:   // 双指针从两端比较
来源：http://dali.hammf.cn/Article/details/gtnkithrnl.html

Ruby: s == s.reverse
来源：http://dali.316326.xyz/Article/details/gtkolkrvjo.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.xuetiantiany.cn/Article/details/gthrynjxoe.html

[N07] 两数之和（返回下标）
来源：http://dali.wangdashe.top/Article/details/gtrvdkwpvm.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.yongpay.top/Article/details/gtxmcsvjct.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.feifeiyinyue.top/Article/details/gtaugnngsg.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.xuanzx.com/Article/details/gtfshlimip.html

TS:   // 手写 Map<string, number>
来源：http://dali.sufxvd.cn/Article/details/gtkgictpby.html

Java: // 手写 HashMap
来源：http://dali.daria6918.cn/Article/details/gtfjbidkpo.html

Go:   // 手写 map[int]int
来源：http://dali.hywenlv.cn/Article/details/gtpahrdbxc.html

Ruby: // 手写 Hash
来源：http://dali.daxiang520.top/Article/details/gttgwbyrbg.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.c1oappe.top/Article/details/gtqxkoumdp.html

[N08] 生成全排列
来源：http://dali.jlsjyb.cn/Article/details/gtzvycqbjp.html

Py:   itertools.permutations(arr)
来源：http://dali.9152youxi.cn/Article/details/gteivociyt.html

PHP:  // 手写递归交换
来源：http://dali.xylfe.cn/Article/details/gtxwvttzbp.html

JS:   // 手写回溯递归
来源：http://dali.gotoacloud.top/Article/details/gtnzzetvzz.html

TS:   // 手写回溯递归
来源：http://dali.zhongyouzk.top/Article/details/gtdpbdjbjy.html

Java: // 手写回溯递归
来源：http://dali.wangdashe.top/Article/details/gtxnxoidlc.html

Go:   // 手写回溯递归
来源：http://dali.vqdsnc.cn/Article/details/gtezarihqa.html

Ruby: arr.permutation.to_a
来源：http://dali.hnxiangtu.top/Article/details/gtdsgwciqa.html

C#:   // 手写回溯递归
来源：http://dali.tianlin.xyz/Article/details/gtbefstibl.html

[N09] 栈与队列
来源：http://dali.ppjwa.cn/Article/details/gtusihtxku.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.xziqi.cn/Article/details/gtxpcbgvgn.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.fzhhl.top/Article/details/gtjihuebcx.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.daria6918.cn/Article/details/gtiaawsuzo.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.guowangkeji.top/Article/details/gtngrnphux.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhengqikj.top/Article/details/gtpfvwmged.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.jinqigfzy.top/Article/details/gtjozkdohs.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.jinqigfzy.top/Article/details/gtumrithla.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.tanke756.top/Article/details/gtdyxgrphi.html

[N10] 链表节点定义
来源：http://dali.jqgfzy.top/Article/details/gtbeddzonc.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.jianghu66.top/Article/details/gtadvtzifm.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.yuanzhike.top/Article/details/gtyyokkssd.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.smart0.xyz/Article/details/gttniwtpna.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.gzhubu.top/Article/details/gthquhplsk.html

Java: class Node { int v; Node next; }
来源：http://dali.hnqzz.top/Article/details/gtsezqtioq.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.svipenyu.cn/Article/details/gtftbmarbc.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.yuanzhike.top/Article/details/gtaribcmgw.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.havefunace.top/Article/details/gtusejonqz.html

[N11] 二叉树中序遍历
来源：http://dali.jiagoushi.top/Article/details/gtmxzpytde.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.smart0.xyz/Article/details/gtepklvmvv.html

PHP:  // 手写递归函数
来源：http://dali.yanxiufei.cn/Article/details/gtrusdajny.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.havefunace.top/Article/details/gtuuafmhmv.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhiwuduotai.top/Article/details/gthntdvmqj.html

Java: // 手写递归
来源：http://dali.aibaodan.cn/Article/details/gtxxfimqsu.html

Go:   // 手写递归
来源：http://dali.haohaochexian.top/Article/details/gtfvppbahh.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.nanxinkj.top/Article/details/gtagihodet.html

C#:   // 手写递归
来源：http://dali.gogol.net.cn/Article/details/gtigbvbgyq.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.xylfe.cn/Article/details/gtkzwzldkl.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.xuetiantiany.cn/Article/details/gtdjclcfzn.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.pengpengdd.cyou/Article/details/gtxxuvhfuv.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.chenzaomai.com/Article/details/gtafrralla.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.haohaochexian.top/Article/details/gtncgudaai.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.andypj.xyz/Article/details/gtowpaagjw.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.haohaochexian.top/Article/details/gtupvrsfcm.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.yj20258.top/Article/details/gtnhrvcmoa.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jinqigfzy.top/Article/details/gtlykklwbc.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtmfmpfgaq.html

O. 并发与异步
来源：http://dali.jinqigufen.top/Article/details/gtrlrwqepx.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtxpprpams.html

[O01] 启动一个线程
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthmexayal.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.mhx1999.top/Article/details/gtagsppqfh.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.kuanghao11.cn/Article/details/gthjunopbv.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.nanxuanxn.top/Article/details/gtjrvodvuo.html

TS:   // 同 JS
来源：http://dali.sxryk.cn/Article/details/gtgccmgawp.html

Java: new Thread(() -> f()).start()
来源：http://dali.svipenyu.cn/Article/details/gtxukhbeai.html

Go:   go f()
来源：http://dali.tian-w.cn/Article/details/gtaiavlafq.html

Ruby: Thread.new { f }
来源：http://dali.dashuyun.cn/Article/details/gtexnpgeoh.html

C#:   Task.Run(() => F());
来源：http://dali.birdmap.top/Article/details/gtiboclydk.html

[O02] 使用线程池
来源：http://dali.shangyingyoupin.top/Article/details/gtgmqcpnpj.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.ivvv.top/Article/details/gtoxlabats.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.cdnleiting.top/Article/details/gtsedrlgsg.html

JS:   // worker_threads 线程池
来源：http://dali.shanyushiyangkeji.top/Article/details/gtndkfqxju.html

TS:   // worker_threads 线程池
来源：http://dali.ybcxt.top/Article/details/gttodgqxzl.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.dianchejie.cn/Article/details/gtznbysvdb.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.dianchejie.cn/Article/details/gtxuorqpgk.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.quarkkingdee.top/Article/details/gttgxktrtn.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhongyouzk.top/Article/details/gtizlxumyk.html

[O03] 加锁保护共享数据
来源：http://dali.tianlin.xyz/Article/details/gtjggzheem.html

Py:   with lock: shared += 1
来源：http://dali.daria6918.cn/Article/details/gthtlcmgqp.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.quarkkingdee.top/Article/details/gthrrvxdbp.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.yj20258888.top/Article/details/gtzwgfiwvz.html

TS:   // 同 JS
来源：http://dali.xinyue.icu/Article/details/gtotceggst.html

Java: synchronized (this) { shared++; }
来源：http://dali.jqgfzy.top/Article/details/gtffdebobz.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.iojbl.cn/Article/details/gtapaizuzi.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.fzhhl.top/Article/details/gtttwqovjy.html

C#:   lock (gate) { shared++; }
来源：http://dali.daxiang520.top/Article/details/gtjjbixgim.html

[O04] 定义异步函数并等待
来源：http://dali.tianlin.xyz/Article/details/gtujtmamoh.html

Py:   async def f():⏎    await g()
来源：http://dali.redwolf501.top/Article/details/gtytqailnn.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrezirgmr.html

JS:   async function f() { await g(); }
来源：http://dali.yj202588.top/Article/details/gtgfjxlmso.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.birdmap.top/Article/details/gtroxjzjss.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.bjfxy.top/Article/details/gtptnerlvq.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.mhx1999.top/Article/details/gtkwniltpe.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.svipenyu.cn/Article/details/gtpchahjnv.html

C#:   async Task F() { await G(); }
来源：http://dali.jinqigfzy.top/Article/details/gtnrwaoxwu.html

[O05] 并发执行并等待全部完成
来源：http://dali.wangdashe.top/Article/details/gtsawwmkep.html

Py:   asyncio.gather(*tasks)
来源：http://dali.cucudq.cn/Article/details/gtrrflnsvi.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.smart0.xyz/Article/details/gtxwuwvpfd.html

JS:   await Promise.all(tasks)
来源：http://dali.hywenlv.cn/Article/details/gtiiwfkvwu.html

TS:   await Promise.all(tasks)
来源：http://dali.yj202588.top/Article/details/gtacptoydb.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.daria6918.cn/Article/details/gtglovxybm.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.xylfe.cn/Article/details/gtzszftode.html

Ruby: threads.map(&:join)
来源：http://dali.shanyushiyangkeji.top/Article/details/gthplwstud.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhongyouzk.top/Article/details/gtoyvbbebc.html

[O06] 使用进程池
来源：http://dali.yangfankeji.com/Article/details/gtauajbwva.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.vqdsnc.cn/Article/details/gtvyjwlkqg.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.quarkkingdee.top/Article/details/gthywyvrnw.html

JS:   // child_process / cluster 模块
来源：http://dali.hywenlv.cn/Article/details/gtczwsylai.html

TS:   // child_process / cluster 模块
来源：http://dali.cucudq.cn/Article/details/gtmybcvsyx.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhoulong.xyz/Article/details/gtvvzrdnqi.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.hongshengwenyu.top/Article/details/gtdtagbesp.html

Ruby: // fork 块
来源：http://dali.bjfxy.top/Article/details/gtfezclecb.html

C#:   Parallel.For
来源：http://dali.meibo888.top/Article/details/gttgjglgwx.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtoqilojxw.html

P. 常用工具函数
来源：http://dali.yongpay.top/Article/details/gtfwgzayqb.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtdltmxszj.html

[P01] 生成 UUID
来源：http://dali.bjfxy.top/Article/details/gtwkwrszdm.html

Py:   str(uuid.uuid4())
来源：http://dali.bjfxy.top/Article/details/gtlfcpulid.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhiwuduotai.top/Article/details/gtsgooczfx.html

JS:   crypto.randomUUID()
来源：http://dali.fengsongda.top/Article/details/gtfmuxrozs.html

TS:   crypto.randomUUID()
来源：http://dali.hammf.cn/Article/details/gtpklovxbo.html

Java: UUID.randomUUID().toString()
来源：http://dali.shuidangran.top/Article/details/gtyeclivsk.html

Go:   // 用 github.com/google/uuid
来源：http://dali.ppjwa.cn/Article/details/gtamwkgnpe.html

Ruby: SecureRandom.uuid
来源：http://dali.xuanzx.com/Article/details/gtzzvxseyh.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.yvedp.cn/Article/details/gtoueibiye.html

[P02] MD5 / SHA256 摘要
来源：http://dali.cqqwz.cn/Article/details/gtcakyxuqc.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.dashuyun.cn/Article/details/gtkarzjabv.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.bjfxy.top/Article/details/gtpogrclra.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.birdmap.top/Article/details/gtpcvdfqtj.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.fengsongda.top/Article/details/gtdogjcdav.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhengqikj.top/Article/details/gtfbygpuua.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.tianlin.xyz/Article/details/gtedzcmxnv.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.316326.xyz/Article/details/gtokrxhxkf.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.nanxuanxn.top/Article/details/gtgmpvyszu.html

[P03] 生成短随机字符串
来源：http://dali.guannengcc.top/Article/details/gtunpybfve.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwshnpksm.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.pengpengdd.cyou/Article/details/gtketuysvd.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.shzxlz.cn/Article/details/gtuubnnylu.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.shangyingyoupin.top/Article/details/gthlrktklr.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhongyouzk.top/Article/details/gtgvwgrcly.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.gzhubu.top/Article/details/gtzgqyfoeo.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.nwbrower.top/Article/details/gtmevewizc.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.ydzc1.top/Article/details/gtwgnrswfd.html

[P04] 求长度
来源：http://dali.daria6918.cn/Article/details/gtexinyoqp.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.xziqi.cn/Article/details/gtmzgxpjdd.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.haohaochexian.top/Article/details/gtmfefhitv.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.smart0.xyz/Article/details/gtuavgfdyy.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jinqigufen.top/Article/details/gthrcuygct.html

Java: list.size();  map.size();  s.length()
来源：http://dali.jqgufenzy.top/Article/details/gtlaurqeym.html

Go:   len(arr);  len(m)
来源：http://dali.yuxming.cn/Article/details/gtsgxwtexo.html

Ruby: x.length;  x.size
来源：http://dali.dashuyun.cn/Article/details/gtlefteinx.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.jqgufenzy.top/Article/details/gtqfhcpfyi.html

[P05] 判断两个对象内容是否相等
来源：http://dali.cdnleiting.top/Article/details/gtovwwhsok.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.jinqigufen.top/Article/details/gteuzmtrrc.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.nwbrower.top/Article/details/gtjrgfqrrh.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.yvedp.cn/Article/details/gtmsbxwnje.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.ehwqpu.com/Article/details/gtfhkfafyq.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.guannengcc.top/Article/details/gtdoujfmkm.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.shangyingyoupin.top/Article/details/gtkoclthad.html

Ruby: a == b
来源：http://dali.shzxlz.cn/Article/details/gtrhjcxotp.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.feifeiyinyue.top/Article/details/gtzohgyoem.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.shuidangran.top/Article/details/gtrbbhihbn.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.quarkkingdee.top/Article/details/gtbxikqmdo.html

PHP:  if (empty($x)) {}
来源：http://dali.gaohongyu789.top/Article/details/gtcltzdwpn.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.cashguo.top/Article/details/gtztyfansb.html

TS:   if (x == null) {}
来源：http://dali.aizwys.cn/Article/details/gtybusrhmf.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.xylfe.cn/Article/details/gtvauwmuwn.html

Go:   if x == nil {}
来源：http://dali.cashguo.top/Article/details/gtjaalmhhu.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.jinqigfzy.top/Article/details/gtehvhttdh.html

C#:   if (x is null) {}
来源：http://dali.dashuyun.cn/Article/details/gtscdxfwie.html

[P07] 防抖与节流
来源：http://dali.xziqi.cn/Article/details/gtjilardns.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.haohaochexian.top/Article/details/gtkknsaegc.html

PHP:  // 手写时间戳比较
来源：http://dali.andypj.xyz/Article/details/gtmasvvhnm.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.ivvv.top/Article/details/gtvjjdoxln.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.pengpengdd.cyou/Article/details/gtzwgimssl.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.chenlongwang.top/Article/details/gtbblxvfkr.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.guowangkeji.top/Article/details/gtujgaoyzj.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.chenlongwang.top/Article/details/gtawonqvre.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.daxiang520.top/Article/details/gtjzdsdhdq.html

[P08] 处理浮点精度问题
来源：http://dali.yanxiufei.cn/Article/details/gttvcwfkdm.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.sufxvd.cn/Article/details/gtbxwonuid.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.jinqigufen.top/Article/details/gtizgvdgej.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zycfv.cn/Article/details/gthbdjbldr.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.jinqigfzy.top/Article/details/gtocmtfitl.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.quarkkingdee.top/Article/details/gtxpnunmcw.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.wangdashe.top/Article/details/gthaxnhvwr.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gtwzjsqswt.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.jinqigfzy.top/Article/details/gtpkyempoj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtcmhqbzso.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.shanyushiyangtech.top/Article/details/gtguzrtuil.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtujuinkni.html

[Q01] 创建表
来源：http://dali.zhengqikj.top/Article/details/gtkgyqfiha.html

CREATE TABLE users (
来源：http://dali.cucudq.cn/Article/details/gtmiecxrqr.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.chenjidiqi.icu/Article/details/gtlmouhxsr.html

name VARCHAR(50) NOT NULL,
来源：http://dali.hfpthk.cn/Article/details/gtmvrdnepm.html

email VARCHAR(100) UNIQUE,
来源：http://dali.tian-w.cn/Article/details/gtnoziciau.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.smart0.xyz/Article/details/gtgxpxdnnb.html

);
来源：http://dali.zhengqikj.top/Article/details/gtdpeokcgo.html

[Q02] 创建带外键的表
来源：http://dali.jinqigufen.top/Article/details/gtoxwlkcnm.html

CREATE TABLE orders (
来源：http://dali.gogol.net.cn/Article/details/gtepstsmsv.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.dianchejie.cn/Article/details/gtcyflidvz.html

user_id INT NOT NULL,
来源：http://dali.yangfankeji.com/Article/details/gtxpyzlnxi.html

amount DECIMAL(10, 2),
来源：http://dali.svipenyu.cn/Article/details/gtobjxqbwg.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.mhx1999.top/Article/details/gtuyhtgzyn.html

);
来源：http://dali.tanke756.top/Article/details/gtzlynmhwy.html

[Q03] 增加列
来源：http://dali.quarkkingdee.top/Article/details/gtriejdbyt.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.wangdashe.top/Article/details/gtwgdqvyge.html

[Q04] 修改列类型
来源：http://dali.ppjwa.cn/Article/details/gtxqxaihvr.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.gzhubu.top/Article/details/gtycljumwr.html

[Q05] 重命名列
来源：http://dali.nwbrower.top/Article/details/gtliplghcm.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.nwbrower.top/Article/details/gtnmczykdl.html

[Q06] 删除列
来源：http://dali.jyoumei.cn/Article/details/gtymcrpubs.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.yj202588.top/Article/details/gtgeiotvft.html

[Q07] 删除表
来源：http://dali.316326.xyz/Article/details/gtanffgpuw.html

DROP TABLE IF EXISTS orders;
来源：http://dali.jqgfzy.top/Article/details/gteizmknha.html

[Q08] 创建普通索引
来源：http://dali.jinghuilouyu.cn/Article/details/gtmyryyqrr.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.redwolf501.top/Article/details/gtxiqttzoc.html

[Q09] 创建唯一索引
来源：http://dali.jinghuilouyu.cn/Article/details/gtnbucqndv.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhixingplan.top/Article/details/gtxbaxocdd.html

[Q10] 插入单行
来源：http://dali.sysykeji.top/Article/details/gtmytkrhbs.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.jiagoushi.top/Article/details/gtwdbprgxp.html

[Q11] 一次插入多行
来源：http://dali.ybcxt.top/Article/details/gtvmbkwpoq.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.shzxlz.cn/Article/details/gtxcuiiftw.html

[Q12] 插入后取自增 ID
来源：http://dali.zhixingplan.top/Article/details/gtrswrwubs.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.cashguo.top/Article/details/gtnpdjwftu.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.zhiwuduotai.top/Article/details/gtheriltlv.html

[Q13] 忽略重复插入
来源：http://dali.nanxinkj.top/Article/details/gtmoueqhxj.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.yonumen.top/Article/details/gtjaoegnoo.html

[Q14] 存在则更新（upsert）
来源：http://dali.xinyue.icu/Article/details/gtztspkxzh.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.hysaishi.cn/Article/details/gtaahbhkdm.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.quarkkingdee.top/Article/details/gtjztknvyb.html

[Q15] 查询全部
来源：http://dali.sufxvd.cn/Article/details/gtraegiist.html

SELECT * FROM users;
来源：http://dali.zycfv.cn/Article/details/gtdyddhmaw.html

[Q16] 查询指定列
来源：http://dali.fzhhl.top/Article/details/gteifgvyoz.html

SELECT id, name FROM users;
来源：http://dali.zdqjudy.top/Article/details/gtyylgbkna.html

[Q17] 条件查询
来源：http://dali.sxryk.cn/Article/details/gtxbzjpynz.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.ybcxt.top/Article/details/gtauhdpyhr.html

[Q18] 模糊匹配
来源：http://dali.wangdashe.top/Article/details/gtyycilmbn.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhengqikj.top/Article/details/gtluckzkaw.html

[Q19] 范围查询
来源：http://dali.sweek.top/Article/details/gtvjwqeeiv.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.aizwys.cn/Article/details/gtfgtajtnl.html

[Q20] IN 列表
来源：http://dali.meibo888.top/Article/details/gtasmhlvzv.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.nanxuanxn.top/Article/details/gtpboplasv.html

[Q21] 空值判断
来源：http://dali.xinyue.icu/Article/details/gtgjxjjlub.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.jinghuilouyu.cn/Article/details/gtuekwaysa.html

[Q22] 排序
来源：http://dali.chenzaomai.com/Article/details/gtsmjpoapq.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.fengsongda.top/Article/details/gtdcyvrdvr.html

[Q23] 分页
来源：http://dali.jqgfzy.top/Article/details/gtwczoiync.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.xinyue.icu/Article/details/gtarqkozda.html

[Q24] 去重
来源：http://dali.shuidangran.top/Article/details/gtnzmkuedf.html

SELECT DISTINCT city FROM users;
来源：http://dali.tanke756.top/Article/details/gtwujbcjfn.html

[Q25] 只取前 N 条
来源：http://dali.nwbrower.top/Article/details/gtjguefrhz.html


<!-- 参考信息 -->