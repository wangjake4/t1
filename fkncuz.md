代发 wailian999

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2wufdooub.html

JS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2bdekxbbn.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2egevpxkx.html

Java: System.getenv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2bbcztdax.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2frpryxvm.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gt2ynwytbpp.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2ewxueesc.html

[M03] 执行外部命令
来源：http://dali.zhijiandao.cn/Article/details/gt2fomccqsv.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2knfqermv.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gt2hfnufsrg.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2tqwdifau.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2vbaspukj.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gt2iptgykxr.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gt2gwusnubs.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gt2llmftpvd.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gt2rqmeysag.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2yqguxowj.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2rkcixdwm.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2bvfztyhk.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2qxxnbedj.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2mcwxfmhd.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2silycdna.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2wvxtnaep.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2ajljvmhe.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2pfanvlyf.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2hucvahvq.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2bxqvcuyz.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2uzfvjwsw.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2uphpsqon.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2vatfnxuh.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ynjrircn.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2yqjfhvna.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2gnkpyghv.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2wmkaseij.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2yrlehani.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ntvpgwlg.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2otzppuzc.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2gunxwzjx.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2qxvegbno.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2mnvtbwcb.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2nheoroke.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2epshwuum.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2psuksfuo.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2geayvwai.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2nerjeyum.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2lqfzcnua.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2sftszfkv.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2lszslyvt.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2dvxvlmje.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2luhnqqlf.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2fmnszfom.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2ajiqpsmh.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2nuwpfnkh.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2xljswagk.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2swyccixj.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2mehcszne.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2rtpsdcmm.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2cnoachdh.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2fdprijql.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2mojuokjx.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2gxdsmnhe.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gqhirsfb.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2grtqjnbk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zwlzrais.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2jdqjmugg.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2bibtlhqs.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2rdfslvgs.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2icggdphb.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2mlixmvlo.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2lxsahxzs.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2fsahpali.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2eonsoqud.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2wpgavtbj.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2shuwfcgv.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2fuodknyd.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2znaanxcf.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2gpmtcwlw.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2imkwnpcr.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2odkayzhf.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2tzxhqbon.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2kjwjdljs.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2keolgsvt.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2zvaeamyg.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2vlunnfyc.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2myeonurk.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2sseauvef.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2bcsggzba.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2kwcscfsz.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2pgccpcpo.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2lbvpynod.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2dsqigokj.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2mhyycsxx.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2mscyupcu.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lxdytzhp.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2ldiasvzp.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2bsogifex.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cwqyjeok.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2neqnevyu.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wtierwnv.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2xlvldnxp.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2ogaggxoe.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2fhziygxc.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jyxqjyru.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2psyjyaat.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jtatuaxs.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2vrhqmlvw.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2zmnalhcw.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2loppnces.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2oqvigwuy.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2neffnump.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2radhpleq.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2kwghagrk.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2gjprwshc.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2npgjagpq.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2xpalbckm.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2njyydwwt.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2jxyqhvtw.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2awwfopew.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2gciplixp.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2bgnwgsrt.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2iuuyytwt.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2biadvdda.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2hpqedxne.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2wmmwxpbw.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2bffnrkbz.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2bqjpgrsk.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2zvbpcpzo.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2zutjrpzh.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2lwxpolrn.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2rdjvtgoy.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2qkzgmrlg.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2vahwaqfg.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2byuahyme.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2tmgrmbju.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2sbbxagna.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2vqaafkzt.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ltmevkei.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2tepmpokd.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2mitxgvuh.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2mtevvevp.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2azovqtpy.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2xtecrzee.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2ypqpsxom.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ktweajxb.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2ipigtsvp.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2kufcuytb.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2pupsyouu.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lptuzvqw.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ppuvhzlq.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2apffwwxm.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oddnzlen.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2npgchpic.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2aegvmamb.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xwsrhmmf.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2kxfunght.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2wlqfjmsh.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2cnaphiir.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2ozsrcgcb.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2imecvixj.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2etcntdre.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ezkgnjrh.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2eshtjgon.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2lmnlanxb.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2tacpinze.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2zeeajnqq.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2rvlzbacz.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2cibsnffc.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2anapkcqk.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2olouizuk.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2uwexgrjt.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ybajsvuo.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2bwlmhizb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fzjbdomo.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2ardwbyrn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tptgejbm.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2bpytziyq.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2ybjjiemu.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2dfopshnm.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2mvhmmvzk.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2evzffcfr.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2fsnocryy.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2lbcjpwch.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2sowygkpq.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2jpovkiqm.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2uveqrcur.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2irndgtjv.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2kasdyiux.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2umyispvo.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2embqwzwe.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2msegkmau.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2rrvwppgq.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2alcxcaae.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2zvfqqfdb.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2ecemiomb.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2kwqkpygp.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2tpspdnkw.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2noavneak.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2khydbecy.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gualchgg.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2cpgeeipv.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2eukfylni.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jjnyskxw.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2emnvgnha.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2jafberwm.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2bkdahygn.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gejpjzjm.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hepvjaaz.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2yvexnahp.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2vnnknhxl.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2aadzpbxv.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2znvxgzfy.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2pvdrsfsh.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2scmxtrfj.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2uwrinekc.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2jeudtrrg.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2cixvletm.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2dxmtvwnw.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2pdwjctfh.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2gpvdqbdk.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2cczeywfu.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2lwcpnfvm.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2wpgxxxbh.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2kdnrakfc.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2bntbcivw.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2jxjotvro.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2wzodhodw.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2lvvoanbk.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2jfrnqvtr.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2hjfejecs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ojkfvjiu.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fqkwvwcl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fnazwnny.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2jnpmkzkq.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2eawkoegu.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2elpfajsv.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2urliuwup.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2xwqjgmyc.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2xvqmaidp.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2wrxvvxek.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2wufdpmud.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2xvdwmfpu.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2gkyaanda.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2bwhuegsa.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2fcztxqwk.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2xymjibpp.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2eenjhexs.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2ideqbqnn.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2uimqnpux.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2pwpddibp.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2ungyehns.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ehcqatwm.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2voxxqhzd.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2khslmlgg.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2byxzvwyl.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2bhkjsnsr.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2yvbwltih.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2oarheovt.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2nlesiwqk.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2lldzizei.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2pyclnwmj.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2apwvhrkg.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2ucqgiagd.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2xefrpmzd.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2vhppbbcg.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2zwdpdjnm.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2hvvhhnrj.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2zztixdjh.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2ondkhdry.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2zkesfjmc.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2tywjgeze.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2jzljkytd.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2fgbudfmb.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2jfrgtpoa.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2zchesvpd.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2qpyzzwxh.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2otydkybw.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2nyezqpyb.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2omjmtxhi.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2ynwnjges.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nxrzwmkj.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2ceqnpkhp.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2puxxfoee.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kyfhfspn.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ftdibrgb.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2yootymuu.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2abektemd.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2cruvzfqu.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2bbucpjsx.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2lswronrn.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2pljqzgiu.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2hkzimpxe.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2orxvttsz.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2ugezwbno.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2suojwzhl.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2mrllwwzq.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2ggbtwvmo.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2eeghodus.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2ubtoqint.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2fzvedffr.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ftckipjb.html


<!-- 参考信息 -->