代发 wailian999

[M08] 获取系统与运行时信息
来源：http://dali.guowangkeji.top/Article/details/gtgmerjgda.html

Py:   platform.system();  platform.python_version()
来源：http://dali.jiagoushi.top/Article/details/gtwbgucdfb.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.hysaishi.cn/Article/details/gtzkbkncga.html

JS:   process.platform;  process.version
来源：http://dali.dianchejie.cn/Article/details/gtttlxmwua.html

TS:   process.platform;  process.version
来源：http://dali.havefunace.top/Article/details/gtuhhrywcp.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.iojbl.cn/Article/details/gtnamjwtfj.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zdqjudy.top/Article/details/gtergqjgkt.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.jqgfzy.top/Article/details/gtrzirbbkb.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.wangdashe.top/Article/details/gtrglovozt.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtrtxcdsur.html

N. 数据结构与算法
来源：http://dali.c1oappe.top/Article/details/gthkjjszht.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtfsaunqmp.html

[N01] 二分查找（有序数组）
来源：http://dali.zhiwuduotai.top/Article/details/gtlbxzcdov.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhoulong.xyz/Article/details/gttclqpcqs.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.ehwqpu.com/Article/details/gtpdreggvg.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.shzxlz.cn/Article/details/gtuxqcnexz.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.fzhhl.top/Article/details/gttssbeqgo.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.chenlongwang.top/Article/details/gtdephcxth.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.ppjwa.cn/Article/details/gtqjopxtvq.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.sufxvd.cn/Article/details/gtfvfcypdx.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.jlsjyb.cn/Article/details/gtppchgdev.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.quarkkingdee.top/Article/details/gtoisiwenr.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.sxryk.cn/Article/details/gtbsunmevy.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.jinghuilouyu.cn/Article/details/gtinvshbtw.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yueranfly.top/Article/details/gtbzjhxihz.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yj20258.top/Article/details/gtntgqythy.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.yongpay.top/Article/details/gtdsqmgher.html

Go:   slices.Sort(arr)
来源：http://dali.jinghuilouyu.cn/Article/details/gtmwwlnzub.html

Ruby: arr.sort
来源：http://dali.sufxvd.cn/Article/details/gtwdqkisxc.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.xinyue.icu/Article/details/gtyftqoekr.html

[N03] 快速排序（分治示例）
来源：http://dali.chenjidiqi.icu/Article/details/gtvlemxcvg.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.jqgufenzy.top/Article/details/gtqpkioqhf.html

PHP:  // 递归实现，或用 usort
来源：http://dali.nwbrower.top/Article/details/gtthabzlgr.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yangfankeji.com/Article/details/gtaniggdgk.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.0kj1m.cn/Article/details/gtsvaqgghd.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.jqgfzy.top/Article/details/gtmkdfnmux.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.snrcjt.cn/Article/details/gtoxvyzidi.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.hywenlv.cn/Article/details/gttpoiavxs.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.shuidangran.top/Article/details/gtmfekrlmz.html

[N04] 斐波那契数列
来源：http://dali.yuxming.cn/Article/details/gtvvbaymcv.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.andypj.xyz/Article/details/gtsdpzluuu.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.nwbrower.top/Article/details/gtbilulcgf.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.sxryk.cn/Article/details/gtqahudkaj.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.gzhubu.top/Article/details/gtfqzwallj.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.tianlin.xyz/Article/details/gtbkpxfprn.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.sweek.top/Article/details/gteokxaxcs.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.jinqigfzy.top/Article/details/gttxtphqrt.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.hfpthk.cn/Article/details/gtzkcupfty.html

[N05] 最大公约数
来源：http://dali.iojbl.cn/Article/details/gtjvpfbivm.html

Py:   math.gcd(a, b)
来源：http://dali.birdmap.top/Article/details/gtchkhlzwk.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.jlsjyb.cn/Article/details/gtwefrkisr.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.fzhhl.top/Article/details/gtxfyiijxo.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdfwfvhnm.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.jqgfzy.top/Article/details/gtvejqzwcy.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.snrcjt.cn/Article/details/gtfbypedpc.html

Ruby: a.gcd(b)
来源：http://dali.redwolf501.top/Article/details/gthjnsbqlo.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.sweek.top/Article/details/gtnxgxlcqk.html

[N06] 判断回文字符串
来源：http://dali.hysaishi.cn/Article/details/gtdaexqkbh.html

Py:   s == s[::-1]
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcracgwro.html

PHP:  $s === strrev($s);
来源：http://dali.cdnleiting.top/Article/details/gtacapztxh.html

JS:   s === [...s].reverse().join("")
来源：http://dali.mhx1999.top/Article/details/gtynvffnnu.html

TS:   s === [...s].reverse().join("")
来源：http://dali.ybcxt.top/Article/details/gtqhbbyjuj.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhaomingkeji.xyz/Article/details/gthzzpgtba.html

Go:   // 双指针从两端比较
来源：http://dali.cqqwz.cn/Article/details/gtnjlpvruq.html

Ruby: s == s.reverse
来源：http://dali.shangyingyoupin.top/Article/details/gtavrkxqau.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.jyoumei.cn/Article/details/gtgmafeasj.html

[N07] 两数之和（返回下标）
来源：http://dali.0kj1m.cn/Article/details/gtuntnlydp.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.ydzc1.top/Article/details/gtkvjhukdk.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.birdmap.top/Article/details/gtozczmhhx.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.hammf.cn/Article/details/gtxmvlicaz.html

TS:   // 手写 Map<string, number>
来源：http://dali.yangfankeji.com/Article/details/gtoynhpqmg.html

Java: // 手写 HashMap
来源：http://dali.gzhubu.top/Article/details/gtgetojkwh.html

Go:   // 手写 map[int]int
来源：http://dali.xylfe.cn/Article/details/gttripujpx.html

Ruby: // 手写 Hash
来源：http://dali.hywenlv.cn/Article/details/gtnzdgixln.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.haohaochexian.top/Article/details/gtloopcylb.html

[N08] 生成全排列
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdzpwrpsx.html

Py:   itertools.permutations(arr)
来源：http://dali.chenlongwang.top/Article/details/gtiypysity.html

PHP:  // 手写递归交换
来源：http://dali.nanxuanxn.top/Article/details/gtrzjofcga.html

JS:   // 手写回溯递归
来源：http://dali.cucudq.cn/Article/details/gtjvrpiiqn.html

TS:   // 手写回溯递归
来源：http://dali.shuidangran.top/Article/details/gtgeymuyyk.html

Java: // 手写回溯递归
来源：http://dali.yongpay.top/Article/details/gtkzafclvl.html

Go:   // 手写回溯递归
来源：http://dali.jqgufenzy.top/Article/details/gtfiywzkmp.html

Ruby: arr.permutation.to_a
来源：http://dali.tian-w.cn/Article/details/gthvtbdvwg.html

C#:   // 手写回溯递归
来源：http://dali.daria6918.cn/Article/details/gtzwiiruvu.html

[N09] 栈与队列
来源：http://dali.dianchejie.cn/Article/details/gtgiikrfpt.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.gotoacloud.top/Article/details/gtooupqjcp.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.haohaochexian.top/Article/details/gthgzsnile.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.chenjidiqi.icu/Article/details/gtxyozksdp.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhengqikj.top/Article/details/gttcrhelzg.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.vqdsnc.cn/Article/details/gtxgbucrrq.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.guannengcc.top/Article/details/gtmxfdyquq.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.jiagoushi.top/Article/details/gtozfzanbz.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.smart0.xyz/Article/details/gttdzqyheg.html

[N10] 链表节点定义
来源：http://dali.gaohongyu789.top/Article/details/gtptwfrlbu.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.cqqwz.cn/Article/details/gtijevjsza.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbyguzvjf.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.andypj.xyz/Article/details/gtpdlcgnre.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.redwolf501.top/Article/details/gthouhkhzb.html

Java: class Node { int v; Node next; }
来源：http://dali.dashuyun.cn/Article/details/gtonfsoebd.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.bjfxy.top/Article/details/gtcxchslhm.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.nanxuanxn.top/Article/details/gtgjlgbpft.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhiwuduotai.top/Article/details/gtjpcxaqgr.html

[N11] 二叉树中序遍历
来源：http://dali.shuidangran.top/Article/details/gtcntpoqhf.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.pengpengdd.cyou/Article/details/gtknfawyks.html

PHP:  // 手写递归函数
来源：http://dali.dashuyun.cn/Article/details/gtfxaayxsc.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.daria6918.cn/Article/details/gtnyuslxhy.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yonumen.top/Article/details/gtivsnitxs.html

Java: // 手写递归
来源：http://dali.0kj1m.cn/Article/details/gtlqesqcvn.html

Go:   // 手写递归
来源：http://dali.daxiang520.top/Article/details/gtchjrjcda.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.iojbl.cn/Article/details/gtlconymer.html

C#:   // 手写递归
来源：http://dali.zhaomingkeji.xyz/Article/details/gtybonayet.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.tian-w.cn/Article/details/gtvhfhtshu.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.xziqi.cn/Article/details/gtvyxstsfw.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.gotoacloud.top/Article/details/gtoscjrbvo.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.chenlongwang.top/Article/details/gtvktzmxyc.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zdqjudy.top/Article/details/gtespxqlpb.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.cqqwz.cn/Article/details/gtbyvxkcls.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.svipenyu.cn/Article/details/gtdfpwvllv.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.jinqigufen.top/Article/details/gtmehivmux.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhoulong.xyz/Article/details/gtsqfzkxvl.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtvtbqwwpo.html

O. 并发与异步
来源：http://dali.zhengqikj.top/Article/details/gtnmbodafv.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gteerdskmh.html

[O01] 启动一个线程
来源：http://dali.yvedp.cn/Article/details/gtsnhqogqn.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.hfpthk.cn/Article/details/gtkgruqcbs.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.sweek.top/Article/details/gtyswelwfj.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.ybcxt.top/Article/details/gthbvhuujv.html

TS:   // 同 JS
来源：http://dali.bjfxy.top/Article/details/gtfhodcyps.html

Java: new Thread(() -> f()).start()
来源：http://dali.jlsjyb.cn/Article/details/gtjamqmrcr.html

Go:   go f()
来源：http://dali.yvedp.cn/Article/details/gtczgukrwk.html

Ruby: Thread.new { f }
来源：http://dali.sweek.top/Article/details/gthliijixe.html

C#:   Task.Run(() => F());
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfaigpbcp.html

[O02] 使用线程池
来源：http://dali.chenzaomai.com/Article/details/gtfvcfxvyh.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.quarkkingdee.top/Article/details/gtzmuettkk.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.andypj.xyz/Article/details/gtjeasxjqk.html

JS:   // worker_threads 线程池
来源：http://dali.daxiang520.top/Article/details/gtrsbgspeb.html

TS:   // worker_threads 线程池
来源：http://dali.xylfe.cn/Article/details/gtlbkizuze.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.chenlongwang.top/Article/details/gtzymyowuh.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.guowangkeji.top/Article/details/gtrjqovbub.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zdqjudy.top/Article/details/gtkxmqzhvx.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.cucudq.cn/Article/details/gtvgbmgkxm.html

[O03] 加锁保护共享数据
来源：http://dali.tanke756.top/Article/details/gtfebjtvky.html

Py:   with lock: shared += 1
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyvmjnhtb.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.ybcxt.top/Article/details/gtyxeuilqw.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.wangdashe.top/Article/details/gthuwgsjqo.html

TS:   // 同 JS
来源：http://dali.ehwqpu.com/Article/details/gtovvcllic.html

Java: synchronized (this) { shared++; }
来源：http://dali.guowangkeji.top/Article/details/gthpdvfgnz.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.shangyingyoupin.top/Article/details/gtjjwmcype.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zdqjudy.top/Article/details/gtjdpfwqku.html

C#:   lock (gate) { shared++; }
来源：http://dali.jqgfzy.top/Article/details/gtxvddqzec.html

[O04] 定义异步函数并等待
来源：http://dali.xuanzx.com/Article/details/gtmggislsw.html

Py:   async def f():⏎    await g()
来源：http://dali.feifeiyinyue.top/Article/details/gtsxvxbkbw.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzpxoltgb.html

JS:   async function f() { await g(); }
来源：http://dali.wangshuangyany.cn/Article/details/gtqmebfyvg.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zycfv.cn/Article/details/gtdvpmbogz.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.hfpthk.cn/Article/details/gtvwcuzuqo.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.hnxiangtu.top/Article/details/gtkgnudvbd.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.jinqigufen.top/Article/details/gthbroaafa.html

C#:   async Task F() { await G(); }
来源：http://dali.hnqzz.top/Article/details/gtgqqyvear.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhiwuduotai.top/Article/details/gtnzrgghmb.html

Py:   asyncio.gather(*tasks)
来源：http://dali.hnqzz.top/Article/details/gtpjriwcra.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.andypj.xyz/Article/details/gtyfacmxhy.html

JS:   await Promise.all(tasks)
来源：http://dali.jiagoushi.top/Article/details/gtawqdsuzm.html

TS:   await Promise.all(tasks)
来源：http://dali.zhixingplan.top/Article/details/gtdjduzwqr.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.tianlin.xyz/Article/details/gtkcsskwdt.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.daxiang520.top/Article/details/gtqvzsdmma.html

Ruby: threads.map(&:join)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfovxinzf.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.ppjwa.cn/Article/details/gtkxazeomx.html

[O06] 使用进程池
来源：http://dali.jinqigufen.top/Article/details/gtwwoasscj.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.pengpengdd.cyou/Article/details/gtbaloaoeh.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.daria6918.cn/Article/details/gtyuqblkuv.html

JS:   // child_process / cluster 模块
来源：http://dali.zhixingplan.top/Article/details/gtiguoqtna.html

TS:   // child_process / cluster 模块
来源：http://dali.guowangkeji.top/Article/details/gtobbkvwaj.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.mhx1999.top/Article/details/gtuzidecde.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.jinghuilouyu.cn/Article/details/gtlbioewzg.html

Ruby: // fork 块
来源：http://dali.xuetiantiany.cn/Article/details/gtbtjokxti.html

C#:   Parallel.For
来源：http://dali.nwbrower.top/Article/details/gtqljbfqgl.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtknssllsz.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gtzmghylcd.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtzgwjhgvf.html

[P01] 生成 UUID
来源：http://dali.zhixingplan.top/Article/details/gtmkbzwkec.html

Py:   str(uuid.uuid4())
来源：http://dali.zhiwuduotai.top/Article/details/gtaurnpysm.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.ivvv.top/Article/details/gtjrytezaf.html

JS:   crypto.randomUUID()
来源：http://dali.xziqi.cn/Article/details/gtojcrldmy.html

TS:   crypto.randomUUID()
来源：http://dali.hnxiangtu.top/Article/details/gtohmkaflc.html

Java: UUID.randomUUID().toString()
来源：http://dali.guannengcc.top/Article/details/gtythumvpk.html

Go:   // 用 github.com/google/uuid
来源：http://dali.jqgufenzy.top/Article/details/gtqmsfzvhe.html

Ruby: SecureRandom.uuid
来源：http://dali.jlsjyb.cn/Article/details/gtonchotvu.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyvdzlnio.html

[P02] MD5 / SHA256 摘要
来源：http://dali.hammf.cn/Article/details/gtsyzmqaal.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.yj202588.top/Article/details/gtsjdaqzoo.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.snrcjt.cn/Article/details/gtppzgrrsq.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.cucudq.cn/Article/details/gtixqiqgfp.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.guannengcc.top/Article/details/gtwuhoydbl.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhixingplan.top/Article/details/gtrqjfqhao.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtussgmnlh.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.hfpthk.cn/Article/details/gtsismwzqm.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.cucudq.cn/Article/details/gttpoeeexa.html

[P03] 生成短随机字符串
来源：http://dali.zdqjudy.top/Article/details/gtwovxqcjp.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.guannengcc.top/Article/details/gtkoxytqfy.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.dashuyun.cn/Article/details/gtjqsdcyvl.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yongpay.top/Article/details/gtbddopzai.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jinqigfzy.top/Article/details/gtlidgjoyz.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.9152youxi.cn/Article/details/gtwnqhuvjx.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.nwbrower.top/Article/details/gtesaverib.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.mhx1999.top/Article/details/gtmrdnspet.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.jinqigufen.top/Article/details/gtxwolffyb.html

[P04] 求长度
来源：http://dali.hywenlv.cn/Article/details/gteqglvjwd.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.xziqi.cn/Article/details/gtpoxsbdhw.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.guowangkeji.top/Article/details/gtxujgjecq.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jinghuilouyu.cn/Article/details/gttngwkkio.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.chenjidiqi.icu/Article/details/gtjoiwntuu.html

Java: list.size();  map.size();  s.length()
来源：http://dali.ehwqpu.com/Article/details/gtotncdlnb.html

Go:   len(arr);  len(m)
来源：http://dali.dashuyun.cn/Article/details/gtonksubxa.html

Ruby: x.length;  x.size
来源：http://dali.havefunace.top/Article/details/gtviytfxgg.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.haohaochexian.top/Article/details/gtlrebttdj.html

[P05] 判断两个对象内容是否相等
来源：http://dali.sxryk.cn/Article/details/gtntshartq.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.sxryk.cn/Article/details/gtnsudxdag.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.nanxinkj.top/Article/details/gtnmiedzsf.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.nanxinkj.top/Article/details/gtntcbqihi.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.nwbrower.top/Article/details/gtenkplqba.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.feifeiyinyue.top/Article/details/gtaizbjyhl.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.hammf.cn/Article/details/gtxpydupdu.html

Ruby: a == b
来源：http://dali.c1oappe.top/Article/details/gtvewocgzp.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.sufxvd.cn/Article/details/gtfmrliyce.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zycfv.cn/Article/details/gtiwfvsndf.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.cucudq.cn/Article/details/gtjlucwabc.html

PHP:  if (empty($x)) {}
来源：http://dali.andypj.xyz/Article/details/gtvijrjvan.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.9152youxi.cn/Article/details/gtncccdcvy.html

TS:   if (x == null) {}
来源：http://dali.yanxiufei.cn/Article/details/gtvjrhorrk.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.svipenyu.cn/Article/details/gtxidmucvf.html

Go:   if x == nil {}
来源：http://dali.ehwqpu.com/Article/details/gtwpahffiy.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.jianghu66.top/Article/details/gtefxqfhlq.html

C#:   if (x is null) {}
来源：http://dali.ivvv.top/Article/details/gtjlxwlwnh.html

[P07] 防抖与节流
来源：http://dali.daria6918.cn/Article/details/gtpojfzhrr.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gtldcdavxk.html

PHP:  // 手写时间戳比较
来源：http://dali.tian-w.cn/Article/details/gterwumsjo.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yongpay.top/Article/details/gtvkgrgkpi.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgsyfaayi.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.xinyue.icu/Article/details/gticemnjjr.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.xuanzx.com/Article/details/gtkuswimpe.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.ehwqpu.com/Article/details/gtochokfgo.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.pengpengdd.cyou/Article/details/gtzdmtalbw.html

[P08] 处理浮点精度问题
来源：http://dali.jinghuilouyu.cn/Article/details/gtjfvkcgeo.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.yueranfly.top/Article/details/gtorcxtfws.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.hywenlv.cn/Article/details/gtblzfkjta.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zycfv.cn/Article/details/gtrkszvaqy.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.wangdashe.top/Article/details/gtcjzyltnb.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.quarkkingdee.top/Article/details/gtvfyivnhm.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.redwolf501.top/Article/details/gtrneapjka.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.wangdashe.top/Article/details/gtmvdmebti.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.feifeiyinyue.top/Article/details/gtwgvyhwey.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gthnljwrls.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.jinghuilouyu.cn/Article/details/gtlufarqrj.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtqhiolngj.html

[Q01] 创建表
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzxidrlce.html

CREATE TABLE users (
来源：http://dali.xuanzx.com/Article/details/gtsqyeevcq.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.iojbl.cn/Article/details/gtsqqbcmgv.html

name VARCHAR(50) NOT NULL,
来源：http://dali.tian-w.cn/Article/details/gtjmjycgdb.html

email VARCHAR(100) UNIQUE,
来源：http://dali.mhx1999.top/Article/details/gtbfwfexyf.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.quarkkingdee.top/Article/details/gtcsgliyhs.html

);
来源：http://dali.fengsongda.top/Article/details/gtouzzrvbs.html

[Q02] 创建带外键的表
来源：http://dali.daxiang520.top/Article/details/gtvckweuyn.html

CREATE TABLE orders (
来源：http://dali.9152youxi.cn/Article/details/gtccyupkyx.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jqgfzy.top/Article/details/gtubsgtubh.html

user_id INT NOT NULL,
来源：http://dali.cashguo.top/Article/details/gtcyvtcssz.html

amount DECIMAL(10, 2),
来源：http://dali.meibo888.top/Article/details/gtbvotoali.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.sweek.top/Article/details/gtlmmjlpop.html

);
来源：http://dali.cucudq.cn/Article/details/gtaopjzekp.html

[Q03] 增加列
来源：http://dali.xylfe.cn/Article/details/gtqmzjzogf.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.birdmap.top/Article/details/gtupfebnoh.html

[Q04] 修改列类型
来源：http://dali.pengpengdd.cyou/Article/details/gtoiscnnhx.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.ivvv.top/Article/details/gtqcewdjwi.html

[Q05] 重命名列
来源：http://dali.nanxuanxn.top/Article/details/gthwpvpjtr.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.yanxiufei.cn/Article/details/gtzflnoqnf.html

[Q06] 删除列
来源：http://dali.andypj.xyz/Article/details/gtzyjbjqvo.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zdqjudy.top/Article/details/gtpnnzmfdy.html

[Q07] 删除表
来源：http://dali.cucudq.cn/Article/details/gtjjhsowqz.html

DROP TABLE IF EXISTS orders;
来源：http://dali.hfpthk.cn/Article/details/gtahdbpgai.html

[Q08] 创建普通索引
来源：http://dali.c1oappe.top/Article/details/gtjpearguw.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.wangdashe.top/Article/details/gtvvlexcvc.html

[Q09] 创建唯一索引
来源：http://dali.sweek.top/Article/details/gttaubxhnk.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.ydzc1.top/Article/details/gtwyomjadr.html

[Q10] 插入单行
来源：http://dali.0kj1m.cn/Article/details/gtxwhdbgjz.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.ybcxt.top/Article/details/gtxvymmlxm.html

[Q11] 一次插入多行
来源：http://dali.hysaishi.cn/Article/details/gtrfwpekji.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.cucudq.cn/Article/details/gtaqnuyeed.html

[Q12] 插入后取自增 ID
来源：http://dali.yj20258888.top/Article/details/gttynwqxbq.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.jinqigfzy.top/Article/details/gtchvqefec.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.yangfankeji.com/Article/details/gtpzfdfkml.html

[Q13] 忽略重复插入
来源：http://dali.shuidangran.top/Article/details/gtqzvdfbnl.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.mhx1999.top/Article/details/gttndrdssr.html

[Q14] 存在则更新（upsert）
来源：http://dali.cdnleiting.top/Article/details/gtxteefnyh.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.guowangkeji.top/Article/details/gtasrmfawc.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.cqqwz.cn/Article/details/gtdnxslova.html

[Q15] 查询全部
来源：http://dali.yvedp.cn/Article/details/gtuomhonnu.html

SELECT * FROM users;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlqiewbyk.html

[Q16] 查询指定列
来源：http://dali.chenzaomai.com/Article/details/gtberhhdys.html

SELECT id, name FROM users;
来源：http://dali.fengsongda.top/Article/details/gteykibpep.html

[Q17] 条件查询
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtboyqrggk.html


<!-- 参考信息 -->