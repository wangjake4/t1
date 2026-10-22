代发 wailian999

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gt2zxppwrwl.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2enleblvi.html

[M02] 读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2fgbopjkg.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2rvkmxowp.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2lwmmkhpn.html

JS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2udexmluz.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2ocllatml.html

Java: System.getenv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2enkkzlsl.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2zwkesycv.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gt2psysugol.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2fthlbdxg.html

[M03] 执行外部命令
来源：http://dali.zhijiandao.cn/Article/details/gt2dipdrrhc.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2liblcfwy.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gt2zioyizxj.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2wcrpqdrm.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2ohshmtlm.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gt2qegrvoco.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gt2ddedwuxm.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gt2onxfggjt.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gt2fjrryfes.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2xiplhznl.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2xmoloeaf.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2fvmzygxt.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2gnkfvysz.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2hqpwgswf.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2icjxhqqw.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2xgufonjn.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2rdhwhzqq.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2drjtqedg.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2caioaccs.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2oaomuiyd.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2alqofyiz.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2dbifoszw.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2szrylcie.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2itrrhnyh.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2unzfxyqe.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2lvofiwpc.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2ulatzyrq.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2aulnnhtp.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2aponrcre.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2iiwlhsgy.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2mctmxupf.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2lcchegpe.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2ddfbihim.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2lixlosyn.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2usnotwcw.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2zuerrcvz.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2aysrorbf.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2kktrqfhv.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2zkgtrkxa.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2hxxcveqq.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2hahcvfby.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2nhljpyeb.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2yfiowlkv.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2wlzacryd.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2ypqagbqp.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2knhvwget.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2excnreyf.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2sjpfwwdk.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2dotjlpod.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2baeqnzwh.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2uatgiciq.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2lzsmvixv.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2hkkonjyj.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2cmplfrqw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2csnkiqxr.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2bepwacut.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jximaomd.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2zdbooxly.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ifdlibpp.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2uceybzhw.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2ggdgbuhw.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2fuzntscc.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2vgvbcmrb.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2fxwjuchb.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2ntptyqmu.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2qtqibamn.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2sshpzcmh.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2maeupcww.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2lvabicpu.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2afhndzdh.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2gtvrmkiw.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2nthmefox.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2egdjtnbu.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2ytibyfnn.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2pepvudey.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2iujbvpis.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2vitdajoi.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2zncejgyn.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2wmmlvjco.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2rrmpxrvh.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2wunecxrp.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2poazlwgq.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2ykgibwpd.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2hefxsejs.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2gdrfonxg.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2dkuoeoxb.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2meydsvsu.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2rlvirvqo.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2nzsooauw.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mhyytzia.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2muowsycd.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2lajpafyx.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2cggnxzzb.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2zhggcfdq.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ehdqzgjq.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xrcbehyj.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rcbvbggp.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hjwkzfjq.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2ptsvcnet.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2fqxdtnot.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2guflqpmg.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vwbfasmi.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ntuionpe.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2ltobwytz.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ialbqbtn.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2cayrhtmd.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2zmkkcqkp.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2izkhyqzz.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2hcjqagzw.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2ialmngoq.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2pjijmbin.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2mrhadzpl.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2itrmysui.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2fcxdopeb.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2htxhnixy.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2asultapl.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2pgtxfdls.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2gckvipxi.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2fgtzaupy.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2xwajnqpi.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2vfplejeq.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2qeixqlbv.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2pfvidoxi.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2mkxsuywe.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2hevzftkb.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2zdemwaqm.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2qjxmuulm.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2mdowuitx.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2mxvazpma.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2gxroclkx.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2kkjmtfnh.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2qnlzsjfx.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ppokqgel.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2jnddcuya.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2hfwgebeq.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2ffuekgot.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2nxkiuplc.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2fqsnqgkb.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2rjlknakv.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2xpsuvozd.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kmstqsyz.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ydleqiyc.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2yfoswmbj.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xaiivqhl.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2pyobwhnr.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2ckaoemur.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2koukxphk.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2eprxjnvd.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2yyafhxky.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ymnnmywa.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2zdkbbdgw.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2lpzcqkgq.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2nsumhupn.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2iatiftem.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2zezccgzo.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2obgnfsiq.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2oexlgxqm.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2dydcfavj.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2edkbhsuz.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2xfieyiig.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2tncuhaou.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2cihkofbv.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2bhlygfta.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2wmvhankw.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2miclyira.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sqebyrpk.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2ejcvsbpy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gwchmslb.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2rqwmjykz.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2mpiruqzf.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ctnikfjy.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2vmztavfa.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2bpzmnjfa.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2uwfsxwme.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2sldzwggq.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2umxvnmav.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2csldurnt.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2soazjcju.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2hmisrloq.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2mtmxulvx.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2kwmrtdpf.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2fzquhbau.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2hoifmtso.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2yrokwclo.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2zawosxym.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2braljqci.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2jquiptoj.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2wdsfxjuk.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2fcaqzxfs.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2qtreqrsn.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2mnhtybgm.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qrtykqrl.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2apfyfifk.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ajfdlkzw.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xvwpihzs.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2elkwzemw.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2sjaaeksm.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2vpowcvai.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ppzorhbx.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2azbpxkdz.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2qpfenbtt.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2sftibpfh.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2kvyyfavz.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2duqiiity.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2exupwukq.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2rcofnzqy.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2mekjqpbh.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2jefoixrt.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2awggrgzv.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2sydfxhjz.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2sdetmumt.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2atjkvgez.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2zkborvum.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2juwicjzn.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2ighzsenb.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2xvumleax.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2orthsujm.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2tchfnwbn.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2gvejtqhl.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2nygmujds.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2xmbowvss.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2lsidezph.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2thrwuxmp.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lhwxxjfp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ordsejqc.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2zxyequdx.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2cqhsmxbs.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2mcmpanru.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2qwbtkcdk.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2obdqffvb.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2idntgckn.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2scfmpygm.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2ortabijm.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2qohvcnob.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2kbdsgkkg.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2rfuncitb.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2xpxyaugw.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2hfoshgmu.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2rhdkzojb.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2jckjznzt.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2wqozewpu.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2qtkhjrwn.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2xiubfczu.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2zfmeeygu.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2bblsmsed.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2qbnslvzv.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2liisohag.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2zcuxpqig.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2gtcfvend.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2lbtgjypi.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2iggrloqi.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2sfzshwyj.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2pqztmbgj.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2obzrhtye.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2iouxddck.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2eoqsedaz.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2uuuciahn.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2alfltiqn.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2luiafanj.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2rqqvqrtb.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2jizyihgf.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2uitoiwrq.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2fzzegokr.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2mgtnarnm.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2frhbdtiu.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ftmzdign.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2ctluvwnv.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2cgloollo.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2euqljprl.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2yyjknkoo.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2ihhyelgf.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2rsaehlkd.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2svraijmi.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2jvvwtuxz.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sheulrhl.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tupxvxfa.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hsdghdxi.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2ozrjrcny.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gojecwai.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2uvfdyhpe.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2iccrjhcr.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2yoolsheo.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2xmxinvhp.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2gmzvevqe.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vualszbq.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2pyhygkkd.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2lgqewxzf.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2uxiiwvyc.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2elehqmxz.html


<!-- 参考信息 -->