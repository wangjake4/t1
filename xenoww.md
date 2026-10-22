代发 wailian999

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zycfv.cn/Article/details/gtxtxdlisw.html

[M05] 设置退出码
来源：http://dali.jlsjyb.cn/Article/details/gtgnfkdzyb.html

Py:   sys.exit(1)
来源：http://dali.shzxlz.cn/Article/details/gtvtbddpts.html

PHP:  exit(1);
来源：http://dali.snrcjt.cn/Article/details/gtkzylypqm.html

JS:   process.exit(1)
来源：http://dali.fzhhl.top/Article/details/gtlinsfjxn.html

TS:   process.exit(1)
来源：http://dali.cheryme.top/Article/details/gtfjpppper.html

Java: System.exit(1)
来源：http://dali.cdnleiting.top/Article/details/gtoaqudndf.html

Go:   os.Exit(1)
来源：http://dali.yuxming.cn/Article/details/gtqvsilqjb.html

Ruby: exit 1
来源：http://dali.cdnleiting.top/Article/details/gtwfmnlhum.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.nwbrower.top/Article/details/gtniqvjyyi.html

[M06] 向标准错误输出
来源：http://dali.birdmap.top/Article/details/gtuvtmhelo.html

Py:   print("err", file=sys.stderr)
来源：http://dali.gzhubu.top/Article/details/gtlawwajfe.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.316326.xyz/Article/details/gtsppvnmfh.html

JS:   console.error("err")
来源：http://dali.hnqzz.top/Article/details/gtagekoiuv.html

TS:   console.error("err")
来源：http://dali.tian-w.cn/Article/details/gtciaicrtf.html

Java: System.err.println("err")
来源：http://dali.aizwys.cn/Article/details/gtwboonzzg.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.fengsongda.top/Article/details/gthrbyvzjo.html

Ruby: warn "err"
来源：http://dali.gotoacloud.top/Article/details/gteazsofdr.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.cucudq.cn/Article/details/gtutfsnveg.html

[M07] 判断是否为主入口
来源：http://dali.chenjidiqi.icu/Article/details/gthtkvbgkx.html

Py:   if __name__ == "__main__":
来源：http://dali.chenlongwang.top/Article/details/gtnogueofs.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.wangshuangyany.cn/Article/details/gtgfxjnwhp.html

JS:   require.main === module
来源：http://dali.yongpay.top/Article/details/gtqxollipu.html

TS:   require.main === module
来源：http://dali.shuidangran.top/Article/details/gtjrvapfbs.html

Java: public static void main(String[] args)
来源：http://dali.yj20258.top/Article/details/gthrjwaldd.html

Go:   func main()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtchfexuwq.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.chenzaomai.com/Article/details/gtztwqgotx.html

C#:   static void Main(string[] args)
来源：http://dali.tanke756.top/Article/details/gtyehrpofs.html

[M08] 获取系统与运行时信息
来源：http://dali.yueranfly.top/Article/details/gteqkehehg.html

Py:   platform.system();  platform.python_version()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfcpczokj.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.hywenlv.cn/Article/details/gtvxwwxnaw.html

JS:   process.platform;  process.version
来源：http://dali.gzhubu.top/Article/details/gtunizbumc.html

TS:   process.platform;  process.version
来源：http://dali.0kj1m.cn/Article/details/gtbmcisnix.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.ybcxt.top/Article/details/gtgngaeteq.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.yvedp.cn/Article/details/gtfdzhbjlo.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.hysaishi.cn/Article/details/gtsublnltq.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.daria6918.cn/Article/details/gtjurzfmwt.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtrojhudxo.html

N. 数据结构与算法
来源：http://dali.fengsongda.top/Article/details/gtatpfwscj.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtgdvcyzsa.html

[N01] 二分查找（有序数组）
来源：http://dali.zhixingplan.top/Article/details/gthleblvdy.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhengqikj.top/Article/details/gtokvollml.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.jinqigfzy.top/Article/details/gtaswvdtoi.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.chenzaomai.com/Article/details/gteqcefihq.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.sweek.top/Article/details/gtxwxmcajo.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.birdmap.top/Article/details/gtbtdvahbg.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhongyouzk.top/Article/details/gtmmivibrf.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.nanxinkj.top/Article/details/gtqjtcuuvz.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.hammf.cn/Article/details/gttmfsbgbv.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.316326.xyz/Article/details/gtrfhmckba.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.xylfe.cn/Article/details/gthxyhhtdl.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.c1oappe.top/Article/details/gtocmlwwnj.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.gotoacloud.top/Article/details/gtvbeymcrg.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.ivvv.top/Article/details/gtjkdrxyrt.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.jqgfzy.top/Article/details/gtcrhacink.html

Go:   slices.Sort(arr)
来源：http://dali.zhengqikj.top/Article/details/gtvnxqgjtd.html

Ruby: arr.sort
来源：http://dali.jinghuilouyu.cn/Article/details/gtvxjnvlrz.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.yj20258888.top/Article/details/gtgmhgoflu.html

[N03] 快速排序（分治示例）
来源：http://dali.tian-w.cn/Article/details/gtltahjbhr.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.jinqigfzy.top/Article/details/gtyzxnyrhl.html

PHP:  // 递归实现，或用 usort
来源：http://dali.9152youxi.cn/Article/details/gtcpgdhbiy.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.quarkkingdee.top/Article/details/gtwbgslwjo.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.haohaochexian.top/Article/details/gtqhlwmyjh.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.sufxvd.cn/Article/details/gtuimtujqk.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.jinqigufen.top/Article/details/gtuibnzpzg.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.feifeiyinyue.top/Article/details/gtcrhcllmn.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.gaohongyu789.top/Article/details/gtppzansec.html

[N04] 斐波那契数列
来源：http://dali.jlsjyb.cn/Article/details/gtvzfpfdjt.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsxhveeqm.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.yj20258.top/Article/details/gtkxpqgtrb.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.nanxuanxn.top/Article/details/gtkoyxxjyg.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.haohaochexian.top/Article/details/gtniznicww.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.jyoumei.cn/Article/details/gtdnebpbgp.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.haohaochexian.top/Article/details/gtwcufqwug.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.316326.xyz/Article/details/gtquwwtaki.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.0kj1m.cn/Article/details/gtoxpjfcjt.html

[N05] 最大公约数
来源：http://dali.jqgufenzy.top/Article/details/gtplnzopjj.html

Py:   math.gcd(a, b)
来源：http://dali.jianghu66.top/Article/details/gtlnwqypkl.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.xinyue.icu/Article/details/gtgfjfvsbe.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hnxiangtu.top/Article/details/gtewwazrqn.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtcntsuluu.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.aizwys.cn/Article/details/gtobtvqpzu.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.iojbl.cn/Article/details/gtoefyfbvb.html

Ruby: a.gcd(b)
来源：http://dali.gogol.net.cn/Article/details/gtzurngupu.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.hammf.cn/Article/details/gtfplbambz.html

[N06] 判断回文字符串
来源：http://dali.hywenlv.cn/Article/details/gtylrmpfhp.html

Py:   s == s[::-1]
来源：http://dali.hywenlv.cn/Article/details/gtisvqmlzd.html

PHP:  $s === strrev($s);
来源：http://dali.yuxming.cn/Article/details/gtlqshlwzt.html

JS:   s === [...s].reverse().join("")
来源：http://dali.316326.xyz/Article/details/gtxcmjvgsu.html

TS:   s === [...s].reverse().join("")
来源：http://dali.dashuyun.cn/Article/details/gtpkdxfjbz.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.jqgfzy.top/Article/details/gtxwvrvxea.html

Go:   // 双指针从两端比较
来源：http://dali.jqgfzy.top/Article/details/gtqujobbfy.html

Ruby: s == s.reverse
来源：http://dali.tianlin.xyz/Article/details/gttnixsilr.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.wangdashe.top/Article/details/gtfizzdedf.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gtoqnhcldm.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhongyouzk.top/Article/details/gtcpujcozy.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.jqgfzy.top/Article/details/gtvktucrop.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.wangdashe.top/Article/details/gtqaqbecbz.html

TS:   // 手写 Map<string, number>
来源：http://dali.jlsjyb.cn/Article/details/gtqyfebxpi.html

Java: // 手写 HashMap
来源：http://dali.jinqigufen.top/Article/details/gtdhrjbepm.html

Go:   // 手写 map[int]int
来源：http://dali.quarkkingdee.top/Article/details/gtmsvrqpqm.html

Ruby: // 手写 Hash
来源：http://dali.guannengcc.top/Article/details/gtxgkwxucl.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.yueranfly.top/Article/details/gtkjeocnfh.html

[N08] 生成全排列
来源：http://dali.9152youxi.cn/Article/details/gtaxjgrqvn.html

Py:   itertools.permutations(arr)
来源：http://dali.daxiang520.top/Article/details/gttovoczyg.html

PHP:  // 手写递归交换
来源：http://dali.zhaomingkeji.xyz/Article/details/gtudwfjtlc.html

JS:   // 手写回溯递归
来源：http://dali.ywan-chungtsiang.top/Article/details/gturoulnks.html

TS:   // 手写回溯递归
来源：http://dali.ehwqpu.com/Article/details/gtcjpvgljn.html

Java: // 手写回溯递归
来源：http://dali.yuanzhike.top/Article/details/gtkawfiacv.html

Go:   // 手写回溯递归
来源：http://dali.pengpengdd.cyou/Article/details/gtbgjbdhlq.html

Ruby: arr.permutation.to_a
来源：http://dali.0kj1m.cn/Article/details/gtukucyjzc.html

C#:   // 手写回溯递归
来源：http://dali.ppjwa.cn/Article/details/gtvlmyxioj.html

[N09] 栈与队列
来源：http://dali.gzhubu.top/Article/details/gtkdzuskfl.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.yuanzhike.top/Article/details/gtuizxpbxs.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.dashuyun.cn/Article/details/gtdqjzjrei.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.xuanzx.com/Article/details/gtksunqhjs.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhoulong.xyz/Article/details/gtzbnulebh.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.pengpengdd.cyou/Article/details/gtarqpqeac.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.dashuyun.cn/Article/details/gtfwvjhqph.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.gzhubu.top/Article/details/gtaxmmxdzl.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.dianchejie.cn/Article/details/gtzdhvvibx.html

[N10] 链表节点定义
来源：http://dali.ywan-chungtsiang.top/Article/details/gtneihzwuq.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.jinqigufen.top/Article/details/gtjvqgfdnt.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.jinqigfzy.top/Article/details/gtqazqcesg.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.fzhhl.top/Article/details/gtujxpiqgb.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.hnxiangtu.top/Article/details/gtbaawxzky.html

Java: class Node { int v; Node next; }
来源：http://dali.shuidangran.top/Article/details/gtveqdclhc.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zycfv.cn/Article/details/gttprtwsif.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.yvedp.cn/Article/details/gtgzpbmymd.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.jyoumei.cn/Article/details/gtcwrfjlyu.html

[N11] 二叉树中序遍历
来源：http://dali.zdqjudy.top/Article/details/gtkfmzphey.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.hnxiangtu.top/Article/details/gtehxchxoe.html

PHP:  // 手写递归函数
来源：http://dali.havefunace.top/Article/details/gtyzdtfskq.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gtchynutlv.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yj20258.top/Article/details/gtbhvnlpjt.html

Java: // 手写递归
来源：http://dali.fzhhl.top/Article/details/gtdfhqxzzd.html

Go:   // 手写递归
来源：http://dali.hammf.cn/Article/details/gtehxnrfzz.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.iojbl.cn/Article/details/gtaoyfjrmf.html

C#:   // 手写递归
来源：http://dali.yangfankeji.com/Article/details/gtbdsvhdwt.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.kuanghao11.cn/Article/details/gtgannpmlv.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.yanxiufei.cn/Article/details/gtpndafbpk.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.daria6918.cn/Article/details/gtxrrkmaar.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.vqdsnc.cn/Article/details/gtaowndtvy.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.guowangkeji.top/Article/details/gtxsrauizb.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.meibo888.top/Article/details/gtuvbcluyx.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhengqikj.top/Article/details/gtgccepvlc.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.shzxlz.cn/Article/details/gtmhojykjn.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.ehwqpu.com/Article/details/gtwhqdshor.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtvircttte.html

O. 并发与异步
来源：http://dali.ppjwa.cn/Article/details/gtuewbwwxy.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtpspwggzz.html

[O01] 启动一个线程
来源：http://dali.jqgfzy.top/Article/details/gtdddyryps.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.daria6918.cn/Article/details/gtxqngjkgu.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.c1oappe.top/Article/details/gtiiamytec.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.cqqwz.cn/Article/details/gtdyunycod.html

TS:   // 同 JS
来源：http://dali.tian-w.cn/Article/details/gtctytazpq.html

Java: new Thread(() -> f()).start()
来源：http://dali.havefunace.top/Article/details/gtnscullzn.html

Go:   go f()
来源：http://dali.cashguo.top/Article/details/gtgxyacswt.html

Ruby: Thread.new { f }
来源：http://dali.kuanghao11.cn/Article/details/gtwqmrestx.html

C#:   Task.Run(() => F());
来源：http://dali.meibo888.top/Article/details/gtqziycwjd.html

[O02] 使用线程池
来源：http://dali.ivvv.top/Article/details/gtbnhiqfdz.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.chenjidiqi.icu/Article/details/gtoofytrlp.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.yueranfly.top/Article/details/gtkgvqspem.html

JS:   // worker_threads 线程池
来源：http://dali.meibo888.top/Article/details/gtaahgajyw.html

TS:   // worker_threads 线程池
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqmctnjdz.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.vqdsnc.cn/Article/details/gtpfdfkfgd.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.yueranfly.top/Article/details/gtcgryedzh.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.ywan-chungtsiang.top/Article/details/gthtuhywjk.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.yvedp.cn/Article/details/gtkzwiiubm.html

[O03] 加锁保护共享数据
来源：http://dali.316326.xyz/Article/details/gtodxuswbk.html

Py:   with lock: shared += 1
来源：http://dali.sufxvd.cn/Article/details/gtaeudwdqo.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.aizwys.cn/Article/details/gtezprrgfd.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhixingplan.top/Article/details/gthzfrkess.html

TS:   // 同 JS
来源：http://dali.gogol.net.cn/Article/details/gtzflywnbw.html

Java: synchronized (this) { shared++; }
来源：http://dali.dianchejie.cn/Article/details/gtbsydtlne.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.jyoumei.cn/Article/details/gtrdeygczj.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.xylfe.cn/Article/details/gtairaofto.html

C#:   lock (gate) { shared++; }
来源：http://dali.chenzaomai.com/Article/details/gtyzheejll.html

[O04] 定义异步函数并等待
来源：http://dali.ivvv.top/Article/details/gtohvsnwkq.html

Py:   async def f():⏎    await g()
来源：http://dali.jiagoushi.top/Article/details/gtomxqjwuf.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.redwolf501.top/Article/details/gtznsrsqoh.html

JS:   async function f() { await g(); }
来源：http://dali.jinqigufen.top/Article/details/gtlgucohtl.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.hfpthk.cn/Article/details/gtwaqhkgsw.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.meibo888.top/Article/details/gtieimgsxm.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.tianlin.xyz/Article/details/gtoaxdjafj.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.shangyingyoupin.top/Article/details/gtgwmxebta.html

C#:   async Task F() { await G(); }
来源：http://dali.xinyue.icu/Article/details/gtqwgdsgou.html

[O05] 并发执行并等待全部完成
来源：http://dali.yonumen.top/Article/details/gtioiwbqdw.html

Py:   asyncio.gather(*tasks)
来源：http://dali.c1oappe.top/Article/details/gtssthmpys.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.cashguo.top/Article/details/gtyxklqkzv.html

JS:   await Promise.all(tasks)
来源：http://dali.ppjwa.cn/Article/details/gtquknainj.html

TS:   await Promise.all(tasks)
来源：http://dali.gotoacloud.top/Article/details/gtegwcysxv.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.guowangkeji.top/Article/details/gtwaicicma.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.ehwqpu.com/Article/details/gtpaqxpowj.html

Ruby: threads.map(&:join)
来源：http://dali.nanxinkj.top/Article/details/gtdzzjmkzj.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.shuidangran.top/Article/details/gtipeilpzo.html

[O06] 使用进程池
来源：http://dali.9152youxi.cn/Article/details/gtgacdxtpr.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.hysaishi.cn/Article/details/gtiovmxtzn.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.iojbl.cn/Article/details/gtmsavycdb.html

JS:   // child_process / cluster 模块
来源：http://dali.ybcxt.top/Article/details/gtfkllqscu.html

TS:   // child_process / cluster 模块
来源：http://dali.cashguo.top/Article/details/gthxtleyyl.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.aibaodan.cn/Article/details/gtnmjrfdfr.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.guannengcc.top/Article/details/gtpdfkrxjd.html

Ruby: // fork 块
来源：http://dali.zycfv.cn/Article/details/gtvpoormoh.html

C#:   Parallel.For
来源：http://dali.yj202588.top/Article/details/gtjazabzvg.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtmfmoxmdz.html

P. 常用工具函数
来源：http://dali.haohaochexian.top/Article/details/gtcaoeritx.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtgtoyrjye.html

[P01] 生成 UUID
来源：http://dali.redwolf501.top/Article/details/gtjehxdxrj.html

Py:   str(uuid.uuid4())
来源：http://dali.chenlongwang.top/Article/details/gtlkxaecyc.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.jqgfzy.top/Article/details/gtpdokawld.html

JS:   crypto.randomUUID()
来源：http://dali.cucudq.cn/Article/details/gtwmjsoeqo.html

TS:   crypto.randomUUID()
来源：http://dali.chenzaomai.com/Article/details/gtisivozex.html

Java: UUID.randomUUID().toString()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgjrbtmhe.html

Go:   // 用 github.com/google/uuid
来源：http://dali.feifeiyinyue.top/Article/details/gtuusborlr.html

Ruby: SecureRandom.uuid
来源：http://dali.redwolf501.top/Article/details/gtxlecwgxc.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtazrrclyl.html

[P02] MD5 / SHA256 摘要
来源：http://dali.haohaochexian.top/Article/details/gtgtrcghyc.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.svipenyu.cn/Article/details/gtetwypydr.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.snrcjt.cn/Article/details/gtfiytsjpf.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.gotoacloud.top/Article/details/gtrylhqdnt.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.meibo888.top/Article/details/gtxbkjwyqx.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.cashguo.top/Article/details/gtfaqscwux.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhiwuduotai.top/Article/details/gtcuzxvnhn.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.daria6918.cn/Article/details/gtvogfpztu.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.ehwqpu.com/Article/details/gtrgkymkjp.html

[P03] 生成短随机字符串
来源：http://dali.jqgufenzy.top/Article/details/gtmdidpuig.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.aibaodan.cn/Article/details/gtyxhclsga.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.andypj.xyz/Article/details/gtptehurxg.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.dashuyun.cn/Article/details/gtemlwklpk.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.vqdsnc.cn/Article/details/gtdfyqfklg.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.ppjwa.cn/Article/details/gtvozhoydk.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.shanyushiyangtech.top/Article/details/gtandbvcyn.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.ppjwa.cn/Article/details/gtfedwlhuy.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.gotoacloud.top/Article/details/gthrdunekc.html

[P04] 求长度
来源：http://dali.zhengqikj.top/Article/details/gtdlwzahkq.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.gogol.net.cn/Article/details/gtncyumwcw.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.shzxlz.cn/Article/details/gtkogwuwde.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yj20258.top/Article/details/gtiearcdqa.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yongpay.top/Article/details/gtmexflgbn.html

Java: list.size();  map.size();  s.length()
来源：http://dali.hnqzz.top/Article/details/gtyzfvvmgq.html

Go:   len(arr);  len(m)
来源：http://dali.andypj.xyz/Article/details/gtprwjrtws.html

Ruby: x.length;  x.size
来源：http://dali.ydzc1.top/Article/details/gtxwrilxbl.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.meibo888.top/Article/details/gtuiwbmycv.html

[P05] 判断两个对象内容是否相等
来源：http://dali.yj202588.top/Article/details/gtomaxafwy.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.xuetiantiany.cn/Article/details/gtzcpjbnlg.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.ybcxt.top/Article/details/gtncdnucfl.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.jyoumei.cn/Article/details/gtqujlpsae.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.aizwys.cn/Article/details/gtogqrcefv.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.smart0.xyz/Article/details/gtsnwmttmc.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.yongpay.top/Article/details/gtlnygnyhs.html

Ruby: a == b
来源：http://dali.tianlin.xyz/Article/details/gtsjjcztdu.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.haohaochexian.top/Article/details/gtjzmiiexz.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.jinghuilouyu.cn/Article/details/gtsjriwzcs.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.nanxinkj.top/Article/details/gtzhospkni.html

PHP:  if (empty($x)) {}
来源：http://dali.daria6918.cn/Article/details/gtjhzivqrs.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.ybcxt.top/Article/details/gthznqwtjk.html

TS:   if (x == null) {}
来源：http://dali.sufxvd.cn/Article/details/gtcwnmuzxs.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhiwuduotai.top/Article/details/gtlpdchtxx.html

Go:   if x == nil {}
来源：http://dali.xziqi.cn/Article/details/gtiydraiut.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.gotoacloud.top/Article/details/gtknecoift.html

C#:   if (x is null) {}
来源：http://dali.zhiwuduotai.top/Article/details/gtsfhpdwff.html

[P07] 防抖与节流
来源：http://dali.guowangkeji.top/Article/details/gtciabfuvk.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.kuanghao11.cn/Article/details/gtkubnxtfu.html

PHP:  // 手写时间戳比较
来源：http://dali.shuidangran.top/Article/details/gtijkkwcpg.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.havefunace.top/Article/details/gtfhbmqnvr.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yuanzhike.top/Article/details/gtpirbwsdn.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.gotoacloud.top/Article/details/gtajfhsnqn.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.316326.xyz/Article/details/gtisavnokl.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.nanxinkj.top/Article/details/gtglalxqjk.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.yuanzhike.top/Article/details/gtjhzcjnhf.html

[P08] 处理浮点精度问题
来源：http://dali.wangdashe.top/Article/details/gtdcszmbyv.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsknaaoec.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.hnqzz.top/Article/details/gtzddfkqoh.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.jqgfzy.top/Article/details/gtxpbeufnz.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.nanxinkj.top/Article/details/gtcltwexud.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.mhx1999.top/Article/details/gtzdvalnio.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.xuetiantiany.cn/Article/details/gtwgrnzypb.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.sufxvd.cn/Article/details/gtpmegjcxe.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.pengpengdd.cyou/Article/details/gtpyhnnlux.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtcgollech.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhixingplan.top/Article/details/gtgzfeqvct.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtxmbstqhh.html

[Q01] 创建表
来源：http://dali.9152youxi.cn/Article/details/gtajlevbjg.html

CREATE TABLE users (
来源：http://dali.dashuyun.cn/Article/details/gthgyjvxoa.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.hammf.cn/Article/details/gtazxiddwo.html

name VARCHAR(50) NOT NULL,
来源：http://dali.yongpay.top/Article/details/gtbkviwvqc.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zycfv.cn/Article/details/gthnbydgrq.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.fzhhl.top/Article/details/gtytggafmh.html

);
来源：http://dali.chenzaomai.com/Article/details/gtenzmjzxn.html

[Q02] 创建带外键的表
来源：http://dali.ydzc1.top/Article/details/gtikbkanho.html

CREATE TABLE orders (
来源：http://dali.gogol.net.cn/Article/details/gtklknnaqv.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhongyouzk.top/Article/details/gtrixxlfcs.html

user_id INT NOT NULL,
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpqeslnkl.html

amount DECIMAL(10, 2),
来源：http://dali.gotoacloud.top/Article/details/gtcupsrfno.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.guannengcc.top/Article/details/gtmylubxft.html

);
来源：http://dali.fengsongda.top/Article/details/gtvagfuhgw.html

[Q03] 增加列
来源：http://dali.hammf.cn/Article/details/gtynuczsuv.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.chenlongwang.top/Article/details/gtsgvljzwe.html

[Q04] 修改列类型
来源：http://dali.dianchejie.cn/Article/details/gtikrhndyx.html


<!-- 参考信息 -->