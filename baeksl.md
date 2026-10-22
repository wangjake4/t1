代发 wailian999

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhengqikj.top/Article/details/gtwhldqldt.html

JS:   console.error("err")
来源：http://dali.cucudq.cn/Article/details/gttktdolap.html

TS:   console.error("err")
来源：http://dali.cdnleiting.top/Article/details/gtqgxxyrid.html

Java: System.err.println("err")
来源：http://dali.xziqi.cn/Article/details/gtypjaayhg.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.0kj1m.cn/Article/details/gtkuhddosb.html

Ruby: warn "err"
来源：http://dali.gzhubu.top/Article/details/gtepctloka.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.shanyushiyangtech.top/Article/details/gtahovqwke.html

[M07] 判断是否为主入口
来源：http://dali.sweek.top/Article/details/gttlaybmud.html

Py:   if __name__ == "__main__":
来源：http://dali.jlsjyb.cn/Article/details/gtncnybfda.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.chenzaomai.com/Article/details/gtsdhouhql.html

JS:   require.main === module
来源：http://dali.chenlongwang.top/Article/details/gtxrrbyzkp.html

TS:   require.main === module
来源：http://dali.jqgufenzy.top/Article/details/gtmqrmpjyw.html

Java: public static void main(String[] args)
来源：http://dali.aibaodan.cn/Article/details/gtuadqzefe.html

Go:   func main()
来源：http://dali.nwbrower.top/Article/details/gtkoeaunfd.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.sxryk.cn/Article/details/gtttkhuccc.html

C#:   static void Main(string[] args)
来源：http://dali.zhiwuduotai.top/Article/details/gtnvraribn.html

[M08] 获取系统与运行时信息
来源：http://dali.hongshengwenyu.top/Article/details/gtzarthfhr.html

Py:   platform.system();  platform.python_version()
来源：http://dali.xziqi.cn/Article/details/gtmbqlrypt.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.tianlin.xyz/Article/details/gtcfhgvdbt.html

JS:   process.platform;  process.version
来源：http://dali.yangfankeji.com/Article/details/gtttuftypt.html

TS:   process.platform;  process.version
来源：http://dali.yueranfly.top/Article/details/gtqzxbxpch.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.dianchejie.cn/Article/details/gtauileivq.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.snrcjt.cn/Article/details/gtiypfsswy.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.guannengcc.top/Article/details/gtqtcoumeo.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.sysykeji.top/Article/details/gtbykjzaoj.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtykbrqjbm.html

N. 数据结构与算法
来源：http://dali.ivvv.top/Article/details/gtdcmauefu.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuxbhzaqe.html

[N01] 二分查找（有序数组）
来源：http://dali.wangshuangyany.cn/Article/details/gtmbbwgyvj.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.xuanzx.com/Article/details/gtfteqohab.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.jiagoushi.top/Article/details/gtxwrdjzeo.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.smart0.xyz/Article/details/gtdmtmdscw.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hammf.cn/Article/details/gtbhxbxach.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfakwcsfj.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.jiagoushi.top/Article/details/gtdiyrrfba.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.birdmap.top/Article/details/gtgsrtvfcv.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.ydzc1.top/Article/details/gtvynwpzst.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.yj20258.top/Article/details/gtzfbltfev.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jinqigfzy.top/Article/details/gtrpaxhkub.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.nwbrower.top/Article/details/gtfvgfutbn.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.smart0.xyz/Article/details/gtazixzudc.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.ydzc1.top/Article/details/gtwbskjvja.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.haohaochexian.top/Article/details/gtuhsurvvs.html

Go:   slices.Sort(arr)
来源：http://dali.gogol.net.cn/Article/details/gtanswkief.html

Ruby: arr.sort
来源：http://dali.shanyushiyangtech.top/Article/details/gtqugrpnkv.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.nanxuanxn.top/Article/details/gtjosngmjt.html

[N03] 快速排序（分治示例）
来源：http://dali.shzxlz.cn/Article/details/gtgegoxoph.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.havefunace.top/Article/details/gtwcsnztmb.html

PHP:  // 递归实现，或用 usort
来源：http://dali.aizwys.cn/Article/details/gtyliyiddh.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.shanyushiyangtech.top/Article/details/gtqpbsopjc.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jinghuilouyu.cn/Article/details/gtnijvakas.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.cheryme.top/Article/details/gtacfojels.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zdqjudy.top/Article/details/gtflnpkabj.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.ivvv.top/Article/details/gtvmddxzpf.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.yanxiufei.cn/Article/details/gtogygkrjc.html

[N04] 斐波那契数列
来源：http://dali.birdmap.top/Article/details/gtqizxskjm.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.yueranfly.top/Article/details/gtxpyrnrez.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.fzhhl.top/Article/details/gtfjwzbvot.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jyoumei.cn/Article/details/gtfnvikptt.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jqgufenzy.top/Article/details/gtrxlfpxec.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.jqgufenzy.top/Article/details/gtgmxlvubb.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.andypj.xyz/Article/details/gtcamufjkx.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.shangyingyoupin.top/Article/details/gtpglgakbj.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.sxryk.cn/Article/details/gttkxceymo.html

[N05] 最大公约数
来源：http://dali.havefunace.top/Article/details/gtmquojsyn.html

Py:   math.gcd(a, b)
来源：http://dali.shuidangran.top/Article/details/gtsxunugqz.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.pycfn.com/Article/details/gtayiwzstp.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrhdglvdt.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jianghu66.top/Article/details/gtwzgrtnsm.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.jinqigfzy.top/Article/details/gtknwugyrq.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.chenzaomai.com/Article/details/gtsbxmymqk.html

Ruby: a.gcd(b)
来源：http://dali.hnqzz.top/Article/details/gtpkckbvqz.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.nanxinkj.top/Article/details/gtelrumzbh.html

[N06] 判断回文字符串
来源：http://dali.bjfxy.top/Article/details/gtkxkhqckq.html

Py:   s == s[::-1]
来源：http://dali.chenzaomai.com/Article/details/gtodqvpnzo.html

PHP:  $s === strrev($s);
来源：http://dali.guowangkeji.top/Article/details/gtfrkazruf.html

JS:   s === [...s].reverse().join("")
来源：http://dali.dianchejie.cn/Article/details/gtibssfutn.html

TS:   s === [...s].reverse().join("")
来源：http://dali.ybcxt.top/Article/details/gtdlfyzgni.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.andypj.xyz/Article/details/gtkljolfla.html

Go:   // 双指针从两端比较
来源：http://dali.nanxuanxn.top/Article/details/gtwdlwdfms.html

Ruby: s == s.reverse
来源：http://dali.sxryk.cn/Article/details/gtsljcqvtd.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.sxryk.cn/Article/details/gtctblsuya.html

[N07] 两数之和（返回下标）
来源：http://dali.shzxlz.cn/Article/details/gtunddqwor.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.nanxuanxn.top/Article/details/gtyhjfnaaf.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.ybcxt.top/Article/details/gtsgwlsowm.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.snrcjt.cn/Article/details/gtzfnlsuik.html

TS:   // 手写 Map<string, number>
来源：http://dali.zycfv.cn/Article/details/gtxcepampc.html

Java: // 手写 HashMap
来源：http://dali.jinqigfzy.top/Article/details/gtsykewahp.html

Go:   // 手写 map[int]int
来源：http://dali.fzhhl.top/Article/details/gtlcmipuym.html

Ruby: // 手写 Hash
来源：http://dali.yj20258.top/Article/details/gtjuypbnxp.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.meibo888.top/Article/details/gtjpaohklm.html

[N08] 生成全排列
来源：http://dali.quarkkingdee.top/Article/details/gtsikehpcn.html

Py:   itertools.permutations(arr)
来源：http://dali.zhiwuduotai.top/Article/details/gtymracyls.html

PHP:  // 手写递归交换
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwjltsded.html

JS:   // 手写回溯递归
来源：http://dali.jinqigfzy.top/Article/details/gtgllhgntr.html

TS:   // 手写回溯递归
来源：http://dali.hysaishi.cn/Article/details/gtddnvrbjy.html

Java: // 手写回溯递归
来源：http://dali.feifeiyinyue.top/Article/details/gtvbxclryz.html

Go:   // 手写回溯递归
来源：http://dali.jlsjyb.cn/Article/details/gtuiyzkhzl.html

Ruby: arr.permutation.to_a
来源：http://dali.fzhhl.top/Article/details/gtxwhobvjg.html

C#:   // 手写回溯递归
来源：http://dali.kuanghao11.cn/Article/details/gtirtdqxyz.html

[N09] 栈与队列
来源：http://dali.yuxming.cn/Article/details/gtxaizhuon.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.sxryk.cn/Article/details/gtajzwctya.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhiwuduotai.top/Article/details/gtcsxpmtkl.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.pycfn.com/Article/details/gttznqwczv.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.chenjidiqi.icu/Article/details/gtjzgvhoxd.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.tanke756.top/Article/details/gtbtvbqecn.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.guannengcc.top/Article/details/gtdkblxtgi.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.guowangkeji.top/Article/details/gtfxcleyau.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.xziqi.cn/Article/details/gtbdyodrfu.html

[N10] 链表节点定义
来源：http://dali.ybcxt.top/Article/details/gtmbglnvkk.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.jlsjyb.cn/Article/details/gtomhgnrmn.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.kuanghao11.cn/Article/details/gtdytabnta.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.yvedp.cn/Article/details/gtrobaemci.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.birdmap.top/Article/details/gtuigoiqar.html

Java: class Node { int v; Node next; }
来源：http://dali.xziqi.cn/Article/details/gtvyykwxyw.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.nwbrower.top/Article/details/gtllgcvhyu.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.yuanzhike.top/Article/details/gtijghjblx.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.quarkkingdee.top/Article/details/gtdicspnoz.html

[N11] 二叉树中序遍历
来源：http://dali.daxiang520.top/Article/details/gtyiarjqtw.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.9152youxi.cn/Article/details/gtgjekvlnk.html

PHP:  // 手写递归函数
来源：http://dali.tanke756.top/Article/details/gtnliitamn.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.xziqi.cn/Article/details/gtmgpwbziu.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhengqikj.top/Article/details/gttisjlulw.html

Java: // 手写递归
来源：http://dali.c1oappe.top/Article/details/gtdrciaurc.html

Go:   // 手写递归
来源：http://dali.gaohongyu789.top/Article/details/gtxadwmcgo.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.shuidangran.top/Article/details/gtovgkeqqx.html

C#:   // 手写递归
来源：http://dali.yj202588.top/Article/details/gtnunibfzr.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.gogol.net.cn/Article/details/gtedkxokja.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.jinghuilouyu.cn/Article/details/gtkjwwjndd.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.hammf.cn/Article/details/gtqghgffqj.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoozyzylm.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yvedp.cn/Article/details/gtweqcyjtd.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.gzhubu.top/Article/details/gtregozace.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.hammf.cn/Article/details/gtlqlcaods.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zdqjudy.top/Article/details/gtiqebtiyz.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.nanxuanxn.top/Article/details/gtphqtlmiy.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtvbgzlxim.html

O. 并发与异步
来源：http://dali.ivvv.top/Article/details/gttvjuqxoq.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtddjogofn.html

[O01] 启动一个线程
来源：http://dali.dashuyun.cn/Article/details/gtqkdlfwth.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.xuanzx.com/Article/details/gtokbtdfix.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.daria6918.cn/Article/details/gtjibiypzg.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.shangyingyoupin.top/Article/details/gtwrmaypgi.html

TS:   // 同 JS
来源：http://dali.jlsjyb.cn/Article/details/gttiqudvav.html

Java: new Thread(() -> f()).start()
来源：http://dali.meibo888.top/Article/details/gtjfwucrlj.html

Go:   go f()
来源：http://dali.nanxuanxn.top/Article/details/gtlkhyxrae.html

Ruby: Thread.new { f }
来源：http://dali.snrcjt.cn/Article/details/gtyovnjlzd.html

C#:   Task.Run(() => F());
来源：http://dali.gogol.net.cn/Article/details/gtvdzoftpw.html

[O02] 使用线程池
来源：http://dali.tanke756.top/Article/details/gtysmlyibf.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.nanxinkj.top/Article/details/gtzdtoncha.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.jinqigufen.top/Article/details/gtjudlueee.html

JS:   // worker_threads 线程池
来源：http://dali.zhengqikj.top/Article/details/gtpstkwulx.html

TS:   // worker_threads 线程池
来源：http://dali.316326.xyz/Article/details/gtdfezqqma.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.yj20258888.top/Article/details/gtydpyuemf.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.chenzaomai.com/Article/details/gtivrbickb.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.tian-w.cn/Article/details/gtwawmntiq.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.yanxiufei.cn/Article/details/gtcakyzrwm.html

[O03] 加锁保护共享数据
来源：http://dali.yuxming.cn/Article/details/gtmchmnprr.html

Py:   with lock: shared += 1
来源：http://dali.shangyingyoupin.top/Article/details/gtazcfnxrw.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.fengsongda.top/Article/details/gtxdjxpeem.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.andypj.xyz/Article/details/gtgepeqhlk.html

TS:   // 同 JS
来源：http://dali.cdnleiting.top/Article/details/gtyzucvhxx.html

Java: synchronized (this) { shared++; }
来源：http://dali.hammf.cn/Article/details/gtkgdoegdg.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.hongshengwenyu.top/Article/details/gtlwacbanb.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.yvedp.cn/Article/details/gtkfxmphgc.html

C#:   lock (gate) { shared++; }
来源：http://dali.nanxinkj.top/Article/details/gtcqygysaj.html

[O04] 定义异步函数并等待
来源：http://dali.sysykeji.top/Article/details/gttthvyegp.html

Py:   async def f():⏎    await g()
来源：http://dali.zhengqikj.top/Article/details/gtdcxawrdh.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.jyoumei.cn/Article/details/gtzfbfgwiz.html

JS:   async function f() { await g(); }
来源：http://dali.hongshengwenyu.top/Article/details/gtqtikpmtz.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.yuxming.cn/Article/details/gtoyeebild.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.wangdashe.top/Article/details/gtuzgowzhh.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.shanyushiyangtech.top/Article/details/gthrllqnfn.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.316326.xyz/Article/details/gtybehunjo.html

C#:   async Task F() { await G(); }
来源：http://dali.dianchejie.cn/Article/details/gtdhlphofd.html

[O05] 并发执行并等待全部完成
来源：http://dali.mhx1999.top/Article/details/gtlbvdteni.html

Py:   asyncio.gather(*tasks)
来源：http://dali.iojbl.cn/Article/details/gtytouysmr.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.gzhubu.top/Article/details/gtavmhsrrf.html

JS:   await Promise.all(tasks)
来源：http://dali.yj20258.top/Article/details/gtdnrwsyxl.html

TS:   await Promise.all(tasks)
来源：http://dali.yangfankeji.com/Article/details/gthejcbryf.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zycfv.cn/Article/details/gtzwdsqzru.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.hnxiangtu.top/Article/details/gtjtiyftqx.html

Ruby: threads.map(&:join)
来源：http://dali.zhoulong.xyz/Article/details/gtxmdgadxi.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.9152youxi.cn/Article/details/gtqdokmrar.html

[O06] 使用进程池
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrhwxehku.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.fzhhl.top/Article/details/gtydlqiocd.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.havefunace.top/Article/details/gtwxspafeg.html

JS:   // child_process / cluster 模块
来源：http://dali.haohaochexian.top/Article/details/gtrfqvfute.html

TS:   // child_process / cluster 模块
来源：http://dali.xziqi.cn/Article/details/gtlzhkwaht.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.aibaodan.cn/Article/details/gtophhgyey.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.andypj.xyz/Article/details/gtuflmqxfo.html

Ruby: // fork 块
来源：http://dali.aizwys.cn/Article/details/gtyemmsuqq.html

C#:   Parallel.For
来源：http://dali.yj20258.top/Article/details/gtamenqnjz.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtamzmbyqa.html

P. 常用工具函数
来源：http://dali.havefunace.top/Article/details/gtqtwynxak.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtlcbwtans.html

[P01] 生成 UUID
来源：http://dali.yanxiufei.cn/Article/details/gtotvpeoww.html

Py:   str(uuid.uuid4())
来源：http://dali.yvedp.cn/Article/details/gtmgerpyln.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.chenjidiqi.icu/Article/details/gthuwvaxqd.html

JS:   crypto.randomUUID()
来源：http://dali.xylfe.cn/Article/details/gtfltrwjfo.html

TS:   crypto.randomUUID()
来源：http://dali.aibaodan.cn/Article/details/gtcsmzrnwm.html

Java: UUID.randomUUID().toString()
来源：http://dali.jinqigufen.top/Article/details/gtchbgpfdj.html

Go:   // 用 github.com/google/uuid
来源：http://dali.jianghu66.top/Article/details/gtnzltyxtd.html

Ruby: SecureRandom.uuid
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnfjfjxej.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.tanke756.top/Article/details/gtkqnivlvs.html

[P02] MD5 / SHA256 摘要
来源：http://dali.yonumen.top/Article/details/gtikunpwxw.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.sysykeji.top/Article/details/gtayzixtpj.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.feifeiyinyue.top/Article/details/gtoyjlajlf.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.gzhubu.top/Article/details/gtraxcipfl.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.chenjidiqi.icu/Article/details/gtqirnqtaa.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqqvgrxbm.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.dianchejie.cn/Article/details/gtxbitnmoe.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.yuxming.cn/Article/details/gtpblaehaj.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.0kj1m.cn/Article/details/gteavxshxw.html

[P03] 生成短随机字符串
来源：http://dali.jinyuanbaomall.cn/Article/details/gtegewsozx.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.ivvv.top/Article/details/gthaqmtueh.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.jinqigufen.top/Article/details/gtikrlsdkj.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.fengsongda.top/Article/details/gtmwiqbxnu.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.hywenlv.cn/Article/details/gtziljodxx.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.tian-w.cn/Article/details/gtgwvfbgji.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.wangdashe.top/Article/details/gtqtrzryza.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.tian-w.cn/Article/details/gtjetbymxn.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gtlzddkuua.html

[P04] 求长度
来源：http://dali.dianchejie.cn/Article/details/gtxypldqwo.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.wangdashe.top/Article/details/gtjqcnxgsu.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.dianchejie.cn/Article/details/gtzbfjtfqb.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.hywenlv.cn/Article/details/gtehxhrurh.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.chenlongwang.top/Article/details/gttimrjqvl.html

Java: list.size();  map.size();  s.length()
来源：http://dali.yuanzhike.top/Article/details/gtxyjiswxv.html

Go:   len(arr);  len(m)
来源：http://dali.quarkkingdee.top/Article/details/gtrdbecbwg.html

Ruby: x.length;  x.size
来源：http://dali.jinqigfzy.top/Article/details/gtibuszlwx.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.guannengcc.top/Article/details/gtuqysgjmn.html

[P05] 判断两个对象内容是否相等
来源：http://dali.nwbrower.top/Article/details/gtocaxoxaz.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.wangshuangyany.cn/Article/details/gtupnoniow.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.wangdashe.top/Article/details/gtquqqflpi.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.xinyue.icu/Article/details/gtfzjlyhix.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.xuetiantiany.cn/Article/details/gtdtfnbamp.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.tanke756.top/Article/details/gthbignbwv.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhongyouzk.top/Article/details/gtugojhvcn.html

Ruby: a == b
来源：http://dali.cheryme.top/Article/details/gthymjjspq.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.0kj1m.cn/Article/details/gtpkhexcai.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.guowangkeji.top/Article/details/gtjgvfcmpd.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.dashuyun.cn/Article/details/gtmggniquk.html

PHP:  if (empty($x)) {}
来源：http://dali.sxryk.cn/Article/details/gtqqxenerm.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.nwbrower.top/Article/details/gtscjtudda.html

TS:   if (x == null) {}
来源：http://dali.zhiwuduotai.top/Article/details/gtrnjclkzs.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtggxouoxe.html

Go:   if x == nil {}
来源：http://dali.sxryk.cn/Article/details/gtizkpkhri.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.cheryme.top/Article/details/gtenyfmqaz.html

C#:   if (x is null) {}
来源：http://dali.gogol.net.cn/Article/details/gtoawxmlhu.html

[P07] 防抖与节流
来源：http://dali.zhoulong.xyz/Article/details/gtxfulhrvg.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.fengsongda.top/Article/details/gtdzfnxeeo.html

PHP:  // 手写时间戳比较
来源：http://dali.fengsongda.top/Article/details/gtpecrllyo.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jinqigfzy.top/Article/details/gtwfojcuuu.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.cucudq.cn/Article/details/gtzjzmduez.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.cheryme.top/Article/details/gtiiajreog.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.fzhhl.top/Article/details/gtgdhejoyg.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.nanxinkj.top/Article/details/gtavnlwzhv.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgbzfksmd.html

[P08] 处理浮点精度问题
来源：http://dali.jinghuilouyu.cn/Article/details/gttlgdnbyj.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.chenzaomai.com/Article/details/gtgrlvlugo.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.gogol.net.cn/Article/details/gtbwwyvoir.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.hnqzz.top/Article/details/gtwwglrsch.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.0kj1m.cn/Article/details/gtdbsmexyt.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.iojbl.cn/Article/details/gtpdqjpsit.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.daria6918.cn/Article/details/gtmeckbqke.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.ydzc1.top/Article/details/gtanaglztg.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.sweek.top/Article/details/gthrgzzyjw.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtrvseogsg.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.birdmap.top/Article/details/gtrwmivaud.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtrurbnbmf.html

[Q01] 创建表
来源：http://dali.sweek.top/Article/details/gtywgvfgri.html

CREATE TABLE users (
来源：http://dali.yonumen.top/Article/details/gtncggjgqm.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.feifeiyinyue.top/Article/details/gtjyzqomds.html

name VARCHAR(50) NOT NULL,
来源：http://dali.jqgfzy.top/Article/details/gtncivxkoc.html

email VARCHAR(100) UNIQUE,
来源：http://dali.hnxiangtu.top/Article/details/gtuyiuwczz.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.316326.xyz/Article/details/gtohcgbhoz.html

);
来源：http://dali.yvedp.cn/Article/details/gtsbzumesu.html

[Q02] 创建带外键的表
来源：http://dali.jyoumei.cn/Article/details/gtilcsqjke.html

CREATE TABLE orders (
来源：http://dali.zhiwuduotai.top/Article/details/gthsblalwy.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yueranfly.top/Article/details/gtvbspxyyu.html

user_id INT NOT NULL,
来源：http://dali.yonumen.top/Article/details/gtyydvqmoe.html

amount DECIMAL(10, 2),
来源：http://dali.hywenlv.cn/Article/details/gtkbbezeud.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.ivvv.top/Article/details/gtytjtxyup.html

);
来源：http://dali.hnxiangtu.top/Article/details/gtttwickzz.html

[Q03] 增加列
来源：http://dali.sysykeji.top/Article/details/gtuiarklvx.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.feifeiyinyue.top/Article/details/gtnjclxyon.html

[Q04] 修改列类型
来源：http://dali.shangyingyoupin.top/Article/details/gtxwvmswqm.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.jinqigufen.top/Article/details/gtkkifgcrc.html

[Q05] 重命名列
来源：http://dali.cdnleiting.top/Article/details/gtqjcsoswn.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.andypj.xyz/Article/details/gtloodpphq.html

[Q06] 删除列
来源：http://dali.fengsongda.top/Article/details/gtpauaelxy.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoydendqz.html

[Q07] 删除表
来源：http://dali.sweek.top/Article/details/gtekourmwp.html

DROP TABLE IF EXISTS orders;
来源：http://dali.cucudq.cn/Article/details/gtrmygvlbx.html

[Q08] 创建普通索引
来源：http://dali.yangfankeji.com/Article/details/gtxpozqyks.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.shanyushiyangtech.top/Article/details/gtukkoqlat.html

[Q09] 创建唯一索引
来源：http://dali.tianlin.xyz/Article/details/gtewckzygk.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.yuxming.cn/Article/details/gtbenqogpn.html

[Q10] 插入单行
来源：http://dali.tanke756.top/Article/details/gtbelorqnx.html


<!-- 参考信息 -->