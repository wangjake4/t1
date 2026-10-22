代发 wailian999

JS:   process.exit(1)
来源：http://dali.jiagoushi.top/Article/details/gtsbarrpek.html

TS:   process.exit(1)
来源：http://dali.hammf.cn/Article/details/gtuvbothjd.html

Java: System.exit(1)
来源：http://dali.hfpthk.cn/Article/details/gtwkehypui.html

Go:   os.Exit(1)
来源：http://dali.gotoacloud.top/Article/details/gtrqwtfspz.html

Ruby: exit 1
来源：http://dali.gogol.net.cn/Article/details/gtocjtvvdb.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.yongpay.top/Article/details/gtwhntsisd.html

[M06] 向标准错误输出
来源：http://dali.daria6918.cn/Article/details/gtpjhsoyor.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhongyouzk.top/Article/details/gtgkimqjqn.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.daria6918.cn/Article/details/gtvgonqibn.html

JS:   console.error("err")
来源：http://dali.ehwqpu.com/Article/details/gtrzivleud.html

TS:   console.error("err")
来源：http://dali.meibo888.top/Article/details/gtkrqvoass.html

Java: System.err.println("err")
来源：http://dali.shanyushiyangtech.top/Article/details/gtigznnfma.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.meibo888.top/Article/details/gtsigharym.html

Ruby: warn "err"
来源：http://dali.nwbrower.top/Article/details/gtftspwuzc.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.hywenlv.cn/Article/details/gtjqbdkfnu.html

[M07] 判断是否为主入口
来源：http://dali.yangfankeji.com/Article/details/gtcbxkugad.html

Py:   if __name__ == "__main__":
来源：http://dali.aizwys.cn/Article/details/gtgppdqxwh.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.ybcxt.top/Article/details/gthrpspvwf.html

JS:   require.main === module
来源：http://dali.hfpthk.cn/Article/details/gtjpkwlfvo.html

TS:   require.main === module
来源：http://dali.chenjidiqi.icu/Article/details/gtbcotkqxn.html

Java: public static void main(String[] args)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyodlosxk.html

Go:   func main()
来源：http://dali.jinghuilouyu.cn/Article/details/gtcdprbsje.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.yj20258.top/Article/details/gtgofrmxmd.html

C#:   static void Main(string[] args)
来源：http://dali.chenlongwang.top/Article/details/gtbvspzjcb.html

[M08] 获取系统与运行时信息
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgyrqgfnc.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhixingplan.top/Article/details/gtlpmjnlmr.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.jianghu66.top/Article/details/gtrnvfgqhy.html

JS:   process.platform;  process.version
来源：http://dali.jiagoushi.top/Article/details/gtgcerapjq.html

TS:   process.platform;  process.version
来源：http://dali.yongpay.top/Article/details/gthmauvygf.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zycfv.cn/Article/details/gtgxfhaqhe.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.gzhubu.top/Article/details/gtvdbztolv.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.xuanzx.com/Article/details/gtgezdeqib.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.gzhubu.top/Article/details/gtjrkhebsb.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtouebixui.html

N. 数据结构与算法
来源：http://dali.chenzaomai.com/Article/details/gtwdsfpazf.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtjfjhpkte.html

[N01] 二分查找（有序数组）
来源：http://dali.smart0.xyz/Article/details/gtxomhpllr.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.dashuyun.cn/Article/details/gtfeeofaif.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.shzxlz.cn/Article/details/gtyzcprjoo.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jianghu66.top/Article/details/gtiozbneaz.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.redwolf501.top/Article/details/gtezmwcwvm.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.aizwys.cn/Article/details/gtkmwyseiw.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxyturyyl.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.jlsjyb.cn/Article/details/gtmvxcumvq.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.chenlongwang.top/Article/details/gtmwurspsy.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.guowangkeji.top/Article/details/gtziflildu.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yj20258.top/Article/details/gthaxpsrwh.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.meibo888.top/Article/details/gtbzfmokyw.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.hysaishi.cn/Article/details/gtykqebamx.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.c1oappe.top/Article/details/gtzufhcvvs.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.yj20258888.top/Article/details/gtooynqzdf.html

Go:   slices.Sort(arr)
来源：http://dali.havefunace.top/Article/details/gtlwnasjtp.html

Ruby: arr.sort
来源：http://dali.snrcjt.cn/Article/details/gtmtrafjtx.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.pycfn.com/Article/details/gtfctutymi.html

[N03] 快速排序（分治示例）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwxjdemnk.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.yj20258.top/Article/details/gtfchvgwao.html

PHP:  // 递归实现，或用 usort
来源：http://dali.feifeiyinyue.top/Article/details/gtjcgysumq.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jyoumei.cn/Article/details/gtqnnhmvfx.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.haohaochexian.top/Article/details/gtemjtxtnm.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gteozqzevh.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.jqgfzy.top/Article/details/gtscwonrru.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zdqjudy.top/Article/details/gtmyyrrfzd.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.ywan-chungtsiang.top/Article/details/gtevpkktjo.html

[N04] 斐波那契数列
来源：http://dali.wangdashe.top/Article/details/gtlymrpyoo.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhixingplan.top/Article/details/gtsfyyyuvb.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.gaohongyu789.top/Article/details/gtasjqcfdw.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.daria6918.cn/Article/details/gtefynseys.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.gaohongyu789.top/Article/details/gtvrhpqksk.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.hongshengwenyu.top/Article/details/gtmrufaqrx.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhixingplan.top/Article/details/gtqysrcirf.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.jiagoushi.top/Article/details/gthcvimwun.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.nwbrower.top/Article/details/gtxasieijv.html

[N05] 最大公约数
来源：http://dali.fengsongda.top/Article/details/gtcjgljrti.html

Py:   math.gcd(a, b)
来源：http://dali.ivvv.top/Article/details/gtsorqsemp.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.ppjwa.cn/Article/details/gtmfwwshkp.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.daria6918.cn/Article/details/gtbpkhmvdf.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.aibaodan.cn/Article/details/gtoqbpnnza.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.jlsjyb.cn/Article/details/gtqgrafyjw.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.jqgufenzy.top/Article/details/gtpjewijkn.html

Ruby: a.gcd(b)
来源：http://dali.zhixingplan.top/Article/details/gttgvmnyrg.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.sxryk.cn/Article/details/gtvltdfcex.html

[N06] 判断回文字符串
来源：http://dali.xuetiantiany.cn/Article/details/gtdizhgsvh.html

Py:   s == s[::-1]
来源：http://dali.tanke756.top/Article/details/gtrknmzyke.html

PHP:  $s === strrev($s);
来源：http://dali.ppjwa.cn/Article/details/gtdqimszlw.html

JS:   s === [...s].reverse().join("")
来源：http://dali.daria6918.cn/Article/details/gtinbinrtq.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhoulong.xyz/Article/details/gtgfztzscr.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.vqdsnc.cn/Article/details/gtxoideajq.html

Go:   // 双指针从两端比较
来源：http://dali.hammf.cn/Article/details/gttzzvtvzq.html

Ruby: s == s.reverse
来源：http://dali.jqgufenzy.top/Article/details/gtewvxhfby.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.jinghuilouyu.cn/Article/details/gtytzkrnuf.html

[N07] 两数之和（返回下标）
来源：http://dali.shuidangran.top/Article/details/gtxrxlnuwd.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.shanyushiyangtech.top/Article/details/gtnxduifsc.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.cqqwz.cn/Article/details/gtjrriwsuf.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.daria6918.cn/Article/details/gtpwqidgxs.html

TS:   // 手写 Map<string, number>
来源：http://dali.gogol.net.cn/Article/details/gtgetaqyrd.html

Java: // 手写 HashMap
来源：http://dali.guannengcc.top/Article/details/gtqwjyljcp.html

Go:   // 手写 map[int]int
来源：http://dali.cucudq.cn/Article/details/gtjihydgsd.html

Ruby: // 手写 Hash
来源：http://dali.jiagoushi.top/Article/details/gtiqrcuczs.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.ppjwa.cn/Article/details/gtnkwocouq.html

[N08] 生成全排列
来源：http://dali.chenzaomai.com/Article/details/gtdvletjss.html

Py:   itertools.permutations(arr)
来源：http://dali.chenzaomai.com/Article/details/gtkuhmajif.html

PHP:  // 手写递归交换
来源：http://dali.zhoulong.xyz/Article/details/gtwzscthet.html

JS:   // 手写回溯递归
来源：http://dali.cqqwz.cn/Article/details/gtcoxuixwu.html

TS:   // 手写回溯递归
来源：http://dali.xziqi.cn/Article/details/gtrqmyrmoh.html

Java: // 手写回溯递归
来源：http://dali.andypj.xyz/Article/details/gttkmgojnj.html

Go:   // 手写回溯递归
来源：http://dali.hongshengwenyu.top/Article/details/gtuvoziklj.html

Ruby: arr.permutation.to_a
来源：http://dali.yanxiufei.cn/Article/details/gtpaczzlsp.html

C#:   // 手写回溯递归
来源：http://dali.sysykeji.top/Article/details/gtpbyvvsdu.html

[N09] 栈与队列
来源：http://dali.yj20258.top/Article/details/gtcqlbbdxw.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.jinqigfzy.top/Article/details/gtqhvczkef.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.birdmap.top/Article/details/gtouwxccfm.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.dianchejie.cn/Article/details/gtevfuqpvl.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.c1oappe.top/Article/details/gtaezaczte.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.shanyushiyangtech.top/Article/details/gtsilkohcj.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhengqikj.top/Article/details/gtycvoldua.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.shuidangran.top/Article/details/gtonjlknkv.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.hongshengwenyu.top/Article/details/gtcnfsppnd.html

[N10] 链表节点定义
来源：http://dali.gaohongyu789.top/Article/details/gtpmmxcsmh.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.gotoacloud.top/Article/details/gtueemvlsq.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.snrcjt.cn/Article/details/gttgyehxtp.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.yanxiufei.cn/Article/details/gtsmmjqotg.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.xinyue.icu/Article/details/gtdozptgvc.html

Java: class Node { int v; Node next; }
来源：http://dali.9152youxi.cn/Article/details/gtaekzsrye.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.yj20258.top/Article/details/gtrvajggzk.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.cashguo.top/Article/details/gtzuzqnfzf.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.gaohongyu789.top/Article/details/gthdaraawc.html

[N11] 二叉树中序遍历
来源：http://dali.ehwqpu.com/Article/details/gtrdgicmtl.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.gzhubu.top/Article/details/gtgbsslkdi.html

PHP:  // 手写递归函数
来源：http://dali.cucudq.cn/Article/details/gtrmdemuew.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zdqjudy.top/Article/details/gtttqnrjzy.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.gaohongyu789.top/Article/details/gtrryeqqfw.html

Java: // 手写递归
来源：http://dali.meibo888.top/Article/details/gtlaocvthl.html

Go:   // 手写递归
来源：http://dali.gzhubu.top/Article/details/gtrvreofjd.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.hnqzz.top/Article/details/gtsrftfrpq.html

C#:   // 手写递归
来源：http://dali.pycfn.com/Article/details/gtsvlfuqgt.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.yj20258888.top/Article/details/gtylzkihmz.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.hnqzz.top/Article/details/gtxxkldncj.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.yuxming.cn/Article/details/gtrpmjlupo.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.0kj1m.cn/Article/details/gtymwfoocc.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.ybcxt.top/Article/details/gthyzpmphw.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jinyuanbaomall.cn/Article/details/gtugwkziyk.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.iojbl.cn/Article/details/gtoahkbmoc.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwoidhlfi.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.hnxiangtu.top/Article/details/gtnolhvjjf.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtrqelgfiq.html

O. 并发与异步
来源：http://dali.cucudq.cn/Article/details/gtjrfysavd.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtpxfcuvjh.html

[O01] 启动一个线程
来源：http://dali.yangfankeji.com/Article/details/gtrrawmftx.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.jiagoushi.top/Article/details/gtysvzxfnw.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.jlsjyb.cn/Article/details/gtvffgqaxh.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrajdozjk.html

TS:   // 同 JS
来源：http://dali.cashguo.top/Article/details/gtcwnjdfvr.html

Java: new Thread(() -> f()).start()
来源：http://dali.haohaochexian.top/Article/details/gtjnfrqnfa.html

Go:   go f()
来源：http://dali.svipenyu.cn/Article/details/gtslumxeic.html

Ruby: Thread.new { f }
来源：http://dali.daria6918.cn/Article/details/gteclolcyk.html

C#:   Task.Run(() => F());
来源：http://dali.9152youxi.cn/Article/details/gtdayswgbc.html

[O02] 使用线程池
来源：http://dali.kuanghao11.cn/Article/details/gtmifdnifk.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.guowangkeji.top/Article/details/gtrdpeevib.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.xziqi.cn/Article/details/gticufggsz.html

JS:   // worker_threads 线程池
来源：http://dali.kuanghao11.cn/Article/details/gtyqzircif.html

TS:   // worker_threads 线程池
来源：http://dali.birdmap.top/Article/details/gtvrjomgrk.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.sysykeji.top/Article/details/gtogsjxamw.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.hnxiangtu.top/Article/details/gtkryunipb.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.sweek.top/Article/details/gtyvvbbdqk.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.chenlongwang.top/Article/details/gtqlrewwyi.html

[O03] 加锁保护共享数据
来源：http://dali.ydzc1.top/Article/details/gtndkovsxu.html

Py:   with lock: shared += 1
来源：http://dali.ppjwa.cn/Article/details/gtjsufkzxp.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.yonumen.top/Article/details/gtmpllokcx.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvvadbxsh.html

TS:   // 同 JS
来源：http://dali.tanke756.top/Article/details/gtscmtjspe.html

Java: synchronized (this) { shared++; }
来源：http://dali.yj202588.top/Article/details/gtravyoaib.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.guowangkeji.top/Article/details/gthzvtcmql.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.tanke756.top/Article/details/gtwizjliog.html

C#:   lock (gate) { shared++; }
来源：http://dali.tanke756.top/Article/details/gtkfakmvvt.html

[O04] 定义异步函数并等待
来源：http://dali.snrcjt.cn/Article/details/gtgfyeogoh.html

Py:   async def f():⏎    await g()
来源：http://dali.iojbl.cn/Article/details/gtgzluxzkc.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.ydzc1.top/Article/details/gtwmhqhdow.html

JS:   async function f() { await g(); }
来源：http://dali.nanxinkj.top/Article/details/gtvdohqdou.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlaqhzdcv.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.jianghu66.top/Article/details/gthkedkgse.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.yvedp.cn/Article/details/gtzydzansd.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfxhzgfse.html

C#:   async Task F() { await G(); }
来源：http://dali.zhixingplan.top/Article/details/gtfpbrogfc.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhongyouzk.top/Article/details/gtzqygylxs.html

Py:   asyncio.gather(*tasks)
来源：http://dali.chenlongwang.top/Article/details/gtsmppvixh.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.c1oappe.top/Article/details/gttergqmti.html

JS:   await Promise.all(tasks)
来源：http://dali.wangshuangyany.cn/Article/details/gtmvxmclge.html

TS:   await Promise.all(tasks)
来源：http://dali.fzhhl.top/Article/details/gtecfrkcaj.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.jlsjyb.cn/Article/details/gtkvagqjfm.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zdqjudy.top/Article/details/gtfmqcvnww.html

Ruby: threads.map(&:join)
来源：http://dali.redwolf501.top/Article/details/gtvzgkmsho.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.ehwqpu.com/Article/details/gtiprzjskt.html

[O06] 使用进程池
来源：http://dali.jyoumei.cn/Article/details/gtdqrwxijb.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.havefunace.top/Article/details/gtmsvauqrr.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.chenlongwang.top/Article/details/gthefhgitw.html

JS:   // child_process / cluster 模块
来源：http://dali.gotoacloud.top/Article/details/gtyiebloho.html

TS:   // child_process / cluster 模块
来源：http://dali.bjfxy.top/Article/details/gtsuobhjdq.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.9152youxi.cn/Article/details/gterawgnfz.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.jqgfzy.top/Article/details/gtqcyrzpmx.html

Ruby: // fork 块
来源：http://dali.jiagoushi.top/Article/details/gtmbwxdwcf.html

C#:   Parallel.For
来源：http://dali.mhx1999.top/Article/details/gtrvuvlkwz.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtupckxxqr.html

P. 常用工具函数
来源：http://dali.hnxiangtu.top/Article/details/gtrdtublws.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtjncvhnxe.html

[P01] 生成 UUID
来源：http://dali.wangdashe.top/Article/details/gtyplrawtt.html

Py:   str(uuid.uuid4())
来源：http://dali.yanxiufei.cn/Article/details/gtegndrzlm.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.haohaochexian.top/Article/details/gtadvpnnmz.html

JS:   crypto.randomUUID()
来源：http://dali.zdqjudy.top/Article/details/gtqvknjore.html

TS:   crypto.randomUUID()
来源：http://dali.haohaochexian.top/Article/details/gteglnpcht.html

Java: UUID.randomUUID().toString()
来源：http://dali.tian-w.cn/Article/details/gtuccjjjcs.html

Go:   // 用 github.com/google/uuid
来源：http://dali.birdmap.top/Article/details/gtdvpklzhr.html

Ruby: SecureRandom.uuid
来源：http://dali.meibo888.top/Article/details/gtgaxehakt.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.iojbl.cn/Article/details/gtuwmjscas.html

[P02] MD5 / SHA256 摘要
来源：http://dali.316326.xyz/Article/details/gtawpmyirx.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.yongpay.top/Article/details/gtuekzhxnm.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.daxiang520.top/Article/details/gtrqidpgno.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.yuanzhike.top/Article/details/gtobizykpq.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.sweek.top/Article/details/gtxbzvtrvt.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.svipenyu.cn/Article/details/gtxlyezqrf.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.mhx1999.top/Article/details/gtkjfhrqtn.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.nanxinkj.top/Article/details/gtcpcqaick.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.quarkkingdee.top/Article/details/gtguqhzchk.html

[P03] 生成短随机字符串
来源：http://dali.jinqigfzy.top/Article/details/gtscnabdzd.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.wangdashe.top/Article/details/gtptfmffey.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.yuanzhike.top/Article/details/gtacterdid.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jqgfzy.top/Article/details/gtljkracqm.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jinqigufen.top/Article/details/gtuqjpfwou.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.meibo888.top/Article/details/gttpizaefg.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.yonumen.top/Article/details/gtjakiksog.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.dianchejie.cn/Article/details/gtfbiggmqk.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.ehwqpu.com/Article/details/gtukdozynp.html

[P04] 求长度
来源：http://dali.sysykeji.top/Article/details/gtzdrlgivc.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zycfv.cn/Article/details/gtmqtrarmz.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmybgwagd.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.hywenlv.cn/Article/details/gtpexhwjvy.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.wangshuangyany.cn/Article/details/gtfgdupdtx.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhixingplan.top/Article/details/gtuqdsrewz.html

Go:   len(arr);  len(m)
来源：http://dali.zycfv.cn/Article/details/gtcszsauzk.html

Ruby: x.length;  x.size
来源：http://dali.kuanghao11.cn/Article/details/gtauzpqtxa.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.xinyue.icu/Article/details/gtiqxaxoxx.html

[P05] 判断两个对象内容是否相等
来源：http://dali.316326.xyz/Article/details/gtwrpewvuy.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.jinqigufen.top/Article/details/gtxjuusecc.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.guowangkeji.top/Article/details/gtoqxknmin.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.sweek.top/Article/details/gtrifdlucw.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.xinyue.icu/Article/details/gtelraglbo.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdpjbvrgn.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.guannengcc.top/Article/details/gtoykygeah.html

Ruby: a == b
来源：http://dali.jyoumei.cn/Article/details/gtzhbuwxfd.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.guannengcc.top/Article/details/gtyncvrusx.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.yuanzhike.top/Article/details/gtlquldwpn.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.chenjidiqi.icu/Article/details/gtfljgfggu.html

PHP:  if (empty($x)) {}
来源：http://dali.cqqwz.cn/Article/details/gteijewqxr.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.hfpthk.cn/Article/details/gtwkorevwk.html

TS:   if (x == null) {}
来源：http://dali.cucudq.cn/Article/details/gtjjorlcic.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.quarkkingdee.top/Article/details/gtjibkivbm.html

Go:   if x == nil {}
来源：http://dali.c1oappe.top/Article/details/gtsngaqhyr.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.fzhhl.top/Article/details/gtmqgjrqyc.html

C#:   if (x is null) {}
来源：http://dali.bjfxy.top/Article/details/gtpytpminx.html

[P07] 防抖与节流
来源：http://dali.xuanzx.com/Article/details/gtpwraapil.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.hysaishi.cn/Article/details/gtdztmzwtn.html

PHP:  // 手写时间戳比较
来源：http://dali.ehwqpu.com/Article/details/gtpttsioxn.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.sysykeji.top/Article/details/gtugnjkheu.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.sxryk.cn/Article/details/gtabkpgcvr.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.iojbl.cn/Article/details/gturfijfdr.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.cqqwz.cn/Article/details/gtpcdkkawi.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiktykwga.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.smart0.xyz/Article/details/gtrnyairpj.html

[P08] 处理浮点精度问题
来源：http://dali.sysykeji.top/Article/details/gtrkpsdygk.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.cucudq.cn/Article/details/gtjwlyyxas.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.yj202588.top/Article/details/gtmrlfpqgl.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.gotoacloud.top/Article/details/gtsiqjbabf.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.gogol.net.cn/Article/details/gtmalulvtj.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.bjfxy.top/Article/details/gtjpvecenk.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.nanxuanxn.top/Article/details/gtovupurru.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.ybcxt.top/Article/details/gthocnwrwg.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.jqgfzy.top/Article/details/gtagnzjdjd.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtygaynzsg.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.chenzaomai.com/Article/details/gtzjtzbwlm.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtldhapsbe.html

[Q01] 创建表
来源：http://dali.daxiang520.top/Article/details/gtkdmikpfj.html

CREATE TABLE users (
来源：http://dali.316326.xyz/Article/details/gtwgxdzifz.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzzenovoz.html

name VARCHAR(50) NOT NULL,
来源：http://dali.gaohongyu789.top/Article/details/gthnphgyty.html

email VARCHAR(100) UNIQUE,
来源：http://dali.jqgfzy.top/Article/details/gtfhfvftxk.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.yuanzhike.top/Article/details/gtfxjhjumy.html

);
来源：http://dali.zhongyouzk.top/Article/details/gtzrgszmko.html

[Q02] 创建带外键的表
来源：http://dali.zhixingplan.top/Article/details/gtjqvsdpoe.html

CREATE TABLE orders (
来源：http://dali.fengsongda.top/Article/details/gtcipnpkzg.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.wangshuangyany.cn/Article/details/gtgrzkgler.html

user_id INT NOT NULL,
来源：http://dali.daria6918.cn/Article/details/gtvclycgbs.html

amount DECIMAL(10, 2),
来源：http://dali.fzhhl.top/Article/details/gtjncckobk.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.zhoulong.xyz/Article/details/gtsrhubllf.html

);
来源：http://dali.bjfxy.top/Article/details/gtxxdqiyjp.html

[Q03] 增加列
来源：http://dali.9152youxi.cn/Article/details/gtcttywtmb.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.feifeiyinyue.top/Article/details/gtxxlxconf.html

[Q04] 修改列类型
来源：http://dali.yj202588.top/Article/details/gtfhwiusdr.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.yongpay.top/Article/details/gtzsgvcbya.html

[Q05] 重命名列
来源：http://dali.guowangkeji.top/Article/details/gtgzfwnbad.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzkavnqtv.html

[Q06] 删除列
来源：http://dali.snrcjt.cn/Article/details/gtondmdhzt.html


<!-- 参考信息 -->