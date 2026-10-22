代发 wailian999

Ruby: exit 1
来源：http://dali.xuanzx.com/Article/details/gtsjsadcfj.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.gotoacloud.top/Article/details/gtnugnwqyp.html

[M06] 向标准错误输出
来源：http://dali.yongpay.top/Article/details/gtxemtjhql.html

Py:   print("err", file=sys.stderr)
来源：http://dali.jinqigufen.top/Article/details/gtdunkcskg.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.cheryme.top/Article/details/gtzfrjdmoa.html

JS:   console.error("err")
来源：http://dali.hongshengwenyu.top/Article/details/gtopamsflb.html

TS:   console.error("err")
来源：http://dali.chenjidiqi.icu/Article/details/gtisubdnui.html

Java: System.err.println("err")
来源：http://dali.tianlin.xyz/Article/details/gtwthvfejt.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzcyipxbq.html

Ruby: warn "err"
来源：http://dali.nwbrower.top/Article/details/gtehlzdgul.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.haohaochexian.top/Article/details/gtsbzxaqaa.html

[M07] 判断是否为主入口
来源：http://dali.hnqzz.top/Article/details/gtlqclifwg.html

Py:   if __name__ == "__main__":
来源：http://dali.hongshengwenyu.top/Article/details/gtboapwmut.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.jinqigfzy.top/Article/details/gtxzfggazq.html

JS:   require.main === module
来源：http://dali.xinyue.icu/Article/details/gtovbxzsex.html

TS:   require.main === module
来源：http://dali.cucudq.cn/Article/details/gtjxeoabtn.html

Java: public static void main(String[] args)
来源：http://dali.havefunace.top/Article/details/gtzepvdgle.html

Go:   func main()
来源：http://dali.jianghu66.top/Article/details/gtesyrebkn.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.daxiang520.top/Article/details/gtcbioysot.html

C#:   static void Main(string[] args)
来源：http://dali.feifeiyinyue.top/Article/details/gtzzjrbgbc.html

[M08] 获取系统与运行时信息
来源：http://dali.wangdashe.top/Article/details/gtxdlyrazw.html

Py:   platform.system();  platform.python_version()
来源：http://dali.snrcjt.cn/Article/details/gtknypmmbw.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.yj202588.top/Article/details/gtarffopef.html

JS:   process.platform;  process.version
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtceaxbmvy.html

TS:   process.platform;  process.version
来源：http://dali.xziqi.cn/Article/details/gthrhebczm.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.haohaochexian.top/Article/details/gtstvrvcon.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.hongshengwenyu.top/Article/details/gtaosbybpu.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.yuanzhike.top/Article/details/gttmzsxlzv.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.haohaochexian.top/Article/details/gtnypghywb.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtnwmjisri.html

N. 数据结构与算法
来源：http://dali.mhx1999.top/Article/details/gtecswvtpj.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtxgftuijf.html

[N01] 二分查找（有序数组）
来源：http://dali.jqgufenzy.top/Article/details/gtenobgpvs.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhiwuduotai.top/Article/details/gtkoxmflgl.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.shanyushiyangtech.top/Article/details/gthioqeiql.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.feifeiyinyue.top/Article/details/gtpdorhohh.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.birdmap.top/Article/details/gtytjwdkwa.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.fengsongda.top/Article/details/gtosquxgra.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.tian-w.cn/Article/details/gtmrpjtbry.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.fengsongda.top/Article/details/gtsfijjvpr.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.hysaishi.cn/Article/details/gtfxraaavi.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.xziqi.cn/Article/details/gtlibpcgxy.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jinqigufen.top/Article/details/gtpctxhxsg.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.9152youxi.cn/Article/details/gtpyerzsyl.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.ybcxt.top/Article/details/gtfngjqwhk.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.hnxiangtu.top/Article/details/gtcftmqzup.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhengqikj.top/Article/details/gtplmmwixf.html

Go:   slices.Sort(arr)
来源：http://dali.yanxiufei.cn/Article/details/gtessbnfdw.html

Ruby: arr.sort
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfflunwoz.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.ivvv.top/Article/details/gtqlbrdpzj.html

[N03] 快速排序（分治示例）
来源：http://dali.yj20258888.top/Article/details/gtpehqqsfq.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.yj202588.top/Article/details/gtwesdguih.html

PHP:  // 递归实现，或用 usort
来源：http://dali.birdmap.top/Article/details/gtmeduuott.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.birdmap.top/Article/details/gtuhhjixqj.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zycfv.cn/Article/details/gtmankvqwz.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.jlsjyb.cn/Article/details/gtfmvfvtan.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.hnxiangtu.top/Article/details/gtfrxgpqxo.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.dianchejie.cn/Article/details/gtdizhzqqz.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhaomingkeji.xyz/Article/details/gtevriytwy.html

[N04] 斐波那契数列
来源：http://dali.yangfankeji.com/Article/details/gtqnxjutdo.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.ydzc1.top/Article/details/gtajarwgei.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.pycfn.com/Article/details/gtmfyoroqn.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.aizwys.cn/Article/details/gtnsldybfq.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.sysykeji.top/Article/details/gtxisbsmkf.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.hnqzz.top/Article/details/gtqvkbcizq.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.hysaishi.cn/Article/details/gtyzrqkvbd.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.ppjwa.cn/Article/details/gtszlikkbq.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.gotoacloud.top/Article/details/gtawifkhlv.html

[N05] 最大公约数
来源：http://dali.xinyue.icu/Article/details/gtprfsfosn.html

Py:   math.gcd(a, b)
来源：http://dali.feifeiyinyue.top/Article/details/gtikrlqkuu.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqkygqrgj.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.birdmap.top/Article/details/gtwjysaago.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaamdkuoj.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.yj202588.top/Article/details/gturtsxqll.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.dianchejie.cn/Article/details/gtujkzdhhw.html

Ruby: a.gcd(b)
来源：http://dali.yuxming.cn/Article/details/gtbvqwcgea.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhiwuduotai.top/Article/details/gtdloxxzuy.html

[N06] 判断回文字符串
来源：http://dali.shangyingyoupin.top/Article/details/gtanwrwivo.html

Py:   s == s[::-1]
来源：http://dali.zhixingplan.top/Article/details/gtwkcrtwco.html

PHP:  $s === strrev($s);
来源：http://dali.cucudq.cn/Article/details/gtjqgayoxz.html

JS:   s === [...s].reverse().join("")
来源：http://dali.sysykeji.top/Article/details/gtlynewbmn.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhiwuduotai.top/Article/details/gtgyzvleqh.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.jinqigfzy.top/Article/details/gtaxsvqepc.html

Go:   // 双指针从两端比较
来源：http://dali.sxryk.cn/Article/details/gtryfxyign.html

Ruby: s == s.reverse
来源：http://dali.zhiwuduotai.top/Article/details/gtwsepxbil.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.sufxvd.cn/Article/details/gtxymjxtpd.html

[N07] 两数之和（返回下标）
来源：http://dali.guowangkeji.top/Article/details/gthglpgrzt.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.snrcjt.cn/Article/details/gtsdbgrsyo.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.nanxinkj.top/Article/details/gtjrlifyqe.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.jianghu66.top/Article/details/gtojpyktct.html

TS:   // 手写 Map<string, number>
来源：http://dali.yj202588.top/Article/details/gtevaldkfm.html

Java: // 手写 HashMap
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzofrshlo.html

Go:   // 手写 map[int]int
来源：http://dali.gaohongyu789.top/Article/details/gtibfdqtwa.html

Ruby: // 手写 Hash
来源：http://dali.zhoulong.xyz/Article/details/gttkfvrdil.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.c1oappe.top/Article/details/gthtffyhnj.html

[N08] 生成全排列
来源：http://dali.jqgufenzy.top/Article/details/gtkmeycpry.html

Py:   itertools.permutations(arr)
来源：http://dali.zhixingplan.top/Article/details/gtfvihzeav.html

PHP:  // 手写递归交换
来源：http://dali.vqdsnc.cn/Article/details/gtyswapyob.html

JS:   // 手写回溯递归
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqceefymv.html

TS:   // 手写回溯递归
来源：http://dali.quarkkingdee.top/Article/details/gtxzislmsa.html

Java: // 手写回溯递归
来源：http://dali.sysykeji.top/Article/details/gtrboazqhl.html

Go:   // 手写回溯递归
来源：http://dali.yj20258.top/Article/details/gtbsqffixq.html

Ruby: arr.permutation.to_a
来源：http://dali.pycfn.com/Article/details/gtdujgztlv.html

C#:   // 手写回溯递归
来源：http://dali.jqgfzy.top/Article/details/gtzrblsizm.html

[N09] 栈与队列
来源：http://dali.jqgfzy.top/Article/details/gtrfxxtggl.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.dashuyun.cn/Article/details/gttseqyopt.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.jlsjyb.cn/Article/details/gtqkurubwp.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.haohaochexian.top/Article/details/gtsutzuugj.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.gogol.net.cn/Article/details/gtbngjmout.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.shanyushiyangkeji.top/Article/details/gtezwvqpcq.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.yvedp.cn/Article/details/gtwiwadruj.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.vqdsnc.cn/Article/details/gtdbbzcxjq.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.yuxming.cn/Article/details/gtqtnubfad.html

[N10] 链表节点定义
来源：http://dali.ppjwa.cn/Article/details/gtwblqjhkm.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.guannengcc.top/Article/details/gtbkbymgsz.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.vqdsnc.cn/Article/details/gteybpxyii.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.tian-w.cn/Article/details/gtmvjxkgiv.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.redwolf501.top/Article/details/gtqjbbruuy.html

Java: class Node { int v; Node next; }
来源：http://dali.zhengqikj.top/Article/details/gtvpysojfv.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.yonumen.top/Article/details/gtllhsxdpn.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.jinghuilouyu.cn/Article/details/gtiovcvybq.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.nanxuanxn.top/Article/details/gtnbvtssqo.html

[N11] 二叉树中序遍历
来源：http://dali.cucudq.cn/Article/details/gthlqueqnp.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.jinghuilouyu.cn/Article/details/gtjwlzbiwv.html

PHP:  // 手写递归函数
来源：http://dali.hongshengwenyu.top/Article/details/gtitxezryb.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jqgufenzy.top/Article/details/gtggcgofxx.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yuanzhike.top/Article/details/gtbpdhspyt.html

Java: // 手写递归
来源：http://dali.jqgufenzy.top/Article/details/gtmuhqgtvn.html

Go:   // 手写递归
来源：http://dali.guannengcc.top/Article/details/gtyxxlgvyg.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.pycfn.com/Article/details/gtvbxrkmcj.html

C#:   // 手写递归
来源：http://dali.hfpthk.cn/Article/details/gtgorlfvlt.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.yangfankeji.com/Article/details/gtzzwcahos.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.aizwys.cn/Article/details/gtnokwczpu.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.jqgfzy.top/Article/details/gtscxhsizp.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.haohaochexian.top/Article/details/gtfxkpwptw.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjllfnyqm.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jianghu66.top/Article/details/gtotstrsky.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.yvedp.cn/Article/details/gtwypcwvzc.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.cashguo.top/Article/details/gtmfyoxjpe.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.gzhubu.top/Article/details/gtqcxbypps.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtnkpuackt.html

O. 并发与异步
来源：http://dali.yongpay.top/Article/details/gtjamwebki.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtpgezsene.html

[O01] 启动一个线程
来源：http://dali.sysykeji.top/Article/details/gtthqhehej.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.9152youxi.cn/Article/details/gtvelyxvhi.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhongyouzk.top/Article/details/gtbhxfcips.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhaomingkeji.xyz/Article/details/gttvxrzbjr.html

TS:   // 同 JS
来源：http://dali.yj202588.top/Article/details/gtaqxisuyg.html

Java: new Thread(() -> f()).start()
来源：http://dali.hnxiangtu.top/Article/details/gtmqxjhmoy.html

Go:   go f()
来源：http://dali.redwolf501.top/Article/details/gtojkzsdhw.html

Ruby: Thread.new { f }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrxkxbrsv.html

C#:   Task.Run(() => F());
来源：http://dali.shanyushiyangtech.top/Article/details/gtvjkxcauj.html

[O02] 使用线程池
来源：http://dali.jyoumei.cn/Article/details/gtrjmggdaj.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.shzxlz.cn/Article/details/gtpjhbyjms.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.birdmap.top/Article/details/gtbtvofaxn.html

JS:   // worker_threads 线程池
来源：http://dali.haohaochexian.top/Article/details/gtkwzfnzbq.html

TS:   // worker_threads 线程池
来源：http://dali.smart0.xyz/Article/details/gtmdmkkqah.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbuizuncm.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.yuanzhike.top/Article/details/gtfzzmerdn.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.xinyue.icu/Article/details/gtrzjubfsp.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.ydzc1.top/Article/details/gtdijpwoeq.html

[O03] 加锁保护共享数据
来源：http://dali.guowangkeji.top/Article/details/gtswqxbfxz.html

Py:   with lock: shared += 1
来源：http://dali.svipenyu.cn/Article/details/gtocipefgr.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zdqjudy.top/Article/details/gtrwkhcxnf.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.cheryme.top/Article/details/gtjtepgbeq.html

TS:   // 同 JS
来源：http://dali.hfpthk.cn/Article/details/gttuptdgxl.html

Java: synchronized (this) { shared++; }
来源：http://dali.xinyue.icu/Article/details/gtnsffzuwz.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.hywenlv.cn/Article/details/gtdmkrxpvk.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.cdnleiting.top/Article/details/gtgvirnroa.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhiwuduotai.top/Article/details/gtlslutbgn.html

[O04] 定义异步函数并等待
来源：http://dali.cdnleiting.top/Article/details/gtdbbhacbp.html

Py:   async def f():⏎    await g()
来源：http://dali.zycfv.cn/Article/details/gtykzytmsa.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.c1oappe.top/Article/details/gtwfdjfgrs.html

JS:   async function f() { await g(); }
来源：http://dali.birdmap.top/Article/details/gtnzighscw.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.316326.xyz/Article/details/gtrhtsmuxb.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.fengsongda.top/Article/details/gthbmuvhjp.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.hfpthk.cn/Article/details/gtelizmvqk.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.shanyushiyangtech.top/Article/details/gtuoqczbwn.html

C#:   async Task F() { await G(); }
来源：http://dali.gogol.net.cn/Article/details/gtahcouumn.html

[O05] 并发执行并等待全部完成
来源：http://dali.cucudq.cn/Article/details/gthtgayqtb.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhengqikj.top/Article/details/gtakrckgml.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.yanxiufei.cn/Article/details/gtkwntserp.html

JS:   await Promise.all(tasks)
来源：http://dali.yj202588.top/Article/details/gtrinvltws.html

TS:   await Promise.all(tasks)
来源：http://dali.gotoacloud.top/Article/details/gtvgmktwij.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.yangfankeji.com/Article/details/gtybbmuokj.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.tianlin.xyz/Article/details/gtjlnuazxu.html

Ruby: threads.map(&:join)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtavypfyiz.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.chenlongwang.top/Article/details/gtqtkslzze.html

[O06] 使用进程池
来源：http://dali.jinqigfzy.top/Article/details/gthcxipbpn.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.cheryme.top/Article/details/gtplupenan.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.yvedp.cn/Article/details/gttvzqidwg.html

JS:   // child_process / cluster 模块
来源：http://dali.iojbl.cn/Article/details/gtqdhrcdpg.html

TS:   // child_process / cluster 模块
来源：http://dali.xylfe.cn/Article/details/gtzdfurohx.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.quarkkingdee.top/Article/details/gtpblfhpdj.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.jinqigufen.top/Article/details/gtptihcmuv.html

Ruby: // fork 块
来源：http://dali.shanyushiyangtech.top/Article/details/gtvqqadraa.html

C#:   Parallel.For
来源：http://dali.cucudq.cn/Article/details/gtsbcffamt.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtzjaswwek.html

P. 常用工具函数
来源：http://dali.xuetiantiany.cn/Article/details/gtgvmjhdmw.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtryxxzzcc.html

[P01] 生成 UUID
来源：http://dali.gzhubu.top/Article/details/gtajmduwkm.html

Py:   str(uuid.uuid4())
来源：http://dali.quarkkingdee.top/Article/details/gtqwpyzmsa.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.chenzaomai.com/Article/details/gtsqvlquwu.html

JS:   crypto.randomUUID()
来源：http://dali.sxryk.cn/Article/details/gtjyjasokk.html

TS:   crypto.randomUUID()
来源：http://dali.yj202588.top/Article/details/gtvhenhcpr.html

Java: UUID.randomUUID().toString()
来源：http://dali.chenzaomai.com/Article/details/gttjkjqfoc.html

Go:   // 用 github.com/google/uuid
来源：http://dali.nanxuanxn.top/Article/details/gtmofpxgnw.html

Ruby: SecureRandom.uuid
来源：http://dali.zhoulong.xyz/Article/details/gtnlgawpoq.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.gogol.net.cn/Article/details/gtgpqiqpyb.html

[P02] MD5 / SHA256 摘要
来源：http://dali.yuanzhike.top/Article/details/gtallzfjtj.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.tian-w.cn/Article/details/gtyrhacfyy.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.yongpay.top/Article/details/gttmgvexyi.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.ivvv.top/Article/details/gtyqydufrp.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.ydzc1.top/Article/details/gtuwxdwhll.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.316326.xyz/Article/details/gtoskwxajk.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.9152youxi.cn/Article/details/gtbzhvluic.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.birdmap.top/Article/details/gtispewebh.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlsjruvtj.html

[P03] 生成短随机字符串
来源：http://dali.jiagoushi.top/Article/details/gthwdnfhwo.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.nanxinkj.top/Article/details/gtmohrbdkg.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.ywan-chungtsiang.top/Article/details/gthmpwoaxj.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.gzhubu.top/Article/details/gtgwpmaqmj.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.aibaodan.cn/Article/details/gtvoaeqnrl.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.pengpengdd.cyou/Article/details/gttuzwpzlp.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.cashguo.top/Article/details/gtfnhyyzuh.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.sufxvd.cn/Article/details/gtuvktsisl.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.shanyushiyangtech.top/Article/details/gtwajdidxr.html

[P04] 求长度
来源：http://dali.tian-w.cn/Article/details/gthpcbhuba.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.andypj.xyz/Article/details/gtziqkymjl.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.dashuyun.cn/Article/details/gtzvtwmnqi.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.kuanghao11.cn/Article/details/gtjckvtrye.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jqgfzy.top/Article/details/gtruiorddr.html

Java: list.size();  map.size();  s.length()
来源：http://dali.dianchejie.cn/Article/details/gtrvqiuipp.html

Go:   len(arr);  len(m)
来源：http://dali.dianchejie.cn/Article/details/gtnnuvyisl.html

Ruby: x.length;  x.size
来源：http://dali.guowangkeji.top/Article/details/gtzkozpbfg.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.yangfankeji.com/Article/details/gtsqzvuajh.html

[P05] 判断两个对象内容是否相等
来源：http://dali.xinyue.icu/Article/details/gtdrmnjvgr.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.quarkkingdee.top/Article/details/gtbroyvcha.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.gaohongyu789.top/Article/details/gtcthfzfwf.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.redwolf501.top/Article/details/gtouwhiots.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.pycfn.com/Article/details/gtljjyvcwy.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.ybcxt.top/Article/details/gtsaslhzzk.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.snrcjt.cn/Article/details/gttpfwmwyo.html

Ruby: a == b
来源：http://dali.yj20258888.top/Article/details/gtompamyoy.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.quarkkingdee.top/Article/details/gtcpejtino.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.yuxming.cn/Article/details/gthhhotwjw.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.hammf.cn/Article/details/gtoijlokut.html

PHP:  if (empty($x)) {}
来源：http://dali.ehwqpu.com/Article/details/gtcehyjlcy.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.jinqigfzy.top/Article/details/gthyuynhuf.html

TS:   if (x == null) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdympdlbi.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.aizwys.cn/Article/details/gtiyexcscf.html

Go:   if x == nil {}
来源：http://dali.zycfv.cn/Article/details/gtzbvogtry.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.hywenlv.cn/Article/details/gtysbyyqjv.html

C#:   if (x is null) {}
来源：http://dali.xziqi.cn/Article/details/gtyncgjmda.html

[P07] 防抖与节流
来源：http://dali.tanke756.top/Article/details/gttxryvlvo.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.ydzc1.top/Article/details/gtbckkxfyw.html

PHP:  // 手写时间戳比较
来源：http://dali.feifeiyinyue.top/Article/details/gtytzxjeze.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yj20258888.top/Article/details/gtjdfnmyhq.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.pengpengdd.cyou/Article/details/gtyzyofmak.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.shzxlz.cn/Article/details/gtsiicwwbv.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.cdnleiting.top/Article/details/gtvukwdbjt.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.chenlongwang.top/Article/details/gtnnlyicst.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.svipenyu.cn/Article/details/gtefieebox.html

[P08] 处理浮点精度问题
来源：http://dali.yj202588.top/Article/details/gtaknzjhvc.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.wangshuangyany.cn/Article/details/gtfjuebsiy.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.redwolf501.top/Article/details/gtjrgakrud.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.yonumen.top/Article/details/gtqmkvrxhs.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.hfpthk.cn/Article/details/gtablkqoiz.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.daria6918.cn/Article/details/gtjrifbjee.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.dianchejie.cn/Article/details/gtwmfgfwob.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.jianghu66.top/Article/details/gtumvjafop.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.chenlongwang.top/Article/details/gtmtpxmskw.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtnclqqljh.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.ydzc1.top/Article/details/gtcznzisng.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtgdnikvrg.html

[Q01] 创建表
来源：http://dali.jinqigufen.top/Article/details/gtekcutziy.html

CREATE TABLE users (
来源：http://dali.smart0.xyz/Article/details/gtfwhrpdqx.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jqgfzy.top/Article/details/gtzbloaflh.html

name VARCHAR(50) NOT NULL,
来源：http://dali.nanxuanxn.top/Article/details/gtikcniwkx.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhixingplan.top/Article/details/gtaarbwmal.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.hfpthk.cn/Article/details/gtaqrlokjq.html

);
来源：http://dali.jinghuilouyu.cn/Article/details/gtatmmhxws.html

[Q02] 创建带外键的表
来源：http://dali.xylfe.cn/Article/details/gtkqyoyqkg.html

CREATE TABLE orders (
来源：http://dali.sufxvd.cn/Article/details/gthjdqzmaz.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.fzhhl.top/Article/details/gtuuuzjygd.html

user_id INT NOT NULL,
来源：http://dali.cqqwz.cn/Article/details/gtpcwwefbp.html

amount DECIMAL(10, 2),
来源：http://dali.daxiang520.top/Article/details/gtsytktaag.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.tanke756.top/Article/details/gtuzdpoyys.html

);
来源：http://dali.havefunace.top/Article/details/gturrqiond.html

[Q03] 增加列
来源：http://dali.zhongyouzk.top/Article/details/gtlgcjnbpt.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhixingplan.top/Article/details/gtfemxaerv.html

[Q04] 修改列类型
来源：http://dali.bjfxy.top/Article/details/gtprrsadzq.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.hywenlv.cn/Article/details/gtqcrwwojv.html

[Q05] 重命名列
来源：http://dali.wangshuangyany.cn/Article/details/gtcwlfgsre.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.xuanzx.com/Article/details/gttkrjpeki.html

[Q06] 删除列
来源：http://dali.zhengqikj.top/Article/details/gtwzwcqyqe.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.dianchejie.cn/Article/details/gtsbglddio.html

[Q07] 删除表
来源：http://dali.9152youxi.cn/Article/details/gtaimhtqcq.html

DROP TABLE IF EXISTS orders;
来源：http://dali.cqqwz.cn/Article/details/gtbvxjjklz.html

[Q08] 创建普通索引
来源：http://dali.shanyushiyangtech.top/Article/details/gtxbuwqdyf.html


<!-- 参考信息 -->