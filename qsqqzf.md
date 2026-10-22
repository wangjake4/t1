代发 wailian999

JS:   process.exit(1)
来源：http://dali.jianghu66.top/Article/details/gt2kvlsvncn.html

TS:   process.exit(1)
来源：http://dali.tian-w.cn/Article/details/gt2yncjxsee.html

Java: System.exit(1)
来源：http://dali.xziqi.cn/Article/details/gt2gldpdtao.html

Go:   os.Exit(1)
来源：http://dali.daria6918.cn/Article/details/gt2piwehkeg.html

Ruby: exit 1
来源：http://dali.feifeiyinyue.top/Article/details/gt2hwadspch.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.cheryme.top/Article/details/gt2gmwjqonu.html

[M06] 向标准错误输出
来源：http://dali.cqqwz.cn/Article/details/gt2yaybvesl.html

Py:   print("err", file=sys.stderr)
来源：http://dali.sysykeji.top/Article/details/gt2lmbuycqc.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.snrcjt.cn/Article/details/gt2gnkvktzy.html

JS:   console.error("err")
来源：http://dali.zhiwuduotai.top/Article/details/gt2mclndrtq.html

TS:   console.error("err")
来源：http://dali.fzhhl.top/Article/details/gt2jtktcabe.html

Java: System.err.println("err")
来源：http://dali.xuetiantiany.cn/Article/details/gt2peccrdjz.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.smart0.xyz/Article/details/gt2tzrlvvlu.html

Ruby: warn "err"
来源：http://dali.hammf.cn/Article/details/gt2wygkonxb.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.tianlin.xyz/Article/details/gt2vffhxpqe.html

[M07] 判断是否为主入口
来源：http://dali.kuanghao11.cn/Article/details/gt2fbszkoac.html

Py:   if __name__ == "__main__":
来源：http://dali.xuetiantiany.cn/Article/details/gt2zxdlubbn.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.hysaishi.cn/Article/details/gt2vyagadcq.html

JS:   require.main === module
来源：http://dali.xinyue.icu/Article/details/gt2xfqpisnf.html

TS:   require.main === module
来源：http://dali.cucudq.cn/Article/details/gt2nattxwck.html

Java: public static void main(String[] args)
来源：http://dali.yanxiufei.cn/Article/details/gt2tmxcedyq.html

Go:   func main()
来源：http://dali.snrcjt.cn/Article/details/gt2zwkedssq.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.haohaochexian.top/Article/details/gt2smaoqpyx.html

C#:   static void Main(string[] args)
来源：http://dali.zdqjudy.top/Article/details/gt2ctcrjyxb.html

[M08] 获取系统与运行时信息
来源：http://dali.fzhhl.top/Article/details/gt2ykoyoxwo.html

Py:   platform.system();  platform.python_version()
来源：http://dali.shzxlz.cn/Article/details/gt2mvpbvqsn.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.aibaodan.cn/Article/details/gt2jqgnutyq.html

JS:   process.platform;  process.version
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qkxncbcp.html

TS:   process.platform;  process.version
来源：http://dali.mhx1999.top/Article/details/gt2ximsqrnu.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.yj20258.top/Article/details/gt2ykfxlxqn.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.hysaishi.cn/Article/details/gt2zojhqeyo.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.ydzc1.top/Article/details/gt2bdtoekbu.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.ivvv.top/Article/details/gt2hksiwnsd.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2kvspegzo.html

N. 数据结构与算法
来源：http://dali.316326.xyz/Article/details/gt2pzntkoyz.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zzfjqedq.html

[N01] 二分查找（有序数组）
来源：http://dali.shzxlz.cn/Article/details/gt2dvcajtbz.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.jinqigfzy.top/Article/details/gt2qqnleihi.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.jianghu66.top/Article/details/gt2mblxncgx.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jqgufenzy.top/Article/details/gt2wgekkykq.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.gzhubu.top/Article/details/gt2nesclyqt.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.yj20258888.top/Article/details/gt2asiwhoep.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.tian-w.cn/Article/details/gt2oejlbgue.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.xuetiantiany.cn/Article/details/gt2nzvbzcea.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xezhvxxo.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.gzhubu.top/Article/details/gt2sihlfkjy.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.pengpengdd.cyou/Article/details/gt2mhrovygl.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.bjfxy.top/Article/details/gt2ifwopimi.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.wangshuangyany.cn/Article/details/gt2ajflwplr.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhongyouzk.top/Article/details/gt2geztttyv.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.sufxvd.cn/Article/details/gt2wyxyzmbb.html

Go:   slices.Sort(arr)
来源：http://dali.cdnleiting.top/Article/details/gt2qhcxmjws.html

Ruby: arr.sort
来源：http://dali.zhengqikj.top/Article/details/gt2amqzlwwi.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.jiagoushi.top/Article/details/gt2ubgqentj.html

[N03] 快速排序（分治示例）
来源：http://dali.zhiwuduotai.top/Article/details/gt2uwvtunoh.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.daxiang520.top/Article/details/gt2eviqajxt.html

PHP:  // 递归实现，或用 usort
来源：http://dali.daxiang520.top/Article/details/gt2kbkfncog.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhongyouzk.top/Article/details/gt2dvyddvsu.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.nanxuanxn.top/Article/details/gt2tvqnndyo.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2teliguhl.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.shzxlz.cn/Article/details/gt2wjdndhex.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.dashuyun.cn/Article/details/gt2ghawhjtx.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.mhx1999.top/Article/details/gt2hxxftpxf.html

[N04] 斐波那契数列
来源：http://dali.snrcjt.cn/Article/details/gt2gzinqfko.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.jqgufenzy.top/Article/details/gt2tiyhxabj.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.316326.xyz/Article/details/gt2vxvorlke.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.gotoacloud.top/Article/details/gt2daqyxcwb.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xgtzuevp.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ljqkvfit.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhoulong.xyz/Article/details/gt2cykfbqpw.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lcbcswbh.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.xinyue.icu/Article/details/gt2xmvvuaxa.html

[N05] 最大公约数
来源：http://dali.sufxvd.cn/Article/details/gt2lexivifj.html

Py:   math.gcd(a, b)
来源：http://dali.sufxvd.cn/Article/details/gt2nstdtcin.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.birdmap.top/Article/details/gt2pmvautoo.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dbcxfvlk.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hnxiangtu.top/Article/details/gt2madrugco.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.tanke756.top/Article/details/gt2yzvqktnn.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.c1oappe.top/Article/details/gt2tbgevkzx.html

Ruby: a.gcd(b)
来源：http://dali.tian-w.cn/Article/details/gt2zmgeliwi.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.ydzc1.top/Article/details/gt2hifclfwg.html

[N06] 判断回文字符串
来源：http://dali.shangyingyoupin.top/Article/details/gt2lnepkiax.html

Py:   s == s[::-1]
来源：http://dali.zhoulong.xyz/Article/details/gt2wfmsbtos.html

PHP:  $s === strrev($s);
来源：http://dali.gogol.net.cn/Article/details/gt2tmkchnrw.html

JS:   s === [...s].reverse().join("")
来源：http://dali.meibo888.top/Article/details/gt2hhollvao.html

TS:   s === [...s].reverse().join("")
来源：http://dali.meibo888.top/Article/details/gt2civhjpww.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.kuanghao11.cn/Article/details/gt2fnwuzngf.html

Go:   // 双指针从两端比较
来源：http://dali.nanxinkj.top/Article/details/gt2euzhmapr.html

Ruby: s == s.reverse
来源：http://dali.zhengqikj.top/Article/details/gt2satjynbd.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.mhx1999.top/Article/details/gt2zekyresa.html

[N07] 两数之和（返回下标）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fnftielx.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhoulong.xyz/Article/details/gt2owzhxgzo.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.jqgufenzy.top/Article/details/gt2sevpcchg.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.c1oappe.top/Article/details/gt2vnnzyjel.html

TS:   // 手写 Map<string, number>
来源：http://dali.dashuyun.cn/Article/details/gt2xaghtxas.html

Java: // 手写 HashMap
来源：http://dali.hongshengwenyu.top/Article/details/gt2alzaswbi.html

Go:   // 手写 map[int]int
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xoymhotd.html

Ruby: // 手写 Hash
来源：http://dali.sysykeji.top/Article/details/gt2grkwkbje.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.gotoacloud.top/Article/details/gt2ctwfwwlc.html

[N08] 生成全排列
来源：http://dali.kuanghao11.cn/Article/details/gt2mdlfjfvl.html

Py:   itertools.permutations(arr)
来源：http://dali.zhengqikj.top/Article/details/gt2jmdkjqpb.html

PHP:  // 手写递归交换
来源：http://dali.snrcjt.cn/Article/details/gt2izzzzkid.html

JS:   // 手写回溯递归
来源：http://dali.zhoulong.xyz/Article/details/gt2hyxhecfc.html

TS:   // 手写回溯递归
来源：http://dali.aizwys.cn/Article/details/gt2yqvbjscl.html

Java: // 手写回溯递归
来源：http://dali.wangdashe.top/Article/details/gt2ftxsgnxt.html

Go:   // 手写回溯递归
来源：http://dali.fzhhl.top/Article/details/gt2hhwcmtrz.html

Ruby: arr.permutation.to_a
来源：http://dali.dashuyun.cn/Article/details/gt2gahapebl.html

C#:   // 手写回溯递归
来源：http://dali.quarkkingdee.top/Article/details/gt2luwkopxx.html

[N09] 栈与队列
来源：http://dali.jqgufenzy.top/Article/details/gt2qvhnzkmk.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.hywenlv.cn/Article/details/gt2lgubsbey.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.smart0.xyz/Article/details/gt2spcdwdzr.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.kuanghao11.cn/Article/details/gt2fmxxnuwo.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2rnevwopc.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.bjfxy.top/Article/details/gt2vcwhaynd.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.pengpengdd.cyou/Article/details/gt2vzmdaahr.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhongyouzk.top/Article/details/gt2ugfzliyg.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.ivvv.top/Article/details/gt2hhcydchr.html

[N10] 链表节点定义
来源：http://dali.svipenyu.cn/Article/details/gt2vmmxggdk.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhoulong.xyz/Article/details/gt2ykccdowx.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.jyoumei.cn/Article/details/gt2zlfjcwbw.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.ehwqpu.com/Article/details/gt2xcepponj.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.yj20258888.top/Article/details/gt2qdahyrhi.html

Java: class Node { int v; Node next; }
来源：http://dali.dashuyun.cn/Article/details/gt2rtuwnrfn.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.hnxiangtu.top/Article/details/gt2ktgbgcin.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.iojbl.cn/Article/details/gt2ggvolsjp.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.yongpay.top/Article/details/gt2rycyuhnu.html

[N11] 二叉树中序遍历
来源：http://dali.chenlongwang.top/Article/details/gt2kkyffmxe.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.cheryme.top/Article/details/gt2fdpgmvrq.html

PHP:  // 手写递归函数
来源：http://dali.vqdsnc.cn/Article/details/gt2jqirvsnu.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.gotoacloud.top/Article/details/gt2aemndedv.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.hammf.cn/Article/details/gt2icetxrnv.html

Java: // 手写递归
来源：http://dali.yueranfly.top/Article/details/gt2xnwmqgcj.html

Go:   // 手写递归
来源：http://dali.chenzaomai.com/Article/details/gt2qqlbiiyq.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.jqgfzy.top/Article/details/gt2htimtqsj.html

C#:   // 手写递归
来源：http://dali.fengsongda.top/Article/details/gt2ytjmepch.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.sxryk.cn/Article/details/gt2biclgcel.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.hammf.cn/Article/details/gt2tszjdoye.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.svipenyu.cn/Article/details/gt2annazvnw.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.ehwqpu.com/Article/details/gt2pogfgtsm.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.chenjidiqi.icu/Article/details/gt2qorgmxtw.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.haohaochexian.top/Article/details/gt2wkrtgdhx.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.feifeiyinyue.top/Article/details/gt2nnbytvpa.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.xziqi.cn/Article/details/gt2ftrvemaw.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhoulong.xyz/Article/details/gt2tdxtxpeg.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gt2mhtmgfrm.html

O. 并发与异步
来源：http://dali.tian-w.cn/Article/details/gt2vtzsffqv.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gt2rxmfgluo.html

[O01] 启动一个线程
来源：http://dali.ydzc1.top/Article/details/gt2etzqxymd.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2gddpheja.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.yongpay.top/Article/details/gt2jqzshyhx.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.ehwqpu.com/Article/details/gt2yliupany.html

TS:   // 同 JS
来源：http://dali.xuanzx.com/Article/details/gt2oeyegicn.html

Java: new Thread(() -> f()).start()
来源：http://dali.svipenyu.cn/Article/details/gt2jvkkkugb.html

Go:   go f()
来源：http://dali.tian-w.cn/Article/details/gt2srkuyjwm.html

Ruby: Thread.new { f }
来源：http://dali.pycfn.com/Article/details/gt2mitlmssn.html

C#:   Task.Run(() => F());
来源：http://dali.chenzaomai.com/Article/details/gt2uhvjbffn.html

[O02] 使用线程池
来源：http://dali.jyoumei.cn/Article/details/gt2bmdptxzf.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.haohaochexian.top/Article/details/gt2bqbcrbes.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.gotoacloud.top/Article/details/gt2onreulvh.html

JS:   // worker_threads 线程池
来源：http://dali.fengsongda.top/Article/details/gt2xswysyrf.html

TS:   // worker_threads 线程池
来源：http://dali.xinyue.icu/Article/details/gt2orzferzf.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.yonumen.top/Article/details/gt2iafmsdjh.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dixrbgcw.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.gaohongyu789.top/Article/details/gt2ekllztot.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.shzxlz.cn/Article/details/gt2eufwbcnj.html

[O03] 加锁保护共享数据
来源：http://dali.xylfe.cn/Article/details/gt2aocuzson.html

Py:   with lock: shared += 1
来源：http://dali.ybcxt.top/Article/details/gt2zljezboj.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.jianghu66.top/Article/details/gt2mseegubk.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.yonumen.top/Article/details/gt2hmdldchl.html

TS:   // 同 JS
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2armnffky.html

Java: synchronized (this) { shared++; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2ubsfdtfe.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.gzhubu.top/Article/details/gt2byjnybwb.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.hammf.cn/Article/details/gt2jnccfltm.html

C#:   lock (gate) { shared++; }
来源：http://dali.xylfe.cn/Article/details/gt2hlfwzjyy.html

[O04] 定义异步函数并等待
来源：http://dali.smart0.xyz/Article/details/gt2qkqpzfth.html

Py:   async def f():⏎    await g()
来源：http://dali.yj20258888.top/Article/details/gt2ftqxytcs.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.jqgfzy.top/Article/details/gt2vnqzeqzp.html

JS:   async function f() { await g(); }
来源：http://dali.snrcjt.cn/Article/details/gt2kyhfqlgn.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.gaohongyu789.top/Article/details/gt2ctijggpj.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.cdnleiting.top/Article/details/gt2gvovqbfk.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.yj20258888.top/Article/details/gt2pahuwakt.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.yonumen.top/Article/details/gt2whpqytnn.html

C#:   async Task F() { await G(); }
来源：http://dali.shangyingyoupin.top/Article/details/gt2ojzomhjq.html

[O05] 并发执行并等待全部完成
来源：http://dali.yanxiufei.cn/Article/details/gt2uxgpcpbc.html

Py:   asyncio.gather(*tasks)
来源：http://dali.yonumen.top/Article/details/gt2txfrufzh.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.nanxuanxn.top/Article/details/gt2kxyhkewy.html

JS:   await Promise.all(tasks)
来源：http://dali.yj20258.top/Article/details/gt2cckbxtdh.html

TS:   await Promise.all(tasks)
来源：http://dali.jqgufenzy.top/Article/details/gt2iaoqzieg.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vzfyjklh.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.cheryme.top/Article/details/gt2sxcsdmgb.html

Ruby: threads.map(&:join)
来源：http://dali.gogol.net.cn/Article/details/gt2qgpickwk.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.guowangkeji.top/Article/details/gt2dmcoenyo.html

[O06] 使用进程池
来源：http://dali.cdnleiting.top/Article/details/gt2rhmyyqve.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.sweek.top/Article/details/gt2axoewutv.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.yuxming.cn/Article/details/gt2wfanfgbb.html

JS:   // child_process / cluster 模块
来源：http://dali.bjfxy.top/Article/details/gt2dvvneuyp.html

TS:   // child_process / cluster 模块
来源：http://dali.yueranfly.top/Article/details/gt2itvowmsh.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.jqgufenzy.top/Article/details/gt2rwprhezi.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.tian-w.cn/Article/details/gt2pojptlfo.html

Ruby: // fork 块
来源：http://dali.jyoumei.cn/Article/details/gt2hdtosusq.html

C#:   Parallel.For
来源：http://dali.fengsongda.top/Article/details/gt2hkjhbair.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gt2ergycnpy.html

P. 常用工具函数
来源：http://dali.0kj1m.cn/Article/details/gt2bacwhcdr.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gt2bahfprae.html

[P01] 生成 UUID
来源：http://dali.smart0.xyz/Article/details/gt2mgkrpovt.html

Py:   str(uuid.uuid4())
来源：http://dali.fengsongda.top/Article/details/gt2fkahhkgi.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.redwolf501.top/Article/details/gt2tfbpiict.html

JS:   crypto.randomUUID()
来源：http://dali.c1oappe.top/Article/details/gt2sgnvtdjn.html

TS:   crypto.randomUUID()
来源：http://dali.ppjwa.cn/Article/details/gt2cvhdsntc.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhiwuduotai.top/Article/details/gt2rcwpiwrz.html

Go:   // 用 github.com/google/uuid
来源：http://dali.wangdashe.top/Article/details/gt2vkzyzqlk.html

Ruby: SecureRandom.uuid
来源：http://dali.guannengcc.top/Article/details/gt2rqrhoxbt.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.redwolf501.top/Article/details/gt2fgwoopst.html

[P02] MD5 / SHA256 摘要
来源：http://dali.chenlongwang.top/Article/details/gt2zdwkykoh.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.quarkkingdee.top/Article/details/gt2khprepif.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.ppjwa.cn/Article/details/gt2fwqrolwu.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.gogol.net.cn/Article/details/gt2hnulvvao.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lxxdeiil.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.smart0.xyz/Article/details/gt2iprpjljo.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.chenlongwang.top/Article/details/gt2otdofzte.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.snrcjt.cn/Article/details/gt2silyomag.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.tanke756.top/Article/details/gt2bngnhviz.html

[P03] 生成短随机字符串
来源：http://dali.birdmap.top/Article/details/gt2gmwhmecq.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.hammf.cn/Article/details/gt2piqjrqnb.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.tianlin.xyz/Article/details/gt2qoemvzkx.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.cheryme.top/Article/details/gt2lyhodkrw.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.shangyingyoupin.top/Article/details/gt2yxwvgwbf.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.chenlongwang.top/Article/details/gt2bznldfjh.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.fzhhl.top/Article/details/gt2bmctthei.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.sweek.top/Article/details/gt2yielwzyq.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.pengpengdd.cyou/Article/details/gt2fussorvu.html

[P04] 求长度
来源：http://dali.jinqigufen.top/Article/details/gt2mlirrznr.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.xuanzx.com/Article/details/gt2ypggbyym.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.gzhubu.top/Article/details/gt2urqhmhee.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.guannengcc.top/Article/details/gt2dntsrdqk.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.tian-w.cn/Article/details/gt2yeapisuh.html

Java: list.size();  map.size();  s.length()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wyhpxyjg.html

Go:   len(arr);  len(m)
来源：http://dali.nanxuanxn.top/Article/details/gt2kvephykx.html

Ruby: x.length;  x.size
来源：http://dali.gotoacloud.top/Article/details/gt2ajzevaed.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.cqqwz.cn/Article/details/gt2kwhizhsn.html

[P05] 判断两个对象内容是否相等
来源：http://dali.9152youxi.cn/Article/details/gt2nqiednkw.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.chenzaomai.com/Article/details/gt2koeofsky.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.hywenlv.cn/Article/details/gt2fvsljfua.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.gzhubu.top/Article/details/gt2llvdhiqr.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.hammf.cn/Article/details/gt2hipipepb.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.sweek.top/Article/details/gt2gxprkxtl.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.jianghu66.top/Article/details/gt2tigamyaz.html

Ruby: a == b
来源：http://dali.hammf.cn/Article/details/gt2jqhogqpo.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhongyouzk.top/Article/details/gt2oprdafwp.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.shzxlz.cn/Article/details/gt2jqsknmhe.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.smart0.xyz/Article/details/gt2lmlhscvr.html

PHP:  if (empty($x)) {}
来源：http://dali.jiagoushi.top/Article/details/gt2rruicvxb.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.svipenyu.cn/Article/details/gt2eehzantw.html

TS:   if (x == null) {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2tjdvtxbu.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.gzhubu.top/Article/details/gt2cocioviu.html

Go:   if x == nil {}
来源：http://dali.sweek.top/Article/details/gt2ozsboebg.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.9152youxi.cn/Article/details/gt2naqmxcyn.html

C#:   if (x is null) {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2jllquzzu.html

[P07] 防抖与节流
来源：http://dali.jqgfzy.top/Article/details/gt2gstloduz.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhongyouzk.top/Article/details/gt2gjmcpqdn.html

PHP:  // 手写时间戳比较
来源：http://dali.c1oappe.top/Article/details/gt2sbwtufrj.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.gogol.net.cn/Article/details/gt2mfypttid.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.havefunace.top/Article/details/gt2gnwmuaum.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.haohaochexian.top/Article/details/gt2gbiyjbiv.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zdqjudy.top/Article/details/gt2gukvmvgm.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.shzxlz.cn/Article/details/gt2kltleqyw.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.yangfankeji.com/Article/details/gt2zkisbkei.html

[P08] 处理浮点精度问题
来源：http://dali.meibo888.top/Article/details/gt2kvvehfed.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.aibaodan.cn/Article/details/gt2amgfgowr.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.svipenyu.cn/Article/details/gt2gdnenthu.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.sysykeji.top/Article/details/gt2xqhanrff.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.jlsjyb.cn/Article/details/gt2sghghpzx.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.ybcxt.top/Article/details/gt2klunftwa.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pdnluuvo.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.redwolf501.top/Article/details/gt2uykijswi.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.pengpengdd.cyou/Article/details/gt2ongdhbje.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2qtjxcejo.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.hongshengwenyu.top/Article/details/gt2oczsapbd.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gt2iqphaomv.html

[Q01] 创建表
来源：http://dali.ydzc1.top/Article/details/gt2pptqansa.html

CREATE TABLE users (
来源：http://dali.9152youxi.cn/Article/details/gt2dsmspogp.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.hammf.cn/Article/details/gt2sdtajlpk.html

name VARCHAR(50) NOT NULL,
来源：http://dali.cheryme.top/Article/details/gt2gnahfrqn.html

email VARCHAR(100) UNIQUE,
来源：http://dali.sysykeji.top/Article/details/gt2bfraepsu.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.chenlongwang.top/Article/details/gt2ngfrpyds.html

);
来源：http://dali.cdnleiting.top/Article/details/gt2uxzfmnvp.html

[Q02] 创建带外键的表
来源：http://dali.haohaochexian.top/Article/details/gt2ztrhkuir.html

CREATE TABLE orders (
来源：http://dali.yvedp.cn/Article/details/gt2tgpagsxi.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jinqigufen.top/Article/details/gt2kmyxcbmq.html

user_id INT NOT NULL,
来源：http://dali.haohaochexian.top/Article/details/gt2nzoyetyj.html

amount DECIMAL(10, 2),
来源：http://dali.fengsongda.top/Article/details/gt2elsfudup.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.yangfankeji.com/Article/details/gt2dhkqohqc.html

);
来源：http://dali.wangshuangyany.cn/Article/details/gt2ufxdirom.html

[Q03] 增加列
来源：http://dali.birdmap.top/Article/details/gt2jdvvhlip.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.fengsongda.top/Article/details/gt2tbgwunzk.html

[Q04] 修改列类型
来源：http://dali.nwbrower.top/Article/details/gt2zrhfmvzr.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.gotoacloud.top/Article/details/gt2qgwpqava.html

[Q05] 重命名列
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pnfcuwfq.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.cqqwz.cn/Article/details/gt2jatdngqt.html

[Q06] 删除列
来源：http://dali.zhijiandao.cn/Article/details/gt2frbxdlym.html


<!-- 参考信息 -->