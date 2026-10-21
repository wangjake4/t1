代发 wailian999

Java: public static void main(String[] args)
来源：http://dali.yanxiufei.cn/Article/details/gtljllhwlg.html

Go:   func main()
来源：http://dali.fengsongda.top/Article/details/gtqihfqxce.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.chenzaomai.com/Article/details/gtglmdiiwz.html

C#:   static void Main(string[] args)
来源：http://dali.zycfv.cn/Article/details/gtvyicnkzi.html

[M08] 获取系统与运行时信息
来源：http://dali.jinqigufen.top/Article/details/gtvfguupmv.html

Py:   platform.system();  platform.python_version()
来源：http://dali.jianghu66.top/Article/details/gtbnnvjkoq.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.gaohongyu789.top/Article/details/gtbmpyjani.html

JS:   process.platform;  process.version
来源：http://dali.tianlin.xyz/Article/details/gtjyuykupt.html

TS:   process.platform;  process.version
来源：http://dali.ywan-chungtsiang.top/Article/details/gtakcwabkt.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjrqwyatm.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.jinghuilouyu.cn/Article/details/gtmurzmhhy.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.yongpay.top/Article/details/gtuapmacri.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.jlsjyb.cn/Article/details/gtnxlkodub.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtypgmnluc.html

N. 数据结构与算法
来源：http://dali.meibo888.top/Article/details/gtrwxmvjsd.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtnzgmdrdh.html

[N01] 二分查找（有序数组）
来源：http://dali.feifeiyinyue.top/Article/details/gtmdlkyyau.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.quarkkingdee.top/Article/details/gtsaniilzq.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.cheryme.top/Article/details/gtnngkpotb.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.ppjwa.cn/Article/details/gtsouoborr.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.guowangkeji.top/Article/details/gtgqownuvf.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.yj20258888.top/Article/details/gtskwgmvgm.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.jinghuilouyu.cn/Article/details/gtealhfsed.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.gotoacloud.top/Article/details/gtxykmvkvu.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.cdnleiting.top/Article/details/gtvhzkmcgb.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.ybcxt.top/Article/details/gtowdevhao.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.ivvv.top/Article/details/gtjesfkatu.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.yvedp.cn/Article/details/gtjkgxagrc.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yuxming.cn/Article/details/gtvymrbcnq.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.sweek.top/Article/details/gtnwqahkju.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.yongpay.top/Article/details/gtzxjsxxfy.html

Go:   slices.Sort(arr)
来源：http://dali.c1oappe.top/Article/details/gtwigoktzb.html

Ruby: arr.sort
来源：http://dali.yonumen.top/Article/details/gtmmjibvvb.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.xuanzx.com/Article/details/gtzvftrdtg.html

[N03] 快速排序（分治示例）
来源：http://dali.yonumen.top/Article/details/gtmjxctaus.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.cucudq.cn/Article/details/gtelomxjzs.html

PHP:  // 递归实现，或用 usort
来源：http://dali.birdmap.top/Article/details/gtglxmbwfy.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.birdmap.top/Article/details/gtogmybjwz.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yueranfly.top/Article/details/gtsbinyiyw.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zdqjudy.top/Article/details/gttnfppsuy.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.hywenlv.cn/Article/details/gtgsecveqx.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.birdmap.top/Article/details/gtrtjnfcws.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.meibo888.top/Article/details/gtemdimbjg.html

[N04] 斐波那契数列
来源：http://dali.birdmap.top/Article/details/gtzexboavl.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.tanke756.top/Article/details/gtzcdrbqbd.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.jinqigfzy.top/Article/details/gtqjxhnlxz.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhoulong.xyz/Article/details/gteuhjpger.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.tian-w.cn/Article/details/gtqiklilcj.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.haohaochexian.top/Article/details/gtmngcqidz.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.meibo888.top/Article/details/gtmkzflqpx.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.pycfn.com/Article/details/gtjlasvzcn.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.guowangkeji.top/Article/details/gtolbxvixz.html

[N05] 最大公约数
来源：http://dali.hammf.cn/Article/details/gtyozjyida.html

Py:   math.gcd(a, b)
来源：http://dali.quarkkingdee.top/Article/details/gtgzvitmku.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.guowangkeji.top/Article/details/gtqcdqygal.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.svipenyu.cn/Article/details/gtwufynsre.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.sweek.top/Article/details/gtshhfjnil.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.bjfxy.top/Article/details/gtvtiddyhe.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.hongshengwenyu.top/Article/details/gtylxwptgr.html

Ruby: a.gcd(b)
来源：http://dali.fengsongda.top/Article/details/gtiuiolobt.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.jlsjyb.cn/Article/details/gtnkenfhjo.html

[N06] 判断回文字符串
来源：http://dali.nwbrower.top/Article/details/gtpxdhfsak.html

Py:   s == s[::-1]
来源：http://dali.sysykeji.top/Article/details/gtfpbwyzfp.html

PHP:  $s === strrev($s);
来源：http://dali.vqdsnc.cn/Article/details/gtarvjsprm.html

JS:   s === [...s].reverse().join("")
来源：http://dali.meibo888.top/Article/details/gtmmuxqdsj.html

TS:   s === [...s].reverse().join("")
来源：http://dali.aibaodan.cn/Article/details/gtimliuygv.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.fzhhl.top/Article/details/gttdjfrjzu.html

Go:   // 双指针从两端比较
来源：http://dali.fengsongda.top/Article/details/gtgpdykzpr.html

Ruby: s == s.reverse
来源：http://dali.ydzc1.top/Article/details/gtzthbjivx.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.hnxiangtu.top/Article/details/gtfqhjpubr.html

[N07] 两数之和（返回下标）
来源：http://dali.yueranfly.top/Article/details/gtvrrgjdee.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.xylfe.cn/Article/details/gtuexrffmn.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.fengsongda.top/Article/details/gtbfmhaxij.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.cashguo.top/Article/details/gtkoulhvpu.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhiwuduotai.top/Article/details/gtnnphfcyh.html

Java: // 手写 HashMap
来源：http://dali.zhiwuduotai.top/Article/details/gtwtqhpden.html

Go:   // 手写 map[int]int
来源：http://dali.sysykeji.top/Article/details/gtzffzvspc.html

Ruby: // 手写 Hash
来源：http://dali.jianghu66.top/Article/details/gtxfukhaxk.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.jianghu66.top/Article/details/gtswuuhrxx.html

[N08] 生成全排列
来源：http://dali.9152youxi.cn/Article/details/gtxtdyixba.html

Py:   itertools.permutations(arr)
来源：http://dali.smart0.xyz/Article/details/gtnjyvsjob.html

PHP:  // 手写递归交换
来源：http://dali.smart0.xyz/Article/details/gthctdijpi.html

JS:   // 手写回溯递归
来源：http://dali.iojbl.cn/Article/details/gtdprhzprj.html

TS:   // 手写回溯递归
来源：http://dali.xuanzx.com/Article/details/gtiifgzidl.html

Java: // 手写回溯递归
来源：http://dali.jinyuanbaomall.cn/Article/details/gttazkqbst.html

Go:   // 手写回溯递归
来源：http://dali.andypj.xyz/Article/details/gttsijozjc.html

Ruby: arr.permutation.to_a
来源：http://dali.shzxlz.cn/Article/details/gtgwtupxia.html

C#:   // 手写回溯递归
来源：http://dali.iojbl.cn/Article/details/gtfwwrokid.html

[N09] 栈与队列
来源：http://dali.wangshuangyany.cn/Article/details/gtlcetazoy.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.jianghu66.top/Article/details/gtbckixhew.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.havefunace.top/Article/details/gtkkyywehw.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gtcgcbnlew.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.redwolf501.top/Article/details/gtzcgsbjyl.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.kuanghao11.cn/Article/details/gtsmybrufn.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.guannengcc.top/Article/details/gthozazpbk.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.yj20258.top/Article/details/gtxdqhqybl.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.hysaishi.cn/Article/details/gtjusetyfx.html

[N10] 链表节点定义
来源：http://dali.zhoulong.xyz/Article/details/gtwreqegbo.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.yvedp.cn/Article/details/gtforgpabr.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zdqjudy.top/Article/details/gtxjtfbcbw.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.dianchejie.cn/Article/details/gtqwrkuiur.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.andypj.xyz/Article/details/gtogwnpxrp.html

Java: class Node { int v; Node next; }
来源：http://dali.ivvv.top/Article/details/gtjixslpju.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.hammf.cn/Article/details/gtlddbxgin.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.wangshuangyany.cn/Article/details/gtyhkgkpxx.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.jianghu66.top/Article/details/gtidxrdvun.html

[N11] 二叉树中序遍历
来源：http://dali.jinqigufen.top/Article/details/gttpehnpgj.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.haohaochexian.top/Article/details/gtybqxckix.html

PHP:  // 手写递归函数
来源：http://dali.sysykeji.top/Article/details/gtceahwepe.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.9152youxi.cn/Article/details/gtnhzlxfyx.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yangfankeji.com/Article/details/gtfjdgaxss.html

Java: // 手写递归
来源：http://dali.sufxvd.cn/Article/details/gtwtnxucfd.html

Go:   // 手写递归
来源：http://dali.hongshengwenyu.top/Article/details/gtndfvtwht.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.chenlongwang.top/Article/details/gtveeunkrk.html

C#:   // 手写递归
来源：http://dali.jlsjyb.cn/Article/details/gtpzqcfkzj.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.bjfxy.top/Article/details/gtwjtoobgr.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.gotoacloud.top/Article/details/gtepjofhdn.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.redwolf501.top/Article/details/gthuokuaif.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yvedp.cn/Article/details/gtnqianadf.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jqgufenzy.top/Article/details/gtjyliozom.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yvedp.cn/Article/details/gtmbstyijv.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.bjfxy.top/Article/details/gtvzsuoozz.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.yongpay.top/Article/details/gtgcocsifn.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.hnqzz.top/Article/details/gtyikqkggw.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtkjyleryj.html

O. 并发与异步
来源：http://dali.yj202588.top/Article/details/gtibtbcqgq.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gthdgruyzw.html

[O01] 启动一个线程
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtamlqvdiw.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhengqikj.top/Article/details/gtkkkbvvcn.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.yueranfly.top/Article/details/gtadtwxqph.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.gotoacloud.top/Article/details/gtlhbvaxyk.html

TS:   // 同 JS
来源：http://dali.yvedp.cn/Article/details/gtlllybezf.html

Java: new Thread(() -> f()).start()
来源：http://dali.316326.xyz/Article/details/gtczporafq.html

Go:   go f()
来源：http://dali.yvedp.cn/Article/details/gtbylwqipd.html

Ruby: Thread.new { f }
来源：http://dali.shuidangran.top/Article/details/gtauombbpu.html

C#:   Task.Run(() => F());
来源：http://dali.svipenyu.cn/Article/details/gtswlhyiig.html

[O02] 使用线程池
来源：http://dali.shanyushiyangtech.top/Article/details/gtwdlmeron.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.ehwqpu.com/Article/details/gtoazcvdrl.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.dianchejie.cn/Article/details/gtrrjepdvg.html

JS:   // worker_threads 线程池
来源：http://dali.guowangkeji.top/Article/details/gtvyfzryld.html

TS:   // worker_threads 线程池
来源：http://dali.jinghuilouyu.cn/Article/details/gtyubropcl.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.dianchejie.cn/Article/details/gtcvixsrmg.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.vqdsnc.cn/Article/details/gthnlttgqa.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.cheryme.top/Article/details/gtgpqmizqi.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.daxiang520.top/Article/details/gtzmcuniob.html

[O03] 加锁保护共享数据
来源：http://dali.pengpengdd.cyou/Article/details/gtdypvautb.html

Py:   with lock: shared += 1
来源：http://dali.sweek.top/Article/details/gtggzqljff.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.c1oappe.top/Article/details/gterddvxic.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.ybcxt.top/Article/details/gtubtebswo.html

TS:   // 同 JS
来源：http://dali.cheryme.top/Article/details/gtzijyfzzm.html

Java: synchronized (this) { shared++; }
来源：http://dali.kuanghao11.cn/Article/details/gtgcwkukmz.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.daria6918.cn/Article/details/gtdlkwhcbb.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.iojbl.cn/Article/details/gtxhxxbnld.html

C#:   lock (gate) { shared++; }
来源：http://dali.feifeiyinyue.top/Article/details/gtvfdwrazh.html

[O04] 定义异步函数并等待
来源：http://dali.shanyushiyangtech.top/Article/details/gtdjozdrmd.html

Py:   async def f():⏎    await g()
来源：http://dali.ppjwa.cn/Article/details/gtilonivts.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.haohaochexian.top/Article/details/gtdkuipqmv.html

JS:   async function f() { await g(); }
来源：http://dali.yj202588.top/Article/details/gttqwyzvsi.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.aibaodan.cn/Article/details/gtaeyugwul.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.wangdashe.top/Article/details/gtnyjfnzjf.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.gaohongyu789.top/Article/details/gtuawqhvcy.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.chenjidiqi.icu/Article/details/gtcctmzfyv.html

C#:   async Task F() { await G(); }
来源：http://dali.9152youxi.cn/Article/details/gtxlhorlly.html

[O05] 并发执行并等待全部完成
来源：http://dali.jyoumei.cn/Article/details/gttxpmvuhq.html

Py:   asyncio.gather(*tasks)
来源：http://dali.sysykeji.top/Article/details/gtbhumzxqb.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.jinqigfzy.top/Article/details/gtontbjuzc.html

JS:   await Promise.all(tasks)
来源：http://dali.yangfankeji.com/Article/details/gtppbtzvht.html

TS:   await Promise.all(tasks)
来源：http://dali.sufxvd.cn/Article/details/gtyuuycxzp.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.hnxiangtu.top/Article/details/gtqpjddzve.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.feifeiyinyue.top/Article/details/gtoqdgmcov.html

Ruby: threads.map(&:join)
来源：http://dali.jinqigufen.top/Article/details/gtsmlrksca.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.havefunace.top/Article/details/gtiltcdaar.html

[O06] 使用进程池
来源：http://dali.yj20258888.top/Article/details/gtvuvpxsgd.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.haohaochexian.top/Article/details/gtyuxszsok.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.hysaishi.cn/Article/details/gtvodubfay.html

JS:   // child_process / cluster 模块
来源：http://dali.jyoumei.cn/Article/details/gtthcazdkh.html

TS:   // child_process / cluster 模块
来源：http://dali.andypj.xyz/Article/details/gtguozjuky.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.tian-w.cn/Article/details/gttejsshhw.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gtwzcgqjut.html

Ruby: // fork 块
来源：http://dali.jlsjyb.cn/Article/details/gtjdmnhwjr.html

C#:   Parallel.For
来源：http://dali.hywenlv.cn/Article/details/gtmxgabpab.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtjggdzhhu.html

P. 常用工具函数
来源：http://dali.andypj.xyz/Article/details/gtbxekrreb.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtcrdldtky.html

[P01] 生成 UUID
来源：http://dali.jlsjyb.cn/Article/details/gtwfextspo.html

Py:   str(uuid.uuid4())
来源：http://dali.jqgufenzy.top/Article/details/gtewuezorp.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.gzhubu.top/Article/details/gtkvzjzjmo.html

JS:   crypto.randomUUID()
来源：http://dali.birdmap.top/Article/details/gtzfjnpqay.html

TS:   crypto.randomUUID()
来源：http://dali.snrcjt.cn/Article/details/gtbpfpmfan.html

Java: UUID.randomUUID().toString()
来源：http://dali.hammf.cn/Article/details/gtzcdodjkq.html

Go:   // 用 github.com/google/uuid
来源：http://dali.yongpay.top/Article/details/gtuaizemct.html

Ruby: SecureRandom.uuid
来源：http://dali.ivvv.top/Article/details/gtlklpwhqx.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.cucudq.cn/Article/details/gtcbpbjgxm.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhaomingkeji.xyz/Article/details/gtucmmljaa.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.guannengcc.top/Article/details/gtonfmzkqi.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.hysaishi.cn/Article/details/gtgmfhtmji.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.meibo888.top/Article/details/gtxhktqnme.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.hysaishi.cn/Article/details/gtyivwgojx.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.chenjidiqi.icu/Article/details/gtsxwrjlof.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.daria6918.cn/Article/details/gtjgarcsbd.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.smart0.xyz/Article/details/gtaktuzaos.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.mhx1999.top/Article/details/gtdjghzcyn.html

[P03] 生成短随机字符串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsoceirju.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.jlsjyb.cn/Article/details/gtuqbscxee.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.9152youxi.cn/Article/details/gtsilhcxla.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.wangdashe.top/Article/details/gtprnqbckl.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.havefunace.top/Article/details/gtkohzvgvd.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.ppjwa.cn/Article/details/gtbhnmcaad.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.pengpengdd.cyou/Article/details/gtehlqealg.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.hysaishi.cn/Article/details/gtcicgjojy.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.c1oappe.top/Article/details/gttpwbkcvy.html

[P04] 求长度
来源：http://dali.wangshuangyany.cn/Article/details/gtkcpyufhu.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.aizwys.cn/Article/details/gticjwkkzg.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.redwolf501.top/Article/details/gtioxjpove.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.aizwys.cn/Article/details/gthrrvpgvp.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yvedp.cn/Article/details/gtcddnjtvq.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbvdaojhf.html

Go:   len(arr);  len(m)
来源：http://dali.chenjidiqi.icu/Article/details/gtrhowslhh.html

Ruby: x.length;  x.size
来源：http://dali.hywenlv.cn/Article/details/gtgsacgagk.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.gogol.net.cn/Article/details/gtxpdktkhi.html

[P05] 判断两个对象内容是否相等
来源：http://dali.wangshuangyany.cn/Article/details/gtwjsquqbv.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.jyoumei.cn/Article/details/gttaicbeeh.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.snrcjt.cn/Article/details/gtagiyulwk.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.cdnleiting.top/Article/details/gtalqzdhtu.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhoulong.xyz/Article/details/gtewiigvns.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.aibaodan.cn/Article/details/gtsrsnpvmu.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.9152youxi.cn/Article/details/gttiikmikh.html

Ruby: a == b
来源：http://dali.redwolf501.top/Article/details/gtzqfsgoso.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.chenlongwang.top/Article/details/gtdbrjvtad.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.guannengcc.top/Article/details/gtfcdpaefb.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.snrcjt.cn/Article/details/gtcckqidxj.html

PHP:  if (empty($x)) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcorywafn.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.hywenlv.cn/Article/details/gttojjlpjs.html

TS:   if (x == null) {}
来源：http://dali.mhx1999.top/Article/details/gtcwptgkad.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zycfv.cn/Article/details/gttcqwsphn.html

Go:   if x == nil {}
来源：http://dali.cucudq.cn/Article/details/gtakovfqwb.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.yonumen.top/Article/details/gtjabnbbdt.html

C#:   if (x is null) {}
来源：http://dali.yuanzhike.top/Article/details/gtytzwvksm.html

[P07] 防抖与节流
来源：http://dali.cdnleiting.top/Article/details/gtcaulwuje.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.bjfxy.top/Article/details/gtkchushsg.html

PHP:  // 手写时间戳比较
来源：http://dali.hfpthk.cn/Article/details/gtkkmzndvt.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yongpay.top/Article/details/gtbnhzaxwc.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjhpreghs.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.yvedp.cn/Article/details/gtmhjpxpqc.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhongyouzk.top/Article/details/gtksshtjmw.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zycfv.cn/Article/details/gtwozdwmyr.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.gogol.net.cn/Article/details/gtxzzovzic.html

[P08] 处理浮点精度问题
来源：http://dali.vqdsnc.cn/Article/details/gtoutliwgt.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.haohaochexian.top/Article/details/gtnndsabve.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.pengpengdd.cyou/Article/details/gtadvfotfc.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.gaohongyu789.top/Article/details/gtoaoeunuf.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmbhcgmup.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.yonumen.top/Article/details/gtdcrttskl.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.sufxvd.cn/Article/details/gtrscsigfj.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.ydzc1.top/Article/details/gtkmqshdzn.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.yanxiufei.cn/Article/details/gtmqqlvhzp.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtegyzuwos.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.hysaishi.cn/Article/details/gtflonnlad.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtrddhxahf.html

[Q01] 创建表
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjvogevve.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gtkyqbirme.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.hongshengwenyu.top/Article/details/gtxmwzjuxk.html

name VARCHAR(50) NOT NULL,
来源：http://dali.guannengcc.top/Article/details/gtbwqekwoq.html

email VARCHAR(100) UNIQUE,
来源：http://dali.nanxuanxn.top/Article/details/gtepbdrzzd.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.kuanghao11.cn/Article/details/gtqlfwergj.html

);
来源：http://dali.chenjidiqi.icu/Article/details/gtlgiiqmoz.html

[Q02] 创建带外键的表
来源：http://dali.zhaomingkeji.xyz/Article/details/gteokaiics.html

CREATE TABLE orders (
来源：http://dali.aibaodan.cn/Article/details/gtixyvbtac.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.chenlongwang.top/Article/details/gtvvnqfxds.html

user_id INT NOT NULL,
来源：http://dali.9152youxi.cn/Article/details/gtmjhuppzg.html

amount DECIMAL(10, 2),
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrckcipje.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.yj20258.top/Article/details/gtdsfijudu.html

);
来源：http://dali.jinqigfzy.top/Article/details/gttbjfawlu.html

[Q03] 增加列
来源：http://dali.tian-w.cn/Article/details/gtnhaexopa.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.316326.xyz/Article/details/gtkdmmdwqj.html

[Q04] 修改列类型
来源：http://dali.hongshengwenyu.top/Article/details/gtvjndlzfy.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.chenjidiqi.icu/Article/details/gtgfggypql.html

[Q05] 重命名列
来源：http://dali.dashuyun.cn/Article/details/gtknyijfua.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.shzxlz.cn/Article/details/gtkjlkxpbq.html

[Q06] 删除列
来源：http://dali.shangyingyoupin.top/Article/details/gtnwlixxpt.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.feifeiyinyue.top/Article/details/gtrvhuqbcf.html

[Q07] 删除表
来源：http://dali.shanyushiyangtech.top/Article/details/gtzaywhyir.html

DROP TABLE IF EXISTS orders;
来源：http://dali.yonumen.top/Article/details/gtdwyseihx.html

[Q08] 创建普通索引
来源：http://dali.sweek.top/Article/details/gtidccjyjw.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.guowangkeji.top/Article/details/gtnchcrejr.html

[Q09] 创建唯一索引
来源：http://dali.hnxiangtu.top/Article/details/gtogedezge.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.guowangkeji.top/Article/details/gtkutuzrqo.html

[Q10] 插入单行
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdmlwhwqf.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.hnqzz.top/Article/details/gtxtqbwaxp.html

[Q11] 一次插入多行
来源：http://dali.wangshuangyany.cn/Article/details/gtfpaarsor.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.zhiwuduotai.top/Article/details/gtpqjpltct.html

[Q12] 插入后取自增 ID
来源：http://dali.jinghuilouyu.cn/Article/details/gtvnqnmfgg.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.sufxvd.cn/Article/details/gtypwzcubj.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.smart0.xyz/Article/details/gtnqtsfibd.html

[Q13] 忽略重复插入
来源：http://dali.smart0.xyz/Article/details/gtxgudugpz.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.daxiang520.top/Article/details/gtkmbsewhg.html

[Q14] 存在则更新（upsert）
来源：http://dali.ivvv.top/Article/details/gtkgfyhnpi.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhoulong.xyz/Article/details/gtfcgdkird.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.chenlongwang.top/Article/details/gtgmnxhkwj.html

[Q15] 查询全部
来源：http://dali.zhijiandao.cn/Article/details/gttiykjjsm.html


<!-- 参考信息 -->