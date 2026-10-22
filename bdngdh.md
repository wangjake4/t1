代发 wailian999

Ruby: exit 1
来源：http://dali.zhaomingkeji.xyz/Article/details/gtshefuxei.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.tianlin.xyz/Article/details/gtwusmzqvk.html

[M06] 向标准错误输出
来源：http://dali.9152youxi.cn/Article/details/gtwfgmenpx.html

Py:   print("err", file=sys.stderr)
来源：http://dali.cdnleiting.top/Article/details/gtcrxnwjgw.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.sweek.top/Article/details/gttwnbuenc.html

JS:   console.error("err")
来源：http://dali.nanxinkj.top/Article/details/gtkzmvbpxv.html

TS:   console.error("err")
来源：http://dali.kuanghao11.cn/Article/details/gtugmxukdo.html

Java: System.err.println("err")
来源：http://dali.yj20258888.top/Article/details/gtwakuycjm.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhiwuduotai.top/Article/details/gtxeolfiky.html

Ruby: warn "err"
来源：http://dali.meibo888.top/Article/details/gtlxergvuo.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.gaohongyu789.top/Article/details/gtfkmobbpz.html

[M07] 判断是否为主入口
来源：http://dali.hammf.cn/Article/details/gtmenexfvm.html

Py:   if __name__ == "__main__":
来源：http://dali.c1oappe.top/Article/details/gtnnizzlui.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.snrcjt.cn/Article/details/gtqtmvyatt.html

JS:   require.main === module
来源：http://dali.yuxming.cn/Article/details/gtpxukhwnu.html

TS:   require.main === module
来源：http://dali.hnxiangtu.top/Article/details/gtfrspifjw.html

Java: public static void main(String[] args)
来源：http://dali.xinyue.icu/Article/details/gtfqatjpdb.html

Go:   func main()
来源：http://dali.ehwqpu.com/Article/details/gtlpxzhjxi.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.jinghuilouyu.cn/Article/details/gtbgvqyvns.html

C#:   static void Main(string[] args)
来源：http://dali.jyoumei.cn/Article/details/gtjjeuerxa.html

[M08] 获取系统与运行时信息
来源：http://dali.cdnleiting.top/Article/details/gttvdbjtng.html

Py:   platform.system();  platform.python_version()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfzkgywec.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.iojbl.cn/Article/details/gtyeixkzux.html

JS:   process.platform;  process.version
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjsgqqhrn.html

TS:   process.platform;  process.version
来源：http://dali.ivvv.top/Article/details/gtpboojann.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.havefunace.top/Article/details/gtzsdmjiei.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.guannengcc.top/Article/details/gtbpxuliow.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhoulong.xyz/Article/details/gtmnwsnozn.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.yuxming.cn/Article/details/gthamjjeuf.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtgssnmwpm.html

N. 数据结构与算法
来源：http://dali.hnqzz.top/Article/details/gtufjnpazg.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtqwprebot.html

[N01] 二分查找（有序数组）
来源：http://dali.zycfv.cn/Article/details/gtbuupdcrb.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhengqikj.top/Article/details/gtzlhotdwt.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhoulong.xyz/Article/details/gtvihjpllx.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.cheryme.top/Article/details/gtikbitfaq.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hywenlv.cn/Article/details/gtgxmbtvnm.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.hammf.cn/Article/details/gtlhqyqifh.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.jlsjyb.cn/Article/details/gtwttdvdqs.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.guannengcc.top/Article/details/gtqwoohykx.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.yuxming.cn/Article/details/gtxwzhidjp.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.yj20258888.top/Article/details/gtcliodgeb.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.chenjidiqi.icu/Article/details/gtxwpzfuxx.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhiwuduotai.top/Article/details/gtvnmhwekp.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.nanxinkj.top/Article/details/gtsoscokte.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zycfv.cn/Article/details/gteikrcuzf.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.svipenyu.cn/Article/details/gtxudkggdm.html

Go:   slices.Sort(arr)
来源：http://dali.cashguo.top/Article/details/gtnhjmjvsq.html

Ruby: arr.sort
来源：http://dali.shzxlz.cn/Article/details/gtyyvqlqwt.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.snrcjt.cn/Article/details/gtaqnuxwhf.html

[N03] 快速排序（分治示例）
来源：http://dali.dashuyun.cn/Article/details/gttjlpbztt.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.hywenlv.cn/Article/details/gtsfrrvtkl.html

PHP:  // 递归实现，或用 usort
来源：http://dali.cdnleiting.top/Article/details/gtioiobiqq.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.gzhubu.top/Article/details/gtdraxqtym.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.shangyingyoupin.top/Article/details/gtvmrsxaxm.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gtdstalxrq.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.quarkkingdee.top/Article/details/gtreulzdep.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.yj202588.top/Article/details/gtotinmflh.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.kuanghao11.cn/Article/details/gtzzlmrbim.html

[N04] 斐波那契数列
来源：http://dali.yj20258.top/Article/details/gtcqxqgjay.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.yj20258.top/Article/details/gtrhqiimeg.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.yanxiufei.cn/Article/details/gtrgqxbpfe.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yonumen.top/Article/details/gtishfcaac.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.tanke756.top/Article/details/gtvsdxwpwk.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.sweek.top/Article/details/gtsvrzidwh.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.cucudq.cn/Article/details/gtqzwbbnxa.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.iojbl.cn/Article/details/gtuddwxqsc.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.havefunace.top/Article/details/gtnjnqrnfb.html

[N05] 最大公约数
来源：http://dali.gzhubu.top/Article/details/gtdinpzvkx.html

Py:   math.gcd(a, b)
来源：http://dali.xylfe.cn/Article/details/gtassewafq.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.gzhubu.top/Article/details/gtoeoppjxt.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.pycfn.com/Article/details/gtumnmoltv.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.fengsongda.top/Article/details/gtetrpyzlu.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.daria6918.cn/Article/details/gtknmcakrz.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.hongshengwenyu.top/Article/details/gthvpzimww.html

Ruby: a.gcd(b)
来源：http://dali.redwolf501.top/Article/details/gtcrinpheo.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.chenjidiqi.icu/Article/details/gtkklvpvky.html

[N06] 判断回文字符串
来源：http://dali.jqgfzy.top/Article/details/gtaphibjew.html

Py:   s == s[::-1]
来源：http://dali.nwbrower.top/Article/details/gttuunhhum.html

PHP:  $s === strrev($s);
来源：http://dali.guannengcc.top/Article/details/gtrzcxxrix.html

JS:   s === [...s].reverse().join("")
来源：http://dali.gotoacloud.top/Article/details/gtubjgjgrw.html

TS:   s === [...s].reverse().join("")
来源：http://dali.andypj.xyz/Article/details/gtvrmmdvmn.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.tanke756.top/Article/details/gtmojojseb.html

Go:   // 双指针从两端比较
来源：http://dali.zhixingplan.top/Article/details/gtiuyplyux.html

Ruby: s == s.reverse
来源：http://dali.hywenlv.cn/Article/details/gtuffxwzhp.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.yj20258888.top/Article/details/gtumxjvuxq.html

[N07] 两数之和（返回下标）
来源：http://dali.0kj1m.cn/Article/details/gtabagxyuq.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.chenlongwang.top/Article/details/gtohdrafof.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.yj20258.top/Article/details/gtybmrjbwt.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.aibaodan.cn/Article/details/gtrcsztwjm.html

TS:   // 手写 Map<string, number>
来源：http://dali.xziqi.cn/Article/details/gtbkldetan.html

Java: // 手写 HashMap
来源：http://dali.gaohongyu789.top/Article/details/gtfjcupygj.html

Go:   // 手写 map[int]int
来源：http://dali.wangdashe.top/Article/details/gtbezlsmsp.html

Ruby: // 手写 Hash
来源：http://dali.shuidangran.top/Article/details/gtgpbupaei.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.hnxiangtu.top/Article/details/gtoiiydnof.html

[N08] 生成全排列
来源：http://dali.ivvv.top/Article/details/gtztvqfilj.html

Py:   itertools.permutations(arr)
来源：http://dali.redwolf501.top/Article/details/gteklhadpq.html

PHP:  // 手写递归交换
来源：http://dali.haohaochexian.top/Article/details/gtuhreyjzf.html

JS:   // 手写回溯递归
来源：http://dali.sysykeji.top/Article/details/gtmtrhhyry.html

TS:   // 手写回溯递归
来源：http://dali.jlsjyb.cn/Article/details/gtnfbengho.html

Java: // 手写回溯递归
来源：http://dali.haohaochexian.top/Article/details/gtmfgkobcm.html

Go:   // 手写回溯递归
来源：http://dali.sxryk.cn/Article/details/gtedwtpuwy.html

Ruby: arr.permutation.to_a
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdipdroby.html

C#:   // 手写回溯递归
来源：http://dali.nanxinkj.top/Article/details/gtykdyhcnz.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gtkpenqxwi.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.sweek.top/Article/details/gtwurbdptc.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfaqzzkjt.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.bjfxy.top/Article/details/gtfffmvmpz.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.jinqigufen.top/Article/details/gtnndfuxbj.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.jinqigfzy.top/Article/details/gtziqjpcay.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxceobkjp.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.andypj.xyz/Article/details/gtcrsbqynt.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.nanxinkj.top/Article/details/gtmhbmnkcc.html

[N10] 链表节点定义
来源：http://dali.sweek.top/Article/details/gtbrcokdzi.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwkgdnmbl.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.yangfankeji.com/Article/details/gtdlbmclin.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.hnqzz.top/Article/details/gthllzxrlh.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.ehwqpu.com/Article/details/gtunfsuyco.html

Java: class Node { int v; Node next; }
来源：http://dali.yonumen.top/Article/details/gtjxhbxxgk.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.chenzaomai.com/Article/details/gtwqrypkgn.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.xziqi.cn/Article/details/gtpcazydls.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhengqikj.top/Article/details/gtqjnudovn.html

[N11] 二叉树中序遍历
来源：http://dali.yanxiufei.cn/Article/details/gtdlpoynsr.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.quarkkingdee.top/Article/details/gtzpqqljrz.html

PHP:  // 手写递归函数
来源：http://dali.hywenlv.cn/Article/details/gtlvpfmyvp.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.hywenlv.cn/Article/details/gtyzflryzu.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.aibaodan.cn/Article/details/gtutqijkmv.html

Java: // 手写递归
来源：http://dali.cucudq.cn/Article/details/gtwojhxoen.html

Go:   // 手写递归
来源：http://dali.sxryk.cn/Article/details/gtpkesumhz.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtowhjsrsj.html

C#:   // 手写递归
来源：http://dali.ppjwa.cn/Article/details/gtueboqsqd.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.sxryk.cn/Article/details/gtebnujeqf.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.yueranfly.top/Article/details/gtswspmdoe.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.vqdsnc.cn/Article/details/gtpltwucdz.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jqgufenzy.top/Article/details/gtvpebskyl.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.hysaishi.cn/Article/details/gtmxfsjtox.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.ydzc1.top/Article/details/gtsxeodisq.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.yvedp.cn/Article/details/gtpptdrnib.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.yanxiufei.cn/Article/details/gtawtkqvib.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jlsjyb.cn/Article/details/gthdksammr.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtnpvwxghf.html

O. 并发与异步
来源：http://dali.daria6918.cn/Article/details/gtugqxcizx.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtzkckynhr.html

[O01] 启动一个线程
来源：http://dali.fzhhl.top/Article/details/gtudosbcqt.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.wangdashe.top/Article/details/gtxutsakvr.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.hfpthk.cn/Article/details/gtwjtnlzjm.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhoulong.xyz/Article/details/gtamatydpk.html

TS:   // 同 JS
来源：http://dali.gogol.net.cn/Article/details/gtwxdvwvrx.html

Java: new Thread(() -> f()).start()
来源：http://dali.yueranfly.top/Article/details/gtdfwjdtfw.html

Go:   go f()
来源：http://dali.fzhhl.top/Article/details/gtxrbqjrgi.html

Ruby: Thread.new { f }
来源：http://dali.tian-w.cn/Article/details/gtlsoifdzs.html

C#:   Task.Run(() => F());
来源：http://dali.c1oappe.top/Article/details/gtwirxbypn.html

[O02] 使用线程池
来源：http://dali.quarkkingdee.top/Article/details/gtubrnbdse.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.aibaodan.cn/Article/details/gtegpginvz.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.yueranfly.top/Article/details/gtppvfknww.html

JS:   // worker_threads 线程池
来源：http://dali.yueranfly.top/Article/details/gtwtqeezxe.html

TS:   // worker_threads 线程池
来源：http://dali.dashuyun.cn/Article/details/gtqilioppb.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.yanxiufei.cn/Article/details/gtbhnlibga.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.snrcjt.cn/Article/details/gtztdoocpx.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.dashuyun.cn/Article/details/gtnqnjnfll.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.nanxuanxn.top/Article/details/gtancijwur.html

[O03] 加锁保护共享数据
来源：http://dali.nanxinkj.top/Article/details/gtlhtrgkjh.html

Py:   with lock: shared += 1
来源：http://dali.gaohongyu789.top/Article/details/gtvkeetupf.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.sysykeji.top/Article/details/gtrpovnena.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.havefunace.top/Article/details/gtkyxgtldm.html

TS:   // 同 JS
来源：http://dali.cucudq.cn/Article/details/gtvrxmarmt.html

Java: synchronized (this) { shared++; }
来源：http://dali.ybcxt.top/Article/details/gtvdzkmvvv.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.yanxiufei.cn/Article/details/gtzsgmhqwu.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.smart0.xyz/Article/details/gtzysfdpav.html

C#:   lock (gate) { shared++; }
来源：http://dali.nanxinkj.top/Article/details/gtlaxqpndp.html

[O04] 定义异步函数并等待
来源：http://dali.yj20258.top/Article/details/gtbuvtgagr.html

Py:   async def f():⏎    await g()
来源：http://dali.jqgufenzy.top/Article/details/gtbsqaacms.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.gzhubu.top/Article/details/gtohmjxzcg.html

JS:   async function f() { await g(); }
来源：http://dali.hfpthk.cn/Article/details/gttcdgnxtt.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.dianchejie.cn/Article/details/gtxfwnegev.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.sysykeji.top/Article/details/gtlahjuckn.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.jinghuilouyu.cn/Article/details/gtiwtdxdbu.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.hysaishi.cn/Article/details/gtqugaatlm.html

C#:   async Task F() { await G(); }
来源：http://dali.xuanzx.com/Article/details/gtejkxhzfk.html

[O05] 并发执行并等待全部完成
来源：http://dali.yj20258888.top/Article/details/gtvvwybknl.html

Py:   asyncio.gather(*tasks)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfxrnhhvb.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.ydzc1.top/Article/details/gtrqqiucmb.html

JS:   await Promise.all(tasks)
来源：http://dali.hfpthk.cn/Article/details/gtlphfddpn.html

TS:   await Promise.all(tasks)
来源：http://dali.cdnleiting.top/Article/details/gtxagmafoq.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.hywenlv.cn/Article/details/gtffflstev.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.dianchejie.cn/Article/details/gtcxnylfvd.html

Ruby: threads.map(&:join)
来源：http://dali.meibo888.top/Article/details/gtwhpcgexr.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.yvedp.cn/Article/details/gtqtmcjiej.html

[O06] 使用进程池
来源：http://dali.gaohongyu789.top/Article/details/gtuxaktvtq.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.shangyingyoupin.top/Article/details/gtlabztiet.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.gogol.net.cn/Article/details/gtwtuujlvm.html

JS:   // child_process / cluster 模块
来源：http://dali.c1oappe.top/Article/details/gtwujyvfmm.html

TS:   // child_process / cluster 模块
来源：http://dali.cqqwz.cn/Article/details/gtumyyrjrg.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoecvmsov.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.0kj1m.cn/Article/details/gtdwstumzf.html

Ruby: // fork 块
来源：http://dali.chenzaomai.com/Article/details/gttfnaeosx.html

C#:   Parallel.For
来源：http://dali.yanxiufei.cn/Article/details/gtgpzduiuf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtebumytji.html

P. 常用工具函数
来源：http://dali.guowangkeji.top/Article/details/gtmhitrtnq.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtlovahsot.html

[P01] 生成 UUID
来源：http://dali.bjfxy.top/Article/details/gthwihhwav.html

Py:   str(uuid.uuid4())
来源：http://dali.meibo888.top/Article/details/gtmpaxbqpp.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.yueranfly.top/Article/details/gtxvnkprtq.html

JS:   crypto.randomUUID()
来源：http://dali.ivvv.top/Article/details/gtelhfkxqr.html

TS:   crypto.randomUUID()
来源：http://dali.dianchejie.cn/Article/details/gtkzruzorm.html

Java: UUID.randomUUID().toString()
来源：http://dali.gzhubu.top/Article/details/gtuvhqlwka.html

Go:   // 用 github.com/google/uuid
来源：http://dali.316326.xyz/Article/details/gtpjuqvcds.html

Ruby: SecureRandom.uuid
来源：http://dali.aizwys.cn/Article/details/gtzijnopbw.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwwcztyce.html

[P02] MD5 / SHA256 摘要
来源：http://dali.shuidangran.top/Article/details/gtnihevgfc.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.xylfe.cn/Article/details/gtkeqdbujb.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.jlsjyb.cn/Article/details/gtbesudqlm.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhoulong.xyz/Article/details/gtbmpveszr.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.tanke756.top/Article/details/gtpwkdxpov.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.xinyue.icu/Article/details/gtosocfpda.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.xuetiantiany.cn/Article/details/gtdievnibw.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.jinqigfzy.top/Article/details/gtgxkembas.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.9152youxi.cn/Article/details/gtvrpavzij.html

[P03] 生成短随机字符串
来源：http://dali.nwbrower.top/Article/details/gtinkajsul.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.aizwys.cn/Article/details/gticumjqze.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.hammf.cn/Article/details/gtfhkzuolm.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.pengpengdd.cyou/Article/details/gtexscpnfv.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jinqigfzy.top/Article/details/gtxqurdtrn.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.svipenyu.cn/Article/details/gtgxcbbfnz.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.jinqigufen.top/Article/details/gtvrbnnlam.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.tanke756.top/Article/details/gtuhrxlxcg.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.nwbrower.top/Article/details/gtdwfqyyyf.html

[P04] 求长度
来源：http://dali.dashuyun.cn/Article/details/gtjudnjjnm.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.wangshuangyany.cn/Article/details/gtbggqodzz.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhongyouzk.top/Article/details/gtzwjekvfn.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.fzhhl.top/Article/details/gtqbqjktxi.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yangfankeji.com/Article/details/gtbazpedpy.html

Java: list.size();  map.size();  s.length()
来源：http://dali.cdnleiting.top/Article/details/gtvxuvfilf.html

Go:   len(arr);  len(m)
来源：http://dali.guowangkeji.top/Article/details/gtplxwwknx.html

Ruby: x.length;  x.size
来源：http://dali.9152youxi.cn/Article/details/gtorqzeqag.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.wangshuangyany.cn/Article/details/gtwoynetra.html

[P05] 判断两个对象内容是否相等
来源：http://dali.xylfe.cn/Article/details/gtdtjtrdfv.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.smart0.xyz/Article/details/gtiroolwfg.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.iojbl.cn/Article/details/gtlfunptec.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.yonumen.top/Article/details/gtihpcrisa.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.sufxvd.cn/Article/details/gtimabwdai.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.mhx1999.top/Article/details/gtybbnvoha.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.ppjwa.cn/Article/details/gtfluwdvef.html

Ruby: a == b
来源：http://dali.ybcxt.top/Article/details/gtumsdeniq.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.havefunace.top/Article/details/gtdaiojrpn.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.tanke756.top/Article/details/gtkolsqzax.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.jqgfzy.top/Article/details/gtcokprcsr.html

PHP:  if (empty($x)) {}
来源：http://dali.havefunace.top/Article/details/gtkkscppol.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.sysykeji.top/Article/details/gtfotwcosz.html

TS:   if (x == null) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtupfrvyax.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.aizwys.cn/Article/details/gtbpwcpiuh.html

Go:   if x == nil {}
来源：http://dali.svipenyu.cn/Article/details/gtasonrhin.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.wangdashe.top/Article/details/gtbnerflmr.html

C#:   if (x is null) {}
来源：http://dali.hnxiangtu.top/Article/details/gtedrqvzyj.html

[P07] 防抖与节流
来源：http://dali.yueranfly.top/Article/details/gtglfppbcp.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtysomhrmx.html

PHP:  // 手写时间戳比较
来源：http://dali.jyoumei.cn/Article/details/gtbdvtzxwz.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.shanyushiyangkeji.top/Article/details/gttqplqxyx.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhongyouzk.top/Article/details/gteoruqqei.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.chenlongwang.top/Article/details/gtnkzucptk.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.quarkkingdee.top/Article/details/gtphveqizu.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.redwolf501.top/Article/details/gtbhucezlw.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.quarkkingdee.top/Article/details/gtwfvoopzu.html

[P08] 处理浮点精度问题
来源：http://dali.gogol.net.cn/Article/details/gtasauhjfi.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.fengsongda.top/Article/details/gttxpxxtsv.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.yj202588.top/Article/details/gtwxedkxit.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhixingplan.top/Article/details/gtqbsnzwoj.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.316326.xyz/Article/details/gtrpgudrir.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhijiandao.cn/Article/details/gtjmtxuqxi.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.yuanzhike.top/Article/details/gtdiytdfip.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.jinqigfzy.top/Article/details/gtqodhllxo.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.xziqi.cn/Article/details/gtnpbvlvze.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtdgluzljk.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.snrcjt.cn/Article/details/gtdgimjuub.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtxmzpefiz.html

[Q01] 创建表
来源：http://dali.redwolf501.top/Article/details/gtksjwuobo.html

CREATE TABLE users (
来源：http://dali.hywenlv.cn/Article/details/gtnovazqhe.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.iojbl.cn/Article/details/gticcfovqx.html

name VARCHAR(50) NOT NULL,
来源：http://dali.jqgfzy.top/Article/details/gtxqqpfvuh.html

email VARCHAR(100) UNIQUE,
来源：http://dali.c1oappe.top/Article/details/gtourritiz.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.aizwys.cn/Article/details/gtiptgftqq.html

);
来源：http://dali.quarkkingdee.top/Article/details/gtuiciudzu.html

[Q02] 创建带外键的表
来源：http://dali.cqqwz.cn/Article/details/gtqvqdicrl.html

CREATE TABLE orders (
来源：http://dali.jiagoushi.top/Article/details/gtdfqcdhyt.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.havefunace.top/Article/details/gtipqtrbrb.html

user_id INT NOT NULL,
来源：http://dali.vqdsnc.cn/Article/details/gttcmrvpft.html

amount DECIMAL(10, 2),
来源：http://dali.jyoumei.cn/Article/details/gtdoalvccf.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.9152youxi.cn/Article/details/gtbtmscjfj.html

);
来源：http://dali.9152youxi.cn/Article/details/gtfumvosco.html

[Q03] 增加列
来源：http://dali.0kj1m.cn/Article/details/gttzryjhtw.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.xuetiantiany.cn/Article/details/gtupmdscsl.html

[Q04] 修改列类型
来源：http://dali.ehwqpu.com/Article/details/gtdsnupwbi.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.fengsongda.top/Article/details/gthlmopust.html

[Q05] 重命名列
来源：http://dali.yanxiufei.cn/Article/details/gtgbhdhibr.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.wangshuangyany.cn/Article/details/gtwwwxqgsr.html

[Q06] 删除列
来源：http://dali.jinyuanbaomall.cn/Article/details/gthirmpykd.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.fzhhl.top/Article/details/gtpfniguhn.html

[Q07] 删除表
来源：http://dali.sysykeji.top/Article/details/gtcmtuqzme.html

DROP TABLE IF EXISTS orders;
来源：http://dali.fengsongda.top/Article/details/gtwocwjxqr.html

[Q08] 创建普通索引
来源：http://dali.xuetiantiany.cn/Article/details/gtmuxpnhfc.html


<!-- 参考信息 -->