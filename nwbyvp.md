代发 wailian999

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.hfpthk.cn/Article/details/gt2vvirdlum.html

Ruby: warn "err"
来源：http://dali.zycfv.cn/Article/details/gt2pfwvbjga.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.svipenyu.cn/Article/details/gt2vcpnxvnb.html

[M07] 判断是否为主入口
来源：http://dali.xuanzx.com/Article/details/gt2pzcjknfk.html

Py:   if __name__ == "__main__":
来源：http://dali.ivvv.top/Article/details/gt2jcanjfas.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.hammf.cn/Article/details/gt2vvvqsyqp.html

JS:   require.main === module
来源：http://dali.cucudq.cn/Article/details/gt2ckyblsnt.html

TS:   require.main === module
来源：http://dali.yanxiufei.cn/Article/details/gt2jbmgomgt.html

Java: public static void main(String[] args)
来源：http://dali.vqdsnc.cn/Article/details/gt2jnjlbgey.html

Go:   func main()
来源：http://dali.smart0.xyz/Article/details/gt2omktbxou.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.yonumen.top/Article/details/gt2pxpjbmkk.html

C#:   static void Main(string[] args)
来源：http://dali.vqdsnc.cn/Article/details/gt2kvsazmjx.html

[M08] 获取系统与运行时信息
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zmakabva.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhongyouzk.top/Article/details/gt2ligagnan.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.316326.xyz/Article/details/gt2qconisio.html

JS:   process.platform;  process.version
来源：http://dali.sweek.top/Article/details/gt2stgewgno.html

TS:   process.platform;  process.version
来源：http://dali.gogol.net.cn/Article/details/gt2vbdxgogm.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.yj202588.top/Article/details/gt2szbmpwen.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.hnxiangtu.top/Article/details/gt2zndmzmyh.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.havefunace.top/Article/details/gt2ctcxthpx.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.aibaodan.cn/Article/details/gt2ntnxbfvo.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nwslgrkh.html

N. 数据结构与算法
来源：http://dali.aizwys.cn/Article/details/gt2ypnxwfbt.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2hdqvvyhx.html

[N01] 二分查找（有序数组）
来源：http://dali.jinqigufen.top/Article/details/gt2wwrftikj.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.yuanzhike.top/Article/details/gt2vbflktdy.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.hongshengwenyu.top/Article/details/gt2mgxxnlkt.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.chenjidiqi.icu/Article/details/gt2hilwwqru.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhixingplan.top/Article/details/gt2exuyeaxk.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rnaibsua.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhongyouzk.top/Article/details/gt2xxrhupgm.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dkycomqy.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.c1oappe.top/Article/details/gt2pdmahhju.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.yj202588.top/Article/details/gt2aokhofqp.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jqgfzy.top/Article/details/gt2zmsgpeso.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.nanxinkj.top/Article/details/gt2ssxxwwen.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhiwuduotai.top/Article/details/gt2dthfhigg.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.tian-w.cn/Article/details/gt2vsmkawpc.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.cqqwz.cn/Article/details/gt2fpustssm.html

Go:   slices.Sort(arr)
来源：http://dali.316326.xyz/Article/details/gt2bbhwxzoa.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2brrvymdr.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hreosrak.html

[N03] 快速排序（分治示例）
来源：http://dali.chenjidiqi.icu/Article/details/gt2dponsbfb.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhixingplan.top/Article/details/gt2jgfwtrmv.html

PHP:  // 递归实现，或用 usort
来源：http://dali.0kj1m.cn/Article/details/gt2xyhxoorz.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yuxming.cn/Article/details/gt2hicaxdga.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.redwolf501.top/Article/details/gt2jkcmsxsr.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.yanxiufei.cn/Article/details/gt2btegcduw.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.wangdashe.top/Article/details/gt2lydaxkbq.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.pycfn.com/Article/details/gt2tqozqwdt.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.gaohongyu789.top/Article/details/gt2dlhtskea.html

[N04] 斐波那契数列
来源：http://dali.daxiang520.top/Article/details/gt2recgkkdm.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.smart0.xyz/Article/details/gt2gjarznpc.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.yj20258.top/Article/details/gt2fmwjmqnf.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.nwbrower.top/Article/details/gt2pxjqevxf.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.nanxinkj.top/Article/details/gt2ggsofxas.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.hfpthk.cn/Article/details/gt2blciykji.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.yuanzhike.top/Article/details/gt2gwzlzfkm.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.cheryme.top/Article/details/gt2jwvtakim.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.nanxuanxn.top/Article/details/gt2cphtsstr.html

[N05] 最大公约数
来源：http://dali.nanxinkj.top/Article/details/gt2jrlcbkol.html

Py:   math.gcd(a, b)
来源：http://dali.gzhubu.top/Article/details/gt2dgvklwlc.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.hammf.cn/Article/details/gt2fcqpecjh.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.sysykeji.top/Article/details/gt2ioojfkew.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.chenzaomai.com/Article/details/gt2ijkrnjmi.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.gotoacloud.top/Article/details/gt2uqzccqlz.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.0kj1m.cn/Article/details/gt2fxtmjqxz.html

Ruby: a.gcd(b)
来源：http://dali.xinyue.icu/Article/details/gt2xkiascle.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.xinyue.icu/Article/details/gt2ossxpbwl.html

[N06] 判断回文字符串
来源：http://dali.kuanghao11.cn/Article/details/gt2iltarawe.html

Py:   s == s[::-1]
来源：http://dali.hfpthk.cn/Article/details/gt2scizafsl.html

PHP:  $s === strrev($s);
来源：http://dali.pycfn.com/Article/details/gt2svpkjysw.html

JS:   s === [...s].reverse().join("")
来源：http://dali.shuidangran.top/Article/details/gt2naduhvbp.html

TS:   s === [...s].reverse().join("")
来源：http://dali.mhx1999.top/Article/details/gt2vfmovftd.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.dashuyun.cn/Article/details/gt2jjrylqou.html

Go:   // 双指针从两端比较
来源：http://dali.havefunace.top/Article/details/gt2dbbvfvdf.html

Ruby: s == s.reverse
来源：http://dali.shuidangran.top/Article/details/gt2gvbwqwta.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.smart0.xyz/Article/details/gt2vccqwfvk.html

[N07] 两数之和（返回下标）
来源：http://dali.wangdashe.top/Article/details/gt2qmiepulj.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.cqqwz.cn/Article/details/gt2keycnspe.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.feifeiyinyue.top/Article/details/gt2irqupyst.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.pengpengdd.cyou/Article/details/gt2eqaynuqg.html

TS:   // 手写 Map<string, number>
来源：http://dali.yonumen.top/Article/details/gt2lkgeeter.html

Java: // 手写 HashMap
来源：http://dali.sysykeji.top/Article/details/gt2eyqiyywd.html

Go:   // 手写 map[int]int
来源：http://dali.ppjwa.cn/Article/details/gt2qkeddbpx.html

Ruby: // 手写 Hash
来源：http://dali.nanxuanxn.top/Article/details/gt2dybrcyvq.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.pengpengdd.cyou/Article/details/gt2cdiuzbns.html

[N08] 生成全排列
来源：http://dali.hnxiangtu.top/Article/details/gt2vgqvohbd.html

Py:   itertools.permutations(arr)
来源：http://dali.birdmap.top/Article/details/gt2jmygdgli.html

PHP:  // 手写递归交换
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yhrebhrd.html

JS:   // 手写回溯递归
来源：http://dali.cashguo.top/Article/details/gt2tpqwjmrx.html

TS:   // 手写回溯递归
来源：http://dali.iojbl.cn/Article/details/gt2msduxypr.html

Java: // 手写回溯递归
来源：http://dali.yj20258888.top/Article/details/gt2iuppyetr.html

Go:   // 手写回溯递归
来源：http://dali.shangyingyoupin.top/Article/details/gt2jepjemxb.html

Ruby: arr.permutation.to_a
来源：http://dali.yj20258.top/Article/details/gt2gfbalqpo.html

C#:   // 手写回溯递归
来源：http://dali.hnqzz.top/Article/details/gt2khmexvxh.html

[N09] 栈与队列
来源：http://dali.yangfankeji.com/Article/details/gt2dyejuxfn.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.hfpthk.cn/Article/details/gt2klknhkdz.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cjhsszss.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.daria6918.cn/Article/details/gt2aebpuzws.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.chenlongwang.top/Article/details/gt2izouiqmo.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.hysaishi.cn/Article/details/gt2rbeuqpqi.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.iojbl.cn/Article/details/gt2kaunkbly.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.feifeiyinyue.top/Article/details/gt2ahjufduk.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.c1oappe.top/Article/details/gt2xjjmhkkc.html

[N10] 链表节点定义
来源：http://dali.hnqzz.top/Article/details/gt2rdljklce.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.9152youxi.cn/Article/details/gt2ybblrpvw.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.nanxuanxn.top/Article/details/gt2dtwjxptg.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.jianghu66.top/Article/details/gt2ouryoion.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.yongpay.top/Article/details/gt2ugfoiaio.html

Java: class Node { int v; Node next; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zrmufhfl.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zycfv.cn/Article/details/gt2cxieuwxx.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.sxryk.cn/Article/details/gt2lwmqzzbu.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2prymromx.html

[N11] 二叉树中序遍历
来源：http://dali.shangyingyoupin.top/Article/details/gt2fmejayhh.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.shuidangran.top/Article/details/gt2sehqdmhe.html

PHP:  // 手写递归函数
来源：http://dali.shuidangran.top/Article/details/gt2dkyxrjds.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.0kj1m.cn/Article/details/gt2njfwdlao.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yangfankeji.com/Article/details/gt2euvoyusi.html

Java: // 手写递归
来源：http://dali.zhiwuduotai.top/Article/details/gt2ethflvie.html

Go:   // 手写递归
来源：http://dali.tian-w.cn/Article/details/gt2ogzjezcl.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.xinyue.icu/Article/details/gt2ikfjasyp.html

C#:   // 手写递归
来源：http://dali.shanyushiyangtech.top/Article/details/gt2sdybumdh.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xkkrynrl.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.daria6918.cn/Article/details/gt2ucuqmbii.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2delpoldc.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.gotoacloud.top/Article/details/gt2ocrtxggc.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.daria6918.cn/Article/details/gt2tjjyqtvi.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.wangshuangyany.cn/Article/details/gt2mmkpljde.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.dashuyun.cn/Article/details/gt2ixhxfbra.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.yanxiufei.cn/Article/details/gt2mvzaelya.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhiwuduotai.top/Article/details/gt2egdzwehe.html

================================================================================
来源：http://dali.sweek.top/Article/details/gt2repmvsau.html

O. 并发与异步
来源：http://dali.sufxvd.cn/Article/details/gt2olhfches.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gt2dqezbkfx.html

[O01] 启动一个线程
来源：http://dali.havefunace.top/Article/details/gt2ilxvgooh.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.vqdsnc.cn/Article/details/gt2nimpkcey.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.gaohongyu789.top/Article/details/gt2igyitafg.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.ydzc1.top/Article/details/gt2wxjfbxxz.html

TS:   // 同 JS
来源：http://dali.birdmap.top/Article/details/gt2tbpnqqxw.html

Java: new Thread(() -> f()).start()
来源：http://dali.yangfankeji.com/Article/details/gt2zeuliqjk.html

Go:   go f()
来源：http://dali.yuanzhike.top/Article/details/gt2ladzxwmh.html

Ruby: Thread.new { f }
来源：http://dali.dashuyun.cn/Article/details/gt2oqlucrvf.html

C#:   Task.Run(() => F());
来源：http://dali.vqdsnc.cn/Article/details/gt2vmvjlzeb.html

[O02] 使用线程池
来源：http://dali.gaohongyu789.top/Article/details/gt2nzbszljy.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.bjfxy.top/Article/details/gt2zjmlgnff.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.xuetiantiany.cn/Article/details/gt2bxvbsffb.html

JS:   // worker_threads 线程池
来源：http://dali.yuxming.cn/Article/details/gt2yvfrngmt.html

TS:   // worker_threads 线程池
来源：http://dali.daria6918.cn/Article/details/gt2mmksfrjz.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.shuidangran.top/Article/details/gt2otomyfpm.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.tianlin.xyz/Article/details/gt2hofxyblx.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhengqikj.top/Article/details/gt2geyngpie.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.cqqwz.cn/Article/details/gt2mpelyxhv.html

[O03] 加锁保护共享数据
来源：http://dali.cheryme.top/Article/details/gt2fqlktwso.html

Py:   with lock: shared += 1
来源：http://dali.kuanghao11.cn/Article/details/gt2ghqbyimp.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mbkmiykb.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.xuetiantiany.cn/Article/details/gt2ikkwkwip.html

TS:   // 同 JS
来源：http://dali.xziqi.cn/Article/details/gt2geqfbxcd.html

Java: synchronized (this) { shared++; }
来源：http://dali.cdnleiting.top/Article/details/gt2gfeztlsk.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.vqdsnc.cn/Article/details/gt2ewmcczpq.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.yongpay.top/Article/details/gt2hlmvivik.html

C#:   lock (gate) { shared++; }
来源：http://dali.gotoacloud.top/Article/details/gt2xzguaowa.html

[O04] 定义异步函数并等待
来源：http://dali.fzhhl.top/Article/details/gt2tliltnyo.html

Py:   async def f():⏎    await g()
来源：http://dali.shzxlz.cn/Article/details/gt2qxbxeelf.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.gogol.net.cn/Article/details/gt2wpfhacbo.html

JS:   async function f() { await g(); }
来源：http://dali.wangdashe.top/Article/details/gt2elkytbwp.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.yj20258.top/Article/details/gt2xrynjqxr.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.haohaochexian.top/Article/details/gt2oorkuanv.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.xuanzx.com/Article/details/gt2gjksrzsv.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.xziqi.cn/Article/details/gt2qbwclegk.html

C#:   async Task F() { await G(); }
来源：http://dali.yj20258888.top/Article/details/gt2mgeyoohf.html

[O05] 并发执行并等待全部完成
来源：http://dali.chenlongwang.top/Article/details/gt2jafuyzlk.html

Py:   asyncio.gather(*tasks)
来源：http://dali.tanke756.top/Article/details/gt2mdukzclp.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pdlbxogv.html

JS:   await Promise.all(tasks)
来源：http://dali.tianlin.xyz/Article/details/gt2bwdkqbpy.html

TS:   await Promise.all(tasks)
来源：http://dali.bjfxy.top/Article/details/gt2fmcbpqjw.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.shzxlz.cn/Article/details/gt2retimryl.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.yvedp.cn/Article/details/gt2ugcjdtta.html

Ruby: threads.map(&:join)
来源：http://dali.redwolf501.top/Article/details/gt2ddrmtosy.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.chenlongwang.top/Article/details/gt2eanzapsb.html

[O06] 使用进程池
来源：http://dali.yuxming.cn/Article/details/gt2gifmnoaa.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.hnqzz.top/Article/details/gt2fvjymehp.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.dashuyun.cn/Article/details/gt2pcoxokly.html

JS:   // child_process / cluster 模块
来源：http://dali.yuanzhike.top/Article/details/gt2qeurbhmy.html

TS:   // child_process / cluster 模块
来源：http://dali.xuanzx.com/Article/details/gt2sekrmwov.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.wangshuangyany.cn/Article/details/gt2segexcat.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.xziqi.cn/Article/details/gt2cmyxrwpk.html

Ruby: // fork 块
来源：http://dali.aizwys.cn/Article/details/gt2ckjftrrf.html

C#:   Parallel.For
来源：http://dali.yonumen.top/Article/details/gt2xbqfrasd.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gt2tftxiiie.html

P. 常用工具函数
来源：http://dali.quarkkingdee.top/Article/details/gt2dgbyofht.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gt2khmdpebh.html

[P01] 生成 UUID
来源：http://dali.pycfn.com/Article/details/gt2wazppayf.html

Py:   str(uuid.uuid4())
来源：http://dali.daria6918.cn/Article/details/gt2tezyrihg.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.fzhhl.top/Article/details/gt2xgiipuqu.html

JS:   crypto.randomUUID()
来源：http://dali.iojbl.cn/Article/details/gt2mfgocgyt.html

TS:   crypto.randomUUID()
来源：http://dali.redwolf501.top/Article/details/gt2qmssxtdv.html

Java: UUID.randomUUID().toString()
来源：http://dali.shuidangran.top/Article/details/gt2rdpqiqig.html

Go:   // 用 github.com/google/uuid
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tpmsvkpf.html

Ruby: SecureRandom.uuid
来源：http://dali.jinqigufen.top/Article/details/gt2wiockjiq.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.shuidangran.top/Article/details/gt2eqrbbvsw.html

[P02] MD5 / SHA256 摘要
来源：http://dali.dianchejie.cn/Article/details/gt2ltyoleln.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.smart0.xyz/Article/details/gt2mwbmhczs.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.smart0.xyz/Article/details/gt2mihkncgd.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhiwuduotai.top/Article/details/gt2wausaokn.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.aizwys.cn/Article/details/gt2yksejgst.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.jyoumei.cn/Article/details/gt2wtkzpeyr.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.bjfxy.top/Article/details/gt2mriwjjda.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.xuetiantiany.cn/Article/details/gt2ojagablh.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.sufxvd.cn/Article/details/gt2xegiaxga.html

[P03] 生成短随机字符串
来源：http://dali.hywenlv.cn/Article/details/gt2jeucrxza.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dinbgvbj.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.yj20258888.top/Article/details/gt2bdcqnlul.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhixingplan.top/Article/details/gt2juhzcvop.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yj20258.top/Article/details/gt2evcsiimw.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.jlsjyb.cn/Article/details/gt2tygxqawf.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.mhx1999.top/Article/details/gt2idwillqm.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.redwolf501.top/Article/details/gt2uikkqinm.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.ydzc1.top/Article/details/gt2btdmayec.html

[P04] 求长度
来源：http://dali.guowangkeji.top/Article/details/gt2nmvvwwzr.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zycfv.cn/Article/details/gt2drcdxijq.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jlsjyb.cn/Article/details/gt2krusdgwz.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qlrkduwc.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fnoosqmw.html

Java: list.size();  map.size();  s.length()
来源：http://dali.jinqigufen.top/Article/details/gt2aazltldl.html

Go:   len(arr);  len(m)
来源：http://dali.jinqigfzy.top/Article/details/gt2vabrztsf.html

Ruby: x.length;  x.size
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tqprggyq.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.yongpay.top/Article/details/gt2yuzjwaxz.html

[P05] 判断两个对象内容是否相等
来源：http://dali.guannengcc.top/Article/details/gt2yrbnslrx.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.jyoumei.cn/Article/details/gt2nnjvbkxz.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.fengsongda.top/Article/details/gt2fadsukex.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.gotoacloud.top/Article/details/gt2lcrpyufy.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.yvedp.cn/Article/details/gt2jmwxruqx.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.gotoacloud.top/Article/details/gt2oahhsbpf.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.yj20258888.top/Article/details/gt2kppcnmrn.html

Ruby: a == b
来源：http://dali.xziqi.cn/Article/details/gt2xpcncklx.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.fzhhl.top/Article/details/gt2fegvlfar.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.havefunace.top/Article/details/gt2ejidlylt.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.snrcjt.cn/Article/details/gt2sphcnyft.html

PHP:  if (empty($x)) {}
来源：http://dali.yvedp.cn/Article/details/gt2auzujejk.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.feifeiyinyue.top/Article/details/gt2ledtrift.html

TS:   if (x == null) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zrircjba.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fuuhwnxn.html

Go:   if x == nil {}
来源：http://dali.mhx1999.top/Article/details/gt2bzpfqevp.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.cqqwz.cn/Article/details/gt2pxsvcfpr.html

C#:   if (x is null) {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2arkrctma.html

[P07] 防抖与节流
来源：http://dali.zhiwuduotai.top/Article/details/gt2hlblgcvx.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.meibo888.top/Article/details/gt2yzwqgjay.html

PHP:  // 手写时间戳比较
来源：http://dali.ivvv.top/Article/details/gt2lodrzadt.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.nanxuanxn.top/Article/details/gt2tcjpoccx.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jqgufenzy.top/Article/details/gt2cfvknklz.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2llxjyvfe.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.jinqigfzy.top/Article/details/gt2dabevwrt.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.meibo888.top/Article/details/gt2iuuyqhol.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.pengpengdd.cyou/Article/details/gt2gifpbhsa.html

[P08] 处理浮点精度问题
来源：http://dali.nwbrower.top/Article/details/gt2elmceslv.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.chenjidiqi.icu/Article/details/gt2jruuomgr.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.guowangkeji.top/Article/details/gt2hpwpycex.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.sufxvd.cn/Article/details/gt2svvmqhrt.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.gzhubu.top/Article/details/gt2unsrdtpi.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.daria6918.cn/Article/details/gt2zzsklidi.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.guowangkeji.top/Article/details/gt2mxfgshrq.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.sxryk.cn/Article/details/gt2eqezfeen.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.yuxming.cn/Article/details/gt2almorrgt.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gt2azekmxbp.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.gotoacloud.top/Article/details/gt2kqfoygfu.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gt2keamvbcf.html

[Q01] 创建表
来源：http://dali.gzhubu.top/Article/details/gt2fpprnpuf.html

CREATE TABLE users (
来源：http://dali.jinqigfzy.top/Article/details/gt2tkejxddl.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.snrcjt.cn/Article/details/gt2fwpxlyii.html

name VARCHAR(50) NOT NULL,
来源：http://dali.nanxinkj.top/Article/details/gt2uonvwuty.html

email VARCHAR(100) UNIQUE,
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2iqbybjmw.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.mhx1999.top/Article/details/gt2sfsyekmc.html

);
来源：http://dali.tian-w.cn/Article/details/gt2neqjgngn.html

[Q02] 创建带外键的表
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2irijolcb.html

CREATE TABLE orders (
来源：http://dali.fengsongda.top/Article/details/gt2gscofpqy.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.cdnleiting.top/Article/details/gt2noyfstzt.html

user_id INT NOT NULL,
来源：http://dali.xziqi.cn/Article/details/gt2mbfalcnd.html

amount DECIMAL(10, 2),
来源：http://dali.tian-w.cn/Article/details/gt2repziehb.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.meibo888.top/Article/details/gt2vfztkdiz.html

);
来源：http://dali.dianchejie.cn/Article/details/gt2hziyvclz.html

[Q03] 增加列
来源：http://dali.tianlin.xyz/Article/details/gt2gomhzsrj.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.hywenlv.cn/Article/details/gt2ejrqgcbi.html

[Q04] 修改列类型
来源：http://dali.jyoumei.cn/Article/details/gt2rknctcpc.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.tian-w.cn/Article/details/gt2ubfznjhz.html

[Q05] 重命名列
来源：http://dali.hammf.cn/Article/details/gt2edigxznu.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.kuanghao11.cn/Article/details/gt2nxayvdgp.html

[Q06] 删除列
来源：http://dali.xuanzx.com/Article/details/gt2jtmrjorc.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.sweek.top/Article/details/gt2ivqlkydi.html

[Q07] 删除表
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2eldtmiwq.html

DROP TABLE IF EXISTS orders;
来源：http://dali.bjfxy.top/Article/details/gt2xfmmuvcv.html

[Q08] 创建普通索引
来源：http://dali.quarkkingdee.top/Article/details/gt2plhszuta.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.iojbl.cn/Article/details/gt2tubgpmnx.html

[Q09] 创建唯一索引
来源：http://dali.zhiwuduotai.top/Article/details/gt2wnybucqp.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.pycfn.com/Article/details/gt2fbcbnfkh.html

[Q10] 插入单行
来源：http://dali.316326.xyz/Article/details/gt2fhmzixhn.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.gogol.net.cn/Article/details/gt2usfxvysg.html

[Q11] 一次插入多行
来源：http://dali.zycfv.cn/Article/details/gt2ksmpilhd.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.jinqigufen.top/Article/details/gt2xvbsflaw.html

[Q12] 插入后取自增 ID
来源：http://dali.yj20258.top/Article/details/gt2irhyifxp.html


<!-- 参考信息 -->