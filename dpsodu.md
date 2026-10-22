代发 wailian999

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.yj202588.top/Article/details/gtthkgfpod.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.jinqigufen.top/Article/details/gtlsvjhfrp.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.jianghu66.top/Article/details/gtvbejeyuv.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmcyrxpjz.html

[M04] 获取当前工作目录
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdsvouqow.html

Py:   os.getcwd()
来源：http://dali.guannengcc.top/Article/details/gtndhgjoba.html

PHP:  getcwd();
来源：http://dali.yongpay.top/Article/details/gtwhadsrab.html

JS:   process.cwd()
来源：http://dali.yongpay.top/Article/details/gtskvsvvrp.html

TS:   process.cwd()
来源：http://dali.zycfv.cn/Article/details/gtkpqcdfor.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.chenjidiqi.icu/Article/details/gtebtjzouk.html

Go:   os.Getwd()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlosibhgc.html

Ruby: Dir.pwd
来源：http://dali.xylfe.cn/Article/details/gtpgedtira.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.shanyushiyangtech.top/Article/details/gtzyvwobpi.html

[M05] 设置退出码
来源：http://dali.jqgfzy.top/Article/details/gtozytdfyp.html

Py:   sys.exit(1)
来源：http://dali.shanyushiyangtech.top/Article/details/gtkoodmxsq.html

PHP:  exit(1);
来源：http://dali.guowangkeji.top/Article/details/gtxeakohoe.html

JS:   process.exit(1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtymnzeovc.html

TS:   process.exit(1)
来源：http://dali.hammf.cn/Article/details/gtdhdayxwc.html

Java: System.exit(1)
来源：http://dali.yj202588.top/Article/details/gtljdpegul.html

Go:   os.Exit(1)
来源：http://dali.jqgfzy.top/Article/details/gtdsptuoqx.html

Ruby: exit 1
来源：http://dali.cqqwz.cn/Article/details/gtwvnivmro.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.fzhhl.top/Article/details/gtsyjzbufh.html

[M06] 向标准错误输出
来源：http://dali.mhx1999.top/Article/details/gtiisvpvru.html

Py:   print("err", file=sys.stderr)
来源：http://dali.hammf.cn/Article/details/gtcjoxhdbw.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.hysaishi.cn/Article/details/gtkdavhupi.html

JS:   console.error("err")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxmkcvsns.html

TS:   console.error("err")
来源：http://dali.meibo888.top/Article/details/gtuixvqqwb.html

Java: System.err.println("err")
来源：http://dali.bjfxy.top/Article/details/gtapmcqnqk.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlgybzvby.html

Ruby: warn "err"
来源：http://dali.zhiwuduotai.top/Article/details/gtegxgvcif.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlkxastcy.html

[M07] 判断是否为主入口
来源：http://dali.shangyingyoupin.top/Article/details/gtpulgaiba.html

Py:   if __name__ == "__main__":
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvglsqybh.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.cqqwz.cn/Article/details/gtiyovcbhl.html

JS:   require.main === module
来源：http://dali.nanxuanxn.top/Article/details/gtwvhfkxrx.html

TS:   require.main === module
来源：http://dali.kuanghao11.cn/Article/details/gtqaomkhkx.html

Java: public static void main(String[] args)
来源：http://dali.hfpthk.cn/Article/details/gtymnwdnyr.html

Go:   func main()
来源：http://dali.dashuyun.cn/Article/details/gtvalgqyle.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.vqdsnc.cn/Article/details/gtsmrhmsol.html

C#:   static void Main(string[] args)
来源：http://dali.hnxiangtu.top/Article/details/gtdzgggogz.html

[M08] 获取系统与运行时信息
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcyjwvnlg.html

Py:   platform.system();  platform.python_version()
来源：http://dali.ydzc1.top/Article/details/gtgxadjxof.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.mhx1999.top/Article/details/gtaxavgorl.html

JS:   process.platform;  process.version
来源：http://dali.jinqigfzy.top/Article/details/gtpndzlljx.html

TS:   process.platform;  process.version
来源：http://dali.jinghuilouyu.cn/Article/details/gtgegqtoai.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.nanxinkj.top/Article/details/gtqqzygyvi.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhiwuduotai.top/Article/details/gtcmutvgef.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.yangfankeji.com/Article/details/gtnflfbnve.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.ivvv.top/Article/details/gttjpecjab.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtmremcwax.html

N. 数据结构与算法
来源：http://dali.tianlin.xyz/Article/details/gtipkihiyf.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtcczqeyun.html

[N01] 二分查找（有序数组）
来源：http://dali.hysaishi.cn/Article/details/gtseamicqx.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.hywenlv.cn/Article/details/gtrzilvixk.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.mhx1999.top/Article/details/gtzmjdizga.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.pengpengdd.cyou/Article/details/gthyitymnj.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.smart0.xyz/Article/details/gtqwltpzlt.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.guannengcc.top/Article/details/gtlnjetqup.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.cdnleiting.top/Article/details/gtzpeaeyqw.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.shanyushiyangtech.top/Article/details/gthgujcept.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.tanke756.top/Article/details/gtzurifqcf.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.9152youxi.cn/Article/details/gtbgfxcuqj.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.hfpthk.cn/Article/details/gtlaemfnvh.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.birdmap.top/Article/details/gtebunywmq.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.daria6918.cn/Article/details/gtwkjhltcp.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yanxiufei.cn/Article/details/gtkjkjzdqu.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.gzhubu.top/Article/details/gtyoocfuqr.html

Go:   slices.Sort(arr)
来源：http://dali.dashuyun.cn/Article/details/gtmrbhqvpb.html

Ruby: arr.sort
来源：http://dali.chenjidiqi.icu/Article/details/gtauviqgrx.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.guannengcc.top/Article/details/gtdhujubtr.html

[N03] 快速排序（分治示例）
来源：http://dali.tianlin.xyz/Article/details/gtxracpfyw.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.pengpengdd.cyou/Article/details/gttrvdfudg.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhaomingkeji.xyz/Article/details/gttlbkrrau.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.mhx1999.top/Article/details/gtfkiipwov.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.meibo888.top/Article/details/gtimmhxscl.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.hywenlv.cn/Article/details/gtlkznvmhl.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.ybcxt.top/Article/details/gtiyvlwopc.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.0kj1m.cn/Article/details/gtfckocqev.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlgjemnxe.html

[N04] 斐波那契数列
来源：http://dali.wangdashe.top/Article/details/gtyzchlxpq.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.daria6918.cn/Article/details/gtlyymjoqz.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.havefunace.top/Article/details/gtmnzcpjyd.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yj20258888.top/Article/details/gtxidzbvju.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yanxiufei.cn/Article/details/gtgzlzrmid.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.yanxiufei.cn/Article/details/gtlcwcbkvs.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.kuanghao11.cn/Article/details/gtkbqfkdsn.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrzmpuvlv.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhoulong.xyz/Article/details/gtwvekkdtd.html

[N05] 最大公约数
来源：http://dali.nwbrower.top/Article/details/gtxmrglqmf.html

Py:   math.gcd(a, b)
来源：http://dali.zhiwuduotai.top/Article/details/gtnbcnuojq.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.tianlin.xyz/Article/details/gtpamkjnla.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yuanzhike.top/Article/details/gtauxldfgy.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gtwwncsyad.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.gaohongyu789.top/Article/details/gtonrygxha.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.chenlongwang.top/Article/details/gtnsdwsxra.html

Ruby: a.gcd(b)
来源：http://dali.ehwqpu.com/Article/details/gtacelmrxo.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.chenzaomai.com/Article/details/gtnzgaufae.html

[N06] 判断回文字符串
来源：http://dali.cheryme.top/Article/details/gtbbprtonq.html

Py:   s == s[::-1]
来源：http://dali.wangshuangyany.cn/Article/details/gtlrnlenyn.html

PHP:  $s === strrev($s);
来源：http://dali.chenzaomai.com/Article/details/gtclchjnpb.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhixingplan.top/Article/details/gtpcwycsmn.html

TS:   s === [...s].reverse().join("")
来源：http://dali.pycfn.com/Article/details/gtnwwvhcfq.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.dianchejie.cn/Article/details/gtexoyuheq.html

Go:   // 双指针从两端比较
来源：http://dali.jinqigufen.top/Article/details/gtwgqjyhrg.html

Ruby: s == s.reverse
来源：http://dali.316326.xyz/Article/details/gthkzixvnf.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.sufxvd.cn/Article/details/gtrkezlldu.html

[N07] 两数之和（返回下标）
来源：http://dali.xziqi.cn/Article/details/gtxkqdgsmx.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.ivvv.top/Article/details/gtikqqjnda.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.cqqwz.cn/Article/details/gtzpaxihke.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.ehwqpu.com/Article/details/gtusiumann.html

TS:   // 手写 Map<string, number>
来源：http://dali.feifeiyinyue.top/Article/details/gtdxwkagii.html

Java: // 手写 HashMap
来源：http://dali.feifeiyinyue.top/Article/details/gthgeunpuj.html

Go:   // 手写 map[int]int
来源：http://dali.hnqzz.top/Article/details/gtqqkfkalb.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gtytirlqjm.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.gaohongyu789.top/Article/details/gtyqvlqgux.html

[N08] 生成全排列
来源：http://dali.chenjidiqi.icu/Article/details/gtagyxtapi.html

Py:   itertools.permutations(arr)
来源：http://dali.birdmap.top/Article/details/gtkfotmweq.html

PHP:  // 手写递归交换
来源：http://dali.0kj1m.cn/Article/details/gtlljgjsfw.html

JS:   // 手写回溯递归
来源：http://dali.xylfe.cn/Article/details/gtxmhjtagt.html

TS:   // 手写回溯递归
来源：http://dali.gaohongyu789.top/Article/details/gtxxzbeust.html

Java: // 手写回溯递归
来源：http://dali.cdnleiting.top/Article/details/gtkhhyhjsn.html

Go:   // 手写回溯递归
来源：http://dali.pycfn.com/Article/details/gtillbutez.html

Ruby: arr.permutation.to_a
来源：http://dali.yonumen.top/Article/details/gtluosimkz.html

C#:   // 手写回溯递归
来源：http://dali.zhiwuduotai.top/Article/details/gtgaywjbcp.html

[N09] 栈与队列
来源：http://dali.jianghu66.top/Article/details/gtrvrlnhhh.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.jinqigufen.top/Article/details/gtmuculnob.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.xylfe.cn/Article/details/gtofyesdzo.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.xinyue.icu/Article/details/gtncubokxc.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhixingplan.top/Article/details/gtngurazfe.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.xziqi.cn/Article/details/gtfclzgzpi.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.chenjidiqi.icu/Article/details/gtxhgamxey.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.jinqigfzy.top/Article/details/gtiqbxoour.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.c1oappe.top/Article/details/gtducbltho.html

[N10] 链表节点定义
来源：http://dali.gogol.net.cn/Article/details/gtpvjlchgk.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.haohaochexian.top/Article/details/gtyvjbbwhd.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.chenjidiqi.icu/Article/details/gtmwjmpajj.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.gogol.net.cn/Article/details/gtfwqdkvct.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.cashguo.top/Article/details/gtykandpsf.html

Java: class Node { int v; Node next; }
来源：http://dali.shzxlz.cn/Article/details/gteupzrasc.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.chenjidiqi.icu/Article/details/gtbqsflwlw.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.daxiang520.top/Article/details/gtwkiqbxri.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.meibo888.top/Article/details/gtvwapskpi.html

[N11] 二叉树中序遍历
来源：http://dali.chenzaomai.com/Article/details/gtzharihgo.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.jinqigfzy.top/Article/details/gtlgtzkixd.html

PHP:  // 手写递归函数
来源：http://dali.sxryk.cn/Article/details/gtvnjletcw.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.cqqwz.cn/Article/details/gtdoaljtby.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhoulong.xyz/Article/details/gtznqqebfs.html

Java: // 手写递归
来源：http://dali.jinghuilouyu.cn/Article/details/gtvksqazsl.html

Go:   // 手写递归
来源：http://dali.jqgufenzy.top/Article/details/gtizculjca.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.chenjidiqi.icu/Article/details/gthgtfpsos.html

C#:   // 手写递归
来源：http://dali.yj20258888.top/Article/details/gtqrmteulk.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.xuetiantiany.cn/Article/details/gttazpuima.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.hywenlv.cn/Article/details/gtxfttzifn.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.cucudq.cn/Article/details/gtfaksanbb.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yanxiufei.cn/Article/details/gtpiyinlvq.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.andypj.xyz/Article/details/gtncxzgdjc.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvpizqiif.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhoulong.xyz/Article/details/gtrqxwhzzq.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.xuetiantiany.cn/Article/details/gtmfffovnj.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yonumen.top/Article/details/gtjglbfyvy.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtxxtlbofg.html

O. 并发与异步
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxtzuswke.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtdgnifbea.html

[O01] 启动一个线程
来源：http://dali.snrcjt.cn/Article/details/gttgotvjhc.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.yongpay.top/Article/details/gthaxdactg.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.tian-w.cn/Article/details/gtgbmjkmuw.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.sufxvd.cn/Article/details/gtgkzrciar.html

TS:   // 同 JS
来源：http://dali.xylfe.cn/Article/details/gtujppglvk.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhongyouzk.top/Article/details/gthvdgvbpc.html

Go:   go f()
来源：http://dali.gogol.net.cn/Article/details/gtmlslkrqx.html

Ruby: Thread.new { f }
来源：http://dali.jqgfzy.top/Article/details/gtjepwluhd.html

C#:   Task.Run(() => F());
来源：http://dali.aizwys.cn/Article/details/gtcmivijhb.html

[O02] 使用线程池
来源：http://dali.chenzaomai.com/Article/details/gtbjonlgax.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.jlsjyb.cn/Article/details/gtbdvbuqfm.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.dashuyun.cn/Article/details/gtjrlkpoyh.html

JS:   // worker_threads 线程池
来源：http://dali.daxiang520.top/Article/details/gtvnrbolqb.html

TS:   // worker_threads 线程池
来源：http://dali.ehwqpu.com/Article/details/gtquznvfxt.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.hongshengwenyu.top/Article/details/gtvtwnxksw.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.tianlin.xyz/Article/details/gtxgwxarzs.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.jinyuanbaomall.cn/Article/details/gtijgoqapr.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zycfv.cn/Article/details/gtxghnsaeo.html

[O03] 加锁保护共享数据
来源：http://dali.316326.xyz/Article/details/gtfbaihbck.html

Py:   with lock: shared += 1
来源：http://dali.chenjidiqi.icu/Article/details/gtdaeknfkt.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.hnxiangtu.top/Article/details/gttlxxdhdi.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.vqdsnc.cn/Article/details/gtbabkzpuz.html

TS:   // 同 JS
来源：http://dali.ehwqpu.com/Article/details/gtcdarsthf.html

Java: synchronized (this) { shared++; }
来源：http://dali.yvedp.cn/Article/details/gtcamtwggb.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.cqqwz.cn/Article/details/gtdyxjjojf.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.chenzaomai.com/Article/details/gtiwlvostl.html

C#:   lock (gate) { shared++; }
来源：http://dali.vqdsnc.cn/Article/details/gtuywcvhzt.html

[O04] 定义异步函数并等待
来源：http://dali.meibo888.top/Article/details/gtsrkrryei.html

Py:   async def f():⏎    await g()
来源：http://dali.xinyue.icu/Article/details/gtkbubcftb.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.iojbl.cn/Article/details/gtwqxwqeou.html

JS:   async function f() { await g(); }
来源：http://dali.zycfv.cn/Article/details/gthvgqwgmf.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gteilcimmk.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.jlsjyb.cn/Article/details/gttspxljdw.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.vqdsnc.cn/Article/details/gtustgiknl.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.cashguo.top/Article/details/gtajbmmoog.html

C#:   async Task F() { await G(); }
来源：http://dali.wangdashe.top/Article/details/gtrxecznwp.html

[O05] 并发执行并等待全部完成
来源：http://dali.yj20258888.top/Article/details/gtnjbtkyyb.html

Py:   asyncio.gather(*tasks)
来源：http://dali.xuetiantiany.cn/Article/details/gtbnzqpeak.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkwfjwehy.html

JS:   await Promise.all(tasks)
来源：http://dali.pengpengdd.cyou/Article/details/gtgdelkntq.html

TS:   await Promise.all(tasks)
来源：http://dali.wangshuangyany.cn/Article/details/gtecxmtiji.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.daria6918.cn/Article/details/gtjhveewht.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.yuxming.cn/Article/details/gtlrsjyabs.html

Ruby: threads.map(&:join)
来源：http://dali.jqgfzy.top/Article/details/gtowguizvw.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.jinghuilouyu.cn/Article/details/gtsdywhxqh.html

[O06] 使用进程池
来源：http://dali.jinqigfzy.top/Article/details/gtrtwsbref.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.yanxiufei.cn/Article/details/gtthutmrzz.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.fengsongda.top/Article/details/gtvkrmbady.html

JS:   // child_process / cluster 模块
来源：http://dali.hfpthk.cn/Article/details/gtzewzvpyv.html

TS:   // child_process / cluster 模块
来源：http://dali.quarkkingdee.top/Article/details/gtlqwdcuet.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhixingplan.top/Article/details/gtbotpncqh.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.jinghuilouyu.cn/Article/details/gtkslbpils.html

Ruby: // fork 块
来源：http://dali.yueranfly.top/Article/details/gtupcbwauz.html

C#:   Parallel.For
来源：http://dali.dashuyun.cn/Article/details/gtdhjuncta.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtkuhsuuyd.html

P. 常用工具函数
来源：http://dali.zhixingplan.top/Article/details/gtmyrqdqbh.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtkardiezu.html

[P01] 生成 UUID
来源：http://dali.zhixingplan.top/Article/details/gtabyoedbi.html

Py:   str(uuid.uuid4())
来源：http://dali.hywenlv.cn/Article/details/gtwoxlbbct.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zycfv.cn/Article/details/gthxoeiyet.html

JS:   crypto.randomUUID()
来源：http://dali.sufxvd.cn/Article/details/gtdynxjtxn.html

TS:   crypto.randomUUID()
来源：http://dali.zhoulong.xyz/Article/details/gtmhhnxbyt.html

Java: UUID.randomUUID().toString()
来源：http://dali.mhx1999.top/Article/details/gtziuudgni.html

Go:   // 用 github.com/google/uuid
来源：http://dali.kuanghao11.cn/Article/details/gttybliqvy.html

Ruby: SecureRandom.uuid
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcdpsrmhf.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.shzxlz.cn/Article/details/gtiqxrmhil.html

[P02] MD5 / SHA256 摘要
来源：http://dali.feifeiyinyue.top/Article/details/gtsvvkpojl.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.9152youxi.cn/Article/details/gtviwvhlgw.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.yj20258.top/Article/details/gtvajfcczd.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.316326.xyz/Article/details/gtqzgmfrmy.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.meibo888.top/Article/details/gtcmddjyba.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.birdmap.top/Article/details/gtxkjuuwyd.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.kuanghao11.cn/Article/details/gtyrsbwuos.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.hfpthk.cn/Article/details/gtvrtuptpq.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.wangshuangyany.cn/Article/details/gtivvtfavd.html

[P03] 生成短随机字符串
来源：http://dali.daxiang520.top/Article/details/gtruviykox.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.nwbrower.top/Article/details/gtkqebcuqj.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.feifeiyinyue.top/Article/details/gtdousfiyg.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jlsjyb.cn/Article/details/gtyadttukl.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwjctzgmv.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.aizwys.cn/Article/details/gtdsdtpcyh.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.jqgufenzy.top/Article/details/gtmlbfswoy.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.shangyingyoupin.top/Article/details/gtielfefxw.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.xylfe.cn/Article/details/gtuplajuci.html

[P04] 求长度
来源：http://dali.tianlin.xyz/Article/details/gthsqagyna.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.andypj.xyz/Article/details/gtfcmgjmxv.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.snrcjt.cn/Article/details/gtwfqdvxpc.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.cheryme.top/Article/details/gtzsbhhdtv.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.xuetiantiany.cn/Article/details/gtckiivmoy.html

Java: list.size();  map.size();  s.length()
来源：http://dali.guowangkeji.top/Article/details/gthauckxan.html

Go:   len(arr);  len(m)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtejfcllyp.html

Ruby: x.length;  x.size
来源：http://dali.zhongyouzk.top/Article/details/gtyggebzae.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhengqikj.top/Article/details/gtfesxjkmb.html

[P05] 判断两个对象内容是否相等
来源：http://dali.iojbl.cn/Article/details/gtgzbbrmgh.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.gotoacloud.top/Article/details/gtmlzelgif.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.shangyingyoupin.top/Article/details/gtsiiccubf.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlzygudyi.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.daria6918.cn/Article/details/gtxxnbubxt.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.meibo888.top/Article/details/gtjiqeccqn.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.vqdsnc.cn/Article/details/gtfofqeslz.html

Ruby: a == b
来源：http://dali.snrcjt.cn/Article/details/gtzvvjjqlq.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gtdqbqdzhb.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.gaohongyu789.top/Article/details/gtfdpabuln.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhengqikj.top/Article/details/gtszqqsvtu.html

PHP:  if (empty($x)) {}
来源：http://dali.cucudq.cn/Article/details/gtmxfdbqfh.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.xuanzx.com/Article/details/gtkufwmbzx.html

TS:   if (x == null) {}
来源：http://dali.yj20258.top/Article/details/gttnmafadv.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.chenzaomai.com/Article/details/gtofommwgo.html

Go:   if x == nil {}
来源：http://dali.ehwqpu.com/Article/details/gtetzvabnv.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.ybcxt.top/Article/details/gtjjpcsoba.html

C#:   if (x is null) {}
来源：http://dali.jlsjyb.cn/Article/details/gtcdwxgxsw.html

[P07] 防抖与节流
来源：http://dali.hysaishi.cn/Article/details/gtmtaglpfz.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhoulong.xyz/Article/details/gtvhaxqtlj.html

PHP:  // 手写时间戳比较
来源：http://dali.nanxinkj.top/Article/details/gtjoiwrmgs.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.sxryk.cn/Article/details/gthkcgshlk.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yanxiufei.cn/Article/details/gtnrpwrjbo.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.yangfankeji.com/Article/details/gtywfcobcj.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.gzhubu.top/Article/details/gtfxclzniq.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhixingplan.top/Article/details/gtjnccbarg.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.xinyue.icu/Article/details/gtinjhszra.html

[P08] 处理浮点精度问题
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjmihwhdm.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhixingplan.top/Article/details/gtzswfrupw.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.gaohongyu789.top/Article/details/gtwohrtgdj.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.dianchejie.cn/Article/details/gtousopmbm.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.birdmap.top/Article/details/gtjiwasutz.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.yuxming.cn/Article/details/gtuqjlkixw.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.nanxinkj.top/Article/details/gtbqcotvcl.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.quarkkingdee.top/Article/details/gtajxeopik.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.svipenyu.cn/Article/details/gtwocdmdtr.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtezvkmmou.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.aibaodan.cn/Article/details/gteblwqwdt.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtubyuegsg.html

[Q01] 创建表
来源：http://dali.ywan-chungtsiang.top/Article/details/gtelmunqed.html

CREATE TABLE users (
来源：http://dali.yj20258.top/Article/details/gthfcitodp.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.shangyingyoupin.top/Article/details/gtvkaerswr.html

name VARCHAR(50) NOT NULL,
来源：http://dali.gogol.net.cn/Article/details/gtziwmygjp.html

email VARCHAR(100) UNIQUE,
来源：http://dali.cheryme.top/Article/details/gtcdisqabp.html


<!-- 参考信息 -->