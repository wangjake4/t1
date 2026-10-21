代发 wailian999

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhengqikj.top/Article/details/gtybiancgv.html

Ruby: warn "err"
来源：http://dali.cqqwz.cn/Article/details/gtwhmnllbg.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.xziqi.cn/Article/details/gtuzfzkfbi.html

[M07] 判断是否为主入口
来源：http://dali.guannengcc.top/Article/details/gtjrczgbqm.html

Py:   if __name__ == "__main__":
来源：http://dali.yonumen.top/Article/details/gtxzrwielt.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.bjfxy.top/Article/details/gtxbloashs.html

JS:   require.main === module
来源：http://dali.xinyue.icu/Article/details/gthvwcsrkk.html

TS:   require.main === module
来源：http://dali.jinyuanbaomall.cn/Article/details/gthbjtbffh.html

Java: public static void main(String[] args)
来源：http://dali.meibo888.top/Article/details/gtpgdnzzwe.html

Go:   func main()
来源：http://dali.xuanzx.com/Article/details/gturlcevxi.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.guowangkeji.top/Article/details/gthcpagxog.html

C#:   static void Main(string[] args)
来源：http://dali.guowangkeji.top/Article/details/gtwoxlkcoj.html

[M08] 获取系统与运行时信息
来源：http://dali.cheryme.top/Article/details/gtndufygfa.html

Py:   platform.system();  platform.python_version()
来源：http://dali.yuxming.cn/Article/details/gtkpzdvoqr.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.jqgufenzy.top/Article/details/gtdhvktruk.html

JS:   process.platform;  process.version
来源：http://dali.aibaodan.cn/Article/details/gtvvmqqbtg.html

TS:   process.platform;  process.version
来源：http://dali.316326.xyz/Article/details/gtbajcijnu.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhongyouzk.top/Article/details/gtpzzwvolz.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.sufxvd.cn/Article/details/gtjanbbwim.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.nanxuanxn.top/Article/details/gtcapeslzm.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.jinqigufen.top/Article/details/gtpxlkoylq.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtqglfumvj.html

N. 数据结构与算法
来源：http://dali.yvedp.cn/Article/details/gtlhsnewcw.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtpqlmhapa.html

[N01] 二分查找（有序数组）
来源：http://dali.jinghuilouyu.cn/Article/details/gtvocqlvvo.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.shanyushiyangtech.top/Article/details/gtudxhaxlj.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.xinyue.icu/Article/details/gtlhennrqn.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jianghu66.top/Article/details/gtrwjvncbw.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.mhx1999.top/Article/details/gtywgwoizx.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.nwbrower.top/Article/details/gtthtgingq.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.shanyushiyangtech.top/Article/details/gtukttawrk.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.chenjidiqi.icu/Article/details/gthxsbidqs.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhixingplan.top/Article/details/gtydbezsgo.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.xinyue.icu/Article/details/gtbmkryqkl.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.gogol.net.cn/Article/details/gtyqmmclaf.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.yj202588.top/Article/details/gtnsobtrjn.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.bjfxy.top/Article/details/gtlfnrebwk.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaxglbwpd.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.jiagoushi.top/Article/details/gtnctqglwm.html

Go:   slices.Sort(arr)
来源：http://dali.hnqzz.top/Article/details/gtjpnodohx.html

Ruby: arr.sort
来源：http://dali.sxryk.cn/Article/details/gtauivtfxh.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.jqgfzy.top/Article/details/gtiixfbkyt.html

[N03] 快速排序（分治示例）
来源：http://dali.zhengqikj.top/Article/details/gttwhuyptm.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.shzxlz.cn/Article/details/gtecvzcqoi.html

PHP:  // 递归实现，或用 usort
来源：http://dali.hfpthk.cn/Article/details/gtmwyaekmu.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.wangshuangyany.cn/Article/details/gtmjyakekr.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.hammf.cn/Article/details/gtsufodhsa.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.cdnleiting.top/Article/details/gtsnuvqhjt.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.ehwqpu.com/Article/details/gtdhabtosg.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.sweek.top/Article/details/gtpptkbjin.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.svipenyu.cn/Article/details/gtpdatczjp.html

[N04] 斐波那契数列
来源：http://dali.havefunace.top/Article/details/gthxckwldn.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.hammf.cn/Article/details/gtbvkrfjsc.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.chenjidiqi.icu/Article/details/gtfkaoxlfr.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yanxiufei.cn/Article/details/gtuqtdterp.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zdqjudy.top/Article/details/gtfnlgfxpd.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.snrcjt.cn/Article/details/gtshxyoiuo.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.yueranfly.top/Article/details/gtxdkmtaww.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zycfv.cn/Article/details/gtuxuegaht.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.feifeiyinyue.top/Article/details/gttouigjvk.html

[N05] 最大公约数
来源：http://dali.hnxiangtu.top/Article/details/gtjyqlezla.html

Py:   math.gcd(a, b)
来源：http://dali.jianghu66.top/Article/details/gtzartqqnb.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.c1oappe.top/Article/details/gtdcxhbwsa.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgewoexgo.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.fzhhl.top/Article/details/gtmbtuxsdl.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhongyouzk.top/Article/details/gtgwoqylun.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.cashguo.top/Article/details/gtwyzovamh.html

Ruby: a.gcd(b)
来源：http://dali.ybcxt.top/Article/details/gtldffzgyn.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.yueranfly.top/Article/details/gtzegrdadn.html

[N06] 判断回文字符串
来源：http://dali.svipenyu.cn/Article/details/gtguspyppn.html

Py:   s == s[::-1]
来源：http://dali.hywenlv.cn/Article/details/gtntfcsxod.html

PHP:  $s === strrev($s);
来源：http://dali.iojbl.cn/Article/details/gtnntaiblv.html

JS:   s === [...s].reverse().join("")
来源：http://dali.cdnleiting.top/Article/details/gtnuiwlzvb.html

TS:   s === [...s].reverse().join("")
来源：http://dali.guannengcc.top/Article/details/gthkdpocue.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.cqqwz.cn/Article/details/gtjkcdhuhn.html

Go:   // 双指针从两端比较
来源：http://dali.fzhhl.top/Article/details/gtpiuacefb.html

Ruby: s == s.reverse
来源：http://dali.pycfn.com/Article/details/gtwwnqvozp.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.pycfn.com/Article/details/gtyaacxcuq.html

[N07] 两数之和（返回下标）
来源：http://dali.pengpengdd.cyou/Article/details/gtrckbsvit.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.daria6918.cn/Article/details/gtdajmacrt.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.jinyuanbaomall.cn/Article/details/gthuhrkwdh.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.ybcxt.top/Article/details/gteexaictu.html

TS:   // 手写 Map<string, number>
来源：http://dali.dianchejie.cn/Article/details/gtxyiwuceu.html

Java: // 手写 HashMap
来源：http://dali.gotoacloud.top/Article/details/gtxfxrifva.html

Go:   // 手写 map[int]int
来源：http://dali.ppjwa.cn/Article/details/gtxydccgdc.html

Ruby: // 手写 Hash
来源：http://dali.zhongyouzk.top/Article/details/gtamdcdvwh.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.xuetiantiany.cn/Article/details/gtfrqskzev.html

[N08] 生成全排列
来源：http://dali.vqdsnc.cn/Article/details/gtupbpfces.html

Py:   itertools.permutations(arr)
来源：http://dali.yongpay.top/Article/details/gtfscfwmga.html

PHP:  // 手写递归交换
来源：http://dali.zhongyouzk.top/Article/details/gtllqtvnuq.html

JS:   // 手写回溯递归
来源：http://dali.smart0.xyz/Article/details/gtpjnaoeiu.html

TS:   // 手写回溯递归
来源：http://dali.chenzaomai.com/Article/details/gtfankfhou.html

Java: // 手写回溯递归
来源：http://dali.gzhubu.top/Article/details/gtycocxmzh.html

Go:   // 手写回溯递归
来源：http://dali.feifeiyinyue.top/Article/details/gtiprxxqig.html

Ruby: arr.permutation.to_a
来源：http://dali.zhoulong.xyz/Article/details/gtjofrmlyb.html

C#:   // 手写回溯递归
来源：http://dali.zhixingplan.top/Article/details/gtebnvenlg.html

[N09] 栈与队列
来源：http://dali.cqqwz.cn/Article/details/gtahdkxace.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.shzxlz.cn/Article/details/gttwfmrhdo.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.hnxiangtu.top/Article/details/gtobtagfbx.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.yuxming.cn/Article/details/gthgjdkubi.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.jiagoushi.top/Article/details/gtbtpjqlbe.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.tian-w.cn/Article/details/gtzpfleosr.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiozzmqju.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.nanxuanxn.top/Article/details/gtzsvusyrl.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.mhx1999.top/Article/details/gturcltqkt.html

[N10] 链表节点定义
来源：http://dali.zycfv.cn/Article/details/gttukzevpi.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhaomingkeji.xyz/Article/details/gthfgkbxvx.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.smart0.xyz/Article/details/gtqsuhoych.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.bjfxy.top/Article/details/gtdbtdkckk.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.aizwys.cn/Article/details/gtjgouvtww.html

Java: class Node { int v; Node next; }
来源：http://dali.xylfe.cn/Article/details/gtuxqtsijp.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.gogol.net.cn/Article/details/gtebyjwwkr.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.havefunace.top/Article/details/gtmbcxahym.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.snrcjt.cn/Article/details/gteytqiqth.html

[N11] 二叉树中序遍历
来源：http://dali.gzhubu.top/Article/details/gtqphxqadw.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.ywan-chungtsiang.top/Article/details/gthzuccsco.html

PHP:  // 手写递归函数
来源：http://dali.quarkkingdee.top/Article/details/gtqfubgsjl.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.nanxuanxn.top/Article/details/gtedefggnw.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.havefunace.top/Article/details/gtowvtfqkt.html

Java: // 手写递归
来源：http://dali.tianlin.xyz/Article/details/gtxlwwxrqz.html

Go:   // 手写递归
来源：http://dali.hnqzz.top/Article/details/gtblhcciib.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.c1oappe.top/Article/details/gtwmxlazur.html

C#:   // 手写递归
来源：http://dali.chenlongwang.top/Article/details/gteegvxppq.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.xinyue.icu/Article/details/gtaeomuazp.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtykrrzbvu.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgwnprhvl.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.kuanghao11.cn/Article/details/gtyeicnlup.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhengqikj.top/Article/details/gtymhyhtpa.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.sxryk.cn/Article/details/gtubgoband.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlpvjcigm.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhengqikj.top/Article/details/gtvavydcwt.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.pengpengdd.cyou/Article/details/gtzvahvczi.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxgtwrgjr.html

O. 并发与异步
来源：http://dali.jinqigfzy.top/Article/details/gtmkdthnnw.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtpgtwkmkk.html

[O01] 启动一个线程
来源：http://dali.yj20258.top/Article/details/gtsjjdgqmy.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.hfpthk.cn/Article/details/gtaxmqzvrm.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.daria6918.cn/Article/details/gtlhorcojc.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhengqikj.top/Article/details/gtqcfvctiz.html

TS:   // 同 JS
来源：http://dali.redwolf501.top/Article/details/gtmialrvds.html

Java: new Thread(() -> f()).start()
来源：http://dali.yuxming.cn/Article/details/gtiedtcyli.html

Go:   go f()
来源：http://dali.hysaishi.cn/Article/details/gtshtmisuh.html

Ruby: Thread.new { f }
来源：http://dali.316326.xyz/Article/details/gtcmerqpbx.html

C#:   Task.Run(() => F());
来源：http://dali.ehwqpu.com/Article/details/gtvursvtug.html

[O02] 使用线程池
来源：http://dali.hysaishi.cn/Article/details/gtnbifxtvo.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.chenjidiqi.icu/Article/details/gtlwjpfxru.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.yj20258.top/Article/details/gttyslokty.html

JS:   // worker_threads 线程池
来源：http://dali.chenjidiqi.icu/Article/details/gtanoyffbn.html

TS:   // worker_threads 线程池
来源：http://dali.daxiang520.top/Article/details/gtonzjzwyy.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.hammf.cn/Article/details/gtmbejdvik.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.havefunace.top/Article/details/gtzvuzpkqt.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.jianghu66.top/Article/details/gtdniiwwcg.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.gzhubu.top/Article/details/gtroxayprz.html

[O03] 加锁保护共享数据
来源：http://dali.jqgufenzy.top/Article/details/gtyieatdps.html

Py:   with lock: shared += 1
来源：http://dali.zycfv.cn/Article/details/gtjvyvpkpj.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.tian-w.cn/Article/details/gthkrtpzld.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.gaohongyu789.top/Article/details/gtlorbvyju.html

TS:   // 同 JS
来源：http://dali.yueranfly.top/Article/details/gtrdpjopui.html

Java: synchronized (this) { shared++; }
来源：http://dali.tianlin.xyz/Article/details/gtvywcdmzg.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.smart0.xyz/Article/details/gtdxsbwdkv.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.yvedp.cn/Article/details/gtkwvggcvs.html

C#:   lock (gate) { shared++; }
来源：http://dali.wangdashe.top/Article/details/gtjvpugcej.html

[O04] 定义异步函数并等待
来源：http://dali.tian-w.cn/Article/details/gtpfyzyggt.html

Py:   async def f():⏎    await g()
来源：http://dali.xinyue.icu/Article/details/gtvvgpesor.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.nanxuanxn.top/Article/details/gtkrohmoar.html

JS:   async function f() { await g(); }
来源：http://dali.quarkkingdee.top/Article/details/gtrhkwphvi.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.dashuyun.cn/Article/details/gtahwhhist.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.yueranfly.top/Article/details/gtsuitxmwb.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.cqqwz.cn/Article/details/gtbqjbvkaq.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.aibaodan.cn/Article/details/gtxtuvsnxz.html

C#:   async Task F() { await G(); }
来源：http://dali.xuanzx.com/Article/details/gtnhoxezmw.html

[O05] 并发执行并等待全部完成
来源：http://dali.cqqwz.cn/Article/details/gtgudaglfv.html

Py:   asyncio.gather(*tasks)
来源：http://dali.kuanghao11.cn/Article/details/gtaduipnoe.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.316326.xyz/Article/details/gtclbusoah.html

JS:   await Promise.all(tasks)
来源：http://dali.ppjwa.cn/Article/details/gtkcwaxemc.html

TS:   await Promise.all(tasks)
来源：http://dali.tianlin.xyz/Article/details/gttqzsphwg.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhiwuduotai.top/Article/details/gtatwcfkdt.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfceoapkt.html

Ruby: threads.map(&:join)
来源：http://dali.guannengcc.top/Article/details/gtqtkhuhym.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.jiagoushi.top/Article/details/gtjnrilfhp.html

[O06] 使用进程池
来源：http://dali.hywenlv.cn/Article/details/gtgeopkhsd.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.yangfankeji.com/Article/details/gtagpgurtv.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zdqjudy.top/Article/details/gtvcvhslfu.html

JS:   // child_process / cluster 模块
来源：http://dali.0kj1m.cn/Article/details/gttpdunkjh.html

TS:   // child_process / cluster 模块
来源：http://dali.yueranfly.top/Article/details/gtppacmxus.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhengqikj.top/Article/details/gtteocdnzw.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.yanxiufei.cn/Article/details/gtzburczxr.html

Ruby: // fork 块
来源：http://dali.ybcxt.top/Article/details/gtvocvjxas.html

C#:   Parallel.For
来源：http://dali.aizwys.cn/Article/details/gtphwfhuhr.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtxztnduks.html

P. 常用工具函数
来源：http://dali.jinghuilouyu.cn/Article/details/gtwwzpqgpp.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtoollsshg.html

[P01] 生成 UUID
来源：http://dali.haohaochexian.top/Article/details/gtiruhsggo.html

Py:   str(uuid.uuid4())
来源：http://dali.pycfn.com/Article/details/gtzkyejmlh.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.haohaochexian.top/Article/details/gtupkpvben.html

JS:   crypto.randomUUID()
来源：http://dali.yj202588.top/Article/details/gtsokkayae.html

TS:   crypto.randomUUID()
来源：http://dali.xuanzx.com/Article/details/gtstfcdfxk.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gtyamtjcta.html

Go:   // 用 github.com/google/uuid
来源：http://dali.haohaochexian.top/Article/details/gtiytssnru.html

Ruby: SecureRandom.uuid
来源：http://dali.chenzaomai.com/Article/details/gtsczoaoth.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.hysaishi.cn/Article/details/gtfyemqtln.html

[P02] MD5 / SHA256 摘要
来源：http://dali.fengsongda.top/Article/details/gtpssntrwm.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.meibo888.top/Article/details/gtgqsquwpj.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.iojbl.cn/Article/details/gtwzsztmji.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.quarkkingdee.top/Article/details/gtdfouiwob.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.gaohongyu789.top/Article/details/gtftbbntog.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtugzywvru.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.cqqwz.cn/Article/details/gtflbyzwil.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.hnxiangtu.top/Article/details/gtaremdjmx.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.birdmap.top/Article/details/gtjlitffsq.html

[P03] 生成短随机字符串
来源：http://dali.aizwys.cn/Article/details/gtbxpeyafa.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.ppjwa.cn/Article/details/gtxqfnpjlf.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.birdmap.top/Article/details/gtfuflivbm.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.cqqwz.cn/Article/details/gtcpysjszr.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.xuanzx.com/Article/details/gtejhqpyec.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.meibo888.top/Article/details/gtknbxzodm.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhixingplan.top/Article/details/gtovkdtbkm.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.nanxuanxn.top/Article/details/gtamdhrsuy.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.jlsjyb.cn/Article/details/gtxspgttrx.html

[P04] 求长度
来源：http://dali.aibaodan.cn/Article/details/gtvqfyfdmk.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zdqjudy.top/Article/details/gtybzyilgp.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.hywenlv.cn/Article/details/gtsqfwsgzh.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.guannengcc.top/Article/details/gtsgdyfsbe.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.pengpengdd.cyou/Article/details/gtqmmevcbf.html

Java: list.size();  map.size();  s.length()
来源：http://dali.jinqigufen.top/Article/details/gtukqsxohb.html

Go:   len(arr);  len(m)
来源：http://dali.tianlin.xyz/Article/details/gtzrmwztlb.html

Ruby: x.length;  x.size
来源：http://dali.nanxinkj.top/Article/details/gtsstzppxt.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.shangyingyoupin.top/Article/details/gtwgkdfgso.html

[P05] 判断两个对象内容是否相等
来源：http://dali.fengsongda.top/Article/details/gtvihjywuq.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.shanyushiyangtech.top/Article/details/gtgijdzmps.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.yj202588.top/Article/details/gtkvysrwup.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.jinqigufen.top/Article/details/gtlyuorjqr.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.jqgfzy.top/Article/details/gtngpehmdv.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.yueranfly.top/Article/details/gtisojvarq.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zycfv.cn/Article/details/gtbwntqcdl.html

Ruby: a == b
来源：http://dali.sysykeji.top/Article/details/gtigbnprnd.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.ybcxt.top/Article/details/gtfyrqhvfo.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.ydzc1.top/Article/details/gtwfwthinj.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhongyouzk.top/Article/details/gtuwkcrewh.html

PHP:  if (empty($x)) {}
来源：http://dali.yj20258.top/Article/details/gtnfhxysoi.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.cqqwz.cn/Article/details/gtbdxqkyyi.html

TS:   if (x == null) {}
来源：http://dali.kuanghao11.cn/Article/details/gtjokioxih.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.jqgufenzy.top/Article/details/gtnumwpwiv.html

Go:   if x == nil {}
来源：http://dali.zycfv.cn/Article/details/gtudubhvfz.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.hywenlv.cn/Article/details/gtlzcoqiie.html

C#:   if (x is null) {}
来源：http://dali.yuanzhike.top/Article/details/gtddeojpuk.html

[P07] 防抖与节流
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtphregnnz.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.c1oappe.top/Article/details/gtpnzxvgyf.html

PHP:  // 手写时间戳比较
来源：http://dali.havefunace.top/Article/details/gtvebfijeg.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.0kj1m.cn/Article/details/gthzxgkzyy.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.nanxinkj.top/Article/details/gtvdyiwtcq.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.shuidangran.top/Article/details/gtopiemhmn.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.meibo888.top/Article/details/gtbmwyludr.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.aizwys.cn/Article/details/gtrgqcfkjc.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.hysaishi.cn/Article/details/gtaptsjfgd.html

[P08] 处理浮点精度问题
来源：http://dali.shuidangran.top/Article/details/gtlrlqlvcd.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.wangdashe.top/Article/details/gtuzntityd.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.yanxiufei.cn/Article/details/gtruqqifgd.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhongyouzk.top/Article/details/gtpsnkrzsu.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.ehwqpu.com/Article/details/gtrtlzslmt.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.sufxvd.cn/Article/details/gthrgivmoi.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.snrcjt.cn/Article/details/gtakgthplf.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.fengsongda.top/Article/details/gtcuszlqex.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhengqikj.top/Article/details/gtxkcokmrn.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtxjhzefyh.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.yanxiufei.cn/Article/details/gttalymhuh.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtdadqpgvn.html

[Q01] 创建表
来源：http://dali.sweek.top/Article/details/gtqvxewkyz.html

CREATE TABLE users (
来源：http://dali.daxiang520.top/Article/details/gtleifjqlx.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.svipenyu.cn/Article/details/gtbhlegbgm.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhixingplan.top/Article/details/gtlqwgxmve.html

email VARCHAR(100) UNIQUE,
来源：http://dali.yuxming.cn/Article/details/gtdxyvutsu.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.tian-w.cn/Article/details/gtffcvwpmz.html

);
来源：http://dali.hammf.cn/Article/details/gtucwjyozk.html

[Q02] 创建带外键的表
来源：http://dali.ehwqpu.com/Article/details/gtqpllkwzk.html

CREATE TABLE orders (
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyndnnmfb.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.0kj1m.cn/Article/details/gtcfwxcasb.html

user_id INT NOT NULL,
来源：http://dali.fzhhl.top/Article/details/gtliepiuhp.html

amount DECIMAL(10, 2),
来源：http://dali.havefunace.top/Article/details/gtavvpdwoj.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.cucudq.cn/Article/details/gtciiggihw.html

);
来源：http://dali.yanxiufei.cn/Article/details/gtbgknkeyc.html

[Q03] 增加列
来源：http://dali.ybcxt.top/Article/details/gtaszmiqgh.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.yongpay.top/Article/details/gtbsjcahqj.html

[Q04] 修改列类型
来源：http://dali.jyoumei.cn/Article/details/gtrbcyewll.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.gaohongyu789.top/Article/details/gtvasilurz.html

[Q05] 重命名列
来源：http://dali.ehwqpu.com/Article/details/gtfiziwzki.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhixingplan.top/Article/details/gtvwoffkcu.html

[Q06] 删除列
来源：http://dali.0kj1m.cn/Article/details/gtgltfxrwp.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.hammf.cn/Article/details/gtcrdprezp.html

[Q07] 删除表
来源：http://dali.smart0.xyz/Article/details/gtlojrytoe.html

DROP TABLE IF EXISTS orders;
来源：http://dali.yj202588.top/Article/details/gtwmpfamuj.html

[Q08] 创建普通索引
来源：http://dali.cdnleiting.top/Article/details/gtzgtpttmq.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.pengpengdd.cyou/Article/details/gtdsqudjtu.html

[Q09] 创建唯一索引
来源：http://dali.jyoumei.cn/Article/details/gtlepcfwqv.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.nanxinkj.top/Article/details/gtgggpokzi.html

[Q10] 插入单行
来源：http://dali.ydzc1.top/Article/details/gtjssmzdzj.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.iojbl.cn/Article/details/gtdpzznhrw.html

[Q11] 一次插入多行
来源：http://dali.dashuyun.cn/Article/details/gtlizgdhde.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.hywenlv.cn/Article/details/gtjzpauasi.html

[Q12] 插入后取自增 ID
来源：http://dali.cheryme.top/Article/details/gtfphxvydn.html


<!-- 参考信息 -->