代发 wailian999

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2swrldpss.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2icovorsl.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhijiandao.cn/Article/details/gt2qzzwafvf.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhijiandao.cn/Article/details/gt2swdcffkk.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2jctcbafb.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2vtkyzeve.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ajkgfydq.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhijiandao.cn/Article/details/gt2nqgddvkc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kvveycxl.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2hiyjwdzx.html

Py:   sys.argv[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2kzeiyhgh.html

PHP:  $argv;  $argc;
来源：http://dali.zhijiandao.cn/Article/details/gt2kknyqefw.html

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wulvpnud.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2gfvmsclq.html

Java: args 数组（main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2amrhcvdv.html

Go:   os.Args[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2vxhrtzwg.html

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gt2jmbsziqt.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2vzndzsvx.html

[M02] 读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2irjmnhfm.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2lhjxgqlh.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2lodffogu.html

JS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2iokbslcd.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2euxkamap.html

Java: System.getenv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2dnyjhsil.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2xhnxwbhq.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gt2dljrbuji.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2mgaibhpb.html

[M03] 执行外部命令
来源：http://dali.zhijiandao.cn/Article/details/gt2halfigcz.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2ekadspnm.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gt2izxvspfm.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2yasqwlga.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2edinvcwb.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gt2leixtuok.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gt2fjhgujwn.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gt2jckavwpo.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gt2mywbubak.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2rcdjldhk.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2tkaridez.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2ychntnxl.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2dnsbafsk.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2gjuqxeiz.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2ltbbrjrt.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2zsjcuocj.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2upbvqtfz.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2mqarddsp.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2itntelyt.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2luzhdkey.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2qtynmmeb.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2vilcmpuf.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2blysluzq.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xhtiacco.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2zjaqefjp.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2nollccta.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2edvjagdd.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2bobriqyl.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2qluoxsxf.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2yclvtitt.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2zrefmjmh.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2ibpvbiir.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2rusbhnvt.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2yyqtjonm.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2bsztvrhz.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2giyacfnv.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2savbjwgo.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2rilwavso.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2rcgdvyeu.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2dpbwydta.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2dokkngvh.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2ywcyyjat.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2lhemubmk.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2vumhhtth.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2nkdjxyut.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2wjxjrydg.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2omtizgqa.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2toychgag.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2sivppwon.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2gnvpzpxx.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2oxiqkqqg.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2hcjckare.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2gzqpwpjk.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2yzwvdgst.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2smqdsblw.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2ujzonpov.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2izvnsdyo.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2argpkztu.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2havnlyhy.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2xsxeemmo.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2qkefyuib.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2srheuxgf.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2hvfyjjuv.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2hwmyrkpn.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2ssybazfc.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2itqvkuki.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2gqpqbjyx.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2ceezkowp.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2lpqvmfxm.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2wwuumgdm.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2nnedypan.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2tiyscrsv.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2dwuofnfy.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2lctxrjls.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2cbhyancf.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2tbuqzzpt.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2zengsezx.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2tvpciqxp.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2etayauua.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2yfdvucna.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2gcyfunyp.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2vuegofra.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2zgzxelbv.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2uzxbgibm.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2emrqgypu.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2asncruys.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bijsvqst.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2dgatkouj.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2hhlbgevg.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2miahjbay.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ijyuacaq.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ezopwvbf.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2yokbxwfx.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2xuhycqxh.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2uasucpaj.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vcystjst.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dxneenie.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yvxnecqi.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2iebvmaaf.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2gfrbqntn.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2axqndmkk.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rdsouydx.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2bsihebgu.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2voompzuz.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2eztqgdzf.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2camjewkm.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2tktbpomd.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2gfqczdwf.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ilqshwnh.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2zskqyxvw.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2jffixdco.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2pppheima.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2zaeatxiz.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2zopvnpqg.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2dwsnvsol.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2vgqbvjqw.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2kcxrgrva.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2qimqrzfv.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2stmnsfxa.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2hsfjytbi.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2yhqczwnq.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2imgcioxo.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2vqgcbddi.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2hcyuzrkd.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2sozlcndd.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2abpqufhs.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2vjyvzuow.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2yqwyjsrp.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2mxrowlqh.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2vnpsqkmp.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2rktykxfm.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2bbnvfcau.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ykgsdyik.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2duigvrgl.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2lhpyberm.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2osjfkzpo.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2gxxbfxlb.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2psewgxpf.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2laucftxw.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2vooydeqc.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ojflxssb.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2asftmwim.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2noejcvbo.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hpjzqxuw.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2dtcusehi.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2ujtxdacg.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qrokxlsg.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ycmssdfm.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2wqbimppp.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rzvdehsm.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2ifduwoys.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2lwvjgxya.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2weljmcru.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2dqsbqxwa.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2zcupwypa.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ibxxopvd.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2vixxwtat.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2afnockgp.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2gbcdrvso.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2fhncuues.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2mntsyqes.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2xthrzaeb.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2twskdeaw.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2wvysqhod.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2pnyzbqdq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ojcczywu.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2csbcikri.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wxfiacfp.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2zlbntyua.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2dpnayofk.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2vwctwatt.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2ytezuswu.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2gkmipdam.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2gfsbhdvx.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2ttzuehep.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2jfvwqfdn.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2zwhljqwg.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2ocduzklo.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2uhdzhhly.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2essqzzhr.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2mdhrxmln.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2skbqhvzq.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2mriblijj.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2bedpgkgx.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2gtqkrgzw.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2ghxpyjeg.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2vhnnrniz.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2voqqyuio.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2nrwcilff.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2swqpohkj.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2bpnetrgd.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nvhsztzz.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2ddkyinno.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2lflsysvv.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wnlmaejv.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2uyygvhjf.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2skbjmajd.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2insdajif.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2robdxgdm.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cbxunwtd.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2ngctxvip.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2abosxlqc.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2bvgvwncy.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qxsumopc.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2ebvocpsq.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2ubuyrryd.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2puqufhho.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2bywbojry.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2lguetjvm.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2nbyzqomv.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2vzjtzesg.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2mgyypofp.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xatjlamu.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2spuqlyrx.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2ceisxnad.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2tdthanaq.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2jbdawtph.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2jogevtri.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2hvgmlwjd.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2evoaegdq.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2iamnosxr.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2xoqblmrm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vwnehiit.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2yiruaang.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xftsklls.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2yvmqnvkd.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2sdqaugew.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2riathrge.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2dphumcer.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2thugawmw.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2hpktrxgj.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2bdpycvbw.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2wgmfgqwx.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2glvjlsvz.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2thmbalgo.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2rvkbvpog.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2jbllotbe.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2utghrqcz.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2cyzhucfp.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2stdtsbrd.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2rsoxtoas.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2lzraspud.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2upsmxkzx.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2pulsrtbt.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2sfsoepsw.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2bbwrodyf.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2gywwnwzx.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2xnydmauo.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2dczybcki.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2pshvhfya.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2iawmeebc.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2gasitukl.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2rgcphafs.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2wimvceey.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2zdntsplw.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2agxgyddk.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2amuwcwrk.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2zwbqqeap.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2wyckyqcj.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2fstcxwbu.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2eplgkytc.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2zqpuzqvr.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2ggghaxiv.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2fhzxmztz.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2vtwgfoom.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2acbiysjb.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2dmtrdxgt.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2eflizihr.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2baouagmd.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2dfitlqvb.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2sxjlopgx.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2pfummwhy.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ezkvfpcs.html


<!-- 参考信息 -->