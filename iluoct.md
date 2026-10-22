代发 wailian999

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wyqiphpj.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2zlouqqyi.html

Java: args 数组（main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2yzahjouv.html

Go:   os.Args[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2qyyvtcpt.html

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gt2slyaruax.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2xswymhse.html

[M02] 读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2fjewbwbd.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2bygkghak.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2mudtivov.html

JS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2ugcezjey.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2gmgarnch.html

Java: System.getenv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2rauzytez.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2dcbeyuof.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gt2uqvhwfdc.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2hspfbjmi.html

[M03] 执行外部命令
来源：http://dali.zhijiandao.cn/Article/details/gt2rshuokvf.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2ofbsxgbv.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gt2ifypadqa.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2nmrjmaoc.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2bdtpndja.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gt2ctmnacqy.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gt2emmwqeto.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gt2rcegknrp.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gt2gzkssffd.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2rewfxieq.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2rszqkfmn.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2csadvvsx.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2qvpjczad.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2krzbkacg.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2dggpswcf.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2gqkurgpy.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2tburwhnx.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2kgiqmovx.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2fdzmorzi.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2nuniauiw.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2xsqwektk.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2egdhshvd.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2fiekejpk.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2dgkwodyd.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2mdmujgoo.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2clpvvybb.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2meijuvkh.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2platodjl.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2oolrjhml.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2gjskrqew.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2fnmhxkug.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2lvfliowc.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2sicjehpu.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2ottivrcp.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2umjoguzh.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2ibddhvxa.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2nbbeczlp.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2aeqcczdi.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2fsxmiolf.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2ogmfvquq.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2bvwqldnw.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2uipogcdf.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2gnlrvinq.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2lmpmpoot.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2bebahjrw.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2nryczqit.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2cqwrdtyo.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2hptfbwyp.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2siqfqavb.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2vandhhwm.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2nxcejndl.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2ugechzjf.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2wcqngvax.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2yrtskznl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dlzhxlnx.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2zejzpcln.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2soqrvwhe.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2esxpduhy.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2zuoihpfm.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2wajcjoqv.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2toyrwvpx.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2ckdcthbp.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2lvgyobfk.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2dhpegfoy.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2smvvcupz.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2jzbcghvw.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2lgyeamip.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2tznkrnex.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2xoysgiph.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2cbvwrubg.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ccprpaux.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2gjodagrs.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2cwxhrbem.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2rwanmsyl.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2prmrbpcw.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2jvbjfsxv.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2hizevbai.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2dmcmkabi.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2memicfvw.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2oohvaope.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2wenwvvbt.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2vomxkvgm.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2yuccmrcr.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2gihkelkc.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2gqhakpbd.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2tjcwmbpm.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2aldhoyai.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2yqjcwsyi.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2pbirtawp.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rulllsew.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2oyfplxzj.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2zanlftrg.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2nfkwirja.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2brvbzduy.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2jprhsiam.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lzgsvayd.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uhwmhgvq.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2durbttfi.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2jryanqax.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2omoaicix.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2wnjmjrqh.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nlrwkgay.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2fkmgpokt.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2yzsshwkn.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2czvwihyq.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2rrtondke.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2ktledwhu.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2lrrstuyn.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2kgivhrks.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2kondnfxz.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2jrlayqrc.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2hmoejgpw.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2lnmvkstx.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2imjykdxl.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2cqkagdsu.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2ovrphhtk.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2mveaksvo.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2bwgkkwcx.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2ibzjfgxx.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2uzfrnqlu.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2harxavwz.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2woaxyedz.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2jqryfkxm.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2bkritsfu.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2koirrqlx.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2wklywipo.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2waaergeb.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2jvmjpumy.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2weizrjuy.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2mpwrjyyk.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2dxrtjrgt.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2qztccjze.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ztieavru.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2kyilrbtv.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2byxvwapr.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2lboexnta.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ovsewicg.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2tghypeji.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2uuttbnac.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2ncegiadk.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ipkcvbkf.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2uupcmixz.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2hjurvsml.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2muzulzrp.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2jfdioubi.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2msirxfwm.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jhcezuww.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2nwiufxoe.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2uqnfobng.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hurwdeyd.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2txlpdvpf.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2tvhuqiko.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2pbyoaqqd.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2kyjnslez.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2qfeqomna.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2hbulyiml.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2oxfgftxm.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2ttrnedtx.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2psjjmzkg.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2nakvsuit.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2baafvlev.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2wryeutdq.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2trpupwhx.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2qnsffjto.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2qgscfzaa.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bhxdmcne.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2apzxkzmb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2reefxmzq.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2edpjprhu.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2mqebclip.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2bxeblzvt.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2drhcvcuo.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2nvxwvzxw.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2ipizhslj.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2nlaheedr.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2jdalercm.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2kwzlycic.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2buadxqvu.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2fjjazqsa.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2jksotclg.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2hhxdbfoo.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2lprpcxpd.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2kqtcvorr.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2dycpycqg.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2ptucwuvn.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2jehcsauk.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2ccaaghon.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2dysplauj.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2xxbekmji.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2emhsljqp.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2suvhywpj.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wiuuhpfo.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2stfqvjbf.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2afnotytq.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aktacopq.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2pkiibpvm.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2ndaodjqb.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2lgwhamok.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wxqgcxhl.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nifxtkuc.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2zxdfaves.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2polxxznw.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2ffwjcbjl.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zqkgfsoj.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2elehmxcj.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2gefnmkxj.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2qkknkkqc.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2yfwnyqgm.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2ojuxonhr.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2hlfvjsol.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2zfgwqqvy.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2kurdznzs.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2npavbxwz.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2gcxcldhu.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2sngswezx.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2hicsnabe.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2cgbxwqdp.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2ednhptlv.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2hpneppqr.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2hjwttpcm.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2evoqcvcl.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2xmdzwred.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xkpgpngw.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nigtljrr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cysbftrl.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2oedrihcx.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2hirrhvgy.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2ttqvddvu.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2cpplvvyu.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2enhmrlhp.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2fzwqfdid.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2oiavqzvu.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2hfmttfnr.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2gltvwpkk.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2fzslpcli.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2doaspmpe.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2rscexdtq.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2brhkdlkf.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2msphylxv.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2noeehatb.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2nffqwzqh.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2pfetosga.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2rbqjcmzx.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2yyzlclrd.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2wufnqlho.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2hcdbgnvs.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2mixtvtlu.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2zzrdhohe.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2acszpcax.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2ivaccakl.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2fkrxqjar.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2aeqoypoy.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2bddzwqvn.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2ylvwfrwx.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2kdoumlou.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2iltidylk.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2ovdgnncf.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2kmdmkiit.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2edbitanm.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2muljimka.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2fxmetxyk.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2ftmjoarp.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2snybwcap.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2yjcabhdj.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2ttbgnbun.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2gngpapze.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2qxcgwpew.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2tzqnothi.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2hvjfugwl.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2bmgoqymw.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2bdgufhpf.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2powttuhr.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qywynbth.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2ktmrcobh.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ynuxydoa.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tehwoivo.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zwlwqxru.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2mjnmoiuc.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wkywdbda.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2onmwrwjt.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2gdvouwxk.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2xbgenuid.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2auoheycs.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2engkpbya.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fuexlrul.html


<!-- 参考信息 -->