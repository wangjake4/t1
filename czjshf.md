代发 wailian999

TS:   process.cwd()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tcfhzezg.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.jinqigufen.top/Article/details/gt2mqtnengu.html

Go:   os.Getwd()
来源：http://dali.daria6918.cn/Article/details/gt2gpouccrm.html

Ruby: Dir.pwd
来源：http://dali.sufxvd.cn/Article/details/gt2qgmjcpsf.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.gogol.net.cn/Article/details/gt2fpviroet.html

[M05] 设置退出码
来源：http://dali.hfpthk.cn/Article/details/gt2zsqxlioj.html

Py:   sys.exit(1)
来源：http://dali.hnqzz.top/Article/details/gt2uizajebn.html

PHP:  exit(1);
来源：http://dali.gogol.net.cn/Article/details/gt2ubmswpnj.html

JS:   process.exit(1)
来源：http://dali.cheryme.top/Article/details/gt2tkjowzmi.html

TS:   process.exit(1)
来源：http://dali.meibo888.top/Article/details/gt2indhkcpz.html

Java: System.exit(1)
来源：http://dali.yueranfly.top/Article/details/gt2bnbjljcd.html

Go:   os.Exit(1)
来源：http://dali.jianghu66.top/Article/details/gt2vxmkisxn.html

Ruby: exit 1
来源：http://dali.nanxuanxn.top/Article/details/gt2suuepnkv.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.jlsjyb.cn/Article/details/gt2rukupqea.html

[M06] 向标准错误输出
来源：http://dali.yuxming.cn/Article/details/gt2fwyzkidg.html

Py:   print("err", file=sys.stderr)
来源：http://dali.tianlin.xyz/Article/details/gt2vgmjlqbx.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.xylfe.cn/Article/details/gt2thplwrav.html

JS:   console.error("err")
来源：http://dali.zycfv.cn/Article/details/gt2saxgmuge.html

TS:   console.error("err")
来源：http://dali.zycfv.cn/Article/details/gt2kauicctl.html

Java: System.err.println("err")
来源：http://dali.zdqjudy.top/Article/details/gt2jpmcpjpf.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.sxryk.cn/Article/details/gt2dzubfckx.html

Ruby: warn "err"
来源：http://dali.andypj.xyz/Article/details/gt2xyovatrc.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.c1oappe.top/Article/details/gt2qwxbkknk.html

[M07] 判断是否为主入口
来源：http://dali.redwolf501.top/Article/details/gt2zyyseuya.html

Py:   if __name__ == "__main__":
来源：http://dali.daxiang520.top/Article/details/gt2wefxnmdv.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.tanke756.top/Article/details/gt2myroxypd.html

JS:   require.main === module
来源：http://dali.hnxiangtu.top/Article/details/gt2ujjfajms.html

TS:   require.main === module
来源：http://dali.yj20258888.top/Article/details/gt2weqaptyi.html

Java: public static void main(String[] args)
来源：http://dali.c1oappe.top/Article/details/gt2ksswfvep.html

Go:   func main()
来源：http://dali.fzhhl.top/Article/details/gt2qweopnfd.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cbnoaxjs.html

C#:   static void Main(string[] args)
来源：http://dali.zhiwuduotai.top/Article/details/gt2hgenxblk.html

[M08] 获取系统与运行时信息
来源：http://dali.hnqzz.top/Article/details/gt2njkrscfm.html

Py:   platform.system();  platform.python_version()
来源：http://dali.yj202588.top/Article/details/gt2ugxjilqa.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.c1oappe.top/Article/details/gt2hxqtzvjf.html

JS:   process.platform;  process.version
来源：http://dali.kuanghao11.cn/Article/details/gt2omxuoopa.html

TS:   process.platform;  process.version
来源：http://dali.fengsongda.top/Article/details/gt2fzzdkwcx.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.vqdsnc.cn/Article/details/gt2xlvozsmr.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.hywenlv.cn/Article/details/gt2kkmqpsiw.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.0kj1m.cn/Article/details/gt2kptosswc.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.jinqigufen.top/Article/details/gt2cpqvqlea.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gt2dpwyktam.html

N. 数据结构与算法
来源：http://dali.jiagoushi.top/Article/details/gt2akuffeih.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2lekvllnz.html

[N01] 二分查找（有序数组）
来源：http://dali.cucudq.cn/Article/details/gt2zbrbnkce.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tsagwcwd.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2sfkwlbuk.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yuanzhike.top/Article/details/gt2sorpryfs.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.kuanghao11.cn/Article/details/gt2qaewsmhw.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.fengsongda.top/Article/details/gt2vxshowux.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.vqdsnc.cn/Article/details/gt2gqrtbftt.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.c1oappe.top/Article/details/gt2gjgigcdu.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.vqdsnc.cn/Article/details/gt2kxnnrghm.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.cucudq.cn/Article/details/gt2qrcxjyxw.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kasepomh.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.aizwys.cn/Article/details/gt2prnvnvlb.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.cashguo.top/Article/details/gt2ylwwcwzj.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jiagoushi.top/Article/details/gt2ycurzxpq.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.ivvv.top/Article/details/gt2zdemsuio.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2wafqmxmi.html

Ruby: arr.sort
来源：http://dali.nwbrower.top/Article/details/gt2zhzkzjxb.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.iojbl.cn/Article/details/gt2bjmdalhb.html

[N03] 快速排序（分治示例）
来源：http://dali.pycfn.com/Article/details/gt2bvsoysuy.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.fengsongda.top/Article/details/gt2pobvltts.html

PHP:  // 递归实现，或用 usort
来源：http://dali.jinghuilouyu.cn/Article/details/gt2glfpuuzf.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yongpay.top/Article/details/gt2irjgsmrx.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.sufxvd.cn/Article/details/gt2pdqixujv.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.xuanzx.com/Article/details/gt2ibmoomma.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.xziqi.cn/Article/details/gt2bqdciojf.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.havefunace.top/Article/details/gt2prsvscue.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.andypj.xyz/Article/details/gt2iuhpkiwf.html

[N04] 斐波那契数列
来源：http://dali.chenjidiqi.icu/Article/details/gt2hmlolcaq.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yybvzxiw.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.cdnleiting.top/Article/details/gt2tqoujxro.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.nanxuanxn.top/Article/details/gt2fhoqtkpt.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jianghu66.top/Article/details/gt2yheycbts.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.jinqigufen.top/Article/details/gt2qcwrihhx.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.meibo888.top/Article/details/gt2skukocnx.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.xuanzx.com/Article/details/gt2ikhforqu.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.svipenyu.cn/Article/details/gt2nznxnudz.html

[N05] 最大公约数
来源：http://dali.xuetiantiany.cn/Article/details/gt2uyzxdkhm.html

Py:   math.gcd(a, b)
来源：http://dali.zhengqikj.top/Article/details/gt2nnplpbji.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.gogol.net.cn/Article/details/gt2jyuydsbu.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yanxiufei.cn/Article/details/gt2bcpibfno.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2rkxksqnx.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhengqikj.top/Article/details/gt2zmxnazzu.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.hnqzz.top/Article/details/gt2ixcddrhq.html

Ruby: a.gcd(b)
来源：http://dali.guannengcc.top/Article/details/gt2kynxqlzu.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.guannengcc.top/Article/details/gt2tvsulphq.html

[N06] 判断回文字符串
来源：http://dali.redwolf501.top/Article/details/gt2xmqvyqtq.html

Py:   s == s[::-1]
来源：http://dali.sweek.top/Article/details/gt2nrcvvpze.html

PHP:  $s === strrev($s);
来源：http://dali.xylfe.cn/Article/details/gt2lbvpoqhd.html

JS:   s === [...s].reverse().join("")
来源：http://dali.cucudq.cn/Article/details/gt2vexdgtpj.html

TS:   s === [...s].reverse().join("")
来源：http://dali.hywenlv.cn/Article/details/gt2luqzfczz.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.0kj1m.cn/Article/details/gt2ypsddvhr.html

Go:   // 双指针从两端比较
来源：http://dali.sweek.top/Article/details/gt2sasejswf.html

Ruby: s == s.reverse
来源：http://dali.jinghuilouyu.cn/Article/details/gt2malvregp.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.quarkkingdee.top/Article/details/gt2tybtjlce.html

[N07] 两数之和（返回下标）
来源：http://dali.havefunace.top/Article/details/gt2zkvthwcy.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.yanxiufei.cn/Article/details/gt2onjmbexm.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.nanxinkj.top/Article/details/gt2wejmzqkx.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.hongshengwenyu.top/Article/details/gt2bffhdgzx.html

TS:   // 手写 Map<string, number>
来源：http://dali.xylfe.cn/Article/details/gt2kxpxmyjb.html

Java: // 手写 HashMap
来源：http://dali.yueranfly.top/Article/details/gt2wyhkckvz.html

Go:   // 手写 map[int]int
来源：http://dali.0kj1m.cn/Article/details/gt2fxrtkwkg.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2tanipulk.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.yvedp.cn/Article/details/gt2vqkarjzo.html

[N08] 生成全排列
来源：http://dali.hnqzz.top/Article/details/gt2zdgtmsei.html

Py:   itertools.permutations(arr)
来源：http://dali.gzhubu.top/Article/details/gt2yovvtagh.html

PHP:  // 手写递归交换
来源：http://dali.cucudq.cn/Article/details/gt2dogbadna.html

JS:   // 手写回溯递归
来源：http://dali.pengpengdd.cyou/Article/details/gt2tzuzxwyg.html

TS:   // 手写回溯递归
来源：http://dali.hongshengwenyu.top/Article/details/gt2bhzaxixy.html

Java: // 手写回溯递归
来源：http://dali.yongpay.top/Article/details/gt2uozpduyp.html

Go:   // 手写回溯递归
来源：http://dali.aibaodan.cn/Article/details/gt2hnblmjbj.html

Ruby: arr.permutation.to_a
来源：http://dali.316326.xyz/Article/details/gt2blnvtiun.html

C#:   // 手写回溯递归
来源：http://dali.316326.xyz/Article/details/gt2dprzkixa.html

[N09] 栈与队列
来源：http://dali.cheryme.top/Article/details/gt2msidbfme.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.cheryme.top/Article/details/gt2pfhkwqnl.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.shangyingyoupin.top/Article/details/gt2tzgfrpsn.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.yongpay.top/Article/details/gt2mqrcpxiy.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.gaohongyu789.top/Article/details/gt2uykaczwl.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.mhx1999.top/Article/details/gt2xixifild.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.yj20258.top/Article/details/gt2mxztsjqr.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2mmgduenh.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.shangyingyoupin.top/Article/details/gt2pykftydz.html

[N10] 链表节点定义
来源：http://dali.smart0.xyz/Article/details/gt2aoeaallr.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.dashuyun.cn/Article/details/gt2jkjkksej.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.andypj.xyz/Article/details/gt2rpyfsghz.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.vqdsnc.cn/Article/details/gt2ullqqabr.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.sweek.top/Article/details/gt2oksbzhco.html

Java: class Node { int v; Node next; }
来源：http://dali.zhengqikj.top/Article/details/gt2wawwgoah.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.wangshuangyany.cn/Article/details/gt2stemifre.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhengqikj.top/Article/details/gt2zpmzyqci.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.dashuyun.cn/Article/details/gt2lkxnaeet.html

[N11] 二叉树中序遍历
来源：http://dali.ppjwa.cn/Article/details/gt2lgzimoaq.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gowowhfj.html

PHP:  // 手写递归函数
来源：http://dali.yuxming.cn/Article/details/gt2xdxjczsg.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jqgufenzy.top/Article/details/gt2dagyywvv.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhongyouzk.top/Article/details/gt2oqrukbam.html

Java: // 手写递归
来源：http://dali.ivvv.top/Article/details/gt2zzkgdskt.html

Go:   // 手写递归
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vtjnupnr.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.kuanghao11.cn/Article/details/gt2rovxprwr.html

C#:   // 手写递归
来源：http://dali.xylfe.cn/Article/details/gt2wirkdbcp.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.nanxinkj.top/Article/details/gt2pnpbypdj.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.redwolf501.top/Article/details/gt2bjaoqpco.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.chenjidiqi.icu/Article/details/gt2fwmhqtvf.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.chenjidiqi.icu/Article/details/gt2lwdmzreg.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.0kj1m.cn/Article/details/gt2cmdkfqla.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2sbnlmioj.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.ppjwa.cn/Article/details/gt2qpakcksv.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.jqgfzy.top/Article/details/gt2ahtfnbbs.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.iojbl.cn/Article/details/gt2bdzazjyj.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gt2dfiojflf.html

O. 并发与异步
来源：http://dali.c1oappe.top/Article/details/gt2tqlqkqgj.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gt2ekicyzam.html

[O01] 启动一个线程
来源：http://dali.shuidangran.top/Article/details/gt2skqohbqp.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.dianchejie.cn/Article/details/gt2zouovogq.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhixingplan.top/Article/details/gt2gapmidpj.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.daxiang520.top/Article/details/gt2djynufgt.html

TS:   // 同 JS
来源：http://dali.yvedp.cn/Article/details/gt2lcteamar.html

Java: new Thread(() -> f()).start()
来源：http://dali.yueranfly.top/Article/details/gt2btblxtsr.html

Go:   go f()
来源：http://dali.c1oappe.top/Article/details/gt2nucsfycc.html

Ruby: Thread.new { f }
来源：http://dali.yongpay.top/Article/details/gt2uayhnlxw.html

C#:   Task.Run(() => F());
来源：http://dali.smart0.xyz/Article/details/gt2bjzssaxb.html

[O02] 使用线程池
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2htuggztw.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.shuidangran.top/Article/details/gt2kxnefbxn.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.yvedp.cn/Article/details/gt2lzvurgox.html

JS:   // worker_threads 线程池
来源：http://dali.wangdashe.top/Article/details/gt2ojcdiveo.html

TS:   // worker_threads 线程池
来源：http://dali.redwolf501.top/Article/details/gt2vhtoezbg.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.dashuyun.cn/Article/details/gt2jskzltmx.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.yanxiufei.cn/Article/details/gt2oetqqmtu.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.sufxvd.cn/Article/details/gt2gqkjztmt.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.aizwys.cn/Article/details/gt2emktyfja.html

[O03] 加锁保护共享数据
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nzbduzze.html

Py:   with lock: shared += 1
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nflkiiqb.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.hongshengwenyu.top/Article/details/gt2xucaupfp.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.hnqzz.top/Article/details/gt2jbyjfoxv.html

TS:   // 同 JS
来源：http://dali.tanke756.top/Article/details/gt2mhawqdzx.html

Java: synchronized (this) { shared++; }
来源：http://dali.chenzaomai.com/Article/details/gt2ngqygkdy.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.xuanzx.com/Article/details/gt2xycknods.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2piycqobx.html

C#:   lock (gate) { shared++; }
来源：http://dali.xuanzx.com/Article/details/gt2zqcglwxx.html

[O04] 定义异步函数并等待
来源：http://dali.svipenyu.cn/Article/details/gt2chhgxodg.html

Py:   async def f():⏎    await g()
来源：http://dali.hnxiangtu.top/Article/details/gt2yycdgott.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.hywenlv.cn/Article/details/gt2bhufkvvh.html

JS:   async function f() { await g(); }
来源：http://dali.zhongyouzk.top/Article/details/gt2dxahwhtm.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.hnqzz.top/Article/details/gt2qcwoiktb.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.yongpay.top/Article/details/gt2wqguccon.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.chenzaomai.com/Article/details/gt2kfgjxchy.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.yj20258888.top/Article/details/gt2eztnubhl.html

C#:   async Task F() { await G(); }
来源：http://dali.ehwqpu.com/Article/details/gt2xfjagfsk.html

[O05] 并发执行并等待全部完成
来源：http://dali.jiagoushi.top/Article/details/gt2vykzknzh.html

Py:   asyncio.gather(*tasks)
来源：http://dali.ehwqpu.com/Article/details/gt2bmcezroj.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.kuanghao11.cn/Article/details/gt2xitxqzex.html

JS:   await Promise.all(tasks)
来源：http://dali.chenzaomai.com/Article/details/gt2bymvchcq.html

TS:   await Promise.all(tasks)
来源：http://dali.yvedp.cn/Article/details/gt2sbexoqhv.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.redwolf501.top/Article/details/gt2dbdikiix.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.nanxuanxn.top/Article/details/gt2dcpxrlvo.html

Ruby: threads.map(&:join)
来源：http://dali.vqdsnc.cn/Article/details/gt2wfskibfc.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.jiagoushi.top/Article/details/gt2vcktgotp.html

[O06] 使用进程池
来源：http://dali.zdqjudy.top/Article/details/gt2mugjxloc.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.feifeiyinyue.top/Article/details/gt2xmznzsay.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.snrcjt.cn/Article/details/gt2wgpsqmzu.html

JS:   // child_process / cluster 模块
来源：http://dali.guowangkeji.top/Article/details/gt2urbsahaa.html

TS:   // child_process / cluster 模块
来源：http://dali.ppjwa.cn/Article/details/gt2razgvyop.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.ehwqpu.com/Article/details/gt2dcnsendn.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.mhx1999.top/Article/details/gt2thivyjaa.html

Ruby: // fork 块
来源：http://dali.yonumen.top/Article/details/gt2klnryjzo.html

C#:   Parallel.For
来源：http://dali.shangyingyoupin.top/Article/details/gt2hvzvsdjr.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2cvtjjedu.html

P. 常用工具函数
来源：http://dali.shzxlz.cn/Article/details/gt2rfsdlcmy.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gt2sdvzrdrk.html

[P01] 生成 UUID
来源：http://dali.yj20258888.top/Article/details/gt2idxhfsdu.html

Py:   str(uuid.uuid4())
来源：http://dali.yvedp.cn/Article/details/gt2xheulwoe.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.chenlongwang.top/Article/details/gt2qsvsccqj.html

JS:   crypto.randomUUID()
来源：http://dali.pengpengdd.cyou/Article/details/gt2rmrqkiyb.html

TS:   crypto.randomUUID()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gvptmttf.html

Java: UUID.randomUUID().toString()
来源：http://dali.nanxuanxn.top/Article/details/gt2cnwcapyh.html

Go:   // 用 github.com/google/uuid
来源：http://dali.aizwys.cn/Article/details/gt2pzaaemnk.html

Ruby: SecureRandom.uuid
来源：http://dali.jqgufenzy.top/Article/details/gt2akjcmmtj.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.yj202588.top/Article/details/gt2tywmfsgj.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2yylxpkcv.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.guannengcc.top/Article/details/gt2aiukjkgl.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.yongpay.top/Article/details/gt2vpozhwlz.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.wangshuangyany.cn/Article/details/gt2gruyjgbj.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.ydzc1.top/Article/details/gt2tpxumqmw.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.dashuyun.cn/Article/details/gt2wkybsnqa.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.vqdsnc.cn/Article/details/gt2ihuagwlh.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.fzhhl.top/Article/details/gt2zbdanpvq.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.chenjidiqi.icu/Article/details/gt2lsavzklt.html

[P03] 生成短随机字符串
来源：http://dali.yonumen.top/Article/details/gt2bbmaprmt.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.andypj.xyz/Article/details/gt2kcsqnkhm.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.yongpay.top/Article/details/gt2nmkvhpxw.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jlsjyb.cn/Article/details/gt2adltfljy.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.hongshengwenyu.top/Article/details/gt2tryivchd.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.cqqwz.cn/Article/details/gt2zdkmlnmz.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhengqikj.top/Article/details/gt2ljmfbquf.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.yj20258888.top/Article/details/gt2sjhuxfnr.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.aizwys.cn/Article/details/gt2cwykwuhw.html

[P04] 求长度
来源：http://dali.sufxvd.cn/Article/details/gt2oknpnqyl.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.birdmap.top/Article/details/gt2wmqozujh.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.vqdsnc.cn/Article/details/gt2rtastaoj.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.aizwys.cn/Article/details/gt2vbzjzpjp.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.haohaochexian.top/Article/details/gt2pddfuarj.html

Java: list.size();  map.size();  s.length()
来源：http://dali.aibaodan.cn/Article/details/gt2ungtfqyf.html

Go:   len(arr);  len(m)
来源：http://dali.jqgfzy.top/Article/details/gt2peobcvvh.html

Ruby: x.length;  x.size
来源：http://dali.0kj1m.cn/Article/details/gt2mghlbzex.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.cheryme.top/Article/details/gt2nvozkogr.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zdqjudy.top/Article/details/gt2qqzrtqgs.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.jqgfzy.top/Article/details/gt2tdcqcglf.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ahanrgcl.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.meibo888.top/Article/details/gt2woyolsok.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.shangyingyoupin.top/Article/details/gt2ckjvaebf.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.pengpengdd.cyou/Article/details/gt2dlwykmjw.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.ehwqpu.com/Article/details/gt2vbmvlwxh.html

Ruby: a == b
来源：http://dali.gaohongyu789.top/Article/details/gt2lpjtdwmt.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.nanxinkj.top/Article/details/gt2wvaondry.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.yonumen.top/Article/details/gt2sgqypest.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.jlsjyb.cn/Article/details/gt2kvwzkmhw.html

PHP:  if (empty($x)) {}
来源：http://dali.zhongyouzk.top/Article/details/gt2emonqntu.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.ybcxt.top/Article/details/gt2muiwugin.html

TS:   if (x == null) {}
来源：http://dali.nwbrower.top/Article/details/gt2nthxqbns.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.dianchejie.cn/Article/details/gt2shabwfet.html

Go:   if x == nil {}
来源：http://dali.chenzaomai.com/Article/details/gt2ehwxyhgu.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.iojbl.cn/Article/details/gt2akxzvxfy.html

C#:   if (x is null) {}
来源：http://dali.yuanzhike.top/Article/details/gt2dzsfsqwk.html

[P07] 防抖与节流
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nnopqcur.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.shanyushiyangtech.top/Article/details/gt2exikhcrg.html

PHP:  // 手写时间戳比较
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2emcwbkkl.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhengqikj.top/Article/details/gt2unckdocw.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lwxerkdw.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.gaohongyu789.top/Article/details/gt2glqjmtqq.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.yongpay.top/Article/details/gt2sopxbwkw.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.snrcjt.cn/Article/details/gt2ejkzrinz.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.svipenyu.cn/Article/details/gt2wxjhsaea.html

[P08] 处理浮点精度问题
来源：http://dali.zycfv.cn/Article/details/gt2gsvpqzls.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.gogol.net.cn/Article/details/gt2jefxzozj.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.redwolf501.top/Article/details/gt2idhtshag.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2kubmexbn.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.birdmap.top/Article/details/gt2pdggztac.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.feifeiyinyue.top/Article/details/gt2ppwlrrxl.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.316326.xyz/Article/details/gt2qejfzhvh.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.nanxinkj.top/Article/details/gt2rqeysxql.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.sysykeji.top/Article/details/gt2nvcaikvz.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gt2ibiumubt.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.hnxiangtu.top/Article/details/gt2jbidnasd.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gt2pveazxxd.html

[Q01] 创建表
来源：http://dali.wangshuangyany.cn/Article/details/gt2jecjsvqv.html

CREATE TABLE users (
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bsyigrbj.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.gogol.net.cn/Article/details/gt2rlscxkii.html

name VARCHAR(50) NOT NULL,
来源：http://dali.yanxiufei.cn/Article/details/gt2klnvlsob.html

email VARCHAR(100) UNIQUE,
来源：http://dali.316326.xyz/Article/details/gt2lqjtohsa.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.316326.xyz/Article/details/gt2nxefsdou.html

);
来源：http://dali.kuanghao11.cn/Article/details/gt2kimuunky.html

[Q02] 创建带外键的表
来源：http://dali.ehwqpu.com/Article/details/gt2yhkvgqiq.html

CREATE TABLE orders (
来源：http://dali.tianlin.xyz/Article/details/gt2nkweilay.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.vqdsnc.cn/Article/details/gt2ofsfhtyn.html

user_id INT NOT NULL,
来源：http://dali.jinqigufen.top/Article/details/gt2gujvcpxy.html

amount DECIMAL(10, 2),
来源：http://dali.svipenyu.cn/Article/details/gt2uthskzvb.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.xuanzx.com/Article/details/gt2gclgxzjw.html


<!-- 参考信息 -->