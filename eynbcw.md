代发 wailian999

JS:   process.exit(1)
来源：http://dali.redwolf501.top/Article/details/gt2xqgadlqm.html

TS:   process.exit(1)
来源：http://dali.ppjwa.cn/Article/details/gt2qdhogqcd.html

Java: System.exit(1)
来源：http://dali.tian-w.cn/Article/details/gt2aettohzs.html

Go:   os.Exit(1)
来源：http://dali.svipenyu.cn/Article/details/gt2rdqnxqmm.html

Ruby: exit 1
来源：http://dali.sysykeji.top/Article/details/gt2ddmhaswn.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.hfpthk.cn/Article/details/gt2xdvtkmfu.html

[M06] 向标准错误输出
来源：http://dali.ydzc1.top/Article/details/gt2sxxysshe.html

Py:   print("err", file=sys.stderr)
来源：http://dali.ivvv.top/Article/details/gt2ogbfnclt.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.tian-w.cn/Article/details/gt2dozcwhuo.html

JS:   console.error("err")
来源：http://dali.zdqjudy.top/Article/details/gt2hrvxigwc.html

TS:   console.error("err")
来源：http://dali.guannengcc.top/Article/details/gt2sysstaqf.html

Java: System.err.println("err")
来源：http://dali.pengpengdd.cyou/Article/details/gt2vmrcfuvh.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.jianghu66.top/Article/details/gt2padguymy.html

Ruby: warn "err"
来源：http://dali.gogol.net.cn/Article/details/gt2vdrivgry.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2sjhomnzp.html

[M07] 判断是否为主入口
来源：http://dali.nanxuanxn.top/Article/details/gt2wyfpkvcd.html

Py:   if __name__ == "__main__":
来源：http://dali.meibo888.top/Article/details/gt2nefsztoe.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.jqgfzy.top/Article/details/gt2sngkphnn.html

JS:   require.main === module
来源：http://dali.chenlongwang.top/Article/details/gt2xntnwayd.html

TS:   require.main === module
来源：http://dali.dianchejie.cn/Article/details/gt2jvedapxp.html

Java: public static void main(String[] args)
来源：http://dali.mhx1999.top/Article/details/gt2lfmwugnm.html

Go:   func main()
来源：http://dali.dianchejie.cn/Article/details/gt2dsvzskzw.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.ivvv.top/Article/details/gt2ddcgczla.html

C#:   static void Main(string[] args)
来源：http://dali.iojbl.cn/Article/details/gt2eulxjeue.html

[M08] 获取系统与运行时信息
来源：http://dali.zhengqikj.top/Article/details/gt2uboxfmgb.html

Py:   platform.system();  platform.python_version()
来源：http://dali.tanke756.top/Article/details/gt2htbqyben.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.tian-w.cn/Article/details/gt2ejzjeicj.html

JS:   process.platform;  process.version
来源：http://dali.ybcxt.top/Article/details/gt2zuvtxfhv.html

TS:   process.platform;  process.version
来源：http://dali.zhoulong.xyz/Article/details/gt2ntciebcn.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.wangdashe.top/Article/details/gt2xkerefdt.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2muzdubji.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.yj20258888.top/Article/details/gt2ewjdyxzx.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.gzhubu.top/Article/details/gt2omeplohy.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gt2xnwqsbcg.html

N. 数据结构与算法
来源：http://dali.tian-w.cn/Article/details/gt2pzjnnliw.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gt2znfxawye.html

[N01] 二分查找（有序数组）
来源：http://dali.shzxlz.cn/Article/details/gt2hbpepodm.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.feifeiyinyue.top/Article/details/gt2cqnkbvee.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zdqjudy.top/Article/details/gt2crcnxwvw.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.shzxlz.cn/Article/details/gt2ashpfxfx.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.gzhubu.top/Article/details/gt2vcggbpod.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.xuetiantiany.cn/Article/details/gt2dimvlfsg.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.c1oappe.top/Article/details/gt2vstamrin.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.yongpay.top/Article/details/gt2qqoyteig.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2oxrkvrfs.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.chenlongwang.top/Article/details/gt2esjjvrzg.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.sysykeji.top/Article/details/gt2wraoljnc.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.nwbrower.top/Article/details/gt2lygyvmoy.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jqgfzy.top/Article/details/gt2geyjnkmh.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.sufxvd.cn/Article/details/gt2ktdqszpc.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.jiagoushi.top/Article/details/gt2lpmzhzkw.html

Go:   slices.Sort(arr)
来源：http://dali.ybcxt.top/Article/details/gt2xhpfwhab.html

Ruby: arr.sort
来源：http://dali.yonumen.top/Article/details/gt2qhmoyqpp.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ortvnlln.html

[N03] 快速排序（分治示例）
来源：http://dali.cheryme.top/Article/details/gt2zktjeiky.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.tanke756.top/Article/details/gt2bzhzxdly.html

PHP:  // 递归实现，或用 usort
来源：http://dali.gotoacloud.top/Article/details/gt2xrzrelfn.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.pengpengdd.cyou/Article/details/gt2xpmkgadt.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.tianlin.xyz/Article/details/gt2jwxmoyvq.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.aibaodan.cn/Article/details/gt2fldmuczb.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.sufxvd.cn/Article/details/gt2jsbbgltp.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.guannengcc.top/Article/details/gt2hxygchkm.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.ivvv.top/Article/details/gt2fxleraql.html

[N04] 斐波那契数列
来源：http://dali.hywenlv.cn/Article/details/gt2bfdowgwj.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.jqgfzy.top/Article/details/gt2gdlldnwl.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.ppjwa.cn/Article/details/gt2inmstors.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yangfankeji.com/Article/details/gt2fugjqhem.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.tian-w.cn/Article/details/gt2mjlmsuxq.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhengqikj.top/Article/details/gt2wvwaxsen.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.andypj.xyz/Article/details/gt2ldsijdkg.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.sxryk.cn/Article/details/gt2rnkdrrjz.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mhottevd.html

[N05] 最大公约数
来源：http://dali.feifeiyinyue.top/Article/details/gt2fordowua.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2lgutejhh.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zukfyjrb.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.cqqwz.cn/Article/details/gt2oquokadb.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhixingplan.top/Article/details/gt2okbqysvs.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.tian-w.cn/Article/details/gt2jdbihbam.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.snrcjt.cn/Article/details/gt2fdmdyvyp.html

Ruby: a.gcd(b)
来源：http://dali.xuetiantiany.cn/Article/details/gt2bwcnngsj.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.jqgfzy.top/Article/details/gt2qculasct.html

[N06] 判断回文字符串
来源：http://dali.yuanzhike.top/Article/details/gt2scnukjje.html

Py:   s == s[::-1]
来源：http://dali.shzxlz.cn/Article/details/gt2mxtpdsmv.html

PHP:  $s === strrev($s);
来源：http://dali.jyoumei.cn/Article/details/gt2acaiplgx.html

JS:   s === [...s].reverse().join("")
来源：http://dali.pycfn.com/Article/details/gt2atccsrgj.html

TS:   s === [...s].reverse().join("")
来源：http://dali.jlsjyb.cn/Article/details/gt2uetlumui.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.hongshengwenyu.top/Article/details/gt2kwpxqnej.html

Go:   // 双指针从两端比较
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yfihkbkt.html

Ruby: s == s.reverse
来源：http://dali.wangshuangyany.cn/Article/details/gt2jbbyovpr.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.0kj1m.cn/Article/details/gt2uwctyrtd.html

[N07] 两数之和（返回下标）
来源：http://dali.havefunace.top/Article/details/gt2smuxslje.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.xuetiantiany.cn/Article/details/gt2tisdgqpn.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2eneodwlq.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.feifeiyinyue.top/Article/details/gt2frkbgdar.html

TS:   // 手写 Map<string, number>
来源：http://dali.yueranfly.top/Article/details/gt2yefxhtng.html

Java: // 手写 HashMap
来源：http://dali.yuanzhike.top/Article/details/gt2gwbkssdj.html

Go:   // 手写 map[int]int
来源：http://dali.sxryk.cn/Article/details/gt2siggfgqe.html

Ruby: // 手写 Hash
来源：http://dali.nanxinkj.top/Article/details/gt2gfdeaqma.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.shzxlz.cn/Article/details/gt2aiyrpalz.html

[N08] 生成全排列
来源：http://dali.xuetiantiany.cn/Article/details/gt2eqmberjq.html

Py:   itertools.permutations(arr)
来源：http://dali.pycfn.com/Article/details/gt2syjffhbs.html

PHP:  // 手写递归交换
来源：http://dali.kuanghao11.cn/Article/details/gt2rpijagzs.html

JS:   // 手写回溯递归
来源：http://dali.shangyingyoupin.top/Article/details/gt2rgmtrpsg.html

TS:   // 手写回溯递归
来源：http://dali.aizwys.cn/Article/details/gt2daukhoxa.html

Java: // 手写回溯递归
来源：http://dali.gogol.net.cn/Article/details/gt2qbveypxa.html

Go:   // 手写回溯递归
来源：http://dali.snrcjt.cn/Article/details/gt2qibdjjig.html

Ruby: arr.permutation.to_a
来源：http://dali.xziqi.cn/Article/details/gt2gttapdyr.html

C#:   // 手写回溯递归
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qbfjqlnr.html

[N09] 栈与队列
来源：http://dali.chenjidiqi.icu/Article/details/gt2vehqomdo.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ljztxqim.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhixingplan.top/Article/details/gt2zlxohcdl.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.bjfxy.top/Article/details/gt2tdsscsjs.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.meibo888.top/Article/details/gt2zjbiozpe.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2pjfbclni.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhengqikj.top/Article/details/gt2amxyrqzy.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.svipenyu.cn/Article/details/gt2szmmhfzy.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.xuanzx.com/Article/details/gt2leholgqp.html

[N10] 链表节点定义
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2twwucent.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.cucudq.cn/Article/details/gt2stgheplh.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.yj20258888.top/Article/details/gt2cqpwjbmd.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.jinqigufen.top/Article/details/gt2artahqyu.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.ybcxt.top/Article/details/gt2opvlikmr.html

Java: class Node { int v; Node next; }
来源：http://dali.hysaishi.cn/Article/details/gt2lyqhgpkb.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.yj202588.top/Article/details/gt2pwvmmksd.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.shuidangran.top/Article/details/gt2giqewhan.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.dashuyun.cn/Article/details/gt2qbupslgo.html

[N11] 二叉树中序遍历
来源：http://dali.fzhhl.top/Article/details/gt2tcqttpmh.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.andypj.xyz/Article/details/gt2spgbfuah.html

PHP:  // 手写递归函数
来源：http://dali.iojbl.cn/Article/details/gt2abkpdkpw.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.birdmap.top/Article/details/gt2lruucnnu.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.dianchejie.cn/Article/details/gt2odzefhbc.html

Java: // 手写递归
来源：http://dali.yvedp.cn/Article/details/gt2bahkbreh.html

Go:   // 手写递归
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jliybvpe.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.bjfxy.top/Article/details/gt2ywrtuavc.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2suwhtytc.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.fzhhl.top/Article/details/gt2mlyztuhf.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.tanke756.top/Article/details/gt2jwgbwslu.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.jinqigufen.top/Article/details/gt2vftbqmrs.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.wangdashe.top/Article/details/gt2ajepbukj.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.gogol.net.cn/Article/details/gt2gljcxzsd.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.quarkkingdee.top/Article/details/gt2ztwdryco.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.hnqzz.top/Article/details/gt2eouinpph.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.xziqi.cn/Article/details/gt2vwupoesw.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.vqdsnc.cn/Article/details/gt2xyworjnb.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gt2issdepjy.html

O. 并发与异步
来源：http://dali.zdqjudy.top/Article/details/gt2xjffdifp.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2owrcasag.html

[O01] 启动一个线程
来源：http://dali.dashuyun.cn/Article/details/gt2zydtzrrh.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.guannengcc.top/Article/details/gt2wctvunbm.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.yj20258888.top/Article/details/gt2sqehiolj.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.ppjwa.cn/Article/details/gt2jcxpgtlk.html

TS:   // 同 JS
来源：http://dali.tianlin.xyz/Article/details/gt2juasuwjl.html

Java: new Thread(() -> f()).start()
来源：http://dali.jinqigfzy.top/Article/details/gt2gwzsbuje.html

Go:   go f()
来源：http://dali.jiagoushi.top/Article/details/gt2opkrdbvi.html

Ruby: Thread.new { f }
来源：http://dali.hnxiangtu.top/Article/details/gt2kanwdppz.html

C#:   Task.Run(() => F());
来源：http://dali.chenzaomai.com/Article/details/gt2vqbynexv.html

[O02] 使用线程池
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uqiuvqkx.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2dnhclptq.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.chenlongwang.top/Article/details/gt2qozbqmfk.html

JS:   // worker_threads 线程池
来源：http://dali.xylfe.cn/Article/details/gt2urcdqszq.html

TS:   // worker_threads 线程池
来源：http://dali.ybcxt.top/Article/details/gt2mxjkmlol.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.smart0.xyz/Article/details/gt2pxkqlhte.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.yj20258.top/Article/details/gt2qyuarovg.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2ofqwvnkl.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yvkvaitc.html

[O03] 加锁保护共享数据
来源：http://dali.pycfn.com/Article/details/gt2qesyyoms.html

Py:   with lock: shared += 1
来源：http://dali.hywenlv.cn/Article/details/gt2hmptupca.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.jianghu66.top/Article/details/gt2abkqdgta.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jltxtzih.html

TS:   // 同 JS
来源：http://dali.gogol.net.cn/Article/details/gt2qunuaphe.html

Java: synchronized (this) { shared++; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kvomqwsf.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.jinqigfzy.top/Article/details/gt2htmcnolb.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.fengsongda.top/Article/details/gt2zaeukyxn.html

C#:   lock (gate) { shared++; }
来源：http://dali.fengsongda.top/Article/details/gt2jtsplcnz.html

[O04] 定义异步函数并等待
来源：http://dali.nanxuanxn.top/Article/details/gt2shnqeibh.html

Py:   async def f():⏎    await g()
来源：http://dali.tanke756.top/Article/details/gt2qwiszfmm.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.gzhubu.top/Article/details/gt2fwrmyiby.html

JS:   async function f() { await g(); }
来源：http://dali.gzhubu.top/Article/details/gt2rcqsnocl.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.vqdsnc.cn/Article/details/gt2sjuefxvr.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhixingplan.top/Article/details/gt2bqnlazeq.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.wangshuangyany.cn/Article/details/gt2rarhmmxl.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.tianlin.xyz/Article/details/gt2qjrwwmba.html

C#:   async Task F() { await G(); }
来源：http://dali.dianchejie.cn/Article/details/gt2nfcnsuiq.html

[O05] 并发执行并等待全部完成
来源：http://dali.xuanzx.com/Article/details/gt2kzfcpqhv.html

Py:   asyncio.gather(*tasks)
来源：http://dali.cashguo.top/Article/details/gt2cqrlhsgv.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.chenjidiqi.icu/Article/details/gt2mzneyias.html

JS:   await Promise.all(tasks)
来源：http://dali.cqqwz.cn/Article/details/gt2fidyncah.html

TS:   await Promise.all(tasks)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rrhguhhl.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.dianchejie.cn/Article/details/gt2epthofpj.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.jqgfzy.top/Article/details/gt2wbnvkcxt.html

Ruby: threads.map(&:join)
来源：http://dali.haohaochexian.top/Article/details/gt2gtdjzvrp.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.jyoumei.cn/Article/details/gt2bxystfmz.html

[O06] 使用进程池
来源：http://dali.cdnleiting.top/Article/details/gt2rreptazu.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhengqikj.top/Article/details/gt2hcvojnys.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.yj20258888.top/Article/details/gt2avolwjtx.html

JS:   // child_process / cluster 模块
来源：http://dali.cashguo.top/Article/details/gt2kweyllwx.html

TS:   // child_process / cluster 模块
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ffbwhvjj.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mzxedgcl.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.cucudq.cn/Article/details/gt2kemaivti.html

Ruby: // fork 块
来源：http://dali.yj202588.top/Article/details/gt2juyuaghf.html

C#:   Parallel.For
来源：http://dali.zhiwuduotai.top/Article/details/gt2bdneshmg.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gt2fishpgoo.html

P. 常用工具函数
来源：http://dali.chenzaomai.com/Article/details/gt2bbfiyfxz.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gt2owuzlkhl.html

[P01] 生成 UUID
来源：http://dali.daxiang520.top/Article/details/gt2qnrqktwr.html

Py:   str(uuid.uuid4())
来源：http://dali.zhengqikj.top/Article/details/gt2muumygem.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.xuetiantiany.cn/Article/details/gt2gxlmpfcu.html

JS:   crypto.randomUUID()
来源：http://dali.c1oappe.top/Article/details/gt2tpmhwdmg.html

TS:   crypto.randomUUID()
来源：http://dali.ybcxt.top/Article/details/gt2hnzuxnpo.html

Java: UUID.randomUUID().toString()
来源：http://dali.c1oappe.top/Article/details/gt2mgxhdtwt.html

Go:   // 用 github.com/google/uuid
来源：http://dali.yuxming.cn/Article/details/gt2hgurdniy.html

Ruby: SecureRandom.uuid
来源：http://dali.pengpengdd.cyou/Article/details/gt2cgdwobqa.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.haohaochexian.top/Article/details/gt2tcchyjui.html

[P02] MD5 / SHA256 摘要
来源：http://dali.hywenlv.cn/Article/details/gt2onyidwyc.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.0kj1m.cn/Article/details/gt2bknlsxmz.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.jinqigfzy.top/Article/details/gt2afnhwqxm.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.ybcxt.top/Article/details/gt2cljhfqub.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wguwymoh.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hmmhkeow.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.daxiang520.top/Article/details/gt2xrfglebh.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.nwbrower.top/Article/details/gt2hptzrklf.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.hnxiangtu.top/Article/details/gt2diyjpsjb.html

[P03] 生成短随机字符串
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2heorifwq.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.sxryk.cn/Article/details/gt2ehizcbre.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.wangdashe.top/Article/details/gt2rxvbfeag.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.hongshengwenyu.top/Article/details/gt2rfwcvyqe.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yj20258888.top/Article/details/gt2qfvdsphq.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.haohaochexian.top/Article/details/gt2gkunuigi.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.sysykeji.top/Article/details/gt2kgvgwijv.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.wangdashe.top/Article/details/gt2ogsdaapd.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.yj20258888.top/Article/details/gt2ddoypqeh.html

[P04] 求长度
来源：http://dali.guowangkeji.top/Article/details/gt2votzeomu.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.shzxlz.cn/Article/details/gt2eqqfncsm.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.xinyue.icu/Article/details/gt2xxkjeyof.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.cheryme.top/Article/details/gt2ovfanxyy.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.daxiang520.top/Article/details/gt2vyvdwkyg.html

Java: list.size();  map.size();  s.length()
来源：http://dali.cqqwz.cn/Article/details/gt2swuzfsju.html

Go:   len(arr);  len(m)
来源：http://dali.guannengcc.top/Article/details/gt2nqjmzsaf.html

Ruby: x.length;  x.size
来源：http://dali.hnqzz.top/Article/details/gt2cupcjrbp.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.nanxuanxn.top/Article/details/gt2qecbjgvz.html

[P05] 判断两个对象内容是否相等
来源：http://dali.jinqigufen.top/Article/details/gt2hjlmrnhh.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gwbkksxq.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.ppjwa.cn/Article/details/gt2hgvdfqko.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.fengsongda.top/Article/details/gt2mwrkxbab.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.yj20258.top/Article/details/gt2ttjeclte.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zhengqikj.top/Article/details/gt2fhsgslpy.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.cdnleiting.top/Article/details/gt2osatuigy.html

Ruby: a == b
来源：http://dali.fzhhl.top/Article/details/gt2rfcqmvvf.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.daxiang520.top/Article/details/gt2qifkxjan.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.fengsongda.top/Article/details/gt2rzfdlwrt.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.bjfxy.top/Article/details/gt2txxjbbki.html

PHP:  if (empty($x)) {}
来源：http://dali.yj20258.top/Article/details/gt2tpamstyn.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.guowangkeji.top/Article/details/gt2wrydiqyx.html

TS:   if (x == null) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2taxeclcs.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.nanxuanxn.top/Article/details/gt2bxotaowf.html

Go:   if x == nil {}
来源：http://dali.gaohongyu789.top/Article/details/gt2mgdeufiy.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.nanxuanxn.top/Article/details/gt2otghunai.html

C#:   if (x is null) {}
来源：http://dali.dashuyun.cn/Article/details/gt2wodexkec.html

[P07] 防抖与节流
来源：http://dali.yj20258.top/Article/details/gt2rdcxmzwl.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.gaohongyu789.top/Article/details/gt2ruskrxkw.html

PHP:  // 手写时间戳比较
来源：http://dali.fengsongda.top/Article/details/gt2maiubtjy.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.sysykeji.top/Article/details/gt2xoqehtgv.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.316326.xyz/Article/details/gt2oqkhrcch.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.yj20258.top/Article/details/gt2qbcowadr.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.shuidangran.top/Article/details/gt2wdfajeor.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.yangfankeji.com/Article/details/gt2jmeuyydh.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zhiwuduotai.top/Article/details/gt2dlrtbamp.html

[P08] 处理浮点精度问题
来源：http://dali.smart0.xyz/Article/details/gt2icogfyei.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.yj20258888.top/Article/details/gt2tnjnukwu.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.xziqi.cn/Article/details/gt2ftavzurj.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.pycfn.com/Article/details/gt2nrkblsvg.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.tanke756.top/Article/details/gt2iuapsgbs.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.zdqjudy.top/Article/details/gt2tfiokdil.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.yuxming.cn/Article/details/gt2imrgdogt.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.zhongyouzk.top/Article/details/gt2euxxjxcw.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.gotoacloud.top/Article/details/gt2blwjskxw.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gt2kzfqvsfg.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.hfpthk.cn/Article/details/gt2bibcetbf.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gt2bikdrjnk.html

[Q01] 创建表
来源：http://dali.smart0.xyz/Article/details/gt2dgzoxyrc.html

CREATE TABLE users (
来源：http://dali.zhiwuduotai.top/Article/details/gt2rmjrdqpb.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.mhx1999.top/Article/details/gt2fblilwit.html

name VARCHAR(50) NOT NULL,
来源：http://dali.gaohongyu789.top/Article/details/gt2eswinqnx.html

email VARCHAR(100) UNIQUE,
来源：http://dali.jinqigfzy.top/Article/details/gt2gxzqgeja.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gibndgin.html

);
来源：http://dali.xuetiantiany.cn/Article/details/gt2csszmtzi.html

[Q02] 创建带外键的表
来源：http://dali.zhiwuduotai.top/Article/details/gt2twejnlop.html

CREATE TABLE orders (
来源：http://dali.cqqwz.cn/Article/details/gt2zogmizni.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zdqjudy.top/Article/details/gt2erltlrzy.html

user_id INT NOT NULL,
来源：http://dali.gotoacloud.top/Article/details/gt2agfmwunf.html

amount DECIMAL(10, 2),
来源：http://dali.yvedp.cn/Article/details/gt2jvuquaus.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.dashuyun.cn/Article/details/gt2deqgxefr.html

);
来源：http://dali.meibo888.top/Article/details/gt2wrnqzpmz.html

[Q03] 增加列
来源：http://dali.mhx1999.top/Article/details/gt2mjjtinpa.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.haohaochexian.top/Article/details/gt2gxvnzkab.html

[Q04] 修改列类型
来源：http://dali.jinqigufen.top/Article/details/gt2wsytsrim.html

ALTER TABLE users MODIFY COLUMN name VARCHAR(100) NOT NULL;
来源：http://dali.nwbrower.top/Article/details/gt2bfwslhmq.html

[Q05] 重命名列
来源：http://dali.zhengqikj.top/Article/details/gt2voyjhcew.html

ALTER TABLE users RENAME COLUMN name TO full_name;
来源：http://dali.cqqwz.cn/Article/details/gt2agjzaklo.html

[Q06] 删除列
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kilttqsd.html


<!-- 参考信息 -->