代发 wailian999

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2oqocpmdu.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2mdicpmnu.html

Py:   sys.argv[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2eaoikpzz.html

PHP:  $argv;  $argc;
来源：http://dali.zhijiandao.cn/Article/details/gt2vogxtyvc.html

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2vyqtbnac.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2hjreqydm.html

Java: args 数组（main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2kagoijbt.html

Go:   os.Args[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2nvhhrzsr.html

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gt2dcxisixi.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2ooijykrx.html

[M02] 读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2nbimuutw.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2qfsuzlql.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2lwknthyr.html

JS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2cqrytght.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2sekmpzli.html

Java: System.getenv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2ncdgappg.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2nmsgmhsh.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gt2ehgiomzd.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2nlifiggg.html

[M03] 执行外部命令
来源：http://dali.zhijiandao.cn/Article/details/gt2cwocslpt.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2xbocyzkb.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gt2qxdugwfs.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2isyzwqav.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2fmzhtdxv.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gt2ktjysoli.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gt2rprlupzv.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gt2heesoeud.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gt2ipntfray.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2rshvuvup.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2iwabclnl.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2qoqwqsaw.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2evqlmsmc.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2xhfpnyoy.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2ttwwnzvk.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2flfkpzrp.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2jpdhglfm.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2lgiielrc.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2jyobpmjp.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ihrtvzvs.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ffuriwbj.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2adftlctg.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2dnawenwg.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qezdwimn.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2lfvpirdk.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2imgoshrb.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2zxujhyis.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2elqpfsru.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2zyxgucmp.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2frwnlstu.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2oyhmbpuj.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2gjabhewc.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2oialrkmk.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2hldimxjd.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2vqgymkvq.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2fqxesvue.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2cuvitikh.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2rmarjdma.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2hnlhxprp.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2jntdtbzu.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2ilaythpy.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2ccvlctzq.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2cbkyvzrf.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2lnqtyyxe.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2wxlovomv.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2eyqkanzx.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2nfuyvtfh.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2jqszitwo.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2beoqlhie.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2ixofyttv.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2pmiuojqe.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2ngfjylve.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2swellech.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2wjgoneko.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qezzutkh.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2qodcnmoe.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wkymvgjk.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2vnbzxmab.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2kuioyjtl.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2cspweebt.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2eupvyyzk.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2wcwrpkxe.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ugphpaac.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2cauviywy.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2qaeqkxdc.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2avyxpdje.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2dspxjgho.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2acznemlk.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2fysgxslz.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2arlxnoar.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2rsysywjn.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2amsnsgps.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2gqcgamvj.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2txtdcjpj.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2dbnnlfyk.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2fcbrybib.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2cawiwkwu.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2pakjqmzg.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2sssvetto.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2pydizooc.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2xhlqjzmf.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2gohrlpif.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2ernowewy.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2qhevrirl.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2thezwuzc.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2isezemwt.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ycgcpiyr.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2muwgbhlk.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2bkboaqda.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2eatjgzud.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2veadwhcy.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ljednokl.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2dyjmtjqs.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2xgzcixvh.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2fzlmnayx.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2esjtvxlt.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dvrchfco.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rlitguyd.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2yhrfkwur.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2hkzrcpao.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2zqgkykkk.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pxpyfihi.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2gluzesxw.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2bdeaokkx.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2uuojrphv.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2bpauriby.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2fygfxkqf.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2bvtdkinr.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2snculada.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2asdwzolz.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2oiybgowh.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2iwwdvfpm.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2hijynomx.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2ylwyjiiv.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2qrgopacp.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2eilsyxxa.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2adszuoki.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2tqmnsyyq.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2rwctjbqx.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2ldnzdcuz.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2oupdfcbt.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2bggdhuyq.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2ptjwbjmx.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2rihdylry.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2gishugst.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2gltoylln.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2cgcjpjlj.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2xjgapeyk.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2cnldeoyr.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2qdlwepvv.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2cuababcy.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2lviyffuo.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2cnfkzpdt.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2dkjtlpcf.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2qfubwout.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2noksygsj.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2bppwryrt.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2ewhsdkjt.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2cheqprxw.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2cjxpadra.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lzzzmyah.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2cgtzmhcp.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2mfclpezj.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fhgvbaqk.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2shkgbqxs.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2htfoznxp.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2irbostcb.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ptmvwvzc.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2hithkpef.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2puarvcuw.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2obtovcvx.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2tgxlkzys.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2eufqzxsy.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ziyvixir.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2cldcfior.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2toptqeyd.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2pqezhyhv.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2fkjmipyh.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2zxlucdor.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2zhefjpso.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2wbibvcqw.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2mmngswar.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2mqfuylqu.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2vlbuvhfu.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2vivsssgj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2grpubika.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2yvzmxgge.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ahshfmyz.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2xtdvceba.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2qodogvdc.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2lbwpcxbb.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2grsasarh.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2gmmzepmr.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2yrtcjrqo.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2pxjsclft.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2cdtehdsz.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2ivqrzwhz.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2qtcbmcsv.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2sodvtlip.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2htasswuk.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2fbvltivp.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2omtgzvhf.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2vkmjvfjh.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2jdqsxmmn.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2jphbzeyw.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2bkxlywmj.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2yiqizalc.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2qazxtqyi.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2yvxovarc.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2bxdwmrky.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2yqotdqde.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2blcpdyng.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2ioocwyon.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2bqapoxwy.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2acivvosp.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2tsrdunbx.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2apdkoaif.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2xtqkliar.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2enqtypfs.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2exjwxhbu.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2opwnctyo.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2ukxpoqhr.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2nzjtqhdr.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wmbdvbsm.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2hreaifhw.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2qbubgacz.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2bgqylotn.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2tmbklztl.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2udjnrlwf.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2dnhwhlnm.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2ztwdwonc.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2arjijldn.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ewweebhb.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2nfviazrn.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2fpylbuea.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2znvildgu.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2osuoupzb.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2rrzclotn.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2xsaeeinr.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2wrwqcite.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2bctquijq.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2cxfibxgq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wexqlsoo.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ghmylxta.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lsfpuzoy.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2ifbyphto.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2cpaidjfr.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2lodoxkwv.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2jikucxnp.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2ocxpixnh.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2cckcllvq.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2tfdytmsm.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2tprkbdic.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2hpxgiglq.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2tyedutxc.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2mojwoyyg.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2jpnuyofq.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2hthbolfv.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2cuxxdlth.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2ymppzeaa.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2bhaaekpy.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2dcxrnnzu.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2hbszboxc.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ytbtzrwd.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2ljnrrbja.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2csxaucrp.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2nvsjhnfe.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2ajgqwzij.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2rmohzkcm.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2bwyaxewg.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2fmqlqucp.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2rijdhizm.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2xxopwvmh.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2vxdcqcpz.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2ikabrobk.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2rbzzvhzi.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2iknuepxp.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2xmgyxdix.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2xyqeqctg.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2jaskvsab.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2xztofnpb.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2hgzctcyy.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2ncdhnnpg.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2vbisifaf.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2fwenhnuq.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2fmfjdlhm.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2wjulraoi.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ypoqgewx.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2lbzfrtoh.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2ilfmrdvq.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2maqukfzr.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2oirfjgpw.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sjfxkwmw.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2kvcyafns.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bctennmv.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2apjsftax.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wwwvujub.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2dvfcoqmg.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ucezsfig.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2inihllkp.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2ginwnuqu.html


<!-- 参考信息 -->