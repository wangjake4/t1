代发 wailian999

JS:   process.exit(1)
来源：http://dali.daria6918.cn/Article/details/gtylbpepgk.html

TS:   process.exit(1)
来源：http://dali.zhengqikj.top/Article/details/gtecmdsarh.html

Java: System.exit(1)
来源：http://dali.daria6918.cn/Article/details/gtlziqnhxy.html

Go:   os.Exit(1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuzlbctpg.html

Ruby: exit 1
来源：http://dali.gotoacloud.top/Article/details/gtkdemeswq.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmxlfiybz.html

[M06] 向标准错误输出
来源：http://dali.wangshuangyany.cn/Article/details/gtakihbyhk.html

Py:   print("err", file=sys.stderr)
来源：http://dali.hongshengwenyu.top/Article/details/gtkgzxrrph.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zycfv.cn/Article/details/gtdffizjxg.html

JS:   console.error("err")
来源：http://dali.wangdashe.top/Article/details/gtkguqdgav.html

TS:   console.error("err")
来源：http://dali.tianlin.xyz/Article/details/gtitgltklq.html

Java: System.err.println("err")
来源：http://dali.gotoacloud.top/Article/details/gtsttgphnp.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.dashuyun.cn/Article/details/gtrujmxhav.html

Ruby: warn "err"
来源：http://dali.chenjidiqi.icu/Article/details/gtximgobcn.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zycfv.cn/Article/details/gtoqfqfbdl.html

[M07] 判断是否为主入口
来源：http://dali.gzhubu.top/Article/details/gtskrtkmkv.html

Py:   if __name__ == "__main__":
来源：http://dali.tianlin.xyz/Article/details/gtdinybrie.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.jianghu66.top/Article/details/gtsyndxqch.html

JS:   require.main === module
来源：http://dali.ehwqpu.com/Article/details/gtbeiopbgl.html

TS:   require.main === module
来源：http://dali.mhx1999.top/Article/details/gtmhrvnhgo.html

Java: public static void main(String[] args)
来源：http://dali.chenjidiqi.icu/Article/details/gthjbjsydn.html

Go:   func main()
来源：http://dali.zhongyouzk.top/Article/details/gttbhmpjrt.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.cqqwz.cn/Article/details/gtbgitbpgy.html

C#:   static void Main(string[] args)
来源：http://dali.xuanzx.com/Article/details/gtznplyagh.html

[M08] 获取系统与运行时信息
来源：http://dali.hysaishi.cn/Article/details/gtcpxgjwhu.html

Py:   platform.system();  platform.python_version()
来源：http://dali.yuanzhike.top/Article/details/gtnrftimms.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.cdnleiting.top/Article/details/gtnfripdlj.html

JS:   process.platform;  process.version
来源：http://dali.feifeiyinyue.top/Article/details/gtstgwxnlv.html

TS:   process.platform;  process.version
来源：http://dali.yanxiufei.cn/Article/details/gtsifswkqm.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.gaohongyu789.top/Article/details/gtehsaqvhk.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.yj202588.top/Article/details/gtdcxmqyua.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhoulong.xyz/Article/details/gtptryojnp.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.jinghuilouyu.cn/Article/details/gtbbvduijh.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtvejzbsah.html

N. 数据结构与算法
来源：http://dali.aizwys.cn/Article/details/gtwtbhubml.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtdobfbalk.html

[N01] 二分查找（有序数组）
来源：http://dali.cdnleiting.top/Article/details/gtnqarlcqc.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsrpboeys.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.daxiang520.top/Article/details/gtcayqxnkk.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.smart0.xyz/Article/details/gtxdxglcuu.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.sysykeji.top/Article/details/gtojbmncbw.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.birdmap.top/Article/details/gtwqnavvym.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhiwuduotai.top/Article/details/gtytedesqm.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.xziqi.cn/Article/details/gtywnlvhfa.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhixingplan.top/Article/details/gtlaqpkhmo.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.yuxming.cn/Article/details/gtojjevwif.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.andypj.xyz/Article/details/gtdkhsbznq.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.birdmap.top/Article/details/gtwthnqiox.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.nwbrower.top/Article/details/gtxgojakcn.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.chenjidiqi.icu/Article/details/gtnqjjvrxo.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.shanyushiyangtech.top/Article/details/gtqyirtgso.html

Go:   slices.Sort(arr)
来源：http://dali.pycfn.com/Article/details/gtqwbmmhdb.html

Ruby: arr.sort
来源：http://dali.cdnleiting.top/Article/details/gtfqawvguc.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.ybcxt.top/Article/details/gthortwvgn.html

[N03] 快速排序（分治示例）
来源：http://dali.gotoacloud.top/Article/details/gtmabpcmnk.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.daria6918.cn/Article/details/gtcfdzridd.html

PHP:  // 递归实现，或用 usort
来源：http://dali.xylfe.cn/Article/details/gtmysgvnhy.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yongpay.top/Article/details/gtxgmuezux.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yuanzhike.top/Article/details/gtcdakjxua.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.feifeiyinyue.top/Article/details/gtugvfuuws.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.shuidangran.top/Article/details/gtvrnlmckc.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.mhx1999.top/Article/details/gtwmenqizt.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhongyouzk.top/Article/details/gtvwjauosg.html

[N04] 斐波那契数列
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcmlgmpic.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhiwuduotai.top/Article/details/gtgzlodywl.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnyrprpjo.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yonumen.top/Article/details/gtilniziet.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.chenjidiqi.icu/Article/details/gtrzqbnopv.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.tanke756.top/Article/details/gtmuepybfo.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gtwhfjkutd.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.aizwys.cn/Article/details/gttjmgfvyl.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.jlsjyb.cn/Article/details/gtqkcvalyk.html

[N05] 最大公约数
来源：http://dali.316326.xyz/Article/details/gtigbtydlw.html

Py:   math.gcd(a, b)
来源：http://dali.zhongyouzk.top/Article/details/gtvoftvtqa.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.guannengcc.top/Article/details/gtanqhhpjx.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hywenlv.cn/Article/details/gtbyvxhzsv.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jiagoushi.top/Article/details/gtwwzdpprg.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.pycfn.com/Article/details/gtoztkthmt.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhongyouzk.top/Article/details/gtgtdzzped.html

Ruby: a.gcd(b)
来源：http://dali.cheryme.top/Article/details/gtzphgmdfz.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.gzhubu.top/Article/details/gtrigsuzyo.html

[N06] 判断回文字符串
来源：http://dali.zhongyouzk.top/Article/details/gtmieefzxr.html

Py:   s == s[::-1]
来源：http://dali.daria6918.cn/Article/details/gtenggzuir.html

PHP:  $s === strrev($s);
来源：http://dali.zhongyouzk.top/Article/details/gtwhkdezsc.html

JS:   s === [...s].reverse().join("")
来源：http://dali.yuanzhike.top/Article/details/gtgizqdmam.html

TS:   s === [...s].reverse().join("")
来源：http://dali.yonumen.top/Article/details/gttfmzmmyb.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.jinghuilouyu.cn/Article/details/gtevnnhfet.html

Go:   // 双指针从两端比较
来源：http://dali.tianlin.xyz/Article/details/gtsalzmtod.html

Ruby: s == s.reverse
来源：http://dali.wangdashe.top/Article/details/gtmqkibnbe.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.yvedp.cn/Article/details/gtowyrojyi.html

[N07] 两数之和（返回下标）
来源：http://dali.guannengcc.top/Article/details/gtxybbygwq.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.xylfe.cn/Article/details/gttehjuogg.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.hysaishi.cn/Article/details/gtcmvryfst.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.smart0.xyz/Article/details/gtjomtvdvo.html

TS:   // 手写 Map<string, number>
来源：http://dali.jqgufenzy.top/Article/details/gtfcttwnmp.html

Java: // 手写 HashMap
来源：http://dali.fengsongda.top/Article/details/gtvurldvrp.html

Go:   // 手写 map[int]int
来源：http://dali.aizwys.cn/Article/details/gtblpsoqtv.html

Ruby: // 手写 Hash
来源：http://dali.zycfv.cn/Article/details/gtymzlpsfz.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.yj202588.top/Article/details/gtemfsjdqn.html

[N08] 生成全排列
来源：http://dali.jinqigfzy.top/Article/details/gtityxeqfo.html

Py:   itertools.permutations(arr)
来源：http://dali.sysykeji.top/Article/details/gtwbxobisw.html

PHP:  // 手写递归交换
来源：http://dali.ppjwa.cn/Article/details/gtdoidjzrw.html

JS:   // 手写回溯递归
来源：http://dali.gzhubu.top/Article/details/gtlgphmxev.html

TS:   // 手写回溯递归
来源：http://dali.zhoulong.xyz/Article/details/gtafkdpoqj.html

Java: // 手写回溯递归
来源：http://dali.chenzaomai.com/Article/details/gtaawgunta.html

Go:   // 手写回溯递归
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgflfnbyt.html

Ruby: arr.permutation.to_a
来源：http://dali.chenlongwang.top/Article/details/gtwhwrzlsy.html

C#:   // 手写回溯递归
来源：http://dali.hywenlv.cn/Article/details/gttiollulh.html

[N09] 栈与队列
来源：http://dali.zhiwuduotai.top/Article/details/gtpjbelgkt.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.jinyuanbaomall.cn/Article/details/gtazvwopsf.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.cqqwz.cn/Article/details/gtubhqnufb.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.nwbrower.top/Article/details/gtytrphjnw.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.andypj.xyz/Article/details/gtviymdtpv.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.hongshengwenyu.top/Article/details/gtajvadnct.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.quarkkingdee.top/Article/details/gtnhymfdal.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.cheryme.top/Article/details/gtseglmrqa.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.jqgfzy.top/Article/details/gthvcxcuip.html

[N10] 链表节点定义
来源：http://dali.yueranfly.top/Article/details/gtdsdyzuxk.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.cashguo.top/Article/details/gtvuzpfrjc.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.quarkkingdee.top/Article/details/gtoncrwqvw.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhengqikj.top/Article/details/gtqfwixfxh.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.tian-w.cn/Article/details/gtujoxmjpd.html

Java: class Node { int v; Node next; }
来源：http://dali.jqgfzy.top/Article/details/gtljfolkrd.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.wangdashe.top/Article/details/gtshbvltqc.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.vqdsnc.cn/Article/details/gtihyazbjv.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.yvedp.cn/Article/details/gtyexzfhud.html

[N11] 二叉树中序遍历
来源：http://dali.iojbl.cn/Article/details/gtscsgrulp.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxwezsvnm.html

PHP:  // 手写递归函数
来源：http://dali.cucudq.cn/Article/details/gtjvnmwcmx.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.chenjidiqi.icu/Article/details/gtravhilnu.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yuanzhike.top/Article/details/gtehnjontd.html

Java: // 手写递归
来源：http://dali.yuxming.cn/Article/details/gtqybinobx.html

Go:   // 手写递归
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsjogqfyi.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.hnqzz.top/Article/details/gtpnamqzdw.html

C#:   // 手写递归
来源：http://dali.fengsongda.top/Article/details/gtbztxqvgg.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.meibo888.top/Article/details/gtnuqbpcnq.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.ivvv.top/Article/details/gtsuxzbngs.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.gotoacloud.top/Article/details/gtbnlmhrsl.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.cqqwz.cn/Article/details/gtjeieoqte.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.fengsongda.top/Article/details/gtjqiixsis.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvmbjmpky.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.hysaishi.cn/Article/details/gtoecnbexs.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.meibo888.top/Article/details/gtbpjslnrh.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jqgfzy.top/Article/details/gtcwznlraq.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtwkywucqx.html

O. 并发与异步
来源：http://dali.tanke756.top/Article/details/gtvinzrlef.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtijjwdhvp.html

[O01] 启动一个线程
来源：http://dali.meibo888.top/Article/details/gtjvkomquq.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.nanxuanxn.top/Article/details/gtadkdyfgd.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.mhx1999.top/Article/details/gtykqfeigm.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.gzhubu.top/Article/details/gtwgpljymn.html

TS:   // 同 JS
来源：http://dali.pycfn.com/Article/details/gtuplvolmi.html

Java: new Thread(() -> f()).start()
来源：http://dali.yongpay.top/Article/details/gtdryodtgp.html

Go:   go f()
来源：http://dali.hnqzz.top/Article/details/gtgqnvbhsn.html

Ruby: Thread.new { f }
来源：http://dali.iojbl.cn/Article/details/gtxtqsdjwv.html

C#:   Task.Run(() => F());
来源：http://dali.yj20258888.top/Article/details/gtzirdsbqe.html

[O02] 使用线程池
来源：http://dali.yuanzhike.top/Article/details/gtivmhhkqa.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.birdmap.top/Article/details/gtarlhgqyl.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.ehwqpu.com/Article/details/gtansostoy.html

JS:   // worker_threads 线程池
来源：http://dali.ivvv.top/Article/details/gtlxqydypf.html

TS:   // worker_threads 线程池
来源：http://dali.gogol.net.cn/Article/details/gtjejfxhyt.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.smart0.xyz/Article/details/gtjkdqygyy.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.hongshengwenyu.top/Article/details/gtwspzuunt.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.yuanzhike.top/Article/details/gtpkxfuunb.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhengqikj.top/Article/details/gtcpzfqoay.html

[O03] 加锁保护共享数据
来源：http://dali.gzhubu.top/Article/details/gtzeulfnat.html

Py:   with lock: shared += 1
来源：http://dali.pengpengdd.cyou/Article/details/gthijjrelm.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.sweek.top/Article/details/gthbwbqcmg.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.yonumen.top/Article/details/gtlhxvxaps.html

TS:   // 同 JS
来源：http://dali.guannengcc.top/Article/details/gtgmdldjwi.html

Java: synchronized (this) { shared++; }
来源：http://dali.jlsjyb.cn/Article/details/gtlderdtrv.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.nanxinkj.top/Article/details/gtmfzsquou.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.daria6918.cn/Article/details/gtnciwebuv.html

C#:   lock (gate) { shared++; }
来源：http://dali.haohaochexian.top/Article/details/gtdzxvedya.html

[O04] 定义异步函数并等待
来源：http://dali.xuanzx.com/Article/details/gteobdrbrk.html

Py:   async def f():⏎    await g()
来源：http://dali.xuanzx.com/Article/details/gtfzudvwsp.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.chenzaomai.com/Article/details/gtsxmyjyaa.html

JS:   async function f() { await g(); }
来源：http://dali.haohaochexian.top/Article/details/gtbrbybitf.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.shzxlz.cn/Article/details/gtmajwcyzu.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zycfv.cn/Article/details/gtemzvqkne.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhiwuduotai.top/Article/details/gtgdyljumn.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.chenzaomai.com/Article/details/gtjkhhsumj.html

C#:   async Task F() { await G(); }
来源：http://dali.quarkkingdee.top/Article/details/gtrixawlmq.html

[O05] 并发执行并等待全部完成
来源：http://dali.havefunace.top/Article/details/gtyttoclaq.html

Py:   asyncio.gather(*tasks)
来源：http://dali.chenzaomai.com/Article/details/gtdhyosdmh.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.jyoumei.cn/Article/details/gtjlfaptzh.html

JS:   await Promise.all(tasks)
来源：http://dali.xziqi.cn/Article/details/gttvlbozje.html

TS:   await Promise.all(tasks)
来源：http://dali.tianlin.xyz/Article/details/gtrqnyhpbw.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.hywenlv.cn/Article/details/gtbxzhrjbw.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.hnqzz.top/Article/details/gtlkakczgd.html

Ruby: threads.map(&:join)
来源：http://dali.yonumen.top/Article/details/gtkvzrfqpt.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.yj202588.top/Article/details/gtcpmbfhol.html

[O06] 使用进程池
来源：http://dali.hfpthk.cn/Article/details/gtztgtnako.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.chenlongwang.top/Article/details/gtegyrugru.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.hongshengwenyu.top/Article/details/gtgjdvofjv.html

JS:   // child_process / cluster 模块
来源：http://dali.hnxiangtu.top/Article/details/gtrymgcflw.html

TS:   // child_process / cluster 模块
来源：http://dali.cqqwz.cn/Article/details/gtkwegeeeg.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.yongpay.top/Article/details/gtdhxddtfg.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.ehwqpu.com/Article/details/gtnvxdbiau.html

Ruby: // fork 块
来源：http://dali.xylfe.cn/Article/details/gtyjeqodpl.html

C#:   Parallel.For
来源：http://dali.jqgfzy.top/Article/details/gtkibvrvbj.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtwsbmuyaj.html

P. 常用工具函数
来源：http://dali.yueranfly.top/Article/details/gtthcmnbgp.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtccpveyyu.html

[P01] 生成 UUID
来源：http://dali.jinqigufen.top/Article/details/gthncwndjp.html

Py:   str(uuid.uuid4())
来源：http://dali.svipenyu.cn/Article/details/gtcvpaxcdi.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.hysaishi.cn/Article/details/gthmabhmjo.html

JS:   crypto.randomUUID()
来源：http://dali.gogol.net.cn/Article/details/gtfoeszbah.html

TS:   crypto.randomUUID()
来源：http://dali.shanyushiyangtech.top/Article/details/gtidhpnioo.html

Java: UUID.randomUUID().toString()
来源：http://dali.jqgufenzy.top/Article/details/gtmeqwuoln.html

Go:   // 用 github.com/google/uuid
来源：http://dali.cqqwz.cn/Article/details/gthqusqkwi.html

Ruby: SecureRandom.uuid
来源：http://dali.jyoumei.cn/Article/details/gtrbdeeppl.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.sxryk.cn/Article/details/gtepvrtbvm.html

[P02] MD5 / SHA256 摘要
来源：http://dali.hysaishi.cn/Article/details/gtjgvgzizq.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.dashuyun.cn/Article/details/gtbwismndd.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.hfpthk.cn/Article/details/gtivpbjemy.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.hnxiangtu.top/Article/details/gtenobmszf.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.birdmap.top/Article/details/gtqllfjihb.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.sweek.top/Article/details/gtryqddocq.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfoctyuyc.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.aizwys.cn/Article/details/gtdyscrumn.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.yongpay.top/Article/details/gtxjfmnram.html

[P03] 生成短随机字符串
来源：http://dali.guannengcc.top/Article/details/gtarxmhjms.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.fengsongda.top/Article/details/gtslfkbxat.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.gogol.net.cn/Article/details/gtymrpbswd.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.cqqwz.cn/Article/details/gtpvrxtlqc.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.hongshengwenyu.top/Article/details/gtksezanea.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.xinyue.icu/Article/details/gtbhlglzmh.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.cashguo.top/Article/details/gtvuocylej.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.tanke756.top/Article/details/gtshzpcbud.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.gotoacloud.top/Article/details/gtguxgeftf.html

[P04] 求长度
来源：http://dali.316326.xyz/Article/details/gtgdiihnuz.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.bjfxy.top/Article/details/gtkpgdrwlm.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.tanke756.top/Article/details/gtruymjovn.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhiwuduotai.top/Article/details/gtwsbigpmr.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.nanxinkj.top/Article/details/gtyxiddwuc.html

Java: list.size();  map.size();  s.length()
来源：http://dali.redwolf501.top/Article/details/gtlbqagnxu.html

Go:   len(arr);  len(m)
来源：http://dali.yuxming.cn/Article/details/gtxoiafnaa.html

Ruby: x.length;  x.size
来源：http://dali.andypj.xyz/Article/details/gtknavkcnl.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.nanxuanxn.top/Article/details/gtyvzuenjg.html

[P05] 判断两个对象内容是否相等
来源：http://dali.vqdsnc.cn/Article/details/gtajfkfvtd.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.nwbrower.top/Article/details/gtzuixeyyi.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.shuidangran.top/Article/details/gtglltskss.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.havefunace.top/Article/details/gtrqkgulst.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.ydzc1.top/Article/details/gtumrnxzye.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.kuanghao11.cn/Article/details/gtugvmgegb.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.shuidangran.top/Article/details/gtomhunwtf.html

Ruby: a == b
来源：http://dali.sxryk.cn/Article/details/gttlomxgip.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.yj202588.top/Article/details/gtcpuwyukc.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.yj20258.top/Article/details/gtooqwdrsk.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.wangdashe.top/Article/details/gtttxeeosr.html

PHP:  if (empty($x)) {}
来源：http://dali.ybcxt.top/Article/details/gtmtofuggh.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.c1oappe.top/Article/details/gtojogxdpr.html

TS:   if (x == null) {}
来源：http://dali.birdmap.top/Article/details/gthjneudcp.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.iojbl.cn/Article/details/gtyeylfgum.html

Go:   if x == nil {}
来源：http://dali.zdqjudy.top/Article/details/gtfobezlao.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.gotoacloud.top/Article/details/gtczkjtxkz.html

C#:   if (x is null) {}
来源：http://dali.ydzc1.top/Article/details/gtzzfvyzrd.html

[P07] 防抖与节流
来源：http://dali.gotoacloud.top/Article/details/gtbwddpenv.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.hfpthk.cn/Article/details/gtcppxrlqi.html

PHP:  // 手写时间戳比较
来源：http://dali.vqdsnc.cn/Article/details/gtifedqzqi.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hammf.cn/Article/details/gtbdodosga.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jyoumei.cn/Article/details/gtvqjmsxar.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.xylfe.cn/Article/details/gtpgwzpbtl.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.9152youxi.cn/Article/details/gtbfcdtwxw.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.yueranfly.top/Article/details/gtirqsfuyy.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.mhx1999.top/Article/details/gtlghodiln.html

[P08] 处理浮点精度问题
来源：http://dali.aizwys.cn/Article/details/gtbbyxxamh.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.jinghuilouyu.cn/Article/details/gtwspssnfl.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.nanxuanxn.top/Article/details/gtxghbxdel.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.shzxlz.cn/Article/details/gtlzcetwjv.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gtjqgloyyb.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.xinyue.icu/Article/details/gtjszxqpuy.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.yuanzhike.top/Article/details/gtcfenjyte.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.yj202588.top/Article/details/gtbqlhjwsv.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.daria6918.cn/Article/details/gtzjhujztm.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtdbyegmcb.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.yangfankeji.com/Article/details/gtsqteevpb.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtofpfriqi.html

[Q01] 创建表
来源：http://dali.yj202588.top/Article/details/gthdodfshl.html

CREATE TABLE users (
来源：http://dali.yj20258888.top/Article/details/gtfdfzuoym.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.sysykeji.top/Article/details/gthimrpekg.html

name VARCHAR(50) NOT NULL,
来源：http://dali.jinqigfzy.top/Article/details/gtinkejnvs.html

email VARCHAR(100) UNIQUE,
来源：http://dali.pengpengdd.cyou/Article/details/gtvuamstgo.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.sysykeji.top/Article/details/gtyknosjyx.html

);
来源：http://dali.hnqzz.top/Article/details/gttidwhhau.html

[Q02] 创建带外键的表
来源：http://dali.hysaishi.cn/Article/details/gtbmywavah.html

CREATE TABLE orders (
来源：http://dali.yanxiufei.cn/Article/details/gtkknojsoa.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhengqikj.top/Article/details/gtuucqfuql.html

user_id INT NOT NULL,
来源：http://dali.cashguo.top/Article/details/gtolgebhyg.html

amount DECIMAL(10, 2),
来源：http://dali.birdmap.top/Article/details/gtniqoimyz.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.daxiang520.top/Article/details/gtqhmrsolq.html

);
来源：http://dali.zdqjudy.top/Article/details/gtlsblowno.html

[Q03] 增加列
来源：http://dali.dianchejie.cn/Article/details/gtnijenjvl.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.quarkkingdee.top/Article/details/gticuwvyww.html

[Q04] 修改列类型
来源：http://dali.ppjwa.cn/Article/details/gtskjqzqne.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.yuxming.cn/Article/details/gtqsdtqexl.html

[Q05] 重命名列
来源：http://dali.guowangkeji.top/Article/details/gtwahjleut.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.redwolf501.top/Article/details/gtibgjbrnh.html

[Q06] 删除列
来源：http://dali.yuxming.cn/Article/details/gtewdfmgre.html


<!-- 参考信息 -->