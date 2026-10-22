代发 wailian999

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2tmrsykbt.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gt2gitwzrtk.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2mbtfsyqj.html

[M03] 执行外部命令
来源：http://dali.zhijiandao.cn/Article/details/gt2vchxwfqx.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2fbfgwihc.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gt2dxfbnqwz.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2mivzuscs.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2hukzdcwu.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gt2wewasvam.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gt2drlcxuwa.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gt2gnppikol.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gt2dqeienun.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2abdlheqx.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2frufapep.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2qxaapkuj.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2wgimoflz.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2gshyzjlm.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2yyagedcp.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2mifwjtzo.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2hfyaycgn.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2cruvjatu.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2tszzcbri.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2pbyyneqd.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2qlltbhho.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2wpcosirk.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2mjtbygkb.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2singelnq.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ksggtwpv.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2dqqgxyqc.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2owqsbsim.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2duiqrgln.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2arsdkfqr.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2skzamjou.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2bwknojaj.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2fzkqfrqz.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2pojoytep.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2jdwqfzja.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2jxecuzni.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2bguqqxxa.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2vquxhnhl.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2cjxlbspq.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2vnvjlkmr.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2hosdycjl.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2fmadswcg.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2njjrvuwl.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2nfihcjjv.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2hdmdyobn.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2saaxcdqr.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2fpwyfjzy.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2dihrklot.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2ybgddnqw.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2zwiadhpn.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2joeoudow.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2kjxuzltn.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2ratusmxp.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2nyqrqpxk.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2kfkhwqdg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pruqoych.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2euexvcyk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mfkmwaie.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2tlanyiuj.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2brlcoaej.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2dzzburfl.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2jfxfhgfb.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2ovzumkzl.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2pubzdvwu.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2vxiifjch.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2hfntrmrd.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2lsykvtmv.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2doreisji.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2jtqohaxf.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2mqyjzuhq.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2qpqlqmju.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2pnkvzqye.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2rjdtrzfc.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ygecbujv.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2hxdzlunm.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2mdogkvxo.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2ttjuuvak.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2zpcgxrmz.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2bvrpojqv.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2fagffwfa.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2xlplsgct.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2dnwfspmc.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2unvoiyby.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2qbhvpxvm.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2grhnrdbq.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2bewruisa.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2pauguvhc.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ucptlzrb.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2gpeeyaat.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2raagihyp.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2yuejprne.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2uuhqjcyk.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wqykgklq.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2kcxfvduo.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2eyriwpfw.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2spaeqxqo.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2otflvgsu.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2adxoeecd.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qrndodfk.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2swkqtwyv.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2hzvvhiaa.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2rlwxllxg.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tneezhpq.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ayzaqgmk.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2brhguufy.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2unxflpxp.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2zodssuja.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2hgclhtbf.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2vqcxreyo.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2oqtochal.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2ujpcfxac.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2sxjqaczj.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2ltzycccm.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2ijnetcdr.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2bahejlnt.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2xvzyigix.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2eygzoeow.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2pwgoahcy.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2sewilzbu.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2qokmtmwv.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2hfgwfmkj.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2djwrepuf.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2vmcvmqwt.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2eqzqzice.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2bweevpng.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2jweswfcq.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2icehcmuv.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2gyafufgr.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2qxffgxih.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2gairmgke.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2zmuuadui.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2jqtuhlqf.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2gntbtjjb.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2fdtthbya.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2ctxcdclh.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2umgdwbae.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2utfphsoz.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2cwunbqaz.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2iixtmfqk.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2xlginler.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2uwvdobgz.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bazkqevc.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2jznppzan.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2ckevihka.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fycizpcg.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2ztqgfxzx.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2ksogejaw.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ifiwnndz.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2rplngsot.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2wazsxfuz.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qrtpbcpi.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2svaulrcb.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2lezuzlmx.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2nqkffdwd.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2vkjkpxsj.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2bazqerhe.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2fipvitcv.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2hvrfdjua.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2chlactiz.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2zwnhfnvp.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2rmghflvq.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2vyklvcfp.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2lrcobexu.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2fpdmaykc.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2otomhsxa.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2tkznfyoa.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bzljmvwt.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2uezrisrz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gnlaueql.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2yvmjckwm.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2spiniozd.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ukrmmqid.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2ayulfbrg.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2mcxpllzx.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2iuriezcl.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2viqzoxnp.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2ucntlggy.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2rbmvamcs.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2bnxdlmyf.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2dwinwebe.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2uamtghud.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2hecyldfq.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2mfqxiemd.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2byjxbuuv.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2ugdofadd.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2vpfpfnbe.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2tizzpbrh.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2zansnyhr.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2fsmieypm.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2mgqmmdal.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2ikosbmts.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2ynjvjnjv.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vnfjzmxh.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2kizzqhio.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2wgimkckg.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tujniqfb.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2larhupqw.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2beilmnoe.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2nlmrbcdt.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gbsigrjx.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bxpgjary.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2kejywlly.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2elbsaqhl.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2cdnkmcqy.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2llqdztze.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2qnrsdoyw.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2oburgjgr.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2twzcqpze.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2izdougzo.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2qkqwohot.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2kqecmqlj.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2ydovlvki.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2imluyfro.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2yqdivrsm.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2fqkoeyfi.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2npfbpkfq.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ydbgayok.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2dqcsbtfz.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2yglmgaid.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2xqrzqmbg.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2laswrtpw.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2qcqwzyeh.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2vclmixfd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bjvvcvxo.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zxwfubcv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qlgrvlus.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2frdvwytn.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2hiikbiyr.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2vkkxtlyj.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2cfizcwst.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2ldcfemgl.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2hlplcvms.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2lnxbulwp.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2izccyozv.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2zytuwysb.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2uikpiyak.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2ncwparwv.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2egpghahi.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2nqhgreqe.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2aonsfugy.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2rhhcvgba.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2jwrqmqun.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2hljscxqz.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2yehahuma.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ndtcthcb.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2qmjsfbxs.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2iomokkfp.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2ajxowwtw.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2ogjipmrz.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2axmptalf.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2diwilrnz.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2jzfbssek.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2xriarkcs.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2mehctvxc.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2qezvzisn.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2iigufotw.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2fgigqwbn.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2jrrrktvs.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2qyjhdduo.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2nzsysasd.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2vfzzjhsg.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2liasalls.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2fjdpjvcl.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2lrhkgcvs.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2djeoddcc.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2psuuveeo.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2taflwbri.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2rfkpkjuh.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2qvecrtva.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2lmfbvhzx.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2wjqejkre.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2lbulzlbk.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2larmvlzg.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rzonjxhe.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2uceheaqn.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jgcngbro.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gjjrbbhk.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jawsicun.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2mcpkzvlo.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2grolgwno.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2qxthixpl.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2drmkluyt.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2tixtnydl.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2rsalqcee.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2okupccek.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vacbpttr.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2rnjcgzem.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2qdholrea.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2umdgmqya.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2drneukeu.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2hfdpmdmg.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2jxwkdwgx.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2dyemliqz.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2bnrojjuc.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2eqxiqwpy.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2wdlumozy.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2gyrzhone.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2kzxphlqq.html


<!-- 参考信息 -->