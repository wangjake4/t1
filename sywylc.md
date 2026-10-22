代发 wailian999

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lijcgdix.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2hzoamdgd.html

Py:   sys.argv[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2kubbnvmf.html

PHP:  $argv;  $argc;
来源：http://dali.zhijiandao.cn/Article/details/gt2snkjbrxx.html

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xbzjvdrb.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2yeinafdk.html

Java: args 数组（main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2snmwynzj.html

Go:   os.Args[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2ttcsmzzh.html

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gt2lslhdhgs.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2onypaukv.html

[M02] 读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xjcuzcca.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2zkrdkfrx.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2qsxboqjt.html

JS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2tnovlson.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2vsaifuqs.html

Java: System.getenv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2qliscxew.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2pjesnjxe.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gt2keuukuqk.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2hoccfrbo.html

[M03] 执行外部命令
来源：http://dali.zhijiandao.cn/Article/details/gt2ekuvimar.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2bosvcjpr.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gt2dtafdvky.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2kszltvsj.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2dasjpziz.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gt2yugnhorl.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gt2gdjwmkue.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gt2aejrpata.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gt2kfyzybzz.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2zkxbasev.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2uehtogqo.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2ozrhyqni.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2ozmlbmej.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2gbbvgkun.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2qwxbcuwl.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2xlhywyzx.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2lfrzgxcr.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2atnqxpan.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2gvzblncw.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xqxxbosc.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2kpvzykzx.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2gamilzyt.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2liwvhhui.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2virqllbk.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2gzauatwz.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2yjvtvwxk.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2xcjnilgx.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2ukwuwmui.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2jpdwztdr.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2rmladayj.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2iozaqrik.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2vqujtlyo.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2bwijcbpc.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2csqnrxcs.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2kynuiaqb.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2ueuovngs.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2dhvwxwqe.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2mlyyzjop.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2pwpmnmnb.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2syaqwnfa.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2wqvzytaw.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2mgwsiotg.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2kkksgldq.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2ptzmmqav.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2lvznlkql.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2emdvlxol.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2mmegdxki.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2cbscyqlh.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2rlotsbaz.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2korsetfk.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2ewulbkeo.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2oqjkiudr.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2vulkkocd.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2bijzowbl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zvlzmtjb.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2anflmpmk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xcarlvmx.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2bjezyfmv.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ajhgqwhb.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2gridqbko.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2wtojzmly.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2mjoxoxem.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2tejpetbo.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2oywoojet.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2ypqdmqte.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2tsrvamka.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2okytfswg.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2qjxeynvv.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2nzbxfxbl.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2mbrgshkq.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ytrbvecp.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2xojjxabs.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2hkuisyyd.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2kjniwphp.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2xytbrlrk.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2tbiljbzs.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2whngacyu.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2hxgetwbo.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2czarorgg.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2oncxdjtl.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2crvevozs.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2dyansmva.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2kegmruxc.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2jdtyqztc.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2vqttocvx.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2jdrppfei.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kqcuodeu.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2qnlsyelv.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2omurrskb.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wvakujug.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2duzewblr.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2pjomniao.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2vgyrakct.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2dvaqxlas.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ppndzhzd.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yfvszcbu.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kxatsmsm.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iixuzluv.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2hqoqilop.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ttnvighb.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2wxjozmoq.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2chhfynhg.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2tifcoteo.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2mswgicip.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2huxoovmc.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2huqbligt.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2ytwmzogh.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2mwagsjtd.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2atzxhumx.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2qazeeqlm.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2mpdcmspy.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2lhwfdzpb.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2kchkujmg.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2lphydovk.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2vvukniwv.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2kjfghuyo.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2hhrzdxod.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2qjsdcdrs.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2slckanhd.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2qzcdnplu.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2guzrngqd.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2abvadfwr.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2lurruaiq.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2hvevessg.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2dyibdwca.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2lhjgmzgr.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2qkltcrrm.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2lgdvyiqt.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2amrtgjwb.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2evcsnbdv.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2lzanhrcq.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2oqghfrmc.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2nlsasqwv.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2ejxvkpxm.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2jqijsbkj.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2lehnftym.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2xxwyyfdr.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2dbzqsqba.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2tgysgzuk.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2dluubndy.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sjrrrdff.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2vkcremzb.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2aihngigi.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wohtcdud.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2vzllugrp.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2ovzobnsn.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mtxmkqeo.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2cuiyhqbx.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2lbumjpgt.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vdrteddm.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2rkvponkz.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2mdynpiva.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2zuyhdxbg.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2hiupgdkm.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2omwxhcjy.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2wyjksioe.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2wrqgyweo.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2qrqxasat.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2hnvdxjfq.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2efsblbbz.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2mengsart.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2guwofbwc.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2abamcgky.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2znxkvxrh.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2cjolowhi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ecpdhmfr.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2csfnipwv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vindebid.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2tqkwuida.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2vyrbxwtm.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2pfwbltfg.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2rmqflztk.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2dbysqbjh.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2gyquionj.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2mgywybwv.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2ndkhwgrh.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2ozzbcfvr.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2rwkrskju.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2sjdiypbv.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2rmanymue.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2lmlddkym.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2hybcjetf.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2pqaqkdlp.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2vbchxilh.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2jearmqpd.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2smcylirk.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2tylpoojp.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2docgppsd.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2sgcpxswa.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2yppdhhxu.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2xyeazczd.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2segvjxri.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2ciuzndeg.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ghjqjyvk.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hfbvceug.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2nsonxuem.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2ixtgkmkp.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2ulaajxzs.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kbbkjyoo.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2prdwlbdh.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2krplssrt.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2xaygpmmf.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2hkdwrxle.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2djvmcmrb.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2juxjpjvx.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2rgebladw.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2ywtlssuy.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2quukvwan.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2muvjslkn.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2muszppri.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2ltexqczh.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2owrulzqy.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2zqysouep.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2rqvhipku.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2jkyxiaai.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2vdayibbh.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2drtmvajg.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2yxlwbpun.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2mjmbnqxn.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2aurzmuwr.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2mipbourz.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2ywknoafu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ixsftlyi.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ncyupepo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xtydtujw.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2tpyowmnk.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2qiiwwwnz.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2sxynqidc.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2uswbigka.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2sczkcked.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2szmktiqp.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2sdivrbgn.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2aslbfhxb.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2gpvifqhf.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2vrgddxul.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2hzkezbaf.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2fwcgkpsb.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2qhryqwba.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2hrykkwcn.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2kynguaxg.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2laktzrof.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2kdiawnuk.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2vglrxjok.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2kweuviqe.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2irycmvbw.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2puesoodv.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2wfqtymtk.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2bbprwetc.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2pbbzldvz.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2isoexvrb.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2yzkgxtlm.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2wgmrirze.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2qxqfzrdx.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2ctnqckzg.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2mpomcuyl.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2cqjglrdr.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2yflsiljq.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2ddpneagp.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2xucnfwzx.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2mfxvbnaj.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2kiynnogg.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2lzlxtjlj.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2bxygoqib.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2lothvcec.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2rwmgsbkp.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2zbaginxr.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2khgekzlr.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2xewxokgd.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2ifniquvw.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2xbtehfln.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2cpaskiqo.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2yfdaqsid.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ewvpuded.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2bhbonvvr.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uwvzutke.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nnhpbfav.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ptgqgptw.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2lfikgaot.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bgxmxphp.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2pxruesmm.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2jupawsky.html


<!-- 参考信息 -->