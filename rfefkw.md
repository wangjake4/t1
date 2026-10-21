代发 wailian999

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.0kj1m.cn/Article/details/gtvqmczdvi.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtyivjesva.html

N. 数据结构与算法
来源：http://dali.zhengqikj.top/Article/details/gtkgjvqget.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtzxiuymfq.html

[N01] 二分查找（有序数组）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpjworafb.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.sxryk.cn/Article/details/gtcajmbxif.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtueuyauit.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yj202588.top/Article/details/gtpiskfqnw.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlnbqvlvh.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.jinqigfzy.top/Article/details/gtbuqtrgio.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.aibaodan.cn/Article/details/gtpjpupdoh.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.gogol.net.cn/Article/details/gtiwnsvkqq.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.jinghuilouyu.cn/Article/details/gtjqpkwflq.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.mhx1999.top/Article/details/gtdcnakiak.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.cheryme.top/Article/details/gtvvugemvm.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.ehwqpu.com/Article/details/gtcnancovb.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhengqikj.top/Article/details/gtvwbaqnbu.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.hywenlv.cn/Article/details/gtttpscmkz.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhixingplan.top/Article/details/gtqacjcsiv.html

Go:   slices.Sort(arr)
来源：http://dali.xziqi.cn/Article/details/gtpnrjnhlr.html

Ruby: arr.sort
来源：http://dali.zhengqikj.top/Article/details/gtivxconrd.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.yonumen.top/Article/details/gtanyberbi.html

[N03] 快速排序（分治示例）
来源：http://dali.pycfn.com/Article/details/gtaytknkal.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhoulong.xyz/Article/details/gtwrmuqjru.html

PHP:  // 递归实现，或用 usort
来源：http://dali.hysaishi.cn/Article/details/gtznrqwtsk.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.redwolf501.top/Article/details/gtsbacwoul.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.hammf.cn/Article/details/gtccpgbygq.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.jinqigfzy.top/Article/details/gtatxojowe.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.yuxming.cn/Article/details/gtaccoxkks.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.jlsjyb.cn/Article/details/gtfzxetwxc.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.chenlongwang.top/Article/details/gtstizhsdj.html

[N04] 斐波那契数列
来源：http://dali.aibaodan.cn/Article/details/gtmvpkhdhr.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.jiagoushi.top/Article/details/gtfocldspb.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.xuanzx.com/Article/details/gtstseeyna.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.gogol.net.cn/Article/details/gttbceualr.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.smart0.xyz/Article/details/gtbuzxicoc.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.bjfxy.top/Article/details/gtlohqdhnt.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtshycjkkk.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.jinghuilouyu.cn/Article/details/gtrnuwqctm.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zycfv.cn/Article/details/gtlrwoqfwe.html

[N05] 最大公约数
来源：http://dali.fzhhl.top/Article/details/gtkioqoquy.html

Py:   math.gcd(a, b)
来源：http://dali.nanxinkj.top/Article/details/gtecjaggnu.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.sysykeji.top/Article/details/gtzvokuduh.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.xuanzx.com/Article/details/gtdimsqfro.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.haohaochexian.top/Article/details/gtqjtgxqka.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.shangyingyoupin.top/Article/details/gtipevtynl.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.gogol.net.cn/Article/details/gtzykcxfjq.html

Ruby: a.gcd(b)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtusnhrtsr.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.ehwqpu.com/Article/details/gtdehaarqx.html

[N06] 判断回文字符串
来源：http://dali.jyoumei.cn/Article/details/gtnyulubji.html

Py:   s == s[::-1]
来源：http://dali.cucudq.cn/Article/details/gtoueeevyh.html

PHP:  $s === strrev($s);
来源：http://dali.cucudq.cn/Article/details/gtefqeucym.html

JS:   s === [...s].reverse().join("")
来源：http://dali.fengsongda.top/Article/details/gtxieynczx.html

TS:   s === [...s].reverse().join("")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtejflmyav.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.316326.xyz/Article/details/gtquibmjmn.html

Go:   // 双指针从两端比较
来源：http://dali.yangfankeji.com/Article/details/gtitwdlftw.html

Ruby: s == s.reverse
来源：http://dali.hysaishi.cn/Article/details/gtogifpsxu.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zycfv.cn/Article/details/gtxdjptqkf.html

[N07] 两数之和（返回下标）
来源：http://dali.cqqwz.cn/Article/details/gtmflfjtiy.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.nanxuanxn.top/Article/details/gttajnkvue.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.quarkkingdee.top/Article/details/gtzuovqiza.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.jinghuilouyu.cn/Article/details/gtevghyyaj.html

TS:   // 手写 Map<string, number>
来源：http://dali.dianchejie.cn/Article/details/gtsubtqbxs.html

Java: // 手写 HashMap
来源：http://dali.ppjwa.cn/Article/details/gtvouxibyu.html

Go:   // 手写 map[int]int
来源：http://dali.redwolf501.top/Article/details/gtourkyarc.html

Ruby: // 手写 Hash
来源：http://dali.guowangkeji.top/Article/details/gtrbijebkv.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.iojbl.cn/Article/details/gtxaydtksn.html

[N08] 生成全排列
来源：http://dali.yj20258888.top/Article/details/gtdnsvxrxv.html

Py:   itertools.permutations(arr)
来源：http://dali.shangyingyoupin.top/Article/details/gtuanecdgq.html

PHP:  // 手写递归交换
来源：http://dali.xuetiantiany.cn/Article/details/gtvaivgkas.html

JS:   // 手写回溯递归
来源：http://dali.yuxming.cn/Article/details/gtyyzqjdpg.html

TS:   // 手写回溯递归
来源：http://dali.yvedp.cn/Article/details/gtxcrzgssx.html

Java: // 手写回溯递归
来源：http://dali.aibaodan.cn/Article/details/gtdpnfzchf.html

Go:   // 手写回溯递归
来源：http://dali.hysaishi.cn/Article/details/gthcrkaaet.html

Ruby: arr.permutation.to_a
来源：http://dali.wangshuangyany.cn/Article/details/gtlqdxyzbv.html

C#:   // 手写回溯递归
来源：http://dali.xylfe.cn/Article/details/gtsxvaaowg.html

[N09] 栈与队列
来源：http://dali.pycfn.com/Article/details/gtvizentli.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.xziqi.cn/Article/details/gtetfqrhtn.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.fengsongda.top/Article/details/gtkpafzkbd.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.316326.xyz/Article/details/gttseqskpy.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.tianlin.xyz/Article/details/gtmldghxhg.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.316326.xyz/Article/details/gtqacercws.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.guowangkeji.top/Article/details/gtxpogusmc.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.ivvv.top/Article/details/gtufgdnbmj.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.xziqi.cn/Article/details/gtccvutzkc.html

[N10] 链表节点定义
来源：http://dali.jqgfzy.top/Article/details/gtytwbexfe.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxugshjlz.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzviwvihf.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.jqgfzy.top/Article/details/gtyhxiukdx.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.guowangkeji.top/Article/details/gtlyxfmnvv.html

Java: class Node { int v; Node next; }
来源：http://dali.yanxiufei.cn/Article/details/gtvkoynarq.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkmzwftts.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.dashuyun.cn/Article/details/gtryxfjwac.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.chenzaomai.com/Article/details/gtgzdqeboi.html

[N11] 二叉树中序遍历
来源：http://dali.yongpay.top/Article/details/gtqudisdtf.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhongyouzk.top/Article/details/gttuxvhemf.html

PHP:  // 手写递归函数
来源：http://dali.haohaochexian.top/Article/details/gtmczwpsmm.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jlsjyb.cn/Article/details/gthxgdcept.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.hongshengwenyu.top/Article/details/gtayxmplpr.html

Java: // 手写递归
来源：http://dali.haohaochexian.top/Article/details/gtymiibmqp.html

Go:   // 手写递归
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgzzbbkcd.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.fengsongda.top/Article/details/gtcgrtyzqh.html

C#:   // 手写递归
来源：http://dali.0kj1m.cn/Article/details/gtkhffgmce.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.fzhhl.top/Article/details/gtjrjsidrn.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.andypj.xyz/Article/details/gtbtcnqstr.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zdqjudy.top/Article/details/gteyimdrgt.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.chenjidiqi.icu/Article/details/gttaurolsb.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jlsjyb.cn/Article/details/gtweeegmew.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.feifeiyinyue.top/Article/details/gtncuhrdvb.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.shuidangran.top/Article/details/gtcpiwazxd.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.cheryme.top/Article/details/gtjrrzwlee.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yj202588.top/Article/details/gtfzpwlwks.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtoocimebe.html

O. 并发与异步
来源：http://dali.zycfv.cn/Article/details/gtsegwijcy.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtmiqpvfaf.html

[O01] 启动一个线程
来源：http://dali.yanxiufei.cn/Article/details/gtwnkyorbm.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.xylfe.cn/Article/details/gtzjrkeabv.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.jlsjyb.cn/Article/details/gtipgkvopc.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.shzxlz.cn/Article/details/gtkwtvcxiu.html

TS:   // 同 JS
来源：http://dali.jqgfzy.top/Article/details/gtkufljwxs.html

Java: new Thread(() -> f()).start()
来源：http://dali.hnqzz.top/Article/details/gtapolsviy.html

Go:   go f()
来源：http://dali.ivvv.top/Article/details/gtvebqisyw.html

Ruby: Thread.new { f }
来源：http://dali.chenzaomai.com/Article/details/gtbubcrrri.html

C#:   Task.Run(() => F());
来源：http://dali.hywenlv.cn/Article/details/gtdrfoovej.html

[O02] 使用线程池
来源：http://dali.hysaishi.cn/Article/details/gtklyfbnla.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.nanxinkj.top/Article/details/gtudpvoylb.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.nwbrower.top/Article/details/gtveprqcet.html

JS:   // worker_threads 线程池
来源：http://dali.sweek.top/Article/details/gthhhfxrow.html

TS:   // worker_threads 线程池
来源：http://dali.yvedp.cn/Article/details/gtvklwejgn.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.sxryk.cn/Article/details/gtjciqlend.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.hfpthk.cn/Article/details/gtfmccrcin.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.jianghu66.top/Article/details/gtscutelzv.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.sweek.top/Article/details/gtmzfpcsnc.html

[O03] 加锁保护共享数据
来源：http://dali.yongpay.top/Article/details/gtmvghtlsv.html

Py:   with lock: shared += 1
来源：http://dali.andypj.xyz/Article/details/gthqejsdss.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.snrcjt.cn/Article/details/gtucznavjb.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.yj20258888.top/Article/details/gthahbafhg.html

TS:   // 同 JS
来源：http://dali.ivvv.top/Article/details/gtkrimvxms.html

Java: synchronized (this) { shared++; }
来源：http://dali.shuidangran.top/Article/details/gtuydrwkem.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.jqgfzy.top/Article/details/gtkqqexyqu.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.iojbl.cn/Article/details/gtfhbpehjo.html

C#:   lock (gate) { shared++; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtngqffdnu.html

[O04] 定义异步函数并等待
来源：http://dali.jiagoushi.top/Article/details/gtkprvfebt.html

Py:   async def f():⏎    await g()
来源：http://dali.hywenlv.cn/Article/details/gtnttxllbz.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.quarkkingdee.top/Article/details/gtjqublbfz.html

JS:   async function f() { await g(); }
来源：http://dali.0kj1m.cn/Article/details/gticbxltqk.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.hammf.cn/Article/details/gtmxvovrfz.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.chenjidiqi.icu/Article/details/gtzfpfddtc.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.shuidangran.top/Article/details/gtortdbmgo.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.hammf.cn/Article/details/gtcumwgkia.html

C#:   async Task F() { await G(); }
来源：http://dali.jiagoushi.top/Article/details/gtgsljqydt.html

[O05] 并发执行并等待全部完成
来源：http://dali.fzhhl.top/Article/details/gtionciazh.html

Py:   asyncio.gather(*tasks)
来源：http://dali.aizwys.cn/Article/details/gtvbieexkp.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.aizwys.cn/Article/details/gtxhnbyfvx.html

JS:   await Promise.all(tasks)
来源：http://dali.chenjidiqi.icu/Article/details/gtldahtagc.html

TS:   await Promise.all(tasks)
来源：http://dali.jinqigufen.top/Article/details/gtnhcltcjo.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.sxryk.cn/Article/details/gtncymeird.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.gaohongyu789.top/Article/details/gtisnesqum.html

Ruby: threads.map(&:join)
来源：http://dali.andypj.xyz/Article/details/gtoraowogv.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.xuanzx.com/Article/details/gtjdnukxam.html

[O06] 使用进程池
来源：http://dali.gogol.net.cn/Article/details/gthlwolttc.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.guannengcc.top/Article/details/gturwqosyz.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.tian-w.cn/Article/details/gteaepyxxf.html

JS:   // child_process / cluster 模块
来源：http://dali.xziqi.cn/Article/details/gtgcnhkbtm.html

TS:   // child_process / cluster 模块
来源：http://dali.zhengqikj.top/Article/details/gtvjjyjuyp.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.ybcxt.top/Article/details/gtnecwrgjr.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.0kj1m.cn/Article/details/gtcvsrfreo.html

Ruby: // fork 块
来源：http://dali.quarkkingdee.top/Article/details/gtsprppior.html

C#:   Parallel.For
来源：http://dali.wangdashe.top/Article/details/gtjrrpupob.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtrziymtaj.html

P. 常用工具函数
来源：http://dali.svipenyu.cn/Article/details/gtowzrrkhm.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gttclemxjb.html

[P01] 生成 UUID
来源：http://dali.xuanzx.com/Article/details/gtfvtpyebu.html

Py:   str(uuid.uuid4())
来源：http://dali.chenjidiqi.icu/Article/details/gtagkchpmv.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.gotoacloud.top/Article/details/gtuhvewlfu.html

JS:   crypto.randomUUID()
来源：http://dali.yuxming.cn/Article/details/gtjhslucay.html

TS:   crypto.randomUUID()
来源：http://dali.9152youxi.cn/Article/details/gtbkhsrqaq.html

Java: UUID.randomUUID().toString()
来源：http://dali.shanyushiyangtech.top/Article/details/gtqjtavhoj.html

Go:   // 用 github.com/google/uuid
来源：http://dali.hfpthk.cn/Article/details/gtabwmgxnk.html

Ruby: SecureRandom.uuid
来源：http://dali.shuidangran.top/Article/details/gtlquzfngr.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.yueranfly.top/Article/details/gtmlfvnicg.html

[P02] MD5 / SHA256 摘要
来源：http://dali.yuxming.cn/Article/details/gtfmqadjhk.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.cqqwz.cn/Article/details/gtgvusqczd.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.hammf.cn/Article/details/gtobnoytvn.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.gotoacloud.top/Article/details/gtlhbjsyxl.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.andypj.xyz/Article/details/gtmlpjgkmv.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.tanke756.top/Article/details/gttzfyyaiq.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.cheryme.top/Article/details/gtqhygafoq.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.meibo888.top/Article/details/gtlhpwoabv.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzrqvezmp.html

[P03] 生成短随机字符串
来源：http://dali.vqdsnc.cn/Article/details/gthywgowco.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.yonumen.top/Article/details/gtrwungelc.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.xuanzx.com/Article/details/gtxxfccute.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.fengsongda.top/Article/details/gtvuntbzhn.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.ppjwa.cn/Article/details/gtbwetoixp.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.yanxiufei.cn/Article/details/gtrickapev.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.bjfxy.top/Article/details/gtretwtren.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.ppjwa.cn/Article/details/gttxixugog.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.jiagoushi.top/Article/details/gtighbtbjd.html

[P04] 求长度
来源：http://dali.cucudq.cn/Article/details/gtxygpvvbd.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.havefunace.top/Article/details/gtuzajmkmd.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jinghuilouyu.cn/Article/details/gtlxxeluzg.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhongyouzk.top/Article/details/gthgfdfahg.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.chenjidiqi.icu/Article/details/gtliqajmuf.html

Java: list.size();  map.size();  s.length()
来源：http://dali.chenjidiqi.icu/Article/details/gtnvezytcq.html

Go:   len(arr);  len(m)
来源：http://dali.zhixingplan.top/Article/details/gtnephousj.html

Ruby: x.length;  x.size
来源：http://dali.yj202588.top/Article/details/gtmhugegbi.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.cqqwz.cn/Article/details/gtkdcdikec.html

[P05] 判断两个对象内容是否相等
来源：http://dali.gzhubu.top/Article/details/gtqvbaprcz.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.kuanghao11.cn/Article/details/gtkkcpqtgt.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.yuxming.cn/Article/details/gtfrktztdl.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.guowangkeji.top/Article/details/gtrdociuqz.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhoulong.xyz/Article/details/gtaslwzpxn.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.chenzaomai.com/Article/details/gtolvcihns.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.chenlongwang.top/Article/details/gtiwllwyiy.html

Ruby: a == b
来源：http://dali.sweek.top/Article/details/gtyieknxog.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.yj20258.top/Article/details/gtgivpeupg.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.gzhubu.top/Article/details/gthunechje.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.mhx1999.top/Article/details/gtslhnbgip.html

PHP:  if (empty($x)) {}
来源：http://dali.yuxming.cn/Article/details/gtabhefcta.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.hfpthk.cn/Article/details/gtwvwmmoij.html

TS:   if (x == null) {}
来源：http://dali.ivvv.top/Article/details/gtdkpqxckq.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.tian-w.cn/Article/details/gtpukdqqbx.html

Go:   if x == nil {}
来源：http://dali.ivvv.top/Article/details/gtlctpmnse.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.nanxuanxn.top/Article/details/gtlrhvaysb.html

C#:   if (x is null) {}
来源：http://dali.hysaishi.cn/Article/details/gtxapzedel.html

[P07] 防抖与节流
来源：http://dali.mhx1999.top/Article/details/gtdhsjbejs.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.svipenyu.cn/Article/details/gtrqbrdaek.html

PHP:  // 手写时间戳比较
来源：http://dali.kuanghao11.cn/Article/details/gtduanezbs.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.cucudq.cn/Article/details/gtrcgmnofl.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.chenjidiqi.icu/Article/details/gtinvqlsmx.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.pengpengdd.cyou/Article/details/gtubzmsfxu.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.cqqwz.cn/Article/details/gtufqvgbql.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.jinghuilouyu.cn/Article/details/gtkaqmznwj.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.pycfn.com/Article/details/gtdogezuhy.html

[P08] 处理浮点精度问题
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkuaygvar.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtawuxpwyc.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.shangyingyoupin.top/Article/details/gtpbhkhpin.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.aizwys.cn/Article/details/gtxwusdpem.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.0kj1m.cn/Article/details/gtmqcfmvhu.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.ywan-chungtsiang.top/Article/details/gteygoqnms.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.jinghuilouyu.cn/Article/details/gtwvsyiain.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpummftkg.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.fzhhl.top/Article/details/gtskxoimys.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtuinohhgi.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.ybcxt.top/Article/details/gtjgieocfd.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtyukfelcu.html

[Q01] 创建表
来源：http://dali.shuidangran.top/Article/details/gtyhwaomdz.html

CREATE TABLE users (
来源：http://dali.sweek.top/Article/details/gtivydgnwr.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jianghu66.top/Article/details/gtfjqvytfo.html

name VARCHAR(50) NOT NULL,
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyamvcgrb.html

email VARCHAR(100) UNIQUE,
来源：http://dali.jqgufenzy.top/Article/details/gtceolqlui.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.yueranfly.top/Article/details/gtjxajlhzk.html

);
来源：http://dali.nwbrower.top/Article/details/gtodczwwuz.html

[Q02] 创建带外键的表
来源：http://dali.kuanghao11.cn/Article/details/gtohqelpfo.html

CREATE TABLE orders (
来源：http://dali.daxiang520.top/Article/details/gthtnfenvd.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.9152youxi.cn/Article/details/gthltfcmrq.html

user_id INT NOT NULL,
来源：http://dali.jyoumei.cn/Article/details/gtucqwysrm.html

amount DECIMAL(10, 2),
来源：http://dali.jyoumei.cn/Article/details/gtuueqpjar.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.haohaochexian.top/Article/details/gtvywuukye.html

);
来源：http://dali.cucudq.cn/Article/details/gtwagrggwy.html

[Q03] 增加列
来源：http://dali.jqgfzy.top/Article/details/gtiewarrwj.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.aibaodan.cn/Article/details/gtmpyoltii.html

[Q04] 修改列类型
来源：http://dali.zhongyouzk.top/Article/details/gthzrqnrae.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.jinghuilouyu.cn/Article/details/gtzfprnota.html

[Q05] 重命名列
来源：http://dali.aibaodan.cn/Article/details/gtnkadvjvf.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.xuanzx.com/Article/details/gticfrptvr.html

[Q06] 删除列
来源：http://dali.yanxiufei.cn/Article/details/gttxndyakj.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.jinghuilouyu.cn/Article/details/gtltrrbnvf.html

[Q07] 删除表
来源：http://dali.shzxlz.cn/Article/details/gtglldsmpm.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhiwuduotai.top/Article/details/gtbzaigpyu.html

[Q08] 创建普通索引
来源：http://dali.smart0.xyz/Article/details/gtkybybknf.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.chenjidiqi.icu/Article/details/gttkniyrrc.html

[Q09] 创建唯一索引
来源：http://dali.wangshuangyany.cn/Article/details/gtcsgzibsu.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.iojbl.cn/Article/details/gtbdyqllwr.html

[Q10] 插入单行
来源：http://dali.chenzaomai.com/Article/details/gtnxhkhmir.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.tian-w.cn/Article/details/gtscovjcsq.html

[Q11] 一次插入多行
来源：http://dali.hysaishi.cn/Article/details/gtgovjrdsi.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.dashuyun.cn/Article/details/gttkmjdeko.html

[Q12] 插入后取自增 ID
来源：http://dali.xuanzx.com/Article/details/gtivncbowd.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.jiagoushi.top/Article/details/gtwmfeqwky.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.shangyingyoupin.top/Article/details/gtjkcdsrez.html

[Q13] 忽略重复插入
来源：http://dali.hammf.cn/Article/details/gtmqutnyoh.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.9152youxi.cn/Article/details/gtfyfqvlgo.html

[Q14] 存在则更新（upsert）
来源：http://dali.guowangkeji.top/Article/details/gtuuviexlm.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gtgfyadzkx.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.chenjidiqi.icu/Article/details/gtlcylqhpy.html

[Q15] 查询全部
来源：http://dali.bjfxy.top/Article/details/gtmplhzpus.html

SELECT * FROM users;
来源：http://dali.xuanzx.com/Article/details/gtnoyfnwib.html

[Q16] 查询指定列
来源：http://dali.wangshuangyany.cn/Article/details/gtpjrmemku.html

SELECT id, name FROM users;
来源：http://dali.316326.xyz/Article/details/gtaxgjxhgy.html

[Q17] 条件查询
来源：http://dali.shangyingyoupin.top/Article/details/gtrccrcpzi.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.pengpengdd.cyou/Article/details/gtmkisqsop.html

[Q18] 模糊匹配
来源：http://dali.nanxinkj.top/Article/details/gtgdfooajz.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.yvedp.cn/Article/details/gtwkgorkfq.html

[Q19] 范围查询
来源：http://dali.sysykeji.top/Article/details/gtosgptdmr.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.iojbl.cn/Article/details/gtdmfqhqjy.html

[Q20] IN 列表
来源：http://dali.316326.xyz/Article/details/gtkfjdguqe.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.havefunace.top/Article/details/gtoxuywrix.html

[Q21] 空值判断
来源：http://dali.yj202588.top/Article/details/gtjcdmplfa.html


<!-- 参考信息 -->