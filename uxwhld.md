代发 wailian999

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxsfocjds.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.chenjidiqi.icu/Article/details/gtjkaubniu.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.snrcjt.cn/Article/details/gtwxjgnnyd.html

C#:   Process.Start("ls", "-l");
来源：http://dali.tanke756.top/Article/details/gtjpgloovi.html

[M04] 获取当前工作目录
来源：http://dali.bjfxy.top/Article/details/gtyzohflyg.html

Py:   os.getcwd()
来源：http://dali.c1oappe.top/Article/details/gtjbypcmis.html

PHP:  getcwd();
来源：http://dali.xziqi.cn/Article/details/gtmhmvqrnp.html

JS:   process.cwd()
来源：http://dali.ivvv.top/Article/details/gtgjziatje.html

TS:   process.cwd()
来源：http://dali.chenlongwang.top/Article/details/gtibknhryk.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.sxryk.cn/Article/details/gtjzutqgdf.html

Go:   os.Getwd()
来源：http://dali.aibaodan.cn/Article/details/gtdzvqtpmp.html

Ruby: Dir.pwd
来源：http://dali.zhoulong.xyz/Article/details/gtdmetzgtm.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.birdmap.top/Article/details/gtuvoypwcb.html

[M05] 设置退出码
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfxavkveq.html

Py:   sys.exit(1)
来源：http://dali.zhoulong.xyz/Article/details/gtlzkrlcco.html

PHP:  exit(1);
来源：http://dali.hnxiangtu.top/Article/details/gtvpvtauhi.html

JS:   process.exit(1)
来源：http://dali.gotoacloud.top/Article/details/gttitvzizn.html

TS:   process.exit(1)
来源：http://dali.haohaochexian.top/Article/details/gtxfqlsavd.html

Java: System.exit(1)
来源：http://dali.xylfe.cn/Article/details/gtialyugyr.html

Go:   os.Exit(1)
来源：http://dali.fengsongda.top/Article/details/gtuhqfrwfn.html

Ruby: exit 1
来源：http://dali.9152youxi.cn/Article/details/gtbirhzjen.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.chenzaomai.com/Article/details/gtixdijlxd.html

[M06] 向标准错误输出
来源：http://dali.cashguo.top/Article/details/gtzukhltod.html

Py:   print("err", file=sys.stderr)
来源：http://dali.ehwqpu.com/Article/details/gtmresmtwq.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.jqgfzy.top/Article/details/gtjwdemawb.html

JS:   console.error("err")
来源：http://dali.dashuyun.cn/Article/details/gtwhlcmkdf.html

TS:   console.error("err")
来源：http://dali.gzhubu.top/Article/details/gtjobgujwv.html

Java: System.err.println("err")
来源：http://dali.jianghu66.top/Article/details/gtcyfdmmuh.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.pycfn.com/Article/details/gtnokdxzkk.html

Ruby: warn "err"
来源：http://dali.meibo888.top/Article/details/gtfukzptkv.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.9152youxi.cn/Article/details/gtczskfjns.html

[M07] 判断是否为主入口
来源：http://dali.chenlongwang.top/Article/details/gtbnbgjgib.html

Py:   if __name__ == "__main__":
来源：http://dali.yonumen.top/Article/details/gtlnsaclyf.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.ydzc1.top/Article/details/gtxqnvnubl.html

JS:   require.main === module
来源：http://dali.ppjwa.cn/Article/details/gtubwokkoq.html

TS:   require.main === module
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzylebhbj.html

Java: public static void main(String[] args)
来源：http://dali.gzhubu.top/Article/details/gtrhjjnqui.html

Go:   func main()
来源：http://dali.fzhhl.top/Article/details/gtboeutrlf.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpopshkzz.html

C#:   static void Main(string[] args)
来源：http://dali.zhengqikj.top/Article/details/gtnlzcmhuh.html

[M08] 获取系统与运行时信息
来源：http://dali.zhiwuduotai.top/Article/details/gtheaqarok.html

Py:   platform.system();  platform.python_version()
来源：http://dali.yj20258888.top/Article/details/gtiwlbabps.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.pycfn.com/Article/details/gtysffymkd.html

JS:   process.platform;  process.version
来源：http://dali.smart0.xyz/Article/details/gtonjffssa.html

TS:   process.platform;  process.version
来源：http://dali.wangshuangyany.cn/Article/details/gtrpekqfts.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.havefunace.top/Article/details/gtzryafkld.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.316326.xyz/Article/details/gtmeylpscy.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.shangyingyoupin.top/Article/details/gtnlaisagi.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.guannengcc.top/Article/details/gtslsvorpz.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtehsnolzs.html

N. 数据结构与算法
来源：http://dali.sxryk.cn/Article/details/gtihdboqat.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtkvkbeixf.html

[N01] 二分查找（有序数组）
来源：http://dali.feifeiyinyue.top/Article/details/gtwfqbknzb.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.9152youxi.cn/Article/details/gtudzwzjcf.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.gotoacloud.top/Article/details/gtjfixanlk.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.aibaodan.cn/Article/details/gtuwrheyyc.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.wangdashe.top/Article/details/gtzurjjtab.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.mhx1999.top/Article/details/gtzyyhsgoa.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.jianghu66.top/Article/details/gttjddjuha.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.cqqwz.cn/Article/details/gtygozslfj.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.jinqigfzy.top/Article/details/gtebbvcnlp.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.aizwys.cn/Article/details/gtgjpunjwp.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.smart0.xyz/Article/details/gtqgwwvtwh.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnetqykju.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.vqdsnc.cn/Article/details/gtqoisubbg.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.guannengcc.top/Article/details/gtsbwgrssn.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.ehwqpu.com/Article/details/gtzdmhzcnv.html

Go:   slices.Sort(arr)
来源：http://dali.snrcjt.cn/Article/details/gtsbwhdmky.html

Ruby: arr.sort
来源：http://dali.nwbrower.top/Article/details/gtvtcqkkrx.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.chenzaomai.com/Article/details/gtoadsqtud.html

[N03] 快速排序（分治示例）
来源：http://dali.cashguo.top/Article/details/gtylrbseoz.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.cucudq.cn/Article/details/gtginihjor.html

PHP:  // 递归实现，或用 usort
来源：http://dali.nanxuanxn.top/Article/details/gtsjqhvmlg.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yonumen.top/Article/details/gtdbhpamwi.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.gotoacloud.top/Article/details/gtiyunvame.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.yanxiufei.cn/Article/details/gtextmbzmr.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.fzhhl.top/Article/details/gtmjsmonqm.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.fengsongda.top/Article/details/gthslvmhkz.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.ybcxt.top/Article/details/gtbioxaiie.html

[N04] 斐波那契数列
来源：http://dali.guannengcc.top/Article/details/gtvyotrznt.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.hongshengwenyu.top/Article/details/gtcwzgtoyq.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.jinqigufen.top/Article/details/gtrntfchag.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.birdmap.top/Article/details/gteuiezrbp.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jqgfzy.top/Article/details/gtayudoags.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtormqlgot.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.yj20258888.top/Article/details/gtzokpoxkm.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.aizwys.cn/Article/details/gtrcyeqrxi.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.cucudq.cn/Article/details/gttvpkukbx.html

[N05] 最大公约数
来源：http://dali.xziqi.cn/Article/details/gtqbhxvuat.html

Py:   math.gcd(a, b)
来源：http://dali.meibo888.top/Article/details/gtwfxiozrw.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.shangyingyoupin.top/Article/details/gtokcehtfw.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zycfv.cn/Article/details/gtkylfbxcm.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yj202588.top/Article/details/gtilcywivs.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.shangyingyoupin.top/Article/details/gtyiqhbvvh.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.guannengcc.top/Article/details/gteznqfjnh.html

Ruby: a.gcd(b)
来源：http://dali.redwolf501.top/Article/details/gttlxsraiy.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.quarkkingdee.top/Article/details/gtotpthlqe.html

[N06] 判断回文字符串
来源：http://dali.zhiwuduotai.top/Article/details/gtqxxdtoel.html

Py:   s == s[::-1]
来源：http://dali.bjfxy.top/Article/details/gtxyapdavc.html

PHP:  $s === strrev($s);
来源：http://dali.snrcjt.cn/Article/details/gtiuqfzuem.html

JS:   s === [...s].reverse().join("")
来源：http://dali.yanxiufei.cn/Article/details/gtmbqpbflw.html

TS:   s === [...s].reverse().join("")
来源：http://dali.wangdashe.top/Article/details/gtedzmkpqv.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.chenzaomai.com/Article/details/gtdhrugirh.html

Go:   // 双指针从两端比较
来源：http://dali.yuxming.cn/Article/details/gtdrtwbwap.html

Ruby: s == s.reverse
来源：http://dali.bjfxy.top/Article/details/gtxdecfzfo.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.gaohongyu789.top/Article/details/gtyjvapmko.html

[N07] 两数之和（返回下标）
来源：http://dali.pycfn.com/Article/details/gtydfsyjss.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.yanxiufei.cn/Article/details/gtlqgsquzq.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.yongpay.top/Article/details/gtppzgebsj.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.guannengcc.top/Article/details/gtqfzgsdrc.html

TS:   // 手写 Map<string, number>
来源：http://dali.tanke756.top/Article/details/gtubwlbxdk.html

Java: // 手写 HashMap
来源：http://dali.pycfn.com/Article/details/gtrdlbqdpg.html

Go:   // 手写 map[int]int
来源：http://dali.fzhhl.top/Article/details/gtphjuhntb.html

Ruby: // 手写 Hash
来源：http://dali.jinghuilouyu.cn/Article/details/gtlvjzohlc.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.shzxlz.cn/Article/details/gtaxgplwbp.html

[N08] 生成全排列
来源：http://dali.jinghuilouyu.cn/Article/details/gtolqaliey.html

Py:   itertools.permutations(arr)
来源：http://dali.sufxvd.cn/Article/details/gtjpghcroz.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gtbqcyhraq.html

JS:   // 手写回溯递归
来源：http://dali.hammf.cn/Article/details/gtxqqlzpjd.html

TS:   // 手写回溯递归
来源：http://dali.havefunace.top/Article/details/gtalgazhzc.html

Java: // 手写回溯递归
来源：http://dali.nanxinkj.top/Article/details/gtwarvflxu.html

Go:   // 手写回溯递归
来源：http://dali.xuanzx.com/Article/details/gtwudwwixe.html

Ruby: arr.permutation.to_a
来源：http://dali.ppjwa.cn/Article/details/gtzirrtdye.html

C#:   // 手写回溯递归
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpwasgwia.html

[N09] 栈与队列
来源：http://dali.bjfxy.top/Article/details/gtxexlfvxx.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.ivvv.top/Article/details/gtvyanukyh.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.hywenlv.cn/Article/details/gtlknsfxkz.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.yongpay.top/Article/details/gtmsupwiku.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.wangshuangyany.cn/Article/details/gtxwqxpicc.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhiwuduotai.top/Article/details/gtvjaqmbmv.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.yuxming.cn/Article/details/gtcpwdjixu.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.snrcjt.cn/Article/details/gtcrfnsstg.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.yuxming.cn/Article/details/gtllkeennk.html

[N10] 链表节点定义
来源：http://dali.wangdashe.top/Article/details/gtzdfyfdzs.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.xziqi.cn/Article/details/gtnyvnobkm.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.nanxuanxn.top/Article/details/gtvpzcglqh.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.xylfe.cn/Article/details/gtdnovfyan.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.cdnleiting.top/Article/details/gtbchhuxyr.html

Java: class Node { int v; Node next; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqoxjhrjf.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.cucudq.cn/Article/details/gtiwrpgczn.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.9152youxi.cn/Article/details/gtrhsxjghg.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.yuxming.cn/Article/details/gtytalxnzm.html

[N11] 二叉树中序遍历
来源：http://dali.zhengqikj.top/Article/details/gtkiivvzla.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.316326.xyz/Article/details/gthopwrexa.html

PHP:  // 手写递归函数
来源：http://dali.cqqwz.cn/Article/details/gtxbocyeex.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.meibo888.top/Article/details/gttxhckjul.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.feifeiyinyue.top/Article/details/gthzznuyle.html

Java: // 手写递归
来源：http://dali.hfpthk.cn/Article/details/gtofvyxeyq.html

Go:   // 手写递归
来源：http://dali.daria6918.cn/Article/details/gtoaoqdzeb.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.cqqwz.cn/Article/details/gtnkdbgoxp.html

C#:   // 手写递归
来源：http://dali.hammf.cn/Article/details/gtsbmwduco.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.sxryk.cn/Article/details/gtkuthbinf.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.daria6918.cn/Article/details/gtjuhesxqu.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.tian-w.cn/Article/details/gtlawtyoda.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.tian-w.cn/Article/details/gtzblidrxe.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.gotoacloud.top/Article/details/gtnzlcoelv.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.cdnleiting.top/Article/details/gtavlncbna.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.quarkkingdee.top/Article/details/gtcodcflkz.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.yj202588.top/Article/details/gtousmrzqy.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.hfpthk.cn/Article/details/gtgkmpjkzz.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtwbcmfmxc.html

O. 并发与异步
来源：http://dali.xuanzx.com/Article/details/gtxwmsuwdc.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtnrrynbrb.html

[O01] 启动一个线程
来源：http://dali.hongshengwenyu.top/Article/details/gtinkdblom.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhixingplan.top/Article/details/gtspbmcgwb.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zycfv.cn/Article/details/gtgrgdwggb.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.pengpengdd.cyou/Article/details/gtspvvdfia.html

TS:   // 同 JS
来源：http://dali.yvedp.cn/Article/details/gthvmakixk.html

Java: new Thread(() -> f()).start()
来源：http://dali.wangdashe.top/Article/details/gtxbvntfok.html

Go:   go f()
来源：http://dali.zhoulong.xyz/Article/details/gtafvcydsc.html

Ruby: Thread.new { f }
来源：http://dali.yj20258888.top/Article/details/gtjevzpqlb.html

C#:   Task.Run(() => F());
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdcpfceuh.html

[O02] 使用线程池
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqjovcoeg.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.hnxiangtu.top/Article/details/gtzkzbwthz.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.kuanghao11.cn/Article/details/gtzkiqwmqj.html

JS:   // worker_threads 线程池
来源：http://dali.wangdashe.top/Article/details/gttjjhgsyl.html

TS:   // worker_threads 线程池
来源：http://dali.hfpthk.cn/Article/details/gtcgtgtrzo.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.aizwys.cn/Article/details/gtccpomoti.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.tianlin.xyz/Article/details/gtkkbmdjki.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.aibaodan.cn/Article/details/gtbipdparn.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.yvedp.cn/Article/details/gtbugcydrz.html

[O03] 加锁保护共享数据
来源：http://dali.zhengqikj.top/Article/details/gtsouydbpc.html

Py:   with lock: shared += 1
来源：http://dali.xuetiantiany.cn/Article/details/gtblupwcxe.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoxyujrex.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhiwuduotai.top/Article/details/gtbuhzegjx.html

TS:   // 同 JS
来源：http://dali.iojbl.cn/Article/details/gtpicvybna.html

Java: synchronized (this) { shared++; }
来源：http://dali.yuanzhike.top/Article/details/gtxqjmapdj.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.xylfe.cn/Article/details/gtivxbgwoi.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.gzhubu.top/Article/details/gtigrylyzh.html

C#:   lock (gate) { shared++; }
来源：http://dali.ydzc1.top/Article/details/gtvuzevrjb.html

[O04] 定义异步函数并等待
来源：http://dali.ivvv.top/Article/details/gtgquhdnff.html

Py:   async def f():⏎    await g()
来源：http://dali.hnqzz.top/Article/details/gtunifqcti.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.fzhhl.top/Article/details/gtgaweznkb.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gtofmduigu.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.dianchejie.cn/Article/details/gtullkxbdy.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gtefdfybsx.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.fengsongda.top/Article/details/gtwnnftbdz.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.jqgfzy.top/Article/details/gtvrzfzaoa.html

C#:   async Task F() { await G(); }
来源：http://dali.jqgufenzy.top/Article/details/gtctdkdywt.html

[O05] 并发执行并等待全部完成
来源：http://dali.yanxiufei.cn/Article/details/gtrphtjaab.html

Py:   asyncio.gather(*tasks)
来源：http://dali.vqdsnc.cn/Article/details/gtsaexpvdb.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.yj202588.top/Article/details/gtnhosgudq.html

JS:   await Promise.all(tasks)
来源：http://dali.cucudq.cn/Article/details/gtnssgkxrn.html

TS:   await Promise.all(tasks)
来源：http://dali.dashuyun.cn/Article/details/gtzbptrqou.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.jyoumei.cn/Article/details/gthmmamafq.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.kuanghao11.cn/Article/details/gtuldkdakg.html

Ruby: threads.map(&:join)
来源：http://dali.shangyingyoupin.top/Article/details/gtlszsxssz.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.nwbrower.top/Article/details/gtpvxsahfb.html

[O06] 使用进程池
来源：http://dali.sweek.top/Article/details/gtllipazcy.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.jlsjyb.cn/Article/details/gtbbsenhtc.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.pycfn.com/Article/details/gtirlefdio.html

JS:   // child_process / cluster 模块
来源：http://dali.yj20258.top/Article/details/gtaxrlfozs.html

TS:   // child_process / cluster 模块
来源：http://dali.sxryk.cn/Article/details/gthznyalhk.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.fzhhl.top/Article/details/gtykxbgwim.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.smart0.xyz/Article/details/gtuvejrcas.html

Ruby: // fork 块
来源：http://dali.jianghu66.top/Article/details/gtpfojbnht.html

C#:   Parallel.For
来源：http://dali.ywan-chungtsiang.top/Article/details/gtycknxxby.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtjxjuyizg.html

P. 常用工具函数
来源：http://dali.tian-w.cn/Article/details/gtfgriwetu.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtiwwrxsqg.html

[P01] 生成 UUID
来源：http://dali.birdmap.top/Article/details/gtemqqival.html

Py:   str(uuid.uuid4())
来源：http://dali.xuanzx.com/Article/details/gtrxahnxiy.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.hysaishi.cn/Article/details/gtjucvsooh.html

JS:   crypto.randomUUID()
来源：http://dali.zhiwuduotai.top/Article/details/gtvcdjubgt.html

TS:   crypto.randomUUID()
来源：http://dali.jyoumei.cn/Article/details/gtbqujzdkf.html

Java: UUID.randomUUID().toString()
来源：http://dali.meibo888.top/Article/details/gtwtxpitjg.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhixingplan.top/Article/details/gtkfqefzpi.html

Ruby: SecureRandom.uuid
来源：http://dali.havefunace.top/Article/details/gttjzzypxd.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.cheryme.top/Article/details/gtbklbdzfb.html

[P02] MD5 / SHA256 摘要
来源：http://dali.mhx1999.top/Article/details/gtzgxfneni.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.gogol.net.cn/Article/details/gtvwnwtvei.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.mhx1999.top/Article/details/gtjovlvuuo.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.snrcjt.cn/Article/details/gtqumlmtlk.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.sysykeji.top/Article/details/gtrkvuultq.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.0kj1m.cn/Article/details/gtgpdbpxtm.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.wangshuangyany.cn/Article/details/gtmtovuitz.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zdqjudy.top/Article/details/gtsdibpudr.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.meibo888.top/Article/details/gtreppfqxo.html

[P03] 生成短随机字符串
来源：http://dali.jinqigfzy.top/Article/details/gtotfmlnjf.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.hnxiangtu.top/Article/details/gttejywljf.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.shuidangran.top/Article/details/gtjvsqnqah.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yanxiufei.cn/Article/details/gtphmovkax.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.bjfxy.top/Article/details/gtmchptyyo.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.hywenlv.cn/Article/details/gtlatolfvb.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgrdswilo.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.feifeiyinyue.top/Article/details/gtidfxjdtp.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.vqdsnc.cn/Article/details/gtxzyggvdc.html

[P04] 求长度
来源：http://dali.zdqjudy.top/Article/details/gtmowjdscw.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.9152youxi.cn/Article/details/gtxakkdxxl.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yangfankeji.com/Article/details/gtkbxehxgv.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.chenjidiqi.icu/Article/details/gtdxhympec.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.sweek.top/Article/details/gtlwdcrweg.html

Java: list.size();  map.size();  s.length()
来源：http://dali.shuidangran.top/Article/details/gtfxiauptk.html

Go:   len(arr);  len(m)
来源：http://dali.meibo888.top/Article/details/gtnwbkimgw.html

Ruby: x.length;  x.size
来源：http://dali.havefunace.top/Article/details/gtcfpdtwtc.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.ppjwa.cn/Article/details/gtlhthftnf.html

[P05] 判断两个对象内容是否相等
来源：http://dali.pengpengdd.cyou/Article/details/gtuyvjijks.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.hnxiangtu.top/Article/details/gtoirnehwm.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.gotoacloud.top/Article/details/gtlztcbjyx.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.iojbl.cn/Article/details/gtkwpkrlcm.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.daxiang520.top/Article/details/gtahprgspu.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.yonumen.top/Article/details/gtnasixcog.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.wangshuangyany.cn/Article/details/gtjzabnxlm.html

Ruby: a == b
来源：http://dali.yvedp.cn/Article/details/gtfhgvberu.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.nanxuanxn.top/Article/details/gtkxdackbz.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.chenlongwang.top/Article/details/gtneplnojy.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.tianlin.xyz/Article/details/gttaijvedo.html

PHP:  if (empty($x)) {}
来源：http://dali.pycfn.com/Article/details/gtwhkkcwaw.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.meibo888.top/Article/details/gtirzwxpzt.html

TS:   if (x == null) {}
来源：http://dali.hysaishi.cn/Article/details/gtabpfmfdi.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.chenlongwang.top/Article/details/gtpkloaxla.html

Go:   if x == nil {}
来源：http://dali.yvedp.cn/Article/details/gtcodmxrgi.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.wangshuangyany.cn/Article/details/gtkxtkwyjm.html

C#:   if (x is null) {}
来源：http://dali.ppjwa.cn/Article/details/gtufdpiyvm.html

[P07] 防抖与节流
来源：http://dali.pycfn.com/Article/details/gtbrqepjva.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.cashguo.top/Article/details/gthaepuufp.html

PHP:  // 手写时间戳比较
来源：http://dali.yanxiufei.cn/Article/details/gtbeycvgkr.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.ehwqpu.com/Article/details/gtrfwmespb.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.shuidangran.top/Article/details/gtcybpkyii.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.cheryme.top/Article/details/gtvdmvtohj.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.pengpengdd.cyou/Article/details/gtwnryvvkw.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.bjfxy.top/Article/details/gtpyxkhujd.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.daxiang520.top/Article/details/gtgujimspj.html

[P08] 处理浮点精度问题
来源：http://dali.yanxiufei.cn/Article/details/gtxcffjxvj.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.havefunace.top/Article/details/gtbhrfedxm.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.cheryme.top/Article/details/gtitnjtlux.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.yonumen.top/Article/details/gtvsvrqdqs.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.hongshengwenyu.top/Article/details/gtaxnnwwpy.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.guannengcc.top/Article/details/gtbiuhhbpm.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zycfv.cn/Article/details/gtxxrkobyl.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.shanyushiyangtech.top/Article/details/gtmgeaohhh.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsfklzndk.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtxtunsqfm.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.jiagoushi.top/Article/details/gtriygbalm.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gttgfckxhv.html

[Q01] 创建表
来源：http://dali.chenjidiqi.icu/Article/details/gtixijgwpg.html

CREATE TABLE users (
来源：http://dali.fengsongda.top/Article/details/gtvhprgqer.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.c1oappe.top/Article/details/gtghuplhby.html

name VARCHAR(50) NOT NULL,
来源：http://dali.nanxinkj.top/Article/details/gtbstcrwjy.html

email VARCHAR(100) UNIQUE,
来源：http://dali.redwolf501.top/Article/details/gtxntlzbgu.html


<!-- 参考信息 -->