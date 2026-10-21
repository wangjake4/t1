代发 wailian999

JS:   process.exit(1)
来源：http://dali.aizwys.cn/Article/details/gtxljbjuax.html

TS:   process.exit(1)
来源：http://dali.chenzaomai.com/Article/details/gtdakinmdb.html

Java: System.exit(1)
来源：http://dali.yangfankeji.com/Article/details/gtcowgdyul.html

Go:   os.Exit(1)
来源：http://dali.fzhhl.top/Article/details/gtpdsgtbbv.html

Ruby: exit 1
来源：http://dali.svipenyu.cn/Article/details/gtxbhhxyyi.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhiwuduotai.top/Article/details/gtcyphctzm.html

[M06] 向标准错误输出
来源：http://dali.wangdashe.top/Article/details/gtlvfwzyjw.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhoulong.xyz/Article/details/gtxxtdmpyq.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.316326.xyz/Article/details/gthzjqqzhu.html

JS:   console.error("err")
来源：http://dali.feifeiyinyue.top/Article/details/gtzfprffdq.html

TS:   console.error("err")
来源：http://dali.yuanzhike.top/Article/details/gtndqwgzuj.html

Java: System.err.println("err")
来源：http://dali.cheryme.top/Article/details/gtbkfymois.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.yuxming.cn/Article/details/gtavxnshoa.html

Ruby: warn "err"
来源：http://dali.birdmap.top/Article/details/gtqigropjd.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.jqgfzy.top/Article/details/gtznurekud.html

[M07] 判断是否为主入口
来源：http://dali.c1oappe.top/Article/details/gtpayiivvp.html

Py:   if __name__ == "__main__":
来源：http://dali.sweek.top/Article/details/gtkslxxvng.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.gaohongyu789.top/Article/details/gtmvxhlokj.html

JS:   require.main === module
来源：http://dali.tianlin.xyz/Article/details/gtpxplapsd.html

TS:   require.main === module
来源：http://dali.jyoumei.cn/Article/details/gteqjxdftz.html

Java: public static void main(String[] args)
来源：http://dali.pengpengdd.cyou/Article/details/gtehznxnwa.html

Go:   func main()
来源：http://dali.xinyue.icu/Article/details/gtxwhspxbr.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.birdmap.top/Article/details/gteccopbmg.html

C#:   static void Main(string[] args)
来源：http://dali.yj20258.top/Article/details/gttohccctj.html

[M08] 获取系统与运行时信息
来源：http://dali.zhoulong.xyz/Article/details/gtvzbhmccz.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhiwuduotai.top/Article/details/gtgmzurbga.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.hfpthk.cn/Article/details/gtpwzgsecz.html

JS:   process.platform;  process.version
来源：http://dali.xylfe.cn/Article/details/gtoatvyquu.html

TS:   process.platform;  process.version
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrtdynrer.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.hfpthk.cn/Article/details/gtqiiinhsx.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.havefunace.top/Article/details/gtrxxaanmg.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.daria6918.cn/Article/details/gtlfbwdezs.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.ppjwa.cn/Article/details/gtrnxcbbwk.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtspxmvust.html

N. 数据结构与算法
来源：http://dali.hysaishi.cn/Article/details/gtmoyshziy.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gthrbcwtpm.html

[N01] 二分查找（有序数组）
来源：http://dali.hywenlv.cn/Article/details/gtwqlobted.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.mhx1999.top/Article/details/gtzygjdanf.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.snrcjt.cn/Article/details/gtuuyywtzo.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.dianchejie.cn/Article/details/gtjxfnjvfo.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.daria6918.cn/Article/details/gtzlmfisqn.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.pycfn.com/Article/details/gtcjiofxtm.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.smart0.xyz/Article/details/gtgajxycyi.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.yueranfly.top/Article/details/gtrzjkfjhh.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.dianchejie.cn/Article/details/gtcrsqcikw.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.tian-w.cn/Article/details/gtxkflkzmz.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.fengsongda.top/Article/details/gtwmqhogky.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.cdnleiting.top/Article/details/gtsvhixcjq.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.gaohongyu789.top/Article/details/gtqljhndgd.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.haohaochexian.top/Article/details/gtxjclaihh.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.sxryk.cn/Article/details/gtrsudgcei.html

Go:   slices.Sort(arr)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzetgzjzg.html

Ruby: arr.sort
来源：http://dali.jqgfzy.top/Article/details/gtbrbsmjtl.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.c1oappe.top/Article/details/gtbrvpiqhm.html

[N03] 快速排序（分治示例）
来源：http://dali.tian-w.cn/Article/details/gtsdcqfcrr.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zdqjudy.top/Article/details/gtmjnrwrqr.html

PHP:  // 递归实现，或用 usort
来源：http://dali.jqgfzy.top/Article/details/gtuintfbje.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.aizwys.cn/Article/details/gtqrhirsai.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.pengpengdd.cyou/Article/details/gtsbtbqslf.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.yj20258.top/Article/details/gtpibgztgf.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.meibo888.top/Article/details/gtasxbofxt.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.redwolf501.top/Article/details/gtatzpqyju.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gtweqdpcbw.html

[N04] 斐波那契数列
来源：http://dali.birdmap.top/Article/details/gtkzhhvugd.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zdqjudy.top/Article/details/gtsnmqgrus.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.cdnleiting.top/Article/details/gtacbiwsle.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.birdmap.top/Article/details/gtimaizsyo.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.chenjidiqi.icu/Article/details/gtrxqgjiia.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.guowangkeji.top/Article/details/gtlgfupchx.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtarredjii.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhixingplan.top/Article/details/gtgfaxjeum.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnkkqozju.html

[N05] 最大公约数
来源：http://dali.mhx1999.top/Article/details/gtgksxknet.html

Py:   math.gcd(a, b)
来源：http://dali.hongshengwenyu.top/Article/details/gtegmqsqdd.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.birdmap.top/Article/details/gtnnhkiqyl.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.xylfe.cn/Article/details/gttzkazdms.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.xinyue.icu/Article/details/gthuygjmtz.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.aibaodan.cn/Article/details/gtyglfbnqb.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.c1oappe.top/Article/details/gthvyotcvl.html

Ruby: a.gcd(b)
来源：http://dali.daxiang520.top/Article/details/gtwuynjyff.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.tian-w.cn/Article/details/gthyxvjvrn.html

[N06] 判断回文字符串
来源：http://dali.c1oappe.top/Article/details/gteftojegs.html

Py:   s == s[::-1]
来源：http://dali.yuanzhike.top/Article/details/gtiikycpfc.html

PHP:  $s === strrev($s);
来源：http://dali.daxiang520.top/Article/details/gtiggdzvun.html

JS:   s === [...s].reverse().join("")
来源：http://dali.jinyuanbaomall.cn/Article/details/gthmajokqe.html

TS:   s === [...s].reverse().join("")
来源：http://dali.vqdsnc.cn/Article/details/gtqrndjtxy.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.9152youxi.cn/Article/details/gtobbjhsxn.html

Go:   // 双指针从两端比较
来源：http://dali.haohaochexian.top/Article/details/gtgsfpassg.html

Ruby: s == s.reverse
来源：http://dali.yanxiufei.cn/Article/details/gtigdtjpom.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.wangdashe.top/Article/details/gtheakglwp.html

[N07] 两数之和（返回下标）
来源：http://dali.cashguo.top/Article/details/gthohedrcs.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.gaohongyu789.top/Article/details/gtcuzrqmoe.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.yj202588.top/Article/details/gtfigqlhtd.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.sxryk.cn/Article/details/gtwntjytxf.html

TS:   // 手写 Map<string, number>
来源：http://dali.fzhhl.top/Article/details/gtdfetfbat.html

Java: // 手写 HashMap
来源：http://dali.zhongyouzk.top/Article/details/gtejjthwfl.html

Go:   // 手写 map[int]int
来源：http://dali.jqgufenzy.top/Article/details/gtdizkmcnn.html

Ruby: // 手写 Hash
来源：http://dali.cheryme.top/Article/details/gtcqgimgxj.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.shanyushiyangtech.top/Article/details/gtqwdqvgjz.html

[N08] 生成全排列
来源：http://dali.yanxiufei.cn/Article/details/gttymqyrch.html

Py:   itertools.permutations(arr)
来源：http://dali.hnxiangtu.top/Article/details/gtzaxmddou.html

PHP:  // 手写递归交换
来源：http://dali.jqgfzy.top/Article/details/gtlstmqzhp.html

JS:   // 手写回溯递归
来源：http://dali.nanxuanxn.top/Article/details/gtuafglfwt.html

TS:   // 手写回溯递归
来源：http://dali.9152youxi.cn/Article/details/gtpxetxhuw.html

Java: // 手写回溯递归
来源：http://dali.pengpengdd.cyou/Article/details/gtccbvhdvh.html

Go:   // 手写回溯递归
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwnzvubok.html

Ruby: arr.permutation.to_a
来源：http://dali.chenjidiqi.icu/Article/details/gtdjvihlwj.html

C#:   // 手写回溯递归
来源：http://dali.chenzaomai.com/Article/details/gtmlzqdews.html

[N09] 栈与队列
来源：http://dali.pengpengdd.cyou/Article/details/gtzfswgafw.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.yonumen.top/Article/details/gtftruwmbt.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.nanxinkj.top/Article/details/gtyppwfkxx.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvhjpyayg.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.gaohongyu789.top/Article/details/gtfyiwseiw.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.vqdsnc.cn/Article/details/gtzqclftcp.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.yanxiufei.cn/Article/details/gtpdsuwupb.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.yanxiufei.cn/Article/details/gtgarkefra.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.daria6918.cn/Article/details/gtkvxbokqw.html

[N10] 链表节点定义
来源：http://dali.jqgufenzy.top/Article/details/gtihnzxrds.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.havefunace.top/Article/details/gtztkeqmhn.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.chenjidiqi.icu/Article/details/gtiwyjiflx.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.redwolf501.top/Article/details/gtengzeapt.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.sufxvd.cn/Article/details/gtadzlqrhh.html

Java: class Node { int v; Node next; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjifaogkw.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.nwbrower.top/Article/details/gtkdhrgeya.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.nwbrower.top/Article/details/gthehzjxwa.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.hywenlv.cn/Article/details/gtmaohvrsu.html

[N11] 二叉树中序遍历
来源：http://dali.aibaodan.cn/Article/details/gtvtohfjsx.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.shuidangran.top/Article/details/gtswwnbxpn.html

PHP:  // 手写递归函数
来源：http://dali.gaohongyu789.top/Article/details/gtkxgupdhz.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.hfpthk.cn/Article/details/gtbkrrhdqp.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.kuanghao11.cn/Article/details/gtwmfueynp.html

Java: // 手写递归
来源：http://dali.hnqzz.top/Article/details/gtoxczgigu.html

Go:   // 手写递归
来源：http://dali.yuanzhike.top/Article/details/gtcseldgmd.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrtzghkhu.html

C#:   // 手写递归
来源：http://dali.hongshengwenyu.top/Article/details/gtjlozfsod.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.birdmap.top/Article/details/gtvtiikwlo.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.shangyingyoupin.top/Article/details/gtfvlfxidi.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.yj202588.top/Article/details/gtqanaxwkb.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqqgrojxe.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.cashguo.top/Article/details/gtrieslvyx.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.0kj1m.cn/Article/details/gtymzeglgy.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.yj20258888.top/Article/details/gtwmvcleym.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.shanyushiyangtech.top/Article/details/gtodcvnxtd.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yanxiufei.cn/Article/details/gtdgatdsvj.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtamikhxcm.html

O. 并发与异步
来源：http://dali.haohaochexian.top/Article/details/gtpbjnzynr.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtiivrpmdi.html

[O01] 启动一个线程
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrocctoow.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.shangyingyoupin.top/Article/details/gtudeuchtv.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.gotoacloud.top/Article/details/gtnrztugox.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.gzhubu.top/Article/details/gtnewgecvl.html

TS:   // 同 JS
来源：http://dali.xylfe.cn/Article/details/gtdyjlezbk.html

Java: new Thread(() -> f()).start()
来源：http://dali.yuanzhike.top/Article/details/gtvseyjzvz.html

Go:   go f()
来源：http://dali.cheryme.top/Article/details/gtejypzsui.html

Ruby: Thread.new { f }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtufgmyuyn.html

C#:   Task.Run(() => F());
来源：http://dali.jinqigufen.top/Article/details/gtlvbfmfxi.html

[O02] 使用线程池
来源：http://dali.kuanghao11.cn/Article/details/gttbhpibzm.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.xuetiantiany.cn/Article/details/gtlibyxumq.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.sysykeji.top/Article/details/gtrnsxagyv.html

JS:   // worker_threads 线程池
来源：http://dali.svipenyu.cn/Article/details/gtebijouok.html

TS:   // worker_threads 线程池
来源：http://dali.yj20258.top/Article/details/gtjuyzorko.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.guowangkeji.top/Article/details/gtpyetizkf.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.tian-w.cn/Article/details/gtpzzoatfd.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.chenzaomai.com/Article/details/gtkfmvsexb.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.birdmap.top/Article/details/gtbvlsqowo.html

[O03] 加锁保护共享数据
来源：http://dali.redwolf501.top/Article/details/gtpkprerry.html

Py:   with lock: shared += 1
来源：http://dali.shangyingyoupin.top/Article/details/gthvssreke.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhaomingkeji.xyz/Article/details/gtejpqcbcy.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.daxiang520.top/Article/details/gtvlpqdcbw.html

TS:   // 同 JS
来源：http://dali.jqgfzy.top/Article/details/gtpmudgtfm.html

Java: synchronized (this) { shared++; }
来源：http://dali.cucudq.cn/Article/details/gtdiveojys.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.yanxiufei.cn/Article/details/gtzwbtxtzw.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.nanxuanxn.top/Article/details/gtdccaemip.html

C#:   lock (gate) { shared++; }
来源：http://dali.nwbrower.top/Article/details/gteyuvuzka.html

[O04] 定义异步函数并等待
来源：http://dali.tian-w.cn/Article/details/gttdrqmeer.html

Py:   async def f():⏎    await g()
来源：http://dali.cashguo.top/Article/details/gtfqhtvbui.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.wangshuangyany.cn/Article/details/gtmhwxwmcm.html

JS:   async function f() { await g(); }
来源：http://dali.gaohongyu789.top/Article/details/gtpxfhihed.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.kuanghao11.cn/Article/details/gteqafbrpj.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.shzxlz.cn/Article/details/gtuopbayop.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.aibaodan.cn/Article/details/gtbufjbzzw.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.mhx1999.top/Article/details/gtpkbhqqpd.html

C#:   async Task F() { await G(); }
来源：http://dali.zycfv.cn/Article/details/gtnrfffudy.html

[O05] 并发执行并等待全部完成
来源：http://dali.dashuyun.cn/Article/details/gtyglcqggq.html

Py:   asyncio.gather(*tasks)
来源：http://dali.ybcxt.top/Article/details/gtqjyetqle.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhoulong.xyz/Article/details/gtvnzjlyjo.html

JS:   await Promise.all(tasks)
来源：http://dali.nanxinkj.top/Article/details/gtiqqqclwt.html

TS:   await Promise.all(tasks)
来源：http://dali.gogol.net.cn/Article/details/gtdsvcpmmi.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.snrcjt.cn/Article/details/gtgmmmdmhp.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.bjfxy.top/Article/details/gtgybthxgo.html

Ruby: threads.map(&:join)
来源：http://dali.iojbl.cn/Article/details/gtlbvagubp.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.yangfankeji.com/Article/details/gtyzukkhuw.html

[O06] 使用进程池
来源：http://dali.cqqwz.cn/Article/details/gtzcvyrsla.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.yj20258888.top/Article/details/gtmgabntmw.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.gzhubu.top/Article/details/gtgbjrtdzg.html

JS:   // child_process / cluster 模块
来源：http://dali.tanke756.top/Article/details/gtnzrdhhpn.html

TS:   // child_process / cluster 模块
来源：http://dali.iojbl.cn/Article/details/gtxagqfhwk.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.wangdashe.top/Article/details/gtwhrrylll.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.yuanzhike.top/Article/details/gtxfariwfi.html

Ruby: // fork 块
来源：http://dali.yanxiufei.cn/Article/details/gtjhlxjibc.html

C#:   Parallel.For
来源：http://dali.bjfxy.top/Article/details/gtdwegmtnt.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtcwvkqqce.html

P. 常用工具函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmuphsvmy.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gthrtdunjj.html

[P01] 生成 UUID
来源：http://dali.andypj.xyz/Article/details/gtjnktdasi.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gtlknvzwyg.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhongyouzk.top/Article/details/gtxzlgwoqm.html

JS:   crypto.randomUUID()
来源：http://dali.jinghuilouyu.cn/Article/details/gtqnhoqpet.html

TS:   crypto.randomUUID()
来源：http://dali.316326.xyz/Article/details/gtrtqckztf.html

Java: UUID.randomUUID().toString()
来源：http://dali.cqqwz.cn/Article/details/gtlngpgelt.html

Go:   // 用 github.com/google/uuid
来源：http://dali.gogol.net.cn/Article/details/gtorexefyc.html

Ruby: SecureRandom.uuid
来源：http://dali.zhixingplan.top/Article/details/gtjvrcpsix.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.pycfn.com/Article/details/gtsujlrbeq.html

[P02] MD5 / SHA256 摘要
来源：http://dali.jianghu66.top/Article/details/gtdsyktcob.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.xylfe.cn/Article/details/gtpfnxabnh.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zycfv.cn/Article/details/gtfgvszuat.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.guowangkeji.top/Article/details/gtzfmqxoix.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.ivvv.top/Article/details/gtmjfzhzgo.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.tianlin.xyz/Article/details/gtritgphnb.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.cheryme.top/Article/details/gtfqxxpero.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.yueranfly.top/Article/details/gtxnmbfvug.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.xuetiantiany.cn/Article/details/gtbiwnvmxj.html

[P03] 生成短随机字符串
来源：http://dali.yongpay.top/Article/details/gtzkpbjovx.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.birdmap.top/Article/details/gtwfvewphu.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.hnqzz.top/Article/details/gtvtsgvrgf.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.quarkkingdee.top/Article/details/gtyyrhiopp.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.hongshengwenyu.top/Article/details/gtqdffiaea.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.feifeiyinyue.top/Article/details/gtwqohuxgv.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.fzhhl.top/Article/details/gtssnadlnz.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.ehwqpu.com/Article/details/gtciydekwl.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.jianghu66.top/Article/details/gthggbmlww.html

[P04] 求长度
来源：http://dali.guowangkeji.top/Article/details/gtfhxcqpne.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.chenjidiqi.icu/Article/details/gtonqjodne.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.daxiang520.top/Article/details/gtvayzicca.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jinqigufen.top/Article/details/gtncvjmqvz.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.kuanghao11.cn/Article/details/gtiazzypjd.html

Java: list.size();  map.size();  s.length()
来源：http://dali.ybcxt.top/Article/details/gtamnwtlhj.html

Go:   len(arr);  len(m)
来源：http://dali.yj202588.top/Article/details/gtgnwqekxe.html

Ruby: x.length;  x.size
来源：http://dali.hongshengwenyu.top/Article/details/gtgxinprgp.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.cheryme.top/Article/details/gtbzbxapjb.html

[P05] 判断两个对象内容是否相等
来源：http://dali.cqqwz.cn/Article/details/gtlqpzmowb.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.jinqigufen.top/Article/details/gtxbsfhlau.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.vqdsnc.cn/Article/details/gtskkikghu.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.birdmap.top/Article/details/gttakhjylo.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxqmmrelz.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.hfpthk.cn/Article/details/gtztwrygjg.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.quarkkingdee.top/Article/details/gtrnuwrnrl.html

Ruby: a == b
来源：http://dali.shuidangran.top/Article/details/gtwjdmuqxo.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.smart0.xyz/Article/details/gtygbqothz.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.yuanzhike.top/Article/details/gtrmfxsetj.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.cdnleiting.top/Article/details/gtccecfgrr.html

PHP:  if (empty($x)) {}
来源：http://dali.redwolf501.top/Article/details/gtcazcjcqb.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.xziqi.cn/Article/details/gtcodkzqlk.html

TS:   if (x == null) {}
来源：http://dali.daria6918.cn/Article/details/gtmtpgivbk.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.xuanzx.com/Article/details/gtmtddgnlu.html

Go:   if x == nil {}
来源：http://dali.daxiang520.top/Article/details/gtfnlqihox.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.sysykeji.top/Article/details/gtwbgttqup.html

C#:   if (x is null) {}
来源：http://dali.ivvv.top/Article/details/gtmrktuotk.html

[P07] 防抖与节流
来源：http://dali.meibo888.top/Article/details/gteogcrqxa.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.jlsjyb.cn/Article/details/gtcwxupojd.html

PHP:  // 手写时间戳比较
来源：http://dali.0kj1m.cn/Article/details/gtbqtgvgii.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.sufxvd.cn/Article/details/gtyubwuguw.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.dianchejie.cn/Article/details/gtzedlbrwn.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gthuxsuueo.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.yj202588.top/Article/details/gtnuzhigmq.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.guannengcc.top/Article/details/gtresdxvad.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.snrcjt.cn/Article/details/gtsznypwfx.html

[P08] 处理浮点精度问题
来源：http://dali.zhengqikj.top/Article/details/gthimtgxbu.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.tian-w.cn/Article/details/gtglrdznma.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.xylfe.cn/Article/details/gtgrdudrkv.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhoulong.xyz/Article/details/gteotqfgmi.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.yuanzhike.top/Article/details/gtanlqxsbo.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.redwolf501.top/Article/details/gtxygxgjuf.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.wangshuangyany.cn/Article/details/gtxjfxjsvz.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.yuxming.cn/Article/details/gtzarcvzig.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.yvedp.cn/Article/details/gtonszrkrv.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtdhxhcdyz.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.xinyue.icu/Article/details/gtisuufyhr.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtacxwuavx.html

[Q01] 创建表
来源：http://dali.sysykeji.top/Article/details/gtmhepapxn.html

CREATE TABLE users (
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnbnjsxej.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.kuanghao11.cn/Article/details/gtquxlleeo.html

name VARCHAR(50) NOT NULL,
来源：http://dali.chenjidiqi.icu/Article/details/gtseqcbxhc.html

email VARCHAR(100) UNIQUE,
来源：http://dali.tanke756.top/Article/details/gttluvegcf.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.hnxiangtu.top/Article/details/gtercycpjn.html

);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrclbpugh.html

[Q02] 创建带外键的表
来源：http://dali.fengsongda.top/Article/details/gtnxfxdlmn.html

CREATE TABLE orders (
来源：http://dali.shanyushiyangtech.top/Article/details/gtwilanrcb.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.9152youxi.cn/Article/details/gtzxxzmzly.html

user_id INT NOT NULL,
来源：http://dali.jianghu66.top/Article/details/gtsyhqqqua.html

amount DECIMAL(10, 2),
来源：http://dali.zhaomingkeji.xyz/Article/details/gtljxjzaut.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.jqgufenzy.top/Article/details/gtclwijuda.html

);
来源：http://dali.nwbrower.top/Article/details/gtujaspzpg.html

[Q03] 增加列
来源：http://dali.yj20258.top/Article/details/gtujliwotf.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.yanxiufei.cn/Article/details/gteguuykxk.html

[Q04] 修改列类型
来源：http://dali.dianchejie.cn/Article/details/gtvuqnnzby.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtepbnvfvu.html

[Q05] 重命名列
来源：http://dali.jyoumei.cn/Article/details/gtrqpxilyg.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.gogol.net.cn/Article/details/gtdoiwsfak.html

[Q06] 删除列
来源：http://dali.yongpay.top/Article/details/gtlbcmpmlm.html


<!-- 参考信息 -->