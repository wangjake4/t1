代发 wailian999

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.dianchejie.cn/Article/details/gtfwlcnjxp.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.jinqigufen.top/Article/details/gtnpzhlkgz.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.jinqigfzy.top/Article/details/gtrhgzqpxn.html

C#:   Process.Start("ls", "-l");
来源：http://dali.jinqigufen.top/Article/details/gtfbsqyalj.html

[M04] 获取当前工作目录
来源：http://dali.zhongyouzk.top/Article/details/gtjiyimbcu.html

Py:   os.getcwd()
来源：http://dali.chenzaomai.com/Article/details/gtjtydirdh.html

PHP:  getcwd();
来源：http://dali.zhixingplan.top/Article/details/gtjbcnztsp.html

JS:   process.cwd()
来源：http://dali.chenlongwang.top/Article/details/gtjrhwibxd.html

TS:   process.cwd()
来源：http://dali.9152youxi.cn/Article/details/gtogloxvyq.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.hammf.cn/Article/details/gthekvzljp.html

Go:   os.Getwd()
来源：http://dali.sweek.top/Article/details/gtgfxnzkea.html

Ruby: Dir.pwd
来源：http://dali.guannengcc.top/Article/details/gtmhpvknvq.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.jyoumei.cn/Article/details/gtjqsvudvj.html

[M05] 设置退出码
来源：http://dali.hysaishi.cn/Article/details/gtocvnwqhj.html

Py:   sys.exit(1)
来源：http://dali.shangyingyoupin.top/Article/details/gtygnnxpcv.html

PHP:  exit(1);
来源：http://dali.andypj.xyz/Article/details/gteaixuzrc.html

JS:   process.exit(1)
来源：http://dali.vqdsnc.cn/Article/details/gtkdvrmqgt.html

TS:   process.exit(1)
来源：http://dali.cdnleiting.top/Article/details/gtaqburffq.html

Java: System.exit(1)
来源：http://dali.gaohongyu789.top/Article/details/gtoxzzkaty.html

Go:   os.Exit(1)
来源：http://dali.xuanzx.com/Article/details/gtcwvhyiex.html

Ruby: exit 1
来源：http://dali.yj20258.top/Article/details/gtaxkkczvt.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.cucudq.cn/Article/details/gtvavtgwsb.html

[M06] 向标准错误输出
来源：http://dali.mhx1999.top/Article/details/gtubsltcly.html

Py:   print("err", file=sys.stderr)
来源：http://dali.jqgufenzy.top/Article/details/gtrhjyevfi.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtibsqvkrb.html

JS:   console.error("err")
来源：http://dali.yongpay.top/Article/details/gtskgphbqa.html

TS:   console.error("err")
来源：http://dali.shzxlz.cn/Article/details/gtxctpxxoc.html

Java: System.err.println("err")
来源：http://dali.jyoumei.cn/Article/details/gtultpqewg.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.havefunace.top/Article/details/gtounlzzgd.html

Ruby: warn "err"
来源：http://dali.jianghu66.top/Article/details/gtajgvyncv.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.jinqigfzy.top/Article/details/gtvfhnjian.html

[M07] 判断是否为主入口
来源：http://dali.redwolf501.top/Article/details/gtmzyvcwmx.html

Py:   if __name__ == "__main__":
来源：http://dali.fengsongda.top/Article/details/gtivavilnb.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.sweek.top/Article/details/gtlmcjaxoj.html

JS:   require.main === module
来源：http://dali.mhx1999.top/Article/details/gtxturglok.html

TS:   require.main === module
来源：http://dali.yj20258.top/Article/details/gtsftcscmo.html

Java: public static void main(String[] args)
来源：http://dali.316326.xyz/Article/details/gtfhurcrjp.html

Go:   func main()
来源：http://dali.wangdashe.top/Article/details/gtenbvrleu.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.chenjidiqi.icu/Article/details/gtvmaodubt.html

C#:   static void Main(string[] args)
来源：http://dali.yuxming.cn/Article/details/gtajashxku.html

[M08] 获取系统与运行时信息
来源：http://dali.hongshengwenyu.top/Article/details/gtgprozscj.html

Py:   platform.system();  platform.python_version()
来源：http://dali.xziqi.cn/Article/details/gtmbrbesaa.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.bjfxy.top/Article/details/gtjmwxzvux.html

JS:   process.platform;  process.version
来源：http://dali.yvedp.cn/Article/details/gtcfadvjeh.html

TS:   process.platform;  process.version
来源：http://dali.ivvv.top/Article/details/gtrpoiqacq.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.birdmap.top/Article/details/gtldnwpspy.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.jinqigfzy.top/Article/details/gtdfjplvcu.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.guowangkeji.top/Article/details/gtynftltsn.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.chenzaomai.com/Article/details/gtsiajbjew.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtwosakqpb.html

N. 数据结构与算法
来源：http://dali.yanxiufei.cn/Article/details/gteplpusgi.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtsxetdtxx.html

[N01] 二分查找（有序数组）
来源：http://dali.nwbrower.top/Article/details/gtcmudmefa.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.birdmap.top/Article/details/gtrzsqprqe.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.yueranfly.top/Article/details/gtnmezibzt.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jqgfzy.top/Article/details/gtpzpvseil.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.wangshuangyany.cn/Article/details/gtnguczjge.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.hfpthk.cn/Article/details/gtsupsgsvw.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.yuanzhike.top/Article/details/gtflaliade.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.sxryk.cn/Article/details/gtucubgmjn.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.dashuyun.cn/Article/details/gtmsznlgeq.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtorirktbe.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.guowangkeji.top/Article/details/gtcjhxxrum.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.dianchejie.cn/Article/details/gtzuzqoetb.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.tian-w.cn/Article/details/gtvkvgbfox.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.sufxvd.cn/Article/details/gtslxkubbv.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.yj20258.top/Article/details/gtdcgsxyto.html

Go:   slices.Sort(arr)
来源：http://dali.cqqwz.cn/Article/details/gtfqgcprcz.html

Ruby: arr.sort
来源：http://dali.quarkkingdee.top/Article/details/gteamgrbcg.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.xuetiantiany.cn/Article/details/gtfkkcrlur.html

[N03] 快速排序（分治示例）
来源：http://dali.zhengqikj.top/Article/details/gtdxrxbwyo.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.wangshuangyany.cn/Article/details/gtrqstpcpz.html

PHP:  // 递归实现，或用 usort
来源：http://dali.wangdashe.top/Article/details/gtdyeyqous.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.tian-w.cn/Article/details/gttilmzuuo.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.cheryme.top/Article/details/gtojelhovt.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.jinqigfzy.top/Article/details/gtcconwsbd.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.xuanzx.com/Article/details/gtvevgpfju.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.xinyue.icu/Article/details/gtequtqmxd.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.aizwys.cn/Article/details/gtevshcimn.html

[N04] 斐波那契数列
来源：http://dali.iojbl.cn/Article/details/gtmahdrnzx.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.cqqwz.cn/Article/details/gtwkoyldnt.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.aizwys.cn/Article/details/gtrchzqdfs.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yanxiufei.cn/Article/details/gteumqeadd.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gteivpjzyg.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhoulong.xyz/Article/details/gtvnuboqxc.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zycfv.cn/Article/details/gtbevzxlvd.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.yanxiufei.cn/Article/details/gtvdvtgzhs.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.jqgfzy.top/Article/details/gtwxxcoimn.html

[N05] 最大公约数
来源：http://dali.ppjwa.cn/Article/details/gtzflogxls.html

Py:   math.gcd(a, b)
来源：http://dali.zdqjudy.top/Article/details/gtcgcmzpdr.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.sufxvd.cn/Article/details/gtaspharix.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhengqikj.top/Article/details/gthhkknlcj.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zdqjudy.top/Article/details/gtwvkfxbpv.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.hywenlv.cn/Article/details/gtcgpymqci.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.hywenlv.cn/Article/details/gtvhnweieu.html

Ruby: a.gcd(b)
来源：http://dali.yj202588.top/Article/details/gtzsvhepgj.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.yueranfly.top/Article/details/gtgonhxrer.html

[N06] 判断回文字符串
来源：http://dali.ppjwa.cn/Article/details/gtiexybcai.html

Py:   s == s[::-1]
来源：http://dali.bjfxy.top/Article/details/gtwhltdlwj.html

PHP:  $s === strrev($s);
来源：http://dali.fengsongda.top/Article/details/gtcevycype.html

JS:   s === [...s].reverse().join("")
来源：http://dali.cheryme.top/Article/details/gtrcfswdfz.html

TS:   s === [...s].reverse().join("")
来源：http://dali.xziqi.cn/Article/details/gtgkgksgui.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.iojbl.cn/Article/details/gtpbvertud.html

Go:   // 双指针从两端比较
来源：http://dali.hammf.cn/Article/details/gtwprnxxmv.html

Ruby: s == s.reverse
来源：http://dali.pengpengdd.cyou/Article/details/gtkxhcpywj.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.chenzaomai.com/Article/details/gtxpsvrvht.html

[N07] 两数之和（返回下标）
来源：http://dali.redwolf501.top/Article/details/gtxxsdwakw.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.aizwys.cn/Article/details/gtwgebydjv.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.yuanzhike.top/Article/details/gthtvitiyw.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.dianchejie.cn/Article/details/gtxazfsjgu.html

TS:   // 手写 Map<string, number>
来源：http://dali.dashuyun.cn/Article/details/gtxabophgi.html

Java: // 手写 HashMap
来源：http://dali.tianlin.xyz/Article/details/gtyluyeuor.html

Go:   // 手写 map[int]int
来源：http://dali.316326.xyz/Article/details/gtxsgjudkh.html

Ruby: // 手写 Hash
来源：http://dali.jinghuilouyu.cn/Article/details/gtllmyrbab.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.vqdsnc.cn/Article/details/gthtwxutoi.html

[N08] 生成全排列
来源：http://dali.pengpengdd.cyou/Article/details/gtoorvdgsw.html

Py:   itertools.permutations(arr)
来源：http://dali.xuetiantiany.cn/Article/details/gtcesdmboq.html

PHP:  // 手写递归交换
来源：http://dali.wangdashe.top/Article/details/gtzktkrduq.html

JS:   // 手写回溯递归
来源：http://dali.quarkkingdee.top/Article/details/gttcsmomxc.html

TS:   // 手写回溯递归
来源：http://dali.cucudq.cn/Article/details/gtldspkems.html

Java: // 手写回溯递归
来源：http://dali.dianchejie.cn/Article/details/gtpqxuhteh.html

Go:   // 手写回溯递归
来源：http://dali.vqdsnc.cn/Article/details/gtfpecoplv.html

Ruby: arr.permutation.to_a
来源：http://dali.sysykeji.top/Article/details/gtusyzqvoi.html

C#:   // 手写回溯递归
来源：http://dali.yangfankeji.com/Article/details/gtremhbohd.html

[N09] 栈与队列
来源：http://dali.jianghu66.top/Article/details/gtjsrjrjgu.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.jinqigufen.top/Article/details/gtbvbpbmzr.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.shzxlz.cn/Article/details/gttgrzjwqp.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.0kj1m.cn/Article/details/gtmirkryub.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.aizwys.cn/Article/details/gtdtyllahp.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.jqgufenzy.top/Article/details/gtcdespafb.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.daria6918.cn/Article/details/gttrxixwmb.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfqgahfuw.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.316326.xyz/Article/details/gtkafkchmq.html

[N10] 链表节点定义
来源：http://dali.xylfe.cn/Article/details/gtcacelmmu.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.gzhubu.top/Article/details/gtalhcqgot.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhiwuduotai.top/Article/details/gtiernufht.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.gogol.net.cn/Article/details/gtdhisdoah.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.yanxiufei.cn/Article/details/gtefhqjtea.html

Java: class Node { int v; Node next; }
来源：http://dali.jinqigufen.top/Article/details/gtolfkqlmg.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.jinqigufen.top/Article/details/gtovaxivor.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.xylfe.cn/Article/details/gthsiougxc.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.yuxming.cn/Article/details/gtgtdhsylo.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gtabtpqvfs.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.xylfe.cn/Article/details/gtfulkqexz.html

PHP:  // 手写递归函数
来源：http://dali.jinqigufen.top/Article/details/gtokwbvwus.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zycfv.cn/Article/details/gtsqvnlzev.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.shanyushiyangkeji.top/Article/details/gthmvognbi.html

Java: // 手写递归
来源：http://dali.redwolf501.top/Article/details/gtdlkfztkm.html

Go:   // 手写递归
来源：http://dali.guowangkeji.top/Article/details/gtdsirgayl.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.ivvv.top/Article/details/gttekrjcpu.html

C#:   // 手写递归
来源：http://dali.iojbl.cn/Article/details/gtpegnwvfa.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhixingplan.top/Article/details/gtscaulxmx.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.dashuyun.cn/Article/details/gtabeowyot.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.jqgufenzy.top/Article/details/gtkcknpifq.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.iojbl.cn/Article/details/gtzsmfcuma.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.wangdashe.top/Article/details/gtqkeiiylk.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.pengpengdd.cyou/Article/details/gtomlokylp.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.wangshuangyany.cn/Article/details/gtmydhgxhb.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.nwbrower.top/Article/details/gtrqducicv.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.fzhhl.top/Article/details/gtaswhwegi.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtigqxpdve.html

O. 并发与异步
来源：http://dali.quarkkingdee.top/Article/details/gtagwvtnkx.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gteiuoeuqi.html

[O01] 启动一个线程
来源：http://dali.jinqigfzy.top/Article/details/gtlxauivhg.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.yuxming.cn/Article/details/gttxfvomjl.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zycfv.cn/Article/details/gtlyprwfqg.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.jqgufenzy.top/Article/details/gtpgfkuhem.html

TS:   // 同 JS
来源：http://dali.0kj1m.cn/Article/details/gtzzlyubeb.html

Java: new Thread(() -> f()).start()
来源：http://dali.dashuyun.cn/Article/details/gtjddokfjk.html

Go:   go f()
来源：http://dali.chenjidiqi.icu/Article/details/gtoezseges.html

Ruby: Thread.new { f }
来源：http://dali.chenzaomai.com/Article/details/gtfbqtljry.html

C#:   Task.Run(() => F());
来源：http://dali.jinqigufen.top/Article/details/gtnovuujcz.html

[O02] 使用线程池
来源：http://dali.dashuyun.cn/Article/details/gtrjlpyugo.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.dianchejie.cn/Article/details/gtiwlvezjl.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.yj20258.top/Article/details/gtnpfehndr.html

JS:   // worker_threads 线程池
来源：http://dali.9152youxi.cn/Article/details/gtdgvlftmx.html

TS:   // worker_threads 线程池
来源：http://dali.daria6918.cn/Article/details/gtglcdrdxh.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.yueranfly.top/Article/details/gthwekwdsf.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhongyouzk.top/Article/details/gtgewaidoh.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.yj202588.top/Article/details/gtrexnmzew.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.guannengcc.top/Article/details/gtcnlbyvch.html

[O03] 加锁保护共享数据
来源：http://dali.sufxvd.cn/Article/details/gtajlwiulk.html

Py:   with lock: shared += 1
来源：http://dali.yongpay.top/Article/details/gtwnrrwqem.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhixingplan.top/Article/details/gthqgvhuuk.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.chenzaomai.com/Article/details/gtwezsivlg.html

TS:   // 同 JS
来源：http://dali.chenlongwang.top/Article/details/gtculerenz.html

Java: synchronized (this) { shared++; }
来源：http://dali.yj20258.top/Article/details/gtkeavbsya.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.wangdashe.top/Article/details/gtwvgakggu.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.sufxvd.cn/Article/details/gtrhgvdwsh.html

C#:   lock (gate) { shared++; }
来源：http://dali.vqdsnc.cn/Article/details/gtvsnlyvpi.html

[O04] 定义异步函数并等待
来源：http://dali.mhx1999.top/Article/details/gtlpwaykym.html

Py:   async def f():⏎    await g()
来源：http://dali.nanxinkj.top/Article/details/gtmykauawo.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.daria6918.cn/Article/details/gtatwtkaqg.html

JS:   async function f() { await g(); }
来源：http://dali.andypj.xyz/Article/details/gteamhsfqh.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.ybcxt.top/Article/details/gthduuphpa.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.tianlin.xyz/Article/details/gtnlhybgao.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.bjfxy.top/Article/details/gtvmxylsxk.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.fzhhl.top/Article/details/gtpswjxdpu.html

C#:   async Task F() { await G(); }
来源：http://dali.ehwqpu.com/Article/details/gtzbtdjymy.html

[O05] 并发执行并等待全部完成
来源：http://dali.nanxinkj.top/Article/details/gtobzpodrr.html

Py:   asyncio.gather(*tasks)
来源：http://dali.smart0.xyz/Article/details/gtoirbquax.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.cdnleiting.top/Article/details/gtavpczgxh.html

JS:   await Promise.all(tasks)
来源：http://dali.daria6918.cn/Article/details/gtocotnvrk.html

TS:   await Promise.all(tasks)
来源：http://dali.gzhubu.top/Article/details/gtmrlidxys.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.gzhubu.top/Article/details/gtxqmobmpd.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.meibo888.top/Article/details/gtwkawmjfs.html

Ruby: threads.map(&:join)
来源：http://dali.meibo888.top/Article/details/gtjxtttynb.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.fengsongda.top/Article/details/gttplfgfhx.html

[O06] 使用进程池
来源：http://dali.ppjwa.cn/Article/details/gteegmasqn.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.xziqi.cn/Article/details/gtkvtxtgfa.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zycfv.cn/Article/details/gtbgdbawsw.html

JS:   // child_process / cluster 模块
来源：http://dali.dianchejie.cn/Article/details/gtksiniyqg.html

TS:   // child_process / cluster 模块
来源：http://dali.ydzc1.top/Article/details/gtukffchsb.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.xinyue.icu/Article/details/gttafyofae.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.xuetiantiany.cn/Article/details/gtgdpsmomw.html

Ruby: // fork 块
来源：http://dali.nanxuanxn.top/Article/details/gtgwlipqol.html

C#:   Parallel.For
来源：http://dali.yj20258888.top/Article/details/gtrqdrtdwc.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtqdnbntvu.html

P. 常用工具函数
来源：http://dali.bjfxy.top/Article/details/gthstbzuif.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtwnimhiap.html

[P01] 生成 UUID
来源：http://dali.hnxiangtu.top/Article/details/gtuhukruga.html

Py:   str(uuid.uuid4())
来源：http://dali.daxiang520.top/Article/details/gtfxgermfs.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.guowangkeji.top/Article/details/gtdmgogmkh.html

JS:   crypto.randomUUID()
来源：http://dali.daxiang520.top/Article/details/gtwmthqshq.html

TS:   crypto.randomUUID()
来源：http://dali.bjfxy.top/Article/details/gtpquakems.html

Java: UUID.randomUUID().toString()
来源：http://dali.iojbl.cn/Article/details/gteambolsl.html

Go:   // 用 github.com/google/uuid
来源：http://dali.yonumen.top/Article/details/gtklbopyfm.html

Ruby: SecureRandom.uuid
来源：http://dali.wangdashe.top/Article/details/gtogktezuw.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.gaohongyu789.top/Article/details/gticzediex.html

[P02] MD5 / SHA256 摘要
来源：http://dali.cheryme.top/Article/details/gtczsnjkzu.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.wangdashe.top/Article/details/gtzufyyjcd.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.ydzc1.top/Article/details/gtongwbcyv.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.chenlongwang.top/Article/details/gtbbgwifjd.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhengqikj.top/Article/details/gtmionrddi.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.chenjidiqi.icu/Article/details/gtzchgeblz.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.pycfn.com/Article/details/gtgzuhcwbg.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.gaohongyu789.top/Article/details/gtxjjovals.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.sxryk.cn/Article/details/gtwfkvheje.html

[P03] 生成短随机字符串
来源：http://dali.wangshuangyany.cn/Article/details/gtwieflyqb.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.wangdashe.top/Article/details/gtepefaqhu.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.9152youxi.cn/Article/details/gtjxmpwasv.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jianghu66.top/Article/details/gtaeemtkht.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gtgwagvadl.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zycfv.cn/Article/details/gtppyvylrl.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.yangfankeji.com/Article/details/gtcjwetmhm.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.cashguo.top/Article/details/gtfkazvkvh.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.aizwys.cn/Article/details/gtsbseojfd.html

[P04] 求长度
来源：http://dali.xylfe.cn/Article/details/gtkbwkxbec.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.snrcjt.cn/Article/details/gtsjedwjtj.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.gotoacloud.top/Article/details/gtmahoezeg.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzcpehvip.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.iojbl.cn/Article/details/gtrovpbftx.html

Java: list.size();  map.size();  s.length()
来源：http://dali.jiagoushi.top/Article/details/gtipvpqthv.html

Go:   len(arr);  len(m)
来源：http://dali.yj202588.top/Article/details/gtorxkbyfg.html

Ruby: x.length;  x.size
来源：http://dali.ybcxt.top/Article/details/gtojwdfvgd.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtncpokytt.html

[P05] 判断两个对象内容是否相等
来源：http://dali.yj20258.top/Article/details/gtupwyqtva.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.c1oappe.top/Article/details/gtnysmqcli.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.meibo888.top/Article/details/gtvgodldvt.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.jiagoushi.top/Article/details/gtrxvrhjoz.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.yanxiufei.cn/Article/details/gtwdcippak.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.fzhhl.top/Article/details/gtemnsvzlx.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhoulong.xyz/Article/details/gtrzdxcksq.html

Ruby: a == b
来源：http://dali.sysykeji.top/Article/details/gttrexfblj.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.dianchejie.cn/Article/details/gthjliovuk.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.kuanghao11.cn/Article/details/gtsybopfwc.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.tianlin.xyz/Article/details/gthyqfdvpp.html

PHP:  if (empty($x)) {}
来源：http://dali.guannengcc.top/Article/details/gtdifxboen.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.xziqi.cn/Article/details/gtclepqotv.html

TS:   if (x == null) {}
来源：http://dali.hnxiangtu.top/Article/details/gtpkfrqlfx.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.chenlongwang.top/Article/details/gtvvjcosdp.html

Go:   if x == nil {}
来源：http://dali.pycfn.com/Article/details/gtdrjdebnv.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.ydzc1.top/Article/details/gthcltyskp.html

C#:   if (x is null) {}
来源：http://dali.chenzaomai.com/Article/details/gtfrqdcpbc.html

[P07] 防抖与节流
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwbziichy.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zdqjudy.top/Article/details/gtqgpywqgp.html

PHP:  // 手写时间戳比较
来源：http://dali.chenzaomai.com/Article/details/gtinuneerw.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.chenzaomai.com/Article/details/gtallqalvj.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhiwuduotai.top/Article/details/gtwtasiojt.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.redwolf501.top/Article/details/gtfaeymupw.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.shangyingyoupin.top/Article/details/gtwtayteel.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoqrbpspn.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.xinyue.icu/Article/details/gttfkaydyr.html

[P08] 处理浮点精度问题
来源：http://dali.yangfankeji.com/Article/details/gthljsnpyh.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.gotoacloud.top/Article/details/gtufnfspge.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.chenlongwang.top/Article/details/gtbpwyhjhk.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.sxryk.cn/Article/details/gtstpqbned.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.bjfxy.top/Article/details/gtwzlkyvct.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.yangfankeji.com/Article/details/gtfsghjfmb.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.cucudq.cn/Article/details/gtvogextqt.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhiwuduotai.top/Article/details/gtqvksehvo.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.0kj1m.cn/Article/details/gtsutarvvf.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtspaflnws.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhoulong.xyz/Article/details/gteijdijuf.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtgysmlqte.html

[Q01] 创建表
来源：http://dali.tian-w.cn/Article/details/gtusnymppj.html

CREATE TABLE users (
来源：http://dali.svipenyu.cn/Article/details/gtoypnysva.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.chenzaomai.com/Article/details/gtdufqlcwd.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gtgsalfxel.html

email VARCHAR(100) UNIQUE,
来源：http://dali.jqgfzy.top/Article/details/gtebvbrxfs.html


<!-- 参考信息 -->