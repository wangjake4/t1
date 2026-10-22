代发 wailian999

Ruby: exit 1
来源：http://dali.havefunace.top/Article/details/gtlogrbmln.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.haohaochexian.top/Article/details/gtsdrdjfjf.html

[M06] 向标准错误输出
来源：http://dali.shanyushiyangkeji.top/Article/details/gtplupioau.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhengqikj.top/Article/details/gtvznkvtwp.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.meibo888.top/Article/details/gtvtfvubwv.html

JS:   console.error("err")
来源：http://dali.chenzaomai.com/Article/details/gtgnxfxqay.html

TS:   console.error("err")
来源：http://dali.zycfv.cn/Article/details/gtyrzylapc.html

Java: System.err.println("err")
来源：http://dali.cdnleiting.top/Article/details/gtlxphkxdg.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.kuanghao11.cn/Article/details/gtxzzcivab.html

Ruby: warn "err"
来源：http://dali.yongpay.top/Article/details/gtotwjtmkw.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.yj202588.top/Article/details/gtmmroyael.html

[M07] 判断是否为主入口
来源：http://dali.gogol.net.cn/Article/details/gtpqgxmndo.html

Py:   if __name__ == "__main__":
来源：http://dali.yj202588.top/Article/details/gtjirfybox.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.hnxiangtu.top/Article/details/gtvcprzanb.html

JS:   require.main === module
来源：http://dali.gzhubu.top/Article/details/gtokepumme.html

TS:   require.main === module
来源：http://dali.ivvv.top/Article/details/gtxfdqnrie.html

Java: public static void main(String[] args)
来源：http://dali.yuxming.cn/Article/details/gtzwanuwre.html

Go:   func main()
来源：http://dali.cheryme.top/Article/details/gtkjuruekv.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.gotoacloud.top/Article/details/gtruphtavv.html

C#:   static void Main(string[] args)
来源：http://dali.xuanzx.com/Article/details/gtntiybxbw.html

[M08] 获取系统与运行时信息
来源：http://dali.snrcjt.cn/Article/details/gtkqaehlhp.html

Py:   platform.system();  platform.python_version()
来源：http://dali.yongpay.top/Article/details/gtoymniilk.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.jiagoushi.top/Article/details/gtlubqevsz.html

JS:   process.platform;  process.version
来源：http://dali.jyoumei.cn/Article/details/gtzgzpmidq.html

TS:   process.platform;  process.version
来源：http://dali.shzxlz.cn/Article/details/gtinzenicu.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.bjfxy.top/Article/details/gtdrtjaemn.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.tian-w.cn/Article/details/gtllfwtxto.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.xuanzx.com/Article/details/gtptelbhmy.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.quarkkingdee.top/Article/details/gtqdmgfiwp.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtsmcyiqlb.html

N. 数据结构与算法
来源：http://dali.c1oappe.top/Article/details/gtdcqqcosg.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtdxbeaklv.html

[N01] 二分查找（有序数组）
来源：http://dali.jinqigufen.top/Article/details/gtmfflnlnm.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.feifeiyinyue.top/Article/details/gtbwapwpkj.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.hywenlv.cn/Article/details/gtzfmspqba.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yj202588.top/Article/details/gtqvbhmlpu.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jianghu66.top/Article/details/gtmpmbiwyo.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.gogol.net.cn/Article/details/gtkdmuzacg.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.chenlongwang.top/Article/details/gtyfuyiaoy.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.pengpengdd.cyou/Article/details/gtrygjdaqb.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.pycfn.com/Article/details/gtblskbkaz.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.nanxinkj.top/Article/details/gtrnpvbwis.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yj20258888.top/Article/details/gtmuxmtgpl.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhixingplan.top/Article/details/gtuyrwlxcf.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yj20258.top/Article/details/gtyhfvrjsl.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.kuanghao11.cn/Article/details/gtbmkzrrdm.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.cdnleiting.top/Article/details/gtqwtvnclm.html

Go:   slices.Sort(arr)
来源：http://dali.shzxlz.cn/Article/details/gtixqtrbqh.html

Ruby: arr.sort
来源：http://dali.fengsongda.top/Article/details/gtbybcmpxk.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.dianchejie.cn/Article/details/gtuwnxdoir.html

[N03] 快速排序（分治示例）
来源：http://dali.xinyue.icu/Article/details/gtfwkeyxcl.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.meibo888.top/Article/details/gtqkfxobmo.html

PHP:  // 递归实现，或用 usort
来源：http://dali.hnqzz.top/Article/details/gtvvdkrjwu.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.xuanzx.com/Article/details/gthgigvrrx.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.ivvv.top/Article/details/gtppuhjjrz.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.9152youxi.cn/Article/details/gtynseqrsd.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.aibaodan.cn/Article/details/gtjlrzpmoz.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.sufxvd.cn/Article/details/gtwpqoqztq.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.shuidangran.top/Article/details/gtdyvmlvsv.html

[N04] 斐波那契数列
来源：http://dali.wangdashe.top/Article/details/gtvhfcsfqv.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.yvedp.cn/Article/details/gtpymvuwdg.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.316326.xyz/Article/details/gtfhcblzht.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.mhx1999.top/Article/details/gtvcntjmld.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.birdmap.top/Article/details/gthkcsiriv.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.chenlongwang.top/Article/details/gtaruryjvn.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.fzhhl.top/Article/details/gtwrgledpa.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.chenlongwang.top/Article/details/gtuuzxymri.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.hnqzz.top/Article/details/gtwsdlximr.html

[N05] 最大公约数
来源：http://dali.pengpengdd.cyou/Article/details/gthxmanzfj.html

Py:   math.gcd(a, b)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdojkreoe.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.sxryk.cn/Article/details/gtwmryjzgt.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.ppjwa.cn/Article/details/gtzkobregj.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.shzxlz.cn/Article/details/gtvttduzya.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.xuanzx.com/Article/details/gttzrewxpg.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.ybcxt.top/Article/details/gttfkgimpg.html

Ruby: a.gcd(b)
来源：http://dali.tian-w.cn/Article/details/gtonigiysv.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.smart0.xyz/Article/details/gtrmbnhafu.html

[N06] 判断回文字符串
来源：http://dali.yuanzhike.top/Article/details/gtwryokipx.html

Py:   s == s[::-1]
来源：http://dali.zhongyouzk.top/Article/details/gtvufrzegr.html

PHP:  $s === strrev($s);
来源：http://dali.zhixingplan.top/Article/details/gthqbivute.html

JS:   s === [...s].reverse().join("")
来源：http://dali.0kj1m.cn/Article/details/gtqzofscfx.html

TS:   s === [...s].reverse().join("")
来源：http://dali.c1oappe.top/Article/details/gtykptizqg.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.sweek.top/Article/details/gtergewmhz.html

Go:   // 双指针从两端比较
来源：http://dali.yangfankeji.com/Article/details/gtiqklvndo.html

Ruby: s == s.reverse
来源：http://dali.svipenyu.cn/Article/details/gtsdyhxtcd.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.shangyingyoupin.top/Article/details/gtfjnomapy.html

[N07] 两数之和（返回下标）
来源：http://dali.xinyue.icu/Article/details/gtuaykpwpv.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.dashuyun.cn/Article/details/gtzktaxhzm.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.tianlin.xyz/Article/details/gtzpllekrw.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.c1oappe.top/Article/details/gtoleaomcc.html

TS:   // 手写 Map<string, number>
来源：http://dali.chenjidiqi.icu/Article/details/gtpmlddjrz.html

Java: // 手写 HashMap
来源：http://dali.snrcjt.cn/Article/details/gtgmtmueiw.html

Go:   // 手写 map[int]int
来源：http://dali.yvedp.cn/Article/details/gttbnabbjs.html

Ruby: // 手写 Hash
来源：http://dali.hammf.cn/Article/details/gtbwymzphy.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.yj20258.top/Article/details/gtmdpawldh.html

[N08] 生成全排列
来源：http://dali.cqqwz.cn/Article/details/gtutemfgbo.html

Py:   itertools.permutations(arr)
来源：http://dali.0kj1m.cn/Article/details/gtqjxyfkdq.html

PHP:  // 手写递归交换
来源：http://dali.zhoulong.xyz/Article/details/gtrfikklfc.html

JS:   // 手写回溯递归
来源：http://dali.cucudq.cn/Article/details/gtrefguovv.html

TS:   // 手写回溯递归
来源：http://dali.quarkkingdee.top/Article/details/gttiaonecf.html

Java: // 手写回溯递归
来源：http://dali.andypj.xyz/Article/details/gtuxpetotv.html

Go:   // 手写回溯递归
来源：http://dali.tian-w.cn/Article/details/gtisgxyaey.html

Ruby: arr.permutation.to_a
来源：http://dali.shanyushiyangtech.top/Article/details/gtafbotiiz.html

C#:   // 手写回溯递归
来源：http://dali.guowangkeji.top/Article/details/gtrfzbtvwi.html

[N09] 栈与队列
来源：http://dali.jinqigufen.top/Article/details/gtrnzistgk.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.sufxvd.cn/Article/details/gthdcelfds.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.daria6918.cn/Article/details/gtualfaycm.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.vqdsnc.cn/Article/details/gtjyixcygm.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlahvutyy.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.yj20258888.top/Article/details/gtdetpsnvz.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhoulong.xyz/Article/details/gtcsfbcoqw.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.daria6918.cn/Article/details/gtjbimywcp.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.nanxuanxn.top/Article/details/gtcvajzvvm.html

[N10] 链表节点定义
来源：http://dali.feifeiyinyue.top/Article/details/gtymreptbv.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.gaohongyu789.top/Article/details/gtodbonhhv.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqnzjzszb.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.ehwqpu.com/Article/details/gtwekthnyx.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.jinqigufen.top/Article/details/gtlkiyjtif.html

Java: class Node { int v; Node next; }
来源：http://dali.chenzaomai.com/Article/details/gtmllajach.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.cqqwz.cn/Article/details/gtlflqqggs.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.xinyue.icu/Article/details/gtezexpqwp.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.svipenyu.cn/Article/details/gtzijytpvc.html

[N11] 二叉树中序遍历
来源：http://dali.hnqzz.top/Article/details/gtocxatyii.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zycfv.cn/Article/details/gtwiphmgty.html

PHP:  // 手写递归函数
来源：http://dali.ivvv.top/Article/details/gtseuyrahj.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.hongshengwenyu.top/Article/details/gtojxlsgvi.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.aibaodan.cn/Article/details/gtrnpfxcpi.html

Java: // 手写递归
来源：http://dali.quarkkingdee.top/Article/details/gtyktgcvbz.html

Go:   // 手写递归
来源：http://dali.shangyingyoupin.top/Article/details/gtphunatad.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.smart0.xyz/Article/details/gtodtebzev.html

C#:   // 手写递归
来源：http://dali.c1oappe.top/Article/details/gtfaxqmguz.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.yj20258888.top/Article/details/gtjzbrjiui.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.sysykeji.top/Article/details/gtkyhrrlel.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.havefunace.top/Article/details/gtgixqhpxv.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yj202588.top/Article/details/gtmqvuekdh.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yj20258888.top/Article/details/gtnhitjwze.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlsdbcoyi.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.gogol.net.cn/Article/details/gtbbxdoylq.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.0kj1m.cn/Article/details/gtpdnlagss.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.shanyushiyangtech.top/Article/details/gtvcvcveeg.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtreqnyybb.html

O. 并发与异步
来源：http://dali.cheryme.top/Article/details/gtgdbuzrwl.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtuwucyakn.html

[O01] 启动一个线程
来源：http://dali.sysykeji.top/Article/details/gtfyryhenm.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.havefunace.top/Article/details/gtbowoajwx.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.jinqigfzy.top/Article/details/gtvdzifzzt.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.hysaishi.cn/Article/details/gteompbfav.html

TS:   // 同 JS
来源：http://dali.cucudq.cn/Article/details/gtqugvcagz.html

Java: new Thread(() -> f()).start()
来源：http://dali.yj202588.top/Article/details/gtswnnysrj.html

Go:   go f()
来源：http://dali.tian-w.cn/Article/details/gtfybjdviy.html

Ruby: Thread.new { f }
来源：http://dali.xylfe.cn/Article/details/gtvotsbihh.html

C#:   Task.Run(() => F());
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpciedlpu.html

[O02] 使用线程池
来源：http://dali.nanxuanxn.top/Article/details/gtzltbbdqk.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.fengsongda.top/Article/details/gtpuprtzvt.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.vqdsnc.cn/Article/details/gtfbpwamgw.html

JS:   // worker_threads 线程池
来源：http://dali.zhongyouzk.top/Article/details/gtsbonqswj.html

TS:   // worker_threads 线程池
来源：http://dali.yvedp.cn/Article/details/gtltrgbztn.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.kuanghao11.cn/Article/details/gtfltnfdvo.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.9152youxi.cn/Article/details/gtjeskhprg.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.shangyingyoupin.top/Article/details/gtcsexxdzk.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.andypj.xyz/Article/details/gtykdcxqop.html

[O03] 加锁保护共享数据
来源：http://dali.meibo888.top/Article/details/gtpklfisvp.html

Py:   with lock: shared += 1
来源：http://dali.ivvv.top/Article/details/gttvjukgek.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.ybcxt.top/Article/details/gtamxfgjgl.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhongyouzk.top/Article/details/gtveufoyft.html

TS:   // 同 JS
来源：http://dali.guowangkeji.top/Article/details/gtrczhejhn.html

Java: synchronized (this) { shared++; }
来源：http://dali.cdnleiting.top/Article/details/gtnknqcivf.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.tanke756.top/Article/details/gttnscxahy.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.ehwqpu.com/Article/details/gtxptsaoar.html

C#:   lock (gate) { shared++; }
来源：http://dali.nanxinkj.top/Article/details/gtfrlawfxo.html

[O04] 定义异步函数并等待
来源：http://dali.yuanzhike.top/Article/details/gtjrezkaxy.html

Py:   async def f():⏎    await g()
来源：http://dali.kuanghao11.cn/Article/details/gtzspotnrm.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.hfpthk.cn/Article/details/gtjhztktlw.html

JS:   async function f() { await g(); }
来源：http://dali.chenzaomai.com/Article/details/gtlsbwhjsc.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.xuanzx.com/Article/details/gtthxpcqrd.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.shzxlz.cn/Article/details/gtanaguboh.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.jiagoushi.top/Article/details/gtknxwwrve.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.andypj.xyz/Article/details/gtospgujiz.html

C#:   async Task F() { await G(); }
来源：http://dali.jinqigfzy.top/Article/details/gtmtgjbgxp.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhoulong.xyz/Article/details/gtqkdyupla.html

Py:   asyncio.gather(*tasks)
来源：http://dali.yj20258.top/Article/details/gtqwnjfwzk.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.sufxvd.cn/Article/details/gtilbeiuco.html

JS:   await Promise.all(tasks)
来源：http://dali.yuanzhike.top/Article/details/gtgcytgomy.html

TS:   await Promise.all(tasks)
来源：http://dali.dashuyun.cn/Article/details/gtyxbuimgm.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.hongshengwenyu.top/Article/details/gtfaitffly.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.pycfn.com/Article/details/gtyynzlutg.html

Ruby: threads.map(&:join)
来源：http://dali.xylfe.cn/Article/details/gtkoehstbi.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zycfv.cn/Article/details/gtzqynqtfw.html

[O06] 使用进程池
来源：http://dali.andypj.xyz/Article/details/gtxktzwbmv.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhiwuduotai.top/Article/details/gtmezhffgt.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.hnqzz.top/Article/details/gtrqjvfjlh.html

JS:   // child_process / cluster 模块
来源：http://dali.snrcjt.cn/Article/details/gtcylywxzj.html

TS:   // child_process / cluster 模块
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjixovgmj.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.guannengcc.top/Article/details/gtcngfacws.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.quarkkingdee.top/Article/details/gtmbcbenkp.html

Ruby: // fork 块
来源：http://dali.vqdsnc.cn/Article/details/gtqhdnfplf.html

C#:   Parallel.For
来源：http://dali.hongshengwenyu.top/Article/details/gtzaabqavk.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtoclszcgg.html

P. 常用工具函数
来源：http://dali.nwbrower.top/Article/details/gtpedoxczo.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtumgcfyym.html

[P01] 生成 UUID
来源：http://dali.yj20258888.top/Article/details/gtggvmswxx.html

Py:   str(uuid.uuid4())
来源：http://dali.xuanzx.com/Article/details/gtvqlkwiua.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.sysykeji.top/Article/details/gtqfdmbrll.html

JS:   crypto.randomUUID()
来源：http://dali.cheryme.top/Article/details/gtyrcuvkwl.html

TS:   crypto.randomUUID()
来源：http://dali.redwolf501.top/Article/details/gtmifpkjkm.html

Java: UUID.randomUUID().toString()
来源：http://dali.cashguo.top/Article/details/gtzuyclzbx.html

Go:   // 用 github.com/google/uuid
来源：http://dali.dashuyun.cn/Article/details/gtzdxounbq.html

Ruby: SecureRandom.uuid
来源：http://dali.jinyuanbaomall.cn/Article/details/gtycrqilvh.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.meibo888.top/Article/details/gtlnsxunkb.html

[P02] MD5 / SHA256 摘要
来源：http://dali.sysykeji.top/Article/details/gtyedlsbhy.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.yanxiufei.cn/Article/details/gtzdroxosc.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.sufxvd.cn/Article/details/gtzgswgwzv.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.tianlin.xyz/Article/details/gtrzxospvl.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.jiagoushi.top/Article/details/gtslebkbhq.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.yuxming.cn/Article/details/gtxyamytia.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.hnqzz.top/Article/details/gtdjvjgiiu.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.cheryme.top/Article/details/gtwscwrzja.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.shangyingyoupin.top/Article/details/gtizbskysr.html

[P03] 生成短随机字符串
来源：http://dali.sysykeji.top/Article/details/gtmlbigujd.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.bjfxy.top/Article/details/gttgbhpwcs.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.shanyushiyangkeji.top/Article/details/gthmmsqonu.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.ydzc1.top/Article/details/gtnvtwetni.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.wangshuangyany.cn/Article/details/gttgoyecam.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.snrcjt.cn/Article/details/gthprijzol.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.hywenlv.cn/Article/details/gtzyrkxdqz.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.xinyue.icu/Article/details/gtdvbhlkmf.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.jqgufenzy.top/Article/details/gtgbpoiwai.html

[P04] 求长度
来源：http://dali.nanxuanxn.top/Article/details/gtylgyynat.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhengqikj.top/Article/details/gtjrllulvv.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhengqikj.top/Article/details/gtzstxpsdf.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.iojbl.cn/Article/details/gtfwmwwqfc.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.snrcjt.cn/Article/details/gtjcqnwvmk.html

Java: list.size();  map.size();  s.length()
来源：http://dali.snrcjt.cn/Article/details/gteyspjgxr.html

Go:   len(arr);  len(m)
来源：http://dali.svipenyu.cn/Article/details/gtdksxdxhn.html

Ruby: x.length;  x.size
来源：http://dali.zhoulong.xyz/Article/details/gtthvxyilg.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.daxiang520.top/Article/details/gtbrtcyxuu.html

[P05] 判断两个对象内容是否相等
来源：http://dali.yvedp.cn/Article/details/gtsgxdbjxk.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhengqikj.top/Article/details/gtbcfjowpn.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.yangfankeji.com/Article/details/gtzrfpbifm.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.jianghu66.top/Article/details/gtuxncvuos.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.vqdsnc.cn/Article/details/gtzvetrdoc.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.gotoacloud.top/Article/details/gtehaprayh.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.birdmap.top/Article/details/gtpexbgekx.html

Ruby: a == b
来源：http://dali.yj20258.top/Article/details/gtiorvuryr.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhoulong.xyz/Article/details/gtekiijjak.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.yongpay.top/Article/details/gtmutsugja.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.xuanzx.com/Article/details/gtymwtejid.html

PHP:  if (empty($x)) {}
来源：http://dali.iojbl.cn/Article/details/gtejelgoij.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmovfsdyq.html

TS:   if (x == null) {}
来源：http://dali.yonumen.top/Article/details/gtrofzacrn.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.hammf.cn/Article/details/gtltxdhzyy.html

Go:   if x == nil {}
来源：http://dali.andypj.xyz/Article/details/gtpkxnanpt.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.jinghuilouyu.cn/Article/details/gtytqweuct.html

C#:   if (x is null) {}
来源：http://dali.kuanghao11.cn/Article/details/gtchzigucl.html

[P07] 防抖与节流
来源：http://dali.wangshuangyany.cn/Article/details/gtwuzuyoop.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.shuidangran.top/Article/details/gtecybllqk.html

PHP:  // 手写时间戳比较
来源：http://dali.hysaishi.cn/Article/details/gtakynihan.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.kuanghao11.cn/Article/details/gtmwxdvrpv.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yonumen.top/Article/details/gtdngvfpvr.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.xuetiantiany.cn/Article/details/gtsdjgcpov.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.yuanzhike.top/Article/details/gtyvhipojg.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.yj20258888.top/Article/details/gtjtfwifwt.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.yuanzhike.top/Article/details/gtadbuytay.html

[P08] 处理浮点精度问题
来源：http://dali.gzhubu.top/Article/details/gteympmlpe.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.ywan-chungtsiang.top/Article/details/gthkfcayjy.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.iojbl.cn/Article/details/gtvkhqlsiq.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.fzhhl.top/Article/details/gtvnverkit.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsacdjgws.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.ehwqpu.com/Article/details/gtkyvxxcio.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.jlsjyb.cn/Article/details/gtjdkmcdjh.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.sufxvd.cn/Article/details/gtgoyjadrh.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.shuidangran.top/Article/details/gtcxqlqryy.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtqvrgblxo.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.bjfxy.top/Article/details/gtvsewlibf.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtbwpzocxw.html

[Q01] 创建表
来源：http://dali.quarkkingdee.top/Article/details/gtmdkgxgum.html

CREATE TABLE users (
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqsrdxuhk.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jqgfzy.top/Article/details/gtcniazhlc.html

name VARCHAR(50) NOT NULL,
来源：http://dali.yvedp.cn/Article/details/gtvbladzug.html

email VARCHAR(100) UNIQUE,
来源：http://dali.andypj.xyz/Article/details/gthfmaqxzo.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.sxryk.cn/Article/details/gtdyaajuxy.html

);
来源：http://dali.ppjwa.cn/Article/details/gttgybtito.html

[Q02] 创建带外键的表
来源：http://dali.cashguo.top/Article/details/gtcusszfmc.html

CREATE TABLE orders (
来源：http://dali.jyoumei.cn/Article/details/gtusoiuwqh.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yongpay.top/Article/details/gtvhlcicgj.html

user_id INT NOT NULL,
来源：http://dali.zhoulong.xyz/Article/details/gtcpqrvsmo.html

amount DECIMAL(10, 2),
来源：http://dali.ppjwa.cn/Article/details/gthofmhwoj.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.smart0.xyz/Article/details/gtkmcorcci.html

);
来源：http://dali.zhengqikj.top/Article/details/gtkgxtxwss.html

[Q03] 增加列
来源：http://dali.yangfankeji.com/Article/details/gtocbmbmpk.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.jyoumei.cn/Article/details/gtcdachxqb.html

[Q04] 修改列类型
来源：http://dali.guowangkeji.top/Article/details/gtaqlmlnsl.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.sysykeji.top/Article/details/gtlemxacmb.html

[Q05] 重命名列
来源：http://dali.pycfn.com/Article/details/gtvdwqxzzl.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.hnxiangtu.top/Article/details/gtqnzutxql.html

[Q06] 删除列
来源：http://dali.sufxvd.cn/Article/details/gtnwmbskbe.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.yangfankeji.com/Article/details/gtiwqwpjym.html

[Q07] 删除表
来源：http://dali.smart0.xyz/Article/details/gtcgklbbiq.html

DROP TABLE IF EXISTS orders;
来源：http://dali.bjfxy.top/Article/details/gtsicfrpsi.html

[Q08] 创建普通索引
来源：http://dali.nwbrower.top/Article/details/gtxknchaex.html


<!-- 参考信息 -->