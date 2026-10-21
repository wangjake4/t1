代发 wailian999

C#:   Directory.GetCurrentDirectory()
来源：http://dali.jqgfzy.top/Article/details/gtsynqwrqq.html

[M05] 设置退出码
来源：http://dali.jyoumei.cn/Article/details/gtqbaocomc.html

Py:   sys.exit(1)
来源：http://dali.tian-w.cn/Article/details/gtotscalmr.html

PHP:  exit(1);
来源：http://dali.jqgufenzy.top/Article/details/gtjuvybtsa.html

JS:   process.exit(1)
来源：http://dali.sxryk.cn/Article/details/gtwxrartuz.html

TS:   process.exit(1)
来源：http://dali.zdqjudy.top/Article/details/gtdushljfz.html

Java: System.exit(1)
来源：http://dali.quarkkingdee.top/Article/details/gthkmevlxu.html

Go:   os.Exit(1)
来源：http://dali.haohaochexian.top/Article/details/gtcunyziix.html

Ruby: exit 1
来源：http://dali.jyoumei.cn/Article/details/gtxprvxldd.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpcycqihl.html

[M06] 向标准错误输出
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxcaeynpi.html

Py:   print("err", file=sys.stderr)
来源：http://dali.0kj1m.cn/Article/details/gtfizbgdja.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.gotoacloud.top/Article/details/gtcvbpwxsr.html

JS:   console.error("err")
来源：http://dali.cheryme.top/Article/details/gtzjxtxuch.html

TS:   console.error("err")
来源：http://dali.zhiwuduotai.top/Article/details/gtutbieazg.html

Java: System.err.println("err")
来源：http://dali.zhixingplan.top/Article/details/gtmvnldepv.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.nanxuanxn.top/Article/details/gtqinekxlo.html

Ruby: warn "err"
来源：http://dali.jinqigufen.top/Article/details/gtpxntypcl.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.ehwqpu.com/Article/details/gtgcpunkwk.html

[M07] 判断是否为主入口
来源：http://dali.snrcjt.cn/Article/details/gtvolojgbw.html

Py:   if __name__ == "__main__":
来源：http://dali.zhongyouzk.top/Article/details/gtmukkfxbm.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.mhx1999.top/Article/details/gtchbpkqbv.html

JS:   require.main === module
来源：http://dali.svipenyu.cn/Article/details/gtsvxgtaet.html

TS:   require.main === module
来源：http://dali.guowangkeji.top/Article/details/gtftapelie.html

Java: public static void main(String[] args)
来源：http://dali.zhiwuduotai.top/Article/details/gtvzhtistd.html

Go:   func main()
来源：http://dali.shangyingyoupin.top/Article/details/gtrbilcuxu.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.hammf.cn/Article/details/gtijesczmw.html

C#:   static void Main(string[] args)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyfrwwtuj.html

[M08] 获取系统与运行时信息
来源：http://dali.zhoulong.xyz/Article/details/gtwoojactd.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zdqjudy.top/Article/details/gtjjofhocu.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.nanxinkj.top/Article/details/gtuuirtkfl.html

JS:   process.platform;  process.version
来源：http://dali.zdqjudy.top/Article/details/gtydgzyshh.html

TS:   process.platform;  process.version
来源：http://dali.xinyue.icu/Article/details/gthhqlbhnd.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zycfv.cn/Article/details/gtzdxmzcuv.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.ydzc1.top/Article/details/gtsxdcdbzo.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.jyoumei.cn/Article/details/gtfrwptyrp.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.yj20258888.top/Article/details/gtubchshwa.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gttakqmgsz.html

N. 数据结构与算法
来源：http://dali.snrcjt.cn/Article/details/gttkitzxbt.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtsuyvndor.html

[N01] 二分查找（有序数组）
来源：http://dali.jinqigufen.top/Article/details/gtlltfpfjb.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.snrcjt.cn/Article/details/gtavivumim.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.xylfe.cn/Article/details/gtewlhmkrh.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.andypj.xyz/Article/details/gtyhsaipqw.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yangfankeji.com/Article/details/gtrhlosqve.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.bjfxy.top/Article/details/gtjhhuicgv.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.c1oappe.top/Article/details/gtbyyvfxvk.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.chenjidiqi.icu/Article/details/gthdlqvlkr.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.shzxlz.cn/Article/details/gtggvcnipm.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.nwbrower.top/Article/details/gtmvqtbsua.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zycfv.cn/Article/details/gtemqvvfxk.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.tanke756.top/Article/details/gtmbwagmdv.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yonumen.top/Article/details/gtvfuscqqd.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.cqqwz.cn/Article/details/gtehfutmwa.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gtwvjqhghz.html

Go:   slices.Sort(arr)
来源：http://dali.gaohongyu789.top/Article/details/gthybmbgtf.html

Ruby: arr.sort
来源：http://dali.mhx1999.top/Article/details/gthntdkdsq.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.gogol.net.cn/Article/details/gttqyuxzkt.html

[N03] 快速排序（分治示例）
来源：http://dali.hywenlv.cn/Article/details/gtvqgqzusn.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.yuanzhike.top/Article/details/gtzosrqzec.html

PHP:  // 递归实现，或用 usort
来源：http://dali.sxryk.cn/Article/details/gtnibdqhpl.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.meibo888.top/Article/details/gtvrnqzztj.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.gaohongyu789.top/Article/details/gtimiqltaf.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.aizwys.cn/Article/details/gtlicxqzxb.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.ppjwa.cn/Article/details/gtfwcualke.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhixingplan.top/Article/details/gtrqyauwbz.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.xziqi.cn/Article/details/gtaywmdywx.html

[N04] 斐波那契数列
来源：http://dali.snrcjt.cn/Article/details/gtvaekrcdv.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.andypj.xyz/Article/details/gthtybirqo.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.aizwys.cn/Article/details/gtcplsyojk.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.daria6918.cn/Article/details/gtdywsbogx.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.0kj1m.cn/Article/details/gtfdowkijr.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.yj202588.top/Article/details/gtpttjxhov.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.sxryk.cn/Article/details/gtvdgkooyg.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.yuanzhike.top/Article/details/gtjbxifqoz.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.ybcxt.top/Article/details/gtitbbzbds.html

[N05] 最大公约数
来源：http://dali.0kj1m.cn/Article/details/gtlcnyystx.html

Py:   math.gcd(a, b)
来源：http://dali.daria6918.cn/Article/details/gtrpkqduvy.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.jinqigufen.top/Article/details/gtlzowcubq.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.sysykeji.top/Article/details/gtuwgvhsiq.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jiagoushi.top/Article/details/gturpifuji.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.hysaishi.cn/Article/details/gtithubsok.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.chenlongwang.top/Article/details/gtdgffhvik.html

Ruby: a.gcd(b)
来源：http://dali.redwolf501.top/Article/details/gtwybadcas.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.nanxuanxn.top/Article/details/gtanozkasf.html

[N06] 判断回文字符串
来源：http://dali.xziqi.cn/Article/details/gtiqkoonpf.html

Py:   s == s[::-1]
来源：http://dali.ivvv.top/Article/details/gtjqzrblnz.html

PHP:  $s === strrev($s);
来源：http://dali.yvedp.cn/Article/details/gtggaikstl.html

JS:   s === [...s].reverse().join("")
来源：http://dali.hysaishi.cn/Article/details/gtvgzphgwg.html

TS:   s === [...s].reverse().join("")
来源：http://dali.yangfankeji.com/Article/details/gttlsbrshk.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.hammf.cn/Article/details/gtmwcltmpb.html

Go:   // 双指针从两端比较
来源：http://dali.quarkkingdee.top/Article/details/gtqawyfzsl.html

Ruby: s == s.reverse
来源：http://dali.xinyue.icu/Article/details/gteplgjmgl.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.cashguo.top/Article/details/gtfzeydlll.html

[N07] 两数之和（返回下标）
来源：http://dali.svipenyu.cn/Article/details/gtikxpxphs.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.pycfn.com/Article/details/gtennuzwca.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.snrcjt.cn/Article/details/gtgpjtjevz.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.dashuyun.cn/Article/details/gtpbcjwhgz.html

TS:   // 手写 Map<string, number>
来源：http://dali.chenjidiqi.icu/Article/details/gtuhnjfnyy.html

Java: // 手写 HashMap
来源：http://dali.yanxiufei.cn/Article/details/gtpjzfifoo.html

Go:   // 手写 map[int]int
来源：http://dali.feifeiyinyue.top/Article/details/gtooxyolvt.html

Ruby: // 手写 Hash
来源：http://dali.jinqigfzy.top/Article/details/gtsqhmsvre.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.yvedp.cn/Article/details/gtkfwgjmbu.html

[N08] 生成全排列
来源：http://dali.xuanzx.com/Article/details/gtwxiysaiu.html

Py:   itertools.permutations(arr)
来源：http://dali.cheryme.top/Article/details/gtepyyoqti.html

PHP:  // 手写递归交换
来源：http://dali.haohaochexian.top/Article/details/gtzifrxjwj.html

JS:   // 手写回溯递归
来源：http://dali.c1oappe.top/Article/details/gtuhiltmbl.html

TS:   // 手写回溯递归
来源：http://dali.aibaodan.cn/Article/details/gtpsyagpgh.html

Java: // 手写回溯递归
来源：http://dali.xylfe.cn/Article/details/gtagsrnoou.html

Go:   // 手写回溯递归
来源：http://dali.fengsongda.top/Article/details/gtqvhdejve.html

Ruby: arr.permutation.to_a
来源：http://dali.hongshengwenyu.top/Article/details/gtyxyeripf.html

C#:   // 手写回溯递归
来源：http://dali.ydzc1.top/Article/details/gtaqyahxsn.html

[N09] 栈与队列
来源：http://dali.jinqigfzy.top/Article/details/gtcpczlaqi.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.jqgufenzy.top/Article/details/gtjjljszzq.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.jinqigufen.top/Article/details/gtgjoyvmpn.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.xylfe.cn/Article/details/gtizqqglsa.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.cashguo.top/Article/details/gtnugnmmqu.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.andypj.xyz/Article/details/gtmgducrpv.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.hywenlv.cn/Article/details/gtnudqqmqq.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.c1oappe.top/Article/details/gtqtsknhcg.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.jianghu66.top/Article/details/gtmfqanlax.html

[N10] 链表节点定义
来源：http://dali.jqgufenzy.top/Article/details/gtyaaazjrg.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.iojbl.cn/Article/details/gtncxbqwrw.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.cdnleiting.top/Article/details/gtopweutwy.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.ppjwa.cn/Article/details/gtgjxtwdgt.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.nanxinkj.top/Article/details/gtzvpgsmeq.html

Java: class Node { int v; Node next; }
来源：http://dali.hfpthk.cn/Article/details/gtkfigkhwq.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.snrcjt.cn/Article/details/gtnkspgmvk.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.yangfankeji.com/Article/details/gtoejwbbup.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.yvedp.cn/Article/details/gtrlfzbjgo.html

[N11] 二叉树中序遍历
来源：http://dali.xziqi.cn/Article/details/gtgreeoswf.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.hywenlv.cn/Article/details/gtaqeoxjod.html

PHP:  // 手写递归函数
来源：http://dali.redwolf501.top/Article/details/gtjoslkhak.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yonumen.top/Article/details/gtofdklsgd.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jlsjyb.cn/Article/details/gtomecirdl.html

Java: // 手写递归
来源：http://dali.shanyushiyangtech.top/Article/details/gtxcrlhaal.html

Go:   // 手写递归
来源：http://dali.c1oappe.top/Article/details/gtxqpjpmlm.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.redwolf501.top/Article/details/gtaejadxsi.html

C#:   // 手写递归
来源：http://dali.shanyushiyangtech.top/Article/details/gtfbocxkbj.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.yuxming.cn/Article/details/gtnwbujdmo.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.ybcxt.top/Article/details/gtewsmzcqj.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.snrcjt.cn/Article/details/gtykfbvqwb.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhoulong.xyz/Article/details/gtergsmipw.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yongpay.top/Article/details/gteciqczmk.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.iojbl.cn/Article/details/gtqwagyvvx.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.9152youxi.cn/Article/details/gtqauntkcb.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.birdmap.top/Article/details/gtmvbvbhbl.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.gotoacloud.top/Article/details/gtgblkcpjf.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtvhrapshq.html

O. 并发与异步
来源：http://dali.iojbl.cn/Article/details/gtofqhuexu.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtxyhicaph.html

[O01] 启动一个线程
来源：http://dali.pycfn.com/Article/details/gtexlphyku.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.tianlin.xyz/Article/details/gtwgudgsin.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.redwolf501.top/Article/details/gtjbfwrdeg.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.ydzc1.top/Article/details/gtoqvfabzt.html

TS:   // 同 JS
来源：http://dali.9152youxi.cn/Article/details/gtmfugnsis.html

Java: new Thread(() -> f()).start()
来源：http://dali.guannengcc.top/Article/details/gtympajlcx.html

Go:   go f()
来源：http://dali.gogol.net.cn/Article/details/gtpqeesvwj.html

Ruby: Thread.new { f }
来源：http://dali.zhoulong.xyz/Article/details/gtnujdoxdv.html

C#:   Task.Run(() => F());
来源：http://dali.andypj.xyz/Article/details/gtxslbrpki.html

[O02] 使用线程池
来源：http://dali.cheryme.top/Article/details/gtefqocuri.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.cdnleiting.top/Article/details/gtakqqonax.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.jinqigufen.top/Article/details/gtmynytnip.html

JS:   // worker_threads 线程池
来源：http://dali.9152youxi.cn/Article/details/gtzxmtthpb.html

TS:   // worker_threads 线程池
来源：http://dali.chenlongwang.top/Article/details/gtlefnokdu.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.jqgufenzy.top/Article/details/gthmfanmwv.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.ydzc1.top/Article/details/gticxkmwvr.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zdqjudy.top/Article/details/gtqcdoernh.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.hfpthk.cn/Article/details/gtrrimqthg.html

[O03] 加锁保护共享数据
来源：http://dali.hnxiangtu.top/Article/details/gtnxwxaiat.html

Py:   with lock: shared += 1
来源：http://dali.316326.xyz/Article/details/gtsprbamjq.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gtkqyxrudk.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.hammf.cn/Article/details/gtgtfwwbif.html

TS:   // 同 JS
来源：http://dali.xinyue.icu/Article/details/gtfzcahrgp.html

Java: synchronized (this) { shared++; }
来源：http://dali.yvedp.cn/Article/details/gttfemekte.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.andypj.xyz/Article/details/gtcoyejvcj.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.nanxinkj.top/Article/details/gtfyvjbbzv.html

C#:   lock (gate) { shared++; }
来源：http://dali.chenlongwang.top/Article/details/gtrpcpqclg.html

[O04] 定义异步函数并等待
来源：http://dali.jyoumei.cn/Article/details/gtjirslgio.html

Py:   async def f():⏎    await g()
来源：http://dali.sxryk.cn/Article/details/gtcyvyddnv.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.yvedp.cn/Article/details/gtmfbdmsun.html

JS:   async function f() { await g(); }
来源：http://dali.aibaodan.cn/Article/details/gtccjrbbjy.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.hnxiangtu.top/Article/details/gtwlnefuaa.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.pengpengdd.cyou/Article/details/gtdoghxhge.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.ydzc1.top/Article/details/gtksokizmg.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.gogol.net.cn/Article/details/gtuugasrmz.html

C#:   async Task F() { await G(); }
来源：http://dali.guannengcc.top/Article/details/gtselacjrr.html

[O05] 并发执行并等待全部完成
来源：http://dali.yj202588.top/Article/details/gtjnhkhbkd.html

Py:   asyncio.gather(*tasks)
来源：http://dali.meibo888.top/Article/details/gtkujdwgfi.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.yuxming.cn/Article/details/gtfdedvxtp.html

JS:   await Promise.all(tasks)
来源：http://dali.mhx1999.top/Article/details/gtjvklweuc.html

TS:   await Promise.all(tasks)
来源：http://dali.jinyuanbaomall.cn/Article/details/gteuvvgzru.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.c1oappe.top/Article/details/gtmzsjrozw.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.shangyingyoupin.top/Article/details/gtmcdojmjh.html

Ruby: threads.map(&:join)
来源：http://dali.smart0.xyz/Article/details/gtsxzrmhrz.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfejaqibe.html

[O06] 使用进程池
来源：http://dali.sweek.top/Article/details/gtojzjyxqu.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.daxiang520.top/Article/details/gtxlegenns.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.jianghu66.top/Article/details/gtzefdjgws.html

JS:   // child_process / cluster 模块
来源：http://dali.sweek.top/Article/details/gticendrqm.html

TS:   // child_process / cluster 模块
来源：http://dali.pycfn.com/Article/details/gtbwgyztsi.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.pycfn.com/Article/details/gtolhsfahf.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.nanxuanxn.top/Article/details/gttknnemmy.html

Ruby: // fork 块
来源：http://dali.yj202588.top/Article/details/gtyatefiqs.html

C#:   Parallel.For
来源：http://dali.sxryk.cn/Article/details/gtnfptjdgn.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtbmmkhkiu.html

P. 常用工具函数
来源：http://dali.zhengqikj.top/Article/details/gtvwitnpef.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtdqrhvfkh.html

[P01] 生成 UUID
来源：http://dali.jinqigufen.top/Article/details/gtevryiazu.html

Py:   str(uuid.uuid4())
来源：http://dali.gotoacloud.top/Article/details/gtgyahzprx.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.hywenlv.cn/Article/details/gtdbcclniq.html

JS:   crypto.randomUUID()
来源：http://dali.hongshengwenyu.top/Article/details/gtowuiypzi.html

TS:   crypto.randomUUID()
来源：http://dali.chenlongwang.top/Article/details/gtxexktyrr.html

Java: UUID.randomUUID().toString()
来源：http://dali.jinqigufen.top/Article/details/gtltevgehh.html

Go:   // 用 github.com/google/uuid
来源：http://dali.bjfxy.top/Article/details/gtcomvwfhe.html

Ruby: SecureRandom.uuid
来源：http://dali.bjfxy.top/Article/details/gtytjaabnn.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.shangyingyoupin.top/Article/details/gtfgrwmsok.html

[P02] MD5 / SHA256 摘要
来源：http://dali.andypj.xyz/Article/details/gtznkzmxtk.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbxwwrmnv.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.vqdsnc.cn/Article/details/gtoivsmkqs.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.nanxinkj.top/Article/details/gtnjpaevuo.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.sufxvd.cn/Article/details/gtkyebfqfx.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.hfpthk.cn/Article/details/gtxbvdnkyr.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.jqgfzy.top/Article/details/gtciymtenm.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.9152youxi.cn/Article/details/gtxyfgmynj.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhengqikj.top/Article/details/gtjgzoeljr.html

[P03] 生成短随机字符串
来源：http://dali.mhx1999.top/Article/details/gtofofynqv.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.jiagoushi.top/Article/details/gtjxxihpqw.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.9152youxi.cn/Article/details/gtkqfpybyv.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yj20258888.top/Article/details/gtaujtitjf.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.cucudq.cn/Article/details/gtlrwuucvq.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.jianghu66.top/Article/details/gtleadmyud.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.shanyushiyangtech.top/Article/details/gtsyknvhma.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.jinqigfzy.top/Article/details/gtmcjveefh.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.ybcxt.top/Article/details/gtjskuqrmy.html

[P04] 求长度
来源：http://dali.sxryk.cn/Article/details/gtfgjgggrs.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.c1oappe.top/Article/details/gthbsqwqzt.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtycalhqqu.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.kuanghao11.cn/Article/details/gtgteiebqx.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zycfv.cn/Article/details/gtwyniljse.html

Java: list.size();  map.size();  s.length()
来源：http://dali.sufxvd.cn/Article/details/gtravqmzrg.html

Go:   len(arr);  len(m)
来源：http://dali.guannengcc.top/Article/details/gtgyzdbrqs.html

Ruby: x.length;  x.size
来源：http://dali.iojbl.cn/Article/details/gtajrmixoa.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.smart0.xyz/Article/details/gtsovrvqqy.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gtuyodquee.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.redwolf501.top/Article/details/gthjcoqbit.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.hysaishi.cn/Article/details/gtllhnppag.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.guannengcc.top/Article/details/gtpysttrwj.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhengqikj.top/Article/details/gtdfqhhuts.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.yvedp.cn/Article/details/gtrcycsolz.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.dashuyun.cn/Article/details/gthjvlyeny.html

Ruby: a == b
来源：http://dali.c1oappe.top/Article/details/gtievggnpu.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.jqgfzy.top/Article/details/gtlzyyataz.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.kuanghao11.cn/Article/details/gtikcdunuf.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.iojbl.cn/Article/details/gtyseubgqp.html

PHP:  if (empty($x)) {}
来源：http://dali.gaohongyu789.top/Article/details/gtlumukius.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.nwbrower.top/Article/details/gtvrosrsng.html

TS:   if (x == null) {}
来源：http://dali.fengsongda.top/Article/details/gtbrkbgbbp.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtlodxncrs.html

Go:   if x == nil {}
来源：http://dali.jinqigufen.top/Article/details/gtvygfkugi.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhoulong.xyz/Article/details/gtksanieoy.html

C#:   if (x is null) {}
来源：http://dali.yongpay.top/Article/details/gtsyigyxjr.html

[P07] 防抖与节流
来源：http://dali.cheryme.top/Article/details/gtsqpptvby.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnqbjrisd.html

PHP:  // 手写时间戳比较
来源：http://dali.xziqi.cn/Article/details/gtbumytqvo.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jianghu66.top/Article/details/gtntvzuuss.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yueranfly.top/Article/details/gtpaajfcfh.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.yj20258.top/Article/details/gtmvgjxwtt.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.fzhhl.top/Article/details/gtljvtucvl.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.yj202588.top/Article/details/gteqvwwelt.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaohujljg.html

[P08] 处理浮点精度问题
来源：http://dali.fengsongda.top/Article/details/gtldozkfld.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.fengsongda.top/Article/details/gtlfriuegw.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.daxiang520.top/Article/details/gtyjsqbgri.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.bjfxy.top/Article/details/gtvrqpmwdb.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.dashuyun.cn/Article/details/gtlrwlnzei.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.yongpay.top/Article/details/gtmqmgoeaz.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.meibo888.top/Article/details/gtrqtlzsep.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.yonumen.top/Article/details/gtohboivur.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.c1oappe.top/Article/details/gtlgmxiytj.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtjdndllbs.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxbplpjdu.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtwfeiropi.html

[Q01] 创建表
来源：http://dali.yonumen.top/Article/details/gtmkumyzdg.html

CREATE TABLE users (
来源：http://dali.wangdashe.top/Article/details/gttzbdnvgn.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.sweek.top/Article/details/gtugamugkq.html

name VARCHAR(50) NOT NULL,
来源：http://dali.mhx1999.top/Article/details/gttduujifk.html

email VARCHAR(100) UNIQUE,
来源：http://dali.sufxvd.cn/Article/details/gtshrtkpyb.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.snrcjt.cn/Article/details/gtzidrsruc.html

);
来源：http://dali.cqqwz.cn/Article/details/gtikvivkpj.html

[Q02] 创建带外键的表
来源：http://dali.dashuyun.cn/Article/details/gtntmdhoxb.html

CREATE TABLE orders (
来源：http://dali.jqgfzy.top/Article/details/gtmuuuqcwb.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.hfpthk.cn/Article/details/gtmegswmqh.html

user_id INT NOT NULL,
来源：http://dali.haohaochexian.top/Article/details/gtnegokmuv.html

amount DECIMAL(10, 2),
来源：http://dali.guannengcc.top/Article/details/gtlzdrfmlp.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.sysykeji.top/Article/details/gtmakjtscv.html

);
来源：http://dali.c1oappe.top/Article/details/gtaxmubmst.html

[Q03] 增加列
来源：http://dali.yangfankeji.com/Article/details/gtupavsbwy.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.shanyushiyangtech.top/Article/details/gtqersilqj.html

[Q04] 修改列类型
来源：http://dali.aizwys.cn/Article/details/gtjhjjrscv.html


<!-- 参考信息 -->