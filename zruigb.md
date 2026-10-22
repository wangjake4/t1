代发 wailian999

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2oumhzyjt.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2nytmhpvq.html

Py:   sys.argv[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2yfzcdbdx.html

PHP:  $argv;  $argc;
来源：http://dali.zhijiandao.cn/Article/details/gt2uobqtnjz.html

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2hnzzomoh.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2vugsniuu.html

Java: args 数组（main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2wphljamv.html

Go:   os.Args[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2nsmzlfsr.html

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gt2bjrvbyxk.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2zfrxvlty.html

[M02] 读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2enzbmvkx.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2utluwgwz.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2rznaxawd.html

JS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2wigjguqv.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2gwgahcia.html

Java: System.getenv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2misxghhf.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2wsybveha.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gt2sfqxhpsi.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2qeluyjks.html

[M03] 执行外部命令
来源：http://dali.zhijiandao.cn/Article/details/gt2upettamp.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2aqqioysx.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gt2fvkfvjsc.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2wbvdrknp.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2dyeueala.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gt2okkkdxma.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gt2buqkynrq.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gt2foanqylh.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gt2itvxwtsi.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2dextrjub.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2ifzlvyvt.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2cmeqkssb.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2xnhczgru.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2ofgwcngf.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2qwzvpmjg.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2enhooxzc.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2adfdtvbk.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2olawozst.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2onpgnhsf.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2bayiatlr.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2cbanvrpc.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qidbibzp.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2pjgvhdii.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2hjymuxek.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2janmfhhj.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2gmabylfi.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2seovrvfl.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2uujfvwpe.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ixykicol.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2fqitqeuj.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2yjtosmzg.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2botplrei.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2smqhjcic.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2qcfmlfym.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2rtreible.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2edawmdfd.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2oyqkwubn.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2qjvzxonb.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2noqtvqgs.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2jicxmdsi.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2pcedaivk.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2bswmwghq.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2jarbeweg.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2ltajsecw.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2ftnlfvvw.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2mqbqweoj.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2bjszesji.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2vkezafgm.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2orodmogo.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2qovtzvwh.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2ctqdtcda.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2vlhcsewd.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2jttqcqsl.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2fvcsljue.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xflttpqz.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2jeehfipa.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2glqdebxd.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2gtraswab.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2xkqmcjtx.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2ssoteexx.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2emoruxol.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2elyclvta.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2dfxhklct.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2uefuereo.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2fbhwsgpq.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ebfmlkcq.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2cuwsrfks.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2ssusdpmb.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2khzzrlyc.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2jucnuybj.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2vkuxvijl.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2yyszaegf.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2djwdccdh.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2dzizvjxl.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2rqptquwv.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2kumtbyqo.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2rjtblhqz.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2gvktdnbe.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2nfsetoqs.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2gswpeweq.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2oaqzhcdv.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2mwmdxkff.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2lzeydmio.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2cvqdxnna.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2xslqgqbc.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xcpwuhmn.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tabnedvz.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2rvpedtic.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2lftrkcib.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jqqnuoao.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2rfmvvbnz.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ccdceros.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2ujwaaohn.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2klmlgacx.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2wnuaxyxs.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ietdojvo.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ygfbnuxv.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cjlzdtng.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2jnxsdxvn.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2nkmwploi.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2tjhoytro.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2oarrtqdp.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2anlxvsjw.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2bpwnumtm.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2erzvuxik.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2yoipezkm.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2cliklcch.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2dmhharda.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ppryndgc.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2lwmadvdh.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2todemhux.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2rmbbrepu.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2bnaluupn.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2ozilsaqi.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2ejrpiiux.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2cmenlhsz.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2gotmnobi.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2xzqmsufu.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2bndznnos.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2bwckgkxq.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2ymrwsuef.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2iypmpaod.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2tdgqifhb.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2wmvcoydd.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2fbcgggnz.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ayaevmhf.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ownpxnsa.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2cukvdnbd.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2tidovltr.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2tkwekaix.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2pgfdujgg.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2zkfhujob.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2sxojszvf.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2eybuzyhs.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2oeismcve.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2vbzmoqcp.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2gfqniirq.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2fvsssbtq.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2lzmedkjl.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2thmwudzb.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tbbvegjt.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ctmbygfh.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2prpemokm.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qsjtqpxa.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2lznrgevj.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2reoooajg.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xwxauztd.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2lekuszne.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2yynotsne.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gjmvplok.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2aukopwzp.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2pjbjpwmv.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2owhxfytv.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2pqqbpdwu.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2upymjnpu.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2bwnxrvks.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2orsuoonh.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2gzyffyux.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2qiwmerbc.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2kcfbkwgi.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2jknehnbq.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2nwijoqry.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2oilwukgi.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2czxkxgjz.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2bohihgdq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vaxcfhpx.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2lrjfinvd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cswiprmd.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2zfzuknjm.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2fniuwjah.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ajcyjpdv.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2bkaaxosq.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2gkkizofe.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2gmbvgfsc.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2leqvouwo.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2abdkvebz.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2ikpnfiow.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2xpmxcfkm.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2xkpfxkce.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2jqgpttid.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2enfoynsk.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2ygjbpvvj.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2meathtsv.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2hcaauyib.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2qbechxnb.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2gruojttx.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2qlutzrrn.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2sytbthom.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2brhhtdza.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2mjumjjpn.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2rshwbuyu.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2afkmkzls.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2udehnyin.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2rujsyfar.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bwczkmyl.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2bgeqfejv.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2xkpswfzt.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2aewxrpin.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2goymdpsf.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2prvrxphb.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2skohklaq.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2wrfpgnra.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2tgirtpoa.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vpiganlv.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2fkzpnszf.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2ahrqahqb.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2fpegdyye.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2boeibdyo.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2vuwyaehl.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2whmtwbnx.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2fzngowax.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2pikcaaqr.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2npyavbby.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2otavpwxl.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2obqpfbbh.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2krvmqwjq.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2lsncofoo.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2utdbqfry.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2xxokbbew.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2sqjtyfey.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2uaenenqv.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2epedzsbb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vcjbligr.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fewsseov.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fizyxkwa.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2jeyhbhip.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2uycqcttj.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2zlgslgsw.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2mukgukdz.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2zjllzmho.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2tmxgtnnl.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2psuouwop.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2jieldlbc.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2uqbuvxsk.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2rderefcp.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2ganzkmym.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2fxabmbnf.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2ejjdwzdt.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2uncofwkp.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2keprhaxi.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2kugkgkdc.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2glynmnmi.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2vlqaybuz.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2hmbxmyml.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2xstkowvh.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2misqzmlu.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2dlcxkwhm.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2hgqpbzlp.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2rmfraqia.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2wruzmltr.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2oxrfsvxk.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2ifgnhzld.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2bnuwcnub.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2yppkwwmn.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2zmatvpwf.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2etuyhemi.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2vwvbsfqg.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2bmauznnr.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2stokmyhd.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2tsblbtci.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2roqfwgip.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2bvnkutfa.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2oshmjjvu.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2rrtaukbb.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2ffboxdhj.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2hjzjclyb.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2yndfxhyh.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2oriktavn.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2mavojeih.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2tkvudcow.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2bpslnpwj.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2eniakwsn.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zavqpoxf.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2khypvmos.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2lbnwbrvn.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2iqmhomez.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ctfaplnr.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2iaevsats.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2djzmdahm.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2vvgzcdlb.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2wkqwnhyf.html


<!-- 参考信息 -->