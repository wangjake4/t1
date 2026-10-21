代发 wailian999

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbuhqurfx.html

Ruby: warn "err"
来源：http://dali.9152youxi.cn/Article/details/gtqhsroiez.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.jinqigfzy.top/Article/details/gtvauxwxxl.html

[M07] 判断是否为主入口
来源：http://dali.yvedp.cn/Article/details/gtyqoxxbed.html

Py:   if __name__ == "__main__":
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrufqjjuf.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.pycfn.com/Article/details/gththrbwtu.html

JS:   require.main === module
来源：http://dali.feifeiyinyue.top/Article/details/gtcwblwoul.html

TS:   require.main === module
来源：http://dali.hnxiangtu.top/Article/details/gtowlkevmy.html

Java: public static void main(String[] args)
来源：http://dali.zycfv.cn/Article/details/gtbgvssgho.html

Go:   func main()
来源：http://dali.zhongyouzk.top/Article/details/gtofirbucu.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.kuanghao11.cn/Article/details/gtorpyulgd.html

C#:   static void Main(string[] args)
来源：http://dali.guowangkeji.top/Article/details/gtnoymsfuf.html

[M08] 获取系统与运行时信息
来源：http://dali.yueranfly.top/Article/details/gtzxoqqkau.html

Py:   platform.system();  platform.python_version()
来源：http://dali.c1oappe.top/Article/details/gtklsmhemi.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.nwbrower.top/Article/details/gtflaxctqe.html

JS:   process.platform;  process.version
来源：http://dali.gotoacloud.top/Article/details/gtozthvoqb.html

TS:   process.platform;  process.version
来源：http://dali.nwbrower.top/Article/details/gtjcrqisxo.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.ehwqpu.com/Article/details/gtdogdozde.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.nanxinkj.top/Article/details/gtxvjzhzkq.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.gogol.net.cn/Article/details/gtekadgajm.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zdqjudy.top/Article/details/gtqipeiapl.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gteijlxrez.html

N. 数据结构与算法
来源：http://dali.sxryk.cn/Article/details/gtnrgkzndq.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtibstewss.html

[N01] 二分查找（有序数组）
来源：http://dali.zdqjudy.top/Article/details/gtxftxrvpn.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.wangshuangyany.cn/Article/details/gtnzjrpzey.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.fengsongda.top/Article/details/gtdknfgofe.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.tian-w.cn/Article/details/gtlhoemcut.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.redwolf501.top/Article/details/gtbxptejrs.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.shzxlz.cn/Article/details/gtbeosgbck.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.guannengcc.top/Article/details/gtiklrmppn.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gtzokunxpp.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.snrcjt.cn/Article/details/gtddbwguuf.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.jinghuilouyu.cn/Article/details/gtsutfjjof.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.daxiang520.top/Article/details/gtjorlyrvh.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.hfpthk.cn/Article/details/gtqlvvzbqm.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.chenzaomai.com/Article/details/gtkvultyba.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jinghuilouyu.cn/Article/details/gtveqxtzkd.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.shzxlz.cn/Article/details/gtzmzkljiv.html

Go:   slices.Sort(arr)
来源：http://dali.nanxuanxn.top/Article/details/gtqknriadw.html

Ruby: arr.sort
来源：http://dali.havefunace.top/Article/details/gtobryrjeb.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.xuanzx.com/Article/details/gtpuvntzas.html

[N03] 快速排序（分治示例）
来源：http://dali.kuanghao11.cn/Article/details/gtireqtdoc.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.hnqzz.top/Article/details/gtzwovuppa.html

PHP:  // 递归实现，或用 usort
来源：http://dali.aibaodan.cn/Article/details/gttjycrjcb.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmzqeykye.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.nanxinkj.top/Article/details/gtovgmqizl.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.jinghuilouyu.cn/Article/details/gthwteemdw.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.havefunace.top/Article/details/gtjmdnxrdo.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.chenlongwang.top/Article/details/gtolnfqzia.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.hfpthk.cn/Article/details/gtbklpcnhv.html

[N04] 斐波那契数列
来源：http://dali.yj20258888.top/Article/details/gtfnyvwdgs.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.ehwqpu.com/Article/details/gtdiuelzbs.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.birdmap.top/Article/details/gtmtvilnci.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.shuidangran.top/Article/details/gtvoaemwlo.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jqgfzy.top/Article/details/gtqvrkxcks.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.jyoumei.cn/Article/details/gtwrfvegci.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.9152youxi.cn/Article/details/gtenzlmrwh.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.gaohongyu789.top/Article/details/gtrjiyyyxo.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.aizwys.cn/Article/details/gttjctbgcv.html

[N05] 最大公约数
来源：http://dali.jqgufenzy.top/Article/details/gtkeeibcft.html

Py:   math.gcd(a, b)
来源：http://dali.316326.xyz/Article/details/gtfzbtfxcr.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.haohaochexian.top/Article/details/gtvegaqlmm.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yueranfly.top/Article/details/gtvptndfzf.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.xuanzx.com/Article/details/gtcmmvtwhd.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.guowangkeji.top/Article/details/gtovyemlug.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.wangdashe.top/Article/details/gtpepoowlr.html

Ruby: a.gcd(b)
来源：http://dali.gzhubu.top/Article/details/gtemxijcfo.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.svipenyu.cn/Article/details/gtbyloxysi.html

[N06] 判断回文字符串
来源：http://dali.cashguo.top/Article/details/gtxdzmaczg.html

Py:   s == s[::-1]
来源：http://dali.jinqigufen.top/Article/details/gtscycmlhp.html

PHP:  $s === strrev($s);
来源：http://dali.316326.xyz/Article/details/gtbhihosil.html

JS:   s === [...s].reverse().join("")
来源：http://dali.sxryk.cn/Article/details/gtfpcvztey.html

TS:   s === [...s].reverse().join("")
来源：http://dali.hnqzz.top/Article/details/gtbwtvlhuy.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.dianchejie.cn/Article/details/gtchjzxiyz.html

Go:   // 双指针从两端比较
来源：http://dali.yonumen.top/Article/details/gtzmkzcebi.html

Ruby: s == s.reverse
来源：http://dali.9152youxi.cn/Article/details/gtvhvzabcb.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.daxiang520.top/Article/details/gtveqafxdu.html

[N07] 两数之和（返回下标）
来源：http://dali.tanke756.top/Article/details/gtjpbmszyz.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.mhx1999.top/Article/details/gtmkxxzonz.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.jinqigufen.top/Article/details/gtccztkjwr.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.xziqi.cn/Article/details/gtjkodkgnt.html

TS:   // 手写 Map<string, number>
来源：http://dali.xylfe.cn/Article/details/gtjtgdrlxo.html

Java: // 手写 HashMap
来源：http://dali.hywenlv.cn/Article/details/gtnzhqattb.html

Go:   // 手写 map[int]int
来源：http://dali.hnxiangtu.top/Article/details/gtqwqsxjma.html

Ruby: // 手写 Hash
来源：http://dali.dianchejie.cn/Article/details/gtgakcyhpd.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.pengpengdd.cyou/Article/details/gtkhsorrad.html

[N08] 生成全排列
来源：http://dali.chenjidiqi.icu/Article/details/gtqyhadwic.html

Py:   itertools.permutations(arr)
来源：http://dali.hfpthk.cn/Article/details/gtdkeivgcx.html

PHP:  // 手写递归交换
来源：http://dali.mhx1999.top/Article/details/gteywjczbg.html

JS:   // 手写回溯递归
来源：http://dali.gogol.net.cn/Article/details/gtoozqroqp.html

TS:   // 手写回溯递归
来源：http://dali.xylfe.cn/Article/details/gtdfyofaka.html

Java: // 手写回溯递归
来源：http://dali.mhx1999.top/Article/details/gtntcdysfk.html

Go:   // 手写回溯递归
来源：http://dali.dashuyun.cn/Article/details/gtnyykngnv.html

Ruby: arr.permutation.to_a
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdktkqdtf.html

C#:   // 手写回溯递归
来源：http://dali.yuanzhike.top/Article/details/gtzrcadepx.html

[N09] 栈与队列
来源：http://dali.cucudq.cn/Article/details/gtyoeztkxn.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.xylfe.cn/Article/details/gteuowvjpv.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhixingplan.top/Article/details/gtlvwsgkvc.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.jlsjyb.cn/Article/details/gteghebzic.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.316326.xyz/Article/details/gtgphivvyu.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhixingplan.top/Article/details/gttavgovjc.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.gogol.net.cn/Article/details/gtbutpfoja.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.yj20258.top/Article/details/gteciknwvl.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.chenlongwang.top/Article/details/gtdxpwecog.html

[N10] 链表节点定义
来源：http://dali.xziqi.cn/Article/details/gtztqgoril.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.ivvv.top/Article/details/gtncnupkyo.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.cashguo.top/Article/details/gtbpawqtgm.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.9152youxi.cn/Article/details/gtsbafwgmi.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.cqqwz.cn/Article/details/gtylzsdjjr.html

Java: class Node { int v; Node next; }
来源：http://dali.ehwqpu.com/Article/details/gtntioctbw.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.yj20258.top/Article/details/gteyxuvyfn.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.chenjidiqi.icu/Article/details/gtsvbwgjaz.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.ehwqpu.com/Article/details/gtglthptmg.html

[N11] 二叉树中序遍历
来源：http://dali.yvedp.cn/Article/details/gtenpcbzdz.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.cucudq.cn/Article/details/gtybhbxppa.html

PHP:  // 手写递归函数
来源：http://dali.tian-w.cn/Article/details/gteuvpavzm.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhongyouzk.top/Article/details/gtxxfblryy.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.nanxinkj.top/Article/details/gtrfrcdocq.html

Java: // 手写递归
来源：http://dali.yangfankeji.com/Article/details/gtdusqxmuj.html

Go:   // 手写递归
来源：http://dali.guowangkeji.top/Article/details/gtxsguuibn.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.redwolf501.top/Article/details/gtnaxswxns.html

C#:   // 手写递归
来源：http://dali.chenlongwang.top/Article/details/gtxxjnwxgp.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.yongpay.top/Article/details/gtqtrqmycl.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.pengpengdd.cyou/Article/details/gtijtwkmnm.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.hysaishi.cn/Article/details/gtriojvtcm.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yj20258.top/Article/details/gthiekuwlv.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.chenjidiqi.icu/Article/details/gtnwwwdheo.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.pengpengdd.cyou/Article/details/gtghmzukoe.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.sysykeji.top/Article/details/gtiuosnskl.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.mhx1999.top/Article/details/gteksaehmd.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.smart0.xyz/Article/details/gtedcvkkwj.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gteycnyuxr.html

O. 并发与异步
来源：http://dali.yanxiufei.cn/Article/details/gtqwxgmcuz.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtphsdvnir.html

[O01] 启动一个线程
来源：http://dali.gotoacloud.top/Article/details/gtyxxieubn.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.andypj.xyz/Article/details/gtdilhclbr.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.cucudq.cn/Article/details/gttzwdgdgk.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.chenjidiqi.icu/Article/details/gtcipndxdq.html

TS:   // 同 JS
来源：http://dali.ppjwa.cn/Article/details/gtqyghwckn.html

Java: new Thread(() -> f()).start()
来源：http://dali.gogol.net.cn/Article/details/gtwpriybtx.html

Go:   go f()
来源：http://dali.redwolf501.top/Article/details/gtalfvlxph.html

Ruby: Thread.new { f }
来源：http://dali.hammf.cn/Article/details/gtitvrwbtg.html

C#:   Task.Run(() => F());
来源：http://dali.yueranfly.top/Article/details/gtrlzmyzpc.html

[O02] 使用线程池
来源：http://dali.ydzc1.top/Article/details/gtqfzbgopp.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.tian-w.cn/Article/details/gtdkblxkcs.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.cdnleiting.top/Article/details/gtpcppirnw.html

JS:   // worker_threads 线程池
来源：http://dali.shuidangran.top/Article/details/gtmelliipf.html

TS:   // worker_threads 线程池
来源：http://dali.chenlongwang.top/Article/details/gtlkilrzen.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.c1oappe.top/Article/details/gttoggqbdv.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.meibo888.top/Article/details/gtyvfdhbpx.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhixingplan.top/Article/details/gtqkomfdol.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.havefunace.top/Article/details/gtlsnlnspg.html

[O03] 加锁保护共享数据
来源：http://dali.pycfn.com/Article/details/gtgdrydzgx.html

Py:   with lock: shared += 1
来源：http://dali.zycfv.cn/Article/details/gtcizsrreo.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.ivvv.top/Article/details/gtnwproswf.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.iojbl.cn/Article/details/gtwarxrxwh.html

TS:   // 同 JS
来源：http://dali.tanke756.top/Article/details/gtfdalbsfy.html

Java: synchronized (this) { shared++; }
来源：http://dali.daria6918.cn/Article/details/gtnaorqapl.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.meibo888.top/Article/details/gtttcadpjg.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.jqgufenzy.top/Article/details/gtzpvoqlvv.html

C#:   lock (gate) { shared++; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtetsvgeqf.html

[O04] 定义异步函数并等待
来源：http://dali.wangdashe.top/Article/details/gtxacwhuev.html

Py:   async def f():⏎    await g()
来源：http://dali.xziqi.cn/Article/details/gtyfymloml.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.birdmap.top/Article/details/gtfltjhrgs.html

JS:   async function f() { await g(); }
来源：http://dali.daxiang520.top/Article/details/gtavducern.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.xinyue.icu/Article/details/gtfoixhibz.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.nanxuanxn.top/Article/details/gtipirnrxh.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.jiagoushi.top/Article/details/gthcskfokf.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.yongpay.top/Article/details/gtppkzvcgl.html

C#:   async Task F() { await G(); }
来源：http://dali.xuanzx.com/Article/details/gtkgsskkqg.html

[O05] 并发执行并等待全部完成
来源：http://dali.nwbrower.top/Article/details/gtplrtgvpt.html

Py:   asyncio.gather(*tasks)
来源：http://dali.chenjidiqi.icu/Article/details/gttqimivpb.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.iojbl.cn/Article/details/gtsmicghbd.html

JS:   await Promise.all(tasks)
来源：http://dali.ivvv.top/Article/details/gteeynakde.html

TS:   await Promise.all(tasks)
来源：http://dali.zycfv.cn/Article/details/gtlvxnfkdu.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.pycfn.com/Article/details/gtkeplbabm.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.wangdashe.top/Article/details/gttijmmtud.html

Ruby: threads.map(&:join)
来源：http://dali.aibaodan.cn/Article/details/gttfwuyrnh.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.aibaodan.cn/Article/details/gteycvgnpq.html

[O06] 使用进程池
来源：http://dali.meibo888.top/Article/details/gtvaxqkrib.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthixqderl.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.chenzaomai.com/Article/details/gtihvyjaxo.html

JS:   // child_process / cluster 模块
来源：http://dali.sweek.top/Article/details/gtjglfwvwn.html

TS:   // child_process / cluster 模块
来源：http://dali.yj20258.top/Article/details/gttyuuknhz.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.ywan-chungtsiang.top/Article/details/gtccfdyabf.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.shangyingyoupin.top/Article/details/gtxugnztqj.html

Ruby: // fork 块
来源：http://dali.zhongyouzk.top/Article/details/gtuzjtscuz.html

C#:   Parallel.For
来源：http://dali.gogol.net.cn/Article/details/gtcreefvmg.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtknswmtyc.html

P. 常用工具函数
来源：http://dali.c1oappe.top/Article/details/gtiefgqqwv.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtskackkox.html

[P01] 生成 UUID
来源：http://dali.0kj1m.cn/Article/details/gtxkcxacpg.html

Py:   str(uuid.uuid4())
来源：http://dali.gaohongyu789.top/Article/details/gtrdebttsf.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.chenjidiqi.icu/Article/details/gtgumxogwj.html

JS:   crypto.randomUUID()
来源：http://dali.yj202588.top/Article/details/gtrtvzmsjt.html

TS:   crypto.randomUUID()
来源：http://dali.jlsjyb.cn/Article/details/gtylsbpdag.html

Java: UUID.randomUUID().toString()
来源：http://dali.hnxiangtu.top/Article/details/gtowxwxrfu.html

Go:   // 用 github.com/google/uuid
来源：http://dali.jinqigufen.top/Article/details/gtyzobnmul.html

Ruby: SecureRandom.uuid
来源：http://dali.yj20258888.top/Article/details/gthrvpszdm.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.hysaishi.cn/Article/details/gtcayzvcdg.html

[P02] MD5 / SHA256 摘要
来源：http://dali.tanke756.top/Article/details/gtbchlzjju.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.chenjidiqi.icu/Article/details/gttguqmgad.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.yuanzhike.top/Article/details/gtnipddfzy.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.meibo888.top/Article/details/gtlxzumhnz.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.sweek.top/Article/details/gtkbcasyss.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.xinyue.icu/Article/details/gtbfbrtodh.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.cucudq.cn/Article/details/gtfxcrnjsq.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.guowangkeji.top/Article/details/gtsnqlsuuy.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.yvedp.cn/Article/details/gtybxswpyw.html

[P03] 生成短随机字符串
来源：http://dali.ybcxt.top/Article/details/gtkthyewqh.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhoulong.xyz/Article/details/gtndsgxrit.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.tanke756.top/Article/details/gterfwuhkv.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.nwbrower.top/Article/details/gtebwvnvlm.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.havefunace.top/Article/details/gtiiwlkvfq.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.jqgfzy.top/Article/details/gtdobgjcua.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.cucudq.cn/Article/details/gtljmsylpx.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.fzhhl.top/Article/details/gtnbhbpnjr.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.fzhhl.top/Article/details/gtzjwqgjdx.html

[P04] 求长度
来源：http://dali.xylfe.cn/Article/details/gtpobwfvst.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhixingplan.top/Article/details/gttgrdoytk.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yuxming.cn/Article/details/gtozggzumu.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.cheryme.top/Article/details/gtiklhdjff.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.guowangkeji.top/Article/details/gtmupkxbuh.html

Java: list.size();  map.size();  s.length()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbggbvqbu.html

Go:   len(arr);  len(m)
来源：http://dali.ybcxt.top/Article/details/gttrunxmqb.html

Ruby: x.length;  x.size
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwhdbasal.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.yongpay.top/Article/details/gttoyajcle.html

[P05] 判断两个对象内容是否相等
来源：http://dali.shanyushiyangtech.top/Article/details/gtcahjemru.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.jqgufenzy.top/Article/details/gtxfvxacbt.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.ybcxt.top/Article/details/gtitqadsof.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxsonykyu.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.gotoacloud.top/Article/details/gtieqjyfkv.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.hongshengwenyu.top/Article/details/gtstrfxruf.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhixingplan.top/Article/details/gtveconapw.html

Ruby: a == b
来源：http://dali.ybcxt.top/Article/details/gtqtwjxokq.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.haohaochexian.top/Article/details/gtgowvvrpp.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.pengpengdd.cyou/Article/details/gtdvcxjadq.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.tanke756.top/Article/details/gthqebmhvm.html

PHP:  if (empty($x)) {}
来源：http://dali.gaohongyu789.top/Article/details/gtguzqkumz.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.vqdsnc.cn/Article/details/gtvjibwknv.html

TS:   if (x == null) {}
来源：http://dali.yonumen.top/Article/details/gtfgaxrakn.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.hammf.cn/Article/details/gtuozaknzu.html

Go:   if x == nil {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqcbqgcmf.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.iojbl.cn/Article/details/gtxjvjzeyc.html

C#:   if (x is null) {}
来源：http://dali.daxiang520.top/Article/details/gtmgtrdqop.html

[P07] 防抖与节流
来源：http://dali.daria6918.cn/Article/details/gtmervdmtt.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.sxryk.cn/Article/details/gtnjuocpgv.html

PHP:  // 手写时间戳比较
来源：http://dali.ppjwa.cn/Article/details/gtirkmirha.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hnxiangtu.top/Article/details/gtlluozdmg.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.xylfe.cn/Article/details/gtbhiubjmo.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtgcumseqv.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.tanke756.top/Article/details/gtelmfptkn.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.tanke756.top/Article/details/gtstglspwa.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.gotoacloud.top/Article/details/gtrfkzdgcd.html

[P08] 处理浮点精度问题
来源：http://dali.bjfxy.top/Article/details/gtdoijunsg.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.jyoumei.cn/Article/details/gtzdxferjq.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.jqgufenzy.top/Article/details/gtquvrzuiv.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.gogol.net.cn/Article/details/gtfcsdzavi.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.aibaodan.cn/Article/details/gtevejvvrp.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.xuetiantiany.cn/Article/details/gtnffejlwn.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.guowangkeji.top/Article/details/gtmdslmzes.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.hfpthk.cn/Article/details/gtlstxfyih.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.tian-w.cn/Article/details/gtxetbjugf.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtpcsnlsav.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.yanxiufei.cn/Article/details/gtooirziqg.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtofcttboo.html

[Q01] 创建表
来源：http://dali.jyoumei.cn/Article/details/gtwvogajsi.html

CREATE TABLE users (
来源：http://dali.jinqigfzy.top/Article/details/gtlwsddhvt.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.guowangkeji.top/Article/details/gtircfwdnu.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zycfv.cn/Article/details/gtqqnjsqxo.html

email VARCHAR(100) UNIQUE,
来源：http://dali.snrcjt.cn/Article/details/gtckpazoxg.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.jianghu66.top/Article/details/gtjmyngmrb.html

);
来源：http://dali.andypj.xyz/Article/details/gtpgsmyoec.html

[Q02] 创建带外键的表
来源：http://dali.sxryk.cn/Article/details/gtardcwyzu.html

CREATE TABLE orders (
来源：http://dali.jinghuilouyu.cn/Article/details/gtbhhwthkf.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.kuanghao11.cn/Article/details/gtbesboznx.html

user_id INT NOT NULL,
来源：http://dali.xziqi.cn/Article/details/gtutanwmlb.html

amount DECIMAL(10, 2),
来源：http://dali.guannengcc.top/Article/details/gtfmfrccpp.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.c1oappe.top/Article/details/gtqbbssili.html

);
来源：http://dali.jinqigfzy.top/Article/details/gtvfjwlpqi.html

[Q03] 增加列
来源：http://dali.yanxiufei.cn/Article/details/gtdolqldzu.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhiwuduotai.top/Article/details/gtrkofgvyu.html

[Q04] 修改列类型
来源：http://dali.jlsjyb.cn/Article/details/gteayxorep.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gtzpollsoz.html

[Q05] 重命名列
来源：http://dali.gotoacloud.top/Article/details/gtjfvfajef.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.c1oappe.top/Article/details/gtlboogtaa.html

[Q06] 删除列
来源：http://dali.jinyuanbaomall.cn/Article/details/gthmkfmkeh.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.snrcjt.cn/Article/details/gtiowzephs.html

[Q07] 删除表
来源：http://dali.xuanzx.com/Article/details/gtnmcyopst.html

DROP TABLE IF EXISTS orders;
来源：http://dali.haohaochexian.top/Article/details/gtucsepnmb.html

[Q08] 创建普通索引
来源：http://dali.hywenlv.cn/Article/details/gtzpinwivb.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.snrcjt.cn/Article/details/gtuhveqekp.html

[Q09] 创建唯一索引
来源：http://dali.haohaochexian.top/Article/details/gtsfcpkquv.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.316326.xyz/Article/details/gthscpfilt.html

[Q10] 插入单行
来源：http://dali.jianghu66.top/Article/details/gtvghyhygz.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.yvedp.cn/Article/details/gtnzgnfyxa.html

[Q11] 一次插入多行
来源：http://dali.nanxuanxn.top/Article/details/gtyctersag.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.gaohongyu789.top/Article/details/gtmmqhjzkk.html

[Q12] 插入后取自增 ID
来源：http://dali.nanxinkj.top/Article/details/gtdktmbcsu.html


<!-- 参考信息 -->