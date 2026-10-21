代发 wailian999

JS:   process.exit(1)
来源：http://dali.jlsjyb.cn/Article/details/gtvdcnokxt.html

TS:   process.exit(1)
来源：http://dali.hammf.cn/Article/details/gtsyklbhqt.html

Java: System.exit(1)
来源：http://dali.cashguo.top/Article/details/gtexojxsyh.html

Go:   os.Exit(1)
来源：http://dali.tianlin.xyz/Article/details/gtkcjlqvpe.html

Ruby: exit 1
来源：http://dali.c1oappe.top/Article/details/gteoutbcmr.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.316326.xyz/Article/details/gtpontnjry.html

[M06] 向标准错误输出
来源：http://dali.pengpengdd.cyou/Article/details/gtfjiveisk.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zycfv.cn/Article/details/gtdclkienn.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.andypj.xyz/Article/details/gtltuslogj.html

JS:   console.error("err")
来源：http://dali.yanxiufei.cn/Article/details/gtlwzxlage.html

TS:   console.error("err")
来源：http://dali.shangyingyoupin.top/Article/details/gtalwcupuv.html

Java: System.err.println("err")
来源：http://dali.sysykeji.top/Article/details/gtawtwedkj.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.chenjidiqi.icu/Article/details/gtgojphklw.html

Ruby: warn "err"
来源：http://dali.fengsongda.top/Article/details/gtovpecbho.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.nanxuanxn.top/Article/details/gtprekstro.html

[M07] 判断是否为主入口
来源：http://dali.yvedp.cn/Article/details/gtjcbpksud.html

Py:   if __name__ == "__main__":
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrvxqkgpc.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.ppjwa.cn/Article/details/gtetipsfjw.html

JS:   require.main === module
来源：http://dali.cqqwz.cn/Article/details/gtvmaekynh.html

TS:   require.main === module
来源：http://dali.yuxming.cn/Article/details/gtlyduiykb.html

Java: public static void main(String[] args)
来源：http://dali.c1oappe.top/Article/details/gtiwcujflj.html

Go:   func main()
来源：http://dali.jiagoushi.top/Article/details/gtzgywnfel.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.ppjwa.cn/Article/details/gtibwoelsn.html

C#:   static void Main(string[] args)
来源：http://dali.jlsjyb.cn/Article/details/gtpwcuyjux.html

[M08] 获取系统与运行时信息
来源：http://dali.zycfv.cn/Article/details/gtgimnzhys.html

Py:   platform.system();  platform.python_version()
来源：http://dali.chenzaomai.com/Article/details/gtuadqaeso.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.feifeiyinyue.top/Article/details/gtahxfshke.html

JS:   process.platform;  process.version
来源：http://dali.gogol.net.cn/Article/details/gtioylccpy.html

TS:   process.platform;  process.version
来源：http://dali.feifeiyinyue.top/Article/details/gtcilcizut.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.jqgfzy.top/Article/details/gtpkmvzfln.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.bjfxy.top/Article/details/gtherhszff.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.hammf.cn/Article/details/gtoiqtnwvo.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gtrgvtlkqv.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtwjkcxelu.html

N. 数据结构与算法
来源：http://dali.mhx1999.top/Article/details/gtmaragknb.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtfhjxfhqe.html

[N01] 二分查找（有序数组）
来源：http://dali.gogol.net.cn/Article/details/gttwlnnjlt.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.sweek.top/Article/details/gtivdscvwe.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.jinghuilouyu.cn/Article/details/gtgrpqpvnv.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrrmuuhtb.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.vqdsnc.cn/Article/details/gtgnzikcvr.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.yangfankeji.com/Article/details/gttngqnnod.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyazwmxrg.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.hnqzz.top/Article/details/gtccchzjdx.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.cashguo.top/Article/details/gttjzziauo.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.shuidangran.top/Article/details/gtlstcwdep.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yj20258888.top/Article/details/gtpenudahw.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.gogol.net.cn/Article/details/gtxgsjvnhx.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.birdmap.top/Article/details/gttwgucypp.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jqgfzy.top/Article/details/gtgizljthw.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.aibaodan.cn/Article/details/gtaenmvinx.html

Go:   slices.Sort(arr)
来源：http://dali.haohaochexian.top/Article/details/gttguipdhs.html

Ruby: arr.sort
来源：http://dali.yj202588.top/Article/details/gtjntjyqjg.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.yueranfly.top/Article/details/gtizqyfovm.html

[N03] 快速排序（分治示例）
来源：http://dali.pycfn.com/Article/details/gtstnkflke.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.yangfankeji.com/Article/details/gtvijufzjq.html

PHP:  // 递归实现，或用 usort
来源：http://dali.gaohongyu789.top/Article/details/gtdploxltd.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.xinyue.icu/Article/details/gtofbhrall.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhoulong.xyz/Article/details/gthtyhdghe.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.ppjwa.cn/Article/details/gtksnyvmpi.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.cqqwz.cn/Article/details/gtfofdkika.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhiwuduotai.top/Article/details/gtonmcidtj.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.mhx1999.top/Article/details/gtmreuziux.html

[N04] 斐波那契数列
来源：http://dali.tian-w.cn/Article/details/gtjuohonhf.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.pycfn.com/Article/details/gtpiddolvu.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.chenzaomai.com/Article/details/gtwobgfccl.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.vqdsnc.cn/Article/details/gtrngwwmql.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jianghu66.top/Article/details/gtifzbeknr.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuvurhwnb.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.guannengcc.top/Article/details/gtiqeyegyd.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.dashuyun.cn/Article/details/gtxtpvrmry.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.jianghu66.top/Article/details/gtgbqnwyzw.html

[N05] 最大公约数
来源：http://dali.jinghuilouyu.cn/Article/details/gtvxyymmuc.html

Py:   math.gcd(a, b)
来源：http://dali.0kj1m.cn/Article/details/gteufkhibg.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.redwolf501.top/Article/details/gtnlelahtl.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhoulong.xyz/Article/details/gtcekbvauj.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hammf.cn/Article/details/gtnsppxkhs.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.haohaochexian.top/Article/details/gtsfbowixf.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.tanke756.top/Article/details/gtgzfefemg.html

Ruby: a.gcd(b)
来源：http://dali.xuetiantiany.cn/Article/details/gttrbmurht.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.xuetiantiany.cn/Article/details/gtrwrqfjcv.html

[N06] 判断回文字符串
来源：http://dali.fengsongda.top/Article/details/gtkfonrhjx.html

Py:   s == s[::-1]
来源：http://dali.hammf.cn/Article/details/gtdcpckvyw.html

PHP:  $s === strrev($s);
来源：http://dali.zhongyouzk.top/Article/details/gtxhsncaeq.html

JS:   s === [...s].reverse().join("")
来源：http://dali.kuanghao11.cn/Article/details/gtdxwgtlml.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhongyouzk.top/Article/details/gtczckkusw.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.sxryk.cn/Article/details/gtxydhcive.html

Go:   // 双指针从两端比较
来源：http://dali.zhixingplan.top/Article/details/gtdtksccxl.html

Ruby: s == s.reverse
来源：http://dali.xziqi.cn/Article/details/gtxbkeroyk.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.yueranfly.top/Article/details/gtzsorckpc.html

[N07] 两数之和（返回下标）
来源：http://dali.guannengcc.top/Article/details/gtwszfapla.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.0kj1m.cn/Article/details/gtppjbioft.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gtmhecolzl.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.0kj1m.cn/Article/details/gtzgfjzugu.html

TS:   // 手写 Map<string, number>
来源：http://dali.guannengcc.top/Article/details/gthfemyoou.html

Java: // 手写 HashMap
来源：http://dali.jianghu66.top/Article/details/gttboegerh.html

Go:   // 手写 map[int]int
来源：http://dali.ehwqpu.com/Article/details/gtlzgpmlyt.html

Ruby: // 手写 Hash
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcfdaxnpp.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.haohaochexian.top/Article/details/gtlhetnicl.html

[N08] 生成全排列
来源：http://dali.yj20258.top/Article/details/gtrcipzqpu.html

Py:   itertools.permutations(arr)
来源：http://dali.xziqi.cn/Article/details/gtbjqhusjd.html

PHP:  // 手写递归交换
来源：http://dali.jiagoushi.top/Article/details/gtgjtiuxob.html

JS:   // 手写回溯递归
来源：http://dali.andypj.xyz/Article/details/gtbnmryndl.html

TS:   // 手写回溯递归
来源：http://dali.shanyushiyangtech.top/Article/details/gttljwrcay.html

Java: // 手写回溯递归
来源：http://dali.haohaochexian.top/Article/details/gttaqntbul.html

Go:   // 手写回溯递归
来源：http://dali.haohaochexian.top/Article/details/gtynurdywo.html

Ruby: arr.permutation.to_a
来源：http://dali.tanke756.top/Article/details/gtcuulmyys.html

C#:   // 手写回溯递归
来源：http://dali.dashuyun.cn/Article/details/gthluenjqr.html

[N09] 栈与队列
来源：http://dali.c1oappe.top/Article/details/gthhanlgfr.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.snrcjt.cn/Article/details/gtpfdswgoh.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.pengpengdd.cyou/Article/details/gtfbexfbby.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.yongpay.top/Article/details/gtmrslejzo.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.c1oappe.top/Article/details/gtqmahlxoy.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.chenzaomai.com/Article/details/gtedrcwdlo.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.yj202588.top/Article/details/gtqfnjrbfd.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.sweek.top/Article/details/gtjemtrrcc.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.haohaochexian.top/Article/details/gtfukrtrdt.html

[N10] 链表节点定义
来源：http://dali.zhongyouzk.top/Article/details/gtfbgamwdx.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.gogol.net.cn/Article/details/gtyfnqcdsz.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.shuidangran.top/Article/details/gtqqbhwukw.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.ehwqpu.com/Article/details/gtheivlyxg.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.yj20258888.top/Article/details/gtlxbvvorm.html

Java: class Node { int v; Node next; }
来源：http://dali.nanxinkj.top/Article/details/gtzjqqzgqb.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.316326.xyz/Article/details/gtwrzevyfd.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.yanxiufei.cn/Article/details/gtkcdnueki.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.wangdashe.top/Article/details/gtamsvxezx.html

[N11] 二叉树中序遍历
来源：http://dali.kuanghao11.cn/Article/details/gtdwasabzl.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhiwuduotai.top/Article/details/gtwslmqjsx.html

PHP:  // 手写递归函数
来源：http://dali.pengpengdd.cyou/Article/details/gtnaitbbnq.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.hysaishi.cn/Article/details/gtmurpubqr.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.xziqi.cn/Article/details/gtottdswxd.html

Java: // 手写递归
来源：http://dali.daria6918.cn/Article/details/gthispcuhg.html

Go:   // 手写递归
来源：http://dali.xuanzx.com/Article/details/gtdotzlovc.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.jqgufenzy.top/Article/details/gtskymmoxs.html

C#:   // 手写递归
来源：http://dali.zycfv.cn/Article/details/gtbaygpbyk.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.cheryme.top/Article/details/gtlwfkmnny.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.tianlin.xyz/Article/details/gtltcsohud.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.xinyue.icu/Article/details/gtatsqdqhd.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.feifeiyinyue.top/Article/details/gtesmwdxfs.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.shuidangran.top/Article/details/gtinvtlkml.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.andypj.xyz/Article/details/gthxmyuwjw.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.aibaodan.cn/Article/details/gtqievmsqd.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.andypj.xyz/Article/details/gtnticxafx.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.daria6918.cn/Article/details/gtnitnrssz.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtccosxgut.html

O. 并发与异步
来源：http://dali.hnxiangtu.top/Article/details/gtbvzbsezt.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtrtlwsata.html

[O01] 启动一个线程
来源：http://dali.havefunace.top/Article/details/gtgocessnf.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.cheryme.top/Article/details/gtnyfrryqv.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.shanyushiyangtech.top/Article/details/gtvrsgjbdn.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.snrcjt.cn/Article/details/gtmvrxlhsb.html

TS:   // 同 JS
来源：http://dali.hysaishi.cn/Article/details/gtuerlciqo.html

Java: new Thread(() -> f()).start()
来源：http://dali.iojbl.cn/Article/details/gtbrfanjnw.html

Go:   go f()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuqrkeppw.html

Ruby: Thread.new { f }
来源：http://dali.chenjidiqi.icu/Article/details/gtvmtdyrut.html

C#:   Task.Run(() => F());
来源：http://dali.pycfn.com/Article/details/gtxetwuvps.html

[O02] 使用线程池
来源：http://dali.fzhhl.top/Article/details/gttqohlsej.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.sweek.top/Article/details/gtrhcemjgk.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.cdnleiting.top/Article/details/gtnvusjapv.html

JS:   // worker_threads 线程池
来源：http://dali.gogol.net.cn/Article/details/gtkdorjqqv.html

TS:   // worker_threads 线程池
来源：http://dali.pengpengdd.cyou/Article/details/gtipugbhxv.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.9152youxi.cn/Article/details/gtokfzfuvn.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zdqjudy.top/Article/details/gturzzrumw.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.jianghu66.top/Article/details/gtseytojhc.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.vqdsnc.cn/Article/details/gtjrvnkpls.html

[O03] 加锁保护共享数据
来源：http://dali.zycfv.cn/Article/details/gtcahvyqak.html

Py:   with lock: shared += 1
来源：http://dali.hnqzz.top/Article/details/gthqbzuecl.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.fengsongda.top/Article/details/gtwrqqnavc.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.pycfn.com/Article/details/gtcuqbuhhi.html

TS:   // 同 JS
来源：http://dali.chenzaomai.com/Article/details/gtgyrjuewb.html

Java: synchronized (this) { shared++; }
来源：http://dali.pengpengdd.cyou/Article/details/gtsvfrxqcj.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.xziqi.cn/Article/details/gtrxceagzg.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.yj202588.top/Article/details/gtsexcwyqc.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gtrzbdvzij.html

[O04] 定义异步函数并等待
来源：http://dali.jinghuilouyu.cn/Article/details/gtyvjzgxjs.html

Py:   async def f():⏎    await g()
来源：http://dali.chenjidiqi.icu/Article/details/gtcmesncti.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.cucudq.cn/Article/details/gtcbayptls.html

JS:   async function f() { await g(); }
来源：http://dali.jqgfzy.top/Article/details/gthiahndca.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.hammf.cn/Article/details/gtlajntrqe.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.ivvv.top/Article/details/gtfmnsadab.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.shuidangran.top/Article/details/gtfyvcixbl.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.jinqigfzy.top/Article/details/gtxgbrwbyt.html

C#:   async Task F() { await G(); }
来源：http://dali.xuanzx.com/Article/details/gtknmnmlcp.html

[O05] 并发执行并等待全部完成
来源：http://dali.jyoumei.cn/Article/details/gtluyxoxlm.html

Py:   asyncio.gather(*tasks)
来源：http://dali.shanyushiyangtech.top/Article/details/gtpoakyowa.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.snrcjt.cn/Article/details/gtnkbwufrt.html

JS:   await Promise.all(tasks)
来源：http://dali.chenzaomai.com/Article/details/gtoctzsyua.html

TS:   await Promise.all(tasks)
来源：http://dali.hammf.cn/Article/details/gtzmejsweb.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtozalgidw.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.xuanzx.com/Article/details/gtvdrgatpb.html

Ruby: threads.map(&:join)
来源：http://dali.cqqwz.cn/Article/details/gtbkbvumkz.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.aibaodan.cn/Article/details/gtiyczfzgu.html

[O06] 使用进程池
来源：http://dali.zhoulong.xyz/Article/details/gtlbayqowm.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.redwolf501.top/Article/details/gtsmvqkzwz.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.ppjwa.cn/Article/details/gttxbbeyke.html

JS:   // child_process / cluster 模块
来源：http://dali.chenzaomai.com/Article/details/gtgprhfvin.html

TS:   // child_process / cluster 模块
来源：http://dali.jinqigfzy.top/Article/details/gtcwscluea.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.xuanzx.com/Article/details/gtvsubpaum.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.sysykeji.top/Article/details/gttjpypyki.html

Ruby: // fork 块
来源：http://dali.svipenyu.cn/Article/details/gtynryjyqi.html

C#:   Parallel.For
来源：http://dali.sweek.top/Article/details/gtvpddxefx.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtdccqsgkg.html

P. 常用工具函数
来源：http://dali.snrcjt.cn/Article/details/gtnmltfiyx.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtpbtyazls.html

[P01] 生成 UUID
来源：http://dali.316326.xyz/Article/details/gtkgfushdk.html

Py:   str(uuid.uuid4())
来源：http://dali.yueranfly.top/Article/details/gtxmyxttlj.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.hfpthk.cn/Article/details/gtlbadmwbl.html

JS:   crypto.randomUUID()
来源：http://dali.guowangkeji.top/Article/details/gtaowieemi.html

TS:   crypto.randomUUID()
来源：http://dali.gaohongyu789.top/Article/details/gtuxwypnsu.html

Java: UUID.randomUUID().toString()
来源：http://dali.yj20258888.top/Article/details/gtfsspvgdw.html

Go:   // 用 github.com/google/uuid
来源：http://dali.hfpthk.cn/Article/details/gtpucvxscs.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gtrsuayubp.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.svipenyu.cn/Article/details/gtoyckfuco.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkkdbnsui.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.redwolf501.top/Article/details/gtxdlfmpdr.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.xziqi.cn/Article/details/gtaeeragsg.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.pycfn.com/Article/details/gtwvruvczz.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.chenzaomai.com/Article/details/gtutjlljwb.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.c1oappe.top/Article/details/gtgvwncljo.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.0kj1m.cn/Article/details/gtciqnubio.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.dashuyun.cn/Article/details/gtwrkkfuza.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.hnxiangtu.top/Article/details/gtigjmsyhu.html

[P03] 生成短随机字符串
来源：http://dali.dashuyun.cn/Article/details/gtmdtetrcb.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.ivvv.top/Article/details/gtchzwyqds.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.dianchejie.cn/Article/details/gtdjzzceec.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.cqqwz.cn/Article/details/gtrukcmjmz.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.meibo888.top/Article/details/gtjxmjssbo.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.haohaochexian.top/Article/details/gtwmubdngh.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.sweek.top/Article/details/gtvapfaqdm.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.xziqi.cn/Article/details/gtiyuexwgq.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.hammf.cn/Article/details/gtwtgdgsan.html

[P04] 求长度
来源：http://dali.yj202588.top/Article/details/gtnhffmeun.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.cdnleiting.top/Article/details/gtpqpvesqp.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxwsxfzap.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.hywenlv.cn/Article/details/gtofemlhnb.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.fengsongda.top/Article/details/gtwtylgolt.html

Java: list.size();  map.size();  s.length()
来源：http://dali.jinqigufen.top/Article/details/gttxepfgig.html

Go:   len(arr);  len(m)
来源：http://dali.nanxinkj.top/Article/details/gtgmftiaff.html

Ruby: x.length;  x.size
来源：http://dali.yuxming.cn/Article/details/gtvzxoylvz.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.jianghu66.top/Article/details/gtvikqsmpy.html

[P05] 判断两个对象内容是否相等
来源：http://dali.cucudq.cn/Article/details/gtdhyqsxnx.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.xinyue.icu/Article/details/gtxmajbxuo.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zdqjudy.top/Article/details/gttuctqqkb.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.birdmap.top/Article/details/gtlcoocewn.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhiwuduotai.top/Article/details/gtzmfgpuvd.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhaomingkeji.xyz/Article/details/gtduotdjdx.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxurbmgjp.html

Ruby: a == b
来源：http://dali.jqgufenzy.top/Article/details/gtmmlhchyu.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.sweek.top/Article/details/gtadetzccd.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.yj20258.top/Article/details/gtnmhzoxus.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.gaohongyu789.top/Article/details/gtadmmdfvr.html

PHP:  if (empty($x)) {}
来源：http://dali.svipenyu.cn/Article/details/gtzfpoqxqb.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.sysykeji.top/Article/details/gtbrlzzofu.html

TS:   if (x == null) {}
来源：http://dali.jinqigufen.top/Article/details/gthyztkppv.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvkcarqbp.html

Go:   if x == nil {}
来源：http://dali.yueranfly.top/Article/details/gtgbrcvrru.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.hammf.cn/Article/details/gtvhuowtae.html

C#:   if (x is null) {}
来源：http://dali.shuidangran.top/Article/details/gtqvhdvmmx.html

[P07] 防抖与节流
来源：http://dali.yuxming.cn/Article/details/gtbftgrtwo.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.yj202588.top/Article/details/gtroilpvtd.html

PHP:  // 手写时间戳比较
来源：http://dali.redwolf501.top/Article/details/gtfbzklabe.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.316326.xyz/Article/details/gtalvuwvdx.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhixingplan.top/Article/details/gtecxgjxit.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.cdnleiting.top/Article/details/gtwkgljrad.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.sysykeji.top/Article/details/gtakkfuukx.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhijiandao.cn/Article/details/gtvyaxabsz.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.guannengcc.top/Article/details/gtjtzemllp.html

[P08] 处理浮点精度问题
来源：http://dali.andypj.xyz/Article/details/gtzhwpiokl.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.fengsongda.top/Article/details/gtbjimlmhz.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.bjfxy.top/Article/details/gtcuqqqfla.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.gogol.net.cn/Article/details/gtgstbmtpg.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.shuidangran.top/Article/details/gtunmkedxq.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.andypj.xyz/Article/details/gtevogomog.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.cqqwz.cn/Article/details/gthdqkqgyx.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.jqgfzy.top/Article/details/gtppsimyxf.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.gogol.net.cn/Article/details/gthxysnxzy.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtihwtzbew.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.gzhubu.top/Article/details/gthxdvunff.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtnsdoaeym.html

[Q01] 创建表
来源：http://dali.dianchejie.cn/Article/details/gtmckuzqvq.html

CREATE TABLE users (
来源：http://dali.birdmap.top/Article/details/gthclilcwd.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jianghu66.top/Article/details/gtopkopkpe.html

name VARCHAR(50) NOT NULL,
来源：http://dali.hywenlv.cn/Article/details/gtldyxwnsa.html

email VARCHAR(100) UNIQUE,
来源：http://dali.shzxlz.cn/Article/details/gtebutjmhj.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.xylfe.cn/Article/details/gtrthdokin.html

);
来源：http://dali.fzhhl.top/Article/details/gtohasscjf.html

[Q02] 创建带外键的表
来源：http://dali.hysaishi.cn/Article/details/gtobnuyhua.html

CREATE TABLE orders (
来源：http://dali.andypj.xyz/Article/details/gtxekirgos.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhaomingkeji.xyz/Article/details/gtloozptos.html

user_id INT NOT NULL,
来源：http://dali.gotoacloud.top/Article/details/gtoeldfqxq.html

amount DECIMAL(10, 2),
来源：http://dali.jqgfzy.top/Article/details/gtfzdetcpv.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zycfv.cn/Article/details/gtbiigezcp.html

);
来源：http://dali.hongshengwenyu.top/Article/details/gtibhbepgc.html

[Q03] 增加列
来源：http://dali.tanke756.top/Article/details/gtofemqhfg.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.hfpthk.cn/Article/details/gtxyebjmwk.html

[Q04] 修改列类型
来源：http://dali.jlsjyb.cn/Article/details/gtlvjcqzhm.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.shuidangran.top/Article/details/gtekommdgm.html

[Q05] 重命名列
来源：http://dali.jiagoushi.top/Article/details/gtrnvuzpcr.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmudyvzlm.html

[Q06] 删除列
来源：http://dali.yanxiufei.cn/Article/details/gtrlwtlvpy.html


<!-- 参考信息 -->