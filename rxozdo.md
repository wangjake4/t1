代发 wailian999

C#:   Directory.GetCurrentDirectory()
来源：http://dali.jlsjyb.cn/Article/details/gt2sozbvuwd.html

[M05] 设置退出码
来源：http://dali.yj20258.top/Article/details/gt2cwqtwcwg.html

Py:   sys.exit(1)
来源：http://dali.fzhhl.top/Article/details/gt2rpkzxazy.html

PHP:  exit(1);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nobbdygi.html

JS:   process.exit(1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bzywblil.html

TS:   process.exit(1)
来源：http://dali.svipenyu.cn/Article/details/gt2pjrpgpwm.html

Java: System.exit(1)
来源：http://dali.cucudq.cn/Article/details/gt2kemzhxws.html

Go:   os.Exit(1)
来源：http://dali.zhoulong.xyz/Article/details/gt2fpqhokyy.html

Ruby: exit 1
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kwocmhcp.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.jyoumei.cn/Article/details/gt2zigimlzg.html

[M06] 向标准错误输出
来源：http://dali.meibo888.top/Article/details/gt2diauadcw.html

Py:   print("err", file=sys.stderr)
来源：http://dali.sysykeji.top/Article/details/gt2nponscoq.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.0kj1m.cn/Article/details/gt2pvzeituk.html

JS:   console.error("err")
来源：http://dali.cucudq.cn/Article/details/gt2lyojtqoq.html

TS:   console.error("err")
来源：http://dali.gzhubu.top/Article/details/gt2bsesqaep.html

Java: System.err.println("err")
来源：http://dali.gaohongyu789.top/Article/details/gt2ponyhtef.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.haohaochexian.top/Article/details/gt2gwwzqwgy.html

Ruby: warn "err"
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pnixhynv.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.nwbrower.top/Article/details/gt2dtqsjsau.html

[M07] 判断是否为主入口
来源：http://dali.redwolf501.top/Article/details/gt2lqwcwlju.html

Py:   if __name__ == "__main__":
来源：http://dali.hnxiangtu.top/Article/details/gt2tvcbwyzn.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.yonumen.top/Article/details/gt2juasfbhe.html

JS:   require.main === module
来源：http://dali.hywenlv.cn/Article/details/gt2mqmzjxbx.html

TS:   require.main === module
来源：http://dali.shuidangran.top/Article/details/gt2rdlneztx.html

Java: public static void main(String[] args)
来源：http://dali.tianlin.xyz/Article/details/gt2oljgsemp.html

Go:   func main()
来源：http://dali.yanxiufei.cn/Article/details/gt2gowqvypp.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.daxiang520.top/Article/details/gt2ejdhtgli.html

C#:   static void Main(string[] args)
来源：http://dali.haohaochexian.top/Article/details/gt2aknyidwm.html

[M08] 获取系统与运行时信息
来源：http://dali.jqgufenzy.top/Article/details/gt2qshdjwkz.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhiwuduotai.top/Article/details/gt2hqoidrpi.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.dianchejie.cn/Article/details/gt2hdpiekto.html

JS:   process.platform;  process.version
来源：http://dali.guowangkeji.top/Article/details/gt2emwsqcwd.html

TS:   process.platform;  process.version
来源：http://dali.jinqigfzy.top/Article/details/gt2uftdhtpw.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.aizwys.cn/Article/details/gt2wytashvh.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.wangdashe.top/Article/details/gt2cowqwdpj.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.fengsongda.top/Article/details/gt2lxirysio.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.vqdsnc.cn/Article/details/gt2jbburyxu.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gt2lcmsisax.html

N. 数据结构与算法
来源：http://dali.ppjwa.cn/Article/details/gt2ukrhzorx.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gt2jqyspozy.html

[N01] 二分查找（有序数组）
来源：http://dali.hnxiangtu.top/Article/details/gt2jlxleqtd.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.jyoumei.cn/Article/details/gt2hnrunens.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.yj20258888.top/Article/details/gt2uiuripom.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.snrcjt.cn/Article/details/gt2lceiszsg.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.sweek.top/Article/details/gt2kqymxaza.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhoulong.xyz/Article/details/gt2gnowwmei.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.xylfe.cn/Article/details/gt2xpqengda.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.jyoumei.cn/Article/details/gt2ovhqutes.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.meibo888.top/Article/details/gt2jcdkpeqf.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.sxryk.cn/Article/details/gt2qpvivkav.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.tian-w.cn/Article/details/gt2vdspzidr.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.guowangkeji.top/Article/details/gt2nzneybot.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhixingplan.top/Article/details/gt2brxsacmo.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.shangyingyoupin.top/Article/details/gt2pzxxzsvb.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.gotoacloud.top/Article/details/gt2ahwtdiss.html

Go:   slices.Sort(arr)
来源：http://dali.yuanzhike.top/Article/details/gt2vlgidfum.html

Ruby: arr.sort
来源：http://dali.shuidangran.top/Article/details/gt2cefmocsw.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.pengpengdd.cyou/Article/details/gt2pmcuqhaj.html

[N03] 快速排序（分治示例）
来源：http://dali.ydzc1.top/Article/details/gt2dwzfypqk.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.xuanzx.com/Article/details/gt2qfatkusy.html

PHP:  // 递归实现，或用 usort
来源：http://dali.jqgufenzy.top/Article/details/gt2qvtpayyj.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.vqdsnc.cn/Article/details/gt2izjmmodg.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.aizwys.cn/Article/details/gt2txsiaddl.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhiwuduotai.top/Article/details/gt2aujhxjyn.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gmtxpalp.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.xuetiantiany.cn/Article/details/gt2nywvnhgf.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tufplgmk.html

[N04] 斐波那契数列
来源：http://dali.cheryme.top/Article/details/gt2zztxylqb.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.cdnleiting.top/Article/details/gt2oprvicdq.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.hammf.cn/Article/details/gt2nqswaxik.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.andypj.xyz/Article/details/gt2ejwuasij.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.mhx1999.top/Article/details/gt2acsoibsz.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.cucudq.cn/Article/details/gt2ezrulfuy.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.shuidangran.top/Article/details/gt2fwjxjmke.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2skpyvrno.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.sysykeji.top/Article/details/gt2hsnovsrm.html

[N05] 最大公约数
来源：http://dali.yuxming.cn/Article/details/gt2tlcxwwul.html

Py:   math.gcd(a, b)
来源：http://dali.sxryk.cn/Article/details/gt2zpjhwhdx.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.yj20258888.top/Article/details/gt2xccganvm.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.gotoacloud.top/Article/details/gt2ozfnqtml.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.aizwys.cn/Article/details/gt2loyqwsda.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.gotoacloud.top/Article/details/gt2jxxgfepn.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.feifeiyinyue.top/Article/details/gt2iiutagxh.html

Ruby: a.gcd(b)
来源：http://dali.quarkkingdee.top/Article/details/gt2iqfclgjn.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.shangyingyoupin.top/Article/details/gt2wuztfqhz.html

[N06] 判断回文字符串
来源：http://dali.andypj.xyz/Article/details/gt2wdqsdtny.html

Py:   s == s[::-1]
来源：http://dali.jqgfzy.top/Article/details/gt2ygsqktji.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2cmejdetw.html

JS:   s === [...s].reverse().join("")
来源：http://dali.cqqwz.cn/Article/details/gt2djqfrhvj.html

TS:   s === [...s].reverse().join("")
来源：http://dali.c1oappe.top/Article/details/gt2auvboevg.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.cashguo.top/Article/details/gt2hgxpgsvt.html

Go:   // 双指针从两端比较
来源：http://dali.zhengqikj.top/Article/details/gt2sntvjjsi.html

Ruby: s == s.reverse
来源：http://dali.bjfxy.top/Article/details/gt2fhwhkeok.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.cheryme.top/Article/details/gt2fcqbopif.html

[N07] 两数之和（返回下标）
来源：http://dali.hnqzz.top/Article/details/gt2rfftrarr.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.hysaishi.cn/Article/details/gt2qbuoaqcg.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.xziqi.cn/Article/details/gt2xdnnvaqe.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2wvqcfluj.html

TS:   // 手写 Map<string, number>
来源：http://dali.jinqigfzy.top/Article/details/gt2fcgtudzr.html

Java: // 手写 HashMap
来源：http://dali.c1oappe.top/Article/details/gt2yshvyfll.html

Go:   // 手写 map[int]int
来源：http://dali.chenjidiqi.icu/Article/details/gt2ruaxzold.html

Ruby: // 手写 Hash
来源：http://dali.hnqzz.top/Article/details/gt2tqmseozd.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.gzhubu.top/Article/details/gt2ndkedgrk.html

[N08] 生成全排列
来源：http://dali.hnxiangtu.top/Article/details/gt2ycpulkzz.html

Py:   itertools.permutations(arr)
来源：http://dali.yonumen.top/Article/details/gt2mcbcupcm.html

PHP:  // 手写递归交换
来源：http://dali.cheryme.top/Article/details/gt2dryyhmmt.html

JS:   // 手写回溯递归
来源：http://dali.smart0.xyz/Article/details/gt2nbdmxmfp.html

TS:   // 手写回溯递归
来源：http://dali.guannengcc.top/Article/details/gt2ktgiedss.html

Java: // 手写回溯递归
来源：http://dali.yj20258.top/Article/details/gt2smzpdwsx.html

Go:   // 手写回溯递归
来源：http://dali.xylfe.cn/Article/details/gt2twibjzfv.html

Ruby: arr.permutation.to_a
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cxnjpgxt.html

C#:   // 手写回溯递归
来源：http://dali.9152youxi.cn/Article/details/gt2ozhtljyf.html

[N09] 栈与队列
来源：http://dali.yanxiufei.cn/Article/details/gt2cxeuapce.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.pycfn.com/Article/details/gt2hyusoxmg.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.ivvv.top/Article/details/gt2qlwdkfbq.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.yueranfly.top/Article/details/gt2qxyryolp.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.jlsjyb.cn/Article/details/gt2gkegrwds.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.sysykeji.top/Article/details/gt2imyxqjst.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.jianghu66.top/Article/details/gt2fxytuycg.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.nanxuanxn.top/Article/details/gt2haryqvpk.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.ybcxt.top/Article/details/gt2hdjciiex.html

[N10] 链表节点定义
来源：http://dali.andypj.xyz/Article/details/gt2ashatmtk.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.gogol.net.cn/Article/details/gt2ucezyrnc.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.gotoacloud.top/Article/details/gt2cmhhhhdu.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.nwbrower.top/Article/details/gt2lskgqcof.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.mhx1999.top/Article/details/gt2fopkskfl.html

Java: class Node { int v; Node next; }
来源：http://dali.yuanzhike.top/Article/details/gt2vashehlg.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.cucudq.cn/Article/details/gt2qksgcjey.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.shangyingyoupin.top/Article/details/gt2hkotovkk.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.jqgfzy.top/Article/details/gt2jqwobchz.html

[N11] 二叉树中序遍历
来源：http://dali.sxryk.cn/Article/details/gt2ohosbctn.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.sxryk.cn/Article/details/gt2coqrbpsd.html

PHP:  // 手写递归函数
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xwyfwshk.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.daria6918.cn/Article/details/gt2fbqegohh.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhiwuduotai.top/Article/details/gt2vwnjcphv.html

Java: // 手写递归
来源：http://dali.dashuyun.cn/Article/details/gt2kdubjzbo.html

Go:   // 手写递归
来源：http://dali.aizwys.cn/Article/details/gt2wtmwhnka.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.shuidangran.top/Article/details/gt2ojqzhvra.html

C#:   // 手写递归
来源：http://dali.cdnleiting.top/Article/details/gt2ndiumvie.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.hysaishi.cn/Article/details/gt2isjjrase.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.sufxvd.cn/Article/details/gt2rjckcwoe.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2njgqwcei.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhixingplan.top/Article/details/gt2wdroqyvb.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.cashguo.top/Article/details/gt2ylsgehou.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jqgufenzy.top/Article/details/gt2gtcpqfec.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.dashuyun.cn/Article/details/gt2ptqtlogy.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.sysykeji.top/Article/details/gt2aeimjepf.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.chenzaomai.com/Article/details/gt2xzqmcamz.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gt2lajnkmvs.html

O. 并发与异步
来源：http://dali.bjfxy.top/Article/details/gt2ktknhxop.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gt2cemomnjd.html

[O01] 启动一个线程
来源：http://dali.dianchejie.cn/Article/details/gt2jtderakm.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.dashuyun.cn/Article/details/gt2yqkcmxrh.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.aizwys.cn/Article/details/gt2uyhwgdwm.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.ivvv.top/Article/details/gt2nlrnanpu.html

TS:   // 同 JS
来源：http://dali.cucudq.cn/Article/details/gt2hfuqzyop.html

Java: new Thread(() -> f()).start()
来源：http://dali.jiagoushi.top/Article/details/gt2zvvcuejl.html

Go:   go f()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jhyixrve.html

Ruby: Thread.new { f }
来源：http://dali.gotoacloud.top/Article/details/gt2pbgoqkju.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2chbvdtob.html

[O02] 使用线程池
来源：http://dali.yonumen.top/Article/details/gt2xtulxqnh.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.shuidangran.top/Article/details/gt2qzsngfcn.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.smart0.xyz/Article/details/gt2hiyzswck.html

JS:   // worker_threads 线程池
来源：http://dali.feifeiyinyue.top/Article/details/gt2vxkdriaf.html

TS:   // worker_threads 线程池
来源：http://dali.wangshuangyany.cn/Article/details/gt2acvamtiz.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.gzhubu.top/Article/details/gt2khhnmgwd.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.yuxming.cn/Article/details/gt2mmqwtcgg.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.kuanghao11.cn/Article/details/gt2mxmwiltd.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.aizwys.cn/Article/details/gt2drspfsgd.html

[O03] 加锁保护共享数据
来源：http://dali.ivvv.top/Article/details/gt2luihbqys.html

Py:   with lock: shared += 1
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2eozbcckm.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.cashguo.top/Article/details/gt2aaqgvwuo.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhoulong.xyz/Article/details/gt2lfybbqvc.html

TS:   // 同 JS
来源：http://dali.yueranfly.top/Article/details/gt2zciebpxx.html

Java: synchronized (this) { shared++; }
来源：http://dali.guowangkeji.top/Article/details/gt2zejrxwhe.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.sweek.top/Article/details/gt2rmcpglfr.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.pycfn.com/Article/details/gt2wrdhmndi.html

C#:   lock (gate) { shared++; }
来源：http://dali.yuxming.cn/Article/details/gt2upqrnvcd.html

[O04] 定义异步函数并等待
来源：http://dali.chenzaomai.com/Article/details/gt2mzindkvh.html

Py:   async def f():⏎    await g()
来源：http://dali.gogol.net.cn/Article/details/gt2qtcjxycd.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.havefunace.top/Article/details/gt2tdgoetaj.html

JS:   async function f() { await g(); }
来源：http://dali.ppjwa.cn/Article/details/gt2rvvtneqi.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhiwuduotai.top/Article/details/gt2nosmeize.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.haohaochexian.top/Article/details/gt2toqemetr.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.shzxlz.cn/Article/details/gt2hcnrsdhf.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.9152youxi.cn/Article/details/gt2fsjgfvqq.html

C#:   async Task F() { await G(); }
来源：http://dali.sxryk.cn/Article/details/gt2lrzlatcf.html

[O05] 并发执行并等待全部完成
来源：http://dali.nwbrower.top/Article/details/gt2jlzitghh.html

Py:   asyncio.gather(*tasks)
来源：http://dali.nanxuanxn.top/Article/details/gt2xfktwawp.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.jqgufenzy.top/Article/details/gt2nkkzcpnb.html

JS:   await Promise.all(tasks)
来源：http://dali.yj20258.top/Article/details/gt2qgxqqush.html

TS:   await Promise.all(tasks)
来源：http://dali.hfpthk.cn/Article/details/gt2dpzbujzy.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.yuanzhike.top/Article/details/gt2omhwmjgs.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.yueranfly.top/Article/details/gt2jnvlhiul.html

Ruby: threads.map(&:join)
来源：http://dali.cqqwz.cn/Article/details/gt2zlqgawox.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.wangshuangyany.cn/Article/details/gt2qwdbtgsn.html

[O06] 使用进程池
来源：http://dali.snrcjt.cn/Article/details/gt2tmjoconh.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.gaohongyu789.top/Article/details/gt2rumhffcw.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.svipenyu.cn/Article/details/gt2bligdyrz.html

JS:   // child_process / cluster 模块
来源：http://dali.wangdashe.top/Article/details/gt2vzhzjeui.html

TS:   // child_process / cluster 模块
来源：http://dali.jinqigufen.top/Article/details/gt2gwruiiyl.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.nanxuanxn.top/Article/details/gt2bodfehnh.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.snrcjt.cn/Article/details/gt2fnmndyvq.html

Ruby: // fork 块
来源：http://dali.cheryme.top/Article/details/gt2oztvgyni.html

C#:   Parallel.For
来源：http://dali.hfpthk.cn/Article/details/gt2hufccrfa.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gt2rbbymamv.html

P. 常用工具函数
来源：http://dali.shzxlz.cn/Article/details/gt2ljoqtmsb.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gt2flnmrzbb.html

[P01] 生成 UUID
来源：http://dali.zhoulong.xyz/Article/details/gt2xpfocijf.html

Py:   str(uuid.uuid4())
来源：http://dali.ehwqpu.com/Article/details/gt2uobvgmmz.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.nwbrower.top/Article/details/gt2rtgqxppk.html

JS:   crypto.randomUUID()
来源：http://dali.316326.xyz/Article/details/gt2adxhytph.html

TS:   crypto.randomUUID()
来源：http://dali.chenlongwang.top/Article/details/gt2mjxjotwj.html

Java: UUID.randomUUID().toString()
来源：http://dali.jlsjyb.cn/Article/details/gt2objuecof.html

Go:   // 用 github.com/google/uuid
来源：http://dali.tian-w.cn/Article/details/gt2idtqxjbp.html

Ruby: SecureRandom.uuid
来源：http://dali.jiagoushi.top/Article/details/gt2xphjmkti.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.xinyue.icu/Article/details/gt2oicxphrc.html

[P02] MD5 / SHA256 摘要
来源：http://dali.daxiang520.top/Article/details/gt2wezdaeuv.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.meibo888.top/Article/details/gt2gxclgyyg.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.cqqwz.cn/Article/details/gt2ktsvdgwn.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.xuetiantiany.cn/Article/details/gt2rstwhlue.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.yangfankeji.com/Article/details/gt2cfggqkes.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhiwuduotai.top/Article/details/gt2bdvyqyyx.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.mhx1999.top/Article/details/gt2rpngicez.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.shzxlz.cn/Article/details/gt2mdevmfyz.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.shanyushiyangtech.top/Article/details/gt2huqbosdg.html

[P03] 生成短随机字符串
来源：http://dali.zhixingplan.top/Article/details/gt2ikyiuxwl.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.tanke756.top/Article/details/gt2yijmtzpt.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.yangfankeji.com/Article/details/gt2yoqvawne.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.birdmap.top/Article/details/gt2wjcetyof.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jiagoushi.top/Article/details/gt2itzeycdi.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.hammf.cn/Article/details/gt2bndbxody.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.yueranfly.top/Article/details/gt2lghbwnrl.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.dashuyun.cn/Article/details/gt2etnlnhas.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zycfv.cn/Article/details/gt2ytiusxrp.html

[P04] 求长度
来源：http://dali.zhoulong.xyz/Article/details/gt2hqdrxmdg.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.yj20258888.top/Article/details/gt2hoizaees.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.xuetiantiany.cn/Article/details/gt2zldihuav.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jlsjyb.cn/Article/details/gt2yizzzshy.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zdqjudy.top/Article/details/gt2snkqpqct.html

Java: list.size();  map.size();  s.length()
来源：http://dali.yuanzhike.top/Article/details/gt2ryhqwkrj.html

Go:   len(arr);  len(m)
来源：http://dali.feifeiyinyue.top/Article/details/gt2syqjpgue.html

Ruby: x.length;  x.size
来源：http://dali.yuxming.cn/Article/details/gt2ajvcjael.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.xuetiantiany.cn/Article/details/gt2becxpowh.html

[P05] 判断两个对象内容是否相等
来源：http://dali.9152youxi.cn/Article/details/gt2anrveowq.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.svipenyu.cn/Article/details/gt2kwdynghd.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rgylmrdy.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.xziqi.cn/Article/details/gt2agnmhmkk.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.gzhubu.top/Article/details/gt2mcsncrwl.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.xuanzx.com/Article/details/gt2ntdxmlyd.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.cucudq.cn/Article/details/gt2nstrdthi.html

Ruby: a == b
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tsgkltpn.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.xuanzx.com/Article/details/gt2zwecohqs.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.yanxiufei.cn/Article/details/gt2cajzwpwq.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.tian-w.cn/Article/details/gt2ubocbjtw.html

PHP:  if (empty($x)) {}
来源：http://dali.yongpay.top/Article/details/gt2mbdcqwdb.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bqmwnbfc.html

TS:   if (x == null) {}
来源：http://dali.gaohongyu789.top/Article/details/gt2eymalqlk.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.cdnleiting.top/Article/details/gt2jdiedoqb.html

Go:   if x == nil {}
来源：http://dali.redwolf501.top/Article/details/gt2krsxzoqi.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.ybcxt.top/Article/details/gt2gwyzqszw.html

C#:   if (x is null) {}
来源：http://dali.jlsjyb.cn/Article/details/gt2jarleryd.html

[P07] 防抖与节流
来源：http://dali.bjfxy.top/Article/details/gt2xqxlnlrz.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.xziqi.cn/Article/details/gt2hmrjjocl.html

PHP:  // 手写时间戳比较
来源：http://dali.aizwys.cn/Article/details/gt2emjpsbuy.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2kaiuitil.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zdqjudy.top/Article/details/gt2nmsvbrcb.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cimgpcgf.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.yongpay.top/Article/details/gt2abovyknb.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.hfpthk.cn/Article/details/gt2tbzrsryc.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.pengpengdd.cyou/Article/details/gt2nnsmimxn.html

[P08] 处理浮点精度问题
来源：http://dali.mhx1999.top/Article/details/gt2jpgqcege.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.yj20258.top/Article/details/gt2yspfwtvo.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xgtefflw.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.jinqigfzy.top/Article/details/gt2qyckxhbm.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.ivvv.top/Article/details/gt2dxqywopi.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.wangdashe.top/Article/details/gt2aisfqdau.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.cucudq.cn/Article/details/gt2rwcnwvzl.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.yangfankeji.com/Article/details/gt2nddmdtew.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.jinqigufen.top/Article/details/gt2iadnukir.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gt2wnapexqt.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.aibaodan.cn/Article/details/gt2vgdbkila.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gt2tecdckqc.html

[Q01] 创建表
来源：http://dali.ppjwa.cn/Article/details/gt2yfkmpydw.html

CREATE TABLE users (
来源：http://dali.cheryme.top/Article/details/gt2gmrukhkm.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.iojbl.cn/Article/details/gt2ewaysleb.html

name VARCHAR(50) NOT NULL,
来源：http://dali.pycfn.com/Article/details/gt2tmtsawhh.html

email VARCHAR(100) UNIQUE,
来源：http://dali.yuxming.cn/Article/details/gt2vhrpxzmm.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.pycfn.com/Article/details/gt2jgcecaid.html

);
来源：http://dali.zhengqikj.top/Article/details/gt2skhqegfz.html

[Q02] 创建带外键的表
来源：http://dali.jinghuilouyu.cn/Article/details/gt2sgjgjtgz.html

CREATE TABLE orders (
来源：http://dali.svipenyu.cn/Article/details/gt2iipoyaoe.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yj20258888.top/Article/details/gt2ifnwkwcb.html

user_id INT NOT NULL,
来源：http://dali.yuxming.cn/Article/details/gt2nuztkkjs.html

amount DECIMAL(10, 2),
来源：http://dali.jinqigfzy.top/Article/details/gt2iryxhfsy.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.guannengcc.top/Article/details/gt2lulpvjkk.html

);
来源：http://dali.hysaishi.cn/Article/details/gt2msihogzu.html

[Q03] 增加列
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ldzruufc.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.xuanzx.com/Article/details/gt2ydafpcde.html

[Q04] 修改列类型
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2joeccrqv.html


<!-- 参考信息 -->