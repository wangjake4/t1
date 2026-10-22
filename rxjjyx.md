代发 wailian999

C#:   Directory.GetCurrentDirectory()
来源：http://dali.guowangkeji.top/Article/details/gtuevaorbk.html

[M05] 设置退出码
来源：http://dali.aibaodan.cn/Article/details/gtfhdcmvhb.html

Py:   sys.exit(1)
来源：http://dali.0kj1m.cn/Article/details/gtmgyoqmaq.html

PHP:  exit(1);
来源：http://dali.redwolf501.top/Article/details/gtawjghdbg.html

JS:   process.exit(1)
来源：http://dali.daria6918.cn/Article/details/gtydsaivqk.html

TS:   process.exit(1)
来源：http://dali.shanyushiyangtech.top/Article/details/gtpohylzsc.html

Java: System.exit(1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gticbpgatv.html

Go:   os.Exit(1)
来源：http://dali.ppjwa.cn/Article/details/gtpuoxvjul.html

Ruby: exit 1
来源：http://dali.hnqzz.top/Article/details/gtpzqrzirw.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.xuetiantiany.cn/Article/details/gtsqvpvqqx.html

[M06] 向标准错误输出
来源：http://dali.xinyue.icu/Article/details/gtccxdsple.html

Py:   print("err", file=sys.stderr)
来源：http://dali.bjfxy.top/Article/details/gtbfnbylxk.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.jqgfzy.top/Article/details/gtriisjhgi.html

JS:   console.error("err")
来源：http://dali.jinqigufen.top/Article/details/gtgbkamlwz.html

TS:   console.error("err")
来源：http://dali.xinyue.icu/Article/details/gtlzrzdtop.html

Java: System.err.println("err")
来源：http://dali.tianlin.xyz/Article/details/gteyozohss.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.hammf.cn/Article/details/gtkkyufgru.html

Ruby: warn "err"
来源：http://dali.yj202588.top/Article/details/gtdcrtnrem.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.yj202588.top/Article/details/gtycrmofpg.html

[M07] 判断是否为主入口
来源：http://dali.shzxlz.cn/Article/details/gtkwlzpkps.html

Py:   if __name__ == "__main__":
来源：http://dali.hnxiangtu.top/Article/details/gttfcoffpj.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.0kj1m.cn/Article/details/gticctvetr.html

JS:   require.main === module
来源：http://dali.zhoulong.xyz/Article/details/gtviyolelc.html

TS:   require.main === module
来源：http://dali.haohaochexian.top/Article/details/gtmnedkvmz.html

Java: public static void main(String[] args)
来源：http://dali.mhx1999.top/Article/details/gtlnroxdfb.html

Go:   func main()
来源：http://dali.cqqwz.cn/Article/details/gtpzdjbzzp.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.shzxlz.cn/Article/details/gtkvacfimn.html

C#:   static void Main(string[] args)
来源：http://dali.sufxvd.cn/Article/details/gtcowiuipg.html

[M08] 获取系统与运行时信息
来源：http://dali.jqgfzy.top/Article/details/gtsyxrznex.html

Py:   platform.system();  platform.python_version()
来源：http://dali.feifeiyinyue.top/Article/details/gtjmddqpnz.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.ivvv.top/Article/details/gtvvsehrau.html

JS:   process.platform;  process.version
来源：http://dali.chenzaomai.com/Article/details/gtyziftbkw.html

TS:   process.platform;  process.version
来源：http://dali.jqgufenzy.top/Article/details/gtcptbgyhn.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.9152youxi.cn/Article/details/gtriogytum.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.yangfankeji.com/Article/details/gtklefgfle.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.sysykeji.top/Article/details/gtotqhnrxz.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.chenlongwang.top/Article/details/gtnjuumqid.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtwfukflgg.html

N. 数据结构与算法
来源：http://dali.cheryme.top/Article/details/gtcxgvgzuv.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtndrawhia.html

[N01] 二分查找（有序数组）
来源：http://dali.birdmap.top/Article/details/gtfzvidmfr.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.nwbrower.top/Article/details/gtdpcnvxxf.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.sweek.top/Article/details/gtfdngvvnj.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zdqjudy.top/Article/details/gtduvhpgsz.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yongpay.top/Article/details/gtznvimcea.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.bjfxy.top/Article/details/gtsjaxotmj.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.aizwys.cn/Article/details/gtklftdele.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.yanxiufei.cn/Article/details/gtqddcugsh.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.shangyingyoupin.top/Article/details/gtcbkafnbl.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.nanxinkj.top/Article/details/gtknxgjypt.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.ppjwa.cn/Article/details/gtibpruwkd.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.xylfe.cn/Article/details/gtgdbubmnn.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jlsjyb.cn/Article/details/gtxprjvssg.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.iojbl.cn/Article/details/gtvfmjpifv.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.nwbrower.top/Article/details/gtnmvnxklx.html

Go:   slices.Sort(arr)
来源：http://dali.dianchejie.cn/Article/details/gtdtgczfgn.html

Ruby: arr.sort
来源：http://dali.shzxlz.cn/Article/details/gtpgdpfyay.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.shuidangran.top/Article/details/gtgjasztev.html

[N03] 快速排序（分治示例）
来源：http://dali.quarkkingdee.top/Article/details/gtwfujdesj.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.pengpengdd.cyou/Article/details/gtxvxbijti.html

PHP:  // 递归实现，或用 usort
来源：http://dali.redwolf501.top/Article/details/gtekvzllnn.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.dianchejie.cn/Article/details/gtkjpfyjhm.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.gaohongyu789.top/Article/details/gtzauijkgy.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.nanxuanxn.top/Article/details/gtlnfsbugw.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.andypj.xyz/Article/details/gtxfaliptc.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.yj20258.top/Article/details/gtoinfxsru.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.ivvv.top/Article/details/gtqxioilej.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gtrqlprzni.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.daria6918.cn/Article/details/gtqtskzqvr.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.redwolf501.top/Article/details/gtdforomdn.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.nanxuanxn.top/Article/details/gtluekkcvw.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhiwuduotai.top/Article/details/gtznryztkx.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.jlsjyb.cn/Article/details/gtspasvneu.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.tanke756.top/Article/details/gtmjmxchqn.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpwkjyudy.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.jianghu66.top/Article/details/gtfjrfbhhx.html

[N05] 最大公约数
来源：http://dali.fzhhl.top/Article/details/gtfgevrbsd.html

Py:   math.gcd(a, b)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqkndefoc.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhixingplan.top/Article/details/gtbttlkctx.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.smart0.xyz/Article/details/gtmpsabeqe.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.cheryme.top/Article/details/gtwwcvavhz.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gtaiuaylbs.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.xylfe.cn/Article/details/gtwpssaxtm.html

Ruby: a.gcd(b)
来源：http://dali.sweek.top/Article/details/gtrmrpqqnh.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.guannengcc.top/Article/details/gtabsyybfd.html

[N06] 判断回文字符串
来源：http://dali.hfpthk.cn/Article/details/gttutelssx.html

Py:   s == s[::-1]
来源：http://dali.yangfankeji.com/Article/details/gttxmunmuv.html

PHP:  $s === strrev($s);
来源：http://dali.wangdashe.top/Article/details/gthgsdmtmn.html

JS:   s === [...s].reverse().join("")
来源：http://dali.xinyue.icu/Article/details/gttmyurlfb.html

TS:   s === [...s].reverse().join("")
来源：http://dali.shanyushiyangtech.top/Article/details/gtqahxiffh.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.pengpengdd.cyou/Article/details/gtupbmkkug.html

Go:   // 双指针从两端比较
来源：http://dali.meibo888.top/Article/details/gthfbnjekg.html

Ruby: s == s.reverse
来源：http://dali.tian-w.cn/Article/details/gtljsvbgkq.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.jiagoushi.top/Article/details/gthohatdku.html

[N07] 两数之和（返回下标）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbthtlztj.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.hywenlv.cn/Article/details/gtweoudbit.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.hfpthk.cn/Article/details/gtzwtmsqwy.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.fengsongda.top/Article/details/gtnvequyau.html

TS:   // 手写 Map<string, number>
来源：http://dali.bjfxy.top/Article/details/gtfmombryt.html

Java: // 手写 HashMap
来源：http://dali.zhixingplan.top/Article/details/gtmzshiwkn.html

Go:   // 手写 map[int]int
来源：http://dali.xinyue.icu/Article/details/gtatfvcakn.html

Ruby: // 手写 Hash
来源：http://dali.xziqi.cn/Article/details/gteffnlhik.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.hongshengwenyu.top/Article/details/gtkehcbnhz.html

[N08] 生成全排列
来源：http://dali.feifeiyinyue.top/Article/details/gtifbgsiyw.html

Py:   itertools.permutations(arr)
来源：http://dali.haohaochexian.top/Article/details/gtahjohpbf.html

PHP:  // 手写递归交换
来源：http://dali.redwolf501.top/Article/details/gtfvngojrj.html

JS:   // 手写回溯递归
来源：http://dali.gotoacloud.top/Article/details/gtmsuxwerl.html

TS:   // 手写回溯递归
来源：http://dali.redwolf501.top/Article/details/gthucuuolv.html

Java: // 手写回溯递归
来源：http://dali.wangdashe.top/Article/details/gtbcaknkiu.html

Go:   // 手写回溯递归
来源：http://dali.xylfe.cn/Article/details/gtajkejmec.html

Ruby: arr.permutation.to_a
来源：http://dali.pycfn.com/Article/details/gtadwbosex.html

C#:   // 手写回溯递归
来源：http://dali.tian-w.cn/Article/details/gtruixksne.html

[N09] 栈与队列
来源：http://dali.jianghu66.top/Article/details/gtzrdhpllw.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.0kj1m.cn/Article/details/gtjvbwhljh.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.tanke756.top/Article/details/gtqltwvieo.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.ydzc1.top/Article/details/gtihlzxphd.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.ivvv.top/Article/details/gtmllnlkmf.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.tian-w.cn/Article/details/gtpczhucio.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.jinqigfzy.top/Article/details/gtnjtuesxu.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.smart0.xyz/Article/details/gtdjerjmpw.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.andypj.xyz/Article/details/gtqsbkxjlt.html

[N10] 链表节点定义
来源：http://dali.meibo888.top/Article/details/gthdppzpob.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.jlsjyb.cn/Article/details/gtleucejya.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zycfv.cn/Article/details/gtzcnpwvfg.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.guowangkeji.top/Article/details/gtnexeqcje.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.andypj.xyz/Article/details/gtdykgmwnz.html

Java: class Node { int v; Node next; }
来源：http://dali.c1oappe.top/Article/details/gtaxsdbxdv.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.ivvv.top/Article/details/gtgmizlxvq.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.shzxlz.cn/Article/details/gtybypllhh.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.ybcxt.top/Article/details/gtbhzysuyd.html

[N11] 二叉树中序遍历
来源：http://dali.yj202588.top/Article/details/gtacotspek.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.jqgufenzy.top/Article/details/gtewifhons.html

PHP:  // 手写递归函数
来源：http://dali.pycfn.com/Article/details/gtmlioaekc.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yuanzhike.top/Article/details/gtkcuokaqm.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yj202588.top/Article/details/gtasplmmye.html

Java: // 手写递归
来源：http://dali.sufxvd.cn/Article/details/gthdtncgav.html

Go:   // 手写递归
来源：http://dali.jiagoushi.top/Article/details/gtbpcnbphb.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.chenzaomai.com/Article/details/gtsilpugcq.html

C#:   // 手写递归
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqmnlbxem.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.guannengcc.top/Article/details/gtvzjtzkba.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.0kj1m.cn/Article/details/gtwtdycdqa.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.daria6918.cn/Article/details/gtjlmgfwfb.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.cdnleiting.top/Article/details/gttcpufloc.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yangfankeji.com/Article/details/gtgmmltsee.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.ehwqpu.com/Article/details/gtvneenrtz.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.nanxinkj.top/Article/details/gtzuqupkze.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.guowangkeji.top/Article/details/gtmcnmoxfy.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.sufxvd.cn/Article/details/gtoitiwbty.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtexlhtjpi.html

O. 并发与异步
来源：http://dali.gaohongyu789.top/Article/details/gtvbnppfdg.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtqpwfdnay.html

[O01] 启动一个线程
来源：http://dali.gaohongyu789.top/Article/details/gtjtqfqwdx.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.daxiang520.top/Article/details/gtknunlexi.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.ppjwa.cn/Article/details/gtmngvuzrw.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.snrcjt.cn/Article/details/gtssxczmdd.html

TS:   // 同 JS
来源：http://dali.zhengqikj.top/Article/details/gtslkxznyc.html

Java: new Thread(() -> f()).start()
来源：http://dali.xuetiantiany.cn/Article/details/gtaazoanww.html

Go:   go f()
来源：http://dali.daria6918.cn/Article/details/gteebeiwet.html

Ruby: Thread.new { f }
来源：http://dali.wangshuangyany.cn/Article/details/gtljrbevqr.html

C#:   Task.Run(() => F());
来源：http://dali.pycfn.com/Article/details/gtdvzmtzrd.html

[O02] 使用线程池
来源：http://dali.ehwqpu.com/Article/details/gtbbhhvdrl.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.kuanghao11.cn/Article/details/gtvcqqjsak.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.aibaodan.cn/Article/details/gtnbrtiopd.html

JS:   // worker_threads 线程池
来源：http://dali.zhongyouzk.top/Article/details/gtrzttywbx.html

TS:   // worker_threads 线程池
来源：http://dali.yueranfly.top/Article/details/gtgzoprdhd.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.sufxvd.cn/Article/details/gtkygwgjjc.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.smart0.xyz/Article/details/gtvhyoafia.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.guannengcc.top/Article/details/gtuqtwhluf.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.daria6918.cn/Article/details/gtlqchrsav.html

[O03] 加锁保护共享数据
来源：http://dali.zycfv.cn/Article/details/gtxshcnest.html

Py:   with lock: shared += 1
来源：http://dali.jianghu66.top/Article/details/gttvwmjvup.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.pycfn.com/Article/details/gtrgbixcte.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.xinyue.icu/Article/details/gtyspoaicn.html

TS:   // 同 JS
来源：http://dali.xuanzx.com/Article/details/gtavubrnxm.html

Java: synchronized (this) { shared++; }
来源：http://dali.hywenlv.cn/Article/details/gtebuwkjzv.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.gaohongyu789.top/Article/details/gtzvjdmfra.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.hongshengwenyu.top/Article/details/gtjnngmwuq.html

C#:   lock (gate) { shared++; }
来源：http://dali.shzxlz.cn/Article/details/gtwxdjrbkw.html

[O04] 定义异步函数并等待
来源：http://dali.cashguo.top/Article/details/gtcxmzgtrk.html

Py:   async def f():⏎    await g()
来源：http://dali.hfpthk.cn/Article/details/gtwbmvajlz.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrdhlvsqz.html

JS:   async function f() { await g(); }
来源：http://dali.shuidangran.top/Article/details/gtujonzfxn.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.cdnleiting.top/Article/details/gtfvphcuzm.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.chenzaomai.com/Article/details/gttrfuwqcj.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.smart0.xyz/Article/details/gtczcbrjdl.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.jinqigfzy.top/Article/details/gtnsiobukd.html

C#:   async Task F() { await G(); }
来源：http://dali.svipenyu.cn/Article/details/gtlrjbzmcu.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhoulong.xyz/Article/details/gtkswotiqj.html

Py:   asyncio.gather(*tasks)
来源：http://dali.cdnleiting.top/Article/details/gtpttuhktz.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.yangfankeji.com/Article/details/gtptpxnzpi.html

JS:   await Promise.all(tasks)
来源：http://dali.yongpay.top/Article/details/gtbtjkblcp.html

TS:   await Promise.all(tasks)
来源：http://dali.yangfankeji.com/Article/details/gtpvwuifjd.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.guannengcc.top/Article/details/gthgitykmw.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.yuxming.cn/Article/details/gtvdifvjhf.html

Ruby: threads.map(&:join)
来源：http://dali.0kj1m.cn/Article/details/gtnvenfomr.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwtlylgqp.html

[O06] 使用进程池
来源：http://dali.ybcxt.top/Article/details/gtbxmrezpc.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.aibaodan.cn/Article/details/gtewplgouj.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.hammf.cn/Article/details/gtelhprket.html

JS:   // child_process / cluster 模块
来源：http://dali.xylfe.cn/Article/details/gtguiqnxrb.html

TS:   // child_process / cluster 模块
来源：http://dali.jyoumei.cn/Article/details/gtrmeapeuy.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.vqdsnc.cn/Article/details/gtlxcbigfu.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.andypj.xyz/Article/details/gtiqwstsce.html

Ruby: // fork 块
来源：http://dali.guannengcc.top/Article/details/gtcwyubvxy.html

C#:   Parallel.For
来源：http://dali.daxiang520.top/Article/details/gterbjzrnx.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtesbliwcn.html

P. 常用工具函数
来源：http://dali.yvedp.cn/Article/details/gtqpqnuklr.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtamtlrlyj.html

[P01] 生成 UUID
来源：http://dali.haohaochexian.top/Article/details/gtcatywnug.html

Py:   str(uuid.uuid4())
来源：http://dali.gzhubu.top/Article/details/gtezirssri.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcyzyxdhi.html

JS:   crypto.randomUUID()
来源：http://dali.jinqigufen.top/Article/details/gtvtgokzyr.html

TS:   crypto.randomUUID()
来源：http://dali.guowangkeji.top/Article/details/gtbknjgiie.html

Java: UUID.randomUUID().toString()
来源：http://dali.fengsongda.top/Article/details/gtngfpjzjv.html

Go:   // 用 github.com/google/uuid
来源：http://dali.0kj1m.cn/Article/details/gtosjyiwrd.html

Ruby: SecureRandom.uuid
来源：http://dali.sysykeji.top/Article/details/gtquupfhfo.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.sweek.top/Article/details/gtrnddjqmz.html

[P02] MD5 / SHA256 摘要
来源：http://dali.jinqigfzy.top/Article/details/gtylhcapve.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.guowangkeji.top/Article/details/gtzwixfomw.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.c1oappe.top/Article/details/gttnvkkfro.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.xylfe.cn/Article/details/gtqewmwxut.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.jyoumei.cn/Article/details/gtyqxxaapa.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.dianchejie.cn/Article/details/gtfjeblvus.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.andypj.xyz/Article/details/gtzgzfglip.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmuandoct.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.iojbl.cn/Article/details/gttkeblioq.html

[P03] 生成短随机字符串
来源：http://dali.zhiwuduotai.top/Article/details/gtohuorvcw.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.fzhhl.top/Article/details/gtwpvparsw.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.hysaishi.cn/Article/details/gtclfyqjpp.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhiwuduotai.top/Article/details/gtekfedzef.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.sysykeji.top/Article/details/gthqjocduy.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.jianghu66.top/Article/details/gthtwgbvlr.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.yongpay.top/Article/details/gtciyvjgzu.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.yj20258.top/Article/details/gtfpogceud.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.jinqigufen.top/Article/details/gtsejxivnm.html

[P04] 求长度
来源：http://dali.yangfankeji.com/Article/details/gtraqzirzf.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.svipenyu.cn/Article/details/gtocmdesyb.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.chenlongwang.top/Article/details/gtafvimrzc.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.ivvv.top/Article/details/gtsvdiwztv.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.0kj1m.cn/Article/details/gtvqmurxcj.html

Java: list.size();  map.size();  s.length()
来源：http://dali.chenlongwang.top/Article/details/gtmhsxyvap.html

Go:   len(arr);  len(m)
来源：http://dali.jinqigufen.top/Article/details/gtgylbgaav.html

Ruby: x.length;  x.size
来源：http://dali.shanyushiyangkeji.top/Article/details/gteudumxmw.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.fengsongda.top/Article/details/gtieovjqfs.html

[P05] 判断两个对象内容是否相等
来源：http://dali.havefunace.top/Article/details/gtpxwugacj.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.jqgufenzy.top/Article/details/gtaqzvkmeq.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.bjfxy.top/Article/details/gtbtmjzklq.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.xziqi.cn/Article/details/gtnipibdxa.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.xinyue.icu/Article/details/gtcppferql.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.shzxlz.cn/Article/details/gtqasocuaz.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.quarkkingdee.top/Article/details/gtcwcbauix.html

Ruby: a == b
来源：http://dali.haohaochexian.top/Article/details/gtlnrbzlga.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.quarkkingdee.top/Article/details/gtcvliucrt.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.pycfn.com/Article/details/gttrnfvgdm.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.daria6918.cn/Article/details/gtroxdardf.html

PHP:  if (empty($x)) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtnyvqjder.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.yuxming.cn/Article/details/gtfoxczvxj.html

TS:   if (x == null) {}
来源：http://dali.zdqjudy.top/Article/details/gthvvycxsz.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.chenzaomai.com/Article/details/gtpbdrwkvk.html

Go:   if x == nil {}
来源：http://dali.gzhubu.top/Article/details/gtwbhdfghe.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.tianlin.xyz/Article/details/gtingjxvwn.html

C#:   if (x is null) {}
来源：http://dali.yonumen.top/Article/details/gtsevzwrjd.html

[P07] 防抖与节流
来源：http://dali.hammf.cn/Article/details/gtkyaeefdj.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.pycfn.com/Article/details/gtvzelaofr.html

PHP:  // 手写时间戳比较
来源：http://dali.hongshengwenyu.top/Article/details/gtxttntfqs.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gtfiqjiahq.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yueranfly.top/Article/details/gtuuudssna.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.daxiang520.top/Article/details/gtdylbfgxn.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.ivvv.top/Article/details/gtfdgbknao.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.tanke756.top/Article/details/gtpjqpeggk.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.bjfxy.top/Article/details/gtoqgrjlto.html

[P08] 处理浮点精度问题
来源：http://dali.feifeiyinyue.top/Article/details/gtxhhrjqqs.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.gzhubu.top/Article/details/gtlbxanizr.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.jqgufenzy.top/Article/details/gtcyfcmhbq.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.yuxming.cn/Article/details/gtwjwjwyfl.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.gzhubu.top/Article/details/gtaesuesyf.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.c1oappe.top/Article/details/gtghknnaxr.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.sweek.top/Article/details/gtsmlyfbkw.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.birdmap.top/Article/details/gtbcbnoxjm.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.kuanghao11.cn/Article/details/gtrcbxkywx.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtvgrsrphv.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhixingplan.top/Article/details/gtywkvkcyx.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtljefnlue.html

[Q01] 创建表
来源：http://dali.nanxuanxn.top/Article/details/gtvmogihrc.html

CREATE TABLE users (
来源：http://dali.0kj1m.cn/Article/details/gtshiftawf.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.gotoacloud.top/Article/details/gtpvdaizih.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhongyouzk.top/Article/details/gtqwxkblmw.html

email VARCHAR(100) UNIQUE,
来源：http://dali.tanke756.top/Article/details/gtgsqwsqkl.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.jyoumei.cn/Article/details/gtejoqtbfp.html

);
来源：http://dali.ehwqpu.com/Article/details/gtawnvgdep.html

[Q02] 创建带外键的表
来源：http://dali.jinqigfzy.top/Article/details/gtlllwuqbq.html

CREATE TABLE orders (
来源：http://dali.hongshengwenyu.top/Article/details/gtbflneext.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.feifeiyinyue.top/Article/details/gtamafmume.html

user_id INT NOT NULL,
来源：http://dali.bjfxy.top/Article/details/gtocosvdmz.html

amount DECIMAL(10, 2),
来源：http://dali.wangdashe.top/Article/details/gtijtjotdd.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.hammf.cn/Article/details/gtjxveqkks.html

);
来源：http://dali.9152youxi.cn/Article/details/gtdaetotzc.html

[Q03] 增加列
来源：http://dali.wangshuangyany.cn/Article/details/gtelbcczfv.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.haohaochexian.top/Article/details/gtselwnkev.html

[Q04] 修改列类型
来源：http://dali.vqdsnc.cn/Article/details/gtblcvjyid.html


<!-- 参考信息 -->