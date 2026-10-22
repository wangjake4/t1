代发 wailian999

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.havefunace.top/Article/details/gtwztctujm.html

Ruby: warn "err"
来源：http://dali.yj20258.top/Article/details/gtqknobdiq.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.yonumen.top/Article/details/gtwuhqajat.html

[M07] 判断是否为主入口
来源：http://dali.yuxming.cn/Article/details/gtlljopwpp.html

Py:   if __name__ == "__main__":
来源：http://dali.jianghu66.top/Article/details/gtxklhwwsg.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.ivvv.top/Article/details/gtwopkozfy.html

JS:   require.main === module
来源：http://dali.cqqwz.cn/Article/details/gtwxtqlyxr.html

TS:   require.main === module
来源：http://dali.zhoulong.xyz/Article/details/gtzdgtuiho.html

Java: public static void main(String[] args)
来源：http://dali.jlsjyb.cn/Article/details/gtsdypszzl.html

Go:   func main()
来源：http://dali.kuanghao11.cn/Article/details/gtnpchzand.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.bjfxy.top/Article/details/gttkqrncav.html

C#:   static void Main(string[] args)
来源：http://dali.xuanzx.com/Article/details/gtadiuzgso.html

[M08] 获取系统与运行时信息
来源：http://dali.andypj.xyz/Article/details/gtuhijnboq.html

Py:   platform.system();  platform.python_version()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfqbnlecx.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.birdmap.top/Article/details/gthmlclqik.html

JS:   process.platform;  process.version
来源：http://dali.hammf.cn/Article/details/gtrvobpier.html

TS:   process.platform;  process.version
来源：http://dali.wangshuangyany.cn/Article/details/gtonrnuall.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.sysykeji.top/Article/details/gtwszckxjo.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.ppjwa.cn/Article/details/gtjcixexff.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.sxryk.cn/Article/details/gtfxusbkwz.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.ybcxt.top/Article/details/gttxkxbccx.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtbcbmjcyo.html

N. 数据结构与算法
来源：http://dali.sxryk.cn/Article/details/gtbdbzuclu.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtrejllmyf.html

[N01] 二分查找（有序数组）
来源：http://dali.gotoacloud.top/Article/details/gtpiutibgq.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.xylfe.cn/Article/details/gtcuyxdpgd.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.dianchejie.cn/Article/details/gtzkfbpexr.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.gaohongyu789.top/Article/details/gtwopaihjp.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.daria6918.cn/Article/details/gtutcexuzo.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.9152youxi.cn/Article/details/gtsqmeahsw.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqnkofuao.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.gotoacloud.top/Article/details/gtfuuaupra.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfvuilxlu.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.svipenyu.cn/Article/details/gtrufrfmag.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.meibo888.top/Article/details/gtwhaxnesd.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.shanyushiyangtech.top/Article/details/gtwonvrzol.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.nanxinkj.top/Article/details/gtgzomtcgd.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhoulong.xyz/Article/details/gtftyxqxzj.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.cashguo.top/Article/details/gtuxjdqkzb.html

Go:   slices.Sort(arr)
来源：http://dali.feifeiyinyue.top/Article/details/gtyszizdvn.html

Ruby: arr.sort
来源：http://dali.dashuyun.cn/Article/details/gtfffpelde.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.aizwys.cn/Article/details/gtilydmdzq.html

[N03] 快速排序（分治示例）
来源：http://dali.feifeiyinyue.top/Article/details/gtoovujjdy.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.jinqigfzy.top/Article/details/gtrqwidlbj.html

PHP:  // 递归实现，或用 usort
来源：http://dali.gaohongyu789.top/Article/details/gttbjtyfma.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhoulong.xyz/Article/details/gtukecxzkg.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.xuetiantiany.cn/Article/details/gtxawxhoxd.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.gaohongyu789.top/Article/details/gthmqvuuuh.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.yuxming.cn/Article/details/gtudtzqieh.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.jqgufenzy.top/Article/details/gttjhnagxg.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.ppjwa.cn/Article/details/gtttqwdjef.html

[N04] 斐波那契数列
来源：http://dali.yongpay.top/Article/details/gthaeuxdqc.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.tanke756.top/Article/details/gtfkcztujz.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.haohaochexian.top/Article/details/gtukxzydwl.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.vqdsnc.cn/Article/details/gtpllmdsdz.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yvedp.cn/Article/details/gtpowgcaaj.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.feifeiyinyue.top/Article/details/gtfzfssuef.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.fengsongda.top/Article/details/gtpyahudro.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.chenlongwang.top/Article/details/gtczlspmua.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.xziqi.cn/Article/details/gtfjomjavo.html

[N05] 最大公约数
来源：http://dali.ydzc1.top/Article/details/gtrmkwpmkl.html

Py:   math.gcd(a, b)
来源：http://dali.redwolf501.top/Article/details/gthvshflmc.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.pengpengdd.cyou/Article/details/gtdxyyzpqn.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yonumen.top/Article/details/gttslpvezr.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.xuetiantiany.cn/Article/details/gtjfkozoei.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.redwolf501.top/Article/details/gtrrbzhgff.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.yvedp.cn/Article/details/gttavuquzr.html

Ruby: a.gcd(b)
来源：http://dali.zhixingplan.top/Article/details/gtzuagdldh.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.pengpengdd.cyou/Article/details/gtnkfijjzn.html

[N06] 判断回文字符串
来源：http://dali.redwolf501.top/Article/details/gttfxklupr.html

Py:   s == s[::-1]
来源：http://dali.xuanzx.com/Article/details/gtziyjvhdl.html

PHP:  $s === strrev($s);
来源：http://dali.zhongyouzk.top/Article/details/gtmrfmmcqa.html

JS:   s === [...s].reverse().join("")
来源：http://dali.gotoacloud.top/Article/details/gtuaofhpsn.html

TS:   s === [...s].reverse().join("")
来源：http://dali.9152youxi.cn/Article/details/gtpgsggzye.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.yj20258888.top/Article/details/gtiqyfihnc.html

Go:   // 双指针从两端比较
来源：http://dali.daria6918.cn/Article/details/gtdrtndcva.html

Ruby: s == s.reverse
来源：http://dali.wangdashe.top/Article/details/gtltzuyamw.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.0kj1m.cn/Article/details/gtovwaiuhn.html

[N07] 两数之和（返回下标）
来源：http://dali.smart0.xyz/Article/details/gtbbzclqme.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.chenjidiqi.icu/Article/details/gtjympmatb.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.jinyuanbaomall.cn/Article/details/gtamheuxlu.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gtzuzgoone.html

TS:   // 手写 Map<string, number>
来源：http://dali.guowangkeji.top/Article/details/gtymedwgej.html

Java: // 手写 HashMap
来源：http://dali.yangfankeji.com/Article/details/gtparoncbs.html

Go:   // 手写 map[int]int
来源：http://dali.shanyushiyangkeji.top/Article/details/gtruhikvhl.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gtlnyzhefd.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.shangyingyoupin.top/Article/details/gtwmbuwdcq.html

[N08] 生成全排列
来源：http://dali.hnqzz.top/Article/details/gtkvjhsgsp.html

Py:   itertools.permutations(arr)
来源：http://dali.sxryk.cn/Article/details/gtskfbudzj.html

PHP:  // 手写递归交换
来源：http://dali.tanke756.top/Article/details/gtpxktmvln.html

JS:   // 手写回溯递归
来源：http://dali.sxryk.cn/Article/details/gteonhkwcz.html

TS:   // 手写回溯递归
来源：http://dali.gzhubu.top/Article/details/gtpigebbfk.html

Java: // 手写回溯递归
来源：http://dali.zhoulong.xyz/Article/details/gtkypuqnhq.html

Go:   // 手写回溯递归
来源：http://dali.aizwys.cn/Article/details/gtjzxdkuzj.html

Ruby: arr.permutation.to_a
来源：http://dali.yj20258888.top/Article/details/gtohggpqqj.html

C#:   // 手写回溯递归
来源：http://dali.zycfv.cn/Article/details/gtobybqnju.html

[N09] 栈与队列
来源：http://dali.gogol.net.cn/Article/details/gtforsfptf.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhiwuduotai.top/Article/details/gtnulhaqsw.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.dashuyun.cn/Article/details/gthgqewgmo.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.chenjidiqi.icu/Article/details/gtntxvnzjr.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zdqjudy.top/Article/details/gtiaucuhfp.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.iojbl.cn/Article/details/gtqcwoavny.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.yvedp.cn/Article/details/gtskvdpdry.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.sufxvd.cn/Article/details/gtwunhwyov.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.chenzaomai.com/Article/details/gtepjlleoq.html

[N10] 链表节点定义
来源：http://dali.chenzaomai.com/Article/details/gtmgycyvfx.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.cashguo.top/Article/details/gtyuegecwn.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.jlsjyb.cn/Article/details/gtgyqrxywv.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.aizwys.cn/Article/details/gtronedone.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgrvxqrly.html

Java: class Node { int v; Node next; }
来源：http://dali.jianghu66.top/Article/details/gtsfvaalah.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.ppjwa.cn/Article/details/gtlxvfrimg.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcjbkcrur.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.pengpengdd.cyou/Article/details/gtzqgambko.html

[N11] 二叉树中序遍历
来源：http://dali.hongshengwenyu.top/Article/details/gtsnuvzrfg.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhengqikj.top/Article/details/gtdfetmuaz.html

PHP:  // 手写递归函数
来源：http://dali.ivvv.top/Article/details/gtrwxsbimn.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.xinyue.icu/Article/details/gtphzkmeqt.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.feifeiyinyue.top/Article/details/gtsytrcyhm.html

Java: // 手写递归
来源：http://dali.havefunace.top/Article/details/gtpgsiaezz.html

Go:   // 手写递归
来源：http://dali.cdnleiting.top/Article/details/gtipbkpodz.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.hywenlv.cn/Article/details/gtbuhpdmow.html

C#:   // 手写递归
来源：http://dali.wangdashe.top/Article/details/gtqaenavpj.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.gaohongyu789.top/Article/details/gtqtwemxxa.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.svipenyu.cn/Article/details/gtkxvsoyty.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.xylfe.cn/Article/details/gtuycczzrm.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yangfankeji.com/Article/details/gtifrzysse.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.snrcjt.cn/Article/details/gtvldwfksl.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.dashuyun.cn/Article/details/gtyrcpyyal.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zdqjudy.top/Article/details/gtylszcubo.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.yj20258888.top/Article/details/gtwgicpmdr.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhongyouzk.top/Article/details/gtwiaffaor.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtfxjfterc.html

O. 并发与异步
来源：http://dali.andypj.xyz/Article/details/gtetauyloo.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtktacnnig.html

[O01] 启动一个线程
来源：http://dali.ydzc1.top/Article/details/gtwxcbkwqt.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.yvedp.cn/Article/details/gtyalcolzy.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.tanke756.top/Article/details/gtgsyfxcgv.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.shzxlz.cn/Article/details/gtfyxpdejk.html

TS:   // 同 JS
来源：http://dali.sysykeji.top/Article/details/gtkeloquqz.html

Java: new Thread(() -> f()).start()
来源：http://dali.jinghuilouyu.cn/Article/details/gtvntmffkz.html

Go:   go f()
来源：http://dali.hysaishi.cn/Article/details/gtwrnpwkxd.html

Ruby: Thread.new { f }
来源：http://dali.guannengcc.top/Article/details/gtfqnxumis.html

C#:   Task.Run(() => F());
来源：http://dali.zhixingplan.top/Article/details/gtqhebyajz.html

[O02] 使用线程池
来源：http://dali.xuanzx.com/Article/details/gtbjbyurja.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.svipenyu.cn/Article/details/gtlvghodra.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.sysykeji.top/Article/details/gtlanqrukp.html

JS:   // worker_threads 线程池
来源：http://dali.pycfn.com/Article/details/gtnqognqju.html

TS:   // worker_threads 线程池
来源：http://dali.jinqigufen.top/Article/details/gtrzksqmfq.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.nwbrower.top/Article/details/gtlznrtxeo.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zdqjudy.top/Article/details/gtwkdlohvw.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.yangfankeji.com/Article/details/gtsyldvlgb.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.feifeiyinyue.top/Article/details/gtnijhlvsn.html

[O03] 加锁保护共享数据
来源：http://dali.guannengcc.top/Article/details/gtstxixxmq.html

Py:   with lock: shared += 1
来源：http://dali.quarkkingdee.top/Article/details/gtyzwixcze.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.ivvv.top/Article/details/gtwpfmawri.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.pycfn.com/Article/details/gticwpldbd.html

TS:   // 同 JS
来源：http://dali.ydzc1.top/Article/details/gtisljkbzy.html

Java: synchronized (this) { shared++; }
来源：http://dali.jqgfzy.top/Article/details/gtkprnhrsk.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zycfv.cn/Article/details/gtxpxzrybm.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqxervueu.html

C#:   lock (gate) { shared++; }
来源：http://dali.ybcxt.top/Article/details/gtpopbqeec.html

[O04] 定义异步函数并等待
来源：http://dali.xinyue.icu/Article/details/gtfzajzsnl.html

Py:   async def f():⏎    await g()
来源：http://dali.fengsongda.top/Article/details/gtsxioskog.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.yangfankeji.com/Article/details/gthvjcxmtr.html

JS:   async function f() { await g(); }
来源：http://dali.yj202588.top/Article/details/gtyjzjydlw.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsouhxvzc.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zdqjudy.top/Article/details/gtrvcrmdli.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.hnqzz.top/Article/details/gtihgyhime.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.yj20258.top/Article/details/gtebpfjmwh.html

C#:   async Task F() { await G(); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlqbtjbrl.html

[O05] 并发执行并等待全部完成
来源：http://dali.wangshuangyany.cn/Article/details/gthfnkdkbh.html

Py:   asyncio.gather(*tasks)
来源：http://dali.c1oappe.top/Article/details/gthqmrfyvv.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.ivvv.top/Article/details/gtnmyzunpo.html

JS:   await Promise.all(tasks)
来源：http://dali.iojbl.cn/Article/details/gtkrbmhruq.html

TS:   await Promise.all(tasks)
来源：http://dali.pycfn.com/Article/details/gtslqutusq.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.guannengcc.top/Article/details/gtxfipyrfq.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.cheryme.top/Article/details/gtkwmxkhad.html

Ruby: threads.map(&:join)
来源：http://dali.hywenlv.cn/Article/details/gtfgytahoy.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.shangyingyoupin.top/Article/details/gttvxgtlle.html

[O06] 使用进程池
来源：http://dali.bjfxy.top/Article/details/gtipkkxbuh.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.quarkkingdee.top/Article/details/gtkacwxtjc.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.hysaishi.cn/Article/details/gtvjucgcog.html

JS:   // child_process / cluster 模块
来源：http://dali.gaohongyu789.top/Article/details/gttvnxhhdw.html

TS:   // child_process / cluster 模块
来源：http://dali.yuxming.cn/Article/details/gtzuflxsvm.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.hnqzz.top/Article/details/gtvfnvmtjp.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.bjfxy.top/Article/details/gtgkxckqpv.html

Ruby: // fork 块
来源：http://dali.redwolf501.top/Article/details/gtpnofjrso.html

C#:   Parallel.For
来源：http://dali.pycfn.com/Article/details/gtgeagzbfd.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtrvpdihhz.html

P. 常用工具函数
来源：http://dali.redwolf501.top/Article/details/gtuuigopib.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gthhhzgmsp.html

[P01] 生成 UUID
来源：http://dali.xylfe.cn/Article/details/gtlyoegxiv.html

Py:   str(uuid.uuid4())
来源：http://dali.yuanzhike.top/Article/details/gtnigxzeag.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.gogol.net.cn/Article/details/gtucctmkhk.html

JS:   crypto.randomUUID()
来源：http://dali.guannengcc.top/Article/details/gtxoqjerwb.html

TS:   crypto.randomUUID()
来源：http://dali.iojbl.cn/Article/details/gtqcabxkyn.html

Java: UUID.randomUUID().toString()
来源：http://dali.yonumen.top/Article/details/gtlcnwesaa.html

Go:   // 用 github.com/google/uuid
来源：http://dali.hysaishi.cn/Article/details/gteaxxqzrm.html

Ruby: SecureRandom.uuid
来源：http://dali.guannengcc.top/Article/details/gtoogynlba.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.havefunace.top/Article/details/gtrqxsuviz.html

[P02] MD5 / SHA256 摘要
来源：http://dali.yanxiufei.cn/Article/details/gtwzyckbwq.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.svipenyu.cn/Article/details/gtlpgnrsvr.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.chenlongwang.top/Article/details/gttbjahdni.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.yuanzhike.top/Article/details/gtcdhtyazn.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.yuxming.cn/Article/details/gtzgrebagg.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gtzklrnvyv.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.iojbl.cn/Article/details/gtmrkitdne.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.yj202588.top/Article/details/gtgtihdyue.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.c1oappe.top/Article/details/gtnwcuhzry.html

[P03] 生成短随机字符串
来源：http://dali.ivvv.top/Article/details/gtgpatmgqt.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.xuetiantiany.cn/Article/details/gtjlknipvd.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcmrzhycd.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yueranfly.top/Article/details/gtvkwfozfn.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yvedp.cn/Article/details/gtpbnkaclm.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.jinqigufen.top/Article/details/gtnrsawcdn.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.pengpengdd.cyou/Article/details/gtbjsbhiao.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.guannengcc.top/Article/details/gtziriwhtk.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.jiagoushi.top/Article/details/gtieurctgn.html

[P04] 求长度
来源：http://dali.xuanzx.com/Article/details/gtkywairey.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gttbprkscc.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.ivvv.top/Article/details/gtooteveex.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.redwolf501.top/Article/details/gteobhtirh.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jinqigufen.top/Article/details/gtbkytelar.html

Java: list.size();  map.size();  s.length()
来源：http://dali.kuanghao11.cn/Article/details/gtdigmtqsr.html

Go:   len(arr);  len(m)
来源：http://dali.cdnleiting.top/Article/details/gttqtvksrm.html

Ruby: x.length;  x.size
来源：http://dali.yuanzhike.top/Article/details/gtgrmudezd.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.hammf.cn/Article/details/gtutxaeaxf.html

[P05] 判断两个对象内容是否相等
来源：http://dali.jiagoushi.top/Article/details/gtqzmsiblk.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.aibaodan.cn/Article/details/gtjasjchwy.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.sysykeji.top/Article/details/gtajihbxwl.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.hongshengwenyu.top/Article/details/gtbuvxtske.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.meibo888.top/Article/details/gtfgwubzti.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.c1oappe.top/Article/details/gtqlysnaxm.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzunnnfhr.html

Ruby: a == b
来源：http://dali.jqgufenzy.top/Article/details/gtjjojqyfv.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.shanyushiyangtech.top/Article/details/gtbctehuil.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.sufxvd.cn/Article/details/gtspsarxly.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.chenzaomai.com/Article/details/gtotoarfuh.html

PHP:  if (empty($x)) {}
来源：http://dali.bjfxy.top/Article/details/gtxoeaoupk.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.haohaochexian.top/Article/details/gtidenohus.html

TS:   if (x == null) {}
来源：http://dali.hnqzz.top/Article/details/gtlljvtgwj.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.ydzc1.top/Article/details/gtvecgvhaw.html

Go:   if x == nil {}
来源：http://dali.feifeiyinyue.top/Article/details/gtnctxyviq.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.redwolf501.top/Article/details/gtkqfvpggi.html

C#:   if (x is null) {}
来源：http://dali.sufxvd.cn/Article/details/gtvrvlasqa.html

[P07] 防抖与节流
来源：http://dali.cdnleiting.top/Article/details/gtcojohgdx.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.shangyingyoupin.top/Article/details/gtiklgmroz.html

PHP:  // 手写时间戳比较
来源：http://dali.havefunace.top/Article/details/gtkrzvjekp.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.wangdashe.top/Article/details/gtxcgsewhd.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hysaishi.cn/Article/details/gtwyfbuvvp.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.ivvv.top/Article/details/gthlppreve.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.jyoumei.cn/Article/details/gtiismwsrj.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.jiagoushi.top/Article/details/gtkmbybvhq.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.fengsongda.top/Article/details/gthlbdikqr.html

[P08] 处理浮点精度问题
来源：http://dali.jlsjyb.cn/Article/details/gtmenejlep.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.pycfn.com/Article/details/gtgqxheajr.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhongyouzk.top/Article/details/gtiufeokhx.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhoulong.xyz/Article/details/gtqrnjofwc.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqexywrdl.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.redwolf501.top/Article/details/gtsawjtltc.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.nanxuanxn.top/Article/details/gtxvolsbfk.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.quarkkingdee.top/Article/details/gtpgdotvcr.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.yongpay.top/Article/details/gtjyopfsvb.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtvvfcsgnf.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.andypj.xyz/Article/details/gtyfvgipnl.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtgnyskply.html

[Q01] 创建表
来源：http://dali.gzhubu.top/Article/details/gtvibdwcsg.html

CREATE TABLE users (
来源：http://dali.zdqjudy.top/Article/details/gtdupkpdwy.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhoulong.xyz/Article/details/gtesnwwxql.html

name VARCHAR(50) NOT NULL,
来源：http://dali.hnqzz.top/Article/details/gtrmbascgz.html

email VARCHAR(100) UNIQUE,
来源：http://dali.pengpengdd.cyou/Article/details/gtnpvopple.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zdqjudy.top/Article/details/gtdrvfjagr.html

);
来源：http://dali.yvedp.cn/Article/details/gtnrylmwmd.html

[Q02] 创建带外键的表
来源：http://dali.iojbl.cn/Article/details/gtygvnhnoc.html

CREATE TABLE orders (
来源：http://dali.gotoacloud.top/Article/details/gtamvsnbvy.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jiagoushi.top/Article/details/gtjqfdetau.html

user_id INT NOT NULL,
来源：http://dali.hnqzz.top/Article/details/gtcufspfqr.html

amount DECIMAL(10, 2),
来源：http://dali.gotoacloud.top/Article/details/gtwvomwife.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gtkkamufnu.html

);
来源：http://dali.yongpay.top/Article/details/gtnpwipfqb.html

[Q03] 增加列
来源：http://dali.hongshengwenyu.top/Article/details/gtzhpsssnw.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.jinqigufen.top/Article/details/gtmeyemgfj.html

[Q04] 修改列类型
来源：http://dali.ppjwa.cn/Article/details/gtfberqdoz.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.vqdsnc.cn/Article/details/gtzogzseut.html

[Q05] 重命名列
来源：http://dali.ydzc1.top/Article/details/gtxbzizhmp.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.cqqwz.cn/Article/details/gtanmxoobm.html

[Q06] 删除列
来源：http://dali.zdqjudy.top/Article/details/gtmsqyqylu.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.9152youxi.cn/Article/details/gtdotpwwhk.html

[Q07] 删除表
来源：http://dali.zhixingplan.top/Article/details/gtmyxnkecm.html

DROP TABLE IF EXISTS orders;
来源：http://dali.vqdsnc.cn/Article/details/gtiucbfhbr.html

[Q08] 创建普通索引
来源：http://dali.jqgfzy.top/Article/details/gttrgtlwzm.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.0kj1m.cn/Article/details/gtkkpccgpo.html

[Q09] 创建唯一索引
来源：http://dali.jinghuilouyu.cn/Article/details/gttztberjo.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.9152youxi.cn/Article/details/gtxrsanioa.html

[Q10] 插入单行
来源：http://dali.jqgufenzy.top/Article/details/gtyylimlem.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.aibaodan.cn/Article/details/gtsojocuqp.html

[Q11] 一次插入多行
来源：http://dali.yj20258.top/Article/details/gtvmssrbbs.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.mhx1999.top/Article/details/gtcweeoyva.html

[Q12] 插入后取自增 ID
来源：http://dali.yongpay.top/Article/details/gtvjgmxnbx.html


<!-- 参考信息 -->