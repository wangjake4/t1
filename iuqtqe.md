代发 wailian999

JS:   process.exit(1)
来源：http://dali.zhongyouzk.top/Article/details/gt2yaocztae.html

TS:   process.exit(1)
来源：http://dali.aibaodan.cn/Article/details/gt2wgeiztjn.html

Java: System.exit(1)
来源：http://dali.zycfv.cn/Article/details/gt2tcalmfuy.html

Go:   os.Exit(1)
来源：http://dali.svipenyu.cn/Article/details/gt2biixborf.html

Ruby: exit 1
来源：http://dali.yanxiufei.cn/Article/details/gt2ckjlfzhf.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.yvedp.cn/Article/details/gt2gvuaeleq.html

[M06] 向标准错误输出
来源：http://dali.kuanghao11.cn/Article/details/gt2gqxogold.html

Py:   print("err", file=sys.stderr)
来源：http://dali.c1oappe.top/Article/details/gt2xccguiuc.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.jqgufenzy.top/Article/details/gt2axfxjdrm.html

JS:   console.error("err")
来源：http://dali.9152youxi.cn/Article/details/gt2syqkaprc.html

TS:   console.error("err")
来源：http://dali.iojbl.cn/Article/details/gt2hyefzdro.html

Java: System.err.println("err")
来源：http://dali.hysaishi.cn/Article/details/gt2rfreeneh.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.birdmap.top/Article/details/gt2uqhexdwy.html

Ruby: warn "err"
来源：http://dali.daxiang520.top/Article/details/gt2ypduqxfc.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.tianlin.xyz/Article/details/gt2ncconzvn.html

[M07] 判断是否为主入口
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cmwriweg.html

Py:   if __name__ == "__main__":
来源：http://dali.sxryk.cn/Article/details/gt2wqwliajk.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.dianchejie.cn/Article/details/gt2amckummj.html

JS:   require.main === module
来源：http://dali.yvedp.cn/Article/details/gt2mjaueehp.html

TS:   require.main === module
来源：http://dali.cdnleiting.top/Article/details/gt2ghvkrkal.html

Java: public static void main(String[] args)
来源：http://dali.mhx1999.top/Article/details/gt2xvcdvlds.html

Go:   func main()
来源：http://dali.gzhubu.top/Article/details/gt2hniibyhr.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.9152youxi.cn/Article/details/gt2qgmabxms.html

C#:   static void Main(string[] args)
来源：http://dali.zhongyouzk.top/Article/details/gt2jepmuwvu.html

[M08] 获取系统与运行时信息
来源：http://dali.yangfankeji.com/Article/details/gt2utxanzea.html

Py:   platform.system();  platform.python_version()
来源：http://dali.fengsongda.top/Article/details/gt2rylaxfjg.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.jqgufenzy.top/Article/details/gt2xfktsvlc.html

JS:   process.platform;  process.version
来源：http://dali.snrcjt.cn/Article/details/gt2eqjzkfvq.html

TS:   process.platform;  process.version
来源：http://dali.yonumen.top/Article/details/gt2vssyycjq.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.shangyingyoupin.top/Article/details/gt2lalnglvb.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.cucudq.cn/Article/details/gt2ykxpmjtw.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.wangdashe.top/Article/details/gt2djzzolnx.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.gogol.net.cn/Article/details/gt2xkihualm.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gt2gwtkpzvp.html

N. 数据结构与算法
来源：http://dali.yanxiufei.cn/Article/details/gt2szivsftq.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gt2rmetjyqo.html

[N01] 二分查找（有序数组）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lchbzsiu.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.fengsongda.top/Article/details/gt2lrgjuswt.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.mhx1999.top/Article/details/gt2egfcqzql.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.smart0.xyz/Article/details/gt2kyfmxmlt.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.wangshuangyany.cn/Article/details/gt2nwanvktx.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.c1oappe.top/Article/details/gt2psnawdzr.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhengqikj.top/Article/details/gt2yegpuhty.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.ehwqpu.com/Article/details/gt2woiblyvl.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.tanke756.top/Article/details/gt2pbbvszpn.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.xuetiantiany.cn/Article/details/gt2ujvujzda.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.daria6918.cn/Article/details/gt2ezprqvij.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.jianghu66.top/Article/details/gt2yzaxgprt.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.wangshuangyany.cn/Article/details/gt2ggyopusx.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.nwbrower.top/Article/details/gt2bzsqrfze.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.yongpay.top/Article/details/gt2dyciaurv.html

Go:   slices.Sort(arr)
来源：http://dali.shuidangran.top/Article/details/gt2nexprtqh.html

Ruby: arr.sort
来源：http://dali.vqdsnc.cn/Article/details/gt2jwiouqri.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.yueranfly.top/Article/details/gt2iabtxxwv.html

[N03] 快速排序（分治示例）
来源：http://dali.pengpengdd.cyou/Article/details/gt2tymspcsu.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2quwkfkxe.html

PHP:  // 递归实现，或用 usort
来源：http://dali.hongshengwenyu.top/Article/details/gt2bsjwvyii.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.wangshuangyany.cn/Article/details/gt2vhwmqdks.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yj20258.top/Article/details/gt2hazaqgwx.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.hongshengwenyu.top/Article/details/gt2mqlhqjae.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.fzhhl.top/Article/details/gt2uzknewyi.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.yj20258.top/Article/details/gt2kseyiizk.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.9152youxi.cn/Article/details/gt2usnwhfwv.html

[N04] 斐波那契数列
来源：http://dali.vqdsnc.cn/Article/details/gt2hiyabywy.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.birdmap.top/Article/details/gt2nevzxihw.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.ydzc1.top/Article/details/gt2pwecsloj.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jqgfzy.top/Article/details/gt2djggdzlg.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yvedp.cn/Article/details/gt2ceczoqeb.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.tanke756.top/Article/details/gt2wuweupay.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.sxryk.cn/Article/details/gt2ukndoepy.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.jianghu66.top/Article/details/gt2ghbqunts.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhixingplan.top/Article/details/gt2btcytasw.html

[N05] 最大公约数
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ofezjwdi.html

Py:   math.gcd(a, b)
来源：http://dali.pycfn.com/Article/details/gt2udhcprpk.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.yj20258888.top/Article/details/gt2ijbxaixq.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.snrcjt.cn/Article/details/gt2ldgdqnxg.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.bjfxy.top/Article/details/gt2novpvjtk.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.smart0.xyz/Article/details/gt2iazylnit.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.aibaodan.cn/Article/details/gt2ffquprul.html

Ruby: a.gcd(b)
来源：http://dali.snrcjt.cn/Article/details/gt2sygsfzfm.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.jyoumei.cn/Article/details/gt2bphtvmho.html

[N06] 判断回文字符串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cqvugknx.html

Py:   s == s[::-1]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dbusofxh.html

PHP:  $s === strrev($s);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lafgmbrl.html

JS:   s === [...s].reverse().join("")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ijoamjas.html

TS:   s === [...s].reverse().join("")
来源：http://dali.shzxlz.cn/Article/details/gt2qnthhstu.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.yvedp.cn/Article/details/gt2lbaizdla.html

Go:   // 双指针从两端比较
来源：http://dali.kuanghao11.cn/Article/details/gt2scmrhugi.html

Ruby: s == s.reverse
来源：http://dali.vqdsnc.cn/Article/details/gt2gsxyqmtw.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.birdmap.top/Article/details/gt2pnkzlpaz.html

[N07] 两数之和（返回下标）
来源：http://dali.hnqzz.top/Article/details/gt2udbsffjg.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.iojbl.cn/Article/details/gt2rcegdppw.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.0kj1m.cn/Article/details/gt2acuzeysg.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.tianlin.xyz/Article/details/gt2kzqrpwni.html

TS:   // 手写 Map<string, number>
来源：http://dali.ybcxt.top/Article/details/gt2hxdsfrck.html

Java: // 手写 HashMap
来源：http://dali.kuanghao11.cn/Article/details/gt2agbylneg.html

Go:   // 手写 map[int]int
来源：http://dali.hfpthk.cn/Article/details/gt2sgyvqcgk.html

Ruby: // 手写 Hash
来源：http://dali.hnxiangtu.top/Article/details/gt2foqpwfmx.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.ivvv.top/Article/details/gt2cwjnbsoi.html

[N08] 生成全排列
来源：http://dali.xuanzx.com/Article/details/gt2dalnxfhy.html

Py:   itertools.permutations(arr)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vcsquakn.html

PHP:  // 手写递归交换
来源：http://dali.sysykeji.top/Article/details/gt2lqylsdit.html

JS:   // 手写回溯递归
来源：http://dali.jiagoushi.top/Article/details/gt2qobtpier.html

TS:   // 手写回溯递归
来源：http://dali.nanxinkj.top/Article/details/gt2aagmzmzc.html

Java: // 手写回溯递归
来源：http://dali.xziqi.cn/Article/details/gt2ppuhyfxe.html

Go:   // 手写回溯递归
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2idulwgfs.html

Ruby: arr.permutation.to_a
来源：http://dali.andypj.xyz/Article/details/gt2ljuzmzro.html

C#:   // 手写回溯递归
来源：http://dali.ivvv.top/Article/details/gt2odlfqxcw.html

[N09] 栈与队列
来源：http://dali.dashuyun.cn/Article/details/gt2ybkwmkdu.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.wangdashe.top/Article/details/gt2gonmvufe.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.meibo888.top/Article/details/gt2jtktsser.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.wangdashe.top/Article/details/gt2cazafuuc.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.sufxvd.cn/Article/details/gt2mwxoyhck.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhoulong.xyz/Article/details/gt2kfsgtpkz.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.gaohongyu789.top/Article/details/gt2jfbsbnhw.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.andypj.xyz/Article/details/gt2qvysuhrz.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.ivvv.top/Article/details/gt2gihdikse.html

[N10] 链表节点定义
来源：http://dali.tian-w.cn/Article/details/gt2kvumzdtc.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.hysaishi.cn/Article/details/gt2ufqxwmbe.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.nwbrower.top/Article/details/gt2usistzih.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.hysaishi.cn/Article/details/gt2ppamzxwe.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.chenlongwang.top/Article/details/gt2nwolrqea.html

Java: class Node { int v; Node next; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2smgbarun.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.sysykeji.top/Article/details/gt2ggknthyq.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fiorxgup.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.hfpthk.cn/Article/details/gt2bbmkmsjg.html

[N11] 二叉树中序遍历
来源：http://dali.zhongyouzk.top/Article/details/gt2lpqccsrj.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.mhx1999.top/Article/details/gt2wltwkqkq.html

PHP:  // 手写递归函数
来源：http://dali.c1oappe.top/Article/details/gt2szhibbbg.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.shzxlz.cn/Article/details/gt2vrhopebh.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zdqjudy.top/Article/details/gt2zgtxxgzg.html

Java: // 手写递归
来源：http://dali.ppjwa.cn/Article/details/gt2ajfuqvgn.html

Go:   // 手写递归
来源：http://dali.feifeiyinyue.top/Article/details/gt2tfgtqmmy.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.ybcxt.top/Article/details/gt2qehackfe.html

C#:   // 手写递归
来源：http://dali.xuetiantiany.cn/Article/details/gt2yywtkvlk.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.feifeiyinyue.top/Article/details/gt2akoauwnl.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.cqqwz.cn/Article/details/gt2indgcobn.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.hnqzz.top/Article/details/gt2rbljgmzb.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.bjfxy.top/Article/details/gt2aeljxott.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.hnqzz.top/Article/details/gt2wjichsob.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.kuanghao11.cn/Article/details/gt2esoxondc.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.jinqigufen.top/Article/details/gt2lqgnwpxj.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.mhx1999.top/Article/details/gt2noltxsok.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.xylfe.cn/Article/details/gt2vtkwtizj.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gt2waeiibyr.html

O. 并发与异步
来源：http://dali.meibo888.top/Article/details/gt2hlpavrwo.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gt2frcthxgu.html

[O01] 启动一个线程
来源：http://dali.yangfankeji.com/Article/details/gt2melyrpbz.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.xziqi.cn/Article/details/gt2xtqufolh.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.pengpengdd.cyou/Article/details/gt2ijrlsahv.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.hfpthk.cn/Article/details/gt2lgeporqn.html

TS:   // 同 JS
来源：http://dali.zhongyouzk.top/Article/details/gt2uqcfkppr.html

Java: new Thread(() -> f()).start()
来源：http://dali.kuanghao11.cn/Article/details/gt2agmzgkzb.html

Go:   go f()
来源：http://dali.jianghu66.top/Article/details/gt2zbluisqh.html

Ruby: Thread.new { f }
来源：http://dali.gaohongyu789.top/Article/details/gt2tgwbjueb.html

C#:   Task.Run(() => F());
来源：http://dali.zhengqikj.top/Article/details/gt2slysiken.html

[O02] 使用线程池
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pddnigwk.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.jinqigufen.top/Article/details/gt2wtnzjzof.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jwnvylvb.html

JS:   // worker_threads 线程池
来源：http://dali.hywenlv.cn/Article/details/gt2boczysft.html

TS:   // worker_threads 线程池
来源：http://dali.jinqigufen.top/Article/details/gt2pmraaijt.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.nwbrower.top/Article/details/gt2gedkdpzd.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.gaohongyu789.top/Article/details/gt2vxtmhlhs.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.hywenlv.cn/Article/details/gt2eolnhuhj.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.shanyushiyangtech.top/Article/details/gt2oqgfkxcb.html

[O03] 加锁保护共享数据
来源：http://dali.chenlongwang.top/Article/details/gt2eftkeukl.html

Py:   with lock: shared += 1
来源：http://dali.pengpengdd.cyou/Article/details/gt2mqwftebf.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.shzxlz.cn/Article/details/gt2qgaprjwm.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.xuetiantiany.cn/Article/details/gt2fjqogsae.html

TS:   // 同 JS
来源：http://dali.havefunace.top/Article/details/gt2aesknajg.html

Java: synchronized (this) { shared++; }
来源：http://dali.yuanzhike.top/Article/details/gt2cddhzwft.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.yanxiufei.cn/Article/details/gt2dqimtsxn.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.meibo888.top/Article/details/gt2iwvtimkf.html

C#:   lock (gate) { shared++; }
来源：http://dali.sysykeji.top/Article/details/gt2kjvvjqeq.html

[O04] 定义异步函数并等待
来源：http://dali.xylfe.cn/Article/details/gt2brkmzkhg.html

Py:   async def f():⏎    await g()
来源：http://dali.zhengqikj.top/Article/details/gt2hnxyjfwj.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.yj20258.top/Article/details/gt2gnkacmlk.html

JS:   async function f() { await g(); }
来源：http://dali.zhiwuduotai.top/Article/details/gt2jjnrpouq.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.pengpengdd.cyou/Article/details/gt2bgjadphj.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.fzhhl.top/Article/details/gt2pctqussx.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.iojbl.cn/Article/details/gt2eboekbbm.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhiwuduotai.top/Article/details/gt2fiktnvtg.html

C#:   async Task F() { await G(); }
来源：http://dali.aizwys.cn/Article/details/gt2uyfiikho.html

[O05] 并发执行并等待全部完成
来源：http://dali.ybcxt.top/Article/details/gt2wkenlzdo.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhixingplan.top/Article/details/gt2ctczlyza.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.svipenyu.cn/Article/details/gt2bkbojevl.html

JS:   await Promise.all(tasks)
来源：http://dali.dashuyun.cn/Article/details/gt2volodkgz.html

TS:   await Promise.all(tasks)
来源：http://dali.quarkkingdee.top/Article/details/gt2nhdydstk.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.gotoacloud.top/Article/details/gt2wipzuhsp.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.tianlin.xyz/Article/details/gt2oftsyuyg.html

Ruby: threads.map(&:join)
来源：http://dali.cdnleiting.top/Article/details/gt2ahhorrwz.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.gogol.net.cn/Article/details/gt2wnvjhpzx.html

[O06] 使用进程池
来源：http://dali.zdqjudy.top/Article/details/gt2dyqhlrdb.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.xuanzx.com/Article/details/gt2rxnzhkyy.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.andypj.xyz/Article/details/gt2ewlkayhs.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2onntctba.html

TS:   // child_process / cluster 模块
来源：http://dali.zhengqikj.top/Article/details/gt2thzudijp.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.birdmap.top/Article/details/gt2timgqiay.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.cucudq.cn/Article/details/gt2ofvzrkwv.html

Ruby: // fork 块
来源：http://dali.iojbl.cn/Article/details/gt2rjsehpws.html

C#:   Parallel.For
来源：http://dali.gogol.net.cn/Article/details/gt2tizvluum.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gt2veofkmdi.html

P. 常用工具函数
来源：http://dali.gaohongyu789.top/Article/details/gt2lyhhfyhh.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gt2piiahlws.html

[P01] 生成 UUID
来源：http://dali.mhx1999.top/Article/details/gt2euyeunya.html

Py:   str(uuid.uuid4())
来源：http://dali.yj20258.top/Article/details/gt2afibrxkh.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.ehwqpu.com/Article/details/gt2dkbuxwgb.html

JS:   crypto.randomUUID()
来源：http://dali.gogol.net.cn/Article/details/gt2dnhjttbt.html

TS:   crypto.randomUUID()
来源：http://dali.kuanghao11.cn/Article/details/gt2jpqdjntl.html

Java: UUID.randomUUID().toString()
来源：http://dali.bjfxy.top/Article/details/gt2bxbyucyk.html

Go:   // 用 github.com/google/uuid
来源：http://dali.hongshengwenyu.top/Article/details/gt2dcjahhxx.html

Ruby: SecureRandom.uuid
来源：http://dali.dianchejie.cn/Article/details/gt2rrpwbgod.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.shuidangran.top/Article/details/gt2rsizsxsm.html

[P02] MD5 / SHA256 摘要
来源：http://dali.redwolf501.top/Article/details/gt2guaeitoi.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.c1oappe.top/Article/details/gt2tycifbcx.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.sufxvd.cn/Article/details/gt2wvcedqcq.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.yuanzhike.top/Article/details/gt2vkqcjgvr.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.nwbrower.top/Article/details/gt2vxdksrei.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhixingplan.top/Article/details/gt2yhdckdsu.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xyabtpuz.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.xylfe.cn/Article/details/gt2enwpwkdg.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.dianchejie.cn/Article/details/gt2bbfhcszi.html

[P03] 生成短随机字符串
来源：http://dali.guowangkeji.top/Article/details/gt2hcpogmpt.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.yangfankeji.com/Article/details/gt2nmolyfkb.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.tianlin.xyz/Article/details/gt2rcudrcii.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ondeaeoh.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uccxszpr.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.yuanzhike.top/Article/details/gt2zkghvygw.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.0kj1m.cn/Article/details/gt2bhxmxfks.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.yj202588.top/Article/details/gt2bxsmoxcw.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yvqnhwur.html

[P04] 求长度
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rdqrpeak.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.jianghu66.top/Article/details/gt2udrjpmfb.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.tanke756.top/Article/details/gt2uklvjtlz.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.hysaishi.cn/Article/details/gt2wdzikmah.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.birdmap.top/Article/details/gt2czkfxxre.html

Java: list.size();  map.size();  s.length()
来源：http://dali.cashguo.top/Article/details/gt2aiiwqvjt.html

Go:   len(arr);  len(m)
来源：http://dali.havefunace.top/Article/details/gt2toesnknq.html

Ruby: x.length;  x.size
来源：http://dali.yonumen.top/Article/details/gt2xaftgqyu.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.ppjwa.cn/Article/details/gt2qifembwt.html

[P05] 判断两个对象内容是否相等
来源：http://dali.yj202588.top/Article/details/gt2fkchoolr.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.yj20258888.top/Article/details/gt2kffmmzpw.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.yangfankeji.com/Article/details/gt2taftjyxo.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.xuanzx.com/Article/details/gt2lphqraxz.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.hammf.cn/Article/details/gt2bjlneslb.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gtliwxfz.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.sweek.top/Article/details/gt2qxaexqpa.html

Ruby: a == b
来源：http://dali.redwolf501.top/Article/details/gt2mewkpibr.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.shangyingyoupin.top/Article/details/gt2gmvqvcqb.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.hysaishi.cn/Article/details/gt2ciuofgze.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.gotoacloud.top/Article/details/gt2slkqpcqn.html

PHP:  if (empty($x)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rkzyjjhj.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.sysykeji.top/Article/details/gt2yolcqkiw.html

TS:   if (x == null) {}
来源：http://dali.vqdsnc.cn/Article/details/gt2vipfsvfr.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.chenzaomai.com/Article/details/gt2vxatbncw.html

Go:   if x == nil {}
来源：http://dali.andypj.xyz/Article/details/gt2rcjpqdnn.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.gzhubu.top/Article/details/gt2daelrtjd.html

C#:   if (x is null) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gjnuwrxi.html

[P07] 防抖与节流
来源：http://dali.xinyue.icu/Article/details/gt2ooileimj.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.cheryme.top/Article/details/gt2onkucwya.html

PHP:  // 手写时间戳比较
来源：http://dali.hysaishi.cn/Article/details/gt2lcjrnimq.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.dashuyun.cn/Article/details/gt2zekcrkmv.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yongpay.top/Article/details/gt2cqjambry.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.wangdashe.top/Article/details/gt2rieethiq.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.yanxiufei.cn/Article/details/gt2lwllitmd.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.dianchejie.cn/Article/details/gt2pooqceah.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.jinghuilouyu.cn/Article/details/gt2evwcyxwp.html

[P08] 处理浮点精度问题
来源：http://dali.gogol.net.cn/Article/details/gt2uavptiii.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.hnqzz.top/Article/details/gt2sbtdeadv.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.jlsjyb.cn/Article/details/gt2zsajusyi.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhongyouzk.top/Article/details/gt2jeycgarx.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.daria6918.cn/Article/details/gt2hgvryjyg.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.nanxinkj.top/Article/details/gt2yqjrqfrp.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.jqgfzy.top/Article/details/gt2vqsfegqh.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.shzxlz.cn/Article/details/gt2wkpgjbdi.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.zhixingplan.top/Article/details/gt2iaxgmubk.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gt2mqpqixpx.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.jyoumei.cn/Article/details/gt2ffwnmytu.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gt2yvnggyjx.html

[Q01] 创建表
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wjetpzbc.html

CREATE TABLE users (
来源：http://dali.ivvv.top/Article/details/gt2kivjquwa.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zycfv.cn/Article/details/gt2ldpmtpgi.html

name VARCHAR(50) NOT NULL,
来源：http://dali.smart0.xyz/Article/details/gt2enoaadir.html

email VARCHAR(100) UNIQUE,
来源：http://dali.shuidangran.top/Article/details/gt2tluyobqb.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.hnqzz.top/Article/details/gt2hhcnznfw.html

);
来源：http://dali.meibo888.top/Article/details/gt2fjjjprtb.html

[Q02] 创建带外键的表
来源：http://dali.quarkkingdee.top/Article/details/gt2fcstlihf.html

CREATE TABLE orders (
来源：http://dali.yvedp.cn/Article/details/gt2uzamwlzk.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2szvhtnec.html

user_id INT NOT NULL,
来源：http://dali.sufxvd.cn/Article/details/gt2dixutoru.html

amount DECIMAL(10, 2),
来源：http://dali.tian-w.cn/Article/details/gt2tulibsnu.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.xuetiantiany.cn/Article/details/gt2lrawlbju.html

);
来源：http://dali.yonumen.top/Article/details/gt2kwhzzjwo.html

[Q03] 增加列
来源：http://dali.zdqjudy.top/Article/details/gt2ghiltber.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.yvedp.cn/Article/details/gt2zwvfgqqn.html

[Q04] 修改列类型
来源：http://dali.tanke756.top/Article/details/gt2dxqberuv.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.shzxlz.cn/Article/details/gt2oyfopmrg.html

[Q05] 重命名列
来源：http://dali.sxryk.cn/Article/details/gt2tispnwgy.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.kuanghao11.cn/Article/details/gt2aplevudd.html

[Q06] 删除列
来源：http://dali.fzhhl.top/Article/details/gt2eexkdhyx.html


<!-- 参考信息 -->