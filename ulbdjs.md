代发 wailian999

Ruby: exit 1
来源：http://dali.smart0.xyz/Article/details/gt2dwksasnr.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.fzhhl.top/Article/details/gt2pisfdldp.html

[M06] 向标准错误输出
来源：http://dali.yongpay.top/Article/details/gt2ksnljxhu.html

Py:   print("err", file=sys.stderr)
来源：http://dali.hnqzz.top/Article/details/gt2sgronpmw.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.haohaochexian.top/Article/details/gt2wqjvjaqa.html

JS:   console.error("err")
来源：http://dali.aibaodan.cn/Article/details/gt2afelcwqh.html

TS:   console.error("err")
来源：http://dali.hongshengwenyu.top/Article/details/gt2oqvquznf.html

Java: System.err.println("err")
来源：http://dali.tanke756.top/Article/details/gt2cxayeikh.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.tanke756.top/Article/details/gt2utvatxdy.html

Ruby: warn "err"
来源：http://dali.316326.xyz/Article/details/gt2ciuouooe.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.wangdashe.top/Article/details/gt2axzcpdki.html

[M07] 判断是否为主入口
来源：http://dali.fengsongda.top/Article/details/gt2gdyeveum.html

Py:   if __name__ == "__main__":
来源：http://dali.fengsongda.top/Article/details/gt2dazeidwt.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.ybcxt.top/Article/details/gt2wvdbkskt.html

JS:   require.main === module
来源：http://dali.ehwqpu.com/Article/details/gt2quldsxal.html

TS:   require.main === module
来源：http://dali.nanxuanxn.top/Article/details/gt2bltfqaxw.html

Java: public static void main(String[] args)
来源：http://dali.mhx1999.top/Article/details/gt2cgchgxkh.html

Go:   func main()
来源：http://dali.yangfankeji.com/Article/details/gt2oiqdeujm.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.yj20258888.top/Article/details/gt2duonencb.html

C#:   static void Main(string[] args)
来源：http://dali.ydzc1.top/Article/details/gt2svzhbtnv.html

[M08] 获取系统与运行时信息
来源：http://dali.shuidangran.top/Article/details/gt2ijxytoyj.html

Py:   platform.system();  platform.python_version()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2eanbmzih.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhoulong.xyz/Article/details/gt2gehicgch.html

JS:   process.platform;  process.version
来源：http://dali.bjfxy.top/Article/details/gt2yztflzoa.html

TS:   process.platform;  process.version
来源：http://dali.yvedp.cn/Article/details/gt2szcttkca.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.xinyue.icu/Article/details/gt2ggopfxpr.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.kuanghao11.cn/Article/details/gt2xnhruqxd.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vnsggsyk.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uisrtryr.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gt2cjbhpffk.html

N. 数据结构与算法
来源：http://dali.daxiang520.top/Article/details/gt2ebmmrtjc.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gt2iigghiss.html

[N01] 二分查找（有序数组）
来源：http://dali.meibo888.top/Article/details/gt2zivehond.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.xinyue.icu/Article/details/gt2bhwqjwtv.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.hnqzz.top/Article/details/gt2vgfiqwdo.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jinqigfzy.top/Article/details/gt2oypcaviy.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jlsjyb.cn/Article/details/gt2xoewztjv.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.cheryme.top/Article/details/gt2wszhuhmj.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.316326.xyz/Article/details/gt2ifgduwrg.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.316326.xyz/Article/details/gt2mxvdalsh.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.cucudq.cn/Article/details/gt2khcqwiic.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.cdnleiting.top/Article/details/gt2fdphlqst.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jqgfzy.top/Article/details/gt2smqudnxx.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.gaohongyu789.top/Article/details/gt2wixzjsmr.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.quarkkingdee.top/Article/details/gt2detohxor.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.snrcjt.cn/Article/details/gt2wzlovjhc.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.nanxinkj.top/Article/details/gt2zxyvxmhl.html

Go:   slices.Sort(arr)
来源：http://dali.jyoumei.cn/Article/details/gt2xjkyzfzh.html

Ruby: arr.sort
来源：http://dali.xuetiantiany.cn/Article/details/gt2qrymreoo.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhoulong.xyz/Article/details/gt2xpfjhmwb.html

[N03] 快速排序（分治示例）
来源：http://dali.9152youxi.cn/Article/details/gt2jknwphrw.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.redwolf501.top/Article/details/gt2avpzlsgo.html

PHP:  // 递归实现，或用 usort
来源：http://dali.gotoacloud.top/Article/details/gt2yddpiytx.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.sxryk.cn/Article/details/gt2bypsnenb.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhongyouzk.top/Article/details/gt2akevtjtg.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.xuetiantiany.cn/Article/details/gt2qmbbyxdy.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.hongshengwenyu.top/Article/details/gt2kazrzbnz.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.aibaodan.cn/Article/details/gt2wuwmkuwp.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.jianghu66.top/Article/details/gt2vxzujoij.html

[N04] 斐波那契数列
来源：http://dali.zhongyouzk.top/Article/details/gt2sodgxkil.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhengqikj.top/Article/details/gt2yvffkvqk.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.feifeiyinyue.top/Article/details/gt2qfcikphj.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.birdmap.top/Article/details/gt2faqvjate.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.gotoacloud.top/Article/details/gt2opxhvjdt.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.yanxiufei.cn/Article/details/gt2rrjstgix.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.yangfankeji.com/Article/details/gt2gukmxptu.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.tanke756.top/Article/details/gt2dnsqgtuy.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.jinqigfzy.top/Article/details/gt2nbmmdtvs.html

[N05] 最大公约数
来源：http://dali.mhx1999.top/Article/details/gt2eemietum.html

Py:   math.gcd(a, b)
来源：http://dali.cucudq.cn/Article/details/gt2srxkjbmf.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.sxryk.cn/Article/details/gt2usabrurn.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.havefunace.top/Article/details/gt2etzxeurn.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.cqqwz.cn/Article/details/gt2sdqbpktn.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.cashguo.top/Article/details/gt2myvozhcg.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.tanke756.top/Article/details/gt2rpovncvg.html

Ruby: a.gcd(b)
来源：http://dali.zdqjudy.top/Article/details/gt2hppmzblo.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.shangyingyoupin.top/Article/details/gt2alofizjr.html

[N06] 判断回文字符串
来源：http://dali.guannengcc.top/Article/details/gt2aqgyindd.html

Py:   s == s[::-1]
来源：http://dali.mhx1999.top/Article/details/gt2hyqiecgr.html

PHP:  $s === strrev($s);
来源：http://dali.birdmap.top/Article/details/gt2otxtprdo.html

JS:   s === [...s].reverse().join("")
来源：http://dali.kuanghao11.cn/Article/details/gt2msmusnjf.html

TS:   s === [...s].reverse().join("")
来源：http://dali.xuetiantiany.cn/Article/details/gt2igcyxvsf.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.meibo888.top/Article/details/gt2brdkekyl.html

Go:   // 双指针从两端比较
来源：http://dali.jqgufenzy.top/Article/details/gt2apxogglf.html

Ruby: s == s.reverse
来源：http://dali.shzxlz.cn/Article/details/gt2clgytcco.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.chenlongwang.top/Article/details/gt2dtialyzb.html

[N07] 两数之和（返回下标）
来源：http://dali.mhx1999.top/Article/details/gt2avyyccpr.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.yj20258888.top/Article/details/gt2logvjepp.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.yueranfly.top/Article/details/gt2slefmxho.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.jqgufenzy.top/Article/details/gt2ghalzlcj.html

TS:   // 手写 Map<string, number>
来源：http://dali.hnqzz.top/Article/details/gt2ugzgrawq.html

Java: // 手写 HashMap
来源：http://dali.iojbl.cn/Article/details/gt2zrftmtcl.html

Go:   // 手写 map[int]int
来源：http://dali.chenlongwang.top/Article/details/gt2ebogfsrz.html

Ruby: // 手写 Hash
来源：http://dali.havefunace.top/Article/details/gt2alirgrhp.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.guowangkeji.top/Article/details/gt2joheoves.html

[N08] 生成全排列
来源：http://dali.xuetiantiany.cn/Article/details/gt2xmymczkd.html

Py:   itertools.permutations(arr)
来源：http://dali.birdmap.top/Article/details/gt2pazylcbk.html

PHP:  // 手写递归交换
来源：http://dali.ppjwa.cn/Article/details/gt2cfzahboo.html

JS:   // 手写回溯递归
来源：http://dali.shuidangran.top/Article/details/gt2ngxrfvso.html

TS:   // 手写回溯递归
来源：http://dali.jinqigfzy.top/Article/details/gt2agakadxt.html

Java: // 手写回溯递归
来源：http://dali.wangdashe.top/Article/details/gt2ypgkqewr.html

Go:   // 手写回溯递归
来源：http://dali.xuetiantiany.cn/Article/details/gt2dknrpsuj.html

Ruby: arr.permutation.to_a
来源：http://dali.jyoumei.cn/Article/details/gt2yywypirp.html

C#:   // 手写回溯递归
来源：http://dali.sweek.top/Article/details/gt2dzjeftld.html

[N09] 栈与队列
来源：http://dali.aibaodan.cn/Article/details/gt2xhhspxdr.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.shuidangran.top/Article/details/gt2vjlzpxrm.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.dianchejie.cn/Article/details/gt2qklnoqdo.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.daria6918.cn/Article/details/gt2cswwulxx.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zycfv.cn/Article/details/gt2grpynuqr.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.shzxlz.cn/Article/details/gt2mnrogazc.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.cqqwz.cn/Article/details/gt2wjypbkuc.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.jinqigfzy.top/Article/details/gt2yjwbsgdz.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.hongshengwenyu.top/Article/details/gt2tksbmjhd.html

[N10] 链表节点定义
来源：http://dali.xinyue.icu/Article/details/gt2vgorpixa.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.vqdsnc.cn/Article/details/gt2dsroiaqv.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.aibaodan.cn/Article/details/gt2cgkthfxm.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.wangdashe.top/Article/details/gt2osrwyvma.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ewjgxmzk.html

Java: class Node { int v; Node next; }
来源：http://dali.cdnleiting.top/Article/details/gt2wydojqqp.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.sxryk.cn/Article/details/gt2jaynfoax.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.birdmap.top/Article/details/gt2wdxstxaf.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.yueranfly.top/Article/details/gt2jmcrahpl.html

[N11] 二叉树中序遍历
来源：http://dali.vqdsnc.cn/Article/details/gt2dizqynyi.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.redwolf501.top/Article/details/gt2umcdcldm.html

PHP:  // 手写递归函数
来源：http://dali.jqgfzy.top/Article/details/gt2dpfapmqo.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.dashuyun.cn/Article/details/gt2qmekaafs.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.meibo888.top/Article/details/gt2gnbhlxns.html

Java: // 手写递归
来源：http://dali.xylfe.cn/Article/details/gt2iddmqbwv.html

Go:   // 手写递归
来源：http://dali.chenlongwang.top/Article/details/gt2izxjikkx.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.ivvv.top/Article/details/gt2eeicucpy.html

C#:   // 手写递归
来源：http://dali.wangshuangyany.cn/Article/details/gt2jsczhxxv.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.yueranfly.top/Article/details/gt2oxmuwkmq.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.hnxiangtu.top/Article/details/gt2mmmilpwj.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.svipenyu.cn/Article/details/gt2gcgespyr.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zycfv.cn/Article/details/gt2phaguheb.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.sufxvd.cn/Article/details/gt2zaktuxvh.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jiagoushi.top/Article/details/gt2uwjalodz.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.havefunace.top/Article/details/gt2vumibwpd.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.yvedp.cn/Article/details/gt2rovcrafk.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.havefunace.top/Article/details/gt2tlvddvqn.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gt2svfzexlt.html

O. 并发与异步
来源：http://dali.jqgufenzy.top/Article/details/gt2lmoduceb.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gt2obmzjtzv.html

[O01] 启动一个线程
来源：http://dali.chenjidiqi.icu/Article/details/gt2hyieogsq.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.svipenyu.cn/Article/details/gt2rklctxoz.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.fengsongda.top/Article/details/gt2htgakxav.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.birdmap.top/Article/details/gt2gouurbel.html

TS:   // 同 JS
来源：http://dali.hnqzz.top/Article/details/gt2smuzsvxy.html

Java: new Thread(() -> f()).start()
来源：http://dali.nwbrower.top/Article/details/gt2aeceycvn.html

Go:   go f()
来源：http://dali.xuanzx.com/Article/details/gt2eokaunzy.html

Ruby: Thread.new { f }
来源：http://dali.chenzaomai.com/Article/details/gt2fmvnptbs.html

C#:   Task.Run(() => F());
来源：http://dali.haohaochexian.top/Article/details/gt2gqhvkycg.html

[O02] 使用线程池
来源：http://dali.gaohongyu789.top/Article/details/gt2eeexnpho.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jlhngrfo.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.yuxming.cn/Article/details/gt2dlpbumev.html

JS:   // worker_threads 线程池
来源：http://dali.guowangkeji.top/Article/details/gt2chtzdihh.html

TS:   // worker_threads 线程池
来源：http://dali.0kj1m.cn/Article/details/gt2nlddbeit.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.ehwqpu.com/Article/details/gt2qvypazrr.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.nanxinkj.top/Article/details/gt2bzqpggaq.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.hysaishi.cn/Article/details/gt2qvttwmtq.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.snrcjt.cn/Article/details/gt2sflrgwyu.html

[O03] 加锁保护共享数据
来源：http://dali.chenlongwang.top/Article/details/gt2okrxqqrj.html

Py:   with lock: shared += 1
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2sfbhxjkl.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.yonumen.top/Article/details/gt2cljuchre.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.shuidangran.top/Article/details/gt2vcvsaqxp.html

TS:   // 同 JS
来源：http://dali.chenzaomai.com/Article/details/gt2slcwsopn.html

Java: synchronized (this) { shared++; }
来源：http://dali.ppjwa.cn/Article/details/gt2uehlqlgn.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.gogol.net.cn/Article/details/gt2pbkbgchp.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.ydzc1.top/Article/details/gt2ocurjdoa.html

C#:   lock (gate) { shared++; }
来源：http://dali.0kj1m.cn/Article/details/gt2ujpgvrpu.html

[O04] 定义异步函数并等待
来源：http://dali.daria6918.cn/Article/details/gt2zmegxlmm.html

Py:   async def f():⏎    await g()
来源：http://dali.hnxiangtu.top/Article/details/gt2krckugqb.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.0kj1m.cn/Article/details/gt2akysphoc.html

JS:   async function f() { await g(); }
来源：http://dali.feifeiyinyue.top/Article/details/gt2iefnjjyx.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.yueranfly.top/Article/details/gt2gcafluov.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dcynzaqc.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.jiagoushi.top/Article/details/gt2sweetssj.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.c1oappe.top/Article/details/gt2wpoatacz.html

C#:   async Task F() { await G(); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2duapvvdf.html

[O05] 并发执行并等待全部完成
来源：http://dali.cashguo.top/Article/details/gt2apotfbjf.html

Py:   asyncio.gather(*tasks)
来源：http://dali.nanxuanxn.top/Article/details/gt2igmgsnno.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.yj20258.top/Article/details/gt2ddvuzjnr.html

JS:   await Promise.all(tasks)
来源：http://dali.aibaodan.cn/Article/details/gt2rqnkaxru.html

TS:   await Promise.all(tasks)
来源：http://dali.hywenlv.cn/Article/details/gt2zsmkafpa.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.haohaochexian.top/Article/details/gt2tbqahoqr.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2sjvgucat.html

Ruby: threads.map(&:join)
来源：http://dali.gotoacloud.top/Article/details/gt2ftmqpsgn.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.hfpthk.cn/Article/details/gt2eukyzghn.html

[O06] 使用进程池
来源：http://dali.yueranfly.top/Article/details/gt2xqbpsldu.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.yvedp.cn/Article/details/gt2uezmgqgl.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cgxwsxne.html

JS:   // child_process / cluster 模块
来源：http://dali.nwbrower.top/Article/details/gt2prurbuxa.html

TS:   // child_process / cluster 模块
来源：http://dali.ydzc1.top/Article/details/gt2vpclaaws.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.chenjidiqi.icu/Article/details/gt2uosrxxrq.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.jinqigufen.top/Article/details/gt2uwpmqojc.html

Ruby: // fork 块
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2impwybhw.html

C#:   Parallel.For
来源：http://dali.zhongyouzk.top/Article/details/gt2xrhdmgth.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gt2pepofket.html

P. 常用工具函数
来源：http://dali.jianghu66.top/Article/details/gt2bytxemyz.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gt2cpcsywhw.html

[P01] 生成 UUID
来源：http://dali.cashguo.top/Article/details/gt2lxzaorpb.html

Py:   str(uuid.uuid4())
来源：http://dali.yanxiufei.cn/Article/details/gt2qeamlavn.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.yongpay.top/Article/details/gt2spqphksc.html

JS:   crypto.randomUUID()
来源：http://dali.zhixingplan.top/Article/details/gt2ilmpjjjb.html

TS:   crypto.randomUUID()
来源：http://dali.hongshengwenyu.top/Article/details/gt2fydxcltc.html

Java: UUID.randomUUID().toString()
来源：http://dali.yonumen.top/Article/details/gt2ufglpgwt.html

Go:   // 用 github.com/google/uuid
来源：http://dali.tanke756.top/Article/details/gt2jyqapkdc.html

Ruby: SecureRandom.uuid
来源：http://dali.jqgfzy.top/Article/details/gt2btvsuwxd.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.havefunace.top/Article/details/gt2wgamzkia.html

[P02] MD5 / SHA256 摘要
来源：http://dali.redwolf501.top/Article/details/gt2wanzzrzs.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.gogol.net.cn/Article/details/gt2aefwuucu.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.vqdsnc.cn/Article/details/gt2gqtnlntb.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.yj20258.top/Article/details/gt2rtzoqato.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.andypj.xyz/Article/details/gt2atdzavku.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2ecdubjhj.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.yanxiufei.cn/Article/details/gt2dnghvuis.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.xuanzx.com/Article/details/gt2gapacpgp.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.hnqzz.top/Article/details/gt2uvucsiet.html

[P03] 生成短随机字符串
来源：http://dali.yj202588.top/Article/details/gt2ionnzgqe.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.hfpthk.cn/Article/details/gt2umrgwpmk.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.sweek.top/Article/details/gt2dxbqulcc.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yj20258.top/Article/details/gt2syslqmnn.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nquuwifl.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.jiagoushi.top/Article/details/gt2wmwysmxx.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.pengpengdd.cyou/Article/details/gt2pakpgsgy.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.jiagoushi.top/Article/details/gt2huwxlwzk.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.redwolf501.top/Article/details/gt2lrqwaset.html

[P04] 求长度
来源：http://dali.meibo888.top/Article/details/gt2ugccseal.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.tian-w.cn/Article/details/gt2uyzexljn.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.tianlin.xyz/Article/details/gt2dannceme.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jyoumei.cn/Article/details/gt2jhcvzzea.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jinqigufen.top/Article/details/gt2nvefchvs.html

Java: list.size();  map.size();  s.length()
来源：http://dali.yj20258.top/Article/details/gt2rlzxfzwn.html

Go:   len(arr);  len(m)
来源：http://dali.ybcxt.top/Article/details/gt2zrscmukm.html

Ruby: x.length;  x.size
来源：http://dali.quarkkingdee.top/Article/details/gt2jlbeufak.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.yj20258.top/Article/details/gt2vfmebdvg.html

[P05] 判断两个对象内容是否相等
来源：http://dali.c1oappe.top/Article/details/gt2eazwjsxu.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.yvedp.cn/Article/details/gt2fsifaepg.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.iojbl.cn/Article/details/gt2dbsnodfq.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.aibaodan.cn/Article/details/gt2hmvgiwtz.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.hywenlv.cn/Article/details/gt2ucgeigpa.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.tianlin.xyz/Article/details/gt2qhylappo.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.yongpay.top/Article/details/gt2ptaidfdl.html

Ruby: a == b
来源：http://dali.zdqjudy.top/Article/details/gt2ghsrnzms.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.jqgfzy.top/Article/details/gt2nlksnibj.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.jqgfzy.top/Article/details/gt2ldaldwun.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.chenlongwang.top/Article/details/gt2pxozdfuy.html

PHP:  if (empty($x)) {}
来源：http://dali.jianghu66.top/Article/details/gt2obtqkdiq.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.xuanzx.com/Article/details/gt2mmbaweau.html

TS:   if (x == null) {}
来源：http://dali.xylfe.cn/Article/details/gt2perulvbd.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.yj20258888.top/Article/details/gt2wccmwuhb.html

Go:   if x == nil {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cgphgjpw.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.fengsongda.top/Article/details/gt2dvmdzdyi.html

C#:   if (x is null) {}
来源：http://dali.havefunace.top/Article/details/gt2cveswjax.html

[P07] 防抖与节流
来源：http://dali.havefunace.top/Article/details/gt2ggairorr.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.andypj.xyz/Article/details/gt2visedxlw.html

PHP:  // 手写时间戳比较
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wpxqdzvi.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2awxrojfl.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhijiandao.cn/Article/details/gt2zpjcwanb.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.nanxinkj.top/Article/details/gt2uifiahne.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhengqikj.top/Article/details/gt2oztogipu.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.hysaishi.cn/Article/details/gt2zskfhiso.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.hywenlv.cn/Article/details/gt2bnnfphim.html

[P08] 处理浮点精度问题
来源：http://dali.hywenlv.cn/Article/details/gt2jfxwdrhd.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.ppjwa.cn/Article/details/gt2hfqrnugy.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.xinyue.icu/Article/details/gt2akwpnbdu.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.jinqigfzy.top/Article/details/gt2kbppoesl.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.shuidangran.top/Article/details/gt2sbelhpnu.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.yonumen.top/Article/details/gt2iyvdmrbp.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.wangshuangyany.cn/Article/details/gt2yjeuzazz.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.chenlongwang.top/Article/details/gt2lueaccur.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.jqgfzy.top/Article/details/gt2colrijlb.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gt2bejhzayf.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.smart0.xyz/Article/details/gt2zdqczbaa.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gt2jemxdyfl.html

[Q01] 创建表
来源：http://dali.vqdsnc.cn/Article/details/gt2ersufxza.html

CREATE TABLE users (
来源：http://dali.birdmap.top/Article/details/gt2nzbcqlzt.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.havefunace.top/Article/details/gt2qzaooaph.html

name VARCHAR(50) NOT NULL,
来源：http://dali.cheryme.top/Article/details/gt2fbufvwfg.html

email VARCHAR(100) UNIQUE,
来源：http://dali.hnxiangtu.top/Article/details/gt2bbpapdwm.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.fzhhl.top/Article/details/gt2ovqqniur.html

);
来源：http://dali.jqgufenzy.top/Article/details/gt2stywtdyr.html

[Q02] 创建带外键的表
来源：http://dali.meibo888.top/Article/details/gt2wfbjboaq.html

CREATE TABLE orders (
来源：http://dali.jinqigfzy.top/Article/details/gt2cjbkaccv.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.tianlin.xyz/Article/details/gt2mivrljjg.html

user_id INT NOT NULL,
来源：http://dali.zhiwuduotai.top/Article/details/gt2qjcwqapn.html

amount DECIMAL(10, 2),
来源：http://dali.tianlin.xyz/Article/details/gt2twioycvo.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.guowangkeji.top/Article/details/gt2bmvhoomn.html

);
来源：http://dali.pycfn.com/Article/details/gt2qgqfzjsd.html

[Q03] 增加列
来源：http://dali.ppjwa.cn/Article/details/gt2iurunmij.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.zdqjudy.top/Article/details/gt2ckwwujcw.html

[Q04] 修改列类型
来源：http://dali.hfpthk.cn/Article/details/gt2qmveigli.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.zhixingplan.top/Article/details/gt2dydtztjt.html

[Q05] 重命名列
来源：http://dali.fzhhl.top/Article/details/gt2dgxtcyec.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.jinqigufen.top/Article/details/gt2lwgszypn.html

[Q06] 删除列
来源：http://dali.yueranfly.top/Article/details/gt2ubpggavj.html

ALTER TABLE users DROP COLUMN age;
来源：http://dali.svipenyu.cn/Article/details/gt2lajiarqu.html

[Q07] 删除表
来源：http://dali.guowangkeji.top/Article/details/gt2oltrhdlp.html

DROP TABLE IF EXISTS orders;
来源：http://dali.smart0.xyz/Article/details/gt2rluvcufi.html

[Q08] 创建普通索引
来源：http://dali.c1oappe.top/Article/details/gt2hphjznun.html


<!-- 参考信息 -->