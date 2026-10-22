代发 wailian999

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2iaejwmqn.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ofqndtla.html

Py:   sys.argv[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2dhmznyua.html

PHP:  $argv;  $argc;
来源：http://dali.zhijiandao.cn/Article/details/gt2owdhnrjm.html

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2avwsipga.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2yhsuavai.html

Java: args 数组（main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2xmjscvhw.html

Go:   os.Args[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2nmjbacec.html

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gt2wuggvzgb.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2bztshsdj.html

[M02] 读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2rtiilacv.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2gfofilco.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2tgabeabn.html

JS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2hhwufuyp.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2ljffrfxz.html

Java: System.getenv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2qupjobor.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2knoqgzzn.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gt2xvtqugbj.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2wexgqjeb.html

[M03] 执行外部命令
来源：http://dali.zhijiandao.cn/Article/details/gt2mritqvqn.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2tlwkcsew.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gt2fqsqrrhp.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2spqkvplh.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2cedlobov.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gt2lspvdpdx.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gt2fqfbrewv.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gt2clkojbbc.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gt2bhigihrz.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2tewcpboe.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2jgfdglqy.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2djnhqnzx.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2jqhgmajo.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2lxyoynqz.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2ilkicbuo.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2rfolredw.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2wqzikcpo.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2nxaaegtn.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2mhvkjqpg.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2hggienpw.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2nxhogugy.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2zbiynyii.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2kjkdqcrl.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xnoqigsm.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2hvddwltv.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2mmpddhdh.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2jpavsyzn.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2giswtmrk.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2zgvteogg.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2eyobfhgv.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2pniixlis.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2lbflpyqo.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2xavapxvl.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2ufwegyfy.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2doickqzt.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2lwkeoant.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2lajirgdo.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2vllergef.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2xgbxrnlr.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2poxpyezf.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2vbpicnnc.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2ozcselyv.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2sxovlhds.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2vxqeokxx.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2lngopteb.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2ithuixgi.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2jbbvjnsa.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2ufglvlbq.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2pckvnmva.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2kbzlwmow.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2jljryzbf.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2qpnjfuho.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2bxgupoai.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2qbplpsyg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ghmugebw.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2divlwxmd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jciwflpo.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2ysadhoah.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ikeihnal.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2vmfowbmo.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2eugkjnxg.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2oyjnedsp.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2uiavtdwe.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2nqptosen.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2gmwcbqtv.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ulgzflzz.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2pzymweyc.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2hrhknmbh.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2fopfcxjc.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2isbzsisw.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2kgtdwhbz.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2tugbohuh.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2mbkgtwvi.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2kzhomzxs.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2iadixjjp.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2rzfskqkf.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2hmiawdpw.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2clykutza.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2sqozujyo.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2hpfrkjwk.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2vymstfyt.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2kouvuwcv.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2konxpenj.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2cjiuzgbz.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2gzhypcsh.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2qllqkqeu.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ncntdygs.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2vcokdwtz.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2crhefddt.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wuffpanh.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2axovyvlo.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2pxqjklxv.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2zlhmgkzj.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2zihdwacs.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2nkzerotz.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2srnwhzpr.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2syhczcpt.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ewzhqnkq.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2xwclasdp.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2rthumnhk.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2emxsqjhe.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ckrzrtrc.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2gbjuheqc.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2eokgrsmi.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2hrvsinjo.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2cudcncrk.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2yvjhhxke.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2rrcaimal.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2cjotwsdb.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2yfdtmzwi.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2hphlcvrs.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2rhdwmnxf.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2oqyufetj.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2wkkqfyva.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2rfucudoq.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2iiorysjj.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2olopayri.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2cxkmtcfh.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2yafwqtho.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2ihkgotlj.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2inxicqxl.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2dildsxvp.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2dcnrrerc.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2vthzcmhr.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2jvdgibrr.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2oystjzam.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2qffasiui.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2dnkwtwmq.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2kyaubmfh.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2fobhbdsl.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2niistkcc.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2cetipqid.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2vjvdbqih.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2glgtocth.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ubhtcehn.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2lueomuck.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2chiyfcjx.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2nkhyaqna.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2uakutajn.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2lohbdhon.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2znvhpvmb.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ckvgtkep.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2tyqdmnsv.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2szshmwqo.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2yrupuycv.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2htdbfksk.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dbkfnsnn.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2srhqrurj.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2alxsrmto.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2sfufljda.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2gfanzxpj.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2wyuybdaw.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2udffjyyx.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ujxfpxwx.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2stenavph.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2egvbgpir.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2xwenzcbn.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2kfxyupkl.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2gbqcqvia.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2ffabywsh.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2igiojygn.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2xdmbjuyp.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2cfviepzg.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2xhbzolds.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2uuuaogma.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2evzqvdkr.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2ugmcmdlv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2racbolyj.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2lihfbvpm.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2uksjodyd.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2nhyxlsjr.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2xjrosrks.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2kcfmzawg.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2nxgsppdv.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2ritrlorv.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2tlcegmvr.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2zibchqrq.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2arjfatmz.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2aiadtjfu.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2gtrvaicb.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2inddvmoy.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2cpeblzlj.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2bvdmjqev.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2yltdsgvu.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2wjvvqrwn.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2oawgnits.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2wkqaxtlg.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2xyxigybb.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2kjqnprod.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2uqyhhcez.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2ycvqzzfr.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2epjmccgf.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2gnbdufyh.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2itlamcgp.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jlnuxapg.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2nguvetyb.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2fejqtnri.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2oqsxvhqk.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ncwbymjr.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2acsvokjo.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2zhurqkvf.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2hwewsqqt.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2slutgykc.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2amumrtup.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2wutsmkry.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2xzheyvhf.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2nenihbep.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2naiqebrx.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2zeuwbsbg.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2zolmdbbm.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2wahubzek.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2vsdfylpm.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2jespumyj.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2rfiwqcvk.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2yjkbmwfk.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2yrojtetu.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2whulubyz.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2ykkxxilt.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2ddbjloyj.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2nwrazkrn.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2kmpnltyg.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2sgfuxcpz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gixddqkp.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lnauqvez.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hzrcscgs.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2qqhnilbd.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2hcxwkbkq.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2ltmineau.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2dqenkcqc.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2ujbnzqja.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2bmcvtyhk.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2hjbwhcmw.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2cqqahsgn.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2ktbkxvmg.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2musfephl.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2exedmfdj.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2uggjypqa.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2hnzjzemk.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2fptouhpw.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2chxkvxqz.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2mrtlgrlo.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2riucfvsf.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2bsmntarm.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2aeaglmet.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2ddftwhen.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2wojmrfkj.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2eapjzzjl.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2zeegcphe.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2hvvyfmau.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2bgnuflmg.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2cgukxzuk.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2kkrtuzsy.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2uwllqbdu.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2rxboeehj.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2lxkiinje.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2sttprdry.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2krgjtemc.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2nflwghgo.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2jfjrpzmd.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2fvmhamcc.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2cpyyruvl.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2oiouvpha.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2ewxfgzzu.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2irmcymzx.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2noyixrhz.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2dnadeniy.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2lpkrxicz.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2fpikgkrj.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2yrqperlu.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2wppzvhuu.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2hfkageof.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2ttjewvlk.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zsvcckxm.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2aaqzgfqt.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2swvwwvor.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wqefdwqb.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2glycrwxf.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2mqrzqxbe.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2brdmysna.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2ctotytut.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2bmmmprtz.html


<!-- 参考信息 -->