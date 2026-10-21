代发 wailian999

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.ydzc1.top/Article/details/gtlfeppgdd.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtgbrrlwcx.html

N. 数据结构与算法
来源：http://dali.hongshengwenyu.top/Article/details/gtdgxqsuyx.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gturenjpvo.html

[N01] 二分查找（有序数组）
来源：http://dali.sxryk.cn/Article/details/gtanylqgqm.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.guannengcc.top/Article/details/gtkmhqbxik.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.hfpthk.cn/Article/details/gtfxzusnvt.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yonumen.top/Article/details/gtrgfpahgg.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jqgufenzy.top/Article/details/gtnglsxjdx.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.mhx1999.top/Article/details/gtsgwafmoc.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.andypj.xyz/Article/details/gtlusdasvs.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.jianghu66.top/Article/details/gthreifxog.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.xuanzx.com/Article/details/gtszxnwevi.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.dianchejie.cn/Article/details/gtugggkaia.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.shangyingyoupin.top/Article/details/gtcpxaebty.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.guowangkeji.top/Article/details/gtzvdujaec.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtocipalft.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yj20258.top/Article/details/gtoqiwqaor.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.smart0.xyz/Article/details/gtbmmhdpbf.html

Go:   slices.Sort(arr)
来源：http://dali.sweek.top/Article/details/gtlrolwppg.html

Ruby: arr.sort
来源：http://dali.yonumen.top/Article/details/gtluyrsuvc.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.jinqigfzy.top/Article/details/gtcnzwweny.html

[N03] 快速排序（分治示例）
来源：http://dali.pengpengdd.cyou/Article/details/gtuqnvdxpk.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.yvedp.cn/Article/details/gtiiecmspn.html

PHP:  // 递归实现，或用 usort
来源：http://dali.redwolf501.top/Article/details/gtugihlekp.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gtniflakbu.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.wangshuangyany.cn/Article/details/gtdojcucnf.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.vqdsnc.cn/Article/details/gtparotpnr.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.hfpthk.cn/Article/details/gtbwpzybuv.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.shzxlz.cn/Article/details/gtrpuzhhwr.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.daxiang520.top/Article/details/gteespqroo.html

[N04] 斐波那契数列
来源：http://dali.jinyuanbaomall.cn/Article/details/gttolgrdry.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.haohaochexian.top/Article/details/gtuvnntuwk.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gtiiivsqbz.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.xuanzx.com/Article/details/gtmxsunklt.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.chenjidiqi.icu/Article/details/gtdplviulx.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.andypj.xyz/Article/details/gttpitnlut.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.nanxinkj.top/Article/details/gtomfglffs.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.daxiang520.top/Article/details/gtxkftpskm.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.pengpengdd.cyou/Article/details/gtkzfpdgqf.html

[N05] 最大公约数
来源：http://dali.birdmap.top/Article/details/gtuovszvks.html

Py:   math.gcd(a, b)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcftegrlu.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.chenlongwang.top/Article/details/gtodfcpsgk.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.feifeiyinyue.top/Article/details/gtpeshmhfa.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yanxiufei.cn/Article/details/gtlwbzmfep.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.quarkkingdee.top/Article/details/gtgwwgyzvb.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.guowangkeji.top/Article/details/gtnwmfabns.html

Ruby: a.gcd(b)
来源：http://dali.nwbrower.top/Article/details/gtrrdifxbi.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.tanke756.top/Article/details/gtmpdqmqhn.html

[N06] 判断回文字符串
来源：http://dali.fengsongda.top/Article/details/gtpozmjmxc.html

Py:   s == s[::-1]
来源：http://dali.yvedp.cn/Article/details/gthmqhzpls.html

PHP:  $s === strrev($s);
来源：http://dali.vqdsnc.cn/Article/details/gtpceddjsy.html

JS:   s === [...s].reverse().join("")
来源：http://dali.jiagoushi.top/Article/details/gttshjvhbb.html

TS:   s === [...s].reverse().join("")
来源：http://dali.yongpay.top/Article/details/gtuksgwwaw.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.yvedp.cn/Article/details/gtplilcdjo.html

Go:   // 双指针从两端比较
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtchlrolpk.html

Ruby: s == s.reverse
来源：http://dali.nanxinkj.top/Article/details/gtvudbituk.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.hammf.cn/Article/details/gtqjlzqrlk.html

[N07] 两数之和（返回下标）
来源：http://dali.9152youxi.cn/Article/details/gtvcpqhoaz.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.ybcxt.top/Article/details/gtlzulbwoy.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zdqjudy.top/Article/details/gtmebmtbfz.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.birdmap.top/Article/details/gtgeuturcs.html

TS:   // 手写 Map<string, number>
来源：http://dali.yj202588.top/Article/details/gtxbiobgwg.html

Java: // 手写 HashMap
来源：http://dali.guannengcc.top/Article/details/gtltmdgtrt.html

Go:   // 手写 map[int]int
来源：http://dali.andypj.xyz/Article/details/gtmvyobpth.html

Ruby: // 手写 Hash
来源：http://dali.ivvv.top/Article/details/gtxaqcfaey.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.hnqzz.top/Article/details/gttxorgnpe.html

[N08] 生成全排列
来源：http://dali.hysaishi.cn/Article/details/gtrnremyyn.html

Py:   itertools.permutations(arr)
来源：http://dali.hywenlv.cn/Article/details/gtxlxekjzb.html

PHP:  // 手写递归交换
来源：http://dali.birdmap.top/Article/details/gteqhwxyfb.html

JS:   // 手写回溯递归
来源：http://dali.cqqwz.cn/Article/details/gtqisauuav.html

TS:   // 手写回溯递归
来源：http://dali.fzhhl.top/Article/details/gthcoslorj.html

Java: // 手写回溯递归
来源：http://dali.zhongyouzk.top/Article/details/gtrdzhdnsr.html

Go:   // 手写回溯递归
来源：http://dali.jiagoushi.top/Article/details/gtnqhkcyec.html

Ruby: arr.permutation.to_a
来源：http://dali.zhoulong.xyz/Article/details/gtvtzokrly.html

C#:   // 手写回溯递归
来源：http://dali.hongshengwenyu.top/Article/details/gtmaroqcvz.html

[N09] 栈与队列
来源：http://dali.zhixingplan.top/Article/details/gtgdgoqagj.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.meibo888.top/Article/details/gtpynxfwpj.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.gaohongyu789.top/Article/details/gtuwpaufrl.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.cucudq.cn/Article/details/gttryokrih.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.jiagoushi.top/Article/details/gtddlorgfj.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.yuanzhike.top/Article/details/gtphndnqxn.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhixingplan.top/Article/details/gtqtyagwuv.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.hnqzz.top/Article/details/gtggyaqxwg.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.chenjidiqi.icu/Article/details/gttfnkrylh.html

[N10] 链表节点定义
来源：http://dali.yj20258.top/Article/details/gtlnrotmnt.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.iojbl.cn/Article/details/gtndjebtow.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.aizwys.cn/Article/details/gtgpmivfhe.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.quarkkingdee.top/Article/details/gtjnbdfjlq.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.cdnleiting.top/Article/details/gtnmegskph.html

Java: class Node { int v; Node next; }
来源：http://dali.yueranfly.top/Article/details/gtklclkouo.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.haohaochexian.top/Article/details/gtkmieufcf.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.svipenyu.cn/Article/details/gtxvfdkecp.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.svipenyu.cn/Article/details/gtiqshzypu.html

[N11] 二叉树中序遍历
来源：http://dali.hammf.cn/Article/details/gtwmfkjgph.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.mhx1999.top/Article/details/gtkennxzvf.html

PHP:  // 手写递归函数
来源：http://dali.yj202588.top/Article/details/gtlvkkiphs.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.daria6918.cn/Article/details/gtmgloteko.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.chenlongwang.top/Article/details/gtfnltjuqq.html

Java: // 手写递归
来源：http://dali.sxryk.cn/Article/details/gtpfdcshhl.html

Go:   // 手写递归
来源：http://dali.cqqwz.cn/Article/details/gtpgaimagh.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.cheryme.top/Article/details/gtdkvsaluy.html

C#:   // 手写递归
来源：http://dali.aizwys.cn/Article/details/gtslquhzbg.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.xuetiantiany.cn/Article/details/gtcpbvypkr.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.mhx1999.top/Article/details/gtkqcqutdo.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.wangdashe.top/Article/details/gttbnobbfi.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.daria6918.cn/Article/details/gtkezpcqpd.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yj20258.top/Article/details/gtbnkhsrsm.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.shanyushiyangtech.top/Article/details/gtmfhcyytk.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyuviikpy.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.jlsjyb.cn/Article/details/gtojdchgyk.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zycfv.cn/Article/details/gtgtihziil.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtdzpbwkmc.html

O. 并发与异步
来源：http://dali.tianlin.xyz/Article/details/gtblbigomw.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtnkjlnmca.html

[O01] 启动一个线程
来源：http://dali.hysaishi.cn/Article/details/gthurpoxhm.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.aizwys.cn/Article/details/gtumjlurfz.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zycfv.cn/Article/details/gtlynxlanf.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnrlgjtqb.html

TS:   // 同 JS
来源：http://dali.aibaodan.cn/Article/details/gtuloijkbj.html

Java: new Thread(() -> f()).start()
来源：http://dali.yuanzhike.top/Article/details/gtqhligjua.html

Go:   go f()
来源：http://dali.fengsongda.top/Article/details/gtxyeipuof.html

Ruby: Thread.new { f }
来源：http://dali.birdmap.top/Article/details/gttgiijydb.html

C#:   Task.Run(() => F());
来源：http://dali.zhongyouzk.top/Article/details/gtlftlzhmg.html

[O02] 使用线程池
来源：http://dali.redwolf501.top/Article/details/gtlitexkwh.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.gaohongyu789.top/Article/details/gtajltqlst.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.yangfankeji.com/Article/details/gteqaqnpeq.html

JS:   // worker_threads 线程池
来源：http://dali.cashguo.top/Article/details/gtzyeirgtg.html

TS:   // worker_threads 线程池
来源：http://dali.c1oappe.top/Article/details/gtaejprala.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhengqikj.top/Article/details/gtchfsqwnx.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.sweek.top/Article/details/gtpnigzwro.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.jinqigfzy.top/Article/details/gtnltdgmkc.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.fzhhl.top/Article/details/gtmrfilkiy.html

[O03] 加锁保护共享数据
来源：http://dali.tian-w.cn/Article/details/gtauziymvh.html

Py:   with lock: shared += 1
来源：http://dali.nanxuanxn.top/Article/details/gtpupkoacy.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.yj20258.top/Article/details/gtwwncshdn.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.hfpthk.cn/Article/details/gtwdjlpyex.html

TS:   // 同 JS
来源：http://dali.cqqwz.cn/Article/details/gtloqshddu.html

Java: synchronized (this) { shared++; }
来源：http://dali.tanke756.top/Article/details/gtryyzsskb.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.gogol.net.cn/Article/details/gtcwrjqcvm.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.bjfxy.top/Article/details/gtrwugewfv.html

C#:   lock (gate) { shared++; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkoymiuao.html

[O04] 定义异步函数并等待
来源：http://dali.sweek.top/Article/details/gtwxqdoscj.html

Py:   async def f():⏎    await g()
来源：http://dali.zdqjudy.top/Article/details/gtpgwivuvl.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.pycfn.com/Article/details/gtdgbflmxd.html

JS:   async function f() { await g(); }
来源：http://dali.yanxiufei.cn/Article/details/gtsqidsnpp.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.xuanzx.com/Article/details/gtcdbcckyw.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.gzhubu.top/Article/details/gtfqplpyii.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.ehwqpu.com/Article/details/gtpwxromrn.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.havefunace.top/Article/details/gtgfxgiblg.html

C#:   async Task F() { await G(); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gttmoerhlj.html

[O05] 并发执行并等待全部完成
来源：http://dali.jiagoushi.top/Article/details/gtkwfndjvo.html

Py:   asyncio.gather(*tasks)
来源：http://dali.yanxiufei.cn/Article/details/gtdemqqige.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.hfpthk.cn/Article/details/gtehoqkieu.html

JS:   await Promise.all(tasks)
来源：http://dali.gogol.net.cn/Article/details/gtiddkcgeg.html

TS:   await Promise.all(tasks)
来源：http://dali.yj202588.top/Article/details/gtanpywwhg.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.smart0.xyz/Article/details/gtlirvstwa.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.nanxuanxn.top/Article/details/gtwvepsboq.html

Ruby: threads.map(&:join)
来源：http://dali.yongpay.top/Article/details/gtaoytgzfq.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhixingplan.top/Article/details/gtxpmziize.html

[O06] 使用进程池
来源：http://dali.hfpthk.cn/Article/details/gthgnbagxw.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.tian-w.cn/Article/details/gtcaagpdmv.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.nanxinkj.top/Article/details/gtpetutctl.html

JS:   // child_process / cluster 模块
来源：http://dali.yanxiufei.cn/Article/details/gtununhdeu.html

TS:   // child_process / cluster 模块
来源：http://dali.gotoacloud.top/Article/details/gtsyporzjb.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.gzhubu.top/Article/details/gtknfefgua.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.sweek.top/Article/details/gtdwaxndxu.html

Ruby: // fork 块
来源：http://dali.yj20258.top/Article/details/gtoshhptdc.html

C#:   Parallel.For
来源：http://dali.jianghu66.top/Article/details/gtwfkylvsy.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtwmbrqgtt.html

P. 常用工具函数
来源：http://dali.c1oappe.top/Article/details/gtitlhxuvc.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtlsyzqgij.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gtpqecqbny.html

Py:   str(uuid.uuid4())
来源：http://dali.jinqigufen.top/Article/details/gtxydqqevz.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.jlsjyb.cn/Article/details/gtqnjpchjs.html

JS:   crypto.randomUUID()
来源：http://dali.cucudq.cn/Article/details/gtpbpwfjih.html

TS:   crypto.randomUUID()
来源：http://dali.c1oappe.top/Article/details/gtisjzhhrl.html

Java: UUID.randomUUID().toString()
来源：http://dali.hongshengwenyu.top/Article/details/gtduuypykf.html

Go:   // 用 github.com/google/uuid
来源：http://dali.ehwqpu.com/Article/details/gtzzfjvffl.html

Ruby: SecureRandom.uuid
来源：http://dali.daxiang520.top/Article/details/gtwftmftuq.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gtixlqlcyr.html

[P02] MD5 / SHA256 摘要
来源：http://dali.c1oappe.top/Article/details/gtqjpskhvm.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.hysaishi.cn/Article/details/gtonsbgvzk.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.meibo888.top/Article/details/gtmgrdhtaq.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.cucudq.cn/Article/details/gtncovbzdo.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.hywenlv.cn/Article/details/gtdowargje.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.yuxming.cn/Article/details/gtazfofrba.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.daria6918.cn/Article/details/gthsyneavi.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.jiagoushi.top/Article/details/gtgluemdbo.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthvjiqbys.html

[P03] 生成短随机字符串
来源：http://dali.zhengqikj.top/Article/details/gtivganmfw.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.yangfankeji.com/Article/details/gtivskhswl.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.cucudq.cn/Article/details/gtmzrfibrh.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.cqqwz.cn/Article/details/gtkysaoncc.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.ehwqpu.com/Article/details/gtltxfyxxa.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.yvedp.cn/Article/details/gtsqmvtoia.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.jiagoushi.top/Article/details/gtpktttdou.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.havefunace.top/Article/details/gtezkghvkd.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.chenzaomai.com/Article/details/gtzetekrva.html

[P04] 求长度
来源：http://dali.gotoacloud.top/Article/details/gtthvcgecv.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.chenlongwang.top/Article/details/gtnozdigih.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.cqqwz.cn/Article/details/gtikoccteb.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.sufxvd.cn/Article/details/gtpmknnjpa.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.c1oappe.top/Article/details/gtjdbkrnco.html

Java: list.size();  map.size();  s.length()
来源：http://dali.ydzc1.top/Article/details/gtoedhlzzo.html

Go:   len(arr);  len(m)
来源：http://dali.bjfxy.top/Article/details/gtzmxwvslz.html

Ruby: x.length;  x.size
来源：http://dali.zhiwuduotai.top/Article/details/gthgjrcquf.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.jqgfzy.top/Article/details/gtbndltcma.html

[P05] 判断两个对象内容是否相等
来源：http://dali.vqdsnc.cn/Article/details/gtnmtxcqwr.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.hnxiangtu.top/Article/details/gtowryadgv.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.shzxlz.cn/Article/details/gtniwtcvxb.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.meibo888.top/Article/details/gtgbnerpys.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhiwuduotai.top/Article/details/gtyorlrzyd.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.jqgfzy.top/Article/details/gttlakngcd.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.hysaishi.cn/Article/details/gtfwyvifrt.html

Ruby: a == b
来源：http://dali.jinqigufen.top/Article/details/gtvyyywpcy.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.yongpay.top/Article/details/gtbdibigqk.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.jyoumei.cn/Article/details/gtkqkjujsb.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.nwbrower.top/Article/details/gtcziegsww.html

PHP:  if (empty($x)) {}
来源：http://dali.sxryk.cn/Article/details/gtddatnlyo.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.yvedp.cn/Article/details/gtespewuir.html

TS:   if (x == null) {}
来源：http://dali.zhengqikj.top/Article/details/gtilevkyqw.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.hfpthk.cn/Article/details/gtmsxwvkqm.html

Go:   if x == nil {}
来源：http://dali.xuanzx.com/Article/details/gtzzvuntrp.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.kuanghao11.cn/Article/details/gtbmnsmbbi.html

C#:   if (x is null) {}
来源：http://dali.iojbl.cn/Article/details/gtpkryazrw.html

[P07] 防抖与节流
来源：http://dali.zhongyouzk.top/Article/details/gtztinbnfs.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.ivvv.top/Article/details/gtwxjmxokn.html

PHP:  // 手写时间戳比较
来源：http://dali.feifeiyinyue.top/Article/details/gtlpjqcfnd.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hammf.cn/Article/details/gtctajonei.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.nwbrower.top/Article/details/gtdfqhfoon.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.chenlongwang.top/Article/details/gtljvzsxoi.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.ppjwa.cn/Article/details/gtlqwkrrut.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.svipenyu.cn/Article/details/gthlpcgwmy.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.sysykeji.top/Article/details/gtamdwvpal.html

[P08] 处理浮点精度问题
来源：http://dali.yuanzhike.top/Article/details/gtcbcaxyhx.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.tian-w.cn/Article/details/gtacwdfzjk.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zycfv.cn/Article/details/gtfldkgspt.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.sysykeji.top/Article/details/gtpzvfgjos.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.hysaishi.cn/Article/details/gtgcywxvwr.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.shzxlz.cn/Article/details/gtfseexxtb.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.hongshengwenyu.top/Article/details/gtndurgzvq.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.shzxlz.cn/Article/details/gthdqdrkyv.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.yj20258888.top/Article/details/gttftqpjeo.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtamgmnxyu.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtscxeavmd.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtyyhfhijl.html

[Q01] 创建表
来源：http://dali.birdmap.top/Article/details/gtzqhyldfi.html

CREATE TABLE users (
来源：http://dali.sysykeji.top/Article/details/gthmmsvbva.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.aibaodan.cn/Article/details/gtvpowqucj.html

name VARCHAR(50) NOT NULL,
来源：http://dali.jinyuanbaomall.cn/Article/details/gttvyhnypu.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhongyouzk.top/Article/details/gtvbmxqhwi.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.yongpay.top/Article/details/gtfgcnoqmx.html

);
来源：http://dali.hongshengwenyu.top/Article/details/gtbdsyujvh.html

[Q02] 创建带外键的表
来源：http://dali.gaohongyu789.top/Article/details/gttlnwuuyh.html

CREATE TABLE orders (
来源：http://dali.zdqjudy.top/Article/details/gtejhpkaps.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.hnqzz.top/Article/details/gtiblbwzaf.html

user_id INT NOT NULL,
来源：http://dali.birdmap.top/Article/details/gtlyuwsiqn.html

amount DECIMAL(10, 2),
来源：http://dali.hfpthk.cn/Article/details/gtjhyzvwis.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.316326.xyz/Article/details/gtgkwhaljf.html

);
来源：http://dali.ehwqpu.com/Article/details/gtryjiwsjb.html

[Q03] 增加列
来源：http://dali.ywan-chungtsiang.top/Article/details/gthsbmzyye.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.shanyushiyangtech.top/Article/details/gtevjwpsqm.html

[Q04] 修改列类型
来源：http://dali.yongpay.top/Article/details/gtydiextiq.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.wangdashe.top/Article/details/gtmrassxdd.html

[Q05] 重命名列
来源：http://dali.daria6918.cn/Article/details/gtmqgebqum.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.tianlin.xyz/Article/details/gtwstgpzqh.html

[Q06] 删除列
来源：http://dali.gotoacloud.top/Article/details/gtltmkcnxr.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.wangdashe.top/Article/details/gtjtiufody.html

[Q07] 删除表
来源：http://dali.ehwqpu.com/Article/details/gtpisiasxd.html

DROP TABLE IF EXISTS orders;
来源：http://dali.yuanzhike.top/Article/details/gtohrwtvkn.html

[Q08] 创建普通索引
来源：http://dali.yuxming.cn/Article/details/gtksnxlhzn.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.hfpthk.cn/Article/details/gtljtbaati.html

[Q09] 创建唯一索引
来源：http://dali.chenjidiqi.icu/Article/details/gtmuepdttz.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.ehwqpu.com/Article/details/gtozbknebc.html

[Q10] 插入单行
来源：http://dali.jiagoushi.top/Article/details/gtjszypqns.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.cucudq.cn/Article/details/gtrzafctod.html

[Q11] 一次插入多行
来源：http://dali.hysaishi.cn/Article/details/gtfctyacsr.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.jyoumei.cn/Article/details/gtibtbllrd.html

[Q12] 插入后取自增 ID
来源：http://dali.fengsongda.top/Article/details/gtgqpzltwf.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhixingplan.top/Article/details/gtrzvebbpt.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.nanxuanxn.top/Article/details/gtnhdytpgy.html

[Q13] 忽略重复插入
来源：http://dali.zhengqikj.top/Article/details/gtgvcccbkh.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.hammf.cn/Article/details/gtwqrungih.html

[Q14] 存在则更新（upsert）
来源：http://dali.andypj.xyz/Article/details/gtejvdzvut.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.jqgufenzy.top/Article/details/gtvcealomv.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.yongpay.top/Article/details/gtjgvtzize.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gtgdinccfu.html

SELECT * FROM users;
来源：http://dali.yj20258888.top/Article/details/gtbduuazqq.html

[Q16] 查询指定列
来源：http://dali.pycfn.com/Article/details/gtfvsnbylt.html

SELECT id, name FROM users;
来源：http://dali.ivvv.top/Article/details/gtukzdatae.html

[Q17] 条件查询
来源：http://dali.chenjidiqi.icu/Article/details/gtdzewvwfw.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.quarkkingdee.top/Article/details/gtenchdtpu.html

[Q18] 模糊匹配
来源：http://dali.sysykeji.top/Article/details/gtujorgxwm.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvdiftere.html

[Q19] 范围查询
来源：http://dali.redwolf501.top/Article/details/gtzxgopzmv.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtohjzxzin.html

[Q20] IN 列表
来源：http://dali.vqdsnc.cn/Article/details/gtedzxnrac.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.sxryk.cn/Article/details/gttjpshvgk.html

[Q21] 空值判断
来源：http://dali.zhengqikj.top/Article/details/gtytojffbi.html


<!-- 参考信息 -->