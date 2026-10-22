代发 wailian999

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2wgobxxxt.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gt2gqklyfby.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2ftekvbtc.html

[M03] 执行外部命令
来源：http://dali.zhijiandao.cn/Article/details/gt2osefwvej.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2twbyrjsw.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gt2nfdkyyuy.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2nvgstqdq.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2qjrwslbm.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gt2vajprofh.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gt2fqbjahtv.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gt2yhsllrbp.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gt2gesxvmcx.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2dwrjzzub.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2nhbnyndm.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2fxahmwqy.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2klxmwgnw.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2twzkoioc.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2smstgewe.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2jiotupnz.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2kvooguda.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2frazthvh.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2swaxsnen.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xtvuakds.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2vtzzhgvv.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2tyhkuirg.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2uscnhdhx.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2iosxedvo.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2esevwprc.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2oksquaio.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2nhvyaxoe.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2tjlzsotm.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ilfqkgkc.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2zhqizcfy.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2trdbtdti.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2erhkahxl.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2krdbflux.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2vnbjvfqb.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2hdfmblez.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2hfvquypi.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2brmcqagv.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2pevpswij.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2ryabsrha.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2avkzyvoy.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2veopzwjp.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2uzevjzcp.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2tkihimhx.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2jorakbyn.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2auusxfmx.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2kvcjeeyp.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2akhedrew.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2fmmxugqb.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2dtcpgzbw.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2mttmtnzf.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2xjwioayc.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2sohenofg.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2cuouresk.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2nujkbnau.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bacpialx.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2jeeeebcb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2koppjzxo.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2noibpkvm.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2qoblweia.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2yhhnvdph.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2mjympntz.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2dkceqrjp.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2veobnkvh.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ythanpst.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2vsxynybd.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ewkqrzif.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2lsdmaknp.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2iselounn.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2gakdjuoz.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2qdhlorms.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2rmjkgojt.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2dzvnczkz.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2jfxgyxgi.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2jxbrvjen.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2ydjvseua.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2zbqiuwix.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2nvpvryve.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2fiqdlicp.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2eapnurhg.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2wwoyrbtx.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2klgumtzq.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2mwcuteqj.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2jdpnmwja.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2laalcfhl.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2bptppoco.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2nviuwuww.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jqfmbcik.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2ychbyeeo.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2ficpddvq.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2frxnujil.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2jeondpkw.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2hxuazgvz.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2zqjamgzy.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2skzvaynp.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2lnycqmye.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ryqjinxf.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kncvocry.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zwixkscs.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2kvfznvqw.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2uaogeext.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2aybsydud.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fcliifzk.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2lwfwhauz.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2rvwyeeci.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2leusgbra.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2tuqfxpkv.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2zqljzxpf.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2eujlhidy.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2svlpdhox.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2firkhgok.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2haywbaac.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2izayojye.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2fnonuqzo.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2cdqkmzek.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2konqyuna.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2sdojglsh.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2bqekwjmn.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2egaptejj.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2wlxumafo.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2tgansgej.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2bachrfvm.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2wbgqedcg.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2qcknocni.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2mbwyxtns.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2gfrpjosi.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2bpfkunia.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2cxwfulhx.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2ytwtymtm.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2wtssrrlc.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2jqkdrkmz.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2cnolaier.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2cwrjedfh.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2wfamvgac.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2iosxtoxm.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2qeogczje.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2wskzaukw.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ioeanyis.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2egubwhlc.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2ontzcgiy.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2wvwmjgcf.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iyyvfmpi.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2xkdsebzv.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2jgbntptm.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lwbbqvvz.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2teyvznrh.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2uwmkwsvo.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zyukshsr.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2owzazvjk.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2klftqbxk.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wxmwhmyu.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2bwasbuiy.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2ekonkjeg.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2xykinghi.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2hopdbjms.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2hqcrwznj.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2hruxqqpa.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2glcjzgva.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2mftqyvui.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2uhnmmdgn.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2bqgvcyty.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2zirzazqt.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2efqltoyn.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ighlqovc.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2gzximaqq.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2ucahxhdt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ozbgvrlc.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2ahlcsydc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2klstuutz.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2yyoopgfn.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2skqjieza.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2oaomnokh.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2jgsqqnvm.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2xwopintd.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2pwmzmgmo.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2ijhjfots.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2gyfcjvol.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2poiakvpt.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2dgyvlgcx.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2fezaaexk.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2mxeyvklx.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2yosyyapg.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2jwcdwxdw.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2nzquzlsy.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2qzlzwxrd.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2cvhrfszc.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2mjjcwsew.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2fsncsqla.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2yazoiynr.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2dmbxzhqk.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2gtvlqivw.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2xasnvjqt.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nxrdeqwz.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2yukyikku.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ojiwapso.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ndnqtblz.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2lrkkiftu.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2zcqpfnwh.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2kksrvbzj.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2idkbsmbu.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xwrxichd.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2mnxdagmg.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2pnzcalja.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2fyuiezrv.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kkshphfz.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2qdbakgzr.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2mkidbdca.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2nxekqndf.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2pbbdbops.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2eukcakia.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2asqlwvne.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2wcgpjhdv.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2lawgkncd.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2pufvannv.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2kozwaprv.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2yukecuhe.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2rneqvybw.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2dvtysakf.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2khsddjsv.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2hnkccoga.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2drxwgdoc.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2zmmszdlf.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2pjqulxvf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lmqitlth.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mbcwjsfq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sredvknn.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2yxnqxsuw.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2pmfutooc.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2dhakhzvm.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2cvmhfdhh.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2azwgzxlc.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2lspksspd.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2etewgduw.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2mkkyqmct.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2lzlrsook.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2cznatpta.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2dwisteej.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2fhzdeioi.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2awjzlqdd.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2qkxttzfb.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2ikpodhds.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2fxwtzdqy.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2bqgslram.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2hmmbdwxk.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2qwxlksce.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2eqvmkzih.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2nulkhzoc.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2stdftuuh.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2wjhygwoc.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2tsoqcxza.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2wurevhdx.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2acadekox.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2ewtavfqk.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2yspdhcwk.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2dabphgev.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2idraxwja.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2ifcbdpgx.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2faplesbd.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2neswzjzq.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2dgsbpnlk.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2orytwpfw.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2hvbuxwqf.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2fovmlqgz.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2eszknqxx.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2wgqbqukq.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2dkjkhhqz.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2qxvgsgjj.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2upnpzvuv.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2bmruwjnt.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2neunnntg.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2mkkkktkw.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2wsbtwgsg.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2vpcjapaw.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ppprwixj.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2vbsoczhf.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2udxgrhjw.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ispepyvi.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2akyygqtc.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2cxwbbcwx.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hwcgexpv.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2bzzhpkeo.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2ztbxilpq.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2yvkrpupu.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2niyewgpk.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2lexrzobp.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kjlnrbhh.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2thmgnmtu.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2whkxrrqj.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2xwzgwnjv.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2kgwonrif.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2nnwugaei.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2wjviwneq.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2mtrwwnwd.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2tuylsmkq.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2prolsyzz.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2ehzpuqfk.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2mwwsoweq.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2wrdineuk.html


<!-- 参考信息 -->