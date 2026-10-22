代发 wailian999

TS:   process.cwd()
来源：http://dali.shzxlz.cn/Article/details/gt2eqwrvyzz.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.gotoacloud.top/Article/details/gt2wwbxdmed.html

Go:   os.Getwd()
来源：http://dali.jinqigfzy.top/Article/details/gt2iscsolqi.html

Ruby: Dir.pwd
来源：http://dali.quarkkingdee.top/Article/details/gt2wfliqxck.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.yangfankeji.com/Article/details/gt2pcgughoa.html

[M05] 设置退出码
来源：http://dali.zhiwuduotai.top/Article/details/gt2fhdlyzgy.html

Py:   sys.exit(1)
来源：http://dali.jyoumei.cn/Article/details/gt2nlmuovmk.html

PHP:  exit(1);
来源：http://dali.birdmap.top/Article/details/gt2mulwhgqv.html

JS:   process.exit(1)
来源：http://dali.hysaishi.cn/Article/details/gt2xvucqosg.html

TS:   process.exit(1)
来源：http://dali.yj20258888.top/Article/details/gt2jeeqdbdv.html

Java: System.exit(1)
来源：http://dali.haohaochexian.top/Article/details/gt2ekyrymti.html

Go:   os.Exit(1)
来源：http://dali.jqgufenzy.top/Article/details/gt2myuiplrs.html

Ruby: exit 1
来源：http://dali.tianlin.xyz/Article/details/gt2qduazjul.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.chenjidiqi.icu/Article/details/gt2cubkloqa.html

[M06] 向标准错误输出
来源：http://dali.daria6918.cn/Article/details/gt2jnxqsezt.html

Py:   print("err", file=sys.stderr)
来源：http://dali.hysaishi.cn/Article/details/gt2fxwmeoea.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.pengpengdd.cyou/Article/details/gt2jazhnyzu.html

JS:   console.error("err")
来源：http://dali.zdqjudy.top/Article/details/gt2lvncywvp.html

TS:   console.error("err")
来源：http://dali.xuetiantiany.cn/Article/details/gt2zslklwvd.html

Java: System.err.println("err")
来源：http://dali.daxiang520.top/Article/details/gt2ladjkmah.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.yuxming.cn/Article/details/gt2xfoyolhu.html

Ruby: warn "err"
来源：http://dali.9152youxi.cn/Article/details/gt2ufueqaud.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.nwbrower.top/Article/details/gt2ivvuaixz.html

[M07] 判断是否为主入口
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2shcvmvwt.html

Py:   if __name__ == "__main__":
来源：http://dali.fzhhl.top/Article/details/gt2fyztnkmb.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.nanxinkj.top/Article/details/gt2vernyxsj.html

JS:   require.main === module
来源：http://dali.fzhhl.top/Article/details/gt2memuyesw.html

TS:   require.main === module
来源：http://dali.mhx1999.top/Article/details/gt2bwjazktf.html

Java: public static void main(String[] args)
来源：http://dali.sweek.top/Article/details/gt2uphkuyjz.html

Go:   func main()
来源：http://dali.jianghu66.top/Article/details/gt2jtdjgqmb.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.cucudq.cn/Article/details/gt2pwsfczuf.html

C#:   static void Main(string[] args)
来源：http://dali.hammf.cn/Article/details/gt2zvzawrpk.html

[M08] 获取系统与运行时信息
来源：http://dali.sxryk.cn/Article/details/gt2snydswrz.html

Py:   platform.system();  platform.python_version()
来源：http://dali.svipenyu.cn/Article/details/gt2hcjaipal.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.c1oappe.top/Article/details/gt2zuyqrqjo.html

JS:   process.platform;  process.version
来源：http://dali.zhengqikj.top/Article/details/gt2rlijsvmi.html

TS:   process.platform;  process.version
来源：http://dali.guannengcc.top/Article/details/gt2kmerweon.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhixingplan.top/Article/details/gt2ejovmifp.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.yvedp.cn/Article/details/gt2omhutdhr.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.hfpthk.cn/Article/details/gt2xtyohbky.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.quarkkingdee.top/Article/details/gt2pefhzdkj.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gt2ljorgosp.html

N. 数据结构与算法
来源：http://dali.fzhhl.top/Article/details/gt2aamjdlwg.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gt2vrecasoa.html

[N01] 二分查找（有序数组）
来源：http://dali.sufxvd.cn/Article/details/gt2ektrxxcu.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhengqikj.top/Article/details/gt2fjyywsah.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.sweek.top/Article/details/gt2kecfooja.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.ppjwa.cn/Article/details/gt2ktorgwfl.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.bjfxy.top/Article/details/gt2oywzvldq.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.gogol.net.cn/Article/details/gt2fmexdjjq.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.hnxiangtu.top/Article/details/gt2jgwwbkvm.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.havefunace.top/Article/details/gt2ixukerrf.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.cqqwz.cn/Article/details/gt2rijmbljp.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.yongpay.top/Article/details/gt2uvxqjaqt.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.xylfe.cn/Article/details/gt2clacovzr.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.svipenyu.cn/Article/details/gt2vacspppy.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.shangyingyoupin.top/Article/details/gt2poasjqid.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.nwbrower.top/Article/details/gt2zimkjywn.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhixingplan.top/Article/details/gt2ezgxlufg.html

Go:   slices.Sort(arr)
来源：http://dali.hammf.cn/Article/details/gt2tecyojof.html

Ruby: arr.sort
来源：http://dali.yanxiufei.cn/Article/details/gt2saryjbkv.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.tianlin.xyz/Article/details/gt2brjbucuk.html

[N03] 快速排序（分治示例）
来源：http://dali.9152youxi.cn/Article/details/gt2vtpkfsed.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.havefunace.top/Article/details/gt2stujevwa.html

PHP:  // 递归实现，或用 usort
来源：http://dali.jlsjyb.cn/Article/details/gt2owiqxghn.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.cucudq.cn/Article/details/gt2hajdubed.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.chenzaomai.com/Article/details/gt2lwbetzyx.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.xuanzx.com/Article/details/gt2igsenvqp.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.shzxlz.cn/Article/details/gt2tyszwofu.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.daxiang520.top/Article/details/gt2pyxvplbt.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.yangfankeji.com/Article/details/gt2tjithljl.html

[N04] 斐波那契数列
来源：http://dali.hongshengwenyu.top/Article/details/gt2hgcpcjlw.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.gaohongyu789.top/Article/details/gt2elcewsib.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vfyywoec.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.shuidangran.top/Article/details/gt2yrgvbkvi.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhoulong.xyz/Article/details/gt2tfxiooje.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.jinqigfzy.top/Article/details/gt2twrunbef.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ucxenzji.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.jqgufenzy.top/Article/details/gt2lwuxommj.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.chenjidiqi.icu/Article/details/gt2ftjdtiyw.html

[N05] 最大公约数
来源：http://dali.chenzaomai.com/Article/details/gt2ukphlxlg.html

Py:   math.gcd(a, b)
来源：http://dali.gaohongyu789.top/Article/details/gt2ztaksccj.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.hammf.cn/Article/details/gt2jxgywmau.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jqgufenzy.top/Article/details/gt2usouwxls.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yangfankeji.com/Article/details/gt2zsogyzso.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zdqjudy.top/Article/details/gt2zjzrznjm.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.aibaodan.cn/Article/details/gt2jkntahxf.html

Ruby: a.gcd(b)
来源：http://dali.cqqwz.cn/Article/details/gt2twgrvmtd.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.quarkkingdee.top/Article/details/gt2vqnsgljk.html

[N06] 判断回文字符串
来源：http://dali.vqdsnc.cn/Article/details/gt2hmfvuzxu.html

Py:   s == s[::-1]
来源：http://dali.zhiwuduotai.top/Article/details/gt2epzogcaw.html

PHP:  $s === strrev($s);
来源：http://dali.gotoacloud.top/Article/details/gt2qarspbis.html

JS:   s === [...s].reverse().join("")
来源：http://dali.aibaodan.cn/Article/details/gt2zkgggysh.html

TS:   s === [...s].reverse().join("")
来源：http://dali.jlsjyb.cn/Article/details/gt2crdstumu.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.hongshengwenyu.top/Article/details/gt2lxdxyfpn.html

Go:   // 双指针从两端比较
来源：http://dali.zhongyouzk.top/Article/details/gt2iuzkalcd.html

Ruby: s == s.reverse
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vrqicbjs.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.sxryk.cn/Article/details/gt2jfckohhj.html

[N07] 两数之和（返回下标）
来源：http://dali.hysaishi.cn/Article/details/gt2dbzyyfyo.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.daria6918.cn/Article/details/gt2oyvkleym.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.hywenlv.cn/Article/details/gt2zqwvffuo.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.aizwys.cn/Article/details/gt2gjuzlraw.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhoulong.xyz/Article/details/gt2eltqvytf.html

Java: // 手写 HashMap
来源：http://dali.yvedp.cn/Article/details/gt2vcjmcvhw.html

Go:   // 手写 map[int]int
来源：http://dali.nwbrower.top/Article/details/gt2eryrokyi.html

Ruby: // 手写 Hash
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lwcuqrfv.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.nwbrower.top/Article/details/gt2lvvhomcx.html

[N08] 生成全排列
来源：http://dali.wangdashe.top/Article/details/gt2zdcoekrw.html

Py:   itertools.permutations(arr)
来源：http://dali.guannengcc.top/Article/details/gt2hgggyfxg.html

PHP:  // 手写递归交换
来源：http://dali.xuetiantiany.cn/Article/details/gt2jzcgipic.html

JS:   // 手写回溯递归
来源：http://dali.redwolf501.top/Article/details/gt2rqjvllym.html

TS:   // 手写回溯递归
来源：http://dali.316326.xyz/Article/details/gt2bcatxyje.html

Java: // 手写回溯递归
来源：http://dali.hammf.cn/Article/details/gt2hcfgghmv.html

Go:   // 手写回溯递归
来源：http://dali.havefunace.top/Article/details/gt2qfdtvbju.html

Ruby: arr.permutation.to_a
来源：http://dali.svipenyu.cn/Article/details/gt2wphbddem.html

C#:   // 手写回溯递归
来源：http://dali.smart0.xyz/Article/details/gt2bxeegtrg.html

[N09] 栈与队列
来源：http://dali.sysykeji.top/Article/details/gt2cnggkjif.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.xuanzx.com/Article/details/gt2cfbuiikg.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.shangyingyoupin.top/Article/details/gt2kuenppft.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.shangyingyoupin.top/Article/details/gt2epdmfplz.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.jinqigufen.top/Article/details/gt2qkescxuy.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.aibaodan.cn/Article/details/gt2otaxgsin.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.jinqigufen.top/Article/details/gt2wgstamia.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.daxiang520.top/Article/details/gt2rmkpjpia.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhoulong.xyz/Article/details/gt2nlhnwfep.html

[N10] 链表节点定义
来源：http://dali.meibo888.top/Article/details/gt2ylgtmcru.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.yj20258.top/Article/details/gt2seqqxpxb.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.yj20258888.top/Article/details/gt2qgzsqkce.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.smart0.xyz/Article/details/gt2wpvertjv.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.dianchejie.cn/Article/details/gt2wzpjyrno.html

Java: class Node { int v; Node next; }
来源：http://dali.yj202588.top/Article/details/gt2fxzlhikg.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.yj20258.top/Article/details/gt2ksyplalv.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vxrrbptk.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wttaojlh.html

[N11] 二叉树中序遍历
来源：http://dali.dianchejie.cn/Article/details/gt2xjkozdoo.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.mhx1999.top/Article/details/gt2mqbmtury.html

PHP:  // 手写递归函数
来源：http://dali.ppjwa.cn/Article/details/gt2eevwjatl.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jiagoushi.top/Article/details/gt2cblelpwo.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.haohaochexian.top/Article/details/gt2vsmsudpn.html

Java: // 手写递归
来源：http://dali.chenzaomai.com/Article/details/gt2kegmwtpz.html

Go:   // 手写递归
来源：http://dali.tanke756.top/Article/details/gt2hjagspte.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.gzhubu.top/Article/details/gt2abjpppkr.html

C#:   // 手写递归
来源：http://dali.yangfankeji.com/Article/details/gt2thwbuqjw.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.yuxming.cn/Article/details/gt2fgomggyt.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.nanxinkj.top/Article/details/gt2vjnmkevi.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.iojbl.cn/Article/details/gt2axcgeeuu.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2smirdpxh.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.xuanzx.com/Article/details/gt2joctpghg.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.shzxlz.cn/Article/details/gt2gkdoghez.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.cucudq.cn/Article/details/gt2peophcrv.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.hammf.cn/Article/details/gt2jxtpvkrz.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yanxiufei.cn/Article/details/gt2ujbbhjap.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gt2onlqdhtj.html

O. 并发与异步
来源：http://dali.haohaochexian.top/Article/details/gt2ueonstbc.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gt2emfhonhp.html

[O01] 启动一个线程
来源：http://dali.hammf.cn/Article/details/gt2hhkrwnjf.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.chenlongwang.top/Article/details/gt2ilbcicln.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.ybcxt.top/Article/details/gt2bfxmwvkp.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.shangyingyoupin.top/Article/details/gt2vetqkkxm.html

TS:   // 同 JS
来源：http://dali.shangyingyoupin.top/Article/details/gt2rguqqxuu.html

Java: new Thread(() -> f()).start()
来源：http://dali.yongpay.top/Article/details/gt2yhurfotd.html

Go:   go f()
来源：http://dali.yuxming.cn/Article/details/gt2syoocxtc.html

Ruby: Thread.new { f }
来源：http://dali.hnqzz.top/Article/details/gt2youtbzbb.html

C#:   Task.Run(() => F());
来源：http://dali.aibaodan.cn/Article/details/gt2uivadgvj.html

[O02] 使用线程池
来源：http://dali.tianlin.xyz/Article/details/gt2arzegxgn.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.jqgfzy.top/Article/details/gt2bpgxqagf.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.quarkkingdee.top/Article/details/gt2dofmewga.html

JS:   // worker_threads 线程池
来源：http://dali.zhongyouzk.top/Article/details/gt2drzbymzy.html

TS:   // worker_threads 线程池
来源：http://dali.ivvv.top/Article/details/gt2skgzzurp.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.vqdsnc.cn/Article/details/gt2cymlayrb.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.gogol.net.cn/Article/details/gt2tlfcsoyv.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.iojbl.cn/Article/details/gt2rfrzpdqj.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.hnqzz.top/Article/details/gt2eawlkngv.html

[O03] 加锁保护共享数据
来源：http://dali.jinqigfzy.top/Article/details/gt2ngofwjwg.html

Py:   with lock: shared += 1
来源：http://dali.jianghu66.top/Article/details/gt2imkbyief.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.guowangkeji.top/Article/details/gt2xohkjayh.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.havefunace.top/Article/details/gt2iccvrqqi.html

TS:   // 同 JS
来源：http://dali.yj202588.top/Article/details/gt2cvefhtmn.html

Java: synchronized (this) { shared++; }
来源：http://dali.gogol.net.cn/Article/details/gt2dgicdsvg.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.dashuyun.cn/Article/details/gt2ypfcwgqd.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.chenzaomai.com/Article/details/gt2jhsqzexj.html

C#:   lock (gate) { shared++; }
来源：http://dali.nanxinkj.top/Article/details/gt2xvtzbjnz.html

[O04] 定义异步函数并等待
来源：http://dali.gaohongyu789.top/Article/details/gt2reyrpowt.html

Py:   async def f():⏎    await g()
来源：http://dali.yj20258.top/Article/details/gt2dsgrwzhu.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.jinqigufen.top/Article/details/gt2gxvuiiyc.html

JS:   async function f() { await g(); }
来源：http://dali.haohaochexian.top/Article/details/gt2carklaon.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.shuidangran.top/Article/details/gt2giymmcps.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.wangshuangyany.cn/Article/details/gt2cbnigdzg.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zycfv.cn/Article/details/gt2ukujjfed.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.cheryme.top/Article/details/gt2viwmwety.html

C#:   async Task F() { await G(); }
来源：http://dali.meibo888.top/Article/details/gt2pwobockg.html

[O05] 并发执行并等待全部完成
来源：http://dali.nwbrower.top/Article/details/gt2amirnpbk.html

Py:   asyncio.gather(*tasks)
来源：http://dali.jiagoushi.top/Article/details/gt2pnpycuyi.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.ybcxt.top/Article/details/gt2diawkmbd.html

JS:   await Promise.all(tasks)
来源：http://dali.kuanghao11.cn/Article/details/gt2ugkonkmn.html

TS:   await Promise.all(tasks)
来源：http://dali.tianlin.xyz/Article/details/gt2rntvqrkw.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.hywenlv.cn/Article/details/gt2vwfnggmr.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.yueranfly.top/Article/details/gt2iezabuau.html

Ruby: threads.map(&:join)
来源：http://dali.jyoumei.cn/Article/details/gt2hmixztjc.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.gaohongyu789.top/Article/details/gt2hagzxieh.html

[O06] 使用进程池
来源：http://dali.yuxming.cn/Article/details/gt2fflipopg.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.hnqzz.top/Article/details/gt2eigyzohz.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.xuetiantiany.cn/Article/details/gt2nsbthmkg.html

JS:   // child_process / cluster 模块
来源：http://dali.tanke756.top/Article/details/gt2vdgvaxzq.html

TS:   // child_process / cluster 模块
来源：http://dali.gzhubu.top/Article/details/gt2cxzuvgpj.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.wangshuangyany.cn/Article/details/gt2vujhzghh.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.pengpengdd.cyou/Article/details/gt2zwheafng.html

Ruby: // fork 块
来源：http://dali.xylfe.cn/Article/details/gt2xqeelwvh.html

C#:   Parallel.For
来源：http://dali.nanxinkj.top/Article/details/gt2upyfgcup.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gt2xjmoqyzp.html

P. 常用工具函数
来源：http://dali.tanke756.top/Article/details/gt2tuxqhxtu.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gt2oieebmfm.html

[P01] 生成 UUID
来源：http://dali.hysaishi.cn/Article/details/gt2aeycruxt.html

Py:   str(uuid.uuid4())
来源：http://dali.gotoacloud.top/Article/details/gt2weedtjwd.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.tianlin.xyz/Article/details/gt2eppclrwu.html

JS:   crypto.randomUUID()
来源：http://dali.gzhubu.top/Article/details/gt2cgobhzch.html

TS:   crypto.randomUUID()
来源：http://dali.hammf.cn/Article/details/gt2nhhozwoc.html

Java: UUID.randomUUID().toString()
来源：http://dali.yangfankeji.com/Article/details/gt2zilcbeiq.html

Go:   // 用 github.com/google/uuid
来源：http://dali.yuanzhike.top/Article/details/gt2ncplbvkn.html

Ruby: SecureRandom.uuid
来源：http://dali.hysaishi.cn/Article/details/gt2ppmjsrmq.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.aibaodan.cn/Article/details/gt2obemarlz.html

[P02] MD5 / SHA256 摘要
来源：http://dali.chenzaomai.com/Article/details/gt2ojvdaaoi.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhengqikj.top/Article/details/gt2fhsmsmab.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.wangshuangyany.cn/Article/details/gt2krmmmqhs.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.nanxuanxn.top/Article/details/gt2hzotygvb.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.chenlongwang.top/Article/details/gt2heazyzyw.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.wangdashe.top/Article/details/gt2mbvsomiq.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.redwolf501.top/Article/details/gt2fcdyrxtc.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.0kj1m.cn/Article/details/gt2bevhngxg.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.pycfn.com/Article/details/gt2dqrhrmgq.html

[P03] 生成短随机字符串
来源：http://dali.zhoulong.xyz/Article/details/gt2evgsumqh.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.gaohongyu789.top/Article/details/gt2cfxehkou.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.aizwys.cn/Article/details/gt2gzrzaywe.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.hywenlv.cn/Article/details/gt2zrltixhq.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yj20258.top/Article/details/gt2pzoflycs.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.nanxuanxn.top/Article/details/gt2wjaccnjr.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.fengsongda.top/Article/details/gt2ndmtnnwv.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.havefunace.top/Article/details/gt2hvsjzfoi.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.iojbl.cn/Article/details/gt2wcybgkrm.html

[P04] 求长度
来源：http://dali.ybcxt.top/Article/details/gt2wyzazccu.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.jinqigufen.top/Article/details/gt2qnfcpuzn.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.shangyingyoupin.top/Article/details/gt2icwoosap.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yuxming.cn/Article/details/gt2oxkhfpjh.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.9152youxi.cn/Article/details/gt2ieusozri.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2sfzivrbi.html

Go:   len(arr);  len(m)
来源：http://dali.haohaochexian.top/Article/details/gt2cnyqegkj.html

Ruby: x.length;  x.size
来源：http://dali.feifeiyinyue.top/Article/details/gt2mknmqgbj.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.xylfe.cn/Article/details/gt2kulzlckr.html

[P05] 判断两个对象内容是否相等
来源：http://dali.shzxlz.cn/Article/details/gt2qoaaxqrq.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.jlsjyb.cn/Article/details/gt2uiykokmf.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zdqjudy.top/Article/details/gt2qznbbpsu.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.dianchejie.cn/Article/details/gt2xsflczzy.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.svipenyu.cn/Article/details/gt2pixluspl.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.quarkkingdee.top/Article/details/gt2euftofay.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.cashguo.top/Article/details/gt2qkyineyb.html

Ruby: a == b
来源：http://dali.jqgfzy.top/Article/details/gt2ohcyrkte.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rgqpnipi.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zdqjudy.top/Article/details/gt2uydnuuqs.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.haohaochexian.top/Article/details/gt2unsqhvdw.html

PHP:  if (empty($x)) {}
来源：http://dali.jlsjyb.cn/Article/details/gt2atcnorwk.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.pycfn.com/Article/details/gt2ovyoveia.html

TS:   if (x == null) {}
来源：http://dali.cqqwz.cn/Article/details/gt2ldmibtwn.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.ehwqpu.com/Article/details/gt2raegexnk.html

Go:   if x == nil {}
来源：http://dali.yj20258.top/Article/details/gt2ensauhpw.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.yj202588.top/Article/details/gt2dsqfbfag.html

C#:   if (x is null) {}
来源：http://dali.sxryk.cn/Article/details/gt2tbplrphg.html

[P07] 防抖与节流
来源：http://dali.zhoulong.xyz/Article/details/gt2vsyowaoc.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.haohaochexian.top/Article/details/gt2jlivajbs.html

PHP:  // 手写时间戳比较
来源：http://dali.nanxinkj.top/Article/details/gt2dgwgwuui.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.xylfe.cn/Article/details/gt2irdfolwi.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jianghu66.top/Article/details/gt2nhuvrhjh.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.mhx1999.top/Article/details/gt2dfdenbfv.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.0kj1m.cn/Article/details/gt2ivghvrjp.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.nanxinkj.top/Article/details/gt2jhfemxar.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.daria6918.cn/Article/details/gt2qldnawsv.html

[P08] 处理浮点精度问题
来源：http://dali.xylfe.cn/Article/details/gt2zshgcguk.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.hongshengwenyu.top/Article/details/gt2fqsnpymk.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.daria6918.cn/Article/details/gt2grdwdwvu.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.cashguo.top/Article/details/gt2ncwafutm.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.gotoacloud.top/Article/details/gt2pvpavtgt.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.jinghuilouyu.cn/Article/details/gt2namgojte.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.ybcxt.top/Article/details/gt2yjgrhrhd.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.nanxuanxn.top/Article/details/gt2zvxmzkof.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.ybcxt.top/Article/details/gt2euwbudqf.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gt2lmpbtpor.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.c1oappe.top/Article/details/gt2ftobprzz.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gt2uqeykzfc.html

[Q01] 创建表
来源：http://dali.zhengqikj.top/Article/details/gt2juxwegnw.html

CREATE TABLE users (
来源：http://dali.9152youxi.cn/Article/details/gt2wuyrwyvq.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhoulong.xyz/Article/details/gt2oxbyvqqz.html

name VARCHAR(50) NOT NULL,
来源：http://dali.cucudq.cn/Article/details/gt2alrkeglb.html

email VARCHAR(100) UNIQUE,
来源：http://dali.daria6918.cn/Article/details/gt2szqxedtu.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.gzhubu.top/Article/details/gt2jmtrtnjh.html

);
来源：http://dali.vqdsnc.cn/Article/details/gt2kpehmtzg.html

[Q02] 创建带外键的表
来源：http://dali.nanxuanxn.top/Article/details/gt2yoljtfrn.html

CREATE TABLE orders (
来源：http://dali.meibo888.top/Article/details/gt2tbegoyqs.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ukjzjwdk.html

user_id INT NOT NULL,
来源：http://dali.zdqjudy.top/Article/details/gt2mkjavufk.html

amount DECIMAL(10, 2),
来源：http://dali.ehwqpu.com/Article/details/gt2amgrcejp.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.aizwys.cn/Article/details/gt2bxtsalth.html


<!-- 参考信息 -->