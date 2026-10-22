代发 wailian999

Py:   if __name__ == "__main__":
来源：http://dali.9152youxi.cn/Article/details/gtoajgsrmy.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhoulong.xyz/Article/details/gtddfbwglh.html

JS:   require.main === module
来源：http://dali.aibaodan.cn/Article/details/gteboxntpb.html

TS:   require.main === module
来源：http://dali.daria6918.cn/Article/details/gtkirdzqte.html

Java: public static void main(String[] args)
来源：http://dali.9152youxi.cn/Article/details/gtbjdbbgas.html

Go:   func main()
来源：http://dali.chenzaomai.com/Article/details/gtwyeowthv.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.yj20258.top/Article/details/gtmyiifjrw.html

C#:   static void Main(string[] args)
来源：http://dali.yj20258888.top/Article/details/gtkegkmvam.html

[M08] 获取系统与运行时信息
来源：http://dali.xziqi.cn/Article/details/gtdkrriuat.html

Py:   platform.system();  platform.python_version()
来源：http://dali.yongpay.top/Article/details/gtrznxndna.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.aizwys.cn/Article/details/gtqcvngrdg.html

JS:   process.platform;  process.version
来源：http://dali.guannengcc.top/Article/details/gtygqidufy.html

TS:   process.platform;  process.version
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyufsevmw.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.xziqi.cn/Article/details/gtbbtxltyu.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.hongshengwenyu.top/Article/details/gtvzonyfbm.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.ehwqpu.com/Article/details/gtyrzrvswg.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.hnqzz.top/Article/details/gtsnhoqrqr.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtkehubtpb.html

N. 数据结构与算法
来源：http://dali.hysaishi.cn/Article/details/gtacdbazjy.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgsssblce.html

[N01] 二分查找（有序数组）
来源：http://dali.shangyingyoupin.top/Article/details/gtcefjinru.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.shanyushiyangtech.top/Article/details/gtajwqjyqw.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.wangdashe.top/Article/details/gtxsapnrtg.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.chenjidiqi.icu/Article/details/gtozxrslcc.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhiwuduotai.top/Article/details/gtaovengfr.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.daria6918.cn/Article/details/gtkaxmnxxy.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.nanxuanxn.top/Article/details/gtqgbpalhk.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.shangyingyoupin.top/Article/details/gtniejadxk.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.nwbrower.top/Article/details/gtdtclhjak.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.hfpthk.cn/Article/details/gtlkhdsmdr.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.birdmap.top/Article/details/gtoszwuzwd.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuabpmqlt.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jianghu66.top/Article/details/gtpociytum.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.snrcjt.cn/Article/details/gtzozlfybg.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.jinghuilouyu.cn/Article/details/gtmjxockbx.html

Go:   slices.Sort(arr)
来源：http://dali.hnqzz.top/Article/details/gtpgoxcghn.html

Ruby: arr.sort
来源：http://dali.tian-w.cn/Article/details/gthwvplqnc.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhongyouzk.top/Article/details/gtkbiheqmz.html

[N03] 快速排序（分治示例）
来源：http://dali.hnqzz.top/Article/details/gtxyjnfjdn.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.shanyushiyangtech.top/Article/details/gtmtrwgaad.html

PHP:  // 递归实现，或用 usort
来源：http://dali.mhx1999.top/Article/details/gtalmeqivs.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.ivvv.top/Article/details/gtuttumakx.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.cucudq.cn/Article/details/gtgauxsdzg.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.hongshengwenyu.top/Article/details/gtucfmslve.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.yueranfly.top/Article/details/gtkxzfftba.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.pycfn.com/Article/details/gtfoedtdok.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.jinqigufen.top/Article/details/gtxnwljcqk.html

[N04] 斐波那契数列
来源：http://dali.jqgufenzy.top/Article/details/gtlnqbtvag.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.svipenyu.cn/Article/details/gtdaozfyas.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.hammf.cn/Article/details/gtobitveyx.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.316326.xyz/Article/details/gthqymvwmj.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.sysykeji.top/Article/details/gtzcaazoho.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.tian-w.cn/Article/details/gtdwzsmyuj.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.dashuyun.cn/Article/details/gtvoqicruj.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.hongshengwenyu.top/Article/details/gtldojjcoq.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.hammf.cn/Article/details/gtjmdqknrp.html

[N05] 最大公约数
来源：http://dali.smart0.xyz/Article/details/gtayypbvbp.html

Py:   math.gcd(a, b)
来源：http://dali.yj202588.top/Article/details/gtmswvqtkw.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.andypj.xyz/Article/details/gtbsadovvy.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.guowangkeji.top/Article/details/gthvexaaki.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.sysykeji.top/Article/details/gtctqqwchp.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.shzxlz.cn/Article/details/gtxvtmwxkz.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.svipenyu.cn/Article/details/gthnhwlzoz.html

Ruby: a.gcd(b)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnitszgcw.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.dashuyun.cn/Article/details/gtlifdueed.html

[N06] 判断回文字符串
来源：http://dali.zdqjudy.top/Article/details/gtvgqjzbsh.html

Py:   s == s[::-1]
来源：http://dali.bjfxy.top/Article/details/gtoalahuyi.html

PHP:  $s === strrev($s);
来源：http://dali.birdmap.top/Article/details/gtduqkibiv.html

JS:   s === [...s].reverse().join("")
来源：http://dali.cheryme.top/Article/details/gtqdjvqrbb.html

TS:   s === [...s].reverse().join("")
来源：http://dali.guannengcc.top/Article/details/gtgmwkjzbn.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhixingplan.top/Article/details/gtafrhpdln.html

Go:   // 双指针从两端比较
来源：http://dali.ydzc1.top/Article/details/gtalljmryp.html

Ruby: s == s.reverse
来源：http://dali.zycfv.cn/Article/details/gtevlkojnh.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.yongpay.top/Article/details/gtrpwmuzdr.html

[N07] 两数之和（返回下标）
来源：http://dali.chenzaomai.com/Article/details/gtqcuqxskg.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.9152youxi.cn/Article/details/gtncadtpjy.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.kuanghao11.cn/Article/details/gtkejkmbfk.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.feifeiyinyue.top/Article/details/gtqkkuzpab.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gtzqgsyccn.html

Java: // 手写 HashMap
来源：http://dali.smart0.xyz/Article/details/gtbecfakrj.html

Go:   // 手写 map[int]int
来源：http://dali.shanyushiyangtech.top/Article/details/gtsbvbofjg.html

Ruby: // 手写 Hash
来源：http://dali.dashuyun.cn/Article/details/gtkvhkwzyh.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnztsvfvh.html

[N08] 生成全排列
来源：http://dali.jinghuilouyu.cn/Article/details/gtgizgpkce.html

Py:   itertools.permutations(arr)
来源：http://dali.hnqzz.top/Article/details/gtfexcebwb.html

PHP:  // 手写递归交换
来源：http://dali.jinqigfzy.top/Article/details/gtxwzozmps.html

JS:   // 手写回溯递归
来源：http://dali.yueranfly.top/Article/details/gtgqsfuazb.html

TS:   // 手写回溯递归
来源：http://dali.chenjidiqi.icu/Article/details/gtbsaddlqh.html

Java: // 手写回溯递归
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjpjwiylo.html

Go:   // 手写回溯递归
来源：http://dali.xuanzx.com/Article/details/gtccngdtyw.html

Ruby: arr.permutation.to_a
来源：http://dali.snrcjt.cn/Article/details/gtmtxayamt.html

C#:   // 手写回溯递归
来源：http://dali.tian-w.cn/Article/details/gtqtayxpoe.html

[N09] 栈与队列
来源：http://dali.hongshengwenyu.top/Article/details/gtkicijdpz.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.gaohongyu789.top/Article/details/gtjnlqgefv.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.guannengcc.top/Article/details/gtlwrwwrzi.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.tianlin.xyz/Article/details/gtfscwvxxd.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.yangfankeji.com/Article/details/gtiofiailw.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.jlsjyb.cn/Article/details/gtfjkrnaij.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.ybcxt.top/Article/details/gtikjgaxge.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.kuanghao11.cn/Article/details/gtsrakobnc.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.daxiang520.top/Article/details/gttaziblge.html

[N10] 链表节点定义
来源：http://dali.0kj1m.cn/Article/details/gtiqbmghkc.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.hywenlv.cn/Article/details/gtwnkntwxu.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.meibo888.top/Article/details/gtvbuewded.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.jinqigufen.top/Article/details/gttxezoqbo.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.havefunace.top/Article/details/gtdyxqpmak.html

Java: class Node { int v; Node next; }
来源：http://dali.cdnleiting.top/Article/details/gtycmwfzsr.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.shanyushiyangtech.top/Article/details/gtjslhbuai.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.quarkkingdee.top/Article/details/gtnsbeaxef.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.jlsjyb.cn/Article/details/gtftegzpxa.html

[N11] 二叉树中序遍历
来源：http://dali.hfpthk.cn/Article/details/gthasfylxu.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.chenjidiqi.icu/Article/details/gtrboiszyy.html

PHP:  // 手写递归函数
来源：http://dali.svipenyu.cn/Article/details/gtfqpysuuk.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsvlyiwdy.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yvedp.cn/Article/details/gtiumjikxh.html

Java: // 手写递归
来源：http://dali.zhengqikj.top/Article/details/gthclmcktd.html

Go:   // 手写递归
来源：http://dali.kuanghao11.cn/Article/details/gtbrdoaibd.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.jqgufenzy.top/Article/details/gtisdtztkn.html

C#:   // 手写递归
来源：http://dali.yanxiufei.cn/Article/details/gtszbbyafm.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.cheryme.top/Article/details/gtqzdlrpsi.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.cheryme.top/Article/details/gtguqjlffw.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhengqikj.top/Article/details/gttyowshti.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.cdnleiting.top/Article/details/gthjhenaqm.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yvedp.cn/Article/details/gthsesnpgf.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhongyouzk.top/Article/details/gtwsqlywvp.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.jqgufenzy.top/Article/details/gtkkbxvioi.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.daxiang520.top/Article/details/gtnsyrocuc.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.fzhhl.top/Article/details/gtyqqrenut.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtxzzsikyj.html

O. 并发与异步
来源：http://dali.zhongyouzk.top/Article/details/gtnvgnlinl.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtjobkmbst.html

[O01] 启动一个线程
来源：http://dali.xziqi.cn/Article/details/gtiiwqcdjk.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.redwolf501.top/Article/details/gtsstlifxr.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.yj20258.top/Article/details/gtlxfidkai.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.guannengcc.top/Article/details/gttrwiazgq.html

TS:   // 同 JS
来源：http://dali.pengpengdd.cyou/Article/details/gttrquttev.html

Java: new Thread(() -> f()).start()
来源：http://dali.redwolf501.top/Article/details/gtfnvdwuqv.html

Go:   go f()
来源：http://dali.dashuyun.cn/Article/details/gtkfravcqx.html

Ruby: Thread.new { f }
来源：http://dali.yj20258888.top/Article/details/gtupsidxul.html

C#:   Task.Run(() => F());
来源：http://dali.shuidangran.top/Article/details/gtbtybbhlk.html

[O02] 使用线程池
来源：http://dali.havefunace.top/Article/details/gtbecwkira.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhoulong.xyz/Article/details/gtvghcobdn.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.gotoacloud.top/Article/details/gtnmiqlofe.html

JS:   // worker_threads 线程池
来源：http://dali.redwolf501.top/Article/details/gtvlsolsis.html

TS:   // worker_threads 线程池
来源：http://dali.0kj1m.cn/Article/details/gtysgivgdl.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.hnxiangtu.top/Article/details/gtfattjyhg.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.hongshengwenyu.top/Article/details/gthylozxig.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.shzxlz.cn/Article/details/gtoemynflr.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.tian-w.cn/Article/details/gtollhcsfk.html

[O03] 加锁保护共享数据
来源：http://dali.yuanzhike.top/Article/details/gtbghliogr.html

Py:   with lock: shared += 1
来源：http://dali.zhongyouzk.top/Article/details/gteanuilye.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.bjfxy.top/Article/details/gtqlwzhzvl.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.9152youxi.cn/Article/details/gtegrihabv.html

TS:   // 同 JS
来源：http://dali.mhx1999.top/Article/details/gtwmmmlebh.html

Java: synchronized (this) { shared++; }
来源：http://dali.fzhhl.top/Article/details/gtpcnuwhbr.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.yueranfly.top/Article/details/gtfkgvglij.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.9152youxi.cn/Article/details/gtzfntrdfs.html

C#:   lock (gate) { shared++; }
来源：http://dali.tianlin.xyz/Article/details/gtwqmghuzg.html

[O04] 定义异步函数并等待
来源：http://dali.guowangkeji.top/Article/details/gtygbveaym.html

Py:   async def f():⏎    await g()
来源：http://dali.ybcxt.top/Article/details/gtscdwxejo.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfucrnvrs.html

JS:   async function f() { await g(); }
来源：http://dali.yangfankeji.com/Article/details/gtsqjrujlf.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.gaohongyu789.top/Article/details/gtlvnrhkib.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.guowangkeji.top/Article/details/gtzmczkyvo.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrxaqrhva.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.nanxuanxn.top/Article/details/gtwgjbkhpb.html

C#:   async Task F() { await G(); }
来源：http://dali.iojbl.cn/Article/details/gtarznkntf.html

[O05] 并发执行并等待全部完成
来源：http://dali.c1oappe.top/Article/details/gtlpeqhrqm.html

Py:   asyncio.gather(*tasks)
来源：http://dali.vqdsnc.cn/Article/details/gttycvggor.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.xziqi.cn/Article/details/gtyyepueye.html

JS:   await Promise.all(tasks)
来源：http://dali.jinghuilouyu.cn/Article/details/gtgjardaky.html

TS:   await Promise.all(tasks)
来源：http://dali.sufxvd.cn/Article/details/gtwymugvuy.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.gotoacloud.top/Article/details/gtfveootyr.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.yj20258.top/Article/details/gtzjvxkjci.html

Ruby: threads.map(&:join)
来源：http://dali.ppjwa.cn/Article/details/gtdaxiilwl.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.gotoacloud.top/Article/details/gtqtyzzyou.html

[O06] 使用进程池
来源：http://dali.jinyuanbaomall.cn/Article/details/gtffpssnrm.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.kuanghao11.cn/Article/details/gtgvrwbwat.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmqfnltja.html

JS:   // child_process / cluster 模块
来源：http://dali.jlsjyb.cn/Article/details/gtmcqawdfl.html

TS:   // child_process / cluster 模块
来源：http://dali.zhongyouzk.top/Article/details/gtelwschis.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.yuxming.cn/Article/details/gtuozvescq.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.nanxuanxn.top/Article/details/gtwtesdghu.html

Ruby: // fork 块
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpdyrcygd.html

C#:   Parallel.For
来源：http://dali.tianlin.xyz/Article/details/gtscajiczw.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtfkyeuynd.html

P. 常用工具函数
来源：http://dali.ppjwa.cn/Article/details/gtbgripxxz.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtulfqzavg.html

[P01] 生成 UUID
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcdpledup.html

Py:   str(uuid.uuid4())
来源：http://dali.hammf.cn/Article/details/gthsepfzft.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.hysaishi.cn/Article/details/gthnkizyyp.html

JS:   crypto.randomUUID()
来源：http://dali.jinqigfzy.top/Article/details/gttmewsxjj.html

TS:   crypto.randomUUID()
来源：http://dali.yueranfly.top/Article/details/gtnyweccut.html

Java: UUID.randomUUID().toString()
来源：http://dali.9152youxi.cn/Article/details/gtnprsttot.html

Go:   // 用 github.com/google/uuid
来源：http://dali.jyoumei.cn/Article/details/gtvdfflhvu.html

Ruby: SecureRandom.uuid
来源：http://dali.fzhhl.top/Article/details/gtahoxpywz.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.hysaishi.cn/Article/details/gtjrcodcnc.html

[P02] MD5 / SHA256 摘要
来源：http://dali.kuanghao11.cn/Article/details/gtniyparbf.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwblxcopn.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnnrkhjus.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhongyouzk.top/Article/details/gtnyktctuj.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.chenlongwang.top/Article/details/gtbgrwojmd.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.dashuyun.cn/Article/details/gtimniredk.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.chenjidiqi.icu/Article/details/gtsukwqjyv.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.c1oappe.top/Article/details/gtjnfvtbxw.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.xuetiantiany.cn/Article/details/gttpuvbquk.html

[P03] 生成短随机字符串
来源：http://dali.ywan-chungtsiang.top/Article/details/gtezsmpaen.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhixingplan.top/Article/details/gteemlkalk.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.tanke756.top/Article/details/gtkmmlntrx.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.chenzaomai.com/Article/details/gthkmpwwrd.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.c1oappe.top/Article/details/gtzgeppepv.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.yangfankeji.com/Article/details/gtpaxpxoyk.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.snrcjt.cn/Article/details/gtpwddyuku.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.xuanzx.com/Article/details/gtdadiexis.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.nanxuanxn.top/Article/details/gtxtaisjxt.html

[P04] 求长度
来源：http://dali.shangyingyoupin.top/Article/details/gthyufkuoz.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.gzhubu.top/Article/details/gtycjaovvd.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.havefunace.top/Article/details/gtknvxexeq.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yj20258.top/Article/details/gtpospwhrq.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhongyouzk.top/Article/details/gtjekhgeqg.html

Java: list.size();  map.size();  s.length()
来源：http://dali.yj202588.top/Article/details/gtbokjpbnw.html

Go:   len(arr);  len(m)
来源：http://dali.svipenyu.cn/Article/details/gtpgcunsqm.html

Ruby: x.length;  x.size
来源：http://dali.daxiang520.top/Article/details/gttfoonxjv.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.xuanzx.com/Article/details/gtrmjzoowv.html

[P05] 判断两个对象内容是否相等
来源：http://dali.cucudq.cn/Article/details/gthvcgbbuh.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.sweek.top/Article/details/gtxiiecwnp.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.chenlongwang.top/Article/details/gtatpvuats.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.sxryk.cn/Article/details/gtrlhssktt.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.tian-w.cn/Article/details/gthkmfodvt.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.ehwqpu.com/Article/details/gthdrjxegt.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.ivvv.top/Article/details/gtpttuvrow.html

Ruby: a == b
来源：http://dali.yuxming.cn/Article/details/gtanghfqpm.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.nwbrower.top/Article/details/gtzszrinuo.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.quarkkingdee.top/Article/details/gtfauhlchi.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.9152youxi.cn/Article/details/gthkgumggx.html

PHP:  if (empty($x)) {}
来源：http://dali.hysaishi.cn/Article/details/gtlobhyshd.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.mhx1999.top/Article/details/gthohgsmbk.html

TS:   if (x == null) {}
来源：http://dali.fzhhl.top/Article/details/gtgbrwciip.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.chenlongwang.top/Article/details/gtpllurpwx.html

Go:   if x == nil {}
来源：http://dali.hammf.cn/Article/details/gtmubapedu.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.yj20258888.top/Article/details/gttfqbxgrp.html

C#:   if (x is null) {}
来源：http://dali.hnxiangtu.top/Article/details/gtburmeyhy.html

[P07] 防抖与节流
来源：http://dali.chenjidiqi.icu/Article/details/gtfbcizrhg.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhengqikj.top/Article/details/gtidwtxruv.html

PHP:  // 手写时间戳比较
来源：http://dali.zhongyouzk.top/Article/details/gtpztbkzqz.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlfehizww.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jinqigfzy.top/Article/details/gtwfzabniq.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.dianchejie.cn/Article/details/gtuzfattyr.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zdqjudy.top/Article/details/gtxlmugvsu.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqmfbbgvy.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.c1oappe.top/Article/details/gtccdoibyp.html

[P08] 处理浮点精度问题
来源：http://dali.haohaochexian.top/Article/details/gtzsnudkaj.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.aizwys.cn/Article/details/gtudbbvcfe.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.yj20258.top/Article/details/gthstonhtb.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.jqgfzy.top/Article/details/gtxkvyvkwj.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.tianlin.xyz/Article/details/gtpepklwda.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.fengsongda.top/Article/details/gtlgpzbykw.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.aizwys.cn/Article/details/gtuqlsnnug.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.havefunace.top/Article/details/gtuvjnhhyf.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.ybcxt.top/Article/details/gtyarbkfzu.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtxvpreina.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.yj202588.top/Article/details/gtlryvrsfm.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtfasparxs.html

[Q01] 创建表
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfwcjogra.html

CREATE TABLE users (
来源：http://dali.feifeiyinyue.top/Article/details/gtbcubaldh.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zycfv.cn/Article/details/gtwteixbpb.html

name VARCHAR(50) NOT NULL,
来源：http://dali.ivvv.top/Article/details/gtnssiasha.html

email VARCHAR(100) UNIQUE,
来源：http://dali.yuanzhike.top/Article/details/gtwbchqtdw.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.hammf.cn/Article/details/gtdhxdwyhc.html

);
来源：http://dali.fengsongda.top/Article/details/gthnsejeqk.html

[Q02] 创建带外键的表
来源：http://dali.sweek.top/Article/details/gtxtbmxuig.html

CREATE TABLE orders (
来源：http://dali.wangdashe.top/Article/details/gtwvcbndmb.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.wangdashe.top/Article/details/gtojaesrxy.html

user_id INT NOT NULL,
来源：http://dali.daxiang520.top/Article/details/gtrsqykbfy.html

amount DECIMAL(10, 2),
来源：http://dali.andypj.xyz/Article/details/gtvrfnjsge.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.sweek.top/Article/details/gtjzfovskf.html

);
来源：http://dali.dashuyun.cn/Article/details/gtbxtshxgd.html

[Q03] 增加列
来源：http://dali.pycfn.com/Article/details/gtdwabuxca.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhengqikj.top/Article/details/gtzukxofdu.html

[Q04] 修改列类型
来源：http://dali.pycfn.com/Article/details/gtjowulwgf.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.guannengcc.top/Article/details/gttpissqtf.html

[Q05] 重命名列
来源：http://dali.nanxinkj.top/Article/details/gtscbglofy.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhiwuduotai.top/Article/details/gtblibdhjr.html

[Q06] 删除列
来源：http://dali.gzhubu.top/Article/details/gtcvevjkja.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.yanxiufei.cn/Article/details/gtlnhyujxj.html

[Q07] 删除表
来源：http://dali.yuanzhike.top/Article/details/gtthtifqtp.html

DROP TABLE IF EXISTS orders;
来源：http://dali.yj20258888.top/Article/details/gtjaaokrtc.html

[Q08] 创建普通索引
来源：http://dali.ydzc1.top/Article/details/gttcvporwp.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.jqgfzy.top/Article/details/gtnygajdua.html

[Q09] 创建唯一索引
来源：http://dali.jianghu66.top/Article/details/gtmxiyjpsq.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.316326.xyz/Article/details/gtyekbzsvq.html

[Q10] 插入单行
来源：http://dali.gzhubu.top/Article/details/gtrcmalxlo.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgubnhsgj.html

[Q11] 一次插入多行
来源：http://dali.andypj.xyz/Article/details/gtzhihksgo.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.316326.xyz/Article/details/gtrgqagjaa.html

[Q12] 插入后取自增 ID
来源：http://dali.snrcjt.cn/Article/details/gtbfxxkmhr.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.wangshuangyany.cn/Article/details/gtgvguwoei.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.iojbl.cn/Article/details/gtzvxietsw.html

[Q13] 忽略重复插入
来源：http://dali.jinghuilouyu.cn/Article/details/gtwxyjhnxv.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.shangyingyoupin.top/Article/details/gtxzognowd.html


<!-- 参考信息 -->