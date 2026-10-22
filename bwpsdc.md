代发 wailian999

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2eqqjqbcn.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2qtfymnam.html

Py:   sys.argv[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2cjkrgshf.html

PHP:  $argv;  $argc;
来源：http://dali.zhijiandao.cn/Article/details/gt2ialwtdqm.html

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2pworpuxa.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ktolprcv.html

Java: args 数组（main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2yuymwept.html

Go:   os.Args[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2ysompock.html

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gt2tbjhevjo.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2klurscqg.html

[M02] 读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2uggpjjnf.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2wpokcvkl.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2ulstevqa.html

JS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2ljmnljau.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2dwxzpuxx.html

Java: System.getenv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2axvfdktt.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2qsaratgm.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gt2iyyeimgc.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2xduuhijz.html

[M03] 执行外部命令
来源：http://dali.zhijiandao.cn/Article/details/gt2afdtpttm.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2axaudrjk.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gt2uuaipiav.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2jevtfnwh.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2xxkmhuhn.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gt2stwivyis.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gt2yyuzquhj.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gt2rxuqntky.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gt2uzfgsrmz.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2mndquapr.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2iotercho.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2cgviktrh.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2xrmoeupr.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2fecvqjuf.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2hhivnivf.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2xffcwknd.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2qkyktmkw.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2czbhajed.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2gkeshump.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2gpqrhxvf.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2lcaltwyk.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2kfzwtkok.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2hpzoqfqy.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2cswivexd.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2cqsbgdkq.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2diszxqmj.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2tfikpcgv.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2ixvvcwnu.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2eckccnps.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2upygiqej.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2jiimkzfy.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2fsxbmdhw.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2gmpxswvx.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2chemlgrp.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2giylhykl.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2hrjeelkm.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2klytooaq.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2pibnjlnq.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2cfcdomam.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2dqeiqxfx.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2xbsyiwkd.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2zmwkjvic.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2imaianpm.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2tennjodf.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2bxmnxdzu.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2bybpaaup.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2idqethih.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2wkyclsju.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2pclduuji.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2vxeojarr.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2ysnzsjqr.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2qzjrnwgt.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2mpuamdgw.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2qqtgzlmf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xgqjogin.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2yftoxwtl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cbhwdeui.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2frdhvqrv.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2hlqiljkn.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2mkabxvfw.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2maidiijj.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2zokweutw.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2blgjxwyc.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2clfdpvxp.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2wwhdcmbo.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2fmvuqush.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2upvhqsra.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2gykfmkvb.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2frsmavqw.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2krosrmtj.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ikjbucnb.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2uhgmbxhp.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2lagucjkc.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2ntcgpjyk.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2gzbxpktc.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2pybqpiwd.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2blzumyww.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2nbrizpfw.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2woqyxkta.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2ctllimvs.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2dqvmexrp.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2frfzopns.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2duxtxdqn.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2zefqdlfz.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2hffxohrq.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2awtrbeuy.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kshapnoi.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2rcdvgomj.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2pbqliirr.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2boydpgcg.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ymfchvlk.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2hyyyfmlc.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2dcqvkebs.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2ajnoqygx.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2lakpcvjt.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ltabccho.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qybnpsuk.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vwuhhkit.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2ltooqsxb.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2pjdclkzq.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2evnovxha.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ldtkzszu.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2adsgmivo.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2ykkmsgxg.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2wlxzijzb.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2kkfesusw.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2kdghtjws.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2cjrmsxin.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2zhllcagx.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2gvlsuors.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2xbcrxrso.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2znescnjb.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2oixrnivg.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2kjifhotu.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2upbuxkmf.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2oxwjddoe.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2wzvibweu.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2bhjjfwkb.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2owveumga.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2xzixlyun.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2uytkaepb.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2oaucltaq.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2ovbhszew.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2vyruytpj.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2qttzcqdl.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2bwlwvibn.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2khhwribz.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2nyquvlfh.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2rlhcbosf.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2wcmijias.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2fsaynrto.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2vpeyukoh.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2phoesvis.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2stdghbuz.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2vjlvmgno.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2bwqyayux.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ofpsertx.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2mqlxcwum.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2auryftig.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2bnqofddu.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nqgpabwq.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2yaheoaym.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2khqshwgb.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bllmtbas.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2qoulxsei.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2prwjnzug.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nhinqvfp.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2cxddgial.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2zajcofbp.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ddrmswpb.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2dsiwoubv.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2onldvkwo.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2xorziftm.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2qtyjcmhx.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2zuxxraqp.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2duzvhgnq.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2gfrczmbe.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2nqncrhdu.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2akrwmjdd.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2vefnngnn.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2pkugueit.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2ypdigwtl.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2xjairvaj.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2arwylxeu.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2rfytjxys.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2muwkuszz.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2fktjfnek.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bfnuoahb.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2ccoxanbt.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2kvjojafp.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2nnxjttkj.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2htytqiav.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2runlxbhh.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2vjymgupu.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2ouyprvzv.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2mywiytur.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2czqiphuw.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2qnfecuoj.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2xuhgjxtf.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2apbqdnbd.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2qvcblyvt.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2onvzvtma.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2dpajhgii.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2gclplotj.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2guzckjed.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2gqddnfyn.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2zvnruynw.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2lcydbpjx.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2brqmgoxf.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2jdxlfudx.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2bqolejnm.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pmmswdoe.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2tcwggijl.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2xnwdhbtw.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xmnpoxbu.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2ebnbttjw.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2iehnglvq.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2bgltjebp.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bunsjrue.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2desrdhkc.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2yoyujxyk.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2rnkoihrq.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2bpicvjzm.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wqgfhzrr.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2lghnuwig.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2vrlnvqon.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2lzzhrrrc.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2ktnyzfbj.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2bomlxkpj.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2cvosqkpf.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2zonxpdkh.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2ijsewghb.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2nhaujapi.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2dtwjntgj.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2xfzgtubq.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ugqavvhd.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2xvppzegy.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2mavbhwqi.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2msaooolv.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2iehdovvc.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2fxdcwrmy.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2aybjtfyq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dhodejqi.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2csxkonpo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lvrmbpkl.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2clfzmbtj.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2uqoqbqzq.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2mtniuvbx.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2nydiahcx.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2gdvvttyk.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2kqhjpkub.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2dewfphhp.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2yxpfqsds.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2rvltxopk.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2putpgrbo.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2qiovhvjn.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2xpvjtaoo.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2eojmnazr.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2tsnkovbn.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2isgnxtvu.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2dsxbbvoz.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2laectyae.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2zmwqilfe.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2wfayhyiz.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2cykezqbe.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2ckkvdpiq.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2napvovnl.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2jolvnukb.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2nzufajie.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2lpxhbpec.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2zdqsjeor.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2dzitrazh.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2agzdeshm.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2qvqwhozx.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2jglaghiw.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2nytgogww.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2rtcfwcsj.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2pdossmux.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2nvghqtwy.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2lfspctjm.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2bqhrlhqz.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2frqkqxjq.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2gofahccb.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2hgrpxmgn.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2rcyhyacn.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2njnutkds.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2kaxyqjbs.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2qixcihlo.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2xkswfnpe.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2eemfwhzh.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2uzmgcofr.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2xxcuymxv.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ciehhkgn.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2yruhuhdc.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2plchbjno.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2slxipguc.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lkeobogq.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2txwpoqbl.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jumcajfb.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2lrcgqvqe.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2euatocjk.html


<!-- 参考信息 -->