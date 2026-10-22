代发 wailian999

JS:   process.exit(1)
来源：http://dali.fzhhl.top/Article/details/gtybnjhlfk.html

TS:   process.exit(1)
来源：http://dali.feifeiyinyue.top/Article/details/gtewixidnd.html

Java: System.exit(1)
来源：http://dali.quarkkingdee.top/Article/details/gtpoicsjlp.html

Go:   os.Exit(1)
来源：http://dali.daxiang520.top/Article/details/gtwmmdghfw.html

Ruby: exit 1
来源：http://dali.ybcxt.top/Article/details/gtnymnhpxr.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhixingplan.top/Article/details/gtkzvgypoz.html

[M06] 向标准错误输出
来源：http://dali.yj20258888.top/Article/details/gtteinsifd.html

Py:   print("err", file=sys.stderr)
来源：http://dali.hysaishi.cn/Article/details/gtetvmlncg.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.jianghu66.top/Article/details/gtazbnxxly.html

JS:   console.error("err")
来源：http://dali.feifeiyinyue.top/Article/details/gtwehjmzfy.html

TS:   console.error("err")
来源：http://dali.sufxvd.cn/Article/details/gtksewkwve.html

Java: System.err.println("err")
来源：http://dali.nanxinkj.top/Article/details/gtgtsksrqj.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.pycfn.com/Article/details/gtirgvdmdo.html

Ruby: warn "err"
来源：http://dali.jyoumei.cn/Article/details/gtwfsxcucn.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.c1oappe.top/Article/details/gtetcuuete.html

[M07] 判断是否为主入口
来源：http://dali.pycfn.com/Article/details/gtznyzgvwl.html

Py:   if __name__ == "__main__":
来源：http://dali.jinghuilouyu.cn/Article/details/gtmlhjdivi.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.xinyue.icu/Article/details/gtkyrpcxuj.html

JS:   require.main === module
来源：http://dali.chenjidiqi.icu/Article/details/gtyglcztdk.html

TS:   require.main === module
来源：http://dali.pengpengdd.cyou/Article/details/gtnunimlki.html

Java: public static void main(String[] args)
来源：http://dali.jqgufenzy.top/Article/details/gtcucthcje.html

Go:   func main()
来源：http://dali.guowangkeji.top/Article/details/gttcanxwwk.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.xziqi.cn/Article/details/gtlcqzosvf.html

C#:   static void Main(string[] args)
来源：http://dali.shangyingyoupin.top/Article/details/gtdamhbnmm.html

[M08] 获取系统与运行时信息
来源：http://dali.meibo888.top/Article/details/gtcdjnathe.html

Py:   platform.system();  platform.python_version()
来源：http://dali.haohaochexian.top/Article/details/gtttsvnqzv.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.xuetiantiany.cn/Article/details/gtmnnehznz.html

JS:   process.platform;  process.version
来源：http://dali.tian-w.cn/Article/details/gttuulvlag.html

TS:   process.platform;  process.version
来源：http://dali.hammf.cn/Article/details/gtbrqpdssi.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.guannengcc.top/Article/details/gttuopnemu.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.yvedp.cn/Article/details/gtqnmcjava.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.hysaishi.cn/Article/details/gtgzhlrrir.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.sysykeji.top/Article/details/gtnwqkhfwm.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtwydmxmhp.html

N. 数据结构与算法
来源：http://dali.jqgfzy.top/Article/details/gtndimilod.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtlfvbwwhv.html

[N01] 二分查找（有序数组）
来源：http://dali.xuanzx.com/Article/details/gtdmnwdkju.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.sufxvd.cn/Article/details/gtrkqpyvxs.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.jiagoushi.top/Article/details/gtabhuyfsm.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.gzhubu.top/Article/details/gtbziwauko.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zycfv.cn/Article/details/gtvdajeffl.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhiwuduotai.top/Article/details/gtjcbrqvqr.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.fzhhl.top/Article/details/gtapkengkx.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhoulong.xyz/Article/details/gtrzwmporj.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.cucudq.cn/Article/details/gtfmafhpdd.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.ywan-chungtsiang.top/Article/details/gthheiinlv.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.gzhubu.top/Article/details/gtceieszij.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.haohaochexian.top/Article/details/gtpjrptgqw.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jlsjyb.cn/Article/details/gtfspcoutx.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.daria6918.cn/Article/details/gtomwyzeat.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.vqdsnc.cn/Article/details/gtxklacjeu.html

Go:   slices.Sort(arr)
来源：http://dali.ppjwa.cn/Article/details/gtwmuvdory.html

Ruby: arr.sort
来源：http://dali.jiagoushi.top/Article/details/gtwgxnhjds.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtulnbxtts.html

[N03] 快速排序（分治示例）
来源：http://dali.hammf.cn/Article/details/gtfnrqfowa.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnrekpcli.html

PHP:  // 递归实现，或用 usort
来源：http://dali.guowangkeji.top/Article/details/gtqojpbspt.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.ivvv.top/Article/details/gttipioyhq.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.fzhhl.top/Article/details/gtzotwjhpb.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhongyouzk.top/Article/details/gtcnhynpki.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.aibaodan.cn/Article/details/gtqakloovv.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.gaohongyu789.top/Article/details/gtpvststyv.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.ppjwa.cn/Article/details/gtadffmnzv.html

[N04] 斐波那契数列
来源：http://dali.gzhubu.top/Article/details/gtrvbxsphy.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.chenzaomai.com/Article/details/gtfoelcbyp.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.gogol.net.cn/Article/details/gtbpkezvsj.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.daria6918.cn/Article/details/gtgzutlkxn.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.nanxuanxn.top/Article/details/gtwkctvymb.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.redwolf501.top/Article/details/gtdpzdmljh.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.gzhubu.top/Article/details/gtkkxhbgzl.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.dianchejie.cn/Article/details/gtjolizbzx.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.sysykeji.top/Article/details/gtfoxgsids.html

[N05] 最大公约数
来源：http://dali.xuanzx.com/Article/details/gtyqjnoigi.html

Py:   math.gcd(a, b)
来源：http://dali.wangshuangyany.cn/Article/details/gtvfbpbhih.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.sweek.top/Article/details/gthfiotwey.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhiwuduotai.top/Article/details/gtefyfmisl.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.ybcxt.top/Article/details/gtabfumney.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.aibaodan.cn/Article/details/gtdkkxfayv.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.ybcxt.top/Article/details/gtrzjatljd.html

Ruby: a.gcd(b)
来源：http://dali.wangshuangyany.cn/Article/details/gtgwyihqws.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.tanke756.top/Article/details/gtfbskluil.html

[N06] 判断回文字符串
来源：http://dali.xinyue.icu/Article/details/gtrkmkwfno.html

Py:   s == s[::-1]
来源：http://dali.nanxinkj.top/Article/details/gtlklxmurm.html

PHP:  $s === strrev($s);
来源：http://dali.havefunace.top/Article/details/gtiteaqgjo.html

JS:   s === [...s].reverse().join("")
来源：http://dali.shuidangran.top/Article/details/gtenfwvier.html

TS:   s === [...s].reverse().join("")
来源：http://dali.chenlongwang.top/Article/details/gtczhhgnte.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.hongshengwenyu.top/Article/details/gtoxzbgkzg.html

Go:   // 双指针从两端比较
来源：http://dali.shanyushiyangtech.top/Article/details/gtwludvlgh.html

Ruby: s == s.reverse
来源：http://dali.shangyingyoupin.top/Article/details/gtrrggdykv.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.yvedp.cn/Article/details/gtoizscgqp.html

[N07] 两数之和（返回下标）
来源：http://dali.yj20258.top/Article/details/gtqtbgngmx.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.birdmap.top/Article/details/gtzmjeeetu.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.sweek.top/Article/details/gtzlqhisee.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.yuanzhike.top/Article/details/gtbjsphhar.html

TS:   // 手写 Map<string, number>
来源：http://dali.ppjwa.cn/Article/details/gtdgxbbivp.html

Java: // 手写 HashMap
来源：http://dali.fengsongda.top/Article/details/gtxfmqvbag.html

Go:   // 手写 map[int]int
来源：http://dali.jinqigfzy.top/Article/details/gthofhyfzf.html

Ruby: // 手写 Hash
来源：http://dali.ywan-chungtsiang.top/Article/details/gtncjecatq.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.shanyushiyangkeji.top/Article/details/gtttaibgnl.html

[N08] 生成全排列
来源：http://dali.hfpthk.cn/Article/details/gtfudkzptt.html

Py:   itertools.permutations(arr)
来源：http://dali.shanyushiyangtech.top/Article/details/gthymlsyvy.html

PHP:  // 手写递归交换
来源：http://dali.jinqigfzy.top/Article/details/gtbvohqnln.html

JS:   // 手写回溯递归
来源：http://dali.chenjidiqi.icu/Article/details/gtszldwkje.html

TS:   // 手写回溯递归
来源：http://dali.aibaodan.cn/Article/details/gtzqmlokbd.html

Java: // 手写回溯递归
来源：http://dali.hnqzz.top/Article/details/gtdnktzuud.html

Go:   // 手写回溯递归
来源：http://dali.zhengqikj.top/Article/details/gtafzfokks.html

Ruby: arr.permutation.to_a
来源：http://dali.yvedp.cn/Article/details/gtxcfystba.html

C#:   // 手写回溯递归
来源：http://dali.chenzaomai.com/Article/details/gtbmvrvuhr.html

[N09] 栈与队列
来源：http://dali.zhengqikj.top/Article/details/gtpdrdsqrb.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.ybcxt.top/Article/details/gtftafvtpz.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.jiagoushi.top/Article/details/gtssbjqprp.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhengqikj.top/Article/details/gtlqbtueap.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.nwbrower.top/Article/details/gtcszvekpg.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.tanke756.top/Article/details/gtpewzmhbu.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhoulong.xyz/Article/details/gtvkjkangt.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.ppjwa.cn/Article/details/gtzzqwxvtk.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.aibaodan.cn/Article/details/gtxqjzlwby.html

[N10] 链表节点定义
来源：http://dali.zhaomingkeji.xyz/Article/details/gtddygclrf.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.quarkkingdee.top/Article/details/gtdyxwusjp.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.yvedp.cn/Article/details/gtlvkootdg.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtssnyuprx.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.ybcxt.top/Article/details/gtlxcddspc.html

Java: class Node { int v; Node next; }
来源：http://dali.xziqi.cn/Article/details/gtnsasbodd.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.tianlin.xyz/Article/details/gtpyplniyr.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.sxryk.cn/Article/details/gtfvazmmim.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gttrzfnpnw.html

[N11] 二叉树中序遍历
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdwdvelij.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.havefunace.top/Article/details/gtkiywqhgs.html

PHP:  // 手写递归函数
来源：http://dali.ppjwa.cn/Article/details/gtatlizywx.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jinqigufen.top/Article/details/gtperxsqmd.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.kuanghao11.cn/Article/details/gtzcnxjwqo.html

Java: // 手写递归
来源：http://dali.jlsjyb.cn/Article/details/gtgubettai.html

Go:   // 手写递归
来源：http://dali.cheryme.top/Article/details/gtsswuzyqa.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.yangfankeji.com/Article/details/gtxzywpkvh.html

C#:   // 手写递归
来源：http://dali.hnqzz.top/Article/details/gtetfyjony.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.birdmap.top/Article/details/gtwxwijttk.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.cqqwz.cn/Article/details/gtnzzpknbo.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.yj20258888.top/Article/details/gtjauctjjs.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.hywenlv.cn/Article/details/gtnoymrama.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfzklczwj.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.nwbrower.top/Article/details/gtfjdbskkr.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.gotoacloud.top/Article/details/gtufspioqe.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdkgudcgx.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.bjfxy.top/Article/details/gtntcykqtf.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtaoonpfxn.html

O. 并发与异步
来源：http://dali.tianlin.xyz/Article/details/gtxpnyqbbh.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgvpndmxp.html

[O01] 启动一个线程
来源：http://dali.jqgfzy.top/Article/details/gtqdkjviia.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.mhx1999.top/Article/details/gtqahyrnry.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.bjfxy.top/Article/details/gtosxtcjir.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.9152youxi.cn/Article/details/gttusvfmvu.html

TS:   // 同 JS
来源：http://dali.jinqigufen.top/Article/details/gtbhrleclv.html

Java: new Thread(() -> f()).start()
来源：http://dali.yanxiufei.cn/Article/details/gtvdnvfgjd.html

Go:   go f()
来源：http://dali.jiagoushi.top/Article/details/gtlhsgxykh.html

Ruby: Thread.new { f }
来源：http://dali.jianghu66.top/Article/details/gtcararabp.html

C#:   Task.Run(() => F());
来源：http://dali.daria6918.cn/Article/details/gtukzhvgtc.html

[O02] 使用线程池
来源：http://dali.dianchejie.cn/Article/details/gtoafuphlx.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.9152youxi.cn/Article/details/gtnxhfegma.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.jqgfzy.top/Article/details/gtweuwbztj.html

JS:   // worker_threads 线程池
来源：http://dali.jqgufenzy.top/Article/details/gtdjioodqg.html

TS:   // worker_threads 线程池
来源：http://dali.daxiang520.top/Article/details/gtjndcefar.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.jinqigufen.top/Article/details/gtpizwlstv.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.xuanzx.com/Article/details/gtpksdlfiu.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.fengsongda.top/Article/details/gthyonrcdm.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhiwuduotai.top/Article/details/gtgplhmuzy.html

[O03] 加锁保护共享数据
来源：http://dali.gaohongyu789.top/Article/details/gtmpubgarp.html

Py:   with lock: shared += 1
来源：http://dali.xuetiantiany.cn/Article/details/gtotvjfcaf.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.cashguo.top/Article/details/gtyuaseymr.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.yongpay.top/Article/details/gtuevaclxo.html

TS:   // 同 JS
来源：http://dali.svipenyu.cn/Article/details/gtyijiwyph.html

Java: synchronized (this) { shared++; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtqmzmjshq.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhoulong.xyz/Article/details/gtzapsdnxc.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.shuidangran.top/Article/details/gtaqgafaby.html

C#:   lock (gate) { shared++; }
来源：http://dali.shangyingyoupin.top/Article/details/gtqpuksvqk.html

[O04] 定义异步函数并等待
来源：http://dali.jqgufenzy.top/Article/details/gtxggbaokj.html

Py:   async def f():⏎    await g()
来源：http://dali.feifeiyinyue.top/Article/details/gtwmljznda.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.jinqigfzy.top/Article/details/gtpkuonbqm.html

JS:   async function f() { await g(); }
来源：http://dali.yuanzhike.top/Article/details/gtskzzypia.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.316326.xyz/Article/details/gtuyxsjsrx.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.guannengcc.top/Article/details/gtmuufltrn.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.yuanzhike.top/Article/details/gtjgscoxwf.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.nwbrower.top/Article/details/gtdmgtmhgk.html

C#:   async Task F() { await G(); }
来源：http://dali.zhengqikj.top/Article/details/gtyrhgqxwt.html

[O05] 并发执行并等待全部完成
来源：http://dali.yuanzhike.top/Article/details/gtcrhkeiru.html

Py:   asyncio.gather(*tasks)
来源：http://dali.dashuyun.cn/Article/details/gtrthvnqvt.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.hnxiangtu.top/Article/details/gtqrvewsbn.html

JS:   await Promise.all(tasks)
来源：http://dali.pengpengdd.cyou/Article/details/gtiocmegjo.html

TS:   await Promise.all(tasks)
来源：http://dali.wangshuangyany.cn/Article/details/gtxvxyazhb.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.jinqigufen.top/Article/details/gtfkgosdcg.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.yangfankeji.com/Article/details/gtajgupeqe.html

Ruby: threads.map(&:join)
来源：http://dali.wangdashe.top/Article/details/gthmvihuob.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.tian-w.cn/Article/details/gtotjrujvd.html

[O06] 使用进程池
来源：http://dali.jqgfzy.top/Article/details/gtsgdvgsnk.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.shuidangran.top/Article/details/gthxzggqva.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.cucudq.cn/Article/details/gtqflptigb.html

JS:   // child_process / cluster 模块
来源：http://dali.pengpengdd.cyou/Article/details/gtlpwmhbxm.html

TS:   // child_process / cluster 模块
来源：http://dali.snrcjt.cn/Article/details/gtjwakqzjq.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.yangfankeji.com/Article/details/gtfkzqwhil.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.yuxming.cn/Article/details/gtqdxieqdm.html

Ruby: // fork 块
来源：http://dali.yvedp.cn/Article/details/gtflvsvkpk.html

C#:   Parallel.For
来源：http://dali.yonumen.top/Article/details/gtyhfazews.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtoeteywei.html

P. 常用工具函数
来源：http://dali.shuidangran.top/Article/details/gtqcrplreg.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtshhtnrii.html

[P01] 生成 UUID
来源：http://dali.yj20258888.top/Article/details/gtfufeabbz.html

Py:   str(uuid.uuid4())
来源：http://dali.cdnleiting.top/Article/details/gtzfhhcarm.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.ydzc1.top/Article/details/gthhftqzdi.html

JS:   crypto.randomUUID()
来源：http://dali.jinqigufen.top/Article/details/gtwcufyagy.html

TS:   crypto.randomUUID()
来源：http://dali.zhoulong.xyz/Article/details/gtqiioxdct.html

Java: UUID.randomUUID().toString()
来源：http://dali.fzhhl.top/Article/details/gthpedtggk.html

Go:   // 用 github.com/google/uuid
来源：http://dali.sxryk.cn/Article/details/gtozjsjjgl.html

Ruby: SecureRandom.uuid
来源：http://dali.zdqjudy.top/Article/details/gtajbyhqvx.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.hywenlv.cn/Article/details/gtudqfuxqw.html

[P02] MD5 / SHA256 摘要
来源：http://dali.ydzc1.top/Article/details/gtolvwgvfz.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.yueranfly.top/Article/details/gtokyzzcwi.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.yj202588.top/Article/details/gtqpvgeudd.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.birdmap.top/Article/details/gtaknhqxdd.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.meibo888.top/Article/details/gtzhcddrre.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.tianlin.xyz/Article/details/gtargaqdvl.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.nwbrower.top/Article/details/gtntkjriig.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.jinqigufen.top/Article/details/gthhlxudco.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.yuxming.cn/Article/details/gtdkceftbt.html

[P03] 生成短随机字符串
来源：http://dali.guowangkeji.top/Article/details/gtadmhuaqo.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhiwuduotai.top/Article/details/gthvnarhwu.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzedekhfs.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.vqdsnc.cn/Article/details/gtdulmowca.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.gaohongyu789.top/Article/details/gtsulhgpeh.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.pycfn.com/Article/details/gtbvrqnmtt.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.cucudq.cn/Article/details/gtasahraoo.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.yonumen.top/Article/details/gtmnlauged.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.redwolf501.top/Article/details/gtlpntrmpz.html

[P04] 求长度
来源：http://dali.hongshengwenyu.top/Article/details/gtopokogpm.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.hammf.cn/Article/details/gtepzltpzt.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yueranfly.top/Article/details/gtmkikxfqu.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yonumen.top/Article/details/gtxkqchxbh.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.cucudq.cn/Article/details/gtylajuueb.html

Java: list.size();  map.size();  s.length()
来源：http://dali.feifeiyinyue.top/Article/details/gtjuxpyizb.html

Go:   len(arr);  len(m)
来源：http://dali.zhiwuduotai.top/Article/details/gtauauaght.html

Ruby: x.length;  x.size
来源：http://dali.zhengqikj.top/Article/details/gtdqviuqna.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.ybcxt.top/Article/details/gtjtvduzql.html

[P05] 判断两个对象内容是否相等
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaqnvdetw.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.feifeiyinyue.top/Article/details/gtbhicybpl.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.yj20258888.top/Article/details/gtxunvtbyb.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.snrcjt.cn/Article/details/gtmbvmyplk.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.andypj.xyz/Article/details/gtefdckmwz.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.cucudq.cn/Article/details/gtdgfjnvdb.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.jiagoushi.top/Article/details/gtrpqvjufc.html

Ruby: a == b
来源：http://dali.svipenyu.cn/Article/details/gtgsnzabdl.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.ehwqpu.com/Article/details/gtofxqfusw.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.hysaishi.cn/Article/details/gtewqelatw.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.jinyuanbaomall.cn/Article/details/gtstriehwj.html

PHP:  if (empty($x)) {}
来源：http://dali.hfpthk.cn/Article/details/gtcdsphrsy.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.yj20258888.top/Article/details/gthipaegfo.html

TS:   if (x == null) {}
来源：http://dali.gaohongyu789.top/Article/details/gttxikhmmv.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.sweek.top/Article/details/gtfagrdohr.html

Go:   if x == nil {}
来源：http://dali.haohaochexian.top/Article/details/gtntfwpyad.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zdqjudy.top/Article/details/gtkfmfvxad.html

C#:   if (x is null) {}
来源：http://dali.quarkkingdee.top/Article/details/gtxdxveowx.html

[P07] 防抖与节流
来源：http://dali.tanke756.top/Article/details/gtlwfnwrnl.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.aibaodan.cn/Article/details/gtbvjyvptd.html

PHP:  // 手写时间戳比较
来源：http://dali.chenlongwang.top/Article/details/gtrmpnfjwt.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jinyuanbaomall.cn/Article/details/gtobektfrc.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdlpaqhzq.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.pycfn.com/Article/details/gtiovkphtx.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.ydzc1.top/Article/details/gtsckhmqfy.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.birdmap.top/Article/details/gtoiprbbjf.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.xuetiantiany.cn/Article/details/gtpxmxlqoh.html

[P08] 处理浮点精度问题
来源：http://dali.havefunace.top/Article/details/gtlmudghpx.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.ehwqpu.com/Article/details/gttrchocex.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.wangdashe.top/Article/details/gtnfhnbpeg.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.yangfankeji.com/Article/details/gtduypftuc.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.jiagoushi.top/Article/details/gtsogatcwn.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.jianghu66.top/Article/details/gtmvfdelwp.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxljvegtq.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgdbddkbo.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.hnxiangtu.top/Article/details/gtmtdespos.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtfltgrdlu.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.yuanzhike.top/Article/details/gtexwgranj.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtcpkewirm.html

[Q01] 创建表
来源：http://dali.jlsjyb.cn/Article/details/gtbubpmnye.html

CREATE TABLE users (
来源：http://dali.jqgfzy.top/Article/details/gthwnrghvd.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.meibo888.top/Article/details/gtxhugqtle.html

name VARCHAR(50) NOT NULL,
来源：http://dali.hongshengwenyu.top/Article/details/gtyrimcwqq.html

email VARCHAR(100) UNIQUE,
来源：http://dali.svipenyu.cn/Article/details/gtbssozsqa.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxstvntqk.html

);
来源：http://dali.birdmap.top/Article/details/gtlvluelwc.html

[Q02] 创建带外键的表
来源：http://dali.jinqigufen.top/Article/details/gtlofmxuje.html

CREATE TABLE orders (
来源：http://dali.jinqigufen.top/Article/details/gtgotdmtkm.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdrhqhstn.html

user_id INT NOT NULL,
来源：http://dali.jinqigufen.top/Article/details/gtfdbswlgi.html

amount DECIMAL(10, 2),
来源：http://dali.xuetiantiany.cn/Article/details/gtbwmteexq.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zycfv.cn/Article/details/gtddmbmprg.html

);
来源：http://dali.daxiang520.top/Article/details/gtdlctelge.html

[Q03] 增加列
来源：http://dali.feifeiyinyue.top/Article/details/gtdayifwax.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.9152youxi.cn/Article/details/gtpayzwlnj.html

[Q04] 修改列类型
来源：http://dali.wangdashe.top/Article/details/gtaadjlvei.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.9152youxi.cn/Article/details/gtcdqnvluw.html

[Q05] 重命名列
来源：http://dali.ydzc1.top/Article/details/gtzesewrwp.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.xylfe.cn/Article/details/gtksbqvnjp.html

[Q06] 删除列
来源：http://dali.ppjwa.cn/Article/details/gtyopueikv.html


<!-- 参考信息 -->