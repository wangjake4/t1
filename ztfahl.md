代发 wailian999

TS:   process.cwd()
来源：http://dali.ppjwa.cn/Article/details/gt2upfkzgpo.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.gogol.net.cn/Article/details/gt2keuehsim.html

Go:   os.Getwd()
来源：http://dali.aibaodan.cn/Article/details/gt2xdyrwflz.html

Ruby: Dir.pwd
来源：http://dali.hfpthk.cn/Article/details/gt2apbzadse.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.jiagoushi.top/Article/details/gt2qydumqrp.html

[M05] 设置退出码
来源：http://dali.gogol.net.cn/Article/details/gt2gtyfnswb.html

Py:   sys.exit(1)
来源：http://dali.hammf.cn/Article/details/gt2jduxzyia.html

PHP:  exit(1);
来源：http://dali.yanxiufei.cn/Article/details/gt2lkzmejyx.html

JS:   process.exit(1)
来源：http://dali.ivvv.top/Article/details/gt2igokcyby.html

TS:   process.exit(1)
来源：http://dali.cucudq.cn/Article/details/gt2pepqkuot.html

Java: System.exit(1)
来源：http://dali.ivvv.top/Article/details/gt2vkpzdyyf.html

Go:   os.Exit(1)
来源：http://dali.jianghu66.top/Article/details/gt2hucywkub.html

Ruby: exit 1
来源：http://dali.hfpthk.cn/Article/details/gt2xzilhmbu.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.quarkkingdee.top/Article/details/gt2jprtwnuh.html

[M06] 向标准错误输出
来源：http://dali.nwbrower.top/Article/details/gt2tscmresg.html

Py:   print("err", file=sys.stderr)
来源：http://dali.jqgufenzy.top/Article/details/gt2qqfznztp.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.hongshengwenyu.top/Article/details/gt2kmboqgzo.html

JS:   console.error("err")
来源：http://dali.pengpengdd.cyou/Article/details/gt2ydoswuqy.html

TS:   console.error("err")
来源：http://dali.guowangkeji.top/Article/details/gt2oaovqlog.html

Java: System.err.println("err")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zztvmpji.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.dianchejie.cn/Article/details/gt2itqrbapd.html

Ruby: warn "err"
来源：http://dali.pycfn.com/Article/details/gt2spprvsdm.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.cqqwz.cn/Article/details/gt2jgmzmzrx.html

[M07] 判断是否为主入口
来源：http://dali.nwbrower.top/Article/details/gt2dxasoapi.html

Py:   if __name__ == "__main__":
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wsoloqap.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.havefunace.top/Article/details/gt2hugxwlad.html

JS:   require.main === module
来源：http://dali.redwolf501.top/Article/details/gt2ynxnivea.html

TS:   require.main === module
来源：http://dali.316326.xyz/Article/details/gt2juyyqgat.html

Java: public static void main(String[] args)
来源：http://dali.hfpthk.cn/Article/details/gt2rpnnkgng.html

Go:   func main()
来源：http://dali.jinqigfzy.top/Article/details/gt2unesatfc.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.hywenlv.cn/Article/details/gt2cqyhknan.html

C#:   static void Main(string[] args)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vywboiyo.html

[M08] 获取系统与运行时信息
来源：http://dali.cheryme.top/Article/details/gt2bmnchapr.html

Py:   platform.system();  platform.python_version()
来源：http://dali.gzhubu.top/Article/details/gt2gtpdrinl.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.sxryk.cn/Article/details/gt2cykdrbax.html

JS:   process.platform;  process.version
来源：http://dali.gotoacloud.top/Article/details/gt2ytzkxktl.html

TS:   process.platform;  process.version
来源：http://dali.havefunace.top/Article/details/gt2wjxvtqls.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.quarkkingdee.top/Article/details/gt2tqpcsumk.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.vqdsnc.cn/Article/details/gt2zypzkogn.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhoulong.xyz/Article/details/gt2eopslfgg.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.daxiang520.top/Article/details/gt2vcfcrcbg.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gt2jifzeamu.html

N. 数据结构与算法
来源：http://dali.jinqigufen.top/Article/details/gt2dvswcagt.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gt2prtfbvhn.html

[N01] 二分查找（有序数组）
来源：http://dali.fzhhl.top/Article/details/gt2boyarbjc.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.gaohongyu789.top/Article/details/gt2dfnpbdxh.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.c1oappe.top/Article/details/gt2bqfccswz.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.gzhubu.top/Article/details/gt2qcskbkwk.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yonumen.top/Article/details/gt2ydlrzspr.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.cashguo.top/Article/details/gt2kmzunwtf.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.ppjwa.cn/Article/details/gt2faqumbjg.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.jiagoushi.top/Article/details/gt2zugoncoc.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.aibaodan.cn/Article/details/gt2vdasqokj.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.chenjidiqi.icu/Article/details/gt2kbiaimhb.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.hfpthk.cn/Article/details/gt2tcdwrhss.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.sweek.top/Article/details/gt2telacvyj.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.daxiang520.top/Article/details/gt2syptceif.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhengqikj.top/Article/details/gt2flqvzadf.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.yangfankeji.com/Article/details/gt2wvolcjss.html

Go:   slices.Sort(arr)
来源：http://dali.0kj1m.cn/Article/details/gt2mvthbmcm.html

Ruby: arr.sort
来源：http://dali.fzhhl.top/Article/details/gt2rnvqdhty.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.dianchejie.cn/Article/details/gt2hxmmteov.html

[N03] 快速排序（分治示例）
来源：http://dali.ivvv.top/Article/details/gt2yhytfrbj.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.xuetiantiany.cn/Article/details/gt2qevhwyrd.html

PHP:  // 递归实现，或用 usort
来源：http://dali.yongpay.top/Article/details/gt2ehintdhe.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.daria6918.cn/Article/details/gt2wpfhifvp.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.ybcxt.top/Article/details/gt2xmiwwgxk.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.hnqzz.top/Article/details/gt2wxuxcikv.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rlexmezx.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.sysykeji.top/Article/details/gt2urzjxbjt.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.andypj.xyz/Article/details/gt2krulndpv.html

[N04] 斐波那契数列
来源：http://dali.xylfe.cn/Article/details/gt2mziixqse.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.feifeiyinyue.top/Article/details/gt2rfcnicul.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.mhx1999.top/Article/details/gt2qtezhxgd.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.redwolf501.top/Article/details/gt2mzusbzjr.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.tanke756.top/Article/details/gt2osblngef.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.jianghu66.top/Article/details/gt2bbdkbqgd.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pesrckuj.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.mhx1999.top/Article/details/gt2ifhdnaot.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nwbxdpmo.html

[N05] 最大公约数
来源：http://dali.yongpay.top/Article/details/gt2svduvfly.html

Py:   math.gcd(a, b)
来源：http://dali.yuxming.cn/Article/details/gt2qbaijwxa.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.9152youxi.cn/Article/details/gt2twrbriia.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.pycfn.com/Article/details/gt2umbamfwt.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.sweek.top/Article/details/gt2cfhanmik.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2mfxgpikq.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.nanxinkj.top/Article/details/gt2eavjmlxm.html

Ruby: a.gcd(b)
来源：http://dali.0kj1m.cn/Article/details/gt2vhumjlqg.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mforhlnx.html

[N06] 判断回文字符串
来源：http://dali.cucudq.cn/Article/details/gt2wubuylpy.html

Py:   s == s[::-1]
来源：http://dali.cdnleiting.top/Article/details/gt2lfjosznj.html

PHP:  $s === strrev($s);
来源：http://dali.dashuyun.cn/Article/details/gt2wmpyvnvc.html

JS:   s === [...s].reverse().join("")
来源：http://dali.yuanzhike.top/Article/details/gt2pspeipyo.html

TS:   s === [...s].reverse().join("")
来源：http://dali.pycfn.com/Article/details/gt2sfrmjdsp.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.yueranfly.top/Article/details/gt2yhwytoyu.html

Go:   // 双指针从两端比较
来源：http://dali.jiagoushi.top/Article/details/gt2citswttc.html

Ruby: s == s.reverse
来源：http://dali.daria6918.cn/Article/details/gt2ursaqewf.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.aibaodan.cn/Article/details/gt2qjvinkky.html

[N07] 两数之和（返回下标）
来源：http://dali.xylfe.cn/Article/details/gt2hultiqte.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.sufxvd.cn/Article/details/gt2eyoeetuf.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2umgtklff.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.jinqigufen.top/Article/details/gt2ckvxxbgr.html

TS:   // 手写 Map<string, number>
来源：http://dali.redwolf501.top/Article/details/gt2dygiqjpy.html

Java: // 手写 HashMap
来源：http://dali.cdnleiting.top/Article/details/gt2brtoqlci.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2cglcwytb.html

Ruby: // 手写 Hash
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ogiytemi.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.cheryme.top/Article/details/gt2ergkuegx.html

[N08] 生成全排列
来源：http://dali.tianlin.xyz/Article/details/gt2qdykkurv.html

Py:   itertools.permutations(arr)
来源：http://dali.dianchejie.cn/Article/details/gt2dwmkiuiz.html

PHP:  // 手写递归交换
来源：http://dali.vqdsnc.cn/Article/details/gt2rhvjoyte.html

JS:   // 手写回溯递归
来源：http://dali.jinqigfzy.top/Article/details/gt2yybzlmyc.html

TS:   // 手写回溯递归
来源：http://dali.c1oappe.top/Article/details/gt2oltnncbn.html

Java: // 手写回溯递归
来源：http://dali.iojbl.cn/Article/details/gt2lowuyfqe.html

Go:   // 手写回溯递归
来源：http://dali.316326.xyz/Article/details/gt2lklkvsiq.html

Ruby: arr.permutation.to_a
来源：http://dali.zhixingplan.top/Article/details/gt2woqbutef.html

C#:   // 手写回溯递归
来源：http://dali.cashguo.top/Article/details/gt2bfhgawqs.html

[N09] 栈与队列
来源：http://dali.snrcjt.cn/Article/details/gt2xjrqvbjf.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.yj202588.top/Article/details/gt2fzdwgtly.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.sysykeji.top/Article/details/gt2tihcylkz.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.cucudq.cn/Article/details/gt2dzoaoefa.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.hnxiangtu.top/Article/details/gt2jnqimcjl.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.feifeiyinyue.top/Article/details/gt2ecnfgzsz.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.ydzc1.top/Article/details/gt2oqwgtsho.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.sxryk.cn/Article/details/gt2fffpivdf.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.cdnleiting.top/Article/details/gt2aqzwxkpi.html

[N10] 链表节点定义
来源：http://dali.aizwys.cn/Article/details/gt2nqugkhqr.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhongyouzk.top/Article/details/gt2eykorxwc.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.smart0.xyz/Article/details/gt2juqwvhqs.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhengqikj.top/Article/details/gt2eenwkcqu.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.guannengcc.top/Article/details/gt2hhuybwcx.html

Java: class Node { int v; Node next; }
来源：http://dali.dashuyun.cn/Article/details/gt2osnvtozf.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.yangfankeji.com/Article/details/gt2wphyfrwm.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2luwkzojo.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.jyoumei.cn/Article/details/gt2epawbesk.html

[N11] 二叉树中序遍历
来源：http://dali.guowangkeji.top/Article/details/gt2hlgxuvnm.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.tanke756.top/Article/details/gt2kqevxdnf.html

PHP:  // 手写递归函数
来源：http://dali.andypj.xyz/Article/details/gt2nllcphwh.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.cdnleiting.top/Article/details/gt2lfpvehue.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.xuanzx.com/Article/details/gt2gpcreccb.html

Java: // 手写递归
来源：http://dali.chenzaomai.com/Article/details/gt2ijqgviyj.html

Go:   // 手写递归
来源：http://dali.cqqwz.cn/Article/details/gt2sxskgfic.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.jyoumei.cn/Article/details/gt2nvtqcqsq.html

C#:   // 手写递归
来源：http://dali.sysykeji.top/Article/details/gt2lnrhrhpi.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.tianlin.xyz/Article/details/gt2avqckksh.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.jlsjyb.cn/Article/details/gt2vhlsbxwp.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.cheryme.top/Article/details/gt2kvmwgbpy.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.mhx1999.top/Article/details/gt2wfglreag.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.ybcxt.top/Article/details/gt2lakiuixt.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zycfv.cn/Article/details/gt2azjlowdx.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jwskrwei.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.sufxvd.cn/Article/details/gt2saqwjhjg.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jeolpbyq.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jmicqvbv.html

O. 并发与异步
来源：http://dali.316326.xyz/Article/details/gt2bjylbglu.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jsklacri.html

[O01] 启动一个线程
来源：http://dali.svipenyu.cn/Article/details/gt2doaykvnm.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.gogol.net.cn/Article/details/gt2gccxdkgi.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.yuxming.cn/Article/details/gt2twrcvgpb.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.0kj1m.cn/Article/details/gt2zerhabng.html

TS:   // 同 JS
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lzdqiafd.html

Java: new Thread(() -> f()).start()
来源：http://dali.svipenyu.cn/Article/details/gt2bohdcehx.html

Go:   go f()
来源：http://dali.guannengcc.top/Article/details/gt2ngnxlzby.html

Ruby: Thread.new { f }
来源：http://dali.hnxiangtu.top/Article/details/gt2aftzoxks.html

C#:   Task.Run(() => F());
来源：http://dali.yueranfly.top/Article/details/gt2rfzquuah.html

[O02] 使用线程池
来源：http://dali.yj202588.top/Article/details/gt2cryxfyhb.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.yongpay.top/Article/details/gt2gueotpnf.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.aibaodan.cn/Article/details/gt2rzuakwba.html

JS:   // worker_threads 线程池
来源：http://dali.mhx1999.top/Article/details/gt2nteccwpy.html

TS:   // worker_threads 线程池
来源：http://dali.cucudq.cn/Article/details/gt2urkusjwk.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.yuanzhike.top/Article/details/gt2rysqcerq.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.jianghu66.top/Article/details/gt2rdmadelc.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.tanke756.top/Article/details/gt2sohmqteg.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.ivvv.top/Article/details/gt2kjijcdyu.html

[O03] 加锁保护共享数据
来源：http://dali.vqdsnc.cn/Article/details/gt2ogdovocq.html

Py:   with lock: shared += 1
来源：http://dali.birdmap.top/Article/details/gt2hdtffftf.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.0kj1m.cn/Article/details/gt2sfxqcyfa.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.gogol.net.cn/Article/details/gt2frauzxfz.html

TS:   // 同 JS
来源：http://dali.smart0.xyz/Article/details/gt2ltnqnasy.html

Java: synchronized (this) { shared++; }
来源：http://dali.chenzaomai.com/Article/details/gt2gqdmrkiw.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhixingplan.top/Article/details/gt2dhhzarou.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.hfpthk.cn/Article/details/gt2kaeyltcf.html

C#:   lock (gate) { shared++; }
来源：http://dali.jqgfzy.top/Article/details/gt2weawviql.html

[O04] 定义异步函数并等待
来源：http://dali.chenzaomai.com/Article/details/gt2messaarb.html

Py:   async def f():⏎    await g()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pauvspmw.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.aizwys.cn/Article/details/gt2snxskuas.html

JS:   async function f() { await g(); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wvtsnxqz.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.cheryme.top/Article/details/gt2kurmftcz.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.yanxiufei.cn/Article/details/gt2yamghviy.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.sxryk.cn/Article/details/gt2kwkwimmx.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.svipenyu.cn/Article/details/gt2vviddabz.html

C#:   async Task F() { await G(); }
来源：http://dali.nanxinkj.top/Article/details/gt2ppieocet.html

[O05] 并发执行并等待全部完成
来源：http://dali.hywenlv.cn/Article/details/gt2zqqxlami.html

Py:   asyncio.gather(*tasks)
来源：http://dali.316326.xyz/Article/details/gt2nlcubotd.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.hnqzz.top/Article/details/gt2xcjohgjv.html

JS:   await Promise.all(tasks)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qlomvada.html

TS:   await Promise.all(tasks)
来源：http://dali.pengpengdd.cyou/Article/details/gt2lajfjyxq.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.gogol.net.cn/Article/details/gt2uocemakt.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.hywenlv.cn/Article/details/gt2ofpwcooa.html

Ruby: threads.map(&:join)
来源：http://dali.chenzaomai.com/Article/details/gt2babttxyj.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.c1oappe.top/Article/details/gt2xgxyypbt.html

[O06] 使用进程池
来源：http://dali.kuanghao11.cn/Article/details/gt2pgnmcjqn.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.gotoacloud.top/Article/details/gt2apujptap.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.jinghuilouyu.cn/Article/details/gt2njvqzdaf.html

JS:   // child_process / cluster 模块
来源：http://dali.aizwys.cn/Article/details/gt2rfcsteio.html

TS:   // child_process / cluster 模块
来源：http://dali.xziqi.cn/Article/details/gt2autmctoy.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.guannengcc.top/Article/details/gt2vbzsvpcp.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.meibo888.top/Article/details/gt2xcwspofb.html

Ruby: // fork 块
来源：http://dali.wangshuangyany.cn/Article/details/gt2kvynbmmo.html

C#:   Parallel.For
来源：http://dali.tian-w.cn/Article/details/gt2asgxzfwz.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gt2dtsbuorz.html

P. 常用工具函数
来源：http://dali.sufxvd.cn/Article/details/gt2ynwjrnss.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gt2morqqzfi.html

[P01] 生成 UUID
来源：http://dali.guowangkeji.top/Article/details/gt2sjwhuzer.html

Py:   str(uuid.uuid4())
来源：http://dali.ivvv.top/Article/details/gt2hgchjjye.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.xuetiantiany.cn/Article/details/gt2nperxfjk.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2xfjqyhge.html

TS:   crypto.randomUUID()
来源：http://dali.gzhubu.top/Article/details/gt2gkkmlyfu.html

Java: UUID.randomUUID().toString()
来源：http://dali.guowangkeji.top/Article/details/gt2hvbjmqia.html

Go:   // 用 github.com/google/uuid
来源：http://dali.iojbl.cn/Article/details/gt2ndmjsanj.html

Ruby: SecureRandom.uuid
来源：http://dali.nanxinkj.top/Article/details/gt2ojyrraqq.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.jyoumei.cn/Article/details/gt2nxtgkvbo.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhoulong.xyz/Article/details/gt2kjimehxk.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.pengpengdd.cyou/Article/details/gt2nsyruilg.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.shuidangran.top/Article/details/gt2ybricjfz.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.guowangkeji.top/Article/details/gt2uabsiglb.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.birdmap.top/Article/details/gt2ayjenelo.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.jinqigufen.top/Article/details/gt2rtkbchos.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.havefunace.top/Article/details/gt2hwdnwvln.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2aozgoegh.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.cdnleiting.top/Article/details/gt2qolsqmff.html

[P03] 生成短随机字符串
来源：http://dali.jlsjyb.cn/Article/details/gt2afdxdyhq.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.xinyue.icu/Article/details/gt2kjjpheay.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.gaohongyu789.top/Article/details/gt2msylrerh.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.wangdashe.top/Article/details/gt2eeqndciq.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jiagoushi.top/Article/details/gt2xswixlkr.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.jinqigufen.top/Article/details/gt2srcyejho.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.tianlin.xyz/Article/details/gt2fskeilgr.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.nwbrower.top/Article/details/gt2iqcvxnnh.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.aibaodan.cn/Article/details/gt2ezwkesti.html

[P04] 求长度
来源：http://dali.jianghu66.top/Article/details/gt2mpwxbqif.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.tianlin.xyz/Article/details/gt2wbokoaio.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.nwbrower.top/Article/details/gt2qzwhmuhp.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.hnqzz.top/Article/details/gt2wwgmtejo.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.daxiang520.top/Article/details/gt2bsnidgnx.html

Java: list.size();  map.size();  s.length()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mbbkjqqe.html

Go:   len(arr);  len(m)
来源：http://dali.snrcjt.cn/Article/details/gt2javxfuap.html

Ruby: x.length;  x.size
来源：http://dali.c1oappe.top/Article/details/gt2iersacjd.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.nwbrower.top/Article/details/gt2msdqvwzr.html

[P05] 判断两个对象内容是否相等
来源：http://dali.shangyingyoupin.top/Article/details/gt2oanayuco.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.xinyue.icu/Article/details/gt2fmghfjxe.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.ybcxt.top/Article/details/gt2jacgrsyl.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.hongshengwenyu.top/Article/details/gt2vlrtcspc.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.9152youxi.cn/Article/details/gt2zvclsvdv.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zycfv.cn/Article/details/gt2bqdnevvx.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.quarkkingdee.top/Article/details/gt2ohojrhjp.html

Ruby: a == b
来源：http://dali.cashguo.top/Article/details/gt2mwtxjyec.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.snrcjt.cn/Article/details/gt2dezoagtr.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.yvedp.cn/Article/details/gt2xwpioeke.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.xinyue.icu/Article/details/gt2robzobha.html

PHP:  if (empty($x)) {}
来源：http://dali.jqgufenzy.top/Article/details/gt2qteatmta.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.shzxlz.cn/Article/details/gt2srjfdkrn.html

TS:   if (x == null) {}
来源：http://dali.sxryk.cn/Article/details/gt2enugbllx.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.yueranfly.top/Article/details/gt2cntjtstc.html

Go:   if x == nil {}
来源：http://dali.sxryk.cn/Article/details/gt2kigwpfhk.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhiwuduotai.top/Article/details/gt2xupbrtpo.html

C#:   if (x is null) {}
来源：http://dali.cucudq.cn/Article/details/gt2uqlhwllp.html

[P07] 防抖与节流
来源：http://dali.svipenyu.cn/Article/details/gt2qofzmcpd.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.gzhubu.top/Article/details/gt2ougapxqv.html

PHP:  // 手写时间戳比较
来源：http://dali.kuanghao11.cn/Article/details/gt2gcjjoaxg.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.ybcxt.top/Article/details/gt2otrmzdcq.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.9152youxi.cn/Article/details/gt2qyeylrbl.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.gaohongyu789.top/Article/details/gt2wpikmagi.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.316326.xyz/Article/details/gt2whpzsvuo.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.nanxuanxn.top/Article/details/gt2jrmeiohq.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.andypj.xyz/Article/details/gt2yqakusqm.html

[P08] 处理浮点精度问题
来源：http://dali.dashuyun.cn/Article/details/gt2zwhfliam.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.jiagoushi.top/Article/details/gt2zrensjmj.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2frkxibug.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.andypj.xyz/Article/details/gt2fcxdvqvs.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.smart0.xyz/Article/details/gt2wkbmlsmx.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.guannengcc.top/Article/details/gt2exuyrlok.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.fzhhl.top/Article/details/gt2hekmseby.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.tianlin.xyz/Article/details/gt2lokneaoa.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.gzhubu.top/Article/details/gt2rosxgkrs.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gt2ljjrhfnw.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.hywenlv.cn/Article/details/gt2pbtrfdlp.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gt2vruzgjke.html

[Q01] 创建表
来源：http://dali.yuanzhike.top/Article/details/gt2qzzoqjxf.html

CREATE TABLE users (
来源：http://dali.havefunace.top/Article/details/gt2qufbdbvg.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yvedp.cn/Article/details/gt2xyifimmz.html

name VARCHAR(50) NOT NULL,
来源：http://dali.yuanzhike.top/Article/details/gt2xmacqnvw.html

email VARCHAR(100) UNIQUE,
来源：http://dali.redwolf501.top/Article/details/gt2cmabodnp.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.yvedp.cn/Article/details/gt2igatdcqy.html

);
来源：http://dali.sufxvd.cn/Article/details/gt2kvbwsvva.html

[Q02] 创建带外键的表
来源：http://dali.sxryk.cn/Article/details/gt2dqwjyiiz.html

CREATE TABLE orders (
来源：http://dali.tianlin.xyz/Article/details/gt2wdaeppgr.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.quarkkingdee.top/Article/details/gt2epgnfriv.html

user_id INT NOT NULL,
来源：http://dali.guowangkeji.top/Article/details/gt2ogjtlptm.html

amount DECIMAL(10, 2),
来源：http://dali.dianchejie.cn/Article/details/gt2qxcvmowb.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ccxvyaem.html


<!-- 参考信息 -->