代发 wailian999

JS:   process.exit(1)
来源：http://dali.nanxinkj.top/Article/details/gt2sajhmdmj.html

TS:   process.exit(1)
来源：http://dali.zycfv.cn/Article/details/gt2aeaoerks.html

Java: System.exit(1)
来源：http://dali.jlsjyb.cn/Article/details/gt2wjxjbtvp.html

Go:   os.Exit(1)
来源：http://dali.yongpay.top/Article/details/gt2gpngmpgn.html

Ruby: exit 1
来源：http://dali.gzhubu.top/Article/details/gt2fheiwjym.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.tanke756.top/Article/details/gt2edcghdze.html

[M06] 向标准错误输出
来源：http://dali.sufxvd.cn/Article/details/gt2qwitzojo.html

Py:   print("err", file=sys.stderr)
来源：http://dali.cqqwz.cn/Article/details/gt2cwhhszlp.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.hfpthk.cn/Article/details/gt2dxjkvvqf.html

JS:   console.error("err")
来源：http://dali.meibo888.top/Article/details/gt2akaogvwd.html

TS:   console.error("err")
来源：http://dali.yj20258.top/Article/details/gt2gfhrwvho.html

Java: System.err.println("err")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2opakcphr.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.cashguo.top/Article/details/gt2umnuybcm.html

Ruby: warn "err"
来源：http://dali.andypj.xyz/Article/details/gt2kitdgyuv.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.svipenyu.cn/Article/details/gt2nplxvtfo.html

[M07] 判断是否为主入口
来源：http://dali.zhiwuduotai.top/Article/details/gt2tfpdrdjl.html

Py:   if __name__ == "__main__":
来源：http://dali.c1oappe.top/Article/details/gt2uptjfoja.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.redwolf501.top/Article/details/gt2erowpxmf.html

JS:   require.main === module
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ujxftoya.html

TS:   require.main === module
来源：http://dali.yangfankeji.com/Article/details/gt2etqyreqt.html

Java: public static void main(String[] args)
来源：http://dali.hnxiangtu.top/Article/details/gt2qjciphwt.html

Go:   func main()
来源：http://dali.gzhubu.top/Article/details/gt2gbiizcbs.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.gaohongyu789.top/Article/details/gt2mmoqvmeo.html

C#:   static void Main(string[] args)
来源：http://dali.hongshengwenyu.top/Article/details/gt2payzjhca.html

[M08] 获取系统与运行时信息
来源：http://dali.gotoacloud.top/Article/details/gt2aetlfynq.html

Py:   platform.system();  platform.python_version()
来源：http://dali.quarkkingdee.top/Article/details/gt2ogoismbc.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.chenzaomai.com/Article/details/gt2qczmgjtb.html

JS:   process.platform;  process.version
来源：http://dali.tanke756.top/Article/details/gt2xyrtsvlx.html

TS:   process.platform;  process.version
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2laogxsdd.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhongyouzk.top/Article/details/gt2nhtueide.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.jinqigufen.top/Article/details/gt2dshjduil.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.feifeiyinyue.top/Article/details/gt2bwkpzdwa.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.yangfankeji.com/Article/details/gt2dwevrypi.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gt2onzdrcdz.html

N. 数据结构与算法
来源：http://dali.dashuyun.cn/Article/details/gt2mvauiymp.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gt2rvxkmeqg.html

[N01] 二分查找（有序数组）
来源：http://dali.dianchejie.cn/Article/details/gt2kacvufbp.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jdaoigiw.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.birdmap.top/Article/details/gt2aevzrksr.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tguevydr.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.birdmap.top/Article/details/gt2kowvcvzl.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.quarkkingdee.top/Article/details/gt2uaulnype.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.yongpay.top/Article/details/gt2sbklasyc.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.yvedp.cn/Article/details/gt2flldvhrm.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ojuopiee.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.9152youxi.cn/Article/details/gt2eukjjfiv.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.ybcxt.top/Article/details/gt2crhwxbva.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.yanxiufei.cn/Article/details/gt2eyxelyhi.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.tanke756.top/Article/details/gt2xavsvsdf.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhixingplan.top/Article/details/gt2kerqouho.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.havefunace.top/Article/details/gt2xwhudqky.html

Go:   slices.Sort(arr)
来源：http://dali.nanxinkj.top/Article/details/gt2bbqssbaj.html

Ruby: arr.sort
来源：http://dali.tanke756.top/Article/details/gt2hjvqexzk.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.nwbrower.top/Article/details/gt2mbzivgku.html

[N03] 快速排序（分治示例）
来源：http://dali.xuetiantiany.cn/Article/details/gt2ntergmpl.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.xylfe.cn/Article/details/gt2rmuzwwrk.html

PHP:  // 递归实现，或用 usort
来源：http://dali.hnxiangtu.top/Article/details/gt2mszbsdxy.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.xinyue.icu/Article/details/gt2swhlgvof.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.tianlin.xyz/Article/details/gt2ujokpvxi.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.hywenlv.cn/Article/details/gt2xqmyqxmp.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2psvqfyfv.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.tianlin.xyz/Article/details/gt2jplzaznt.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.yonumen.top/Article/details/gt2dvkgcacn.html

[N04] 斐波那契数列
来源：http://dali.nwbrower.top/Article/details/gt2yucxopcw.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.xinyue.icu/Article/details/gt2bsaaymal.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.cdnleiting.top/Article/details/gt2jgdrktan.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.ehwqpu.com/Article/details/gt2fvcpemtr.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jinqigufen.top/Article/details/gt2wezfffok.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.tanke756.top/Article/details/gt2ollaxsma.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.ivvv.top/Article/details/gt2nmwtrxkb.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.snrcjt.cn/Article/details/gt2zxnefbkc.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.meibo888.top/Article/details/gt2bpdqidsn.html

[N05] 最大公约数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ybwlepwx.html

Py:   math.gcd(a, b)
来源：http://dali.ehwqpu.com/Article/details/gt2jekvnqam.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.bjfxy.top/Article/details/gt2haygvbun.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2aaxmgjra.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.9152youxi.cn/Article/details/gt2cbsvazpt.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.guowangkeji.top/Article/details/gt2blxqgqjo.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.hongshengwenyu.top/Article/details/gt2brcjesbd.html

Ruby: a.gcd(b)
来源：http://dali.yueranfly.top/Article/details/gt2gbvtopel.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.snrcjt.cn/Article/details/gt2ymmsxdoj.html

[N06] 判断回文字符串
来源：http://dali.zhixingplan.top/Article/details/gt2zsrwdnbd.html

Py:   s == s[::-1]
来源：http://dali.hammf.cn/Article/details/gt2evhyzrud.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2rbmtmisk.html

JS:   s === [...s].reverse().join("")
来源：http://dali.cqqwz.cn/Article/details/gt2uezgoptv.html

TS:   s === [...s].reverse().join("")
来源：http://dali.tianlin.xyz/Article/details/gt2jygmgcan.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zdqjudy.top/Article/details/gt2hymwlllc.html

Go:   // 双指针从两端比较
来源：http://dali.cucudq.cn/Article/details/gt2wkyrrpdf.html

Ruby: s == s.reverse
来源：http://dali.sufxvd.cn/Article/details/gt2uybedqjt.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.jiagoushi.top/Article/details/gt2trudqcym.html

[N07] 两数之和（返回下标）
来源：http://dali.chenjidiqi.icu/Article/details/gt2cnssbhvs.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.wangdashe.top/Article/details/gt2bkwtssqc.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.shzxlz.cn/Article/details/gt2fhbunkot.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.gaohongyu789.top/Article/details/gt2bludcqpb.html

TS:   // 手写 Map<string, number>
来源：http://dali.yvedp.cn/Article/details/gt2acwrehyo.html

Java: // 手写 HashMap
来源：http://dali.mhx1999.top/Article/details/gt2uxaibswe.html

Go:   // 手写 map[int]int
来源：http://dali.bjfxy.top/Article/details/gt2qncuwpxr.html

Ruby: // 手写 Hash
来源：http://dali.snrcjt.cn/Article/details/gt2xqiyiaur.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pzgxcauy.html

[N08] 生成全排列
来源：http://dali.yj202588.top/Article/details/gt2cdrptlpy.html

Py:   itertools.permutations(arr)
来源：http://dali.wangshuangyany.cn/Article/details/gt2swqrzpdt.html

PHP:  // 手写递归交换
来源：http://dali.jlsjyb.cn/Article/details/gt2deqyknbp.html

JS:   // 手写回溯递归
来源：http://dali.dashuyun.cn/Article/details/gt2fydfwqry.html

TS:   // 手写回溯递归
来源：http://dali.gaohongyu789.top/Article/details/gt2yvrdxtuf.html

Java: // 手写回溯递归
来源：http://dali.316326.xyz/Article/details/gt2zsixffpx.html

Go:   // 手写回溯递归
来源：http://dali.jqgufenzy.top/Article/details/gt2mrofamxh.html

Ruby: arr.permutation.to_a
来源：http://dali.gzhubu.top/Article/details/gt2upxktkug.html

C#:   // 手写回溯递归
来源：http://dali.zhiwuduotai.top/Article/details/gt2zhgdoxbw.html

[N09] 栈与队列
来源：http://dali.hammf.cn/Article/details/gt2yfjrbpip.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rfsubtmq.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.quarkkingdee.top/Article/details/gt2ipspnqqk.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.sufxvd.cn/Article/details/gt2wefwglaq.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.hammf.cn/Article/details/gt2oahsjvqy.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.shanyushiyangtech.top/Article/details/gt2izcmhuds.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.xuetiantiany.cn/Article/details/gt2tgjqfcjo.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.bjfxy.top/Article/details/gt2piqfftej.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2oqglzfic.html

[N10] 链表节点定义
来源：http://dali.fengsongda.top/Article/details/gt2ovfutfip.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.gogol.net.cn/Article/details/gt2vmoyvemb.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.jiagoushi.top/Article/details/gt2sctmhndq.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.meibo888.top/Article/details/gt2krxeqsxo.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bhngxxnk.html

Java: class Node { int v; Node next; }
来源：http://dali.aibaodan.cn/Article/details/gt2egqpbieu.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.iojbl.cn/Article/details/gt2suplwnzd.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.pycfn.com/Article/details/gt2unqqgmos.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.yj20258888.top/Article/details/gt2inmyamhh.html

[N11] 二叉树中序遍历
来源：http://dali.zhixingplan.top/Article/details/gt2xibdahqo.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.jianghu66.top/Article/details/gt2aezkotdj.html

PHP:  // 手写递归函数
来源：http://dali.yueranfly.top/Article/details/gt2flmqxdlr.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.cucudq.cn/Article/details/gt2bqtuenmt.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.pycfn.com/Article/details/gt2twrmjcxp.html

Java: // 手写递归
来源：http://dali.nanxuanxn.top/Article/details/gt2gkznbcfe.html

Go:   // 手写递归
来源：http://dali.havefunace.top/Article/details/gt2giaksnen.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.ydzc1.top/Article/details/gt2eycjrenc.html

C#:   // 手写递归
来源：http://dali.pengpengdd.cyou/Article/details/gt2fibzhuzn.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.cucudq.cn/Article/details/gt2lhgozynp.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zpwvrsbu.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uaxyuobx.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.ivvv.top/Article/details/gt2wawretpk.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.havefunace.top/Article/details/gt2zquezhms.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jinqigufen.top/Article/details/gt2ggobwvuw.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.jlsjyb.cn/Article/details/gt2mfquyals.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.9152youxi.cn/Article/details/gt2awrsxphz.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.xziqi.cn/Article/details/gt2nsayezvv.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gt2pqhtfzda.html

O. 并发与异步
来源：http://dali.vqdsnc.cn/Article/details/gt2mjltskna.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gt2weveevkl.html

[O01] 启动一个线程
来源：http://dali.shangyingyoupin.top/Article/details/gt2pwdkmtkq.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.redwolf501.top/Article/details/gt2hqlhdmfu.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.cdnleiting.top/Article/details/gt2cbwzspjf.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.gotoacloud.top/Article/details/gt2lmpkrttt.html

TS:   // 同 JS
来源：http://dali.quarkkingdee.top/Article/details/gt2rwalcedo.html

Java: new Thread(() -> f()).start()
来源：http://dali.gaohongyu789.top/Article/details/gt2ivfidqfz.html

Go:   go f()
来源：http://dali.meibo888.top/Article/details/gt2xdkforps.html

Ruby: Thread.new { f }
来源：http://dali.jinqigfzy.top/Article/details/gt2infvmrxs.html

C#:   Task.Run(() => F());
来源：http://dali.havefunace.top/Article/details/gt2rnkblffb.html

[O02] 使用线程池
来源：http://dali.ivvv.top/Article/details/gt2usrrzjsr.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.daxiang520.top/Article/details/gt2gshkxrik.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.feifeiyinyue.top/Article/details/gt2jjtnksll.html

JS:   // worker_threads 线程池
来源：http://dali.wangshuangyany.cn/Article/details/gt2ggbujctf.html

TS:   // worker_threads 线程池
来源：http://dali.cqqwz.cn/Article/details/gt2gfqbrjnc.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.smart0.xyz/Article/details/gt2ggtmmmiy.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.yuanzhike.top/Article/details/gt2wsgsxlmp.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ludvvzyp.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uhvhqkeo.html

[O03] 加锁保护共享数据
来源：http://dali.xziqi.cn/Article/details/gt2idetbtbj.html

Py:   with lock: shared += 1
来源：http://dali.aibaodan.cn/Article/details/gt2pgamlcnp.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhongyouzk.top/Article/details/gt2bwrqfnzr.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ahwsxhqk.html

TS:   // 同 JS
来源：http://dali.birdmap.top/Article/details/gt2hwuiuqmh.html

Java: synchronized (this) { shared++; }
来源：http://dali.fzhhl.top/Article/details/gt2xcybhmuq.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.sxryk.cn/Article/details/gt2kaeqsita.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.jianghu66.top/Article/details/gt2czvobynu.html

C#:   lock (gate) { shared++; }
来源：http://dali.jqgfzy.top/Article/details/gt2gmclwzom.html

[O04] 定义异步函数并等待
来源：http://dali.ydzc1.top/Article/details/gt2afenmmwy.html

Py:   async def f():⏎    await g()
来源：http://dali.gaohongyu789.top/Article/details/gt2kbqkhazq.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.cheryme.top/Article/details/gt2uktwvkox.html

JS:   async function f() { await g(); }
来源：http://dali.hysaishi.cn/Article/details/gt2caszsusw.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.daria6918.cn/Article/details/gt2fjlwhjyt.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.fengsongda.top/Article/details/gt2pmkyxkru.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nznkukzz.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.yuxming.cn/Article/details/gt2psjxsqxk.html

C#:   async Task F() { await G(); }
来源：http://dali.chenjidiqi.icu/Article/details/gt2ulktnutj.html

[O05] 并发执行并等待全部完成
来源：http://dali.xziqi.cn/Article/details/gt2wxaelhwg.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhiwuduotai.top/Article/details/gt2bsbawszb.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.birdmap.top/Article/details/gt2jvgowtlu.html

JS:   await Promise.all(tasks)
来源：http://dali.jlsjyb.cn/Article/details/gt2atwyxgsr.html

TS:   await Promise.all(tasks)
来源：http://dali.gzhubu.top/Article/details/gt2ickafpnb.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.birdmap.top/Article/details/gt2pudvkcna.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.nanxinkj.top/Article/details/gt2zyssnbue.html

Ruby: threads.map(&:join)
来源：http://dali.cheryme.top/Article/details/gt2bgjmvscz.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.yuxming.cn/Article/details/gt2xjdbvxee.html

[O06] 使用进程池
来源：http://dali.yongpay.top/Article/details/gt2miaaqyih.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.jiagoushi.top/Article/details/gt2trkulbds.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.tian-w.cn/Article/details/gt2vqtaqsjv.html

JS:   // child_process / cluster 模块
来源：http://dali.chenjidiqi.icu/Article/details/gt2mfftgitd.html

TS:   // child_process / cluster 模块
来源：http://dali.cashguo.top/Article/details/gt2spfhlhje.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.daria6918.cn/Article/details/gt2rggsiytw.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.fengsongda.top/Article/details/gt2hxfurnew.html

Ruby: // fork 块
来源：http://dali.yj20258.top/Article/details/gt2feknbidu.html

C#:   Parallel.For
来源：http://dali.cashguo.top/Article/details/gt2xcmqgaoo.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gt2unzgbnlf.html

P. 常用工具函数
来源：http://dali.yuanzhike.top/Article/details/gt2bngzeojw.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ptcbdfsy.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2ovqvfrrp.html

Py:   str(uuid.uuid4())
来源：http://dali.yuxming.cn/Article/details/gt2yxihqbex.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.ydzc1.top/Article/details/gt2gdnojcpe.html

JS:   crypto.randomUUID()
来源：http://dali.c1oappe.top/Article/details/gt2wtuhqprm.html

TS:   crypto.randomUUID()
来源：http://dali.chenlongwang.top/Article/details/gt2frfeigxn.html

Java: UUID.randomUUID().toString()
来源：http://dali.andypj.xyz/Article/details/gt2jahynxqg.html

Go:   // 用 github.com/google/uuid
来源：http://dali.hongshengwenyu.top/Article/details/gt2ncmxhioz.html

Ruby: SecureRandom.uuid
来源：http://dali.quarkkingdee.top/Article/details/gt2qrbocoec.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.redwolf501.top/Article/details/gt2pwuyaosg.html

[P02] MD5 / SHA256 摘要
来源：http://dali.snrcjt.cn/Article/details/gt2ncijuslj.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2ghzhlsel.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.snrcjt.cn/Article/details/gt2mbhcskxb.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.dashuyun.cn/Article/details/gt2vnpyxddz.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zdqjudy.top/Article/details/gt2fcibhusr.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.chenzaomai.com/Article/details/gt2qfjukaao.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.0kj1m.cn/Article/details/gt2doicscqf.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zmvnvzmp.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.chenzaomai.com/Article/details/gt2pogedaju.html

[P03] 生成短随机字符串
来源：http://dali.zhongyouzk.top/Article/details/gt2osoxugbw.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.yongpay.top/Article/details/gt2wnpwmoot.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2noiwwunl.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jqgufenzy.top/Article/details/gt2rwpehgpn.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.quarkkingdee.top/Article/details/gt2xurpestu.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.sweek.top/Article/details/gt2ryndicoi.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.shangyingyoupin.top/Article/details/gt2mwmdnopc.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.shuidangran.top/Article/details/gt2ibashtll.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.cqqwz.cn/Article/details/gt2hlrharwz.html

[P04] 求长度
来源：http://dali.jinqigfzy.top/Article/details/gt2mnnqnghg.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.snrcjt.cn/Article/details/gt2cnkoyopz.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.ivvv.top/Article/details/gt2neqzlbpb.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zxdfcdjf.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.hfpthk.cn/Article/details/gt2cgyxlbgl.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zycfv.cn/Article/details/gt2cjqwmyzc.html

Go:   len(arr);  len(m)
来源：http://dali.cashguo.top/Article/details/gt2gglmavdq.html

Ruby: x.length;  x.size
来源：http://dali.yanxiufei.cn/Article/details/gt2wnohicmw.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.xuetiantiany.cn/Article/details/gt2pshbaokv.html

[P05] 判断两个对象内容是否相等
来源：http://dali.hnxiangtu.top/Article/details/gt2xsifputc.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.xuetiantiany.cn/Article/details/gt2qlbepyrz.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.9152youxi.cn/Article/details/gt2spfxmlkw.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.cdnleiting.top/Article/details/gt2cmaxslii.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.yuanzhike.top/Article/details/gt2zvvlndmr.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.shzxlz.cn/Article/details/gt2lsflebmu.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.ydzc1.top/Article/details/gt2vguusorj.html

Ruby: a == b
来源：http://dali.chenzaomai.com/Article/details/gt2zkahojwj.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.dashuyun.cn/Article/details/gt2njncyjyh.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.snrcjt.cn/Article/details/gt2nahwbgmw.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qjlotiea.html

PHP:  if (empty($x)) {}
来源：http://dali.sufxvd.cn/Article/details/gt2bvgdbqbv.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.aizwys.cn/Article/details/gt2zwwqdvci.html

TS:   if (x == null) {}
来源：http://dali.yonumen.top/Article/details/gt2mnswhtce.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2uoncntfx.html

Go:   if x == nil {}
来源：http://dali.0kj1m.cn/Article/details/gt2rmjhomnj.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.cheryme.top/Article/details/gt2hbrzdcvj.html

C#:   if (x is null) {}
来源：http://dali.sweek.top/Article/details/gt2bbmtqakr.html

[P07] 防抖与节流
来源：http://dali.sxryk.cn/Article/details/gt2tvnpkene.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.hnxiangtu.top/Article/details/gt2zhpvxtdw.html

PHP:  // 手写时间戳比较
来源：http://dali.tian-w.cn/Article/details/gt2aqeulmyo.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.andypj.xyz/Article/details/gt2nqnszzly.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jianghu66.top/Article/details/gt2glubtemp.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.0kj1m.cn/Article/details/gt2lwbiivti.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zdqjudy.top/Article/details/gt2zfsqpqmc.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.xinyue.icu/Article/details/gt2veruyhgw.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.mhx1999.top/Article/details/gt2puwuldpg.html

[P08] 处理浮点精度问题
来源：http://dali.pycfn.com/Article/details/gt2vvkgboar.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2uvybyhan.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.hongshengwenyu.top/Article/details/gt2vdqqdhav.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.cucudq.cn/Article/details/gt2daesjxlt.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.yonumen.top/Article/details/gt2yemxqmth.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.guannengcc.top/Article/details/gt2qbzjmonk.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.svipenyu.cn/Article/details/gt2hhbuukdc.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhixingplan.top/Article/details/gt2dnoxtrqc.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.smart0.xyz/Article/details/gt2mgyuyswk.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gt2xettjvjj.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.tanke756.top/Article/details/gt2oxmbflqn.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gt2ssgjwpdm.html

[Q01] 创建表
来源：http://dali.hywenlv.cn/Article/details/gt2pphhrkln.html

CREATE TABLE users (
来源：http://dali.jlsjyb.cn/Article/details/gt2gemfhlgn.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.chenzaomai.com/Article/details/gt2ctkdsfub.html

name VARCHAR(50) NOT NULL,
来源：http://dali.yj20258.top/Article/details/gt2krocrrjl.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zycfv.cn/Article/details/gt2elpxeqzg.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.hongshengwenyu.top/Article/details/gt2kzvggqbf.html

);
来源：http://dali.mhx1999.top/Article/details/gt2uqxlbdrf.html

[Q02] 创建带外键的表
来源：http://dali.vqdsnc.cn/Article/details/gt2lpfmwwui.html

CREATE TABLE orders (
来源：http://dali.nwbrower.top/Article/details/gt2wabxldqm.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yanxiufei.cn/Article/details/gt2brmjzwvp.html

user_id INT NOT NULL,
来源：http://dali.chenlongwang.top/Article/details/gt2mzaxcjig.html

amount DECIMAL(10, 2),
来源：http://dali.xuetiantiany.cn/Article/details/gt2cpzobwqu.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.meibo888.top/Article/details/gt2sgrbqymg.html

);
来源：http://dali.jianghu66.top/Article/details/gt2dbkvyslr.html

[Q03] 增加列
来源：http://dali.zhixingplan.top/Article/details/gt2shmkongm.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.birdmap.top/Article/details/gt2vwmyavfd.html

[Q04] 修改列类型
来源：http://dali.ppjwa.cn/Article/details/gt2lpwliqbf.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.wangdashe.top/Article/details/gt2sjkmamqr.html

[Q05] 重命名列
来源：http://dali.jinqigfzy.top/Article/details/gt2xarscllu.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.nanxinkj.top/Article/details/gt2xczqnars.html

[Q06] 删除列
来源：http://dali.gzhubu.top/Article/details/gt2nwscwozm.html


<!-- 参考信息 -->