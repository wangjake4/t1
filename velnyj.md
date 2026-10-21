代发 wailian999

C#:   Directory.GetCurrentDirectory()
来源：http://dali.yueranfly.top/Article/details/gtlitniqji.html

[M05] 设置退出码
来源：http://dali.zdqjudy.top/Article/details/gtbznmtckf.html

Py:   sys.exit(1)
来源：http://dali.nanxuanxn.top/Article/details/gtjhhtbfyl.html

PHP:  exit(1);
来源：http://dali.havefunace.top/Article/details/gtobwysqap.html

JS:   process.exit(1)
来源：http://dali.bjfxy.top/Article/details/gtxtrtgjqs.html

TS:   process.exit(1)
来源：http://dali.9152youxi.cn/Article/details/gtqhqhutpf.html

Java: System.exit(1)
来源：http://dali.zycfv.cn/Article/details/gtajcyjfbd.html

Go:   os.Exit(1)
来源：http://dali.snrcjt.cn/Article/details/gthtfqgajj.html

Ruby: exit 1
来源：http://dali.guowangkeji.top/Article/details/gtlunmdnpc.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.ppjwa.cn/Article/details/gtvjxtpzef.html

[M06] 向标准错误输出
来源：http://dali.andypj.xyz/Article/details/gtjlqylgfk.html

Py:   print("err", file=sys.stderr)
来源：http://dali.wangshuangyany.cn/Article/details/gtsovhxygc.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.gotoacloud.top/Article/details/gtlibalqtp.html

JS:   console.error("err")
来源：http://dali.zhixingplan.top/Article/details/gtkvdedhia.html

TS:   console.error("err")
来源：http://dali.sweek.top/Article/details/gthbiwkyqv.html

Java: System.err.println("err")
来源：http://dali.hysaishi.cn/Article/details/gttedratvh.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.jianghu66.top/Article/details/gtvbaesbig.html

Ruby: warn "err"
来源：http://dali.xuetiantiany.cn/Article/details/gtvmlndmge.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.meibo888.top/Article/details/gtabivnfcx.html

[M07] 判断是否为主入口
来源：http://dali.hammf.cn/Article/details/gthasiqqmy.html

Py:   if __name__ == "__main__":
来源：http://dali.jinqigfzy.top/Article/details/gtineckhye.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.yuanzhike.top/Article/details/gttzwvlcre.html

JS:   require.main === module
来源：http://dali.tanke756.top/Article/details/gtqsozvgll.html

TS:   require.main === module
来源：http://dali.nwbrower.top/Article/details/gtedbsuiut.html

Java: public static void main(String[] args)
来源：http://dali.zhiwuduotai.top/Article/details/gtobxyteea.html

Go:   func main()
来源：http://dali.yj202588.top/Article/details/gtanuwhkwd.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.chenjidiqi.icu/Article/details/gthqvwkecp.html

C#:   static void Main(string[] args)
来源：http://dali.yuanzhike.top/Article/details/gtemuovwjl.html

[M08] 获取系统与运行时信息
来源：http://dali.gzhubu.top/Article/details/gtugtpckip.html

Py:   platform.system();  platform.python_version()
来源：http://dali.sweek.top/Article/details/gtgznovwxs.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.jqgufenzy.top/Article/details/gtrzogiopw.html

JS:   process.platform;  process.version
来源：http://dali.gogol.net.cn/Article/details/gtyvymzrac.html

TS:   process.platform;  process.version
来源：http://dali.nanxinkj.top/Article/details/gtlhbqdkie.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.shangyingyoupin.top/Article/details/gtrwhkeieq.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.daria6918.cn/Article/details/gtejzvysjm.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.wangdashe.top/Article/details/gtwyqaowvu.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.shangyingyoupin.top/Article/details/gtfdjashqu.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtjhzaftxy.html

N. 数据结构与算法
来源：http://dali.wangdashe.top/Article/details/gtkzkpgxgj.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtjypntcac.html

[N01] 二分查找（有序数组）
来源：http://dali.ppjwa.cn/Article/details/gtveukyojv.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.xuanzx.com/Article/details/gtwhjjwmnh.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.sweek.top/Article/details/gtrkqbpwkp.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.pycfn.com/Article/details/gttpcmnrds.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtonclkjuz.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.yonumen.top/Article/details/gtqamyeseg.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.fengsongda.top/Article/details/gtnualcyye.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.0kj1m.cn/Article/details/gtneeiedkx.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.svipenyu.cn/Article/details/gtgpmvdggz.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.hnxiangtu.top/Article/details/gtmlpwqmae.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.shangyingyoupin.top/Article/details/gtrvnzfeic.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.hammf.cn/Article/details/gtccsunvii.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.tian-w.cn/Article/details/gtoiktmbli.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.aizwys.cn/Article/details/gtotnqbsir.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.svipenyu.cn/Article/details/gtxglmozkr.html

Go:   slices.Sort(arr)
来源：http://dali.gaohongyu789.top/Article/details/gtweyqiwbs.html

Ruby: arr.sort
来源：http://dali.jlsjyb.cn/Article/details/gtosjcesim.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.gogol.net.cn/Article/details/gtealwcaxj.html

[N03] 快速排序（分治示例）
来源：http://dali.jianghu66.top/Article/details/gtmgbvihre.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.shanyushiyangtech.top/Article/details/gtmxjbgrfs.html

PHP:  // 递归实现，或用 usort
来源：http://dali.wangdashe.top/Article/details/gtlluvufgj.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.ehwqpu.com/Article/details/gtzcyzossd.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.xinyue.icu/Article/details/gtzojgakcy.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.haohaochexian.top/Article/details/gtqnvdmjjt.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.daria6918.cn/Article/details/gtnckxaago.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.hammf.cn/Article/details/gtdhipjfip.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.guannengcc.top/Article/details/gtjswdujgl.html

[N04] 斐波那契数列
来源：http://dali.nwbrower.top/Article/details/gtxbwyxotr.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.tianlin.xyz/Article/details/gtqkwmopil.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.snrcjt.cn/Article/details/gtnxtxwfll.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.birdmap.top/Article/details/gtdcvryexg.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.svipenyu.cn/Article/details/gtxzrwoknu.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.yuxming.cn/Article/details/gtkzlkdqpr.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.xinyue.icu/Article/details/gtfwiwnctd.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.hysaishi.cn/Article/details/gtgjkndpgk.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.nanxuanxn.top/Article/details/gtgrzbikob.html

[N05] 最大公约数
来源：http://dali.cashguo.top/Article/details/gtntfvpstf.html

Py:   math.gcd(a, b)
来源：http://dali.yuanzhike.top/Article/details/gtrquilmpg.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.ppjwa.cn/Article/details/gtfmdowewv.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfmfcvxbi.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yuxming.cn/Article/details/gtumnegthj.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.yangfankeji.com/Article/details/gtuxkyzgxc.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.jlsjyb.cn/Article/details/gtjcdeuqwu.html

Ruby: a.gcd(b)
来源：http://dali.ppjwa.cn/Article/details/gtbojqfdub.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhongyouzk.top/Article/details/gtckectrlr.html

[N06] 判断回文字符串
来源：http://dali.pengpengdd.cyou/Article/details/gtzlapoydj.html

Py:   s == s[::-1]
来源：http://dali.0kj1m.cn/Article/details/gtlbptgdwx.html

PHP:  $s === strrev($s);
来源：http://dali.zdqjudy.top/Article/details/gtahxhtkcb.html

JS:   s === [...s].reverse().join("")
来源：http://dali.gotoacloud.top/Article/details/gtapueusoc.html

TS:   s === [...s].reverse().join("")
来源：http://dali.hongshengwenyu.top/Article/details/gthntyckuc.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.feifeiyinyue.top/Article/details/gtvggsasgn.html

Go:   // 双指针从两端比较
来源：http://dali.redwolf501.top/Article/details/gtodowiugg.html

Ruby: s == s.reverse
来源：http://dali.sxryk.cn/Article/details/gtldjnshia.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.nanxinkj.top/Article/details/gtaksvjdpc.html

[N07] 两数之和（返回下标）
来源：http://dali.yueranfly.top/Article/details/gtnzcdjfio.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.jinyuanbaomall.cn/Article/details/gttldxamfa.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.cashguo.top/Article/details/gtdydljezs.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.316326.xyz/Article/details/gtgodgqxff.html

TS:   // 手写 Map<string, number>
来源：http://dali.iojbl.cn/Article/details/gtksqbwciz.html

Java: // 手写 HashMap
来源：http://dali.tianlin.xyz/Article/details/gtqrejcppm.html

Go:   // 手写 map[int]int
来源：http://dali.zhengqikj.top/Article/details/gtzlnkbypv.html

Ruby: // 手写 Hash
来源：http://dali.fengsongda.top/Article/details/gtcomvyuic.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.shanyushiyangtech.top/Article/details/gtmvqzfijq.html

[N08] 生成全排列
来源：http://dali.daria6918.cn/Article/details/gtqhygojcf.html

Py:   itertools.permutations(arr)
来源：http://dali.xuanzx.com/Article/details/gtdmhekahi.html

PHP:  // 手写递归交换
来源：http://dali.wangshuangyany.cn/Article/details/gttuletlhv.html

JS:   // 手写回溯递归
来源：http://dali.dashuyun.cn/Article/details/gtwzslahss.html

TS:   // 手写回溯递归
来源：http://dali.jianghu66.top/Article/details/gtymjkcvrj.html

Java: // 手写回溯递归
来源：http://dali.snrcjt.cn/Article/details/gtlqmxjlxm.html

Go:   // 手写回溯递归
来源：http://dali.chenjidiqi.icu/Article/details/gtehblsqbr.html

Ruby: arr.permutation.to_a
来源：http://dali.yanxiufei.cn/Article/details/gtbkfjnkwn.html

C#:   // 手写回溯递归
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyktewtku.html

[N09] 栈与队列
来源：http://dali.dianchejie.cn/Article/details/gtgkcrdwpm.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdfaaqnca.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.gaohongyu789.top/Article/details/gtshuzokas.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.chenzaomai.com/Article/details/gtrxrxcprr.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zycfv.cn/Article/details/gtydzdtgfo.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.ppjwa.cn/Article/details/gtgzutbboc.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.fengsongda.top/Article/details/gtmictkvgw.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.jianghu66.top/Article/details/gthsehmijs.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.hysaishi.cn/Article/details/gtmjotqvqp.html

[N10] 链表节点定义
来源：http://dali.yanxiufei.cn/Article/details/gtzxuufspd.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.sysykeji.top/Article/details/gtovevjgax.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.gotoacloud.top/Article/details/gtenyalvci.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.wangshuangyany.cn/Article/details/gtwrkulyup.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.havefunace.top/Article/details/gtuvohlypt.html

Java: class Node { int v; Node next; }
来源：http://dali.chenjidiqi.icu/Article/details/gtgsgdcjow.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.gaohongyu789.top/Article/details/gtvrfmzuig.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.jianghu66.top/Article/details/gtejraagbk.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.jqgfzy.top/Article/details/gtwnzvlzvt.html

[N11] 二叉树中序遍历
来源：http://dali.shuidangran.top/Article/details/gthgwgwwak.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.snrcjt.cn/Article/details/gtalxmouvg.html

PHP:  // 手写递归函数
来源：http://dali.9152youxi.cn/Article/details/gtcenisbct.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.cheryme.top/Article/details/gtdmnjolzt.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhongyouzk.top/Article/details/gtqhmgsoxj.html

Java: // 手写递归
来源：http://dali.nanxinkj.top/Article/details/gtelnufrxz.html

Go:   // 手写递归
来源：http://dali.zhongyouzk.top/Article/details/gtgdzvqdjh.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.xuanzx.com/Article/details/gtlmyctbfx.html

C#:   // 手写递归
来源：http://dali.kuanghao11.cn/Article/details/gterdcvygi.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.yvedp.cn/Article/details/gtdvkofvgm.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.svipenyu.cn/Article/details/gtlucihogk.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.redwolf501.top/Article/details/gtyuyxliin.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.redwolf501.top/Article/details/gtqunmzsay.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yanxiufei.cn/Article/details/gtwpuzjrlp.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxlmlxjzh.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.xylfe.cn/Article/details/gtyvrmkkff.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.mhx1999.top/Article/details/gtctqoditb.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.vqdsnc.cn/Article/details/gtzfagybah.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtxszbxddh.html

O. 并发与异步
来源：http://dali.c1oappe.top/Article/details/gtgfpqtlxl.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtimhnhbvq.html

[O01] 启动一个线程
来源：http://dali.cashguo.top/Article/details/gtrklpyywc.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.wangshuangyany.cn/Article/details/gtfmbtxhpz.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.chenlongwang.top/Article/details/gtfcdnonvx.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.tian-w.cn/Article/details/gtnmrbnxts.html

TS:   // 同 JS
来源：http://dali.nwbrower.top/Article/details/gtkmjvrjwv.html

Java: new Thread(() -> f()).start()
来源：http://dali.hywenlv.cn/Article/details/gtnhzywcyb.html

Go:   go f()
来源：http://dali.ppjwa.cn/Article/details/gtrrxnxkwh.html

Ruby: Thread.new { f }
来源：http://dali.yanxiufei.cn/Article/details/gtjaacvgpz.html

C#:   Task.Run(() => F());
来源：http://dali.9152youxi.cn/Article/details/gtxpsppvgs.html

[O02] 使用线程池
来源：http://dali.yueranfly.top/Article/details/gtmqycqmgk.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhixingplan.top/Article/details/gtrcszklkb.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.xuetiantiany.cn/Article/details/gtzgtglsgy.html

JS:   // worker_threads 线程池
来源：http://dali.dashuyun.cn/Article/details/gtkaqqtyud.html

TS:   // worker_threads 线程池
来源：http://dali.yvedp.cn/Article/details/gtlximyopf.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.meibo888.top/Article/details/gtbwhdybrl.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.xinyue.icu/Article/details/gtsapudxad.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.jqgufenzy.top/Article/details/gtbmcpslad.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.xuetiantiany.cn/Article/details/gtbdagrgcy.html

[O03] 加锁保护共享数据
来源：http://dali.shanyushiyangtech.top/Article/details/gteregsqef.html

Py:   with lock: shared += 1
来源：http://dali.cucudq.cn/Article/details/gtopovpjvt.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.jqgfzy.top/Article/details/gtfknzdqrt.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.shuidangran.top/Article/details/gtixbqqklk.html

TS:   // 同 JS
来源：http://dali.kuanghao11.cn/Article/details/gtxwvajgqm.html

Java: synchronized (this) { shared++; }
来源：http://dali.feifeiyinyue.top/Article/details/gtccahjihp.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.316326.xyz/Article/details/gtpsuriodl.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.jinghuilouyu.cn/Article/details/gtjxjpsbcs.html

C#:   lock (gate) { shared++; }
来源：http://dali.yonumen.top/Article/details/gtzbkmzpdh.html

[O04] 定义异步函数并等待
来源：http://dali.zhiwuduotai.top/Article/details/gtvwgtnkea.html

Py:   async def f():⏎    await g()
来源：http://dali.feifeiyinyue.top/Article/details/gtyagwtuxs.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.xinyue.icu/Article/details/gtkswkndna.html

JS:   async function f() { await g(); }
来源：http://dali.zhoulong.xyz/Article/details/gtauwoojxe.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.9152youxi.cn/Article/details/gtnekrkbpo.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrksnylzy.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.hammf.cn/Article/details/gttimdcslp.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.yanxiufei.cn/Article/details/gtkocmpcoq.html

C#:   async Task F() { await G(); }
来源：http://dali.9152youxi.cn/Article/details/gtugzvajsq.html

[O05] 并发执行并等待全部完成
来源：http://dali.yj202588.top/Article/details/gtxgcmelef.html

Py:   asyncio.gather(*tasks)
来源：http://dali.tanke756.top/Article/details/gtuwcyjhya.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.gotoacloud.top/Article/details/gtoaaoormd.html

JS:   await Promise.all(tasks)
来源：http://dali.jiagoushi.top/Article/details/gtcthiqihv.html

TS:   await Promise.all(tasks)
来源：http://dali.andypj.xyz/Article/details/gtrhtmsnpu.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.yuanzhike.top/Article/details/gtwievafby.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.jyoumei.cn/Article/details/gtldtcrsjn.html

Ruby: threads.map(&:join)
来源：http://dali.ehwqpu.com/Article/details/gtvjufhevl.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zycfv.cn/Article/details/gttztgjthq.html

[O06] 使用进程池
来源：http://dali.andypj.xyz/Article/details/gtckvgqhwz.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.ybcxt.top/Article/details/gteikqxsdy.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.ppjwa.cn/Article/details/gtizfaueen.html

JS:   // child_process / cluster 模块
来源：http://dali.hywenlv.cn/Article/details/gtmjhrryzw.html

TS:   // child_process / cluster 模块
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxkishwrd.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.fzhhl.top/Article/details/gtpumlokkb.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.c1oappe.top/Article/details/gtkavceeao.html

Ruby: // fork 块
来源：http://dali.nanxuanxn.top/Article/details/gtwrljtwvd.html

C#:   Parallel.For
来源：http://dali.gogol.net.cn/Article/details/gtswnjqvzi.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtfuppysht.html

P. 常用工具函数
来源：http://dali.shuidangran.top/Article/details/gtcyjmlatw.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtvdkcqmai.html

[P01] 生成 UUID
来源：http://dali.ehwqpu.com/Article/details/gtuwovjlpl.html

Py:   str(uuid.uuid4())
来源：http://dali.gzhubu.top/Article/details/gtwutomeef.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.tian-w.cn/Article/details/gtrknilluv.html

JS:   crypto.randomUUID()
来源：http://dali.xinyue.icu/Article/details/gtyrxjvwdb.html

TS:   crypto.randomUUID()
来源：http://dali.hammf.cn/Article/details/gtfejkcdpr.html

Java: UUID.randomUUID().toString()
来源：http://dali.kuanghao11.cn/Article/details/gtnegcrcxn.html

Go:   // 用 github.com/google/uuid
来源：http://dali.jinghuilouyu.cn/Article/details/gtixvyvwuf.html

Ruby: SecureRandom.uuid
来源：http://dali.bjfxy.top/Article/details/gtvaqmbnpe.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.cashguo.top/Article/details/gtfouynslj.html

[P02] MD5 / SHA256 摘要
来源：http://dali.ivvv.top/Article/details/gtvciwukqb.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.hongshengwenyu.top/Article/details/gttwcxdxjv.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.chenjidiqi.icu/Article/details/gtbondomuw.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.yongpay.top/Article/details/gtjqvdcpqh.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zdqjudy.top/Article/details/gtxhzhzrsk.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.yongpay.top/Article/details/gtefpdwopv.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuwuijaha.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.gotoacloud.top/Article/details/gtsifuhpyi.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.ppjwa.cn/Article/details/gtdlrrshlq.html

[P03] 生成短随机字符串
来源：http://dali.cucudq.cn/Article/details/gtgiesmmyy.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.hammf.cn/Article/details/gtiyazlusz.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.yanxiufei.cn/Article/details/gtwtlhygii.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsmdjrrsj.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.cqqwz.cn/Article/details/gtfohsfjsr.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.hysaishi.cn/Article/details/gtsrksyevv.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.meibo888.top/Article/details/gtzxtrepdf.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.cashguo.top/Article/details/gtvtmxucae.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.yj20258.top/Article/details/gtlqsrntcw.html

[P04] 求长度
来源：http://dali.guowangkeji.top/Article/details/gtbfgpcsji.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.hnqzz.top/Article/details/gtutqcjudw.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.sxryk.cn/Article/details/gtebismadj.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.tanke756.top/Article/details/gtjggvhmpq.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.gaohongyu789.top/Article/details/gtdmcoykpg.html

Java: list.size();  map.size();  s.length()
来源：http://dali.mhx1999.top/Article/details/gtusroxlct.html

Go:   len(arr);  len(m)
来源：http://dali.wangshuangyany.cn/Article/details/gtthiqpqrz.html

Ruby: x.length;  x.size
来源：http://dali.jqgfzy.top/Article/details/gtqmthghsl.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.cashguo.top/Article/details/gtnfstzqwr.html

[P05] 判断两个对象内容是否相等
来源：http://dali.gzhubu.top/Article/details/gtngsxjmot.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.sysykeji.top/Article/details/gtomxfjlnd.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.jinqigfzy.top/Article/details/gtstkcwrng.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.yuxming.cn/Article/details/gttkzedats.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.guowangkeji.top/Article/details/gtipjqaads.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.yuxming.cn/Article/details/gtosdchrmd.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.ivvv.top/Article/details/gtnvkcbmrv.html

Ruby: a == b
来源：http://dali.zycfv.cn/Article/details/gtgbgynfaq.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.jqgfzy.top/Article/details/gtcycrjhaj.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.jqgufenzy.top/Article/details/gtutgucizc.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.jqgfzy.top/Article/details/gtonqkazxr.html

PHP:  if (empty($x)) {}
来源：http://dali.xuetiantiany.cn/Article/details/gtcdufhemq.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.fengsongda.top/Article/details/gtvsguslfi.html

TS:   if (x == null) {}
来源：http://dali.tanke756.top/Article/details/gtpjgvwuud.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.birdmap.top/Article/details/gtnagkvqil.html

Go:   if x == nil {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gthzltyuzs.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.shzxlz.cn/Article/details/gtobohhqyy.html

C#:   if (x is null) {}
来源：http://dali.hfpthk.cn/Article/details/gtdualjvei.html

[P07] 防抖与节流
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpbegfcmq.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.chenzaomai.com/Article/details/gtcfgkkkfg.html

PHP:  // 手写时间戳比较
来源：http://dali.aibaodan.cn/Article/details/gtptwpmmab.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.gotoacloud.top/Article/details/gtdgfxwmkj.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hnqzz.top/Article/details/gtjckbxovy.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.havefunace.top/Article/details/gtjmkojjhq.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.pengpengdd.cyou/Article/details/gtgykkbirl.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.yuanzhike.top/Article/details/gtrubyebiy.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.tian-w.cn/Article/details/gtsemmqyby.html

[P08] 处理浮点精度问题
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcepuihed.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.haohaochexian.top/Article/details/gtbasfcmqb.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.shzxlz.cn/Article/details/gtbpfitphy.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.cucudq.cn/Article/details/gtsipumlaj.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhoulong.xyz/Article/details/gtasbmmfxf.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.iojbl.cn/Article/details/gtnbajslij.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.hnxiangtu.top/Article/details/gtidxuacyd.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.wangdashe.top/Article/details/gtnswqgoku.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.yj202588.top/Article/details/gtisibirtf.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtotlkaruw.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.shangyingyoupin.top/Article/details/gtpziompbl.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtyicpxyzq.html

[Q01] 创建表
来源：http://dali.sufxvd.cn/Article/details/gtnzvcbxpl.html

CREATE TABLE users (
来源：http://dali.sweek.top/Article/details/gtmxcfddbq.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsrrzuvss.html

name VARCHAR(50) NOT NULL,
来源：http://dali.jinghuilouyu.cn/Article/details/gtxrskpdwy.html

email VARCHAR(100) UNIQUE,
来源：http://dali.cashguo.top/Article/details/gtgjaplieg.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.havefunace.top/Article/details/gtrxbkuoam.html

);
来源：http://dali.pycfn.com/Article/details/gtvxphrswk.html

[Q02] 创建带外键的表
来源：http://dali.gzhubu.top/Article/details/gtjjxkynso.html

CREATE TABLE orders (
来源：http://dali.jqgfzy.top/Article/details/gtogzrvdje.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrckthctl.html

user_id INT NOT NULL,
来源：http://dali.pycfn.com/Article/details/gtsiuaoyph.html

amount DECIMAL(10, 2),
来源：http://dali.snrcjt.cn/Article/details/gtvtypsdgv.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiguptqkr.html

);
来源：http://dali.yuanzhike.top/Article/details/gtqmtjyjsk.html

[Q03] 增加列
来源：http://dali.yj20258888.top/Article/details/gternbqlxf.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.jlsjyb.cn/Article/details/gtvrwjbgds.html

[Q04] 修改列类型
来源：http://dali.xuanzx.com/Article/details/gtuhsuovtx.html


<!-- 参考信息 -->