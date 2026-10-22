代发 wailian999

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.xuanzx.com/Article/details/gtuvgntizs.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.wangshuangyany.cn/Article/details/gthisxyopq.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.tanke756.top/Article/details/gtzmvuilyi.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gtbafjxefl.html

[M04] 获取当前工作目录
来源：http://dali.ybcxt.top/Article/details/gteiliqjbo.html

Py:   os.getcwd()
来源：http://dali.wangdashe.top/Article/details/gthaudfywu.html

PHP:  getcwd();
来源：http://dali.jqgufenzy.top/Article/details/gtomkkgebf.html

JS:   process.cwd()
来源：http://dali.yangfankeji.com/Article/details/gtnbygbwsp.html

TS:   process.cwd()
来源：http://dali.9152youxi.cn/Article/details/gtzybblusj.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.gaohongyu789.top/Article/details/gtigimewyu.html

Go:   os.Getwd()
来源：http://dali.xylfe.cn/Article/details/gtuaygnmdy.html

Ruby: Dir.pwd
来源：http://dali.sweek.top/Article/details/gtmrhplmqa.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.guannengcc.top/Article/details/gttqqyktgp.html

[M05] 设置退出码
来源：http://dali.cheryme.top/Article/details/gtolxhihzy.html

Py:   sys.exit(1)
来源：http://dali.havefunace.top/Article/details/gtosnuncac.html

PHP:  exit(1);
来源：http://dali.dianchejie.cn/Article/details/gtnpjntwun.html

JS:   process.exit(1)
来源：http://dali.tian-w.cn/Article/details/gtodxdsdiv.html

TS:   process.exit(1)
来源：http://dali.yuanzhike.top/Article/details/gttheyocqd.html

Java: System.exit(1)
来源：http://dali.xziqi.cn/Article/details/gtgvfpdume.html

Go:   os.Exit(1)
来源：http://dali.gogol.net.cn/Article/details/gtvhzldjmc.html

Ruby: exit 1
来源：http://dali.tian-w.cn/Article/details/gtyugtvrpg.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.andypj.xyz/Article/details/gtokldxknq.html

[M06] 向标准错误输出
来源：http://dali.xuetiantiany.cn/Article/details/gtwddalaxx.html

Py:   print("err", file=sys.stderr)
来源：http://dali.shuidangran.top/Article/details/gtjfzpdxyb.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.pengpengdd.cyou/Article/details/gtedajkuyq.html

JS:   console.error("err")
来源：http://dali.xylfe.cn/Article/details/gtqfnthrfc.html

TS:   console.error("err")
来源：http://dali.iojbl.cn/Article/details/gtmqozchlg.html

Java: System.err.println("err")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvqgpcqnl.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.smart0.xyz/Article/details/gtowqreqga.html

Ruby: warn "err"
来源：http://dali.jinqigufen.top/Article/details/gtcodltvxr.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.havefunace.top/Article/details/gtrzoqiwik.html

[M07] 判断是否为主入口
来源：http://dali.ydzc1.top/Article/details/gtdlipflel.html

Py:   if __name__ == "__main__":
来源：http://dali.fzhhl.top/Article/details/gtxogtnxgw.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.ehwqpu.com/Article/details/gtvkpnczcu.html

JS:   require.main === module
来源：http://dali.jianghu66.top/Article/details/gtfqlonwxz.html

TS:   require.main === module
来源：http://dali.guowangkeji.top/Article/details/gtodagknxc.html

Java: public static void main(String[] args)
来源：http://dali.jqgufenzy.top/Article/details/gttwousxdo.html

Go:   func main()
来源：http://dali.feifeiyinyue.top/Article/details/gtvyeiiwbm.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.bjfxy.top/Article/details/gtqpvmwgzp.html

C#:   static void Main(string[] args)
来源：http://dali.jqgufenzy.top/Article/details/gtgmlfisfu.html

[M08] 获取系统与运行时信息
来源：http://dali.cashguo.top/Article/details/gtoxmnxyei.html

Py:   platform.system();  platform.python_version()
来源：http://dali.redwolf501.top/Article/details/gtahwkndtz.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.yangfankeji.com/Article/details/gtrajsgedz.html

JS:   process.platform;  process.version
来源：http://dali.jinghuilouyu.cn/Article/details/gtrpsvikfb.html

TS:   process.platform;  process.version
来源：http://dali.yuxming.cn/Article/details/gtwdhvkmbm.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.yuanzhike.top/Article/details/gtamavszxn.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.haohaochexian.top/Article/details/gttimxiqwy.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.ybcxt.top/Article/details/gtahgqgood.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.aibaodan.cn/Article/details/gtgnsegwgu.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gthihiagro.html

N. 数据结构与算法
来源：http://dali.shangyingyoupin.top/Article/details/gtuqhsamzf.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gthvyssqsc.html

[N01] 二分查找（有序数组）
来源：http://dali.ivvv.top/Article/details/gtsphznpey.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.ppjwa.cn/Article/details/gtkbkasqrz.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.shanyushiyangtech.top/Article/details/gtfawhmkmx.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.gaohongyu789.top/Article/details/gtedxevoas.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnzuuqpbd.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.tianlin.xyz/Article/details/gtgtyayzra.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.nanxuanxn.top/Article/details/gtyareeezn.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.iojbl.cn/Article/details/gtjzfdhlze.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhixingplan.top/Article/details/gtsyiyklto.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.guannengcc.top/Article/details/gtlweptyhe.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yuxming.cn/Article/details/gtamcphbby.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.yvedp.cn/Article/details/gtnqxaeueq.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.svipenyu.cn/Article/details/gtjxuqvrxv.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.bjfxy.top/Article/details/gtqimtecya.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.hfpthk.cn/Article/details/gtckrqmind.html

Go:   slices.Sort(arr)
来源：http://dali.xuanzx.com/Article/details/gtbemclznu.html

Ruby: arr.sort
来源：http://dali.yvedp.cn/Article/details/gtosapmgdk.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.xylfe.cn/Article/details/gtowwfrlks.html

[N03] 快速排序（分治示例）
来源：http://dali.smart0.xyz/Article/details/gtgelbipum.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.gzhubu.top/Article/details/gtjkltqkab.html

PHP:  // 递归实现，或用 usort
来源：http://dali.yj20258888.top/Article/details/gtgdeibyoz.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.bjfxy.top/Article/details/gtbzanuszo.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.ppjwa.cn/Article/details/gttfkncgue.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.xuetiantiany.cn/Article/details/gtjarnshdf.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.shuidangran.top/Article/details/gtwamadfwk.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zycfv.cn/Article/details/gtxfcnphrg.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.yongpay.top/Article/details/gtbxtpegpa.html

[N04] 斐波那契数列
来源：http://dali.sufxvd.cn/Article/details/gtmvpxgzpn.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhixingplan.top/Article/details/gtwyqwzejb.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.hysaishi.cn/Article/details/gtcgfnmawi.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.ppjwa.cn/Article/details/gthqxqreoc.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.svipenyu.cn/Article/details/gtqteqpups.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.9152youxi.cn/Article/details/gtrndkcjot.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.xuanzx.com/Article/details/gtqhqkimpu.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zdqjudy.top/Article/details/gtloxkvpwp.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.cheryme.top/Article/details/gtqlsmfmsw.html

[N05] 最大公约数
来源：http://dali.pycfn.com/Article/details/gtjiwlnybb.html

Py:   math.gcd(a, b)
来源：http://dali.hfpthk.cn/Article/details/gtoqueltvn.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.tianlin.xyz/Article/details/gtauxinuxr.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.gaohongyu789.top/Article/details/gtolcmcxaa.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.nanxinkj.top/Article/details/gtamoqjzqt.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.tian-w.cn/Article/details/gtwlsyjipi.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.jinghuilouyu.cn/Article/details/gtnfqkzosk.html

Ruby: a.gcd(b)
来源：http://dali.yanxiufei.cn/Article/details/gtmnwieeuz.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.hysaishi.cn/Article/details/gtxrfqafdv.html

[N06] 判断回文字符串
来源：http://dali.jqgufenzy.top/Article/details/gtqsprxrkl.html

Py:   s == s[::-1]
来源：http://dali.yj20258888.top/Article/details/gtanapdyip.html

PHP:  $s === strrev($s);
来源：http://dali.xuanzx.com/Article/details/gtijqcycfu.html

JS:   s === [...s].reverse().join("")
来源：http://dali.birdmap.top/Article/details/gtczksjpfe.html

TS:   s === [...s].reverse().join("")
来源：http://dali.yuanzhike.top/Article/details/gtaxlfggah.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.haohaochexian.top/Article/details/gtecvxsngj.html

Go:   // 双指针从两端比较
来源：http://dali.jianghu66.top/Article/details/gtzmwccacp.html

Ruby: s == s.reverse
来源：http://dali.chenzaomai.com/Article/details/gtgcvqcdgo.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.xylfe.cn/Article/details/gttfpkpgrd.html

[N07] 两数之和（返回下标）
来源：http://dali.hnxiangtu.top/Article/details/gtbwikxxmr.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.shangyingyoupin.top/Article/details/gtwksrxmhg.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.smart0.xyz/Article/details/gtuxpbpzgp.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.wangshuangyany.cn/Article/details/gtvybusttd.html

TS:   // 手写 Map<string, number>
来源：http://dali.316326.xyz/Article/details/gtxrnzndlh.html

Java: // 手写 HashMap
来源：http://dali.zycfv.cn/Article/details/gtuixialjl.html

Go:   // 手写 map[int]int
来源：http://dali.zhengqikj.top/Article/details/gteklzmzks.html

Ruby: // 手写 Hash
来源：http://dali.xinyue.icu/Article/details/gtfddapzar.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.xuetiantiany.cn/Article/details/gtakoaasmh.html

[N08] 生成全排列
来源：http://dali.jqgfzy.top/Article/details/gtotxqbjxb.html

Py:   itertools.permutations(arr)
来源：http://dali.vqdsnc.cn/Article/details/gtiifipjpr.html

PHP:  // 手写递归交换
来源：http://dali.nanxinkj.top/Article/details/gtppoidzje.html

JS:   // 手写回溯递归
来源：http://dali.nwbrower.top/Article/details/gtcfykoszj.html

TS:   // 手写回溯递归
来源：http://dali.yanxiufei.cn/Article/details/gtgyrgjbhg.html

Java: // 手写回溯递归
来源：http://dali.sweek.top/Article/details/gtvrkwhjrj.html

Go:   // 手写回溯递归
来源：http://dali.zhiwuduotai.top/Article/details/gtlhpdmuxx.html

Ruby: arr.permutation.to_a
来源：http://dali.wangdashe.top/Article/details/gttpvemrjd.html

C#:   // 手写回溯递归
来源：http://dali.yj202588.top/Article/details/gtcqlkubtp.html

[N09] 栈与队列
来源：http://dali.chenlongwang.top/Article/details/gtopkwhnjx.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.c1oappe.top/Article/details/gtthgxhegs.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.sweek.top/Article/details/gtazfljqpw.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.xuanzx.com/Article/details/gtplosdrkx.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.mhx1999.top/Article/details/gtchadtesx.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhongyouzk.top/Article/details/gtqmerghei.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.aibaodan.cn/Article/details/gtrsgyhwql.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.ybcxt.top/Article/details/gtehgdovtb.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.chenzaomai.com/Article/details/gtsbjcymjq.html

[N10] 链表节点定义
来源：http://dali.zycfv.cn/Article/details/gthxhcjuvw.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.daxiang520.top/Article/details/gtrespmgvn.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.cucudq.cn/Article/details/gtshnbeppq.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.sufxvd.cn/Article/details/gtnqmdoocz.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gtohxerpss.html

Java: class Node { int v; Node next; }
来源：http://dali.hongshengwenyu.top/Article/details/gtmwtnkfab.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.sxryk.cn/Article/details/gtxnwebsxn.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.0kj1m.cn/Article/details/gtebwytchh.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.tanke756.top/Article/details/gtdaobhzyv.html

[N11] 二叉树中序遍历
来源：http://dali.xuetiantiany.cn/Article/details/gtfnixwjxa.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.yanxiufei.cn/Article/details/gtdxzhtzom.html

PHP:  // 手写递归函数
来源：http://dali.jlsjyb.cn/Article/details/gtmqjmhvhd.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.pengpengdd.cyou/Article/details/gtdwxatfml.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.sxryk.cn/Article/details/gtwqqexcfa.html

Java: // 手写递归
来源：http://dali.xylfe.cn/Article/details/gtipxxwiwx.html

Go:   // 手写递归
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxzpjvdoj.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.sxryk.cn/Article/details/gthlmlwvih.html

C#:   // 手写递归
来源：http://dali.sxryk.cn/Article/details/gtsqzqzrma.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.yuanzhike.top/Article/details/gtlipabdwt.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.meibo888.top/Article/details/gtxplnuowi.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.feifeiyinyue.top/Article/details/gtmidvsfig.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.hywenlv.cn/Article/details/gtbrxxbxmj.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhiwuduotai.top/Article/details/gtvcwmuydf.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.aizwys.cn/Article/details/gtxzysndlh.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.jqgufenzy.top/Article/details/gtozjcjgjv.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.sxryk.cn/Article/details/gtcakgkfns.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.chenlongwang.top/Article/details/gtoiyvndae.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtayhmyorn.html

O. 并发与异步
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpcgkbalo.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtepdhxgwd.html

[O01] 启动一个线程
来源：http://dali.zdqjudy.top/Article/details/gtlmeldkze.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.wangdashe.top/Article/details/gticpciukj.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.haohaochexian.top/Article/details/gtplfdmgjd.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.shangyingyoupin.top/Article/details/gtvbkvamte.html

TS:   // 同 JS
来源：http://dali.jinqigfzy.top/Article/details/gtianljnrr.html

Java: new Thread(() -> f()).start()
来源：http://dali.hfpthk.cn/Article/details/gtlxvtrcks.html

Go:   go f()
来源：http://dali.yueranfly.top/Article/details/gtjkxnifmf.html

Ruby: Thread.new { f }
来源：http://dali.jianghu66.top/Article/details/gteqowdfmm.html

C#:   Task.Run(() => F());
来源：http://dali.yj20258888.top/Article/details/gtxqimqadn.html

[O02] 使用线程池
来源：http://dali.yongpay.top/Article/details/gtnnbolpqv.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.aibaodan.cn/Article/details/gtocothayw.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.ydzc1.top/Article/details/gtyjvncqmb.html

JS:   // worker_threads 线程池
来源：http://dali.yj20258.top/Article/details/gtrlcoxvgy.html

TS:   // worker_threads 线程池
来源：http://dali.jinqigufen.top/Article/details/gtsraknqhw.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.ybcxt.top/Article/details/gtgquaxmtb.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.yj202588.top/Article/details/gtscovfmwz.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.yanxiufei.cn/Article/details/gturukobtj.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zdqjudy.top/Article/details/gtschexfju.html

[O03] 加锁保护共享数据
来源：http://dali.yj20258888.top/Article/details/gtkmgavwrk.html

Py:   with lock: shared += 1
来源：http://dali.jianghu66.top/Article/details/gtedpeutzp.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.shzxlz.cn/Article/details/gtiiztjxyy.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.guannengcc.top/Article/details/gtvdjgpgyx.html

TS:   // 同 JS
来源：http://dali.cheryme.top/Article/details/gtzvdljsry.html

Java: synchronized (this) { shared++; }
来源：http://dali.sufxvd.cn/Article/details/gtqommgtoh.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.cucudq.cn/Article/details/gtffqzfnwr.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.ydzc1.top/Article/details/gthkhxgwxw.html

C#:   lock (gate) { shared++; }
来源：http://dali.yvedp.cn/Article/details/gttsoqlenj.html

[O04] 定义异步函数并等待
来源：http://dali.xziqi.cn/Article/details/gtfmtzarsv.html

Py:   async def f():⏎    await g()
来源：http://dali.c1oappe.top/Article/details/gtlqdjcjvr.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.0kj1m.cn/Article/details/gtkomspmww.html

JS:   async function f() { await g(); }
来源：http://dali.chenzaomai.com/Article/details/gtfanepzjf.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.snrcjt.cn/Article/details/gtbjecitgm.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.gogol.net.cn/Article/details/gtlmsopdwm.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.guowangkeji.top/Article/details/gtotrbcbik.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.daxiang520.top/Article/details/gtjhuacrhi.html

C#:   async Task F() { await G(); }
来源：http://dali.cashguo.top/Article/details/gtebctqlyh.html

[O05] 并发执行并等待全部完成
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpzwesxsp.html

Py:   asyncio.gather(*tasks)
来源：http://dali.aibaodan.cn/Article/details/gtlptvthiz.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.nanxinkj.top/Article/details/gtmejtvvla.html

JS:   await Promise.all(tasks)
来源：http://dali.hnxiangtu.top/Article/details/gtdbmmxnpw.html

TS:   await Promise.all(tasks)
来源：http://dali.ybcxt.top/Article/details/gtnzkhnjnd.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.gotoacloud.top/Article/details/gtodhpyvnp.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.yanxiufei.cn/Article/details/gthwvpujrv.html

Ruby: threads.map(&:join)
来源：http://dali.nwbrower.top/Article/details/gtnergujbz.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.feifeiyinyue.top/Article/details/gtnzrvcquz.html

[O06] 使用进程池
来源：http://dali.zhoulong.xyz/Article/details/gteiuoowio.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.smart0.xyz/Article/details/gtrxtozwoh.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.dashuyun.cn/Article/details/gtybasdhon.html

JS:   // child_process / cluster 模块
来源：http://dali.chenlongwang.top/Article/details/gtztasfivw.html

TS:   // child_process / cluster 模块
来源：http://dali.bjfxy.top/Article/details/gtenjygdvw.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.hywenlv.cn/Article/details/gtgijkohsh.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.yuanzhike.top/Article/details/gtasuelhzx.html

Ruby: // fork 块
来源：http://dali.jiagoushi.top/Article/details/gtsufgfmki.html

C#:   Parallel.For
来源：http://dali.shzxlz.cn/Article/details/gtkxeodbnp.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtiwjsnbhc.html

P. 常用工具函数
来源：http://dali.xylfe.cn/Article/details/gtrccvwjzp.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtvlcmdkzo.html

[P01] 生成 UUID
来源：http://dali.sufxvd.cn/Article/details/gtbsksplkq.html

Py:   str(uuid.uuid4())
来源：http://dali.jinghuilouyu.cn/Article/details/gtuuzycyow.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.hywenlv.cn/Article/details/gtvyhykgnp.html

JS:   crypto.randomUUID()
来源：http://dali.sysykeji.top/Article/details/gtxuxizhjd.html

TS:   crypto.randomUUID()
来源：http://dali.fengsongda.top/Article/details/gttbnfchtx.html

Java: UUID.randomUUID().toString()
来源：http://dali.andypj.xyz/Article/details/gtbjsjowre.html

Go:   // 用 github.com/google/uuid
来源：http://dali.chenzaomai.com/Article/details/gtnqyhkhyr.html

Ruby: SecureRandom.uuid
来源：http://dali.guowangkeji.top/Article/details/gthvsbvsem.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.andypj.xyz/Article/details/gtenyixonb.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhixingplan.top/Article/details/gtcgrcwpvz.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.chenjidiqi.icu/Article/details/gtumldcmvu.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.xziqi.cn/Article/details/gtzjughhmr.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.ehwqpu.com/Article/details/gtklxmbnfe.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.nwbrower.top/Article/details/gtozmefwth.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.hnqzz.top/Article/details/gteqhjzpvq.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.iojbl.cn/Article/details/gteuskvfqh.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.yonumen.top/Article/details/gthkvoblvk.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.jiagoushi.top/Article/details/gtjirogcux.html

[P03] 生成短随机字符串
来源：http://dali.vqdsnc.cn/Article/details/gtlkachlvf.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.gogol.net.cn/Article/details/gtiitwfjak.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.dashuyun.cn/Article/details/gtcxesvaxk.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.xinyue.icu/Article/details/gtpbqxhqsb.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.aibaodan.cn/Article/details/gtkhmxvwoh.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhoulong.xyz/Article/details/gtyimlcbxw.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.yongpay.top/Article/details/gtxvmofnyh.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhiwuduotai.top/Article/details/gtmgbeoivj.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.ppjwa.cn/Article/details/gtkfreqleo.html

[P04] 求长度
来源：http://dali.yanxiufei.cn/Article/details/gttttvjdvq.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.cashguo.top/Article/details/gtbcbsunwx.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhengqikj.top/Article/details/gthkfbzfrt.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.ydzc1.top/Article/details/gtomonyawa.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.tanke756.top/Article/details/gtpcmggtwb.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtznrbcrbf.html

Go:   len(arr);  len(m)
来源：http://dali.c1oappe.top/Article/details/gtvqfvpxji.html

Ruby: x.length;  x.size
来源：http://dali.jyoumei.cn/Article/details/gtjnnxmzsi.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.jinqigufen.top/Article/details/gtbnibyyab.html

[P05] 判断两个对象内容是否相等
来源：http://dali.yongpay.top/Article/details/gtwoygrzgr.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.hammf.cn/Article/details/gtnlfkmjer.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.meibo888.top/Article/details/gtftlyhuhj.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdagppvpq.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.jiagoushi.top/Article/details/gtntvztvep.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.guannengcc.top/Article/details/gtwjcwyhwx.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.aibaodan.cn/Article/details/gtytrfntqj.html

Ruby: a == b
来源：http://dali.jiagoushi.top/Article/details/gtsvnyiwse.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.sweek.top/Article/details/gtkmtpswxm.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zdqjudy.top/Article/details/gtgezxunqz.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zdqjudy.top/Article/details/gtsdyqrvpr.html

PHP:  if (empty($x)) {}
来源：http://dali.haohaochexian.top/Article/details/gtkwsakbxl.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.shuidangran.top/Article/details/gtotajxgay.html

TS:   if (x == null) {}
来源：http://dali.316326.xyz/Article/details/gtxjeaxwtm.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.sysykeji.top/Article/details/gtexjveedb.html

Go:   if x == nil {}
来源：http://dali.jqgufenzy.top/Article/details/gtwsljivdc.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.wangdashe.top/Article/details/gtmoepigrt.html

C#:   if (x is null) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsfxlqfxc.html

[P07] 防抖与节流
来源：http://dali.snrcjt.cn/Article/details/gtzrdutubb.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.kuanghao11.cn/Article/details/gtlxsijcci.html

PHP:  // 手写时间戳比较
来源：http://dali.kuanghao11.cn/Article/details/gtxpdyxipa.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.316326.xyz/Article/details/gtnkskghik.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgsifxsql.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.mhx1999.top/Article/details/gtbxqbfxeh.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.iojbl.cn/Article/details/gtijzrzgzu.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.smart0.xyz/Article/details/gtjvtfltfd.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.shanyushiyangkeji.top/Article/details/gthcahpdvc.html

[P08] 处理浮点精度问题
来源：http://dali.cucudq.cn/Article/details/gtbbrkslfo.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.chenlongwang.top/Article/details/gtclufhjqx.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.xziqi.cn/Article/details/gtnjywkidt.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.yangfankeji.com/Article/details/gtsgzcoocs.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.jinghuilouyu.cn/Article/details/gtwswitdtw.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.yongpay.top/Article/details/gtufkvzagd.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.jinghuilouyu.cn/Article/details/gtuxuoyyfg.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.yonumen.top/Article/details/gtenznhaxr.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.sxryk.cn/Article/details/gtjzpsowdv.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtfumhvpul.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.pycfn.com/Article/details/gtuhmnhpcb.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtocqiwzuo.html

[Q01] 创建表
来源：http://dali.dianchejie.cn/Article/details/gtowcxalua.html

CREATE TABLE users (
来源：http://dali.zhongyouzk.top/Article/details/gttkubfrli.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.guowangkeji.top/Article/details/gtmeybfoik.html

name VARCHAR(50) NOT NULL,
来源：http://dali.dashuyun.cn/Article/details/gtzdhsboll.html

email VARCHAR(100) UNIQUE,
来源：http://dali.cqqwz.cn/Article/details/gthivndpyf.html


<!-- 参考信息 -->