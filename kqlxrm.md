代发 wailian999

C#:   Directory.GetCurrentDirectory()
来源：http://dali.hnqzz.top/Article/details/gt2inocbuoh.html

[M05] 设置退出码
来源：http://dali.nwbrower.top/Article/details/gt2sjltvyxi.html

Py:   sys.exit(1)
来源：http://dali.nanxinkj.top/Article/details/gt2pkiiytcr.html

PHP:  exit(1);
来源：http://dali.yvedp.cn/Article/details/gt2membgnka.html

JS:   process.exit(1)
来源：http://dali.gzhubu.top/Article/details/gt2luneofgz.html

TS:   process.exit(1)
来源：http://dali.cashguo.top/Article/details/gt2bwrrdwww.html

Java: System.exit(1)
来源：http://dali.shzxlz.cn/Article/details/gt2yzzschcf.html

Go:   os.Exit(1)
来源：http://dali.shangyingyoupin.top/Article/details/gt2macyxdrt.html

Ruby: exit 1
来源：http://dali.mhx1999.top/Article/details/gt2aegcmegt.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.jinghuilouyu.cn/Article/details/gt2isajnsmp.html

[M06] 向标准错误输出
来源：http://dali.guannengcc.top/Article/details/gt2aucpomkb.html

Py:   print("err", file=sys.stderr)
来源：http://dali.ydzc1.top/Article/details/gt2sifvyyga.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.snrcjt.cn/Article/details/gt2lxrgkdei.html

JS:   console.error("err")
来源：http://dali.shangyingyoupin.top/Article/details/gt2izxwjdka.html

TS:   console.error("err")
来源：http://dali.bjfxy.top/Article/details/gt2gjavtoag.html

Java: System.err.println("err")
来源：http://dali.cashguo.top/Article/details/gt2qctcdizt.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.snrcjt.cn/Article/details/gt2zgfsevyq.html

Ruby: warn "err"
来源：http://dali.gaohongyu789.top/Article/details/gt2glvovvoi.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.aizwys.cn/Article/details/gt2nvbklsyv.html

[M07] 判断是否为主入口
来源：http://dali.ppjwa.cn/Article/details/gt2pdyybgoc.html

Py:   if __name__ == "__main__":
来源：http://dali.cucudq.cn/Article/details/gt2egnmgzqm.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.vqdsnc.cn/Article/details/gt2xzevzqfi.html

JS:   require.main === module
来源：http://dali.snrcjt.cn/Article/details/gt2kpnsuusx.html

TS:   require.main === module
来源：http://dali.cucudq.cn/Article/details/gt2barehiyj.html

Java: public static void main(String[] args)
来源：http://dali.yueranfly.top/Article/details/gt2ppzlrgvm.html

Go:   func main()
来源：http://dali.vqdsnc.cn/Article/details/gt2aawzxizz.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.xylfe.cn/Article/details/gt2eeclujfg.html

C#:   static void Main(string[] args)
来源：http://dali.quarkkingdee.top/Article/details/gt2kefxxpjg.html

[M08] 获取系统与运行时信息
来源：http://dali.cucudq.cn/Article/details/gt2nunzqwxh.html

Py:   platform.system();  platform.python_version()
来源：http://dali.nanxinkj.top/Article/details/gt2doexvchv.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.chenjidiqi.icu/Article/details/gt2guhgtdsz.html

JS:   process.platform;  process.version
来源：http://dali.shzxlz.cn/Article/details/gt2fvfzkngx.html

TS:   process.platform;  process.version
来源：http://dali.chenjidiqi.icu/Article/details/gt2gyllqkmp.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.vqdsnc.cn/Article/details/gt2qdsoaffc.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.xziqi.cn/Article/details/gt2kwdwsncr.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.cdnleiting.top/Article/details/gt2tixjocpv.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.cqqwz.cn/Article/details/gt2jmfkwoav.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gt2bpbgdjjd.html

N. 数据结构与算法
来源：http://dali.birdmap.top/Article/details/gt2fwbbbsmp.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gt2zkvlfypo.html

[N01] 二分查找（有序数组）
来源：http://dali.aizwys.cn/Article/details/gt2ubuwizbd.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.ydzc1.top/Article/details/gt2ezskqcag.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.yj202588.top/Article/details/gt2jlnalcpt.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jinqigufen.top/Article/details/gt2slstryhr.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jiagoushi.top/Article/details/gt2lsfgvwcf.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.yj20258888.top/Article/details/gt2tmtfebez.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.hywenlv.cn/Article/details/gt2ubyzxnem.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.nwbrower.top/Article/details/gt2mcgiosov.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.aizwys.cn/Article/details/gt2yfzapupu.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.nanxinkj.top/Article/details/gt2paipollq.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jiagoushi.top/Article/details/gt2ogbmqdcy.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.aizwys.cn/Article/details/gt2xhjybytr.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.chenjidiqi.icu/Article/details/gt2nvffnrhw.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.xylfe.cn/Article/details/gt2vbzdetxx.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhengqikj.top/Article/details/gt2vhmxkoyv.html

Go:   slices.Sort(arr)
来源：http://dali.yuxming.cn/Article/details/gt2lkisrhtg.html

Ruby: arr.sort
来源：http://dali.zycfv.cn/Article/details/gt2jhmgegpu.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.hongshengwenyu.top/Article/details/gt2yavelfwx.html

[N03] 快速排序（分治示例）
来源：http://dali.316326.xyz/Article/details/gt2aitekhmd.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.yuxming.cn/Article/details/gt2joqiiqth.html

PHP:  // 递归实现，或用 usort
来源：http://dali.gaohongyu789.top/Article/details/gt2dchwuhlx.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.cdnleiting.top/Article/details/gt2fvbfbjlh.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2qzatzepd.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhiwuduotai.top/Article/details/gt2rvtckxss.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.fzhhl.top/Article/details/gt2qtjprrio.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.hammf.cn/Article/details/gt2crvggsti.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhoulong.xyz/Article/details/gt2jffbynir.html

[N04] 斐波那契数列
来源：http://dali.hammf.cn/Article/details/gt2cqktzxir.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.cdnleiting.top/Article/details/gt2rbfuadzg.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.c1oappe.top/Article/details/gt2apxohsco.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.kuanghao11.cn/Article/details/gt2btxoyxgj.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.pycfn.com/Article/details/gt2tcybndxk.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.aibaodan.cn/Article/details/gt2ambqrbye.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2sjmismdl.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.birdmap.top/Article/details/gt2osfnddvo.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.fzhhl.top/Article/details/gt2lbwjrrle.html

[N05] 最大公约数
来源：http://dali.cqqwz.cn/Article/details/gt2siblphma.html

Py:   math.gcd(a, b)
来源：http://dali.jqgfzy.top/Article/details/gt2dxhtuyir.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2oigqmuan.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2rmjivggy.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zdqjudy.top/Article/details/gt2czizbidr.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.gogol.net.cn/Article/details/gt2frxubzxq.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.sysykeji.top/Article/details/gt2jubvodlh.html

Ruby: a.gcd(b)
来源：http://dali.snrcjt.cn/Article/details/gt2yxmvidff.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhiwuduotai.top/Article/details/gt2arelhwds.html

[N06] 判断回文字符串
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nauihubf.html

Py:   s == s[::-1]
来源：http://dali.guannengcc.top/Article/details/gt2wtcbncil.html

PHP:  $s === strrev($s);
来源：http://dali.zhoulong.xyz/Article/details/gt2cctkrdvd.html

JS:   s === [...s].reverse().join("")
来源：http://dali.jinqigfzy.top/Article/details/gt2bxpxeded.html

TS:   s === [...s].reverse().join("")
来源：http://dali.chenzaomai.com/Article/details/gt2umzknjbf.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.fzhhl.top/Article/details/gt2wqymprmm.html

Go:   // 双指针从两端比较
来源：http://dali.chenzaomai.com/Article/details/gt2eihoqzcl.html

Ruby: s == s.reverse
来源：http://dali.316326.xyz/Article/details/gt2pprirjld.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.tanke756.top/Article/details/gt2lbliayns.html

[N07] 两数之和（返回下标）
来源：http://dali.hongshengwenyu.top/Article/details/gt2cyekejtm.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhixingplan.top/Article/details/gt2krzanhsn.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.316326.xyz/Article/details/gt2lkfkpzfo.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.shuidangran.top/Article/details/gt2yiezligr.html

TS:   // 手写 Map<string, number>
来源：http://dali.gogol.net.cn/Article/details/gt2yrqhdlum.html

Java: // 手写 HashMap
来源：http://dali.dianchejie.cn/Article/details/gt2ymqegwfv.html

Go:   // 手写 map[int]int
来源：http://dali.hywenlv.cn/Article/details/gt2lukucnmm.html

Ruby: // 手写 Hash
来源：http://dali.316326.xyz/Article/details/gt2ejzabflh.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.hywenlv.cn/Article/details/gt2yopprbvn.html

[N08] 生成全排列
来源：http://dali.haohaochexian.top/Article/details/gt2tgzayufq.html

Py:   itertools.permutations(arr)
来源：http://dali.gotoacloud.top/Article/details/gt2vtvdjirn.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2pxgmalpy.html

JS:   // 手写回溯递归
来源：http://dali.c1oappe.top/Article/details/gt2aauqxabn.html

TS:   // 手写回溯递归
来源：http://dali.ybcxt.top/Article/details/gt2efcrwbjd.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2hoadvpjl.html

Go:   // 手写回溯递归
来源：http://dali.nwbrower.top/Article/details/gt2zqiidmqo.html

Ruby: arr.permutation.to_a
来源：http://dali.bjfxy.top/Article/details/gt2noyjglcv.html

C#:   // 手写回溯递归
来源：http://dali.nanxuanxn.top/Article/details/gt2lyryqdja.html

[N09] 栈与队列
来源：http://dali.hfpthk.cn/Article/details/gt2xfnbohyr.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhoulong.xyz/Article/details/gt2okhdhvlv.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.shangyingyoupin.top/Article/details/gt2wenwfrcs.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.svipenyu.cn/Article/details/gt2qktyiubu.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.jlsjyb.cn/Article/details/gt2xotxkjvy.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.guannengcc.top/Article/details/gt2ahdtwzik.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.havefunace.top/Article/details/gt2tlpixrao.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.guowangkeji.top/Article/details/gt2vkmchrzg.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.aizwys.cn/Article/details/gt2ppfrhvji.html

[N10] 链表节点定义
来源：http://dali.xylfe.cn/Article/details/gt2nkxylhvq.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.chenjidiqi.icu/Article/details/gt2buldzfof.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.sxryk.cn/Article/details/gt2hftmxjaq.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.bjfxy.top/Article/details/gt2pehvlhze.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.snrcjt.cn/Article/details/gt2bnoxhpja.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pdabrlat.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.guannengcc.top/Article/details/gt2fjwnpfjp.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhongyouzk.top/Article/details/gt2gcxdcayv.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.birdmap.top/Article/details/gt2uxsbzzyq.html

[N11] 二叉树中序遍历
来源：http://dali.xinyue.icu/Article/details/gt2lwnsmdmo.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.xuanzx.com/Article/details/gt2jaetqnsn.html

PHP:  // 手写递归函数
来源：http://dali.316326.xyz/Article/details/gt2teuafxou.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.316326.xyz/Article/details/gt2lxbzltdd.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zdqjudy.top/Article/details/gt2qesilcfb.html

Java: // 手写递归
来源：http://dali.yueranfly.top/Article/details/gt2qdwksasw.html

Go:   // 手写递归
来源：http://dali.mhx1999.top/Article/details/gt2ssutammc.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhoulong.xyz/Article/details/gt2jeprvhsb.html

C#:   // 手写递归
来源：http://dali.gotoacloud.top/Article/details/gt2aumxbapm.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.redwolf501.top/Article/details/gt2iylhjcbf.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.hywenlv.cn/Article/details/gt2iglirwlv.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.havefunace.top/Article/details/gt2qkcgrcex.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhiwuduotai.top/Article/details/gt2snfvfgvd.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.xuanzx.com/Article/details/gt2ibsgryiz.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.cheryme.top/Article/details/gt2xiootmfm.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.daria6918.cn/Article/details/gt2bmeoboly.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.yuxming.cn/Article/details/gt2xutdyvlf.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.gotoacloud.top/Article/details/gt2jndvftos.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gt2ymzmbynl.html

O. 并发与异步
来源：http://dali.sweek.top/Article/details/gt2uxmjhtbc.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gt2mqgssvpe.html

[O01] 启动一个线程
来源：http://dali.aibaodan.cn/Article/details/gt2ktjikxwa.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.yj20258.top/Article/details/gt2aqkerzjp.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.meibo888.top/Article/details/gt2kdjrxovz.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhongyouzk.top/Article/details/gt2qfquebtw.html

TS:   // 同 JS
来源：http://dali.chenjidiqi.icu/Article/details/gt2zhscudpw.html

Java: new Thread(() -> f()).start()
来源：http://dali.hnqzz.top/Article/details/gt2cgpkrdaa.html

Go:   go f()
来源：http://dali.9152youxi.cn/Article/details/gt2zjmwirfp.html

Ruby: Thread.new { f }
来源：http://dali.cucudq.cn/Article/details/gt2tmgtvxfp.html

C#:   Task.Run(() => F());
来源：http://dali.yangfankeji.com/Article/details/gt2wbvmktqx.html

[O02] 使用线程池
来源：http://dali.xuetiantiany.cn/Article/details/gt2elcazoos.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.gogol.net.cn/Article/details/gt2snypzwcx.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.chenjidiqi.icu/Article/details/gt2mqjndexq.html

JS:   // worker_threads 线程池
来源：http://dali.wangshuangyany.cn/Article/details/gt2ncafjhfi.html

TS:   // worker_threads 线程池
来源：http://dali.svipenyu.cn/Article/details/gt2ursgqwne.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.hywenlv.cn/Article/details/gt2ijnkhglk.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.mhx1999.top/Article/details/gt2xvlhgidl.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.wangshuangyany.cn/Article/details/gt2dvljnetk.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.xuetiantiany.cn/Article/details/gt2drfztfug.html

[O03] 加锁保护共享数据
来源：http://dali.jinghuilouyu.cn/Article/details/gt2evsdjqbp.html

Py:   with lock: shared += 1
来源：http://dali.ivvv.top/Article/details/gt2lazgmonp.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.316326.xyz/Article/details/gt2qyltlhvm.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.c1oappe.top/Article/details/gt2tityivkj.html

TS:   // 同 JS
来源：http://dali.andypj.xyz/Article/details/gt2xbenszoa.html

Java: synchronized (this) { shared++; }
来源：http://dali.sxryk.cn/Article/details/gt2mjlqdcyh.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.jiagoushi.top/Article/details/gt2yescopqf.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.yueranfly.top/Article/details/gt2ajqqfmni.html

C#:   lock (gate) { shared++; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qratshyp.html

[O04] 定义异步函数并等待
来源：http://dali.ybcxt.top/Article/details/gt2gyswjnwe.html

Py:   async def f():⏎    await g()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nulevbku.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.tanke756.top/Article/details/gt2yupuhakk.html

JS:   async function f() { await g(); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2sqcgukar.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.bjfxy.top/Article/details/gt2jdknrbcy.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.snrcjt.cn/Article/details/gt2bqedphmq.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.yj20258.top/Article/details/gt2ahhufqlv.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.cucudq.cn/Article/details/gt2fhreqruv.html

C#:   async Task F() { await G(); }
来源：http://dali.hnxiangtu.top/Article/details/gt2uvnowywa.html

[O05] 并发执行并等待全部完成
来源：http://dali.shanyushiyangtech.top/Article/details/gt2upsmasxy.html

Py:   asyncio.gather(*tasks)
来源：http://dali.yangfankeji.com/Article/details/gt2oogriulh.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.nanxuanxn.top/Article/details/gt2tdakgwkz.html

JS:   await Promise.all(tasks)
来源：http://dali.wangdashe.top/Article/details/gt2bjoothdc.html

TS:   await Promise.all(tasks)
来源：http://dali.9152youxi.cn/Article/details/gt2cowwnvhq.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.ivvv.top/Article/details/gt2mjonmxdg.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.mhx1999.top/Article/details/gt2pxcqpcwo.html

Ruby: threads.map(&:join)
来源：http://dali.hywenlv.cn/Article/details/gt2xytylftu.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.cashguo.top/Article/details/gt2tpgkplfb.html

[O06] 使用进程池
来源：http://dali.chenjidiqi.icu/Article/details/gt2ajucenso.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.gotoacloud.top/Article/details/gt2geyocafk.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.shangyingyoupin.top/Article/details/gt2fmbhtuhe.html

JS:   // child_process / cluster 模块
来源：http://dali.dianchejie.cn/Article/details/gt2szabgicr.html

TS:   // child_process / cluster 模块
来源：http://dali.shzxlz.cn/Article/details/gt2fydmqsnw.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.tianlin.xyz/Article/details/gt2icqjzrsw.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.kuanghao11.cn/Article/details/gt2ugnqggjj.html

Ruby: // fork 块
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bckuqwvc.html

C#:   Parallel.For
来源：http://dali.ivvv.top/Article/details/gt2mmxriiod.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gt2mwtzgnul.html

P. 常用工具函数
来源：http://dali.sweek.top/Article/details/gt2ifzhvzkj.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gt2reqhtrtg.html

[P01] 生成 UUID
来源：http://dali.svipenyu.cn/Article/details/gt2ebkxfvku.html

Py:   str(uuid.uuid4())
来源：http://dali.sxryk.cn/Article/details/gt2imdqstov.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.snrcjt.cn/Article/details/gt2zitrwmpc.html

JS:   crypto.randomUUID()
来源：http://dali.gotoacloud.top/Article/details/gt2evllinak.html

TS:   crypto.randomUUID()
来源：http://dali.daria6918.cn/Article/details/gt2lytgxamb.html

Java: UUID.randomUUID().toString()
来源：http://dali.guowangkeji.top/Article/details/gt2neusqici.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhengqikj.top/Article/details/gt2xtnvrkfd.html

Ruby: SecureRandom.uuid
来源：http://dali.fengsongda.top/Article/details/gt2qcpmidet.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.jqgufenzy.top/Article/details/gt2mutixoib.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zdqjudy.top/Article/details/gt2muobetsc.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.gotoacloud.top/Article/details/gt2ndjqzvlu.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.havefunace.top/Article/details/gt2dwciciko.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.yueranfly.top/Article/details/gt2ydthqzjz.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.jyoumei.cn/Article/details/gt2iaiwqhyf.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.wangdashe.top/Article/details/gt2nycsckqu.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhixingplan.top/Article/details/gt2fyvmbbyv.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.gotoacloud.top/Article/details/gt2ttilpgpr.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.iojbl.cn/Article/details/gt2imnriqxy.html

[P03] 生成短随机字符串
来源：http://dali.zdqjudy.top/Article/details/gt2howdytbn.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.9152youxi.cn/Article/details/gt2uggdchmg.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.cheryme.top/Article/details/gt2fnyvbcdc.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.haohaochexian.top/Article/details/gt2rrvhoxat.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.hfpthk.cn/Article/details/gt2fupmxloy.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.jqgfzy.top/Article/details/gt2rmxbgqzv.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.hnxiangtu.top/Article/details/gt2ebwuhebr.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.iojbl.cn/Article/details/gt2fxyovynh.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.hnxiangtu.top/Article/details/gt2srzvbrne.html

[P04] 求长度
来源：http://dali.hnxiangtu.top/Article/details/gt2pvwscast.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.vqdsnc.cn/Article/details/gt2baraihrw.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.snrcjt.cn/Article/details/gt2ufewcohu.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.haohaochexian.top/Article/details/gt2sfrzuafe.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhengqikj.top/Article/details/gt2xhazfijm.html

Java: list.size();  map.size();  s.length()
来源：http://dali.yanxiufei.cn/Article/details/gt2objhirmj.html

Go:   len(arr);  len(m)
来源：http://dali.haohaochexian.top/Article/details/gt2uxyarvdf.html

Ruby: x.length;  x.size
来源：http://dali.dashuyun.cn/Article/details/gt2gvxpojwk.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.sweek.top/Article/details/gt2nqgczycp.html

[P05] 判断两个对象内容是否相等
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2aqoxtiuc.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.gzhubu.top/Article/details/gt2udfnytsr.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.sweek.top/Article/details/gt2dqohpejv.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhoulong.xyz/Article/details/gt2fdtkntrg.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.nanxinkj.top/Article/details/gt2ovrdqpty.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.vqdsnc.cn/Article/details/gt2wzihehpa.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.tianlin.xyz/Article/details/gt2cqzstxqj.html

Ruby: a == b
来源：http://dali.9152youxi.cn/Article/details/gt2xuqdizzv.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fyckvqex.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lshycppl.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zycfv.cn/Article/details/gt2lopypjpg.html

PHP:  if (empty($x)) {}
来源：http://dali.jinqigfzy.top/Article/details/gt2khomeytf.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.dashuyun.cn/Article/details/gt2foadjitb.html

TS:   if (x == null) {}
来源：http://dali.tanke756.top/Article/details/gt2rsxkaqqr.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2skpexscn.html

Go:   if x == nil {}
来源：http://dali.daria6918.cn/Article/details/gt2flhxecer.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fhkommnu.html

C#:   if (x is null) {}
来源：http://dali.chenlongwang.top/Article/details/gt2fiysmoff.html

[P07] 防抖与节流
来源：http://dali.nwbrower.top/Article/details/gt2zkmbdfhm.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.dianchejie.cn/Article/details/gt2roybdodu.html

PHP:  // 手写时间戳比较
来源：http://dali.ppjwa.cn/Article/details/gt2yhmvlxeo.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jinqigfzy.top/Article/details/gt2uylccvmv.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zycfv.cn/Article/details/gt2bnplhrus.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.hnqzz.top/Article/details/gt2thnpdgnf.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.cucudq.cn/Article/details/gt2slzwspck.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lcevqkup.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2bwgtixtz.html

[P08] 处理浮点精度问题
来源：http://dali.andypj.xyz/Article/details/gt2acamcymg.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.dashuyun.cn/Article/details/gt2taanyvjj.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.daxiang520.top/Article/details/gt2qkdhbkqn.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.birdmap.top/Article/details/gt2hisvdusi.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.nanxinkj.top/Article/details/gt2ucdrcmiq.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.pengpengdd.cyou/Article/details/gt2pazonuic.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.pengpengdd.cyou/Article/details/gt2jnotbvoz.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.andypj.xyz/Article/details/gt2uelnxlom.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.sufxvd.cn/Article/details/gt2owbgnxcy.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gt2hcxhpylh.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.jqgfzy.top/Article/details/gt2ydmfchpo.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gt2agkvoakh.html

[Q01] 创建表
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vfueffgx.html

CREATE TABLE users (
来源：http://dali.cdnleiting.top/Article/details/gt2xxmehgiq.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yvedp.cn/Article/details/gt2cygqbfyi.html

name VARCHAR(50) NOT NULL,
来源：http://dali.nwbrower.top/Article/details/gt2voyyagsm.html

email VARCHAR(100) UNIQUE,
来源：http://dali.hongshengwenyu.top/Article/details/gt2tpkxotrp.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.cashguo.top/Article/details/gt2zxfdtcft.html

);
来源：http://dali.vqdsnc.cn/Article/details/gt2oamnuedf.html

[Q02] 创建带外键的表
来源：http://dali.vqdsnc.cn/Article/details/gt2hdfgtqwf.html

CREATE TABLE orders (
来源：http://dali.guowangkeji.top/Article/details/gt2phmeivch.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.daxiang520.top/Article/details/gt2yflficmm.html

user_id INT NOT NULL,
来源：http://dali.aizwys.cn/Article/details/gt2wnwsshem.html

amount DECIMAL(10, 2),
来源：http://dali.gaohongyu789.top/Article/details/gt2sfwryyax.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.tanke756.top/Article/details/gt2tkjwacfs.html

);
来源：http://dali.jlsjyb.cn/Article/details/gt2ejzbakvp.html

[Q03] 增加列
来源：http://dali.zhixingplan.top/Article/details/gt2tiveoecs.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.jlsjyb.cn/Article/details/gt2jxdzshth.html

[Q04] 修改列类型
来源：http://dali.sweek.top/Article/details/gt2hegkaphc.html


<!-- 参考信息 -->