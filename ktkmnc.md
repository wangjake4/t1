代发 wailian999

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ldzswcqx.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2yahhjosy.html

Java: args 数组（main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2wxcswmbz.html

Go:   os.Args[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2osqtfwcg.html

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gt2ehgayjfj.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2auiowkgg.html

[M02] 读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2yncjjxwe.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2agqwgpti.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2fkospmxb.html

JS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2nkwmucay.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2rdvnjlmm.html

Java: System.getenv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2kzabvbpq.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2eazaxlrf.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gt2wqytqkqo.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2lctxhdbk.html

[M03] 执行外部命令
来源：http://dali.zhijiandao.cn/Article/details/gt2gzgakakz.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2unrrxutu.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gt2rkbnxhrc.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2vkjwrhpu.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2lmykvpnp.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gt2pisaxlig.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gt2ksattvzv.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gt2vkghkmmc.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gt2vutbzlbj.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2xgwurhyu.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2dixywzsy.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2mcusnfdr.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2fvegtbuw.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2urrxsjjh.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2rotwoqob.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2fkpcsuhj.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2yelwqgxu.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2jdrydwzr.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2hurgzazh.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2vrvqraab.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2lqdvscjj.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2befkcgrs.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xvqbopaf.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2whdpecrd.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2gfdqftcz.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2wjokfrrk.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2balazalv.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2mokyaxai.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2pkfedmrk.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2ohdfuowx.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2srntefwc.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2hffyekwd.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2efeivhct.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2tlpenwok.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2srzxbaon.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2cuunynxj.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2rsxijmdc.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2epwyzazz.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2qamuxsyh.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2epymcvkz.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2ftxgonri.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2txlgnzzd.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2zotesuvm.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2ytlxpwxw.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2bxouvevm.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2dwoxeodj.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2vocfcdeo.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2byejpmtd.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2hpmzxnbj.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2ljacudeo.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2uwfkbjpw.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2ihcsmitd.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2tizlsoiu.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2lwstjfsp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hfalnktl.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2lgjholye.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2eiyuqxmi.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2dbyacpgc.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2siypbdam.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2ohdedpeu.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2ahmbchrm.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2zvxhkmrd.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2rjeqpuvp.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2rvgjjsml.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2gmlggaor.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2awrulhay.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2fwuesvqe.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2dkcfudye.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2dnszifwx.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2keoxlnso.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2wjtfohno.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2mfpxwmkd.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2pmisegns.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2lzhsmfyd.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2aqfbfncg.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2enjxdoag.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2peyqelmu.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2viobsdtu.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2wutrtrrp.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2fmjgdwwi.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2yoyuityg.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2qkcxczek.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2gtjqztfw.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2sukpbcck.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2vzqffags.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2tpvkigvh.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2recpkegn.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2ukcvrrys.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2dvlqagjx.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dqudukrs.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2egveyqzc.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2kkknqahj.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2oemzxrwa.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2vgxnlclg.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2clyavhlq.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wlohyjhv.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2spvjvtzy.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2duaiuhwe.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2lgfefgvq.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2mtpxrjnx.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2uxhyeyrk.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gqfsbiuq.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2pzhdkgqu.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2wywxmzjy.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ldfdtevv.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2ajlujmdq.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2yyrmswmg.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2kkksyvhn.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2rfgwyhsf.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2lpobqwkp.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2zkowndae.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2dbhnbjie.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2jtzcjcra.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2cunvzbza.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2eejmvqzk.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2kdbfbicx.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2mvdfstqc.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2dazrqukg.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2mkrxyarl.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2xteuhktk.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2dlibmdtk.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ysdvcsmg.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2jkqijcke.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2iecbfcod.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2mcaafvuh.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2flejhttt.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2gfafmsyy.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2ccnjhyrw.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2hplmvapo.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2sakhaxqv.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2fefeggjb.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2qdmlqvms.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2tehprbso.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2vjnfgkvq.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2twikeyeo.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2iavhjudi.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2mvnylzze.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2afejemmu.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2amdescou.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2brurtjfz.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2baooctmr.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ozzcieie.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2gfzhxcct.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sgcujuqp.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2smpntzwu.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2rtnhapbd.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2okmqnsuv.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2vnxfwgcj.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2gheezufg.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rarvaitw.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2phtwnvue.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2iktcicjp.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2eesrhvuy.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2lwhijmgd.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2isikesie.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2jfmlyoip.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2nseiodkf.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2euajjhmm.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2zukegyti.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2xlmsxyjq.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2wjvhiajl.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2eqwmanug.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ucaktpof.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2mhdbybjq.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2gfoyyvir.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wizeoahr.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2opxleyce.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qpyfmqyx.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2qetmdbzl.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2mnfadatg.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2alrpoxow.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2lokbradm.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2vhvbfzxv.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2luszgbho.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2xyqwpcsj.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2wmqimaid.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2celkcbxe.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2pvoszulr.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2zbfdmkqf.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2cwrqcvtb.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2aqtatgqc.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2qehbifck.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2umfwaakj.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2avskbcqr.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2jhijzdhg.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2lpugwjoq.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2dwtijgrd.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2gopvzdry.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2hdaojwnv.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2ctbdnize.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2uenqxedl.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aingqlhb.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2sgcwfbbp.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2jfaczmvz.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lcpnlpwf.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2ondevhtd.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2djpojqob.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2psnzvzjl.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wnmijbkx.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tizvpgne.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2sxomtxvm.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2vnskuzjb.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2pikzgacf.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2igercnun.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2qolqcwug.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2uukimhdq.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2znynwnqa.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2prgfpspz.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2zxobmhii.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2rdxscrpk.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2xltxfwjo.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2auxlvovi.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2novvhsmh.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2cgkcoiar.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2jarohpyo.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2dknatjrx.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2ppskuxcs.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2ojymbshu.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2vulrndmr.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2lewlfacp.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2ucooqrea.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2roxyjkrw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2iaeolsbq.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ydlyeflo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rxoiuytq.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2zjudofne.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2kfkwfkuq.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2dbnoojir.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2ucqxuvhr.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2wqmdvjrq.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2ciceujhh.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2umipogqe.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2tigiagvh.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2stkilxep.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2rgxgrpgk.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2ikugvdec.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2unhtammu.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2fkatcuoe.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2tkomwprv.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2cjbwsalj.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2mcfpzbvz.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2forbagri.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2luxhspod.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2fjiyjwut.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2ysnkduoj.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2tsqlqrhi.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2eqdlwirf.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2dyemrwcs.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2ysxlixme.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2euvxsnsa.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2fbslkfdd.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2mvyhgmje.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2kzpqbflu.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2jvgrjgas.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2mliidzsi.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2msuqlwis.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2cguehvuj.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2tkzvqeyx.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2wnjstriu.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2yucxpiqe.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2zlmzzchq.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2ppkwqwlv.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2bqmoolhq.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2xfpidmyh.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2fipugaiz.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2kccgckrd.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2gixbrlqx.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2dgdocbqm.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2ogclzzki.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2atrmhqfr.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2ldvnqgii.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2nsqajfrc.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kvoxcbdl.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2vzkgewik.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2grxmtthp.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fnpkeuov.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2godrwnkn.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2kgfrjctt.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bwfltzfz.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2hrlfnzrc.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2ieilqhxw.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2rfedyxvq.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2povdahxv.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2qrvhtgjt.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dyukfsrt.html


<!-- 参考信息 -->