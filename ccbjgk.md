代发 wailian999

[N01] 二分查找（有序数组）
来源：http://dali.yongpay.top/Article/details/gtidvrketn.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.havefunace.top/Article/details/gtlqhqqyze.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gtnhzuyimr.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.gogol.net.cn/Article/details/gtwilarnsm.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.tian-w.cn/Article/details/gtilrginpz.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.kuanghao11.cn/Article/details/gtswqeugyk.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.316326.xyz/Article/details/gtxogicwhr.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.nanxinkj.top/Article/details/gtdtnkrwip.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.c1oappe.top/Article/details/gtxpdhsozr.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.hysaishi.cn/Article/details/gtrruxjobp.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.svipenyu.cn/Article/details/gtlaggwuzk.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.hywenlv.cn/Article/details/gtojpokwqb.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.haohaochexian.top/Article/details/gtaygorsgh.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jyoumei.cn/Article/details/gtlpchyrxt.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.jinqigufen.top/Article/details/gtfzkjkjwx.html

Go:   slices.Sort(arr)
来源：http://dali.zhixingplan.top/Article/details/gtxhkulkcp.html

Ruby: arr.sort
来源：http://dali.andypj.xyz/Article/details/gtpidwvsnf.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.iojbl.cn/Article/details/gtfgygivox.html

[N03] 快速排序（分治示例）
来源：http://dali.hnqzz.top/Article/details/gtbycptywb.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.cashguo.top/Article/details/gtjbuetnat.html

PHP:  // 递归实现，或用 usort
来源：http://dali.ivvv.top/Article/details/gtceoynrvt.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yj20258888.top/Article/details/gtbzgiraku.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.sysykeji.top/Article/details/gtnhsxolod.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.yj202588.top/Article/details/gtmcvtfbiz.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.yongpay.top/Article/details/gtwyxtcsxy.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.jyoumei.cn/Article/details/gtadwflvse.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.yongpay.top/Article/details/gthzwhsfjc.html

[N04] 斐波那契数列
来源：http://dali.iojbl.cn/Article/details/gtqkjchpzb.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.gaohongyu789.top/Article/details/gtgtqfdfyj.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttnmpesbu.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.gogol.net.cn/Article/details/gtccyvjusz.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yj20258888.top/Article/details/gthvofftoi.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.wangshuangyany.cn/Article/details/gtmzhhtwwo.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.wangdashe.top/Article/details/gtijtfriqf.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.xylfe.cn/Article/details/gttgjawymc.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.iojbl.cn/Article/details/gtbxwgnwqn.html

[N05] 最大公约数
来源：http://dali.ppjwa.cn/Article/details/gtvnzyawzq.html

Py:   math.gcd(a, b)
来源：http://dali.wangshuangyany.cn/Article/details/gtxihvtvac.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.haohaochexian.top/Article/details/gtbpzjqram.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhoulong.xyz/Article/details/gtorhxkxxn.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtkuibmczd.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.gotoacloud.top/Article/details/gttzcxgnhd.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.mhx1999.top/Article/details/gtrkppfmxl.html

Ruby: a.gcd(b)
来源：http://dali.ybcxt.top/Article/details/gtccucqqso.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.jqgufenzy.top/Article/details/gtfyihrkgk.html

[N06] 判断回文字符串
来源：http://dali.cucudq.cn/Article/details/gtcthztbyf.html

Py:   s == s[::-1]
来源：http://dali.0kj1m.cn/Article/details/gtumdqdcdw.html

PHP:  $s === strrev($s);
来源：http://dali.hammf.cn/Article/details/gttsjomovp.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhengqikj.top/Article/details/gtdmqbxmao.html

TS:   s === [...s].reverse().join("")
来源：http://dali.xylfe.cn/Article/details/gtdmrxmnmo.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.hfpthk.cn/Article/details/gtehhlqony.html

Go:   // 双指针从两端比较
来源：http://dali.jinqigfzy.top/Article/details/gtsilrkdzk.html

Ruby: s == s.reverse
来源：http://dali.nanxuanxn.top/Article/details/gtmpfkcoqt.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.pengpengdd.cyou/Article/details/gtydoudnjm.html

[N07] 两数之和（返回下标）
来源：http://dali.c1oappe.top/Article/details/gteejdrvtg.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.jinqigufen.top/Article/details/gtawmhzkvf.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.xuetiantiany.cn/Article/details/gtdcerqbgu.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.yj202588.top/Article/details/gtkcpsbfsf.html

TS:   // 手写 Map<string, number>
来源：http://dali.cucudq.cn/Article/details/gtyruntfnp.html

Java: // 手写 HashMap
来源：http://dali.sufxvd.cn/Article/details/gtlwsgckub.html

Go:   // 手写 map[int]int
来源：http://dali.316326.xyz/Article/details/gtatuykdfx.html

Ruby: // 手写 Hash
来源：http://dali.0kj1m.cn/Article/details/gtgvgblflg.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.cheryme.top/Article/details/gtoeevvxsf.html

[N08] 生成全排列
来源：http://dali.xuanzx.com/Article/details/gtiaedarqf.html

Py:   itertools.permutations(arr)
来源：http://dali.ppjwa.cn/Article/details/gtytifzsms.html

PHP:  // 手写递归交换
来源：http://dali.yonumen.top/Article/details/gtwauvlrom.html

JS:   // 手写回溯递归
来源：http://dali.9152youxi.cn/Article/details/gtcvbjakkk.html

TS:   // 手写回溯递归
来源：http://dali.mhx1999.top/Article/details/gtzjinjywv.html

Java: // 手写回溯递归
来源：http://dali.dashuyun.cn/Article/details/gtaruchvbr.html

Go:   // 手写回溯递归
来源：http://dali.zhiwuduotai.top/Article/details/gtrvtkbyiz.html

Ruby: arr.permutation.to_a
来源：http://dali.cqqwz.cn/Article/details/gtyauutmgl.html

C#:   // 手写回溯递归
来源：http://dali.iojbl.cn/Article/details/gtlfjpigso.html

[N09] 栈与队列
来源：http://dali.jqgufenzy.top/Article/details/gtnbzrwtvw.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.ybcxt.top/Article/details/gtfdguluox.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.jinghuilouyu.cn/Article/details/gtvlpbtplg.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.9152youxi.cn/Article/details/gtzabnnjpe.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.cashguo.top/Article/details/gtivncopjl.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.jinqigfzy.top/Article/details/gtoygvpbsg.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.jiagoushi.top/Article/details/gtbmovifvx.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.havefunace.top/Article/details/gtbxabisih.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.tanke756.top/Article/details/gtnlftcykt.html

[N10] 链表节点定义
来源：http://dali.shangyingyoupin.top/Article/details/gtlzycppxd.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.snrcjt.cn/Article/details/gtaagzhbvt.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.cdnleiting.top/Article/details/gtijagdgav.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.sysykeji.top/Article/details/gtngbgqddu.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.guannengcc.top/Article/details/gtyzrlrxvn.html

Java: class Node { int v; Node next; }
来源：http://dali.wangshuangyany.cn/Article/details/gtblsnmcss.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.ivvv.top/Article/details/gthscplliy.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.cashguo.top/Article/details/gtwzevttee.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.fengsongda.top/Article/details/gtjplfqxok.html

[N11] 二叉树中序遍历
来源：http://dali.ybcxt.top/Article/details/gtdpzrifak.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhixingplan.top/Article/details/gtzskkhkoj.html

PHP:  // 手写递归函数
来源：http://dali.yvedp.cn/Article/details/gtjkywcerm.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jinqigfzy.top/Article/details/gtotvyocyj.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.ybcxt.top/Article/details/gtsiyvtohd.html

Java: // 手写递归
来源：http://dali.9152youxi.cn/Article/details/gtncqgrtlz.html

Go:   // 手写递归
来源：http://dali.fzhhl.top/Article/details/gtpqvygado.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.svipenyu.cn/Article/details/gtkkqytwju.html

C#:   // 手写递归
来源：http://dali.zhengqikj.top/Article/details/gtxgijcejo.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zdqjudy.top/Article/details/gtgpadkxbh.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.jyoumei.cn/Article/details/gtmkfvvjzl.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.xylfe.cn/Article/details/gtdxsxylvu.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.dashuyun.cn/Article/details/gtaltptgyf.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.shuidangran.top/Article/details/gtrjsaxjuy.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jqgufenzy.top/Article/details/gthkybdkia.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhiwuduotai.top/Article/details/gtpvpnotiq.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.snrcjt.cn/Article/details/gtwsxzgmbw.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhongyouzk.top/Article/details/gtadeiucjy.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtvwcmgatf.html

O. 并发与异步
来源：http://dali.316326.xyz/Article/details/gtephygfda.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtsygcfmoe.html

[O01] 启动一个线程
来源：http://dali.jinyuanbaomall.cn/Article/details/gteectduej.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.shanyushiyangtech.top/Article/details/gtwlpycqyr.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.aibaodan.cn/Article/details/gtjdenccsb.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhengqikj.top/Article/details/gtmfdglall.html

TS:   // 同 JS
来源：http://dali.jianghu66.top/Article/details/gtblgmlllt.html

Java: new Thread(() -> f()).start()
来源：http://dali.0kj1m.cn/Article/details/gttlpttfyf.html

Go:   go f()
来源：http://dali.redwolf501.top/Article/details/gtoowgmguu.html

Ruby: Thread.new { f }
来源：http://dali.yanxiufei.cn/Article/details/gtjuxhmxcg.html

C#:   Task.Run(() => F());
来源：http://dali.zdqjudy.top/Article/details/gtegthgkez.html

[O02] 使用线程池
来源：http://dali.hongshengwenyu.top/Article/details/gtibaknbze.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.vqdsnc.cn/Article/details/gtoqlcrwau.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.jinqigufen.top/Article/details/gtjxtmjjxd.html

JS:   // worker_threads 线程池
来源：http://dali.hysaishi.cn/Article/details/gtmrabsjpv.html

TS:   // worker_threads 线程池
来源：http://dali.zhiwuduotai.top/Article/details/gttibfclee.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.jyoumei.cn/Article/details/gtdqofrrtt.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.daria6918.cn/Article/details/gtsctvdyou.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.sufxvd.cn/Article/details/gttudeojpi.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhengqikj.top/Article/details/gtsujiyyyx.html

[O03] 加锁保护共享数据
来源：http://dali.9152youxi.cn/Article/details/gtklalruic.html

Py:   with lock: shared += 1
来源：http://dali.hammf.cn/Article/details/gtnkupqdie.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.nanxinkj.top/Article/details/gtnbazizbx.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.cqqwz.cn/Article/details/gtyoxeqiot.html

TS:   // 同 JS
来源：http://dali.zhengqikj.top/Article/details/gttsvrmnjd.html

Java: synchronized (this) { shared++; }
来源：http://dali.shzxlz.cn/Article/details/gttctisxsb.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhongyouzk.top/Article/details/gtzoxcioal.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzpwozvre.html

C#:   lock (gate) { shared++; }
来源：http://dali.ydzc1.top/Article/details/gtmqngkwja.html

[O04] 定义异步函数并等待
来源：http://dali.shuidangran.top/Article/details/gtsjvkgdwu.html

Py:   async def f():⏎    await g()
来源：http://dali.zhongyouzk.top/Article/details/gtiwlhibvs.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.pengpengdd.cyou/Article/details/gtkjcukzep.html

JS:   async function f() { await g(); }
来源：http://dali.meibo888.top/Article/details/gtwxjwmvap.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.9152youxi.cn/Article/details/gtiuxtjlsq.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.316326.xyz/Article/details/gtvrckrpmp.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.ehwqpu.com/Article/details/gtjkieewgh.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.daxiang520.top/Article/details/gtktxeimvm.html

C#:   async Task F() { await G(); }
来源：http://dali.cdnleiting.top/Article/details/gtzyxkrsmt.html

[O05] 并发执行并等待全部完成
来源：http://dali.yj20258888.top/Article/details/gtfgqebjhx.html

Py:   asyncio.gather(*tasks)
来源：http://dali.fzhhl.top/Article/details/gtzortsrwv.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.yuxming.cn/Article/details/gtjkncalcz.html

JS:   await Promise.all(tasks)
来源：http://dali.nanxuanxn.top/Article/details/gtanuraylc.html

TS:   await Promise.all(tasks)
来源：http://dali.ppjwa.cn/Article/details/gtqavealbf.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.gaohongyu789.top/Article/details/gtopimqllk.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.cqqwz.cn/Article/details/gtvjsuwmod.html

Ruby: threads.map(&:join)
来源：http://dali.jqgufenzy.top/Article/details/gtpjrotvzo.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.snrcjt.cn/Article/details/gtokxyaunp.html

[O06] 使用进程池
来源：http://dali.zhiwuduotai.top/Article/details/gtmhnaqibp.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.ivvv.top/Article/details/gtehxneeqy.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.cdnleiting.top/Article/details/gtpxcxquma.html

JS:   // child_process / cluster 模块
来源：http://dali.mhx1999.top/Article/details/gtlhstalwg.html

TS:   // child_process / cluster 模块
来源：http://dali.pengpengdd.cyou/Article/details/gtkcztrefd.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.shanyushiyangtech.top/Article/details/gtgtkdoxcj.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.yonumen.top/Article/details/gtmrhmjrzu.html

Ruby: // fork 块
来源：http://dali.daria6918.cn/Article/details/gtpkznplbj.html

C#:   Parallel.For
来源：http://dali.zhongyouzk.top/Article/details/gtnddbrlde.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtbfvcrlsb.html

P. 常用工具函数
来源：http://dali.ywan-chungtsiang.top/Article/details/gttmeprehe.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpwelbatj.html

[P01] 生成 UUID
来源：http://dali.zhengqikj.top/Article/details/gtlxqzdflj.html

Py:   str(uuid.uuid4())
来源：http://dali.hysaishi.cn/Article/details/gtwozdnfhn.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zycfv.cn/Article/details/gtxykonwfy.html

JS:   crypto.randomUUID()
来源：http://dali.316326.xyz/Article/details/gtemkvkzlf.html

TS:   crypto.randomUUID()
来源：http://dali.c1oappe.top/Article/details/gtntuwusag.html

Java: UUID.randomUUID().toString()
来源：http://dali.guannengcc.top/Article/details/gteoijhzyy.html

Go:   // 用 github.com/google/uuid
来源：http://dali.tian-w.cn/Article/details/gtinoxypnt.html

Ruby: SecureRandom.uuid
来源：http://dali.hnqzz.top/Article/details/gtucfxbiqs.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.ppjwa.cn/Article/details/gthkdcwuxy.html

[P02] MD5 / SHA256 摘要
来源：http://dali.cashguo.top/Article/details/gtjzygwpbi.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.jinqigfzy.top/Article/details/gtawunyzse.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.chenjidiqi.icu/Article/details/gthwbfzuoc.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.bjfxy.top/Article/details/gtknbgoxai.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.dianchejie.cn/Article/details/gtnvqvbvai.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.hywenlv.cn/Article/details/gthqnjygtm.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.nanxuanxn.top/Article/details/gtlsiqaxfg.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zdqjudy.top/Article/details/gtnygbtxqt.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.jqgufenzy.top/Article/details/gtjaefzjos.html

[P03] 生成短随机字符串
来源：http://dali.yvedp.cn/Article/details/gtjdxnrylh.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.wangshuangyany.cn/Article/details/gtedlloekk.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.shzxlz.cn/Article/details/gtkiecxala.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gtbyouilpz.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.aibaodan.cn/Article/details/gtanjvdhww.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.gogol.net.cn/Article/details/gtxheqjjxn.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.mhx1999.top/Article/details/gtasfkbbyo.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.fzhhl.top/Article/details/gtrtvgzlee.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.yuanzhike.top/Article/details/gtcxfijraa.html

[P04] 求长度
来源：http://dali.mhx1999.top/Article/details/gtripyfqzw.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.tianlin.xyz/Article/details/gttwtzbtjt.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.wangshuangyany.cn/Article/details/gtqkvlnxid.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.xuanzx.com/Article/details/gteqxkuyyc.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.cheryme.top/Article/details/gtukgdsfeh.html

Java: list.size();  map.size();  s.length()
来源：http://dali.jinqigufen.top/Article/details/gthbvaviwt.html

Go:   len(arr);  len(m)
来源：http://dali.daria6918.cn/Article/details/gtxvsltazn.html

Ruby: x.length;  x.size
来源：http://dali.cheryme.top/Article/details/gtqllttsgu.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.sxryk.cn/Article/details/gtyxgnrogk.html

[P05] 判断两个对象内容是否相等
来源：http://dali.havefunace.top/Article/details/gtaqambnjb.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.jinyuanbaomall.cn/Article/details/gteztvuanr.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.316326.xyz/Article/details/gtgfpuzviv.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.guowangkeji.top/Article/details/gtfpjyigxz.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.cqqwz.cn/Article/details/gtlfpkqvzd.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgkkqwjpu.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.andypj.xyz/Article/details/gtxefrykmg.html

Ruby: a == b
来源：http://dali.cdnleiting.top/Article/details/gtolklmfrh.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.hongshengwenyu.top/Article/details/gtgudqhpgx.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.chenlongwang.top/Article/details/gtndyfdlzr.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.guannengcc.top/Article/details/gtezzeldmw.html

PHP:  if (empty($x)) {}
来源：http://dali.jiagoushi.top/Article/details/gtbntoorqu.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvxnieoan.html

TS:   if (x == null) {}
来源：http://dali.jiagoushi.top/Article/details/gtwmkmczfx.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.sxryk.cn/Article/details/gtlgggkpvu.html

Go:   if x == nil {}
来源：http://dali.yangfankeji.com/Article/details/gtitfycuxu.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.xuanzx.com/Article/details/gtbbirvnme.html

C#:   if (x is null) {}
来源：http://dali.pycfn.com/Article/details/gthprszfcr.html

[P07] 防抖与节流
来源：http://dali.jyoumei.cn/Article/details/gtrjddjbjc.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zdqjudy.top/Article/details/gtuudhbmrl.html

PHP:  // 手写时间戳比较
来源：http://dali.hongshengwenyu.top/Article/details/gtokjsmlfa.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.shzxlz.cn/Article/details/gtfjiravan.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.nanxuanxn.top/Article/details/gtrqogievh.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhoulong.xyz/Article/details/gtugduiegm.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.tianlin.xyz/Article/details/gtqrezrsil.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.ydzc1.top/Article/details/gtpaymfrkc.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.jlsjyb.cn/Article/details/gtnvgfmxkp.html

[P08] 处理浮点精度问题
来源：http://dali.zycfv.cn/Article/details/gtdvwjwfqq.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.tanke756.top/Article/details/gtotbnfiye.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.hysaishi.cn/Article/details/gtsrrdsvdd.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.shuidangran.top/Article/details/gtnfcndtqk.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.hywenlv.cn/Article/details/gtpwrrzdwi.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.feifeiyinyue.top/Article/details/gtifmvfnol.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.vqdsnc.cn/Article/details/gtauesmhqe.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.chenzaomai.com/Article/details/gtpvmrsifz.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.cashguo.top/Article/details/gtbsumkiqg.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtjsuiybpc.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.xziqi.cn/Article/details/gtothipgxe.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtjtkkzsfj.html

[Q01] 创建表
来源：http://dali.guannengcc.top/Article/details/gtfgczmxkq.html

CREATE TABLE users (
来源：http://dali.redwolf501.top/Article/details/gtvepgtjsr.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jinqigfzy.top/Article/details/gtnyoaviwv.html

name VARCHAR(50) NOT NULL,
来源：http://dali.ybcxt.top/Article/details/gtaarknmfr.html

email VARCHAR(100) UNIQUE,
来源：http://dali.meibo888.top/Article/details/gtyttsjiec.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.0kj1m.cn/Article/details/gtleuwojae.html

);
来源：http://dali.gzhubu.top/Article/details/gtdgyohscc.html

[Q02] 创建带外键的表
来源：http://dali.kuanghao11.cn/Article/details/gtjyieeqey.html

CREATE TABLE orders (
来源：http://dali.cashguo.top/Article/details/gtdorvhbzn.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.chenlongwang.top/Article/details/gtnkvfzfzp.html

user_id INT NOT NULL,
来源：http://dali.nwbrower.top/Article/details/gtkewvlzzq.html

amount DECIMAL(10, 2),
来源：http://dali.wangdashe.top/Article/details/gtpmegulif.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.yongpay.top/Article/details/gtjuegircu.html

);
来源：http://dali.meibo888.top/Article/details/gtuycsrhqt.html

[Q03] 增加列
来源：http://dali.yonumen.top/Article/details/gtadquoasn.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.ehwqpu.com/Article/details/gtooexluag.html

[Q04] 修改列类型
来源：http://dali.xuetiantiany.cn/Article/details/gtrkfmvfxh.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.c1oappe.top/Article/details/gttabynega.html

[Q05] 重命名列
来源：http://dali.wangshuangyany.cn/Article/details/gtahxennpb.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.aizwys.cn/Article/details/gtvzmxfsbu.html

[Q06] 删除列
来源：http://dali.chenlongwang.top/Article/details/gtukflizid.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.ivvv.top/Article/details/gtcfcdhebq.html

[Q07] 删除表
来源：http://dali.shuidangran.top/Article/details/gtffaisjzc.html

DROP TABLE IF EXISTS orders;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgteikgax.html

[Q08] 创建普通索引
来源：http://dali.yvedp.cn/Article/details/gtufkckuom.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.hnxiangtu.top/Article/details/gthvqhchrz.html

[Q09] 创建唯一索引
来源：http://dali.tianlin.xyz/Article/details/gtgvwudorl.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.shuidangran.top/Article/details/gtbknfpffq.html

[Q10] 插入单行
来源：http://dali.jlsjyb.cn/Article/details/gtoagdonks.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvabbihzt.html

[Q11] 一次插入多行
来源：http://dali.ppjwa.cn/Article/details/gtljubsutd.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.ppjwa.cn/Article/details/gtnrobwhdj.html

[Q12] 插入后取自增 ID
来源：http://dali.hongshengwenyu.top/Article/details/gtxdbdogiv.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhengqikj.top/Article/details/gtobxrktqc.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.xinyue.icu/Article/details/gtiybnzgee.html

[Q13] 忽略重复插入
来源：http://dali.chenzaomai.com/Article/details/gtpnhcafwd.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.cheryme.top/Article/details/gtlckdfdvb.html

[Q14] 存在则更新（upsert）
来源：http://dali.hnqzz.top/Article/details/gthymxzpil.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.gzhubu.top/Article/details/gtccushodj.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.jqgfzy.top/Article/details/gtiaiuhmgw.html

[Q15] 查询全部
来源：http://dali.ppjwa.cn/Article/details/gtmewkreab.html

SELECT * FROM users;
来源：http://dali.smart0.xyz/Article/details/gtvqjiuuah.html

[Q16] 查询指定列
来源：http://dali.tianlin.xyz/Article/details/gtxfmhszvr.html

SELECT id, name FROM users;
来源：http://dali.dashuyun.cn/Article/details/gtjgkzhpbt.html

[Q17] 条件查询
来源：http://dali.yueranfly.top/Article/details/gtiwnuwtya.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.shuidangran.top/Article/details/gtuieenfyh.html

[Q18] 模糊匹配
来源：http://dali.zdqjudy.top/Article/details/gtqdezicfn.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.jianghu66.top/Article/details/gtlqbjuejz.html

[Q19] 范围查询
来源：http://dali.fengsongda.top/Article/details/gtdctcfvne.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.jinqigufen.top/Article/details/gtcdltbzct.html

[Q20] IN 列表
来源：http://dali.haohaochexian.top/Article/details/gtyiqswhtx.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.yuxming.cn/Article/details/gtdilvismf.html

[Q21] 空值判断
来源：http://dali.feifeiyinyue.top/Article/details/gtgjgtcrsr.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.yuxming.cn/Article/details/gtesqyrmnv.html

[Q22] 排序
来源：http://dali.yvedp.cn/Article/details/gtkqvigudr.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhongyouzk.top/Article/details/gtskqbqbcf.html

[Q23] 分页
来源：http://dali.jiagoushi.top/Article/details/gtricnmqct.html


<!-- 参考信息 -->