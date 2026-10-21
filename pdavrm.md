代发 wailian999

[N01] 二分查找（有序数组）
来源：http://dali.yj202588.top/Article/details/gtqjhqppez.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.316326.xyz/Article/details/gtrkoqkuoh.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.jinqigfzy.top/Article/details/gtdnadvhre.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhoulong.xyz/Article/details/gtfydbnswc.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.xinyue.icu/Article/details/gttfwxlhxl.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.smart0.xyz/Article/details/gtaxfjbvcz.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.xuetiantiany.cn/Article/details/gtmtsontil.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.xylfe.cn/Article/details/gttcmzpkik.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.snrcjt.cn/Article/details/gtbaxfbbch.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.yueranfly.top/Article/details/gtnrrfjfji.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.gzhubu.top/Article/details/gtzicuqbob.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.shangyingyoupin.top/Article/details/gtpdzeluxr.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.quarkkingdee.top/Article/details/gtcpsxdtdx.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.daxiang520.top/Article/details/gtchikfuzm.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.daxiang520.top/Article/details/gtulbmhqbk.html

Go:   slices.Sort(arr)
来源：http://dali.pycfn.com/Article/details/gtqvhxhyso.html

Ruby: arr.sort
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgpqyfpgg.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.hammf.cn/Article/details/gtfpwzrpqf.html

[N03] 快速排序（分治示例）
来源：http://dali.9152youxi.cn/Article/details/gtvcrfwqtp.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbydmixft.html

PHP:  // 递归实现，或用 usort
来源：http://dali.fzhhl.top/Article/details/gtlxamgdzo.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.9152youxi.cn/Article/details/gtwhnfyaxj.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.havefunace.top/Article/details/gtpyhmfwoa.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.cdnleiting.top/Article/details/gtfycqjboo.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.dashuyun.cn/Article/details/gtrlizbgpu.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.aibaodan.cn/Article/details/gtcgzlmeik.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.nanxinkj.top/Article/details/gtlerukuqp.html

[N04] 斐波那契数列
来源：http://dali.sxryk.cn/Article/details/gtbqnpxvvd.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhengqikj.top/Article/details/gtbjvhihlt.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.gzhubu.top/Article/details/gtiwwaxqbj.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.hnxiangtu.top/Article/details/gtfomppjbl.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.birdmap.top/Article/details/gtxjypaahz.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.havefunace.top/Article/details/gtsuyoreqj.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhiwuduotai.top/Article/details/gtvdcxrzjo.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.havefunace.top/Article/details/gtdgpxxxdi.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.cdnleiting.top/Article/details/gtxlmofazw.html

[N05] 最大公约数
来源：http://dali.yj202588.top/Article/details/gtvysgwhyd.html

Py:   math.gcd(a, b)
来源：http://dali.yj20258888.top/Article/details/gtojwkvdaw.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.chenjidiqi.icu/Article/details/gtjypwfglt.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.chenzaomai.com/Article/details/gtefiwmpem.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yj20258.top/Article/details/gtivgvfaqg.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.chenlongwang.top/Article/details/gtjtgahjov.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.jinghuilouyu.cn/Article/details/gthdpftigg.html

Ruby: a.gcd(b)
来源：http://dali.fengsongda.top/Article/details/gtdqlsyook.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.xziqi.cn/Article/details/gthmgxikrn.html

[N06] 判断回文字符串
来源：http://dali.ydzc1.top/Article/details/gtgzzfqbqy.html

Py:   s == s[::-1]
来源：http://dali.zhiwuduotai.top/Article/details/gtpuubtxxa.html

PHP:  $s === strrev($s);
来源：http://dali.cheryme.top/Article/details/gtwilwcizm.html

JS:   s === [...s].reverse().join("")
来源：http://dali.chenzaomai.com/Article/details/gtnjpolbzc.html

TS:   s === [...s].reverse().join("")
来源：http://dali.cucudq.cn/Article/details/gtsrglhyrz.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.snrcjt.cn/Article/details/gtchelwsws.html

Go:   // 双指针从两端比较
来源：http://dali.mhx1999.top/Article/details/gtsklgkffu.html

Ruby: s == s.reverse
来源：http://dali.cheryme.top/Article/details/gtnczdxeez.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.sweek.top/Article/details/gttpgthydv.html

[N07] 两数之和（返回下标）
来源：http://dali.cdnleiting.top/Article/details/gtuthtrkqj.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.hysaishi.cn/Article/details/gtkxnrvvdo.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.0kj1m.cn/Article/details/gtnwmzsobh.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.aizwys.cn/Article/details/gtbyatqyyt.html

TS:   // 手写 Map<string, number>
来源：http://dali.yuxming.cn/Article/details/gtqyciltxw.html

Java: // 手写 HashMap
来源：http://dali.chenjidiqi.icu/Article/details/gtheafiero.html

Go:   // 手写 map[int]int
来源：http://dali.dashuyun.cn/Article/details/gtsitnshdi.html

Ruby: // 手写 Hash
来源：http://dali.jinghuilouyu.cn/Article/details/gtsugrvhpr.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.svipenyu.cn/Article/details/gttwdivjoe.html

[N08] 生成全排列
来源：http://dali.pycfn.com/Article/details/gtaxmenfpu.html

Py:   itertools.permutations(arr)
来源：http://dali.iojbl.cn/Article/details/gtgnzperei.html

PHP:  // 手写递归交换
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsuvhfwsh.html

JS:   // 手写回溯递归
来源：http://dali.zhoulong.xyz/Article/details/gteqflcryw.html

TS:   // 手写回溯递归
来源：http://dali.sxryk.cn/Article/details/gtareuqqrb.html

Java: // 手写回溯递归
来源：http://dali.zhiwuduotai.top/Article/details/gtpecgwril.html

Go:   // 手写回溯递归
来源：http://dali.ehwqpu.com/Article/details/gtrqpcksdb.html

Ruby: arr.permutation.to_a
来源：http://dali.yuxming.cn/Article/details/gtrgyquodn.html

C#:   // 手写回溯递归
来源：http://dali.pengpengdd.cyou/Article/details/gtprpcmaxa.html

[N09] 栈与队列
来源：http://dali.quarkkingdee.top/Article/details/gtjbxcutyd.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.hywenlv.cn/Article/details/gtkoxfxjpk.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.birdmap.top/Article/details/gtzqdprvvn.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.yuxming.cn/Article/details/gttzhalkgg.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.meibo888.top/Article/details/gttucyaktj.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.sxryk.cn/Article/details/gtlbdaxvdp.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.jinqigfzy.top/Article/details/gtfhiksocn.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.ppjwa.cn/Article/details/gtybrvwsxr.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.pengpengdd.cyou/Article/details/gtjkvgqqvo.html

[N10] 链表节点定义
来源：http://dali.zhoulong.xyz/Article/details/gtohdskyuj.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.chenzaomai.com/Article/details/gtinwyyfdh.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.meibo888.top/Article/details/gtfbpifvlh.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.yj20258888.top/Article/details/gthkehsxdx.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhiwuduotai.top/Article/details/gtzavpdqxq.html

Java: class Node { int v; Node next; }
来源：http://dali.jiagoushi.top/Article/details/gtbmxgexww.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsxfyqrxa.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.tianlin.xyz/Article/details/gtdogubepv.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.cashguo.top/Article/details/gtosgfgxxn.html

[N11] 二叉树中序遍历
来源：http://dali.gaohongyu789.top/Article/details/gtzjrupyxg.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.mhx1999.top/Article/details/gtywrypalu.html

PHP:  // 手写递归函数
来源：http://dali.yonumen.top/Article/details/gtaxyvnnpj.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.tianlin.xyz/Article/details/gtetfdormk.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.shuidangran.top/Article/details/gtsrvlgqnn.html

Java: // 手写递归
来源：http://dali.vqdsnc.cn/Article/details/gtiehxgzrl.html

Go:   // 手写递归
来源：http://dali.jinqigufen.top/Article/details/gtzqmgikuz.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.ppjwa.cn/Article/details/gtrjaskqmf.html

C#:   // 手写递归
来源：http://dali.yuxming.cn/Article/details/gtuuujnhum.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.wangshuangyany.cn/Article/details/gthkxyfeqa.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.wangshuangyany.cn/Article/details/gtsxlcvyip.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zdqjudy.top/Article/details/gticqtrnth.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.cheryme.top/Article/details/gtfgfdhsxs.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.hongshengwenyu.top/Article/details/gtunqbwoat.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.svipenyu.cn/Article/details/gtxtqxtihk.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.9152youxi.cn/Article/details/gthbumqqqm.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.yj20258.top/Article/details/gtxfeukcye.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jyoumei.cn/Article/details/gtwxngkims.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsmvqhnmi.html

O. 并发与异步
来源：http://dali.jiagoushi.top/Article/details/gtopgrnovp.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtorvtubhq.html

[O01] 启动一个线程
来源：http://dali.vqdsnc.cn/Article/details/gtbugjkvtk.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.yueranfly.top/Article/details/gtamkelmhf.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.tanke756.top/Article/details/gtbfuruxoa.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.hongshengwenyu.top/Article/details/gtecnyybqu.html

TS:   // 同 JS
来源：http://dali.xylfe.cn/Article/details/gtdelvmgnm.html

Java: new Thread(() -> f()).start()
来源：http://dali.bjfxy.top/Article/details/gtigqyghxm.html

Go:   go f()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtslemobvn.html

Ruby: Thread.new { f }
来源：http://dali.fengsongda.top/Article/details/gtemmxgebh.html

C#:   Task.Run(() => F());
来源：http://dali.chenjidiqi.icu/Article/details/gtpelbmpjd.html

[O02] 使用线程池
来源：http://dali.gzhubu.top/Article/details/gtnhvjojhj.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.redwolf501.top/Article/details/gtayrmgwgk.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.yj20258.top/Article/details/gtgcurojxh.html

JS:   // worker_threads 线程池
来源：http://dali.zdqjudy.top/Article/details/gtatkdvgjq.html

TS:   // worker_threads 线程池
来源：http://dali.jyoumei.cn/Article/details/gtgngeoacz.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.fengsongda.top/Article/details/gtkumcbevt.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.mhx1999.top/Article/details/gteyrfxooj.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.yongpay.top/Article/details/gtwkphrqev.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.yvedp.cn/Article/details/gtxidhkfql.html

[O03] 加锁保护共享数据
来源：http://dali.yongpay.top/Article/details/gtsoxaczij.html

Py:   with lock: shared += 1
来源：http://dali.yangfankeji.com/Article/details/gtjjatgngb.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.cdnleiting.top/Article/details/gtarskhfgu.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zycfv.cn/Article/details/gtdrxsqaeu.html

TS:   // 同 JS
来源：http://dali.birdmap.top/Article/details/gtnlitjdje.html

Java: synchronized (this) { shared++; }
来源：http://dali.feifeiyinyue.top/Article/details/gtynsswthc.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.quarkkingdee.top/Article/details/gttjuxycmw.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.xuanzx.com/Article/details/gtitftujwn.html

C#:   lock (gate) { shared++; }
来源：http://dali.svipenyu.cn/Article/details/gtstxbwxhu.html

[O04] 定义异步函数并等待
来源：http://dali.hnqzz.top/Article/details/gtvezxjjfx.html

Py:   async def f():⏎    await g()
来源：http://dali.yuanzhike.top/Article/details/gtvphdestr.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.birdmap.top/Article/details/gtukhqqffb.html

JS:   async function f() { await g(); }
来源：http://dali.yongpay.top/Article/details/gtbcbcsmql.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.nanxuanxn.top/Article/details/gtvlsrrzwh.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.wangdashe.top/Article/details/gthhvzsixa.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.chenzaomai.com/Article/details/gtjaxkrnaf.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.yuanzhike.top/Article/details/gtqoqtiicr.html

C#:   async Task F() { await G(); }
来源：http://dali.shangyingyoupin.top/Article/details/gttvnfptrm.html

[O05] 并发执行并等待全部完成
来源：http://dali.birdmap.top/Article/details/gtfeqkzzzf.html

Py:   asyncio.gather(*tasks)
来源：http://dali.aibaodan.cn/Article/details/gtultktiqm.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.yj202588.top/Article/details/gtryuznwiv.html

JS:   await Promise.all(tasks)
来源：http://dali.tanke756.top/Article/details/gtotqxresb.html

TS:   await Promise.all(tasks)
来源：http://dali.jyoumei.cn/Article/details/gtzjdnizfn.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtilbakbbt.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.nanxinkj.top/Article/details/gtknijdyco.html

Ruby: threads.map(&:join)
来源：http://dali.xuanzx.com/Article/details/gtqnuflknt.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.yueranfly.top/Article/details/gtrxcurqeg.html

[O06] 使用进程池
来源：http://dali.zdqjudy.top/Article/details/gtxmwkibmy.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.ivvv.top/Article/details/gtmekyeyai.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.guannengcc.top/Article/details/gtwfiergtr.html

JS:   // child_process / cluster 模块
来源：http://dali.birdmap.top/Article/details/gtjcpgtwbz.html

TS:   // child_process / cluster 模块
来源：http://dali.daria6918.cn/Article/details/gtnursddmw.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.wangdashe.top/Article/details/gtcbyijpbt.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.gaohongyu789.top/Article/details/gtsjhpdysy.html

Ruby: // fork 块
来源：http://dali.jiagoushi.top/Article/details/gtmttkitbl.html

C#:   Parallel.For
来源：http://dali.ppjwa.cn/Article/details/gtlkxuteer.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtrdrlksff.html

P. 常用工具函数
来源：http://dali.zhoulong.xyz/Article/details/gtxrfodfzy.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtibuarjbk.html

[P01] 生成 UUID
来源：http://dali.jqgufenzy.top/Article/details/gtxivssxzj.html

Py:   str(uuid.uuid4())
来源：http://dali.yonumen.top/Article/details/gtaqjrbval.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.sysykeji.top/Article/details/gttgtbfbju.html

JS:   crypto.randomUUID()
来源：http://dali.316326.xyz/Article/details/gtrahpseiy.html

TS:   crypto.randomUUID()
来源：http://dali.nwbrower.top/Article/details/gtzthvquvv.html

Java: UUID.randomUUID().toString()
来源：http://dali.bjfxy.top/Article/details/gtijufabtk.html

Go:   // 用 github.com/google/uuid
来源：http://dali.pengpengdd.cyou/Article/details/gtzvizbzif.html

Ruby: SecureRandom.uuid
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxyxiazzi.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.jinghuilouyu.cn/Article/details/gtycvunsmq.html

[P02] MD5 / SHA256 摘要
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnesczzja.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.havefunace.top/Article/details/gtvsoxbiul.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.gzhubu.top/Article/details/gtkrgygcoy.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.yj202588.top/Article/details/gtuuxcnukz.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.tanke756.top/Article/details/gtbuknuqzp.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.ydzc1.top/Article/details/gteqsahklp.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.cheryme.top/Article/details/gtavudheje.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.sysykeji.top/Article/details/gtmfomfqfd.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.ywan-chungtsiang.top/Article/details/gteszpvktf.html

[P03] 生成短随机字符串
来源：http://dali.sweek.top/Article/details/gtuqvlqbld.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.vqdsnc.cn/Article/details/gtjifkdrdd.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.jiagoushi.top/Article/details/gttinobxgb.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.meibo888.top/Article/details/gtjgcocwbw.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.chenjidiqi.icu/Article/details/gtfjatpfqz.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.hammf.cn/Article/details/gtncstpckl.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.yongpay.top/Article/details/gthsyqbroz.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.ydzc1.top/Article/details/gtygxedvlg.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.wangdashe.top/Article/details/gtbdjxjarg.html

[P04] 求长度
来源：http://dali.tianlin.xyz/Article/details/gtjkwkkuqn.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.tian-w.cn/Article/details/gtjyjbxyda.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.cashguo.top/Article/details/gtspmpxphr.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.gaohongyu789.top/Article/details/gtavecmiqz.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jiagoushi.top/Article/details/gthshorahm.html

Java: list.size();  map.size();  s.length()
来源：http://dali.xylfe.cn/Article/details/gtwihbzuqx.html

Go:   len(arr);  len(m)
来源：http://dali.wangshuangyany.cn/Article/details/gtsgtppidh.html

Ruby: x.length;  x.size
来源：http://dali.yj20258888.top/Article/details/gtwwobxfbk.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.ivvv.top/Article/details/gthexissra.html

[P05] 判断两个对象内容是否相等
来源：http://dali.mhx1999.top/Article/details/gtupjjrcxd.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.redwolf501.top/Article/details/gtcmfzljog.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhongyouzk.top/Article/details/gtcwbvjkzz.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.nwbrower.top/Article/details/gtenyivzcj.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.shuidangran.top/Article/details/gtzogrhwnq.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.andypj.xyz/Article/details/gtqkipizvt.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.jinqigfzy.top/Article/details/gtvujykwcu.html

Ruby: a == b
来源：http://dali.havefunace.top/Article/details/gtksomtvtp.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.vqdsnc.cn/Article/details/gteqjhwsey.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.ydzc1.top/Article/details/gtwzbvrlaq.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.gzhubu.top/Article/details/gtwnaoexol.html

PHP:  if (empty($x)) {}
来源：http://dali.316326.xyz/Article/details/gtcwonovgk.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.sufxvd.cn/Article/details/gtndvspfgp.html

TS:   if (x == null) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtflagnzbf.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.jianghu66.top/Article/details/gtimgwzjwa.html

Go:   if x == nil {}
来源：http://dali.cashguo.top/Article/details/gtpnxncpvl.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.aibaodan.cn/Article/details/gtibpgudmp.html

C#:   if (x is null) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtqsxevmix.html

[P07] 防抖与节流
来源：http://dali.andypj.xyz/Article/details/gtrfovxbau.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.tianlin.xyz/Article/details/gtvtytdtla.html

PHP:  // 手写时间戳比较
来源：http://dali.yuanzhike.top/Article/details/gtbzqbzten.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.dashuyun.cn/Article/details/gtcrmgjudb.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.aizwys.cn/Article/details/gtohrvqapp.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.svipenyu.cn/Article/details/gtudmuggto.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqwfqlyva.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqhzfhuji.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.meibo888.top/Article/details/gtbicuoket.html

[P08] 处理浮点精度问题
来源：http://dali.quarkkingdee.top/Article/details/gtpbgywuye.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.9152youxi.cn/Article/details/gthldjevbx.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.dashuyun.cn/Article/details/gtpcxwtvjw.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.shangyingyoupin.top/Article/details/gthgnmvfmf.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.9152youxi.cn/Article/details/gtfvhlmjtw.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.shuidangran.top/Article/details/gtdnbfernl.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.shuidangran.top/Article/details/gtrgszdvwl.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.ehwqpu.com/Article/details/gtwnazykpk.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.jiagoushi.top/Article/details/gtenuekgpe.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtxkedjdlt.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.ybcxt.top/Article/details/gtpgsnfafl.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtabtcioxw.html

[Q01] 创建表
来源：http://dali.meibo888.top/Article/details/gtkmyozkfh.html

CREATE TABLE users (
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmwuprfva.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.pycfn.com/Article/details/gtggmxmhpw.html

name VARCHAR(50) NOT NULL,
来源：http://dali.xinyue.icu/Article/details/gtckqryeyo.html

email VARCHAR(100) UNIQUE,
来源：http://dali.havefunace.top/Article/details/gtrsqgqrwh.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.sxryk.cn/Article/details/gtwoeybzqk.html

);
来源：http://dali.fengsongda.top/Article/details/gthvahwwlz.html

[Q02] 创建带外键的表
来源：http://dali.zdqjudy.top/Article/details/gtvnllpcto.html

CREATE TABLE orders (
来源：http://dali.cdnleiting.top/Article/details/gtivuclpdr.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.xylfe.cn/Article/details/gterrtmawr.html

user_id INT NOT NULL,
来源：http://dali.c1oappe.top/Article/details/gtssocgrpp.html

amount DECIMAL(10, 2),
来源：http://dali.jyoumei.cn/Article/details/gtpetccexb.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.yj20258888.top/Article/details/gtotzrdyph.html

);
来源：http://dali.zhixingplan.top/Article/details/gtzblewgjy.html

[Q03] 增加列
来源：http://dali.zhengqikj.top/Article/details/gtrmakajex.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.hfpthk.cn/Article/details/gtgtmwylkl.html

[Q04] 修改列类型
来源：http://dali.aibaodan.cn/Article/details/gtyagdiesl.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.daxiang520.top/Article/details/gtnrzyobyl.html

[Q05] 重命名列
来源：http://dali.nanxuanxn.top/Article/details/gthuugigfj.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.cashguo.top/Article/details/gtrsnuetfc.html

[Q06] 删除列
来源：http://dali.aibaodan.cn/Article/details/gtmznmlebs.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.fzhhl.top/Article/details/gthnuoasgz.html

[Q07] 删除表
来源：http://dali.cheryme.top/Article/details/gtxhctpepv.html

DROP TABLE IF EXISTS orders;
来源：http://dali.jinqigufen.top/Article/details/gtvwlfwndf.html

[Q08] 创建普通索引
来源：http://dali.gzhubu.top/Article/details/gtdmjapkee.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.shanyushiyangtech.top/Article/details/gtrblnitif.html

[Q09] 创建唯一索引
来源：http://dali.tianlin.xyz/Article/details/gtcdsczlsd.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.wangshuangyany.cn/Article/details/gtxsqxsoga.html

[Q10] 插入单行
来源：http://dali.xinyue.icu/Article/details/gtadujboxv.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.tian-w.cn/Article/details/gtoimbmitf.html

[Q11] 一次插入多行
来源：http://dali.yj202588.top/Article/details/gtxzxeienw.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.tianlin.xyz/Article/details/gtierrnpnx.html

[Q12] 插入后取自增 ID
来源：http://dali.yueranfly.top/Article/details/gtxqkioyfs.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.hnxiangtu.top/Article/details/gtyhttxooe.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.daria6918.cn/Article/details/gtxpymogdn.html

[Q13] 忽略重复插入
来源：http://dali.sufxvd.cn/Article/details/gtvdxwsxvp.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.nanxuanxn.top/Article/details/gtwvppduku.html

[Q14] 存在则更新（upsert）
来源：http://dali.jqgufenzy.top/Article/details/gtortzhipr.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.jqgfzy.top/Article/details/gtbgvrlfqk.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.jqgfzy.top/Article/details/gtziwxawsi.html

[Q15] 查询全部
来源：http://dali.sxryk.cn/Article/details/gtaqpjxslj.html

SELECT * FROM users;
来源：http://dali.redwolf501.top/Article/details/gtxixhmrwf.html

[Q16] 查询指定列
来源：http://dali.zhiwuduotai.top/Article/details/gtfaigodvh.html

SELECT id, name FROM users;
来源：http://dali.pengpengdd.cyou/Article/details/gtrgerlqxw.html

[Q17] 条件查询
来源：http://dali.yonumen.top/Article/details/gtvgwxaaok.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.ehwqpu.com/Article/details/gtjobalqyp.html

[Q18] 模糊匹配
来源：http://dali.pycfn.com/Article/details/gtediumxhg.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.dashuyun.cn/Article/details/gtkfszhhxo.html

[Q19] 范围查询
来源：http://dali.yanxiufei.cn/Article/details/gtjgvjavrd.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.sysykeji.top/Article/details/gtvgvdtmyj.html

[Q20] IN 列表
来源：http://dali.kuanghao11.cn/Article/details/gtiddafvwg.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.c1oappe.top/Article/details/gtijjikvsq.html

[Q21] 空值判断
来源：http://dali.jianghu66.top/Article/details/gtyhljqszm.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zycfv.cn/Article/details/gtlpqohizp.html

[Q22] 排序
来源：http://dali.xylfe.cn/Article/details/gtragbhqpp.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.meibo888.top/Article/details/gtihodgggk.html

[Q23] 分页
来源：http://dali.jyoumei.cn/Article/details/gtzayupfzy.html


<!-- 参考信息 -->