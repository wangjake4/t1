代发 wailian999

Ruby: exit 1
来源：http://dali.hywenlv.cn/Article/details/gt2btcduskn.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.jqgufenzy.top/Article/details/gt2jhtpwfcj.html

[M06] 向标准错误输出
来源：http://dali.sufxvd.cn/Article/details/gt2slcpklah.html

Py:   print("err", file=sys.stderr)
来源：http://dali.vqdsnc.cn/Article/details/gt2hxdmldgt.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.tanke756.top/Article/details/gt2ulojhvrw.html

JS:   console.error("err")
来源：http://dali.zhongyouzk.top/Article/details/gt2bsuzlsma.html

TS:   console.error("err")
来源：http://dali.mhx1999.top/Article/details/gt2kazlnueg.html

Java: System.err.println("err")
来源：http://dali.yj202588.top/Article/details/gt2jvfvuisf.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.yj202588.top/Article/details/gt2camwadph.html

Ruby: warn "err"
来源：http://dali.hammf.cn/Article/details/gt2jrsuvsjk.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.jinqigfzy.top/Article/details/gt2kugklcsx.html

[M07] 判断是否为主入口
来源：http://dali.316326.xyz/Article/details/gt2yrzornwj.html

Py:   if __name__ == "__main__":
来源：http://dali.cqqwz.cn/Article/details/gt2iioquvgm.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.ehwqpu.com/Article/details/gt2ybofiuir.html

JS:   require.main === module
来源：http://dali.bjfxy.top/Article/details/gt2bdhizxvc.html

TS:   require.main === module
来源：http://dali.zdqjudy.top/Article/details/gt2vcobnedc.html

Java: public static void main(String[] args)
来源：http://dali.cheryme.top/Article/details/gt2oihdqhmk.html

Go:   func main()
来源：http://dali.ivvv.top/Article/details/gt2eqnpgzun.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.jlsjyb.cn/Article/details/gt2yjqqkvvw.html

C#:   static void Main(string[] args)
来源：http://dali.gogol.net.cn/Article/details/gt2zzvgmlcc.html

[M08] 获取系统与运行时信息
来源：http://dali.smart0.xyz/Article/details/gt2qdpqceku.html

Py:   platform.system();  platform.python_version()
来源：http://dali.smart0.xyz/Article/details/gt2fdebtdll.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.cqqwz.cn/Article/details/gt2eewffmbn.html

JS:   process.platform;  process.version
来源：http://dali.yuxming.cn/Article/details/gt2hjowbjpb.html

TS:   process.platform;  process.version
来源：http://dali.gaohongyu789.top/Article/details/gt2nkqptwjl.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.tianlin.xyz/Article/details/gt2uykbgous.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wbdvbtst.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.c1oappe.top/Article/details/gt2ygzewwwt.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.bjfxy.top/Article/details/gt2tchpxiwc.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2lxafnuwj.html

N. 数据结构与算法
来源：http://dali.guannengcc.top/Article/details/gt2rqwhpcqc.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gt2zyaslhag.html

[N01] 二分查找（有序数组）
来源：http://dali.ivvv.top/Article/details/gt2qvedtyfe.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.shuidangran.top/Article/details/gt2exelfwbb.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.andypj.xyz/Article/details/gt2qiynafcx.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.haohaochexian.top/Article/details/gt2uufecadc.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.xylfe.cn/Article/details/gt2objiwkvw.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.quarkkingdee.top/Article/details/gt2fvpzuyjo.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.sysykeji.top/Article/details/gt2mqjiplmo.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.sufxvd.cn/Article/details/gt2wihkenjy.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.pengpengdd.cyou/Article/details/gt2zhjnhkpa.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.jqgufenzy.top/Article/details/gt2jmskttie.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.sufxvd.cn/Article/details/gt2apmyzypt.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.jyoumei.cn/Article/details/gt2pmhztfso.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jinqigfzy.top/Article/details/gt2lxjhtube.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.dianchejie.cn/Article/details/gt2lfltodkf.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2eaxtrocc.html

Go:   slices.Sort(arr)
来源：http://dali.zhengqikj.top/Article/details/gt2xbpxwcrq.html

Ruby: arr.sort
来源：http://dali.mhx1999.top/Article/details/gt2trauunzg.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.xylfe.cn/Article/details/gt2jqmmpusp.html

[N03] 快速排序（分治示例）
来源：http://dali.smart0.xyz/Article/details/gt2sjohylzq.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.hysaishi.cn/Article/details/gt2yuzqxdzt.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2fcafmyat.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.dashuyun.cn/Article/details/gt2kecvplcp.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yj20258888.top/Article/details/gt2qjbadzkt.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.hongshengwenyu.top/Article/details/gt2phuftitg.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.smart0.xyz/Article/details/gt2cbbuewmj.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.pycfn.com/Article/details/gt2kgwbyxes.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.xziqi.cn/Article/details/gt2ulzdyjzb.html

[N04] 斐波那契数列
来源：http://dali.snrcjt.cn/Article/details/gt2vlezzpoh.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.smart0.xyz/Article/details/gt2tkpsmkku.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.ybcxt.top/Article/details/gt2qmgkyuiq.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.ydzc1.top/Article/details/gt2hixirhhj.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.ivvv.top/Article/details/gt2nngppshh.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.xuetiantiany.cn/Article/details/gt2cucodgur.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.jyoumei.cn/Article/details/gt2pkjjavtq.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.9152youxi.cn/Article/details/gt2ljsjsypu.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.xuanzx.com/Article/details/gt2byitglrx.html

[N05] 最大公约数
来源：http://dali.dashuyun.cn/Article/details/gt2mzvdgobx.html

Py:   math.gcd(a, b)
来源：http://dali.ivvv.top/Article/details/gt2gmbyvate.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.hammf.cn/Article/details/gt2sqssijfc.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xtlckstw.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.tianlin.xyz/Article/details/gt2ggsmrscv.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.jinqigufen.top/Article/details/gt2ioyyjoxw.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.xinyue.icu/Article/details/gt2eazryowy.html

Ruby: a.gcd(b)
来源：http://dali.sufxvd.cn/Article/details/gt2cvmstlod.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.vqdsnc.cn/Article/details/gt2xnqnoxkb.html

[N06] 判断回文字符串
来源：http://dali.gogol.net.cn/Article/details/gt2gncslltl.html

Py:   s == s[::-1]
来源：http://dali.andypj.xyz/Article/details/gt2smgoxstq.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2kmudgpdj.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhiwuduotai.top/Article/details/gt2lqwmictr.html

TS:   s === [...s].reverse().join("")
来源：http://dali.316326.xyz/Article/details/gt2mheqznwr.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.guannengcc.top/Article/details/gt2ljlvgwjc.html

Go:   // 双指针从两端比较
来源：http://dali.tanke756.top/Article/details/gt2cuarcuhc.html

Ruby: s == s.reverse
来源：http://dali.guannengcc.top/Article/details/gt2feprwsrz.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.haohaochexian.top/Article/details/gt2uqlclpsz.html

[N07] 两数之和（返回下标）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2aaydbipt.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.yangfankeji.com/Article/details/gt2azgokzxv.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.dashuyun.cn/Article/details/gt2nbqbxqup.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.tanke756.top/Article/details/gt2zysvvddj.html

TS:   // 手写 Map<string, number>
来源：http://dali.jinqigufen.top/Article/details/gt2dlqseurd.html

Java: // 手写 HashMap
来源：http://dali.feifeiyinyue.top/Article/details/gt2vgkgqmap.html

Go:   // 手写 map[int]int
来源：http://dali.cqqwz.cn/Article/details/gt2xcrzamkn.html

Ruby: // 手写 Hash
来源：http://dali.tianlin.xyz/Article/details/gt2agzxucka.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.xylfe.cn/Article/details/gt2vfqrnxgk.html

[N08] 生成全排列
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xihfwyhy.html

Py:   itertools.permutations(arr)
来源：http://dali.pycfn.com/Article/details/gt2fuukmwoj.html

PHP:  // 手写递归交换
来源：http://dali.yj20258888.top/Article/details/gt2opzrjxmg.html

JS:   // 手写回溯递归
来源：http://dali.yj202588.top/Article/details/gt2tjmngmux.html

TS:   // 手写回溯递归
来源：http://dali.yangfankeji.com/Article/details/gt2psbqrcxi.html

Java: // 手写回溯递归
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mdbrijaz.html

Go:   // 手写回溯递归
来源：http://dali.gotoacloud.top/Article/details/gt2dkprklys.html

Ruby: arr.permutation.to_a
来源：http://dali.yueranfly.top/Article/details/gt2eyxhpxak.html

C#:   // 手写回溯递归
来源：http://dali.chenjidiqi.icu/Article/details/gt2pryqdmnv.html

[N09] 栈与队列
来源：http://dali.zdqjudy.top/Article/details/gt2jactrnqr.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.yuxming.cn/Article/details/gt2sbmkyvay.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.hfpthk.cn/Article/details/gt2ohiqctlc.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.vqdsnc.cn/Article/details/gt2fysgefdk.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.xylfe.cn/Article/details/gt2nqctmqfi.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.pycfn.com/Article/details/gt2kyyrzthv.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.chenzaomai.com/Article/details/gt2inxyxlop.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gkxnhwbo.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.guowangkeji.top/Article/details/gt2aroeupnb.html

[N10] 链表节点定义
来源：http://dali.gzhubu.top/Article/details/gt2nuhdnwis.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.cucudq.cn/Article/details/gt2hhgpaupx.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.hfpthk.cn/Article/details/gt2ccdpvfno.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.svipenyu.cn/Article/details/gt2dfxfoahr.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.xuanzx.com/Article/details/gt2aeogppst.html

Java: class Node { int v; Node next; }
来源：http://dali.ydzc1.top/Article/details/gt2uwzwxout.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.yanxiufei.cn/Article/details/gt2urdsckqv.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.hnxiangtu.top/Article/details/gt2pjmapvmz.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.guannengcc.top/Article/details/gt2kpacvcwp.html

[N11] 二叉树中序遍历
来源：http://dali.hywenlv.cn/Article/details/gt2ndudybnh.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.c1oappe.top/Article/details/gt2ullvgdnu.html

PHP:  // 手写递归函数
来源：http://dali.hywenlv.cn/Article/details/gt2tlvkblkl.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.mhx1999.top/Article/details/gt2lyfzysnm.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.cheryme.top/Article/details/gt2yimkcfsc.html

Java: // 手写递归
来源：http://dali.quarkkingdee.top/Article/details/gt2zlswislk.html

Go:   // 手写递归
来源：http://dali.yvedp.cn/Article/details/gt2tkhmyyxc.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.yongpay.top/Article/details/gt2kornhstt.html

C#:   // 手写递归
来源：http://dali.yonumen.top/Article/details/gt2nzyjadhw.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.yanxiufei.cn/Article/details/gt2wjqseark.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.fengsongda.top/Article/details/gt2menesjuy.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.chenlongwang.top/Article/details/gt2fwlztcul.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jqgfzy.top/Article/details/gt2icduriag.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.hfpthk.cn/Article/details/gt2jzftknup.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhiwuduotai.top/Article/details/gt2owjjqxcy.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.kuanghao11.cn/Article/details/gt2ydsdmdiu.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.iojbl.cn/Article/details/gt2jhqfgixk.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.gotoacloud.top/Article/details/gt2anbhyiop.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gt2lcflsoxt.html

O. 并发与异步
来源：http://dali.jlsjyb.cn/Article/details/gt2gdoislty.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gt2jsagbprq.html

[O01] 启动一个线程
来源：http://dali.jlsjyb.cn/Article/details/gt2bbhedkab.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.xinyue.icu/Article/details/gt2cswvqdvq.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.hammf.cn/Article/details/gt2zfuvozpr.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.redwolf501.top/Article/details/gt2mqtqgedt.html

TS:   // 同 JS
来源：http://dali.andypj.xyz/Article/details/gt2jsvznybq.html

Java: new Thread(() -> f()).start()
来源：http://dali.chenlongwang.top/Article/details/gt2sqgaedqw.html

Go:   go f()
来源：http://dali.xylfe.cn/Article/details/gt2vpggswou.html

Ruby: Thread.new { f }
来源：http://dali.zhongyouzk.top/Article/details/gt2xuzwzbjb.html

C#:   Task.Run(() => F());
来源：http://dali.316326.xyz/Article/details/gt2aojeghwl.html

[O02] 使用线程池
来源：http://dali.zycfv.cn/Article/details/gt2jwnqfclv.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.jinqigufen.top/Article/details/gt2adsrqpii.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.aibaodan.cn/Article/details/gt2plkoxwou.html

JS:   // worker_threads 线程池
来源：http://dali.0kj1m.cn/Article/details/gt2ppwgcfcu.html

TS:   // worker_threads 线程池
来源：http://dali.316326.xyz/Article/details/gt2tygzzmei.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.tanke756.top/Article/details/gt2asonohnx.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.feifeiyinyue.top/Article/details/gt2rbyufwtm.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.daria6918.cn/Article/details/gt2sozmdoun.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.cqqwz.cn/Article/details/gt2achdgdhr.html

[O03] 加锁保护共享数据
来源：http://dali.xylfe.cn/Article/details/gt2jhjiutec.html

Py:   with lock: shared += 1
来源：http://dali.sysykeji.top/Article/details/gt2aauiyrau.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.cucudq.cn/Article/details/gt2pieduvba.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.mhx1999.top/Article/details/gt2yjqsngbc.html

TS:   // 同 JS
来源：http://dali.tanke756.top/Article/details/gt2zddhmkuk.html

Java: synchronized (this) { shared++; }
来源：http://dali.xinyue.icu/Article/details/gt2vbhbqevm.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.feifeiyinyue.top/Article/details/gt2pyljjcme.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.9152youxi.cn/Article/details/gt2hnhsruff.html

C#:   lock (gate) { shared++; }
来源：http://dali.tianlin.xyz/Article/details/gt2evskbeiq.html

[O04] 定义异步函数并等待
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nlmprkmw.html

Py:   async def f():⏎    await g()
来源：http://dali.havefunace.top/Article/details/gt2xoxlkmlv.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.hongshengwenyu.top/Article/details/gt2qpygsnkn.html

JS:   async function f() { await g(); }
来源：http://dali.gogol.net.cn/Article/details/gt2jyxxinlh.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.yangfankeji.com/Article/details/gt2eoreascc.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.0kj1m.cn/Article/details/gt2vtyytsnx.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.ppjwa.cn/Article/details/gt2yvogcqsk.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.ppjwa.cn/Article/details/gt2jxscptul.html

C#:   async Task F() { await G(); }
来源：http://dali.gaohongyu789.top/Article/details/gt2hoqyylnr.html

[O05] 并发执行并等待全部完成
来源：http://dali.wangdashe.top/Article/details/gt2gbxoyycr.html

Py:   asyncio.gather(*tasks)
来源：http://dali.jlsjyb.cn/Article/details/gt2mkqzgcei.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.dianchejie.cn/Article/details/gt2nsanvumq.html

JS:   await Promise.all(tasks)
来源：http://dali.fzhhl.top/Article/details/gt2ezutswuo.html

TS:   await Promise.all(tasks)
来源：http://dali.zhiwuduotai.top/Article/details/gt2swvkinxv.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2spokgoic.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.shzxlz.cn/Article/details/gt2hzbmzjml.html

Ruby: threads.map(&:join)
来源：http://dali.nanxuanxn.top/Article/details/gt2dvrbalrd.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.316326.xyz/Article/details/gt2sqvdbxeb.html

[O06] 使用进程池
来源：http://dali.jyoumei.cn/Article/details/gt2vvtzrajo.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.c1oappe.top/Article/details/gt2wnvnebav.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.fengsongda.top/Article/details/gt2sljvivuv.html

JS:   // child_process / cluster 模块
来源：http://dali.cqqwz.cn/Article/details/gt2deqwhyhw.html

TS:   // child_process / cluster 模块
来源：http://dali.yongpay.top/Article/details/gt2hblbnlgh.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhoulong.xyz/Article/details/gt2ntkqvxhn.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.nwbrower.top/Article/details/gt2oqgmzoxe.html

Ruby: // fork 块
来源：http://dali.feifeiyinyue.top/Article/details/gt2amghukhe.html

C#:   Parallel.For
来源：http://dali.nanxuanxn.top/Article/details/gt2zclrndkz.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gt2jawcoidi.html

P. 常用工具函数
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jvmeuwxv.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gt2fqolhfxm.html

[P01] 生成 UUID
来源：http://dali.tianlin.xyz/Article/details/gt2bwfncwtc.html

Py:   str(uuid.uuid4())
来源：http://dali.havefunace.top/Article/details/gt2nnugjpmq.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.c1oappe.top/Article/details/gt2dbohzbsc.html

JS:   crypto.randomUUID()
来源：http://dali.9152youxi.cn/Article/details/gt2ekxurxjs.html

TS:   crypto.randomUUID()
来源：http://dali.cucudq.cn/Article/details/gt2shyxrabz.html

Java: UUID.randomUUID().toString()
来源：http://dali.haohaochexian.top/Article/details/gt2agunkdeq.html

Go:   // 用 github.com/google/uuid
来源：http://dali.aibaodan.cn/Article/details/gt2tldcmbip.html

Ruby: SecureRandom.uuid
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pbbpxjok.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.hfpthk.cn/Article/details/gt2fywyjlak.html

[P02] MD5 / SHA256 摘要
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kjbfuknh.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.sysykeji.top/Article/details/gt2oskgfmnj.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.yj202588.top/Article/details/gt2romdtqeb.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.hongshengwenyu.top/Article/details/gt2kktdmxiz.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.tanke756.top/Article/details/gt2xtmqging.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.cqqwz.cn/Article/details/gt2auugorku.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.xuetiantiany.cn/Article/details/gt2swchcpsl.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.shangyingyoupin.top/Article/details/gt2cqzqjugs.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.vqdsnc.cn/Article/details/gt2gcyxwgyk.html

[P03] 生成短随机字符串
来源：http://dali.0kj1m.cn/Article/details/gt2buyoqdlt.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.fengsongda.top/Article/details/gt2iftalcfo.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.dianchejie.cn/Article/details/gt2jmcmhssy.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.daria6918.cn/Article/details/gt2myhqmqzd.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.kuanghao11.cn/Article/details/gt2xjyxqogq.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.daria6918.cn/Article/details/gt2cnqbujxl.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.gaohongyu789.top/Article/details/gt2zeruxgql.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.bjfxy.top/Article/details/gt2vrqthnyq.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2isgeimsj.html

[P04] 求长度
来源：http://dali.guowangkeji.top/Article/details/gt2ikbjasdk.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.nanxuanxn.top/Article/details/gt2wmextrix.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.andypj.xyz/Article/details/gt2coahjlia.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhiwuduotai.top/Article/details/gt2jjeoafko.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.0kj1m.cn/Article/details/gt2qckuczdn.html

Java: list.size();  map.size();  s.length()
来源：http://dali.tian-w.cn/Article/details/gt2vcxzvynx.html

Go:   len(arr);  len(m)
来源：http://dali.xinyue.icu/Article/details/gt2nvyqjtcp.html

Ruby: x.length;  x.size
来源：http://dali.zhixingplan.top/Article/details/gt2glbqgfvg.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.hywenlv.cn/Article/details/gt2mjvisswr.html

[P05] 判断两个对象内容是否相等
来源：http://dali.daxiang520.top/Article/details/gt2sboswaga.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.jiagoushi.top/Article/details/gt2umlbpjfb.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.iojbl.cn/Article/details/gt2imynirwj.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.gzhubu.top/Article/details/gt2vmkdwdoz.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2rykxeuip.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.c1oappe.top/Article/details/gt2qklwxziq.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.haohaochexian.top/Article/details/gt2pxgblkdv.html

Ruby: a == b
来源：http://dali.hongshengwenyu.top/Article/details/gt2whznoinq.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.jinqigfzy.top/Article/details/gt2nlcrccvu.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.chenlongwang.top/Article/details/gt2jasjrech.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.jinghuilouyu.cn/Article/details/gt2csigqplm.html

PHP:  if (empty($x)) {}
来源：http://dali.quarkkingdee.top/Article/details/gt2abyjkaos.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.guowangkeji.top/Article/details/gt2yyvxxsfu.html

TS:   if (x == null) {}
来源：http://dali.hfpthk.cn/Article/details/gt2uydcfqmr.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.hammf.cn/Article/details/gt2djlkuecx.html

Go:   if x == nil {}
来源：http://dali.cdnleiting.top/Article/details/gt2kgwekwub.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.fengsongda.top/Article/details/gt2jtcbicfh.html

C#:   if (x is null) {}
来源：http://dali.jianghu66.top/Article/details/gt2qogqkiuo.html

[P07] 防抖与节流
来源：http://dali.yj202588.top/Article/details/gt2nrjqwteg.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.shangyingyoupin.top/Article/details/gt2mzmncwkr.html

PHP:  // 手写时间戳比较
来源：http://dali.sufxvd.cn/Article/details/gt2solhgbpn.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.nwbrower.top/Article/details/gt2nesigllu.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.feifeiyinyue.top/Article/details/gt2gxdnrimg.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.shuidangran.top/Article/details/gt2nwvvhjvd.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.mhx1999.top/Article/details/gt2ilbpbazi.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.yonumen.top/Article/details/gt2mswnvyle.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.smart0.xyz/Article/details/gt2fdophwxy.html

[P08] 处理浮点精度问题
来源：http://dali.sweek.top/Article/details/gt2tdgjwelw.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.gzhubu.top/Article/details/gt2vwbftjpi.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.xinyue.icu/Article/details/gt2qxwjswpn.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.feifeiyinyue.top/Article/details/gt2cuzxzklr.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.xinyue.icu/Article/details/gt2zcxbepca.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.tian-w.cn/Article/details/gt2pxedhhms.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.xziqi.cn/Article/details/gt2mzzmmrsm.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.316326.xyz/Article/details/gt2qgvotrol.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.dashuyun.cn/Article/details/gt2mwopnwnd.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gt2hbpqnwkb.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.guowangkeji.top/Article/details/gt2ydqtfozy.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gt2hecfeyhs.html

[Q01] 创建表
来源：http://dali.xuetiantiany.cn/Article/details/gt2hkwriomp.html

CREATE TABLE users (
来源：http://dali.kuanghao11.cn/Article/details/gt2riccwlxq.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.xuetiantiany.cn/Article/details/gt2iroaepbv.html

name VARCHAR(50) NOT NULL,
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dcrpsnjt.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhengqikj.top/Article/details/gt2jlwlkfse.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.hfpthk.cn/Article/details/gt2qeznebpa.html

);
来源：http://dali.hysaishi.cn/Article/details/gt2zcourrmf.html

[Q02] 创建带外键的表
来源：http://dali.ydzc1.top/Article/details/gt2fpatvrme.html

CREATE TABLE orders (
来源：http://dali.fengsongda.top/Article/details/gt2nfkmszrw.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mkpoylxi.html

user_id INT NOT NULL,
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dbhwssmq.html

amount DECIMAL(10, 2),
来源：http://dali.haohaochexian.top/Article/details/gt2webkzevn.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.dianchejie.cn/Article/details/gt2xgnxpwiq.html

);
来源：http://dali.yj20258888.top/Article/details/gt2qcwmyfcx.html

[Q03] 增加列
来源：http://dali.yonumen.top/Article/details/gt2hzbdbxeq.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.hammf.cn/Article/details/gt2yoexggmd.html

[Q04] 修改列类型
来源：http://dali.shangyingyoupin.top/Article/details/gt2xrvkzeuh.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhongyouzk.top/Article/details/gt2cxcugeoq.html

[Q05] 重命名列
来源：http://dali.yongpay.top/Article/details/gt2kxwgudgx.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.fengsongda.top/Article/details/gt2ewokonjk.html

[Q06] 删除列
来源：http://dali.gaohongyu789.top/Article/details/gt2fvswpsoo.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhoulong.xyz/Article/details/gt2ahidivqp.html

[Q07] 删除表
来源：http://dali.hammf.cn/Article/details/gt2trfcasfk.html

DROP TABLE IF EXISTS orders;
来源：http://dali.pycfn.com/Article/details/gt2qqwvzrfs.html

[Q08] 创建普通索引
来源：http://dali.vqdsnc.cn/Article/details/gt2nvlvrazw.html


<!-- 参考信息 -->