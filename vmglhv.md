代发 wailian999

C#:   Directory.GetCurrentDirectory()
来源：http://dali.jinqigfzy.top/Article/details/gtszbxqcly.html

[M05] 设置退出码
来源：http://dali.andypj.xyz/Article/details/gtujsewnav.html

Py:   sys.exit(1)
来源：http://dali.daria6918.cn/Article/details/gtsmnyhezj.html

PHP:  exit(1);
来源：http://dali.tian-w.cn/Article/details/gtzcqzgzxe.html

JS:   process.exit(1)
来源：http://dali.pycfn.com/Article/details/gtkqvnclzx.html

TS:   process.exit(1)
来源：http://dali.chenjidiqi.icu/Article/details/gtfqrvyaul.html

Java: System.exit(1)
来源：http://dali.hywenlv.cn/Article/details/gtjltpaxwj.html

Go:   os.Exit(1)
来源：http://dali.hnqzz.top/Article/details/gtzcqoossf.html

Ruby: exit 1
来源：http://dali.ybcxt.top/Article/details/gtodwsytok.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.fengsongda.top/Article/details/gtxpimpzbs.html

[M06] 向标准错误输出
来源：http://dali.gaohongyu789.top/Article/details/gtsobjdwmg.html

Py:   print("err", file=sys.stderr)
来源：http://dali.svipenyu.cn/Article/details/gtqqwvmsmw.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.fzhhl.top/Article/details/gtyxarcjsb.html

JS:   console.error("err")
来源：http://dali.fzhhl.top/Article/details/gtodnrwitr.html

TS:   console.error("err")
来源：http://dali.havefunace.top/Article/details/gtalfuapin.html

Java: System.err.println("err")
来源：http://dali.tian-w.cn/Article/details/gtxptvznsj.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.tianlin.xyz/Article/details/gtruyitwmi.html

Ruby: warn "err"
来源：http://dali.hywenlv.cn/Article/details/gtzmsoobss.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.jianghu66.top/Article/details/gtzjkjmyzj.html

[M07] 判断是否为主入口
来源：http://dali.feifeiyinyue.top/Article/details/gttkudrjhh.html

Py:   if __name__ == "__main__":
来源：http://dali.ppjwa.cn/Article/details/gtinybqrii.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.wangshuangyany.cn/Article/details/gtyqzgvsij.html

JS:   require.main === module
来源：http://dali.ybcxt.top/Article/details/gtmmrnzomz.html

TS:   require.main === module
来源：http://dali.jinyuanbaomall.cn/Article/details/gtofhkaukw.html

Java: public static void main(String[] args)
来源：http://dali.cqqwz.cn/Article/details/gtcxqsdojv.html

Go:   func main()
来源：http://dali.daxiang520.top/Article/details/gtrloemabw.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.xuanzx.com/Article/details/gtesbvahfg.html

C#:   static void Main(string[] args)
来源：http://dali.jinqigfzy.top/Article/details/gttzptxkgp.html

[M08] 获取系统与运行时信息
来源：http://dali.ydzc1.top/Article/details/gthvntbjbi.html

Py:   platform.system();  platform.python_version()
来源：http://dali.shzxlz.cn/Article/details/gtksepmpbg.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.birdmap.top/Article/details/gtnaolcirm.html

JS:   process.platform;  process.version
来源：http://dali.sysykeji.top/Article/details/gtgtwocarw.html

TS:   process.platform;  process.version
来源：http://dali.hammf.cn/Article/details/gttbiwzdkc.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.feifeiyinyue.top/Article/details/gtecgirpte.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.nanxinkj.top/Article/details/gttgtbvewa.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.shangyingyoupin.top/Article/details/gtewsfbajr.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.shanyushiyangtech.top/Article/details/gtstmwrfad.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtdmkfttjd.html

N. 数据结构与算法
来源：http://dali.smart0.xyz/Article/details/gtsaacmwnx.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtwzuyemvu.html

[N01] 二分查找（有序数组）
来源：http://dali.yj20258.top/Article/details/gtgosjgoct.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.sysykeji.top/Article/details/gtqdggedra.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtblaybytp.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hywenlv.cn/Article/details/gtgzkvdbbi.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.daxiang520.top/Article/details/gtbejxrinn.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.tianlin.xyz/Article/details/gtgtqiqtdd.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.cucudq.cn/Article/details/gtfrblhfuj.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.yanxiufei.cn/Article/details/gtihupkgof.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.hnxiangtu.top/Article/details/gtffuiisfm.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhixingplan.top/Article/details/gtrcesvcwm.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.ivvv.top/Article/details/gtzwxyzeij.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.wangshuangyany.cn/Article/details/gtcjnhweae.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.9152youxi.cn/Article/details/gtehfqlldr.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.meibo888.top/Article/details/gtevcrjubn.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.yangfankeji.com/Article/details/gtcwldfepd.html

Go:   slices.Sort(arr)
来源：http://dali.c1oappe.top/Article/details/gtkmdfmhyp.html

Ruby: arr.sort
来源：http://dali.meibo888.top/Article/details/gtluwicsve.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.fzhhl.top/Article/details/gthgqhudel.html

[N03] 快速排序（分治示例）
来源：http://dali.gogol.net.cn/Article/details/gttzkdrbvu.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.sysykeji.top/Article/details/gtxkuiewkj.html

PHP:  // 递归实现，或用 usort
来源：http://dali.gaohongyu789.top/Article/details/gterpfujia.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.kuanghao11.cn/Article/details/gtxkanpkch.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yvedp.cn/Article/details/gtizrrcniq.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.tianlin.xyz/Article/details/gtcecwfoki.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.shzxlz.cn/Article/details/gtwdfcsowt.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhiwuduotai.top/Article/details/gtqicxnogq.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.tanke756.top/Article/details/gttpzdhdpb.html

[N04] 斐波那契数列
来源：http://dali.wangdashe.top/Article/details/gticaqsecd.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.sweek.top/Article/details/gtsidufhni.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.jianghu66.top/Article/details/gthzzonkpv.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.havefunace.top/Article/details/gttobsdpds.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.pycfn.com/Article/details/gtczzyoiub.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.guowangkeji.top/Article/details/gtoguwmizy.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.chenjidiqi.icu/Article/details/gtnzwjfbqb.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.yj20258888.top/Article/details/gtxrblwpuj.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.shuidangran.top/Article/details/gtovkugosy.html

[N05] 最大公约数
来源：http://dali.0kj1m.cn/Article/details/gtvltikzqc.html

Py:   math.gcd(a, b)
来源：http://dali.jqgfzy.top/Article/details/gtwnipbdcx.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.dashuyun.cn/Article/details/gtjzgqouyv.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhongyouzk.top/Article/details/gtgemhsfve.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvpcohnez.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcwkcrdny.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.shuidangran.top/Article/details/gtmatizypw.html

Ruby: a.gcd(b)
来源：http://dali.nanxuanxn.top/Article/details/gtjdyrpyxv.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.iojbl.cn/Article/details/gtfocnmeel.html

[N06] 判断回文字符串
来源：http://dali.zhixingplan.top/Article/details/gtmcwmrcsv.html

Py:   s == s[::-1]
来源：http://dali.cqqwz.cn/Article/details/gtvzechcpw.html

PHP:  $s === strrev($s);
来源：http://dali.aibaodan.cn/Article/details/gtggdwtzyz.html

JS:   s === [...s].reverse().join("")
来源：http://dali.yuxming.cn/Article/details/gtlemmzpxp.html

TS:   s === [...s].reverse().join("")
来源：http://dali.mhx1999.top/Article/details/gtcmhxinth.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.snrcjt.cn/Article/details/gtcvudfzbw.html

Go:   // 双指针从两端比较
来源：http://dali.hongshengwenyu.top/Article/details/gthxznbrxo.html

Ruby: s == s.reverse
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyrxsxaxh.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.kuanghao11.cn/Article/details/gtgoapsbfq.html

[N07] 两数之和（返回下标）
来源：http://dali.cdnleiting.top/Article/details/gtavarcbou.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.gogol.net.cn/Article/details/gtfvdufslk.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.nanxinkj.top/Article/details/gtwyzwjbpp.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.cqqwz.cn/Article/details/gtkyhyjzra.html

TS:   // 手写 Map<string, number>
来源：http://dali.yanxiufei.cn/Article/details/gtkndpvbpf.html

Java: // 手写 HashMap
来源：http://dali.shzxlz.cn/Article/details/gtecbuavuv.html

Go:   // 手写 map[int]int
来源：http://dali.sweek.top/Article/details/gtikvezory.html

Ruby: // 手写 Hash
来源：http://dali.chenjidiqi.icu/Article/details/gtbhmggokr.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.jqgfzy.top/Article/details/gtkwwhjlku.html

[N08] 生成全排列
来源：http://dali.daria6918.cn/Article/details/gtgdzvvlkl.html

Py:   itertools.permutations(arr)
来源：http://dali.pengpengdd.cyou/Article/details/gtevclzvbo.html

PHP:  // 手写递归交换
来源：http://dali.xuanzx.com/Article/details/gtaisxfzts.html

JS:   // 手写回溯递归
来源：http://dali.snrcjt.cn/Article/details/gtxweoyzrk.html

TS:   // 手写回溯递归
来源：http://dali.gaohongyu789.top/Article/details/gtegnsubrh.html

Java: // 手写回溯递归
来源：http://dali.yonumen.top/Article/details/gtrdyelppj.html

Go:   // 手写回溯递归
来源：http://dali.pengpengdd.cyou/Article/details/gtlughzxsc.html

Ruby: arr.permutation.to_a
来源：http://dali.jiagoushi.top/Article/details/gthzfikhpm.html

C#:   // 手写回溯递归
来源：http://dali.smart0.xyz/Article/details/gterqxboii.html

[N09] 栈与队列
来源：http://dali.sufxvd.cn/Article/details/gtqyctfaoj.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.316326.xyz/Article/details/gtaurgbszd.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.dashuyun.cn/Article/details/gthamycpzg.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.0kj1m.cn/Article/details/gtuanqkklo.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.shanyushiyangtech.top/Article/details/gtwlziflnb.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.chenlongwang.top/Article/details/gttjksgabh.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.9152youxi.cn/Article/details/gtgnpruefl.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.gogol.net.cn/Article/details/gtdgmfzbit.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.chenjidiqi.icu/Article/details/gtrhvbgcyc.html

[N10] 链表节点定义
来源：http://dali.tanke756.top/Article/details/gtwnfyhuek.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.bjfxy.top/Article/details/gtehyzozqz.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.gaohongyu789.top/Article/details/gtfqzmqpuf.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.yj202588.top/Article/details/gtalzhwdlj.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.guannengcc.top/Article/details/gtachkcuxy.html

Java: class Node { int v; Node next; }
来源：http://dali.fengsongda.top/Article/details/gtwpjneves.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.xinyue.icu/Article/details/gtrnxusdhp.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.yangfankeji.com/Article/details/gtiqfruolk.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.cucudq.cn/Article/details/gtrnofgrqs.html

[N11] 二叉树中序遍历
来源：http://dali.shangyingyoupin.top/Article/details/gtdniubycf.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.sxryk.cn/Article/details/gtxzwadpfl.html

PHP:  // 手写递归函数
来源：http://dali.pengpengdd.cyou/Article/details/gtojwpfxsf.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.birdmap.top/Article/details/gtyimjjjlm.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.meibo888.top/Article/details/gtxytjebxk.html

Java: // 手写递归
来源：http://dali.daria6918.cn/Article/details/gtynyjuroi.html

Go:   // 手写递归
来源：http://dali.gotoacloud.top/Article/details/gtequmrdlr.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.shuidangran.top/Article/details/gtdqtndnqj.html

C#:   // 手写递归
来源：http://dali.jinghuilouyu.cn/Article/details/gtqbkeahev.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.yvedp.cn/Article/details/gtnfosxpmv.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvdioxasp.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.jlsjyb.cn/Article/details/gtstbythfs.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.ehwqpu.com/Article/details/gtozzpshnp.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.ehwqpu.com/Article/details/gtvtnygmda.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.sweek.top/Article/details/gtwnjhscka.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.jqgfzy.top/Article/details/gtcjwqvoge.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.jinqigfzy.top/Article/details/gtclsgewrh.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.nwbrower.top/Article/details/gtruriwjyx.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtiksueahg.html

O. 并发与异步
来源：http://dali.gzhubu.top/Article/details/gtidabbrac.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtfoqwhmaz.html

[O01] 启动一个线程
来源：http://dali.9152youxi.cn/Article/details/gtaiqfrjze.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.birdmap.top/Article/details/gtlzhczben.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdxdmijqf.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyghlncku.html

TS:   // 同 JS
来源：http://dali.daxiang520.top/Article/details/gtcqocgvmk.html

Java: new Thread(() -> f()).start()
来源：http://dali.jinghuilouyu.cn/Article/details/gtewfxluzp.html

Go:   go f()
来源：http://dali.wangdashe.top/Article/details/gthersfhvr.html

Ruby: Thread.new { f }
来源：http://dali.ppjwa.cn/Article/details/gtrpcgpvkt.html

C#:   Task.Run(() => F());
来源：http://dali.316326.xyz/Article/details/gtfukkxdtq.html

[O02] 使用线程池
来源：http://dali.jyoumei.cn/Article/details/gtbgpkdbbi.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.0kj1m.cn/Article/details/gtefeewedh.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.yj20258888.top/Article/details/gtyimjwxjq.html

JS:   // worker_threads 线程池
来源：http://dali.haohaochexian.top/Article/details/gtoxzszrob.html

TS:   // worker_threads 线程池
来源：http://dali.shangyingyoupin.top/Article/details/gtepurxhyx.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.tian-w.cn/Article/details/gtowflwziq.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.jqgufenzy.top/Article/details/gtjccodbuh.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.yanxiufei.cn/Article/details/gtmabaupsb.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.chenlongwang.top/Article/details/gtmvifntwp.html

[O03] 加锁保护共享数据
来源：http://dali.zycfv.cn/Article/details/gtrpnusosp.html

Py:   with lock: shared += 1
来源：http://dali.9152youxi.cn/Article/details/gtsaajkyqw.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.hywenlv.cn/Article/details/gtgmzlatrj.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.cqqwz.cn/Article/details/gtwzwpmucy.html

TS:   // 同 JS
来源：http://dali.zhiwuduotai.top/Article/details/gtlbcavafd.html

Java: synchronized (this) { shared++; }
来源：http://dali.c1oappe.top/Article/details/gtplqlmpfe.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.aibaodan.cn/Article/details/gtgixvteaf.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.meibo888.top/Article/details/gttshaywtu.html

C#:   lock (gate) { shared++; }
来源：http://dali.yuanzhike.top/Article/details/gtpbccctpo.html

[O04] 定义异步函数并等待
来源：http://dali.tanke756.top/Article/details/gtrlqiddfx.html

Py:   async def f():⏎    await g()
来源：http://dali.quarkkingdee.top/Article/details/gtshxaluep.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.0kj1m.cn/Article/details/gtjrsrocnn.html

JS:   async function f() { await g(); }
来源：http://dali.zhengqikj.top/Article/details/gtmsbtdjkm.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhengqikj.top/Article/details/gtbdwniuld.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.daria6918.cn/Article/details/gtymakpkat.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.nanxuanxn.top/Article/details/gtnmrqckri.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.nwbrower.top/Article/details/gtnjtfyyoe.html

C#:   async Task F() { await G(); }
来源：http://dali.yueranfly.top/Article/details/gtpdjrpyju.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhoulong.xyz/Article/details/gticxizlqd.html

Py:   asyncio.gather(*tasks)
来源：http://dali.nwbrower.top/Article/details/gtvjknkwop.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.nwbrower.top/Article/details/gtstimposs.html

JS:   await Promise.all(tasks)
来源：http://dali.kuanghao11.cn/Article/details/gtjzpmaaub.html

TS:   await Promise.all(tasks)
来源：http://dali.snrcjt.cn/Article/details/gtmatetiyy.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.hammf.cn/Article/details/gtzfkxrztw.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.c1oappe.top/Article/details/gtzlepqbkb.html

Ruby: threads.map(&:join)
来源：http://dali.shanyushiyangtech.top/Article/details/gtjgpnrxcf.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.chenjidiqi.icu/Article/details/gtdpratydd.html

[O06] 使用进程池
来源：http://dali.c1oappe.top/Article/details/gtfrskcclz.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.vqdsnc.cn/Article/details/gtlilyyuzj.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.ppjwa.cn/Article/details/gtikhziolm.html

JS:   // child_process / cluster 模块
来源：http://dali.andypj.xyz/Article/details/gtdsneqdmf.html

TS:   // child_process / cluster 模块
来源：http://dali.snrcjt.cn/Article/details/gtuvcfbmac.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.haohaochexian.top/Article/details/gtunrzvcxq.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.nwbrower.top/Article/details/gtyfjlaxrn.html

Ruby: // fork 块
来源：http://dali.gogol.net.cn/Article/details/gtstkozroz.html

C#:   Parallel.For
来源：http://dali.yj202588.top/Article/details/gtwonnxhbr.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtouvkvdnd.html

P. 常用工具函数
来源：http://dali.fengsongda.top/Article/details/gtifwrmekj.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtpkwlplff.html

[P01] 生成 UUID
来源：http://dali.kuanghao11.cn/Article/details/gtyhezpnzz.html

Py:   str(uuid.uuid4())
来源：http://dali.chenjidiqi.icu/Article/details/gtrvfzkxyp.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhongyouzk.top/Article/details/gtfezoggzx.html

JS:   crypto.randomUUID()
来源：http://dali.daxiang520.top/Article/details/gtzhxmzxyv.html

TS:   crypto.randomUUID()
来源：http://dali.ehwqpu.com/Article/details/gtoeccpuux.html

Java: UUID.randomUUID().toString()
来源：http://dali.iojbl.cn/Article/details/gtxhkquutw.html

Go:   // 用 github.com/google/uuid
来源：http://dali.dashuyun.cn/Article/details/gtokxhlawi.html

Ruby: SecureRandom.uuid
来源：http://dali.smart0.xyz/Article/details/gtebrlvpig.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.hnxiangtu.top/Article/details/gtzmqttbpd.html

[P02] MD5 / SHA256 摘要
来源：http://dali.jqgfzy.top/Article/details/gtugstrqpk.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.yj202588.top/Article/details/gtpkrlhaoe.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.fengsongda.top/Article/details/gtkdopscde.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.redwolf501.top/Article/details/gtxvmweriu.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.hywenlv.cn/Article/details/gtxrfboasy.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.yangfankeji.com/Article/details/gtftxrtshf.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.wangdashe.top/Article/details/gtfrvrpvnd.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.hywenlv.cn/Article/details/gthwhkcvcq.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.guannengcc.top/Article/details/gtjctgpmyv.html

[P03] 生成短随机字符串
来源：http://dali.pycfn.com/Article/details/gttmphyubl.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.9152youxi.cn/Article/details/gtqvdpyelx.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.sysykeji.top/Article/details/gtutrxfeyl.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.0kj1m.cn/Article/details/gtlqxukazq.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.9152youxi.cn/Article/details/gtlrginbqu.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.pengpengdd.cyou/Article/details/gtqsmswfdj.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.gaohongyu789.top/Article/details/gtpfmhwuyr.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.ybcxt.top/Article/details/gtuviffium.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.ydzc1.top/Article/details/gtqxihpkqk.html

[P04] 求长度
来源：http://dali.xylfe.cn/Article/details/gtnzunwsvs.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhixingplan.top/Article/details/gtrewmpbjt.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.xuanzx.com/Article/details/gtzccjpiot.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.hfpthk.cn/Article/details/gttrtekyut.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yanxiufei.cn/Article/details/gtbzjpqyyt.html

Java: list.size();  map.size();  s.length()
来源：http://dali.nanxinkj.top/Article/details/gtlrwqaibg.html

Go:   len(arr);  len(m)
来源：http://dali.yvedp.cn/Article/details/gtmzmznhxy.html

Ruby: x.length;  x.size
来源：http://dali.9152youxi.cn/Article/details/gtyphvfuxi.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.hnqzz.top/Article/details/gtjjwggzqb.html

[P05] 判断两个对象内容是否相等
来源：http://dali.ydzc1.top/Article/details/gtqpceshma.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.wangdashe.top/Article/details/gtkunmgnem.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.kuanghao11.cn/Article/details/gtnqzwntdd.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.kuanghao11.cn/Article/details/gtagilbixo.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.hongshengwenyu.top/Article/details/gtimrsovpw.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.cheryme.top/Article/details/gthbqdwnom.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.sysykeji.top/Article/details/gtkngozdik.html

Ruby: a == b
来源：http://dali.9152youxi.cn/Article/details/gtzjrbpipw.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.fzhhl.top/Article/details/gtjvyzyofq.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.pycfn.com/Article/details/gtyolwzqcv.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.wangdashe.top/Article/details/gtgiinktmd.html

PHP:  if (empty($x)) {}
来源：http://dali.yvedp.cn/Article/details/gtqffcwqzi.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.tanke756.top/Article/details/gtxlpnjbqb.html

TS:   if (x == null) {}
来源：http://dali.yanxiufei.cn/Article/details/gthduhnebh.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.nanxuanxn.top/Article/details/gtfobzzotr.html

Go:   if x == nil {}
来源：http://dali.zhijiandao.cn/Article/details/gttnauydrb.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.tanke756.top/Article/details/gtktdexnpp.html

C#:   if (x is null) {}
来源：http://dali.fzhhl.top/Article/details/gtmlfsfybg.html

[P07] 防抖与节流
来源：http://dali.shanyushiyangtech.top/Article/details/gtcwezeftu.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.hongshengwenyu.top/Article/details/gtfojvymvt.html

PHP:  // 手写时间戳比较
来源：http://dali.yangfankeji.com/Article/details/gtcgblbayo.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuwqvxacf.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.daxiang520.top/Article/details/gtryviadlx.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.9152youxi.cn/Article/details/gteskeobun.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.cashguo.top/Article/details/gtcjinojqx.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.pengpengdd.cyou/Article/details/gttffxilom.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.shanyushiyangtech.top/Article/details/gtuagtphrj.html

[P08] 处理浮点精度问题
来源：http://dali.cheryme.top/Article/details/gtxoliuigr.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.kuanghao11.cn/Article/details/gtqysffxkk.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.ehwqpu.com/Article/details/gtuivlfguh.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.c1oappe.top/Article/details/gtzbrhhoqx.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.ydzc1.top/Article/details/gtjnrzrxyg.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.yangfankeji.com/Article/details/gtrogfuphx.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.havefunace.top/Article/details/gtylvxtcjn.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.yj202588.top/Article/details/gthwdnbzie.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.nanxinkj.top/Article/details/gtthssrokz.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtpaoeocws.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.hnxiangtu.top/Article/details/gtaxllusec.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtjeminlah.html

[Q01] 创建表
来源：http://dali.yonumen.top/Article/details/gtbpoqnkwg.html

CREATE TABLE users (
来源：http://dali.birdmap.top/Article/details/gtxunxklkd.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhoulong.xyz/Article/details/gtsltyzpqw.html

name VARCHAR(50) NOT NULL,
来源：http://dali.kuanghao11.cn/Article/details/gtkkaptlkl.html

email VARCHAR(100) UNIQUE,
来源：http://dali.vqdsnc.cn/Article/details/gtbitsjbcj.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.nanxinkj.top/Article/details/gtbrovxycj.html

);
来源：http://dali.pycfn.com/Article/details/gtguugtdqj.html

[Q02] 创建带外键的表
来源：http://dali.316326.xyz/Article/details/gtiicwdwgu.html

CREATE TABLE orders (
来源：http://dali.ybcxt.top/Article/details/gtklkpeqns.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoqjgkhkb.html

user_id INT NOT NULL,
来源：http://dali.mhx1999.top/Article/details/gtrdzmaywf.html

amount DECIMAL(10, 2),
来源：http://dali.shangyingyoupin.top/Article/details/gtdivmtroo.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.dashuyun.cn/Article/details/gtapxwcfzd.html

);
来源：http://dali.yuanzhike.top/Article/details/gtqkzpmwbc.html

[Q03] 增加列
来源：http://dali.havefunace.top/Article/details/gtrmvhdizw.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.c1oappe.top/Article/details/gtpyrafxcf.html

[Q04] 修改列类型
来源：http://dali.snrcjt.cn/Article/details/gtgeanbxuy.html


<!-- 参考信息 -->