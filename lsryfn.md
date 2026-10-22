代发 wailian999

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2foxpaucp.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2cyryuojg.html

Py:   sys.argv[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2hvlwlddh.html

PHP:  $argv;  $argc;
来源：http://dali.zhijiandao.cn/Article/details/gt2gwzstxbk.html

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wxqgajuc.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2lelehufq.html

Java: args 数组（main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2rkyimggy.html

Go:   os.Args[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2xkevvghc.html

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gt2rgwwjfkw.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2ivvspfwv.html

[M02] 读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2anpsvywu.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2njbupide.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2ghqicyls.html

JS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2jrlelyzc.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2lkdigjgv.html

Java: System.getenv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2qeldqlde.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2ojgzmdbo.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gt2slolyzzg.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2puircnlv.html

[M03] 执行外部命令
来源：http://dali.zhijiandao.cn/Article/details/gt2tczeiaxk.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2sjcpwolf.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gt2hnqptvlq.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2qzmzluht.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2meboegyp.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gt2jqqgynno.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gt2jhocluub.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gt2ftemrxrd.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gt2nztgoajz.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2hqcurbmt.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2lcpbgziu.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2wunzrmay.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2vjtfomqg.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2jhmdfdkq.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2smkufciv.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2hbickrsg.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2raahpvyh.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2aqvebutd.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2xiamzpln.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2hstifqlt.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2lctrslnk.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2chfisisn.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2rxfkrwyk.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2fwtpsqmm.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2fzitmptb.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ahunfneg.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2afejucwd.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2ivmokrcl.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2bwdnwgpo.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2jimkofhc.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2jgktwrwq.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2nydpsrok.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2ezgbqohh.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2divzgmew.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2zdcxnekz.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2jzdpjrlg.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2fcqjkyel.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2ysqscaxj.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2zaydejhi.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2qiyzpthi.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2bfwumppk.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2skvtrjqf.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2spcaoxpe.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2hfbmtrqy.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2fwxsbxtp.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2twyvults.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2cejjvzit.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2itylniql.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2qrrrryqb.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2hbrqlqae.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2vjhtnvba.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2gemjdavm.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2zpuxxsgr.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2hrlncnnz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kuafjhps.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2gqjgffaz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xvkqmvfx.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2xlctafvl.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2dxoctbtg.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2wdvqsftz.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2rijwvoij.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2skrfinml.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2pvcpqlwz.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2qujzbgnq.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2qwcjqqdf.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2tyagazyy.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2wvugthsz.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2npewxaiz.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2dcvgmotj.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2kjqwyego.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2nyhppflt.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2sutpakxf.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2zfiaduhs.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2ubdeylbv.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2nwmicmgn.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2ippgkaul.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2svhjrioa.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2covongkt.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2tscfoopp.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2hrypffoc.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2ppjobwgl.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2exjbvkbk.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2wwiqagds.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2incuclrs.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2zmgezwsc.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wjnshogc.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rxiqdeln.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2jccueyxk.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2gngomulj.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kqmukzwu.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2yatrirur.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2vwlpucou.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2ecuifiqb.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2msvciosh.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ybmopfqa.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2egdiqzgc.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eriyjnap.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bfkochvv.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2zbghrirf.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ebqejpkr.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2eskrvsyi.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ggiyuvpv.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2iijuhdoq.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2noizruka.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2opyhmvgc.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2qbjdeaxy.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2jbggemkn.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2yijcypos.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2zgsteeyz.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2fkpliauj.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2hfvhmnfb.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2uhpgbtli.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2seccmouo.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2xkexavmk.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2jsobylre.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2ttpmetvu.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2fgymixmh.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2uezqxdmi.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2nulrgsrm.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2tjmccsjj.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2idwmkpwt.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2watbniuw.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2djbvozft.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2fyfoidci.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2deshhstx.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2usjzsnsr.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2qykqwcat.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2aozlihmi.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2bifcynpr.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2mugbgfqc.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ykujehkb.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2xkwxvuhf.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2liwikhyy.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2fbvlktuj.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2vbwzrlvn.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2kbtdjjfv.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2cniyqewz.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2bhfprjxs.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2lyutzleh.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2vsidbuic.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xwrqjloo.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2qpumueld.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2zebnlxwq.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bllfuind.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2dxfexsoa.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2mlqqskpl.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qnofaobp.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2acytumbk.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2wnsfkttt.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hnhmxzgv.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2alyninxh.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2lyytqnnh.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2bkisqjau.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2tfkjnicl.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2cmnaqkzu.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2pmtmrfct.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2iqivrzjt.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2jzecwunv.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2bdnagqio.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2luttjzfp.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2decczgaj.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2urjxqgpi.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2zspuyubo.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2xrhzjcro.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2fjctxdyg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2exktpang.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2eanjplus.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yaglgqsj.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2ztxewlfa.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2bxmgbtmj.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2pphmttvk.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2azvcodpz.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2hdmvbdck.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2oxolykgv.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2peisvzrf.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2iuzceuqb.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2fzahfuem.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2stuokpjb.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2yiuwldvk.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2viowczeh.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2tfetpbux.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2ddzwzbcl.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2obhtnlqf.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2cambhjlg.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2ahirciiz.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2lywgypan.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2sjocctsh.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2osukprik.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2suvahsgu.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2vnjldqom.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2hdztyhif.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gschkelg.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2rfftdnwf.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2gilhdhyf.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2auosvbip.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2xsilhkwx.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2rhlvbyac.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2tdltvwpa.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kaeghrgs.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2doiswzmo.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2vfvafnhy.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2ybeqttyv.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2riesbytl.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2amxngdyf.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2jjxaxbnc.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2zbgsxycx.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2pyhouqjt.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2vjuzeycv.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2fosoyhfu.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2fudbwrsb.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2ipezjsqy.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2mnwddysf.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2dbjnnfxz.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2mfndizlz.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2vhttiklu.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2wtqhyutc.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2ocfwhoff.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2vaoqvwpu.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2dzvbqymx.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2gpyxkyhr.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2yddiaegn.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2iecfalns.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ckvddlqd.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xslnqvue.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2basziyqq.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2ahkkdvoq.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2bjvjvncc.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2fimrrtjx.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2jxvpmpjj.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2rkkthxvv.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2xffflaax.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2ysbualup.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2aiyzfbdq.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2yspumani.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2ylabjdsk.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2xxrtuglr.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ljqxctuw.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2rolkbjdt.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2agaexano.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2yihruhex.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2vwdbgxeg.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2voppqeec.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2dergmtbp.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2orqsdzcc.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2waxjwcpj.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2bnqxzgzb.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2yhubuqyy.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2psjyvocs.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2brangozq.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2wnlziauj.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2qovkuxvy.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2nrmdqjyc.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2cnijjibs.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2bgpjihcr.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2bylrdorf.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2owpeqleo.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2jhjtorzp.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2emffrdpc.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2uitmvnri.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2blngwscp.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2qkdbkqcy.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2lhzzieem.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2ilooxjub.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2jajxzfgz.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2qjgiufjg.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2jtoovboo.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2godatezx.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2otcsumia.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2aamirlva.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2zzivedto.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2eruetdwc.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2wjckhyik.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2enyucyys.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2nrsgbmzx.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ghohgkvt.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2iyukqxxe.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2iwzddiwx.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2nrchuiop.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gmyzqczw.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2wowmvflo.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2jpnvxokh.html


<!-- 参考信息 -->