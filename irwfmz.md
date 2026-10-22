代发 wailian999

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mbuhwjxc.html

Ruby: warn "err"
来源：http://dali.dianchejie.cn/Article/details/gt2bisrxeiy.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.sweek.top/Article/details/gt2xsogtxke.html

[M07] 判断是否为主入口
来源：http://dali.pengpengdd.cyou/Article/details/gt2acciswxw.html

Py:   if __name__ == "__main__":
来源：http://dali.chenzaomai.com/Article/details/gt2jhdpcgvi.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.sysykeji.top/Article/details/gt2vvczhbgi.html

JS:   require.main === module
来源：http://dali.hnxiangtu.top/Article/details/gt2xkftcbfo.html

TS:   require.main === module
来源：http://dali.wangshuangyany.cn/Article/details/gt2ccnpcuxo.html

Java: public static void main(String[] args)
来源：http://dali.gaohongyu789.top/Article/details/gt2neknxddz.html

Go:   func main()
来源：http://dali.guannengcc.top/Article/details/gt2wnmiyosg.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.xinyue.icu/Article/details/gt2ujhfofdp.html

C#:   static void Main(string[] args)
来源：http://dali.zhoulong.xyz/Article/details/gt2vjaqvuee.html

[M08] 获取系统与运行时信息
来源：http://dali.feifeiyinyue.top/Article/details/gt2hxqdkfbe.html

Py:   platform.system();  platform.python_version()
来源：http://dali.yangfankeji.com/Article/details/gt2vqqqrbnw.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.0kj1m.cn/Article/details/gt2qzljmkrt.html

JS:   process.platform;  process.version
来源：http://dali.cheryme.top/Article/details/gt2bfseingo.html

TS:   process.platform;  process.version
来源：http://dali.pycfn.com/Article/details/gt2fscwpums.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.jinqigufen.top/Article/details/gt2qxvqiywj.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.jyoumei.cn/Article/details/gt2ceslhmvm.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zdqjudy.top/Article/details/gt2iozryuyn.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhengqikj.top/Article/details/gt2vuasqabm.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gt2ykbjidzo.html

N. 数据结构与算法
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yrvsezqw.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gt2nepsehax.html

[N01] 二分查找（有序数组）
来源：http://dali.shzxlz.cn/Article/details/gt2gqqidlke.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.ehwqpu.com/Article/details/gt2esnvuxhf.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.pycfn.com/Article/details/gt2ljbkrape.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.birdmap.top/Article/details/gt2hurxxpej.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.kuanghao11.cn/Article/details/gt2dqasmrbe.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.jinqigufen.top/Article/details/gt2safpmigi.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.cdnleiting.top/Article/details/gt2yapuiarm.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.jianghu66.top/Article/details/gt2pneutqwv.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.ppjwa.cn/Article/details/gt2rakwjvbl.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.pycfn.com/Article/details/gt2rwlpeayh.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.bjfxy.top/Article/details/gt2tyzebthu.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.ydzc1.top/Article/details/gt2gnluirdm.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.vqdsnc.cn/Article/details/gt2jvwweyhy.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhiwuduotai.top/Article/details/gt2eqyccpur.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhengqikj.top/Article/details/gt2mapppcre.html

Go:   slices.Sort(arr)
来源：http://dali.fzhhl.top/Article/details/gt2nrnugvjo.html

Ruby: arr.sort
来源：http://dali.jiagoushi.top/Article/details/gt2uksfnvig.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.feifeiyinyue.top/Article/details/gt2rlngijos.html

[N03] 快速排序（分治示例）
来源：http://dali.cashguo.top/Article/details/gt2zjlhuthj.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.aizwys.cn/Article/details/gt2pnialqnv.html

PHP:  // 递归实现，或用 usort
来源：http://dali.nanxinkj.top/Article/details/gt2rdwudklm.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.fzhhl.top/Article/details/gt2eldpkdhu.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.ivvv.top/Article/details/gt2qfrakfld.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhoulong.xyz/Article/details/gt2yvxorfll.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.jyoumei.cn/Article/details/gt2xanvvsju.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.wangdashe.top/Article/details/gt2kjryxcgo.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.daxiang520.top/Article/details/gt2kzmxjsds.html

[N04] 斐波那契数列
来源：http://dali.daria6918.cn/Article/details/gt2tausfzev.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhongyouzk.top/Article/details/gt2fbynbrwk.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.meibo888.top/Article/details/gt2kmchubzl.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cyyjojus.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.aibaodan.cn/Article/details/gt2rnzqvxdi.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bjzjhswf.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.xziqi.cn/Article/details/gt2zcbornii.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rqtjkufc.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.vqdsnc.cn/Article/details/gt2wyoykjfp.html

[N05] 最大公约数
来源：http://dali.yangfankeji.com/Article/details/gt2nnfndzqb.html

Py:   math.gcd(a, b)
来源：http://dali.ybcxt.top/Article/details/gt2hicdpqtp.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2nnyhxriq.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zdqjudy.top/Article/details/gt2hlrstljk.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.svipenyu.cn/Article/details/gt2qkoopkrj.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.bjfxy.top/Article/details/gt2uatjlqfp.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhengqikj.top/Article/details/gt2jwxqxpbz.html

Ruby: a.gcd(b)
来源：http://dali.ydzc1.top/Article/details/gt2afuflljz.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.guannengcc.top/Article/details/gt2bowunxbr.html

[N06] 判断回文字符串
来源：http://dali.zhoulong.xyz/Article/details/gt2ctmkbgcd.html

Py:   s == s[::-1]
来源：http://dali.jinqigufen.top/Article/details/gt2shanmwmq.html

PHP:  $s === strrev($s);
来源：http://dali.feifeiyinyue.top/Article/details/gt2hgybigga.html

JS:   s === [...s].reverse().join("")
来源：http://dali.xylfe.cn/Article/details/gt2fvigsyul.html

TS:   s === [...s].reverse().join("")
来源：http://dali.jianghu66.top/Article/details/gt2sgcatjko.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.yj20258.top/Article/details/gt2ivvgcqsp.html

Go:   // 双指针从两端比较
来源：http://dali.wangshuangyany.cn/Article/details/gt2hhtglzwz.html

Ruby: s == s.reverse
来源：http://dali.jiagoushi.top/Article/details/gt2kvenchak.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.haohaochexian.top/Article/details/gt2kcgdfajs.html

[N07] 两数之和（返回下标）
来源：http://dali.c1oappe.top/Article/details/gt2ybhcaptr.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.sxryk.cn/Article/details/gt2hihnvsdn.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tsuufcaa.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhengqikj.top/Article/details/gt2cafyqltr.html

TS:   // 手写 Map<string, number>
来源：http://dali.jqgfzy.top/Article/details/gt2wchmccob.html

Java: // 手写 HashMap
来源：http://dali.wangshuangyany.cn/Article/details/gt2macipvkf.html

Go:   // 手写 map[int]int
来源：http://dali.zycfv.cn/Article/details/gt2xutntwic.html

Ruby: // 手写 Hash
来源：http://dali.vqdsnc.cn/Article/details/gt2svfurqsg.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.daxiang520.top/Article/details/gt2zycckkgn.html

[N08] 生成全排列
来源：http://dali.zhiwuduotai.top/Article/details/gt2ewhixdrv.html

Py:   itertools.permutations(arr)
来源：http://dali.daxiang520.top/Article/details/gt2bewvrvtq.html

PHP:  // 手写递归交换
来源：http://dali.yanxiufei.cn/Article/details/gt2tmwapxba.html

JS:   // 手写回溯递归
来源：http://dali.redwolf501.top/Article/details/gt2micozeqg.html

TS:   // 手写回溯递归
来源：http://dali.vqdsnc.cn/Article/details/gt2giiiujru.html

Java: // 手写回溯递归
来源：http://dali.dianchejie.cn/Article/details/gt2jnyewhgo.html

Go:   // 手写回溯递归
来源：http://dali.zhiwuduotai.top/Article/details/gt2hybbqyqf.html

Ruby: arr.permutation.to_a
来源：http://dali.hnxiangtu.top/Article/details/gt2dmivbxom.html

C#:   // 手写回溯递归
来源：http://dali.zhixingplan.top/Article/details/gt2ynmfrpmi.html

[N09] 栈与队列
来源：http://dali.jlsjyb.cn/Article/details/gt2vvmmsxji.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.ydzc1.top/Article/details/gt2tcmshhcd.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.quarkkingdee.top/Article/details/gt2bqqplzvq.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zycfv.cn/Article/details/gt2wjstcgcf.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.hnqzz.top/Article/details/gt2pcqfjcci.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.yuanzhike.top/Article/details/gt2sqojqmee.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.gaohongyu789.top/Article/details/gt2onqmckri.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.ybcxt.top/Article/details/gt2lnkktval.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.daxiang520.top/Article/details/gt2hupeholk.html

[N10] 链表节点定义
来源：http://dali.jinqigfzy.top/Article/details/gt2fvalmumq.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.gzhubu.top/Article/details/gt2ydmqflmp.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.c1oappe.top/Article/details/gt2lyeajnyh.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.aizwys.cn/Article/details/gt2xjevqakv.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.hongshengwenyu.top/Article/details/gt2cvrahaik.html

Java: class Node { int v; Node next; }
来源：http://dali.jyoumei.cn/Article/details/gt2wsfofiej.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.aizwys.cn/Article/details/gt2qbfdyjfn.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.wangshuangyany.cn/Article/details/gt2xsbvtmso.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.gotoacloud.top/Article/details/gt2znrhhlpz.html

[N11] 二叉树中序遍历
来源：http://dali.jinqigufen.top/Article/details/gt2tjckgslv.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.yueranfly.top/Article/details/gt2vddgcair.html

PHP:  // 手写递归函数
来源：http://dali.hfpthk.cn/Article/details/gt2cldmbroh.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.c1oappe.top/Article/details/gt2xyoxsriz.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.ehwqpu.com/Article/details/gt2mtkgdhpb.html

Java: // 手写递归
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rplphvtz.html

Go:   // 手写递归
来源：http://dali.jianghu66.top/Article/details/gt2owbucfux.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.chenzaomai.com/Article/details/gt2szzgorau.html

C#:   // 手写递归
来源：http://dali.yanxiufei.cn/Article/details/gt2mlastfdz.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.andypj.xyz/Article/details/gt2skqqdkct.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhixingplan.top/Article/details/gt2tszkpfuv.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.cdnleiting.top/Article/details/gt2nilzascg.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.havefunace.top/Article/details/gt2xxximzwj.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.hysaishi.cn/Article/details/gt2gnddbglh.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.haohaochexian.top/Article/details/gt2nifwtkgr.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.xylfe.cn/Article/details/gt2clcszihg.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.jiagoushi.top/Article/details/gt2noonjiqw.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.cheryme.top/Article/details/gt2ednjrcso.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2ttxfqlbd.html

O. 并发与异步
来源：http://dali.hysaishi.cn/Article/details/gt2zwmdceqz.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gt2usszwotf.html

[O01] 启动一个线程
来源：http://dali.vqdsnc.cn/Article/details/gt2ngttrfpc.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.daxiang520.top/Article/details/gt2uchbiwys.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.316326.xyz/Article/details/gt2kezqqywq.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.yangfankeji.com/Article/details/gt2ulyhunpv.html

TS:   // 同 JS
来源：http://dali.smart0.xyz/Article/details/gt2vrllqyvk.html

Java: new Thread(() -> f()).start()
来源：http://dali.yvedp.cn/Article/details/gt2rgtuukvi.html

Go:   go f()
来源：http://dali.tianlin.xyz/Article/details/gt2npvqbock.html

Ruby: Thread.new { f }
来源：http://dali.tian-w.cn/Article/details/gt2rkioynih.html

C#:   Task.Run(() => F());
来源：http://dali.smart0.xyz/Article/details/gt2lfykozfw.html

[O02] 使用线程池
来源：http://dali.sxryk.cn/Article/details/gt2plgirsax.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.yonumen.top/Article/details/gt2ulihyfhl.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.fzhhl.top/Article/details/gt2eymuuaoe.html

JS:   // worker_threads 线程池
来源：http://dali.yueranfly.top/Article/details/gt2nkqeidch.html

TS:   // worker_threads 线程池
来源：http://dali.quarkkingdee.top/Article/details/gt2okhcgidj.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.svipenyu.cn/Article/details/gt2esssjmcu.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.yj202588.top/Article/details/gt2nktwyzar.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.redwolf501.top/Article/details/gt2pfnflrhm.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.jqgfzy.top/Article/details/gt2ibvxverz.html

[O03] 加锁保护共享数据
来源：http://dali.yongpay.top/Article/details/gt2muuxwnmx.html

Py:   with lock: shared += 1
来源：http://dali.meibo888.top/Article/details/gt2pchukuca.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.bjfxy.top/Article/details/gt2uzhffdms.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.smart0.xyz/Article/details/gt2eubemxoa.html

TS:   // 同 JS
来源：http://dali.fzhhl.top/Article/details/gt2yepuiouh.html

Java: synchronized (this) { shared++; }
来源：http://dali.smart0.xyz/Article/details/gt2czcithse.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.sweek.top/Article/details/gt2xqrwsljw.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.guowangkeji.top/Article/details/gt2bzzeykyk.html

C#:   lock (gate) { shared++; }
来源：http://dali.yuxming.cn/Article/details/gt2zshwfxqr.html

[O04] 定义异步函数并等待
来源：http://dali.jyoumei.cn/Article/details/gt2qbusjgzq.html

Py:   async def f():⏎    await g()
来源：http://dali.jqgufenzy.top/Article/details/gt2rzvrgnog.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.wangshuangyany.cn/Article/details/gt2sjmszgto.html

JS:   async function f() { await g(); }
来源：http://dali.hfpthk.cn/Article/details/gt2uiahcjre.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.guowangkeji.top/Article/details/gt2zfwdkxzi.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.kuanghao11.cn/Article/details/gt2gpusjxpe.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.jyoumei.cn/Article/details/gt2evvnuodr.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.feifeiyinyue.top/Article/details/gt2ogcxuvlr.html

C#:   async Task F() { await G(); }
来源：http://dali.sxryk.cn/Article/details/gt2aogookrf.html

[O05] 并发执行并等待全部完成
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pagpuklu.html

Py:   asyncio.gather(*tasks)
来源：http://dali.yvedp.cn/Article/details/gt2hdyczqty.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.aizwys.cn/Article/details/gt2dvawdktc.html

JS:   await Promise.all(tasks)
来源：http://dali.havefunace.top/Article/details/gt2eepdobwi.html

TS:   await Promise.all(tasks)
来源：http://dali.0kj1m.cn/Article/details/gt2tcupwlwp.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.yuxming.cn/Article/details/gt2dyobpkuw.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.xinyue.icu/Article/details/gt2zhcyvcns.html

Ruby: threads.map(&:join)
来源：http://dali.nanxuanxn.top/Article/details/gt2slfahydn.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.cucudq.cn/Article/details/gt2qfyjclbf.html

[O06] 使用进程池
来源：http://dali.birdmap.top/Article/details/gt2cuisdqqj.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.iojbl.cn/Article/details/gt2zoinypgm.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.jqgufenzy.top/Article/details/gt2bwhcjpql.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2pkmeczgy.html

TS:   // child_process / cluster 模块
来源：http://dali.pengpengdd.cyou/Article/details/gt2mlmnmykx.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhoulong.xyz/Article/details/gt2fkibnduw.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhoulong.xyz/Article/details/gt2pzgvjibd.html

Ruby: // fork 块
来源：http://dali.hnqzz.top/Article/details/gt2wvbhtmeg.html

C#:   Parallel.For
来源：http://dali.gzhubu.top/Article/details/gt2ngwfzetn.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gt2yxzffagn.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2agsjaxwp.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gt2rovzetdi.html

[P01] 生成 UUID
来源：http://dali.tianlin.xyz/Article/details/gt2fqecosdo.html

Py:   str(uuid.uuid4())
来源：http://dali.hfpthk.cn/Article/details/gt2wzahfhgn.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2gifoduae.html

JS:   crypto.randomUUID()
来源：http://dali.guowangkeji.top/Article/details/gt2ofqaiusb.html

TS:   crypto.randomUUID()
来源：http://dali.zdqjudy.top/Article/details/gt2isynlebc.html

Java: UUID.randomUUID().toString()
来源：http://dali.tianlin.xyz/Article/details/gt2uuawavis.html

Go:   // 用 github.com/google/uuid
来源：http://dali.jlsjyb.cn/Article/details/gt2xtvplnqr.html

Ruby: SecureRandom.uuid
来源：http://dali.hnqzz.top/Article/details/gt2jiymplro.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.hnqzz.top/Article/details/gt2acoiitfp.html

[P02] MD5 / SHA256 摘要
来源：http://dali.yj20258.top/Article/details/gt2wjrpkyju.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.xuanzx.com/Article/details/gt2zdbncjfv.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rxcriong.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.daxiang520.top/Article/details/gt2cjdqcjwm.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.yuanzhike.top/Article/details/gt2wkhdezsh.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.ehwqpu.com/Article/details/gt2etxmhgym.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.smart0.xyz/Article/details/gt2oxiuzmfs.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.cashguo.top/Article/details/gt2sknejcmw.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.jyoumei.cn/Article/details/gt2ekrgdgrl.html

[P03] 生成短随机字符串
来源：http://dali.sysykeji.top/Article/details/gt2qcdngdix.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.wangshuangyany.cn/Article/details/gt2cysmwiwv.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.xuetiantiany.cn/Article/details/gt2azqurdju.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fmiuvycd.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.wangdashe.top/Article/details/gt2erpfwhuy.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.snrcjt.cn/Article/details/gt2zkfvngpd.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.nwbrower.top/Article/details/gt2zpxjynpj.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.cheryme.top/Article/details/gt2akbywxee.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.bjfxy.top/Article/details/gt2ncdeyryj.html

[P04] 求长度
来源：http://dali.tian-w.cn/Article/details/gt2yotcwapv.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhiwuduotai.top/Article/details/gt2xgstenql.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.aibaodan.cn/Article/details/gt2amjzofyv.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.andypj.xyz/Article/details/gt2juhuvrjr.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.quarkkingdee.top/Article/details/gt2zcbocxbf.html

Java: list.size();  map.size();  s.length()
来源：http://dali.yueranfly.top/Article/details/gt2tiftqvts.html

Go:   len(arr);  len(m)
来源：http://dali.316326.xyz/Article/details/gt2ngcvcjlu.html

Ruby: x.length;  x.size
来源：http://dali.ehwqpu.com/Article/details/gt2jdycmxvh.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2evlodmue.html

[P05] 判断两个对象内容是否相等
来源：http://dali.hnqzz.top/Article/details/gt2mftcnvmm.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ozfimaka.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.ivvv.top/Article/details/gt2nytifisu.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.jianghu66.top/Article/details/gt2nwnvglso.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.chenjidiqi.icu/Article/details/gt2xtagtsvz.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.yj20258.top/Article/details/gt2pzbltqrc.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.wangdashe.top/Article/details/gt2toqexuof.html

Ruby: a == b
来源：http://dali.cheryme.top/Article/details/gt2pniijeyu.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.sweek.top/Article/details/gt2gjywtzqj.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.jinqigufen.top/Article/details/gt2csdoonaf.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.wangdashe.top/Article/details/gt2tlzkyqya.html

PHP:  if (empty($x)) {}
来源：http://dali.jqgufenzy.top/Article/details/gt2nwzoiqzj.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zycfv.cn/Article/details/gt2xwdademl.html

TS:   if (x == null) {}
来源：http://dali.hnqzz.top/Article/details/gt2hgcmvnfs.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2qvcxtxya.html

Go:   if x == nil {}
来源：http://dali.dashuyun.cn/Article/details/gt2soqulwqw.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.guowangkeji.top/Article/details/gt2ozlgeuhg.html

C#:   if (x is null) {}
来源：http://dali.jlsjyb.cn/Article/details/gt2qqoitsbd.html

[P07] 防抖与节流
来源：http://dali.tanke756.top/Article/details/gt2khbubukq.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.feifeiyinyue.top/Article/details/gt2fbddkoax.html

PHP:  // 手写时间戳比较
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qpeziwzm.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.quarkkingdee.top/Article/details/gt2ptsmxfgu.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.ppjwa.cn/Article/details/gt2vrwyznrv.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.ydzc1.top/Article/details/gt2luqjshvo.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.cashguo.top/Article/details/gt2nuvqyltv.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.cashguo.top/Article/details/gt2piafctgb.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.jinqigfzy.top/Article/details/gt2zohsulfh.html

[P08] 处理浮点精度问题
来源：http://dali.zhengqikj.top/Article/details/gt2krjhqkeu.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.jinqigfzy.top/Article/details/gt2bguvxriu.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhiwuduotai.top/Article/details/gt2gadpnbqw.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.jqgfzy.top/Article/details/gt2wpktltdn.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.xziqi.cn/Article/details/gt2fokqbghj.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.gogol.net.cn/Article/details/gt2xwbtyuuk.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.jinqigufen.top/Article/details/gt2axnpyfyv.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ewbzqmfz.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.wangdashe.top/Article/details/gt2dfikhnld.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2glzrvrgc.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.shangyingyoupin.top/Article/details/gt2hhygjlyj.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gt2lydpkfps.html

[Q01] 创建表
来源：http://dali.nanxuanxn.top/Article/details/gt2neydlwzu.html

CREATE TABLE users (
来源：http://dali.yongpay.top/Article/details/gt2lvqofqnf.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yj202588.top/Article/details/gt2metdjsmg.html

name VARCHAR(50) NOT NULL,
来源：http://dali.yangfankeji.com/Article/details/gt2hictyhxy.html

email VARCHAR(100) UNIQUE,
来源：http://dali.vqdsnc.cn/Article/details/gt2cubhdvxw.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.yueranfly.top/Article/details/gt2lbenpzgl.html

);
来源：http://dali.yvedp.cn/Article/details/gt2lbqcptvq.html

[Q02] 创建带外键的表
来源：http://dali.jlsjyb.cn/Article/details/gt2evfmtphy.html

CREATE TABLE orders (
来源：http://dali.cheryme.top/Article/details/gt2ixcpbmgn.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhixingplan.top/Article/details/gt2agqpeevf.html

user_id INT NOT NULL,
来源：http://dali.cdnleiting.top/Article/details/gt2itnhywbt.html

amount DECIMAL(10, 2),
来源：http://dali.pengpengdd.cyou/Article/details/gt2udkwjhsw.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.xziqi.cn/Article/details/gt2ynhvnhzz.html

);
来源：http://dali.chenzaomai.com/Article/details/gt2olzbjpmy.html

[Q03] 增加列
来源：http://dali.hysaishi.cn/Article/details/gt2rovbhoep.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.yvedp.cn/Article/details/gt2gcysbbhz.html

[Q04] 修改列类型
来源：http://dali.jianghu66.top/Article/details/gt2gfsqhwzw.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.daxiang520.top/Article/details/gt2inrcveay.html

[Q05] 重命名列
来源：http://dali.sysykeji.top/Article/details/gt2ltukwftu.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhixingplan.top/Article/details/gt2ehxapxjb.html

[Q06] 删除列
来源：http://dali.yonumen.top/Article/details/gt2aituitbz.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.yj202588.top/Article/details/gt2qasdosip.html

[Q07] 删除表
来源：http://dali.cucudq.cn/Article/details/gt2wwehxvof.html

DROP TABLE IF EXISTS orders;
来源：http://dali.jyoumei.cn/Article/details/gt2tiaocddz.html

[Q08] 创建普通索引
来源：http://dali.xuanzx.com/Article/details/gt2yselemee.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.yj202588.top/Article/details/gt2wkebjcsy.html

[Q09] 创建唯一索引
来源：http://dali.hywenlv.cn/Article/details/gt2emflcjcv.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.nanxinkj.top/Article/details/gt2ulghmmrf.html

[Q10] 插入单行
来源：http://dali.xinyue.icu/Article/details/gt2ljghycbd.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.tian-w.cn/Article/details/gt2eowdquti.html

[Q11] 一次插入多行
来源：http://dali.sxryk.cn/Article/details/gt2qapyxzzi.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.yuxming.cn/Article/details/gt2ejlpfndv.html

[Q12] 插入后取自增 ID
来源：http://dali.ydzc1.top/Article/details/gt2ztxacrko.html


<!-- 参考信息 -->