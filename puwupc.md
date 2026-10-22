代发 wailian999

Ruby: arr.sort
来源：http://dali.daxiang520.top/Article/details/gt2whvovuww.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.tian-w.cn/Article/details/gt2blspolxi.html

[N03] 快速排序（分治示例）
来源：http://dali.wangshuangyany.cn/Article/details/gt2oujxelzy.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.316326.xyz/Article/details/gt2korcrjdl.html

PHP:  // 递归实现，或用 usort
来源：http://dali.wangshuangyany.cn/Article/details/gt2yixlnzdo.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jiagoushi.top/Article/details/gt2eomytjkc.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.hammf.cn/Article/details/gt2oxtzgefm.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.sufxvd.cn/Article/details/gt2parjotrl.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.hfpthk.cn/Article/details/gt2oexplbdw.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhoulong.xyz/Article/details/gt2qvvvzzao.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.fzhhl.top/Article/details/gt2eogtwtbb.html

[N04] 斐波那契数列
来源：http://dali.shuidangran.top/Article/details/gt2zzxaneth.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.andypj.xyz/Article/details/gt2mwzfkfkr.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2geotlbnb.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jqgufenzy.top/Article/details/gt2zyiusspf.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yanxiufei.cn/Article/details/gt2wklrmnmj.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.aizwys.cn/Article/details/gt2xsykbugg.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.cdnleiting.top/Article/details/gt2temtfgkq.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.sysykeji.top/Article/details/gt2dnqufwvh.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.jyoumei.cn/Article/details/gt2huxtxrck.html

[N05] 最大公约数
来源：http://dali.jianghu66.top/Article/details/gt2dcqxbjjs.html

Py:   math.gcd(a, b)
来源：http://dali.hfpthk.cn/Article/details/gt2vcddbeub.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wqnlayjl.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.vqdsnc.cn/Article/details/gt2deowemjh.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.daria6918.cn/Article/details/gt2rzovbtqu.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.jinqigufen.top/Article/details/gt2huasdptz.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.yvedp.cn/Article/details/gt2vlaquynz.html

Ruby: a.gcd(b)
来源：http://dali.wangdashe.top/Article/details/gt2qcllylkj.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.shzxlz.cn/Article/details/gt2btchwiiv.html

[N06] 判断回文字符串
来源：http://dali.zhongyouzk.top/Article/details/gt2hzfvrnoh.html

Py:   s == s[::-1]
来源：http://dali.haohaochexian.top/Article/details/gt2ckjkfrbp.html

PHP:  $s === strrev($s);
来源：http://dali.cdnleiting.top/Article/details/gt2zdozxuje.html

JS:   s === [...s].reverse().join("")
来源：http://dali.pengpengdd.cyou/Article/details/gt2ydsiptqk.html

TS:   s === [...s].reverse().join("")
来源：http://dali.jiagoushi.top/Article/details/gt2swllzavj.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhongyouzk.top/Article/details/gt2jwbdeqhv.html

Go:   // 双指针从两端比较
来源：http://dali.xziqi.cn/Article/details/gt2andecrrl.html

Ruby: s == s.reverse
来源：http://dali.gotoacloud.top/Article/details/gt2elynqzpa.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.wangdashe.top/Article/details/gt2hmbmuqjv.html

[N07] 两数之和（返回下标）
来源：http://dali.guannengcc.top/Article/details/gt2thrkyhnl.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.pengpengdd.cyou/Article/details/gt2kzrgcezn.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.mhx1999.top/Article/details/gt2hlpcubkb.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.yanxiufei.cn/Article/details/gt2sivgkukd.html

TS:   // 手写 Map<string, number>
来源：http://dali.9152youxi.cn/Article/details/gt2zhjistiz.html

Java: // 手写 HashMap
来源：http://dali.gaohongyu789.top/Article/details/gt2zqwzlykd.html

Go:   // 手写 map[int]int
来源：http://dali.haohaochexian.top/Article/details/gt2cyhirjjk.html

Ruby: // 手写 Hash
来源：http://dali.meibo888.top/Article/details/gt2tgvrlkvx.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.mhx1999.top/Article/details/gt2lrfrfypo.html

[N08] 生成全排列
来源：http://dali.kuanghao11.cn/Article/details/gt2bnhqmexm.html

Py:   itertools.permutations(arr)
来源：http://dali.fengsongda.top/Article/details/gt2dxsulamy.html

PHP:  // 手写递归交换
来源：http://dali.tianlin.xyz/Article/details/gt2fbzwfjmo.html

JS:   // 手写回溯递归
来源：http://dali.0kj1m.cn/Article/details/gt2gxkuctiq.html

TS:   // 手写回溯递归
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ikrbztdb.html

Java: // 手写回溯递归
来源：http://dali.wangdashe.top/Article/details/gt2kvaiewhs.html

Go:   // 手写回溯递归
来源：http://dali.feifeiyinyue.top/Article/details/gt2zcxiiysh.html

Ruby: arr.permutation.to_a
来源：http://dali.dianchejie.cn/Article/details/gt2txwdcygy.html

C#:   // 手写回溯递归
来源：http://dali.hongshengwenyu.top/Article/details/gt2cbjsaeyq.html

[N09] 栈与队列
来源：http://dali.cucudq.cn/Article/details/gt2rjlequsw.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.dianchejie.cn/Article/details/gt2mjmszjst.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.yj20258888.top/Article/details/gt2ddwwagrs.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.chenjidiqi.icu/Article/details/gt2vnjzligq.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.cqqwz.cn/Article/details/gt2wrsxjksh.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.jinqigufen.top/Article/details/gt2ckyucgmh.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.andypj.xyz/Article/details/gt2tskyociu.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zdqjudy.top/Article/details/gt2regehlsk.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.guannengcc.top/Article/details/gt2lseqrffl.html

[N10] 链表节点定义
来源：http://dali.xziqi.cn/Article/details/gt2jqsxexcp.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.yonumen.top/Article/details/gt2dkpfndjq.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.jiagoushi.top/Article/details/gt2blqbxwkf.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.yanxiufei.cn/Article/details/gt2sfymluku.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.yuxming.cn/Article/details/gt2bvocuqhj.html

Java: class Node { int v; Node next; }
来源：http://dali.gogol.net.cn/Article/details/gt2zajnxgij.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zycfv.cn/Article/details/gt2siwtnffv.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.xuanzx.com/Article/details/gt2bplvpxzk.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.ivvv.top/Article/details/gt2ljanxhnm.html

[N11] 二叉树中序遍历
来源：http://dali.iojbl.cn/Article/details/gt2blgygwge.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.yanxiufei.cn/Article/details/gt2xocgzjkd.html

PHP:  // 手写递归函数
来源：http://dali.hnxiangtu.top/Article/details/gt2sfpfncyy.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.hnqzz.top/Article/details/gt2owsglbej.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yuxming.cn/Article/details/gt2gavexrqo.html

Java: // 手写递归
来源：http://dali.yueranfly.top/Article/details/gt2qtibovon.html

Go:   // 手写递归
来源：http://dali.zhixingplan.top/Article/details/gt2smzvejxs.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.9152youxi.cn/Article/details/gt2lrkhdyeo.html

C#:   // 手写递归
来源：http://dali.zhengqikj.top/Article/details/gt2ojfbgzwg.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.yj20258.top/Article/details/gt2uufhcmcs.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.mhx1999.top/Article/details/gt2aouwuzmh.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.hongshengwenyu.top/Article/details/gt2rankjlle.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yuanzhike.top/Article/details/gt2byevtymv.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yuanzhike.top/Article/details/gt2gzhzgwwh.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.chenzaomai.com/Article/details/gt2xeofvjpn.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.ppjwa.cn/Article/details/gt2gkvzlpek.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.yongpay.top/Article/details/gt2szosrxtw.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.kuanghao11.cn/Article/details/gt2tgwmcpdc.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gt2lfzgseqz.html

O. 并发与异步
来源：http://dali.tian-w.cn/Article/details/gt2haulykky.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gt2xuirwfze.html

[O01] 启动一个线程
来源：http://dali.redwolf501.top/Article/details/gt2kciiaypo.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.gogol.net.cn/Article/details/gt2iwateakw.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.redwolf501.top/Article/details/gt2voqjncwm.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.tanke756.top/Article/details/gt2xnmrkdlb.html

TS:   // 同 JS
来源：http://dali.chenjidiqi.icu/Article/details/gt2xaarysgz.html

Java: new Thread(() -> f()).start()
来源：http://dali.xuanzx.com/Article/details/gt2tjoaztyx.html

Go:   go f()
来源：http://dali.yj20258888.top/Article/details/gt2gjqynult.html

Ruby: Thread.new { f }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2motsexdl.html

C#:   Task.Run(() => F());
来源：http://dali.zhiwuduotai.top/Article/details/gt2dmggihne.html

[O02] 使用线程池
来源：http://dali.redwolf501.top/Article/details/gt2ykmewscn.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhengqikj.top/Article/details/gt2wzyjkkpw.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.pengpengdd.cyou/Article/details/gt2gdmovjpe.html

JS:   // worker_threads 线程池
来源：http://dali.yueranfly.top/Article/details/gt2odxrkfoh.html

TS:   // worker_threads 线程池
来源：http://dali.jyoumei.cn/Article/details/gt2dpzctltn.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.smart0.xyz/Article/details/gt2vnzwosnb.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.smart0.xyz/Article/details/gt2dmelhzpz.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.pengpengdd.cyou/Article/details/gt2hilxnbsv.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.pengpengdd.cyou/Article/details/gt2sclxfjmw.html

[O03] 加锁保护共享数据
来源：http://dali.fengsongda.top/Article/details/gt2akaiyyfi.html

Py:   with lock: shared += 1
来源：http://dali.cheryme.top/Article/details/gt2dorpbwrj.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.yuanzhike.top/Article/details/gt2fsswhjuw.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.sufxvd.cn/Article/details/gt2pqccdieg.html

TS:   // 同 JS
来源：http://dali.kuanghao11.cn/Article/details/gt2scxaqtjw.html

Java: synchronized (this) { shared++; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2ibikmydp.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.chenzaomai.com/Article/details/gt2wchqlgoo.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.hnqzz.top/Article/details/gt2cygxzspm.html

C#:   lock (gate) { shared++; }
来源：http://dali.nanxuanxn.top/Article/details/gt2aehnniki.html

[O04] 定义异步函数并等待
来源：http://dali.316326.xyz/Article/details/gt2gazufswz.html

Py:   async def f():⏎    await g()
来源：http://dali.fengsongda.top/Article/details/gt2sqdzufaj.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.ivvv.top/Article/details/gt2oicgysqr.html

JS:   async function f() { await g(); }
来源：http://dali.jqgufenzy.top/Article/details/gt2dbllfncm.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.jqgfzy.top/Article/details/gt2marpoqmp.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ouxvlbyx.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.cheryme.top/Article/details/gt2tknrgpsj.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.ivvv.top/Article/details/gt2zalkbjej.html

C#:   async Task F() { await G(); }
来源：http://dali.jqgufenzy.top/Article/details/gt2wkbtqlfu.html

[O05] 并发执行并等待全部完成
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tnptsuov.html

Py:   asyncio.gather(*tasks)
来源：http://dali.xuanzx.com/Article/details/gt2felxouba.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.chenjidiqi.icu/Article/details/gt2cnijoayd.html

JS:   await Promise.all(tasks)
来源：http://dali.feifeiyinyue.top/Article/details/gt2oxbqtowe.html

TS:   await Promise.all(tasks)
来源：http://dali.yongpay.top/Article/details/gt2xugzieez.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.ybcxt.top/Article/details/gt2keisqhhe.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.fengsongda.top/Article/details/gt2hwxkwwns.html

Ruby: threads.map(&:join)
来源：http://dali.fzhhl.top/Article/details/gt2wdtrohmb.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.chenjidiqi.icu/Article/details/gt2hzgemqpb.html

[O06] 使用进程池
来源：http://dali.xylfe.cn/Article/details/gt2aqdxgvvw.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.birdmap.top/Article/details/gt2yworuazi.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.xziqi.cn/Article/details/gt2npzeinqf.html

JS:   // child_process / cluster 模块
来源：http://dali.cashguo.top/Article/details/gt2hcyupkqm.html

TS:   // child_process / cluster 模块
来源：http://dali.zhiwuduotai.top/Article/details/gt2lpssnlbb.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.9152youxi.cn/Article/details/gt2cvptxwmr.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.dashuyun.cn/Article/details/gt2dbpyvmvn.html

Ruby: // fork 块
来源：http://dali.zhongyouzk.top/Article/details/gt2bumkembx.html

C#:   Parallel.For
来源：http://dali.zhiwuduotai.top/Article/details/gt2jievolwq.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2fmfaginc.html

P. 常用工具函数
来源：http://dali.xinyue.icu/Article/details/gt2pzgyfvwb.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gt2gshvdtdp.html

[P01] 生成 UUID
来源：http://dali.cashguo.top/Article/details/gt2mnarveop.html

Py:   str(uuid.uuid4())
来源：http://dali.yj20258.top/Article/details/gt2ltwscgmr.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.yvedp.cn/Article/details/gt2qiklptwt.html

JS:   crypto.randomUUID()
来源：http://dali.svipenyu.cn/Article/details/gt2ypkcksvg.html

TS:   crypto.randomUUID()
来源：http://dali.gzhubu.top/Article/details/gt2retjfkco.html

Java: UUID.randomUUID().toString()
来源：http://dali.redwolf501.top/Article/details/gt2kwqhunfb.html

Go:   // 用 github.com/google/uuid
来源：http://dali.cashguo.top/Article/details/gt2kjxppjxl.html

Ruby: SecureRandom.uuid
来源：http://dali.snrcjt.cn/Article/details/gt2wegnibxf.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.hnqzz.top/Article/details/gt2tkpblcmo.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zycfv.cn/Article/details/gt2twqrvurf.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.jinqigufen.top/Article/details/gt2huwjzkij.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.yvedp.cn/Article/details/gt2lyugunip.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.yongpay.top/Article/details/gt2wxonisnj.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.smart0.xyz/Article/details/gt2sbuvdbew.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2akouklww.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2zwnxrxii.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.fengsongda.top/Article/details/gt2sjtmiurl.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.yanxiufei.cn/Article/details/gt2oufodsyh.html

[P03] 生成短随机字符串
来源：http://dali.chenjidiqi.icu/Article/details/gt2smrdwfnq.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.snrcjt.cn/Article/details/gt2xcfsniwq.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.c1oappe.top/Article/details/gt2frfiuuxt.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.shzxlz.cn/Article/details/gt2yxzudpph.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jqgfzy.top/Article/details/gt2wlvbrzbb.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.yueranfly.top/Article/details/gt2oprptife.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.jinqigfzy.top/Article/details/gt2sfowjbmp.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.jianghu66.top/Article/details/gt2qqygzfcy.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.cqqwz.cn/Article/details/gt2anfwzqbv.html

[P04] 求长度
来源：http://dali.meibo888.top/Article/details/gt2rnpcxeam.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.andypj.xyz/Article/details/gt2tbhcphxe.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jinqigufen.top/Article/details/gt2nmxfuvxe.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhengqikj.top/Article/details/gt2mmabugun.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.tanke756.top/Article/details/gt2xucgigrk.html

Java: list.size();  map.size();  s.length()
来源：http://dali.dianchejie.cn/Article/details/gt2ujxtnhrh.html

Go:   len(arr);  len(m)
来源：http://dali.xinyue.icu/Article/details/gt2lvmnerhc.html

Ruby: x.length;  x.size
来源：http://dali.gaohongyu789.top/Article/details/gt2spdaqkua.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.iojbl.cn/Article/details/gt2wlpillpz.html

[P05] 判断两个对象内容是否相等
来源：http://dali.wangshuangyany.cn/Article/details/gt2lcgbhymq.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.yj20258888.top/Article/details/gt2pdbiefjh.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.pycfn.com/Article/details/gt2szljqfyz.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.xuetiantiany.cn/Article/details/gt2fejrkxvc.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.gzhubu.top/Article/details/gt2udzlkuww.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.shangyingyoupin.top/Article/details/gt2ffbjeshy.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.tian-w.cn/Article/details/gt2kalojubx.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2itbdrobl.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.hammf.cn/Article/details/gt2eburpdhe.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.sysykeji.top/Article/details/gt2hjxkifqh.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.xziqi.cn/Article/details/gt2qvwwunxs.html

PHP:  if (empty($x)) {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2bvytwlwx.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.hywenlv.cn/Article/details/gt2dlxntmvg.html

TS:   if (x == null) {}
来源：http://dali.havefunace.top/Article/details/gt2mgnmhzrz.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.jqgfzy.top/Article/details/gt2zzjsuzob.html

Go:   if x == nil {}
来源：http://dali.fzhhl.top/Article/details/gt2tevwxwnt.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.hammf.cn/Article/details/gt2jcwxdymt.html

C#:   if (x is null) {}
来源：http://dali.andypj.xyz/Article/details/gt2hgvpiycv.html

[P07] 防抖与节流
来源：http://dali.yonumen.top/Article/details/gt2sndlplkk.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.yvedp.cn/Article/details/gt2moxhxlaq.html

PHP:  // 手写时间戳比较
来源：http://dali.fengsongda.top/Article/details/gt2gwlbcgrg.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.nanxinkj.top/Article/details/gt2qgduviae.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jianghu66.top/Article/details/gt2wgeemquu.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.andypj.xyz/Article/details/gt2cbdgsjha.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hhydfnwy.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.hnqzz.top/Article/details/gt2urikagsu.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2bdwtjown.html

[P08] 处理浮点精度问题
来源：http://dali.smart0.xyz/Article/details/gt2uobcxjou.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.hnxiangtu.top/Article/details/gt2rvmmnpnx.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ijfczpvh.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zycfv.cn/Article/details/gt2jhhymwow.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.yvedp.cn/Article/details/gt2xnfssqzx.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.jinqigfzy.top/Article/details/gt2nlbpxaju.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.hysaishi.cn/Article/details/gt2yajfajvp.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.yonumen.top/Article/details/gt2xgqogagj.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.feifeiyinyue.top/Article/details/gt2oayuwacn.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gt2qzxbkjzu.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.jqgfzy.top/Article/details/gt2opbmhcsr.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gt2feybsvcc.html

[Q01] 创建表
来源：http://dali.bjfxy.top/Article/details/gt2cqdnucpx.html

CREATE TABLE users (
来源：http://dali.pengpengdd.cyou/Article/details/gt2fhpbuoru.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.quarkkingdee.top/Article/details/gt2gbuiwaay.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhoulong.xyz/Article/details/gt2jmqfiqow.html

email VARCHAR(100) UNIQUE,
来源：http://dali.yuxming.cn/Article/details/gt2viouympf.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.xuanzx.com/Article/details/gt2rrqvkrbo.html

);
来源：http://dali.daria6918.cn/Article/details/gt2cxbaefai.html

[Q02] 创建带外键的表
来源：http://dali.xuetiantiany.cn/Article/details/gt2ejnwevsq.html

CREATE TABLE orders (
来源：http://dali.shzxlz.cn/Article/details/gt2saxmywej.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.9152youxi.cn/Article/details/gt2uqsivujq.html

user_id INT NOT NULL,
来源：http://dali.316326.xyz/Article/details/gt2bbsuhzzn.html

amount DECIMAL(10, 2),
来源：http://dali.snrcjt.cn/Article/details/gt2iipuumjl.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.andypj.xyz/Article/details/gt2bbpbrlza.html

);
来源：http://dali.dashuyun.cn/Article/details/gt2fzmjubvv.html

[Q03] 增加列
来源：http://dali.gaohongyu789.top/Article/details/gt2xhhidtnv.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.hfpthk.cn/Article/details/gt2rlgmvbni.html

[Q04] 修改列类型
来源：http://dali.cdnleiting.top/Article/details/gt2iiiqssuc.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.cucudq.cn/Article/details/gt2tmbggjjz.html

[Q05] 重命名列
来源：http://dali.havefunace.top/Article/details/gt2gbwhrrat.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.hnqzz.top/Article/details/gt2zkytsonh.html

[Q06] 删除列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jyjoxevu.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.cashguo.top/Article/details/gt2uelrqqab.html

[Q07] 删除表
来源：http://dali.xinyue.icu/Article/details/gt2zgpredxk.html

DROP TABLE IF EXISTS orders;
来源：http://dali.jqgfzy.top/Article/details/gt2qmhgddzm.html

[Q08] 创建普通索引
来源：http://dali.guannengcc.top/Article/details/gt2ptyqhwcd.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zdqjudy.top/Article/details/gt2dzlfbihm.html

[Q09] 创建唯一索引
来源：http://dali.hammf.cn/Article/details/gt2tzheefon.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.xylfe.cn/Article/details/gt2eemxoqgg.html

[Q10] 插入单行
来源：http://dali.tianlin.xyz/Article/details/gt2eqfqixnu.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhoulong.xyz/Article/details/gt2wollukqm.html

[Q11] 一次插入多行
来源：http://dali.svipenyu.cn/Article/details/gt2ppemdhnh.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.yongpay.top/Article/details/gt2bemouttn.html

[Q12] 插入后取自增 ID
来源：http://dali.jianghu66.top/Article/details/gt2fxobpczq.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ccoskzeb.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.aibaodan.cn/Article/details/gt2kqosqpvo.html

[Q13] 忽略重复插入
来源：http://dali.xuanzx.com/Article/details/gt2hybtdwhq.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.jyoumei.cn/Article/details/gt2cennnbbo.html

[Q14] 存在则更新（upsert）
来源：http://dali.zycfv.cn/Article/details/gt2afucmahf.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.yueranfly.top/Article/details/gt2wpnspdos.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhoulong.xyz/Article/details/gt2kzenenqw.html

[Q15] 查询全部
来源：http://dali.dashuyun.cn/Article/details/gt2qyegpccz.html

SELECT * FROM users;
来源：http://dali.ydzc1.top/Article/details/gt2tkkpyjwc.html

[Q16] 查询指定列
来源：http://dali.jinqigfzy.top/Article/details/gt2wbwcinpy.html

SELECT id, name FROM users;
来源：http://dali.guowangkeji.top/Article/details/gt2bnkitqco.html

[Q17] 条件查询
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qmrnsdmk.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.havefunace.top/Article/details/gt2kirppnfj.html

[Q18] 模糊匹配
来源：http://dali.cheryme.top/Article/details/gt2fplxxrqt.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.chenzaomai.com/Article/details/gt2fgihtkkw.html

[Q19] 范围查询
来源：http://dali.sxryk.cn/Article/details/gt2kytvdbut.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.gaohongyu789.top/Article/details/gt2irvwpvyl.html

[Q20] IN 列表
来源：http://dali.9152youxi.cn/Article/details/gt2umgyujmd.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.tanke756.top/Article/details/gt2enyfevwo.html

[Q21] 空值判断
来源：http://dali.gogol.net.cn/Article/details/gt2kbuynwui.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.xziqi.cn/Article/details/gt2dstcwuqy.html

[Q22] 排序
来源：http://dali.gzhubu.top/Article/details/gt2fpyzdjcy.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vqofculo.html

[Q23] 分页
来源：http://dali.yuxming.cn/Article/details/gt2yjhdczvk.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.fengsongda.top/Article/details/gt2cnagmfbc.html

[Q24] 去重
来源：http://dali.zhixingplan.top/Article/details/gt2mhaluqfe.html

SELECT DISTINCT city FROM users;
来源：http://dali.cqqwz.cn/Article/details/gt2nfphxven.html

[Q25] 只取前 N 条
来源：http://dali.hnxiangtu.top/Article/details/gt2tjfaqobx.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.sxryk.cn/Article/details/gt2jnutvvmi.html

[Q26] 计数
来源：http://dali.cqqwz.cn/Article/details/gt2bjhtlpsw.html

SELECT COUNT(*) FROM users;
来源：http://dali.chenjidiqi.icu/Article/details/gt2nvvglzxl.html

[Q27] 条件计数
来源：http://dali.cqqwz.cn/Article/details/gt2ualesewp.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.havefunace.top/Article/details/gt2aheojpye.html

[Q28] 求和与平均
来源：http://dali.xuetiantiany.cn/Article/details/gt2orvxwkxn.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.havefunace.top/Article/details/gt2ojnzpnwi.html

[Q29] 最大最小值
来源：http://dali.hfpthk.cn/Article/details/gt2cvmfkuhz.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.hongshengwenyu.top/Article/details/gt2gownfqml.html

[Q30] 分组统计
来源：http://dali.ydzc1.top/Article/details/gt2ipbkgybs.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.daxiang520.top/Article/details/gt2tmdqzbqt.html

[Q31] 分组后过滤
来源：http://dali.daxiang520.top/Article/details/gt2qvcquleh.html


<!-- 参考信息 -->