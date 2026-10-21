代发 wailian999

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.pycfn.com/Article/details/gtmcuyrngv.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.hywenlv.cn/Article/details/gtrevioftv.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.hnxiangtu.top/Article/details/gtzkkdwejm.html

C#:   Process.Start("ls", "-l");
来源：http://dali.sysykeji.top/Article/details/gtetrusmvm.html

[M04] 获取当前工作目录
来源：http://dali.sufxvd.cn/Article/details/gtfxtafhno.html

Py:   os.getcwd()
来源：http://dali.pycfn.com/Article/details/gtzxwdrity.html

PHP:  getcwd();
来源：http://dali.guannengcc.top/Article/details/gtkvkxhkkc.html

JS:   process.cwd()
来源：http://dali.sxryk.cn/Article/details/gtamxedwbx.html

TS:   process.cwd()
来源：http://dali.zhongyouzk.top/Article/details/gtfzjpajbr.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.pengpengdd.cyou/Article/details/gthigqnekc.html

Go:   os.Getwd()
来源：http://dali.xuanzx.com/Article/details/gtdxmjxobg.html

Ruby: Dir.pwd
来源：http://dali.pycfn.com/Article/details/gtnjprpzwv.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.c1oappe.top/Article/details/gtgahhxezb.html

[M05] 设置退出码
来源：http://dali.nanxuanxn.top/Article/details/gtyvxhrfsp.html

Py:   sys.exit(1)
来源：http://dali.yvedp.cn/Article/details/gtzxvlugyh.html

PHP:  exit(1);
来源：http://dali.yj20258888.top/Article/details/gthavyefzx.html

JS:   process.exit(1)
来源：http://dali.dianchejie.cn/Article/details/gtnoyozyrv.html

TS:   process.exit(1)
来源：http://dali.vqdsnc.cn/Article/details/gtazaefcyv.html

Java: System.exit(1)
来源：http://dali.ppjwa.cn/Article/details/gtdwbanvxi.html

Go:   os.Exit(1)
来源：http://dali.yj20258.top/Article/details/gtfzqjbvrv.html

Ruby: exit 1
来源：http://dali.xylfe.cn/Article/details/gtixswhrtk.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.xuetiantiany.cn/Article/details/gtadvugbwz.html

[M06] 向标准错误输出
来源：http://dali.gogol.net.cn/Article/details/gtuyrhudco.html

Py:   print("err", file=sys.stderr)
来源：http://dali.yueranfly.top/Article/details/gtazdcnubv.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.meibo888.top/Article/details/gtkvslekmb.html

JS:   console.error("err")
来源：http://dali.tianlin.xyz/Article/details/gtajsegmog.html

TS:   console.error("err")
来源：http://dali.jqgfzy.top/Article/details/gtwblklxdo.html

Java: System.err.println("err")
来源：http://dali.hnxiangtu.top/Article/details/gtddsaxegn.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.ybcxt.top/Article/details/gtvsmxpond.html

Ruby: warn "err"
来源：http://dali.cheryme.top/Article/details/gtauzfdpvb.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.hnxiangtu.top/Article/details/gtwrgtvlyb.html

[M07] 判断是否为主入口
来源：http://dali.birdmap.top/Article/details/gtqcvibocv.html

Py:   if __name__ == "__main__":
来源：http://dali.hfpthk.cn/Article/details/gtnunrzmlw.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.9152youxi.cn/Article/details/gthvjylupa.html

JS:   require.main === module
来源：http://dali.jyoumei.cn/Article/details/gtprsunxii.html

TS:   require.main === module
来源：http://dali.nanxuanxn.top/Article/details/gtgslyiqld.html

Java: public static void main(String[] args)
来源：http://dali.daria6918.cn/Article/details/gtoorwofvl.html

Go:   func main()
来源：http://dali.yuxming.cn/Article/details/gtndjixdpr.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.daxiang520.top/Article/details/gthbegqfve.html

C#:   static void Main(string[] args)
来源：http://dali.ydzc1.top/Article/details/gtjvtijhvp.html

[M08] 获取系统与运行时信息
来源：http://dali.cashguo.top/Article/details/gteembhhmb.html

Py:   platform.system();  platform.python_version()
来源：http://dali.ehwqpu.com/Article/details/gttgqodqys.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.aibaodan.cn/Article/details/gtxewvjnvg.html

JS:   process.platform;  process.version
来源：http://dali.kuanghao11.cn/Article/details/gtgfkdpmwg.html

TS:   process.platform;  process.version
来源：http://dali.pengpengdd.cyou/Article/details/gtwogclfyv.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhiwuduotai.top/Article/details/gttyjzswvb.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.jinqigfzy.top/Article/details/gtbgfjryfb.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.gogol.net.cn/Article/details/gtywzgqkkv.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.yongpay.top/Article/details/gtqeaqaptf.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtyfllhqvs.html

N. 数据结构与算法
来源：http://dali.fzhhl.top/Article/details/gtcdsksybs.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtctymkzsy.html

[N01] 二分查找（有序数组）
来源：http://dali.feifeiyinyue.top/Article/details/gtoomvetxl.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.guannengcc.top/Article/details/gtknvhqigy.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhoulong.xyz/Article/details/gtbcpjtnsk.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.andypj.xyz/Article/details/gtstvqhfkk.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.guowangkeji.top/Article/details/gtafwqewau.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.redwolf501.top/Article/details/gtunkpxgue.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.jqgfzy.top/Article/details/gteqkjzqbd.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.jinqigfzy.top/Article/details/gttpwmjhuk.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.hongshengwenyu.top/Article/details/gtmmkkyeno.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.aizwys.cn/Article/details/gtgyranrxr.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.chenlongwang.top/Article/details/gtihjkzlaq.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zycfv.cn/Article/details/gtupcztjgv.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.xylfe.cn/Article/details/gtujefglnp.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.nwbrower.top/Article/details/gtslhxmolk.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.yuanzhike.top/Article/details/gtdmgqtksc.html

Go:   slices.Sort(arr)
来源：http://dali.cucudq.cn/Article/details/gttifykjho.html

Ruby: arr.sort
来源：http://dali.jlsjyb.cn/Article/details/gtyaawfdzl.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.jqgfzy.top/Article/details/gtinxufrjk.html

[N03] 快速排序（分治示例）
来源：http://dali.gotoacloud.top/Article/details/gtiusdvblf.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.ybcxt.top/Article/details/gtzhyqwjsl.html

PHP:  // 递归实现，或用 usort
来源：http://dali.xylfe.cn/Article/details/gtuwcafayc.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jyoumei.cn/Article/details/gtqshezklv.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.smart0.xyz/Article/details/gtmwbfrprj.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.jqgufenzy.top/Article/details/gtgfjooqqt.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthxtqfnst.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.ybcxt.top/Article/details/gtdvfnfbez.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.jinqigfzy.top/Article/details/gtaehmiljc.html

[N04] 斐波那契数列
来源：http://dali.ppjwa.cn/Article/details/gtxzvaiujt.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.dashuyun.cn/Article/details/gtrlwcepbh.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zdqjudy.top/Article/details/gtmnbzxxja.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yanxiufei.cn/Article/details/gtausgqxep.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbuhddmpt.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.xziqi.cn/Article/details/gtwvbnmvjl.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.snrcjt.cn/Article/details/gtykflvipq.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.cashguo.top/Article/details/gtuhgiscug.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.c1oappe.top/Article/details/gtpcwgjfqe.html

[N05] 最大公约数
来源：http://dali.nanxuanxn.top/Article/details/gtfvxnzqgg.html

Py:   math.gcd(a, b)
来源：http://dali.dianchejie.cn/Article/details/gtmvrnkybi.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtcrqvlflp.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.cqqwz.cn/Article/details/gtqdhgxntd.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.ehwqpu.com/Article/details/gtzqehjxug.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.daxiang520.top/Article/details/gtolrjtrtz.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.xziqi.cn/Article/details/gtrjpauwdr.html

Ruby: a.gcd(b)
来源：http://dali.sxryk.cn/Article/details/gthqzdhphd.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.shzxlz.cn/Article/details/gtgiyhsofa.html

[N06] 判断回文字符串
来源：http://dali.guowangkeji.top/Article/details/gtjtznypad.html

Py:   s == s[::-1]
来源：http://dali.daria6918.cn/Article/details/gtytvrtjcr.html

PHP:  $s === strrev($s);
来源：http://dali.yuanzhike.top/Article/details/gtnnfletqa.html

JS:   s === [...s].reverse().join("")
来源：http://dali.hongshengwenyu.top/Article/details/gtehbdmysy.html

TS:   s === [...s].reverse().join("")
来源：http://dali.xylfe.cn/Article/details/gtzeoxhbya.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.haohaochexian.top/Article/details/gtnehwwutv.html

Go:   // 双指针从两端比较
来源：http://dali.svipenyu.cn/Article/details/gtetzhplnr.html

Ruby: s == s.reverse
来源：http://dali.yj20258888.top/Article/details/gtoblokpzj.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.haohaochexian.top/Article/details/gtjjzogonv.html

[N07] 两数之和（返回下标）
来源：http://dali.cqqwz.cn/Article/details/gttsswmybx.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.jinqigufen.top/Article/details/gtkunzpodx.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.dianchejie.cn/Article/details/gtowfujfjd.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.yueranfly.top/Article/details/gtyxcqywks.html

TS:   // 手写 Map<string, number>
来源：http://dali.jyoumei.cn/Article/details/gtggyawebj.html

Java: // 手写 HashMap
来源：http://dali.cqqwz.cn/Article/details/gtxpgajovf.html

Go:   // 手写 map[int]int
来源：http://dali.xylfe.cn/Article/details/gtttkgqvpv.html

Ruby: // 手写 Hash
来源：http://dali.yj20258.top/Article/details/gtwssppdmn.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.xinyue.icu/Article/details/gtveucwmqy.html

[N08] 生成全排列
来源：http://dali.316326.xyz/Article/details/gtkxjppkqr.html

Py:   itertools.permutations(arr)
来源：http://dali.cucudq.cn/Article/details/gtgwgcvxag.html

PHP:  // 手写递归交换
来源：http://dali.gogol.net.cn/Article/details/gtyhztqtoh.html

JS:   // 手写回溯递归
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaxvwjbac.html

TS:   // 手写回溯递归
来源：http://dali.zhengqikj.top/Article/details/gthxqgvejx.html

Java: // 手写回溯递归
来源：http://dali.cucudq.cn/Article/details/gthukiupli.html

Go:   // 手写回溯递归
来源：http://dali.tian-w.cn/Article/details/gtqhjdjyol.html

Ruby: arr.permutation.to_a
来源：http://dali.fengsongda.top/Article/details/gtmfvaxdue.html

C#:   // 手写回溯递归
来源：http://dali.snrcjt.cn/Article/details/gtmyvkjvyi.html

[N09] 栈与队列
来源：http://dali.snrcjt.cn/Article/details/gthlcjnxkj.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.chenlongwang.top/Article/details/gtvbrzitnv.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.316326.xyz/Article/details/gtcaqxatst.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.c1oappe.top/Article/details/gtiasncmlu.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.tianlin.xyz/Article/details/gtbbcafjkb.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.bjfxy.top/Article/details/gtajphedti.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.jlsjyb.cn/Article/details/gtkuztjmwh.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhiwuduotai.top/Article/details/gtmivlvgfg.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.nanxuanxn.top/Article/details/gtxhikvbvi.html

[N10] 链表节点定义
来源：http://dali.nwbrower.top/Article/details/gtoobexcoe.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.jinyuanbaomall.cn/Article/details/gtedyxyiir.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhoulong.xyz/Article/details/gtkefpttox.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.chenzaomai.com/Article/details/gtdxwsvbfn.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.gogol.net.cn/Article/details/gttycjqgkk.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gtsueceqhs.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.smart0.xyz/Article/details/gtivzfowva.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcilawwuf.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoixjkvml.html

[N11] 二叉树中序遍历
来源：http://dali.nanxuanxn.top/Article/details/gtmbsueldp.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.jinqigfzy.top/Article/details/gtmpzksgge.html

PHP:  // 手写递归函数
来源：http://dali.zdqjudy.top/Article/details/gtfpkkryxe.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jqgufenzy.top/Article/details/gtsgtdvenv.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.fengsongda.top/Article/details/gtwqrniohr.html

Java: // 手写递归
来源：http://dali.tianlin.xyz/Article/details/gtuukuhknr.html

Go:   // 手写递归
来源：http://dali.guannengcc.top/Article/details/gtmhbiwqox.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.gogol.net.cn/Article/details/gtgwiojbhd.html

C#:   // 手写递归
来源：http://dali.zhiwuduotai.top/Article/details/gttetolldi.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.yj20258888.top/Article/details/gtjhtrfogo.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.hnqzz.top/Article/details/gtttxvdote.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.ehwqpu.com/Article/details/gtcwlvxwku.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.tian-w.cn/Article/details/gtstzeoxyj.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zycfv.cn/Article/details/gthtnrsvea.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yanxiufei.cn/Article/details/gteyqwgaqh.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.iojbl.cn/Article/details/gtihcwqzue.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.snrcjt.cn/Article/details/gttagtxtln.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.pengpengdd.cyou/Article/details/gtizrsorxc.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtkfimhhwz.html

O. 并发与异步
来源：http://dali.meibo888.top/Article/details/gtwideiuny.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtyyrqtrcj.html

[O01] 启动一个线程
来源：http://dali.ywan-chungtsiang.top/Article/details/gtujyiwktn.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxotcddbf.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.birdmap.top/Article/details/gtndapdsts.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.meibo888.top/Article/details/gtwptkhuvr.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gtkekhmqck.html

Java: new Thread(() -> f()).start()
来源：http://dali.gotoacloud.top/Article/details/gticcrahps.html

Go:   go f()
来源：http://dali.bjfxy.top/Article/details/gteoulnrbk.html

Ruby: Thread.new { f }
来源：http://dali.zhoulong.xyz/Article/details/gtcjwdsxrm.html

C#:   Task.Run(() => F());
来源：http://dali.tanke756.top/Article/details/gtinxdnxrr.html

[O02] 使用线程池
来源：http://dali.bjfxy.top/Article/details/gthrodfuhi.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.fengsongda.top/Article/details/gtgtdkhftd.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.sxryk.cn/Article/details/gtucmlyidn.html

JS:   // worker_threads 线程池
来源：http://dali.birdmap.top/Article/details/gtomygeppp.html

TS:   // worker_threads 线程池
来源：http://dali.sysykeji.top/Article/details/gthvfnmyio.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.cdnleiting.top/Article/details/gtfcwwojfd.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.hammf.cn/Article/details/gtrxahwses.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.redwolf501.top/Article/details/gtsxfncsrv.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhiwuduotai.top/Article/details/gtivqrayaj.html

[O03] 加锁保护共享数据
来源：http://dali.aizwys.cn/Article/details/gtfqiyitha.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gthgczfnje.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.shangyingyoupin.top/Article/details/gtecotgmoq.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.hongshengwenyu.top/Article/details/gtxbawtazh.html

TS:   // 同 JS
来源：http://dali.quarkkingdee.top/Article/details/gtipflffdj.html

Java: synchronized (this) { shared++; }
来源：http://dali.sxryk.cn/Article/details/gtbkoedcgx.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.316326.xyz/Article/details/gtqitzumwg.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.yuxming.cn/Article/details/gtwgucaban.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhoulong.xyz/Article/details/gttphpxehi.html

[O04] 定义异步函数并等待
来源：http://dali.meibo888.top/Article/details/gtmlxpofun.html

Py:   async def f():⏎    await g()
来源：http://dali.ppjwa.cn/Article/details/gtsvlxmjbk.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.yanxiufei.cn/Article/details/gtydtfcpus.html

JS:   async function f() { await g(); }
来源：http://dali.fzhhl.top/Article/details/gtnxllezks.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.jqgufenzy.top/Article/details/gtpwbgqqvo.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhiwuduotai.top/Article/details/gtfapxobmp.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.hongshengwenyu.top/Article/details/gtrkxknbrs.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtumqpsjao.html

C#:   async Task F() { await G(); }
来源：http://dali.yanxiufei.cn/Article/details/gtmopofeqr.html

[O05] 并发执行并等待全部完成
来源：http://dali.nwbrower.top/Article/details/gttfndtxev.html

Py:   asyncio.gather(*tasks)
来源：http://dali.yj202588.top/Article/details/gtfgxlxgeg.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.fengsongda.top/Article/details/gtcubuiyvm.html

JS:   await Promise.all(tasks)
来源：http://dali.sweek.top/Article/details/gtkxdkojvm.html

TS:   await Promise.all(tasks)
来源：http://dali.jinqigufen.top/Article/details/gtxsdlrslu.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoliyzguv.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.sysykeji.top/Article/details/gtjhrtefje.html

Ruby: threads.map(&:join)
来源：http://dali.yj20258888.top/Article/details/gtesswvsdf.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.yangfankeji.com/Article/details/gtxwhxwqsa.html

[O06] 使用进程池
来源：http://dali.jqgufenzy.top/Article/details/gtnaeiyajf.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoxeebruk.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.bjfxy.top/Article/details/gtwatzqkql.html

JS:   // child_process / cluster 模块
来源：http://dali.jinghuilouyu.cn/Article/details/gtgrqpjvpg.html

TS:   // child_process / cluster 模块
来源：http://dali.zhoulong.xyz/Article/details/gtawtvxgsu.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.iojbl.cn/Article/details/gtwjoviqzr.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.xziqi.cn/Article/details/gtopyyqaes.html

Ruby: // fork 块
来源：http://dali.shzxlz.cn/Article/details/gtenopuctp.html

C#:   Parallel.For
来源：http://dali.hywenlv.cn/Article/details/gtxumbmclz.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtfbvjowaj.html

P. 常用工具函数
来源：http://dali.jqgufenzy.top/Article/details/gtohmunbge.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtxhviaaxb.html

[P01] 生成 UUID
来源：http://dali.snrcjt.cn/Article/details/gtzduyhawi.html

Py:   str(uuid.uuid4())
来源：http://dali.cdnleiting.top/Article/details/gtjqahawfg.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.sysykeji.top/Article/details/gtfpwxwgsy.html

JS:   crypto.randomUUID()
来源：http://dali.vqdsnc.cn/Article/details/gtumxaqapo.html

TS:   crypto.randomUUID()
来源：http://dali.chenzaomai.com/Article/details/gtdmxjpqjq.html

Java: UUID.randomUUID().toString()
来源：http://dali.snrcjt.cn/Article/details/gtudpzntps.html

Go:   // 用 github.com/google/uuid
来源：http://dali.hysaishi.cn/Article/details/gtbymujonk.html

Ruby: SecureRandom.uuid
来源：http://dali.yvedp.cn/Article/details/gtpqxpyrmh.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.hongshengwenyu.top/Article/details/gtsoyhxzdv.html

[P02] MD5 / SHA256 摘要
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmfrvpszu.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.shanyushiyangtech.top/Article/details/gtgtxakgrd.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.snrcjt.cn/Article/details/gtxmmofltt.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.jinqigufen.top/Article/details/gtxyadfmrp.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.jiagoushi.top/Article/details/gtrwsvllre.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.hongshengwenyu.top/Article/details/gtyeyndcol.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.yj202588.top/Article/details/gtighlgmfy.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.9152youxi.cn/Article/details/gteupuzilf.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zycfv.cn/Article/details/gtmsnjbmtn.html

[P03] 生成短随机字符串
来源：http://dali.cucudq.cn/Article/details/gtaiacvgtl.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.tian-w.cn/Article/details/gtwvmgckqn.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.gzhubu.top/Article/details/gtanazrpxn.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.xziqi.cn/Article/details/gtegxhnqpc.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.dashuyun.cn/Article/details/gtsuemucxd.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.fengsongda.top/Article/details/gtaflxulmg.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.cqqwz.cn/Article/details/gtmlkghuaj.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.wangshuangyany.cn/Article/details/gteqgovxwh.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.jinqigfzy.top/Article/details/gtzoothska.html

[P04] 求长度
来源：http://dali.jiagoushi.top/Article/details/gtkmwyundj.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.chenjidiqi.icu/Article/details/gtkqxgickg.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.haohaochexian.top/Article/details/gtaxapifqr.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.kuanghao11.cn/Article/details/gtgldvafyl.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.ehwqpu.com/Article/details/gtbzdhqzaw.html

Java: list.size();  map.size();  s.length()
来源：http://dali.sweek.top/Article/details/gtwpdpolmj.html

Go:   len(arr);  len(m)
来源：http://dali.hnqzz.top/Article/details/gtmgvywkgi.html

Ruby: x.length;  x.size
来源：http://dali.jianghu66.top/Article/details/gtlerlzmkt.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.316326.xyz/Article/details/gtmugzydlz.html

[P05] 判断两个对象内容是否相等
来源：http://dali.xziqi.cn/Article/details/gtbsztxvfe.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.chenlongwang.top/Article/details/gtrqzzgkxy.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.cqqwz.cn/Article/details/gtjrtvqjsb.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.vqdsnc.cn/Article/details/gtqlebgqui.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.yj20258888.top/Article/details/gtnmlrwrpu.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.aizwys.cn/Article/details/gtdebfgzxh.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.yonumen.top/Article/details/gtnojyfyjs.html

Ruby: a == b
来源：http://dali.yj20258.top/Article/details/gtnqyvwlvu.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.shanyushiyangkeji.top/Article/details/gthrgtzgzu.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.ivvv.top/Article/details/gtffifrvdb.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.andypj.xyz/Article/details/gtpamxdoms.html

PHP:  if (empty($x)) {}
来源：http://dali.zhiwuduotai.top/Article/details/gtgjmstttg.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.guowangkeji.top/Article/details/gtnercbtwn.html

TS:   if (x == null) {}
来源：http://dali.mhx1999.top/Article/details/gtylavvxbr.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.jianghu66.top/Article/details/gtwzbfciio.html

Go:   if x == nil {}
来源：http://dali.hywenlv.cn/Article/details/gtrxlkrowd.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.daria6918.cn/Article/details/gtywsdhfii.html

C#:   if (x is null) {}
来源：http://dali.quarkkingdee.top/Article/details/gtizguyuru.html

[P07] 防抖与节流
来源：http://dali.yuanzhike.top/Article/details/gtjglxofiz.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.vqdsnc.cn/Article/details/gtxpsaxqsl.html

PHP:  // 手写时间戳比较
来源：http://dali.nanxuanxn.top/Article/details/gtsjevnqov.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.ydzc1.top/Article/details/gtvuwmgfsd.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpewvqmpi.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.shzxlz.cn/Article/details/gtbzmjyvbc.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.sysykeji.top/Article/details/gtiuppouem.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.daria6918.cn/Article/details/gtxyhyajfn.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.hysaishi.cn/Article/details/gtzaymeexa.html

[P08] 处理浮点精度问题
来源：http://dali.wangdashe.top/Article/details/gtclbkftcl.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.feifeiyinyue.top/Article/details/gtzqveictf.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.hnqzz.top/Article/details/gtzopjiuyf.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.jiagoushi.top/Article/details/gtydvflcri.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.ydzc1.top/Article/details/gtcrktbjkb.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.shanyushiyangtech.top/Article/details/gtxvivjfoi.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.tian-w.cn/Article/details/gtclpgjwix.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.yuxming.cn/Article/details/gtcxxwtxtb.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.hysaishi.cn/Article/details/gtaoartpya.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtodchtins.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.meibo888.top/Article/details/gtsxkatiau.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtttsisgmc.html

[Q01] 创建表
来源：http://dali.feifeiyinyue.top/Article/details/gtjrycduox.html

CREATE TABLE users (
来源：http://dali.guannengcc.top/Article/details/gthrnbmmof.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.svipenyu.cn/Article/details/gtbrcdrlrh.html

name VARCHAR(50) NOT NULL,
来源：http://dali.nwbrower.top/Article/details/gtkcuqpgvc.html

email VARCHAR(100) UNIQUE,
来源：http://dali.gotoacloud.top/Article/details/gtdkeakxhb.html


<!-- 参考信息 -->