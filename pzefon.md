代发 wailian999

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.sweek.top/Article/details/gtcmjihati.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtldxhcdix.html

N. 数据结构与算法
来源：http://dali.cashguo.top/Article/details/gtdkpikoty.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtspcezkts.html

[N01] 二分查找（有序数组）
来源：http://dali.xinyue.icu/Article/details/gtkshnpcvy.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.hywenlv.cn/Article/details/gtlrnbgolb.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.shzxlz.cn/Article/details/gtvxtrjppf.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jinqigufen.top/Article/details/gtumfytpjx.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zycfv.cn/Article/details/gtfholejls.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.pengpengdd.cyou/Article/details/gtefeqpawu.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.pengpengdd.cyou/Article/details/gteojqkwda.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.kuanghao11.cn/Article/details/gtmlxabdqs.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.cucudq.cn/Article/details/gtusftfhfr.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zycfv.cn/Article/details/gtojepvrqs.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.gaohongyu789.top/Article/details/gtcbvrpzhg.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.ehwqpu.com/Article/details/gtaubimyni.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.shangyingyoupin.top/Article/details/gtjzbnexky.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yanxiufei.cn/Article/details/gtptvvdzht.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.chenlongwang.top/Article/details/gtxgtxfoax.html

Go:   slices.Sort(arr)
来源：http://dali.jinghuilouyu.cn/Article/details/gtdwepfbpf.html

Ruby: arr.sort
来源：http://dali.zhixingplan.top/Article/details/gtghovtifk.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.haohaochexian.top/Article/details/gtowfjdxlq.html

[N03] 快速排序（分治示例）
来源：http://dali.vqdsnc.cn/Article/details/gtdwaeqzyn.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.gotoacloud.top/Article/details/gtakwkzchk.html

PHP:  // 递归实现，或用 usort
来源：http://dali.c1oappe.top/Article/details/gtslixixmq.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.mhx1999.top/Article/details/gtcofapjbk.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.tian-w.cn/Article/details/gtuvtdigdi.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.smart0.xyz/Article/details/gtdbcnucpd.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zycfv.cn/Article/details/gtuohavflj.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.havefunace.top/Article/details/gtxxygzlzb.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.tanke756.top/Article/details/gtcscqdnwd.html

[N04] 斐波那契数列
来源：http://dali.jiagoushi.top/Article/details/gtvdkmyreo.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.gzhubu.top/Article/details/gtioqtfmze.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.0kj1m.cn/Article/details/gtwxyermkz.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.sysykeji.top/Article/details/gtnanantjc.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.gaohongyu789.top/Article/details/gtwcwtlbbd.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.ivvv.top/Article/details/gtccheutdv.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.xziqi.cn/Article/details/gtlzoufqis.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.0kj1m.cn/Article/details/gtktzrxeld.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.tianlin.xyz/Article/details/gtxxmsppgb.html

[N05] 最大公约数
来源：http://dali.gogol.net.cn/Article/details/gtxqjldwwq.html

Py:   math.gcd(a, b)
来源：http://dali.gzhubu.top/Article/details/gtipuxszlt.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.svipenyu.cn/Article/details/gtikextfmf.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.dashuyun.cn/Article/details/gtoyturmdo.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jqgfzy.top/Article/details/gtrffctqvf.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.xylfe.cn/Article/details/gtufoylbxs.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.yvedp.cn/Article/details/gtvjuhwvdt.html

Ruby: a.gcd(b)
来源：http://dali.chenzaomai.com/Article/details/gtfnkyojxi.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttbdelujj.html

[N06] 判断回文字符串
来源：http://dali.yanxiufei.cn/Article/details/gtwzhrbbks.html

Py:   s == s[::-1]
来源：http://dali.gotoacloud.top/Article/details/gtuwtgozbk.html

PHP:  $s === strrev($s);
来源：http://dali.cqqwz.cn/Article/details/gtrjgzhrwj.html

JS:   s === [...s].reverse().join("")
来源：http://dali.xylfe.cn/Article/details/gtmtrsnytw.html

TS:   s === [...s].reverse().join("")
来源：http://dali.kuanghao11.cn/Article/details/gtlpqflmuh.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.fzhhl.top/Article/details/gtgscxaatm.html

Go:   // 双指针从两端比较
来源：http://dali.sysykeji.top/Article/details/gtfjcjpdyj.html

Ruby: s == s.reverse
来源：http://dali.ivvv.top/Article/details/gtumztegnv.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zycfv.cn/Article/details/gtqzluqouz.html

[N07] 两数之和（返回下标）
来源：http://dali.smart0.xyz/Article/details/gtzupfgims.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.xuanzx.com/Article/details/gtknfeqxvf.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.ehwqpu.com/Article/details/gtcuhiudjt.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.316326.xyz/Article/details/gtaxjfvlxj.html

TS:   // 手写 Map<string, number>
来源：http://dali.jinghuilouyu.cn/Article/details/gtvdljptpg.html

Java: // 手写 HashMap
来源：http://dali.dianchejie.cn/Article/details/gthqeoajvu.html

Go:   // 手写 map[int]int
来源：http://dali.xinyue.icu/Article/details/gteynsfqiu.html

Ruby: // 手写 Hash
来源：http://dali.cheryme.top/Article/details/gtcfznbsgo.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.snrcjt.cn/Article/details/gtjvmxrnws.html

[N08] 生成全排列
来源：http://dali.ivvv.top/Article/details/gtqgzrzjuo.html

Py:   itertools.permutations(arr)
来源：http://dali.guowangkeji.top/Article/details/gtydfacnix.html

PHP:  // 手写递归交换
来源：http://dali.jinqigfzy.top/Article/details/gtunqtzsrz.html

JS:   // 手写回溯递归
来源：http://dali.chenlongwang.top/Article/details/gtwusieyjg.html

TS:   // 手写回溯递归
来源：http://dali.nanxuanxn.top/Article/details/gtehfjjyxf.html

Java: // 手写回溯递归
来源：http://dali.jinqigufen.top/Article/details/gtotucxxcj.html

Go:   // 手写回溯递归
来源：http://dali.guowangkeji.top/Article/details/gteziqwgtj.html

Ruby: arr.permutation.to_a
来源：http://dali.chenjidiqi.icu/Article/details/gttmwnrmey.html

C#:   // 手写回溯递归
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxtyqbmxq.html

[N09] 栈与队列
来源：http://dali.kuanghao11.cn/Article/details/gtxabzazww.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.jyoumei.cn/Article/details/gtfdbyckbd.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.sweek.top/Article/details/gtqjedzbtq.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.chenzaomai.com/Article/details/gtbgdrjiqg.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhongyouzk.top/Article/details/gtvuvhxpyg.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.pycfn.com/Article/details/gtchgkfaoy.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhoulong.xyz/Article/details/gtvsxbvcfo.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.hammf.cn/Article/details/gtgwxjdeei.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.yueranfly.top/Article/details/gtxetxdrwy.html

[N10] 链表节点定义
来源：http://dali.cashguo.top/Article/details/gtqqfmyuux.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.yanxiufei.cn/Article/details/gttnymprln.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.xziqi.cn/Article/details/gtjdstizvt.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.nwbrower.top/Article/details/gtnusnbuza.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.xylfe.cn/Article/details/gtuoorytpv.html

Java: class Node { int v; Node next; }
来源：http://dali.yj20258.top/Article/details/gtxjusfiiu.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.gaohongyu789.top/Article/details/gtkzashgal.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.jqgufenzy.top/Article/details/gthrvjtkyn.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.shanyushiyangtech.top/Article/details/gttfehpzzd.html

[N11] 二叉树中序遍历
来源：http://dali.jyoumei.cn/Article/details/gtmwxsgvvx.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.xuanzx.com/Article/details/gtfghzalpf.html

PHP:  // 手写递归函数
来源：http://dali.fengsongda.top/Article/details/gtnlekdwng.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.cucudq.cn/Article/details/gtzcrtpzho.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.nwbrower.top/Article/details/gtrrfifjve.html

Java: // 手写递归
来源：http://dali.tianlin.xyz/Article/details/gtzkdnbbfd.html

Go:   // 手写递归
来源：http://dali.snrcjt.cn/Article/details/gthoawxvsz.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.cqqwz.cn/Article/details/gtpoksnqqf.html

C#:   // 手写递归
来源：http://dali.zhoulong.xyz/Article/details/gtuadiwfbp.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.c1oappe.top/Article/details/gtdawczxcf.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.xinyue.icu/Article/details/gtyxhzbzur.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.jlsjyb.cn/Article/details/gtlewnyqff.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.dianchejie.cn/Article/details/gtzmvyyqyk.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhixingplan.top/Article/details/gtnccpxtpc.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yonumen.top/Article/details/gtdgsxicuv.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqiayrkav.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.cucudq.cn/Article/details/gtpbsfutwt.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.gogol.net.cn/Article/details/gtdeenpldt.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtrpfpejex.html

O. 并发与异步
来源：http://dali.hammf.cn/Article/details/gtwlwoffrw.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtiahmxiyj.html

[O01] 启动一个线程
来源：http://dali.wangdashe.top/Article/details/gtzfvmpsez.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.aibaodan.cn/Article/details/gtbemslcld.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.aibaodan.cn/Article/details/gthjangcly.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.yueranfly.top/Article/details/gtmeymyate.html

TS:   // 同 JS
来源：http://dali.nwbrower.top/Article/details/gtxvqlhrox.html

Java: new Thread(() -> f()).start()
来源：http://dali.wangdashe.top/Article/details/gtzffeicae.html

Go:   go f()
来源：http://dali.jinghuilouyu.cn/Article/details/gtemctsckc.html

Ruby: Thread.new { f }
来源：http://dali.yangfankeji.com/Article/details/gtxuxktzle.html

C#:   Task.Run(() => F());
来源：http://dali.xziqi.cn/Article/details/gtkinnexdq.html

[O02] 使用线程池
来源：http://dali.jinqigufen.top/Article/details/gtjaswwfqm.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.gogol.net.cn/Article/details/gtzlpijapu.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.svipenyu.cn/Article/details/gtuqasqiyx.html

JS:   // worker_threads 线程池
来源：http://dali.cdnleiting.top/Article/details/gtigvuqaib.html

TS:   // worker_threads 线程池
来源：http://dali.kuanghao11.cn/Article/details/gthudzxgpg.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.jqgufenzy.top/Article/details/gtctttdnxc.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.yj20258.top/Article/details/gtywoqptwx.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.sysykeji.top/Article/details/gtkhqxyddt.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.hysaishi.cn/Article/details/gtscirzndb.html

[O03] 加锁保护共享数据
来源：http://dali.shuidangran.top/Article/details/gthvmawvxq.html

Py:   with lock: shared += 1
来源：http://dali.kuanghao11.cn/Article/details/gtsyyimnla.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.yj20258888.top/Article/details/gtzmsjvveg.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.xziqi.cn/Article/details/gtgormtcsm.html

TS:   // 同 JS
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzihtpnhp.html

Java: synchronized (this) { shared++; }
来源：http://dali.0kj1m.cn/Article/details/gtfanigoka.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.gogol.net.cn/Article/details/gtpkqqpuvo.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.xuetiantiany.cn/Article/details/gtbmwcnflt.html

C#:   lock (gate) { shared++; }
来源：http://dali.yj202588.top/Article/details/gtlksuobwz.html

[O04] 定义异步函数并等待
来源：http://dali.shanyushiyangtech.top/Article/details/gtfeaqhbwd.html

Py:   async def f():⏎    await g()
来源：http://dali.ehwqpu.com/Article/details/gtaaavqfmx.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.shanyushiyangtech.top/Article/details/gtnbgrdfwp.html

JS:   async function f() { await g(); }
来源：http://dali.gaohongyu789.top/Article/details/gtgtkfrwur.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.ppjwa.cn/Article/details/gtfkfzgqfd.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.hammf.cn/Article/details/gtilsksqrj.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.sufxvd.cn/Article/details/gtrbrldrlj.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.jinyuanbaomall.cn/Article/details/gtptdsrhlr.html

C#:   async Task F() { await G(); }
来源：http://dali.snrcjt.cn/Article/details/gtcufkweyx.html

[O05] 并发执行并等待全部完成
来源：http://dali.shanyushiyangtech.top/Article/details/gtnekgeosi.html

Py:   asyncio.gather(*tasks)
来源：http://dali.wangshuangyany.cn/Article/details/gtxvwvktdk.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.yangfankeji.com/Article/details/gtpnzokluk.html

JS:   await Promise.all(tasks)
来源：http://dali.ivvv.top/Article/details/gtpumwlkjc.html

TS:   await Promise.all(tasks)
来源：http://dali.ybcxt.top/Article/details/gtsioajvku.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.cdnleiting.top/Article/details/gtibjdobjp.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.fengsongda.top/Article/details/gtyuxezapm.html

Ruby: threads.map(&:join)
来源：http://dali.svipenyu.cn/Article/details/gtpqfdqzio.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.mhx1999.top/Article/details/gtzomokxdg.html

[O06] 使用进程池
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtavlgwpou.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.vqdsnc.cn/Article/details/gtexyxlkfe.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.jqgfzy.top/Article/details/gtostfygvo.html

JS:   // child_process / cluster 模块
来源：http://dali.ybcxt.top/Article/details/gtoesdzibn.html

TS:   // child_process / cluster 模块
来源：http://dali.cashguo.top/Article/details/gtnkrcadpt.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.tanke756.top/Article/details/gtoqrmlnzi.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.tianlin.xyz/Article/details/gtizyzxmjm.html

Ruby: // fork 块
来源：http://dali.yj20258.top/Article/details/gtatjzigeh.html

C#:   Parallel.For
来源：http://dali.0kj1m.cn/Article/details/gtofhtsmpt.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtdxeqcsro.html

P. 常用工具函数
来源：http://dali.andypj.xyz/Article/details/gtncvxxjxl.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtkvhakrdk.html

[P01] 生成 UUID
来源：http://dali.hongshengwenyu.top/Article/details/gtszsnxepi.html

Py:   str(uuid.uuid4())
来源：http://dali.zhongyouzk.top/Article/details/gtvctkiscp.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.shangyingyoupin.top/Article/details/gtliwiuhsg.html

JS:   crypto.randomUUID()
来源：http://dali.jianghu66.top/Article/details/gtaeuwfltg.html

TS:   crypto.randomUUID()
来源：http://dali.pycfn.com/Article/details/gthousvbqm.html

Java: UUID.randomUUID().toString()
来源：http://dali.sweek.top/Article/details/gtkndtuqbf.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhongyouzk.top/Article/details/gtluwkwtda.html

Ruby: SecureRandom.uuid
来源：http://dali.hnqzz.top/Article/details/gtujmcqgbi.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zdqjudy.top/Article/details/gtwktdoeey.html

[P02] MD5 / SHA256 摘要
来源：http://dali.xuanzx.com/Article/details/gtvopwekjp.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.daxiang520.top/Article/details/gtoasyhrye.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmuqkcien.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.ydzc1.top/Article/details/gtimsffyvc.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.cdnleiting.top/Article/details/gtwtopbbhi.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.pycfn.com/Article/details/gtfswsbhdy.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.hnxiangtu.top/Article/details/gtreosdqbk.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gtziitrojc.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.wangdashe.top/Article/details/gtckvbqafo.html

[P03] 生成短随机字符串
来源：http://dali.hnqzz.top/Article/details/gtsingmelb.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.andypj.xyz/Article/details/gtcjhgggbl.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.chenzaomai.com/Article/details/gtygqejohq.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jyoumei.cn/Article/details/gtosgyldhg.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.vqdsnc.cn/Article/details/gtfnttihyk.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.aibaodan.cn/Article/details/gtsgkphlnb.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.pengpengdd.cyou/Article/details/gtauuxojpx.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.yueranfly.top/Article/details/gtxpkuymnr.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.tanke756.top/Article/details/gtjygraprw.html

[P04] 求长度
来源：http://dali.jqgufenzy.top/Article/details/gtuktrmhmz.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.vqdsnc.cn/Article/details/gthhiijukk.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.andypj.xyz/Article/details/gtfnpdnnuq.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yongpay.top/Article/details/gtalwawuyb.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.kuanghao11.cn/Article/details/gtfoussnek.html

Java: list.size();  map.size();  s.length()
来源：http://dali.wangshuangyany.cn/Article/details/gtxivdegox.html

Go:   len(arr);  len(m)
来源：http://dali.jinqigfzy.top/Article/details/gthocqdhay.html

Ruby: x.length;  x.size
来源：http://dali.guowangkeji.top/Article/details/gthnkpnhnj.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.hongshengwenyu.top/Article/details/gtqbgtxnkz.html

[P05] 判断两个对象内容是否相等
来源：http://dali.nanxuanxn.top/Article/details/gtwxkjgqtw.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.jiagoushi.top/Article/details/gthqlcnarw.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.fzhhl.top/Article/details/gtfuvltekb.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.iojbl.cn/Article/details/gtniklobsp.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gttncvlcef.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.dashuyun.cn/Article/details/gttakjaaxx.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhengqikj.top/Article/details/gtdqecuwlh.html

Ruby: a == b
来源：http://dali.pengpengdd.cyou/Article/details/gteqqjfwli.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.xziqi.cn/Article/details/gtfmcuopge.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhiwuduotai.top/Article/details/gthxykhbvq.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.sxryk.cn/Article/details/gtpxldihki.html

PHP:  if (empty($x)) {}
来源：http://dali.jqgufenzy.top/Article/details/gtacdvphps.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.tian-w.cn/Article/details/gtxgmwmqvj.html

TS:   if (x == null) {}
来源：http://dali.xuetiantiany.cn/Article/details/gtiboeeyef.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.wangdashe.top/Article/details/gtqzscjqvr.html

Go:   if x == nil {}
来源：http://dali.redwolf501.top/Article/details/gtvmnrtgvu.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.nanxuanxn.top/Article/details/gtslhhnmqy.html

C#:   if (x is null) {}
来源：http://dali.0kj1m.cn/Article/details/gtdvtdlmpf.html

[P07] 防抖与节流
来源：http://dali.cqqwz.cn/Article/details/gtgdkcwedp.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhongyouzk.top/Article/details/gteqaahxff.html

PHP:  // 手写时间戳比较
来源：http://dali.zhongyouzk.top/Article/details/gturibimva.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hysaishi.cn/Article/details/gtsbuhxqbp.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.ydzc1.top/Article/details/gtmboyykul.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.jianghu66.top/Article/details/gtxlhnijzn.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.birdmap.top/Article/details/gtcxcdoten.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.ivvv.top/Article/details/gtryehnfvy.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.snrcjt.cn/Article/details/gtnlwktwtt.html

[P08] 处理浮点精度问题
来源：http://dali.wangshuangyany.cn/Article/details/gtptzbgvil.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zdqjudy.top/Article/details/gtkkmahpcp.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.aizwys.cn/Article/details/gtvcfmstea.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.meibo888.top/Article/details/gttngamhhi.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.ybcxt.top/Article/details/gtyccopzer.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.daria6918.cn/Article/details/gtutjvqgsu.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.cdnleiting.top/Article/details/gttinlppse.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.shangyingyoupin.top/Article/details/gtkcndvziv.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.ybcxt.top/Article/details/gtctudcwtd.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaqzeccat.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.yongpay.top/Article/details/gtguosuqrd.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtskrcsrjr.html

[Q01] 创建表
来源：http://dali.pengpengdd.cyou/Article/details/gtzuemkzte.html

CREATE TABLE users (
来源：http://dali.jqgufenzy.top/Article/details/gtxuvjjlhd.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.ydzc1.top/Article/details/gtniplfuci.html

name VARCHAR(50) NOT NULL,
来源：http://dali.jinqigufen.top/Article/details/gtdgsmvubw.html

email VARCHAR(100) UNIQUE,
来源：http://dali.jqgfzy.top/Article/details/gtdqehqere.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.jyoumei.cn/Article/details/gtzzregmcg.html

);
来源：http://dali.xuanzx.com/Article/details/gtpxwjzwrt.html

[Q02] 创建带外键的表
来源：http://dali.ppjwa.cn/Article/details/gtedtojnws.html

CREATE TABLE orders (
来源：http://dali.fzhhl.top/Article/details/gtawdvzhkc.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtndjzpavc.html

user_id INT NOT NULL,
来源：http://dali.smart0.xyz/Article/details/gthhhvxzot.html

amount DECIMAL(10, 2),
来源：http://dali.gotoacloud.top/Article/details/gtgszhwawa.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.xinyue.icu/Article/details/gthjuppabm.html

);
来源：http://dali.shuidangran.top/Article/details/gtudsaoevr.html

[Q03] 增加列
来源：http://dali.yuxming.cn/Article/details/gtagkfmzdu.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.hammf.cn/Article/details/gtbxngaisj.html

[Q04] 修改列类型
来源：http://dali.ywan-chungtsiang.top/Article/details/gtofqyfogg.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.andypj.xyz/Article/details/gtqarbvyqs.html

[Q05] 重命名列
来源：http://dali.meibo888.top/Article/details/gtzwvqhwdh.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.haohaochexian.top/Article/details/gtkpcmrovi.html

[Q06] 删除列
来源：http://dali.yuxming.cn/Article/details/gtvszibskb.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.jinqigfzy.top/Article/details/gtlypxyqpn.html

[Q07] 删除表
来源：http://dali.zhoulong.xyz/Article/details/gtthxkdwwt.html

DROP TABLE IF EXISTS orders;
来源：http://dali.dashuyun.cn/Article/details/gtzmveocvm.html

[Q08] 创建普通索引
来源：http://dali.jinyuanbaomall.cn/Article/details/gtljiropcw.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.yuanzhike.top/Article/details/gtsjdpmnec.html

[Q09] 创建唯一索引
来源：http://dali.havefunace.top/Article/details/gtcsaicsvt.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.fzhhl.top/Article/details/gtmqeketbx.html

[Q10] 插入单行
来源：http://dali.xuetiantiany.cn/Article/details/gtcwounzoa.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.jinqigufen.top/Article/details/gtwhumqvvj.html

[Q11] 一次插入多行
来源：http://dali.cqqwz.cn/Article/details/gtwqqorfiw.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.tian-w.cn/Article/details/gtvjqvrgnk.html

[Q12] 插入后取自增 ID
来源：http://dali.hysaishi.cn/Article/details/gtrkgawrqm.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.redwolf501.top/Article/details/gtwchmrvyp.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.cqqwz.cn/Article/details/gtjphmkjdk.html

[Q13] 忽略重复插入
来源：http://dali.bjfxy.top/Article/details/gtujmtsalt.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.xylfe.cn/Article/details/gtwlynuksm.html

[Q14] 存在则更新（upsert）
来源：http://dali.zhiwuduotai.top/Article/details/gtalacsixn.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.yuanzhike.top/Article/details/gtwdfmejck.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.haohaochexian.top/Article/details/gtjdeflchm.html

[Q15] 查询全部
来源：http://dali.xziqi.cn/Article/details/gttgrrefrj.html

SELECT * FROM users;
来源：http://dali.ppjwa.cn/Article/details/gtmbrpttly.html

[Q16] 查询指定列
来源：http://dali.gogol.net.cn/Article/details/gtyxmpjglg.html

SELECT id, name FROM users;
来源：http://dali.yonumen.top/Article/details/gtwkqkecbn.html

[Q17] 条件查询
来源：http://dali.hfpthk.cn/Article/details/gtgafpasai.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwbldvfxy.html

[Q18] 模糊匹配
来源：http://dali.shanyushiyangtech.top/Article/details/gtvqamriqu.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.hnxiangtu.top/Article/details/gtphosnlbj.html

[Q19] 范围查询
来源：http://dali.yuanzhike.top/Article/details/gtyelaflrg.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.yanxiufei.cn/Article/details/gtittbpftf.html

[Q20] IN 列表
来源：http://dali.chenjidiqi.icu/Article/details/gtxzvlaotz.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.gotoacloud.top/Article/details/gtymzlxwkn.html

[Q21] 空值判断
来源：http://dali.nanxinkj.top/Article/details/gtszqyzbfb.html


<!-- 参考信息 -->