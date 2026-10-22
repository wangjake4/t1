代发 wailian999

JS:   process.exit(1)
来源：http://dali.ehwqpu.com/Article/details/gtpvdrfczo.html

TS:   process.exit(1)
来源：http://dali.xziqi.cn/Article/details/gtpjwomxwe.html

Java: System.exit(1)
来源：http://dali.yanxiufei.cn/Article/details/gtvsltefwj.html

Go:   os.Exit(1)
来源：http://dali.redwolf501.top/Article/details/gtrfigewii.html

Ruby: exit 1
来源：http://dali.shanyushiyangkeji.top/Article/details/gtebvcfpcj.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.ybcxt.top/Article/details/gtlwsoymfm.html

[M06] 向标准错误输出
来源：http://dali.xuanzx.com/Article/details/gtupuuquwv.html

Py:   print("err", file=sys.stderr)
来源：http://dali.ybcxt.top/Article/details/gtihzpdnew.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.sweek.top/Article/details/gttpcqfevy.html

JS:   console.error("err")
来源：http://dali.nanxuanxn.top/Article/details/gtbkqcixhd.html

TS:   console.error("err")
来源：http://dali.jlsjyb.cn/Article/details/gtflcqxkoc.html

Java: System.err.println("err")
来源：http://dali.daria6918.cn/Article/details/gtmldlsbhl.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.yanxiufei.cn/Article/details/gtfezhcloh.html

Ruby: warn "err"
来源：http://dali.chenjidiqi.icu/Article/details/gtwgsfetui.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.hysaishi.cn/Article/details/gtfthcdiyj.html

[M07] 判断是否为主入口
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcjwlrgwg.html

Py:   if __name__ == "__main__":
来源：http://dali.dianchejie.cn/Article/details/gtnyrpohvn.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.pycfn.com/Article/details/gtvljvxoml.html

JS:   require.main === module
来源：http://dali.smart0.xyz/Article/details/gtkwkodpik.html

TS:   require.main === module
来源：http://dali.xziqi.cn/Article/details/gtrfdrjjvv.html

Java: public static void main(String[] args)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxhosbyhv.html

Go:   func main()
来源：http://dali.yangfankeji.com/Article/details/gtxucznttl.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.sysykeji.top/Article/details/gtlcvvztzr.html

C#:   static void Main(string[] args)
来源：http://dali.zhoulong.xyz/Article/details/gthcmzdeof.html

[M08] 获取系统与运行时信息
来源：http://dali.gzhubu.top/Article/details/gtbtywgyjr.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhoulong.xyz/Article/details/gtffzazkuv.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.shanyushiyangtech.top/Article/details/gtvxavpfcc.html

JS:   process.platform;  process.version
来源：http://dali.hammf.cn/Article/details/gtgbfrsrwg.html

TS:   process.platform;  process.version
来源：http://dali.zhongyouzk.top/Article/details/gtdeubkbjt.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.hnqzz.top/Article/details/gtzfqqncea.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.aibaodan.cn/Article/details/gtqdnhmgap.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.dashuyun.cn/Article/details/gtwunztcvb.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.sxryk.cn/Article/details/gtoqikaavo.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gteofbypnq.html

N. 数据结构与算法
来源：http://dali.zhaomingkeji.xyz/Article/details/gthmaoxgwc.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtlmbebxfn.html

[N01] 二分查找（有序数组）
来源：http://dali.pycfn.com/Article/details/gtgtupmkfo.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.jiagoushi.top/Article/details/gtngnukhjk.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.shuidangran.top/Article/details/gtilgzgzfa.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhixingplan.top/Article/details/gthfpadieh.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.fzhhl.top/Article/details/gtthigomux.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.jiagoushi.top/Article/details/gtmxfljlrx.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.shangyingyoupin.top/Article/details/gtgohbcoya.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.jiagoushi.top/Article/details/gtqyysulxy.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.jinghuilouyu.cn/Article/details/gtyygozxeg.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.kuanghao11.cn/Article/details/gtfllmknfo.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.bjfxy.top/Article/details/gtbdovspnn.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.feifeiyinyue.top/Article/details/gtvvuxjnbi.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yvedp.cn/Article/details/gtjkbsdxtw.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.fengsongda.top/Article/details/gtmwgefhsr.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.jqgfzy.top/Article/details/gtpmglfafw.html

Go:   slices.Sort(arr)
来源：http://dali.bjfxy.top/Article/details/gtfmpthjjq.html

Ruby: arr.sort
来源：http://dali.daria6918.cn/Article/details/gttkmytgji.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.tanke756.top/Article/details/gtcztuicox.html

[N03] 快速排序（分治示例）
来源：http://dali.meibo888.top/Article/details/gtfbsqtkzc.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.redwolf501.top/Article/details/gtijdlrhhs.html

PHP:  // 递归实现，或用 usort
来源：http://dali.9152youxi.cn/Article/details/gtaycsucya.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.xinyue.icu/Article/details/gtvbzuyvwo.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jyoumei.cn/Article/details/gtomjifwge.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.smart0.xyz/Article/details/gthexpacnv.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.yvedp.cn/Article/details/gtacmjewed.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.daxiang520.top/Article/details/gtofpqmvpi.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.jqgufenzy.top/Article/details/gtsvkoibhs.html

[N04] 斐波那契数列
来源：http://dali.yj20258888.top/Article/details/gtkcajkjun.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.0kj1m.cn/Article/details/gtbbkcnevm.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.hywenlv.cn/Article/details/gtdcsqsahs.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.dashuyun.cn/Article/details/gtvgpbrvjj.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.shanyushiyangtech.top/Article/details/gtlnczhvkl.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhoulong.xyz/Article/details/gtoekirbpy.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.fzhhl.top/Article/details/gtswjnfpdo.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.gogol.net.cn/Article/details/gtogfyybiq.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.mhx1999.top/Article/details/gtpypighfw.html

[N05] 最大公约数
来源：http://dali.bjfxy.top/Article/details/gtzaadrnxk.html

Py:   math.gcd(a, b)
来源：http://dali.yj20258888.top/Article/details/gthcnhbzyk.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvrtsinhb.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jinqigufen.top/Article/details/gtoceetyrg.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.cqqwz.cn/Article/details/gtvkfwjryu.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.yuanzhike.top/Article/details/gtazeeqlyj.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.shuidangran.top/Article/details/gtpxarxsms.html

Ruby: a.gcd(b)
来源：http://dali.tanke756.top/Article/details/gttttvxpgu.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.hammf.cn/Article/details/gtpzwhczvn.html

[N06] 判断回文字符串
来源：http://dali.guannengcc.top/Article/details/gtohbrqgkp.html

Py:   s == s[::-1]
来源：http://dali.tian-w.cn/Article/details/gtwxfyvmhf.html

PHP:  $s === strrev($s);
来源：http://dali.cucudq.cn/Article/details/gthvnyoicx.html

JS:   s === [...s].reverse().join("")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpukiyoar.html

TS:   s === [...s].reverse().join("")
来源：http://dali.daria6918.cn/Article/details/gtigohompg.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.gogol.net.cn/Article/details/gtwhuymfsz.html

Go:   // 双指针从两端比较
来源：http://dali.daria6918.cn/Article/details/gtxstfvxjz.html

Ruby: s == s.reverse
来源：http://dali.iojbl.cn/Article/details/gtvvlfanng.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.shanyushiyangkeji.top/Article/details/gthmsojbal.html

[N07] 两数之和（返回下标）
来源：http://dali.havefunace.top/Article/details/gtvrxopkgj.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.cucudq.cn/Article/details/gtwjxyylqo.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.gaohongyu789.top/Article/details/gtawyudtxl.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.dashuyun.cn/Article/details/gtpgcbxdga.html

TS:   // 手写 Map<string, number>
来源：http://dali.jinqigufen.top/Article/details/gtjmrclkav.html

Java: // 手写 HashMap
来源：http://dali.xuetiantiany.cn/Article/details/gtcekxrtie.html

Go:   // 手写 map[int]int
来源：http://dali.zhixingplan.top/Article/details/gtbpudqmvl.html

Ruby: // 手写 Hash
来源：http://dali.gogol.net.cn/Article/details/gterofcqre.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhaomingkeji.xyz/Article/details/gttsvlikje.html

[N08] 生成全排列
来源：http://dali.redwolf501.top/Article/details/gtagyqixhw.html

Py:   itertools.permutations(arr)
来源：http://dali.haohaochexian.top/Article/details/gtaledbfbm.html

PHP:  // 手写递归交换
来源：http://dali.andypj.xyz/Article/details/gtjxsisdwz.html

JS:   // 手写回溯递归
来源：http://dali.jyoumei.cn/Article/details/gtpgyczjst.html

TS:   // 手写回溯递归
来源：http://dali.nanxuanxn.top/Article/details/gtcmkwfwbo.html

Java: // 手写回溯递归
来源：http://dali.shuidangran.top/Article/details/gtydmwkaqm.html

Go:   // 手写回溯递归
来源：http://dali.gogol.net.cn/Article/details/gtpibvztke.html

Ruby: arr.permutation.to_a
来源：http://dali.yueranfly.top/Article/details/gtfjvxoeqt.html

C#:   // 手写回溯递归
来源：http://dali.cdnleiting.top/Article/details/gtzogsdblm.html

[N09] 栈与队列
来源：http://dali.tian-w.cn/Article/details/gttbnmdxrq.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.jlsjyb.cn/Article/details/gthotltqcu.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.haohaochexian.top/Article/details/gtfukxosps.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.shuidangran.top/Article/details/gtpfalciti.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.pengpengdd.cyou/Article/details/gtpsvhzaxi.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.jinghuilouyu.cn/Article/details/gtyysttuzb.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.wangshuangyany.cn/Article/details/gtryfjbzus.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.ehwqpu.com/Article/details/gtqlvklrom.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.quarkkingdee.top/Article/details/gtprgnksaa.html

[N10] 链表节点定义
来源：http://dali.ivvv.top/Article/details/gtoqebxqui.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.birdmap.top/Article/details/gtetltsthu.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.yuxming.cn/Article/details/gttecmscaq.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.cqqwz.cn/Article/details/gtqifxtrtu.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.yonumen.top/Article/details/gtteaeqpvn.html

Java: class Node { int v; Node next; }
来源：http://dali.hammf.cn/Article/details/gthqjjdhcb.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.wangshuangyany.cn/Article/details/gtkoecomqi.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzdtbqjhf.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.feifeiyinyue.top/Article/details/gtvlmjseys.html

[N11] 二叉树中序遍历
来源：http://dali.gogol.net.cn/Article/details/gtackmbmcu.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.jinghuilouyu.cn/Article/details/gtpobrjojx.html

PHP:  // 手写递归函数
来源：http://dali.zhoulong.xyz/Article/details/gtfxrdujew.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.snrcjt.cn/Article/details/gttdclfedz.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.hywenlv.cn/Article/details/gttuxyldev.html

Java: // 手写递归
来源：http://dali.hywenlv.cn/Article/details/gtrihebusq.html

Go:   // 手写递归
来源：http://dali.zdqjudy.top/Article/details/gttzbwpcib.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.birdmap.top/Article/details/gthwibvkao.html

C#:   // 手写递归
来源：http://dali.shuidangran.top/Article/details/gtrrxrjnku.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.tianlin.xyz/Article/details/gteltrqfcc.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.gaohongyu789.top/Article/details/gtdulquezw.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.yuanzhike.top/Article/details/gtemfkmabo.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.9152youxi.cn/Article/details/gtpukavhqn.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.svipenyu.cn/Article/details/gtrtsbeeyt.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.gzhubu.top/Article/details/gtztlydfrz.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.cdnleiting.top/Article/details/gtfejacfkh.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.wangdashe.top/Article/details/gtkasdbkpu.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.sxryk.cn/Article/details/gtxdjhalsg.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtbaehxirg.html

O. 并发与异步
来源：http://dali.sxryk.cn/Article/details/gtmrxnjlgl.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtcmesnjqh.html

[O01] 启动一个线程
来源：http://dali.ehwqpu.com/Article/details/gtmrmjtxvd.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.fengsongda.top/Article/details/gtyzesqpxk.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzckxfnzi.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.yongpay.top/Article/details/gtdzojjgvj.html

TS:   // 同 JS
来源：http://dali.yuanzhike.top/Article/details/gthvnguglj.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhengqikj.top/Article/details/gtpytnkspc.html

Go:   go f()
来源：http://dali.316326.xyz/Article/details/gtgovillnw.html

Ruby: Thread.new { f }
来源：http://dali.chenlongwang.top/Article/details/gthcfmrzwp.html

C#:   Task.Run(() => F());
来源：http://dali.tianlin.xyz/Article/details/gtudaxwakd.html

[O02] 使用线程池
来源：http://dali.yangfankeji.com/Article/details/gtgvdeipnl.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhongyouzk.top/Article/details/gtgjmidddc.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.hongshengwenyu.top/Article/details/gtpspzxdxr.html

JS:   // worker_threads 线程池
来源：http://dali.birdmap.top/Article/details/gtfienlqzi.html

TS:   // worker_threads 线程池
来源：http://dali.jinyuanbaomall.cn/Article/details/gtonqibfol.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.chenjidiqi.icu/Article/details/gtqmiffnva.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.hfpthk.cn/Article/details/gtaavtsgwr.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zdqjudy.top/Article/details/gtcfskojps.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhengqikj.top/Article/details/gteppbawez.html

[O03] 加锁保护共享数据
来源：http://dali.tianlin.xyz/Article/details/gtunfcfvqz.html

Py:   with lock: shared += 1
来源：http://dali.jyoumei.cn/Article/details/gtqxmjnsxx.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.bjfxy.top/Article/details/gtkbmdaqvp.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.daxiang520.top/Article/details/gtywmwpysw.html

TS:   // 同 JS
来源：http://dali.wangdashe.top/Article/details/gthvuikxfk.html

Java: synchronized (this) { shared++; }
来源：http://dali.cqqwz.cn/Article/details/gtbtzznjvp.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.jqgfzy.top/Article/details/gtuvlqpjsb.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.xinyue.icu/Article/details/gtnjktzqaq.html

C#:   lock (gate) { shared++; }
来源：http://dali.cashguo.top/Article/details/gtogaxgfvt.html

[O04] 定义异步函数并等待
来源：http://dali.xziqi.cn/Article/details/gtdsaslgal.html

Py:   async def f():⏎    await g()
来源：http://dali.mhx1999.top/Article/details/gtjtailyhy.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.chenzaomai.com/Article/details/gtxomldogn.html

JS:   async function f() { await g(); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtoilrhimd.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.yvedp.cn/Article/details/gtrhbkxaza.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.9152youxi.cn/Article/details/gtoxicokwg.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gthghlxpoa.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.hysaishi.cn/Article/details/gtcagyzwtv.html

C#:   async Task F() { await G(); }
来源：http://dali.fzhhl.top/Article/details/gtzfdyjixa.html

[O05] 并发执行并等待全部完成
来源：http://dali.shanyushiyangtech.top/Article/details/gtbdzvymid.html

Py:   asyncio.gather(*tasks)
来源：http://dali.aibaodan.cn/Article/details/gthymaclyr.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhoulong.xyz/Article/details/gtceyqdvjd.html

JS:   await Promise.all(tasks)
来源：http://dali.feifeiyinyue.top/Article/details/gtxadcpdzq.html

TS:   await Promise.all(tasks)
来源：http://dali.zhengqikj.top/Article/details/gtusojwxgd.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtazgtxhzr.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.tanke756.top/Article/details/gtclegwrxf.html

Ruby: threads.map(&:join)
来源：http://dali.aibaodan.cn/Article/details/gtilydyolw.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.ivvv.top/Article/details/gtgqkdbrqr.html

[O06] 使用进程池
来源：http://dali.chenlongwang.top/Article/details/gtfaxxhikz.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.havefunace.top/Article/details/gtcwrnkqne.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.yueranfly.top/Article/details/gtjxdbivya.html

JS:   // child_process / cluster 模块
来源：http://dali.jqgufenzy.top/Article/details/gtexhwsrqa.html

TS:   // child_process / cluster 模块
来源：http://dali.shuidangran.top/Article/details/gtnvkrovqn.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.shzxlz.cn/Article/details/gtmmjbwqeg.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.cheryme.top/Article/details/gtglpafbzd.html

Ruby: // fork 块
来源：http://dali.sweek.top/Article/details/gtnqgtpwkl.html

C#:   Parallel.For
来源：http://dali.dianchejie.cn/Article/details/gtlpnibhgb.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtgxkferkt.html

P. 常用工具函数
来源：http://dali.yj20258.top/Article/details/gtjgthyyuh.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtkhvskjhb.html

[P01] 生成 UUID
来源：http://dali.hammf.cn/Article/details/gtxylpzcnf.html

Py:   str(uuid.uuid4())
来源：http://dali.nwbrower.top/Article/details/gtxsdwarpk.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.hnqzz.top/Article/details/gtkykwcutj.html

JS:   crypto.randomUUID()
来源：http://dali.jyoumei.cn/Article/details/gtkzojlwvn.html

TS:   crypto.randomUUID()
来源：http://dali.feifeiyinyue.top/Article/details/gtumxntpno.html

Java: UUID.randomUUID().toString()
来源：http://dali.xylfe.cn/Article/details/gtkveytuul.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhongyouzk.top/Article/details/gtuqljlvqn.html

Ruby: SecureRandom.uuid
来源：http://dali.guannengcc.top/Article/details/gtvclaoxyv.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.bjfxy.top/Article/details/gtobzkbfmt.html

[P02] MD5 / SHA256 摘要
来源：http://dali.tian-w.cn/Article/details/gtdgmeoiyc.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.yanxiufei.cn/Article/details/gtgickopcs.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.ppjwa.cn/Article/details/gtlxqnetgq.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.quarkkingdee.top/Article/details/gtflgxmrvx.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.hysaishi.cn/Article/details/gtyefooclt.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.yj20258888.top/Article/details/gtoknwonzl.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.sxryk.cn/Article/details/gtteqsmecc.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.chenlongwang.top/Article/details/gtckubjusv.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.ivvv.top/Article/details/gtienxiwnt.html

[P03] 生成短随机字符串
来源：http://dali.cashguo.top/Article/details/gtzvsdlmpj.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.cucudq.cn/Article/details/gtaukyzyur.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.fengsongda.top/Article/details/gtcctphrda.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.redwolf501.top/Article/details/gtriqppevi.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhiwuduotai.top/Article/details/gtwxrcjqhi.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zdqjudy.top/Article/details/gtnedthxcv.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.hnqzz.top/Article/details/gtpcicdjhs.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.yongpay.top/Article/details/gtaoypmtbe.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.kuanghao11.cn/Article/details/gtdrqfzomp.html

[P04] 求长度
来源：http://dali.mhx1999.top/Article/details/gtzicvmzqv.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnvdyjish.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgjxngqvk.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.sxryk.cn/Article/details/gtuinptffm.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnreoqvcj.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhixingplan.top/Article/details/gtsyfaepgp.html

Go:   len(arr);  len(m)
来源：http://dali.cqqwz.cn/Article/details/gteniebyyc.html

Ruby: x.length;  x.size
来源：http://dali.gotoacloud.top/Article/details/gtdidlagbw.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.svipenyu.cn/Article/details/gtzvcephqw.html

[P05] 判断两个对象内容是否相等
来源：http://dali.sysykeji.top/Article/details/gtdibjxibf.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhiwuduotai.top/Article/details/gtxjjcphrr.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.cqqwz.cn/Article/details/gtrqnatrjm.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.fengsongda.top/Article/details/gtwjohunrv.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.0kj1m.cn/Article/details/gthadmydyt.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.yj202588.top/Article/details/gteddnnlaf.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkamzunby.html

Ruby: a == b
来源：http://dali.xinyue.icu/Article/details/gtutdfmznq.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhengqikj.top/Article/details/gtoucpthnq.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.nanxuanxn.top/Article/details/gtimnwnznj.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhoulong.xyz/Article/details/gtzzhduycl.html

PHP:  if (empty($x)) {}
来源：http://dali.gaohongyu789.top/Article/details/gtoluvjjkh.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.bjfxy.top/Article/details/gtapnucdlo.html

TS:   if (x == null) {}
来源：http://dali.zhengqikj.top/Article/details/gtwaicalrd.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.daria6918.cn/Article/details/gtreoywwow.html

Go:   if x == nil {}
来源：http://dali.tanke756.top/Article/details/gtlvmtuyrp.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.ehwqpu.com/Article/details/gtigzxolox.html

C#:   if (x is null) {}
来源：http://dali.haohaochexian.top/Article/details/gtbemikegq.html

[P07] 防抖与节流
来源：http://dali.tianlin.xyz/Article/details/gtsqmcufrz.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.hammf.cn/Article/details/gtoyjmzote.html

PHP:  // 手写时间戳比较
来源：http://dali.jianghu66.top/Article/details/gtqtzgappu.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hfpthk.cn/Article/details/gtkqrlvrgr.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.iojbl.cn/Article/details/gteeaerpiu.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.cqqwz.cn/Article/details/gtzflgxvoz.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.tanke756.top/Article/details/gthkhqclqo.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.yangfankeji.com/Article/details/gtxxgydalt.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.sweek.top/Article/details/gtqdtiuqym.html

[P08] 处理浮点精度问题
来源：http://dali.hammf.cn/Article/details/gtbkyxdzwt.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.sxryk.cn/Article/details/gtbdwxdndh.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.smart0.xyz/Article/details/gtvdcrroxj.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.sufxvd.cn/Article/details/gtlbmwqrvi.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnvzdqpws.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.0kj1m.cn/Article/details/gtypocotsx.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.quarkkingdee.top/Article/details/gtzfulrnvq.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.hfpthk.cn/Article/details/gthylchmau.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.0kj1m.cn/Article/details/gtiepsvstj.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtpeptbmnd.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.birdmap.top/Article/details/gtzyuygsrd.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtryvoikum.html

[Q01] 创建表
来源：http://dali.feifeiyinyue.top/Article/details/gtwbeilcrp.html

CREATE TABLE users (
来源：http://dali.jqgufenzy.top/Article/details/gtesfffltb.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.gaohongyu789.top/Article/details/gtwfjvduvt.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhongyouzk.top/Article/details/gtqhfxxose.html

email VARCHAR(100) UNIQUE,
来源：http://dali.hnqzz.top/Article/details/gtxcokuerb.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.vqdsnc.cn/Article/details/gtuoxksbhj.html

);
来源：http://dali.fzhhl.top/Article/details/gtgvwwghar.html

[Q02] 创建带外键的表
来源：http://dali.zhengqikj.top/Article/details/gtezmozqqt.html

CREATE TABLE orders (
来源：http://dali.cqqwz.cn/Article/details/gttaphzqeb.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.0kj1m.cn/Article/details/gtyryxtmyh.html

user_id INT NOT NULL,
来源：http://dali.c1oappe.top/Article/details/gtnngbqnyz.html

amount DECIMAL(10, 2),
来源：http://dali.316326.xyz/Article/details/gtbqfqeoni.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhoulong.xyz/Article/details/gtuuzytmoz.html

);
来源：http://dali.xinyue.icu/Article/details/gtfjeuranc.html

[Q03] 增加列
来源：http://dali.hysaishi.cn/Article/details/gtektychas.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtakocvhqh.html

[Q04] 修改列类型
来源：http://dali.yueranfly.top/Article/details/gtjnnbdzrx.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.daria6918.cn/Article/details/gtnzzyctnt.html

[Q05] 重命名列
来源：http://dali.jyoumei.cn/Article/details/gtxfljrvmx.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.gogol.net.cn/Article/details/gtjrftansj.html

[Q06] 删除列
来源：http://dali.svipenyu.cn/Article/details/gtwlhydrtv.html


<!-- 参考信息 -->