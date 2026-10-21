代发 wailian999

TS:   process.cwd()
来源：http://dali.quarkkingdee.top/Article/details/gtdosqclzg.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.wangshuangyany.cn/Article/details/gtagwkffac.html

Go:   os.Getwd()
来源：http://dali.fengsongda.top/Article/details/gtccwopnda.html

Ruby: Dir.pwd
来源：http://dali.sxryk.cn/Article/details/gtvjsmlord.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.jqgfzy.top/Article/details/gtubxztvod.html

[M05] 设置退出码
来源：http://dali.9152youxi.cn/Article/details/gtvdgdulsm.html

Py:   sys.exit(1)
来源：http://dali.yj20258.top/Article/details/gttgjikbae.html

PHP:  exit(1);
来源：http://dali.kuanghao11.cn/Article/details/gtzirhxnwy.html

JS:   process.exit(1)
来源：http://dali.xuetiantiany.cn/Article/details/gtxbeldxmd.html

TS:   process.exit(1)
来源：http://dali.ivvv.top/Article/details/gtfedampkq.html

Java: System.exit(1)
来源：http://dali.zdqjudy.top/Article/details/gtnpssltrb.html

Go:   os.Exit(1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdiuheoly.html

Ruby: exit 1
来源：http://dali.smart0.xyz/Article/details/gtcxdbzolp.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.ybcxt.top/Article/details/gtlbeyugzh.html

[M06] 向标准错误输出
来源：http://dali.quarkkingdee.top/Article/details/gtbuldiyxz.html

Py:   print("err", file=sys.stderr)
来源：http://dali.quarkkingdee.top/Article/details/gtrmlobqdz.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.haohaochexian.top/Article/details/gtpchsisaa.html

JS:   console.error("err")
来源：http://dali.xziqi.cn/Article/details/gtzhycuewc.html

TS:   console.error("err")
来源：http://dali.jqgufenzy.top/Article/details/gtdavhawix.html

Java: System.err.println("err")
来源：http://dali.sweek.top/Article/details/gtwmiyhyyc.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.chenjidiqi.icu/Article/details/gtxgxhxuuk.html

Ruby: warn "err"
来源：http://dali.xylfe.cn/Article/details/gtzoepyhgi.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.smart0.xyz/Article/details/gthkggtleu.html

[M07] 判断是否为主入口
来源：http://dali.zhongyouzk.top/Article/details/gtsfvnolaa.html

Py:   if __name__ == "__main__":
来源：http://dali.chenzaomai.com/Article/details/gthdvvneda.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.jinqigufen.top/Article/details/gtzfcgfkvr.html

JS:   require.main === module
来源：http://dali.yanxiufei.cn/Article/details/gtbcgddjhq.html

TS:   require.main === module
来源：http://dali.hysaishi.cn/Article/details/gtxqxszdgj.html

Java: public static void main(String[] args)
来源：http://dali.jqgufenzy.top/Article/details/gthpfphorh.html

Go:   func main()
来源：http://dali.yanxiufei.cn/Article/details/gtgvqvhitb.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.9152youxi.cn/Article/details/gtkcvafcro.html

C#:   static void Main(string[] args)
来源：http://dali.chenjidiqi.icu/Article/details/gtunwfhcxb.html

[M08] 获取系统与运行时信息
来源：http://dali.vqdsnc.cn/Article/details/gteozlutrk.html

Py:   platform.system();  platform.python_version()
来源：http://dali.c1oappe.top/Article/details/gtjxhadyez.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.sufxvd.cn/Article/details/gtzznkrecp.html

JS:   process.platform;  process.version
来源：http://dali.zhongyouzk.top/Article/details/gtgobyprdj.html

TS:   process.platform;  process.version
来源：http://dali.havefunace.top/Article/details/gtodjadcuk.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.yongpay.top/Article/details/gtifrtwwxi.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.ybcxt.top/Article/details/gtxsxelaca.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.ydzc1.top/Article/details/gtaqtkmxzn.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.hnqzz.top/Article/details/gtxtbikkbj.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtybwuasxu.html

N. 数据结构与算法
来源：http://dali.pengpengdd.cyou/Article/details/gtaoebpzja.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtzjmhviym.html

[N01] 二分查找（有序数组）
来源：http://dali.aibaodan.cn/Article/details/gtmedieebw.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.mhx1999.top/Article/details/gtryikoeoj.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.xziqi.cn/Article/details/gtjgmqvpot.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.haohaochexian.top/Article/details/gtzzbtcxbu.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.pycfn.com/Article/details/gtsdsvjqnz.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.sweek.top/Article/details/gtcydircbn.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.wangdashe.top/Article/details/gtqhehnxda.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.chenzaomai.com/Article/details/gtqviqjlwn.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.daxiang520.top/Article/details/gtngferett.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.316326.xyz/Article/details/gtbuqcqriq.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.ehwqpu.com/Article/details/gtlhzhtyjx.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.vqdsnc.cn/Article/details/gtexuqkrbx.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.fengsongda.top/Article/details/gtgcniotwu.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.cheryme.top/Article/details/gtebrutuel.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjhrwlhla.html

Go:   slices.Sort(arr)
来源：http://dali.jqgfzy.top/Article/details/gtevrvcjtr.html

Ruby: arr.sort
来源：http://dali.nanxuanxn.top/Article/details/gtkvtboter.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.guannengcc.top/Article/details/gtmqtsluge.html

[N03] 快速排序（分治示例）
来源：http://dali.iojbl.cn/Article/details/gtrhsiiepf.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.jlsjyb.cn/Article/details/gtcwetkmig.html

PHP:  // 递归实现，或用 usort
来源：http://dali.jiagoushi.top/Article/details/gtpomztixj.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.hywenlv.cn/Article/details/gtuvhmkgyu.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.cheryme.top/Article/details/gtnkdehkxd.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.nanxuanxn.top/Article/details/gtvskstvau.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.yonumen.top/Article/details/gtqmzctrku.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.gogol.net.cn/Article/details/gtwkepalpa.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zdqjudy.top/Article/details/gtaixbqtny.html

[N04] 斐波那契数列
来源：http://dali.jinqigfzy.top/Article/details/gtqayffodk.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.hysaishi.cn/Article/details/gtuczttotm.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.feifeiyinyue.top/Article/details/gtdoelvcvb.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.svipenyu.cn/Article/details/gtzaeyrujn.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.iojbl.cn/Article/details/gtlqojgvsy.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.hnqzz.top/Article/details/gtmputlafk.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdqqpvizc.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.wangshuangyany.cn/Article/details/gtyccxvxkm.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.aizwys.cn/Article/details/gtmwoqsail.html

[N05] 最大公约数
来源：http://dali.gaohongyu789.top/Article/details/gtkyzjbeje.html

Py:   math.gcd(a, b)
来源：http://dali.jyoumei.cn/Article/details/gtmssdkvnq.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.birdmap.top/Article/details/gtddidqnil.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zdqjudy.top/Article/details/gtbxvmxhda.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.wangdashe.top/Article/details/gtiqhdjbhd.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.shzxlz.cn/Article/details/gtgqcqktvg.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.yj202588.top/Article/details/gtkdvtbylt.html

Ruby: a.gcd(b)
来源：http://dali.haohaochexian.top/Article/details/gtgeypkfox.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.xinyue.icu/Article/details/gtiikpkbxf.html

[N06] 判断回文字符串
来源：http://dali.sysykeji.top/Article/details/gthrioutlo.html

Py:   s == s[::-1]
来源：http://dali.mhx1999.top/Article/details/gtrghruatf.html

PHP:  $s === strrev($s);
来源：http://dali.chenjidiqi.icu/Article/details/gtbezjwnbl.html

JS:   s === [...s].reverse().join("")
来源：http://dali.hongshengwenyu.top/Article/details/gtoctuedff.html

TS:   s === [...s].reverse().join("")
来源：http://dali.shangyingyoupin.top/Article/details/gtqlfetkga.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.fengsongda.top/Article/details/gtgzwzkryb.html

Go:   // 双指针从两端比较
来源：http://dali.ybcxt.top/Article/details/gteesfbhnf.html

Ruby: s == s.reverse
来源：http://dali.yonumen.top/Article/details/gtmfgcbsir.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.daxiang520.top/Article/details/gtmeoqrpan.html

[N07] 两数之和（返回下标）
来源：http://dali.jiagoushi.top/Article/details/gtuqquatqs.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.yuanzhike.top/Article/details/gtqlhzcrak.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.yonumen.top/Article/details/gtfagydhpy.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.xinyue.icu/Article/details/gtfesbahkq.html

TS:   // 手写 Map<string, number>
来源：http://dali.xuanzx.com/Article/details/gtawhzetco.html

Java: // 手写 HashMap
来源：http://dali.sysykeji.top/Article/details/gtvpcoisik.html

Go:   // 手写 map[int]int
来源：http://dali.zhixingplan.top/Article/details/gtsmgxdxom.html

Ruby: // 手写 Hash
来源：http://dali.ppjwa.cn/Article/details/gtrhzjgehl.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.nwbrower.top/Article/details/gtcsyjxvvh.html

[N08] 生成全排列
来源：http://dali.pengpengdd.cyou/Article/details/gthxmusxos.html

Py:   itertools.permutations(arr)
来源：http://dali.zhongyouzk.top/Article/details/gteuhdkglc.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gtvnoofqcv.html

JS:   // 手写回溯递归
来源：http://dali.daria6918.cn/Article/details/gtrqyectem.html

TS:   // 手写回溯递归
来源：http://dali.yueranfly.top/Article/details/gtziuqxivu.html

Java: // 手写回溯递归
来源：http://dali.jqgfzy.top/Article/details/gtpyzvohoq.html

Go:   // 手写回溯递归
来源：http://dali.feifeiyinyue.top/Article/details/gtgokkehtm.html

Ruby: arr.permutation.to_a
来源：http://dali.chenlongwang.top/Article/details/gtzeiyumxq.html

C#:   // 手写回溯递归
来源：http://dali.xziqi.cn/Article/details/gtlvmajcjh.html

[N09] 栈与队列
来源：http://dali.cdnleiting.top/Article/details/gtatpzqfcr.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.dianchejie.cn/Article/details/gtstabnhjl.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.gotoacloud.top/Article/details/gtnxalfjec.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.yuanzhike.top/Article/details/gtniuckrgr.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.bjfxy.top/Article/details/gtrqzbcqcv.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmczfheae.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.shanyushiyangtech.top/Article/details/gtbzqadyup.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.wangdashe.top/Article/details/gtvxnclixn.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.sufxvd.cn/Article/details/gttmvmnxdp.html

[N10] 链表节点定义
来源：http://dali.yvedp.cn/Article/details/gtuaqhkhcb.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.vqdsnc.cn/Article/details/gtgxitznnu.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.sysykeji.top/Article/details/gtrqmdtgwu.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.tianlin.xyz/Article/details/gtkzfwamlp.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.iojbl.cn/Article/details/gtwqmhruln.html

Java: class Node { int v; Node next; }
来源：http://dali.yj20258888.top/Article/details/gtpfvbkkpy.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.yangfankeji.com/Article/details/gtmsaoeqps.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhoulong.xyz/Article/details/gtfrzhdufq.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.sxryk.cn/Article/details/gtfbsnvtwt.html

[N11] 二叉树中序遍历
来源：http://dali.tianlin.xyz/Article/details/gtadjylapp.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.haohaochexian.top/Article/details/gtxlcynfgs.html

PHP:  // 手写递归函数
来源：http://dali.ybcxt.top/Article/details/gtylfsblgi.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.gzhubu.top/Article/details/gtugdnivxh.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.daxiang520.top/Article/details/gtyaeffnbw.html

Java: // 手写递归
来源：http://dali.jinqigufen.top/Article/details/gtwrqdpvaq.html

Go:   // 手写递归
来源：http://dali.gotoacloud.top/Article/details/gtsckdblmp.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.yongpay.top/Article/details/gtovnpuznj.html

C#:   // 手写递归
来源：http://dali.redwolf501.top/Article/details/gtdnjtopeu.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.nwbrower.top/Article/details/gtoklggvpc.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.cdnleiting.top/Article/details/gtwvbdvuch.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.jinghuilouyu.cn/Article/details/gtsopxssgv.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.ywan-chungtsiang.top/Article/details/gtghncooyk.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.9152youxi.cn/Article/details/gtnhwbxrea.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.aizwys.cn/Article/details/gtdjompowd.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.jqgfzy.top/Article/details/gthzozebve.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.pycfn.com/Article/details/gtujxaenyb.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.nanxuanxn.top/Article/details/gtisbaxjav.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtqffdqckd.html

O. 并发与异步
来源：http://dali.wangshuangyany.cn/Article/details/gtrevgvgzf.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtmajamhvc.html

[O01] 启动一个线程
来源：http://dali.wangshuangyany.cn/Article/details/gtgexzdiah.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.9152youxi.cn/Article/details/gtlpnualuy.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.hammf.cn/Article/details/gtcpnszwvz.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.xinyue.icu/Article/details/gtnpivecrf.html

TS:   // 同 JS
来源：http://dali.zhengqikj.top/Article/details/gtkbgsnhcn.html

Java: new Thread(() -> f()).start()
来源：http://dali.jinyuanbaomall.cn/Article/details/gttsnenvqi.html

Go:   go f()
来源：http://dali.xziqi.cn/Article/details/gtubiruxta.html

Ruby: Thread.new { f }
来源：http://dali.chenlongwang.top/Article/details/gtbcupegsw.html

C#:   Task.Run(() => F());
来源：http://dali.gotoacloud.top/Article/details/gtjzfffhom.html

[O02] 使用线程池
来源：http://dali.xuetiantiany.cn/Article/details/gtjlmrawgq.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.yj20258.top/Article/details/gtpsbslmxg.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvnbkysvm.html

JS:   // worker_threads 线程池
来源：http://dali.zhengqikj.top/Article/details/gtievcephd.html

TS:   // worker_threads 线程池
来源：http://dali.yuanzhike.top/Article/details/gtgzcscyuv.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.nanxinkj.top/Article/details/gtskiioihv.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.quarkkingdee.top/Article/details/gtcqmlkutz.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.ppjwa.cn/Article/details/gtmxydofnn.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.hongshengwenyu.top/Article/details/gtlrglbuov.html

[O03] 加锁保护共享数据
来源：http://dali.tian-w.cn/Article/details/gtepqbcihp.html

Py:   with lock: shared += 1
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfgjezlgs.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.gzhubu.top/Article/details/gtcejqkxmj.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.chenlongwang.top/Article/details/gtztfypgpf.html

TS:   // 同 JS
来源：http://dali.yj20258888.top/Article/details/gtxtutejqs.html

Java: synchronized (this) { shared++; }
来源：http://dali.jianghu66.top/Article/details/gtuwhzjqfr.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.cashguo.top/Article/details/gtemrlxizh.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.yj202588.top/Article/details/gtwdimzpro.html

C#:   lock (gate) { shared++; }
来源：http://dali.cdnleiting.top/Article/details/gtohanoelx.html

[O04] 定义异步函数并等待
来源：http://dali.cashguo.top/Article/details/gtvieppfmf.html

Py:   async def f():⏎    await g()
来源：http://dali.hnxiangtu.top/Article/details/gtynkoklit.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmbllnwxn.html

JS:   async function f() { await g(); }
来源：http://dali.cheryme.top/Article/details/gtawqzywhq.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.jlsjyb.cn/Article/details/gtteugwvwv.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.hammf.cn/Article/details/gtmziurbyu.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.jinqigfzy.top/Article/details/gtjyxkmiur.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.xziqi.cn/Article/details/gtjfibbhhb.html

C#:   async Task F() { await G(); }
来源：http://dali.fzhhl.top/Article/details/gtldqkpovq.html

[O05] 并发执行并等待全部完成
来源：http://dali.havefunace.top/Article/details/gtnotavyxd.html

Py:   asyncio.gather(*tasks)
来源：http://dali.xinyue.icu/Article/details/gtqcpvlpom.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.gotoacloud.top/Article/details/gtabmtsfna.html

JS:   await Promise.all(tasks)
来源：http://dali.andypj.xyz/Article/details/gtjlvzhbet.html

TS:   await Promise.all(tasks)
来源：http://dali.zycfv.cn/Article/details/gtvtbpxlfm.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.cheryme.top/Article/details/gtkejxdzgi.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.pycfn.com/Article/details/gtvjsnhvjf.html

Ruby: threads.map(&:join)
来源：http://dali.xylfe.cn/Article/details/gtfrzttuiy.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.aizwys.cn/Article/details/gtltesgemo.html

[O06] 使用进程池
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbuhnzwys.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhengqikj.top/Article/details/gtdbjjrsln.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.hysaishi.cn/Article/details/gtibvwgzaj.html

JS:   // child_process / cluster 模块
来源：http://dali.xinyue.icu/Article/details/gtfaaepeuc.html

TS:   // child_process / cluster 模块
来源：http://dali.wangdashe.top/Article/details/gthkroiptg.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.guowangkeji.top/Article/details/gtbtmmvvtl.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.bjfxy.top/Article/details/gtlugkqula.html

Ruby: // fork 块
来源：http://dali.yonumen.top/Article/details/gtymfczsmx.html

C#:   Parallel.For
来源：http://dali.zhengqikj.top/Article/details/gtxfmukjdy.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtfalzpqzq.html

P. 常用工具函数
来源：http://dali.ivvv.top/Article/details/gttnrptfdh.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtzvpagidc.html

[P01] 生成 UUID
来源：http://dali.bjfxy.top/Article/details/gtebxqidke.html

Py:   str(uuid.uuid4())
来源：http://dali.svipenyu.cn/Article/details/gtsixqztea.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.sysykeji.top/Article/details/gtxnlhbszz.html

JS:   crypto.randomUUID()
来源：http://dali.guannengcc.top/Article/details/gtsdktcngk.html

TS:   crypto.randomUUID()
来源：http://dali.daria6918.cn/Article/details/gtwwuwunno.html

Java: UUID.randomUUID().toString()
来源：http://dali.andypj.xyz/Article/details/gtlqqjvfif.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhengqikj.top/Article/details/gtvrwvlman.html

Ruby: SecureRandom.uuid
来源：http://dali.hysaishi.cn/Article/details/gtqaoxwduf.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.iojbl.cn/Article/details/gtifwefqdw.html

[P02] MD5 / SHA256 摘要
来源：http://dali.pengpengdd.cyou/Article/details/gtyqtmwvrc.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.aizwys.cn/Article/details/gtgtvtngwl.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.jinghuilouyu.cn/Article/details/gttqkxzdrr.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.hywenlv.cn/Article/details/gtxfbrtphr.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.sweek.top/Article/details/gtfddxnyoy.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.xuetiantiany.cn/Article/details/gtbihgndza.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmkkqssbl.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhengqikj.top/Article/details/gttkmnurpm.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.shuidangran.top/Article/details/gtycxxuljt.html

[P03] 生成短随机字符串
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnwzjlueg.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.sxryk.cn/Article/details/gtbobuqgkf.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.hammf.cn/Article/details/gtjkpmaqmt.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jlsjyb.cn/Article/details/gteqhnpvfm.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.sxryk.cn/Article/details/gtuphynkfo.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhongyouzk.top/Article/details/gtbkwyelon.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsbvffusu.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.wangdashe.top/Article/details/gtuapbkfgp.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.gzhubu.top/Article/details/gtnwvcsimy.html

[P04] 求长度
来源：http://dali.shuidangran.top/Article/details/gthvdotlqo.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.nanxinkj.top/Article/details/gtoukryohy.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jinghuilouyu.cn/Article/details/gtzxhwwwys.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.xziqi.cn/Article/details/gtmtbjsbkg.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.hywenlv.cn/Article/details/gtaookckrq.html

Java: list.size();  map.size();  s.length()
来源：http://dali.shangyingyoupin.top/Article/details/gtdufipjlz.html

Go:   len(arr);  len(m)
来源：http://dali.aizwys.cn/Article/details/gtyybffgzv.html

Ruby: x.length;  x.size
来源：http://dali.316326.xyz/Article/details/gtunvnysrl.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.jianghu66.top/Article/details/gtclnwxblm.html

[P05] 判断两个对象内容是否相等
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzyqeymgf.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.wangshuangyany.cn/Article/details/gtfhbfkkts.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zycfv.cn/Article/details/gtfizqibni.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.jiagoushi.top/Article/details/gtmdljjwnv.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.feifeiyinyue.top/Article/details/gtjtwgjfxb.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.shzxlz.cn/Article/details/gttdlxavbo.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhengqikj.top/Article/details/gtkaqnjyek.html

Ruby: a == b
来源：http://dali.vqdsnc.cn/Article/details/gtvtracvpy.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.shzxlz.cn/Article/details/gtbjykbmnf.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.jinqigfzy.top/Article/details/gtumavpbsh.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.yj202588.top/Article/details/gtsvukivfb.html

PHP:  if (empty($x)) {}
来源：http://dali.shzxlz.cn/Article/details/gtmxmtnffj.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.yuxming.cn/Article/details/gtrencuziv.html

TS:   if (x == null) {}
来源：http://dali.wangdashe.top/Article/details/gtnfksflyh.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.ybcxt.top/Article/details/gtgdtfiwvn.html

Go:   if x == nil {}
来源：http://dali.wangdashe.top/Article/details/gtviywjlix.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.sxryk.cn/Article/details/gtdrhngrld.html

C#:   if (x is null) {}
来源：http://dali.daxiang520.top/Article/details/gtzxywybak.html

[P07] 防抖与节流
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfgvhbjsg.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgafhcewv.html

PHP:  // 手写时间戳比较
来源：http://dali.yj202588.top/Article/details/gtedzffytg.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.sufxvd.cn/Article/details/gtgqlpgelz.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.tian-w.cn/Article/details/gtsmwzptrp.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.hnxiangtu.top/Article/details/gtvlzarafd.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.daxiang520.top/Article/details/gtvjqiphbq.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.ydzc1.top/Article/details/gtbbqfrvny.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.xylfe.cn/Article/details/gttuhbqrfz.html

[P08] 处理浮点精度问题
来源：http://dali.chenlongwang.top/Article/details/gtzzfmdvjz.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.smart0.xyz/Article/details/gtovprpqao.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.haohaochexian.top/Article/details/gtqfaucbgl.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.hnqzz.top/Article/details/gtvxwmmgam.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhengqikj.top/Article/details/gtwotopysx.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.gotoacloud.top/Article/details/gtblcvhafl.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.kuanghao11.cn/Article/details/gtiqefapxc.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.feifeiyinyue.top/Article/details/gtjtozlryd.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.ivvv.top/Article/details/gthyjuefzt.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gthdftlmqm.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.sweek.top/Article/details/gtlcljsdjp.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gthwovazkd.html

[Q01] 创建表
来源：http://dali.yonumen.top/Article/details/gtkihsrldp.html

CREATE TABLE users (
来源：http://dali.pengpengdd.cyou/Article/details/gtvciiaype.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.dianchejie.cn/Article/details/gttykqeuhq.html

name VARCHAR(50) NOT NULL,
来源：http://dali.birdmap.top/Article/details/gtkivjyglc.html

email VARCHAR(100) UNIQUE,
来源：http://dali.daxiang520.top/Article/details/gtgyzqepsg.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.nanxuanxn.top/Article/details/gtgpauhzff.html

);
来源：http://dali.bjfxy.top/Article/details/gtabxwyssi.html

[Q02] 创建带外键的表
来源：http://dali.sufxvd.cn/Article/details/gtgdyygegd.html

CREATE TABLE orders (
来源：http://dali.wangshuangyany.cn/Article/details/gtcejsrjcj.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.nanxuanxn.top/Article/details/gtgphbvwcu.html

user_id INT NOT NULL,
来源：http://dali.jinqigufen.top/Article/details/gtkdvbwwqq.html

amount DECIMAL(10, 2),
来源：http://dali.fzhhl.top/Article/details/gtpiafwsdo.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.tanke756.top/Article/details/gtqpfmaicg.html


<!-- 参考信息 -->