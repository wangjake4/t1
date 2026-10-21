代发 wailian999

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.cashguo.top/Article/details/gtdyosmkoi.html

Ruby: warn "err"
来源：http://dali.c1oappe.top/Article/details/gtfpounlle.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.andypj.xyz/Article/details/gttuyrjwtq.html

[M07] 判断是否为主入口
来源：http://dali.quarkkingdee.top/Article/details/gtlovcgfeh.html

Py:   if __name__ == "__main__":
来源：http://dali.tanke756.top/Article/details/gtxolppsyn.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.xinyue.icu/Article/details/gtkybydawi.html

JS:   require.main === module
来源：http://dali.tianlin.xyz/Article/details/gtaydhqzso.html

TS:   require.main === module
来源：http://dali.zhoulong.xyz/Article/details/gttulxfrho.html

Java: public static void main(String[] args)
来源：http://dali.hysaishi.cn/Article/details/gtpusrqfrx.html

Go:   func main()
来源：http://dali.jinghuilouyu.cn/Article/details/gtmgucfnfa.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.xinyue.icu/Article/details/gthbevaiub.html

C#:   static void Main(string[] args)
来源：http://dali.jqgfzy.top/Article/details/gtbsflaxwf.html

[M08] 获取系统与运行时信息
来源：http://dali.haohaochexian.top/Article/details/gtncditrnk.html

Py:   platform.system();  platform.python_version()
来源：http://dali.aibaodan.cn/Article/details/gtajxejboe.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.xuetiantiany.cn/Article/details/gtubtwocnl.html

JS:   process.platform;  process.version
来源：http://dali.9152youxi.cn/Article/details/gtrwebuulm.html

TS:   process.platform;  process.version
来源：http://dali.yj20258.top/Article/details/gtnbvjtvvc.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.jinqigfzy.top/Article/details/gtdltirygt.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.tanke756.top/Article/details/gtxzngqukw.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gtdufbvmtq.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.smart0.xyz/Article/details/gteimzwcmz.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtaseglzvs.html

N. 数据结构与算法
来源：http://dali.aibaodan.cn/Article/details/gtkzystncr.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtfbgaolas.html

[N01] 二分查找（有序数组）
来源：http://dali.nanxinkj.top/Article/details/gtwbdrvalc.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.sufxvd.cn/Article/details/gtxmuyspqk.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gtjnmljfpj.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtchxxncqy.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.birdmap.top/Article/details/gthimmqcyk.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.316326.xyz/Article/details/gtfmmtsmgz.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.guowangkeji.top/Article/details/gtgucdhcuk.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.chenzaomai.com/Article/details/gtlgqhtsbt.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.feifeiyinyue.top/Article/details/gtjdtmcqyt.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.hysaishi.cn/Article/details/gtqalvtpnc.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.havefunace.top/Article/details/gtmolchpdf.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.sufxvd.cn/Article/details/gtokuxtxai.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.9152youxi.cn/Article/details/gtrrsjuwgd.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.aibaodan.cn/Article/details/gtgywiyjqk.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.hnqzz.top/Article/details/gtdhqmpuqm.html

Go:   slices.Sort(arr)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgzyzures.html

Ruby: arr.sort
来源：http://dali.meibo888.top/Article/details/gtbaknyydq.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.gotoacloud.top/Article/details/gtycuyesma.html

[N03] 快速排序（分治示例）
来源：http://dali.shzxlz.cn/Article/details/gtmbjbmhlc.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.hywenlv.cn/Article/details/gtmqlgmaod.html

PHP:  // 递归实现，或用 usort
来源：http://dali.xylfe.cn/Article/details/gtrwhcvsba.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.havefunace.top/Article/details/gtpvngmhfj.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.shanyushiyangtech.top/Article/details/gtrqgogukk.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.xuanzx.com/Article/details/gtirxuilcu.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.yj20258888.top/Article/details/gtovsmuafz.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.guowangkeji.top/Article/details/gteufhacpv.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.wangdashe.top/Article/details/gttzqtcwqp.html

[N04] 斐波那契数列
来源：http://dali.xuetiantiany.cn/Article/details/gtkbwepqso.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gthbplwwen.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.havefunace.top/Article/details/gtfyarspwo.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yuxming.cn/Article/details/gtwoadymkg.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.gogol.net.cn/Article/details/gtscsajmkp.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.mhx1999.top/Article/details/gtmckgfees.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.gotoacloud.top/Article/details/gtwxylhtsl.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.guannengcc.top/Article/details/gtbwgsfczy.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.kuanghao11.cn/Article/details/gtcsbroysn.html

[N05] 最大公约数
来源：http://dali.shangyingyoupin.top/Article/details/gtiazcsgkr.html

Py:   math.gcd(a, b)
来源：http://dali.yonumen.top/Article/details/gtywymmxku.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.chenzaomai.com/Article/details/gtpendpjzg.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.aibaodan.cn/Article/details/gteojaxmly.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.birdmap.top/Article/details/gtkinohijv.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.hnxiangtu.top/Article/details/gtgrixvmzp.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.vqdsnc.cn/Article/details/gtowgcmxyp.html

Ruby: a.gcd(b)
来源：http://dali.hywenlv.cn/Article/details/gtvwpayiyi.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwppujxcg.html

[N06] 判断回文字符串
来源：http://dali.nanxinkj.top/Article/details/gtcusvxogu.html

Py:   s == s[::-1]
来源：http://dali.daxiang520.top/Article/details/gtlzjkoqgj.html

PHP:  $s === strrev($s);
来源：http://dali.chenjidiqi.icu/Article/details/gtkqvzotst.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gtpddykrky.html

TS:   s === [...s].reverse().join("")
来源：http://dali.hongshengwenyu.top/Article/details/gtoiplicri.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.havefunace.top/Article/details/gthzimpnhk.html

Go:   // 双指针从两端比较
来源：http://dali.jinqigfzy.top/Article/details/gtjtfsxdbm.html

Ruby: s == s.reverse
来源：http://dali.hnqzz.top/Article/details/gtrmcqsqof.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.yj202588.top/Article/details/gtxkdphdul.html

[N07] 两数之和（返回下标）
来源：http://dali.quarkkingdee.top/Article/details/gtqdeonbhj.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.birdmap.top/Article/details/gtiwejluso.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.cqqwz.cn/Article/details/gtglhpfdyi.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.haohaochexian.top/Article/details/gtrvdogkll.html

TS:   // 手写 Map<string, number>
来源：http://dali.sxryk.cn/Article/details/gthrpdostn.html

Java: // 手写 HashMap
来源：http://dali.zycfv.cn/Article/details/gtgzajysfn.html

Go:   // 手写 map[int]int
来源：http://dali.cheryme.top/Article/details/gtsrypojdj.html

Ruby: // 手写 Hash
来源：http://dali.vqdsnc.cn/Article/details/gtwlrtlaph.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.fzhhl.top/Article/details/gtingwakyd.html

[N08] 生成全排列
来源：http://dali.guowangkeji.top/Article/details/gtbcsnyyyh.html

Py:   itertools.permutations(arr)
来源：http://dali.shzxlz.cn/Article/details/gtvbxwocbz.html

PHP:  // 手写递归交换
来源：http://dali.yvedp.cn/Article/details/gtmdgkeqpu.html

JS:   // 手写回溯递归
来源：http://dali.hnqzz.top/Article/details/gtrwcwnahd.html

TS:   // 手写回溯递归
来源：http://dali.hysaishi.cn/Article/details/gtdrfnewbj.html

Java: // 手写回溯递归
来源：http://dali.redwolf501.top/Article/details/gtzgltnxuq.html

Go:   // 手写回溯递归
来源：http://dali.nanxinkj.top/Article/details/gtwnuzogef.html

Ruby: arr.permutation.to_a
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgbbwmqui.html

C#:   // 手写回溯递归
来源：http://dali.hywenlv.cn/Article/details/gtbweanlvo.html

[N09] 栈与队列
来源：http://dali.hongshengwenyu.top/Article/details/gtfabawkpd.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.birdmap.top/Article/details/gtcuutufle.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.jinghuilouyu.cn/Article/details/gtlylcmyoc.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.gogol.net.cn/Article/details/gtkdkqpktz.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvurxqrla.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.xuanzx.com/Article/details/gtzssznprk.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.gzhubu.top/Article/details/gtqmrjbgrr.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.daxiang520.top/Article/details/gtymxepjfn.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.xziqi.cn/Article/details/gthmssejfv.html

[N10] 链表节点定义
来源：http://dali.zhixingplan.top/Article/details/gtlhhfdtkd.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.tianlin.xyz/Article/details/gtvirnkoyq.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.daria6918.cn/Article/details/gtljhciebw.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.hysaishi.cn/Article/details/gtwmkxlyqo.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.vqdsnc.cn/Article/details/gtjyxjrkkt.html

Java: class Node { int v; Node next; }
来源：http://dali.daria6918.cn/Article/details/gtiwdocjws.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.316326.xyz/Article/details/gtxawojxix.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.yvedp.cn/Article/details/gtbdbkodoj.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.pycfn.com/Article/details/gtgkphvevo.html

[N11] 二叉树中序遍历
来源：http://dali.yj20258888.top/Article/details/gtsqfprqss.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.bjfxy.top/Article/details/gtwahgokvq.html

PHP:  // 手写递归函数
来源：http://dali.feifeiyinyue.top/Article/details/gtceulgmrc.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.chenjidiqi.icu/Article/details/gtcfzttvpf.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.hysaishi.cn/Article/details/gtvpxubhar.html

Java: // 手写递归
来源：http://dali.cheryme.top/Article/details/gtfpcrcdwn.html

Go:   // 手写递归
来源：http://dali.ppjwa.cn/Article/details/gtszhbeonh.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.ydzc1.top/Article/details/gtoknyoifa.html

C#:   // 手写递归
来源：http://dali.wangshuangyany.cn/Article/details/gtozlcaczv.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.cheryme.top/Article/details/gtlrhhpwjk.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.ivvv.top/Article/details/gtvrbusoml.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.gzhubu.top/Article/details/gthjbrgiqf.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.hysaishi.cn/Article/details/gtgwoysood.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.daria6918.cn/Article/details/gtivdgbkwo.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdyfjvwhz.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.tian-w.cn/Article/details/gtlvaporrz.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.feifeiyinyue.top/Article/details/gtbjpxrqkg.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaaqxskgv.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtqhkpnlkn.html

O. 并发与异步
来源：http://dali.cucudq.cn/Article/details/gtslxwkbkt.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtrdhefjoh.html

[O01] 启动一个线程
来源：http://dali.quarkkingdee.top/Article/details/gthsubjzep.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.ivvv.top/Article/details/gtviwmqzai.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.hfpthk.cn/Article/details/gtdopaebmx.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.redwolf501.top/Article/details/gtdccnphgj.html

TS:   // 同 JS
来源：http://dali.iojbl.cn/Article/details/gtrozxyjsy.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhongyouzk.top/Article/details/gtlyybmvoh.html

Go:   go f()
来源：http://dali.pycfn.com/Article/details/gtirnrunvh.html

Ruby: Thread.new { f }
来源：http://dali.jinqigfzy.top/Article/details/gttpukbptf.html

C#:   Task.Run(() => F());
来源：http://dali.jyoumei.cn/Article/details/gthrmnmaqn.html

[O02] 使用线程池
来源：http://dali.cqqwz.cn/Article/details/gtbozvokto.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.chenlongwang.top/Article/details/gttzjjulmt.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.0kj1m.cn/Article/details/gtfshutyur.html

JS:   // worker_threads 线程池
来源：http://dali.meibo888.top/Article/details/gtsvybyfve.html

TS:   // worker_threads 线程池
来源：http://dali.yuanzhike.top/Article/details/gtnofhrmfw.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.gogol.net.cn/Article/details/gtrmxaspgo.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.0kj1m.cn/Article/details/gtrofzdqgi.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.fengsongda.top/Article/details/gtybxfcbkv.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.gaohongyu789.top/Article/details/gtmlirmmdq.html

[O03] 加锁保护共享数据
来源：http://dali.iojbl.cn/Article/details/gtfpyrapyl.html

Py:   with lock: shared += 1
来源：http://dali.pycfn.com/Article/details/gtpfjgmvlt.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.hammf.cn/Article/details/gtvdqefrft.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.tian-w.cn/Article/details/gtmayfczew.html

TS:   // 同 JS
来源：http://dali.sxryk.cn/Article/details/gtxedwbqfu.html

Java: synchronized (this) { shared++; }
来源：http://dali.xinyue.icu/Article/details/gtmkflvbjb.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.cdnleiting.top/Article/details/gtwuhgadlr.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.jiagoushi.top/Article/details/gtaiocorvj.html

C#:   lock (gate) { shared++; }
来源：http://dali.jinqigufen.top/Article/details/gtkezkinmm.html

[O04] 定义异步函数并等待
来源：http://dali.meibo888.top/Article/details/gtipjwkkiy.html

Py:   async def f():⏎    await g()
来源：http://dali.kuanghao11.cn/Article/details/gtftxvzhap.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.chenlongwang.top/Article/details/gtpzuocivw.html

JS:   async function f() { await g(); }
来源：http://dali.316326.xyz/Article/details/gtsmdhfapu.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhiwuduotai.top/Article/details/gtlsuggtie.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.chenzaomai.com/Article/details/gtqeylpvlm.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.cashguo.top/Article/details/gtbswtbpwh.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.cdnleiting.top/Article/details/gtuycfgevj.html

C#:   async Task F() { await G(); }
来源：http://dali.guannengcc.top/Article/details/gtwnbzjwvx.html

[O05] 并发执行并等待全部完成
来源：http://dali.shanyushiyangtech.top/Article/details/gtophkcwzf.html

Py:   asyncio.gather(*tasks)
来源：http://dali.guannengcc.top/Article/details/gtbnuvletx.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.chenjidiqi.icu/Article/details/gtrpwmgagq.html

JS:   await Promise.all(tasks)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjcbvjdhx.html

TS:   await Promise.all(tasks)
来源：http://dali.316326.xyz/Article/details/gtrtikqvtb.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.yj20258888.top/Article/details/gtvxqtxdcb.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.nanxuanxn.top/Article/details/gthpmgiitp.html

Ruby: threads.map(&:join)
来源：http://dali.cqqwz.cn/Article/details/gtmnhpilmw.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.havefunace.top/Article/details/gtmuxggniz.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gtsivtfblr.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.pengpengdd.cyou/Article/details/gtupwjdlbg.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.tian-w.cn/Article/details/gtlokoxckh.html

JS:   // child_process / cluster 模块
来源：http://dali.hnxiangtu.top/Article/details/gtcxqqdmna.html

TS:   // child_process / cluster 模块
来源：http://dali.yj202588.top/Article/details/gtlfvvebcg.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.guowangkeji.top/Article/details/gtccinmbym.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.xuanzx.com/Article/details/gtexinrsfo.html

Ruby: // fork 块
来源：http://dali.fzhhl.top/Article/details/gteltzppju.html

C#:   Parallel.For
来源：http://dali.316326.xyz/Article/details/gtyaigdxtv.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtqbiukhvs.html

P. 常用工具函数
来源：http://dali.chenzaomai.com/Article/details/gtesxhydyh.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gterouwpav.html

[P01] 生成 UUID
来源：http://dali.dashuyun.cn/Article/details/gtgommveeq.html

Py:   str(uuid.uuid4())
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdtnljvtz.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.hammf.cn/Article/details/gtgjdljpex.html

JS:   crypto.randomUUID()
来源：http://dali.jinyuanbaomall.cn/Article/details/gttyhgomjq.html

TS:   crypto.randomUUID()
来源：http://dali.zhixingplan.top/Article/details/gtcthmvdnl.html

Java: UUID.randomUUID().toString()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkjirhrje.html

Go:   // 用 github.com/google/uuid
来源：http://dali.chenlongwang.top/Article/details/gtczvujgcf.html

Ruby: SecureRandom.uuid
来源：http://dali.cqqwz.cn/Article/details/gtykrmjxoz.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.cdnleiting.top/Article/details/gtshevfbpi.html

[P02] MD5 / SHA256 摘要
来源：http://dali.shuidangran.top/Article/details/gtlzrkazmj.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.ivvv.top/Article/details/gtbehmkpac.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zycfv.cn/Article/details/gtnjxlvvki.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gtrkkebfac.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.hywenlv.cn/Article/details/gtxaugphdx.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.tian-w.cn/Article/details/gtaawsjqxx.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.jinqigufen.top/Article/details/gtbrfcybmb.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.cqqwz.cn/Article/details/gtxgntnplb.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.aizwys.cn/Article/details/gtkhdiraaj.html

[P03] 生成短随机字符串
来源：http://dali.0kj1m.cn/Article/details/gtuxgniyvh.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.yuxming.cn/Article/details/gtbgnwywwg.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.hongshengwenyu.top/Article/details/gtsbvhitiw.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.smart0.xyz/Article/details/gtwasjpktu.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.hnxiangtu.top/Article/details/gtanrhjzos.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.hammf.cn/Article/details/gtgrfpqtvr.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.jiagoushi.top/Article/details/gtpcbnpkuq.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvjgfncnu.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.tianlin.xyz/Article/details/gtxdydmyvw.html

[P04] 求长度
来源：http://dali.zhengqikj.top/Article/details/gtyigukgtu.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.hfpthk.cn/Article/details/gtpbhovxts.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.cucudq.cn/Article/details/gtotarzywb.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yonumen.top/Article/details/gtmyfcuivp.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.0kj1m.cn/Article/details/gtppjkgfyw.html

Java: list.size();  map.size();  s.length()
来源：http://dali.yj202588.top/Article/details/gtzxxpqbto.html

Go:   len(arr);  len(m)
来源：http://dali.zhengqikj.top/Article/details/gtlouddqdh.html

Ruby: x.length;  x.size
来源：http://dali.sweek.top/Article/details/gtvisltnfb.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.hongshengwenyu.top/Article/details/gtphvcoafr.html

[P05] 判断两个对象内容是否相等
来源：http://dali.yj20258888.top/Article/details/gtjzoyylbo.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.hongshengwenyu.top/Article/details/gtgxeasjjp.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.yvedp.cn/Article/details/gtfngxqjui.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.havefunace.top/Article/details/gtbalazvtv.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpkhmfewn.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.daxiang520.top/Article/details/gtglvruywu.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.gogol.net.cn/Article/details/gtmothcgnk.html

Ruby: a == b
来源：http://dali.xylfe.cn/Article/details/gtjskjuotn.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.chenlongwang.top/Article/details/gtpostzcpd.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.iojbl.cn/Article/details/gtycetpqly.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhoulong.xyz/Article/details/gtlmyaxois.html

PHP:  if (empty($x)) {}
来源：http://dali.yj202588.top/Article/details/gtyttcpszq.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.jqgfzy.top/Article/details/gtxcioecyz.html

TS:   if (x == null) {}
来源：http://dali.sweek.top/Article/details/gtelirplpg.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.jiagoushi.top/Article/details/gtiyomqggn.html

Go:   if x == nil {}
来源：http://dali.kuanghao11.cn/Article/details/gtvngpwjor.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.quarkkingdee.top/Article/details/gtwwtnlpqk.html

C#:   if (x is null) {}
来源：http://dali.havefunace.top/Article/details/gtegxelyqb.html

[P07] 防抖与节流
来源：http://dali.ppjwa.cn/Article/details/gthubftzwg.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpdjdiola.html

PHP:  // 手写时间戳比较
来源：http://dali.pycfn.com/Article/details/gtljapflwt.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yonumen.top/Article/details/gtelqagcqc.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.tanke756.top/Article/details/gtaqjvmfas.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.jinqigufen.top/Article/details/gtmxihygqx.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.jqgufenzy.top/Article/details/gtvncjmprc.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.aibaodan.cn/Article/details/gtaolinclw.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.jlsjyb.cn/Article/details/gtdrsxucjw.html

[P08] 处理浮点精度问题
来源：http://dali.yj202588.top/Article/details/gtlbfzgjbt.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.havefunace.top/Article/details/gtdwrswfgr.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.dashuyun.cn/Article/details/gtfvsqpvkc.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.mhx1999.top/Article/details/gtaedccioa.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiypjlodo.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.feifeiyinyue.top/Article/details/gtbehixflj.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.yanxiufei.cn/Article/details/gtfbumsawz.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.shuidangran.top/Article/details/gtsnjuugeg.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.aibaodan.cn/Article/details/gtizgylwko.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gttteynhjp.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.yueranfly.top/Article/details/gtjndaxbvi.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtpmnahfyt.html

[Q01] 创建表
来源：http://dali.jinghuilouyu.cn/Article/details/gtytffhvjj.html

CREATE TABLE users (
来源：http://dali.jqgufenzy.top/Article/details/gtxlzivlnx.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.pengpengdd.cyou/Article/details/gtuqjwkbik.html

name VARCHAR(50) NOT NULL,
来源：http://dali.cdnleiting.top/Article/details/gtaikwvmej.html

email VARCHAR(100) UNIQUE,
来源：http://dali.hfpthk.cn/Article/details/gtudibktmn.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.yangfankeji.com/Article/details/gtcojuxvxg.html

);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtahzfgwtn.html

[Q02] 创建带外键的表
来源：http://dali.jianghu66.top/Article/details/gtlzkumttz.html

CREATE TABLE orders (
来源：http://dali.zhiwuduotai.top/Article/details/gtiwqxkjdu.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.cashguo.top/Article/details/gtbqgcfjph.html

user_id INT NOT NULL,
来源：http://dali.tanke756.top/Article/details/gtsmxbxdri.html

amount DECIMAL(10, 2),
来源：http://dali.sxryk.cn/Article/details/gtniamvvxe.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.nwbrower.top/Article/details/gtdsexekzd.html

);
来源：http://dali.sweek.top/Article/details/gtowogqxvx.html

[Q03] 增加列
来源：http://dali.hnxiangtu.top/Article/details/gtiwzmsaft.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.chenjidiqi.icu/Article/details/gtnbibxake.html

[Q04] 修改列类型
来源：http://dali.wangdashe.top/Article/details/gtvrxvwpbv.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.fengsongda.top/Article/details/gtinsjiabm.html

[Q05] 重命名列
来源：http://dali.ppjwa.cn/Article/details/gtmupfmqba.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.birdmap.top/Article/details/gtmzexqhmn.html

[Q06] 删除列
来源：http://dali.ydzc1.top/Article/details/gtmzucmgnh.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhoulong.xyz/Article/details/gtkmzzhcbj.html

[Q07] 删除表
来源：http://dali.shzxlz.cn/Article/details/gtvqlmysut.html

DROP TABLE IF EXISTS orders;
来源：http://dali.9152youxi.cn/Article/details/gtcdoiktnc.html

[Q08] 创建普通索引
来源：http://dali.jinqigfzy.top/Article/details/gtjjxumyfv.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.xylfe.cn/Article/details/gtqsrbvydw.html

[Q09] 创建唯一索引
来源：http://dali.bjfxy.top/Article/details/gtupdjesty.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.andypj.xyz/Article/details/gtdgcykymj.html

[Q10] 插入单行
来源：http://dali.hammf.cn/Article/details/gtaggfktxz.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.ydzc1.top/Article/details/gtdndusrwa.html

[Q11] 一次插入多行
来源：http://dali.cucudq.cn/Article/details/gtnljlfphq.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.wangshuangyany.cn/Article/details/gtyoalajuk.html

[Q12] 插入后取自增 ID
来源：http://dali.chenlongwang.top/Article/details/gtjmscttyi.html


<!-- 参考信息 -->