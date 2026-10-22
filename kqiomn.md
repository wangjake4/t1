代发 wailian999

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yaysljcd.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2tehdgrdj.html

Py:   sys.argv[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2gtdnnlkq.html

PHP:  $argv;  $argc;
来源：http://dali.zhijiandao.cn/Article/details/gt2nljdesro.html

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2bprcobgh.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2yatxgmdw.html

Java: args 数组（main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2dfnsqqqd.html

Go:   os.Args[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2auwpabfc.html

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gt2juvrwgih.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2bwxgfygg.html

[M02] 读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2huvenozs.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2zdwjytpw.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2ptrpxjbs.html

JS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2nqjyqrkh.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2rqndwupo.html

Java: System.getenv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2fzffquca.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2jgyvrxnz.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gt2apmywsag.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2sersweyy.html

[M03] 执行外部命令
来源：http://dali.zhijiandao.cn/Article/details/gt2nhikwqni.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2evdivohp.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gt2fdswknly.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2onnuupje.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2igcpxokz.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gt2brpwlhwq.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gt2woxpmxqs.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gt2uyjbzajh.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gt2cekvyzez.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2uyrbhqgp.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2srjxewqh.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2ishfhpad.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2msoxfyfd.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2vjhqllne.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2nyntcasc.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2vdbpzvaz.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2aykhvhbd.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2iecgawba.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2cmfbanoj.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ytofgwuf.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2gqawewkw.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jsrvkjsg.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2wphwpslz.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2vmdatfpn.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jqpmxmld.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2pnhmcfyj.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2qftcyuzg.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2roebdytw.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2qxxwlvtj.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2cyfshmje.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2bhhhadrv.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2auolsrqk.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2tuijgbpy.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2nloesakw.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2yxoozmgu.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2shoreqin.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2xbnuhduh.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2qfkdjrtr.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2gxjkjuii.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2qimonviw.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2ypvgvrkb.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2gtdjpqmw.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2fcbvaeyy.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2nwfherex.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2qyldmcen.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2izbdytos.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2gsgpyylk.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2pkahmzwp.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2sxqyeslk.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2lyjwnojz.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2hfqqhgwz.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2anbsabuf.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2ndwanrlm.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2hhwwvaqt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gwglzbcp.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2gewfyegr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tntrtpen.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2mksebbxg.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2nuumbfwu.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2ikytpaqk.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2brxmgzck.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2mhktqskr.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2bstpovkn.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2eyqqfqbf.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2lpouumhu.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2rutujinu.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2wlsfjwdt.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2azjkgpcp.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2gxoyertu.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2nzcuszlu.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2vgkqjwbd.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2mbbusmmq.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ggkiplxi.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2ripoysjk.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2lhpvyvdz.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2kdnctntw.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2aojkfmys.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2cpmuvshx.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2vkcczkcs.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2umeqhymp.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2vrfgcfzu.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2wxkxjjnb.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2wzptjfna.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2gfowlwlb.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2qwwopvfb.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xkvvwujn.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2looslqys.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2xlfhlown.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2dgvwkqkx.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cisomhim.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2pzrgfxqf.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2jlxlbodq.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2wclvubgq.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2vylxrcmr.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2usrjtxhk.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xsxdyfpt.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ssakdziz.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xtejvslb.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2snqssvau.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ldgebfnh.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ffrzhslq.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2iugboici.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2rkobaxuj.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2ewbtbenu.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2zxjjptit.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2jinolwcf.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2ljnrrbfo.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2iiuzcfgs.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2jbtpvptp.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2srptptjk.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2qxyvtris.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2owwcfqqq.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2tbdggzfd.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2zjfjsfyc.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2gwpuwqgx.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2xfydlueu.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2rwojkode.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2eoaxpnac.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2ftmrnkcf.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2jhlwhvnw.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2ibxxfnsg.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2giyxhvpf.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2yaabimvr.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2pewnvapo.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ptjoksuo.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2thpafvjv.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2epwahcbg.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2gvvyjjkl.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2pbqqjgga.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2iiawzxna.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2grdmwshv.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2keoegvcn.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2awevkwmc.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2qudsptgm.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2bdrvdrho.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2nruwmdtb.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ieaxjfxp.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2lmtnjvah.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2axkwwgee.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2vzsusado.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zumaqjbb.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2rpsfpytz.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2fmjsqxhr.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ibqguils.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2iicpghqo.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2edhzavct.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ciwyzrcr.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2hgajctob.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2diaeffam.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2neqgelkm.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2zfegdyhh.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2zkmbmvsv.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2hrqefdev.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2llgizqna.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2ivxaucpb.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2wriaryzs.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2kykpncol.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2rgitknhz.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2qqbpuxhl.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2smfzrxgt.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2bnfoxpra.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2qdjftfth.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2qzcgbgtm.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2dndlbznx.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2wvclnjhl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2frwwslqr.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2guninbvi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rzlbckrs.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2uffwsfdm.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2yoyimgal.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2pdsyxzge.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2giyodaub.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2uisylxzp.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2blxmvqkb.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2uvhkuqdt.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2vdfumsfs.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2ijuytevb.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2ajjplvsg.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2qmdjofof.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2tnrvrhdt.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2nionbfab.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2srtdwocl.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2srtitsrs.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2jdrcvxqb.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2dnlxmvrh.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2cxxibkkm.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2hhdlzwso.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2wfsmnvmd.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2aqkoqdou.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2cktfdaom.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2sjuwytih.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zjzyetwj.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2mrilubvb.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2xbnecolf.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2liwarswi.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2jwgxzgen.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2fyncdpsa.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2yjoqgjvs.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tlxhlgcj.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qexaiohb.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2gbyigocr.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2zxwvktup.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2npcovwdp.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jzcwwzxw.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2yexffwhu.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2kodxtgnc.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2qcebzghn.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2mcfikixe.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2stkmnglj.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2pjiaquuj.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2ogcwxkmy.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2ceysirde.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2oeopjzeq.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2rwxaxsno.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2mzgyyrpd.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2mioluebg.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2bkgxycau.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2dzawkiks.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2xteuttgk.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2yvfcgtze.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2vpsuoivs.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2rittuylq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qhsnrryx.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2llyivrsl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gcsurxaq.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2xadepmme.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2zsuzvqmg.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2xvdulgze.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2pzdysmws.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2hnitqjsb.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2dtnehxxj.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2ffqiisnc.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2gobllrmf.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2iudzepao.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2mmbxcdmb.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2dmlaaeyk.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2geggkoke.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2nohbuwzz.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2yqcxhgii.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2umnajtjr.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2kjmoprgx.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2nfixvuyc.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2gtcbrqka.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2auyukcba.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2sgohuezq.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2crjwiifn.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2bprepozg.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2cgzahcpl.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2qyakqfke.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2ubaxsjgo.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2humxvwdt.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2pfbcwqmw.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2uuztinpq.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2djibyqcf.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2mpqidayr.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2lzmeqepp.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2isxrzkff.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2dkxhtrgu.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2mdjmtsjy.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2pjqdushi.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2jyevkeol.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2urtjbtfm.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2fzdfhmfx.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2dwndomjs.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2kglfuwqy.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2oagwjlkf.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2ibsbdsan.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ixcbpalg.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2bwobqozt.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2dvejzzqi.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2yovnsgjs.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2iuwceqvv.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kqrwrnfp.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2lcwesadx.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xxbpsjpw.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gbdhyyvq.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cdulctjy.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2uogsquud.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gsfvotpz.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2zekxjltx.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2wlkwfmgy.html


<!-- 参考信息 -->