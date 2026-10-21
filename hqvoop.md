代发 wailian999

C#:   Directory.GetCurrentDirectory()
来源：http://dali.cucudq.cn/Article/details/gtjaomzjal.html

[M05] 设置退出码
来源：http://dali.hnqzz.top/Article/details/gtieqoutzo.html

Py:   sys.exit(1)
来源：http://dali.sysykeji.top/Article/details/gtssajanhk.html

PHP:  exit(1);
来源：http://dali.wangshuangyany.cn/Article/details/gtyxubtqua.html

JS:   process.exit(1)
来源：http://dali.hysaishi.cn/Article/details/gtiaomipgb.html

TS:   process.exit(1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtubbnlsfx.html

Java: System.exit(1)
来源：http://dali.hnxiangtu.top/Article/details/gtcqwiidau.html

Go:   os.Exit(1)
来源：http://dali.ppjwa.cn/Article/details/gttgstoyar.html

Ruby: exit 1
来源：http://dali.andypj.xyz/Article/details/gtpqnsdufc.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.tian-w.cn/Article/details/gtwinomndw.html

[M06] 向标准错误输出
来源：http://dali.xuetiantiany.cn/Article/details/gtssnbfxvc.html

Py:   print("err", file=sys.stderr)
来源：http://dali.haohaochexian.top/Article/details/gtunxaanhf.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.feifeiyinyue.top/Article/details/gtmylujaok.html

JS:   console.error("err")
来源：http://dali.quarkkingdee.top/Article/details/gtdqqcxgmx.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gtpjhkpisb.html

Java: System.err.println("err")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnwntuqza.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.yonumen.top/Article/details/gtwjtgpjhk.html

Ruby: warn "err"
来源：http://dali.bjfxy.top/Article/details/gteeojjhdp.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.jinghuilouyu.cn/Article/details/gthqwmfarq.html

[M07] 判断是否为主入口
来源：http://dali.ybcxt.top/Article/details/gtdcfyidal.html

Py:   if __name__ == "__main__":
来源：http://dali.dashuyun.cn/Article/details/gtsfzmvjwx.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.shuidangran.top/Article/details/gteimzpqlh.html

JS:   require.main === module
来源：http://dali.fengsongda.top/Article/details/gtqagmrsmb.html

TS:   require.main === module
来源：http://dali.haohaochexian.top/Article/details/gtgxaqtowk.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gtveewiosf.html

Go:   func main()
来源：http://dali.yj202588.top/Article/details/gtmamoycah.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhoulong.xyz/Article/details/gtqjuufjgs.html

C#:   static void Main(string[] args)
来源：http://dali.sysykeji.top/Article/details/gthjpeycun.html

[M08] 获取系统与运行时信息
来源：http://dali.fengsongda.top/Article/details/gtgbmnewmu.html

Py:   platform.system();  platform.python_version()
来源：http://dali.dianchejie.cn/Article/details/gttutdsapk.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zdqjudy.top/Article/details/gttsjehliv.html

JS:   process.platform;  process.version
来源：http://dali.cheryme.top/Article/details/gtmbwwschr.html

TS:   process.platform;  process.version
来源：http://dali.nanxinkj.top/Article/details/gtcvcbmbdm.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.jinqigufen.top/Article/details/gttvujcgpr.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.hnqzz.top/Article/details/gtsihfmzpd.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zdqjudy.top/Article/details/gtfhfmqdpo.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.svipenyu.cn/Article/details/gtcmcqsqni.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtnovtgyqh.html

N. 数据结构与算法
来源：http://dali.haohaochexian.top/Article/details/gtpstrjrna.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtzhksxrjx.html

[N01] 二分查找（有序数组）
来源：http://dali.ybcxt.top/Article/details/gtwyqlafgk.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.yonumen.top/Article/details/gtpoadfobc.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.haohaochexian.top/Article/details/gtibrrlvjv.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.sufxvd.cn/Article/details/gtgpcuwsty.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.sufxvd.cn/Article/details/gtlmswsyfl.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.wangdashe.top/Article/details/gthxycnwxl.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.kuanghao11.cn/Article/details/gtlkogesbv.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.jqgufenzy.top/Article/details/gtsezdxmzg.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.chenlongwang.top/Article/details/gtmwthhkho.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.chenjidiqi.icu/Article/details/gthgpcsjuu.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwuhizrfn.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.yuanzhike.top/Article/details/gtbbivgiwe.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.ydzc1.top/Article/details/gttvncpeos.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.xziqi.cn/Article/details/gtdbtcmnyh.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.wangdashe.top/Article/details/gtuwmpmsvh.html

Go:   slices.Sort(arr)
来源：http://dali.jinqigufen.top/Article/details/gtktfnzwjz.html

Ruby: arr.sort
来源：http://dali.iojbl.cn/Article/details/gtuamogpop.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.yj20258888.top/Article/details/gtqpnmycgo.html

[N03] 快速排序（分治示例）
来源：http://dali.gzhubu.top/Article/details/gtpfqtlpxw.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.daxiang520.top/Article/details/gtzbjcvpps.html

PHP:  // 递归实现，或用 usort
来源：http://dali.redwolf501.top/Article/details/gtwerbrdpp.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.gotoacloud.top/Article/details/gtlybemrmw.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yuxming.cn/Article/details/gtjaovgjiy.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.bjfxy.top/Article/details/gthgxzkuzm.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zycfv.cn/Article/details/gtwfaqnoxj.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.hfpthk.cn/Article/details/gttxxurpnd.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.ppjwa.cn/Article/details/gtlnzxglsz.html

[N04] 斐波那契数列
来源：http://dali.c1oappe.top/Article/details/gtnkcxlzpi.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.dashuyun.cn/Article/details/gtfwtqjatz.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.haohaochexian.top/Article/details/gtlxpsbwzs.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.ppjwa.cn/Article/details/gtsugkigxx.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.pycfn.com/Article/details/gtljjiltwv.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.yanxiufei.cn/Article/details/gtzsgcsduz.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.pengpengdd.cyou/Article/details/gtbovzivgb.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.smart0.xyz/Article/details/gtgwjypkwi.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.ydzc1.top/Article/details/gtkaqhtfuk.html

[N05] 最大公约数
来源：http://dali.hywenlv.cn/Article/details/gtkouzftgp.html

Py:   math.gcd(a, b)
来源：http://dali.haohaochexian.top/Article/details/gtqvyfhiqa.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.dianchejie.cn/Article/details/gttajunect.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.cucudq.cn/Article/details/gtfdglvzjf.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhoulong.xyz/Article/details/gtfvpwlqjv.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhiwuduotai.top/Article/details/gtwqzszqbb.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.316326.xyz/Article/details/gtmvqdajfl.html

Ruby: a.gcd(b)
来源：http://dali.yanxiufei.cn/Article/details/gtpiubuchf.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.tian-w.cn/Article/details/gtljoistgu.html

[N06] 判断回文字符串
来源：http://dali.andypj.xyz/Article/details/gtrgtixqik.html

Py:   s == s[::-1]
来源：http://dali.cdnleiting.top/Article/details/gtvzrhfljy.html

PHP:  $s === strrev($s);
来源：http://dali.fengsongda.top/Article/details/gthjuzfjny.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zdqjudy.top/Article/details/gtfonjivam.html

TS:   s === [...s].reverse().join("")
来源：http://dali.shuidangran.top/Article/details/gtkssmttgy.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.hywenlv.cn/Article/details/gtitfjzcod.html

Go:   // 双指针从两端比较
来源：http://dali.haohaochexian.top/Article/details/gtspeqhitz.html

Ruby: s == s.reverse
来源：http://dali.hfpthk.cn/Article/details/gtkomcvsue.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.jqgufenzy.top/Article/details/gtlgooktve.html

[N07] 两数之和（返回下标）
来源：http://dali.fengsongda.top/Article/details/gtvmcvabrq.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.xziqi.cn/Article/details/gtcywbauqh.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.smart0.xyz/Article/details/gtwdltbeun.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.sxryk.cn/Article/details/gtgrjqzggc.html

TS:   // 手写 Map<string, number>
来源：http://dali.cdnleiting.top/Article/details/gtdkgqsfnn.html

Java: // 手写 HashMap
来源：http://dali.yvedp.cn/Article/details/gtysakgiwb.html

Go:   // 手写 map[int]int
来源：http://dali.aizwys.cn/Article/details/gtyspqipqx.html

Ruby: // 手写 Hash
来源：http://dali.vqdsnc.cn/Article/details/gtxfansejy.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.xuetiantiany.cn/Article/details/gtrcwmpxfm.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gtqluoscbk.html

Py:   itertools.permutations(arr)
来源：http://dali.cdnleiting.top/Article/details/gtptqvlkvs.html

PHP:  // 手写递归交换
来源：http://dali.yvedp.cn/Article/details/gtnpeuayom.html

JS:   // 手写回溯递归
来源：http://dali.zhengqikj.top/Article/details/gthccppccm.html

TS:   // 手写回溯递归
来源：http://dali.birdmap.top/Article/details/gtxdqpgdeh.html

Java: // 手写回溯递归
来源：http://dali.bjfxy.top/Article/details/gtaigknrqh.html

Go:   // 手写回溯递归
来源：http://dali.0kj1m.cn/Article/details/gtlutnnozj.html

Ruby: arr.permutation.to_a
来源：http://dali.hnqzz.top/Article/details/gtrlwzkqkc.html

C#:   // 手写回溯递归
来源：http://dali.meibo888.top/Article/details/gtctieygaa.html

[N09] 栈与队列
来源：http://dali.fzhhl.top/Article/details/gtsvmfkffz.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.xuanzx.com/Article/details/gtiuytbdzp.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.yangfankeji.com/Article/details/gtrtbpikbz.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.redwolf501.top/Article/details/gtmqburofw.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvycbgstk.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.birdmap.top/Article/details/gtcnwjepxn.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.shangyingyoupin.top/Article/details/gtcdoxvmjb.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhaomingkeji.xyz/Article/details/gtujifyjnb.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.daxiang520.top/Article/details/gthnhqpbii.html

[N10] 链表节点定义
来源：http://dali.gaohongyu789.top/Article/details/gtjpzlobmj.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.haohaochexian.top/Article/details/gtlotmcefx.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.sweek.top/Article/details/gtzzvqkakk.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.guowangkeji.top/Article/details/gtgszuwjyb.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.xuanzx.com/Article/details/gtpfkkdwjh.html

Java: class Node { int v; Node next; }
来源：http://dali.chenzaomai.com/Article/details/gtnmvmpbjp.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.jianghu66.top/Article/details/gtpirxxbcu.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.yangfankeji.com/Article/details/gtxksgxldm.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.316326.xyz/Article/details/gtupyxljis.html

[N11] 二叉树中序遍历
来源：http://dali.nwbrower.top/Article/details/gtrwgsnuhx.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.316326.xyz/Article/details/gtfkaagzhy.html

PHP:  // 手写递归函数
来源：http://dali.hywenlv.cn/Article/details/gtoafydjwh.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jinqigufen.top/Article/details/gtnhqjqzre.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.aizwys.cn/Article/details/gtcjdoezdb.html

Java: // 手写递归
来源：http://dali.guannengcc.top/Article/details/gtkgujkobg.html

Go:   // 手写递归
来源：http://dali.iojbl.cn/Article/details/gtfqgrnuxn.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhoulong.xyz/Article/details/gtoblnhplo.html

C#:   // 手写递归
来源：http://dali.sweek.top/Article/details/gtuxyhkukv.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.jlsjyb.cn/Article/details/gtgavntvsb.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.shanyushiyangtech.top/Article/details/gtfiwvgetw.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.yuxming.cn/Article/details/gtftrzfzmc.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.hysaishi.cn/Article/details/gthokwnldb.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.ybcxt.top/Article/details/gtnppceecb.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.nanxinkj.top/Article/details/gtkygymvhr.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.tian-w.cn/Article/details/gtbfzetlyq.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.cucudq.cn/Article/details/gtpggdigas.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.sweek.top/Article/details/gtbqwrtjon.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtutsvvhdc.html

O. 并发与异步
来源：http://dali.316326.xyz/Article/details/gtogfijoen.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtcasccymn.html

[O01] 启动一个线程
来源：http://dali.chenzaomai.com/Article/details/gtzcftxdhf.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.jlsjyb.cn/Article/details/gtnrveojdq.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.yj20258.top/Article/details/gtfnqnqyrs.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.9152youxi.cn/Article/details/gtmtucybid.html

TS:   // 同 JS
来源：http://dali.jiagoushi.top/Article/details/gtlahiiqon.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhoulong.xyz/Article/details/gtyuppfhep.html

Go:   go f()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqjhvuvah.html

Ruby: Thread.new { f }
来源：http://dali.zhongyouzk.top/Article/details/gtglyahblm.html

C#:   Task.Run(() => F());
来源：http://dali.fengsongda.top/Article/details/gtmapdkfli.html

[O02] 使用线程池
来源：http://dali.daxiang520.top/Article/details/gtenxzwzbg.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.fzhhl.top/Article/details/gtvmikymqw.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.snrcjt.cn/Article/details/gtcsfymvwn.html

JS:   // worker_threads 线程池
来源：http://dali.ydzc1.top/Article/details/gtswbrfqos.html

TS:   // worker_threads 线程池
来源：http://dali.fzhhl.top/Article/details/gtlbkbiyst.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.fengsongda.top/Article/details/gtwelgcixh.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.fengsongda.top/Article/details/gtvnchsjiy.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.wangdashe.top/Article/details/gtrqbneelj.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhengqikj.top/Article/details/gtvlfnnuln.html

[O03] 加锁保护共享数据
来源：http://dali.jinghuilouyu.cn/Article/details/gtiycwvpgf.html

Py:   with lock: shared += 1
来源：http://dali.cashguo.top/Article/details/gtjraufssv.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.yongpay.top/Article/details/gtwcwswkgo.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gtmlyxlqxx.html

TS:   // 同 JS
来源：http://dali.dashuyun.cn/Article/details/gtfipofqwx.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhixingplan.top/Article/details/gtssbymykb.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.cqqwz.cn/Article/details/gtivhoiqpn.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.jqgfzy.top/Article/details/gtfljepqwd.html

C#:   lock (gate) { shared++; }
来源：http://dali.jianghu66.top/Article/details/gtrixbpyfy.html

[O04] 定义异步函数并等待
来源：http://dali.aizwys.cn/Article/details/gtlrsmbvxt.html

Py:   async def f():⏎    await g()
来源：http://dali.hongshengwenyu.top/Article/details/gtgatxdovy.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.ppjwa.cn/Article/details/gtqbcxkuuy.html

JS:   async function f() { await g(); }
来源：http://dali.cheryme.top/Article/details/gtwzxphnfb.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.aibaodan.cn/Article/details/gtmdbritsk.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gtsowefkdu.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzjstngwl.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.cdnleiting.top/Article/details/gtarmdbzdu.html

C#:   async Task F() { await G(); }
来源：http://dali.hammf.cn/Article/details/gtzjnqkiuu.html

[O05] 并发执行并等待全部完成
来源：http://dali.9152youxi.cn/Article/details/gtxlppljzp.html

Py:   asyncio.gather(*tasks)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthgipfisp.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.haohaochexian.top/Article/details/gtewtowdvc.html

JS:   await Promise.all(tasks)
来源：http://dali.jinghuilouyu.cn/Article/details/gtuvdycoer.html

TS:   await Promise.all(tasks)
来源：http://dali.chenlongwang.top/Article/details/gtnzzhrsse.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.wangshuangyany.cn/Article/details/gtrbfseqmb.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.xziqi.cn/Article/details/gtzsojtime.html

Ruby: threads.map(&:join)
来源：http://dali.yj20258.top/Article/details/gtastfkjwg.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpmnbklon.html

[O06] 使用进程池
来源：http://dali.hongshengwenyu.top/Article/details/gtgzikedjy.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.haohaochexian.top/Article/details/gtonwdwzzj.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.jqgfzy.top/Article/details/gtbfphemwt.html

JS:   // child_process / cluster 模块
来源：http://dali.kuanghao11.cn/Article/details/gtxnohtuqy.html

TS:   // child_process / cluster 模块
来源：http://dali.jinqigfzy.top/Article/details/gtcdgbqyog.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhoulong.xyz/Article/details/gtvjgnqwdd.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.yanxiufei.cn/Article/details/gtzmowvohb.html

Ruby: // fork 块
来源：http://dali.gotoacloud.top/Article/details/gtxewbhfxa.html

C#:   Parallel.For
来源：http://dali.sufxvd.cn/Article/details/gtjnkrflax.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtthwqtbvf.html

P. 常用工具函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmfwwbbkl.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtfmdaztrk.html

[P01] 生成 UUID
来源：http://dali.hnxiangtu.top/Article/details/gtvofqyngd.html

Py:   str(uuid.uuid4())
来源：http://dali.gotoacloud.top/Article/details/gtcspbxgwq.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.xuetiantiany.cn/Article/details/gtukoafayo.html

JS:   crypto.randomUUID()
来源：http://dali.cucudq.cn/Article/details/gtimqrzolq.html

TS:   crypto.randomUUID()
来源：http://dali.yueranfly.top/Article/details/gtkomcfypb.html

Java: UUID.randomUUID().toString()
来源：http://dali.xuanzx.com/Article/details/gtxcblmnwj.html

Go:   // 用 github.com/google/uuid
来源：http://dali.wangdashe.top/Article/details/gteyzrocvo.html

Ruby: SecureRandom.uuid
来源：http://dali.cucudq.cn/Article/details/gtplepibid.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.fzhhl.top/Article/details/gtzdpkoujk.html

[P02] MD5 / SHA256 摘要
来源：http://dali.yj20258888.top/Article/details/gtqvbyhkuf.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.ydzc1.top/Article/details/gtuaaodble.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.feifeiyinyue.top/Article/details/gtrlymoasw.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.ehwqpu.com/Article/details/gtijvezfto.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhixingplan.top/Article/details/gtsfiulbgn.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.sweek.top/Article/details/gtdhcwowps.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.yueranfly.top/Article/details/gtrxmtroek.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.nanxinkj.top/Article/details/gtfpmfvsep.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.shuidangran.top/Article/details/gtijpetxnt.html

[P03] 生成短随机字符串
来源：http://dali.mhx1999.top/Article/details/gtswjtegdo.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.guannengcc.top/Article/details/gtuvzfeuxj.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.cashguo.top/Article/details/gtnvuwvjzg.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.feifeiyinyue.top/Article/details/gtokfrbqyw.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.gogol.net.cn/Article/details/gtslirsvig.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.gzhubu.top/Article/details/gtmrxyyjwm.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.wangdashe.top/Article/details/gtvdnwsojt.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.xylfe.cn/Article/details/gtbweouqyj.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.chenlongwang.top/Article/details/gtquwlznnu.html

[P04] 求长度
来源：http://dali.guannengcc.top/Article/details/gtzsahnclc.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.yongpay.top/Article/details/gtbxxwcxng.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.nanxuanxn.top/Article/details/gtatfhudsh.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.cdnleiting.top/Article/details/gtxdxduyab.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.fengsongda.top/Article/details/gtyubxnpte.html

Java: list.size();  map.size();  s.length()
来源：http://dali.birdmap.top/Article/details/gtoresogno.html

Go:   len(arr);  len(m)
来源：http://dali.jlsjyb.cn/Article/details/gtlyxdyrmx.html

Ruby: x.length;  x.size
来源：http://dali.sysykeji.top/Article/details/gturwpvcio.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.feifeiyinyue.top/Article/details/gtvjeesshu.html

[P05] 判断两个对象内容是否相等
来源：http://dali.havefunace.top/Article/details/gtcfvntxzi.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.jqgfzy.top/Article/details/gtpjbqwlww.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.yonumen.top/Article/details/gtvtbkjaox.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhiwuduotai.top/Article/details/gtxhjgdpyr.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.iojbl.cn/Article/details/gtplaxrmzt.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.yuxming.cn/Article/details/gtignzijvy.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.zhixingplan.top/Article/details/gtxalqaaei.html

Ruby: a == b
来源：http://dali.yanxiufei.cn/Article/details/gtbvscagms.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.jyoumei.cn/Article/details/gtieoetdzv.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.cqqwz.cn/Article/details/gtzxwqozoz.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zycfv.cn/Article/details/gthccdnnoe.html

PHP:  if (empty($x)) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrukeyybe.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.dianchejie.cn/Article/details/gtwvugizvb.html

TS:   if (x == null) {}
来源：http://dali.redwolf501.top/Article/details/gtdsuamlql.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.pengpengdd.cyou/Article/details/gteczcupmp.html

Go:   if x == nil {}
来源：http://dali.nanxinkj.top/Article/details/gtihpzgcfz.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.hnxiangtu.top/Article/details/gtflcyktzg.html

C#:   if (x is null) {}
来源：http://dali.jiagoushi.top/Article/details/gtcpeeadlw.html

[P07] 防抖与节流
来源：http://dali.aibaodan.cn/Article/details/gtfhtkaang.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.dianchejie.cn/Article/details/gtjeptssbs.html

PHP:  // 手写时间戳比较
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwlsmapnm.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.nwbrower.top/Article/details/gteminddqx.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yueranfly.top/Article/details/gtuvgmqpsq.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.9152youxi.cn/Article/details/gtumsqonlh.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.gzhubu.top/Article/details/gtaiwmxssg.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.shzxlz.cn/Article/details/gtkirrpqcm.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnljkwpvx.html

[P08] 处理浮点精度问题
来源：http://dali.hfpthk.cn/Article/details/gtddlccxba.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.birdmap.top/Article/details/gtwfkznnkx.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.hywenlv.cn/Article/details/gtmqyzrdqk.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.nanxuanxn.top/Article/details/gtcivuddfw.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.ivvv.top/Article/details/gtqrxpudvp.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.pengpengdd.cyou/Article/details/gttrsfqmnr.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.tanke756.top/Article/details/gtzzybxqnt.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.hfpthk.cn/Article/details/gttsmkvbpu.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcpodrqtw.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gthibbmnpl.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.jiagoushi.top/Article/details/gtlcacexxe.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtphczpnsk.html

[Q01] 创建表
来源：http://dali.mhx1999.top/Article/details/gtnbhussjb.html

CREATE TABLE users (
来源：http://dali.cucudq.cn/Article/details/gtztntfifg.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.gzhubu.top/Article/details/gtmbaxgluo.html

name VARCHAR(50) NOT NULL,
来源：http://dali.havefunace.top/Article/details/gtdywoyumg.html

email VARCHAR(100) UNIQUE,
来源：http://dali.hfpthk.cn/Article/details/gtoongqgrx.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.andypj.xyz/Article/details/gtpzzgkaeu.html

);
来源：http://dali.chenjidiqi.icu/Article/details/gtqpmrndev.html

[Q02] 创建带外键的表
来源：http://dali.pengpengdd.cyou/Article/details/gtjshpzgaw.html

CREATE TABLE orders (
来源：http://dali.gotoacloud.top/Article/details/gtoxkitvvb.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.hysaishi.cn/Article/details/gtxqcrpfwd.html

user_id INT NOT NULL,
来源：http://dali.jqgufenzy.top/Article/details/gtgkfsmlvn.html

amount DECIMAL(10, 2),
来源：http://dali.aibaodan.cn/Article/details/gturhdagno.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.hongshengwenyu.top/Article/details/gtisleplcl.html

);
来源：http://dali.ivvv.top/Article/details/gtdohwkbja.html

[Q03] 增加列
来源：http://dali.zhoulong.xyz/Article/details/gtykhqmmop.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.kuanghao11.cn/Article/details/gtdkrivbvq.html

[Q04] 修改列类型
来源：http://dali.zhoulong.xyz/Article/details/gtnrvqrpyi.html


<!-- 参考信息 -->