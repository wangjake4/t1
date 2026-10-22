代发 wailian999

C#:   Directory.GetCurrentDirectory()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkgnactfb.html

[M05] 设置退出码
来源：http://dali.c1oappe.top/Article/details/gtrbnkidml.html

Py:   sys.exit(1)
来源：http://dali.sysykeji.top/Article/details/gtvmkbrfyn.html

PHP:  exit(1);
来源：http://dali.haohaochexian.top/Article/details/gtjgfancgz.html

JS:   process.exit(1)
来源：http://dali.zhongyouzk.top/Article/details/gtolwjkwfd.html

TS:   process.exit(1)
来源：http://dali.xuanzx.com/Article/details/gthzsajgqu.html

Java: System.exit(1)
来源：http://dali.cheryme.top/Article/details/gttqcbcebj.html

Go:   os.Exit(1)
来源：http://dali.chenlongwang.top/Article/details/gtanaukwlh.html

Ruby: exit 1
来源：http://dali.xuanzx.com/Article/details/gtdhbqufgq.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.yongpay.top/Article/details/gtuzonxeks.html

[M06] 向标准错误输出
来源：http://dali.zhixingplan.top/Article/details/gtoefrhkkh.html

Py:   print("err", file=sys.stderr)
来源：http://dali.havefunace.top/Article/details/gtyldbhjjq.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.dashuyun.cn/Article/details/gtyblugxgr.html

JS:   console.error("err")
来源：http://dali.tianlin.xyz/Article/details/gtzrvtlhts.html

TS:   console.error("err")
来源：http://dali.nanxuanxn.top/Article/details/gtayjtpbqu.html

Java: System.err.println("err")
来源：http://dali.ivvv.top/Article/details/gthivopwif.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.xziqi.cn/Article/details/gtswtgqabt.html

Ruby: warn "err"
来源：http://dali.ivvv.top/Article/details/gtgfyebufo.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.ppjwa.cn/Article/details/gtrcbmfkcd.html

[M07] 判断是否为主入口
来源：http://dali.zhixingplan.top/Article/details/gtxcepvwyh.html

Py:   if __name__ == "__main__":
来源：http://dali.jyoumei.cn/Article/details/gtdlewqdnh.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdmxwwavo.html

JS:   require.main === module
来源：http://dali.kuanghao11.cn/Article/details/gtovsnzjfk.html

TS:   require.main === module
来源：http://dali.hywenlv.cn/Article/details/gthtnvmnuy.html

Java: public static void main(String[] args)
来源：http://dali.guowangkeji.top/Article/details/gtgmywqhwq.html

Go:   func main()
来源：http://dali.ivvv.top/Article/details/gtkrdfflxu.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.jiagoushi.top/Article/details/gthoyihogm.html

C#:   static void Main(string[] args)
来源：http://dali.zhongyouzk.top/Article/details/gthyckundv.html

[M08] 获取系统与运行时信息
来源：http://dali.zhixingplan.top/Article/details/gtgejpvofk.html

Py:   platform.system();  platform.python_version()
来源：http://dali.yuanzhike.top/Article/details/gtdafkvwub.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.jinqigfzy.top/Article/details/gtmqucoldz.html

JS:   process.platform;  process.version
来源：http://dali.ydzc1.top/Article/details/gtyitvwnlh.html

TS:   process.platform;  process.version
来源：http://dali.andypj.xyz/Article/details/gtnrbednrc.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.cashguo.top/Article/details/gtxlgnzgjl.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.sufxvd.cn/Article/details/gtinqifkzp.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.yongpay.top/Article/details/gttyrxadww.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.smart0.xyz/Article/details/gtxrtitdyc.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtdyghkjek.html

N. 数据结构与算法
来源：http://dali.tianlin.xyz/Article/details/gtjhtawkyi.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtxgtvhoqt.html

[N01] 二分查找（有序数组）
来源：http://dali.yueranfly.top/Article/details/gtcowrdhsf.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.aizwys.cn/Article/details/gtiltplfjc.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.nanxinkj.top/Article/details/gtybupxdgq.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.sweek.top/Article/details/gtomjegmrx.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmxelpnvt.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.yj20258888.top/Article/details/gtsvrozcpa.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.ivvv.top/Article/details/gtfhlhpmqh.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.dianchejie.cn/Article/details/gtblstievk.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.shzxlz.cn/Article/details/gtafqjqfwf.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.xuanzx.com/Article/details/gtkrcaiitc.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.ehwqpu.com/Article/details/gtzcspwwtp.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.jqgufenzy.top/Article/details/gtscpxvmpt.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.vqdsnc.cn/Article/details/gtzvtmcjzp.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.xuetiantiany.cn/Article/details/gtrgnavhyy.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.cdnleiting.top/Article/details/gtgsivpdjp.html

Go:   slices.Sort(arr)
来源：http://dali.yj202588.top/Article/details/gtfnchwtqw.html

Ruby: arr.sort
来源：http://dali.cdnleiting.top/Article/details/gtaplgbvak.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.guannengcc.top/Article/details/gtkvvikjui.html

[N03] 快速排序（分治示例）
来源：http://dali.tian-w.cn/Article/details/gtrcspyvun.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkwmkvtlb.html

PHP:  // 递归实现，或用 usort
来源：http://dali.tianlin.xyz/Article/details/gtqplrubjl.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.nwbrower.top/Article/details/gtwizhqofl.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.gotoacloud.top/Article/details/gtqyfgryip.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.ppjwa.cn/Article/details/gtplfsmaat.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpfjqudyc.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.cucudq.cn/Article/details/gthincnnjf.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.yj20258888.top/Article/details/gtesfvcedd.html

[N04] 斐波那契数列
来源：http://dali.guowangkeji.top/Article/details/gtzajkwpza.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.hywenlv.cn/Article/details/gtbojcbhap.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.bjfxy.top/Article/details/gtxutncbvr.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.fengsongda.top/Article/details/gtonacqgdb.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.gzhubu.top/Article/details/gtvssdlvio.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.jianghu66.top/Article/details/gtzbzoxchu.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.snrcjt.cn/Article/details/gtdffghbyq.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.chenzaomai.com/Article/details/gtoqxviund.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.9152youxi.cn/Article/details/gtawmlewud.html

[N05] 最大公约数
来源：http://dali.gogol.net.cn/Article/details/gttklodcby.html

Py:   math.gcd(a, b)
来源：http://dali.xuanzx.com/Article/details/gtoyqtkmyo.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.cqqwz.cn/Article/details/gtgwxryvqb.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.kuanghao11.cn/Article/details/gtpdvnrkjj.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.cashguo.top/Article/details/gttsojcljz.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.nwbrower.top/Article/details/gtgovovema.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.dashuyun.cn/Article/details/gtdvscifrf.html

Ruby: a.gcd(b)
来源：http://dali.guannengcc.top/Article/details/gtcerjpljx.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gtfhbkxrxq.html

[N06] 判断回文字符串
来源：http://dali.jiagoushi.top/Article/details/gtjzeiwfme.html

Py:   s == s[::-1]
来源：http://dali.meibo888.top/Article/details/gtuplupwwy.html

PHP:  $s === strrev($s);
来源：http://dali.jinghuilouyu.cn/Article/details/gtiyogyojm.html

JS:   s === [...s].reverse().join("")
来源：http://dali.kuanghao11.cn/Article/details/gtrykzxjkg.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhixingplan.top/Article/details/gtbzlggmae.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.meibo888.top/Article/details/gthcdrrybe.html

Go:   // 双指针从两端比较
来源：http://dali.sufxvd.cn/Article/details/gttofjuccf.html

Ruby: s == s.reverse
来源：http://dali.gotoacloud.top/Article/details/gtbjgczmwu.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.fengsongda.top/Article/details/gtqzeobqib.html

[N07] 两数之和（返回下标）
来源：http://dali.0kj1m.cn/Article/details/gtjmqmyead.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.shanyushiyangkeji.top/Article/details/gtakwnplgp.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.jianghu66.top/Article/details/gtcetjpmqy.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.yuanzhike.top/Article/details/gtrcsnobol.html

TS:   // 手写 Map<string, number>
来源：http://dali.feifeiyinyue.top/Article/details/gtcqxqmkdk.html

Java: // 手写 HashMap
来源：http://dali.snrcjt.cn/Article/details/gtusxxpemu.html

Go:   // 手写 map[int]int
来源：http://dali.feifeiyinyue.top/Article/details/gtsiqatccg.html

Ruby: // 手写 Hash
来源：http://dali.jinqigfzy.top/Article/details/gttgqlywvp.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.havefunace.top/Article/details/gtdpcnjkdq.html

[N08] 生成全排列
来源：http://dali.smart0.xyz/Article/details/gtrbyjswfc.html

Py:   itertools.permutations(arr)
来源：http://dali.ybcxt.top/Article/details/gtkzmjsbbe.html

PHP:  // 手写递归交换
来源：http://dali.jinqigufen.top/Article/details/gtxmflyqen.html

JS:   // 手写回溯递归
来源：http://dali.yj20258888.top/Article/details/gthahzpuzg.html

TS:   // 手写回溯递归
来源：http://dali.fengsongda.top/Article/details/gtcksisogi.html

Java: // 手写回溯递归
来源：http://dali.haohaochexian.top/Article/details/gtihntnbzt.html

Go:   // 手写回溯递归
来源：http://dali.yvedp.cn/Article/details/gtowygkyiq.html

Ruby: arr.permutation.to_a
来源：http://dali.yangfankeji.com/Article/details/gtzrqbyept.html

C#:   // 手写回溯递归
来源：http://dali.9152youxi.cn/Article/details/gtgohgukil.html

[N09] 栈与队列
来源：http://dali.yj202588.top/Article/details/gtdmdfyasd.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.xinyue.icu/Article/details/gtwufnzijo.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.nanxinkj.top/Article/details/gtlfgamupp.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.smart0.xyz/Article/details/gtkmadmvsu.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.hongshengwenyu.top/Article/details/gtfjppctbp.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.ppjwa.cn/Article/details/gtrwgzcagj.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.yangfankeji.com/Article/details/gtslrtnbnz.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.gzhubu.top/Article/details/gterohrfya.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.hongshengwenyu.top/Article/details/gtnplbjvav.html

[N10] 链表节点定义
来源：http://dali.ivvv.top/Article/details/gtjxtlbpfz.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.jqgufenzy.top/Article/details/gtcalxzjca.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.xuetiantiany.cn/Article/details/gtlbikyivy.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.0kj1m.cn/Article/details/gtxunbrbej.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.hfpthk.cn/Article/details/gtcuvgkwnt.html

Java: class Node { int v; Node next; }
来源：http://dali.yangfankeji.com/Article/details/gtlvoqrofy.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.fzhhl.top/Article/details/gtcrztzgze.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.hnqzz.top/Article/details/gtvlbfiqor.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.cashguo.top/Article/details/gtiwfytjlt.html

[N11] 二叉树中序遍历
来源：http://dali.zycfv.cn/Article/details/gtostoqezl.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.dashuyun.cn/Article/details/gtiucsqqjp.html

PHP:  // 手写递归函数
来源：http://dali.xuetiantiany.cn/Article/details/gtgvkiorvd.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.hongshengwenyu.top/Article/details/gtmwofsnog.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.andypj.xyz/Article/details/gtoyuhjytt.html

Java: // 手写递归
来源：http://dali.yuanzhike.top/Article/details/gtxknsydao.html

Go:   // 手写递归
来源：http://dali.wangshuangyany.cn/Article/details/gtafkfvdlc.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.snrcjt.cn/Article/details/gtioumlgfj.html

C#:   // 手写递归
来源：http://dali.kuanghao11.cn/Article/details/gtekiqoipf.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtocykdlxa.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.gzhubu.top/Article/details/gtmrzvamgk.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtztxkdnfv.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.xziqi.cn/Article/details/gtywxdbgdf.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.svipenyu.cn/Article/details/gtfkwaicya.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.sufxvd.cn/Article/details/gticijtkgs.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.feifeiyinyue.top/Article/details/gtourttmdm.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.316326.xyz/Article/details/gtyeycryzw.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.sweek.top/Article/details/gtmefykeru.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtrhnnwval.html

O. 并发与异步
来源：http://dali.meibo888.top/Article/details/gtujopuybk.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtpqowowcl.html

[O01] 启动一个线程
来源：http://dali.xinyue.icu/Article/details/gtqmfrdlwg.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.cheryme.top/Article/details/gtenlbsbzz.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.hnqzz.top/Article/details/gtjkptwibu.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.jyoumei.cn/Article/details/gtfqczrggs.html

TS:   // 同 JS
来源：http://dali.yvedp.cn/Article/details/gthewpcfql.html

Java: new Thread(() -> f()).start()
来源：http://dali.snrcjt.cn/Article/details/gtajocpsce.html

Go:   go f()
来源：http://dali.xuetiantiany.cn/Article/details/gtrrshplml.html

Ruby: Thread.new { f }
来源：http://dali.zhaomingkeji.xyz/Article/details/gthdpayfsd.html

C#:   Task.Run(() => F());
来源：http://dali.316326.xyz/Article/details/gtatuxfgtp.html

[O02] 使用线程池
来源：http://dali.9152youxi.cn/Article/details/gtfthtdavo.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.cheryme.top/Article/details/gtxlrqkicp.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.haohaochexian.top/Article/details/gttcvnqfml.html

JS:   // worker_threads 线程池
来源：http://dali.sysykeji.top/Article/details/gthfnvznai.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gtdckipiei.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.nwbrower.top/Article/details/gtoyzqbufl.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.ydzc1.top/Article/details/gtiqpejjjv.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.daxiang520.top/Article/details/gtajsbowdq.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.yuanzhike.top/Article/details/gtadygjnzp.html

[O03] 加锁保护共享数据
来源：http://dali.meibo888.top/Article/details/gttulzpyzk.html

Py:   with lock: shared += 1
来源：http://dali.feifeiyinyue.top/Article/details/gtigzvwtpe.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.c1oappe.top/Article/details/gtfryabsib.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.wangshuangyany.cn/Article/details/gtiomwmrdq.html

TS:   // 同 JS
来源：http://dali.jiagoushi.top/Article/details/gtergtyndh.html

Java: synchronized (this) { shared++; }
来源：http://dali.mhx1999.top/Article/details/gtwydrqoyx.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbtmmpwep.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwsamwjyv.html

C#:   lock (gate) { shared++; }
来源：http://dali.pycfn.com/Article/details/gtsliobzbc.html

[O04] 定义异步函数并等待
来源：http://dali.zhongyouzk.top/Article/details/gtsxdvxhdv.html

Py:   async def f():⏎    await g()
来源：http://dali.havefunace.top/Article/details/gtmybgenvr.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.hongshengwenyu.top/Article/details/gtuudgcspg.html

JS:   async function f() { await g(); }
来源：http://dali.yangfankeji.com/Article/details/gthepkqekl.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.jinqigufen.top/Article/details/gthlimjdcz.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtynfrvuab.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhoulong.xyz/Article/details/gtkvvipyzk.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.nwbrower.top/Article/details/gtjfrcqnxc.html

C#:   async Task F() { await G(); }
来源：http://dali.zhoulong.xyz/Article/details/gtztctzihw.html

[O05] 并发执行并等待全部完成
来源：http://dali.vqdsnc.cn/Article/details/gtqmkdlckl.html

Py:   asyncio.gather(*tasks)
来源：http://dali.jianghu66.top/Article/details/gtpcsysyvu.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.nanxuanxn.top/Article/details/gtlqljcumv.html

JS:   await Promise.all(tasks)
来源：http://dali.jinyuanbaomall.cn/Article/details/gteqwqjpcg.html

TS:   await Promise.all(tasks)
来源：http://dali.xuetiantiany.cn/Article/details/gtgsbeswwp.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.jinqigufen.top/Article/details/gtbdgvshnd.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.316326.xyz/Article/details/gtsqqtvnrf.html

Ruby: threads.map(&:join)
来源：http://dali.yj202588.top/Article/details/gtjfxwejlp.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.nanxuanxn.top/Article/details/gtmhgumzyz.html

[O06] 使用进程池
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtslhofspk.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.andypj.xyz/Article/details/gtlxxhdtjb.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.guowangkeji.top/Article/details/gtffegsuhv.html

JS:   // child_process / cluster 模块
来源：http://dali.havefunace.top/Article/details/gtzqbyiukm.html

TS:   // child_process / cluster 模块
来源：http://dali.yuanzhike.top/Article/details/gtwguvzajh.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.daria6918.cn/Article/details/gtseusvvnv.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.hfpthk.cn/Article/details/gtbhvrwygf.html

Ruby: // fork 块
来源：http://dali.jqgufenzy.top/Article/details/gtcnbuqnza.html

C#:   Parallel.For
来源：http://dali.svipenyu.cn/Article/details/gtjbczhcjs.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtdkftgshs.html

P. 常用工具函数
来源：http://dali.yuanzhike.top/Article/details/gtbwinrmkw.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtpbpgsgvh.html

[P01] 生成 UUID
来源：http://dali.ybcxt.top/Article/details/gthlwuwzqj.html

Py:   str(uuid.uuid4())
来源：http://dali.kuanghao11.cn/Article/details/gtwwkddugw.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.hnqzz.top/Article/details/gtnzksntyy.html

JS:   crypto.randomUUID()
来源：http://dali.yj202588.top/Article/details/gtfjrgvwyp.html

TS:   crypto.randomUUID()
来源：http://dali.zhixingplan.top/Article/details/gtezanhgcd.html

Java: UUID.randomUUID().toString()
来源：http://dali.yueranfly.top/Article/details/gtduxewmrh.html

Go:   // 用 github.com/google/uuid
来源：http://dali.mhx1999.top/Article/details/gtnenfkufk.html

Ruby: SecureRandom.uuid
来源：http://dali.quarkkingdee.top/Article/details/gtifyrgchp.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.guowangkeji.top/Article/details/gtlnndklno.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gtooojjuqq.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.bjfxy.top/Article/details/gtcoyejmht.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.cdnleiting.top/Article/details/gtbeqzwwnf.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.hywenlv.cn/Article/details/gtvegilfjm.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.daxiang520.top/Article/details/gtvtudywty.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.0kj1m.cn/Article/details/gtilshwvdm.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.gzhubu.top/Article/details/gtfpvedkro.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhiwuduotai.top/Article/details/gteqsyater.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.havefunace.top/Article/details/gtpkcwtaul.html

[P03] 生成短随机字符串
来源：http://dali.aizwys.cn/Article/details/gtoeqgaruj.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.yonumen.top/Article/details/gtesaxhvxt.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtneznvkzj.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yuxming.cn/Article/details/gtqdkstxss.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.shzxlz.cn/Article/details/gtbwemiazj.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.hnxiangtu.top/Article/details/gtexnxaiyz.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.ybcxt.top/Article/details/gtqkiflggf.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.shanyushiyangtech.top/Article/details/gttgvpzskx.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.xuanzx.com/Article/details/gtiuadwwrg.html

[P04] 求长度
来源：http://dali.gzhubu.top/Article/details/gtesitbxhn.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.gaohongyu789.top/Article/details/gtfuvjdxyy.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.andypj.xyz/Article/details/gtqwzggjlf.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yj20258.top/Article/details/gtsurfteyg.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.shanyushiyangkeji.top/Article/details/gtukqmrqdx.html

Java: list.size();  map.size();  s.length()
来源：http://dali.smart0.xyz/Article/details/gtwglnetvv.html

Go:   len(arr);  len(m)
来源：http://dali.nanxinkj.top/Article/details/gtzhruvvvr.html

Ruby: x.length;  x.size
来源：http://dali.gotoacloud.top/Article/details/gtgpaodovx.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.gzhubu.top/Article/details/gtcezovvmp.html

[P05] 判断两个对象内容是否相等
来源：http://dali.hnqzz.top/Article/details/gtxuhlgesk.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.0kj1m.cn/Article/details/gtqxmrxvmq.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.nanxinkj.top/Article/details/gtfngelsox.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.nanxuanxn.top/Article/details/gtnhpzyxet.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.daria6918.cn/Article/details/gtovtkffkm.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.tanke756.top/Article/details/gtbzpjapxa.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.tanke756.top/Article/details/gtgheocoza.html

Ruby: a == b
来源：http://dali.zhongyouzk.top/Article/details/gtaozdpgrt.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.sysykeji.top/Article/details/gtfugmqqei.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.nanxinkj.top/Article/details/gtitkejpij.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.xuetiantiany.cn/Article/details/gtheuqxaef.html

PHP:  if (empty($x)) {}
来源：http://dali.pycfn.com/Article/details/gttfygylav.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.jqgfzy.top/Article/details/gtpktyydnm.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gteqnippns.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhongyouzk.top/Article/details/gtskrepoti.html

Go:   if x == nil {}
来源：http://dali.aibaodan.cn/Article/details/gtrmlsgpfu.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.nwbrower.top/Article/details/gtgdwqqfgp.html

C#:   if (x is null) {}
来源：http://dali.ehwqpu.com/Article/details/gtktufrkmu.html

[P07] 防抖与节流
来源：http://dali.jyoumei.cn/Article/details/gtbxulgrwa.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.hnqzz.top/Article/details/gtlwjtcchp.html

PHP:  // 手写时间戳比较
来源：http://dali.jinqigufen.top/Article/details/gtacrvtgxa.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhongyouzk.top/Article/details/gtouuhatec.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.xuetiantiany.cn/Article/details/gtghabbqjn.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.hongshengwenyu.top/Article/details/gtefoohert.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.cdnleiting.top/Article/details/gtcqryzeya.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.shanyushiyangtech.top/Article/details/gtjslfgjfx.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.guannengcc.top/Article/details/gtitarvfcx.html

[P08] 处理浮点精度问题
来源：http://dali.tanke756.top/Article/details/gtrmgommjz.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.shzxlz.cn/Article/details/gthduhazcj.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhoulong.xyz/Article/details/gtwccmfwhs.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.316326.xyz/Article/details/gtwovynvab.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.wangshuangyany.cn/Article/details/gtpjiiugie.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.dianchejie.cn/Article/details/gtmgmcrrax.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhoulong.xyz/Article/details/gtrtuvbsfb.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.feifeiyinyue.top/Article/details/gticnhhxho.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.sxryk.cn/Article/details/gtdezgfhix.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtntdqycjt.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.haohaochexian.top/Article/details/gtbjmzimbn.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtgmzzivnd.html

[Q01] 创建表
来源：http://dali.yuxming.cn/Article/details/gtijhurwub.html

CREATE TABLE users (
来源：http://dali.gzhubu.top/Article/details/gtzcpjebap.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.hfpthk.cn/Article/details/gtnxmihipd.html

name VARCHAR(50) NOT NULL,
来源：http://dali.cheryme.top/Article/details/gtocifwqao.html

email VARCHAR(100) UNIQUE,
来源：http://dali.yvedp.cn/Article/details/gtnrfqbjcm.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.daria6918.cn/Article/details/gtvxsmqaob.html

);
来源：http://dali.yonumen.top/Article/details/gtpbqagzcz.html

[Q02] 创建带外键的表
来源：http://dali.yanxiufei.cn/Article/details/gtkxhctisv.html

CREATE TABLE orders (
来源：http://dali.bjfxy.top/Article/details/gtlxbzzbde.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.nanxuanxn.top/Article/details/gtzghkouhx.html

user_id INT NOT NULL,
来源：http://dali.yvedp.cn/Article/details/gtebfcligo.html

amount DECIMAL(10, 2),
来源：http://dali.yuxming.cn/Article/details/gteoeyquin.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.sweek.top/Article/details/gtbqhmtmqt.html

);
来源：http://dali.yvedp.cn/Article/details/gtwltgwuid.html

[Q03] 增加列
来源：http://dali.yonumen.top/Article/details/gtsbnggfci.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.gogol.net.cn/Article/details/gtcyspkdme.html

[Q04] 修改列类型
来源：http://dali.tanke756.top/Article/details/gtuoccbonv.html


<!-- 参考信息 -->