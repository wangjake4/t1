代发 wailian999

JS:   process.exit(1)
来源：http://dali.sxryk.cn/Article/details/gt2ovfatiij.html

TS:   process.exit(1)
来源：http://dali.guannengcc.top/Article/details/gt2jmmtrvey.html

Java: System.exit(1)
来源：http://dali.svipenyu.cn/Article/details/gt2twejfuir.html

Go:   os.Exit(1)
来源：http://dali.cucudq.cn/Article/details/gt2gtiuytal.html

Ruby: exit 1
来源：http://dali.hnxiangtu.top/Article/details/gt2dbwzazzu.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zdqjudy.top/Article/details/gt2ushkuacz.html

[M06] 向标准错误输出
来源：http://dali.jqgfzy.top/Article/details/gt2nnoxxfqs.html

Py:   print("err", file=sys.stderr)
来源：http://dali.9152youxi.cn/Article/details/gt2psgikbez.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.aibaodan.cn/Article/details/gt2vgrcazlb.html

JS:   console.error("err")
来源：http://dali.yj202588.top/Article/details/gt2xrqwgtvs.html

TS:   console.error("err")
来源：http://dali.gotoacloud.top/Article/details/gt2pmzjbkhx.html

Java: System.err.println("err")
来源：http://dali.gotoacloud.top/Article/details/gt2grvzzrni.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhoulong.xyz/Article/details/gt2zmkhbozx.html

Ruby: warn "err"
来源：http://dali.gogol.net.cn/Article/details/gt2tdqmspzk.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.jinqigufen.top/Article/details/gt2ceilohkd.html

[M07] 判断是否为主入口
来源：http://dali.chenjidiqi.icu/Article/details/gt2uvvwnazv.html

Py:   if __name__ == "__main__":
来源：http://dali.yueranfly.top/Article/details/gt2ffephpqg.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.hammf.cn/Article/details/gt2lybqdmkl.html

JS:   require.main === module
来源：http://dali.xziqi.cn/Article/details/gt2pqwrmfpb.html

TS:   require.main === module
来源：http://dali.gzhubu.top/Article/details/gt2htoskfsu.html

Java: public static void main(String[] args)
来源：http://dali.dianchejie.cn/Article/details/gt2bvcbyzjh.html

Go:   func main()
来源：http://dali.smart0.xyz/Article/details/gt2tmzcwmtf.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.bjfxy.top/Article/details/gt2uimmgmtr.html

C#:   static void Main(string[] args)
来源：http://dali.ybcxt.top/Article/details/gt2inoijziz.html

[M08] 获取系统与运行时信息
来源：http://dali.andypj.xyz/Article/details/gt2rklmnaqv.html

Py:   platform.system();  platform.python_version()
来源：http://dali.jinqigfzy.top/Article/details/gt2wxbctohp.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fuomasgc.html

JS:   process.platform;  process.version
来源：http://dali.hysaishi.cn/Article/details/gt2monvlakr.html

TS:   process.platform;  process.version
来源：http://dali.nwbrower.top/Article/details/gt2rlehptea.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.cucudq.cn/Article/details/gt2ymtfvdau.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zdqjudy.top/Article/details/gt2xvcroird.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.hywenlv.cn/Article/details/gt2dkbyshac.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.xziqi.cn/Article/details/gt2ffecrpjf.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gt2kwterovu.html

N. 数据结构与算法
来源：http://dali.jlsjyb.cn/Article/details/gt2cgoqtawz.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gt2mjcjmbcc.html

[N01] 二分查找（有序数组）
来源：http://dali.cashguo.top/Article/details/gt2gvrgvkgr.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.dianchejie.cn/Article/details/gt2sqczifnc.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.hnqzz.top/Article/details/gt2jjjuaqog.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.svipenyu.cn/Article/details/gt2fjqfbsja.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.0kj1m.cn/Article/details/gt2sbmwwsig.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.quarkkingdee.top/Article/details/gt2ekryfvup.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.aibaodan.cn/Article/details/gt2rrgdnhnz.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.jyoumei.cn/Article/details/gt2wfmpoofh.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.jinqigfzy.top/Article/details/gt2zuskamzn.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.vqdsnc.cn/Article/details/gt2mhqekmpv.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.xinyue.icu/Article/details/gt2phbuqvqg.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ahjmrauc.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jinqigufen.top/Article/details/gt2zkigwuwq.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.snrcjt.cn/Article/details/gt2arvfnedk.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.wangdashe.top/Article/details/gt2mdzvtszm.html

Go:   slices.Sort(arr)
来源：http://dali.jianghu66.top/Article/details/gt2tchoetui.html

Ruby: arr.sort
来源：http://dali.hysaishi.cn/Article/details/gt2pntnyape.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.feifeiyinyue.top/Article/details/gt2lnwrcwlb.html

[N03] 快速排序（分治示例）
来源：http://dali.zdqjudy.top/Article/details/gt2hlrgmptg.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dkmlcslh.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhiwuduotai.top/Article/details/gt2bqkhzcrq.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.wangdashe.top/Article/details/gt2kpnsvtbg.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.havefunace.top/Article/details/gt2kmkhtuob.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.jiagoushi.top/Article/details/gt2efutcrxx.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.smart0.xyz/Article/details/gt2gdjmjrhl.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.hysaishi.cn/Article/details/gt2othjnauv.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bproervm.html

[N04] 斐波那契数列
来源：http://dali.sweek.top/Article/details/gt2njwrufdj.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.aibaodan.cn/Article/details/gt2uawkawtn.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.0kj1m.cn/Article/details/gt2fwuzrnbj.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yuxming.cn/Article/details/gt2typyimam.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.ivvv.top/Article/details/gt2hkzjzenv.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.wangshuangyany.cn/Article/details/gt2rcmevdyh.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.dashuyun.cn/Article/details/gt2hwxpwtlz.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.yanxiufei.cn/Article/details/gt2nnuwrrar.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.snrcjt.cn/Article/details/gt2rkkvtcyu.html

[N05] 最大公约数
来源：http://dali.fzhhl.top/Article/details/gt2zyjpfamj.html

Py:   math.gcd(a, b)
来源：http://dali.jinqigufen.top/Article/details/gt2jpqlrxnc.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.nanxinkj.top/Article/details/gt2dnlcoipv.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.sysykeji.top/Article/details/gt2hpvbbgap.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2ojjmcnvn.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhoulong.xyz/Article/details/gt2psilygyh.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.daxiang520.top/Article/details/gt2bqxvhrdl.html

Ruby: a.gcd(b)
来源：http://dali.xuetiantiany.cn/Article/details/gt2gzpfzzzd.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.chenjidiqi.icu/Article/details/gt2swwrgtxz.html

[N06] 判断回文字符串
来源：http://dali.iojbl.cn/Article/details/gt2twtfdlpp.html

Py:   s == s[::-1]
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gnofbuio.html

PHP:  $s === strrev($s);
来源：http://dali.sweek.top/Article/details/gt2jeoknxuz.html

JS:   s === [...s].reverse().join("")
来源：http://dali.cucudq.cn/Article/details/gt2tfujpold.html

TS:   s === [...s].reverse().join("")
来源：http://dali.guowangkeji.top/Article/details/gt2bifgdrgq.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhoulong.xyz/Article/details/gt2nxopyfet.html

Go:   // 双指针从两端比较
来源：http://dali.cqqwz.cn/Article/details/gt2drgpbcup.html

Ruby: s == s.reverse
来源：http://dali.ehwqpu.com/Article/details/gt2zymzqixt.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.cdnleiting.top/Article/details/gt2rurniirm.html

[N07] 两数之和（返回下标）
来源：http://dali.yvedp.cn/Article/details/gt2vgkoemjj.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.yuanzhike.top/Article/details/gt2ajsbkomm.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.cheryme.top/Article/details/gt2llptimxq.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.cqqwz.cn/Article/details/gt2lhuvsobz.html

TS:   // 手写 Map<string, number>
来源：http://dali.jlsjyb.cn/Article/details/gt2achzlnpq.html

Java: // 手写 HashMap
来源：http://dali.yueranfly.top/Article/details/gt2griynskh.html

Go:   // 手写 map[int]int
来源：http://dali.jinqigfzy.top/Article/details/gt2ddchdjno.html

Ruby: // 手写 Hash
来源：http://dali.svipenyu.cn/Article/details/gt2ntnwfksy.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.fengsongda.top/Article/details/gt2gvctoshu.html

[N08] 生成全排列
来源：http://dali.nanxinkj.top/Article/details/gt2sjuymqsn.html

Py:   itertools.permutations(arr)
来源：http://dali.9152youxi.cn/Article/details/gt2yfpsogls.html

PHP:  // 手写递归交换
来源：http://dali.hywenlv.cn/Article/details/gt2fasqyhnj.html

JS:   // 手写回溯递归
来源：http://dali.guannengcc.top/Article/details/gt2bgcpshdf.html

TS:   // 手写回溯递归
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2majasrou.html

Java: // 手写回溯递归
来源：http://dali.yuanzhike.top/Article/details/gt2nvgcysku.html

Go:   // 手写回溯递归
来源：http://dali.feifeiyinyue.top/Article/details/gt2wqmqeajw.html

Ruby: arr.permutation.to_a
来源：http://dali.zycfv.cn/Article/details/gt2pmpwtkln.html

C#:   // 手写回溯递归
来源：http://dali.yuxming.cn/Article/details/gt2cmubfamo.html

[N09] 栈与队列
来源：http://dali.nanxuanxn.top/Article/details/gt2owyhvcmm.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.hnxiangtu.top/Article/details/gt2brvcqfvy.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.yuxming.cn/Article/details/gt2giwozquh.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.hammf.cn/Article/details/gt2ryvmmjjm.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.kuanghao11.cn/Article/details/gt2yhfwfnhj.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.nanxinkj.top/Article/details/gt2oqdzvkmn.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.dianchejie.cn/Article/details/gt2wotkiitv.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.cqqwz.cn/Article/details/gt2mfxmfcrg.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.chenzaomai.com/Article/details/gt2imxxbaxo.html

[N10] 链表节点定义
来源：http://dali.daxiang520.top/Article/details/gt2pssxnhvy.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.sxryk.cn/Article/details/gt2vwhepnnt.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.jqgufenzy.top/Article/details/gt2mjcabjjq.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhiwuduotai.top/Article/details/gt2dssmciwn.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.jqgufenzy.top/Article/details/gt2nzqgkhli.html

Java: class Node { int v; Node next; }
来源：http://dali.dianchejie.cn/Article/details/gt2qicpxaqn.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.jianghu66.top/Article/details/gt2siuyhtwo.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.xziqi.cn/Article/details/gt2rgyqjkhm.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nvocimom.html

[N11] 二叉树中序遍历
来源：http://dali.yongpay.top/Article/details/gt2omkazexo.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhoulong.xyz/Article/details/gt2etndmqjq.html

PHP:  // 手写递归函数
来源：http://dali.hongshengwenyu.top/Article/details/gt2okruyawc.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yonumen.top/Article/details/gt2scwbmprz.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.gogol.net.cn/Article/details/gt2ldkupvzl.html

Java: // 手写递归
来源：http://dali.chenlongwang.top/Article/details/gt2wyxyksmo.html

Go:   // 手写递归
来源：http://dali.jiagoushi.top/Article/details/gt2iyxcoyey.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.daxiang520.top/Article/details/gt2nspxzahf.html

C#:   // 手写递归
来源：http://dali.hongshengwenyu.top/Article/details/gt2szsslemz.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.cashguo.top/Article/details/gt2ocjgyesf.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.havefunace.top/Article/details/gt2zlpsbjmo.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.gzhubu.top/Article/details/gt2rajhoeuq.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.hysaishi.cn/Article/details/gt2wjurdpcc.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.guowangkeji.top/Article/details/gt2ortjaepm.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.tianlin.xyz/Article/details/gt2dxctbkkp.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.wangshuangyany.cn/Article/details/gt2jsetwkcx.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.9152youxi.cn/Article/details/gt2nxkohqmi.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.svipenyu.cn/Article/details/gt2ibsodtfi.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gt2vpvrxtfr.html

O. 并发与异步
来源：http://dali.kuanghao11.cn/Article/details/gt2glsbmnuu.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2sqidqszc.html

[O01] 启动一个线程
来源：http://dali.wangshuangyany.cn/Article/details/gt2fnkckcye.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.hongshengwenyu.top/Article/details/gt2vdajlaog.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.redwolf501.top/Article/details/gt2jssqftxc.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.wangdashe.top/Article/details/gt2egnuvthw.html

TS:   // 同 JS
来源：http://dali.gaohongyu789.top/Article/details/gt2ciyaqlqo.html

Java: new Thread(() -> f()).start()
来源：http://dali.ppjwa.cn/Article/details/gt2gulziwuq.html

Go:   go f()
来源：http://dali.zdqjudy.top/Article/details/gt2esvbvici.html

Ruby: Thread.new { f }
来源：http://dali.yangfankeji.com/Article/details/gt2wybjyhmt.html

C#:   Task.Run(() => F());
来源：http://dali.bjfxy.top/Article/details/gt2krtnbzsv.html

[O02] 使用线程池
来源：http://dali.zycfv.cn/Article/details/gt2tfouerxj.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.guowangkeji.top/Article/details/gt2ngvzgkio.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.c1oappe.top/Article/details/gt2svmsctgo.html

JS:   // worker_threads 线程池
来源：http://dali.pycfn.com/Article/details/gt2lnbuqdrh.html

TS:   // worker_threads 线程池
来源：http://dali.chenlongwang.top/Article/details/gt2ytbafpju.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rkcoijcz.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.feifeiyinyue.top/Article/details/gt2ibqhwfmz.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.yangfankeji.com/Article/details/gt2hihzxnao.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.xuanzx.com/Article/details/gt2wfcooavl.html

[O03] 加锁保护共享数据
来源：http://dali.pycfn.com/Article/details/gt2evikhosn.html

Py:   with lock: shared += 1
来源：http://dali.zdqjudy.top/Article/details/gt2uepeddws.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.sxryk.cn/Article/details/gt2bkxkzuyv.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gzierzsn.html

TS:   // 同 JS
来源：http://dali.yj20258888.top/Article/details/gt2ljpmdjnz.html

Java: synchronized (this) { shared++; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2lrnloumg.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.yanxiufei.cn/Article/details/gt2gzgucfxc.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.316326.xyz/Article/details/gt2dtvoxgtb.html

C#:   lock (gate) { shared++; }
来源：http://dali.jinqigfzy.top/Article/details/gt2fhflfsdq.html

[O04] 定义异步函数并等待
来源：http://dali.quarkkingdee.top/Article/details/gt2sunolasd.html

Py:   async def f():⏎    await g()
来源：http://dali.sysykeji.top/Article/details/gt2lxsjebnl.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.xinyue.icu/Article/details/gt2kssgjgtf.html

JS:   async function f() { await g(); }
来源：http://dali.daxiang520.top/Article/details/gt2nxvugstz.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.xziqi.cn/Article/details/gt2kqmpnqie.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.yj20258.top/Article/details/gt2sexbmzxg.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.fengsongda.top/Article/details/gt2eccjsxsf.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.fengsongda.top/Article/details/gt2clydspru.html

C#:   async Task F() { await G(); }
来源：http://dali.pycfn.com/Article/details/gt2quqwvxsi.html

[O05] 并发执行并等待全部完成
来源：http://dali.ppjwa.cn/Article/details/gt2tonsjlkz.html

Py:   asyncio.gather(*tasks)
来源：http://dali.tian-w.cn/Article/details/gt2shxkeygu.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vnzjikts.html

JS:   await Promise.all(tasks)
来源：http://dali.yuxming.cn/Article/details/gt2rnhtgbmz.html

TS:   await Promise.all(tasks)
来源：http://dali.ehwqpu.com/Article/details/gt2fkjtghdr.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhixingplan.top/Article/details/gt2ykeoztym.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.yvedp.cn/Article/details/gt2vymnumki.html

Ruby: threads.map(&:join)
来源：http://dali.yj20258.top/Article/details/gt2wttqyazw.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.yongpay.top/Article/details/gt2dtohrpon.html

[O06] 使用进程池
来源：http://dali.jqgfzy.top/Article/details/gt2urdmlfpo.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.jqgfzy.top/Article/details/gt2jnppzkiv.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.bjfxy.top/Article/details/gt2mdutbdjx.html

JS:   // child_process / cluster 模块
来源：http://dali.zycfv.cn/Article/details/gt2tcxazmfu.html

TS:   // child_process / cluster 模块
来源：http://dali.cucudq.cn/Article/details/gt2crsqcgcr.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hmoquwsy.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.guowangkeji.top/Article/details/gt2ipjbjmwt.html

Ruby: // fork 块
来源：http://dali.bjfxy.top/Article/details/gt2sxibrnwp.html

C#:   Parallel.For
来源：http://dali.sysykeji.top/Article/details/gt2qkrimsyj.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gt2ycoipzzz.html

P. 常用工具函数
来源：http://dali.dashuyun.cn/Article/details/gt2crkdnygb.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gt2mpvfrwml.html

[P01] 生成 UUID
来源：http://dali.jqgufenzy.top/Article/details/gt2axytzlit.html

Py:   str(uuid.uuid4())
来源：http://dali.hongshengwenyu.top/Article/details/gt2sshtkunr.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.mhx1999.top/Article/details/gt2lavjhgll.html

JS:   crypto.randomUUID()
来源：http://dali.hnxiangtu.top/Article/details/gt2oukmdmey.html

TS:   crypto.randomUUID()
来源：http://dali.hnqzz.top/Article/details/gt2pubmdzbn.html

Java: UUID.randomUUID().toString()
来源：http://dali.yongpay.top/Article/details/gt2bcfpovmf.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhoulong.xyz/Article/details/gt2wvgwcmku.html

Ruby: SecureRandom.uuid
来源：http://dali.jianghu66.top/Article/details/gt2xznvcdwf.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.yj20258888.top/Article/details/gt2dkazgega.html

[P02] MD5 / SHA256 摘要
来源：http://dali.dianchejie.cn/Article/details/gt2eckzyirn.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.yueranfly.top/Article/details/gt2fanqkxvj.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2regqayos.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.jlsjyb.cn/Article/details/gt2yoroegtz.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.cqqwz.cn/Article/details/gt2erebbrey.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.redwolf501.top/Article/details/gt2iqtxgent.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.yueranfly.top/Article/details/gt2aclxswsi.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.chenlongwang.top/Article/details/gt2bwjohhxk.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.jinqigufen.top/Article/details/gt2ckdsafna.html

[P03] 生成短随机字符串
来源：http://dali.yj20258.top/Article/details/gt2vegktuuz.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.fengsongda.top/Article/details/gt2voowhmty.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.cqqwz.cn/Article/details/gt2esnqoyvs.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yuxming.cn/Article/details/gt2lupsvogo.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.snrcjt.cn/Article/details/gt2uoktykdz.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.quarkkingdee.top/Article/details/gt2cwrgfjqy.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.gzhubu.top/Article/details/gt2jpjutfvg.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.yangfankeji.com/Article/details/gt2ojtipfun.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.daxiang520.top/Article/details/gt2djcrhupu.html

[P04] 求长度
来源：http://dali.jqgufenzy.top/Article/details/gt2yheaearz.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.tanke756.top/Article/details/gt2dbywnkgl.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.hnqzz.top/Article/details/gt2tourhkyw.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.hnqzz.top/Article/details/gt2sozuxfty.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.daxiang520.top/Article/details/gt2degbapmo.html

Java: list.size();  map.size();  s.length()
来源：http://dali.cqqwz.cn/Article/details/gt2ygfimply.html

Go:   len(arr);  len(m)
来源：http://dali.wangdashe.top/Article/details/gt2mjjujldk.html

Ruby: x.length;  x.size
来源：http://dali.bjfxy.top/Article/details/gt2ksjnxrsa.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.tanke756.top/Article/details/gt2daqezwsw.html

[P05] 判断两个对象内容是否相等
来源：http://dali.vqdsnc.cn/Article/details/gt2huymxwoc.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.yonumen.top/Article/details/gt2xkpecmui.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.aibaodan.cn/Article/details/gt2zondpyhr.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.yj20258888.top/Article/details/gt2klklgogv.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.hysaishi.cn/Article/details/gt2uwqhfvqq.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.yj20258.top/Article/details/gt2nohhnfgq.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.hnqzz.top/Article/details/gt2yzwkoaey.html

Ruby: a == b
来源：http://dali.cdnleiting.top/Article/details/gt2lzpblpyh.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.tianlin.xyz/Article/details/gt2aqadmpdf.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.vqdsnc.cn/Article/details/gt2djzwjppr.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.yvedp.cn/Article/details/gt2peslszws.html

PHP:  if (empty($x)) {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2dsyinlkj.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.fengsongda.top/Article/details/gt2zvewxhgc.html

TS:   if (x == null) {}
来源：http://dali.andypj.xyz/Article/details/gt2jmkjompe.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.ehwqpu.com/Article/details/gt2eoahyioq.html

Go:   if x == nil {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2cohnpcwa.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.meibo888.top/Article/details/gt2xlroehsx.html

C#:   if (x is null) {}
来源：http://dali.chenzaomai.com/Article/details/gt2shhcrfbt.html

[P07] 防抖与节流
来源：http://dali.zdqjudy.top/Article/details/gt2mhclbash.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.jlsjyb.cn/Article/details/gt2qatquyty.html

PHP:  // 手写时间戳比较
来源：http://dali.tanke756.top/Article/details/gt2pqlzbdwx.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.c1oappe.top/Article/details/gt2wkbwvwte.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.cashguo.top/Article/details/gt2ltozjyvg.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.birdmap.top/Article/details/gt2tbluxzna.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.hysaishi.cn/Article/details/gt2vkuarvfb.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.xylfe.cn/Article/details/gt2aepohcwc.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ghhnhuha.html

[P08] 处理浮点精度问题
来源：http://dali.ybcxt.top/Article/details/gt2fycwdxdi.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.cucudq.cn/Article/details/gt2vlwfhiiy.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.hysaishi.cn/Article/details/gt2mnzzgtzx.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.chenjidiqi.icu/Article/details/gt2toexmhkp.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.9152youxi.cn/Article/details/gt2epgadyka.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.shzxlz.cn/Article/details/gt2gvycrjig.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.0kj1m.cn/Article/details/gt2qeohyelc.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fvmoqizf.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.snrcjt.cn/Article/details/gt2sccdkysf.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gt2egvpyeca.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.chenjidiqi.icu/Article/details/gt2baulnxdz.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gt2vytqrnfq.html

[Q01] 创建表
来源：http://dali.hysaishi.cn/Article/details/gt2marzezlw.html

CREATE TABLE users (
来源：http://dali.yongpay.top/Article/details/gt2smptjcql.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.snrcjt.cn/Article/details/gt2zesrmnor.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhixingplan.top/Article/details/gt2mytbpfbd.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhoulong.xyz/Article/details/gt2tjyedkmg.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.316326.xyz/Article/details/gt2msmlozam.html

);
来源：http://dali.ivvv.top/Article/details/gt2odxvsysu.html

[Q02] 创建带外键的表
来源：http://dali.sweek.top/Article/details/gt2quehmkdu.html

CREATE TABLE orders (
来源：http://dali.kuanghao11.cn/Article/details/gt2hwnigoka.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.sufxvd.cn/Article/details/gt2tzmwfpbs.html

user_id INT NOT NULL,
来源：http://dali.jiagoushi.top/Article/details/gt2sbjdifss.html

amount DECIMAL(10, 2),
来源：http://dali.quarkkingdee.top/Article/details/gt2relkbmxw.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.birdmap.top/Article/details/gt2plvcgspl.html

);
来源：http://dali.daxiang520.top/Article/details/gt2ncifhomn.html

[Q03] 增加列
来源：http://dali.xuanzx.com/Article/details/gt2whfekxnq.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.gzhubu.top/Article/details/gt2xfiaoeat.html

[Q04] 修改列类型
来源：http://dali.fengsongda.top/Article/details/gt2giisavlr.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.sysykeji.top/Article/details/gt2qtndvgru.html

[Q05] 重命名列
来源：http://dali.guannengcc.top/Article/details/gt2snhjuxvi.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.jinqigfzy.top/Article/details/gt2witqvahq.html

[Q06] 删除列
来源：http://dali.gaohongyu789.top/Article/details/gt2bosztdya.html


<!-- 参考信息 -->