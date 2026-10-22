代发 wailian999

C#:   Directory.GetCurrentDirectory()
来源：http://dali.pycfn.com/Article/details/gt2ejkgvwpx.html

[M05] 设置退出码
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2iufimlci.html

Py:   sys.exit(1)
来源：http://dali.yueranfly.top/Article/details/gt2bqnrqxvy.html

PHP:  exit(1);
来源：http://dali.xuetiantiany.cn/Article/details/gt2nesankxs.html

JS:   process.exit(1)
来源：http://dali.ydzc1.top/Article/details/gt2vyekyiph.html

TS:   process.exit(1)
来源：http://dali.chenlongwang.top/Article/details/gt2lxnktvic.html

Java: System.exit(1)
来源：http://dali.hywenlv.cn/Article/details/gt2sylxxecz.html

Go:   os.Exit(1)
来源：http://dali.fzhhl.top/Article/details/gt2tflrqkzu.html

Ruby: exit 1
来源：http://dali.nanxuanxn.top/Article/details/gt2aitriejf.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.meibo888.top/Article/details/gt2hgqduucx.html

[M06] 向标准错误输出
来源：http://dali.ydzc1.top/Article/details/gt2rcpzamlc.html

Py:   print("err", file=sys.stderr)
来源：http://dali.ydzc1.top/Article/details/gt2phdxlsju.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.redwolf501.top/Article/details/gt2urivdcck.html

JS:   console.error("err")
来源：http://dali.jinqigfzy.top/Article/details/gt2mdsljkys.html

TS:   console.error("err")
来源：http://dali.snrcjt.cn/Article/details/gt2gaybkibx.html

Java: System.err.println("err")
来源：http://dali.jyoumei.cn/Article/details/gt2rzmimqyr.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zycfv.cn/Article/details/gt2bnaalhjq.html

Ruby: warn "err"
来源：http://dali.aizwys.cn/Article/details/gt2dioawvty.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.c1oappe.top/Article/details/gt2dqofniqm.html

[M07] 判断是否为主入口
来源：http://dali.tanke756.top/Article/details/gt2vjspipsw.html

Py:   if __name__ == "__main__":
来源：http://dali.xuanzx.com/Article/details/gt2mfslymjy.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.cqqwz.cn/Article/details/gt2uwzbfkwc.html

JS:   require.main === module
来源：http://dali.zhongyouzk.top/Article/details/gt2vveohilm.html

TS:   require.main === module
来源：http://dali.svipenyu.cn/Article/details/gt2ayayaxcj.html

Java: public static void main(String[] args)
来源：http://dali.pycfn.com/Article/details/gt2ehybrnjb.html

Go:   func main()
来源：http://dali.hysaishi.cn/Article/details/gt2rncbnvbk.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.havefunace.top/Article/details/gt2weenhmwy.html

C#:   static void Main(string[] args)
来源：http://dali.hammf.cn/Article/details/gt2kzqodlxi.html

[M08] 获取系统与运行时信息
来源：http://dali.jqgfzy.top/Article/details/gt2thezjnyw.html

Py:   platform.system();  platform.python_version()
来源：http://dali.xuetiantiany.cn/Article/details/gt2gzqcnmtr.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.jlsjyb.cn/Article/details/gt2pglmkltb.html

JS:   process.platform;  process.version
来源：http://dali.xuanzx.com/Article/details/gt2gudxommd.html

TS:   process.platform;  process.version
来源：http://dali.sufxvd.cn/Article/details/gt2szheezpt.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.cucudq.cn/Article/details/gt2lauasyhv.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.0kj1m.cn/Article/details/gt2skjaomdn.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.chenzaomai.com/Article/details/gt2nvkbjayh.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.bjfxy.top/Article/details/gt2wtjwhpzt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2amdykwwv.html

N. 数据结构与算法
来源：http://dali.birdmap.top/Article/details/gt2hjqaumzb.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gt2gxqlguyq.html

[N01] 二分查找（有序数组）
来源：http://dali.cdnleiting.top/Article/details/gt2tcoetfxi.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.0kj1m.cn/Article/details/gt2ikrepwvo.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.yongpay.top/Article/details/gt2mahcqoes.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.316326.xyz/Article/details/gt2fvgaphno.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.chenzaomai.com/Article/details/gt2ergbvwgw.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dbwtahtu.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.tanke756.top/Article/details/gt2hmzijzep.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.yanxiufei.cn/Article/details/gt2slnrajfc.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.nanxinkj.top/Article/details/gt2oaqzeimt.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.andypj.xyz/Article/details/gt2evuxjsid.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.hysaishi.cn/Article/details/gt2wsoymhsp.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.xuanzx.com/Article/details/gt2hsqotycy.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.0kj1m.cn/Article/details/gt2ymawvbes.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.ehwqpu.com/Article/details/gt2cptoygxu.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.aibaodan.cn/Article/details/gt2zpgugxcg.html

Go:   slices.Sort(arr)
来源：http://dali.redwolf501.top/Article/details/gt2tsinltoy.html

Ruby: arr.sort
来源：http://dali.ydzc1.top/Article/details/gt2zahktbfa.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.cheryme.top/Article/details/gt2dnaoqaqr.html

[N03] 快速排序（分治示例）
来源：http://dali.wangshuangyany.cn/Article/details/gt2locrbeic.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.nanxinkj.top/Article/details/gt2xqmfaurm.html

PHP:  // 递归实现，或用 usort
来源：http://dali.nanxinkj.top/Article/details/gt2avscwyzd.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.chenlongwang.top/Article/details/gt2svnoxpwd.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhongyouzk.top/Article/details/gt2vnywvqgi.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zycfv.cn/Article/details/gt2iuyurdak.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.yj20258888.top/Article/details/gt2gukpvttg.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.aibaodan.cn/Article/details/gt2btdctckn.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.guowangkeji.top/Article/details/gt2zokzvmgt.html

[N04] 斐波那契数列
来源：http://dali.daria6918.cn/Article/details/gt2krpqbdic.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.shangyingyoupin.top/Article/details/gt2fhjkamhu.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.yuxming.cn/Article/details/gt2jjioozoe.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jiagoushi.top/Article/details/gt2mjjzxpsu.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.c1oappe.top/Article/details/gt2vbnjiyqy.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.dashuyun.cn/Article/details/gt2rsoyvyrz.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.0kj1m.cn/Article/details/gt2uipktkea.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zdqjudy.top/Article/details/gt2qjmteplw.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.nwbrower.top/Article/details/gt2vxevrdtn.html

[N05] 最大公约数
来源：http://dali.feifeiyinyue.top/Article/details/gt2jcaspbrv.html

Py:   math.gcd(a, b)
来源：http://dali.svipenyu.cn/Article/details/gt2cddhaxzv.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.gotoacloud.top/Article/details/gt2xaljohhz.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.cdnleiting.top/Article/details/gt2qjnrbzgq.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.0kj1m.cn/Article/details/gt2xmkiedqk.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.yuxming.cn/Article/details/gt2kwvosqvx.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhixingplan.top/Article/details/gt2zrkomaxl.html

Ruby: a.gcd(b)
来源：http://dali.zycfv.cn/Article/details/gt2bpboipxf.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.dashuyun.cn/Article/details/gt2cjussxjq.html

[N06] 判断回文字符串
来源：http://dali.tanke756.top/Article/details/gt2qpwnkwqa.html

Py:   s == s[::-1]
来源：http://dali.jlsjyb.cn/Article/details/gt2zubpncvx.html

PHP:  $s === strrev($s);
来源：http://dali.sufxvd.cn/Article/details/gt2furkrnqk.html

JS:   s === [...s].reverse().join("")
来源：http://dali.smart0.xyz/Article/details/gt2hefffwlx.html

TS:   s === [...s].reverse().join("")
来源：http://dali.svipenyu.cn/Article/details/gt2itlfoscc.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.0kj1m.cn/Article/details/gt2stzibfib.html

Go:   // 双指针从两端比较
来源：http://dali.quarkkingdee.top/Article/details/gt2xlmrezor.html

Ruby: s == s.reverse
来源：http://dali.yangfankeji.com/Article/details/gt2yboramod.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhengqikj.top/Article/details/gt2xhxetzev.html

[N07] 两数之和（返回下标）
来源：http://dali.aibaodan.cn/Article/details/gt2befsvbtr.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.tianlin.xyz/Article/details/gt2prlbehxo.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.wangdashe.top/Article/details/gt2kjrqptdo.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zdqjudy.top/Article/details/gt2pejigquw.html

TS:   // 手写 Map<string, number>
来源：http://dali.sweek.top/Article/details/gt2meojsojj.html

Java: // 手写 HashMap
来源：http://dali.svipenyu.cn/Article/details/gt2ciaxriup.html

Go:   // 手写 map[int]int
来源：http://dali.fengsongda.top/Article/details/gt2agkpuwyt.html

Ruby: // 手写 Hash
来源：http://dali.hnqzz.top/Article/details/gt2tknqijky.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.nwbrower.top/Article/details/gt2ipverhzd.html

[N08] 生成全排列
来源：http://dali.feifeiyinyue.top/Article/details/gt2vptwmxic.html

Py:   itertools.permutations(arr)
来源：http://dali.gzhubu.top/Article/details/gt2spbfphpw.html

PHP:  // 手写递归交换
来源：http://dali.yj20258888.top/Article/details/gt2pmvlaeky.html

JS:   // 手写回溯递归
来源：http://dali.jinqigfzy.top/Article/details/gt2henwgkep.html

TS:   // 手写回溯递归
来源：http://dali.cdnleiting.top/Article/details/gt2aullxqqo.html

Java: // 手写回溯递归
来源：http://dali.fzhhl.top/Article/details/gt2csfkvijg.html

Go:   // 手写回溯递归
来源：http://dali.feifeiyinyue.top/Article/details/gt2sziuhoho.html

Ruby: arr.permutation.to_a
来源：http://dali.yueranfly.top/Article/details/gt2sjznuzxu.html

C#:   // 手写回溯递归
来源：http://dali.haohaochexian.top/Article/details/gt2yczeadwd.html

[N09] 栈与队列
来源：http://dali.xinyue.icu/Article/details/gt2fewwhxjm.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.yanxiufei.cn/Article/details/gt2kabgjxic.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.c1oappe.top/Article/details/gt2ficbhoby.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.gotoacloud.top/Article/details/gt2lfuxynas.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.birdmap.top/Article/details/gt2pqpxfqve.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.ehwqpu.com/Article/details/gt2wqisqthk.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.snrcjt.cn/Article/details/gt2nclaiglw.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.pengpengdd.cyou/Article/details/gt2gthkulnx.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.dashuyun.cn/Article/details/gt2iosdczpd.html

[N10] 链表节点定义
来源：http://dali.cucudq.cn/Article/details/gt2mbvrgjbr.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.mhx1999.top/Article/details/gt2xpemqyad.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.yj202588.top/Article/details/gt2sjttamse.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.jianghu66.top/Article/details/gt2wepfejrf.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.chenzaomai.com/Article/details/gt2wdzrgazr.html

Java: class Node { int v; Node next; }
来源：http://dali.sufxvd.cn/Article/details/gt2kmybosow.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.yuanzhike.top/Article/details/gt2noebgwhh.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2siurwmac.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.bjfxy.top/Article/details/gt2ltlygjvk.html

[N11] 二叉树中序遍历
来源：http://dali.gzhubu.top/Article/details/gt2xtewueai.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.gaohongyu789.top/Article/details/gt2pkxomcvh.html

PHP:  // 手写递归函数
来源：http://dali.gzhubu.top/Article/details/gt2ipseyorv.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.xinyue.icu/Article/details/gt2acbzufvp.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.hysaishi.cn/Article/details/gt2dpoqtdlt.html

Java: // 手写递归
来源：http://dali.nanxinkj.top/Article/details/gt2tlfpfgwz.html

Go:   // 手写递归
来源：http://dali.c1oappe.top/Article/details/gt2jlexhlzi.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.ybcxt.top/Article/details/gt2xbmrcvil.html

C#:   // 手写递归
来源：http://dali.tianlin.xyz/Article/details/gt2mkkeebwl.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.feifeiyinyue.top/Article/details/gt2yfmtxtan.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.gogol.net.cn/Article/details/gt2dyxdpqpn.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.cdnleiting.top/Article/details/gt2kedgzpic.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.sxryk.cn/Article/details/gt2ppvhzjwp.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.shzxlz.cn/Article/details/gt2qpkprjbn.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.hfpthk.cn/Article/details/gt2siwfwmln.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.hysaishi.cn/Article/details/gt2lslkmqwe.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.yj202588.top/Article/details/gt2rupwahcc.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.hywenlv.cn/Article/details/gt2lrjetzwh.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gt2zcwkamsy.html

O. 并发与异步
来源：http://dali.snrcjt.cn/Article/details/gt2bqvqdyog.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gt2gqqkxawd.html

[O01] 启动一个线程
来源：http://dali.yj20258.top/Article/details/gt2oqhlawyc.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.c1oappe.top/Article/details/gt2jfdhzrik.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.c1oappe.top/Article/details/gt2ysadopuo.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhengqikj.top/Article/details/gt2iqiydtdf.html

TS:   // 同 JS
来源：http://dali.zhongyouzk.top/Article/details/gt2lfmlxjws.html

Java: new Thread(() -> f()).start()
来源：http://dali.hnqzz.top/Article/details/gt2neweeswz.html

Go:   go f()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2exzelhie.html

Ruby: Thread.new { f }
来源：http://dali.gaohongyu789.top/Article/details/gt2gsllrgje.html

C#:   Task.Run(() => F());
来源：http://dali.wangshuangyany.cn/Article/details/gt2vdogjpci.html

[O02] 使用线程池
来源：http://dali.zhoulong.xyz/Article/details/gt2rgmspddz.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.ybcxt.top/Article/details/gt2kxqpplvx.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.shangyingyoupin.top/Article/details/gt2jckudzjm.html

JS:   // worker_threads 线程池
来源：http://dali.gaohongyu789.top/Article/details/gt2ujbqyhpj.html

TS:   // worker_threads 线程池
来源：http://dali.jyoumei.cn/Article/details/gt2bpjydlrr.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.cashguo.top/Article/details/gt2rdwferel.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.nanxuanxn.top/Article/details/gt2dnknaujk.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.gaohongyu789.top/Article/details/gt2oymxmdnn.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.pengpengdd.cyou/Article/details/gt2fbmbibng.html

[O03] 加锁保护共享数据
来源：http://dali.feifeiyinyue.top/Article/details/gt2zzjgldko.html

Py:   with lock: shared += 1
来源：http://dali.zhiwuduotai.top/Article/details/gt2dpqetnmk.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.daria6918.cn/Article/details/gt2jjdpgyao.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.jqgfzy.top/Article/details/gt2eovchgdz.html

TS:   // 同 JS
来源：http://dali.aizwys.cn/Article/details/gt2ezwkglle.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhongyouzk.top/Article/details/gt2arcaqnks.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.jiagoushi.top/Article/details/gt2ykzoloza.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.ivvv.top/Article/details/gt2oszspnwa.html

C#:   lock (gate) { shared++; }
来源：http://dali.xziqi.cn/Article/details/gt2aaahnpqb.html

[O04] 定义异步函数并等待
来源：http://dali.meibo888.top/Article/details/gt2rliucyos.html

Py:   async def f():⏎    await g()
来源：http://dali.xylfe.cn/Article/details/gt2sqkkitff.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.gotoacloud.top/Article/details/gt2zumuqccn.html

JS:   async function f() { await g(); }
来源：http://dali.cqqwz.cn/Article/details/gt2pasragdr.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.xuetiantiany.cn/Article/details/gt2dcesnnpa.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhixingplan.top/Article/details/gt2zwzzrmbx.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zycfv.cn/Article/details/gt2lkjshnql.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.cashguo.top/Article/details/gt2lwfltcls.html

C#:   async Task F() { await G(); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2oozzolvg.html

[O05] 并发执行并等待全部完成
来源：http://dali.nwbrower.top/Article/details/gt2adurswbp.html

Py:   asyncio.gather(*tasks)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ghqdtyos.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.shuidangran.top/Article/details/gt2dfafzilm.html

JS:   await Promise.all(tasks)
来源：http://dali.cashguo.top/Article/details/gt2cynrxizs.html

TS:   await Promise.all(tasks)
来源：http://dali.pengpengdd.cyou/Article/details/gt2qpjfprdd.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.daria6918.cn/Article/details/gt2xlnickpk.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.jyoumei.cn/Article/details/gt2hyqdhwcg.html

Ruby: threads.map(&:join)
来源：http://dali.aibaodan.cn/Article/details/gt2ozirgeyw.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.snrcjt.cn/Article/details/gt2frqpvwmu.html

[O06] 使用进程池
来源：http://dali.jinqigfzy.top/Article/details/gt2nztstfpj.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.chenjidiqi.icu/Article/details/gt2giyfjtpo.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.tanke756.top/Article/details/gt2fubkmxow.html

JS:   // child_process / cluster 模块
来源：http://dali.chenlongwang.top/Article/details/gt2rkqnbiyr.html

TS:   // child_process / cluster 模块
来源：http://dali.meibo888.top/Article/details/gt2wusuuuaf.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhiwuduotai.top/Article/details/gt2hesmviht.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uirebfnu.html

Ruby: // fork 块
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xyxttnwy.html

C#:   Parallel.For
来源：http://dali.ivvv.top/Article/details/gt2vqnuyxpd.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gt2fbeywtrp.html

P. 常用工具函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zsreqrcv.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gt2bufhfwic.html

[P01] 生成 UUID
来源：http://dali.xuanzx.com/Article/details/gt2rgjkifqx.html

Py:   str(uuid.uuid4())
来源：http://dali.chenzaomai.com/Article/details/gt2panxfgqs.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.tanke756.top/Article/details/gt2zpyppzsm.html

JS:   crypto.randomUUID()
来源：http://dali.hnqzz.top/Article/details/gt2nuefxlua.html

TS:   crypto.randomUUID()
来源：http://dali.shzxlz.cn/Article/details/gt2xnvmftod.html

Java: UUID.randomUUID().toString()
来源：http://dali.svipenyu.cn/Article/details/gt2bclqdcee.html

Go:   // 用 github.com/google/uuid
来源：http://dali.ehwqpu.com/Article/details/gt2jvcysblz.html

Ruby: SecureRandom.uuid
来源：http://dali.cucudq.cn/Article/details/gt2brpqotma.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zdqjudy.top/Article/details/gt2lyojhmoh.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhijiandao.cn/Article/details/gt2mbofpvpw.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.aibaodan.cn/Article/details/gt2cjpbbepm.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.xinyue.icu/Article/details/gt2ehfhgvxi.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2eqfrauof.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.gzhubu.top/Article/details/gt2yjzscekz.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.nanxinkj.top/Article/details/gt2bpqyciiq.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.pycfn.com/Article/details/gt2dqtivwgl.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.guannengcc.top/Article/details/gt2umfhwczz.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.dianchejie.cn/Article/details/gt2hdlsvpju.html

[P03] 生成短随机字符串
来源：http://dali.shangyingyoupin.top/Article/details/gt2nengjhwv.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.nwbrower.top/Article/details/gt2epaxocfr.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.andypj.xyz/Article/details/gt2vakbomwr.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.chenlongwang.top/Article/details/gt2jjgzmimk.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.aibaodan.cn/Article/details/gt2ikescxzw.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.xylfe.cn/Article/details/gt2yrtmujvo.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.ppjwa.cn/Article/details/gt2hykmdypi.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.zhixingplan.top/Article/details/gt2iqcjzzdm.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.jianghu66.top/Article/details/gt2hnymkwbv.html

[P04] 求长度
来源：http://dali.cashguo.top/Article/details/gt2elfadoyb.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.redwolf501.top/Article/details/gt2uteepgng.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rpaxjied.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.mhx1999.top/Article/details/gt2drcglvxg.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.fzhhl.top/Article/details/gt2lzrvstmk.html

Java: list.size();  map.size();  s.length()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rhdbsejy.html

Go:   len(arr);  len(m)
来源：http://dali.hongshengwenyu.top/Article/details/gt2geavaphp.html

Ruby: x.length;  x.size
来源：http://dali.ehwqpu.com/Article/details/gt2ijdtrugg.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.wangshuangyany.cn/Article/details/gt2aekksmfi.html

[P05] 判断两个对象内容是否相等
来源：http://dali.sysykeji.top/Article/details/gt2wgjehaka.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.guannengcc.top/Article/details/gt2lbbgrbrs.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.hnqzz.top/Article/details/gt2raztdplu.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.cucudq.cn/Article/details/gt2olkhdzct.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zdqjudy.top/Article/details/gt2oyfzeqku.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.gotoacloud.top/Article/details/gt2darovowf.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.316326.xyz/Article/details/gt2skmdzosn.html

Ruby: a == b
来源：http://dali.hnqzz.top/Article/details/gt2nhavpdvo.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.shuidangran.top/Article/details/gt2mtxwqrev.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.yongpay.top/Article/details/gt2arfpkfao.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.0kj1m.cn/Article/details/gt2fqsdzvii.html

PHP:  if (empty($x)) {}
来源：http://dali.0kj1m.cn/Article/details/gt2emjyqinu.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.tanke756.top/Article/details/gt2lasgxqut.html

TS:   if (x == null) {}
来源：http://dali.tanke756.top/Article/details/gt2lnjzvwfq.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2oclsexks.html

Go:   if x == nil {}
来源：http://dali.sweek.top/Article/details/gt2pjbnrdvr.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.yuxming.cn/Article/details/gt2gythneuf.html

C#:   if (x is null) {}
来源：http://dali.jinqigfzy.top/Article/details/gt2rueytajw.html

[P07] 防抖与节流
来源：http://dali.ydzc1.top/Article/details/gt2asbpcrrs.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.cdnleiting.top/Article/details/gt2alpbgies.html

PHP:  // 手写时间戳比较
来源：http://dali.shangyingyoupin.top/Article/details/gt2njneostp.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhongyouzk.top/Article/details/gt2hsymraop.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.daxiang520.top/Article/details/gt2uitixnys.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.sxryk.cn/Article/details/gt2paetvmeo.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.yonumen.top/Article/details/gt2cikhsqvx.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.hywenlv.cn/Article/details/gt2ugqvjxzi.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.yj202588.top/Article/details/gt2whueqoxp.html

[P08] 处理浮点精度问题
来源：http://dali.cdnleiting.top/Article/details/gt2fxtxsbom.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.chenjidiqi.icu/Article/details/gt2vzjhkznt.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.bjfxy.top/Article/details/gt2jiwbpayf.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.meibo888.top/Article/details/gt2lcssgwch.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.ehwqpu.com/Article/details/gt2vuttozke.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.quarkkingdee.top/Article/details/gt2isvgyhhb.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.quarkkingdee.top/Article/details/gt2gswozcij.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.havefunace.top/Article/details/gt2mrwfbxkj.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.fzhhl.top/Article/details/gt2hhihtkhk.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gt2vafbefdp.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.yonumen.top/Article/details/gt2vcmjiiif.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gt2idlidvof.html

[Q01] 创建表
来源：http://dali.chenjidiqi.icu/Article/details/gt2uajyluwe.html

CREATE TABLE users (
来源：http://dali.sweek.top/Article/details/gt2llpboupj.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gt2xblgvoog.html

name VARCHAR(50) NOT NULL,
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2slohbgly.html

email VARCHAR(100) UNIQUE,
来源：http://dali.hfpthk.cn/Article/details/gt2eorrxhpv.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.jqgufenzy.top/Article/details/gt2opssjdeq.html

);
来源：http://dali.wangdashe.top/Article/details/gt2ueqexbxu.html

[Q02] 创建带外键的表
来源：http://dali.guannengcc.top/Article/details/gt2gvkffyxa.html

CREATE TABLE orders (
来源：http://dali.nanxinkj.top/Article/details/gt2pxlnrjnp.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.cucudq.cn/Article/details/gt2tpetzmuz.html

user_id INT NOT NULL,
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lcmjjyad.html

amount DECIMAL(10, 2),
来源：http://dali.fzhhl.top/Article/details/gt2ymkqhcvt.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.tianlin.xyz/Article/details/gt2nklxxead.html

);
来源：http://dali.cheryme.top/Article/details/gt2luudzcbd.html

[Q03] 增加列
来源：http://dali.ivvv.top/Article/details/gt2tzqjfwlv.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.hongshengwenyu.top/Article/details/gt2rltnfuku.html

[Q04] 修改列类型
来源：http://dali.fengsongda.top/Article/details/gt2kvlnqemn.html


<!-- 参考信息 -->