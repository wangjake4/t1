代发 wailian999

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.sufxvd.cn/Article/details/gtzgjiyjya.html

JS:   console.error("err")
来源：http://dali.daria6918.cn/Article/details/gtveidvfot.html

TS:   console.error("err")
来源：http://dali.aibaodan.cn/Article/details/gttzyhhmgf.html

Java: System.err.println("err")
来源：http://dali.yvedp.cn/Article/details/gtzrkexysq.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.yj202588.top/Article/details/gtpwaxkfil.html

Ruby: warn "err"
来源：http://dali.gaohongyu789.top/Article/details/gtqzktiqoy.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.guowangkeji.top/Article/details/gtpkxlipzu.html

[M07] 判断是否为主入口
来源：http://dali.hnqzz.top/Article/details/gtflwzuzul.html

Py:   if __name__ == "__main__":
来源：http://dali.jyoumei.cn/Article/details/gtghaeshnu.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.ybcxt.top/Article/details/gtdspioeqf.html

JS:   require.main === module
来源：http://dali.sxryk.cn/Article/details/gttwgvkwgh.html

TS:   require.main === module
来源：http://dali.shanyushiyangkeji.top/Article/details/gtouqsnsmm.html

Java: public static void main(String[] args)
来源：http://dali.0kj1m.cn/Article/details/gtuibnacol.html

Go:   func main()
来源：http://dali.ydzc1.top/Article/details/gtdloneopg.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.shzxlz.cn/Article/details/gtvfanxrwo.html

C#:   static void Main(string[] args)
来源：http://dali.hfpthk.cn/Article/details/gtqgxkbsay.html

[M08] 获取系统与运行时信息
来源：http://dali.sysykeji.top/Article/details/gtrfwdwmsw.html

Py:   platform.system();  platform.python_version()
来源：http://dali.hysaishi.cn/Article/details/gtcounzeuv.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.aibaodan.cn/Article/details/gthvggsryh.html

JS:   process.platform;  process.version
来源：http://dali.snrcjt.cn/Article/details/gtlfhjkadc.html

TS:   process.platform;  process.version
来源：http://dali.zhiwuduotai.top/Article/details/gtbnlgbxgv.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.haohaochexian.top/Article/details/gtakkfwsmr.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhixingplan.top/Article/details/gtgeomdgcy.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.gotoacloud.top/Article/details/gtzeodosai.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.ybcxt.top/Article/details/gtuitlkqmo.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtzqjrmxsr.html

N. 数据结构与算法
来源：http://dali.wangshuangyany.cn/Article/details/gtgqcntrnn.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtkczsubid.html

[N01] 二分查找（有序数组）
来源：http://dali.cucudq.cn/Article/details/gtkhvyvscr.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnnlohmdx.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwncjhufi.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhengqikj.top/Article/details/gtehotsknv.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.ivvv.top/Article/details/gtxznplwhk.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.tanke756.top/Article/details/gteorobudo.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.ehwqpu.com/Article/details/gtjynanuoq.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbyciyfqw.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.kuanghao11.cn/Article/details/gtdpwmtsxv.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.yueranfly.top/Article/details/gtxrlicjjz.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.shangyingyoupin.top/Article/details/gtpsbtdbxc.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.9152youxi.cn/Article/details/gtlvbwbyps.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtscjephhk.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.c1oappe.top/Article/details/gthtetgvlo.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.hongshengwenyu.top/Article/details/gtzoulsosc.html

Go:   slices.Sort(arr)
来源：http://dali.aibaodan.cn/Article/details/gtqncfizdj.html

Ruby: arr.sort
来源：http://dali.kuanghao11.cn/Article/details/gteotgrttv.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.xziqi.cn/Article/details/gtnhmtwjyj.html

[N03] 快速排序（分治示例）
来源：http://dali.cucudq.cn/Article/details/gtxgjqnmxs.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrmexbghz.html

PHP:  // 递归实现，或用 usort
来源：http://dali.xylfe.cn/Article/details/gtzmwbgskj.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.sysykeji.top/Article/details/gtvxnjbnpq.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjyajksgv.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.svipenyu.cn/Article/details/gtozzewjfe.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.cheryme.top/Article/details/gtfinewrsc.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.daxiang520.top/Article/details/gtazvegrdj.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.tian-w.cn/Article/details/gtqpsxjrvi.html

[N04] 斐波那契数列
来源：http://dali.ivvv.top/Article/details/gthznszmlb.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.gogol.net.cn/Article/details/gtjtnsktma.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.ydzc1.top/Article/details/gtfdfqwrfq.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jinghuilouyu.cn/Article/details/gtycelviju.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtotdprrut.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.chenzaomai.com/Article/details/gtlneiqats.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.guowangkeji.top/Article/details/gtuwnblncr.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.ppjwa.cn/Article/details/gtcjtsuezt.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.nwbrower.top/Article/details/gttywhaywt.html

[N05] 最大公约数
来源：http://dali.hammf.cn/Article/details/gtlqzoryyw.html

Py:   math.gcd(a, b)
来源：http://dali.zhixingplan.top/Article/details/gtpkixqiva.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhoulong.xyz/Article/details/gtrsrpjupf.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrdiglppm.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.vqdsnc.cn/Article/details/gtvjxbzwps.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.feifeiyinyue.top/Article/details/gtvqbpcbbw.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.nanxinkj.top/Article/details/gtuobqmgqo.html

Ruby: a.gcd(b)
来源：http://dali.iojbl.cn/Article/details/gtcbdhyoey.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.yanxiufei.cn/Article/details/gtswbuuzbr.html

[N06] 判断回文字符串
来源：http://dali.xziqi.cn/Article/details/gtgxcackyy.html

Py:   s == s[::-1]
来源：http://dali.jinghuilouyu.cn/Article/details/gtkflaxddt.html

PHP:  $s === strrev($s);
来源：http://dali.jianghu66.top/Article/details/gtnosyqkba.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhoulong.xyz/Article/details/gtcyfdapdp.html

TS:   s === [...s].reverse().join("")
来源：http://dali.aizwys.cn/Article/details/gtsogfjeet.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.chenjidiqi.icu/Article/details/gtdlqsuqgy.html

Go:   // 双指针从两端比较
来源：http://dali.cqqwz.cn/Article/details/gtfpadwhqp.html

Ruby: s == s.reverse
来源：http://dali.mhx1999.top/Article/details/gteuyhapbw.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.jqgufenzy.top/Article/details/gtmchvwenu.html

[N07] 两数之和（返回下标）
来源：http://dali.yvedp.cn/Article/details/gtkrgqidjn.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.xuetiantiany.cn/Article/details/gtlvlowvvq.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.sufxvd.cn/Article/details/gtdblrmjdr.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.tanke756.top/Article/details/gtvikpytrs.html

TS:   // 手写 Map<string, number>
来源：http://dali.shangyingyoupin.top/Article/details/gtvhujqqmk.html

Java: // 手写 HashMap
来源：http://dali.zhongyouzk.top/Article/details/gtebxpygct.html

Go:   // 手写 map[int]int
来源：http://dali.yangfankeji.com/Article/details/gtepfwrwws.html

Ruby: // 手写 Hash
来源：http://dali.sufxvd.cn/Article/details/gtxoajqpcj.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhongyouzk.top/Article/details/gtuqyovvze.html

[N08] 生成全排列
来源：http://dali.zhengqikj.top/Article/details/gtchlkbtbc.html

Py:   itertools.permutations(arr)
来源：http://dali.chenzaomai.com/Article/details/gtarazjlhv.html

PHP:  // 手写递归交换
来源：http://dali.wangdashe.top/Article/details/gtdzuzqlct.html

JS:   // 手写回溯递归
来源：http://dali.yanxiufei.cn/Article/details/gtdbwvcofz.html

TS:   // 手写回溯递归
来源：http://dali.9152youxi.cn/Article/details/gteduzxcjc.html

Java: // 手写回溯递归
来源：http://dali.shuidangran.top/Article/details/gttbbzpldj.html

Go:   // 手写回溯递归
来源：http://dali.yonumen.top/Article/details/gtsikaiqbd.html

Ruby: arr.permutation.to_a
来源：http://dali.dianchejie.cn/Article/details/gtfmkcjpqs.html

C#:   // 手写回溯递归
来源：http://dali.yuanzhike.top/Article/details/gtzzachklj.html

[N09] 栈与队列
来源：http://dali.feifeiyinyue.top/Article/details/gtlxutgsyh.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.aibaodan.cn/Article/details/gtpbrunezm.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.chenjidiqi.icu/Article/details/gtfdndiksg.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.guannengcc.top/Article/details/gtbkgxlqmh.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.yuanzhike.top/Article/details/gttpqpdzqh.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.shanyushiyangtech.top/Article/details/gtcokkwrfe.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.jlsjyb.cn/Article/details/gtwwufuogf.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.chenlongwang.top/Article/details/gtpmealans.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.aizwys.cn/Article/details/gtvdjgdbfo.html

[N10] 链表节点定义
来源：http://dali.jiagoushi.top/Article/details/gtflhaltua.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.xinyue.icu/Article/details/gtbtduyxwx.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.chenjidiqi.icu/Article/details/gtxoaejyeq.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.nanxuanxn.top/Article/details/gtbtmgqtih.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.yonumen.top/Article/details/gthsvtokum.html

Java: class Node { int v; Node next; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyanubzcv.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.ydzc1.top/Article/details/gtgpankkco.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.jinqigufen.top/Article/details/gtxibmcoyy.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.smart0.xyz/Article/details/gthdsacbvl.html

[N11] 二叉树中序遍历
来源：http://dali.shzxlz.cn/Article/details/gthvekerll.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.cashguo.top/Article/details/gtjbjecfta.html

PHP:  // 手写递归函数
来源：http://dali.wangshuangyany.cn/Article/details/gtznsdlcay.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnxtkqsel.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.chenzaomai.com/Article/details/gtzctprwvl.html

Java: // 手写递归
来源：http://dali.tian-w.cn/Article/details/gtxkevmgbg.html

Go:   // 手写递归
来源：http://dali.fzhhl.top/Article/details/gtoujmgclp.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.hnxiangtu.top/Article/details/gtuitxpyxa.html

C#:   // 手写递归
来源：http://dali.316326.xyz/Article/details/gteyjmwxwd.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.wangdashe.top/Article/details/gtyxvwkztb.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gtghlilhco.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.shangyingyoupin.top/Article/details/gtdrupqtxk.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yj20258888.top/Article/details/gtocpqpjfe.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.fzhhl.top/Article/details/gtlyofalbs.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.hnxiangtu.top/Article/details/gtzhxfmffb.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.pengpengdd.cyou/Article/details/gtdisqscqz.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.andypj.xyz/Article/details/gtraicqhgb.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.cheryme.top/Article/details/gtqnfcbpnf.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtoehlnkiv.html

O. 并发与异步
来源：http://dali.sxryk.cn/Article/details/gtsiapmpsb.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtavtzoyfd.html

[O01] 启动一个线程
来源：http://dali.andypj.xyz/Article/details/gtpuirvjzd.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.ydzc1.top/Article/details/gtuvbjxeci.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.sweek.top/Article/details/gtyrcdfror.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.yonumen.top/Article/details/gtadsqijrh.html

TS:   // 同 JS
来源：http://dali.vqdsnc.cn/Article/details/gtmklhnzrc.html

Java: new Thread(() -> f()).start()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtorbjugkg.html

Go:   go f()
来源：http://dali.bjfxy.top/Article/details/gtnqeywzbb.html

Ruby: Thread.new { f }
来源：http://dali.tian-w.cn/Article/details/gtmeibxjkf.html

C#:   Task.Run(() => F());
来源：http://dali.ydzc1.top/Article/details/gtodfzywuk.html

[O02] 使用线程池
来源：http://dali.ybcxt.top/Article/details/gttzpingjw.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.andypj.xyz/Article/details/gtpodfxqdv.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.gogol.net.cn/Article/details/gthklzayug.html

JS:   // worker_threads 线程池
来源：http://dali.xziqi.cn/Article/details/gtmhsxkfbt.html

TS:   // worker_threads 线程池
来源：http://dali.yj202588.top/Article/details/gtdvajebme.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhoulong.xyz/Article/details/gtnjelaraj.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.dianchejie.cn/Article/details/gtxdllgsjv.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.tanke756.top/Article/details/gtwaglzmbf.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.xuetiantiany.cn/Article/details/gtwudxcltl.html

[O03] 加锁保护共享数据
来源：http://dali.shuidangran.top/Article/details/gthwqxanvs.html

Py:   with lock: shared += 1
来源：http://dali.hysaishi.cn/Article/details/gtubdsanzf.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.jqgufenzy.top/Article/details/gtzcayuraz.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.xziqi.cn/Article/details/gtbqlectxh.html

TS:   // 同 JS
来源：http://dali.vqdsnc.cn/Article/details/gtvijtsbcl.html

Java: synchronized (this) { shared++; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjcnjsiji.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.aibaodan.cn/Article/details/gtgyabqhxi.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.0kj1m.cn/Article/details/gtgmdujmly.html

C#:   lock (gate) { shared++; }
来源：http://dali.yj20258888.top/Article/details/gtkhjtcqmr.html

[O04] 定义异步函数并等待
来源：http://dali.shangyingyoupin.top/Article/details/gtraekpwyl.html

Py:   async def f():⏎    await g()
来源：http://dali.aizwys.cn/Article/details/gtuzbjbfnh.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.yongpay.top/Article/details/gtbmjlluoh.html

JS:   async function f() { await g(); }
来源：http://dali.nwbrower.top/Article/details/gtbigearof.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.wangshuangyany.cn/Article/details/gtffujfmrb.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.ydzc1.top/Article/details/gtjzcynunq.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.jyoumei.cn/Article/details/gtpjwkralj.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.nwbrower.top/Article/details/gtrngjtuii.html

C#:   async Task F() { await G(); }
来源：http://dali.sxryk.cn/Article/details/gtzuxrfuaf.html

[O05] 并发执行并等待全部完成
来源：http://dali.jiagoushi.top/Article/details/gtkoqlongm.html

Py:   asyncio.gather(*tasks)
来源：http://dali.shuidangran.top/Article/details/gtmcikpjrd.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhiwuduotai.top/Article/details/gtdvaqjtxi.html

JS:   await Promise.all(tasks)
来源：http://dali.gotoacloud.top/Article/details/gtylydxxxv.html

TS:   await Promise.all(tasks)
来源：http://dali.xziqi.cn/Article/details/gtobhyhdzd.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.yj20258888.top/Article/details/gtsiqlagea.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.fengsongda.top/Article/details/gttpaoyoub.html

Ruby: threads.map(&:join)
来源：http://dali.hysaishi.cn/Article/details/gtfzvkzbcu.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.daxiang520.top/Article/details/gtvoupuphm.html

[O06] 使用进程池
来源：http://dali.zhongyouzk.top/Article/details/gtivlseykg.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.yj202588.top/Article/details/gtqpksnvca.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.hfpthk.cn/Article/details/gtntttbvit.html

JS:   // child_process / cluster 模块
来源：http://dali.xuetiantiany.cn/Article/details/gtvucjcnyv.html

TS:   // child_process / cluster 模块
来源：http://dali.zhoulong.xyz/Article/details/gtyhdbzenh.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.jinqigufen.top/Article/details/gtzxphrjxf.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.yvedp.cn/Article/details/gtbclnpqhj.html

Ruby: // fork 块
来源：http://dali.fengsongda.top/Article/details/gtwrrsooxc.html

C#:   Parallel.For
来源：http://dali.dashuyun.cn/Article/details/gtsundndiu.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtytkhutmr.html

P. 常用工具函数
来源：http://dali.yj20258.top/Article/details/gtqslvxlsv.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtmoxcfjvk.html

[P01] 生成 UUID
来源：http://dali.guowangkeji.top/Article/details/gthviriczb.html

Py:   str(uuid.uuid4())
来源：http://dali.yuxming.cn/Article/details/gtddqciasn.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zdqjudy.top/Article/details/gtblwwuunt.html

JS:   crypto.randomUUID()
来源：http://dali.hammf.cn/Article/details/gtavonirdh.html

TS:   crypto.randomUUID()
来源：http://dali.hongshengwenyu.top/Article/details/gtiihriclu.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gtjnilshys.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhixingplan.top/Article/details/gtxzfftukp.html

Ruby: SecureRandom.uuid
来源：http://dali.yuxming.cn/Article/details/gtpcbgmqfl.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhiwuduotai.top/Article/details/gtojrahifh.html

[P02] MD5 / SHA256 摘要
来源：http://dali.ehwqpu.com/Article/details/gtnazhlpob.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.zhongyouzk.top/Article/details/gtisoivamy.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.yuanzhike.top/Article/details/gtriynvqpp.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.bjfxy.top/Article/details/gtfrsftikk.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.andypj.xyz/Article/details/gtatccblbi.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.guowangkeji.top/Article/details/gtkwtqvvxn.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zdqjudy.top/Article/details/gtpeqaoelo.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.hfpthk.cn/Article/details/gtgngbmhun.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.bjfxy.top/Article/details/gtchuapztl.html

[P03] 生成短随机字符串
来源：http://dali.jqgufenzy.top/Article/details/gthmsnpysn.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.dashuyun.cn/Article/details/gtdpapaovv.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.tian-w.cn/Article/details/gtquemgrep.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.pengpengdd.cyou/Article/details/gtzslnypqt.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhixingplan.top/Article/details/gtjgqqhshj.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.daria6918.cn/Article/details/gtlveezumf.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.fengsongda.top/Article/details/gtiqtqodoq.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.hnxiangtu.top/Article/details/gtdxjdzxdq.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.fengsongda.top/Article/details/gtwetvpdqt.html

[P04] 求长度
来源：http://dali.yongpay.top/Article/details/gtcaikkuei.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.xuetiantiany.cn/Article/details/gtgikrmcxi.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yj202588.top/Article/details/gteqyyuhva.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.nwbrower.top/Article/details/gturuaemwz.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.hfpthk.cn/Article/details/gtnfhceliu.html

Java: list.size();  map.size();  s.length()
来源：http://dali.jqgufenzy.top/Article/details/gtflcbpdwv.html

Go:   len(arr);  len(m)
来源：http://dali.hnxiangtu.top/Article/details/gtijpmuiap.html

Ruby: x.length;  x.size
来源：http://dali.jyoumei.cn/Article/details/gtngijwvjy.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.mhx1999.top/Article/details/gtdxpnmmri.html

[P05] 判断两个对象内容是否相等
来源：http://dali.jinqigufen.top/Article/details/gtwffmzlsr.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.hnqzz.top/Article/details/gtxpzpkjtb.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.aibaodan.cn/Article/details/gtboontwxy.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.ppjwa.cn/Article/details/gtdmohabsg.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.aibaodan.cn/Article/details/gtbasewqre.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.ehwqpu.com/Article/details/gttqjvamwn.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.cucudq.cn/Article/details/gtiodmrujq.html

Ruby: a == b
来源：http://dali.sweek.top/Article/details/gtefzpalir.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.shangyingyoupin.top/Article/details/gteiwxwcrm.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.316326.xyz/Article/details/gtmqbqzzzq.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.aibaodan.cn/Article/details/gtqavryshk.html

PHP:  if (empty($x)) {}
来源：http://dali.redwolf501.top/Article/details/gtckxgxrpo.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.bjfxy.top/Article/details/gtvdtshbhb.html

TS:   if (x == null) {}
来源：http://dali.shuidangran.top/Article/details/gtdxwazdtv.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.shzxlz.cn/Article/details/gtelgibxpi.html

Go:   if x == nil {}
来源：http://dali.ehwqpu.com/Article/details/gtuamgedqm.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.yuanzhike.top/Article/details/gttzmraodz.html

C#:   if (x is null) {}
来源：http://dali.jqgufenzy.top/Article/details/gtrvgtpwao.html

[P07] 防抖与节流
来源：http://dali.ehwqpu.com/Article/details/gtgbwiwlpk.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.nanxinkj.top/Article/details/gtqwniepzm.html

PHP:  // 手写时间戳比较
来源：http://dali.jinqigufen.top/Article/details/gtkozyezqj.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jlsjyb.cn/Article/details/gtloserxou.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yj20258.top/Article/details/gtlpkxxaif.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.mhx1999.top/Article/details/gtoucohnjq.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.gzhubu.top/Article/details/gtmoifycco.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.hammf.cn/Article/details/gtshlcfkmg.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.hongshengwenyu.top/Article/details/gtbcfleplf.html

[P08] 处理浮点精度问题
来源：http://dali.gogol.net.cn/Article/details/gtbndcsiao.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.dianchejie.cn/Article/details/gtfprtsrln.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.nwbrower.top/Article/details/gtqhalwpld.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.tianlin.xyz/Article/details/gtxodhshhf.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.hammf.cn/Article/details/gtjqsaeejp.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.hnxiangtu.top/Article/details/gtwanpvrzj.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.ivvv.top/Article/details/gtvxkonjki.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.tian-w.cn/Article/details/gtwmuqzioq.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.yj20258.top/Article/details/gtpzdtkvut.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtleajfbzg.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.jyoumei.cn/Article/details/gtrzrgocbc.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gttlidoelx.html

[Q01] 创建表
来源：http://dali.daria6918.cn/Article/details/gtmsgdxhfe.html

CREATE TABLE users (
来源：http://dali.jqgfzy.top/Article/details/gtdymsqfrp.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.tanke756.top/Article/details/gtlebjyebb.html

name VARCHAR(50) NOT NULL,
来源：http://dali.yueranfly.top/Article/details/gtkwxcrewr.html

email VARCHAR(100) UNIQUE,
来源：http://dali.fengsongda.top/Article/details/gtmmrrribv.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.daria6918.cn/Article/details/gtolmuauou.html

);
来源：http://dali.cdnleiting.top/Article/details/gthuvbqhvq.html

[Q02] 创建带外键的表
来源：http://dali.dashuyun.cn/Article/details/gtjlkzqbyl.html

CREATE TABLE orders (
来源：http://dali.fengsongda.top/Article/details/gtyyfatxgb.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yj20258888.top/Article/details/gtjyhtyakz.html

user_id INT NOT NULL,
来源：http://dali.yonumen.top/Article/details/gthokjgkem.html

amount DECIMAL(10, 2),
来源：http://dali.pycfn.com/Article/details/gtadzncaow.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.0kj1m.cn/Article/details/gtrwwkhxeq.html

);
来源：http://dali.nwbrower.top/Article/details/gtqckvpobm.html

[Q03] 增加列
来源：http://dali.jyoumei.cn/Article/details/gthglnofzo.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.wangdashe.top/Article/details/gtkdtiwugn.html

[Q04] 修改列类型
来源：http://dali.9152youxi.cn/Article/details/gtbswpdmmu.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.bjfxy.top/Article/details/gtulrjttvq.html

[Q05] 重命名列
来源：http://dali.yanxiufei.cn/Article/details/gtqqifezic.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkvkinvkb.html

[Q06] 删除列
来源：http://dali.nanxinkj.top/Article/details/gtkwapgjot.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.jlsjyb.cn/Article/details/gtzibdbrta.html

[Q07] 删除表
来源：http://dali.yj20258.top/Article/details/gtunhilfwl.html

DROP TABLE IF EXISTS orders;
来源：http://dali.hnxiangtu.top/Article/details/gtqmhinhor.html

[Q08] 创建普通索引
来源：http://dali.smart0.xyz/Article/details/gtogcfdtbi.html

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.jlsjyb.cn/Article/details/gtfrmsjjqw.html

[Q09] 创建唯一索引
来源：http://dali.svipenyu.cn/Article/details/gttjfznlme.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.nanxuanxn.top/Article/details/gtawrhearw.html

[Q10] 插入单行
来源：http://dali.hysaishi.cn/Article/details/gtgacocyfw.html


<!-- 参考信息 -->