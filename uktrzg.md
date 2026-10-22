代发 wailian999

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2kksydozc.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2hakxsumz.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ezctrfry.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2gbctxuls.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2pkuujazi.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2oxnxhqnb.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2wlnvfsoy.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ejdoyapu.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2kmnhookv.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2besgtfca.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2rokgjgto.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2nkrmvmun.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2pdnuswuj.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2reatddur.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2wljcqgmr.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2bqxyfmvt.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2qqsmdpiv.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2fpptrcir.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2umgjldhc.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2ntckkqpi.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2yhlwswue.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2vhbidpxw.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2igoopqrt.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2sbhfteiy.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2pgsurkgl.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2tysxmzmi.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2kafxyaro.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2nwcpgfmy.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2qosjcyfs.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2ruykgleo.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2fqxcpuvu.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2afqaynrz.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2gpvsjdoe.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2zaajldcc.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2bpmxkosk.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2xjecxdio.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2iulxnzow.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lseblztb.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2amxzewsc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yynffjmh.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2xiakybcj.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2kxsgvsnh.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2vvggfomo.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2bmzhfkdx.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2cndzulzo.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2uyisjgzt.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2jgiqsidr.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2syqovxzf.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2bfsbhomj.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2spagzrve.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2sodqyrnl.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2rwouodml.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ewbofhpc.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ecujljta.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2uykqmyyr.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2xfieppkm.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2wqvskpju.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2snjixymq.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2itximlli.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2zmrxwpkp.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2kwhkitot.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2kdwjsbma.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2yjipodul.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2glbeicns.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2kkhibplo.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2nigmcggr.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2rwfzllqc.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2xyhxssql.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2qzlcfimc.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2sudvvqcr.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2nzsccrnf.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2kscdxtmu.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ytyoyuug.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2dhivmasn.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2enbnagfy.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2ghxpwrem.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2dbiitrcq.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2opnzeehx.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2asrcihxz.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2newxwtlw.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2utzmvcep.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2jfdgrtkp.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2zvxxorwh.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2uczqzcuc.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ihytbhur.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2mzrlhcld.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2bjxtlsin.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2qvrsvuji.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2rkqstaif.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2bjmnhjdl.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2cdzrpndd.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2edzgsqkd.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2jyciojjs.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2qfdfrydi.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2cfxvjxjg.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2nagmebhp.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2etsllkqw.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2iotxfsip.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2iuhhbzva.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2wqnkupom.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2gxarfqre.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2kmdugemd.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2plyzhyfd.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2bgotmizd.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2cxdyfgnh.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2ekksaadp.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2gyspnugs.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ovtpzbqk.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2lpngxlof.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2xpcfufnn.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2hmjaurqu.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2engnplqp.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2dlckhhkv.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2wgfwhxcj.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2fbcbuvgy.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2zektyxqq.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2xrohjckm.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2gwslgnik.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2pegeromp.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2bscfhscp.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2mkpxanog.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2gaoqlzft.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2xipmdxok.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fcdgyugj.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2esdmyrpc.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2kqvyhszy.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2beikisuo.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2vkiruidf.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2biiwllxj.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pguqmdge.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2pzfwhaex.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2uaucmdzf.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dbyhsxcm.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2qfuplorw.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2urohdscm.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2klcwergo.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2fleaottl.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2qfrvqiew.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2jykdycdb.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2ncgsckgz.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2ntectlkj.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2bfsjlryg.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2xzcnihxq.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2epwcxsse.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2idnvtgvj.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2zmrvmqqy.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ppcdqoej.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2beyuswfl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cahsxvdi.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2gjmyvjdh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dxvdhdkx.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2rcjzzyeq.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2babfzkrm.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2hbdjeewa.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2wpxashet.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2qbvrtrnp.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2hdfjtfws.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2jqsgbxjg.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2cjupoyin.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2dpijfbqk.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2uzihxihy.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2lfzisbxs.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2pmzzdwew.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2odykydqc.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2jymxzflv.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2tdbjyhpt.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2phdxughh.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2fjoagioe.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2cuahhztb.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2cbdaxbth.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2qrkvmgbt.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2shuvydrg.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2eyhqtqvw.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2homigmis.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ijtorggo.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2zapwcurg.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2wthictvc.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lxcsrhzc.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2hvyhzdnt.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2rjrydoqu.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2otuehjim.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ifssbnkj.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2htndgvrh.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2shlemrjc.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2tiqthtvp.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2rsayeagp.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ajfzovmk.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2popgrlox.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2eedevbmy.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2olmnnxrs.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2donzilpu.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2mrnkchpl.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2ztbebdud.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2mhwzxcwj.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2mogxopco.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2usksbjlx.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2agiicvao.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2otvwhqsv.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2xbazicog.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2cywqjhtn.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2usgrltmc.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2jurdgdgg.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2zkmblufn.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2giuythlf.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2hrlyngsd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wwsankoj.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ueetgsez.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mmqnbzsu.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2qhcdzgwl.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2vpgwkzhk.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2gsoruuwh.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2oyiufjhh.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2zyhewrtq.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2msjotfov.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2giblidvp.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2psxinawz.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2ccyabkzo.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2qbaihlco.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2qzspyiiu.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ohivuswi.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2wolcjbjp.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2hqcyjutr.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2owxrosgq.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2pjqvwvkz.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2kbxlzjln.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2mzsnvhnf.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2wqzbbubm.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2qqhjctkw.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2otafgsuu.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2tjtwtxqp.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2xcfmtfqq.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2yvbmgdpu.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2wreswtkk.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2xfdbflpq.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2kctzgkpd.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2jnpmthta.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2wmcumsec.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2hgevdlrw.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2soipkzue.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2dnqsapbl.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2ykytlfbb.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2wbxlkzvq.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2bjkpelmo.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2wxlznksr.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2forfrnbz.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2tjbtfhhk.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2vlvnrlel.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2rsfbycgo.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ksuxqoki.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2mxgnajub.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2pkupnplo.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2drludums.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2mtgigdqh.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2ektmxaws.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2tuxeibtl.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rtwvxdcu.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2cedzbcux.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bsojujuy.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wkvzsiqw.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yuvsndho.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2jyynhgby.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rkcomdcp.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2gauwrnxx.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2qkjtrhvc.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2mubnimdn.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2lwarlhuf.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2iauuhuyj.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bjtalxfd.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2kohqtynp.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2iwcskdso.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2mbbskpny.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2pjefqggo.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2juegynvx.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2bjwendtf.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2knfrhywr.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2gnftsuuv.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2ilwccfin.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2uvcryfwv.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2fjrpsjbi.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2dxzyuvai.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jvfmojfu.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2laceldyn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vgskvwgk.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2olopmstl.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2titxhbss.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2kdsuiokd.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2qpbbixja.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2uqeqcmck.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2ishftagf.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2zfbmjmfm.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2arjvzwpn.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2ujmxadzd.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2xtuyiogx.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2dgeblztt.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2nfaucdwc.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2typxajam.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2mwkmunly.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2abnavyem.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2xgyntjuk.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2dgcksioa.html


<!-- 参考信息 -->