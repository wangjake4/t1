代发 wailian999

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.yj20258888.top/Article/details/gt2wjtgheqd.html

Ruby: warn "err"
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lqgpclvm.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.cashguo.top/Article/details/gt2umemrred.html

[M07] 判断是否为主入口
来源：http://dali.svipenyu.cn/Article/details/gt2acacfezz.html

Py:   if __name__ == "__main__":
来源：http://dali.smart0.xyz/Article/details/gt2eepnyugu.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhixingplan.top/Article/details/gt2obauclok.html

JS:   require.main === module
来源：http://dali.yanxiufei.cn/Article/details/gt2owmfkuyj.html

TS:   require.main === module
来源：http://dali.316326.xyz/Article/details/gt2fcyfeylb.html

Java: public static void main(String[] args)
来源：http://dali.jlsjyb.cn/Article/details/gt2rjnikgfz.html

Go:   func main()
来源：http://dali.nanxinkj.top/Article/details/gt2qpmrusvb.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.redwolf501.top/Article/details/gt2vcaudyht.html

C#:   static void Main(string[] args)
来源：http://dali.yueranfly.top/Article/details/gt2dcaddgdf.html

[M08] 获取系统与运行时信息
来源：http://dali.c1oappe.top/Article/details/gt2ciighzjh.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zdqjudy.top/Article/details/gt2cyvkyrkh.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhengqikj.top/Article/details/gt2xhnzufsy.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2sezwfiwh.html

TS:   process.platform;  process.version
来源：http://dali.tianlin.xyz/Article/details/gt2liprupfp.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.kuanghao11.cn/Article/details/gt2ksiodqjy.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.jqgfzy.top/Article/details/gt2kggvqjws.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ohxxriah.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.pycfn.com/Article/details/gt2yvuimsng.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gt2xirervnt.html

N. 数据结构与算法
来源：http://dali.fzhhl.top/Article/details/gt2tucqbtag.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gt2thbmoclw.html

[N01] 二分查找（有序数组）
来源：http://dali.wangshuangyany.cn/Article/details/gt2rubuykwr.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.sweek.top/Article/details/gt2bzkbbula.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.0kj1m.cn/Article/details/gt2mlsylyvl.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.pycfn.com/Article/details/gt2lkqvepdn.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jianghu66.top/Article/details/gt2okqqaagu.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.yangfankeji.com/Article/details/gt2wqadwtie.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.c1oappe.top/Article/details/gt2bbpqfkcq.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.aizwys.cn/Article/details/gt2kdcfghtt.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.jinqigfzy.top/Article/details/gt2sinugwqk.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.andypj.xyz/Article/details/gt2swsqglol.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.wangshuangyany.cn/Article/details/gt2idfnokya.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.yj20258.top/Article/details/gt2sfzfyhdq.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.hnqzz.top/Article/details/gt2mthuxytz.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.cdnleiting.top/Article/details/gt2fcsfjogz.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.jlsjyb.cn/Article/details/gt2mjxzxtjk.html

Go:   slices.Sort(arr)
来源：http://dali.316326.xyz/Article/details/gt2pgrcbvlp.html

Ruby: arr.sort
来源：http://dali.jyoumei.cn/Article/details/gt2lbmwuntb.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.kuanghao11.cn/Article/details/gt2gojrfrru.html

[N03] 快速排序（分治示例）
来源：http://dali.ivvv.top/Article/details/gt2fnsdtibg.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.vqdsnc.cn/Article/details/gt2hzgfckhx.html

PHP:  // 递归实现，或用 usort
来源：http://dali.ybcxt.top/Article/details/gt2dguzhsai.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yj20258888.top/Article/details/gt2xxhybenx.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.feifeiyinyue.top/Article/details/gt2lzdcktbc.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.smart0.xyz/Article/details/gt2dkqxzeim.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.yj20258.top/Article/details/gt2tdwfuuca.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.pengpengdd.cyou/Article/details/gt2svbzohec.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.feifeiyinyue.top/Article/details/gt2kbvbeesa.html

[N04] 斐波那契数列
来源：http://dali.xinyue.icu/Article/details/gt2rvaybpiz.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.dashuyun.cn/Article/details/gt2pnojfiml.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.hysaishi.cn/Article/details/gt2yntrtzxz.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.iojbl.cn/Article/details/gt2axpvpfjo.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.kuanghao11.cn/Article/details/gt2wyelzpcg.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.smart0.xyz/Article/details/gt2srtvlazb.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.0kj1m.cn/Article/details/gt2ijmimhoe.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zycfv.cn/Article/details/gt2bgphlgdb.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.0kj1m.cn/Article/details/gt2suznpcwl.html

[N05] 最大公约数
来源：http://dali.gogol.net.cn/Article/details/gt2uhtnpwyr.html

Py:   math.gcd(a, b)
来源：http://dali.sxryk.cn/Article/details/gt2flzhilbw.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2zdpvxfjf.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.snrcjt.cn/Article/details/gt2tcnmmdmw.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jinqigfzy.top/Article/details/gt2fecroroz.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.guowangkeji.top/Article/details/gt2hoakyqgw.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.0kj1m.cn/Article/details/gt2lrsxtblc.html

Ruby: a.gcd(b)
来源：http://dali.hnxiangtu.top/Article/details/gt2mtjbvkwb.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.hfpthk.cn/Article/details/gt2aaqxjlen.html

[N06] 判断回文字符串
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ttuoqhxj.html

Py:   s == s[::-1]
来源：http://dali.hnqzz.top/Article/details/gt2jcwvkliv.html

PHP:  $s === strrev($s);
来源：http://dali.sysykeji.top/Article/details/gt2btonchzz.html

JS:   s === [...s].reverse().join("")
来源：http://dali.cdnleiting.top/Article/details/gt2wrsfusvv.html

TS:   s === [...s].reverse().join("")
来源：http://dali.kuanghao11.cn/Article/details/gt2lavdnwla.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.nanxuanxn.top/Article/details/gt2tdrulger.html

Go:   // 双指针从两端比较
来源：http://dali.yueranfly.top/Article/details/gt2hpqfjtdk.html

Ruby: s == s.reverse
来源：http://dali.0kj1m.cn/Article/details/gt2mwlrkvbj.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhongyouzk.top/Article/details/gt2mlgalupm.html

[N07] 两数之和（返回下标）
来源：http://dali.jlsjyb.cn/Article/details/gt2nakozrsd.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.hongshengwenyu.top/Article/details/gt2easzdykv.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.jiagoushi.top/Article/details/gt2rkftslik.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.sufxvd.cn/Article/details/gt2trnniqjy.html

TS:   // 手写 Map<string, number>
来源：http://dali.jqgfzy.top/Article/details/gt2jtcmathu.html

Java: // 手写 HashMap
来源：http://dali.yj20258.top/Article/details/gt2eghrntkm.html

Go:   // 手写 map[int]int
来源：http://dali.c1oappe.top/Article/details/gt2hybaffxw.html

Ruby: // 手写 Hash
来源：http://dali.jianghu66.top/Article/details/gt2svohgtnh.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.hnxiangtu.top/Article/details/gt2konzwutu.html

[N08] 生成全排列
来源：http://dali.smart0.xyz/Article/details/gt2oweimjwd.html

Py:   itertools.permutations(arr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vmxywlri.html

PHP:  // 手写递归交换
来源：http://dali.smart0.xyz/Article/details/gt2wbwkeqlc.html

JS:   // 手写回溯递归
来源：http://dali.fengsongda.top/Article/details/gt2daiqjazq.html

TS:   // 手写回溯递归
来源：http://dali.nanxinkj.top/Article/details/gt2tqdiqwoa.html

Java: // 手写回溯递归
来源：http://dali.zhiwuduotai.top/Article/details/gt2hlvgyxfh.html

Go:   // 手写回溯递归
来源：http://dali.aizwys.cn/Article/details/gt2dimjrcqf.html

Ruby: arr.permutation.to_a
来源：http://dali.jyoumei.cn/Article/details/gt2sulbqtwf.html

C#:   // 手写回溯递归
来源：http://dali.sufxvd.cn/Article/details/gt2xmxxjptz.html

[N09] 栈与队列
来源：http://dali.bjfxy.top/Article/details/gt2tnmgxvyy.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.ydzc1.top/Article/details/gt2qrhccpbg.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.daria6918.cn/Article/details/gt2dkvbozqt.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2mfolklgu.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.xziqi.cn/Article/details/gt2tsizowtu.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.daria6918.cn/Article/details/gt2zrbszxhd.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.dashuyun.cn/Article/details/gt2yncrxmwt.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.wangdashe.top/Article/details/gt2nnfxlfqa.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.aizwys.cn/Article/details/gt2udlgtnrg.html

[N10] 链表节点定义
来源：http://dali.sysykeji.top/Article/details/gt2ptujvvhg.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.hnxiangtu.top/Article/details/gt2ndmgjypr.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.gogol.net.cn/Article/details/gt2caxavoiy.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2insnmnod.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.birdmap.top/Article/details/gt2uljofqdo.html

Java: class Node { int v; Node next; }
来源：http://dali.mhx1999.top/Article/details/gt2ozadlcwl.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.aizwys.cn/Article/details/gt2upxmcwyl.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.yj20258888.top/Article/details/gt2bihmhamq.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.tianlin.xyz/Article/details/gt2dtewbqmn.html

[N11] 二叉树中序遍历
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2riotdspk.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.aibaodan.cn/Article/details/gt2styvhhhj.html

PHP:  // 手写递归函数
来源：http://dali.svipenyu.cn/Article/details/gt2zclynosf.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yj20258888.top/Article/details/gt2xeazqobv.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.cqqwz.cn/Article/details/gt2hdzdzpey.html

Java: // 手写递归
来源：http://dali.xylfe.cn/Article/details/gt2wswfmbee.html

Go:   // 手写递归
来源：http://dali.yueranfly.top/Article/details/gt2asfjzrea.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.aibaodan.cn/Article/details/gt2inuryifi.html

C#:   // 手写递归
来源：http://dali.zhongyouzk.top/Article/details/gt2sdzsmckg.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.jinqigufen.top/Article/details/gt2tfiewpzf.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.sufxvd.cn/Article/details/gt2qmiasleq.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.chenjidiqi.icu/Article/details/gt2wejpwezm.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.quarkkingdee.top/Article/details/gt2nzkpnkij.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.xylfe.cn/Article/details/gt2jjudynal.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.vqdsnc.cn/Article/details/gt2vzxzozjy.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.sufxvd.cn/Article/details/gt2zpliftlv.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.svipenyu.cn/Article/details/gt2zeeujhas.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dnggosyj.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gt2pgfrvnqv.html

O. 并发与异步
来源：http://dali.vqdsnc.cn/Article/details/gt2fdaabkfu.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gt2vxmwtoab.html

[O01] 启动一个线程
来源：http://dali.snrcjt.cn/Article/details/gt2xtzfezyo.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhengqikj.top/Article/details/gt2xgbnmodl.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.nanxuanxn.top/Article/details/gt2ryvzhafc.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.sufxvd.cn/Article/details/gt2rhlbushs.html

TS:   // 同 JS
来源：http://dali.jqgufenzy.top/Article/details/gt2abbavacz.html

Java: new Thread(() -> f()).start()
来源：http://dali.gotoacloud.top/Article/details/gt2dcrogmue.html

Go:   go f()
来源：http://dali.chenzaomai.com/Article/details/gt2txkxeveu.html

Ruby: Thread.new { f }
来源：http://dali.daxiang520.top/Article/details/gt2hnjptfkl.html

C#:   Task.Run(() => F());
来源：http://dali.xuetiantiany.cn/Article/details/gt2oznaptoe.html

[O02] 使用线程池
来源：http://dali.yj20258.top/Article/details/gt2ehivnnqf.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.nwbrower.top/Article/details/gt2bmwdjsjd.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.yj202588.top/Article/details/gt2bcumscsq.html

JS:   // worker_threads 线程池
来源：http://dali.hfpthk.cn/Article/details/gt2baloandn.html

TS:   // worker_threads 线程池
来源：http://dali.yvedp.cn/Article/details/gt2zouchspf.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.vqdsnc.cn/Article/details/gt2psfitvxi.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.feifeiyinyue.top/Article/details/gt2xlqinahh.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.gzhubu.top/Article/details/gt2enrcklet.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.pengpengdd.cyou/Article/details/gt2hthzplhj.html

[O03] 加锁保护共享数据
来源：http://dali.jianghu66.top/Article/details/gt2msunneik.html

Py:   with lock: shared += 1
来源：http://dali.tianlin.xyz/Article/details/gt2blnoaurm.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.yanxiufei.cn/Article/details/gt2fciairzi.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2ghbnqelq.html

TS:   // 同 JS
来源：http://dali.svipenyu.cn/Article/details/gt2xujdxnkr.html

Java: synchronized (this) { shared++; }
来源：http://dali.ydzc1.top/Article/details/gt2vfrjjqgj.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.hnqzz.top/Article/details/gt2xtxusayi.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.xziqi.cn/Article/details/gt2jewibzyr.html

C#:   lock (gate) { shared++; }
来源：http://dali.svipenyu.cn/Article/details/gt2cbhgwgmp.html

[O04] 定义异步函数并等待
来源：http://dali.haohaochexian.top/Article/details/gt2trzuwgbp.html

Py:   async def f():⏎    await g()
来源：http://dali.kuanghao11.cn/Article/details/gt2kdyvhxcp.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.xinyue.icu/Article/details/gt2zhespjnl.html

JS:   async function f() { await g(); }
来源：http://dali.hysaishi.cn/Article/details/gt2dpcpxbsr.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.vqdsnc.cn/Article/details/gt2kgfgtfid.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.ydzc1.top/Article/details/gt2bupiebev.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.bjfxy.top/Article/details/gt2utyatmku.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.meibo888.top/Article/details/gt2yzuowunm.html

C#:   async Task F() { await G(); }
来源：http://dali.ivvv.top/Article/details/gt2gcytyfxu.html

[O05] 并发执行并等待全部完成
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lasxhaia.html

Py:   asyncio.gather(*tasks)
来源：http://dali.xylfe.cn/Article/details/gt2viseyslx.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.guannengcc.top/Article/details/gt2djcbrmwd.html

JS:   await Promise.all(tasks)
来源：http://dali.sxryk.cn/Article/details/gt2brirkgzm.html

TS:   await Promise.all(tasks)
来源：http://dali.nwbrower.top/Article/details/gt2jvmhblij.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.ppjwa.cn/Article/details/gt2yjhakxse.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.pengpengdd.cyou/Article/details/gt2uprgayze.html

Ruby: threads.map(&:join)
来源：http://dali.daria6918.cn/Article/details/gt2cnhmrjsf.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.meibo888.top/Article/details/gt2ndhhfksz.html

[O06] 使用进程池
来源：http://dali.birdmap.top/Article/details/gt2cvbzbezw.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.tanke756.top/Article/details/gt2juasznvn.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.cashguo.top/Article/details/gt2izpoohyz.html

JS:   // child_process / cluster 模块
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hkuzzjyv.html

TS:   // child_process / cluster 模块
来源：http://dali.feifeiyinyue.top/Article/details/gt2vsqecreu.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.jiagoushi.top/Article/details/gt2polwqdmp.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.xuetiantiany.cn/Article/details/gt2acjjhgab.html

Ruby: // fork 块
来源：http://dali.meibo888.top/Article/details/gt2bluuptvz.html

C#:   Parallel.For
来源：http://dali.zycfv.cn/Article/details/gt2cbgeuktn.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gt2ivwnwzhh.html

P. 常用工具函数
来源：http://dali.yj20258.top/Article/details/gt2dllkhzij.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gt2qzbgduvn.html

[P01] 生成 UUID
来源：http://dali.smart0.xyz/Article/details/gt2pmapnsqf.html

Py:   str(uuid.uuid4())
来源：http://dali.sysykeji.top/Article/details/gt2syjvymiv.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.cqqwz.cn/Article/details/gt2whfxvnwa.html

JS:   crypto.randomUUID()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hecuveqx.html

TS:   crypto.randomUUID()
来源：http://dali.fzhhl.top/Article/details/gt2sguixtsf.html

Java: UUID.randomUUID().toString()
来源：http://dali.redwolf501.top/Article/details/gt2gfncdtyb.html

Go:   // 用 github.com/google/uuid
来源：http://dali.smart0.xyz/Article/details/gt2kibbpgpz.html

Ruby: SecureRandom.uuid
来源：http://dali.jiagoushi.top/Article/details/gt2eaewqqfa.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhiwuduotai.top/Article/details/gt2zvlfzvmb.html

[P02] MD5 / SHA256 摘要
来源：http://dali.nwbrower.top/Article/details/gt2zfdsjgeo.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.chenlongwang.top/Article/details/gt2uesesxvl.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.yonumen.top/Article/details/gt2ksbldyjv.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.nwbrower.top/Article/details/gt2recpabgr.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.ehwqpu.com/Article/details/gt2ohyuhkfi.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zdqjudy.top/Article/details/gt2phrhvmgu.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.hnqzz.top/Article/details/gt2yxfprtxx.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.cucudq.cn/Article/details/gt2swayyyiw.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hpfjnqso.html

[P03] 生成短随机字符串
来源：http://dali.guannengcc.top/Article/details/gt2efunspmf.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.tian-w.cn/Article/details/gt2sjcebhrv.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.bjfxy.top/Article/details/gt2kwbnjumr.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.sysykeji.top/Article/details/gt2klmktcxn.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.xuetiantiany.cn/Article/details/gt2gzmddxjq.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.hnxiangtu.top/Article/details/gt2aayjjhnl.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.guowangkeji.top/Article/details/gt2xvvgxlwr.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.pycfn.com/Article/details/gt2lnlopjrf.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.redwolf501.top/Article/details/gt2ypfnpnjs.html

[P04] 求长度
来源：http://dali.guowangkeji.top/Article/details/gt2kowkjhtf.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.aizwys.cn/Article/details/gt2pnwpchwn.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jinqigfzy.top/Article/details/gt2kbswnnwv.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jinqigfzy.top/Article/details/gt2mbciaxrd.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.gzhubu.top/Article/details/gt2ewmkilab.html

Java: list.size();  map.size();  s.length()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mwsacvxt.html

Go:   len(arr);  len(m)
来源：http://dali.xinyue.icu/Article/details/gt2aspuwgky.html

Ruby: x.length;  x.size
来源：http://dali.zycfv.cn/Article/details/gt2waojbpxu.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.sweek.top/Article/details/gt2mfetdlyx.html

[P05] 判断两个对象内容是否相等
来源：http://dali.yj20258888.top/Article/details/gt2xwgfmapa.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.yueranfly.top/Article/details/gt2qxtdmmzl.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.xziqi.cn/Article/details/gt2meutdtog.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.yongpay.top/Article/details/gt2wpylxdok.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.yanxiufei.cn/Article/details/gt2ptwjlwyq.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.316326.xyz/Article/details/gt2zwjpivqa.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.kuanghao11.cn/Article/details/gt2xkhevxzl.html

Ruby: a == b
来源：http://dali.ydzc1.top/Article/details/gt2tgvtloov.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.dashuyun.cn/Article/details/gt2rdjcsthe.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.nanxuanxn.top/Article/details/gt2matlthqv.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wjwbpayb.html

PHP:  if (empty($x)) {}
来源：http://dali.tianlin.xyz/Article/details/gt2dxmyskni.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.yonumen.top/Article/details/gt2yoypxpcj.html

TS:   if (x == null) {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2lopbagsn.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.xuanzx.com/Article/details/gt2mwqvdyht.html

Go:   if x == nil {}
来源：http://dali.dianchejie.cn/Article/details/gt2qiinnqxd.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.jinqigufen.top/Article/details/gt2ucgjsnnr.html

C#:   if (x is null) {}
来源：http://dali.sxryk.cn/Article/details/gt2njtuzpwf.html

[P07] 防抖与节流
来源：http://dali.cqqwz.cn/Article/details/gt2abjoawgo.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.yj20258888.top/Article/details/gt2kbpqrove.html

PHP:  // 手写时间戳比较
来源：http://dali.yonumen.top/Article/details/gt2stxemwdd.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.pycfn.com/Article/details/gt2wmybmtbc.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.ydzc1.top/Article/details/gt2ijufyhgg.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.sysykeji.top/Article/details/gt2xggwexdy.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.ivvv.top/Article/details/gt2jxsqfqzd.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.hammf.cn/Article/details/gt2qlbtvdaa.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.meibo888.top/Article/details/gt2qgybdsrn.html

[P08] 处理浮点精度问题
来源：http://dali.yj20258.top/Article/details/gt2jdfagdbr.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhiwuduotai.top/Article/details/gt2poamdacy.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.cqqwz.cn/Article/details/gt2bprrxssd.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.c1oappe.top/Article/details/gt2cmbfbqks.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.hammf.cn/Article/details/gt2hibhfpdj.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.yueranfly.top/Article/details/gt2rihkqvng.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.fengsongda.top/Article/details/gt2tgstfvgi.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.haohaochexian.top/Article/details/gt2lynspgyd.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.svipenyu.cn/Article/details/gt2mwiselsx.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gt2nlegmmat.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.xylfe.cn/Article/details/gt2vscuyarv.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gt2rzmnmacu.html

[Q01] 创建表
来源：http://dali.guannengcc.top/Article/details/gt2wwicywkx.html

CREATE TABLE users (
来源：http://dali.sysykeji.top/Article/details/gt2voepbcap.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.cashguo.top/Article/details/gt2jnccaxdg.html

name VARCHAR(50) NOT NULL,
来源：http://dali.pycfn.com/Article/details/gt2uoairckp.html

email VARCHAR(100) UNIQUE,
来源：http://dali.ivvv.top/Article/details/gt2zcnjtmpe.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.hfpthk.cn/Article/details/gt2unwlabzj.html

);
来源：http://dali.andypj.xyz/Article/details/gt2hwxhyvwh.html

[Q02] 创建带外键的表
来源：http://dali.cashguo.top/Article/details/gt2vfwsutac.html

CREATE TABLE orders (
来源：http://dali.quarkkingdee.top/Article/details/gt2bhmunoml.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhengqikj.top/Article/details/gt2evshrtsx.html

user_id INT NOT NULL,
来源：http://dali.hnqzz.top/Article/details/gt2trzjevtf.html

amount DECIMAL(10, 2),
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2sqwticxp.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.yj20258.top/Article/details/gt2dtsnyyee.html

);
来源：http://dali.redwolf501.top/Article/details/gt2jtxnwbzd.html

[Q03] 增加列
来源：http://dali.0kj1m.cn/Article/details/gt2qbjucqdx.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.jinqigfzy.top/Article/details/gt2wjmklcec.html

[Q04] 修改列类型
来源：http://dali.snrcjt.cn/Article/details/gt2lnvmdmvm.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.xylfe.cn/Article/details/gt2xclmlwbh.html

[Q05] 重命名列
来源：http://dali.pycfn.com/Article/details/gt2noewhnyj.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.jianghu66.top/Article/details/gt2agermodt.html

[Q06] 删除列
来源：http://dali.cucudq.cn/Article/details/gt2qasayyza.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.cqqwz.cn/Article/details/gt2dkxllsfn.html

[Q07] 删除表
来源：http://dali.c1oappe.top/Article/details/gt2sxcokrgm.html

DROP TABLE IF EXISTS orders;
来源：http://dali.jinqigfzy.top/Article/details/gt2jxegiwuc.html

[Q08] 创建普通索引
来源：http://dali.redwolf501.top/Article/details/gt2adqbmxnx.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.jinqigufen.top/Article/details/gt2ynlqogyx.html

[Q09] 创建唯一索引
来源：http://dali.zdqjudy.top/Article/details/gt2lsdeutsy.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.pycfn.com/Article/details/gt2lczcfbva.html

[Q10] 插入单行
来源：http://dali.yanxiufei.cn/Article/details/gt2zyzvusmj.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.xinyue.icu/Article/details/gt2fykchcnt.html

[Q11] 一次插入多行
来源：http://dali.wangshuangyany.cn/Article/details/gt2ppeuvfgh.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.sweek.top/Article/details/gt2ghljbeds.html

[Q12] 插入后取自增 ID
来源：http://dali.jqgfzy.top/Article/details/gt2knoxytnj.html


<!-- 参考信息 -->