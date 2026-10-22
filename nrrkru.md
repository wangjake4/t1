代发 wailian999

JS:   process.exit(1)
来源：http://dali.havefunace.top/Article/details/gt2jaaiezhv.html

TS:   process.exit(1)
来源：http://dali.hysaishi.cn/Article/details/gt2dannmboe.html

Java: System.exit(1)
来源：http://dali.sxryk.cn/Article/details/gt2fofkyinj.html

Go:   os.Exit(1)
来源：http://dali.zycfv.cn/Article/details/gt2qtnlfhvp.html

Ruby: exit 1
来源：http://dali.shangyingyoupin.top/Article/details/gt2dvcpvwyo.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.yuxming.cn/Article/details/gt2yunzrqrt.html

[M06] 向标准错误输出
来源：http://dali.haohaochexian.top/Article/details/gt2vcfigodr.html

Py:   print("err", file=sys.stderr)
来源：http://dali.jiagoushi.top/Article/details/gt2ejdgpdjk.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.redwolf501.top/Article/details/gt2mhrvayeg.html

JS:   console.error("err")
来源：http://dali.jiagoushi.top/Article/details/gt2hukzzoon.html

TS:   console.error("err")
来源：http://dali.yuanzhike.top/Article/details/gt2vfhazehx.html

Java: System.err.println("err")
来源：http://dali.dashuyun.cn/Article/details/gt2stuyasus.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.xinyue.icu/Article/details/gt2hxmfrkzb.html

Ruby: warn "err"
来源：http://dali.iojbl.cn/Article/details/gt2aqsksdxx.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.wangdashe.top/Article/details/gt2wyuroylb.html

[M07] 判断是否为主入口
来源：http://dali.shangyingyoupin.top/Article/details/gt2zparotwc.html

Py:   if __name__ == "__main__":
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vfjzcvjn.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.fzhhl.top/Article/details/gt2hastlyxx.html

JS:   require.main === module
来源：http://dali.xinyue.icu/Article/details/gt2pcflnsjt.html

TS:   require.main === module
来源：http://dali.c1oappe.top/Article/details/gt2izkihzjf.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2bkmmgano.html

Go:   func main()
来源：http://dali.guannengcc.top/Article/details/gt2vvhgmqyn.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.shuidangran.top/Article/details/gt2itqgigbi.html

C#:   static void Main(string[] args)
来源：http://dali.yongpay.top/Article/details/gt2iyqlopnb.html

[M08] 获取系统与运行时信息
来源：http://dali.ydzc1.top/Article/details/gt2sahtkqqf.html

Py:   platform.system();  platform.python_version()
来源：http://dali.daxiang520.top/Article/details/gt2ofjmkiez.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.sufxvd.cn/Article/details/gt2nqelhhrx.html

JS:   process.platform;  process.version
来源：http://dali.0kj1m.cn/Article/details/gt2sknvxskr.html

TS:   process.platform;  process.version
来源：http://dali.shzxlz.cn/Article/details/gt2wjswdeni.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.chenjidiqi.icu/Article/details/gt2kzssyzrw.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.jqgufenzy.top/Article/details/gt2pyrtcief.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.tianlin.xyz/Article/details/gt2emyxvbao.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.iojbl.cn/Article/details/gt2aglvqgnz.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gt2jkuoscoh.html

N. 数据结构与算法
来源：http://dali.zhengqikj.top/Article/details/gt2vpqzvzfw.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gt2ttpizybl.html

[N01] 二分查找（有序数组）
来源：http://dali.haohaochexian.top/Article/details/gt2lhfscane.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.hysaishi.cn/Article/details/gt2dcdasrbh.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.yueranfly.top/Article/details/gt2txxczasw.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.xylfe.cn/Article/details/gt2ymkmjiqw.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhiwuduotai.top/Article/details/gt2lmcyjirf.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.jqgfzy.top/Article/details/gt2yeholdmw.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.c1oappe.top/Article/details/gt2ifetpbkx.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.ydzc1.top/Article/details/gt2bvxduzpb.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.cucudq.cn/Article/details/gt2evksxftu.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.ppjwa.cn/Article/details/gt2qxjtzszx.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.gaohongyu789.top/Article/details/gt2aonoxxfi.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.jlsjyb.cn/Article/details/gt2jpqayagh.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.sxryk.cn/Article/details/gt2ncagbmca.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhongyouzk.top/Article/details/gt2qcllgepm.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.hysaishi.cn/Article/details/gt2bpdjnzst.html

Go:   slices.Sort(arr)
来源：http://dali.c1oappe.top/Article/details/gt2bjlbsauv.html

Ruby: arr.sort
来源：http://dali.jlsjyb.cn/Article/details/gt2fwmccakl.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.yuanzhike.top/Article/details/gt2nozlpncn.html

[N03] 快速排序（分治示例）
来源：http://dali.snrcjt.cn/Article/details/gt2gzekrnip.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.gogol.net.cn/Article/details/gt2dsazlyco.html

PHP:  // 递归实现，或用 usort
来源：http://dali.snrcjt.cn/Article/details/gt2fhjngsan.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhengqikj.top/Article/details/gt2piqzwjfq.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.tianlin.xyz/Article/details/gt2hqfkmfsq.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.yj20258.top/Article/details/gt2sefleagk.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.hysaishi.cn/Article/details/gt2lvjdomso.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.nanxinkj.top/Article/details/gt2bmbvolia.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.shzxlz.cn/Article/details/gt2azeydehw.html

[N04] 斐波那契数列
来源：http://dali.xinyue.icu/Article/details/gt2osrhkmfk.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.havefunace.top/Article/details/gt2mpxmkpgc.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zycfv.cn/Article/details/gt2buapkicg.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.shuidangran.top/Article/details/gt2usayntxo.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.nwbrower.top/Article/details/gt2pumqrtfc.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.gotoacloud.top/Article/details/gt2sxusblvf.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.jqgfzy.top/Article/details/gt2gzdacofe.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.jqgfzy.top/Article/details/gt2wyvmrdkq.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nnuevnyt.html

[N05] 最大公约数
来源：http://dali.wangdashe.top/Article/details/gt2elmdofhq.html

Py:   math.gcd(a, b)
来源：http://dali.zhongyouzk.top/Article/details/gt2hausrlhp.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.yvedp.cn/Article/details/gt2xavahaky.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.ydzc1.top/Article/details/gt2fgggvgld.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.bjfxy.top/Article/details/gt2qxymvjxs.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2vzpmmcad.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.svipenyu.cn/Article/details/gt2bkdcnqfl.html

Ruby: a.gcd(b)
来源：http://dali.shzxlz.cn/Article/details/gt2qijzabvl.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.shuidangran.top/Article/details/gt2kyifqvjq.html

[N06] 判断回文字符串
来源：http://dali.zhengqikj.top/Article/details/gt2ucyyofmv.html

Py:   s == s[::-1]
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rysnzkcs.html

PHP:  $s === strrev($s);
来源：http://dali.tianlin.xyz/Article/details/gt2hmleicil.html

JS:   s === [...s].reverse().join("")
来源：http://dali.yanxiufei.cn/Article/details/gt2szdincxm.html

TS:   s === [...s].reverse().join("")
来源：http://dali.yueranfly.top/Article/details/gt2cpkljsah.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.gotoacloud.top/Article/details/gt2bxxzhrzy.html

Go:   // 双指针从两端比较
来源：http://dali.gaohongyu789.top/Article/details/gt2xpjptmny.html

Ruby: s == s.reverse
来源：http://dali.gzhubu.top/Article/details/gt2gfvhxfpv.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.nanxinkj.top/Article/details/gt2cuyiwwri.html

[N07] 两数之和（返回下标）
来源：http://dali.hnxiangtu.top/Article/details/gt2wntzvvwr.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.jyoumei.cn/Article/details/gt2odhtttch.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.jianghu66.top/Article/details/gt2ykchqjze.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.wangdashe.top/Article/details/gt2gcifslss.html

TS:   // 手写 Map<string, number>
来源：http://dali.sufxvd.cn/Article/details/gt2sgnfuncc.html

Java: // 手写 HashMap
来源：http://dali.vqdsnc.cn/Article/details/gt2fiseicss.html

Go:   // 手写 map[int]int
来源：http://dali.chenzaomai.com/Article/details/gt2vnsguhuh.html

Ruby: // 手写 Hash
来源：http://dali.xziqi.cn/Article/details/gt2oibhxddj.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.hnqzz.top/Article/details/gt2jkkqcwxj.html

[N08] 生成全排列
来源：http://dali.9152youxi.cn/Article/details/gt2dejcmwpz.html

Py:   itertools.permutations(arr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rvzgiyuw.html

PHP:  // 手写递归交换
来源：http://dali.ivvv.top/Article/details/gt2pznpzwbc.html

JS:   // 手写回溯递归
来源：http://dali.daxiang520.top/Article/details/gt2llxwigeq.html

TS:   // 手写回溯递归
来源：http://dali.tianlin.xyz/Article/details/gt2yejhwrnc.html

Java: // 手写回溯递归
来源：http://dali.tanke756.top/Article/details/gt2mmziulve.html

Go:   // 手写回溯递归
来源：http://dali.chenjidiqi.icu/Article/details/gt2ztclgowe.html

Ruby: arr.permutation.to_a
来源：http://dali.yvedp.cn/Article/details/gt2ywdcrphb.html

C#:   // 手写回溯递归
来源：http://dali.vqdsnc.cn/Article/details/gt2eaysoyqo.html

[N09] 栈与队列
来源：http://dali.ivvv.top/Article/details/gt2qpplwrfh.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2btvdcjvb.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.birdmap.top/Article/details/gt2ngmdeprx.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.jiagoushi.top/Article/details/gt2kqyhaohv.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.yongpay.top/Article/details/gt2ygpvmcub.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.gzhubu.top/Article/details/gt2haxjtjid.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.sufxvd.cn/Article/details/gt2chcleiqh.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.yanxiufei.cn/Article/details/gt2dcxkzzpz.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.xuanzx.com/Article/details/gt2oyxugqtg.html

[N10] 链表节点定义
来源：http://dali.shangyingyoupin.top/Article/details/gt2yjmsltwb.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhixingplan.top/Article/details/gt2ulbsqfrm.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.jqgufenzy.top/Article/details/gt2jnpwbknp.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.hnxiangtu.top/Article/details/gt2lnxebkjr.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.yangfankeji.com/Article/details/gt2kqyguljm.html

Java: class Node { int v; Node next; }
来源：http://dali.jqgfzy.top/Article/details/gt2cpcgleup.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.jianghu66.top/Article/details/gt2adeiomvp.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.xylfe.cn/Article/details/gt2mnizairl.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.hnxiangtu.top/Article/details/gt2zqzkegxv.html

[N11] 二叉树中序遍历
来源：http://dali.gzhubu.top/Article/details/gt2yefemrln.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.tianlin.xyz/Article/details/gt2lqftlmka.html

PHP:  // 手写递归函数
来源：http://dali.xziqi.cn/Article/details/gt2fdxxuboe.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.hnqzz.top/Article/details/gt2amhmncbr.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.hammf.cn/Article/details/gt2nwcwzuxy.html

Java: // 手写递归
来源：http://dali.xinyue.icu/Article/details/gt2jvmhpups.html

Go:   // 手写递归
来源：http://dali.quarkkingdee.top/Article/details/gt2ifyclnxt.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.yueranfly.top/Article/details/gt2vlogwxyc.html

C#:   // 手写递归
来源：http://dali.chenlongwang.top/Article/details/gt2nwathprj.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.yuanzhike.top/Article/details/gt2attlbmjf.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2qrtrryag.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wpbgcnmt.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.shzxlz.cn/Article/details/gt2boflscxk.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.kuanghao11.cn/Article/details/gt2hfguhhou.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhoulong.xyz/Article/details/gt2ryvverli.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.yj202588.top/Article/details/gt2lqvcsubn.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.hnqzz.top/Article/details/gt2tqovpobu.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.dianchejie.cn/Article/details/gt2mtsndmtd.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gt2jsroynwe.html

O. 并发与异步
来源：http://dali.zycfv.cn/Article/details/gt2wvjkcntd.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gt2ocbqdhii.html

[O01] 启动一个线程
来源：http://dali.jqgufenzy.top/Article/details/gt2emgzedkh.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.yuanzhike.top/Article/details/gt2rrplqxpp.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.tanke756.top/Article/details/gt2rchaskub.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.hfpthk.cn/Article/details/gt2cynxvhac.html

TS:   // 同 JS
来源：http://dali.sysykeji.top/Article/details/gt2dfgechms.html

Java: new Thread(() -> f()).start()
来源：http://dali.xinyue.icu/Article/details/gt2kdqhorxa.html

Go:   go f()
来源：http://dali.birdmap.top/Article/details/gt2srtmesbd.html

Ruby: Thread.new { f }
来源：http://dali.bjfxy.top/Article/details/gt2dvfkzgee.html

C#:   Task.Run(() => F());
来源：http://dali.redwolf501.top/Article/details/gt2ofdqrcvv.html

[O02] 使用线程池
来源：http://dali.fzhhl.top/Article/details/gt2lawfwzhs.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.hammf.cn/Article/details/gt2nchkngop.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.jinqigfzy.top/Article/details/gt2ysvktlxx.html

JS:   // worker_threads 线程池
来源：http://dali.tanke756.top/Article/details/gt2jtcmxdtq.html

TS:   // worker_threads 线程池
来源：http://dali.cdnleiting.top/Article/details/gt2hhaidrmk.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.daria6918.cn/Article/details/gt2mgmllkxc.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.shangyingyoupin.top/Article/details/gt2qvsvkgug.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.yueranfly.top/Article/details/gt2dsuahfex.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.aizwys.cn/Article/details/gt2vkmrlwhy.html

[O03] 加锁保护共享数据
来源：http://dali.sweek.top/Article/details/gt2cezwvudu.html

Py:   with lock: shared += 1
来源：http://dali.cucudq.cn/Article/details/gt2dgyyqypj.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.ybcxt.top/Article/details/gt2evtbepid.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.sweek.top/Article/details/gt2qmthkgsi.html

TS:   // 同 JS
来源：http://dali.9152youxi.cn/Article/details/gt2fedomela.html

Java: synchronized (this) { shared++; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2orsawuuh.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.sysykeji.top/Article/details/gt2zzbcnepp.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.hammf.cn/Article/details/gt2mbacupko.html

C#:   lock (gate) { shared++; }
来源：http://dali.zycfv.cn/Article/details/gt2taqmwrbc.html

[O04] 定义异步函数并等待
来源：http://dali.haohaochexian.top/Article/details/gt2yyqarfwk.html

Py:   async def f():⏎    await g()
来源：http://dali.chenzaomai.com/Article/details/gt2yylutvco.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.wangshuangyany.cn/Article/details/gt2hgvkkftd.html

JS:   async function f() { await g(); }
来源：http://dali.sweek.top/Article/details/gt2rjvnaooy.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhiwuduotai.top/Article/details/gt2cmmgcihm.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.daria6918.cn/Article/details/gt2mjfoiogc.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.tanke756.top/Article/details/gt2toldgqwq.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.yueranfly.top/Article/details/gt2ofxomotm.html

C#:   async Task F() { await G(); }
来源：http://dali.fzhhl.top/Article/details/gt2kwmvgvta.html

[O05] 并发执行并等待全部完成
来源：http://dali.jyoumei.cn/Article/details/gt2nmdpgfon.html

Py:   asyncio.gather(*tasks)
来源：http://dali.jinqigufen.top/Article/details/gt2fgsmllbs.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.mhx1999.top/Article/details/gt2vdlcceog.html

JS:   await Promise.all(tasks)
来源：http://dali.hongshengwenyu.top/Article/details/gt2orjxjmax.html

TS:   await Promise.all(tasks)
来源：http://dali.ivvv.top/Article/details/gt2emwrxhbu.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.guannengcc.top/Article/details/gt2zekcjgof.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.gotoacloud.top/Article/details/gt2qricnkbb.html

Ruby: threads.map(&:join)
来源：http://dali.quarkkingdee.top/Article/details/gt2giynlnob.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.jqgufenzy.top/Article/details/gt2xxjglrla.html

[O06] 使用进程池
来源：http://dali.jlsjyb.cn/Article/details/gt2trnsffnk.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.yuanzhike.top/Article/details/gt2emsbqdpk.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.xuanzx.com/Article/details/gt2okwjghgx.html

JS:   // child_process / cluster 模块
来源：http://dali.wangshuangyany.cn/Article/details/gt2jidfukcq.html

TS:   // child_process / cluster 模块
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2aavfolgy.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.316326.xyz/Article/details/gt2ohygmvfr.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.fengsongda.top/Article/details/gt2wpmwfnpo.html

Ruby: // fork 块
来源：http://dali.gotoacloud.top/Article/details/gt2teacpaoy.html

C#:   Parallel.For
来源：http://dali.redwolf501.top/Article/details/gt2gidkqrer.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gt2erpxfizs.html

P. 常用工具函数
来源：http://dali.yueranfly.top/Article/details/gt2bofnrnny.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gt2zydlecyi.html

[P01] 生成 UUID
来源：http://dali.mhx1999.top/Article/details/gt2oyeckejx.html

Py:   str(uuid.uuid4())
来源：http://dali.nanxinkj.top/Article/details/gt2imwnyeit.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.xuanzx.com/Article/details/gt2uykvkvia.html

JS:   crypto.randomUUID()
来源：http://dali.gotoacloud.top/Article/details/gt2lqarysip.html

TS:   crypto.randomUUID()
来源：http://dali.ehwqpu.com/Article/details/gt2sijtaeju.html

Java: UUID.randomUUID().toString()
来源：http://dali.dashuyun.cn/Article/details/gt2nabtllhh.html

Go:   // 用 github.com/google/uuid
来源：http://dali.iojbl.cn/Article/details/gt2irqdcltj.html

Ruby: SecureRandom.uuid
来源：http://dali.yuanzhike.top/Article/details/gt2wnbplfev.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.shuidangran.top/Article/details/gt2fnewhpii.html

[P02] MD5 / SHA256 摘要
来源：http://dali.sxryk.cn/Article/details/gt2mkqajany.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.aibaodan.cn/Article/details/gt2qownejzn.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.cheryme.top/Article/details/gt2qbhnssxj.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.kuanghao11.cn/Article/details/gt2sgikppjj.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.jinqigufen.top/Article/details/gt2lbsnsndo.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.guannengcc.top/Article/details/gt2lsrjubhh.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhijiandao.cn/Article/details/gt2pedgfdze.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhengqikj.top/Article/details/gt2yonbebom.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.cucudq.cn/Article/details/gt2oybfxivw.html

[P03] 生成短随机字符串
来源：http://dali.hnxiangtu.top/Article/details/gt2nqvveuis.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.nanxinkj.top/Article/details/gt2oxfvfiwy.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xlidkewv.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.shzxlz.cn/Article/details/gt2zzrldyan.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.nanxuanxn.top/Article/details/gt2mggxbghw.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.smart0.xyz/Article/details/gt2lrcsqxdg.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zycfv.cn/Article/details/gt2ypdmoxdl.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhixingplan.top/Article/details/gt2asbgnfyq.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.chenjidiqi.icu/Article/details/gt2sbzwxpuw.html

[P04] 求长度
来源：http://dali.chenzaomai.com/Article/details/gt2qadvztcb.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.shzxlz.cn/Article/details/gt2ixsfjmob.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhengqikj.top/Article/details/gt2jtvyfzfa.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.hnxiangtu.top/Article/details/gt2yfolakmb.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.hongshengwenyu.top/Article/details/gt2vzzilejr.html

Java: list.size();  map.size();  s.length()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ylmpgivi.html

Go:   len(arr);  len(m)
来源：http://dali.yj20258.top/Article/details/gt2morvsmaa.html

Ruby: x.length;  x.size
来源：http://dali.cashguo.top/Article/details/gt2ptqlbqxj.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.shuidangran.top/Article/details/gt2wjfdxxcz.html

[P05] 判断两个对象内容是否相等
来源：http://dali.hysaishi.cn/Article/details/gt2mfukcdln.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.yanxiufei.cn/Article/details/gt2pakkhkke.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.jqgfzy.top/Article/details/gt2txvhywrt.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.daxiang520.top/Article/details/gt2hpwoaneh.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.jinqigfzy.top/Article/details/gt2jwavrdhu.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zdqjudy.top/Article/details/gt2czcaunsp.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2skaqwkgx.html

Ruby: a == b
来源：http://dali.jiagoushi.top/Article/details/gt2fokmyuoy.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhijiandao.cn/Article/details/gt2bqkbcpaq.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.chenzaomai.com/Article/details/gt2kdzjagfm.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.svipenyu.cn/Article/details/gt2ghkiwmrt.html

PHP:  if (empty($x)) {}
来源：http://dali.bjfxy.top/Article/details/gt2rgxiivkj.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.xuanzx.com/Article/details/gt2ktucfayr.html

TS:   if (x == null) {}
来源：http://dali.nanxinkj.top/Article/details/gt2zqkziafv.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.yvedp.cn/Article/details/gt2kcmmvvsy.html

Go:   if x == nil {}
来源：http://dali.gogol.net.cn/Article/details/gt2qjtdzfyk.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.316326.xyz/Article/details/gt2ahfrulic.html

C#:   if (x is null) {}
来源：http://dali.sysykeji.top/Article/details/gt2xpwolfuj.html

[P07] 防抖与节流
来源：http://dali.cucudq.cn/Article/details/gt2gmvlduah.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.birdmap.top/Article/details/gt2savpraqu.html

PHP:  // 手写时间戳比较
来源：http://dali.sysykeji.top/Article/details/gt2krgtjtnz.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.xuetiantiany.cn/Article/details/gt2fgchtnfw.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.smart0.xyz/Article/details/gt2pzwdchji.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.jyoumei.cn/Article/details/gt2gguatyrf.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zdqjudy.top/Article/details/gt2fkrustrn.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.chenlongwang.top/Article/details/gt2spbkcauf.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.hywenlv.cn/Article/details/gt2dkbkloer.html

[P08] 处理浮点精度问题
来源：http://dali.cqqwz.cn/Article/details/gt2vwrhbgiv.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.pycfn.com/Article/details/gt2phpvoner.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.cucudq.cn/Article/details/gt2izbukjfq.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.svipenyu.cn/Article/details/gt2jogasajl.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.hywenlv.cn/Article/details/gt2rjycenhl.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zhixingplan.top/Article/details/gt2atofhteu.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dihcqicx.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.snrcjt.cn/Article/details/gt2vdpoehov.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.yuanzhike.top/Article/details/gt2latosvoa.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gt2xrvtakqi.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.pengpengdd.cyou/Article/details/gt2iynkafmu.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gt2gzkfvsbl.html

[Q01] 创建表
来源：http://dali.haohaochexian.top/Article/details/gt2qdjlounl.html

CREATE TABLE users (
来源：http://dali.jqgfzy.top/Article/details/gt2tuuegllf.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.nwbrower.top/Article/details/gt2ejvmnogc.html

name VARCHAR(50) NOT NULL,
来源：http://dali.nanxuanxn.top/Article/details/gt2wknsulpx.html

email VARCHAR(100) UNIQUE,
来源：http://dali.jiagoushi.top/Article/details/gt2fwwbatwb.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.birdmap.top/Article/details/gt2bshxrkby.html

);
来源：http://dali.cdnleiting.top/Article/details/gt2lmjhwxep.html

[Q02] 创建带外键的表
来源：http://dali.hongshengwenyu.top/Article/details/gt2uyewbwga.html

CREATE TABLE orders (
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xlqotfgw.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.hnqzz.top/Article/details/gt2apkyubiu.html

user_id INT NOT NULL,
来源：http://dali.kuanghao11.cn/Article/details/gt2njppmrhq.html

amount DECIMAL(10, 2),
来源：http://dali.yueranfly.top/Article/details/gt2etdzetnr.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.jinqigufen.top/Article/details/gt2fxjzrjhp.html

);
来源：http://dali.yueranfly.top/Article/details/gt2ubnbujts.html

[Q03] 增加列
来源：http://dali.wangshuangyany.cn/Article/details/gt2hpanygup.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.hongshengwenyu.top/Article/details/gt2bauelpqw.html

[Q04] 修改列类型
来源：http://dali.c1oappe.top/Article/details/gt2xeicyiin.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.redwolf501.top/Article/details/gt2cddkylwv.html

[Q05] 重命名列
来源：http://dali.xuanzx.com/Article/details/gt2kwrukxtk.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.yuanzhike.top/Article/details/gt2ckmaewxw.html

[Q06] 删除列
来源：http://dali.dashuyun.cn/Article/details/gt2oxzfzqby.html


<!-- 参考信息 -->