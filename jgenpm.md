代发 wailian999

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2cpyjigal.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2ibjzrdzw.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2zgbbuakz.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2ihzopogj.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2jfhmwoit.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2vffyzbli.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2dmabxpnm.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2cinxsvzq.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2rlzymstv.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2hhvvsgoq.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2kcfpmyfo.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2vfhljhhm.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2iafzgkpc.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2nbrrboom.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2xiqcfhbj.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2jcfafxsi.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2lxlgznvm.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2zrirafiu.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2ckpqttzd.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2khymahva.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2eolfungj.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2rlxngzmy.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2jfuzbzbh.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2gtnfqykt.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2qnisjtfp.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2brevpwiu.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2lspjtvzk.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2hkdwrrwy.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2oekquwak.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2dpdvncmt.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2rtidyieh.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2pxzerhzp.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2dkqxyrxa.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2oayeqiew.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2klkwbxup.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2qmnmxjrt.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2mwubqhij.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2gqlxuiwq.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2cnbttzqk.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2qkayvdql.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2wrqrnzay.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jtbhyilz.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2rfkfksfb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2blnkhcdr.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2bplwjlji.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2csdifqil.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2youvhxrb.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2bxmgkojm.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2qdqjisad.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2kzsymzrz.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2vpzrkghi.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2fjqdatbh.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2rjwssjyk.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2mqunrwxv.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2vuspusok.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2joetmart.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2hjacqaov.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2hoaxihqt.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2kybszoop.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2eufuwnep.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2jndbfhvp.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2gupnepqq.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2ixlcmjvk.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2hszhagla.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2hqehtqeg.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2aekfugxx.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2ndtoitty.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2ldjyrtax.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2lhsjyjuk.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2nwfvachw.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2ryzjspar.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2vhupimuh.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2tdbcsvqs.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jpynakdv.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2rkrophqv.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2oaxjalox.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ylgwmdll.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2mdwnanmq.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2aomphcdh.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2hcojgypu.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2jwexthji.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2nfbpjmod.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rkbvwxop.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rpwttikl.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dzkavjpy.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2qfultxdd.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2jkjwmwoj.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2lcanknrt.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nxeirbbk.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2mhfzgthe.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2rtewrgay.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2nnlswiyg.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2aihnvpep.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2uvdhwnbn.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2wzanbzlj.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2jbxdpvhi.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2hqqonshv.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2tzxjcjlo.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2ewpuprdo.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2ncsikaqe.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2xbnghsmf.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2kwzbxjsw.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2bijnyhby.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2ywvorkzc.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2adbdocjm.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2ksxkbxmx.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2xeeplbcm.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2brrdokfp.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2bbzmomdh.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2fbqgugxe.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2odercyki.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2cltkxhhp.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2qdkazumj.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2imffmjyd.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2fecpcdyg.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2qcahycey.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2mupgpszg.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2utyatvdw.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2nmvrjeem.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2xncqcjod.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2uhafufbg.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2cezluvco.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2eashuiie.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2cocikjln.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2lulthtdx.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2cjovjvlf.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2bwiwtdjp.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wlsbzqgg.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2cbajirax.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2aqfdmfyc.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qqywgntg.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2oufjlujp.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2wnedsixo.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mxdascmw.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2urwnlnab.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2lictwilr.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lqjdbnko.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2hmtsjatj.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2vpvuwzdk.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2encpcglt.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2rjqvalfp.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2icppqidc.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2paubemso.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2rgewlzrp.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2gbuxkrkq.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2pfterval.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2ygjpckgd.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2qvvdcurz.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2hmxpareg.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ngchnare.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2alkmqotq.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2hdwnuvth.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zwelqjef.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2daxuefsc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pjotfdnx.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2aqhabzvw.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2vjbjfscq.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2yhybrwfp.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2szlixplo.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2qbryialr.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2eihzorux.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2ekvfivix.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2tzspmgrl.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2llttfmly.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2nxduukyu.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2fofmbyuf.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2rxqfijkn.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2oaqgkzuh.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2nmohuisi.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2dszcaios.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2zdhrdtgt.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2nsolxkpv.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2mthkwmpd.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2mvulwlor.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2wljdciag.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2kjeuevyr.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2wfjiwoht.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2zesigsmg.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2soaxaqrf.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2qweyvlxc.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2rhqvwaqm.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vbgjloqm.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2lftrgovb.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2bkmjfenu.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2nearhtao.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2uxyhqqbg.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2easislce.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2sctlwknr.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2wmzivohu.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2cuvjgang.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2oozimadj.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2kkxenafe.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2ecdimurt.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2mzzudlob.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2prrxcjsd.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2hwzvypwk.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2uwqfxxly.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2ibemyufr.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2wvhxgrgv.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wucqpupo.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2tvreydkj.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2dlzuzbfw.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2vamggsnb.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2qiatccsj.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2knabxlyq.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2jsbcxmnp.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2rmirvkel.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2frtfscqh.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2pivqqwob.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sbcbknth.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2eipcxjww.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nixdiism.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2ikgckczv.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2klvqqqkk.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2yiqvbhwu.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2bjscfwph.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2ghyyzwjv.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2uhlpihsq.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2bvydgmxh.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2ffkaoppy.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2bgxvgiia.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2maivcuwq.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2htgetatc.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2huvhrdkh.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2awjzznru.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2ltaokhpg.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2pfnmsrux.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2uwkkrjlq.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2belmonsq.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2jntbaivw.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2nqmwxpdw.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2wadznvcz.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2kwzlqdzt.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2eixosszy.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2uacuxrzp.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2bycrgryr.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2mqafzqcd.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2lswjazhp.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2juamddoh.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2fwdlzrpv.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2knrxesbl.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2ofdphila.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2kjbuaerl.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2klyzozjd.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2liwigxle.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2gjtinhcu.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2wlnykfxv.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2uubngrjj.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2byobrnfc.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2vfpwvcuu.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2zjueyzjp.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2vnzktuax.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2emroptur.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2mkvgfdjk.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2gmixfaoe.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2xvkisqsc.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2tfaurfve.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2vmnkmnpk.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2melsmkdw.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2isejdomu.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2wvhjxhud.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ifjwqjgs.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uilmldfm.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zgeuiabw.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2fsscrnbf.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2exxxjqna.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2jzqmkzim.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2arrtzpaa.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2xdqwqfba.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ifvcwtny.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2mfcatlbw.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vkcxovpb.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2gyfeiopg.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2lsbczjmy.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2eqdwjleo.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2moumyits.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2hcjwvyhd.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2frcdxmfe.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2fuknsliu.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2kbrurged.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2voiwukdw.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2gyxpqhzb.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2iraaqvni.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2qeawgaaw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pteqtrvi.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2vhhngqxy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ykvqcent.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2vtygyffw.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2gffixhtr.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2mkyxghsk.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2aglxjvpb.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2hntngcch.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2juadpgkc.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2mhhjdwot.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2hhpmfjba.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2fcvsvfgb.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2lupueame.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2oqukcjzz.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2sniqcpbn.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2ooujmrmu.html


<!-- 参考信息 -->