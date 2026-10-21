代发 wailian999

Ruby: exit 1
来源：http://dali.gzhubu.top/Article/details/gtsbanwipc.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.yongpay.top/Article/details/gtpcttgbyz.html

[M06] 向标准错误输出
来源：http://dali.gotoacloud.top/Article/details/gtqmwtelvn.html

Py:   print("err", file=sys.stderr)
来源：http://dali.sysykeji.top/Article/details/gthpfyhefy.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.9152youxi.cn/Article/details/gtdydonluj.html

JS:   console.error("err")
来源：http://dali.ydzc1.top/Article/details/gtjhyfmwvl.html

TS:   console.error("err")
来源：http://dali.sweek.top/Article/details/gtsxqryotj.html

Java: System.err.println("err")
来源：http://dali.jyoumei.cn/Article/details/gtighhdpyv.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.haohaochexian.top/Article/details/gtgglsumya.html

Ruby: warn "err"
来源：http://dali.xinyue.icu/Article/details/gtildyavjz.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.tianlin.xyz/Article/details/gtxrftjakx.html

[M07] 判断是否为主入口
来源：http://dali.hnxiangtu.top/Article/details/gtactylmhi.html

Py:   if __name__ == "__main__":
来源：http://dali.iojbl.cn/Article/details/gttrsmhrab.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.yj202588.top/Article/details/gtwjuxlxoi.html

JS:   require.main === module
来源：http://dali.cqqwz.cn/Article/details/gtbhvctxal.html

TS:   require.main === module
来源：http://dali.yuxming.cn/Article/details/gtjxiremss.html

Java: public static void main(String[] args)
来源：http://dali.jinghuilouyu.cn/Article/details/gtorngotxe.html

Go:   func main()
来源：http://dali.hongshengwenyu.top/Article/details/gtwjluybha.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.yuxming.cn/Article/details/gtyydgyrod.html

C#:   static void Main(string[] args)
来源：http://dali.xylfe.cn/Article/details/gtoteledfw.html

[M08] 获取系统与运行时信息
来源：http://dali.jiagoushi.top/Article/details/gtepbnhlny.html

Py:   platform.system();  platform.python_version()
来源：http://dali.fzhhl.top/Article/details/gtzgfktrkk.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.shangyingyoupin.top/Article/details/gtwlbgopvd.html

JS:   process.platform;  process.version
来源：http://dali.jinghuilouyu.cn/Article/details/gtwcbgcqpo.html

TS:   process.platform;  process.version
来源：http://dali.pycfn.com/Article/details/gthqegzrvu.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.jinqigfzy.top/Article/details/gtxfovutpd.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.birdmap.top/Article/details/gtljkjmpab.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.bjfxy.top/Article/details/gtdkuyxlmy.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsdwcgorz.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtlzwcxlmp.html

N. 数据结构与算法
来源：http://dali.wangdashe.top/Article/details/gtwtlupawp.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtpvsindqe.html

[N01] 二分查找（有序数组）
来源：http://dali.yongpay.top/Article/details/gtzvpjsntz.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.quarkkingdee.top/Article/details/gtdodrljej.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.xziqi.cn/Article/details/gtfsixqfkz.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.fengsongda.top/Article/details/gtdduawoim.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.xinyue.icu/Article/details/gtvrbxzfxk.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.0kj1m.cn/Article/details/gtopawvpol.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.sysykeji.top/Article/details/gtuvlbfabx.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.yanxiufei.cn/Article/details/gtqjofajif.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.xuetiantiany.cn/Article/details/gthodarfgf.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhongyouzk.top/Article/details/gtycypkora.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yuanzhike.top/Article/details/gtkpcvzuqb.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.yuxming.cn/Article/details/gtctyoetou.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zdqjudy.top/Article/details/gtswqnlwvv.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.kuanghao11.cn/Article/details/gtkdnhlcvv.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.hnqzz.top/Article/details/gtqucfsiej.html

Go:   slices.Sort(arr)
来源：http://dali.xziqi.cn/Article/details/gtaeutgvhj.html

Ruby: arr.sort
来源：http://dali.xziqi.cn/Article/details/gtixgnpwzz.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.ydzc1.top/Article/details/gtehyjxkho.html

[N03] 快速排序（分治示例）
来源：http://dali.cdnleiting.top/Article/details/gtdgnumazn.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.guannengcc.top/Article/details/gtgssikymx.html

PHP:  // 递归实现，或用 usort
来源：http://dali.jinqigfzy.top/Article/details/gtbuojjudw.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.aizwys.cn/Article/details/gtjaomqjmc.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.ybcxt.top/Article/details/gthehlwfis.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.jiagoushi.top/Article/details/gtihtddena.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.cheryme.top/Article/details/gtzhgmusng.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.jqgufenzy.top/Article/details/gtsmklidne.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrfkprxaa.html

[N04] 斐波那契数列
来源：http://dali.hysaishi.cn/Article/details/gtowzmafkc.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.nanxuanxn.top/Article/details/gtaroptifg.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.quarkkingdee.top/Article/details/gtzfdsfnnm.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.ybcxt.top/Article/details/gtfhihipcd.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.ppjwa.cn/Article/details/gthfqlzdem.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.yuanzhike.top/Article/details/gtsbdzaept.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.9152youxi.cn/Article/details/gtgxknqpmi.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.yangfankeji.com/Article/details/gtqudnimur.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.chenjidiqi.icu/Article/details/gtdiesdgbx.html

[N05] 最大公约数
来源：http://dali.yuxming.cn/Article/details/gtiihbjwcs.html

Py:   math.gcd(a, b)
来源：http://dali.nanxinkj.top/Article/details/gtzihyygoz.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.316326.xyz/Article/details/gtqnyytejk.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.ivvv.top/Article/details/gthmtthstv.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.mhx1999.top/Article/details/gtlddluawj.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.yj202588.top/Article/details/gtvosuxshs.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.smart0.xyz/Article/details/gtqnwgitti.html

Ruby: a.gcd(b)
来源：http://dali.hywenlv.cn/Article/details/gtrfaelzfr.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.tanke756.top/Article/details/gtpxaicpwe.html

[N06] 判断回文字符串
来源：http://dali.tian-w.cn/Article/details/gtuufvpbgq.html

Py:   s == s[::-1]
来源：http://dali.zdqjudy.top/Article/details/gtpvgctndo.html

PHP:  $s === strrev($s);
来源：http://dali.sufxvd.cn/Article/details/gtnpevaipt.html

JS:   s === [...s].reverse().join("")
来源：http://dali.ivvv.top/Article/details/gtynqkmqit.html

TS:   s === [...s].reverse().join("")
来源：http://dali.andypj.xyz/Article/details/gtkxxgdhyz.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.aizwys.cn/Article/details/gtleuswvpv.html

Go:   // 双指针从两端比较
来源：http://dali.aibaodan.cn/Article/details/gtbzqkkbqe.html

Ruby: s == s.reverse
来源：http://dali.nanxuanxn.top/Article/details/gtecjyidso.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.tanke756.top/Article/details/gtxrsgfsni.html

[N07] 两数之和（返回下标）
来源：http://dali.ivvv.top/Article/details/gthbmvqtxu.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.jinghuilouyu.cn/Article/details/gtzzdmhsvk.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.hywenlv.cn/Article/details/gtmqculaws.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.wangshuangyany.cn/Article/details/gtzlmgcgbx.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gtkfpsjtdo.html

Java: // 手写 HashMap
来源：http://dali.andypj.xyz/Article/details/gtvdpkhcdz.html

Go:   // 手写 map[int]int
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdetrgjhe.html

Ruby: // 手写 Hash
来源：http://dali.feifeiyinyue.top/Article/details/gtymwbcknm.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.gotoacloud.top/Article/details/gtxfrlvswu.html

[N08] 生成全排列
来源：http://dali.cucudq.cn/Article/details/gtmpuacjma.html

Py:   itertools.permutations(arr)
来源：http://dali.zycfv.cn/Article/details/gtlycyagwz.html

PHP:  // 手写递归交换
来源：http://dali.yj20258888.top/Article/details/gttcgoouam.html

JS:   // 手写回溯递归
来源：http://dali.ehwqpu.com/Article/details/gtfmhzwedd.html

TS:   // 手写回溯递归
来源：http://dali.hfpthk.cn/Article/details/gtdjgfvtdq.html

Java: // 手写回溯递归
来源：http://dali.yangfankeji.com/Article/details/gtauwirgso.html

Go:   // 手写回溯递归
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbosdtjkl.html

Ruby: arr.permutation.to_a
来源：http://dali.zhoulong.xyz/Article/details/gtkylzdkwv.html

C#:   // 手写回溯递归
来源：http://dali.0kj1m.cn/Article/details/gtbcsohove.html

[N09] 栈与队列
来源：http://dali.nwbrower.top/Article/details/gtghirfnew.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.svipenyu.cn/Article/details/gtvawxeomh.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.snrcjt.cn/Article/details/gttqnzjrzd.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhixingplan.top/Article/details/gtozbenlhp.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.haohaochexian.top/Article/details/gthoqskoww.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.cashguo.top/Article/details/gtszmjklyl.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.havefunace.top/Article/details/gtypprfljs.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.hysaishi.cn/Article/details/gtwevaahrc.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.andypj.xyz/Article/details/gtwajqbtpe.html

[N10] 链表节点定义
来源：http://dali.hywenlv.cn/Article/details/gtrwdrlsdr.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.nanxinkj.top/Article/details/gtqrruiedf.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.0kj1m.cn/Article/details/gtpmbydonn.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfwmwyifi.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.sysykeji.top/Article/details/gtidizatff.html

Java: class Node { int v; Node next; }
来源：http://dali.c1oappe.top/Article/details/gtvlzdtopy.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.yuanzhike.top/Article/details/gttbgjolss.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhongyouzk.top/Article/details/gtqelmspea.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zycfv.cn/Article/details/gtalipxbzt.html

[N11] 二叉树中序遍历
来源：http://dali.yangfankeji.com/Article/details/gtwzvhscjv.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrrpclazu.html

PHP:  // 手写递归函数
来源：http://dali.fzhhl.top/Article/details/gtxerdzpow.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zycfv.cn/Article/details/gtbdglnvpp.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.andypj.xyz/Article/details/gthsuqnxvq.html

Java: // 手写递归
来源：http://dali.0kj1m.cn/Article/details/gtqybhtzsd.html

Go:   // 手写递归
来源：http://dali.cashguo.top/Article/details/gtuenaaybf.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqinceost.html

C#:   // 手写递归
来源：http://dali.jinghuilouyu.cn/Article/details/gtpmfyibxo.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.haohaochexian.top/Article/details/gtxmhjnbjf.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.haohaochexian.top/Article/details/gtbalkxwvc.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.aizwys.cn/Article/details/gtdidviiuj.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.dashuyun.cn/Article/details/gtiawymilr.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.fengsongda.top/Article/details/gtujjzqsut.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yueranfly.top/Article/details/gtfqyqnoyn.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhongyouzk.top/Article/details/gtbnnueisi.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.ybcxt.top/Article/details/gtnpuzerns.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yuxming.cn/Article/details/gtnxkunlmf.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtfiqhsrzi.html

O. 并发与异步
来源：http://dali.mhx1999.top/Article/details/gtlenoebbx.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtrixqpvwa.html

[O01] 启动一个线程
来源：http://dali.yuanzhike.top/Article/details/gtjdqqeqra.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.snrcjt.cn/Article/details/gthgsbrndp.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.nanxuanxn.top/Article/details/gtnricvmgo.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.nwbrower.top/Article/details/gtvxbpttid.html

TS:   // 同 JS
来源：http://dali.yj20258.top/Article/details/gtifuqanfd.html

Java: new Thread(() -> f()).start()
来源：http://dali.ehwqpu.com/Article/details/gtmzkbewzc.html

Go:   go f()
来源：http://dali.fengsongda.top/Article/details/gtamooqkcc.html

Ruby: Thread.new { f }
来源：http://dali.jinqigufen.top/Article/details/gtnjzhtudb.html

C#:   Task.Run(() => F());
来源：http://dali.shangyingyoupin.top/Article/details/gtlyelonaj.html

[O02] 使用线程池
来源：http://dali.zycfv.cn/Article/details/gtbfhelcqd.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.hywenlv.cn/Article/details/gtpetfqvil.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.nwbrower.top/Article/details/gtomiiqwkw.html

JS:   // worker_threads 线程池
来源：http://dali.xinyue.icu/Article/details/gtfcfaqwvq.html

TS:   // worker_threads 线程池
来源：http://dali.yueranfly.top/Article/details/gtdkxtextp.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.sweek.top/Article/details/gtrudzxjfc.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.yj202588.top/Article/details/gtcpsjtlxu.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.yj20258888.top/Article/details/gtsvwprqen.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.tian-w.cn/Article/details/gtcrnpbxjz.html

[O03] 加锁保护共享数据
来源：http://dali.hongshengwenyu.top/Article/details/gtdlpleenk.html

Py:   with lock: shared += 1
来源：http://dali.pycfn.com/Article/details/gtsklgefbp.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.jinqigfzy.top/Article/details/gtevkttqej.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.guannengcc.top/Article/details/gtpawhdkwy.html

TS:   // 同 JS
来源：http://dali.shanyushiyangtech.top/Article/details/gtyvxdctky.html

Java: synchronized (this) { shared++; }
来源：http://dali.jlsjyb.cn/Article/details/gtgpaetcji.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.gotoacloud.top/Article/details/gtmmkyxkpi.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.nanxuanxn.top/Article/details/gtywoycnyn.html

C#:   lock (gate) { shared++; }
来源：http://dali.jlsjyb.cn/Article/details/gtphtujcdd.html

[O04] 定义异步函数并等待
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpyvzhtfm.html

Py:   async def f():⏎    await g()
来源：http://dali.havefunace.top/Article/details/gtnguwybcl.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.xuanzx.com/Article/details/gtwkksiauq.html

JS:   async function f() { await g(); }
来源：http://dali.haohaochexian.top/Article/details/gtnkykmcef.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzjrfwual.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.jianghu66.top/Article/details/gtftmcoknh.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.pycfn.com/Article/details/gtnsdyntya.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.gotoacloud.top/Article/details/gtyvxqtdlo.html

C#:   async Task F() { await G(); }
来源：http://dali.hongshengwenyu.top/Article/details/gtjcmkkxwj.html

[O05] 并发执行并等待全部完成
来源：http://dali.dianchejie.cn/Article/details/gtkkexkfpd.html

Py:   asyncio.gather(*tasks)
来源：http://dali.havefunace.top/Article/details/gtiryyvelu.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.svipenyu.cn/Article/details/gtkclhblkx.html

JS:   await Promise.all(tasks)
来源：http://dali.nwbrower.top/Article/details/gtqelfmedq.html

TS:   await Promise.all(tasks)
来源：http://dali.c1oappe.top/Article/details/gtapfmkjub.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.chenlongwang.top/Article/details/gtgsxeiaeb.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.quarkkingdee.top/Article/details/gtwfxujkpp.html

Ruby: threads.map(&:join)
来源：http://dali.xuetiantiany.cn/Article/details/gtjcmfdaih.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gtxzmemsif.html

[O06] 使用进程池
来源：http://dali.xuetiantiany.cn/Article/details/gtlxhxnzbb.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyujjjrpa.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrzsmsfoj.html

JS:   // child_process / cluster 模块
来源：http://dali.svipenyu.cn/Article/details/gtltokqfkk.html

TS:   // child_process / cluster 模块
来源：http://dali.cashguo.top/Article/details/gtumwvggsx.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.chenjidiqi.icu/Article/details/gttymhkwaa.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdbrqujkt.html

Ruby: // fork 块
来源：http://dali.cdnleiting.top/Article/details/gtbmzejukc.html

C#:   Parallel.For
来源：http://dali.wangshuangyany.cn/Article/details/gtafomvrds.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gthydumsqt.html

P. 常用工具函数
来源：http://dali.pengpengdd.cyou/Article/details/gtyzbppynb.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtywyrsmxc.html

[P01] 生成 UUID
来源：http://dali.pycfn.com/Article/details/gtiauyeytb.html

Py:   str(uuid.uuid4())
来源：http://dali.cucudq.cn/Article/details/gttbiutjcm.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.cashguo.top/Article/details/gtbylouqrs.html

JS:   crypto.randomUUID()
来源：http://dali.hammf.cn/Article/details/gtojgstojl.html

TS:   crypto.randomUUID()
来源：http://dali.yj20258.top/Article/details/gtvhrjvvvo.html

Java: UUID.randomUUID().toString()
来源：http://dali.gogol.net.cn/Article/details/gtvolnavfg.html

Go:   // 用 github.com/google/uuid
来源：http://dali.gzhubu.top/Article/details/gtmdahztgn.html

Ruby: SecureRandom.uuid
来源：http://dali.wangshuangyany.cn/Article/details/gtznjzlmwy.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.cashguo.top/Article/details/gttwyaxwim.html

[P02] MD5 / SHA256 摘要
来源：http://dali.hysaishi.cn/Article/details/gtjslhbtil.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.cashguo.top/Article/details/gtohpidzdn.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfeoxfril.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.jianghu66.top/Article/details/gtnlpdfruo.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.cdnleiting.top/Article/details/gtnfywlkbp.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.0kj1m.cn/Article/details/gtjbittrmn.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhiwuduotai.top/Article/details/gttbfqbyqq.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.yonumen.top/Article/details/gtpnufrsdm.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.yj202588.top/Article/details/gtjmczbrjh.html

[P03] 生成短随机字符串
来源：http://dali.tanke756.top/Article/details/gtdulrbitp.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.quarkkingdee.top/Article/details/gtonsgyvxt.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.hongshengwenyu.top/Article/details/gtcilptnpn.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhiwuduotai.top/Article/details/gtswhkjenb.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yangfankeji.com/Article/details/gtqhcbccbp.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.hnxiangtu.top/Article/details/gtoofcvixq.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zdqjudy.top/Article/details/gtanmmeqwp.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.gzhubu.top/Article/details/gtcadgcyog.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.haohaochexian.top/Article/details/gtsaksbjdn.html

[P04] 求长度
来源：http://dali.9152youxi.cn/Article/details/gtjhoryjqg.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.mhx1999.top/Article/details/gtmuuaknvy.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.daxiang520.top/Article/details/gtqlvmevpx.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yangfankeji.com/Article/details/gtekerlgyl.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.dianchejie.cn/Article/details/gthoxyctly.html

Java: list.size();  map.size();  s.length()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdngopwyg.html

Go:   len(arr);  len(m)
来源：http://dali.snrcjt.cn/Article/details/gterxspcxa.html

Ruby: x.length;  x.size
来源：http://dali.jinqigfzy.top/Article/details/gtoslaniqi.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.cqqwz.cn/Article/details/gtfvjippvs.html

[P05] 判断两个对象内容是否相等
来源：http://dali.aibaodan.cn/Article/details/gtettuueqx.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.cheryme.top/Article/details/gtnylzqagi.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.shangyingyoupin.top/Article/details/gtmcapajtg.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.c1oappe.top/Article/details/gtekjrwthr.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.pengpengdd.cyou/Article/details/gtlssjtbbx.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.sysykeji.top/Article/details/gtmgfxyqpv.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.gotoacloud.top/Article/details/gtqoqdypnf.html

Ruby: a == b
来源：http://dali.zycfv.cn/Article/details/gtcdjxbfgy.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.gogol.net.cn/Article/details/gthzkxysjh.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.snrcjt.cn/Article/details/gteypyzsvs.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.aibaodan.cn/Article/details/gtltdvblch.html

PHP:  if (empty($x)) {}
来源：http://dali.shuidangran.top/Article/details/gtnwtpjbak.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.zhengqikj.top/Article/details/gtjjbrdudq.html

TS:   if (x == null) {}
来源：http://dali.jqgfzy.top/Article/details/gtoavicfvj.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zdqjudy.top/Article/details/gtbsagjoun.html

Go:   if x == nil {}
来源：http://dali.0kj1m.cn/Article/details/gtzitcueqr.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.sxryk.cn/Article/details/gtefspyvcn.html

C#:   if (x is null) {}
来源：http://dali.gotoacloud.top/Article/details/gtubgmoruv.html

[P07] 防抖与节流
来源：http://dali.jyoumei.cn/Article/details/gtenmvinzu.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.jyoumei.cn/Article/details/gtrceqpugv.html

PHP:  // 手写时间戳比较
来源：http://dali.sxryk.cn/Article/details/gtlrpxffmk.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yj20258888.top/Article/details/gtzrzjwunb.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.gotoacloud.top/Article/details/gthmzpedgq.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.smart0.xyz/Article/details/gtnkdtrppr.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.wangdashe.top/Article/details/gtwwkqehde.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.yj20258.top/Article/details/gtovtjnmcf.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.quarkkingdee.top/Article/details/gtymopqcyg.html

[P08] 处理浮点精度问题
来源：http://dali.9152youxi.cn/Article/details/gtssgvpfva.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.zycfv.cn/Article/details/gtzucfuhee.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.shuidangran.top/Article/details/gtkjqvdcjx.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.sysykeji.top/Article/details/gtqfcutchw.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.dashuyun.cn/Article/details/gtjvgdcleu.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.yangfankeji.com/Article/details/gtngslgshv.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.jyoumei.cn/Article/details/gtsxmlufim.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.fengsongda.top/Article/details/gtqzanfmql.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.jyoumei.cn/Article/details/gtsmbxavgo.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtpsxcpufx.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.bjfxy.top/Article/details/gtgxlekvgk.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gthblrhilb.html

[Q01] 创建表
来源：http://dali.gzhubu.top/Article/details/gtlvliqapc.html

CREATE TABLE users (
来源：http://dali.xziqi.cn/Article/details/gtcaopllfg.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.ppjwa.cn/Article/details/gtaxsxcqbf.html

name VARCHAR(50) NOT NULL,
来源：http://dali.chenlongwang.top/Article/details/gtxfszxsqt.html

email VARCHAR(100) UNIQUE,
来源：http://dali.shuidangran.top/Article/details/gtsfyoipku.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.chenjidiqi.icu/Article/details/gtwxokzwlo.html

);
来源：http://dali.redwolf501.top/Article/details/gtopuvnbbf.html

[Q02] 创建带外键的表
来源：http://dali.nwbrower.top/Article/details/gtpnhmwxwl.html

CREATE TABLE orders (
来源：http://dali.gogol.net.cn/Article/details/gtcesckosa.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zycfv.cn/Article/details/gtcqcevkry.html

user_id INT NOT NULL,
来源：http://dali.9152youxi.cn/Article/details/gthvtqdfdv.html

amount DECIMAL(10, 2),
来源：http://dali.jinghuilouyu.cn/Article/details/gttiljciks.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.meibo888.top/Article/details/gtgymstoqy.html

);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtimemwqrt.html

[Q03] 增加列
来源：http://dali.xuanzx.com/Article/details/gtuevmcakp.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.hammf.cn/Article/details/gtjfovlrwg.html

[Q04] 修改列类型
来源：http://dali.xuanzx.com/Article/details/gthyzmgmzn.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.cqqwz.cn/Article/details/gtqzsphsld.html

[Q05] 重命名列
来源：http://dali.jyoumei.cn/Article/details/gtmedpsqhc.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.wangshuangyany.cn/Article/details/gtzkcvthnr.html

[Q06] 删除列
来源：http://dali.smart0.xyz/Article/details/gthcxydbac.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtobgcjtzo.html

[Q07] 删除表
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkkskcwgd.html

DROP TABLE IF EXISTS orders;
来源：http://dali.wangshuangyany.cn/Article/details/gtisuscrbe.html

[Q08] 创建普通索引
来源：http://dali.chenlongwang.top/Article/details/gtidasxjnm.html


<!-- 参考信息 -->