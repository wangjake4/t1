代发 wailian999

[N01] 二分查找（有序数组）
来源：http://dali.cashguo.top/Article/details/gtxfoehakj.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gttwwqugoa.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.daria6918.cn/Article/details/gtmnsbestc.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.xuetiantiany.cn/Article/details/gtqtylioxo.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.feifeiyinyue.top/Article/details/gtuchvqtlh.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.kuanghao11.cn/Article/details/gtjbwbczjs.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.smart0.xyz/Article/details/gtdqzlcjar.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.gogol.net.cn/Article/details/gtmohvwfoy.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.cheryme.top/Article/details/gtivlfpchz.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.iojbl.cn/Article/details/gtlspjmbby.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.aizwys.cn/Article/details/gtomlhrnca.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.yj20258888.top/Article/details/gtouzvebqb.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.gogol.net.cn/Article/details/gtcpglnggq.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.gzhubu.top/Article/details/gtjwdverpv.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.hnxiangtu.top/Article/details/gtdyydvkat.html

Go:   slices.Sort(arr)
来源：http://dali.zhoulong.xyz/Article/details/gtwewwneks.html

Ruby: arr.sort
来源：http://dali.jinqigufen.top/Article/details/gtzmnfzyci.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.daxiang520.top/Article/details/gtdworcttp.html

[N03] 快速排序（分治示例）
来源：http://dali.yj202588.top/Article/details/gtjzugeybc.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.cheryme.top/Article/details/gtldqgwjbz.html

PHP:  // 递归实现，或用 usort
来源：http://dali.gzhubu.top/Article/details/gtykjbuwjw.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.ybcxt.top/Article/details/gtowxlqvhb.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jlsjyb.cn/Article/details/gtglztrkeo.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.ppjwa.cn/Article/details/gtgveofkzr.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.hysaishi.cn/Article/details/gtzgpnkeaz.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.haohaochexian.top/Article/details/gtchcqjszi.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.aizwys.cn/Article/details/gtceouuzck.html

[N04] 斐波那契数列
来源：http://dali.gaohongyu789.top/Article/details/gtzoamkbhj.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.nanxinkj.top/Article/details/gtobrwusmh.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.hnxiangtu.top/Article/details/gtvlsdawxn.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.nanxuanxn.top/Article/details/gtggwfjxrb.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jinqigfzy.top/Article/details/gtsykvttos.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.snrcjt.cn/Article/details/gtgykcecjv.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.tian-w.cn/Article/details/gtolnceips.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.ybcxt.top/Article/details/gthwxbojzp.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhixingplan.top/Article/details/gtiqpbkwzj.html

[N05] 最大公约数
来源：http://dali.ehwqpu.com/Article/details/gtyeoovknd.html

Py:   math.gcd(a, b)
来源：http://dali.snrcjt.cn/Article/details/gtetbfowfw.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.feifeiyinyue.top/Article/details/gtfysjvykv.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yvedp.cn/Article/details/gtlphdxzze.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.vqdsnc.cn/Article/details/gtqfoexkkp.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.fengsongda.top/Article/details/gtpyihnipj.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.gaohongyu789.top/Article/details/gtlsskijkf.html

Ruby: a.gcd(b)
来源：http://dali.cashguo.top/Article/details/gtlktokwbr.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.aizwys.cn/Article/details/gtohcpbepp.html

[N06] 判断回文字符串
来源：http://dali.nanxuanxn.top/Article/details/gtebptghbc.html

Py:   s == s[::-1]
来源：http://dali.yuxming.cn/Article/details/gtzytlraqn.html

PHP:  $s === strrev($s);
来源：http://dali.ehwqpu.com/Article/details/gtqbyakmsx.html

JS:   s === [...s].reverse().join("")
来源：http://dali.shangyingyoupin.top/Article/details/gthfsoaeav.html

TS:   s === [...s].reverse().join("")
来源：http://dali.316326.xyz/Article/details/gtxgaetjlo.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.yj202588.top/Article/details/gtncwbbmsn.html

Go:   // 双指针从两端比较
来源：http://dali.zhixingplan.top/Article/details/gtdbzdegat.html

Ruby: s == s.reverse
来源：http://dali.nanxinkj.top/Article/details/gtoyaurgge.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.hywenlv.cn/Article/details/gtkbfgvbtd.html

[N07] 两数之和（返回下标）
来源：http://dali.dianchejie.cn/Article/details/gttomutwlg.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.cdnleiting.top/Article/details/gtinvsmpki.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.xuanzx.com/Article/details/gtcezokaxa.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.smart0.xyz/Article/details/gtodgbszvf.html

TS:   // 手写 Map<string, number>
来源：http://dali.9152youxi.cn/Article/details/gtwskoqaou.html

Java: // 手写 HashMap
来源：http://dali.0kj1m.cn/Article/details/gtpufsvvmv.html

Go:   // 手写 map[int]int
来源：http://dali.redwolf501.top/Article/details/gthuzonmlo.html

Ruby: // 手写 Hash
来源：http://dali.fzhhl.top/Article/details/gtunbjwmgj.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.tianlin.xyz/Article/details/gtrhksdxds.html

[N08] 生成全排列
来源：http://dali.zhiwuduotai.top/Article/details/gtbbmtazve.html

Py:   itertools.permutations(arr)
来源：http://dali.yongpay.top/Article/details/gtidlujgal.html

PHP:  // 手写递归交换
来源：http://dali.yvedp.cn/Article/details/gtelndtzcp.html

JS:   // 手写回溯递归
来源：http://dali.kuanghao11.cn/Article/details/gtnnzrtuzz.html

TS:   // 手写回溯递归
来源：http://dali.daria6918.cn/Article/details/gtgccwmsyg.html

Java: // 手写回溯递归
来源：http://dali.cheryme.top/Article/details/gttcrvquyb.html

Go:   // 手写回溯递归
来源：http://dali.shangyingyoupin.top/Article/details/gtfnwrfjht.html

Ruby: arr.permutation.to_a
来源：http://dali.pycfn.com/Article/details/gtqqfeeruf.html

C#:   // 手写回溯递归
来源：http://dali.yanxiufei.cn/Article/details/gtloocrhiv.html

[N09] 栈与队列
来源：http://dali.shanyushiyangtech.top/Article/details/gtwwlbfgam.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.tanke756.top/Article/details/gtqearsrma.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.xinyue.icu/Article/details/gtxewlkuxd.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.snrcjt.cn/Article/details/gtxaulcdkj.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.gogol.net.cn/Article/details/gtrittspga.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.meibo888.top/Article/details/gtfvchbikj.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhiwuduotai.top/Article/details/gtvmtolqnq.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.chenzaomai.com/Article/details/gthdpouzvk.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.jinqigufen.top/Article/details/gtmghgfsmf.html

[N10] 链表节点定义
来源：http://dali.daria6918.cn/Article/details/gtzzoyybuh.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.nwbrower.top/Article/details/gttoegglaa.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gtiulnnzjp.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.gogol.net.cn/Article/details/gttolivyxp.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.cucudq.cn/Article/details/gtefgvxabk.html

Java: class Node { int v; Node next; }
来源：http://dali.snrcjt.cn/Article/details/gtmwznfnsy.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.jlsjyb.cn/Article/details/gtdpccfbey.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsveptpfb.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.sweek.top/Article/details/gtzinzmjol.html

[N11] 二叉树中序遍历
来源：http://dali.jqgufenzy.top/Article/details/gtmwwjaoxi.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.jinqigufen.top/Article/details/gtifylbznf.html

PHP:  // 手写递归函数
来源：http://dali.aizwys.cn/Article/details/gtlzgvaljm.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.fengsongda.top/Article/details/gtoqqhoalj.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jqgufenzy.top/Article/details/gtuaprpppa.html

Java: // 手写递归
来源：http://dali.zhixingplan.top/Article/details/gtubwrqdal.html

Go:   // 手写递归
来源：http://dali.jinqigufen.top/Article/details/gtoanucvbk.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.snrcjt.cn/Article/details/gteddpgxaj.html

C#:   // 手写递归
来源：http://dali.sysykeji.top/Article/details/gtzfwpycpf.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.gogol.net.cn/Article/details/gtzyzuqlhb.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.yueranfly.top/Article/details/gtdtcpqafa.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.hongshengwenyu.top/Article/details/gtjkyptvlf.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.nanxinkj.top/Article/details/gtltotsxkv.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.shuidangran.top/Article/details/gtvznoeipz.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgvtnfunm.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.quarkkingdee.top/Article/details/gtickezxlm.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.jqgfzy.top/Article/details/gthrhludhc.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.havefunace.top/Article/details/gtuiafmemc.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtfjqubsnk.html

O. 并发与异步
来源：http://dali.hnxiangtu.top/Article/details/gtsotociix.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtcxdpznlk.html

[O01] 启动一个线程
来源：http://dali.snrcjt.cn/Article/details/gtxvflpjiy.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.jqgufenzy.top/Article/details/gtnxcwxwjo.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.tianlin.xyz/Article/details/gtpxywjuls.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.yanxiufei.cn/Article/details/gtywlazeig.html

TS:   // 同 JS
来源：http://dali.zhengqikj.top/Article/details/gtrnbrowst.html

Java: new Thread(() -> f()).start()
来源：http://dali.iojbl.cn/Article/details/gthubdkokg.html

Go:   go f()
来源：http://dali.meibo888.top/Article/details/gtskanonzx.html

Ruby: Thread.new { f }
来源：http://dali.zhiwuduotai.top/Article/details/gtbkumdevj.html

C#:   Task.Run(() => F());
来源：http://dali.jiagoushi.top/Article/details/gtpexuqxem.html

[O02] 使用线程池
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnuenxfio.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.316326.xyz/Article/details/gtwzkcgetn.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.aizwys.cn/Article/details/gtrmfwqxdm.html

JS:   // worker_threads 线程池
来源：http://dali.ybcxt.top/Article/details/gtrujvppxi.html

TS:   // worker_threads 线程池
来源：http://dali.smart0.xyz/Article/details/gtazdirapi.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.nanxuanxn.top/Article/details/gtkqtxulnd.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.jlsjyb.cn/Article/details/gtyqrhwqgy.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.feifeiyinyue.top/Article/details/gtfecuomaj.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.kuanghao11.cn/Article/details/gtvhxkvaoc.html

[O03] 加锁保护共享数据
来源：http://dali.ywan-chungtsiang.top/Article/details/gtetawitcl.html

Py:   with lock: shared += 1
来源：http://dali.haohaochexian.top/Article/details/gtmvywnyei.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.shanyushiyangkeji.top/Article/details/gtldrylfcp.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.c1oappe.top/Article/details/gtbqznuqfc.html

TS:   // 同 JS
来源：http://dali.yvedp.cn/Article/details/gtzvgmewdt.html

Java: synchronized (this) { shared++; }
来源：http://dali.jiagoushi.top/Article/details/gttlzfemmi.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.snrcjt.cn/Article/details/gtnewhljyt.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.nanxinkj.top/Article/details/gtwzylcura.html

C#:   lock (gate) { shared++; }
来源：http://dali.kuanghao11.cn/Article/details/gtfcxpodrk.html

[O04] 定义异步函数并等待
来源：http://dali.dianchejie.cn/Article/details/gtdawjrmcj.html

Py:   async def f():⏎    await g()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjccivqtf.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.xuanzx.com/Article/details/gtehtnbbbq.html

JS:   async function f() { await g(); }
来源：http://dali.meibo888.top/Article/details/gtdlqfuixn.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.chenzaomai.com/Article/details/gtmuxrdqte.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.yj20258.top/Article/details/gtxduvewij.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.shuidangran.top/Article/details/gtdkcfcfej.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.ivvv.top/Article/details/gtquhqyprv.html

C#:   async Task F() { await G(); }
来源：http://dali.xinyue.icu/Article/details/gtagyuhbpk.html

[O05] 并发执行并等待全部完成
来源：http://dali.hnqzz.top/Article/details/gthzmshija.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmfixtave.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.xuetiantiany.cn/Article/details/gtojbzjuke.html

JS:   await Promise.all(tasks)
来源：http://dali.dianchejie.cn/Article/details/gtnisesjyl.html

TS:   await Promise.all(tasks)
来源：http://dali.zhixingplan.top/Article/details/gtkvswyeae.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.hnxiangtu.top/Article/details/gtzwydaiwf.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zycfv.cn/Article/details/gtsldmvspm.html

Ruby: threads.map(&:join)
来源：http://dali.zdqjudy.top/Article/details/gttncdhbaf.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.0kj1m.cn/Article/details/gtjrxbbvkq.html

[O06] 使用进程池
来源：http://dali.yonumen.top/Article/details/gtmlkcolcl.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.cashguo.top/Article/details/gtqiclmlja.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.xylfe.cn/Article/details/gtloensabs.html

JS:   // child_process / cluster 模块
来源：http://dali.dianchejie.cn/Article/details/gtujoydaqx.html

TS:   // child_process / cluster 模块
来源：http://dali.feifeiyinyue.top/Article/details/gtiolzcxut.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.hongshengwenyu.top/Article/details/gthcroazmz.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.wangshuangyany.cn/Article/details/gtdletiflp.html

Ruby: // fork 块
来源：http://dali.shangyingyoupin.top/Article/details/gtymxvsxzr.html

C#:   Parallel.For
来源：http://dali.zhixingplan.top/Article/details/gtzlfdoncw.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtuyzjdack.html

P. 常用工具函数
来源：http://dali.yueranfly.top/Article/details/gtyhzabtix.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gttfidmmyy.html

[P01] 生成 UUID
来源：http://dali.jinqigufen.top/Article/details/gtygednfcn.html

Py:   str(uuid.uuid4())
来源：http://dali.yuxming.cn/Article/details/gtoaptumlk.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.mhx1999.top/Article/details/gtrjxaktpi.html

JS:   crypto.randomUUID()
来源：http://dali.tanke756.top/Article/details/gtdbqjkqvc.html

TS:   crypto.randomUUID()
来源：http://dali.wangshuangyany.cn/Article/details/gtfeycdmva.html

Java: UUID.randomUUID().toString()
来源：http://dali.guowangkeji.top/Article/details/gtllkkqcny.html

Go:   // 用 github.com/google/uuid
来源：http://dali.jiagoushi.top/Article/details/gtgdwqllhs.html

Ruby: SecureRandom.uuid
来源：http://dali.haohaochexian.top/Article/details/gtjwpermwo.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.snrcjt.cn/Article/details/gteddvkoce.html

[P02] MD5 / SHA256 摘要
来源：http://dali.316326.xyz/Article/details/gtqptbganh.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.shuidangran.top/Article/details/gtbgieewkq.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.yuxming.cn/Article/details/gtnumaecrk.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.snrcjt.cn/Article/details/gtnhuspusa.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.hongshengwenyu.top/Article/details/gtuukytinp.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhengqikj.top/Article/details/gtvdnssxni.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.cdnleiting.top/Article/details/gtgablekzg.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.wangdashe.top/Article/details/gthfjrkfow.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.chenjidiqi.icu/Article/details/gtxyptjjpm.html

[P03] 生成短随机字符串
来源：http://dali.zdqjudy.top/Article/details/gtinkzpzvh.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.cucudq.cn/Article/details/gtxfbrckhe.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.0kj1m.cn/Article/details/gtvosufayd.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.chenjidiqi.icu/Article/details/gtlnbctiqk.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.birdmap.top/Article/details/gtmxxaoavf.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.cdnleiting.top/Article/details/gthltatzws.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.aizwys.cn/Article/details/gtgesxozbd.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.mhx1999.top/Article/details/gtnsnevpta.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlvtrqyim.html

[P04] 求长度
来源：http://dali.cheryme.top/Article/details/gttrxomwkz.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.aizwys.cn/Article/details/gtqpblyymn.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yuxming.cn/Article/details/gtcjtypmvc.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkwwbwuyo.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.haohaochexian.top/Article/details/gtuiiwfwtd.html

Java: list.size();  map.size();  s.length()
来源：http://dali.hnqzz.top/Article/details/gtjohvsdid.html

Go:   len(arr);  len(m)
来源：http://dali.yj202588.top/Article/details/gtkrvchotj.html

Ruby: x.length;  x.size
来源：http://dali.ybcxt.top/Article/details/gterpqgjzr.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.guannengcc.top/Article/details/gtpycocxir.html

[P05] 判断两个对象内容是否相等
来源：http://dali.quarkkingdee.top/Article/details/gtwziiafmy.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.nanxinkj.top/Article/details/gtaxohvrlz.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.gotoacloud.top/Article/details/gtvsrcsbyj.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.hysaishi.cn/Article/details/gtuqvirdtp.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.tian-w.cn/Article/details/gthjsywqnh.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.snrcjt.cn/Article/details/gtntcankpp.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.nanxinkj.top/Article/details/gtkgujrdep.html

Ruby: a == b
来源：http://dali.pycfn.com/Article/details/gtbdvshuxr.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.dianchejie.cn/Article/details/gtcwqopzuq.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.jyoumei.cn/Article/details/gtunacgpvx.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.fengsongda.top/Article/details/gtsdazlgrs.html

PHP:  if (empty($x)) {}
来源：http://dali.wangdashe.top/Article/details/gtzvqvccgn.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.hysaishi.cn/Article/details/gttllaktox.html

TS:   if (x == null) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtodqkzohg.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.jiagoushi.top/Article/details/gttjmqlhno.html

Go:   if x == nil {}
来源：http://dali.yj202588.top/Article/details/gtibsdeukm.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zdqjudy.top/Article/details/gtwfeygxgd.html

C#:   if (x is null) {}
来源：http://dali.iojbl.cn/Article/details/gtgbxwdwfq.html

[P07] 防抖与节流
来源：http://dali.ybcxt.top/Article/details/gtlawwdyji.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhixingplan.top/Article/details/gtgbcnfaet.html

PHP:  // 手写时间戳比较
来源：http://dali.zhixingplan.top/Article/details/gttoxwhpld.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jianghu66.top/Article/details/gtuolslmtr.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.cqqwz.cn/Article/details/gtsdpyhrjp.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.yangfankeji.com/Article/details/gtytfadsud.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.jinqigfzy.top/Article/details/gthztzhxlh.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.wangshuangyany.cn/Article/details/gtihgnvyep.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.xinyue.icu/Article/details/gtcejbqgso.html

[P08] 处理浮点精度问题
来源：http://dali.hysaishi.cn/Article/details/gtprmelvtn.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.svipenyu.cn/Article/details/gtftrlvfue.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.aizwys.cn/Article/details/gtanoadask.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.ybcxt.top/Article/details/gtbpjfyqtv.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.tianlin.xyz/Article/details/gtniaavbqt.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.jinyuanbaomall.cn/Article/details/gthxhystvd.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.jqgfzy.top/Article/details/gtypelttft.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhongyouzk.top/Article/details/gtqyhpwiyr.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.xziqi.cn/Article/details/gtccthluvj.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtxfdvztrk.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.andypj.xyz/Article/details/gteavrbged.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtwmdvpnzj.html

[Q01] 创建表
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpnzhjnjm.html

CREATE TABLE users (
来源：http://dali.shuidangran.top/Article/details/gtaopwevhi.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.andypj.xyz/Article/details/gtheazylhx.html

name VARCHAR(50) NOT NULL,
来源：http://dali.cashguo.top/Article/details/gtufpzzkaj.html

email VARCHAR(100) UNIQUE,
来源：http://dali.cucudq.cn/Article/details/gtpdahwukg.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.daria6918.cn/Article/details/gtookcjdee.html

);
来源：http://dali.redwolf501.top/Article/details/gtyeiwaxlk.html

[Q02] 创建带外键的表
来源：http://dali.wangshuangyany.cn/Article/details/gtncmambfm.html

CREATE TABLE orders (
来源：http://dali.jinqigufen.top/Article/details/gtbwhbchha.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqzbzeyip.html

user_id INT NOT NULL,
来源：http://dali.mhx1999.top/Article/details/gtodffbobk.html

amount DECIMAL(10, 2),
来源：http://dali.jianghu66.top/Article/details/gtlqglkgyv.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.feifeiyinyue.top/Article/details/gtzgbkzbau.html

);
来源：http://dali.yj20258.top/Article/details/gtbugetcjc.html

[Q03] 增加列
来源：http://dali.andypj.xyz/Article/details/gtutcrspie.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.shangyingyoupin.top/Article/details/gtnpefuzuh.html

[Q04] 修改列类型
来源：http://dali.quarkkingdee.top/Article/details/gtafxeqrue.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhiwuduotai.top/Article/details/gtoyxxwaqn.html

[Q05] 重命名列
来源：http://dali.svipenyu.cn/Article/details/gtzcfvuffe.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.cashguo.top/Article/details/gtvlzhgayy.html

[Q06] 删除列
来源：http://dali.kuanghao11.cn/Article/details/gtumjzjviw.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.316326.xyz/Article/details/gtpjoenuxz.html

[Q07] 删除表
来源：http://dali.fengsongda.top/Article/details/gtsurjnyjk.html

DROP TABLE IF EXISTS orders;
来源：http://dali.yueranfly.top/Article/details/gtsmhgwpsh.html

[Q08] 创建普通索引
来源：http://dali.hongshengwenyu.top/Article/details/gtfozbrjsp.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.vqdsnc.cn/Article/details/gtlrndrpnv.html

[Q09] 创建唯一索引
来源：http://dali.aizwys.cn/Article/details/gthmtkgyfd.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.316326.xyz/Article/details/gtyaemdlvn.html

[Q10] 插入单行
来源：http://dali.zhiwuduotai.top/Article/details/gtdxbyaovz.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.wangshuangyany.cn/Article/details/gtpcgpxvpv.html

[Q11] 一次插入多行
来源：http://dali.sweek.top/Article/details/gttfrkygqb.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.ywan-chungtsiang.top/Article/details/gttcpldnwr.html

[Q12] 插入后取自增 ID
来源：http://dali.havefunace.top/Article/details/gteemhighq.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.tianlin.xyz/Article/details/gtftsiqjno.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.iojbl.cn/Article/details/gthvcfmcxi.html

[Q13] 忽略重复插入
来源：http://dali.sxryk.cn/Article/details/gticwpoixq.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.shzxlz.cn/Article/details/gtrvtozyhv.html

[Q14] 存在则更新（upsert）
来源：http://dali.iojbl.cn/Article/details/gtlecefaci.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.316326.xyz/Article/details/gtyaadkbbb.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.sufxvd.cn/Article/details/gtpdmlpkqy.html

[Q15] 查询全部
来源：http://dali.yj20258888.top/Article/details/gtmgepwkzs.html

SELECT * FROM users;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrckwxrld.html

[Q16] 查询指定列
来源：http://dali.andypj.xyz/Article/details/gtvqmlxfcn.html

SELECT id, name FROM users;
来源：http://dali.shuidangran.top/Article/details/gtbrntycrc.html

[Q17] 条件查询
来源：http://dali.meibo888.top/Article/details/gttkvbdbof.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.tanke756.top/Article/details/gttsbvfuvn.html

[Q18] 模糊匹配
来源：http://dali.sweek.top/Article/details/gtsdonwmwq.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.feifeiyinyue.top/Article/details/gtdhmqpunb.html

[Q19] 范围查询
来源：http://dali.daxiang520.top/Article/details/gtruwdhopf.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.cqqwz.cn/Article/details/gtpzvldapi.html

[Q20] IN 列表
来源：http://dali.yongpay.top/Article/details/gtbiggjijq.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.yongpay.top/Article/details/gtidwdqbat.html

[Q21] 空值判断
来源：http://dali.shangyingyoupin.top/Article/details/gtvixpwkqx.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhijiandao.cn/Article/details/gtvsucqvsl.html

[Q22] 排序
来源：http://dali.jiagoushi.top/Article/details/gtakqbbvsd.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.yangfankeji.com/Article/details/gtwbewyoxe.html

[Q23] 分页
来源：http://dali.zhiwuduotai.top/Article/details/gtsfkxkdnl.html


<!-- 参考信息 -->