代发 wailian999

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2kjycdxln.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2tdtfwtyy.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2vlszoemg.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2fxzchniy.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2tnajztif.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2fpzrlirn.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2uxrrctrk.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2fjzelpim.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2uhtpzkkw.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2wvgkukxy.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2mqjniske.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2vrdgtfww.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2bbzccktv.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2mavirfsg.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2uezumabz.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2mbubygou.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2cwkkhymo.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2zxnmfemp.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2qzdganbf.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2lipiadyv.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2xxubgkls.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2mennummb.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2quaoefug.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2vhldcdca.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2izhvdfik.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jfijirxa.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2ziscyczp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uvokzrkn.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2imyrmjng.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2qyhdtkee.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2vdfwyqtf.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2dgpfziei.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2tltigelb.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ydylcsgo.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2bhmznbod.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2adtyrggu.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2xsxgtazc.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2qmmoeviy.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2bnzcerpk.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2gkrzbech.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2xkaqdvag.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2kzzxwqql.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2jwbrkszj.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2rkehvvkg.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2zsjdsuoi.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2liuelqnp.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2kyftrddv.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2kafbaltk.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2oaeizlhn.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2qcyepmrx.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2hamdbyax.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2jdlxnvgn.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2pegdkhvr.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2ajlyqget.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2eizjcpgx.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2kuunsmji.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2fbyczfbv.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pgxvrota.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2vrjadich.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2boemkkoo.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2imjgpqsw.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2klhsjtom.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2jcoqlgkd.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2ekgojmvo.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2hfgymncm.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2sfdjbuec.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hzsfpoxz.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xgyurlgn.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fkgnkkun.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2lggwnlzb.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2dibnlebo.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2dndevifp.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zgukfgtr.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2zdrmkfau.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2fcbolfvr.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2qurhrwdb.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2hvuawjxk.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2jhfvsidh.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2ixvdatlx.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2nkmnywdz.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2mqrywaoj.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2cieeuubf.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2bfyzpgej.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2tzshznhz.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2zoiaeeul.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2zklipsjh.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2kkircdau.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2kghshrlr.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2exdlowlc.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2eidcxpon.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2sffzpkoy.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2axnhambs.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2mycljrhi.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2jvzfqlii.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2xgzxzmul.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2hduumhle.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2mduvcthl.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2gtklfeog.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2mivlnmck.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2apgxdzoc.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2encvilst.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2zcflzijx.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2fzverlla.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2nxkswtxb.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2berlnxgd.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ndhueyss.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2xemjldfi.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2zwyueofx.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2qbdpqtcl.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2ffkfowsl.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2rrpazzqj.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ckoqcojy.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2uarepkmh.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2umydkryo.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xdtwehkf.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2vfxbglgh.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2qsejxkpc.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2voyhrjwc.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2pzfdnwuv.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2qkvlygca.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pxfrecso.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2bpjmdqfj.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2ykmkwbbs.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2xxmixfak.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2mfubblac.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2auuvllvo.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2wtwzbtwe.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2pjgtpmmc.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2tmkzkppy.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2jheskmze.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2jgrnzseg.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2rjlfbvph.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2tlyqacge.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2nbodidjs.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2yvojkncw.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2szubboud.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zkirzewt.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2rzbzcxyb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ugrrpixl.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2wioappmi.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2bmblttrr.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2vgzlvlpd.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2bvlcpcsn.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2mewosaau.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2ybnkonhq.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2pwoiqiez.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2zjkrhzre.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2fxkzmfkb.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2ktuvqmvc.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2wjgrocgk.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2uemaisju.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2waijuame.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2jyunoyhb.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2ycubqysg.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2zfugrawo.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2bswqcqjc.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2qkvucwhb.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2smuepppv.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2bvplepqr.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2zmxxzziy.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2uiaobyun.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2ozrmvcww.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qokftxxc.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2ocyomivu.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2jrnplfvw.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2slarqsjg.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2nsvkrudi.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2lsybksjs.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2wghynmsc.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gabptyft.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pkitjdpy.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2psuxknjg.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2tvymplfs.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2doscjheq.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2akzxxrpn.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2nvzcqkog.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2xliusnnh.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2aatlymyf.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2fvxpufof.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2lfrjhzho.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2hbkunwzt.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2yxobjmxb.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2pwqfrmmj.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wblckoil.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2rhpzayfw.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2kbksnveb.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2eaahqwwd.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2ivwkjaiw.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2wmqutabs.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2qpklabbz.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2mfmamrsg.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2oiqoyeen.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2isqazxal.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qglbutjw.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2yosgpalr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ptvqcsaf.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2tbkpramt.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2geknentz.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2dyxutbbz.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2gnmebgql.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2ihyfomjy.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2mshekszm.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2qphkgldy.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2upwuqtqf.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhijiandao.cn/Article/details/gt2nzmyqmmz.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2jsukresp.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhijiandao.cn/Article/details/gt2mboalgxb.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ixjmsoii.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhijiandao.cn/Article/details/gt2emtynonf.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhijiandao.cn/Article/details/gt2hledcctj.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2qwlwwvev.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2gcjkrgzg.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2kdnrrqbd.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhijiandao.cn/Article/details/gt2vggjeltq.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2mgnrbrgs.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhijiandao.cn/Article/details/gt2oysgzrcw.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gt2wfouimay.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2uattiqlv.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2ayaltugq.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.zhijiandao.cn/Article/details/gt2lohrfpcp.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhijiandao.cn/Article/details/gt2bzrecovw.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhijiandao.cn/Article/details/gt2xvmuvgqj.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhijiandao.cn/Article/details/gt2abggfprv.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gt2dceebxqu.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gt2mkfaytaq.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gt2wiyphevk.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2llijkugv.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zhijiandao.cn/Article/details/gt2jaqqgwnv.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhijiandao.cn/Article/details/gt2eibxykpe.html

Go:   len(arr);  len(m)
来源：http://dali.zhijiandao.cn/Article/details/gt2hhukxlio.html

Ruby: x.length;  x.size
来源：http://dali.zhijiandao.cn/Article/details/gt2lirngjep.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.zhijiandao.cn/Article/details/gt2haospwtr.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhijiandao.cn/Article/details/gt2cbbakyks.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhijiandao.cn/Article/details/gt2dvorlazi.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhijiandao.cn/Article/details/gt2phfkqocy.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gt2rbdgmpog.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2qacducwy.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhijiandao.cn/Article/details/gt2saavlckn.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2jolwjupr.html

Ruby: a == b
来源：http://dali.zhijiandao.cn/Article/details/gt2rgqdmnvg.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2jmfndubx.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhijiandao.cn/Article/details/gt2yhdbhcqe.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhijiandao.cn/Article/details/gt2hhkqcgoh.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2exnwyyol.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gt2xlpynorh.html

TS:   if (x == null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xautgikh.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2okmvtuyf.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gt2orrulwuo.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhijiandao.cn/Article/details/gt2ofjutris.html

C#:   if (x is null) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wqteghsa.html

[P07] 防抖与节流
来源：http://dali.zhijiandao.cn/Article/details/gt2xxmdznrh.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhijiandao.cn/Article/details/gt2qwpinmpf.html

PHP:  // 手写时间戳比较
来源：http://dali.zhijiandao.cn/Article/details/gt2hahkjfbx.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2xauxpkrf.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ylshzrng.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mzqijvho.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gt2kulablmg.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gt2yxcdjarq.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhijiandao.cn/Article/details/gt2uqbjuvmb.html

[P08] 处理浮点精度问题
来源：http://dali.zhijiandao.cn/Article/details/gt2alkgoygu.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zhijiandao.cn/Article/details/gt2jitlxrcv.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2ydhwkpnl.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhijiandao.cn/Article/details/gt2zizuxcsl.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2cxdvdeig.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gt2fopnjdsr.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhijiandao.cn/Article/details/gt2ghavybrl.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhijiandao.cn/Article/details/gt2ljkhoast.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhijiandao.cn/Article/details/gt2jdccdsjg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wergnyeg.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.zhijiandao.cn/Article/details/gt2juehyfpp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lnczvhuv.html

[Q01] 创建表
来源：http://dali.zhijiandao.cn/Article/details/gt2ztipzefu.html

CREATE TABLE users (
来源：http://dali.zhijiandao.cn/Article/details/gt2epqqrtqw.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2jwzsxbca.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2kqciwerr.html

email VARCHAR(100) UNIQUE,
来源：http://dali.zhijiandao.cn/Article/details/gt2lczjvudz.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.zhijiandao.cn/Article/details/gt2jjipgiui.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2czopehhc.html

[Q02] 创建带外键的表
来源：http://dali.zhijiandao.cn/Article/details/gt2tcfriwjn.html

CREATE TABLE orders (
来源：http://dali.zhijiandao.cn/Article/details/gt2zjisklhg.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2vnxewxcd.html

user_id INT NOT NULL,
来源：http://dali.zhijiandao.cn/Article/details/gt2tgyxujau.html

amount DECIMAL(10, 2),
来源：http://dali.zhijiandao.cn/Article/details/gt2ixocckcs.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhijiandao.cn/Article/details/gt2nshsdszw.html

);
来源：http://dali.zhijiandao.cn/Article/details/gt2nhjpddbl.html

[Q03] 增加列
来源：http://dali.zhijiandao.cn/Article/details/gt2syuketli.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2lkzpycgf.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gt2kvcslphz.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhijiandao.cn/Article/details/gt2kqxdwfkz.html

[Q05] 重命名列
来源：http://dali.zhijiandao.cn/Article/details/gt2zojbmsqi.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.zhijiandao.cn/Article/details/gt2mrgeeodg.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2biynxtxp.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.zhijiandao.cn/Article/details/gt2zbekxhnb.html

[Q07] 删除表
来源：http://dali.zhijiandao.cn/Article/details/gt2vwufghay.html

DROP TABLE IF EXISTS orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2fxkfjvzj.html

[Q08] 创建普通索引
来源：http://dali.zhijiandao.cn/Article/details/gt2tfmqhbvz.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2rsgvsalt.html

[Q09] 创建唯一索引
来源：http://dali.zhijiandao.cn/Article/details/gt2vqtuegda.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.zhijiandao.cn/Article/details/gt2ppejivna.html

[Q10] 插入单行
来源：http://dali.zhijiandao.cn/Article/details/gt2hccvlphh.html


<!-- 参考信息 -->