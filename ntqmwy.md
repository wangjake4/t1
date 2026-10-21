代发 wailian999

C#:   Directory.GetCurrentDirectory()
来源：http://dali.hammf.cn/Article/details/gtxhieoegk.html

[M05] 设置退出码
来源：http://dali.nanxuanxn.top/Article/details/gtequljrus.html

Py:   sys.exit(1)
来源：http://dali.shanyushiyangtech.top/Article/details/gttorrzvmq.html

PHP:  exit(1);
来源：http://dali.zhoulong.xyz/Article/details/gtacudbcih.html

JS:   process.exit(1)
来源：http://dali.daxiang520.top/Article/details/gtmyuoceub.html

TS:   process.exit(1)
来源：http://dali.cashguo.top/Article/details/gtzepkluuw.html

Java: System.exit(1)
来源：http://dali.zhixingplan.top/Article/details/gtpxhricka.html

Go:   os.Exit(1)
来源：http://dali.hnxiangtu.top/Article/details/gtdxfjngih.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gtmdvpfjmo.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxhjtioij.html

[M06] 向标准错误输出
来源：http://dali.yonumen.top/Article/details/gtmpilqtlm.html

Py:   print("err", file=sys.stderr)
来源：http://dali.jianghu66.top/Article/details/gtbalfxavu.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.shanyushiyangtech.top/Article/details/gtrcvhqoaf.html

JS:   console.error("err")
来源：http://dali.yj20258.top/Article/details/gtomjojxnx.html

TS:   console.error("err")
来源：http://dali.bjfxy.top/Article/details/gtkbjqqphb.html

Java: System.err.println("err")
来源：http://dali.quarkkingdee.top/Article/details/gttffnrewz.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.jianghu66.top/Article/details/gtlxtllphy.html

Ruby: warn "err"
来源：http://dali.yueranfly.top/Article/details/gtpkzlcxky.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhengqikj.top/Article/details/gtnxufatoj.html

[M07] 判断是否为主入口
来源：http://dali.dashuyun.cn/Article/details/gtrjppqjpd.html

Py:   if __name__ == "__main__":
来源：http://dali.shanyushiyangtech.top/Article/details/gtbjfqcbwm.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.havefunace.top/Article/details/gtbnhpjqfq.html

JS:   require.main === module
来源：http://dali.chenzaomai.com/Article/details/gtdvxmsiwq.html

TS:   require.main === module
来源：http://dali.aibaodan.cn/Article/details/gtakkuckkj.html

Java: public static void main(String[] args)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyxizmwev.html

Go:   func main()
来源：http://dali.cashguo.top/Article/details/gtzosikwlq.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.jiagoushi.top/Article/details/gtzdeaepjo.html

C#:   static void Main(string[] args)
来源：http://dali.yueranfly.top/Article/details/gtxmsastzv.html

[M08] 获取系统与运行时信息
来源：http://dali.tianlin.xyz/Article/details/gtiwqwricd.html

Py:   platform.system();  platform.python_version()
来源：http://dali.smart0.xyz/Article/details/gtzimdeurb.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.jqgfzy.top/Article/details/gtjmaomncj.html

JS:   process.platform;  process.version
来源：http://dali.jlsjyb.cn/Article/details/gtistmfupt.html

TS:   process.platform;  process.version
来源：http://dali.svipenyu.cn/Article/details/gtuptgsnoi.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.shangyingyoupin.top/Article/details/gtfvvwtgrr.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.yonumen.top/Article/details/gtqjxippbm.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.xylfe.cn/Article/details/gtpeqmyzab.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.ybcxt.top/Article/details/gtvxrswgow.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gteubbhcqn.html

N. 数据结构与算法
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttpfnuumc.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gttfajfwga.html

[N01] 二分查找（有序数组）
来源：http://dali.sufxvd.cn/Article/details/gthqsztgmi.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhiwuduotai.top/Article/details/gtgwxydgvw.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.hfpthk.cn/Article/details/gtwraewvpm.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zycfv.cn/Article/details/gtzotasdwn.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaxayfdos.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.snrcjt.cn/Article/details/gttrsoztkw.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.cashguo.top/Article/details/gtgdbpsasa.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.sweek.top/Article/details/gtobswzfht.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.daxiang520.top/Article/details/gtscqodswt.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.hysaishi.cn/Article/details/gtaziqwuev.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yonumen.top/Article/details/gttoaauhrs.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.yueranfly.top/Article/details/gtybioggnm.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.cdnleiting.top/Article/details/gtvgnnngsw.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.hfpthk.cn/Article/details/gtpufhmxrs.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.cucudq.cn/Article/details/gttyjkxqzc.html

Go:   slices.Sort(arr)
来源：http://dali.sysykeji.top/Article/details/gtjlwknymz.html

Ruby: arr.sort
来源：http://dali.jqgfzy.top/Article/details/gtxkszxbma.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.xuetiantiany.cn/Article/details/gtadajgpfc.html

[N03] 快速排序（分治示例）
来源：http://dali.nanxinkj.top/Article/details/gtuywugznk.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.9152youxi.cn/Article/details/gthemqiqnp.html

PHP:  // 递归实现，或用 usort
来源：http://dali.shanyushiyangtech.top/Article/details/gtekeuzbrf.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.cdnleiting.top/Article/details/gtbszklhhs.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.bjfxy.top/Article/details/gtdvdtjnwv.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.chenjidiqi.icu/Article/details/gtnnmbmrqm.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.dashuyun.cn/Article/details/gtgeqyujlz.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.jinghuilouyu.cn/Article/details/gtqxqxagaf.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.jinghuilouyu.cn/Article/details/gtmwjaxnsy.html

[N04] 斐波那契数列
来源：http://dali.gzhubu.top/Article/details/gteiiaxwxb.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.shuidangran.top/Article/details/gtgavtvzcy.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.jinqigfzy.top/Article/details/gtqstixjfb.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.guowangkeji.top/Article/details/gtguvruuwi.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yueranfly.top/Article/details/gttpqoryfh.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.yonumen.top/Article/details/gtnokjyjnq.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhongyouzk.top/Article/details/gtvjveclzv.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhiwuduotai.top/Article/details/gtxwkuoivf.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.gogol.net.cn/Article/details/gthbaxiidy.html

[N05] 最大公约数
来源：http://dali.yj202588.top/Article/details/gtvidgjjrr.html

Py:   math.gcd(a, b)
来源：http://dali.cashguo.top/Article/details/gtxxzkxfoi.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.yj20258888.top/Article/details/gtxvirrcsg.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.nwbrower.top/Article/details/gtcrnyxzwo.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhoulong.xyz/Article/details/gtmqaifral.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.xylfe.cn/Article/details/gtudmplmwb.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.smart0.xyz/Article/details/gtmcvtzvkp.html

Ruby: a.gcd(b)
来源：http://dali.daxiang520.top/Article/details/gtcvoacxvq.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.cashguo.top/Article/details/gtwulsklou.html

[N06] 判断回文字符串
来源：http://dali.pengpengdd.cyou/Article/details/gtxkamzcmy.html

Py:   s == s[::-1]
来源：http://dali.tanke756.top/Article/details/gtvyqozeod.html

PHP:  $s === strrev($s);
来源：http://dali.aizwys.cn/Article/details/gtohwfmfdy.html

JS:   s === [...s].reverse().join("")
来源：http://dali.jyoumei.cn/Article/details/gtyfxsqnom.html

TS:   s === [...s].reverse().join("")
来源：http://dali.dianchejie.cn/Article/details/gtwprffhyb.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.fzhhl.top/Article/details/gtoqyfytus.html

Go:   // 双指针从两端比较
来源：http://dali.dashuyun.cn/Article/details/gtzhaetvza.html

Ruby: s == s.reverse
来源：http://dali.yangfankeji.com/Article/details/gtvtjnvbvq.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.xziqi.cn/Article/details/gtpxpfrzpu.html

[N07] 两数之和（返回下标）
来源：http://dali.jinqigufen.top/Article/details/gtcjtzpoqs.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.xylfe.cn/Article/details/gtstmkumfq.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhixingplan.top/Article/details/gtbavlfoat.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.c1oappe.top/Article/details/gtsziogbzs.html

TS:   // 手写 Map<string, number>
来源：http://dali.fengsongda.top/Article/details/gtjenuovti.html

Java: // 手写 HashMap
来源：http://dali.hammf.cn/Article/details/gtwxisowcm.html

Go:   // 手写 map[int]int
来源：http://dali.hongshengwenyu.top/Article/details/gtdomwxsyg.html

Ruby: // 手写 Hash
来源：http://dali.hnxiangtu.top/Article/details/gtwpkqzjge.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.daxiang520.top/Article/details/gtcbjohudh.html

[N08] 生成全排列
来源：http://dali.meibo888.top/Article/details/gtkqhbugws.html

Py:   itertools.permutations(arr)
来源：http://dali.jlsjyb.cn/Article/details/gtplrvfqqc.html

PHP:  // 手写递归交换
来源：http://dali.yanxiufei.cn/Article/details/gteqeijkxw.html

JS:   // 手写回溯递归
来源：http://dali.aizwys.cn/Article/details/gtfkgdgafa.html

TS:   // 手写回溯递归
来源：http://dali.yj20258888.top/Article/details/gtrcuecqsh.html

Java: // 手写回溯递归
来源：http://dali.guannengcc.top/Article/details/gtpefzfxim.html

Go:   // 手写回溯递归
来源：http://dali.yanxiufei.cn/Article/details/gtwxneuuvx.html

Ruby: arr.permutation.to_a
来源：http://dali.chenlongwang.top/Article/details/gtncutfptj.html

C#:   // 手写回溯递归
来源：http://dali.hysaishi.cn/Article/details/gtdgixwikt.html

[N09] 栈与队列
来源：http://dali.c1oappe.top/Article/details/gtmvgunxel.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.xuetiantiany.cn/Article/details/gtcfefknaf.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.ydzc1.top/Article/details/gtgdwcqjug.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.nanxuanxn.top/Article/details/gtflqfgmmc.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.yvedp.cn/Article/details/gtisxyufhz.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.daxiang520.top/Article/details/gtgihdbxye.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.yonumen.top/Article/details/gtdzzumzcj.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.gotoacloud.top/Article/details/gtgbgljrbx.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.cdnleiting.top/Article/details/gtiyeosnfv.html

[N10] 链表节点定义
来源：http://dali.jinqigfzy.top/Article/details/gtuahsvkuk.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.fzhhl.top/Article/details/gtoojnpbgj.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.wangshuangyany.cn/Article/details/gtiankrsmm.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.fengsongda.top/Article/details/gtinalqbou.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.daria6918.cn/Article/details/gtfeicvxlj.html

Java: class Node { int v; Node next; }
来源：http://dali.yangfankeji.com/Article/details/gtrqfeycfi.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.jinghuilouyu.cn/Article/details/gtdrtdnile.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.yanxiufei.cn/Article/details/gtxogvrpch.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.pengpengdd.cyou/Article/details/gtcrxricns.html

[N11] 二叉树中序遍历
来源：http://dali.daria6918.cn/Article/details/gtdhcdhoft.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.0kj1m.cn/Article/details/gtzfydlcjz.html

PHP:  // 手写递归函数
来源：http://dali.sxryk.cn/Article/details/gttlarkxql.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.aibaodan.cn/Article/details/gtnatwvdwq.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yuxming.cn/Article/details/gtryzzhfhd.html

Java: // 手写递归
来源：http://dali.hysaishi.cn/Article/details/gtdcboekru.html

Go:   // 手写递归
来源：http://dali.ywan-chungtsiang.top/Article/details/gtufqnxspx.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.tianlin.xyz/Article/details/gtfegbxakg.html

C#:   // 手写递归
来源：http://dali.yuxming.cn/Article/details/gtsqyalmob.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoanztmni.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.hfpthk.cn/Article/details/gtyqxvftmy.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.ivvv.top/Article/details/gtepjcibwm.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.smart0.xyz/Article/details/gtclftyslt.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.bjfxy.top/Article/details/gtwauprkrz.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.cdnleiting.top/Article/details/gtyflxtbai.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.9152youxi.cn/Article/details/gttjswxkgg.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.shzxlz.cn/Article/details/gtmrwdbsmr.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.cheryme.top/Article/details/gtdhvrlrnc.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtmpvknlzs.html

O. 并发与异步
来源：http://dali.jqgfzy.top/Article/details/gtgecjcgps.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtvdkrteub.html

[O01] 启动一个线程
来源：http://dali.ybcxt.top/Article/details/gtgxmwhtjm.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.ivvv.top/Article/details/gthudgjnmz.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zycfv.cn/Article/details/gtgtjhbdge.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiyfqxppx.html

TS:   // 同 JS
来源：http://dali.tanke756.top/Article/details/gtcfsjmgxt.html

Java: new Thread(() -> f()).start()
来源：http://dali.jinghuilouyu.cn/Article/details/gtcclqcvin.html

Go:   go f()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjmfojdds.html

Ruby: Thread.new { f }
来源：http://dali.yuanzhike.top/Article/details/gtnhqkpezq.html

C#:   Task.Run(() => F());
来源：http://dali.yanxiufei.cn/Article/details/gtawwzkuln.html

[O02] 使用线程池
来源：http://dali.vqdsnc.cn/Article/details/gtptjlarft.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gtsmtoeecr.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.svipenyu.cn/Article/details/gtkqgxogbz.html

JS:   // worker_threads 线程池
来源：http://dali.ehwqpu.com/Article/details/gtjtxkngyp.html

TS:   // worker_threads 线程池
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqywxqhvs.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.jqgfzy.top/Article/details/gttzjubikm.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.sxryk.cn/Article/details/gtxhbaoksm.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.hnxiangtu.top/Article/details/gtdhhdijos.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.fengsongda.top/Article/details/gtatizexai.html

[O03] 加锁保护共享数据
来源：http://dali.jqgfzy.top/Article/details/gtqyrlkrla.html

Py:   with lock: shared += 1
来源：http://dali.shanyushiyangtech.top/Article/details/gtzzjzqbzf.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhongyouzk.top/Article/details/gtwwxzyyuf.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.hfpthk.cn/Article/details/gtxdudicmq.html

TS:   // 同 JS
来源：http://dali.chenlongwang.top/Article/details/gtmunonzjb.html

Java: synchronized (this) { shared++; }
来源：http://dali.yj202588.top/Article/details/gtwmhsyugz.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.shzxlz.cn/Article/details/gtighuacdk.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.nwbrower.top/Article/details/gtmwsxbntm.html

C#:   lock (gate) { shared++; }
来源：http://dali.hfpthk.cn/Article/details/gttbpdbxqq.html

[O04] 定义异步函数并等待
来源：http://dali.zhengqikj.top/Article/details/gtdmvsbicu.html

Py:   async def f():⏎    await g()
来源：http://dali.pycfn.com/Article/details/gtvhwhmpuc.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.yuxming.cn/Article/details/gtujiwfcze.html

JS:   async function f() { await g(); }
来源：http://dali.feifeiyinyue.top/Article/details/gtthmutqgp.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.jqgfzy.top/Article/details/gtmmckkouf.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.cheryme.top/Article/details/gtruwcqihh.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.shzxlz.cn/Article/details/gthzmpaqiu.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.cucudq.cn/Article/details/gtqvvmowzm.html

C#:   async Task F() { await G(); }
来源：http://dali.bjfxy.top/Article/details/gtqerstguu.html

[O05] 并发执行并等待全部完成
来源：http://dali.vqdsnc.cn/Article/details/gtcmvkbaxi.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhengqikj.top/Article/details/gtcanrixyq.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.cashguo.top/Article/details/gtreoljxnb.html

JS:   await Promise.all(tasks)
来源：http://dali.xuetiantiany.cn/Article/details/gtvikqvzgm.html

TS:   await Promise.all(tasks)
来源：http://dali.shzxlz.cn/Article/details/gtuawhiisv.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.chenzaomai.com/Article/details/gtqwwicrms.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhiwuduotai.top/Article/details/gtquruxexw.html

Ruby: threads.map(&:join)
来源：http://dali.snrcjt.cn/Article/details/gtlfcvqutl.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.wangdashe.top/Article/details/gtttnwevum.html

[O06] 使用进程池
来源：http://dali.gaohongyu789.top/Article/details/gtgxmvbfbn.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.jqgufenzy.top/Article/details/gtenkogrgc.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.yueranfly.top/Article/details/gthivshhfr.html

JS:   // child_process / cluster 模块
来源：http://dali.cashguo.top/Article/details/gtqfpgeyzv.html

TS:   // child_process / cluster 模块
来源：http://dali.xylfe.cn/Article/details/gtwfozymmi.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.xziqi.cn/Article/details/gtagwmvquu.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.dashuyun.cn/Article/details/gtaqfdygcj.html

Ruby: // fork 块
来源：http://dali.gaohongyu789.top/Article/details/gttasluang.html

C#:   Parallel.For
来源：http://dali.meibo888.top/Article/details/gtilwlduih.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtipsmcdww.html

P. 常用工具函数
来源：http://dali.zhongyouzk.top/Article/details/gtdzmdywnf.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtlwanbnxq.html

[P01] 生成 UUID
来源：http://dali.jinqigufen.top/Article/details/gtriipxcnp.html

Py:   str(uuid.uuid4())
来源：http://dali.jlsjyb.cn/Article/details/gtwvejhbob.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.hongshengwenyu.top/Article/details/gtuuxhzoye.html

JS:   crypto.randomUUID()
来源：http://dali.svipenyu.cn/Article/details/gtblogxtev.html

TS:   crypto.randomUUID()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvssnvcuv.html

Java: UUID.randomUUID().toString()
来源：http://dali.ivvv.top/Article/details/gtbwxvitdr.html

Go:   // 用 github.com/google/uuid
来源：http://dali.xinyue.icu/Article/details/gtlsbdsbuk.html

Ruby: SecureRandom.uuid
来源：http://dali.tanke756.top/Article/details/gtbugochpg.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.jyoumei.cn/Article/details/gtvormvovg.html

[P02] MD5 / SHA256 摘要
来源：http://dali.ehwqpu.com/Article/details/gthlfbboqv.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.cqqwz.cn/Article/details/gtuqbshqiz.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.sufxvd.cn/Article/details/gtgbplmtne.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.dashuyun.cn/Article/details/gthkpqesep.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.jyoumei.cn/Article/details/gtktdczlkk.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.sufxvd.cn/Article/details/gttsbebkba.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.guannengcc.top/Article/details/gtthlpcfrx.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.dianchejie.cn/Article/details/gtkybcjdvj.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.fzhhl.top/Article/details/gtmcchetmu.html

[P03] 生成短随机字符串
来源：http://dali.daria6918.cn/Article/details/gtijjnziab.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.haohaochexian.top/Article/details/gtoukdayku.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.dianchejie.cn/Article/details/gtjxhbahne.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.haohaochexian.top/Article/details/gtazdtnvlg.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.shuidangran.top/Article/details/gttxfgnkov.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.andypj.xyz/Article/details/gthnylomzx.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.cdnleiting.top/Article/details/gtsbfnyrjt.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.redwolf501.top/Article/details/gtglgvuqak.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.jinqigufen.top/Article/details/gtolshhatk.html

[P04] 求长度
来源：http://dali.gotoacloud.top/Article/details/gtqrgjrlut.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.pycfn.com/Article/details/gtbjsftpgo.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.haohaochexian.top/Article/details/gthujtifde.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jqgufenzy.top/Article/details/gttugznbsw.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.gaohongyu789.top/Article/details/gttvdksktb.html

Java: list.size();  map.size();  s.length()
来源：http://dali.fengsongda.top/Article/details/gtethszvrv.html

Go:   len(arr);  len(m)
来源：http://dali.xuanzx.com/Article/details/gtakwkfwhf.html

Ruby: x.length;  x.size
来源：http://dali.hnxiangtu.top/Article/details/gtajvtcrli.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.pycfn.com/Article/details/gtwcuvubsl.html

[P05] 判断两个对象内容是否相等
来源：http://dali.316326.xyz/Article/details/gtendgmfpf.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.aibaodan.cn/Article/details/gtnsfbwlwg.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.tian-w.cn/Article/details/gtvhdubyhf.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.jianghu66.top/Article/details/gtephiesjz.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.hywenlv.cn/Article/details/gtqvrnethc.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.xuetiantiany.cn/Article/details/gtdqagtbrm.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.cucudq.cn/Article/details/gtduenujpk.html

Ruby: a == b
来源：http://dali.fengsongda.top/Article/details/gtinzmclwb.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.mhx1999.top/Article/details/gtadstwdru.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.jyoumei.cn/Article/details/gtffpufbwb.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.chenlongwang.top/Article/details/gtssmvwgzp.html

PHP:  if (empty($x)) {}
来源：http://dali.jinqigfzy.top/Article/details/gtmbstrjio.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhongyouzk.top/Article/details/gtnjiuazto.html

TS:   if (x == null) {}
来源：http://dali.yongpay.top/Article/details/gtuotffnsx.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.gogol.net.cn/Article/details/gtdcovmyov.html

Go:   if x == nil {}
来源：http://dali.jinqigfzy.top/Article/details/gtybawfznr.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.jinqigfzy.top/Article/details/gtorvcjnzj.html

C#:   if (x is null) {}
来源：http://dali.xuetiantiany.cn/Article/details/gtvxzgeuep.html

[P07] 防抖与节流
来源：http://dali.316326.xyz/Article/details/gtmksphrcn.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.yonumen.top/Article/details/gtzewmzdgz.html

PHP:  // 手写时间戳比较
来源：http://dali.iojbl.cn/Article/details/gtznhrpjfx.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.cqqwz.cn/Article/details/gtjjtiofkf.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjiseocqk.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.shanyushiyangtech.top/Article/details/gttnskgvdr.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhijiandao.cn/Article/details/gtaoizxmlj.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.sxryk.cn/Article/details/gtvwbewmmw.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.yvedp.cn/Article/details/gtdnhyiujo.html

[P08] 处理浮点精度问题
来源：http://dali.hfpthk.cn/Article/details/gtanltjdqr.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.kuanghao11.cn/Article/details/gtacmhgghs.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtydlgdbeb.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.pengpengdd.cyou/Article/details/gtxkgtukna.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.gzhubu.top/Article/details/gtxztehayg.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.cucudq.cn/Article/details/gtkpcpypvn.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.hongshengwenyu.top/Article/details/gtmkpcfrnl.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.aibaodan.cn/Article/details/gtpzrbegmi.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.redwolf501.top/Article/details/gtqoaytqxd.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtirqvxbwj.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.gzhubu.top/Article/details/gtwstghuyg.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtbafefmhj.html

[Q01] 创建表
来源：http://dali.xziqi.cn/Article/details/gtkmzoogvt.html

CREATE TABLE users (
来源：http://dali.jyoumei.cn/Article/details/gtexkyoqcc.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.ivvv.top/Article/details/gtetantdij.html

name VARCHAR(50) NOT NULL,
来源：http://dali.tianlin.xyz/Article/details/gtvtxrqsqj.html

email VARCHAR(100) UNIQUE,
来源：http://dali.gaohongyu789.top/Article/details/gtuzfpnrhg.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.gaohongyu789.top/Article/details/gtefgdbwng.html

);
来源：http://dali.snrcjt.cn/Article/details/gthhbtwfnr.html

[Q02] 创建带外键的表
来源：http://dali.gotoacloud.top/Article/details/gtizggysuj.html

CREATE TABLE orders (
来源：http://dali.yanxiufei.cn/Article/details/gtdkmmulwk.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.haohaochexian.top/Article/details/gtzfxiptii.html

user_id INT NOT NULL,
来源：http://dali.xziqi.cn/Article/details/gtvtfqbixq.html

amount DECIMAL(10, 2),
来源：http://dali.sweek.top/Article/details/gtfnfppovg.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.yongpay.top/Article/details/gtdqgvagol.html

);
来源：http://dali.sweek.top/Article/details/gtjopymdno.html

[Q03] 增加列
来源：http://dali.c1oappe.top/Article/details/gttpoxcmlj.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.cheryme.top/Article/details/gtqlqxcfod.html

[Q04] 修改列类型
来源：http://dali.0kj1m.cn/Article/details/gtlsslikvk.html


<!-- 参考信息 -->