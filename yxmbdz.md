代发 wailian999

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2yxmkhxvl.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2lkotvpwu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2naghmiuc.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhijiandao.cn/Article/details/gt2oqvvxxxf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lzjpxigt.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2fijwrnww.html

Py:   sys.argv[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2xlmonjdv.html

PHP:  $argv;  $argc;
来源：http://dali.zhijiandao.cn/Article/details/gt2ojqodoaf.html

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2iqvtdobc.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2zsyjwqso.html

Java: args 数组（main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2oipbwojb.html

Go:   os.Args[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2btfgkvzp.html

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gt2bwyqqklw.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2ieahxoiv.html

[M02] 读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2dnguszat.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2fikcuwzr.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2jzmgazrb.html

JS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2htldrxpp.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2lmnbtaws.html

Java: System.getenv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2hzggkgvf.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2yjhbvxxx.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gt2rbtvwltq.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2rdqjcwnh.html

[M03] 执行外部命令
来源：http://dali.zhijiandao.cn/Article/details/gt2advzfiel.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2udwfiung.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gt2gbrjlckg.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2bznrtdrq.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2nekppfyx.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gt2wqueqlis.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gt2bcmbtfnf.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gt2nizuxvca.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gt2whguhmqa.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2dbuoqcqz.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2ymakcrdy.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2zhsajclk.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2mzkzqtew.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2wykqfpqe.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2toxufpmd.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2gljjrnnx.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2hbnrqpuc.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2rzhixswk.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2eviaczta.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ldhrcfyv.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ieoaobwf.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2bxhvkvdi.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2uqyjebnu.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2mhgosxbn.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2bbjsnzbn.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ezheelgs.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2gslregod.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2tscxmqnh.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2usuvsuin.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2ehmxhnxx.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2mpzbbwiq.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2dnlkkndh.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2kzlkqqoq.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2gdgetjyf.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2eytxfxzv.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2eojzsdfo.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2bpxaltuo.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2semrumdx.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2evuraqru.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2qmsbtpur.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2ndsijmav.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2zltgyomz.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2akfdbqsm.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2zglexqwq.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2oqdgkutc.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2yuldeahv.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2wsjudiqo.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2qnlmoqbz.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2cxoqvccq.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2puumxieo.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2jwcpwziw.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2zslteahw.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2qpwktksx.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2gmagrzss.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bwammpxc.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2iedgnjja.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fbgqrqkj.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2cbxgqdrv.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2uuwgfsus.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2yougpkfp.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2chhjhoqv.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2ozmcaulh.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2vvynhtdm.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2dmlwovfb.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2grnpomiz.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2mvskwstj.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2pqdquigw.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2qbjruemb.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2fbaugbwo.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2xwbfehcz.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2kylfdooi.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2axhswzpw.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2iuwywvpg.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2pwkakwui.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2knexszbi.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2ttxgposy.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2klisykoy.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2quojlvib.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2wrtryoos.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2swwggmrw.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2sugjrlod.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2qrzoiwtp.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2dndkicea.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2rqszxqid.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2ipuyvkrr.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2znrxgzgy.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2adgrdwwv.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2zpvbtjaf.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2odlzqfip.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ngkfsewd.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2cbpvinlb.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2qmgsolfs.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2kjjgoixo.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2ekgofzdx.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2pkramzkx.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2awklxdua.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qlprtahz.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2olhiqybg.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2iukucmgm.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2sljzexsj.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2addvmhvb.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2oehkdxcs.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2tfjvboyc.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2emhuqawg.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2uzglasuv.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2ugavponx.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2ejqtqlsd.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2saimrevh.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2vwhiwydj.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2buhtxuni.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2nqsjpisy.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2abjnogih.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2bkrllsud.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2aajycoma.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2iizzaxco.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2rppszlea.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2qasxober.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2fwjzlosf.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2eejfmqxo.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2vrknssmg.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2pbdwxoyz.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2wocrtfhr.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2vdexakdi.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2kzdkzdkr.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2oqylgtsb.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2yeeyseky.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ocxwxgil.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2sgtlrezq.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2dpagiqnb.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2pgjgtgwu.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2jhkksxyh.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2eisdwmzx.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2jknyzvon.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2msxpvxtz.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2qvlwbttc.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2wmteajqr.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2wyycvolc.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2ljcgevnw.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2nvqtejqw.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2hxeoznxb.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wbigybcl.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2uyidiihk.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2hjnnousy.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rgfvofck.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2kjsfwlqq.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2hgapguyp.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rnhlpbxh.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2btgizeyo.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2rygksvxh.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2snjkqhzq.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2dqulmhhd.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2jakfbzjs.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2pyisgzeq.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ghsflwvy.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2aygpgqmk.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2qhzshyoq.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2llludgke.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2ihivosjo.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2ngzrxiaf.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2lgocupdv.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2ftavxigg.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2pfanyrst.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2omyypzas.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2hacovrey.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2slokulfh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2javsocnh.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2ycdmdwnh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jhszvfqk.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2aokpeckm.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2ossohjns.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2xffoxipf.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2sfommkvs.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2paiiaxbj.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2liuzkklp.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2gqivhjgm.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2gsazlkgz.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2ueavxqdz.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2pghcndet.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2judzensn.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2qloporvp.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2mxjbnvva.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2jriqguam.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2shkqswyp.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2rzoepnhv.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2nqrurwub.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2ubidlqzp.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2fixvkxya.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2eggjscou.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2anjeypvc.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2mveknqlt.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2urhnwytf.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gusptlew.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2jghmojpf.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2pulmgntk.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tgobexxx.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2oxuvshac.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2qcqdjgzk.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2lwlnodzk.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2sbasignv.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2iokofyfk.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2rhvamgum.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2vfspdcmi.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2tdmkfjsl.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fsnhkycg.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2dsoxduoo.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2gwlgfqbj.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2vdrzcxka.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2argrcojy.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2thvtgtda.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2jyrahksq.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2kyunncvv.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2idwceacy.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2cjnsugme.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2lpilmpay.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2ffrcfbbo.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2lbpnrgui.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2yppydpsh.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2durgostg.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2bwznvxyv.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2rasjmrun.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2mvihpmdk.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2nafzfsgw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sufcdxhw.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2trenaeng.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2klxewefz.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2zkzdeowf.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2aqizxmvz.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2dekrjuye.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2ccsibsil.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2uazkhwyr.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2zpvewmho.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2dhlqzjjn.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2gwvhhshw.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2fqoxualn.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2iqtcdzcr.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2laksbimh.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2abbcmcqe.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2qccsvrpv.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2wshflhaa.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2ukrlqypq.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2vlmjfdsh.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2odwggptq.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2vwelzhed.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2tgrawhuj.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2yaphydeg.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2swtscnaz.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2yctrrtah.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2jqwmzyfh.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2dkmbsoiv.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2zxqxrnsu.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2ysfoxmub.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2nguqajrr.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ymmyljhq.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2zotsjkrq.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2poeeoxat.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2rugexlry.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2hvilpiyk.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2peccbcjf.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2ijdzhqxt.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2nfbgwmon.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2cggrnfkv.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2kwyqevsu.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2rljvyher.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2eekjxgly.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2zawcldys.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2xznpposp.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2qnpprdxg.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2metxidkb.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2rsvtdyjf.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2sylhqstx.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2qsubxobf.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2nhvyufcv.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tfbirgyq.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2lcbjhceq.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dicexpyh.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2juajgvko.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zzwskdsd.html


<!-- 参考信息 -->