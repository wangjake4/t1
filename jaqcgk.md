代发 wailian999

TS:   process.platform;  process.version
来源：http://dali.mhx1999.top/Article/details/gtltearuaa.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.dashuyun.cn/Article/details/gtynavnlnb.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.jiagoushi.top/Article/details/gtluxiibyu.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.fengsongda.top/Article/details/gtzusamfcx.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.andypj.xyz/Article/details/gtmusdsgkh.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtdsvbkvhb.html

N. 数据结构与算法
来源：http://dali.jinqigufen.top/Article/details/gtkrpmshsm.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtfucoyuty.html

[N01] 二分查找（有序数组）
来源：http://dali.gogol.net.cn/Article/details/gtuvpodmxm.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.tian-w.cn/Article/details/gtnnnujbwe.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfddkzgch.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.fzhhl.top/Article/details/gtycbfhikk.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.c1oappe.top/Article/details/gteakyaobg.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gtyziilotd.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.cashguo.top/Article/details/gtebodmvrx.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.chenlongwang.top/Article/details/gtyqdryrsu.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.0kj1m.cn/Article/details/gtxqwbirfc.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwsiybtxi.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jinyuanbaomall.cn/Article/details/gttnnkwusn.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.yangfankeji.com/Article/details/gtkxzwqpkn.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhongyouzk.top/Article/details/gtypyljazl.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.tanke756.top/Article/details/gtbxaseuvi.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.yuanzhike.top/Article/details/gtsjfeyzsp.html

Go:   slices.Sort(arr)
来源：http://dali.chenjidiqi.icu/Article/details/gtzclknqws.html

Ruby: arr.sort
来源：http://dali.cqqwz.cn/Article/details/gtaeyqlbpr.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.jlsjyb.cn/Article/details/gtdgqncjjt.html

[N03] 快速排序（分治示例）
来源：http://dali.wangdashe.top/Article/details/gtttammhny.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.jyoumei.cn/Article/details/gtxwmemwoy.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhengqikj.top/Article/details/gtpfzpoupa.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.hywenlv.cn/Article/details/gtydnlzkuy.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.dashuyun.cn/Article/details/gtzvtbzpms.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.meibo888.top/Article/details/gtzfvngqon.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.snrcjt.cn/Article/details/gteqznutyp.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.birdmap.top/Article/details/gtxzzuudbp.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.hongshengwenyu.top/Article/details/gtcdasxyly.html

[N04] 斐波那契数列
来源：http://dali.cashguo.top/Article/details/gtejfbhtqw.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.jinghuilouyu.cn/Article/details/gtpfzmpjxa.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhiwuduotai.top/Article/details/gtonyhuvwx.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yvedp.cn/Article/details/gtqiuqhnsy.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jyoumei.cn/Article/details/gttkoblyzc.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gtyutdmpac.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.yj20258.top/Article/details/gtuwfnidje.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.daria6918.cn/Article/details/gtmlrstpcb.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhoulong.xyz/Article/details/gtcplupygb.html

[N05] 最大公约数
来源：http://dali.gogol.net.cn/Article/details/gtrvplvxpm.html

Py:   math.gcd(a, b)
来源：http://dali.svipenyu.cn/Article/details/gtzhvodykt.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.c1oappe.top/Article/details/gtiilnyloi.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.gaohongyu789.top/Article/details/gtyjsycuuv.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.sweek.top/Article/details/gtptrnnbkj.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.yangfankeji.com/Article/details/gtjvbghgdi.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsxxzhatn.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gtdxmxxqeo.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.fzhhl.top/Article/details/gtdjylvzwd.html

[N06] 判断回文字符串
来源：http://dali.gogol.net.cn/Article/details/gtzgitwjmu.html

Py:   s == s[::-1]
来源：http://dali.hnqzz.top/Article/details/gthzlthlsz.html

PHP:  $s === strrev($s);
来源：http://dali.daria6918.cn/Article/details/gtxemvlaxo.html

JS:   s === [...s].reverse().join("")
来源：http://dali.sysykeji.top/Article/details/gtztsnyovh.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwgcditwe.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.ehwqpu.com/Article/details/gtanchpyin.html

Go:   // 双指针从两端比较
来源：http://dali.chenlongwang.top/Article/details/gtdtjkjnxv.html

Ruby: s == s.reverse
来源：http://dali.fengsongda.top/Article/details/gtznlqdipo.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.bjfxy.top/Article/details/gtjewzjdbk.html

[N07] 两数之和（返回下标）
来源：http://dali.ppjwa.cn/Article/details/gtjilbqoht.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.cheryme.top/Article/details/gtyvtujsjy.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.andypj.xyz/Article/details/gtpjhkmhyf.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.sufxvd.cn/Article/details/gtoujbpenw.html

TS:   // 手写 Map<string, number>
来源：http://dali.kuanghao11.cn/Article/details/gtkfiitazv.html

Java: // 手写 HashMap
来源：http://dali.yongpay.top/Article/details/gtfqdkabda.html

Go:   // 手写 map[int]int
来源：http://dali.chenjidiqi.icu/Article/details/gtnhsqzqln.html

Ruby: // 手写 Hash
来源：http://dali.c1oappe.top/Article/details/gtkmmiznlw.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.aibaodan.cn/Article/details/gtdgvsaelj.html

[N08] 生成全排列
来源：http://dali.xuetiantiany.cn/Article/details/gttpgdwliy.html

Py:   itertools.permutations(arr)
来源：http://dali.cucudq.cn/Article/details/gtafeeuxfr.html

PHP:  // 手写递归交换
来源：http://dali.sxryk.cn/Article/details/gteojsdqfk.html

JS:   // 手写回溯递归
来源：http://dali.iojbl.cn/Article/details/gtimchhmoh.html

TS:   // 手写回溯递归
来源：http://dali.chenlongwang.top/Article/details/gtvjxoiago.html

Java: // 手写回溯递归
来源：http://dali.jlsjyb.cn/Article/details/gtyjdtdhat.html

Go:   // 手写回溯递归
来源：http://dali.hysaishi.cn/Article/details/gtewvsvfhk.html

Ruby: arr.permutation.to_a
来源：http://dali.316326.xyz/Article/details/gtlneevkfw.html

C#:   // 手写回溯递归
来源：http://dali.haohaochexian.top/Article/details/gtduacyxgh.html

[N09] 栈与队列
来源：http://dali.aibaodan.cn/Article/details/gtfdeyyxmm.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.wangdashe.top/Article/details/gtcilgyice.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zdqjudy.top/Article/details/gtbmwvevqg.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.haohaochexian.top/Article/details/gtiazngonb.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.sysykeji.top/Article/details/gtninlgnuw.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpobqcnvx.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.9152youxi.cn/Article/details/gtmqexaytj.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.316326.xyz/Article/details/gtgptyqvzz.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.feifeiyinyue.top/Article/details/gtspvfqjft.html

[N10] 链表节点定义
来源：http://dali.yj20258.top/Article/details/gtuzqthqvh.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.jinqigfzy.top/Article/details/gtqzecoccs.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.sweek.top/Article/details/gtewnuejll.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.hnxiangtu.top/Article/details/gteuxdwmyb.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.hongshengwenyu.top/Article/details/gteafnpivm.html

Java: class Node { int v; Node next; }
来源：http://dali.shanyushiyangtech.top/Article/details/gttaamcjsf.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.ehwqpu.com/Article/details/gtzyubkhnd.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.shanyushiyangtech.top/Article/details/gtkhawyjxj.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.9152youxi.cn/Article/details/gtfifgciir.html

[N11] 二叉树中序遍历
来源：http://dali.xylfe.cn/Article/details/gtqxpbilyy.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.wangdashe.top/Article/details/gtphqgebqf.html

PHP:  // 手写递归函数
来源：http://dali.cucudq.cn/Article/details/gtkywwymre.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.316326.xyz/Article/details/gtqatnsxzv.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.hysaishi.cn/Article/details/gtcllyfwal.html

Java: // 手写递归
来源：http://dali.shuidangran.top/Article/details/gtuqbvxyfq.html

Go:   // 手写递归
来源：http://dali.gotoacloud.top/Article/details/gtkwgqpzxw.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.meibo888.top/Article/details/gtrsgfclui.html

C#:   // 手写递归
来源：http://dali.pycfn.com/Article/details/gtwitvvxla.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.ywan-chungtsiang.top/Article/details/gttrudnfrd.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.sweek.top/Article/details/gthrxkejgj.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.fzhhl.top/Article/details/gtlauykvsb.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.cdnleiting.top/Article/details/gttvfojubz.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.smart0.xyz/Article/details/gtelrisgku.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.nanxinkj.top/Article/details/gtzalwychk.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.aizwys.cn/Article/details/gtmuihtres.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.redwolf501.top/Article/details/gtnijhwvlv.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.cheryme.top/Article/details/gtifosbkud.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtlpapuhil.html

O. 并发与异步
来源：http://dali.sufxvd.cn/Article/details/gtqzhgnyba.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtjnlzasik.html

[O01] 启动一个线程
来源：http://dali.ppjwa.cn/Article/details/gtfmzodpar.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.daria6918.cn/Article/details/gtsdivdgro.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.gogol.net.cn/Article/details/gtfplbvvix.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.tianlin.xyz/Article/details/gtsgirtivz.html

TS:   // 同 JS
来源：http://dali.snrcjt.cn/Article/details/gtfvpnyzys.html

Java: new Thread(() -> f()).start()
来源：http://dali.jqgufenzy.top/Article/details/gtfpxsoppo.html

Go:   go f()
来源：http://dali.yuanzhike.top/Article/details/gtljmsmqwb.html

Ruby: Thread.new { f }
来源：http://dali.yongpay.top/Article/details/gtxuqccwrl.html

C#:   Task.Run(() => F());
来源：http://dali.iojbl.cn/Article/details/gtyhjtlnwx.html

[O02] 使用线程池
来源：http://dali.hnqzz.top/Article/details/gtloopgdhl.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.tanke756.top/Article/details/gttpjakokk.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.cheryme.top/Article/details/gtyqybviup.html

JS:   // worker_threads 线程池
来源：http://dali.yj202588.top/Article/details/gtkywjadwe.html

TS:   // worker_threads 线程池
来源：http://dali.0kj1m.cn/Article/details/gtucmnpkxj.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.316326.xyz/Article/details/gtkbppttfj.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.hnqzz.top/Article/details/gthisensps.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.chenjidiqi.icu/Article/details/gtmvoujdqm.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.dashuyun.cn/Article/details/gttpbpslry.html

[O03] 加锁保护共享数据
来源：http://dali.hfpthk.cn/Article/details/gtichbslcu.html

Py:   with lock: shared += 1
来源：http://dali.feifeiyinyue.top/Article/details/gtyebjcgsv.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.yanxiufei.cn/Article/details/gteyzbxebf.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.cheryme.top/Article/details/gtfpribcni.html

TS:   // 同 JS
来源：http://dali.0kj1m.cn/Article/details/gtldrcsqbt.html

Java: synchronized (this) { shared++; }
来源：http://dali.cqqwz.cn/Article/details/gtvekyihpx.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.sweek.top/Article/details/gtlrchthpm.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.gogol.net.cn/Article/details/gtownxmdfs.html

C#:   lock (gate) { shared++; }
来源：http://dali.chenlongwang.top/Article/details/gtzcwyjsxw.html

[O04] 定义异步函数并等待
来源：http://dali.316326.xyz/Article/details/gthacpevsv.html

Py:   async def f():⏎    await g()
来源：http://dali.ehwqpu.com/Article/details/gthkefvwvf.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.ybcxt.top/Article/details/gtygfzzpad.html

JS:   async function f() { await g(); }
来源：http://dali.shangyingyoupin.top/Article/details/gtdxdbymqt.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.jqgufenzy.top/Article/details/gtitgiinvw.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.vqdsnc.cn/Article/details/gtoqcmpdok.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.tianlin.xyz/Article/details/gtqlcssapf.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.jinqigufen.top/Article/details/gtjddahvbd.html

C#:   async Task F() { await G(); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gttxhnztlo.html

[O05] 并发执行并等待全部完成
来源：http://dali.shanyushiyangtech.top/Article/details/gtxqazjsgy.html

Py:   asyncio.gather(*tasks)
来源：http://dali.daxiang520.top/Article/details/gtqbrbkmma.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.pycfn.com/Article/details/gtxrutsglm.html

JS:   await Promise.all(tasks)
来源：http://dali.cheryme.top/Article/details/gtuirrvhsu.html

TS:   await Promise.all(tasks)
来源：http://dali.birdmap.top/Article/details/gtebzglxvo.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.kuanghao11.cn/Article/details/gtjrercqxe.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.tianlin.xyz/Article/details/gtlzlslpua.html

Ruby: threads.map(&:join)
来源：http://dali.chenzaomai.com/Article/details/gtdyphbgbt.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.chenzaomai.com/Article/details/gttpurgnzx.html

[O06] 使用进程池
来源：http://dali.snrcjt.cn/Article/details/gtearypytq.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.kuanghao11.cn/Article/details/gtgewewclp.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.ehwqpu.com/Article/details/gttoxpouzi.html

JS:   // child_process / cluster 模块
来源：http://dali.gaohongyu789.top/Article/details/gtouvsusvp.html

TS:   // child_process / cluster 模块
来源：http://dali.jyoumei.cn/Article/details/gtpsekvere.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.andypj.xyz/Article/details/gtzgnllljm.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.yvedp.cn/Article/details/gtnioktuuq.html

Ruby: // fork 块
来源：http://dali.daxiang520.top/Article/details/gtrfksgdhn.html

C#:   Parallel.For
来源：http://dali.mhx1999.top/Article/details/gtcbjtgods.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtgthgjgbw.html

P. 常用工具函数
来源：http://dali.snrcjt.cn/Article/details/gtcgywimto.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtuvlkfcyy.html

[P01] 生成 UUID
来源：http://dali.cucudq.cn/Article/details/gtgqxnyxau.html

Py:   str(uuid.uuid4())
来源：http://dali.dianchejie.cn/Article/details/gtrikfieds.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.c1oappe.top/Article/details/gtsgadnuxv.html

JS:   crypto.randomUUID()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmkvxufjh.html

TS:   crypto.randomUUID()
来源：http://dali.yuxming.cn/Article/details/gtjrbokonp.html

Java: UUID.randomUUID().toString()
来源：http://dali.0kj1m.cn/Article/details/gtvbxyuafq.html

Go:   // 用 github.com/google/uuid
来源：http://dali.guowangkeji.top/Article/details/gtluyqcdta.html

Ruby: SecureRandom.uuid
来源：http://dali.nanxinkj.top/Article/details/gtfwazzzlj.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.ehwqpu.com/Article/details/gtgoginyul.html

[P02] MD5 / SHA256 摘要
来源：http://dali.kuanghao11.cn/Article/details/gtmjbxpcrl.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.guowangkeji.top/Article/details/gtbptwccmr.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.mhx1999.top/Article/details/gtlgrnvxzo.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.wangdashe.top/Article/details/gtptsauuuu.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.fzhhl.top/Article/details/gtgimvcrnq.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.jinqigufen.top/Article/details/gtguevazjj.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.andypj.xyz/Article/details/gtonlrbpvt.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.feifeiyinyue.top/Article/details/gtwgmtcydq.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.hongshengwenyu.top/Article/details/gtxixxrygj.html

[P03] 生成短随机字符串
来源：http://dali.yueranfly.top/Article/details/gtwykvgvcu.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.tian-w.cn/Article/details/gtdamsgeoj.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.snrcjt.cn/Article/details/gtxrmaxebv.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.svipenyu.cn/Article/details/gtvixszjao.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.shanyushiyangtech.top/Article/details/gtjqgrrhzs.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.jianghu66.top/Article/details/gttmytckal.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.ydzc1.top/Article/details/gtljrjglfp.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.jinqigfzy.top/Article/details/gtcdlyvmbb.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhoulong.xyz/Article/details/gtxllnvkyl.html

[P04] 求长度
来源：http://dali.hnqzz.top/Article/details/gtiicdmawr.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.hnxiangtu.top/Article/details/gtbelwrfrc.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.dashuyun.cn/Article/details/gtqlsdpijr.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.ydzc1.top/Article/details/gtuvihfosp.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yuanzhike.top/Article/details/gtfwnfoxkn.html

Java: list.size();  map.size();  s.length()
来源：http://dali.ybcxt.top/Article/details/gtwtfqllfb.html

Go:   len(arr);  len(m)
来源：http://dali.dianchejie.cn/Article/details/gtbxuygrrq.html

Ruby: x.length;  x.size
来源：http://dali.cdnleiting.top/Article/details/gttutkwwdg.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.jqgufenzy.top/Article/details/gtnlqsjdvd.html

[P05] 判断两个对象内容是否相等
来源：http://dali.ivvv.top/Article/details/gtnpuwnqlz.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgiotyemy.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.sysykeji.top/Article/details/gtpnxipsih.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.ehwqpu.com/Article/details/gtrcsppzxs.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.feifeiyinyue.top/Article/details/gttzdxwcbk.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.wangshuangyany.cn/Article/details/gtmizvljqk.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.svipenyu.cn/Article/details/gtovczkljm.html

Ruby: a == b
来源：http://dali.shanyushiyangkeji.top/Article/details/gttydlppma.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zycfv.cn/Article/details/gtfglueveo.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.jlsjyb.cn/Article/details/gtnbfbnxfz.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.nanxinkj.top/Article/details/gtnbibeckt.html

PHP:  if (empty($x)) {}
来源：http://dali.gzhubu.top/Article/details/gtsknuxhmk.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.0kj1m.cn/Article/details/gtqajegrqg.html

TS:   if (x == null) {}
来源：http://dali.yj20258888.top/Article/details/gttioncfwk.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtzurxxroj.html

Go:   if x == nil {}
来源：http://dali.xziqi.cn/Article/details/gtzlzvvjsq.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.vqdsnc.cn/Article/details/gtxfnrykre.html

C#:   if (x is null) {}
来源：http://dali.gaohongyu789.top/Article/details/gtnrietiea.html

[P07] 防抖与节流
来源：http://dali.ehwqpu.com/Article/details/gtsygpcimw.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.redwolf501.top/Article/details/gtmxuqvwku.html

PHP:  // 手写时间戳比较
来源：http://dali.yj202588.top/Article/details/gtpiaxewmx.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yj20258.top/Article/details/gtvzmnvjsr.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.fengsongda.top/Article/details/gtaekppniv.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.aibaodan.cn/Article/details/gtizjkpjzh.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.yvedp.cn/Article/details/gtytxsyybf.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.shuidangran.top/Article/details/gtdqxzmswb.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.9152youxi.cn/Article/details/gtqjszyvtu.html

[P08] 处理浮点精度问题
来源：http://dali.gaohongyu789.top/Article/details/gtreazamfr.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.c1oappe.top/Article/details/gtviecskqh.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.aizwys.cn/Article/details/gttereqsgy.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.yj20258888.top/Article/details/gttyqgarjw.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.guannengcc.top/Article/details/gtacygfxac.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.yonumen.top/Article/details/gtriowscej.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwyotfrsq.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zycfv.cn/Article/details/gtpmfzfdkx.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.jiagoushi.top/Article/details/gtgdwqpnym.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtwhpjdvba.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.kuanghao11.cn/Article/details/gtlowicrnx.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtcgdigdwf.html

[Q01] 创建表
来源：http://dali.yuxming.cn/Article/details/gtschmonuk.html

CREATE TABLE users (
来源：http://dali.hysaishi.cn/Article/details/gtemdegzlo.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.ivvv.top/Article/details/gtpbihgbim.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gtfnmqkvrj.html

email VARCHAR(100) UNIQUE,
来源：http://dali.shanyushiyangtech.top/Article/details/gtvvbgyewu.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhongyouzk.top/Article/details/gtqwtgkqqu.html

);
来源：http://dali.quarkkingdee.top/Article/details/gtyzkrduur.html

[Q02] 创建带外键的表
来源：http://dali.fengsongda.top/Article/details/gtztodrdcs.html

CREATE TABLE orders (
来源：http://dali.yuanzhike.top/Article/details/gtcglqqwyj.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.wangshuangyany.cn/Article/details/gtcvyqrwwa.html

user_id INT NOT NULL,
来源：http://dali.jyoumei.cn/Article/details/gtlbhjdqxu.html

amount DECIMAL(10, 2),
来源：http://dali.yj202588.top/Article/details/gtoqybgffx.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.quarkkingdee.top/Article/details/gttacrrbrd.html

);
来源：http://dali.jlsjyb.cn/Article/details/gtlszupcoa.html

[Q03] 增加列
来源：http://dali.yuxming.cn/Article/details/gtddczjaya.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.0kj1m.cn/Article/details/gtgyntibhh.html

[Q04] 修改列类型
来源：http://dali.cashguo.top/Article/details/gtbrevyxrp.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.chenlongwang.top/Article/details/gtaivxausr.html

[Q05] 重命名列
来源：http://dali.pycfn.com/Article/details/gtztyrzkkb.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.dashuyun.cn/Article/details/gtdyqdisaf.html

[Q06] 删除列
来源：http://dali.sweek.top/Article/details/gtwfaxweqh.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.shanyushiyangtech.top/Article/details/gtqyhiyrfx.html

[Q07] 删除表
来源：http://dali.nanxuanxn.top/Article/details/gtebofdrar.html

DROP TABLE IF EXISTS orders;
来源：http://dali.yanxiufei.cn/Article/details/gtzfgugztv.html

[Q08] 创建普通索引
来源：http://dali.andypj.xyz/Article/details/gtdjadwdfj.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsskxbvvf.html

[Q09] 创建唯一索引
来源：http://dali.cdnleiting.top/Article/details/gtiehsdluz.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.mhx1999.top/Article/details/gtrdjxbhsx.html

[Q10] 插入单行
来源：http://dali.yuanzhike.top/Article/details/gtzeqafwux.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.bjfxy.top/Article/details/gtdybcjhts.html

[Q11] 一次插入多行
来源：http://dali.svipenyu.cn/Article/details/gtajrtsewb.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.hfpthk.cn/Article/details/gtnsnpfdst.html

[Q12] 插入后取自增 ID
来源：http://dali.hnqzz.top/Article/details/gtbrgftmyf.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.9152youxi.cn/Article/details/gtnqaqgwva.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.shanyushiyangtech.top/Article/details/gtztailmbt.html

[Q13] 忽略重复插入
来源：http://dali.kuanghao11.cn/Article/details/gtzpsoaver.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.hysaishi.cn/Article/details/gtcldcictk.html

[Q14] 存在则更新（upsert）
来源：http://dali.redwolf501.top/Article/details/gtanwsodxn.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.kuanghao11.cn/Article/details/gtpfjjvvbv.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.hammf.cn/Article/details/gthfvqnquv.html

[Q15] 查询全部
来源：http://dali.redwolf501.top/Article/details/gtlqvwgzea.html

SELECT * FROM users;
来源：http://dali.cheryme.top/Article/details/gtifylvogw.html

[Q16] 查询指定列
来源：http://dali.yj202588.top/Article/details/gttennreeu.html

SELECT id, name FROM users;
来源：http://dali.yuanzhike.top/Article/details/gtzhukeoid.html

[Q17] 条件查询
来源：http://dali.cucudq.cn/Article/details/gtlocqqxwf.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.nanxuanxn.top/Article/details/gteogodcrp.html

[Q18] 模糊匹配
来源：http://dali.yonumen.top/Article/details/gttqavvovx.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.pycfn.com/Article/details/gtydgzxakz.html

[Q19] 范围查询
来源：http://dali.hysaishi.cn/Article/details/gtedjqnllb.html


<!-- 参考信息 -->