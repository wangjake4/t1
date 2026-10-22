代发 wailian999

JS:   process.exit(1)
来源：http://dali.vqdsnc.cn/Article/details/gtzwciyhfd.html

TS:   process.exit(1)
来源：http://dali.nanxuanxn.top/Article/details/gtyyezpbne.html

Java: System.exit(1)
来源：http://dali.andypj.xyz/Article/details/gtpyukhwbu.html

Go:   os.Exit(1)
来源：http://dali.tian-w.cn/Article/details/gtoyaiqvyt.html

Ruby: exit 1
来源：http://dali.svipenyu.cn/Article/details/gtwqldwtqe.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhiwuduotai.top/Article/details/gtjnoffhek.html

[M06] 向标准错误输出
来源：http://dali.yuanzhike.top/Article/details/gtobgptppd.html

Py:   print("err", file=sys.stderr)
来源：http://dali.ybcxt.top/Article/details/gtxapqrach.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.jinghuilouyu.cn/Article/details/gttzocoprq.html

JS:   console.error("err")
来源：http://dali.jqgufenzy.top/Article/details/gtfndkhuvt.html

TS:   console.error("err")
来源：http://dali.ybcxt.top/Article/details/gtitzkszqy.html

Java: System.err.println("err")
来源：http://dali.feifeiyinyue.top/Article/details/gtniecuzyo.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.cashguo.top/Article/details/gtaxgphgfg.html

Ruby: warn "err"
来源：http://dali.iojbl.cn/Article/details/gtecgwstib.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.hnqzz.top/Article/details/gthdfksyte.html

[M07] 判断是否为主入口
来源：http://dali.shzxlz.cn/Article/details/gtrxjmsycy.html

Py:   if __name__ == "__main__":
来源：http://dali.jqgufenzy.top/Article/details/gtbiaihfpw.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.316326.xyz/Article/details/gthhfcfplo.html

JS:   require.main === module
来源：http://dali.jinghuilouyu.cn/Article/details/gtsmgfnvhp.html

TS:   require.main === module
来源：http://dali.jinghuilouyu.cn/Article/details/gtdmvapzzn.html

Java: public static void main(String[] args)
来源：http://dali.xziqi.cn/Article/details/gtrfooaddg.html

Go:   func main()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjkrhlgqj.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.gzhubu.top/Article/details/gteqooxnij.html

C#:   static void Main(string[] args)
来源：http://dali.jinghuilouyu.cn/Article/details/gtheairjzx.html

[M08] 获取系统与运行时信息
来源：http://dali.wangshuangyany.cn/Article/details/gtvrldikld.html

Py:   platform.system();  platform.python_version()
来源：http://dali.ppjwa.cn/Article/details/gtgxwmsyie.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.316326.xyz/Article/details/gtwnanwhgt.html

JS:   process.platform;  process.version
来源：http://dali.cdnleiting.top/Article/details/gtlvjvdilu.html

TS:   process.platform;  process.version
来源：http://dali.shzxlz.cn/Article/details/gturatyokn.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtspwcqsbu.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.daxiang520.top/Article/details/gtnogbpxlg.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.dashuyun.cn/Article/details/gtdjqtuxjn.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.hysaishi.cn/Article/details/gtapxmvauj.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gttcpnvcja.html

N. 数据结构与算法
来源：http://dali.chenzaomai.com/Article/details/gtirtdiwey.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtbofyoajs.html

[N01] 二分查找（有序数组）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtooapudkn.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zdqjudy.top/Article/details/gtnhgafzta.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.smart0.xyz/Article/details/gtuoztsbnk.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yangfankeji.com/Article/details/gtkyoblziq.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.cqqwz.cn/Article/details/gtrczsfpno.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gtwapydato.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.nanxuanxn.top/Article/details/gtfmayygxy.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.xziqi.cn/Article/details/gtftcnivri.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.sufxvd.cn/Article/details/gtdwytcbak.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.jinqigufen.top/Article/details/gtbhlrxplp.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.sweek.top/Article/details/gtbiehfhdm.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteirzbjzn.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfnntgqiv.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.havefunace.top/Article/details/gttdhvqjzs.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.ivvv.top/Article/details/gtcfeqlsay.html

Go:   slices.Sort(arr)
来源：http://dali.zycfv.cn/Article/details/gtqshbnyvn.html

Ruby: arr.sort
来源：http://dali.bjfxy.top/Article/details/gthontfdsp.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.jiagoushi.top/Article/details/gterfakvae.html

[N03] 快速排序（分治示例）
来源：http://dali.yongpay.top/Article/details/gtdbvvdoqv.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.chenlongwang.top/Article/details/gtrtgybfml.html

PHP:  // 递归实现，或用 usort
来源：http://dali.hysaishi.cn/Article/details/gtotnlcden.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.tanke756.top/Article/details/gtoopjhzwx.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.svipenyu.cn/Article/details/gtrdprhqeh.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.9152youxi.cn/Article/details/gtlnsgapvn.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.jiagoushi.top/Article/details/gtyidrprld.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.kuanghao11.cn/Article/details/gtpzdrbuze.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.yongpay.top/Article/details/gtkqhaxdjf.html

[N04] 斐波那契数列
来源：http://dali.xylfe.cn/Article/details/gtcjemnjgv.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.shuidangran.top/Article/details/gtazsijvpp.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.ppjwa.cn/Article/details/gtfnndoftw.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.vqdsnc.cn/Article/details/gttfbytcgu.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.hfpthk.cn/Article/details/gtnimsirlt.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.jianghu66.top/Article/details/gtduqumlzq.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.fzhhl.top/Article/details/gtieaegxgw.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.smart0.xyz/Article/details/gtuwmfaghr.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.wangshuangyany.cn/Article/details/gtqqhdriza.html

[N05] 最大公约数
来源：http://dali.haohaochexian.top/Article/details/gttprnpjdc.html

Py:   math.gcd(a, b)
来源：http://dali.shzxlz.cn/Article/details/gtonmypuhg.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.yonumen.top/Article/details/gttysqmhcl.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.xziqi.cn/Article/details/gteivyngle.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.tian-w.cn/Article/details/gtkmmjjppd.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.ehwqpu.com/Article/details/gtndofzncf.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.yuanzhike.top/Article/details/gtiwmjgjbs.html

Ruby: a.gcd(b)
来源：http://dali.cashguo.top/Article/details/gtlybjayvu.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.nanxinkj.top/Article/details/gtmhnldavb.html

[N06] 判断回文字符串
来源：http://dali.andypj.xyz/Article/details/gtozljaifu.html

Py:   s == s[::-1]
来源：http://dali.hysaishi.cn/Article/details/gtxckdzkes.html

PHP:  $s === strrev($s);
来源：http://dali.nanxuanxn.top/Article/details/gtmcenvezm.html

JS:   s === [...s].reverse().join("")
来源：http://dali.nanxinkj.top/Article/details/gtyurgqgal.html

TS:   s === [...s].reverse().join("")
来源：http://dali.svipenyu.cn/Article/details/gtzfivxekv.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.yongpay.top/Article/details/gtpmuaitva.html

Go:   // 双指针从两端比较
来源：http://dali.xziqi.cn/Article/details/gtbzbnnojh.html

Ruby: s == s.reverse
来源：http://dali.zhongyouzk.top/Article/details/gteujiswiq.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.gaohongyu789.top/Article/details/gtfdsmrxiy.html

[N07] 两数之和（返回下标）
来源：http://dali.yj202588.top/Article/details/gtzihcdxsc.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.ivvv.top/Article/details/gtqkuakbnv.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.yueranfly.top/Article/details/gtokyklreu.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.9152youxi.cn/Article/details/gtarvjkael.html

TS:   // 手写 Map<string, number>
来源：http://dali.jqgufenzy.top/Article/details/gtbqjwcpli.html

Java: // 手写 HashMap
来源：http://dali.pycfn.com/Article/details/gthihvrnim.html

Go:   // 手写 map[int]int
来源：http://dali.zdqjudy.top/Article/details/gtamrkoiab.html

Ruby: // 手写 Hash
来源：http://dali.tian-w.cn/Article/details/gtkhbwxlth.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.meibo888.top/Article/details/gtcdandmmd.html

[N08] 生成全排列
来源：http://dali.ybcxt.top/Article/details/gtbgetgxfe.html

Py:   itertools.permutations(arr)
来源：http://dali.fzhhl.top/Article/details/gtcbrxpbrg.html

PHP:  // 手写递归交换
来源：http://dali.yvedp.cn/Article/details/gtdrbxejev.html

JS:   // 手写回溯递归
来源：http://dali.hongshengwenyu.top/Article/details/gtutlngoge.html

TS:   // 手写回溯递归
来源：http://dali.hongshengwenyu.top/Article/details/gtmgxqbumu.html

Java: // 手写回溯递归
来源：http://dali.shzxlz.cn/Article/details/gtnucjvdwo.html

Go:   // 手写回溯递归
来源：http://dali.yanxiufei.cn/Article/details/gttttotkwe.html

Ruby: arr.permutation.to_a
来源：http://dali.havefunace.top/Article/details/gtkkktdlpg.html

C#:   // 手写回溯递归
来源：http://dali.yuanzhike.top/Article/details/gtgipwmekz.html

[N09] 栈与队列
来源：http://dali.kuanghao11.cn/Article/details/gtoyflgjdm.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.guowangkeji.top/Article/details/gtjdvssqpn.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.hongshengwenyu.top/Article/details/gtjszgznhn.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.dashuyun.cn/Article/details/gtvwyghzlr.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.cheryme.top/Article/details/gtryykcfez.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.jqgfzy.top/Article/details/gttwetlpjz.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zycfv.cn/Article/details/gttidyaaqw.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.chenlongwang.top/Article/details/gtsibrnkdt.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.wangdashe.top/Article/details/gtcrcuzqrx.html

[N10] 链表节点定义
来源：http://dali.wangshuangyany.cn/Article/details/gtsxaflkmk.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.fengsongda.top/Article/details/gtiiivliqw.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gttxufqiuu.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.hammf.cn/Article/details/gtkfyvvzqu.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.meibo888.top/Article/details/gtdncldrtd.html

Java: class Node { int v; Node next; }
来源：http://dali.birdmap.top/Article/details/gtzerpkivm.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.jinqigufen.top/Article/details/gtncqpjtnn.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.tian-w.cn/Article/details/gtaytcmzrf.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.dashuyun.cn/Article/details/gtouifzkts.html

[N11] 二叉树中序遍历
来源：http://dali.zhengqikj.top/Article/details/gtmghtstss.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.cqqwz.cn/Article/details/gtdlrontat.html

PHP:  // 手写递归函数
来源：http://dali.sufxvd.cn/Article/details/gtxsnitwcn.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.wangshuangyany.cn/Article/details/gtxzzaropl.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtibrnvkmv.html

Java: // 手写递归
来源：http://dali.hnxiangtu.top/Article/details/gtlxfevjoi.html

Go:   // 手写递归
来源：http://dali.jinyuanbaomall.cn/Article/details/gtekuzadzu.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.shzxlz.cn/Article/details/gtblsgnsyp.html

C#:   // 手写递归
来源：http://dali.meibo888.top/Article/details/gtltwrmucf.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.tian-w.cn/Article/details/gtzksftqcr.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.quarkkingdee.top/Article/details/gtowvkvmuq.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.sysykeji.top/Article/details/gttzfqykbm.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yanxiufei.cn/Article/details/gtmwuazcim.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.ybcxt.top/Article/details/gtttwiczxp.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.guannengcc.top/Article/details/gtwsrnkufu.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.yj20258888.top/Article/details/gtqzchpkhc.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.yj20258.top/Article/details/gteiyjbsvs.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.andypj.xyz/Article/details/gtomqnfvme.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtwywpqjax.html

O. 并发与异步
来源：http://dali.yuxming.cn/Article/details/gtzljqksuc.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtlajdyodw.html

[O01] 启动一个线程
来源：http://dali.jqgfzy.top/Article/details/gtkebvxwwu.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.tian-w.cn/Article/details/gtuqbnhhqr.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.yuxming.cn/Article/details/gtbxuoksvj.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.ydzc1.top/Article/details/gtntkotves.html

TS:   // 同 JS
来源：http://dali.gogol.net.cn/Article/details/gtvirdjcvl.html

Java: new Thread(() -> f()).start()
来源：http://dali.tian-w.cn/Article/details/gtmeocfmsh.html

Go:   go f()
来源：http://dali.sufxvd.cn/Article/details/gtocfbickf.html

Ruby: Thread.new { f }
来源：http://dali.svipenyu.cn/Article/details/gtxecmarnu.html

C#:   Task.Run(() => F());
来源：http://dali.hnxiangtu.top/Article/details/gtgykghyyd.html

[O02] 使用线程池
来源：http://dali.yj20258.top/Article/details/gtmqcztzly.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhongyouzk.top/Article/details/gtocnpqybp.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.jinghuilouyu.cn/Article/details/gtmustcrli.html

JS:   // worker_threads 线程池
来源：http://dali.yangfankeji.com/Article/details/gtbwaykiek.html

TS:   // worker_threads 线程池
来源：http://dali.wangshuangyany.cn/Article/details/gtohryejbn.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.wangshuangyany.cn/Article/details/gtthwolsvq.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.havefunace.top/Article/details/gtincgxhgj.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.xinyue.icu/Article/details/gtkcganwqw.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcnwzlwrp.html

[O03] 加锁保护共享数据
来源：http://dali.cashguo.top/Article/details/gtslgvxczx.html

Py:   with lock: shared += 1
来源：http://dali.jinghuilouyu.cn/Article/details/gtzcbzhrtu.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhiwuduotai.top/Article/details/gtqfajpbxe.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.andypj.xyz/Article/details/gtgzzniehi.html

TS:   // 同 JS
来源：http://dali.daria6918.cn/Article/details/gtepezjffq.html

Java: synchronized (this) { shared++; }
来源：http://dali.ybcxt.top/Article/details/gtlixpancd.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.ybcxt.top/Article/details/gtrrgkjlhv.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.fzhhl.top/Article/details/gtksxlscyv.html

C#:   lock (gate) { shared++; }
来源：http://dali.tanke756.top/Article/details/gtvcdxyljd.html

[O04] 定义异步函数并等待
来源：http://dali.haohaochexian.top/Article/details/gtqrcoydgk.html

Py:   async def f():⏎    await g()
来源：http://dali.fengsongda.top/Article/details/gtreyngtdi.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.cheryme.top/Article/details/gtutncbuxy.html

JS:   async function f() { await g(); }
来源：http://dali.jyoumei.cn/Article/details/gtvacyvada.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.hammf.cn/Article/details/gtwvksmlpi.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.daria6918.cn/Article/details/gtvvhmdqim.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.snrcjt.cn/Article/details/gtxkzqmvae.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.cheryme.top/Article/details/gtdxmsypbx.html

C#:   async Task F() { await G(); }
来源：http://dali.wangdashe.top/Article/details/gtmzfjcuyb.html

[O05] 并发执行并等待全部完成
来源：http://dali.yvedp.cn/Article/details/gtngqyyvqo.html

Py:   asyncio.gather(*tasks)
来源：http://dali.c1oappe.top/Article/details/gtkzeutjhy.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.fengsongda.top/Article/details/gtefeptywr.html

JS:   await Promise.all(tasks)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzsonodjo.html

TS:   await Promise.all(tasks)
来源：http://dali.yongpay.top/Article/details/gtpxnpwcov.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.shuidangran.top/Article/details/gtubhibybj.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.tian-w.cn/Article/details/gtcqsxypeb.html

Ruby: threads.map(&:join)
来源：http://dali.daxiang520.top/Article/details/gtkugxnqdq.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.nwbrower.top/Article/details/gtbxkigtem.html

[O06] 使用进程池
来源：http://dali.nanxinkj.top/Article/details/gttddqtepp.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.jqgufenzy.top/Article/details/gtthuprumr.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.fzhhl.top/Article/details/gtmqmzezok.html

JS:   // child_process / cluster 模块
来源：http://dali.aibaodan.cn/Article/details/gtzybokesh.html

TS:   // child_process / cluster 模块
来源：http://dali.ppjwa.cn/Article/details/gtdnmyjnqf.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.0kj1m.cn/Article/details/gtmpghlbck.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.hfpthk.cn/Article/details/gtjsrbhnoc.html

Ruby: // fork 块
来源：http://dali.zhongyouzk.top/Article/details/gtmoeqizhw.html

C#:   Parallel.For
来源：http://dali.hammf.cn/Article/details/gtkllhwdlg.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtxkagwgfm.html

P. 常用工具函数
来源：http://dali.gzhubu.top/Article/details/gtivjnyzxd.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtxxqebyre.html

[P01] 生成 UUID
来源：http://dali.tian-w.cn/Article/details/gtjfevydwc.html

Py:   str(uuid.uuid4())
来源：http://dali.shanyushiyangkeji.top/Article/details/gttuxkuecv.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.hysaishi.cn/Article/details/gtsftrfwld.html

JS:   crypto.randomUUID()
来源：http://dali.nanxinkj.top/Article/details/gtqqutkils.html

TS:   crypto.randomUUID()
来源：http://dali.birdmap.top/Article/details/gtbicneqhu.html

Java: UUID.randomUUID().toString()
来源：http://dali.gzhubu.top/Article/details/gtsudidreq.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhoulong.xyz/Article/details/gtlrzxqagw.html

Ruby: SecureRandom.uuid
来源：http://dali.yanxiufei.cn/Article/details/gtkujmenri.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.redwolf501.top/Article/details/gtozkdwjcp.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gtncrgmqua.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.ivvv.top/Article/details/gtfhlcujkx.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.pycfn.com/Article/details/gtheqfdoie.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.aizwys.cn/Article/details/gtkqrcdjcm.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.yuanzhike.top/Article/details/gtqhahqwad.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.316326.xyz/Article/details/gtgciqrkmm.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.xuanzx.com/Article/details/gtsqpbylma.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.yj20258888.top/Article/details/gtxqukyokk.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.sxryk.cn/Article/details/gturcidpux.html

[P03] 生成短随机字符串
来源：http://dali.jqgufenzy.top/Article/details/gthiuhxiog.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.yonumen.top/Article/details/gtqiennchq.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.jqgufenzy.top/Article/details/gtsazeszlb.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.aizwys.cn/Article/details/gtmsywobkc.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.hysaishi.cn/Article/details/gtbofrcert.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.tian-w.cn/Article/details/gtpuvrhlep.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.9152youxi.cn/Article/details/gtmeevkajx.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.bjfxy.top/Article/details/gtwwmgqsle.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.fengsongda.top/Article/details/gtvvbbhffi.html

[P04] 求长度
来源：http://dali.vqdsnc.cn/Article/details/gtepmormrj.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gtlnsexnhj.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.wangdashe.top/Article/details/gtsvpbqzbz.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jianghu66.top/Article/details/gtaexyxfgw.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jinghuilouyu.cn/Article/details/gtrvuldqhj.html

Java: list.size();  map.size();  s.length()
来源：http://dali.aibaodan.cn/Article/details/gtpvykfesl.html

Go:   len(arr);  len(m)
来源：http://dali.wangshuangyany.cn/Article/details/gtsmtlcode.html

Ruby: x.length;  x.size
来源：http://dali.yuanzhike.top/Article/details/gtipzdyhzg.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.yuxming.cn/Article/details/gtjbvmuxxt.html

[P05] 判断两个对象内容是否相等
来源：http://dali.sysykeji.top/Article/details/gtkrmeyfak.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.chenlongwang.top/Article/details/gtzxzuycgm.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.daria6918.cn/Article/details/gtrexetswd.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.dashuyun.cn/Article/details/gtnhijxbyb.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.fengsongda.top/Article/details/gtibldmnkj.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.smart0.xyz/Article/details/gtthkmuetg.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.yanxiufei.cn/Article/details/gttbpapaae.html

Ruby: a == b
来源：http://dali.jianghu66.top/Article/details/gtquathtjg.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhiwuduotai.top/Article/details/gtfvftboxa.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.jinqigufen.top/Article/details/gtxlqqynmy.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtufglkcdl.html

PHP:  if (empty($x)) {}
来源：http://dali.guowangkeji.top/Article/details/gtvbvyhpat.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.cqqwz.cn/Article/details/gtjzqcgzwc.html

TS:   if (x == null) {}
来源：http://dali.svipenyu.cn/Article/details/gtfbiqaevg.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.hysaishi.cn/Article/details/gtafehzlni.html

Go:   if x == nil {}
来源：http://dali.cashguo.top/Article/details/gtxrwzmomj.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.jyoumei.cn/Article/details/gtmcaeacpy.html

C#:   if (x is null) {}
来源：http://dali.zhongyouzk.top/Article/details/gtprmdbfkj.html

[P07] 防抖与节流
来源：http://dali.mhx1999.top/Article/details/gtroniitlk.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.iojbl.cn/Article/details/gtumadwvsl.html

PHP:  // 手写时间戳比较
来源：http://dali.cdnleiting.top/Article/details/gtqrcwjlwp.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.dashuyun.cn/Article/details/gtpechdjno.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.9152youxi.cn/Article/details/gtdpgjknqh.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.birdmap.top/Article/details/gtsktpxkkc.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.cdnleiting.top/Article/details/gtzwzsnoyh.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.aizwys.cn/Article/details/gthcdczpjz.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.iojbl.cn/Article/details/gtlqshaybx.html

[P08] 处理浮点精度问题
来源：http://dali.zdqjudy.top/Article/details/gtlfotsmuj.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.hongshengwenyu.top/Article/details/gtczmhjfti.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.zdqjudy.top/Article/details/gtoavyfusp.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.havefunace.top/Article/details/gtjkqdcabp.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.daxiang520.top/Article/details/gtblvynajl.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.meibo888.top/Article/details/gtbxcpjtdj.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.sweek.top/Article/details/gthpwfwkob.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.aibaodan.cn/Article/details/gtsmjgxulh.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.316326.xyz/Article/details/gtvdkempce.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtjjfckfvy.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.iojbl.cn/Article/details/gtbtszvszv.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gttipbceru.html

[Q01] 创建表
来源：http://dali.xziqi.cn/Article/details/gtcdmlsedb.html

CREATE TABLE users (
来源：http://dali.zhoulong.xyz/Article/details/gtrrsauujh.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpajxatyz.html

name VARCHAR(50) NOT NULL,
来源：http://dali.316326.xyz/Article/details/gtdhspjnjl.html

email VARCHAR(100) UNIQUE,
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnlrmugol.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.gzhubu.top/Article/details/gtamexrjha.html

);
来源：http://dali.ppjwa.cn/Article/details/gtzrqxwqra.html

[Q02] 创建带外键的表
来源：http://dali.daxiang520.top/Article/details/gtgwgqxivf.html

CREATE TABLE orders (
来源：http://dali.ehwqpu.com/Article/details/gtsxgtvqxn.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.aibaodan.cn/Article/details/gtdkntlpxy.html

user_id INT NOT NULL,
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyuvqfikn.html

amount DECIMAL(10, 2),
来源：http://dali.jinqigfzy.top/Article/details/gtrcytaznk.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.tanke756.top/Article/details/gtqpyypnys.html

);
来源：http://dali.yuxming.cn/Article/details/gtoyzszesj.html

[Q03] 增加列
来源：http://dali.yongpay.top/Article/details/gtzypyvmuh.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.jinqigfzy.top/Article/details/gtbidfpkfo.html

[Q04] 修改列类型
来源：http://dali.dashuyun.cn/Article/details/gtlnnfwlsf.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.guowangkeji.top/Article/details/gtqfgzmros.html

[Q05] 重命名列
来源：http://dali.shanyushiyangtech.top/Article/details/gtbieeelqa.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.cdnleiting.top/Article/details/gtvvjfpqkf.html

[Q06] 删除列
来源：http://dali.haohaochexian.top/Article/details/gtspiwknnz.html


<!-- 参考信息 -->