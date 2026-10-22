代发 wailian999

TS:   process.platform;  process.version
来源：http://dali.birdmap.top/Article/details/gtscdobfer.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhongyouzk.top/Article/details/gtrbjaodgk.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.birdmap.top/Article/details/gtvelpexph.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.hammf.cn/Article/details/gtiwvfetzq.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.mhx1999.top/Article/details/gtayqpgzzs.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gthwczbwni.html

N. 数据结构与算法
来源：http://dali.zhengqikj.top/Article/details/gtdopbsizt.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gteizzpwej.html

[N01] 二分查找（有序数组）
来源：http://dali.guowangkeji.top/Article/details/gtavrgamyh.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.bjfxy.top/Article/details/gtdefrrtzj.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.birdmap.top/Article/details/gtdsgcpicl.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.9152youxi.cn/Article/details/gtilmnttwu.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoezihzgh.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.aizwys.cn/Article/details/gtbpaflymf.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.gzhubu.top/Article/details/gtrqcsivvz.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.kuanghao11.cn/Article/details/gthyjubcra.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.xuetiantiany.cn/Article/details/gtudmmswcv.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.jlsjyb.cn/Article/details/gtdjwhxudr.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.snrcjt.cn/Article/details/gtetrbgwsi.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.sweek.top/Article/details/gtksuqhtqt.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.iojbl.cn/Article/details/gttyokmcpj.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.nwbrower.top/Article/details/gtevfvapug.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.chenlongwang.top/Article/details/gtvixxdwej.html

Go:   slices.Sort(arr)
来源：http://dali.ybcxt.top/Article/details/gthufhjrpt.html

Ruby: arr.sort
来源：http://dali.sweek.top/Article/details/gtvdgytjff.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfwalvzne.html

[N03] 快速排序（分治示例）
来源：http://dali.meibo888.top/Article/details/gtfmjwbblm.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.dianchejie.cn/Article/details/gtwdaqbcca.html

PHP:  // 递归实现，或用 usort
来源：http://dali.dashuyun.cn/Article/details/gtfmxgwbdr.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhongyouzk.top/Article/details/gtwbwpwass.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.gzhubu.top/Article/details/gtmdkeynbw.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.chenzaomai.com/Article/details/gtoncndvgp.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.ivvv.top/Article/details/gthtlsvwvv.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.bjfxy.top/Article/details/gtywawsino.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.jqgfzy.top/Article/details/gtxwxhtdbj.html

[N04] 斐波那契数列
来源：http://dali.hnqzz.top/Article/details/gtthkqoxgr.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.nwbrower.top/Article/details/gtivroqdvh.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.chenzaomai.com/Article/details/gtchhqgwfb.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.smart0.xyz/Article/details/gtikzbhcbc.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.cqqwz.cn/Article/details/gtnsxsdfdm.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.svipenyu.cn/Article/details/gtwdnsbiby.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.9152youxi.cn/Article/details/gtcwzrgsmn.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.snrcjt.cn/Article/details/gturcversg.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.jinqigfzy.top/Article/details/gtwyfbhurq.html

[N05] 最大公约数
来源：http://dali.jyoumei.cn/Article/details/gtejzfvcyb.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gtousmljol.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwnfzfpuy.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtksvlvszd.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.xuanzx.com/Article/details/gtwmopxtyv.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.ivvv.top/Article/details/gtnaxcyety.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwexiokfc.html

Ruby: a.gcd(b)
来源：http://dali.aibaodan.cn/Article/details/gtodkvwpxq.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.ppjwa.cn/Article/details/gtkfxidqmt.html

[N06] 判断回文字符串
来源：http://dali.yanxiufei.cn/Article/details/gtkzvsgxjf.html

Py:   s == s[::-1]
来源：http://dali.chenlongwang.top/Article/details/gtcfrtnhbs.html

PHP:  $s === strrev($s);
来源：http://dali.jiagoushi.top/Article/details/gtcwctacrk.html

JS:   s === [...s].reverse().join("")
来源：http://dali.kuanghao11.cn/Article/details/gtnkflduei.html

TS:   s === [...s].reverse().join("")
来源：http://dali.tian-w.cn/Article/details/gtvofnzvwr.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhixingplan.top/Article/details/gtimoreegu.html

Go:   // 双指针从两端比较
来源：http://dali.sysykeji.top/Article/details/gtdrocdkae.html

Ruby: s == s.reverse
来源：http://dali.chenjidiqi.icu/Article/details/gtyvfeoluz.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.yvedp.cn/Article/details/gtyujqzcvw.html

[N07] 两数之和（返回下标）
来源：http://dali.shangyingyoupin.top/Article/details/gtyfqxyddg.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.sweek.top/Article/details/gthvcceczs.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.xziqi.cn/Article/details/gtaazfoqmd.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.mhx1999.top/Article/details/gtcgcioxal.html

TS:   // 手写 Map<string, number>
来源：http://dali.yuxming.cn/Article/details/gtucqipvqk.html

Java: // 手写 HashMap
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbzgjvden.html

Go:   // 手写 map[int]int
来源：http://dali.xylfe.cn/Article/details/gtytduyggz.html

Ruby: // 手写 Hash
来源：http://dali.zhongyouzk.top/Article/details/gtwusjfhyl.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.jlsjyb.cn/Article/details/gteqotkzic.html

[N08] 生成全排列
来源：http://dali.nanxinkj.top/Article/details/gtawtcdoko.html

Py:   itertools.permutations(arr)
来源：http://dali.dianchejie.cn/Article/details/gtdvpiohco.html

PHP:  // 手写递归交换
来源：http://dali.gzhubu.top/Article/details/gtkwmlfghh.html

JS:   // 手写回溯递归
来源：http://dali.shangyingyoupin.top/Article/details/gtjhmkjhko.html

TS:   // 手写回溯递归
来源：http://dali.chenjidiqi.icu/Article/details/gtvregpaot.html

Java: // 手写回溯递归
来源：http://dali.chenzaomai.com/Article/details/gtgvfmhywg.html

Go:   // 手写回溯递归
来源：http://dali.ivvv.top/Article/details/gtyhghlydg.html

Ruby: arr.permutation.to_a
来源：http://dali.daria6918.cn/Article/details/gtoxwarccj.html

C#:   // 手写回溯递归
来源：http://dali.xziqi.cn/Article/details/gtnvcfgbqx.html

[N09] 栈与队列
来源：http://dali.xuetiantiany.cn/Article/details/gtajckfrpz.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.chenzaomai.com/Article/details/gtfxxvmfru.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.jinghuilouyu.cn/Article/details/gtskwuhtej.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.jinqigufen.top/Article/details/gtobgrougb.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.ehwqpu.com/Article/details/gtlnqudfpi.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.gzhubu.top/Article/details/gtuqqozlap.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.shzxlz.cn/Article/details/gttitgvimh.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.xuetiantiany.cn/Article/details/gtcsiqkqtt.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhengqikj.top/Article/details/gthbxtoquk.html

[N10] 链表节点定义
来源：http://dali.snrcjt.cn/Article/details/gturrksgzm.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.jlsjyb.cn/Article/details/gtsyjnasmu.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.pengpengdd.cyou/Article/details/gtuwkxpfvl.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.smart0.xyz/Article/details/gtvnerncoe.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.jqgfzy.top/Article/details/gtrrceuiyf.html

Java: class Node { int v; Node next; }
来源：http://dali.daria6918.cn/Article/details/gtevhxcfbx.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.shzxlz.cn/Article/details/gtktpdviut.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.cdnleiting.top/Article/details/gtnrpekdcu.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.guannengcc.top/Article/details/gtdhezrgpj.html

[N11] 二叉树中序遍历
来源：http://dali.pengpengdd.cyou/Article/details/gtprpobzun.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.gotoacloud.top/Article/details/gtmedtiiqu.html

PHP:  // 手写递归函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtesqthskg.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.daxiang520.top/Article/details/gtwqhuroxe.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.daria6918.cn/Article/details/gtojpwnnax.html

Java: // 手写递归
来源：http://dali.hammf.cn/Article/details/gtudtvyail.html

Go:   // 手写递归
来源：http://dali.chenjidiqi.icu/Article/details/gttgahzvbe.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.haohaochexian.top/Article/details/gtmcsqgwhr.html

C#:   // 手写递归
来源：http://dali.yj20258888.top/Article/details/gtgjskxwwu.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.xylfe.cn/Article/details/gthlnhtnfm.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.hammf.cn/Article/details/gtwqcmjgnz.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.cdnleiting.top/Article/details/gtqrtwljis.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.cheryme.top/Article/details/gtpjpbwmbe.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yonumen.top/Article/details/gtxznxlspg.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jqgufenzy.top/Article/details/gtkkjmiaig.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.shangyingyoupin.top/Article/details/gtyabecvoj.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.aizwys.cn/Article/details/gtvpkopkvb.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqzmnemgb.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtlvqdifiv.html

O. 并发与异步
来源：http://dali.shangyingyoupin.top/Article/details/gtzusximiu.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtmfvrggzh.html

[O01] 启动一个线程
来源：http://dali.aibaodan.cn/Article/details/gtroefptrg.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.mhx1999.top/Article/details/gtazhczdum.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.ydzc1.top/Article/details/gtxzmnzqaa.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.c1oappe.top/Article/details/gtrazwjfqe.html

TS:   // 同 JS
来源：http://dali.gaohongyu789.top/Article/details/gtcvlhiatm.html

Java: new Thread(() -> f()).start()
来源：http://dali.xinyue.icu/Article/details/gtqoaxmtie.html

Go:   go f()
来源：http://dali.dianchejie.cn/Article/details/gtaqefmvlp.html

Ruby: Thread.new { f }
来源：http://dali.aizwys.cn/Article/details/gtjfvjwdnu.html

C#:   Task.Run(() => F());
来源：http://dali.cdnleiting.top/Article/details/gtsfhatgtt.html

[O02] 使用线程池
来源：http://dali.gaohongyu789.top/Article/details/gtmozlalxt.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.hammf.cn/Article/details/gtktunrssg.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.yj20258888.top/Article/details/gtccehqsym.html

JS:   // worker_threads 线程池
来源：http://dali.jinqigufen.top/Article/details/gtyqhretec.html

TS:   // worker_threads 线程池
来源：http://dali.haohaochexian.top/Article/details/gtfbfqkozt.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.ybcxt.top/Article/details/gtkcgcjmgq.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.0kj1m.cn/Article/details/gtyxzlzili.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.yvedp.cn/Article/details/gtztugufqj.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.shangyingyoupin.top/Article/details/gtjlwuuqzd.html

[O03] 加锁保护共享数据
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqurxbjtb.html

Py:   with lock: shared += 1
来源：http://dali.chenzaomai.com/Article/details/gtscthgbot.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.c1oappe.top/Article/details/gtpzllimyp.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.sxryk.cn/Article/details/gtmlgikcnq.html

TS:   // 同 JS
来源：http://dali.zhiwuduotai.top/Article/details/gtdfcvomeh.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gtkbxnuzwn.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.yj20258.top/Article/details/gtcbchfofx.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.hongshengwenyu.top/Article/details/gtpxplgdfg.html

C#:   lock (gate) { shared++; }
来源：http://dali.smart0.xyz/Article/details/gtcrypahel.html

[O04] 定义异步函数并等待
来源：http://dali.guannengcc.top/Article/details/gtcbmpzmrc.html

Py:   async def f():⏎    await g()
来源：http://dali.daxiang520.top/Article/details/gtmypkbezb.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.xylfe.cn/Article/details/gtqvkfbmll.html

JS:   async function f() { await g(); }
来源：http://dali.jlsjyb.cn/Article/details/gtjjpgkaux.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.gogol.net.cn/Article/details/gtpqyfsbia.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.yuxming.cn/Article/details/gtghjwrsmr.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.xuetiantiany.cn/Article/details/gtxlwhghym.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.meibo888.top/Article/details/gtdrvjaotx.html

C#:   async Task F() { await G(); }
来源：http://dali.yueranfly.top/Article/details/gtggueqsgv.html

[O05] 并发执行并等待全部完成
来源：http://dali.shanyushiyangkeji.top/Article/details/gtstskmwta.html

Py:   asyncio.gather(*tasks)
来源：http://dali.shanyushiyangtech.top/Article/details/gtsquynnkl.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhixingplan.top/Article/details/gtkhckfjaz.html

JS:   await Promise.all(tasks)
来源：http://dali.kuanghao11.cn/Article/details/gtqhujbfyh.html

TS:   await Promise.all(tasks)
来源：http://dali.chenlongwang.top/Article/details/gtbeukssvh.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.jinqigufen.top/Article/details/gtbxqdfwnx.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.dashuyun.cn/Article/details/gtdzaxgeoy.html

Ruby: threads.map(&:join)
来源：http://dali.guowangkeji.top/Article/details/gtscrsdbdc.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.jianghu66.top/Article/details/gtbymtktmd.html

[O06] 使用进程池
来源：http://dali.fzhhl.top/Article/details/gtbluwjron.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.bjfxy.top/Article/details/gtgqpkudsa.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.redwolf501.top/Article/details/gtfkivfjuz.html

JS:   // child_process / cluster 模块
来源：http://dali.ppjwa.cn/Article/details/gtwkxoyiqv.html

TS:   // child_process / cluster 模块
来源：http://dali.mhx1999.top/Article/details/gtjlzzspcm.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.hywenlv.cn/Article/details/gtsmdfvjdg.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.fzhhl.top/Article/details/gtufnxrizv.html

Ruby: // fork 块
来源：http://dali.hnqzz.top/Article/details/gtxldthkmr.html

C#:   Parallel.For
来源：http://dali.zhixingplan.top/Article/details/gtguxxgjqh.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtyjdjcxro.html

P. 常用工具函数
来源：http://dali.aibaodan.cn/Article/details/gtbmopathn.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtgulvslsq.html

[P01] 生成 UUID
来源：http://dali.quarkkingdee.top/Article/details/gtchhztwng.html

Py:   str(uuid.uuid4())
来源：http://dali.ybcxt.top/Article/details/gteacdhpdt.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.guannengcc.top/Article/details/gttscbpvhj.html

JS:   crypto.randomUUID()
来源：http://dali.cdnleiting.top/Article/details/gttvgjscqs.html

TS:   crypto.randomUUID()
来源：http://dali.xylfe.cn/Article/details/gthgwcmulj.html

Java: UUID.randomUUID().toString()
来源：http://dali.cdnleiting.top/Article/details/gtsyctgnmw.html

Go:   // 用 github.com/google/uuid
来源：http://dali.xziqi.cn/Article/details/gtiyijatun.html

Ruby: SecureRandom.uuid
来源：http://dali.cdnleiting.top/Article/details/gtqklhduwg.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhengqikj.top/Article/details/gtjtnhgymj.html

[P02] MD5 / SHA256 摘要
来源：http://dali.0kj1m.cn/Article/details/gtpcijnukv.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.316326.xyz/Article/details/gtcodjmpul.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.sxryk.cn/Article/details/gtcejejyso.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.hnqzz.top/Article/details/gtqyemurcd.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.cheryme.top/Article/details/gteyxndyyq.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhaomingkeji.xyz/Article/details/gteudyyvzs.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.jyoumei.cn/Article/details/gttprucnxq.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.tanke756.top/Article/details/gteaifnvck.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.gotoacloud.top/Article/details/gtrcldwumw.html

[P03] 生成短随机字符串
来源：http://dali.0kj1m.cn/Article/details/gtfzjdjwvb.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.hywenlv.cn/Article/details/gtyzqqtrlb.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.jianghu66.top/Article/details/gtvesjipdx.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.daxiang520.top/Article/details/gtpyocbipx.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.fengsongda.top/Article/details/gtunphwhwy.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.svipenyu.cn/Article/details/gtdmkgucsf.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.nwbrower.top/Article/details/gtwawsdgsm.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.mhx1999.top/Article/details/gtfjeeempa.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.shangyingyoupin.top/Article/details/gtczlgilsv.html

[P04] 求长度
来源：http://dali.birdmap.top/Article/details/gtpfvmcxdb.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.xziqi.cn/Article/details/gtitefvglm.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.aibaodan.cn/Article/details/gtkmnhjxyp.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.chenlongwang.top/Article/details/gtzdnxskrm.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jinghuilouyu.cn/Article/details/gtfficylnf.html

Java: list.size();  map.size();  s.length()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlyrdsugh.html

Go:   len(arr);  len(m)
来源：http://dali.chenjidiqi.icu/Article/details/gtsyexdnfz.html

Ruby: x.length;  x.size
来源：http://dali.jyoumei.cn/Article/details/gtlfrcafpj.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.smart0.xyz/Article/details/gtjyczwtsx.html

[P05] 判断两个对象内容是否相等
来源：http://dali.jlsjyb.cn/Article/details/gtukhcnxjw.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.xinyue.icu/Article/details/gtdbgjwqrv.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.bjfxy.top/Article/details/gtareyievj.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.daria6918.cn/Article/details/gteydmffbk.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.jyoumei.cn/Article/details/gtvxuxmifh.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.ydzc1.top/Article/details/gtrxdqwwgn.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.hnqzz.top/Article/details/gtwtcuzkcp.html

Ruby: a == b
来源：http://dali.guowangkeji.top/Article/details/gtxalzhuus.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.cucudq.cn/Article/details/gtapdwpvmy.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.haohaochexian.top/Article/details/gtqzsvzezx.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.fzhhl.top/Article/details/gttxwwhxcy.html

PHP:  if (empty($x)) {}
来源：http://dali.9152youxi.cn/Article/details/gtqegrxjjn.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.yueranfly.top/Article/details/gtxgozrbtt.html

TS:   if (x == null) {}
来源：http://dali.yj20258888.top/Article/details/gtnebjmynl.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.yonumen.top/Article/details/gtieqdxldg.html

Go:   if x == nil {}
来源：http://dali.hammf.cn/Article/details/gtbmfhytav.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhengqikj.top/Article/details/gtfcedcltv.html

C#:   if (x is null) {}
来源：http://dali.chenjidiqi.icu/Article/details/gtzzasabgr.html

[P07] 防抖与节流
来源：http://dali.ehwqpu.com/Article/details/gtnnpmhygn.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.xylfe.cn/Article/details/gtursdcqyo.html

PHP:  // 手写时间戳比较
来源：http://dali.hywenlv.cn/Article/details/gtqixcvwca.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.quarkkingdee.top/Article/details/gttvylnitm.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yangfankeji.com/Article/details/gtbqmoisep.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.yuanzhike.top/Article/details/gtywhmnvua.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.birdmap.top/Article/details/gtevbalpds.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.haohaochexian.top/Article/details/gtnnhfjnqi.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.gogol.net.cn/Article/details/gthjogppsa.html

[P08] 处理浮点精度问题
来源：http://dali.redwolf501.top/Article/details/gtlhpaqzus.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.yangfankeji.com/Article/details/gtnhsxgcnp.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.wangdashe.top/Article/details/gtcvqnkfdb.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.ehwqpu.com/Article/details/gtnldpnznb.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.c1oappe.top/Article/details/gtfcalgkbo.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhiwuduotai.top/Article/details/gtlmwtekzv.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.ybcxt.top/Article/details/gtwskuzbor.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.cashguo.top/Article/details/gtqztwqphc.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.tanke756.top/Article/details/gtkgxoxscn.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gthjefialt.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.shuidangran.top/Article/details/gtxltioywp.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtqwjgrohk.html

[Q01] 创建表
来源：http://dali.sxryk.cn/Article/details/gtvpqrwtqs.html

CREATE TABLE users (
来源：http://dali.chenlongwang.top/Article/details/gtmihxunfb.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yanxiufei.cn/Article/details/gtoymklrhu.html

name VARCHAR(50) NOT NULL,
来源：http://dali.jinghuilouyu.cn/Article/details/gtwvfjeqvb.html

email VARCHAR(100) UNIQUE,
来源：http://dali.tianlin.xyz/Article/details/gtthckntmy.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.fzhhl.top/Article/details/gtjmugpvzi.html

);
来源：http://dali.redwolf501.top/Article/details/gtdzvyftit.html

[Q02] 创建带外键的表
来源：http://dali.jqgufenzy.top/Article/details/gtnuknqtit.html

CREATE TABLE orders (
来源：http://dali.redwolf501.top/Article/details/gtfezouwrh.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.ehwqpu.com/Article/details/gtokdsgtye.html

user_id INT NOT NULL,
来源：http://dali.haohaochexian.top/Article/details/gthkacbzjc.html

amount DECIMAL(10, 2),
来源：http://dali.hammf.cn/Article/details/gtoqrnphhv.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.jiagoushi.top/Article/details/gtoofwnpbl.html

);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmggqrfly.html

[Q03] 增加列
来源：http://dali.tianlin.xyz/Article/details/gtkwvxuyaq.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.smart0.xyz/Article/details/gtzkdqxemb.html

[Q04] 修改列类型
来源：http://dali.chenlongwang.top/Article/details/gtjihwjkjg.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.jinghuilouyu.cn/Article/details/gtgmphoizq.html

[Q05] 重命名列
来源：http://dali.haohaochexian.top/Article/details/gtfmaqaiok.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.kuanghao11.cn/Article/details/gtuvvnemxg.html

[Q06] 删除列
来源：http://dali.hongshengwenyu.top/Article/details/gtczmzpkca.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.gaohongyu789.top/Article/details/gtoybfojpc.html

[Q07] 删除表
来源：http://dali.ehwqpu.com/Article/details/gtxdiurwfa.html

DROP TABLE IF EXISTS orders;
来源：http://dali.meibo888.top/Article/details/gtvhbatcwf.html

[Q08] 创建普通索引
来源：http://dali.xuetiantiany.cn/Article/details/gtszvrqegh.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.daria6918.cn/Article/details/gteryvquxr.html

[Q09] 创建唯一索引
来源：http://dali.sxryk.cn/Article/details/gtnskcqyop.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.xziqi.cn/Article/details/gtadhecsst.html

[Q10] 插入单行
来源：http://dali.jyoumei.cn/Article/details/gteowvsryx.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.wangdashe.top/Article/details/gtreddhbhv.html

[Q11] 一次插入多行
来源：http://dali.xuetiantiany.cn/Article/details/gtryylsrwd.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhiwuduotai.top/Article/details/gtvvqhpsvm.html

[Q12] 插入后取自增 ID
来源：http://dali.jyoumei.cn/Article/details/gtqvcdbrcb.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.ivvv.top/Article/details/gtodezzjwq.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.smart0.xyz/Article/details/gtggsahcup.html

[Q13] 忽略重复插入
来源：http://dali.9152youxi.cn/Article/details/gtgmeilypj.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.tanke756.top/Article/details/gtrflegwhr.html

[Q14] 存在则更新（upsert）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfxasxrrm.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.nanxuanxn.top/Article/details/gtlxrckgql.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.cashguo.top/Article/details/gtqcmjsdxo.html

[Q15] 查询全部
来源：http://dali.zhixingplan.top/Article/details/gtpnaygimz.html

SELECT * FROM users;
来源：http://dali.daria6918.cn/Article/details/gtzjzrwpcq.html

[Q16] 查询指定列
来源：http://dali.nanxuanxn.top/Article/details/gtxvmcxczx.html

SELECT id, name FROM users;
来源：http://dali.cqqwz.cn/Article/details/gtlrustfti.html

[Q17] 条件查询
来源：http://dali.guannengcc.top/Article/details/gtrpfpdake.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.hnqzz.top/Article/details/gthutehjoa.html

[Q18] 模糊匹配
来源：http://dali.jinghuilouyu.cn/Article/details/gtpqfsyywp.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.zhengqikj.top/Article/details/gtrunqxzmt.html

[Q19] 范围查询
来源：http://dali.gotoacloud.top/Article/details/gtjdmdzyqk.html


<!-- 参考信息 -->