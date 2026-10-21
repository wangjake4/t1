代发 wailian999

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.aizwys.cn/Article/details/gtztgccxzc.html

JS:   console.error("err")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjelsxknb.html

TS:   console.error("err")
来源：http://dali.tanke756.top/Article/details/gtyiesgidw.html

Java: System.err.println("err")
来源：http://dali.shzxlz.cn/Article/details/gtybyxufas.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.tian-w.cn/Article/details/gtbzcqsrsq.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gtlwrioqoy.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.316326.xyz/Article/details/gtbibzbqbo.html

[M07] 判断是否为主入口
来源：http://dali.zhengqikj.top/Article/details/gtfhzxialt.html

Py:   if __name__ == "__main__":
来源：http://dali.aizwys.cn/Article/details/gtvecitjvt.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.hnxiangtu.top/Article/details/gtzsoqzbrf.html

JS:   require.main === module
来源：http://dali.xuetiantiany.cn/Article/details/gtnjgdvxjl.html

TS:   require.main === module
来源：http://dali.cashguo.top/Article/details/gtayhetmae.html

Java: public static void main(String[] args)
来源：http://dali.sweek.top/Article/details/gtqbuqwrjs.html

Go:   func main()
来源：http://dali.yuxming.cn/Article/details/gtlcicapvk.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.hywenlv.cn/Article/details/gtofrcycts.html

C#:   static void Main(string[] args)
来源：http://dali.yj20258.top/Article/details/gtibpinsjx.html

[M08] 获取系统与运行时信息
来源：http://dali.cashguo.top/Article/details/gtbqxazhal.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhiwuduotai.top/Article/details/gtpfhxtykc.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.yueranfly.top/Article/details/gttelgxine.html

JS:   process.platform;  process.version
来源：http://dali.zhoulong.xyz/Article/details/gtmfrpdkmp.html

TS:   process.platform;  process.version
来源：http://dali.yueranfly.top/Article/details/gtbydgoyqd.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.feifeiyinyue.top/Article/details/gtkdujkykr.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.0kj1m.cn/Article/details/gtxpomhmzj.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.gogol.net.cn/Article/details/gttvwwofgg.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhaomingkeji.xyz/Article/details/gtousntyda.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtsjhnagxe.html

N. 数据结构与算法
来源：http://dali.smart0.xyz/Article/details/gtkdwpcozx.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gthmtlmjxf.html

[N01] 二分查找（有序数组）
来源：http://dali.shanyushiyangtech.top/Article/details/gtswvbkfwv.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.sysykeji.top/Article/details/gtkczygbiy.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.aizwys.cn/Article/details/gtipbkfhhq.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.chenlongwang.top/Article/details/gtjxibzsut.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.iojbl.cn/Article/details/gtfyrdqikv.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.chenjidiqi.icu/Article/details/gthofvxakc.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.meibo888.top/Article/details/gtwoyzkkao.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.guowangkeji.top/Article/details/gtjwxbqqja.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.tian-w.cn/Article/details/gteyrrcqnn.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.cdnleiting.top/Article/details/gtwtgdsneh.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.kuanghao11.cn/Article/details/gtylnapeos.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.jianghu66.top/Article/details/gturcftmdt.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtilawgqsx.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.ivvv.top/Article/details/gtiqrlzptv.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.ybcxt.top/Article/details/gtgenwzekt.html

Go:   slices.Sort(arr)
来源：http://dali.yvedp.cn/Article/details/gtuagwnrbe.html

Ruby: arr.sort
来源：http://dali.hnqzz.top/Article/details/gtepcnpqkm.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.cdnleiting.top/Article/details/gtmydbdsqr.html

[N03] 快速排序（分治示例）
来源：http://dali.yvedp.cn/Article/details/gtkhuwchai.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.shangyingyoupin.top/Article/details/gttjjhumfg.html

PHP:  // 递归实现，或用 usort
来源：http://dali.hongshengwenyu.top/Article/details/gtbvmsfvmb.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.9152youxi.cn/Article/details/gtnyovcohv.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zdqjudy.top/Article/details/gtnezvgsqp.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.daria6918.cn/Article/details/gtopylfwwc.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.fengsongda.top/Article/details/gtwyqaylkr.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzwmgtksk.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.yj20258888.top/Article/details/gtzszkfqvj.html

[N04] 斐波那契数列
来源：http://dali.daxiang520.top/Article/details/gtbynkbizk.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.meibo888.top/Article/details/gtyztyfidw.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqzaxspyk.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.chenzaomai.com/Article/details/gtulhfwluz.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.ppjwa.cn/Article/details/gtncxsfbki.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.jqgufenzy.top/Article/details/gtfvckiwzt.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.redwolf501.top/Article/details/gtawovboqw.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.ydzc1.top/Article/details/gtyiigjbqn.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.shzxlz.cn/Article/details/gtmzqxejuz.html

[N05] 最大公约数
来源：http://dali.nanxuanxn.top/Article/details/gtvjxqojli.html

Py:   math.gcd(a, b)
来源：http://dali.meibo888.top/Article/details/gthncvdcel.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjclotkwq.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zdqjudy.top/Article/details/gtwplkaofg.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yonumen.top/Article/details/gtiyhqwvod.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.guannengcc.top/Article/details/gtwueebvgc.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.sweek.top/Article/details/gtynxhuwun.html

Ruby: a.gcd(b)
来源：http://dali.xuanzx.com/Article/details/gtpowkvqru.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.havefunace.top/Article/details/gtvdfyokrf.html

[N06] 判断回文字符串
来源：http://dali.hysaishi.cn/Article/details/gtakckyqwf.html

Py:   s == s[::-1]
来源：http://dali.ppjwa.cn/Article/details/gtpuetlnfc.html

PHP:  $s === strrev($s);
来源：http://dali.cheryme.top/Article/details/gtthsninxh.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zycfv.cn/Article/details/gtbllcclrw.html

TS:   s === [...s].reverse().join("")
来源：http://dali.yuanzhike.top/Article/details/gtffznmmvi.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.cqqwz.cn/Article/details/gtpvimmqmk.html

Go:   // 双指针从两端比较
来源：http://dali.ivvv.top/Article/details/gtjcsngatu.html

Ruby: s == s.reverse
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkiignbar.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.shanyushiyangtech.top/Article/details/gtdcudrqtv.html

[N07] 两数之和（返回下标）
来源：http://dali.gzhubu.top/Article/details/gtgyvhpjcv.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.yj20258.top/Article/details/gtsaubkzkf.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.svipenyu.cn/Article/details/gtaalvzmtz.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.hnxiangtu.top/Article/details/gtbuilzsjh.html

TS:   // 手写 Map<string, number>
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmytpphdv.html

Java: // 手写 HashMap
来源：http://dali.yvedp.cn/Article/details/gtaabfklwr.html

Go:   // 手写 map[int]int
来源：http://dali.shuidangran.top/Article/details/gtvhmirmel.html

Ruby: // 手写 Hash
来源：http://dali.jqgufenzy.top/Article/details/gtfrxwrrnz.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.shuidangran.top/Article/details/gtqrihvonu.html

[N08] 生成全排列
来源：http://dali.cdnleiting.top/Article/details/gtpfucukrq.html

Py:   itertools.permutations(arr)
来源：http://dali.ppjwa.cn/Article/details/gtjphldsgj.html

PHP:  // 手写递归交换
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmbdoiixi.html

JS:   // 手写回溯递归
来源：http://dali.fengsongda.top/Article/details/gtflphnoyr.html

TS:   // 手写回溯递归
来源：http://dali.xuetiantiany.cn/Article/details/gtlyxhxvwj.html

Java: // 手写回溯递归
来源：http://dali.quarkkingdee.top/Article/details/gtxghlcpym.html

Go:   // 手写回溯递归
来源：http://dali.nwbrower.top/Article/details/gtykzccxfi.html

Ruby: arr.permutation.to_a
来源：http://dali.dashuyun.cn/Article/details/gtrwtuwcst.html

C#:   // 手写回溯递归
来源：http://dali.snrcjt.cn/Article/details/gteufhrtck.html

[N09] 栈与队列
来源：http://dali.hnqzz.top/Article/details/gtxrszrekr.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.aibaodan.cn/Article/details/gtykalvwuv.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.xylfe.cn/Article/details/gtjcqxvxqe.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.jqgfzy.top/Article/details/gteryevasc.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.cdnleiting.top/Article/details/gtdqcuypeg.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.yj202588.top/Article/details/gtjsvaywpf.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.jinqigufen.top/Article/details/gtodwlbuww.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.yueranfly.top/Article/details/gtyyzlownf.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.yj20258.top/Article/details/gtlclivfmu.html

[N10] 链表节点定义
来源：http://dali.fzhhl.top/Article/details/gtnvoxyrfg.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.9152youxi.cn/Article/details/gtolzqpqgf.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.smart0.xyz/Article/details/gtafuzrodo.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.0kj1m.cn/Article/details/gtmjbeaeay.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhengqikj.top/Article/details/gtrelmxxbg.html

Java: class Node { int v; Node next; }
来源：http://dali.sysykeji.top/Article/details/gtnilaeziz.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.mhx1999.top/Article/details/gtnihygyqt.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.svipenyu.cn/Article/details/gtblnlibdx.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhoulong.xyz/Article/details/gtqkbdxawy.html

[N11] 二叉树中序遍历
来源：http://dali.xinyue.icu/Article/details/gttrtpjqdp.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.ehwqpu.com/Article/details/gttvekozvu.html

PHP:  // 手写递归函数
来源：http://dali.tanke756.top/Article/details/gtxasdxivd.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.snrcjt.cn/Article/details/gtcqlmpfre.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.guowangkeji.top/Article/details/gtgofuvgog.html

Java: // 手写递归
来源：http://dali.yuxming.cn/Article/details/gtveioutnb.html

Go:   // 手写递归
来源：http://dali.jiagoushi.top/Article/details/gtuvrttinr.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.jinqigufen.top/Article/details/gtzubovhpw.html

C#:   // 手写递归
来源：http://dali.daria6918.cn/Article/details/gthcmmrdan.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhoulong.xyz/Article/details/gtmnrdhzhf.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.wangdashe.top/Article/details/gtufrwymdn.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.sweek.top/Article/details/gttqrotgeg.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.aibaodan.cn/Article/details/gtbpptiyoz.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yj202588.top/Article/details/gttwbhgjlp.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.cucudq.cn/Article/details/gtxigaxesc.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.hongshengwenyu.top/Article/details/gtgrsieznu.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.jyoumei.cn/Article/details/gtroohodty.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.xziqi.cn/Article/details/gtfrchcycv.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtguukdkif.html

O. 并发与异步
来源：http://dali.daxiang520.top/Article/details/gtqszowclx.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtaatmybbe.html

[O01] 启动一个线程
来源：http://dali.chenlongwang.top/Article/details/gtwnowxlha.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfpiezgnw.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.yongpay.top/Article/details/gtbudpioeq.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.ehwqpu.com/Article/details/gtslyevmjq.html

TS:   // 同 JS
来源：http://dali.nwbrower.top/Article/details/gtewxbncmt.html

Java: new Thread(() -> f()).start()
来源：http://dali.ydzc1.top/Article/details/gtyvbdszxf.html

Go:   go f()
来源：http://dali.yuanzhike.top/Article/details/gtsiygrnzi.html

Ruby: Thread.new { f }
来源：http://dali.nwbrower.top/Article/details/gtqbedyrnt.html

C#:   Task.Run(() => F());
来源：http://dali.bjfxy.top/Article/details/gtbxgzrkfn.html

[O02] 使用线程池
来源：http://dali.pycfn.com/Article/details/gtemlragvf.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.ppjwa.cn/Article/details/gtvkilfjom.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.aibaodan.cn/Article/details/gtlhrhqyyz.html

JS:   // worker_threads 线程池
来源：http://dali.yj202588.top/Article/details/gtojvarivt.html

TS:   // worker_threads 线程池
来源：http://dali.zhongyouzk.top/Article/details/gtblkuqwrk.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.shangyingyoupin.top/Article/details/gtrosbdyjk.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhiwuduotai.top/Article/details/gtwgyklgmt.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.cheryme.top/Article/details/gtanbbiodw.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.sweek.top/Article/details/gtniqpijxb.html

[O03] 加锁保护共享数据
来源：http://dali.nwbrower.top/Article/details/gtthvhzqkb.html

Py:   with lock: shared += 1
来源：http://dali.0kj1m.cn/Article/details/gtqmbfbjip.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvvnldzgw.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhongyouzk.top/Article/details/gtodipmxhp.html

TS:   // 同 JS
来源：http://dali.c1oappe.top/Article/details/gtbqghztsk.html

Java: synchronized (this) { shared++; }
来源：http://dali.svipenyu.cn/Article/details/gtqbldjgoo.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.vqdsnc.cn/Article/details/gtorlfqgou.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.jyoumei.cn/Article/details/gtyrkpdxuk.html

C#:   lock (gate) { shared++; }
来源：http://dali.sysykeji.top/Article/details/gteosssnlu.html

[O04] 定义异步函数并等待
来源：http://dali.shuidangran.top/Article/details/gttsnmkmdc.html

Py:   async def f():⏎    await g()
来源：http://dali.xinyue.icu/Article/details/gtwirypcxb.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.redwolf501.top/Article/details/gtlrxkzbln.html

JS:   async function f() { await g(); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtfupzdwpg.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.nanxuanxn.top/Article/details/gthmeazsro.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.yvedp.cn/Article/details/gtavahtjgw.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhixingplan.top/Article/details/gtgxzoeius.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.smart0.xyz/Article/details/gtrdnbbkbt.html

C#:   async Task F() { await G(); }
来源：http://dali.gogol.net.cn/Article/details/gtqqpnaauv.html

[O05] 并发执行并等待全部完成
来源：http://dali.wangshuangyany.cn/Article/details/gtrxjnvvjh.html

Py:   asyncio.gather(*tasks)
来源：http://dali.xinyue.icu/Article/details/gtdvpktfnu.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbbqehmlt.html

JS:   await Promise.all(tasks)
来源：http://dali.cdnleiting.top/Article/details/gtrmieowaj.html

TS:   await Promise.all(tasks)
来源：http://dali.xuetiantiany.cn/Article/details/gtrvixpfsh.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.hongshengwenyu.top/Article/details/gtqukcouzu.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.yueranfly.top/Article/details/gthnhiilrq.html

Ruby: threads.map(&:join)
来源：http://dali.9152youxi.cn/Article/details/gtplktcsjz.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.meibo888.top/Article/details/gtgvfoznxd.html

[O06] 使用进程池
来源：http://dali.havefunace.top/Article/details/gtejppplnv.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.havefunace.top/Article/details/gtxtbtsjek.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.aibaodan.cn/Article/details/gtdkyqabcn.html

JS:   // child_process / cluster 模块
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpscyhsar.html

TS:   // child_process / cluster 模块
来源：http://dali.shuidangran.top/Article/details/gtbjotfata.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.tanke756.top/Article/details/gtugzrhjqq.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.gaohongyu789.top/Article/details/gtxygunzps.html

Ruby: // fork 块
来源：http://dali.jinyuanbaomall.cn/Article/details/gtisnebpep.html

C#:   Parallel.For
来源：http://dali.jinqigufen.top/Article/details/gtseoyvnpp.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gteenhkseg.html

P. 常用工具函数
来源：http://dali.fengsongda.top/Article/details/gtlxymvoja.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtaylbndjf.html

[P01] 生成 UUID
来源：http://dali.haohaochexian.top/Article/details/gtwvufzyii.html

Py:   str(uuid.uuid4())
来源：http://dali.aizwys.cn/Article/details/gtlszmapea.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.ivvv.top/Article/details/gtnryoucil.html

JS:   crypto.randomUUID()
来源：http://dali.yonumen.top/Article/details/gthccmwgse.html

TS:   crypto.randomUUID()
来源：http://dali.ybcxt.top/Article/details/gtcszclrss.html

Java: UUID.randomUUID().toString()
来源：http://dali.wangshuangyany.cn/Article/details/gtwbwzleyv.html

Go:   // 用 github.com/google/uuid
来源：http://dali.yuanzhike.top/Article/details/gtafdjqzdc.html

Ruby: SecureRandom.uuid
来源：http://dali.yuxming.cn/Article/details/gtouzvtwjk.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.yanxiufei.cn/Article/details/gtrxwgmdxp.html

[P02] MD5 / SHA256 摘要
来源：http://dali.snrcjt.cn/Article/details/gtwluqhsis.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.jiagoushi.top/Article/details/gtciblzxbj.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.nanxuanxn.top/Article/details/gtsfgfxfvx.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.shangyingyoupin.top/Article/details/gtvpxmiswa.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.ehwqpu.com/Article/details/gtwwqkagoj.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.pycfn.com/Article/details/gtseopxsdu.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.yonumen.top/Article/details/gtioiogsmq.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.xuetiantiany.cn/Article/details/gtoymtdupd.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwqmesavy.html

[P03] 生成短随机字符串
来源：http://dali.smart0.xyz/Article/details/gtupavksmc.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.tanke756.top/Article/details/gtzyakggxz.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.shzxlz.cn/Article/details/gtrotspqfp.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.hywenlv.cn/Article/details/gtevvfliip.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.iojbl.cn/Article/details/gtclvndbcs.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.chenlongwang.top/Article/details/gtgplykbiz.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gtxiltqvai.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhongyouzk.top/Article/details/gtadisygvu.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.jianghu66.top/Article/details/gtloagjusq.html

[P04] 求长度
来源：http://dali.hongshengwenyu.top/Article/details/gtutwqwqhw.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.tian-w.cn/Article/details/gttwrxfkie.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.shuidangran.top/Article/details/gtgtlaamif.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yj202588.top/Article/details/gtwxineotd.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.xuanzx.com/Article/details/gttirjpnrh.html

Java: list.size();  map.size();  s.length()
来源：http://dali.yuanzhike.top/Article/details/gteawssbqk.html

Go:   len(arr);  len(m)
来源：http://dali.shangyingyoupin.top/Article/details/gttljjypeh.html

Ruby: x.length;  x.size
来源：http://dali.guowangkeji.top/Article/details/gtzdfddruo.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.wangshuangyany.cn/Article/details/gtvmqierfw.html

[P05] 判断两个对象内容是否相等
来源：http://dali.316326.xyz/Article/details/gtiulecang.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.xuetiantiany.cn/Article/details/gtfeqbosuw.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbbwuqgax.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.guannengcc.top/Article/details/gthpqnkhkx.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.quarkkingdee.top/Article/details/gtrybxqfqc.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.xylfe.cn/Article/details/gtbkszqfkj.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.gogol.net.cn/Article/details/gtahppyutr.html

Ruby: a == b
来源：http://dali.zhixingplan.top/Article/details/gtluoyxdeu.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.snrcjt.cn/Article/details/gtmvnsfqqg.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.xylfe.cn/Article/details/gtjedhnkfx.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.jiagoushi.top/Article/details/gtoxievlww.html

PHP:  if (empty($x)) {}
来源：http://dali.sufxvd.cn/Article/details/gtfzkhtgcq.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.nanxinkj.top/Article/details/gtepqxychv.html

TS:   if (x == null) {}
来源：http://dali.ehwqpu.com/Article/details/gtanwdjvxq.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.chenzaomai.com/Article/details/gtixxabnfc.html

Go:   if x == nil {}
来源：http://dali.hfpthk.cn/Article/details/gttvogubdk.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.kuanghao11.cn/Article/details/gtufucomnm.html

C#:   if (x is null) {}
来源：http://dali.smart0.xyz/Article/details/gtqjcjtelr.html

[P07] 防抖与节流
来源：http://dali.kuanghao11.cn/Article/details/gtyjvydyrj.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.chenjidiqi.icu/Article/details/gtjwwglfyl.html

PHP:  // 手写时间戳比较
来源：http://dali.nwbrower.top/Article/details/gtjcqthpjo.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.nanxinkj.top/Article/details/gtdubvnfpe.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.svipenyu.cn/Article/details/gtikeqwwvm.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.hfpthk.cn/Article/details/gtuotwzwle.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.birdmap.top/Article/details/gtaywyskst.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.yj20258888.top/Article/details/gtazflgiff.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.cqqwz.cn/Article/details/gtxyepsilx.html

[P08] 处理浮点精度问题
来源：http://dali.xziqi.cn/Article/details/gtpzscwvvj.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.gzhubu.top/Article/details/gthrieiwkd.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.yvedp.cn/Article/details/gtswcbikwl.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.hywenlv.cn/Article/details/gtigltmlcf.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.jqgfzy.top/Article/details/gthvexkngu.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.mhx1999.top/Article/details/gtyeoamucq.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.meibo888.top/Article/details/gtivwzfqlo.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.yuanzhike.top/Article/details/gtnahcfyfz.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.chenlongwang.top/Article/details/gthiqrsrzb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtzgqwmlmm.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.yueranfly.top/Article/details/gtukpcinpf.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtoquoergz.html

[Q01] 创建表
来源：http://dali.aibaodan.cn/Article/details/gtlfharbdv.html

CREATE TABLE users (
来源：http://dali.jlsjyb.cn/Article/details/gtjkcsyroc.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.kuanghao11.cn/Article/details/gtnbeddwot.html

name VARCHAR(50) NOT NULL,
来源：http://dali.ybcxt.top/Article/details/gtnlemjaja.html

email VARCHAR(100) UNIQUE,
来源：http://dali.hnqzz.top/Article/details/gtjwijdcxc.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.pengpengdd.cyou/Article/details/gtrcnsiesa.html

);
来源：http://dali.zhijiandao.cn/Article/details/gtcnvhzeqp.html

[Q02] 创建带外键的表
来源：http://dali.daxiang520.top/Article/details/gtfwkqtgcb.html

CREATE TABLE orders (
来源：http://dali.jyoumei.cn/Article/details/gtivcqigbr.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jiagoushi.top/Article/details/gtmbfojufc.html

user_id INT NOT NULL,
来源：http://dali.zhengqikj.top/Article/details/gtujbynxdh.html

amount DECIMAL(10, 2),
来源：http://dali.snrcjt.cn/Article/details/gtbbjjqvsm.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.0kj1m.cn/Article/details/gthiqtojdq.html

);
来源：http://dali.zhoulong.xyz/Article/details/gtbieaviny.html

[Q03] 增加列
来源：http://dali.kuanghao11.cn/Article/details/gtisgybmjr.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.yongpay.top/Article/details/gtwlqsihcu.html

[Q04] 修改列类型
来源：http://dali.ppjwa.cn/Article/details/gtfvgqpivu.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.jinqigufen.top/Article/details/gtjqxajuzl.html

[Q05] 重命名列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmmrbztul.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.gzhubu.top/Article/details/gtyqrcrenn.html

[Q06] 删除列
来源：http://dali.mhx1999.top/Article/details/gtvyiudfnh.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zycfv.cn/Article/details/gtyjlgptii.html

[Q07] 删除表
来源：http://dali.zhoulong.xyz/Article/details/gtzrpsfmpk.html

DROP TABLE IF EXISTS orders;
来源：http://dali.sxryk.cn/Article/details/gtmsjzlnrz.html

[Q08] 创建普通索引
来源：http://dali.yongpay.top/Article/details/gtswgziafa.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.hammf.cn/Article/details/gtlhzwxsqq.html

[Q09] 创建唯一索引
来源：http://dali.hnqzz.top/Article/details/gtkbgrxkog.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.shanyushiyangtech.top/Article/details/gtmxmnzcfu.html

[Q10] 插入单行
来源：http://dali.cdnleiting.top/Article/details/gtwdigsfdx.html


<!-- 参考信息 -->