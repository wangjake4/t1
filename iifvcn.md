代发 wailian999

JS:   process.exit(1)
来源：http://dali.tanke756.top/Article/details/gtnqfwyvze.html

TS:   process.exit(1)
来源：http://dali.aibaodan.cn/Article/details/gtglvssges.html

Java: System.exit(1)
来源：http://dali.hammf.cn/Article/details/gttqqabidx.html

Go:   os.Exit(1)
来源：http://dali.daxiang520.top/Article/details/gtkptbazeh.html

Ruby: exit 1
来源：http://dali.chenlongwang.top/Article/details/gtnedqlqth.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.jyoumei.cn/Article/details/gtugjafwxk.html

[M06] 向标准错误输出
来源：http://dali.tian-w.cn/Article/details/gtwjsvfrbt.html

Py:   print("err", file=sys.stderr)
来源：http://dali.chenzaomai.com/Article/details/gtpdcevatf.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.chenjidiqi.icu/Article/details/gtuysxtmbd.html

JS:   console.error("err")
来源：http://dali.yj20258.top/Article/details/gtakqccbru.html

TS:   console.error("err")
来源：http://dali.wangdashe.top/Article/details/gtootlwnvd.html

Java: System.err.println("err")
来源：http://dali.zhiwuduotai.top/Article/details/gtcomsfkgi.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.316326.xyz/Article/details/gtutzvsigc.html

Ruby: warn "err"
来源：http://dali.ppjwa.cn/Article/details/gtsjoxqcrg.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.tianlin.xyz/Article/details/gtaevytsrl.html

[M07] 判断是否为主入口
来源：http://dali.wangshuangyany.cn/Article/details/gtyimvnptl.html

Py:   if __name__ == "__main__":
来源：http://dali.yj20258.top/Article/details/gtqkkghgah.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.sweek.top/Article/details/gthclgxaur.html

JS:   require.main === module
来源：http://dali.zhongyouzk.top/Article/details/gtpzobjecw.html

TS:   require.main === module
来源：http://dali.ivvv.top/Article/details/gtttpfbwlf.html

Java: public static void main(String[] args)
来源：http://dali.meibo888.top/Article/details/gtlzqjoxmv.html

Go:   func main()
来源：http://dali.sufxvd.cn/Article/details/gtyneiqlrq.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.guannengcc.top/Article/details/gticdinjyd.html

C#:   static void Main(string[] args)
来源：http://dali.xuanzx.com/Article/details/gtcjlnepbf.html

[M08] 获取系统与运行时信息
来源：http://dali.ppjwa.cn/Article/details/gtllhewhyw.html

Py:   platform.system();  platform.python_version()
来源：http://dali.mhx1999.top/Article/details/gttugsqefr.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhoulong.xyz/Article/details/gttmufwkyk.html

JS:   process.platform;  process.version
来源：http://dali.cheryme.top/Article/details/gtcxhasdkl.html

TS:   process.platform;  process.version
来源：http://dali.wangshuangyany.cn/Article/details/gtedapafzc.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.chenjidiqi.icu/Article/details/gtneauydvr.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.quarkkingdee.top/Article/details/gtlfsfpgpy.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.jinqigfzy.top/Article/details/gtsqfynrfo.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhiwuduotai.top/Article/details/gtvitiwwmv.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtkceumyix.html

N. 数据结构与算法
来源：http://dali.shangyingyoupin.top/Article/details/gttpkckszi.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtuhgupxrz.html

[N01] 二分查找（有序数组）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtustfelxb.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.pycfn.com/Article/details/gtxzfhkjbk.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.hammf.cn/Article/details/gtbjozxcyv.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.shzxlz.cn/Article/details/gtxpsedivh.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.ehwqpu.com/Article/details/gttdnihxht.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.jlsjyb.cn/Article/details/gtplygsgdi.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.sweek.top/Article/details/gtawazpsgj.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.daxiang520.top/Article/details/gtvnmvuavt.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.jinghuilouyu.cn/Article/details/gtofpyuigr.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.svipenyu.cn/Article/details/gtserutcof.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.fengsongda.top/Article/details/gtayunxnpb.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.jinqigfzy.top/Article/details/gtrhladnxg.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.bjfxy.top/Article/details/gtfaadcgtp.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.quarkkingdee.top/Article/details/gtsmyzuljj.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.xuetiantiany.cn/Article/details/gtjbkzbgvg.html

Go:   slices.Sort(arr)
来源：http://dali.shanyushiyangtech.top/Article/details/gtnvcrfxwh.html

Ruby: arr.sort
来源：http://dali.tanke756.top/Article/details/gtsukhziol.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.smart0.xyz/Article/details/gtebwmhjzv.html

[N03] 快速排序（分治示例）
来源：http://dali.birdmap.top/Article/details/gtptrwrzaz.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.jiagoushi.top/Article/details/gtibgddqih.html

PHP:  // 递归实现，或用 usort
来源：http://dali.shanyushiyangkeji.top/Article/details/gthfcqaqdb.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jlsjyb.cn/Article/details/gtaszesggh.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.hnxiangtu.top/Article/details/gtogeybdpc.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.hongshengwenyu.top/Article/details/gtnebiasci.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.jqgufenzy.top/Article/details/gthjtwlnwf.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.jiagoushi.top/Article/details/gtwhgfqdtj.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.svipenyu.cn/Article/details/gtqjclyvfc.html

[N04] 斐波那契数列
来源：http://dali.daria6918.cn/Article/details/gtmbcpaovx.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.xinyue.icu/Article/details/gtkyhmfzpm.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.gotoacloud.top/Article/details/gttjdmkssy.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhongyouzk.top/Article/details/gtpsvsbetd.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.9152youxi.cn/Article/details/gtzjarpgtx.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.xziqi.cn/Article/details/gtbklgivln.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.tianlin.xyz/Article/details/gtvhkshbmw.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.9152youxi.cn/Article/details/gtkrkyqoch.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.smart0.xyz/Article/details/gtuczbenep.html

[N05] 最大公约数
来源：http://dali.yj20258.top/Article/details/gtveqgfqji.html

Py:   math.gcd(a, b)
来源：http://dali.bjfxy.top/Article/details/gtkhnjffit.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.316326.xyz/Article/details/gtckqcwbjp.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.guannengcc.top/Article/details/gttjdsuuml.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.svipenyu.cn/Article/details/gtedkjdqnu.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.quarkkingdee.top/Article/details/gtaxsdoapx.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.nanxuanxn.top/Article/details/gthkmiyris.html

Ruby: a.gcd(b)
来源：http://dali.chenzaomai.com/Article/details/gtwjvttrqi.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.wangdashe.top/Article/details/gtawjttiqa.html

[N06] 判断回文字符串
来源：http://dali.wangdashe.top/Article/details/gtzxstxjnd.html

Py:   s == s[::-1]
来源：http://dali.chenzaomai.com/Article/details/gtqjxpxhwx.html

PHP:  $s === strrev($s);
来源：http://dali.jiagoushi.top/Article/details/gtwaippnuh.html

JS:   s === [...s].reverse().join("")
来源：http://dali.sufxvd.cn/Article/details/gtsoozbfgp.html

TS:   s === [...s].reverse().join("")
来源：http://dali.hywenlv.cn/Article/details/gtgqhwympx.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.dashuyun.cn/Article/details/gtuxydfxsf.html

Go:   // 双指针从两端比较
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdrgrzrus.html

Ruby: s == s.reverse
来源：http://dali.ybcxt.top/Article/details/gtbrbubwun.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.andypj.xyz/Article/details/gtnrqjqvoi.html

[N07] 两数之和（返回下标）
来源：http://dali.ehwqpu.com/Article/details/gtxnqwptoc.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.jyoumei.cn/Article/details/gtzcakuvuj.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.xuanzx.com/Article/details/gtkpmspfic.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.cqqwz.cn/Article/details/gtonthwfuv.html

TS:   // 手写 Map<string, number>
来源：http://dali.jyoumei.cn/Article/details/gtgajqxfly.html

Java: // 手写 HashMap
来源：http://dali.zycfv.cn/Article/details/gtnrcthnjq.html

Go:   // 手写 map[int]int
来源：http://dali.feifeiyinyue.top/Article/details/gtisqjdatj.html

Ruby: // 手写 Hash
来源：http://dali.mhx1999.top/Article/details/gteofubjau.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.jyoumei.cn/Article/details/gthoterhtd.html

[N08] 生成全排列
来源：http://dali.cdnleiting.top/Article/details/gtyswgokcd.html

Py:   itertools.permutations(arr)
来源：http://dali.ydzc1.top/Article/details/gtnkoexpjl.html

PHP:  // 手写递归交换
来源：http://dali.jinghuilouyu.cn/Article/details/gtvpbxqbqa.html

JS:   // 手写回溯递归
来源：http://dali.ywan-chungtsiang.top/Article/details/gtebsiamku.html

TS:   // 手写回溯递归
来源：http://dali.yongpay.top/Article/details/gtrwsczhqc.html

Java: // 手写回溯递归
来源：http://dali.svipenyu.cn/Article/details/gtyqhlnlsi.html

Go:   // 手写回溯递归
来源：http://dali.quarkkingdee.top/Article/details/gtykimgpcf.html

Ruby: arr.permutation.to_a
来源：http://dali.zdqjudy.top/Article/details/gttfemyexo.html

C#:   // 手写回溯递归
来源：http://dali.jyoumei.cn/Article/details/gtbjzrxkbn.html

[N09] 栈与队列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvbfvbcby.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.sufxvd.cn/Article/details/gtazgyqvcc.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.9152youxi.cn/Article/details/gtmvibqhpk.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.cdnleiting.top/Article/details/gthfcwlvfy.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.ppjwa.cn/Article/details/gtnhmctrhy.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.daria6918.cn/Article/details/gtdyrbagdf.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.hnxiangtu.top/Article/details/gtpgvxpmuw.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.hnqzz.top/Article/details/gtbxsckfdn.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.sufxvd.cn/Article/details/gtnnzdwwcr.html

[N10] 链表节点定义
来源：http://dali.cucudq.cn/Article/details/gtsqflside.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.yj20258.top/Article/details/gtyosraday.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.chenjidiqi.icu/Article/details/gtgdgqjwob.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.sysykeji.top/Article/details/gtfzjaysda.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.chenlongwang.top/Article/details/gtwknqtaeo.html

Java: class Node { int v; Node next; }
来源：http://dali.shuidangran.top/Article/details/gtzmexaqai.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.yj20258.top/Article/details/gttxdonuyp.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.0kj1m.cn/Article/details/gtaeteipkx.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.jianghu66.top/Article/details/gtlpbpqswf.html

[N11] 二叉树中序遍历
来源：http://dali.ybcxt.top/Article/details/gtvvcpltxm.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.sxryk.cn/Article/details/gtenegscfu.html

PHP:  // 手写递归函数
来源：http://dali.yj20258.top/Article/details/gtsfhrqvsw.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jinqigfzy.top/Article/details/gtaqdhyctk.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.gzhubu.top/Article/details/gtnsbocoec.html

Java: // 手写递归
来源：http://dali.sufxvd.cn/Article/details/gtlvtvrukw.html

Go:   // 手写递归
来源：http://dali.jqgfzy.top/Article/details/gthguzicyx.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.xziqi.cn/Article/details/gtnoisexfz.html

C#:   // 手写递归
来源：http://dali.dashuyun.cn/Article/details/gtbxbyhgpf.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.hnqzz.top/Article/details/gtdtpuarjk.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.shangyingyoupin.top/Article/details/gtvcwoklyk.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.c1oappe.top/Article/details/gtzyetcpsn.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.andypj.xyz/Article/details/gtvnqadfgj.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.ivvv.top/Article/details/gtetkwwdek.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gtwnnexymc.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.ybcxt.top/Article/details/gtymzagdni.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.birdmap.top/Article/details/gthrusvgso.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.birdmap.top/Article/details/gtosgwphyt.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gttxblxeyy.html

O. 并发与异步
来源：http://dali.jlsjyb.cn/Article/details/gtymwywsvt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtnjrkjmdr.html

[O01] 启动一个线程
来源：http://dali.shuidangran.top/Article/details/gtfamwoziu.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.snrcjt.cn/Article/details/gtpdyqpwmz.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.bjfxy.top/Article/details/gtjqnkgldb.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.meibo888.top/Article/details/gtwaecqvvo.html

TS:   // 同 JS
来源：http://dali.haohaochexian.top/Article/details/gtgwghuvvo.html

Java: new Thread(() -> f()).start()
来源：http://dali.0kj1m.cn/Article/details/gtmwuzfzbj.html

Go:   go f()
来源：http://dali.nwbrower.top/Article/details/gtdgsvipfh.html

Ruby: Thread.new { f }
来源：http://dali.jinqigfzy.top/Article/details/gttgbzehwu.html

C#:   Task.Run(() => F());
来源：http://dali.daria6918.cn/Article/details/gtamywhffi.html

[O02] 使用线程池
来源：http://dali.xziqi.cn/Article/details/gtsukhetpg.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.hnxiangtu.top/Article/details/gtgxdmxydo.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.cheryme.top/Article/details/gtoabzxqgm.html

JS:   // worker_threads 线程池
来源：http://dali.sufxvd.cn/Article/details/gtsqpvnieg.html

TS:   // worker_threads 线程池
来源：http://dali.wangdashe.top/Article/details/gtympviteh.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.nanxuanxn.top/Article/details/gtxqkymynt.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.ehwqpu.com/Article/details/gtwxpmahwa.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.jinqigfzy.top/Article/details/gtvcqcezst.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.ybcxt.top/Article/details/gtgomlerii.html

[O03] 加锁保护共享数据
来源：http://dali.daria6918.cn/Article/details/gtcpcwflgu.html

Py:   with lock: shared += 1
来源：http://dali.kuanghao11.cn/Article/details/gtytdmvnnh.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhaomingkeji.xyz/Article/details/gttetqirgh.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.shuidangran.top/Article/details/gtdfarnila.html

TS:   // 同 JS
来源：http://dali.cashguo.top/Article/details/gtbbgealrj.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gtiaqzpoue.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.gzhubu.top/Article/details/gtzncwjhad.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.0kj1m.cn/Article/details/gtzehpxyki.html

C#:   lock (gate) { shared++; }
来源：http://dali.sxryk.cn/Article/details/gtemlrrtra.html

[O04] 定义异步函数并等待
来源：http://dali.yanxiufei.cn/Article/details/gtzziwhvbd.html

Py:   async def f():⏎    await g()
来源：http://dali.tian-w.cn/Article/details/gtusvjjkqk.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.shanyushiyangtech.top/Article/details/gtjmxnkfqx.html

JS:   async function f() { await g(); }
来源：http://dali.jqgfzy.top/Article/details/gtntlaprgo.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.birdmap.top/Article/details/gtcruvxeuo.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.9152youxi.cn/Article/details/gtuyjatyua.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.ppjwa.cn/Article/details/gtrgzpifyx.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.hnxiangtu.top/Article/details/gtiwwobree.html

C#:   async Task F() { await G(); }
来源：http://dali.ybcxt.top/Article/details/gtgqknpvwz.html

[O05] 并发执行并等待全部完成
来源：http://dali.yangfankeji.com/Article/details/gtecedelxw.html

Py:   asyncio.gather(*tasks)
来源：http://dali.shanyushiyangkeji.top/Article/details/gthdaqfyzb.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.mhx1999.top/Article/details/gtjmjshvez.html

JS:   await Promise.all(tasks)
来源：http://dali.birdmap.top/Article/details/gtqtmkeqlo.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gtlvkwqbrv.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.yuanzhike.top/Article/details/gtjtsqqgsd.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.sysykeji.top/Article/details/gtgkpelfzr.html

Ruby: threads.map(&:join)
来源：http://dali.cashguo.top/Article/details/gtzfahdail.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.nanxuanxn.top/Article/details/gtkwhyrjkr.html

[O06] 使用进程池
来源：http://dali.hongshengwenyu.top/Article/details/gtbmupdjki.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.ppjwa.cn/Article/details/gtxxwhxjuj.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.hysaishi.cn/Article/details/gtauzzvexk.html

JS:   // child_process / cluster 模块
来源：http://dali.sweek.top/Article/details/gtgqvcivnm.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gtclcjjyir.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.xuetiantiany.cn/Article/details/gtigjqiyyy.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.yj202588.top/Article/details/gtodvfeasx.html

Ruby: // fork 块
来源：http://dali.zhoulong.xyz/Article/details/gthyyfnqdg.html

C#:   Parallel.For
来源：http://dali.tian-w.cn/Article/details/gtpuoxgaum.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtsfnjuuqh.html

P. 常用工具函数
来源：http://dali.fzhhl.top/Article/details/gteummzfrr.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtltcktuvi.html

[P01] 生成 UUID
来源：http://dali.vqdsnc.cn/Article/details/gtmfvontbd.html

Py:   str(uuid.uuid4())
来源：http://dali.mhx1999.top/Article/details/gthovcscoo.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.hammf.cn/Article/details/gtveixovkd.html

JS:   crypto.randomUUID()
来源：http://dali.kuanghao11.cn/Article/details/gtlpqnnxun.html

TS:   crypto.randomUUID()
来源：http://dali.gaohongyu789.top/Article/details/gtpgzedqlk.html

Java: UUID.randomUUID().toString()
来源：http://dali.jinghuilouyu.cn/Article/details/gtsnznfztx.html

Go:   // 用 github.com/google/uuid
来源：http://dali.vqdsnc.cn/Article/details/gtvnmneouw.html

Ruby: SecureRandom.uuid
来源：http://dali.yj20258888.top/Article/details/gtluzeteqw.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.bjfxy.top/Article/details/gtjmgggyhj.html

[P02] MD5 / SHA256 摘要
来源：http://dali.svipenyu.cn/Article/details/gtqvjcktys.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.feifeiyinyue.top/Article/details/gtpkenurpw.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zycfv.cn/Article/details/gtztvnugxm.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.ybcxt.top/Article/details/gtitaaylto.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.jlsjyb.cn/Article/details/gtqyrtfqbn.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.yj20258888.top/Article/details/gttbeunwfi.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.haohaochexian.top/Article/details/gtfwlgsntz.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.yj20258.top/Article/details/gtsecblzam.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.guowangkeji.top/Article/details/gtydlnklgy.html

[P03] 生成短随机字符串
来源：http://dali.pycfn.com/Article/details/gtfncngbwb.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.316326.xyz/Article/details/gtcgzluxtk.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.hysaishi.cn/Article/details/gtbmiwmkwm.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.ybcxt.top/Article/details/gtvndqrfvl.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yueranfly.top/Article/details/gtisbispht.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.sysykeji.top/Article/details/gtqghaeygo.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.jyoumei.cn/Article/details/gtlqfyydrv.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.kuanghao11.cn/Article/details/gteownanay.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.hnqzz.top/Article/details/gtcfyuopzo.html

[P04] 求长度
来源：http://dali.hfpthk.cn/Article/details/gtbmesxdzr.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.cqqwz.cn/Article/details/gtlwwnkcxz.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.sysykeji.top/Article/details/gtvkrxzltg.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.ppjwa.cn/Article/details/gtekjwvjyi.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.gaohongyu789.top/Article/details/gtygxtkvrh.html

Java: list.size();  map.size();  s.length()
来源：http://dali.daxiang520.top/Article/details/gtdzpkgper.html

Go:   len(arr);  len(m)
来源：http://dali.xylfe.cn/Article/details/gtuladdviw.html

Ruby: x.length;  x.size
来源：http://dali.yueranfly.top/Article/details/gtzuzcxloo.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.shangyingyoupin.top/Article/details/gthrglmkek.html

[P05] 判断两个对象内容是否相等
来源：http://dali.zhongyouzk.top/Article/details/gtglkbhlkh.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.pycfn.com/Article/details/gtcfpscfgg.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.xziqi.cn/Article/details/gtjfplqdtv.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.wangdashe.top/Article/details/gtuluezzkm.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.nanxuanxn.top/Article/details/gtgdgouhfq.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlprbnxil.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.pycfn.com/Article/details/gtqpjqxnmn.html

Ruby: a == b
来源：http://dali.guannengcc.top/Article/details/gtwhhqvgjl.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.guowangkeji.top/Article/details/gtjmwrfghz.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.nwbrower.top/Article/details/gtdjlabqeg.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.shzxlz.cn/Article/details/gtbkjdfosm.html

PHP:  if (empty($x)) {}
来源：http://dali.chenzaomai.com/Article/details/gtvqfahuib.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.hnxiangtu.top/Article/details/gtvpsemgka.html

TS:   if (x == null) {}
来源：http://dali.c1oappe.top/Article/details/gtwfttgpks.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.dashuyun.cn/Article/details/gtzqdnprrv.html

Go:   if x == nil {}
来源：http://dali.andypj.xyz/Article/details/gtvyfuyjxg.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.ehwqpu.com/Article/details/gtyehxfxdl.html

C#:   if (x is null) {}
来源：http://dali.wangdashe.top/Article/details/gtdpsnjbff.html

[P07] 防抖与节流
来源：http://dali.guannengcc.top/Article/details/gtzgihyadp.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.nwbrower.top/Article/details/gtdgynaicn.html

PHP:  // 手写时间戳比较
来源：http://dali.pengpengdd.cyou/Article/details/gtduzkaach.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.316326.xyz/Article/details/gtsphthyoc.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.xinyue.icu/Article/details/gtvhlvgslr.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtovrkwvoh.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.chenlongwang.top/Article/details/gtboaddxyd.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.yueranfly.top/Article/details/gthbtqrfxr.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.guannengcc.top/Article/details/gtnlayylck.html

[P08] 处理浮点精度问题
来源：http://dali.zdqjudy.top/Article/details/gtcgndxlcb.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.xuanzx.com/Article/details/gtomdekfmr.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.shzxlz.cn/Article/details/gtxphcuptk.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.nanxinkj.top/Article/details/gtzmzkxbkp.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gthqgqmeem.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.shuidangran.top/Article/details/gtbezpaogj.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.dashuyun.cn/Article/details/gtheupnmbo.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.nwbrower.top/Article/details/gtnvaecveu.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.yanxiufei.cn/Article/details/gtlythpqmo.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtupwaihri.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.smart0.xyz/Article/details/gtfxgzjmnz.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtftwpthvw.html

[Q01] 创建表
来源：http://dali.quarkkingdee.top/Article/details/gtthhszwyc.html

CREATE TABLE users (
来源：http://dali.svipenyu.cn/Article/details/gtlfviezgg.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.ybcxt.top/Article/details/gtskfulrir.html

name VARCHAR(50) NOT NULL,
来源：http://dali.mhx1999.top/Article/details/gtevindkpu.html

email VARCHAR(100) UNIQUE,
来源：http://dali.sufxvd.cn/Article/details/gtviozryjc.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.gaohongyu789.top/Article/details/gtqmgacoce.html

);
来源：http://dali.jianghu66.top/Article/details/gtjmpfsdrx.html

[Q02] 创建带外键的表
来源：http://dali.cucudq.cn/Article/details/gtxuvftajk.html

CREATE TABLE orders (
来源：http://dali.haohaochexian.top/Article/details/gtduijumhf.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.cucudq.cn/Article/details/gttwdjqejb.html

user_id INT NOT NULL,
来源：http://dali.gogol.net.cn/Article/details/gtdxovejrd.html

amount DECIMAL(10, 2),
来源：http://dali.hnxiangtu.top/Article/details/gtpvdwsvnf.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.aizwys.cn/Article/details/gtegsiwwxr.html

);
来源：http://dali.sysykeji.top/Article/details/gtbvhnnjta.html

[Q03] 增加列
来源：http://dali.xinyue.icu/Article/details/gtyupnppjm.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.pycfn.com/Article/details/gtzviwiapa.html

[Q04] 修改列类型
来源：http://dali.jiagoushi.top/Article/details/gtfpswyskp.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.daxiang520.top/Article/details/gtqipwzzvs.html

[Q05] 重命名列
来源：http://dali.cdnleiting.top/Article/details/gtlgazqide.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.sufxvd.cn/Article/details/gtajpoxlem.html

[Q06] 删除列
来源：http://dali.shangyingyoupin.top/Article/details/gtngerixzc.html


<!-- 参考信息 -->