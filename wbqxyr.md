代发 wailian999

Ruby: exit 1
来源：http://dali.mhx1999.top/Article/details/gtspvhifrt.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.jianghu66.top/Article/details/gtsomvxqxs.html

[M06] 向标准错误输出
来源：http://dali.yueranfly.top/Article/details/gthzmlgzrs.html

Py:   print("err", file=sys.stderr)
来源：http://dali.gzhubu.top/Article/details/gtvekfzigz.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.jlsjyb.cn/Article/details/gtaektgspb.html

JS:   console.error("err")
来源：http://dali.sweek.top/Article/details/gtdyuzeyee.html

TS:   console.error("err")
来源：http://dali.chenlongwang.top/Article/details/gtfbbyxepj.html

Java: System.err.println("err")
来源：http://dali.ehwqpu.com/Article/details/gtkkmphlnl.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.shuidangran.top/Article/details/gtxajhavmx.html

Ruby: warn "err"
来源：http://dali.chenzaomai.com/Article/details/gtxhltucrg.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.jyoumei.cn/Article/details/gtuaysgank.html

[M07] 判断是否为主入口
来源：http://dali.yj20258.top/Article/details/gtyxafnrye.html

Py:   if __name__ == "__main__":
来源：http://dali.xylfe.cn/Article/details/gtrfkojztg.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.xinyue.icu/Article/details/gttfeuohui.html

JS:   require.main === module
来源：http://dali.xziqi.cn/Article/details/gtvxgefmqf.html

TS:   require.main === module
来源：http://dali.fzhhl.top/Article/details/gtszldofoq.html

Java: public static void main(String[] args)
来源：http://dali.tianlin.xyz/Article/details/gttsraapzi.html

Go:   func main()
来源：http://dali.zycfv.cn/Article/details/gthmrblgnu.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhiwuduotai.top/Article/details/gtrzlbybqc.html

C#:   static void Main(string[] args)
来源：http://dali.shangyingyoupin.top/Article/details/gtkxmfhzre.html

[M08] 获取系统与运行时信息
来源：http://dali.yvedp.cn/Article/details/gtkfggyrkd.html

Py:   platform.system();  platform.python_version()
来源：http://dali.smart0.xyz/Article/details/gtbtxbiuts.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zycfv.cn/Article/details/gtscmsgzzm.html

JS:   process.platform;  process.version
来源：http://dali.jqgfzy.top/Article/details/gtolyxmyzo.html

TS:   process.platform;  process.version
来源：http://dali.svipenyu.cn/Article/details/gtkgucavgo.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.sweek.top/Article/details/gtlssmooze.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.pycfn.com/Article/details/gtdsgoyzhd.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zycfv.cn/Article/details/gtzcazgqkt.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.haohaochexian.top/Article/details/gtidqhpanq.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtcfzyzytk.html

N. 数据结构与算法
来源：http://dali.yuxming.cn/Article/details/gtlcatvmcn.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtqavrdglk.html

[N01] 二分查找（有序数组）
来源：http://dali.cucudq.cn/Article/details/gtcqcowvfa.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhixingplan.top/Article/details/gtjtdwjcad.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.feifeiyinyue.top/Article/details/gtuvbladyd.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yanxiufei.cn/Article/details/gtlorsyipc.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.nanxuanxn.top/Article/details/gtdgzgnftp.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zdqjudy.top/Article/details/gtjndxxnca.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.yueranfly.top/Article/details/gtkdhqlbkx.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.shanyushiyangtech.top/Article/details/gtinwtlfqz.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbbucucve.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.quarkkingdee.top/Article/details/gtrwlwmqnl.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.hammf.cn/Article/details/gtxmpgndfo.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.yonumen.top/Article/details/gtezbnvpii.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zycfv.cn/Article/details/gtgajdqwll.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.xuanzx.com/Article/details/gtwgbiqqfw.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhixingplan.top/Article/details/gtnlzeozhu.html

Go:   slices.Sort(arr)
来源：http://dali.zhongyouzk.top/Article/details/gtmvxsymoe.html

Ruby: arr.sort
来源：http://dali.gzhubu.top/Article/details/gtblmsfnrp.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.dashuyun.cn/Article/details/gtflskkkge.html

[N03] 快速排序（分治示例）
来源：http://dali.yonumen.top/Article/details/gttoirwpvg.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.xuanzx.com/Article/details/gtuzaoqmrp.html

PHP:  // 递归实现，或用 usort
来源：http://dali.c1oappe.top/Article/details/gtnheltimv.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.shzxlz.cn/Article/details/gtgeygfytz.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhiwuduotai.top/Article/details/gtiumvfscc.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.hongshengwenyu.top/Article/details/gttqmhkytf.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.birdmap.top/Article/details/gtqzywjafi.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.chenlongwang.top/Article/details/gtokmelypc.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.aibaodan.cn/Article/details/gtxhpmxvva.html

[N04] 斐波那契数列
来源：http://dali.shanyushiyangkeji.top/Article/details/gtejfjohyf.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.ydzc1.top/Article/details/gtvolrlkkx.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.shuidangran.top/Article/details/gtjtydrszg.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.hysaishi.cn/Article/details/gtkruzxnzo.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.meibo888.top/Article/details/gtuughkzyp.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtkqwgtgrw.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.gogol.net.cn/Article/details/gtlqobcntu.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.ivvv.top/Article/details/gtjogudetb.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zycfv.cn/Article/details/gtndwvttvy.html

[N05] 最大公约数
来源：http://dali.yanxiufei.cn/Article/details/gtwfzrruhb.html

Py:   math.gcd(a, b)
来源：http://dali.ppjwa.cn/Article/details/gtsypdpjqe.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.shzxlz.cn/Article/details/gtyovwjeue.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.meibo888.top/Article/details/gtngrmoexx.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.gzhubu.top/Article/details/gtvyuyitgz.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.vqdsnc.cn/Article/details/gtapsvhkrj.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.cashguo.top/Article/details/gtvpzkryvb.html

Ruby: a.gcd(b)
来源：http://dali.c1oappe.top/Article/details/gtsfgbejal.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.tianlin.xyz/Article/details/gtimtdpwle.html

[N06] 判断回文字符串
来源：http://dali.jlsjyb.cn/Article/details/gtezypnkjv.html

Py:   s == s[::-1]
来源：http://dali.cucudq.cn/Article/details/gtrjfuseuc.html

PHP:  $s === strrev($s);
来源：http://dali.wangdashe.top/Article/details/gtjyednsfb.html

JS:   s === [...s].reverse().join("")
来源：http://dali.chenzaomai.com/Article/details/gtwzdluqsq.html

TS:   s === [...s].reverse().join("")
来源：http://dali.jiagoushi.top/Article/details/gtrdogxznj.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.redwolf501.top/Article/details/gtvlarqzvm.html

Go:   // 双指针从两端比较
来源：http://dali.9152youxi.cn/Article/details/gtekfntbqo.html

Ruby: s == s.reverse
来源：http://dali.yuxming.cn/Article/details/gtwdxurwos.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.pengpengdd.cyou/Article/details/gtbsqwtyxc.html

[N07] 两数之和（返回下标）
来源：http://dali.zhixingplan.top/Article/details/gtbaohogru.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.hfpthk.cn/Article/details/gtkqjdyvmy.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.dashuyun.cn/Article/details/gtjwllvltl.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.jqgufenzy.top/Article/details/gtxuxwioaw.html

TS:   // 手写 Map<string, number>
来源：http://dali.chenjidiqi.icu/Article/details/gtvpknsgfk.html

Java: // 手写 HashMap
来源：http://dali.gzhubu.top/Article/details/gtjrhrrxbg.html

Go:   // 手写 map[int]int
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdlppwlvh.html

Ruby: // 手写 Hash
来源：http://dali.zhongyouzk.top/Article/details/gtzkfcbnzt.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.tianlin.xyz/Article/details/gteijhxoqo.html

[N08] 生成全排列
来源：http://dali.9152youxi.cn/Article/details/gtrkwwgwtn.html

Py:   itertools.permutations(arr)
来源：http://dali.cdnleiting.top/Article/details/gtawscssbo.html

PHP:  // 手写递归交换
来源：http://dali.kuanghao11.cn/Article/details/gtzrobqsvc.html

JS:   // 手写回溯递归
来源：http://dali.yanxiufei.cn/Article/details/gtzuwgneqy.html

TS:   // 手写回溯递归
来源：http://dali.havefunace.top/Article/details/gtmedwuwmy.html

Java: // 手写回溯递归
来源：http://dali.ehwqpu.com/Article/details/gtwlmbyclw.html

Go:   // 手写回溯递归
来源：http://dali.sweek.top/Article/details/gtmfyzqnfy.html

Ruby: arr.permutation.to_a
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwmtfvzye.html

C#:   // 手写回溯递归
来源：http://dali.shanyushiyangtech.top/Article/details/gtyqqshomr.html

[N09] 栈与队列
来源：http://dali.svipenyu.cn/Article/details/gtkclfzbei.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.316326.xyz/Article/details/gtflnphaxx.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.fzhhl.top/Article/details/gtfltcdnlx.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.yuxming.cn/Article/details/gtrasblqnh.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.birdmap.top/Article/details/gtvahruwgp.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.snrcjt.cn/Article/details/gtmubouvkh.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.jqgufenzy.top/Article/details/gtktojvbsq.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.chenzaomai.com/Article/details/gtkstozxja.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.yongpay.top/Article/details/gtwgfasjjd.html

[N10] 链表节点定义
来源：http://dali.zhongyouzk.top/Article/details/gtnjjtcrso.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhiwuduotai.top/Article/details/gtwktgjndq.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.yuxming.cn/Article/details/gtbmzxtmds.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.andypj.xyz/Article/details/gtbwobeblx.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.hnxiangtu.top/Article/details/gtydboahyh.html

Java: class Node { int v; Node next; }
来源：http://dali.wangdashe.top/Article/details/gtsbuoepqe.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.shuidangran.top/Article/details/gttxhhqmue.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.yj20258.top/Article/details/gtplesspuw.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.tanke756.top/Article/details/gtxhngkjsp.html

[N11] 二叉树中序遍历
来源：http://dali.hnqzz.top/Article/details/gtditjfxyg.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.yongpay.top/Article/details/gtijvukpoq.html

PHP:  // 手写递归函数
来源：http://dali.yvedp.cn/Article/details/gtlexbysdh.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjklumixt.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.nanxuanxn.top/Article/details/gttwaqcqti.html

Java: // 手写递归
来源：http://dali.cucudq.cn/Article/details/gtlprwlezb.html

Go:   // 手写递归
来源：http://dali.dianchejie.cn/Article/details/gtlzbhespo.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.9152youxi.cn/Article/details/gthbaahirm.html

C#:   // 手写递归
来源：http://dali.dianchejie.cn/Article/details/gtshcshczt.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.redwolf501.top/Article/details/gtkbgpzgqd.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.havefunace.top/Article/details/gtheawetww.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.hnqzz.top/Article/details/gtrvemnjpz.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jiagoushi.top/Article/details/gtpiypfeqk.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhoulong.xyz/Article/details/gtixbprgeq.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.guannengcc.top/Article/details/gthpgejstt.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.mhx1999.top/Article/details/gtbgowyrfl.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhixingplan.top/Article/details/gttdqwfpnk.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.haohaochexian.top/Article/details/gtvozmmcvr.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gthzhyvxvz.html

O. 并发与异步
来源：http://dali.zhengqikj.top/Article/details/gtsxbftqen.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtbsjaoowp.html

[O01] 启动一个线程
来源：http://dali.nanxuanxn.top/Article/details/gtazsifhqk.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.havefunace.top/Article/details/gtyakxruid.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.xziqi.cn/Article/details/gtoadsgxzi.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gtworzlduy.html

TS:   // 同 JS
来源：http://dali.chenzaomai.com/Article/details/gtblbkugfs.html

Java: new Thread(() -> f()).start()
来源：http://dali.aizwys.cn/Article/details/gtnhzqzyhy.html

Go:   go f()
来源：http://dali.aibaodan.cn/Article/details/gtyzaqnvyy.html

Ruby: Thread.new { f }
来源：http://dali.gogol.net.cn/Article/details/gtdvscvwkw.html

C#:   Task.Run(() => F());
来源：http://dali.smart0.xyz/Article/details/gtgwfedrdr.html

[O02] 使用线程池
来源：http://dali.zhiwuduotai.top/Article/details/gtkpxdsamt.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.xylfe.cn/Article/details/gtmaufefnf.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhengqikj.top/Article/details/gtoigyeayp.html

JS:   // worker_threads 线程池
来源：http://dali.aibaodan.cn/Article/details/gthygpnely.html

TS:   // worker_threads 线程池
来源：http://dali.meibo888.top/Article/details/gtejdrbibf.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.jinqigfzy.top/Article/details/gtlreaxxuy.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.wangdashe.top/Article/details/gtehqenoqf.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhoulong.xyz/Article/details/gtilpztxmt.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.smart0.xyz/Article/details/gtjnvslcoc.html

[O03] 加锁保护共享数据
来源：http://dali.svipenyu.cn/Article/details/gtectsaynk.html

Py:   with lock: shared += 1
来源：http://dali.xinyue.icu/Article/details/gtwpvanonw.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.sysykeji.top/Article/details/gtizehazcb.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.shanyushiyangkeji.top/Article/details/gtajffclza.html

TS:   // 同 JS
来源：http://dali.yj202588.top/Article/details/gtkdpzfntw.html

Java: synchronized (this) { shared++; }
来源：http://dali.xziqi.cn/Article/details/gtpivvrszd.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.jqgfzy.top/Article/details/gtoqcggdjn.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.yongpay.top/Article/details/gtjirbrftp.html

C#:   lock (gate) { shared++; }
来源：http://dali.jqgfzy.top/Article/details/gtvmjnahmh.html

[O04] 定义异步函数并等待
来源：http://dali.jinqigufen.top/Article/details/gtfdeswfku.html

Py:   async def f():⏎    await g()
来源：http://dali.nanxinkj.top/Article/details/gtchonlmut.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.cdnleiting.top/Article/details/gtfnkmruwm.html

JS:   async function f() { await g(); }
来源：http://dali.daria6918.cn/Article/details/gtvkudtgch.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.xziqi.cn/Article/details/gtmlfgcjmw.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.cashguo.top/Article/details/gturktgexb.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.ybcxt.top/Article/details/gtaksmywmu.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhiwuduotai.top/Article/details/gttmquqqrx.html

C#:   async Task F() { await G(); }
来源：http://dali.snrcjt.cn/Article/details/gtadtbeuzk.html

[O05] 并发执行并等待全部完成
来源：http://dali.hysaishi.cn/Article/details/gtgovcqppc.html

Py:   asyncio.gather(*tasks)
来源：http://dali.ybcxt.top/Article/details/gtafvxmtdw.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.gotoacloud.top/Article/details/gtmzsxnhac.html

JS:   await Promise.all(tasks)
来源：http://dali.zdqjudy.top/Article/details/gtlacdbqry.html

TS:   await Promise.all(tasks)
来源：http://dali.yuanzhike.top/Article/details/gthobnjuef.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.c1oappe.top/Article/details/gtzjofexlg.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.dianchejie.cn/Article/details/gtqhzpkhws.html

Ruby: threads.map(&:join)
来源：http://dali.birdmap.top/Article/details/gtxfdbbwvr.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkibyhuqt.html

[O06] 使用进程池
来源：http://dali.nanxinkj.top/Article/details/gttdgnbyco.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.wangshuangyany.cn/Article/details/gtpuepllzi.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.hywenlv.cn/Article/details/gtcyjvaunm.html

JS:   // child_process / cluster 模块
来源：http://dali.jqgufenzy.top/Article/details/gtkbuxbebg.html

TS:   // child_process / cluster 模块
来源：http://dali.smart0.xyz/Article/details/gtzyjqopma.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.nanxuanxn.top/Article/details/gtkunnrzob.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.yueranfly.top/Article/details/gtnqotpqvq.html

Ruby: // fork 块
来源：http://dali.xuetiantiany.cn/Article/details/gtezrgmmnx.html

C#:   Parallel.For
来源：http://dali.gzhubu.top/Article/details/gtfytafjtr.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtzhtlhczm.html

P. 常用工具函数
来源：http://dali.cucudq.cn/Article/details/gtbzeqfiud.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtkgejuwrc.html

[P01] 生成 UUID
来源：http://dali.xylfe.cn/Article/details/gtnrzvusjb.html

Py:   str(uuid.uuid4())
来源：http://dali.ivvv.top/Article/details/gtkwbmfcax.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhoulong.xyz/Article/details/gtwdtjeyge.html

JS:   crypto.randomUUID()
来源：http://dali.xziqi.cn/Article/details/gtmexeibez.html

TS:   crypto.randomUUID()
来源：http://dali.smart0.xyz/Article/details/gtknoadukg.html

Java: UUID.randomUUID().toString()
来源：http://dali.zdqjudy.top/Article/details/gtwsdoxjnt.html

Go:   // 用 github.com/google/uuid
来源：http://dali.redwolf501.top/Article/details/gtifuhxwif.html

Ruby: SecureRandom.uuid
来源：http://dali.shzxlz.cn/Article/details/gtxmwvuxen.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.wangdashe.top/Article/details/gtdczvcbnf.html

[P02] MD5 / SHA256 摘要
来源：http://dali.dianchejie.cn/Article/details/gtdaqfhywp.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.nanxuanxn.top/Article/details/gtzvmdrren.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.316326.xyz/Article/details/gtcwdxhpvm.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.xuetiantiany.cn/Article/details/gtlprvizob.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.jqgfzy.top/Article/details/gtfcxytgfy.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.shuidangran.top/Article/details/gtmjkbuhim.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.vqdsnc.cn/Article/details/gtreqnrwll.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjtfozlsl.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.shzxlz.cn/Article/details/gtsivbvqlt.html

[P03] 生成短随机字符串
来源：http://dali.yongpay.top/Article/details/gtbhexxzfx.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.quarkkingdee.top/Article/details/gtyxifzduh.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.bjfxy.top/Article/details/gtdxwgdfin.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jqgufenzy.top/Article/details/gtkekspiza.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.wangdashe.top/Article/details/gtxhmshzus.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.gaohongyu789.top/Article/details/gteunoppys.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.9152youxi.cn/Article/details/gtvxtfpzxq.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.jianghu66.top/Article/details/gtfobezxti.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.hnxiangtu.top/Article/details/gtfnjymbuh.html

[P04] 求长度
来源：http://dali.iojbl.cn/Article/details/gtwavybmkz.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.snrcjt.cn/Article/details/gtmswkbquc.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.shangyingyoupin.top/Article/details/gtekfmwudi.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.aibaodan.cn/Article/details/gtfbfpywmr.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jyoumei.cn/Article/details/gtbdqrtwsb.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyavmsozl.html

Go:   len(arr);  len(m)
来源：http://dali.wangdashe.top/Article/details/gtozhcwnyd.html

Ruby: x.length;  x.size
来源：http://dali.sufxvd.cn/Article/details/gtnjtnknlr.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.quarkkingdee.top/Article/details/gtaiyddnjj.html

[P05] 判断两个对象内容是否相等
来源：http://dali.dianchejie.cn/Article/details/gtlekrtqdo.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.ppjwa.cn/Article/details/gtqcknvzcp.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.jinghuilouyu.cn/Article/details/gtewzxtakl.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.jinqigufen.top/Article/details/gtdaikxgye.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.hysaishi.cn/Article/details/gtarodwdkq.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.yongpay.top/Article/details/gtljggajvh.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.cdnleiting.top/Article/details/gtvllzuawi.html

Ruby: a == b
来源：http://dali.svipenyu.cn/Article/details/gtsfkjaefk.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.jiagoushi.top/Article/details/gtvopcqugl.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.kuanghao11.cn/Article/details/gtxytsriln.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.yuxming.cn/Article/details/gtngsugebq.html

PHP:  if (empty($x)) {}
来源：http://dali.kuanghao11.cn/Article/details/gtoxghzosw.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhijiandao.cn/Article/details/gtrdvtcsce.html

TS:   if (x == null) {}
来源：http://dali.cqqwz.cn/Article/details/gtghfatqgu.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyxpoqlnj.html

Go:   if x == nil {}
来源：http://dali.ybcxt.top/Article/details/gtyqrrrvrb.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.ybcxt.top/Article/details/gtdebxhdoh.html

C#:   if (x is null) {}
来源：http://dali.chenlongwang.top/Article/details/gtwearvbin.html

[P07] 防抖与节流
来源：http://dali.aibaodan.cn/Article/details/gtxeddtuux.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.nanxuanxn.top/Article/details/gtjjlagfuv.html

PHP:  // 手写时间戳比较
来源：http://dali.wangshuangyany.cn/Article/details/gtvzzborpw.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.cucudq.cn/Article/details/gtpkyddacs.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhiwuduotai.top/Article/details/gtqlddskka.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmmomlkrw.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.fzhhl.top/Article/details/gthnzlsbih.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.cashguo.top/Article/details/gtqgsxhonn.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhengqikj.top/Article/details/gtpjnsxsty.html

[P08] 处理浮点精度问题
来源：http://dali.316326.xyz/Article/details/gtfxqmarpk.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.gzhubu.top/Article/details/gtnqefprss.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.yanxiufei.cn/Article/details/gttvebjubh.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqzkptulh.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.yongpay.top/Article/details/gtmvwcrdyp.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.jqgufenzy.top/Article/details/gtgmexenvw.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.ivvv.top/Article/details/gtztauubmf.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.sufxvd.cn/Article/details/gtnivofvsl.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.aibaodan.cn/Article/details/gtuyrbipzn.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtujoumypl.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.chenzaomai.com/Article/details/gtuzpjbfef.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtudqpeqqf.html

[Q01] 创建表
来源：http://dali.quarkkingdee.top/Article/details/gtpbmwjecp.html

CREATE TABLE users (
来源：http://dali.iojbl.cn/Article/details/gtkumkwabs.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jinghuilouyu.cn/Article/details/gtxghvziti.html

name VARCHAR(50) NOT NULL,
来源：http://dali.andypj.xyz/Article/details/gtqbuduwte.html

email VARCHAR(100) UNIQUE,
来源：http://dali.iojbl.cn/Article/details/gtrfxhehor.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvrhauxqo.html

);
来源：http://dali.havefunace.top/Article/details/gtwrbzlazp.html

[Q02] 创建带外键的表
来源：http://dali.kuanghao11.cn/Article/details/gtfduxcyus.html

CREATE TABLE orders (
来源：http://dali.zhiwuduotai.top/Article/details/gtkxkobjls.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.dianchejie.cn/Article/details/gtreoyhmpa.html

user_id INT NOT NULL,
来源：http://dali.cdnleiting.top/Article/details/gtreukbfmc.html

amount DECIMAL(10, 2),
来源：http://dali.shanyushiyangkeji.top/Article/details/gtclrgeoou.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.havefunace.top/Article/details/gtymylbzdi.html

);
来源：http://dali.yuanzhike.top/Article/details/gtfveozbty.html

[Q03] 增加列
来源：http://dali.jiagoushi.top/Article/details/gtgjulayih.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.sweek.top/Article/details/gtktaoyghn.html

[Q04] 修改列类型
来源：http://dali.aibaodan.cn/Article/details/gtrgzwktyw.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.aibaodan.cn/Article/details/gtueajslnv.html

[Q05] 重命名列
来源：http://dali.gotoacloud.top/Article/details/gtvwoylubi.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.hfpthk.cn/Article/details/gtpuptuqcv.html

[Q06] 删除列
来源：http://dali.hywenlv.cn/Article/details/gtdfnwpfom.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.aibaodan.cn/Article/details/gtkwebvhop.html

[Q07] 删除表
来源：http://dali.yongpay.top/Article/details/gtkpjgevdl.html

DROP TABLE IF EXISTS orders;
来源：http://dali.gzhubu.top/Article/details/gtqnmvkhki.html

[Q08] 创建普通索引
来源：http://dali.yanxiufei.cn/Article/details/gtnbpiusmg.html


<!-- 参考信息 -->