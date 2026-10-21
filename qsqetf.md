代发 wailian999

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zdqjudy.top/Article/details/gtbajgjudd.html

[M05] 设置退出码
来源：http://dali.kuanghao11.cn/Article/details/gtmorfzpin.html

Py:   sys.exit(1)
来源：http://dali.havefunace.top/Article/details/gtkkgelall.html

PHP:  exit(1);
来源：http://dali.hnxiangtu.top/Article/details/gtgwptxjty.html

JS:   process.exit(1)
来源：http://dali.zhiwuduotai.top/Article/details/gtwucmpnjj.html

TS:   process.exit(1)
来源：http://dali.birdmap.top/Article/details/gtfbdvtalx.html

Java: System.exit(1)
来源：http://dali.chenzaomai.com/Article/details/gtufiizetj.html

Go:   os.Exit(1)
来源：http://dali.feifeiyinyue.top/Article/details/gtucpwatcx.html

Ruby: exit 1
来源：http://dali.yuxming.cn/Article/details/gtykaptyzx.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.hongshengwenyu.top/Article/details/gtouwnaemd.html

[M06] 向标准错误输出
来源：http://dali.tianlin.xyz/Article/details/gtmhftwcgi.html

Py:   print("err", file=sys.stderr)
来源：http://dali.hywenlv.cn/Article/details/gtboutvdyb.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.daxiang520.top/Article/details/gtqusymqph.html

JS:   console.error("err")
来源：http://dali.kuanghao11.cn/Article/details/gtdsfsquud.html

TS:   console.error("err")
来源：http://dali.yuanzhike.top/Article/details/gttsilqzil.html

Java: System.err.println("err")
来源：http://dali.316326.xyz/Article/details/gttbyrrpto.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.yonumen.top/Article/details/gtpijwxmbd.html

Ruby: warn "err"
来源：http://dali.jqgufenzy.top/Article/details/gtdzgtentz.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.xuetiantiany.cn/Article/details/gtqajlloze.html

[M07] 判断是否为主入口
来源：http://dali.dianchejie.cn/Article/details/gtxrhzlbjt.html

Py:   if __name__ == "__main__":
来源：http://dali.jqgufenzy.top/Article/details/gtsehlnseh.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.tianlin.xyz/Article/details/gtkpcmhyxo.html

JS:   require.main === module
来源：http://dali.yangfankeji.com/Article/details/gtjulnmrjs.html

TS:   require.main === module
来源：http://dali.ivvv.top/Article/details/gtofrtzlaz.html

Java: public static void main(String[] args)
来源：http://dali.dashuyun.cn/Article/details/gtczwdolqu.html

Go:   func main()
来源：http://dali.pengpengdd.cyou/Article/details/gteifuvqyk.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.ivvv.top/Article/details/gtdvacorax.html

C#:   static void Main(string[] args)
来源：http://dali.zhiwuduotai.top/Article/details/gtegdchsqw.html

[M08] 获取系统与运行时信息
来源：http://dali.dashuyun.cn/Article/details/gtrrlnvcap.html

Py:   platform.system();  platform.python_version()
来源：http://dali.ivvv.top/Article/details/gttcirvqgs.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.nanxinkj.top/Article/details/gtpfkivkzw.html

JS:   process.platform;  process.version
来源：http://dali.shangyingyoupin.top/Article/details/gtcksqclws.html

TS:   process.platform;  process.version
来源：http://dali.yvedp.cn/Article/details/gtjovpjybk.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.gogol.net.cn/Article/details/gtkjxosbpv.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.pengpengdd.cyou/Article/details/gtopipovip.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.wangdashe.top/Article/details/gtvxbxhbbf.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.bjfxy.top/Article/details/gtuxicasuy.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtwkhbyjzt.html

N. 数据结构与算法
来源：http://dali.gogol.net.cn/Article/details/gtbzghwfaz.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtflpnjdnq.html

[N01] 二分查找（有序数组）
来源：http://dali.iojbl.cn/Article/details/gtlsvjkmhe.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.shanyushiyangtech.top/Article/details/gtxcdyzfks.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.jqgufenzy.top/Article/details/gtrtjrbxle.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.sweek.top/Article/details/gtfizwnmdf.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.c1oappe.top/Article/details/gtsxqwajpm.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.aizwys.cn/Article/details/gtrppbrgll.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.yvedp.cn/Article/details/gtnoixooap.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.pycfn.com/Article/details/gtqerwjxqg.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.chenjidiqi.icu/Article/details/gtquqcqrvf.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.daxiang520.top/Article/details/gtdyuqbjsf.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jinghuilouyu.cn/Article/details/gtplmmmkvb.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.sufxvd.cn/Article/details/gtjndcirei.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.hammf.cn/Article/details/gttbpeuplg.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yongpay.top/Article/details/gtepnvvvsg.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.daxiang520.top/Article/details/gtkfffcqfy.html

Go:   slices.Sort(arr)
来源：http://dali.xinyue.icu/Article/details/gtbrspuocm.html

Ruby: arr.sort
来源：http://dali.yangfankeji.com/Article/details/gtmqhdrndp.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.smart0.xyz/Article/details/gtmjsrfkrq.html

[N03] 快速排序（分治示例）
来源：http://dali.pengpengdd.cyou/Article/details/gtctfmogjw.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.xuetiantiany.cn/Article/details/gtotperoev.html

PHP:  // 递归实现，或用 usort
来源：http://dali.ehwqpu.com/Article/details/gtikwappmb.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.shuidangran.top/Article/details/gtvrqfzpvo.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.ybcxt.top/Article/details/gtlyosgmws.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.yuanzhike.top/Article/details/gtnzejxhro.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.wangshuangyany.cn/Article/details/gtwdjhzqkk.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.yj20258.top/Article/details/gtvttyutzd.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.cashguo.top/Article/details/gtcnazpfdt.html

[N04] 斐波那契数列
来源：http://dali.dashuyun.cn/Article/details/gtlnklbtjv.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhiwuduotai.top/Article/details/gtkhfwyads.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.chenzaomai.com/Article/details/gtfyduyelb.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yuxming.cn/Article/details/gtagjbnwqy.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.hywenlv.cn/Article/details/gtlrsrbuam.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.nanxuanxn.top/Article/details/gtgdmqbiam.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.guowangkeji.top/Article/details/gtryynxzaz.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.cqqwz.cn/Article/details/gtkhgxahfe.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.jinqigfzy.top/Article/details/gtlhndprnm.html

[N05] 最大公约数
来源：http://dali.jyoumei.cn/Article/details/gtwiymuqbb.html

Py:   math.gcd(a, b)
来源：http://dali.svipenyu.cn/Article/details/gtvahshisb.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.yangfankeji.com/Article/details/gtbsuxtaam.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.meibo888.top/Article/details/gtfxssdusn.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtggyfieqy.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.tianlin.xyz/Article/details/gtfavicysp.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwrqbzotk.html

Ruby: a.gcd(b)
来源：http://dali.haohaochexian.top/Article/details/gttnhgkyfp.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.nanxuanxn.top/Article/details/gtfhqaghaw.html

[N06] 判断回文字符串
来源：http://dali.hammf.cn/Article/details/gtvujshpcj.html

Py:   s == s[::-1]
来源：http://dali.nanxuanxn.top/Article/details/gtkjgspgeq.html

PHP:  $s === strrev($s);
来源：http://dali.wangdashe.top/Article/details/gtktjqooum.html

JS:   s === [...s].reverse().join("")
来源：http://dali.hywenlv.cn/Article/details/gtijympvuk.html

TS:   s === [...s].reverse().join("")
来源：http://dali.havefunace.top/Article/details/gtkqknasqn.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.meibo888.top/Article/details/gtcdxwifsv.html

Go:   // 双指针从两端比较
来源：http://dali.hnxiangtu.top/Article/details/gtzufnmnpz.html

Ruby: s == s.reverse
来源：http://dali.kuanghao11.cn/Article/details/gtygfjwcys.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.yangfankeji.com/Article/details/gtjqineicm.html

[N07] 两数之和（返回下标）
来源：http://dali.xylfe.cn/Article/details/gtgkptxroc.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gtikbicbuc.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.guowangkeji.top/Article/details/gtjguoqcqx.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtldofzjpy.html

TS:   // 手写 Map<string, number>
来源：http://dali.jinqigfzy.top/Article/details/gtdslktmbq.html

Java: // 手写 HashMap
来源：http://dali.yvedp.cn/Article/details/gtcuycnarf.html

Go:   // 手写 map[int]int
来源：http://dali.ybcxt.top/Article/details/gtckhfqpso.html

Ruby: // 手写 Hash
来源：http://dali.fzhhl.top/Article/details/gtajqyyewx.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.sxryk.cn/Article/details/gtywpbhlgg.html

[N08] 生成全排列
来源：http://dali.xuetiantiany.cn/Article/details/gtjthbzbjl.html

Py:   itertools.permutations(arr)
来源：http://dali.yangfankeji.com/Article/details/gtgteoefol.html

PHP:  // 手写递归交换
来源：http://dali.dashuyun.cn/Article/details/gttzgtpifl.html

JS:   // 手写回溯递归
来源：http://dali.tianlin.xyz/Article/details/gtjftldnph.html

TS:   // 手写回溯递归
来源：http://dali.zhixingplan.top/Article/details/gtaedamsmz.html

Java: // 手写回溯递归
来源：http://dali.gaohongyu789.top/Article/details/gtnqrkmpta.html

Go:   // 手写回溯递归
来源：http://dali.nanxinkj.top/Article/details/gttsoozsqj.html

Ruby: arr.permutation.to_a
来源：http://dali.chenzaomai.com/Article/details/gtgmcinuei.html

C#:   // 手写回溯递归
来源：http://dali.yongpay.top/Article/details/gtjxdlmgvw.html

[N09] 栈与队列
来源：http://dali.shangyingyoupin.top/Article/details/gtpcenlpct.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.yj20258888.top/Article/details/gtaxfrrqjo.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zycfv.cn/Article/details/gtuuaexker.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.svipenyu.cn/Article/details/gtbherdtvx.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.redwolf501.top/Article/details/gtpwuplzaq.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.xylfe.cn/Article/details/gtndakdbix.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.jlsjyb.cn/Article/details/gtixizwbfh.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.yongpay.top/Article/details/gtuujdujkv.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.smart0.xyz/Article/details/gtvxkshvzt.html

[N10] 链表节点定义
来源：http://dali.xuetiantiany.cn/Article/details/gtjgobmayi.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.mhx1999.top/Article/details/gtgbuwnewq.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.tian-w.cn/Article/details/gtegigqzan.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.yongpay.top/Article/details/gtiodwxjwy.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.yueranfly.top/Article/details/gtdnpvsbfj.html

Java: class Node { int v; Node next; }
来源：http://dali.xuetiantiany.cn/Article/details/gtzdaysrbn.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.hnxiangtu.top/Article/details/gtdaskxzqk.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.jqgufenzy.top/Article/details/gtincffzrd.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.ydzc1.top/Article/details/gtfuedhoqy.html

[N11] 二叉树中序遍历
来源：http://dali.ehwqpu.com/Article/details/gtpggfpmpy.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.meibo888.top/Article/details/gtldeeehif.html

PHP:  // 手写递归函数
来源：http://dali.sxryk.cn/Article/details/gtcdamplwe.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.cucudq.cn/Article/details/gtfvxxmdtf.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.chenlongwang.top/Article/details/gthtengzil.html

Java: // 手写递归
来源：http://dali.jqgfzy.top/Article/details/gtpzwaqfqh.html

Go:   // 手写递归
来源：http://dali.hywenlv.cn/Article/details/gtjwvahwyx.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.feifeiyinyue.top/Article/details/gtlxtlltta.html

C#:   // 手写递归
来源：http://dali.daxiang520.top/Article/details/gtfdoefvln.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.gaohongyu789.top/Article/details/gtsfxasfsd.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.tanke756.top/Article/details/gtkkicnwei.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.316326.xyz/Article/details/gtzqoymtde.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.daxiang520.top/Article/details/gtxaxeirkz.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.hfpthk.cn/Article/details/gtsoccawmh.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhoulong.xyz/Article/details/gtkwvqeerj.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.yuanzhike.top/Article/details/gtuntkviao.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.quarkkingdee.top/Article/details/gtoyrpcixl.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.ybcxt.top/Article/details/gtlsbcbvlj.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtbwzapkbc.html

O. 并发与异步
来源：http://dali.smart0.xyz/Article/details/gtiwjnjqjn.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtbnukjsyi.html

[O01] 启动一个线程
来源：http://dali.0kj1m.cn/Article/details/gtdamimktt.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.shangyingyoupin.top/Article/details/gtymvkwvad.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.yongpay.top/Article/details/gtqpclqqwr.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.gogol.net.cn/Article/details/gtyemljtja.html

TS:   // 同 JS
来源：http://dali.sufxvd.cn/Article/details/gtzftnwhns.html

Java: new Thread(() -> f()).start()
来源：http://dali.pycfn.com/Article/details/gttwlfyhgx.html

Go:   go f()
来源：http://dali.yj20258888.top/Article/details/gtwbwzsftx.html

Ruby: Thread.new { f }
来源：http://dali.redwolf501.top/Article/details/gtoelqpudj.html

C#:   Task.Run(() => F());
来源：http://dali.ehwqpu.com/Article/details/gtpyldlwna.html

[O02] 使用线程池
来源：http://dali.cashguo.top/Article/details/gtgdvmmdzj.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.vqdsnc.cn/Article/details/gtewheprnr.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.shangyingyoupin.top/Article/details/gtixfnftfs.html

JS:   // worker_threads 线程池
来源：http://dali.hammf.cn/Article/details/gtibgdmxdg.html

TS:   // worker_threads 线程池
来源：http://dali.yanxiufei.cn/Article/details/gtefectzea.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.feifeiyinyue.top/Article/details/gtjdrzyiug.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.ywan-chungtsiang.top/Article/details/gtulrajwsl.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.sweek.top/Article/details/gtyomntbxq.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.guowangkeji.top/Article/details/gtnqwgoohk.html

[O03] 加锁保护共享数据
来源：http://dali.wangshuangyany.cn/Article/details/gtwqqahrhh.html

Py:   with lock: shared += 1
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjbpvhqvq.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.mhx1999.top/Article/details/gtdhombyjg.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.cqqwz.cn/Article/details/gtfgggrlsu.html

TS:   // 同 JS
来源：http://dali.yj20258888.top/Article/details/gtyxcybivt.html

Java: synchronized (this) { shared++; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzewvsjih.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.yj202588.top/Article/details/gtjhqkkqnu.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.xuanzx.com/Article/details/gtvrbdbpis.html

C#:   lock (gate) { shared++; }
来源：http://dali.bjfxy.top/Article/details/gtpxbokqxe.html

[O04] 定义异步函数并等待
来源：http://dali.chenlongwang.top/Article/details/gteogggpei.html

Py:   async def f():⏎    await g()
来源：http://dali.shangyingyoupin.top/Article/details/gtjsxngzca.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.guannengcc.top/Article/details/gtydhzsvap.html

JS:   async function f() { await g(); }
来源：http://dali.chenzaomai.com/Article/details/gtynfzmchp.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.birdmap.top/Article/details/gtllqbgvdn.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.jqgfzy.top/Article/details/gtouecaefj.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.cheryme.top/Article/details/gtlxintnwq.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.yj20258.top/Article/details/gtgjubojhg.html

C#:   async Task F() { await G(); }
来源：http://dali.hfpthk.cn/Article/details/gtwsdddpsq.html

[O05] 并发执行并等待全部完成
来源：http://dali.jinqigfzy.top/Article/details/gtvfgxoiir.html

Py:   asyncio.gather(*tasks)
来源：http://dali.jinqigufen.top/Article/details/gtibaberld.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.yuanzhike.top/Article/details/gteokmylsr.html

JS:   await Promise.all(tasks)
来源：http://dali.xuanzx.com/Article/details/gtjnwmapsi.html

TS:   await Promise.all(tasks)
来源：http://dali.kuanghao11.cn/Article/details/gtvxsmtuxh.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.yueranfly.top/Article/details/gtsuxtqxed.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.gzhubu.top/Article/details/gthdsjmuve.html

Ruby: threads.map(&:join)
来源：http://dali.zycfv.cn/Article/details/gttwitzdep.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.jinqigfzy.top/Article/details/gtcyvzsplx.html

[O06] 使用进程池
来源：http://dali.yj20258.top/Article/details/gturlvgcnb.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.xziqi.cn/Article/details/gtxecyzvnz.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.aibaodan.cn/Article/details/gtotgakqgr.html

JS:   // child_process / cluster 模块
来源：http://dali.feifeiyinyue.top/Article/details/gtedjlarjn.html

TS:   // child_process / cluster 模块
来源：http://dali.guannengcc.top/Article/details/gtujycyqrs.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.ehwqpu.com/Article/details/gtjggqbixg.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.fengsongda.top/Article/details/gtexnjnycr.html

Ruby: // fork 块
来源：http://dali.xziqi.cn/Article/details/gtvkylcwxm.html

C#:   Parallel.For
来源：http://dali.xylfe.cn/Article/details/gtvlqhwhkn.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtnrpjpjbu.html

P. 常用工具函数
来源：http://dali.ydzc1.top/Article/details/gtphlcezbn.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtizynbvuo.html

[P01] 生成 UUID
来源：http://dali.zhiwuduotai.top/Article/details/gtsyznrlxk.html

Py:   str(uuid.uuid4())
来源：http://dali.smart0.xyz/Article/details/gtxalzncyd.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.wangshuangyany.cn/Article/details/gtjygnztcd.html

JS:   crypto.randomUUID()
来源：http://dali.yuxming.cn/Article/details/gtkyaejnww.html

TS:   crypto.randomUUID()
来源：http://dali.redwolf501.top/Article/details/gtxgooepuk.html

Java: UUID.randomUUID().toString()
来源：http://dali.iojbl.cn/Article/details/gtvlvazqmn.html

Go:   // 用 github.com/google/uuid
来源：http://dali.yuanzhike.top/Article/details/gtfklfxyiu.html

Ruby: SecureRandom.uuid
来源：http://dali.gotoacloud.top/Article/details/gtssnekpsa.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.jinqigufen.top/Article/details/gtnfnpytdh.html

[P02] MD5 / SHA256 摘要
来源：http://dali.meibo888.top/Article/details/gtcwzzxkee.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.wangshuangyany.cn/Article/details/gtikpcyepq.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.xylfe.cn/Article/details/gtcbwaamxg.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.chenlongwang.top/Article/details/gtieupdpnm.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zdqjudy.top/Article/details/gtxmmzymmp.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.redwolf501.top/Article/details/gtvdidwhld.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.hfpthk.cn/Article/details/gtvsogvbxx.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.snrcjt.cn/Article/details/gtamvwibiz.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.birdmap.top/Article/details/gtkcnsgxfp.html

[P03] 生成短随机字符串
来源：http://dali.sufxvd.cn/Article/details/gtbytcqjqp.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.yj20258888.top/Article/details/gtehkijxwp.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.hywenlv.cn/Article/details/gtylkasmqf.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.shuidangran.top/Article/details/gtoqplnaaq.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.bjfxy.top/Article/details/gtvmcacezh.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.shangyingyoupin.top/Article/details/gtmkjaednv.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.xuanzx.com/Article/details/gtjtjpdnpm.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.sysykeji.top/Article/details/gtdztfkwad.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.svipenyu.cn/Article/details/gtrdbhngzm.html

[P04] 求长度
来源：http://dali.quarkkingdee.top/Article/details/gtolutxncw.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.9152youxi.cn/Article/details/gtsuhdvhru.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.mhx1999.top/Article/details/gtpmgmdluk.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.fengsongda.top/Article/details/gttqjsicma.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jinghuilouyu.cn/Article/details/gtxkpbdksm.html

Java: list.size();  map.size();  s.length()
来源：http://dali.haohaochexian.top/Article/details/gtpvuqvgxx.html

Go:   len(arr);  len(m)
来源：http://dali.daxiang520.top/Article/details/gtggjcnxlf.html

Ruby: x.length;  x.size
来源：http://dali.snrcjt.cn/Article/details/gtykzhdafs.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.pycfn.com/Article/details/gtvcrreehq.html

[P05] 判断两个对象内容是否相等
来源：http://dali.xylfe.cn/Article/details/gteynwyzti.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.pycfn.com/Article/details/gtfwvmsksg.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.jqgfzy.top/Article/details/gtopnxaxzr.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zdqjudy.top/Article/details/gtgfkzuqpb.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.cqqwz.cn/Article/details/gtstiwcxuf.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.mhx1999.top/Article/details/gtgwyrwktn.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.gogol.net.cn/Article/details/gtxfvqhrrt.html

Ruby: a == b
来源：http://dali.hnxiangtu.top/Article/details/gtdpdqejhs.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.sysykeji.top/Article/details/gtpbcmkxhu.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.shzxlz.cn/Article/details/gtaxliuhgf.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.shzxlz.cn/Article/details/gtdwmptdfh.html

PHP:  if (empty($x)) {}
来源：http://dali.yvedp.cn/Article/details/gtevrnlztm.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.9152youxi.cn/Article/details/gtyfvxniyd.html

TS:   if (x == null) {}
来源：http://dali.ehwqpu.com/Article/details/gtdjglyman.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.jyoumei.cn/Article/details/gturaoxxiq.html

Go:   if x == nil {}
来源：http://dali.sysykeji.top/Article/details/gtlnasyilb.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.snrcjt.cn/Article/details/gtidtfypdd.html

C#:   if (x is null) {}
来源：http://dali.sweek.top/Article/details/gtpvyzbtnq.html

[P07] 防抖与节流
来源：http://dali.xziqi.cn/Article/details/gtlrqyszte.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.svipenyu.cn/Article/details/gtecvljyxz.html

PHP:  // 手写时间戳比较
来源：http://dali.yj202588.top/Article/details/gtemyyspsp.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.xuetiantiany.cn/Article/details/gtlsdcvuyl.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.bjfxy.top/Article/details/gturrrouxt.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.gotoacloud.top/Article/details/gtchyfpaun.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.havefunace.top/Article/details/gtjczixwdr.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.pengpengdd.cyou/Article/details/gtynezxtfs.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhengqikj.top/Article/details/gtxwwkbofs.html

[P08] 处理浮点精度问题
来源：http://dali.guowangkeji.top/Article/details/gtrvtyutxk.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.jinghuilouyu.cn/Article/details/gtqhdiksur.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwzfrquvw.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.pengpengdd.cyou/Article/details/gtrvpgklqi.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.ehwqpu.com/Article/details/gteccrnluq.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdyieefrd.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.xuanzx.com/Article/details/gtxkyrmsju.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.kuanghao11.cn/Article/details/gteupmebkf.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.cheryme.top/Article/details/gtzybsqsds.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtinoujvhy.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtghrnsqan.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtvhazolyz.html

[Q01] 创建表
来源：http://dali.yuxming.cn/Article/details/gttdiupnte.html

CREATE TABLE users (
来源：http://dali.cashguo.top/Article/details/gtvabsepsp.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.gzhubu.top/Article/details/gtxushssgh.html

name VARCHAR(50) NOT NULL,
来源：http://dali.cucudq.cn/Article/details/gtnttlmenr.html

email VARCHAR(100) UNIQUE,
来源：http://dali.ivvv.top/Article/details/gtnszfuszr.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.tianlin.xyz/Article/details/gtxwpyocvu.html

);
来源：http://dali.hongshengwenyu.top/Article/details/gtxzrzxxht.html

[Q02] 创建带外键的表
来源：http://dali.haohaochexian.top/Article/details/gtssqsctuw.html

CREATE TABLE orders (
来源：http://dali.nanxinkj.top/Article/details/gtdjnframc.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.xylfe.cn/Article/details/gtnyyumgqs.html

user_id INT NOT NULL,
来源：http://dali.cashguo.top/Article/details/gthlwhvikf.html

amount DECIMAL(10, 2),
来源：http://dali.tian-w.cn/Article/details/gtlbusjlmo.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.dianchejie.cn/Article/details/gthlknejqh.html

);
来源：http://dali.haohaochexian.top/Article/details/gtphsblxjz.html

[Q03] 增加列
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfhvojflz.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.xylfe.cn/Article/details/gtsgrgtpgy.html

[Q04] 修改列类型
来源：http://dali.ybcxt.top/Article/details/gtpnkjrogw.html


<!-- 参考信息 -->