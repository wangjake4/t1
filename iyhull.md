代发 wailian999

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dgaezlev.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2quwlwlbi.html

Py:   sys.argv[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2ogiufjpa.html

PHP:  $argv;  $argc;
来源：http://dali.zhijiandao.cn/Article/details/gt2lggonrno.html

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2pvotkule.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2syydqusy.html

Java: args 数组（main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2yuvamesv.html

Go:   os.Args[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2kuzumymn.html

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gt2ocwrqykb.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2ybqrbtvw.html

[M02] 读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2kvhcjxuo.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2jhctvgoj.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2epvsjckv.html

JS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2bniwchxv.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2fzwyojcd.html

Java: System.getenv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2xykjhbrt.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2tpkmngjj.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gt2jqastbjz.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2flymdlzu.html

[M03] 执行外部命令
来源：http://dali.zhijiandao.cn/Article/details/gt2cnquieuh.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2ukamukcx.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gt2uvwwktix.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2gfabnhzo.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2fvljcepy.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gt2wafsusfg.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gt2rkpgaova.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gt2uiubvkne.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gt2oyavcthe.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2sdirrxbo.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2yocxwkpt.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2hhamvpzw.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2mtuphxtl.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2vxmfffrh.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2tjlmqbwy.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2puysmftm.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2uibqwghj.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2ezzlsyxi.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2yrtorpdz.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ruylwnim.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2vcmnvfph.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2kgjzhjjt.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2kkpeoudr.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2dcntzfxe.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2upzcioys.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ikyvhhxb.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2rpcngaga.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2rchgmcqp.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2piilckfe.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2gujnitqn.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2xgrxxidf.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2nqgqiexq.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2fdpeevop.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2ymetehlt.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2pnzjiufc.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2snkglaet.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2ytqvoedu.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2paroejbr.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2bzorcupu.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2qumucsgg.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2hscryrgi.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2bkeivpxm.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2ybikxzsn.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2qurlvgyw.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2tkwlgguy.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2pmcfocky.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2zarozbgy.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2okuoqlnv.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2rvumiavv.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2xbyrmjri.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2pufwjrmj.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2lyyhojez.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2yulwpcov.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2mtfzbusw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2iuuqbywg.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2odkokhaf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2skjabqkk.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2zmyshflh.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2veqnevna.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2avjousvv.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2cbnwpviy.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2rmljhjxw.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ykstrzlw.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2sjptjkij.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2jmzvkqal.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2dbssyzzo.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2oggbauhf.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2xokvwiqs.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2ndhqxfyc.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2yjrrfmql.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ppabbosu.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2kyggiajv.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2gdkbzfqj.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2blhupwiz.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2ybnlzrhq.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2bivpvulh.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2rejdxbsf.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2fxhafcwv.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2zrxcdnyz.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2ahomfpcp.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2yeiykavo.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2quspztcz.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2chpfneys.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2ipqcpmla.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2mfwdjpba.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2rkbbugdh.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mlsrzcmy.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2jbwmdwyq.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2mvlakquz.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nkfxmifw.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2czstllce.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2lbvvvgse.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2oejjxijy.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2wqirysdj.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2cpbuyfrm.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2djagpubw.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2epnszptn.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cqcuedda.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2tsmefgft.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2rbhippmw.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ordsxhbw.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fcseftya.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2dhiqchhi.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2atisltky.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2yqkmorjp.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2nemctbbc.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2jmmjjobf.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2knhrmdab.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2cybujvsm.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2fjtxcabt.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2gjtlgkuv.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2vnsygsiy.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2crmujwxv.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2rxzcmbfy.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2xrilbnfq.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2dlbztgep.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2qfoqnzek.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2xtoycovi.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2gcexqzyh.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2ouananzr.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2xbyvlutp.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2hyemabxv.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2hkyhfgty.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2sytahjwr.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2kxkeglkw.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2yhktgwzo.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2woqyrpgd.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2ksmkzfgp.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ayteftdu.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2sdftwytp.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ubkpgfac.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ztcmtojp.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2lwhtgwxg.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2gjoyfzio.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2fwwisvqt.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2eiuujoil.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2sxbnnupg.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2mdsxzvwq.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2xdrvdvss.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2vdspgrty.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xchjtktm.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2chrkbnyc.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2vuytugwu.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wmlguuaf.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2bppgowpd.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2dzhfwkxh.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ukciwsqe.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2mfjppbur.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2sbbwtwyu.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qegjsxsb.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2tdbzymcn.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2vancxnof.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2mkftsmyk.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2hhhozkpl.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2xjfdnago.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2unqbbalk.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2xgqjiveb.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2gmppitxs.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2apqtvlql.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2enuguzgw.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2rkmbiuex.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2jbtshnvm.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2mwhcuyso.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2kqrvjlbr.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2whljgcaw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cfkfihyf.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2zdijlkle.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2oqyozbug.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2ooukgpjf.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2mszsnwdv.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2sxavpuwo.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2dhuppztt.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2locufnif.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2qxsaytoi.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2loxqljuz.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2vommhjnl.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2ugrfcdmz.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2wtsmxdsu.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2vfubidku.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2oqqslvlx.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2dsawwoyo.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2cyyegqrd.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2esgxnwei.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2chjzzyds.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2ybzwnlgc.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2prjdlgay.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2igtlwnrm.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2sopfjtum.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2gseqtgku.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2qyaecrrb.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2pmtfjwpo.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ynghexnw.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2xygfjdyr.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2qbezpeke.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kvdwklup.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2robvywfz.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2zrfswawt.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2sezhuvpj.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tsrqcuam.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2akjmmoix.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2inkvwzqc.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2fieitsxr.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2alaqnccu.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ezdivfkz.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2ybudsosp.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2djoykyci.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2lovbraiw.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2wrogbicl.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2sutezwob.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2rdohegtm.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2xajlbfgi.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2shxaynth.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xqrituco.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2ltbgfodq.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2fmepekfq.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2utfsvbsl.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2qciawebx.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2lbmdjzof.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2eofmohvu.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2naorasii.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2acmethme.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2dqzqoiva.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2woxrxxqh.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2cijqojnq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rfyxejiz.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2fguxcltg.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2ndickfdm.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2eerxgyck.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2lrgfmdwd.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2kpvwrfef.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2yimharmc.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2vlbeaukl.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2sdqtkiuv.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2bsppedgo.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2vuuzrapf.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2vuuwwxme.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2dttbmlpi.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2juoxksyq.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2psdvjgch.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2stohayht.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2wpsikmpw.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2jrkhvyng.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2skdoyahw.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2tkesyqhc.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2idtijuxl.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2xiavbrfs.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2vxnzlkgi.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2lzywvkej.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2tdimwplt.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2tnexgntt.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2ghdshbvf.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2vciekqxo.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2esjftokp.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2dhjpsqqm.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2ddutmpsw.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2ifloxosr.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2mfjdicnt.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2hlwhhhlh.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2hpbfayoc.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2wpyagees.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2apwpazun.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2nnnswhmy.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2owauywhj.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2kuayifql.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2lelxrqtp.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2bibzotfz.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2wizqiytu.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2xzmmgtih.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2fthyoktx.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2abswcdpp.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2dpcqwkhr.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2vxlbzald.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pzsozffx.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2kzoybclo.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yftuikzs.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vzzlmbnu.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tqyaykxs.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2dsddiloc.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wigfysxs.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2jnpnlxuf.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2wybjeayo.html


<!-- 参考信息 -->