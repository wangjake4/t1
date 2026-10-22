代发 wailian999

Ruby: exit 1
来源：http://dali.aizwys.cn/Article/details/gt2ykdynkkb.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.shangyingyoupin.top/Article/details/gt2igsoekan.html

[M06] 向标准错误输出
来源：http://dali.yanxiufei.cn/Article/details/gt2lysvrwty.html

Py:   print("err", file=sys.stderr)
来源：http://dali.gaohongyu789.top/Article/details/gt2gkvxamgr.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.yanxiufei.cn/Article/details/gt2ytgmpogh.html

JS:   console.error("err")
来源：http://dali.hywenlv.cn/Article/details/gt2rjoyligp.html

TS:   console.error("err")
来源：http://dali.yuanzhike.top/Article/details/gt2ilwzhzch.html

Java: System.err.println("err")
来源：http://dali.zhoulong.xyz/Article/details/gt2gjrnsddo.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhiwuduotai.top/Article/details/gt2sefjazjt.html

Ruby: warn "err"
来源：http://dali.yongpay.top/Article/details/gt2gjfenwdl.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.yj202588.top/Article/details/gt2oqryveoc.html

[M07] 判断是否为主入口
来源：http://dali.cucudq.cn/Article/details/gt2frfdtkfd.html

Py:   if __name__ == "__main__":
来源：http://dali.tianlin.xyz/Article/details/gt2atdjechd.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.aizwys.cn/Article/details/gt2bncqcpin.html

JS:   require.main === module
来源：http://dali.yueranfly.top/Article/details/gt2rthqksjg.html

TS:   require.main === module
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cqbjruul.html

Java: public static void main(String[] args)
来源：http://dali.nanxuanxn.top/Article/details/gt2lxicsbgi.html

Go:   func main()
来源：http://dali.tanke756.top/Article/details/gt2tpdhbpze.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.yangfankeji.com/Article/details/gt2aqlqptmz.html

C#:   static void Main(string[] args)
来源：http://dali.feifeiyinyue.top/Article/details/gt2vkvyiytw.html

[M08] 获取系统与运行时信息
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2trxytfwu.html

Py:   platform.system();  platform.python_version()
来源：http://dali.ydzc1.top/Article/details/gt2vbldrquz.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.sufxvd.cn/Article/details/gt2qnpnhayl.html

JS:   process.platform;  process.version
来源：http://dali.hnqzz.top/Article/details/gt2vcdevhix.html

TS:   process.platform;  process.version
来源：http://dali.0kj1m.cn/Article/details/gt2zmuyumwp.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.hywenlv.cn/Article/details/gt2argmnqsp.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.dianchejie.cn/Article/details/gt2bgauttna.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.ppjwa.cn/Article/details/gt2ecseowyx.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.316326.xyz/Article/details/gt2vodrqapl.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gt2jvtiqabf.html

N. 数据结构与算法
来源：http://dali.dashuyun.cn/Article/details/gt2cvhnglbw.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2foyrrqhx.html

[N01] 二分查找（有序数组）
来源：http://dali.zhoulong.xyz/Article/details/gt2ivklgufe.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.ppjwa.cn/Article/details/gt2lyffatla.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.daxiang520.top/Article/details/gt2tvogjvic.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yvedp.cn/Article/details/gt2ntlhwssg.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.sysykeji.top/Article/details/gt2hvxllhyz.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lfjcscnx.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.yvedp.cn/Article/details/gt2msqejpae.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.hongshengwenyu.top/Article/details/gt2bbfxvxjf.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gnaqzitw.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.gotoacloud.top/Article/details/gt2jnadewwp.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.cheryme.top/Article/details/gt2mnzzkcbk.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.jqgfzy.top/Article/details/gt2nznszkhx.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2esxrwcva.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jianghu66.top/Article/details/gt2cdlchndj.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.tanke756.top/Article/details/gt2ychgpkhu.html

Go:   slices.Sort(arr)
来源：http://dali.yuanzhike.top/Article/details/gt2jrxzxzex.html

Ruby: arr.sort
来源：http://dali.yangfankeji.com/Article/details/gt2uuxsijsg.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhiwuduotai.top/Article/details/gt2llinflry.html

[N03] 快速排序（分治示例）
来源：http://dali.sweek.top/Article/details/gt2nxuzypbt.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.yvedp.cn/Article/details/gt2cyveejox.html

PHP:  // 递归实现，或用 usort
来源：http://dali.jinqigfzy.top/Article/details/gt2nzhuyhxb.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yvedp.cn/Article/details/gt2yvdtzwjg.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.birdmap.top/Article/details/gt2njywbvrd.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.jqgufenzy.top/Article/details/gt2ujipkvvc.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.vqdsnc.cn/Article/details/gt2nipousmk.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.c1oappe.top/Article/details/gt2newzxlbb.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.guowangkeji.top/Article/details/gt2pxwveawo.html

[N04] 斐波那契数列
来源：http://dali.ivvv.top/Article/details/gt2rhmezpnc.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.guannengcc.top/Article/details/gt2vajyzyoj.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xnjbkvqa.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.wangshuangyany.cn/Article/details/gt2gjlmanul.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.dashuyun.cn/Article/details/gt2mutykkjs.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.vqdsnc.cn/Article/details/gt2twwysgtl.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.yuanzhike.top/Article/details/gt2xilfxnmy.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.aibaodan.cn/Article/details/gt2jjvpxobi.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhengqikj.top/Article/details/gt2toiqwtvz.html

[N05] 最大公约数
来源：http://dali.yangfankeji.com/Article/details/gt2wphzguok.html

Py:   math.gcd(a, b)
来源：http://dali.aizwys.cn/Article/details/gt2dobugcbk.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ydmriqtl.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.sysykeji.top/Article/details/gt2ukqelfqt.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.cashguo.top/Article/details/gt2tdzpbyca.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.cashguo.top/Article/details/gt2laukmlwm.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.yanxiufei.cn/Article/details/gt2chskywep.html

Ruby: a.gcd(b)
来源：http://dali.pycfn.com/Article/details/gt2yvudgaom.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bsbxeqay.html

[N06] 判断回文字符串
来源：http://dali.daxiang520.top/Article/details/gt2bpbbgbcx.html

Py:   s == s[::-1]
来源：http://dali.cqqwz.cn/Article/details/gt2lpfrtlkl.html

PHP:  $s === strrev($s);
来源：http://dali.zhoulong.xyz/Article/details/gt2szlniwdi.html

JS:   s === [...s].reverse().join("")
来源：http://dali.ppjwa.cn/Article/details/gt2vufkorgt.html

TS:   s === [...s].reverse().join("")
来源：http://dali.chenjidiqi.icu/Article/details/gt2xyoonftt.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.birdmap.top/Article/details/gt2rfxjcmok.html

Go:   // 双指针从两端比较
来源：http://dali.chenlongwang.top/Article/details/gt2fjpzahud.html

Ruby: s == s.reverse
来源：http://dali.gaohongyu789.top/Article/details/gt2quwhhsdm.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.aizwys.cn/Article/details/gt2jijqlhyf.html

[N07] 两数之和（返回下标）
来源：http://dali.aizwys.cn/Article/details/gt2igslwweh.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pihupfrz.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.ivvv.top/Article/details/gt2tjfqjuva.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.jiagoushi.top/Article/details/gt2ocflwptf.html

TS:   // 手写 Map<string, number>
来源：http://dali.hnxiangtu.top/Article/details/gt2fbozgpgz.html

Java: // 手写 HashMap
来源：http://dali.shanyushiyangtech.top/Article/details/gt2psknkcoc.html

Go:   // 手写 map[int]int
来源：http://dali.jqgfzy.top/Article/details/gt2cbpuazhc.html

Ruby: // 手写 Hash
来源：http://dali.meibo888.top/Article/details/gt2lbzlrufu.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.hnqzz.top/Article/details/gt2fdbwcyjk.html

[N08] 生成全排列
来源：http://dali.zhiwuduotai.top/Article/details/gt2joexyexx.html

Py:   itertools.permutations(arr)
来源：http://dali.meibo888.top/Article/details/gt2mbwfaicu.html

PHP:  // 手写递归交换
来源：http://dali.jinqigufen.top/Article/details/gt2rgnghhbx.html

JS:   // 手写回溯递归
来源：http://dali.jqgufenzy.top/Article/details/gt2dmxskvxt.html

TS:   // 手写回溯递归
来源：http://dali.daxiang520.top/Article/details/gt2xvjttunf.html

Java: // 手写回溯递归
来源：http://dali.nwbrower.top/Article/details/gt2fycqweym.html

Go:   // 手写回溯递归
来源：http://dali.gogol.net.cn/Article/details/gt2lsskhqun.html

Ruby: arr.permutation.to_a
来源：http://dali.birdmap.top/Article/details/gt2yvpiujze.html

C#:   // 手写回溯递归
来源：http://dali.chenlongwang.top/Article/details/gt2xtiezrtf.html

[N09] 栈与队列
来源：http://dali.daria6918.cn/Article/details/gt2jblqwwov.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.quarkkingdee.top/Article/details/gt2xupztyjo.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.wangdashe.top/Article/details/gt2zbuitqet.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.dashuyun.cn/Article/details/gt2wfqpiayl.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.wangdashe.top/Article/details/gt2jixavwia.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.ybcxt.top/Article/details/gt2ulswklbi.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ddhxevud.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.xuetiantiany.cn/Article/details/gt2ysjsoxsm.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.kuanghao11.cn/Article/details/gt2grlqmsfn.html

[N10] 链表节点定义
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yxdfporj.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.yanxiufei.cn/Article/details/gt2ztsafazg.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.havefunace.top/Article/details/gt2wyupjfsg.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.fzhhl.top/Article/details/gt2yiodzfbp.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.cdnleiting.top/Article/details/gt2jbrvwvuo.html

Java: class Node { int v; Node next; }
来源：http://dali.cdnleiting.top/Article/details/gt2sjxruzdb.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.jianghu66.top/Article/details/gt2dqgepxsx.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.chenzaomai.com/Article/details/gt2abbpvssk.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2inyjivby.html

[N11] 二叉树中序遍历
来源：http://dali.zhixingplan.top/Article/details/gt2gpsunuiu.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.chenjidiqi.icu/Article/details/gt2ntwnisfp.html

PHP:  // 手写递归函数
来源：http://dali.guowangkeji.top/Article/details/gt2ghehpldn.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.fzhhl.top/Article/details/gt2dnzyuubw.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhixingplan.top/Article/details/gt2wssktgtv.html

Java: // 手写递归
来源：http://dali.pycfn.com/Article/details/gt2zhcmsyrk.html

Go:   // 手写递归
来源：http://dali.gotoacloud.top/Article/details/gt2qbtvzivm.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.andypj.xyz/Article/details/gt2kcbdbfin.html

C#:   // 手写递归
来源：http://dali.snrcjt.cn/Article/details/gt2ejhwqngx.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.smart0.xyz/Article/details/gt2xvtqjcme.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhixingplan.top/Article/details/gt2elnqrwhn.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.yuxming.cn/Article/details/gt2iqdggsdw.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.haohaochexian.top/Article/details/gt2tpfweheg.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.mhx1999.top/Article/details/gt2yetfnzec.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nqumxgqd.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.fengsongda.top/Article/details/gt2qapcoogm.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.daria6918.cn/Article/details/gt2halyhgqy.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.nwbrower.top/Article/details/gt2zmutbbqd.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tomdbpir.html

O. 并发与异步
来源：http://dali.sweek.top/Article/details/gt2cfknclzp.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gt2dyrsjtnl.html

[O01] 启动一个线程
来源：http://dali.zhengqikj.top/Article/details/gt2ghoutdjz.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vurcqbgh.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.guowangkeji.top/Article/details/gt2mpfjrujv.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.yuxming.cn/Article/details/gt2efqglcye.html

TS:   // 同 JS
来源：http://dali.sufxvd.cn/Article/details/gt2invwpdsy.html

Java: new Thread(() -> f()).start()
来源：http://dali.daria6918.cn/Article/details/gt2ocqkicde.html

Go:   go f()
来源：http://dali.9152youxi.cn/Article/details/gt2aeefxfda.html

Ruby: Thread.new { f }
来源：http://dali.dashuyun.cn/Article/details/gt2wnosalih.html

C#:   Task.Run(() => F());
来源：http://dali.ppjwa.cn/Article/details/gt2frqlwitm.html

[O02] 使用线程池
来源：http://dali.xuetiantiany.cn/Article/details/gt2oxxtywjl.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.sufxvd.cn/Article/details/gt2ubtbydnw.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.yj20258.top/Article/details/gt2dmnnbsdd.html

JS:   // worker_threads 线程池
来源：http://dali.jqgufenzy.top/Article/details/gt2lbamdqhz.html

TS:   // worker_threads 线程池
来源：http://dali.zycfv.cn/Article/details/gt2auisujxz.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.chenjidiqi.icu/Article/details/gt2xukxkouo.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.gaohongyu789.top/Article/details/gt2swqalrcf.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhiwuduotai.top/Article/details/gt2ggytilmc.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.chenjidiqi.icu/Article/details/gt2twfqlicb.html

[O03] 加锁保护共享数据
来源：http://dali.zhoulong.xyz/Article/details/gt2sgguooql.html

Py:   with lock: shared += 1
来源：http://dali.yanxiufei.cn/Article/details/gt2oippqkyp.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.smart0.xyz/Article/details/gt2eegdnbcx.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.feifeiyinyue.top/Article/details/gt2xaoizsjd.html

TS:   // 同 JS
来源：http://dali.ppjwa.cn/Article/details/gt2uzwddhuh.html

Java: synchronized (this) { shared++; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2xfrdnpit.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.shuidangran.top/Article/details/gt2bpibjmji.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.xuanzx.com/Article/details/gt2tbgkihcs.html

C#:   lock (gate) { shared++; }
来源：http://dali.sxryk.cn/Article/details/gt2cbgxndnx.html

[O04] 定义异步函数并等待
来源：http://dali.gzhubu.top/Article/details/gt2uehmhzbe.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2rhlooxgk.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.jlsjyb.cn/Article/details/gt2crtqmbjl.html

JS:   async function f() { await g(); }
来源：http://dali.yueranfly.top/Article/details/gt2sihtdpve.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.aizwys.cn/Article/details/gt2chjwmtix.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.xylfe.cn/Article/details/gt2geyejoms.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.daria6918.cn/Article/details/gt2myrbmjko.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.xylfe.cn/Article/details/gt2uweeesil.html

C#:   async Task F() { await G(); }
来源：http://dali.cdnleiting.top/Article/details/gt2fjwvjvgo.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhengqikj.top/Article/details/gt2mkdnznex.html

Py:   asyncio.gather(*tasks)
来源：http://dali.gzhubu.top/Article/details/gt2yfmpqcta.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.chenjidiqi.icu/Article/details/gt2ahdsvyfm.html

JS:   await Promise.all(tasks)
来源：http://dali.jiagoushi.top/Article/details/gt2zqxgokkg.html

TS:   await Promise.all(tasks)
来源：http://dali.jyoumei.cn/Article/details/gt2volmbplj.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhoulong.xyz/Article/details/gt2zmfltadb.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2kdyrwnwh.html

Ruby: threads.map(&:join)
来源：http://dali.sxryk.cn/Article/details/gt2ekcpjstf.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.gogol.net.cn/Article/details/gt2siphwoid.html

[O06] 使用进程池
来源：http://dali.zhiwuduotai.top/Article/details/gt2gqayhlsp.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.xuetiantiany.cn/Article/details/gt2teguctkf.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.smart0.xyz/Article/details/gt2xqbjxuou.html

JS:   // child_process / cluster 模块
来源：http://dali.cucudq.cn/Article/details/gt2kfhlkrhg.html

TS:   // child_process / cluster 模块
来源：http://dali.andypj.xyz/Article/details/gt2ipqmxydy.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.yonumen.top/Article/details/gt2ekrbnbad.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.svipenyu.cn/Article/details/gt2eehyqurm.html

Ruby: // fork 块
来源：http://dali.aizwys.cn/Article/details/gt2rniififj.html

C#:   Parallel.For
来源：http://dali.guannengcc.top/Article/details/gt2sgczgvjc.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gt2owihoavy.html

P. 常用工具函数
来源：http://dali.tianlin.xyz/Article/details/gt2mjgzngeu.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gt2wegethmc.html

[P01] 生成 UUID
来源：http://dali.nanxuanxn.top/Article/details/gt2orqdvcos.html

Py:   str(uuid.uuid4())
来源：http://dali.sxryk.cn/Article/details/gt2nmskpuoz.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.vqdsnc.cn/Article/details/gt2xzehvkso.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2phzqdkya.html

TS:   crypto.randomUUID()
来源：http://dali.daxiang520.top/Article/details/gt2prsklgmz.html

Java: UUID.randomUUID().toString()
来源：http://dali.yanxiufei.cn/Article/details/gt2nfogzoyi.html

Go:   // 用 github.com/google/uuid
来源：http://dali.cashguo.top/Article/details/gt2jshavaxj.html

Ruby: SecureRandom.uuid
来源：http://dali.hywenlv.cn/Article/details/gt2ovhvgpno.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wicanoxx.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhiwuduotai.top/Article/details/gt2aimfrmft.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.hnxiangtu.top/Article/details/gt2pbuonong.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.cqqwz.cn/Article/details/gt2avgmpiya.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.jinqigfzy.top/Article/details/gt2zkupswqf.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.xuanzx.com/Article/details/gt2dvabufwo.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.tanke756.top/Article/details/gt2klagtifb.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.ybcxt.top/Article/details/gt2hbyfzmxk.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.sufxvd.cn/Article/details/gt2jxopqllu.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhengqikj.top/Article/details/gt2flbduyuq.html

[P03] 生成短随机字符串
来源：http://dali.nanxinkj.top/Article/details/gt2sbodxuev.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhiwuduotai.top/Article/details/gt2ckvtsfww.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.mhx1999.top/Article/details/gt2kzyarhtf.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.fzhhl.top/Article/details/gt2fdjkpqvf.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.gzhubu.top/Article/details/gt2aimdcbxf.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.cqqwz.cn/Article/details/gt2rsfyrvni.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.bjfxy.top/Article/details/gt2egoxsjex.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.aizwys.cn/Article/details/gt2hhjqqptv.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.hammf.cn/Article/details/gt2lceddbeo.html

[P04] 求长度
来源：http://dali.cucudq.cn/Article/details/gt2iainvlxk.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.ehwqpu.com/Article/details/gt2ztzcusmh.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.meibo888.top/Article/details/gt2wjuwddkl.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.haohaochexian.top/Article/details/gt2yfesjurg.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jinqigfzy.top/Article/details/gt2yfgjxzzr.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhiwuduotai.top/Article/details/gt2gjsavrmo.html

Go:   len(arr);  len(m)
来源：http://dali.ppjwa.cn/Article/details/gt2suqntkgd.html

Ruby: x.length;  x.size
来源：http://dali.feifeiyinyue.top/Article/details/gt2rqkwnqpf.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.cdnleiting.top/Article/details/gt2ubqsvjop.html

[P05] 判断两个对象内容是否相等
来源：http://dali.shangyingyoupin.top/Article/details/gt2ksvrudga.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.yj202588.top/Article/details/gt2nbigmrpz.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.yangfankeji.com/Article/details/gt2cxmklogu.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.cdnleiting.top/Article/details/gt2galrfggo.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.yanxiufei.cn/Article/details/gt2idhwhkeb.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.feifeiyinyue.top/Article/details/gt2lmgepsve.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.aizwys.cn/Article/details/gt2ncooxwbx.html

Ruby: a == b
来源：http://dali.jqgufenzy.top/Article/details/gt2jnhuretf.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.jyoumei.cn/Article/details/gt2bzzyczlq.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.0kj1m.cn/Article/details/gt2isttjzzl.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.smart0.xyz/Article/details/gt2ehiifjzv.html

PHP:  if (empty($x)) {}
来源：http://dali.sxryk.cn/Article/details/gt2dofgzuqy.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.9152youxi.cn/Article/details/gt2zipbfdlp.html

TS:   if (x == null) {}
来源：http://dali.iojbl.cn/Article/details/gt2ppjscdwh.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.xylfe.cn/Article/details/gt2cssrardb.html

Go:   if x == nil {}
来源：http://dali.fzhhl.top/Article/details/gt2pihkvwtl.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.hongshengwenyu.top/Article/details/gt2hpvxhbxi.html

C#:   if (x is null) {}
来源：http://dali.cashguo.top/Article/details/gt2wlfivhvr.html

[P07] 防抖与节流
来源：http://dali.hammf.cn/Article/details/gt2kbbrtoyu.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.aizwys.cn/Article/details/gt2rwkcdbfs.html

PHP:  // 手写时间戳比较
来源：http://dali.nanxinkj.top/Article/details/gt2xwbxdxdu.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.xziqi.cn/Article/details/gt2krodvlhn.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mrntmnjt.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.jiagoushi.top/Article/details/gt2ztppdmeu.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.sysykeji.top/Article/details/gt2ppydfyar.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.smart0.xyz/Article/details/gt2hsyyrnzf.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.jyoumei.cn/Article/details/gt2bgegromr.html

[P08] 处理浮点精度问题
来源：http://dali.cdnleiting.top/Article/details/gt2jzpjoqmi.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ewqsvgvj.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.haohaochexian.top/Article/details/gt2qqeimtyu.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.9152youxi.cn/Article/details/gt2ivnaiupz.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.havefunace.top/Article/details/gt2dzuidkiv.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.fengsongda.top/Article/details/gt2yjjkrand.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.9152youxi.cn/Article/details/gt2ffjqsjfn.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.xuanzx.com/Article/details/gt2ecuefcor.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.quarkkingdee.top/Article/details/gt2mgwvmoww.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gt2hevkiulv.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.mhx1999.top/Article/details/gt2othfihdg.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gt2qxbtvuwi.html

[Q01] 创建表
来源：http://dali.aizwys.cn/Article/details/gt2igglwrxf.html

CREATE TABLE users (
来源：http://dali.cqqwz.cn/Article/details/gt2jffiwwzw.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.dianchejie.cn/Article/details/gt2nljtomre.html

name VARCHAR(50) NOT NULL,
来源：http://dali.kuanghao11.cn/Article/details/gt2quhwwurm.html

email VARCHAR(100) UNIQUE,
来源：http://dali.aibaodan.cn/Article/details/gt2cfjgldwn.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.vqdsnc.cn/Article/details/gt2bkmxizgz.html

);
来源：http://dali.gzhubu.top/Article/details/gt2ispqpihl.html

[Q02] 创建带外键的表
来源：http://dali.yj20258.top/Article/details/gt2obsfxmlj.html

CREATE TABLE orders (
来源：http://dali.hammf.cn/Article/details/gt2zaituzox.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.tianlin.xyz/Article/details/gt2krotqunn.html

user_id INT NOT NULL,
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2riufoavw.html

amount DECIMAL(10, 2),
来源：http://dali.fengsongda.top/Article/details/gt2qhcbddad.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.shuidangran.top/Article/details/gt2haceodgo.html

);
来源：http://dali.aibaodan.cn/Article/details/gt2mxmhjoxc.html

[Q03] 增加列
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wbddwkke.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.hongshengwenyu.top/Article/details/gt2jrvhjbhr.html

[Q04] 修改列类型
来源：http://dali.wangdashe.top/Article/details/gt2dgmhnkui.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.sweek.top/Article/details/gt2wlwpigky.html

[Q05] 重命名列
来源：http://dali.yangfankeji.com/Article/details/gt2pdmvnlhb.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.guowangkeji.top/Article/details/gt2nlesoqhu.html

[Q06] 删除列
来源：http://dali.andypj.xyz/Article/details/gt2elfmamzp.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.ydzc1.top/Article/details/gt2bdhjkcdl.html

[Q07] 删除表
来源：http://dali.zycfv.cn/Article/details/gt2njhgudly.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zdqjudy.top/Article/details/gt2platcwwm.html

[Q08] 创建普通索引
来源：http://dali.sufxvd.cn/Article/details/gt2ivbbisib.html


<!-- 参考信息 -->