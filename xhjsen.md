代发 wailian999

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhongyouzk.top/Article/details/gtrigxyemi.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtleiqlklf.html

N. 数据结构与算法
来源：http://dali.ppjwa.cn/Article/details/gtleotuzym.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtogmiawph.html

[N01] 二分查找（有序数组）
来源：http://dali.chenzaomai.com/Article/details/gtjjgkyoig.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.yj202588.top/Article/details/gtfmyimqfc.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.hongshengwenyu.top/Article/details/gttrwwksmd.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.cashguo.top/Article/details/gtnikaelxz.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.0kj1m.cn/Article/details/gtyzxfeqyv.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.jlsjyb.cn/Article/details/gtcdiexrxk.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.hfpthk.cn/Article/details/gtswxpbsgq.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.nanxinkj.top/Article/details/gtrxpwmtih.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.jinqigfzy.top/Article/details/gtzpvzsley.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.hammf.cn/Article/details/gthqpsaxgb.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.dashuyun.cn/Article/details/gtvecdfmim.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.nwbrower.top/Article/details/gtzlvhwydw.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.xylfe.cn/Article/details/gtespcxncg.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yvedp.cn/Article/details/gtvkwpnpwn.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.hnqzz.top/Article/details/gtkjaexuja.html

Go:   slices.Sort(arr)
来源：http://dali.shuidangran.top/Article/details/gtpxhesaar.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gtncelemrr.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.ehwqpu.com/Article/details/gtyaqjoszt.html

[N03] 快速排序（分治示例）
来源：http://dali.hysaishi.cn/Article/details/gtguxkgdhr.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.aizwys.cn/Article/details/gtobprjyfd.html

PHP:  // 递归实现，或用 usort
来源：http://dali.hnxiangtu.top/Article/details/gtbasypfrz.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzkalrfxw.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.haohaochexian.top/Article/details/gtjduezrqv.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.yj20258.top/Article/details/gteqccnxjt.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.sufxvd.cn/Article/details/gtpbyndqsw.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.jlsjyb.cn/Article/details/gtqfvxdnja.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.wangdashe.top/Article/details/gtbfevbzsh.html

[N04] 斐波那契数列
来源：http://dali.vqdsnc.cn/Article/details/gtbpejinmk.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.ydzc1.top/Article/details/gtiggqbovh.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.ppjwa.cn/Article/details/gtvgwtaxlw.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yvedp.cn/Article/details/gttuwaiupd.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yonumen.top/Article/details/gttzovmwar.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtygrqlgji.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gtaqqbypjl.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.xuanzx.com/Article/details/gtyvqjhifs.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.jinyuanbaomall.cn/Article/details/gttesgtngb.html

[N05] 最大公约数
来源：http://dali.yuanzhike.top/Article/details/gtcpbcszpt.html

Py:   math.gcd(a, b)
来源：http://dali.zhengqikj.top/Article/details/gtvhvruhdo.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.yongpay.top/Article/details/gtcafuppta.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.andypj.xyz/Article/details/gthvwwwnbs.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.iojbl.cn/Article/details/gtgcqqulme.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.chenjidiqi.icu/Article/details/gtgvreutew.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.yonumen.top/Article/details/gtylafujdn.html

Ruby: a.gcd(b)
来源：http://dali.yueranfly.top/Article/details/gtziopzywb.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.chenlongwang.top/Article/details/gtrcpgbybe.html

[N06] 判断回文字符串
来源：http://dali.smart0.xyz/Article/details/gtkjclranq.html

Py:   s == s[::-1]
来源：http://dali.tian-w.cn/Article/details/gtxrjheihd.html

PHP:  $s === strrev($s);
来源：http://dali.cheryme.top/Article/details/gtxrvbndpp.html

JS:   s === [...s].reverse().join("")
来源：http://dali.cucudq.cn/Article/details/gtfxkfljoh.html

TS:   s === [...s].reverse().join("")
来源：http://dali.meibo888.top/Article/details/gtzmnvlbdk.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.ywan-chungtsiang.top/Article/details/gtavnabtuj.html

Go:   // 双指针从两端比较
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmqvdxans.html

Ruby: s == s.reverse
来源：http://dali.jinyuanbaomall.cn/Article/details/gthsvstmoa.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.wangdashe.top/Article/details/gtfrenhibl.html

[N07] 两数之和（返回下标）
来源：http://dali.ppjwa.cn/Article/details/gtfggvkqfy.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.daxiang520.top/Article/details/gtoihhgkmg.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.haohaochexian.top/Article/details/gtmuknxyck.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.ivvv.top/Article/details/gtwxxgbaee.html

TS:   // 手写 Map<string, number>
来源：http://dali.xuetiantiany.cn/Article/details/gtrrtovyoq.html

Java: // 手写 HashMap
来源：http://dali.fzhhl.top/Article/details/gtjxaosvhh.html

Go:   // 手写 map[int]int
来源：http://dali.sxryk.cn/Article/details/gtugfxwhlf.html

Ruby: // 手写 Hash
来源：http://dali.daria6918.cn/Article/details/gtolmncmnk.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.jinghuilouyu.cn/Article/details/gteukvvonf.html

[N08] 生成全排列
来源：http://dali.9152youxi.cn/Article/details/gtxltbpsyk.html

Py:   itertools.permutations(arr)
来源：http://dali.jqgfzy.top/Article/details/gtsirxcvmq.html

PHP:  // 手写递归交换
来源：http://dali.ppjwa.cn/Article/details/gtytcmsccr.html

JS:   // 手写回溯递归
来源：http://dali.ivvv.top/Article/details/gttypxotfa.html

TS:   // 手写回溯递归
来源：http://dali.shzxlz.cn/Article/details/gturzlgzka.html

Java: // 手写回溯递归
来源：http://dali.iojbl.cn/Article/details/gtmwixkhki.html

Go:   // 手写回溯递归
来源：http://dali.mhx1999.top/Article/details/gtenoeogvd.html

Ruby: arr.permutation.to_a
来源：http://dali.nwbrower.top/Article/details/gtahaioewj.html

C#:   // 手写回溯递归
来源：http://dali.chenzaomai.com/Article/details/gtwgdwvzmv.html

[N09] 栈与队列
来源：http://dali.xziqi.cn/Article/details/gttzlldyvu.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.daria6918.cn/Article/details/gtednkhizd.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthdmocftp.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.ydzc1.top/Article/details/gtrjuznztx.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.cheryme.top/Article/details/gtbyjuvdlk.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.aibaodan.cn/Article/details/gtawjdjyiy.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.cdnleiting.top/Article/details/gttspzwmdn.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.pycfn.com/Article/details/gtokzuuwgq.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.iojbl.cn/Article/details/gtknkdaopo.html

[N10] 链表节点定义
来源：http://dali.kuanghao11.cn/Article/details/gtkaounqsw.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.yj202588.top/Article/details/gtkgesnlka.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.chenlongwang.top/Article/details/gtrxjaxbtw.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.hnxiangtu.top/Article/details/gtkzdhswuy.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.jinghuilouyu.cn/Article/details/gtaeddxhfd.html

Java: class Node { int v; Node next; }
来源：http://dali.ppjwa.cn/Article/details/gtkiajlezs.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.cashguo.top/Article/details/gtbggpityf.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.wangshuangyany.cn/Article/details/gtqfqmotje.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.sysykeji.top/Article/details/gtjaixvjkw.html

[N11] 二叉树中序遍历
来源：http://dali.nanxinkj.top/Article/details/gtlqvfvkih.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhoulong.xyz/Article/details/gtzfihkftu.html

PHP:  // 手写递归函数
来源：http://dali.bjfxy.top/Article/details/gturdgpumf.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.fengsongda.top/Article/details/gtasplfvgv.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhaomingkeji.xyz/Article/details/gtosbwpgqf.html

Java: // 手写递归
来源：http://dali.zdqjudy.top/Article/details/gtfraxsbkc.html

Go:   // 手写递归
来源：http://dali.pycfn.com/Article/details/gtmillerpm.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zdqjudy.top/Article/details/gtmlcdvghf.html

C#:   // 手写递归
来源：http://dali.jinqigufen.top/Article/details/gtjivltyhj.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.yj20258.top/Article/details/gtwyakwnqm.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhiwuduotai.top/Article/details/gtmuzzpvtr.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.ybcxt.top/Article/details/gtnxzeyesu.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zdqjudy.top/Article/details/gtbbjtqseo.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yanxiufei.cn/Article/details/gtbpjzgzsr.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.snrcjt.cn/Article/details/gtaickrurf.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.jlsjyb.cn/Article/details/gttavkhoak.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.ppjwa.cn/Article/details/gtfhnvfefx.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjjlwvbui.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtmiwjwzpy.html

O. 并发与异步
来源：http://dali.ydzc1.top/Article/details/gtyhjluljx.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtwpsdfshf.html

[O01] 启动一个线程
来源：http://dali.0kj1m.cn/Article/details/gtorvdalta.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.jlsjyb.cn/Article/details/gtrhtwrsot.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.xuanzx.com/Article/details/gtbltlstjo.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.birdmap.top/Article/details/gtzgoijnls.html

TS:   // 同 JS
来源：http://dali.sysykeji.top/Article/details/gtcmanrdhz.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhoulong.xyz/Article/details/gtgummfzxe.html

Go:   go f()
来源：http://dali.sweek.top/Article/details/gtyhdmpyqr.html

Ruby: Thread.new { f }
来源：http://dali.feifeiyinyue.top/Article/details/gtiphtcste.html

C#:   Task.Run(() => F());
来源：http://dali.chenlongwang.top/Article/details/gtpfgmjtjp.html

[O02] 使用线程池
来源：http://dali.shangyingyoupin.top/Article/details/gttdzeyadc.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.hnqzz.top/Article/details/gtavqtseei.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.yuxming.cn/Article/details/gtsvgecstl.html

JS:   // worker_threads 线程池
来源：http://dali.andypj.xyz/Article/details/gtvmgaeqqu.html

TS:   // worker_threads 线程池
来源：http://dali.hongshengwenyu.top/Article/details/gtpqkomwqk.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.hysaishi.cn/Article/details/gtrbydjxxr.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.hongshengwenyu.top/Article/details/gtwheewbde.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zycfv.cn/Article/details/gtorztcqqf.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.hysaishi.cn/Article/details/gtthsklugo.html

[O03] 加锁保护共享数据
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfhdexkuf.html

Py:   with lock: shared += 1
来源：http://dali.yanxiufei.cn/Article/details/gtrynnntfv.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.yangfankeji.com/Article/details/gtxemqjnez.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.hnqzz.top/Article/details/gtudostbfl.html

TS:   // 同 JS
来源：http://dali.bjfxy.top/Article/details/gtjdqkfegp.html

Java: synchronized (this) { shared++; }
来源：http://dali.gotoacloud.top/Article/details/gtihpooyop.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.cheryme.top/Article/details/gtvhiijtox.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.kuanghao11.cn/Article/details/gthzaynhhi.html

C#:   lock (gate) { shared++; }
来源：http://dali.gzhubu.top/Article/details/gtgckqukhq.html

[O04] 定义异步函数并等待
来源：http://dali.shanyushiyangkeji.top/Article/details/gtayzcbjrj.html

Py:   async def f():⏎    await g()
来源：http://dali.hfpthk.cn/Article/details/gtzgwcyiah.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.daria6918.cn/Article/details/gtoohoiejm.html

JS:   async function f() { await g(); }
来源：http://dali.hywenlv.cn/Article/details/gtgyeewlgo.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.yj20258.top/Article/details/gtpzsmjhjh.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.gaohongyu789.top/Article/details/gtmdkzshkg.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.jinghuilouyu.cn/Article/details/gtnjxzzvke.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.ehwqpu.com/Article/details/gtgkhngjjl.html

C#:   async Task F() { await G(); }
来源：http://dali.xinyue.icu/Article/details/gttdjxlizy.html

[O05] 并发执行并等待全部完成
来源：http://dali.ivvv.top/Article/details/gtyxwgovgr.html

Py:   asyncio.gather(*tasks)
来源：http://dali.gzhubu.top/Article/details/gtwztnwrbm.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.gogol.net.cn/Article/details/gtppzeebnr.html

JS:   await Promise.all(tasks)
来源：http://dali.andypj.xyz/Article/details/gtlnbnubif.html

TS:   await Promise.all(tasks)
来源：http://dali.hammf.cn/Article/details/gtexfkskkp.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.9152youxi.cn/Article/details/gtsefmuojo.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.tanke756.top/Article/details/gtgfohmrzx.html

Ruby: threads.map(&:join)
来源：http://dali.zhiwuduotai.top/Article/details/gtsdrpersy.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhiwuduotai.top/Article/details/gtynesagkb.html

[O06] 使用进程池
来源：http://dali.vqdsnc.cn/Article/details/gtuaaxvbsb.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zycfv.cn/Article/details/gtpbirsyrf.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.cucudq.cn/Article/details/gtavyupywp.html

JS:   // child_process / cluster 模块
来源：http://dali.gzhubu.top/Article/details/gtxbgdctid.html

TS:   // child_process / cluster 模块
来源：http://dali.tianlin.xyz/Article/details/gtckxnimcw.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.jinqigufen.top/Article/details/gtjxumawbc.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.jiagoushi.top/Article/details/gtcmnhvlej.html

Ruby: // fork 块
来源：http://dali.yueranfly.top/Article/details/gtzmbadcrc.html

C#:   Parallel.For
来源：http://dali.mhx1999.top/Article/details/gtapvqaoqq.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtezjfgvoc.html

P. 常用工具函数
来源：http://dali.sufxvd.cn/Article/details/gtgaukuzal.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtghsbezqf.html

[P01] 生成 UUID
来源：http://dali.jianghu66.top/Article/details/gtcgeulspa.html

Py:   str(uuid.uuid4())
来源：http://dali.hongshengwenyu.top/Article/details/gtjbgqddfi.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.havefunace.top/Article/details/gtfamwikqm.html

JS:   crypto.randomUUID()
来源：http://dali.ppjwa.cn/Article/details/gtnnfimuhw.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gtvtowbrkd.html

Java: UUID.randomUUID().toString()
来源：http://dali.c1oappe.top/Article/details/gtvkzbeneo.html

Go:   // 用 github.com/google/uuid
来源：http://dali.jlsjyb.cn/Article/details/gttaqhppex.html

Ruby: SecureRandom.uuid
来源：http://dali.yuanzhike.top/Article/details/gtierpnsjg.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.daria6918.cn/Article/details/gtanawlsyf.html

[P02] MD5 / SHA256 摘要
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnzrwusai.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.nanxinkj.top/Article/details/gtgwmuopij.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.jinghuilouyu.cn/Article/details/gteneayhpg.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.dianchejie.cn/Article/details/gtalztfvbr.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.chenzaomai.com/Article/details/gtjvzddjyl.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.hfpthk.cn/Article/details/gttuwevgvz.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.yanxiufei.cn/Article/details/gtoycabvod.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhiwuduotai.top/Article/details/gthksmewmc.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.daria6918.cn/Article/details/gtdlawchge.html

[P03] 生成短随机字符串
来源：http://dali.yonumen.top/Article/details/gtdomxrejq.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhongyouzk.top/Article/details/gtxkvrowxk.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.cucudq.cn/Article/details/gtmltgfyqu.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.gogol.net.cn/Article/details/gtdrlszeem.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.ehwqpu.com/Article/details/gtbdqxwmve.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.dianchejie.cn/Article/details/gtahmmdtne.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.kuanghao11.cn/Article/details/gtyosrrcin.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.kuanghao11.cn/Article/details/gtumzabiap.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.jianghu66.top/Article/details/gtdshpgibq.html

[P04] 求长度
来源：http://dali.fzhhl.top/Article/details/gtlvtzezma.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.gotoacloud.top/Article/details/gthodxtivn.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.tianlin.xyz/Article/details/gtmkbdtlvm.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.dianchejie.cn/Article/details/gtympxhesf.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.iojbl.cn/Article/details/gtyuhkocuy.html

Java: list.size();  map.size();  s.length()
来源：http://dali.yj20258.top/Article/details/gthswdjzye.html

Go:   len(arr);  len(m)
来源：http://dali.9152youxi.cn/Article/details/gtbggyagaz.html

Ruby: x.length;  x.size
来源：http://dali.hfpthk.cn/Article/details/gtyhirfnoj.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.jinqigufen.top/Article/details/gtejzwjwef.html

[P05] 判断两个对象内容是否相等
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqtcuzuea.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.svipenyu.cn/Article/details/gtjqixmhtx.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.nanxuanxn.top/Article/details/gtafcajrmo.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.hnqzz.top/Article/details/gtelocasct.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.iojbl.cn/Article/details/gtupyjmlug.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.vqdsnc.cn/Article/details/gtysmtohgy.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.aibaodan.cn/Article/details/gtrdhvglyl.html

Ruby: a == b
来源：http://dali.chenzaomai.com/Article/details/gtitumbrcz.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrnqbknxl.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.xuetiantiany.cn/Article/details/gtomwddpyv.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.aizwys.cn/Article/details/gtkgdsiuud.html

PHP:  if (empty($x)) {}
来源：http://dali.yj20258888.top/Article/details/gtdudbhqqi.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.shuidangran.top/Article/details/gtjtbzibdn.html

TS:   if (x == null) {}
来源：http://dali.hammf.cn/Article/details/gtpcgjiwlt.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.aibaodan.cn/Article/details/gtkgddsqba.html

Go:   if x == nil {}
来源：http://dali.sxryk.cn/Article/details/gtrezqineb.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.smart0.xyz/Article/details/gtdwqrhvul.html

C#:   if (x is null) {}
来源：http://dali.cqqwz.cn/Article/details/gtauigqhbj.html

[P07] 防抖与节流
来源：http://dali.yangfankeji.com/Article/details/gtbcdphyfr.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.yj20258888.top/Article/details/gtfzvuvcsk.html

PHP:  // 手写时间戳比较
来源：http://dali.shanyushiyangkeji.top/Article/details/gtezblnkoj.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.xuanzx.com/Article/details/gterfuamuv.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jlsjyb.cn/Article/details/gtivrpbtmf.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.quarkkingdee.top/Article/details/gtdzihvwth.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.nanxuanxn.top/Article/details/gtndrrkmae.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.yangfankeji.com/Article/details/gtgcdosgac.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.hfpthk.cn/Article/details/gtsfyjfeyt.html

[P08] 处理浮点精度问题
来源：http://dali.zhongyouzk.top/Article/details/gtviyxgjuv.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.feifeiyinyue.top/Article/details/gtsksgvdbw.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.haohaochexian.top/Article/details/gtfhafpfsm.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.quarkkingdee.top/Article/details/gtudxhhsjo.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.aibaodan.cn/Article/details/gtqdnkfqnq.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.sweek.top/Article/details/gtciyjywgd.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.xziqi.cn/Article/details/gtuvbhsmdq.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.cqqwz.cn/Article/details/gtripbrlxt.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.c1oappe.top/Article/details/gtptqrqpbr.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtgtpevsse.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.fzhhl.top/Article/details/gtvartsdnd.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtsipzztjw.html

[Q01] 创建表
来源：http://dali.cqqwz.cn/Article/details/gtxigufztr.html

CREATE TABLE users (
来源：http://dali.yj202588.top/Article/details/gtsqmiidwj.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.pycfn.com/Article/details/gtlmwafwsz.html

name VARCHAR(50) NOT NULL,
来源：http://dali.svipenyu.cn/Article/details/gtehxnnnek.html

email VARCHAR(100) UNIQUE,
来源：http://dali.svipenyu.cn/Article/details/gtwrbksdqm.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.nwbrower.top/Article/details/gtoskniwds.html

);
来源：http://dali.hammf.cn/Article/details/gtshlvxvqi.html

[Q02] 创建带外键的表
来源：http://dali.shangyingyoupin.top/Article/details/gtvmhgzswq.html

CREATE TABLE orders (
来源：http://dali.ppjwa.cn/Article/details/gtirfajcpt.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.tian-w.cn/Article/details/gtexuprphq.html

user_id INT NOT NULL,
来源：http://dali.hywenlv.cn/Article/details/gthoyvxfho.html

amount DECIMAL(10, 2),
来源：http://dali.bjfxy.top/Article/details/gtaicajuat.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.snrcjt.cn/Article/details/gtjfatiaiq.html

);
来源：http://dali.yongpay.top/Article/details/gttcuhlmxl.html

[Q03] 增加列
来源：http://dali.yj20258888.top/Article/details/gtgilndbfy.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.hammf.cn/Article/details/gtckqmgfnc.html

[Q04] 修改列类型
来源：http://dali.ivvv.top/Article/details/gtxauvltyk.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.tian-w.cn/Article/details/gtthxkugwx.html

[Q05] 重命名列
来源：http://dali.guannengcc.top/Article/details/gtqtdumigj.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.jyoumei.cn/Article/details/gtgoojifxv.html

[Q06] 删除列
来源：http://dali.yuxming.cn/Article/details/gtgjdklkdp.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.vqdsnc.cn/Article/details/gtudbbphot.html

[Q07] 删除表
来源：http://dali.yueranfly.top/Article/details/gtuxcmbobw.html

DROP TABLE IF EXISTS orders;
来源：http://dali.0kj1m.cn/Article/details/gthtqfeudh.html

[Q08] 创建普通索引
来源：http://dali.xuetiantiany.cn/Article/details/gtelsqqxdq.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhiwuduotai.top/Article/details/gtldjkanzb.html

[Q09] 创建唯一索引
来源：http://dali.xuetiantiany.cn/Article/details/gtqhhruijo.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.tianlin.xyz/Article/details/gtdlreumwa.html

[Q10] 插入单行
来源：http://dali.guannengcc.top/Article/details/gtakmxzjxd.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.daxiang520.top/Article/details/gtztdnbdgw.html

[Q11] 一次插入多行
来源：http://dali.aizwys.cn/Article/details/gtpijlsckc.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.xziqi.cn/Article/details/gttpsktocr.html

[Q12] 插入后取自增 ID
来源：http://dali.kuanghao11.cn/Article/details/gtxvypkwkz.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.nanxuanxn.top/Article/details/gthrnvcbma.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.sysykeji.top/Article/details/gtbichbiiv.html

[Q13] 忽略重复插入
来源：http://dali.fzhhl.top/Article/details/gtcjhswffz.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.feifeiyinyue.top/Article/details/gtrlowhoao.html

[Q14] 存在则更新（upsert）
来源：http://dali.smart0.xyz/Article/details/gtpocpogwo.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.yonumen.top/Article/details/gtdqgajsaf.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.nanxinkj.top/Article/details/gttoqslqbl.html

[Q15] 查询全部
来源：http://dali.yanxiufei.cn/Article/details/gthmvqvkil.html

SELECT * FROM users;
来源：http://dali.jiagoushi.top/Article/details/gtsamzvunw.html

[Q16] 查询指定列
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnuoeivln.html

SELECT id, name FROM users;
来源：http://dali.andypj.xyz/Article/details/gtyixkmjxx.html

[Q17] 条件查询
来源：http://dali.yuanzhike.top/Article/details/gtkwugfrra.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.yuanzhike.top/Article/details/gtyqrlwqaa.html

[Q18] 模糊匹配
来源：http://dali.nwbrower.top/Article/details/gtrhzxquwc.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.yuxming.cn/Article/details/gtlyhphrwh.html

[Q19] 范围查询
来源：http://dali.yvedp.cn/Article/details/gtnzbkookg.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.dianchejie.cn/Article/details/gtzpcuflbe.html

[Q20] IN 列表
来源：http://dali.jqgfzy.top/Article/details/gtdtkipfpb.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.jqgufenzy.top/Article/details/gtoubzyxzc.html

[Q21] 空值判断
来源：http://dali.hnqzz.top/Article/details/gtfbteeamy.html


<!-- 参考信息 -->