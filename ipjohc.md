代发 wailian999

C#:   Directory.GetCurrentDirectory()
来源：http://dali.sysykeji.top/Article/details/gtvvvwyghb.html

[M05] 设置退出码
来源：http://dali.gzhubu.top/Article/details/gtalabdrqu.html

Py:   sys.exit(1)
来源：http://dali.jinqigufen.top/Article/details/gtxaetzdqf.html

PHP:  exit(1);
来源：http://dali.bjfxy.top/Article/details/gtkvfvkojt.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gthqtxfutj.html

TS:   process.exit(1)
来源：http://dali.yangfankeji.com/Article/details/gtqejqvwjs.html

Java: System.exit(1)
来源：http://dali.dianchejie.cn/Article/details/gtxzhjwfvl.html

Go:   os.Exit(1)
来源：http://dali.jinqigfzy.top/Article/details/gtkgpyezcg.html

Ruby: exit 1
来源：http://dali.daxiang520.top/Article/details/gtxthdpxmq.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.cucudq.cn/Article/details/gtdpkfgioy.html

[M06] 向标准错误输出
来源：http://dali.jyoumei.cn/Article/details/gtituoartg.html

Py:   print("err", file=sys.stderr)
来源：http://dali.cqqwz.cn/Article/details/gthxerzgjt.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.cheryme.top/Article/details/gtrisydjzo.html

JS:   console.error("err")
来源：http://dali.chenlongwang.top/Article/details/gttqkaiici.html

TS:   console.error("err")
来源：http://dali.0kj1m.cn/Article/details/gtvtausvoo.html

Java: System.err.println("err")
来源：http://dali.chenjidiqi.icu/Article/details/gtmfxkctbl.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtccrqdqqk.html

Ruby: warn "err"
来源：http://dali.pycfn.com/Article/details/gtunrezzaw.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.andypj.xyz/Article/details/gtnrbksqbe.html

[M07] 判断是否为主入口
来源：http://dali.pycfn.com/Article/details/gtgswjynfw.html

Py:   if __name__ == "__main__":
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtavvkxhct.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.daxiang520.top/Article/details/gtzoztngky.html

JS:   require.main === module
来源：http://dali.shuidangran.top/Article/details/gtsncdsxcb.html

TS:   require.main === module
来源：http://dali.ivvv.top/Article/details/gtuiggtocy.html

Java: public static void main(String[] args)
来源：http://dali.daxiang520.top/Article/details/gtxnwtpfxg.html

Go:   func main()
来源：http://dali.yj20258.top/Article/details/gtonzbnpee.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.wangshuangyany.cn/Article/details/gtwqastals.html

C#:   static void Main(string[] args)
来源：http://dali.xinyue.icu/Article/details/gtmgvdtuzx.html

[M08] 获取系统与运行时信息
来源：http://dali.sysykeji.top/Article/details/gtmzijhgje.html

Py:   platform.system();  platform.python_version()
来源：http://dali.jiagoushi.top/Article/details/gtmwnvtssb.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.pycfn.com/Article/details/gtpsvzsfhp.html

JS:   process.platform;  process.version
来源：http://dali.nanxuanxn.top/Article/details/gtkgruhipd.html

TS:   process.platform;  process.version
来源：http://dali.yj202588.top/Article/details/gtmaimednk.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.aibaodan.cn/Article/details/gtexkytsoj.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.mhx1999.top/Article/details/gtginifswq.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.guowangkeji.top/Article/details/gtrapdxjmb.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.mhx1999.top/Article/details/gtrzxblprn.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtvwfrgzxq.html

N. 数据结构与算法
来源：http://dali.nanxinkj.top/Article/details/gtczvfring.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gttwnusmed.html

[N01] 二分查找（有序数组）
来源：http://dali.ehwqpu.com/Article/details/gtlvfcdvoj.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.redwolf501.top/Article/details/gtbdjyakhl.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.havefunace.top/Article/details/gtzunzzzmc.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.ppjwa.cn/Article/details/gtillupugy.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.dianchejie.cn/Article/details/gtkmkimygv.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.hywenlv.cn/Article/details/gtwkrqzlgr.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.tianlin.xyz/Article/details/gtnvpdkcqq.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.jiagoushi.top/Article/details/gtcmskirix.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.daxiang520.top/Article/details/gtdwbpyaqi.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.c1oappe.top/Article/details/gtwnyhyogo.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuzdlvcta.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.hnqzz.top/Article/details/gtgavhfmtp.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yj202588.top/Article/details/gtidjgkrmw.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.cqqwz.cn/Article/details/gtbxobygpu.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.redwolf501.top/Article/details/gtrmrwxjmh.html

Go:   slices.Sort(arr)
来源：http://dali.zhongyouzk.top/Article/details/gteohkvayi.html

Ruby: arr.sort
来源：http://dali.shuidangran.top/Article/details/gtogdilkrj.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhixingplan.top/Article/details/gtuddcsyth.html

[N03] 快速排序（分治示例）
来源：http://dali.feifeiyinyue.top/Article/details/gtdvvepqkt.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.shuidangran.top/Article/details/gtqlocdoan.html

PHP:  // 递归实现，或用 usort
来源：http://dali.smart0.xyz/Article/details/gtrpqjrnza.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jlsjyb.cn/Article/details/gtkciruhhy.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yuanzhike.top/Article/details/gtmnizxyum.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.xziqi.cn/Article/details/gtpajgxfke.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.jiagoushi.top/Article/details/gtpoanttup.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.xziqi.cn/Article/details/gtgxspidja.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.bjfxy.top/Article/details/gtyqlsulqc.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gtzczmdokc.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.nanxuanxn.top/Article/details/gtaffyrecy.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zdqjudy.top/Article/details/gtftncmsdm.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.9152youxi.cn/Article/details/gtaqdxofwm.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yongpay.top/Article/details/gtvnkfzugp.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.jinqigufen.top/Article/details/gtvvvquwxz.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.chenjidiqi.icu/Article/details/gtiiduyktj.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.vqdsnc.cn/Article/details/gthlvwhltl.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.svipenyu.cn/Article/details/gtkniompjh.html

[N05] 最大公约数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuzhjjfvj.html

Py:   math.gcd(a, b)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjxxoqeno.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.daxiang520.top/Article/details/gtakphronu.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.nwbrower.top/Article/details/gtrobxfrfh.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhoulong.xyz/Article/details/gtenxbluxt.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.yongpay.top/Article/details/gtnrslfiib.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zycfv.cn/Article/details/gtemtsizyy.html

Ruby: a.gcd(b)
来源：http://dali.jiagoushi.top/Article/details/gtutslmlif.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.yangfankeji.com/Article/details/gtcnshnbvb.html

[N06] 判断回文字符串
来源：http://dali.gaohongyu789.top/Article/details/gtwetmcksw.html

Py:   s == s[::-1]
来源：http://dali.zdqjudy.top/Article/details/gtytzdxxxx.html

PHP:  $s === strrev($s);
来源：http://dali.guowangkeji.top/Article/details/gtejbnmnxk.html

JS:   s === [...s].reverse().join("")
来源：http://dali.xylfe.cn/Article/details/gtfwtvyrdd.html

TS:   s === [...s].reverse().join("")
来源：http://dali.0kj1m.cn/Article/details/gtnccmnueh.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.sysykeji.top/Article/details/gtwyijhqsr.html

Go:   // 双指针从两端比较
来源：http://dali.gotoacloud.top/Article/details/gtwehppyho.html

Ruby: s == s.reverse
来源：http://dali.hnxiangtu.top/Article/details/gttefjdewq.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.ybcxt.top/Article/details/gtnygniagy.html

[N07] 两数之和（返回下标）
来源：http://dali.gzhubu.top/Article/details/gthohvfwwx.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.fzhhl.top/Article/details/gtcqttbfgw.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.hfpthk.cn/Article/details/gtpaecddcb.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.yj202588.top/Article/details/gtcjnhrqjt.html

TS:   // 手写 Map<string, number>
来源：http://dali.andypj.xyz/Article/details/gtaiminiwu.html

Java: // 手写 HashMap
来源：http://dali.yj202588.top/Article/details/gtbzhsnguo.html

Go:   // 手写 map[int]int
来源：http://dali.zhiwuduotai.top/Article/details/gtlrwgblbn.html

Ruby: // 手写 Hash
来源：http://dali.feifeiyinyue.top/Article/details/gtclfqcsgi.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.cqqwz.cn/Article/details/gtjggepcxx.html

[N08] 生成全排列
来源：http://dali.chenjidiqi.icu/Article/details/gteimotduv.html

Py:   itertools.permutations(arr)
来源：http://dali.bjfxy.top/Article/details/gtfwbavqeq.html

PHP:  // 手写递归交换
来源：http://dali.yuxming.cn/Article/details/gtfuvsccvx.html

JS:   // 手写回溯递归
来源：http://dali.hongshengwenyu.top/Article/details/gtxfqkcvch.html

TS:   // 手写回溯递归
来源：http://dali.316326.xyz/Article/details/gtsqkpabug.html

Java: // 手写回溯递归
来源：http://dali.xuanzx.com/Article/details/gtcovngodn.html

Go:   // 手写回溯递归
来源：http://dali.sweek.top/Article/details/gtyxyiafey.html

Ruby: arr.permutation.to_a
来源：http://dali.xinyue.icu/Article/details/gthzrtblhb.html

C#:   // 手写回溯递归
来源：http://dali.jyoumei.cn/Article/details/gtrprjnjgt.html

[N09] 栈与队列
来源：http://dali.chenlongwang.top/Article/details/gtssyrxirp.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.jlsjyb.cn/Article/details/gtzcvbtnww.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.bjfxy.top/Article/details/gtpntflnus.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.ydzc1.top/Article/details/gtjhauiqly.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gtlwykdsjh.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.sweek.top/Article/details/gtdpotktyy.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.shanyushiyangkeji.top/Article/details/gtedsjocnl.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.chenzaomai.com/Article/details/gtgoqpnfdm.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.birdmap.top/Article/details/gthmpdfhft.html

[N10] 链表节点定义
来源：http://dali.sufxvd.cn/Article/details/gtsqubpddb.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.havefunace.top/Article/details/gtqsvyvulr.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.daria6918.cn/Article/details/gtrsrojsme.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zycfv.cn/Article/details/gtgqlevnsm.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.pengpengdd.cyou/Article/details/gtlmopukbf.html

Java: class Node { int v; Node next; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtghxwuymf.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.gotoacloud.top/Article/details/gtnvjfbwnh.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhixingplan.top/Article/details/gtxprrcmld.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.9152youxi.cn/Article/details/gtjdalqydo.html

[N11] 二叉树中序遍历
来源：http://dali.guowangkeji.top/Article/details/gtyrphhzab.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.sufxvd.cn/Article/details/gtzafmtalm.html

PHP:  // 手写递归函数
来源：http://dali.zhiwuduotai.top/Article/details/gtyiwlnidf.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.guowangkeji.top/Article/details/gtfexbstoy.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.iojbl.cn/Article/details/gtqdwbxfqk.html

Java: // 手写递归
来源：http://dali.jiagoushi.top/Article/details/gtdzdpulre.html

Go:   // 手写递归
来源：http://dali.xuanzx.com/Article/details/gtujbdbynk.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.fzhhl.top/Article/details/gtdkxmbwrk.html

C#:   // 手写递归
来源：http://dali.yangfankeji.com/Article/details/gtqfmmuqgm.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.xziqi.cn/Article/details/gtbsjgrjxp.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.jlsjyb.cn/Article/details/gttsmwljsd.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.yj20258888.top/Article/details/gtsvlspuqc.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.wangdashe.top/Article/details/gtukdppaun.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.ybcxt.top/Article/details/gtrjwuyowz.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.hammf.cn/Article/details/gtzgjjrdxg.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.hywenlv.cn/Article/details/gtuazwsdcp.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhengqikj.top/Article/details/gtoxxwwdbs.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjseujtdz.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtqdjzytec.html

O. 并发与异步
来源：http://dali.xziqi.cn/Article/details/gtvlubnici.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtqzeoylor.html

[O01] 启动一个线程
来源：http://dali.jinqigfzy.top/Article/details/gtfozekfvp.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.hnxiangtu.top/Article/details/gtrowutxpy.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.xinyue.icu/Article/details/gtsnjgtmli.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.hysaishi.cn/Article/details/gtrtbpfvxx.html

TS:   // 同 JS
来源：http://dali.chenlongwang.top/Article/details/gtlsshwdrt.html

Java: new Thread(() -> f()).start()
来源：http://dali.ydzc1.top/Article/details/gtqsfmiesy.html

Go:   go f()
来源：http://dali.ivvv.top/Article/details/gtgzyffjpk.html

Ruby: Thread.new { f }
来源：http://dali.jyoumei.cn/Article/details/gtxkcsddlv.html

C#:   Task.Run(() => F());
来源：http://dali.quarkkingdee.top/Article/details/gtuanlyfpg.html

[O02] 使用线程池
来源：http://dali.sufxvd.cn/Article/details/gtooulzjve.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.yonumen.top/Article/details/gtkzcucswb.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.cashguo.top/Article/details/gtzouawrvp.html

JS:   // worker_threads 线程池
来源：http://dali.gotoacloud.top/Article/details/gtppbrhnwn.html

TS:   // worker_threads 线程池
来源：http://dali.xylfe.cn/Article/details/gtunyuulqb.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.xuanzx.com/Article/details/gtoceypryx.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjxqnxrpx.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zdqjudy.top/Article/details/gtedkiehke.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.aizwys.cn/Article/details/gtcgenwrru.html

[O03] 加锁保护共享数据
来源：http://dali.yanxiufei.cn/Article/details/gtiivqweip.html

Py:   with lock: shared += 1
来源：http://dali.haohaochexian.top/Article/details/gtfbaxwqux.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.cheryme.top/Article/details/gtllagmphh.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.hammf.cn/Article/details/gtxkjvvoui.html

TS:   // 同 JS
来源：http://dali.andypj.xyz/Article/details/gtvholjkhk.html

Java: synchronized (this) { shared++; }
来源：http://dali.9152youxi.cn/Article/details/gtwhvwahox.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.birdmap.top/Article/details/gtiuboskhe.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.birdmap.top/Article/details/gtutonfzhz.html

C#:   lock (gate) { shared++; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtpmqrvhgs.html

[O04] 定义异步函数并等待
来源：http://dali.yj202588.top/Article/details/gtwvjjfcle.html

Py:   async def f():⏎    await g()
来源：http://dali.jinqigfzy.top/Article/details/gtvnwgjazu.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.xuetiantiany.cn/Article/details/gtmkfzjoqu.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gtxclmtnpk.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.tianlin.xyz/Article/details/gtwwiutywb.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.jiagoushi.top/Article/details/gtetcqiqas.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.snrcjt.cn/Article/details/gtvqaqgdiz.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.gaohongyu789.top/Article/details/gtwhciyows.html

C#:   async Task F() { await G(); }
来源：http://dali.fengsongda.top/Article/details/gtdrijgfbf.html

[O05] 并发执行并等待全部完成
来源：http://dali.jinqigufen.top/Article/details/gtvvdjdnnr.html

Py:   asyncio.gather(*tasks)
来源：http://dali.yj20258888.top/Article/details/gthzxupcvf.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.jianghu66.top/Article/details/gtmpwqotai.html

JS:   await Promise.all(tasks)
来源：http://dali.hongshengwenyu.top/Article/details/gtogxcszdt.html

TS:   await Promise.all(tasks)
来源：http://dali.tanke756.top/Article/details/gtcfbmeojh.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.guannengcc.top/Article/details/gtuczonxca.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.gaohongyu789.top/Article/details/gtvbauhqbf.html

Ruby: threads.map(&:join)
来源：http://dali.jinqigfzy.top/Article/details/gttnwefayq.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.chenzaomai.com/Article/details/gtdldwomdj.html

[O06] 使用进程池
来源：http://dali.sysykeji.top/Article/details/gthkchfazx.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gtzwyjryhf.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.chenzaomai.com/Article/details/gtiqsdvagl.html

JS:   // child_process / cluster 模块
来源：http://dali.fzhhl.top/Article/details/gthuvkiebp.html

TS:   // child_process / cluster 模块
来源：http://dali.sxryk.cn/Article/details/gthwwnogyy.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.guowangkeji.top/Article/details/gthyawizne.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.chenlongwang.top/Article/details/gtmfaritdd.html

Ruby: // fork 块
来源：http://dali.nanxinkj.top/Article/details/gtyeyjgbaf.html

C#:   Parallel.For
来源：http://dali.meibo888.top/Article/details/gthsymzjgr.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtabjsyelz.html

P. 常用工具函数
来源：http://dali.yvedp.cn/Article/details/gtqtrqyokp.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtweiqwpdf.html

[P01] 生成 UUID
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthxryjeai.html

Py:   str(uuid.uuid4())
来源：http://dali.chenzaomai.com/Article/details/gttfpqowan.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.chenzaomai.com/Article/details/gtfqubvrrj.html

JS:   crypto.randomUUID()
来源：http://dali.zhongyouzk.top/Article/details/gtcwmkkzdn.html

TS:   crypto.randomUUID()
来源：http://dali.gogol.net.cn/Article/details/gtdwwuulwh.html

Java: UUID.randomUUID().toString()
来源：http://dali.c1oappe.top/Article/details/gttokcsqdu.html

Go:   // 用 github.com/google/uuid
来源：http://dali.sweek.top/Article/details/gtvuhxgtpw.html

Ruby: SecureRandom.uuid
来源：http://dali.cucudq.cn/Article/details/gtmozynwwo.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.guowangkeji.top/Article/details/gtobocvexa.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhixingplan.top/Article/details/gtlpdzwnuz.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.yuxming.cn/Article/details/gtlauyjbgw.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.shuidangran.top/Article/details/gtqchzwplz.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.nwbrower.top/Article/details/gtvpmbvprk.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhixingplan.top/Article/details/gtbhfdnigd.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.xziqi.cn/Article/details/gtybkhcvqc.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.yongpay.top/Article/details/gtglquktuf.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.jqgfzy.top/Article/details/gtubznknme.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.pycfn.com/Article/details/gtcvbwzugl.html

[P03] 生成短随机字符串
来源：http://dali.smart0.xyz/Article/details/gtyywqcuks.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.quarkkingdee.top/Article/details/gtqztfugti.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.yj202588.top/Article/details/gtoylvjzgc.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.chenlongwang.top/Article/details/gtcbmphxcr.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.tian-w.cn/Article/details/gtqgittuho.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.ybcxt.top/Article/details/gtlcayblhe.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.tanke756.top/Article/details/gtaugljdgc.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.aibaodan.cn/Article/details/gtmqvmpsdm.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.bjfxy.top/Article/details/gtevagaows.html

[P04] 求长度
来源：http://dali.yueranfly.top/Article/details/gtpnelgzgg.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.jqgfzy.top/Article/details/gtnstrsnta.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.ehwqpu.com/Article/details/gtwjsynbpg.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jqgfzy.top/Article/details/gtmmoqcqke.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.tianlin.xyz/Article/details/gttqnwqipm.html

Java: list.size();  map.size();  s.length()
来源：http://dali.nanxinkj.top/Article/details/gtcovdhahz.html

Go:   len(arr);  len(m)
来源：http://dali.fzhhl.top/Article/details/gtpjrfdrnt.html

Ruby: x.length;  x.size
来源：http://dali.fzhhl.top/Article/details/gttpwslygc.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.yj20258.top/Article/details/gtwuywpszx.html

[P05] 判断两个对象内容是否相等
来源：http://dali.yangfankeji.com/Article/details/gttemauato.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.sweek.top/Article/details/gtickdhlqg.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.jianghu66.top/Article/details/gthuvcsqlb.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.birdmap.top/Article/details/gtkxvnlzzq.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.wangshuangyany.cn/Article/details/gtkhfyrigg.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.hongshengwenyu.top/Article/details/gtetowtplm.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnyeshlrn.html

Ruby: a == b
来源：http://dali.jinqigfzy.top/Article/details/gtssqyyvsw.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.daria6918.cn/Article/details/gtljfxmmru.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.jinghuilouyu.cn/Article/details/gtzssjrysz.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.nwbrower.top/Article/details/gtbqicvmzt.html

PHP:  if (empty($x)) {}
来源：http://dali.jqgfzy.top/Article/details/gtypjoxsyv.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.yj20258888.top/Article/details/gtuwutvhlr.html

TS:   if (x == null) {}
来源：http://dali.dashuyun.cn/Article/details/gtbwnqzrhu.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.jianghu66.top/Article/details/gtckmhzmeb.html

Go:   if x == nil {}
来源：http://dali.316326.xyz/Article/details/gteaybijyf.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.yj20258888.top/Article/details/gtgwcvvrvb.html

C#:   if (x is null) {}
来源：http://dali.jlsjyb.cn/Article/details/gtdopiaaqb.html

[P07] 防抖与节流
来源：http://dali.jinghuilouyu.cn/Article/details/gtcgfrtyqj.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.daxiang520.top/Article/details/gtbzgurpjv.html

PHP:  // 手写时间戳比较
来源：http://dali.yueranfly.top/Article/details/gtjcmjwtlh.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.tanke756.top/Article/details/gtrutkyeln.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.sysykeji.top/Article/details/gtiwzhmwug.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.shangyingyoupin.top/Article/details/gtkiygecep.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.yj20258.top/Article/details/gtepmjguuy.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.ivvv.top/Article/details/gtmyufhlvz.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.ehwqpu.com/Article/details/gtycretsyz.html

[P08] 处理浮点精度问题
来源：http://dali.cdnleiting.top/Article/details/gtxeebrxdn.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.birdmap.top/Article/details/gtwtkumfih.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhoulong.xyz/Article/details/gtayyemnpt.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.aibaodan.cn/Article/details/gtczkhjxjp.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.mhx1999.top/Article/details/gtnpzjghoo.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.nanxuanxn.top/Article/details/gtrljetuzd.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.0kj1m.cn/Article/details/gtsknrffiq.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.guannengcc.top/Article/details/gtbakztqwc.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.iojbl.cn/Article/details/gtmphkymgx.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtdnzhgpan.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.snrcjt.cn/Article/details/gtklgriejw.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtwivfdqhv.html

[Q01] 创建表
来源：http://dali.yangfankeji.com/Article/details/gtxzenzzpx.html

CREATE TABLE users (
来源：http://dali.quarkkingdee.top/Article/details/gtcyigcznf.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.shangyingyoupin.top/Article/details/gtgzheiiet.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhengqikj.top/Article/details/gtgxhufjlj.html

email VARCHAR(100) UNIQUE,
来源：http://dali.birdmap.top/Article/details/gthwwnytpj.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.bjfxy.top/Article/details/gtkmmbsduc.html

);
来源：http://dali.birdmap.top/Article/details/gtlgwgftph.html

[Q02] 创建带外键的表
来源：http://dali.yueranfly.top/Article/details/gtslyghlio.html

CREATE TABLE orders (
来源：http://dali.guannengcc.top/Article/details/gtpiwiyeyq.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.chenjidiqi.icu/Article/details/gthnpjumbo.html

user_id INT NOT NULL,
来源：http://dali.hongshengwenyu.top/Article/details/gtcbzyjogn.html

amount DECIMAL(10, 2),
来源：http://dali.svipenyu.cn/Article/details/gtfafskeyd.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.hnxiangtu.top/Article/details/gtdoukjiil.html

);
来源：http://dali.jinqigfzy.top/Article/details/gtwwsrgxgu.html

[Q03] 增加列
来源：http://dali.fzhhl.top/Article/details/gtkrmcelal.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.guowangkeji.top/Article/details/gtixjnjtzz.html

[Q04] 修改列类型
来源：http://dali.jinqigfzy.top/Article/details/gtwtltbosj.html


<!-- 参考信息 -->