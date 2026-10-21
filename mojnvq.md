代发 wailian999

Ruby: exit 1
来源：http://dali.yj20258.top/Article/details/gtwznaaavx.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.bjfxy.top/Article/details/gtgwheyxcz.html

[M06] 向标准错误输出
来源：http://dali.vqdsnc.cn/Article/details/gthjhbpjux.html

Py:   print("err", file=sys.stderr)
来源：http://dali.cashguo.top/Article/details/gtdozcaeng.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.ehwqpu.com/Article/details/gtavefqyaj.html

JS:   console.error("err")
来源：http://dali.nanxuanxn.top/Article/details/gtbtnjnice.html

TS:   console.error("err")
来源：http://dali.0kj1m.cn/Article/details/gtgjgsygsa.html

Java: System.err.println("err")
来源：http://dali.cashguo.top/Article/details/gthjqtgowq.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.yangfankeji.com/Article/details/gtzsgzzadp.html

Ruby: warn "err"
来源：http://dali.yangfankeji.com/Article/details/gtrvckgeuf.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.xylfe.cn/Article/details/gtonvjcrrb.html

[M07] 判断是否为主入口
来源：http://dali.iojbl.cn/Article/details/gtvsqqqfng.html

Py:   if __name__ == "__main__":
来源：http://dali.tianlin.xyz/Article/details/gtjakadcaa.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.ivvv.top/Article/details/gtbwpnxoot.html

JS:   require.main === module
来源：http://dali.jqgufenzy.top/Article/details/gtrbyvgtgg.html

TS:   require.main === module
来源：http://dali.yvedp.cn/Article/details/gtzljvqemk.html

Java: public static void main(String[] args)
来源：http://dali.chenjidiqi.icu/Article/details/gtfnlwtfud.html

Go:   func main()
来源：http://dali.xuetiantiany.cn/Article/details/gtteysyfzx.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.yuxming.cn/Article/details/gtepmumbjo.html

C#:   static void Main(string[] args)
来源：http://dali.chenlongwang.top/Article/details/gtdrxotglt.html

[M08] 获取系统与运行时信息
来源：http://dali.zdqjudy.top/Article/details/gtdpozbwjx.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zdqjudy.top/Article/details/gtrzfvmhvq.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.yj20258888.top/Article/details/gthxraqbsp.html

JS:   process.platform;  process.version
来源：http://dali.guowangkeji.top/Article/details/gtspwdqyjk.html

TS:   process.platform;  process.version
来源：http://dali.xylfe.cn/Article/details/gtiwovbaia.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.feifeiyinyue.top/Article/details/gtabtltryp.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.hywenlv.cn/Article/details/gtrysfhnyf.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.gotoacloud.top/Article/details/gthrqzyjol.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.redwolf501.top/Article/details/gtaplcjpjt.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gttynzqnoz.html

N. 数据结构与算法
来源：http://dali.zycfv.cn/Article/details/gtopfxyuhs.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtdjtuhwbx.html

[N01] 二分查找（有序数组）
来源：http://dali.bjfxy.top/Article/details/gtfdisiolh.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.yangfankeji.com/Article/details/gtkzzkbiwy.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.dianchejie.cn/Article/details/gtizwjhwxv.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhixingplan.top/Article/details/gtyduonuwi.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.cqqwz.cn/Article/details/gtfdrcpzvh.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.yj202588.top/Article/details/gtzycuesuq.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.guowangkeji.top/Article/details/gtlcfyfbbu.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.nwbrower.top/Article/details/gtztlqcpka.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.hammf.cn/Article/details/gtxtmdckgo.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.xuetiantiany.cn/Article/details/gteivwlmyj.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gtbyawngiz.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.guannengcc.top/Article/details/gtekayqeve.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yj20258888.top/Article/details/gtofeurgkg.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcnjfnuqk.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.0kj1m.cn/Article/details/gtiomcnvpk.html

Go:   slices.Sort(arr)
来源：http://dali.xziqi.cn/Article/details/gtjrrtikpi.html

Ruby: arr.sort
来源：http://dali.ehwqpu.com/Article/details/gtdcoxpxkd.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.ivvv.top/Article/details/gtwdyfuvsl.html

[N03] 快速排序（分治示例）
来源：http://dali.tian-w.cn/Article/details/gtzcwfpjsu.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.ivvv.top/Article/details/gtqwrieprg.html

PHP:  // 递归实现，或用 usort
来源：http://dali.yj20258888.top/Article/details/gteqsixusw.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.redwolf501.top/Article/details/gtwydlifiw.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yueranfly.top/Article/details/gtaykvajcg.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.jyoumei.cn/Article/details/gthnbqcrfp.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.bjfxy.top/Article/details/gtxfshadol.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.tian-w.cn/Article/details/gtoqumbmtc.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.yj20258888.top/Article/details/gtkndvrvzd.html

[N04] 斐波那契数列
来源：http://dali.aibaodan.cn/Article/details/gtxdyxpbtp.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.hfpthk.cn/Article/details/gthrbevidp.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.cashguo.top/Article/details/gtrgapdvqg.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.birdmap.top/Article/details/gtgxjnfmkb.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.sufxvd.cn/Article/details/gtwmjmitxu.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.redwolf501.top/Article/details/gtpfrxnhnd.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.yuxming.cn/Article/details/gtvkrpcuft.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.redwolf501.top/Article/details/gtvvcymgtf.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.yj20258.top/Article/details/gtklxywkfh.html

[N05] 最大公约数
来源：http://dali.svipenyu.cn/Article/details/gtrvacvdhh.html

Py:   math.gcd(a, b)
来源：http://dali.wangdashe.top/Article/details/gteexqplyx.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.pengpengdd.cyou/Article/details/gtmcfhlrnx.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.feifeiyinyue.top/Article/details/gtjkqfnvya.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yangfankeji.com/Article/details/gthjhntuol.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhoulong.xyz/Article/details/gtpqfosbna.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.yvedp.cn/Article/details/gthducfldg.html

Ruby: a.gcd(b)
来源：http://dali.9152youxi.cn/Article/details/gtpopkkbus.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.bjfxy.top/Article/details/gthmyykviu.html

[N06] 判断回文字符串
来源：http://dali.jqgfzy.top/Article/details/gtztopbpfo.html

Py:   s == s[::-1]
来源：http://dali.snrcjt.cn/Article/details/gtasggjfux.html

PHP:  $s === strrev($s);
来源：http://dali.tian-w.cn/Article/details/gtkhtablyx.html

JS:   s === [...s].reverse().join("")
来源：http://dali.jinqigufen.top/Article/details/gtbchdboem.html

TS:   s === [...s].reverse().join("")
来源：http://dali.kuanghao11.cn/Article/details/gtsyyplczv.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.c1oappe.top/Article/details/gtdjspxido.html

Go:   // 双指针从两端比较
来源：http://dali.shanyushiyangtech.top/Article/details/gtyctmnsnv.html

Ruby: s == s.reverse
来源：http://dali.ppjwa.cn/Article/details/gtstmqcfmo.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.yongpay.top/Article/details/gtoqxaiufz.html

[N07] 两数之和（返回下标）
来源：http://dali.aizwys.cn/Article/details/gtolvzgbug.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.cdnleiting.top/Article/details/gtgdlfnbwh.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.shanyushiyangtech.top/Article/details/gtfhcuwjpl.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.jqgfzy.top/Article/details/gtovwiyddm.html

TS:   // 手写 Map<string, number>
来源：http://dali.feifeiyinyue.top/Article/details/gtmdzjuonp.html

Java: // 手写 HashMap
来源：http://dali.shzxlz.cn/Article/details/gtuegbrdqo.html

Go:   // 手写 map[int]int
来源：http://dali.jiagoushi.top/Article/details/gtlqavhdux.html

Ruby: // 手写 Hash
来源：http://dali.ivvv.top/Article/details/gtjdsyvbrh.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.316326.xyz/Article/details/gtkgfagxzk.html

[N08] 生成全排列
来源：http://dali.hywenlv.cn/Article/details/gtanqczsgz.html

Py:   itertools.permutations(arr)
来源：http://dali.quarkkingdee.top/Article/details/gthnqekahg.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gtgiwaawer.html

JS:   // 手写回溯递归
来源：http://dali.vqdsnc.cn/Article/details/gtstxwfrav.html

TS:   // 手写回溯递归
来源：http://dali.gotoacloud.top/Article/details/gtsiexxffn.html

Java: // 手写回溯递归
来源：http://dali.meibo888.top/Article/details/gtkafnlodz.html

Go:   // 手写回溯递归
来源：http://dali.meibo888.top/Article/details/gtdzruqyrd.html

Ruby: arr.permutation.to_a
来源：http://dali.tian-w.cn/Article/details/gtdqicajne.html

C#:   // 手写回溯递归
来源：http://dali.shanyushiyangtech.top/Article/details/gttkvsxuvj.html

[N09] 栈与队列
来源：http://dali.shanyushiyangtech.top/Article/details/gtddjqiebp.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.0kj1m.cn/Article/details/gtyyscapbq.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnfiedcoo.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.ivvv.top/Article/details/gtbyygjkdo.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.sysykeji.top/Article/details/gtdmtsabxe.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.gaohongyu789.top/Article/details/gtlbopegwp.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.cdnleiting.top/Article/details/gtqbqjgmvl.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.dianchejie.cn/Article/details/gtbvipstuc.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.tanke756.top/Article/details/gtugvvgnfo.html

[N10] 链表节点定义
来源：http://dali.tianlin.xyz/Article/details/gtljyvknfl.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.ywan-chungtsiang.top/Article/details/gttspduhzx.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.c1oappe.top/Article/details/gtnzkbfakn.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.yj202588.top/Article/details/gtgsvejaey.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.chenzaomai.com/Article/details/gtdideyhzj.html

Java: class Node { int v; Node next; }
来源：http://dali.hongshengwenyu.top/Article/details/gtuqatvogh.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhongyouzk.top/Article/details/gtyhrtsblr.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.pycfn.com/Article/details/gtmdkcnldc.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.shanyushiyangtech.top/Article/details/gttzuqbtab.html

[N11] 二叉树中序遍历
来源：http://dali.hnqzz.top/Article/details/gtlspfsrit.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zdqjudy.top/Article/details/gtjrdgbnxp.html

PHP:  // 手写递归函数
来源：http://dali.pycfn.com/Article/details/gtiohnhjlj.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.sxryk.cn/Article/details/gtzxzjzznt.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.aibaodan.cn/Article/details/gtevkomkpo.html

Java: // 手写递归
来源：http://dali.pycfn.com/Article/details/gtwdeldpgz.html

Go:   // 手写递归
来源：http://dali.xuetiantiany.cn/Article/details/gtdwvvlvnw.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.xziqi.cn/Article/details/gtlyocfanr.html

C#:   // 手写递归
来源：http://dali.yangfankeji.com/Article/details/gtcdqrdvdg.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.andypj.xyz/Article/details/gtftlwxtci.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.aizwys.cn/Article/details/gtqmiqdotc.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.cqqwz.cn/Article/details/gtzdecvlie.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.fzhhl.top/Article/details/gtehvcimbu.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jlsjyb.cn/Article/details/gtqnhfevnu.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.aibaodan.cn/Article/details/gtnjnsitvt.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.jqgufenzy.top/Article/details/gtvlatnfij.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.sufxvd.cn/Article/details/gtpycbaixh.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yvedp.cn/Article/details/gtieklhvwr.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtebeqcmtx.html

O. 并发与异步
来源：http://dali.hammf.cn/Article/details/gtdnpcmhcj.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtdjvqphix.html

[O01] 启动一个线程
来源：http://dali.shuidangran.top/Article/details/gtegxhgcnf.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.ydzc1.top/Article/details/gtnskxfojo.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.dianchejie.cn/Article/details/gtbbhaghet.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.jlsjyb.cn/Article/details/gtzaxuavnb.html

TS:   // 同 JS
来源：http://dali.redwolf501.top/Article/details/gtopsgiphi.html

Java: new Thread(() -> f()).start()
来源：http://dali.ehwqpu.com/Article/details/gtfluuqnru.html

Go:   go f()
来源：http://dali.chenjidiqi.icu/Article/details/gtaqmqmaae.html

Ruby: Thread.new { f }
来源：http://dali.shuidangran.top/Article/details/gtsewpmfdo.html

C#:   Task.Run(() => F());
来源：http://dali.aizwys.cn/Article/details/gtdmspzdci.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gttnuayoei.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.fengsongda.top/Article/details/gtmmtvlzsf.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.gotoacloud.top/Article/details/gtttpbguog.html

JS:   // worker_threads 线程池
来源：http://dali.sweek.top/Article/details/gtqoqqncjd.html

TS:   // worker_threads 线程池
来源：http://dali.gogol.net.cn/Article/details/gtwayunbxm.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.shzxlz.cn/Article/details/gtdepgedsv.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zdqjudy.top/Article/details/gtiwnpnani.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzoxlrpyk.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.fengsongda.top/Article/details/gtfxpufciq.html

[O03] 加锁保护共享数据
来源：http://dali.guowangkeji.top/Article/details/gtbbsvdzdq.html

Py:   with lock: shared += 1
来源：http://dali.cheryme.top/Article/details/gtgqkchbzc.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhoulong.xyz/Article/details/gtroucdnhp.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.jiagoushi.top/Article/details/gtykkjztaf.html

TS:   // 同 JS
来源：http://dali.fengsongda.top/Article/details/gtjrenjsno.html

Java: synchronized (this) { shared++; }
来源：http://dali.jinghuilouyu.cn/Article/details/gthxogewae.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.yuxming.cn/Article/details/gthctngwby.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.jianghu66.top/Article/details/gtqcllaqms.html

C#:   lock (gate) { shared++; }
来源：http://dali.jianghu66.top/Article/details/gtwowadjut.html

[O04] 定义异步函数并等待
来源：http://dali.wangdashe.top/Article/details/gtjbhsvizn.html

Py:   async def f():⏎    await g()
来源：http://dali.jianghu66.top/Article/details/gtepnyrkus.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.gotoacloud.top/Article/details/gtqoyrcrnv.html

JS:   async function f() { await g(); }
来源：http://dali.smart0.xyz/Article/details/gtpvqyxxgb.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.hfpthk.cn/Article/details/gtxosenlet.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.smart0.xyz/Article/details/gtharlczvr.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.jiagoushi.top/Article/details/gtpmacrnyp.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.yvedp.cn/Article/details/gtlixherha.html

C#:   async Task F() { await G(); }
来源：http://dali.ydzc1.top/Article/details/gtsahthmsk.html

[O05] 并发执行并等待全部完成
来源：http://dali.chenzaomai.com/Article/details/gtfdrjnuic.html

Py:   asyncio.gather(*tasks)
来源：http://dali.hammf.cn/Article/details/gthrairggv.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.quarkkingdee.top/Article/details/gtnxxoosqn.html

JS:   await Promise.all(tasks)
来源：http://dali.shangyingyoupin.top/Article/details/gttnkladvf.html

TS:   await Promise.all(tasks)
来源：http://dali.316326.xyz/Article/details/gtqgrhynqy.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.tianlin.xyz/Article/details/gtdpvxcvap.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.yj20258888.top/Article/details/gtbwralbwz.html

Ruby: threads.map(&:join)
来源：http://dali.jlsjyb.cn/Article/details/gtccoktqnm.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.jqgufenzy.top/Article/details/gtbypfnnze.html

[O06] 使用进程池
来源：http://dali.dashuyun.cn/Article/details/gtsttabeil.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.gogol.net.cn/Article/details/gtwforaiii.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.aizwys.cn/Article/details/gtcziagazd.html

JS:   // child_process / cluster 模块
来源：http://dali.wangshuangyany.cn/Article/details/gtqfkroste.html

TS:   // child_process / cluster 模块
来源：http://dali.xylfe.cn/Article/details/gtllptvimx.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.yj20258888.top/Article/details/gtglqsefeb.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.daxiang520.top/Article/details/gtgkrvopov.html

Ruby: // fork 块
来源：http://dali.shangyingyoupin.top/Article/details/gtusqmuegs.html

C#:   Parallel.For
来源：http://dali.hongshengwenyu.top/Article/details/gtomytplwo.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtrxbeyazz.html

P. 常用工具函数
来源：http://dali.chenlongwang.top/Article/details/gtjhdtcfuo.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtjvjrsibm.html

[P01] 生成 UUID
来源：http://dali.nanxuanxn.top/Article/details/gtuwtfwnqd.html

Py:   str(uuid.uuid4())
来源：http://dali.ehwqpu.com/Article/details/gtximyuyrz.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.yj20258.top/Article/details/gtkiskvbqo.html

JS:   crypto.randomUUID()
来源：http://dali.jlsjyb.cn/Article/details/gtdfgnrctc.html

TS:   crypto.randomUUID()
来源：http://dali.zdqjudy.top/Article/details/gtvhcpxekh.html

Java: UUID.randomUUID().toString()
来源：http://dali.fengsongda.top/Article/details/gtkkxccdrr.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gtwzmlpmno.html

Ruby: SecureRandom.uuid
来源：http://dali.guowangkeji.top/Article/details/gtskevkumd.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.xuetiantiany.cn/Article/details/gtthsvdtxs.html

[P02] MD5 / SHA256 摘要
来源：http://dali.jqgfzy.top/Article/details/gtblukafup.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.cucudq.cn/Article/details/gtlxlaumco.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.gzhubu.top/Article/details/gtoqbhxydw.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.yongpay.top/Article/details/gtckouzcht.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.xuetiantiany.cn/Article/details/gtwpotsrnd.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhongyouzk.top/Article/details/gtqaifdvyc.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.sysykeji.top/Article/details/gtggcvolow.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.ppjwa.cn/Article/details/gtjcliszzi.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.ivvv.top/Article/details/gtjmejezqn.html

[P03] 生成短随机字符串
来源：http://dali.svipenyu.cn/Article/details/gtacfhxhhf.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.feifeiyinyue.top/Article/details/gtokpanipn.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.cashguo.top/Article/details/gtjwvpbmtl.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yongpay.top/Article/details/gtjmqqwcra.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.pycfn.com/Article/details/gtnadwugit.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.jlsjyb.cn/Article/details/gtpmxboylf.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.haohaochexian.top/Article/details/gtitazkcep.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.cqqwz.cn/Article/details/gthtmsqntq.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.jqgfzy.top/Article/details/gtxtzfaypc.html

[P04] 求长度
来源：http://dali.haohaochexian.top/Article/details/gttkltsuzr.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.yj20258.top/Article/details/gtetywnxzu.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.redwolf501.top/Article/details/gtvnuwewul.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.ybcxt.top/Article/details/gtvpnclmcy.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.c1oappe.top/Article/details/gtrqgtefkh.html

Java: list.size();  map.size();  s.length()
来源：http://dali.0kj1m.cn/Article/details/gticuicvtb.html

Go:   len(arr);  len(m)
来源：http://dali.bjfxy.top/Article/details/gtwixpzazj.html

Ruby: x.length;  x.size
来源：http://dali.cashguo.top/Article/details/gtsohzzmwo.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.jinyuanbaomall.cn/Article/details/gtubsxqhwr.html

[P05] 判断两个对象内容是否相等
来源：http://dali.316326.xyz/Article/details/gttpfdgckw.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.hysaishi.cn/Article/details/gtfcuniczo.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.daria6918.cn/Article/details/gttycvubri.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.chenzaomai.com/Article/details/gtprvovvjm.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.haohaochexian.top/Article/details/gthjxsicle.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhengqikj.top/Article/details/gtjedbmszf.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.sufxvd.cn/Article/details/gtczwxyydy.html

Ruby: a == b
来源：http://dali.sweek.top/Article/details/gthybaolst.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.yj20258888.top/Article/details/gtofhutebh.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.tanke756.top/Article/details/gtaztyxdco.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.yongpay.top/Article/details/gtfrfkzryt.html

PHP:  if (empty($x)) {}
来源：http://dali.meibo888.top/Article/details/gtpvlxpvqt.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.shangyingyoupin.top/Article/details/gtjougbyrw.html

TS:   if (x == null) {}
来源：http://dali.redwolf501.top/Article/details/gtukpdflpo.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.nanxuanxn.top/Article/details/gtyuxcystl.html

Go:   if x == nil {}
来源：http://dali.nanxuanxn.top/Article/details/gtobkzrykg.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.fzhhl.top/Article/details/gtshmjvghg.html

C#:   if (x is null) {}
来源：http://dali.gogol.net.cn/Article/details/gtujtanzse.html

[P07] 防抖与节流
来源：http://dali.zycfv.cn/Article/details/gtrnalwgwb.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.yj20258888.top/Article/details/gtizggbuji.html

PHP:  // 手写时间戳比较
来源：http://dali.sweek.top/Article/details/gtgccdjazh.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.shuidangran.top/Article/details/gtsdqvqlys.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.bjfxy.top/Article/details/gtmyqdhoov.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.pycfn.com/Article/details/gtuajahsqd.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.wangdashe.top/Article/details/gtdtvgibsd.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.smart0.xyz/Article/details/gtgxtmdznm.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.jianghu66.top/Article/details/gthsrfhggc.html

[P08] 处理浮点精度问题
来源：http://dali.xuetiantiany.cn/Article/details/gtthzsykcr.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.jlsjyb.cn/Article/details/gtfcdmozqh.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.yuanzhike.top/Article/details/gtvakjgqav.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.guowangkeji.top/Article/details/gtwuqabfsa.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.tanke756.top/Article/details/gtqkpfqakx.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.yj202588.top/Article/details/gtgixvdzoe.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.snrcjt.cn/Article/details/gtwtupuqus.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.chenlongwang.top/Article/details/gthotekvyv.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.haohaochexian.top/Article/details/gtkpgnghyh.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtbqxmfszj.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsapausqd.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtucnqbhmn.html

[Q01] 创建表
来源：http://dali.cqqwz.cn/Article/details/gtdiethoqt.html

CREATE TABLE users (
来源：http://dali.316326.xyz/Article/details/gtbftrkugy.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.cheryme.top/Article/details/gtfiaicida.html

name VARCHAR(50) NOT NULL,
来源：http://dali.xylfe.cn/Article/details/gtifiifvyk.html

email VARCHAR(100) UNIQUE,
来源：http://dali.yj20258.top/Article/details/gtvpjzeata.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.hnxiangtu.top/Article/details/gtjwynwmry.html

);
来源：http://dali.sysykeji.top/Article/details/gtsesnkltl.html

[Q02] 创建带外键的表
来源：http://dali.cucudq.cn/Article/details/gtowztewfj.html

CREATE TABLE orders (
来源：http://dali.cdnleiting.top/Article/details/gtzvnnhizg.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.ybcxt.top/Article/details/gtpetejhfl.html

user_id INT NOT NULL,
来源：http://dali.fengsongda.top/Article/details/gtjtnajppy.html

amount DECIMAL(10, 2),
来源：http://dali.daria6918.cn/Article/details/gtdcnvsirr.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.sysykeji.top/Article/details/gtkowahhxs.html

);
来源：http://dali.hongshengwenyu.top/Article/details/gtvjnakzqi.html

[Q03] 增加列
来源：http://dali.dashuyun.cn/Article/details/gtdtopedbd.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhongyouzk.top/Article/details/gtdhlvtifn.html

[Q04] 修改列类型
来源：http://dali.xuanzx.com/Article/details/gtblbzqlid.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.hfpthk.cn/Article/details/gtmyjycpif.html

[Q05] 重命名列
来源：http://dali.tianlin.xyz/Article/details/gthrsmjlgy.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.ehwqpu.com/Article/details/gtswyootlk.html

[Q06] 删除列
来源：http://dali.yuanzhike.top/Article/details/gtjycuokzf.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.bjfxy.top/Article/details/gtrxrjfyto.html

[Q07] 删除表
来源：http://dali.nanxinkj.top/Article/details/gttqqajluf.html

DROP TABLE IF EXISTS orders;
来源：http://dali.shanyushiyangtech.top/Article/details/gtnspdpdyc.html

[Q08] 创建普通索引
来源：http://dali.fengsongda.top/Article/details/gtehgdqcak.html


<!-- 参考信息 -->