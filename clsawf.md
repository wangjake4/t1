代发 wailian999

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gt2schbpdxf.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gt2ijvubxor.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gt2qnvomrtz.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gt2ytieshwo.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2mtlmienv.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2rqbmddfq.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2rwvxszen.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2skpdatiq.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2gqldwqew.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2incmmcak.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2gkxiszzo.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2ppcchwga.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2tktgasxy.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2sthmedfr.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2vttuqkxz.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2doszamtg.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2oqujffhj.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2usrionln.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2akqjfxgy.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2iohdrxyw.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2igljssin.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2stysvmaa.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2lasutbfq.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ryfnmctv.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2kzlkmnmz.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2lnozxhxh.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2vndnzteq.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2lghrepay.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2eghglcpk.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2wkyaptld.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2pmtwsdrj.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2sxectmzj.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2pqeqpzet.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2okkywton.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2leqkdetm.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2lxrgcwmw.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2gkrlvzti.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2wvqnrhzb.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2igridyvc.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2lflwpomu.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2gllzifif.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2sgznjsdb.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2uswrwjqe.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2ncijlatz.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2rtfgelzd.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2imbxzfca.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2gvlkfvjl.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2crhcldaf.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2rdszoxne.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2owrauaxf.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2oyotoajx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gsaoeotr.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2fpvuomoa.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2qewyzckp.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2ekyezrsp.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2ywsvzcrs.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2pelohtyz.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2bhcukile.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2cfjnrkee.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2tplbsgvt.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2qxnpkrgb.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2yvpylxkn.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2vpmpvxoa.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2eodzymtl.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2guhrmdhq.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2mrowjvid.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2uajxuklw.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2pvgkausp.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2tqjtqvpq.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2evhcpllo.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2nudmgeeb.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2xuvjuqhd.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2sshcafwn.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2tfoclcos.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2hjzmwzvk.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2oxepksrh.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2etbjrtcg.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2yfhcmzgw.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2asquxwgp.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2cfvggzxz.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2jxonmjie.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rnixxylc.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2ngcmxlzu.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2awfcbbiu.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2psnjizqm.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2enoalfvv.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2qyrepeba.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2urvaccyf.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2akqzpqqz.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2sewuyvfz.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2plzttpbm.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ijvvxvzd.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2elutixfb.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2emndkggu.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2qjmtlkzs.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2qaizuxqy.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ezuqborq.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2msjwmmdv.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2ikjoudpx.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2yvuokfnj.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2oiwjmqyz.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2tpiyerah.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2wzoqbsff.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2kgfmrtdv.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2hyafbtxb.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2byzukyfn.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2vxwdognr.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2ctqgsmka.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2ixczgwar.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2tywrgiqy.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2qgtnckmy.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2kelqnfow.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2otdwjdzr.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2jwjxbtxu.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2gikhtwfk.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2uellfbhg.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2aavuasyy.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2cecokspf.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2zhmuhpqr.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2hxuplvwm.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2owkweaio.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2nsihnjkn.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2pcbpbgrp.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2mtrzuzay.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2spelpcvj.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2uhsswuml.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2dnjrcwzp.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2tzcesmnk.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2zngsjlay.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2qziqfvfh.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2brodfmjk.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2fllquqzi.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2oaaugcwt.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2ujzmghjo.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2ghkhyjjz.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lefoashr.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2sksohwgk.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2xyhjakep.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2spkfvttk.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2ftwrjwqe.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2ifpbnuyn.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jrnfhdor.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2tsjieyem.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2fhrkeftr.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jouvyyoy.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2lxzkqlix.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2ydojzima.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2gtlywnzt.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2wtxlpcez.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2jehcsefb.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2vhogmnuq.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2rpewcptm.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2gwwbhewb.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2hcvchhoi.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2bqddrxkd.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2ugpayhbj.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2wdcdomrd.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2osnydsiq.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ilfocpvt.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2lforbhsl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tfvpxtoj.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2wdtdqwyx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dbochzwl.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2olteumma.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2bcmkcnlr.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2sbeffatq.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2mxjpgvdb.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2xktpciik.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2nqdanozi.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2nthptzhv.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2pgnppods.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2lzlrhggp.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2slbgvrdk.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2fyyxuwlw.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2ywptbpmv.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2kpltvire.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2booqtsca.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2zsknlllw.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2nrmilulm.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2keoiythv.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2tlaymcnr.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2koadzusj.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2jbmwxvqt.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2inohvjid.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2zftwyxtv.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2xzxybezn.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uxxyweka.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2ofbgsqao.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ewppqmqv.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2odoyawts.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2dkulpnen.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2xljgmiho.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2weyuwone.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wigcrgdd.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fqzgetau.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2ezdqkapg.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2pxqkjbqe.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2jzokqzqr.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2eihpayca.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2saispdss.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2wmzguuoc.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2nzpvxnzj.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2rtekpomv.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2fkredykl.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2iqmhencz.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2pxyflrsw.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2kjvxfpgh.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2zezvklck.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2venrlktt.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2widxylpw.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2rekmweod.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2yvihbcik.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2pedqilni.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2lkubdhwl.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2gucnosaa.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2tmwbrcra.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2vczjcolb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2slolvskx.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mefffsiz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mvmdiwon.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2fkanaiqj.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2qvtrtccu.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2sucyqncz.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2ojyudsac.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2aqwslvaj.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2orbbmoux.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2lpoczqxc.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2bxcivzqr.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2vjqoxbes.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2yfgqzlhl.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2dyfuiqad.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ymiqfytv.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2qsesloom.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2aduflnwj.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2kweceuoe.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2ewbloylc.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2zmejfgdy.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2uoxnjvav.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2feoczjqj.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2sgbkxtxq.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2dhfwranm.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2lixqymfg.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2nftsrvlg.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2iadpdfwh.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2sujlngzu.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2ihesktcy.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2cgcbzkpv.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2mxqaojrb.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2wakndame.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2ejwclqby.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2rtkganhz.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2jttloutz.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2rcvyechg.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2snswguco.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2sxbniehm.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2kpxxippj.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2eptduoze.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2bikfqggc.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2coyufjtf.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2sdiqktga.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2qvmrdojz.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2xobhkoic.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2pzdrtwwj.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2fwomqjvm.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2bmpaugvv.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2ecplzvew.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2ntfmrcwv.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zrjmjtsz.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2qcgmayir.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ifxfsmks.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kxiwcdxq.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yloxtloz.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2mymycgom.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qhiqyqxd.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2amclyjkr.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2wfxeczqs.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ynznphox.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ptxcxusc.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ssknsotb.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2stghxzfp.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2yxlqobmx.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2omfqvqgw.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2qdymazhk.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2rjerbznf.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2prslzxyq.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2bfvcsbxz.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2jjziwcbk.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2frgpwamr.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2jbkqpfpe.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2smxastme.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2ohcjzezb.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2rtqkdgqh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gnfegzpy.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2ijymocxg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zmadypcj.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2kzattadl.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2kbjukdew.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2yloznjrd.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2tmyfxenv.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2uwymrvar.html


<!-- 参考信息 -->