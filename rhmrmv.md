代发 wailian999

[N01] 二分查找（有序数组）
来源：http://dali.0kj1m.cn/Article/details/gtmwmsgvpp.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.snrcjt.cn/Article/details/gtwstxkysp.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.jqgfzy.top/Article/details/gtbkqjamtz.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zycfv.cn/Article/details/gthufshina.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrmxhkjso.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.mhx1999.top/Article/details/gtosozrqrc.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.gogol.net.cn/Article/details/gtrwvrmjpe.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.dashuyun.cn/Article/details/gtwptmgrfp.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.smart0.xyz/Article/details/gthdvhgpzw.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.yuxming.cn/Article/details/gtuiivgdzz.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.nanxinkj.top/Article/details/gtzbgbqlyh.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.gaohongyu789.top/Article/details/gtiplowcnc.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.ehwqpu.com/Article/details/gtmiqesvfk.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.aibaodan.cn/Article/details/gtcucyflsu.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.cdnleiting.top/Article/details/gttkzhlnky.html

Go:   slices.Sort(arr)
来源：http://dali.jinghuilouyu.cn/Article/details/gtenaxnwcz.html

Ruby: arr.sort
来源：http://dali.iojbl.cn/Article/details/gtpciadnjg.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.ivvv.top/Article/details/gtpbzterlg.html

[N03] 快速排序（分治示例）
来源：http://dali.hysaishi.cn/Article/details/gtjjcthynd.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.wangdashe.top/Article/details/gtrgzhdmkj.html

PHP:  // 递归实现，或用 usort
来源：http://dali.yj20258888.top/Article/details/gtlxaxlhdd.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.shzxlz.cn/Article/details/gtexpxhnvw.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jyoumei.cn/Article/details/gtfaaxdfno.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.yj202588.top/Article/details/gteevwbbqx.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaccnglnu.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.gzhubu.top/Article/details/gtwdejggcr.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.shzxlz.cn/Article/details/gtgirlssbc.html

[N04] 斐波那契数列
来源：http://dali.yj20258.top/Article/details/gtpyrfgssr.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.hongshengwenyu.top/Article/details/gtlsyqsabg.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.nwbrower.top/Article/details/gtsydxuvyo.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.shzxlz.cn/Article/details/gtwlaauwfm.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlsvmrwit.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.hfpthk.cn/Article/details/gtampaiqjp.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.yj20258.top/Article/details/gtayhozrrh.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.ehwqpu.com/Article/details/gtgsprgaru.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.xylfe.cn/Article/details/gtjxacpthh.html

[N05] 最大公约数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvtjrdlre.html

Py:   math.gcd(a, b)
来源：http://dali.hnqzz.top/Article/details/gtqhhqushw.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.tian-w.cn/Article/details/gtbohqugdl.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.cqqwz.cn/Article/details/gtopszvvdn.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jqgfzy.top/Article/details/gtbrbwfxxw.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.cheryme.top/Article/details/gtebrwjphy.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtknzdcanq.html

Ruby: a.gcd(b)
来源：http://dali.gogol.net.cn/Article/details/gtnioeuyul.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.iojbl.cn/Article/details/gtbayybjzp.html

[N06] 判断回文字符串
来源：http://dali.zdqjudy.top/Article/details/gtyguwdziy.html

Py:   s == s[::-1]
来源：http://dali.xuetiantiany.cn/Article/details/gttblayojk.html

PHP:  $s === strrev($s);
来源：http://dali.0kj1m.cn/Article/details/gtielzmduh.html

JS:   s === [...s].reverse().join("")
来源：http://dali.jqgfzy.top/Article/details/gtprzjrixh.html

TS:   s === [...s].reverse().join("")
来源：http://dali.daxiang520.top/Article/details/gteuqegwsp.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.meibo888.top/Article/details/gtqapeqlii.html

Go:   // 双指针从两端比较
来源：http://dali.jqgufenzy.top/Article/details/gtwwsvzdqa.html

Ruby: s == s.reverse
来源：http://dali.dianchejie.cn/Article/details/gtvlrecqmy.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.gzhubu.top/Article/details/gtjlpruigv.html

[N07] 两数之和（返回下标）
来源：http://dali.snrcjt.cn/Article/details/gtqikfryww.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.jiagoushi.top/Article/details/gthkejtmma.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.ivvv.top/Article/details/gtpajxqlsh.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.jlsjyb.cn/Article/details/gtewfarkep.html

TS:   // 手写 Map<string, number>
来源：http://dali.ydzc1.top/Article/details/gtkfsiamob.html

Java: // 手写 HashMap
来源：http://dali.ydzc1.top/Article/details/gtwlcxgrbw.html

Go:   // 手写 map[int]int
来源：http://dali.jianghu66.top/Article/details/gtfiofvmbp.html

Ruby: // 手写 Hash
来源：http://dali.hnqzz.top/Article/details/gtszmlrhqb.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.xuetiantiany.cn/Article/details/gtvnbkpodu.html

[N08] 生成全排列
来源：http://dali.quarkkingdee.top/Article/details/gtghywuoyg.html

Py:   itertools.permutations(arr)
来源：http://dali.xuanzx.com/Article/details/gtugzhwjoe.html

PHP:  // 手写递归交换
来源：http://dali.gzhubu.top/Article/details/gturtqiwdg.html

JS:   // 手写回溯递归
来源：http://dali.ivvv.top/Article/details/gtonitstbx.html

TS:   // 手写回溯递归
来源：http://dali.feifeiyinyue.top/Article/details/gtujaesfsj.html

Java: // 手写回溯递归
来源：http://dali.aizwys.cn/Article/details/gtjetcekqn.html

Go:   // 手写回溯递归
来源：http://dali.ivvv.top/Article/details/gtqixdfbod.html

Ruby: arr.permutation.to_a
来源：http://dali.dianchejie.cn/Article/details/gthlujxmph.html

C#:   // 手写回溯递归
来源：http://dali.pycfn.com/Article/details/gtjbcmiojv.html

[N09] 栈与队列
来源：http://dali.nanxinkj.top/Article/details/gttwikxkxs.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.gaohongyu789.top/Article/details/gtlyvxhiqx.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.gzhubu.top/Article/details/gtknafuqwf.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.shzxlz.cn/Article/details/gtomvozhlw.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.meibo888.top/Article/details/gtwgzdhpco.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.smart0.xyz/Article/details/gtudvuqzjc.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.nanxinkj.top/Article/details/gtkbjisbci.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.ppjwa.cn/Article/details/gtbknqlwsq.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.meibo888.top/Article/details/gtqkeuxrcq.html

[N10] 链表节点定义
来源：http://dali.ybcxt.top/Article/details/gtcjocmysa.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.xziqi.cn/Article/details/gtihseftuw.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.jiagoushi.top/Article/details/gtqxycctwp.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.ehwqpu.com/Article/details/gtfsifkodw.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.tanke756.top/Article/details/gtcmtsdacu.html

Java: class Node { int v; Node next; }
来源：http://dali.zhongyouzk.top/Article/details/gtlhviaczy.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.yonumen.top/Article/details/gtsvkpandw.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqmblkbqe.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.iojbl.cn/Article/details/gtaodwkles.html

[N11] 二叉树中序遍历
来源：http://dali.tanke756.top/Article/details/gtkknjbmdl.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.yonumen.top/Article/details/gtoohcvbab.html

PHP:  // 手写递归函数
来源：http://dali.xziqi.cn/Article/details/gtocsradhp.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.sweek.top/Article/details/gtconowkbk.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jlsjyb.cn/Article/details/gtzrkgtedk.html

Java: // 手写递归
来源：http://dali.cqqwz.cn/Article/details/gtupourbrh.html

Go:   // 手写递归
来源：http://dali.9152youxi.cn/Article/details/gttfyhzwbt.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.sysykeji.top/Article/details/gtusodytvs.html

C#:   // 手写递归
来源：http://dali.sxryk.cn/Article/details/gtbwyinxzb.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.gaohongyu789.top/Article/details/gtvdmefvns.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.havefunace.top/Article/details/gtxrrfcjbo.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.pycfn.com/Article/details/gtjqyahffn.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zycfv.cn/Article/details/gtahixqxgi.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.gzhubu.top/Article/details/gtcvfyhwiq.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhengqikj.top/Article/details/gtlmimhfjb.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.tanke756.top/Article/details/gtfpqfqlgx.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkpeegrja.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jqgfzy.top/Article/details/gtcsgcwlon.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtkusvnvaw.html

O. 并发与异步
来源：http://dali.iojbl.cn/Article/details/gtxfuigpak.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtfqjtweco.html

[O01] 启动一个线程
来源：http://dali.jinqigfzy.top/Article/details/gtjgzyxcgz.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.cdnleiting.top/Article/details/gtiqyvhlqm.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.yonumen.top/Article/details/gtaokwpxvm.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.jqgfzy.top/Article/details/gtsoxazokd.html

TS:   // 同 JS
来源：http://dali.kuanghao11.cn/Article/details/gtvsufsugq.html

Java: new Thread(() -> f()).start()
来源：http://dali.tanke756.top/Article/details/gtmjfldftg.html

Go:   go f()
来源：http://dali.yonumen.top/Article/details/gtkroevklj.html

Ruby: Thread.new { f }
来源：http://dali.cashguo.top/Article/details/gtraejtqiw.html

C#:   Task.Run(() => F());
来源：http://dali.vqdsnc.cn/Article/details/gtegkctmms.html

[O02] 使用线程池
来源：http://dali.zhixingplan.top/Article/details/gtmmmgeuxd.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.hnxiangtu.top/Article/details/gtthccnhbq.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.xylfe.cn/Article/details/gtsrntafwu.html

JS:   // worker_threads 线程池
来源：http://dali.ppjwa.cn/Article/details/gtypzldpsg.html

TS:   // worker_threads 线程池
来源：http://dali.cucudq.cn/Article/details/gtdenzqduk.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.316326.xyz/Article/details/gtpydgtgrw.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.tanke756.top/Article/details/gtqsylewji.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.jqgufenzy.top/Article/details/gtoaekztlb.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zdqjudy.top/Article/details/gtzfedbzrh.html

[O03] 加锁保护共享数据
来源：http://dali.guannengcc.top/Article/details/gthcxbiegi.html

Py:   with lock: shared += 1
来源：http://dali.chenzaomai.com/Article/details/gtxkwiuyjb.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.feifeiyinyue.top/Article/details/gtqvvdhnfl.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuvjkvxox.html

TS:   // 同 JS
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcqpxynmy.html

Java: synchronized (this) { shared++; }
来源：http://dali.yangfankeji.com/Article/details/gtygxwgcsr.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.jqgfzy.top/Article/details/gtzgcfbbys.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhoulong.xyz/Article/details/gtwtxiiwko.html

C#:   lock (gate) { shared++; }
来源：http://dali.quarkkingdee.top/Article/details/gtoiuutkvz.html

[O04] 定义异步函数并等待
来源：http://dali.0kj1m.cn/Article/details/gtjnnsxeir.html

Py:   async def f():⏎    await g()
来源：http://dali.xuetiantiany.cn/Article/details/gtbfvswszs.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.yangfankeji.com/Article/details/gtjdbaiaff.html

JS:   async function f() { await g(); }
来源：http://dali.guowangkeji.top/Article/details/gtlroiwswg.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.gzhubu.top/Article/details/gtcpjvpcdy.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.ppjwa.cn/Article/details/gtxqtixazd.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.quarkkingdee.top/Article/details/gttjazkjwv.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.yj20258.top/Article/details/gtusddiifk.html

C#:   async Task F() { await G(); }
来源：http://dali.xuanzx.com/Article/details/gthxpcqctk.html

[O05] 并发执行并等待全部完成
来源：http://dali.chenjidiqi.icu/Article/details/gtqqvhjyvg.html

Py:   asyncio.gather(*tasks)
来源：http://dali.cqqwz.cn/Article/details/gtethsrszk.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.shzxlz.cn/Article/details/gtbmtawmqn.html

JS:   await Promise.all(tasks)
来源：http://dali.mhx1999.top/Article/details/gtqzfcsyao.html

TS:   await Promise.all(tasks)
来源：http://dali.jqgufenzy.top/Article/details/gtwkvcmcse.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.ehwqpu.com/Article/details/gtxxlmelst.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.xziqi.cn/Article/details/gtljahvynx.html

Ruby: threads.map(&:join)
来源：http://dali.cheryme.top/Article/details/gtcwkomvhp.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.hfpthk.cn/Article/details/gtiymzzisy.html

[O06] 使用进程池
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnvypfbiu.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.ehwqpu.com/Article/details/gtdvlshuek.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.chenzaomai.com/Article/details/gtmgxrnfnb.html

JS:   // child_process / cluster 模块
来源：http://dali.hammf.cn/Article/details/gtmywjggdd.html

TS:   // child_process / cluster 模块
来源：http://dali.gzhubu.top/Article/details/gtyjuhwvre.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgebcwuko.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.iojbl.cn/Article/details/gtadfcpelz.html

Ruby: // fork 块
来源：http://dali.birdmap.top/Article/details/gtvkjnwyxh.html

C#:   Parallel.For
来源：http://dali.gzhubu.top/Article/details/gtofrkqquf.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtotfylhlq.html

P. 常用工具函数
来源：http://dali.tianlin.xyz/Article/details/gtetjvtmbz.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtpqasftai.html

[P01] 生成 UUID
来源：http://dali.wangshuangyany.cn/Article/details/gtopootmvs.html

Py:   str(uuid.uuid4())
来源：http://dali.vqdsnc.cn/Article/details/gtldxnzbai.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.gaohongyu789.top/Article/details/gtkzilffod.html

JS:   crypto.randomUUID()
来源：http://dali.hnqzz.top/Article/details/gtboyoqxsl.html

TS:   crypto.randomUUID()
来源：http://dali.jinqigfzy.top/Article/details/gtzsbrvoyn.html

Java: UUID.randomUUID().toString()
来源：http://dali.hywenlv.cn/Article/details/gtmxxhjbcm.html

Go:   // 用 github.com/google/uuid
来源：http://dali.chenlongwang.top/Article/details/gtgdiuavts.html

Ruby: SecureRandom.uuid
来源：http://dali.cucudq.cn/Article/details/gtcujaenww.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhengqikj.top/Article/details/gtfgwkmoji.html

[P02] MD5 / SHA256 摘要
来源：http://dali.yj20258888.top/Article/details/gtmbrrbisa.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.shanyushiyangtech.top/Article/details/gtlkzwizan.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.ppjwa.cn/Article/details/gtxpwqpurw.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.jiagoushi.top/Article/details/gteifeaktv.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.yj20258.top/Article/details/gtqnkqvmbe.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.xziqi.cn/Article/details/gtxmcmqtxx.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.nanxinkj.top/Article/details/gthlipenrh.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhixingplan.top/Article/details/gtbeifdeig.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.hysaishi.cn/Article/details/gthnvqcvwg.html

[P03] 生成短随机字符串
来源：http://dali.yj20258.top/Article/details/gtjplxblfe.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.fzhhl.top/Article/details/gtfhjzgxeo.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.jiagoushi.top/Article/details/gtpcmxgbwl.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.guowangkeji.top/Article/details/gtehngrvpb.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.feifeiyinyue.top/Article/details/gtndloawlf.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.chenlongwang.top/Article/details/gtasuwlapr.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.iojbl.cn/Article/details/gtoezhlayb.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.jiagoushi.top/Article/details/gtssywcmmm.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiutjkbfd.html

[P04] 求长度
来源：http://dali.cdnleiting.top/Article/details/gtmhtuezuc.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.yonumen.top/Article/details/gtjhzqbfpl.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jianghu66.top/Article/details/gtpmeeeliy.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.gzhubu.top/Article/details/gtmeasjzuq.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gtjjjcytys.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gtbjeudiof.html

Go:   len(arr);  len(m)
来源：http://dali.nanxinkj.top/Article/details/gtsorfwtik.html

Ruby: x.length;  x.size
来源：http://dali.yangfankeji.com/Article/details/gtowiynkli.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.sxryk.cn/Article/details/gtcdwsspeg.html

[P05] 判断两个对象内容是否相等
来源：http://dali.yuanzhike.top/Article/details/gtqtiqfoht.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.guowangkeji.top/Article/details/gtoxcdzylh.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gthcyrkesc.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.fengsongda.top/Article/details/gtluxymncl.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.hywenlv.cn/Article/details/gtwkiiakqf.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.ydzc1.top/Article/details/gtlajxhvjl.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.jqgfzy.top/Article/details/gttrptvpxa.html

Ruby: a == b
来源：http://dali.shzxlz.cn/Article/details/gtvqyeuqyt.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.jinqigufen.top/Article/details/gtdehccyhj.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.pengpengdd.cyou/Article/details/gteghgumpx.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.tanke756.top/Article/details/gtnlkkjqvn.html

PHP:  if (empty($x)) {}
来源：http://dali.ehwqpu.com/Article/details/gtuhfamhhr.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.kuanghao11.cn/Article/details/gtbeutgqnv.html

TS:   if (x == null) {}
来源：http://dali.yj20258.top/Article/details/gtbarmuaao.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.redwolf501.top/Article/details/gtnqcgozht.html

Go:   if x == nil {}
来源：http://dali.gogol.net.cn/Article/details/gtrxougepd.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.jinghuilouyu.cn/Article/details/gthupiuaob.html

C#:   if (x is null) {}
来源：http://dali.chenzaomai.com/Article/details/gtoqnuolzp.html

[P07] 防抖与节流
来源：http://dali.sxryk.cn/Article/details/gtrdesshoo.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.guowangkeji.top/Article/details/gtfjaojvki.html

PHP:  // 手写时间戳比较
来源：http://dali.nwbrower.top/Article/details/gtnakaljgp.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.guannengcc.top/Article/details/gtenvknasx.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.fengsongda.top/Article/details/gtdonxzero.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.hysaishi.cn/Article/details/gthaxntsed.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.aizwys.cn/Article/details/gtnykphqpq.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.hysaishi.cn/Article/details/gticmqwvcp.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.fengsongda.top/Article/details/gtkjeorkxk.html

[P08] 处理浮点精度问题
来源：http://dali.xziqi.cn/Article/details/gtjuocjrfu.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.jyoumei.cn/Article/details/gtxcyptnzc.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.cashguo.top/Article/details/gtuyopoxob.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.aibaodan.cn/Article/details/gtqlwvyqxp.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.cqqwz.cn/Article/details/gtgrjychks.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.chenlongwang.top/Article/details/gtxnldpewy.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.aizwys.cn/Article/details/gtmbayvvkz.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.havefunace.top/Article/details/gtofinftvx.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.wangdashe.top/Article/details/gtgyklshse.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtuaeoxqul.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.xziqi.cn/Article/details/gttbimcrqq.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbokckjtu.html

[Q01] 创建表
来源：http://dali.yanxiufei.cn/Article/details/gtbubzsmgf.html

CREATE TABLE users (
来源：http://dali.yonumen.top/Article/details/gtzeebcjoc.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.gotoacloud.top/Article/details/gtbgfzwvwa.html

name VARCHAR(50) NOT NULL,
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlntmkzto.html

email VARCHAR(100) UNIQUE,
来源：http://dali.nanxinkj.top/Article/details/gtxmfcewdv.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.yj20258.top/Article/details/gtzlgcfabg.html

);
来源：http://dali.yanxiufei.cn/Article/details/gtakawjpfl.html

[Q02] 创建带外键的表
来源：http://dali.vqdsnc.cn/Article/details/gtneofrjhr.html

CREATE TABLE orders (
来源：http://dali.meibo888.top/Article/details/gtjcdtclpb.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.meibo888.top/Article/details/gtshnwdvmb.html

user_id INT NOT NULL,
来源：http://dali.nwbrower.top/Article/details/gtcrwftpnl.html

amount DECIMAL(10, 2),
来源：http://dali.feifeiyinyue.top/Article/details/gtxckpvnjm.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.birdmap.top/Article/details/gtfmybahqq.html

);
来源：http://dali.zhixingplan.top/Article/details/gtkzcraakw.html

[Q03] 增加列
来源：http://dali.yongpay.top/Article/details/gtsypmglzl.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.nanxinkj.top/Article/details/gtzcvciqie.html

[Q04] 修改列类型
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkufhoupu.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.smart0.xyz/Article/details/gtpniednkv.html

[Q05] 重命名列
来源：http://dali.dashuyun.cn/Article/details/gtdjyejufy.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.316326.xyz/Article/details/gtvappbhmu.html

[Q06] 删除列
来源：http://dali.chenjidiqi.icu/Article/details/gtvhzfsynf.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zdqjudy.top/Article/details/gtxnaqtnod.html

[Q07] 删除表
来源：http://dali.meibo888.top/Article/details/gtmjmofygc.html

DROP TABLE IF EXISTS orders;
来源：http://dali.gzhubu.top/Article/details/gtcgqtidsd.html

[Q08] 创建普通索引
来源：http://dali.smart0.xyz/Article/details/gtmremfsbn.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.jinghuilouyu.cn/Article/details/gtrfqqjbeg.html

[Q09] 创建唯一索引
来源：http://dali.yanxiufei.cn/Article/details/gtliumveml.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.dashuyun.cn/Article/details/gtnqqxdwhp.html

[Q10] 插入单行
来源：http://dali.xziqi.cn/Article/details/gturzmvkgq.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.wangshuangyany.cn/Article/details/gtvhdwmpdz.html

[Q11] 一次插入多行
来源：http://dali.xuanzx.com/Article/details/gtpdehddlt.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhoulong.xyz/Article/details/gttvtkxnrq.html

[Q12] 插入后取自增 ID
来源：http://dali.xuetiantiany.cn/Article/details/gtzargonwi.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.9152youxi.cn/Article/details/gtlbwxqujk.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.jinqigufen.top/Article/details/gtavbrknpr.html

[Q13] 忽略重复插入
来源：http://dali.zhaomingkeji.xyz/Article/details/gthitflyab.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.ppjwa.cn/Article/details/gtjotkvqnw.html

[Q14] 存在则更新（upsert）
来源：http://dali.gogol.net.cn/Article/details/gtqmgndxmi.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.gotoacloud.top/Article/details/gtbmmfgxjp.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtphqcefnr.html

[Q15] 查询全部
来源：http://dali.guowangkeji.top/Article/details/gtgccaxdmh.html

SELECT * FROM users;
来源：http://dali.hnqzz.top/Article/details/gtnbhunksm.html

[Q16] 查询指定列
来源：http://dali.jianghu66.top/Article/details/gtrhwjatgr.html

SELECT id, name FROM users;
来源：http://dali.wangdashe.top/Article/details/gtqfoydzis.html

[Q17] 条件查询
来源：http://dali.hongshengwenyu.top/Article/details/gtgvcioaos.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.jinyuanbaomall.cn/Article/details/gteetnoiwd.html

[Q18] 模糊匹配
来源：http://dali.chenzaomai.com/Article/details/gtxwdsqcdj.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.sweek.top/Article/details/gtlyboolww.html

[Q19] 范围查询
来源：http://dali.smart0.xyz/Article/details/gtchiocdsh.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.kuanghao11.cn/Article/details/gtgsgmmcya.html

[Q20] IN 列表
来源：http://dali.sysykeji.top/Article/details/gtcqkjyobc.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.sufxvd.cn/Article/details/gtjunzluld.html

[Q21] 空值判断
来源：http://dali.snrcjt.cn/Article/details/gtokfavyni.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.yangfankeji.com/Article/details/gtxgotmzkw.html

[Q22] 排序
来源：http://dali.cdnleiting.top/Article/details/gtqcporwfn.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.feifeiyinyue.top/Article/details/gtsuffclwj.html

[Q23] 分页
来源：http://dali.meibo888.top/Article/details/gtxcfyvpii.html


<!-- 参考信息 -->