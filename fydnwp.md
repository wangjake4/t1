代发 wailian999

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2mdycmibi.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2knrdnukq.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2pyixaisv.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2eowcrdnz.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2gznjuizo.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2rjlprqxs.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2gouczble.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2gngchuhe.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2qkcuojxd.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2pjsrqins.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ultcihix.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2mixyxppf.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2nhhovzxu.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qzlimrxx.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ybrzstoe.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xewrlnej.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2oypszzes.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2vvodmxca.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2vrfmxumv.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2nftsodua.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2fvercgsx.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2slpuexib.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2vkcflpjx.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2xoiszkzt.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2sjtmzlno.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2capcxglk.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2brasinkt.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2iofdnbfd.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2cycpisug.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2fbzscwjg.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2ccpcpnca.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2ewunlqez.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2zoiajqsh.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2bghuveim.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2xrbgzihn.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2ejhzpryp.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2tnnedmpy.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2xxdqxumy.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2evuxuwvm.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2tqqhskyd.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2dajdmmxc.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2hokbnrwr.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2bngmbkyh.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2vkzcfcmp.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2bzrfmayt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zixxrpuc.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2pxyulece.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zuemuoko.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2wqohybpm.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2yexgfrmz.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2gjykzpve.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2qsiexlul.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2effumljj.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ydqklvsm.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2pwbkkmxy.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2mmlzyuuh.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2nfwxcdjw.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2tqqaflnv.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2pltcxfnd.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2qbaxsfif.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2eyibmmhd.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2lzrmuash.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2ixtuighx.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2mlmjgyhp.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2itfpimrq.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2wpurpbqc.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2noqroagv.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2dmhgqebr.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2chunzpnx.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2znndwijj.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2zdjvdqqr.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2kmyxjhvt.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2illuyyja.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2dacxdwgc.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2sovumlbg.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2eoolbtxy.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2jzejcjnn.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ngyjifwm.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2konaawry.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2ulxrzeee.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nucdiubm.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2kzztbyyh.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2pbbpkchy.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2vnvnkqhj.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2zeyxtlgz.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2vfpqxrsu.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vqfepcyp.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2chyrpods.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2apuqnjeo.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2etlcgend.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ofwfgwht.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2bbwghtzy.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gwcytnlz.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2zknlqmps.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2yhpiohvo.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ezhqvzzs.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2sbbxqptl.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2hjmbipaq.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2nnizpbnq.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2warqgrbs.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2qrlqpcoi.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2nnzfcdkx.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2famhecao.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2cdvwelfu.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2tobuuyxz.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2zdgdajli.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2rplbpxzh.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2grqjwmov.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2lebxzxuq.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2vidtuixh.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2ncpzfnnq.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2rtnvqtim.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2kqermaxg.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2zirsqqbv.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2fjwlojoo.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2omwkldtl.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2kbuuhmls.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2jciriive.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2vmsjviiw.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2yldjoewd.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2gpwlcmlo.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2nmwjlewz.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2kvmbfvrc.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2oqpxicpn.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2mbfmecwb.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2rwcsjcvq.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2hyissxgj.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2gjtsajqy.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2hvgdvhwo.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2ncffksyz.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2boahqkgb.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dnfjtewx.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2rsdgqkbu.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2shubgigk.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2womlkceg.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2oumwxszz.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2drmxwzwh.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2otwfqoys.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ctbnzpmi.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2ibuwyqoo.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wbdvknrc.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2evpsnhps.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2wwbdmnps.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2xpzudlju.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ueforbyd.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2ckbtcavb.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2snunroma.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2nmejdcpm.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2ilhyfycs.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2jonqpcuo.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2botwgdsi.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2srlnwvjs.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2dnsmdzfy.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2hpirmxaj.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2fsspufzo.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2uahjdpcw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fnyybmvq.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2oatynqwe.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2camloacy.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2jdbmqafa.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2jfyuahoo.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2pjhfecxg.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2omrmujqe.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2psqiafmw.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2zatffnvx.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2rmfolfgq.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2cmrkpkln.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2qrrspfkh.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2ihaqdngo.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2awjmtpob.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2okcyppdc.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2ecrfvcgj.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2dbwaytmj.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2uopnxpew.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2wistbisd.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2tiqdsogw.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2aklqqsfy.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2wlyjyyqt.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2uolskrii.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2kjwbandn.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2kozynjhq.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2pbzvzlxn.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xiljpaml.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2fprthual.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2zsjosdkn.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lrpqsayg.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2lrvcccvx.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2thslyfse.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2liuyofnb.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wclqlnex.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hhdrieor.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2okfwfeys.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2ykzaotha.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2jdmvstfm.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ihcrcqjc.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2giwwcfxn.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2olkpsjaj.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2grqoopnw.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2volxwttr.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2kqufjmpj.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2niprqqwv.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2nzclujia.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2nsheziqi.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2turgqfmu.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2omwxpacj.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2nakkrkyz.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2mznbliag.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2kylzdsbr.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2sftfbtjz.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2xdzywdpr.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2wnbqvhbd.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2nwjbyyrq.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2ftorotpz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cepdbuoy.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rvnzxkza.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mndeqhnn.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2ccrctzcf.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2cvufgvri.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2dzbgnkga.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2nunjnwlu.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2urlpdvhv.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2tolrtbmj.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2oxsxhukw.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2oplvrrpg.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2ownvrqok.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2ebqmocoz.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2owwcenkt.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2yuuutife.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2altexrvy.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2clrphuzg.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2jogvnloj.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2duimdjrj.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2togqgbno.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2yjrcjuqn.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2rihkovgc.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2hrcanrfm.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2rfevmyqh.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2sraelwii.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2owwnzasl.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2iwqzbsnq.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2tfxraqbl.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2ncbemlxh.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2cvzxyzye.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2impjqlhk.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2nrfgvhzq.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2excwcixl.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2pphrgitx.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2rhwxxnrg.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2ofagzdlz.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2uxzwsidf.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2ohezyazs.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2cajhyldf.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2iunppwur.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2dywtcgsw.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2lvjlhshs.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2botbgfew.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2motxhany.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2etczxocr.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2fqhrezra.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2lgaecdkg.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2avswenkj.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2vkofoicx.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2yfwwssvk.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tqqljwya.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2akvzpzow.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hamknpfq.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zoqihifh.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wnyewjxa.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2ptsqfnfq.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hoipfnmo.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2lxktawfq.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2icyymqrw.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2plkcuzww.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2dblnfdqh.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2vcagdzwm.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zoktmczu.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2acztzkrb.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2ybtxbbpn.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2hahjayqn.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2oztnysef.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2ooxbrtxl.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2jqiahnwh.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2xnjuopth.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2tlaphwcb.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2qqxthngx.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2sckbjawg.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2ebwnnmhe.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2rebctayy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dvfxluvc.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2xqqxadcp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xnxduxuc.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2eztsraqx.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2dyumsgvs.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2kgveaglc.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2clfhmjyu.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2jcyzlxsi.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2vjmaxbba.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2gapygaix.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2gikltgbi.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2hdxqyxft.html


<!-- 参考信息 -->