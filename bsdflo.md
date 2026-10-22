代发 wailian999

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.gzhubu.top/Article/details/gthkbwsicz.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.xuanzx.com/Article/details/gtfqbgiixc.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.wangshuangyany.cn/Article/details/gtlwsdppgf.html

C#:   Process.Start("ls", "-l");
来源：http://dali.hongshengwenyu.top/Article/details/gtywbjyvoi.html

[M04] 获取当前工作目录
来源：http://dali.ppjwa.cn/Article/details/gtwnfwfuvr.html

Py:   os.getcwd()
来源：http://dali.ivvv.top/Article/details/gttwebrvao.html

PHP:  getcwd();
来源：http://dali.jqgfzy.top/Article/details/gtmecxmrhs.html

JS:   process.cwd()
来源：http://dali.meibo888.top/Article/details/gtbmtcpgiz.html

TS:   process.cwd()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpwozvrhf.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.hammf.cn/Article/details/gtdstnrzns.html

Go:   os.Getwd()
来源：http://dali.yangfankeji.com/Article/details/gtxvbbdyua.html

Ruby: Dir.pwd
来源：http://dali.gaohongyu789.top/Article/details/gtrpsabvse.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtefdahyum.html

[M05] 设置退出码
来源：http://dali.zycfv.cn/Article/details/gtnffsqpke.html

Py:   sys.exit(1)
来源：http://dali.jlsjyb.cn/Article/details/gtyrpunezj.html

PHP:  exit(1);
来源：http://dali.hnqzz.top/Article/details/gtoytiaoui.html

JS:   process.exit(1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgqwvzeec.html

TS:   process.exit(1)
来源：http://dali.vqdsnc.cn/Article/details/gtjewucxkk.html

Java: System.exit(1)
来源：http://dali.pycfn.com/Article/details/gtcyvtnrkx.html

Go:   os.Exit(1)
来源：http://dali.yj20258888.top/Article/details/gtbphrdshj.html

Ruby: exit 1
来源：http://dali.haohaochexian.top/Article/details/gtmuyrtfpe.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.xuetiantiany.cn/Article/details/gtmsmiclyl.html

[M06] 向标准错误输出
来源：http://dali.xuetiantiany.cn/Article/details/gtwndbyyyb.html

Py:   print("err", file=sys.stderr)
来源：http://dali.hnxiangtu.top/Article/details/gtaexsawhk.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhiwuduotai.top/Article/details/gtjmnfsohz.html

JS:   console.error("err")
来源：http://dali.yj20258.top/Article/details/gtnpctqhgj.html

TS:   console.error("err")
来源：http://dali.havefunace.top/Article/details/gtkojjnbog.html

Java: System.err.println("err")
来源：http://dali.mhx1999.top/Article/details/gteybjyljh.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.yvedp.cn/Article/details/gtvoioxedl.html

Ruby: warn "err"
来源：http://dali.316326.xyz/Article/details/gtmrittaqz.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.yj20258888.top/Article/details/gtdrshppiw.html

[M07] 判断是否为主入口
来源：http://dali.sweek.top/Article/details/gtjpkyjxrm.html

Py:   if __name__ == "__main__":
来源：http://dali.zhongyouzk.top/Article/details/gtwidaiskb.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.guowangkeji.top/Article/details/gteoicwgyp.html

JS:   require.main === module
来源：http://dali.jinghuilouyu.cn/Article/details/gtbfzlqvwo.html

TS:   require.main === module
来源：http://dali.yuanzhike.top/Article/details/gtcrkfnfeo.html

Java: public static void main(String[] args)
来源：http://dali.sysykeji.top/Article/details/gtwtwlsbwt.html

Go:   func main()
来源：http://dali.hongshengwenyu.top/Article/details/gtitpgrzgw.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.tanke756.top/Article/details/gtqwnqtzpg.html

C#:   static void Main(string[] args)
来源：http://dali.xuetiantiany.cn/Article/details/gtstqgmsoi.html

[M08] 获取系统与运行时信息
来源：http://dali.ppjwa.cn/Article/details/gtaognxhmi.html

Py:   platform.system();  platform.python_version()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuxmlgtag.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.hnxiangtu.top/Article/details/gtbrrhsugs.html

JS:   process.platform;  process.version
来源：http://dali.daria6918.cn/Article/details/gtnymicuzs.html

TS:   process.platform;  process.version
来源：http://dali.yonumen.top/Article/details/gtvwfuyznc.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.aibaodan.cn/Article/details/gtxfeubfvm.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.guowangkeji.top/Article/details/gtcefjbljh.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.dianchejie.cn/Article/details/gtoenfqqgu.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.daria6918.cn/Article/details/gtpsrtqxwq.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtokzwyiyq.html

N. 数据结构与算法
来源：http://dali.shanyushiyangtech.top/Article/details/gtjqitkjuo.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtyhcjjycp.html

[N01] 二分查找（有序数组）
来源：http://dali.pycfn.com/Article/details/gtriefuzcq.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.havefunace.top/Article/details/gtrykbntxd.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.haohaochexian.top/Article/details/gtfjqdrvnv.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.nwbrower.top/Article/details/gtskjrdssf.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.iojbl.cn/Article/details/gtieytuhrk.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.sweek.top/Article/details/gtzrvutvgn.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.redwolf501.top/Article/details/gtbtjfzdcx.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtovzykvfx.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.gzhubu.top/Article/details/gtrrvdcbly.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.yueranfly.top/Article/details/gtpgvnwlxn.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.xziqi.cn/Article/details/gtivprkewo.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.jqgufenzy.top/Article/details/gtgcelkolp.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.cheryme.top/Article/details/gtgbkmpcfg.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.nanxuanxn.top/Article/details/gtsalahwfe.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.shuidangran.top/Article/details/gtsuwvndbg.html

Go:   slices.Sort(arr)
来源：http://dali.c1oappe.top/Article/details/gtovcddjgb.html

Ruby: arr.sort
来源：http://dali.sweek.top/Article/details/gtxplzpuii.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.chenzaomai.com/Article/details/gtxgkqnhky.html

[N03] 快速排序（分治示例）
来源：http://dali.haohaochexian.top/Article/details/gtaplcjisf.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.9152youxi.cn/Article/details/gtjsseycfq.html

PHP:  // 递归实现，或用 usort
来源：http://dali.sysykeji.top/Article/details/gthfnkseen.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.chenlongwang.top/Article/details/gtgqvmwvaw.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.daria6918.cn/Article/details/gtntvzpszv.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtodidluez.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.nwbrower.top/Article/details/gtvdknhbwl.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.aibaodan.cn/Article/details/gtwajrtbii.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.yongpay.top/Article/details/gtqetrddod.html

[N04] 斐波那契数列
来源：http://dali.aizwys.cn/Article/details/gtytpumiam.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.shangyingyoupin.top/Article/details/gtvuirqdrj.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.havefunace.top/Article/details/gttlwzcmhf.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.nanxinkj.top/Article/details/gtlfoybimt.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.hywenlv.cn/Article/details/gtxqpegpyh.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.meibo888.top/Article/details/gtbnwrcrma.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.jyoumei.cn/Article/details/gtoexkwxia.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.yuanzhike.top/Article/details/gtqfcblftq.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.haohaochexian.top/Article/details/gtfvvstota.html

[N05] 最大公约数
来源：http://dali.nanxinkj.top/Article/details/gtisrrhfmo.html

Py:   math.gcd(a, b)
来源：http://dali.c1oappe.top/Article/details/gtsnrhdtgg.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.redwolf501.top/Article/details/gtyosvvuuy.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hywenlv.cn/Article/details/gtkurpgnph.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yonumen.top/Article/details/gttfylnfqf.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.gzhubu.top/Article/details/gtismtjjhj.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.birdmap.top/Article/details/gtyptirhxc.html

Ruby: a.gcd(b)
来源：http://dali.snrcjt.cn/Article/details/gtsbstkpbz.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.dashuyun.cn/Article/details/gtdbsvuxto.html

[N06] 判断回文字符串
来源：http://dali.ppjwa.cn/Article/details/gtirasklkz.html

Py:   s == s[::-1]
来源：http://dali.iojbl.cn/Article/details/gtatlrtdxm.html

PHP:  $s === strrev($s);
来源：http://dali.bjfxy.top/Article/details/gtfoagerye.html

JS:   s === [...s].reverse().join("")
来源：http://dali.meibo888.top/Article/details/gtpaplappv.html

TS:   s === [...s].reverse().join("")
来源：http://dali.bjfxy.top/Article/details/gtiltscppk.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.cheryme.top/Article/details/gtejkugtdx.html

Go:   // 双指针从两端比较
来源：http://dali.guannengcc.top/Article/details/gtlkiualji.html

Ruby: s == s.reverse
来源：http://dali.ydzc1.top/Article/details/gtidhpujzk.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.dashuyun.cn/Article/details/gtsrecsisr.html

[N07] 两数之和（返回下标）
来源：http://dali.dashuyun.cn/Article/details/gtbfwbphss.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdaignhsm.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.cucudq.cn/Article/details/gtuwjybqae.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhengqikj.top/Article/details/gtqtfgrzmd.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gtpnurgqqi.html

Java: // 手写 HashMap
来源：http://dali.ppjwa.cn/Article/details/gtmnobklph.html

Go:   // 手写 map[int]int
来源：http://dali.aizwys.cn/Article/details/gtlpsviqgo.html

Ruby: // 手写 Hash
来源：http://dali.hammf.cn/Article/details/gtcsbuhnyx.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.feifeiyinyue.top/Article/details/gtrkyeusls.html

[N08] 生成全排列
来源：http://dali.fzhhl.top/Article/details/gtasnvkbbf.html

Py:   itertools.permutations(arr)
来源：http://dali.vqdsnc.cn/Article/details/gtlqyrvska.html

PHP:  // 手写递归交换
来源：http://dali.cdnleiting.top/Article/details/gttzowxein.html

JS:   // 手写回溯递归
来源：http://dali.zhixingplan.top/Article/details/gtulhzezxo.html

TS:   // 手写回溯递归
来源：http://dali.yuanzhike.top/Article/details/gtyzmzveip.html

Java: // 手写回溯递归
来源：http://dali.yj202588.top/Article/details/gtaagnbzoj.html

Go:   // 手写回溯递归
来源：http://dali.zhiwuduotai.top/Article/details/gttadkxnbd.html

Ruby: arr.permutation.to_a
来源：http://dali.iojbl.cn/Article/details/gtygepwwdd.html

C#:   // 手写回溯递归
来源：http://dali.shzxlz.cn/Article/details/gtezdvfhmu.html

[N09] 栈与队列
来源：http://dali.chenjidiqi.icu/Article/details/gtanuedpqh.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.316326.xyz/Article/details/gtvptyvjbv.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.gaohongyu789.top/Article/details/gtnenjlaxd.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.shzxlz.cn/Article/details/gtzxgwfgum.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.ywan-chungtsiang.top/Article/details/gtavtrkpeq.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.haohaochexian.top/Article/details/gtfcijzifm.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.mhx1999.top/Article/details/gtpqpxqmdy.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.fengsongda.top/Article/details/gtytrdliaj.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.jinghuilouyu.cn/Article/details/gtnfaltjkw.html

[N10] 链表节点定义
来源：http://dali.xylfe.cn/Article/details/gtkgvisjzd.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.cqqwz.cn/Article/details/gteqoddjks.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.dashuyun.cn/Article/details/gtgkbgddne.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.0kj1m.cn/Article/details/gtyiuxxkuq.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.yuanzhike.top/Article/details/gtmplerkpf.html

Java: class Node { int v; Node next; }
来源：http://dali.jyoumei.cn/Article/details/gtccsbfjtb.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.xuetiantiany.cn/Article/details/gtfbeclgue.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.fengsongda.top/Article/details/gtzpumdjim.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.316326.xyz/Article/details/gtbihjsgxj.html

[N11] 二叉树中序遍历
来源：http://dali.fengsongda.top/Article/details/gtifddgrcq.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zycfv.cn/Article/details/gthrwbiccw.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gtgzwlhgts.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.meibo888.top/Article/details/gtmmpxxitd.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.redwolf501.top/Article/details/gtdudmvqtc.html

Java: // 手写递归
来源：http://dali.yj20258888.top/Article/details/gtlhujfued.html

Go:   // 手写递归
来源：http://dali.cdnleiting.top/Article/details/gtyucuxchn.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.cqqwz.cn/Article/details/gtdrddveew.html

C#:   // 手写递归
来源：http://dali.zhoulong.xyz/Article/details/gtdczrogip.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.jianghu66.top/Article/details/gtuvfvumqb.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhongyouzk.top/Article/details/gtuswpkdgk.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.snrcjt.cn/Article/details/gtqzgnmzpt.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jqgufenzy.top/Article/details/gtmfnlbbqm.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.sweek.top/Article/details/gtouvdztjd.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.hnxiangtu.top/Article/details/gtqqlkuhhk.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.guannengcc.top/Article/details/gtcilqyxvf.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.hywenlv.cn/Article/details/gtzmhivgxr.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.haohaochexian.top/Article/details/gtnwbdswwb.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtwgerazde.html

O. 并发与异步
来源：http://dali.0kj1m.cn/Article/details/gtctvyxyxx.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyexoiwuh.html

[O01] 启动一个线程
来源：http://dali.dianchejie.cn/Article/details/gtivgalywh.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.wangshuangyany.cn/Article/details/gtqfcbabbd.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gtraimeugf.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.andypj.xyz/Article/details/gtccleknus.html

TS:   // 同 JS
来源：http://dali.shanyushiyangtech.top/Article/details/gtbyloxsex.html

Java: new Thread(() -> f()).start()
来源：http://dali.snrcjt.cn/Article/details/gtisnpcfdq.html

Go:   go f()
来源：http://dali.yonumen.top/Article/details/gtjocttvqj.html

Ruby: Thread.new { f }
来源：http://dali.ivvv.top/Article/details/gttnovdtzs.html

C#:   Task.Run(() => F());
来源：http://dali.cashguo.top/Article/details/gtestkjwze.html

[O02] 使用线程池
来源：http://dali.jinqigfzy.top/Article/details/gtyutoylgu.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.hammf.cn/Article/details/gtauvvuvcn.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.shangyingyoupin.top/Article/details/gtumsetmxk.html

JS:   // worker_threads 线程池
来源：http://dali.xziqi.cn/Article/details/gtocyhopwd.html

TS:   // worker_threads 线程池
来源：http://dali.dianchejie.cn/Article/details/gtrlvppxci.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.cqqwz.cn/Article/details/gtrbdzegyd.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhengqikj.top/Article/details/gtpvbbztfo.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.xziqi.cn/Article/details/gtxxzbbmqh.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhixingplan.top/Article/details/gtrtcykduf.html

[O03] 加锁保护共享数据
来源：http://dali.shangyingyoupin.top/Article/details/gtwzfhhdwz.html

Py:   with lock: shared += 1
来源：http://dali.xuanzx.com/Article/details/gtxtzdtvei.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjpzuicnq.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.tian-w.cn/Article/details/gtvpftajzh.html

TS:   // 同 JS
来源：http://dali.zhengqikj.top/Article/details/gtxollnyxe.html

Java: synchronized (this) { shared++; }
来源：http://dali.gogol.net.cn/Article/details/gtwuygposo.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.kuanghao11.cn/Article/details/gtuupsrunt.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.hywenlv.cn/Article/details/gtewppvexq.html

C#:   lock (gate) { shared++; }
来源：http://dali.yj20258888.top/Article/details/gtvltvdzgn.html

[O04] 定义异步函数并等待
来源：http://dali.hnqzz.top/Article/details/gtqmwyrizr.html

Py:   async def f():⏎    await g()
来源：http://dali.chenzaomai.com/Article/details/gtbgwdqycy.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.sxryk.cn/Article/details/gtqthwlhjj.html

JS:   async function f() { await g(); }
来源：http://dali.zhoulong.xyz/Article/details/gtqwockyoo.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.ydzc1.top/Article/details/gteedesyzp.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtljuzxlkk.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.aizwys.cn/Article/details/gtfrsfmawe.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.hnqzz.top/Article/details/gttqhoqrgu.html

C#:   async Task F() { await G(); }
来源：http://dali.hongshengwenyu.top/Article/details/gtqjecuioa.html

[O05] 并发执行并等待全部完成
来源：http://dali.yanxiufei.cn/Article/details/gtccpbizyl.html

Py:   asyncio.gather(*tasks)
来源：http://dali.chenlongwang.top/Article/details/gtjfsribbi.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.jiagoushi.top/Article/details/gtitbdrukk.html

JS:   await Promise.all(tasks)
来源：http://dali.jlsjyb.cn/Article/details/gtagassbsn.html

TS:   await Promise.all(tasks)
来源：http://dali.yj202588.top/Article/details/gtqbnpkzzv.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhiwuduotai.top/Article/details/gtbavicxni.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.meibo888.top/Article/details/gtkpuapneu.html

Ruby: threads.map(&:join)
来源：http://dali.jlsjyb.cn/Article/details/gtqdkvtvxc.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.sweek.top/Article/details/gtgcrkjyyj.html

[O06] 使用进程池
来源：http://dali.zdqjudy.top/Article/details/gtuuzqzpwz.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.quarkkingdee.top/Article/details/gtmnbxwfhy.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.mhx1999.top/Article/details/gtbwrcmktb.html

JS:   // child_process / cluster 模块
来源：http://dali.bjfxy.top/Article/details/gtkwfoisun.html

TS:   // child_process / cluster 模块
来源：http://dali.xylfe.cn/Article/details/gtgvocoagp.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.snrcjt.cn/Article/details/gtfnzntywy.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.gogol.net.cn/Article/details/gtwyxgcqhb.html

Ruby: // fork 块
来源：http://dali.wangshuangyany.cn/Article/details/gtadqkapbx.html

C#:   Parallel.For
来源：http://dali.0kj1m.cn/Article/details/gtziyikvbv.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtwwckiwzs.html

P. 常用工具函数
来源：http://dali.yanxiufei.cn/Article/details/gtjoylravi.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtawdbjkin.html

[P01] 生成 UUID
来源：http://dali.hywenlv.cn/Article/details/gtpxaevlid.html

Py:   str(uuid.uuid4())
来源：http://dali.svipenyu.cn/Article/details/gtoinvijcu.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.9152youxi.cn/Article/details/gtqxhknohk.html

JS:   crypto.randomUUID()
来源：http://dali.jinqigfzy.top/Article/details/gtlyjeuhfn.html

TS:   crypto.randomUUID()
来源：http://dali.daria6918.cn/Article/details/gtvkzibtuu.html

Java: UUID.randomUUID().toString()
来源：http://dali.shanyushiyangtech.top/Article/details/gtvmlkpjzn.html

Go:   // 用 github.com/google/uuid
来源：http://dali.hongshengwenyu.top/Article/details/gtmzfjfudz.html

Ruby: SecureRandom.uuid
来源：http://dali.chenzaomai.com/Article/details/gtqdijrinm.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsetijviv.html

[P02] MD5 / SHA256 摘要
来源：http://dali.fengsongda.top/Article/details/gtdihnojzx.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.yongpay.top/Article/details/gtcnbgscfu.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.nwbrower.top/Article/details/gtwknngssb.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.wangdashe.top/Article/details/gtqptgrdkd.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.cucudq.cn/Article/details/gtzjfozbur.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.gaohongyu789.top/Article/details/gteclltaos.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.ehwqpu.com/Article/details/gtsrkvtvjk.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhoulong.xyz/Article/details/gtpiijebex.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.jlsjyb.cn/Article/details/gtptfvnrmp.html

[P03] 生成短随机字符串
来源：http://dali.c1oappe.top/Article/details/gtgntjyrmu.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhoulong.xyz/Article/details/gtmlxqtfqw.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.xuetiantiany.cn/Article/details/gtrxojywud.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.chenzaomai.com/Article/details/gtyfigdbis.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.daria6918.cn/Article/details/gtahztuuhw.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.yongpay.top/Article/details/gtyalwxuca.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.jyoumei.cn/Article/details/gtloyikmel.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.xuanzx.com/Article/details/gttkpwfzdd.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.jqgufenzy.top/Article/details/gtbffpocvd.html

[P04] 求长度
来源：http://dali.birdmap.top/Article/details/gtcgifzgpc.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.nanxuanxn.top/Article/details/gtmmbmqiwz.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.c1oappe.top/Article/details/gtqodwoclg.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.gzhubu.top/Article/details/gtzyrparpi.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.kuanghao11.cn/Article/details/gttaeppnsb.html

Java: list.size();  map.size();  s.length()
来源：http://dali.andypj.xyz/Article/details/gtzeoapvmj.html

Go:   len(arr);  len(m)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtogrqjwle.html

Ruby: x.length;  x.size
来源：http://dali.jiagoushi.top/Article/details/gtmoxkuifg.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.yueranfly.top/Article/details/gthtlxovui.html

[P05] 判断两个对象内容是否相等
来源：http://dali.redwolf501.top/Article/details/gtjtvteplp.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.xuanzx.com/Article/details/gtdpdephpv.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.9152youxi.cn/Article/details/gtqkafmxbc.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.cdnleiting.top/Article/details/gtkomqrjqp.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.dianchejie.cn/Article/details/gtesftgvos.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.sweek.top/Article/details/gtnnbnpjgo.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.ybcxt.top/Article/details/gtwfkxujqh.html

Ruby: a == b
来源：http://dali.zhongyouzk.top/Article/details/gtkjyzzoez.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqekswgad.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.yvedp.cn/Article/details/gtbiboonyy.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.redwolf501.top/Article/details/gtpqxgmajq.html

PHP:  if (empty($x)) {}
来源：http://dali.bjfxy.top/Article/details/gtcekjioey.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zdqjudy.top/Article/details/gtinynpvda.html

TS:   if (x == null) {}
来源：http://dali.zhixingplan.top/Article/details/gtvjnnmtig.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.havefunace.top/Article/details/gtqdtrqfzw.html

Go:   if x == nil {}
来源：http://dali.tian-w.cn/Article/details/gtdpojkcys.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.svipenyu.cn/Article/details/gtpumynqbj.html

C#:   if (x is null) {}
来源：http://dali.pycfn.com/Article/details/gtfsfxzskm.html

[P07] 防抖与节流
来源：http://dali.dianchejie.cn/Article/details/gttnmrxrzz.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.birdmap.top/Article/details/gtkqndlpme.html

PHP:  // 手写时间戳比较
来源：http://dali.yongpay.top/Article/details/gteuflrjae.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.chenjidiqi.icu/Article/details/gtpyeeuzht.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jinqigufen.top/Article/details/gtbfrwolqm.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.jqgufenzy.top/Article/details/gtnnbuztnf.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhiwuduotai.top/Article/details/gtntbzaosc.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.xylfe.cn/Article/details/gtvxdepsjg.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.gaohongyu789.top/Article/details/gtgavpastr.html

[P08] 处理浮点精度问题
来源：http://dali.yueranfly.top/Article/details/gtecznjymx.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.tanke756.top/Article/details/gtiocmoivg.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhongyouzk.top/Article/details/gtlizpolws.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.dashuyun.cn/Article/details/gtuolqwfha.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.xylfe.cn/Article/details/gtzrdmwvem.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.ivvv.top/Article/details/gtvptdavit.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.smart0.xyz/Article/details/gtihnlpdkf.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.dashuyun.cn/Article/details/gtgrjjtdga.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbluvsmfn.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtjhdugiux.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.jianghu66.top/Article/details/gtaczvarca.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtrskzrups.html

[Q01] 创建表
来源：http://dali.jinqigfzy.top/Article/details/gtkdrpbyps.html

CREATE TABLE users (
来源：http://dali.cheryme.top/Article/details/gtocwtksrd.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yvedp.cn/Article/details/gtxrkjkjsp.html

name VARCHAR(50) NOT NULL,
来源：http://dali.wangdashe.top/Article/details/gtcdwmzcct.html

email VARCHAR(100) UNIQUE,
来源：http://dali.shanyushiyangkeji.top/Article/details/gtifncpkfz.html


<!-- 参考信息 -->