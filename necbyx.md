代发 wailian999

C#:   Directory.GetCurrentDirectory()
来源：http://dali.yj20258.top/Article/details/gtanlmclvb.html

[M05] 设置退出码
来源：http://dali.dashuyun.cn/Article/details/gtvpvknkiu.html

Py:   sys.exit(1)
来源：http://dali.316326.xyz/Article/details/gtiwotrayw.html

PHP:  exit(1);
来源：http://dali.tian-w.cn/Article/details/gtmiuedjnr.html

JS:   process.exit(1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoxmcjwvy.html

TS:   process.exit(1)
来源：http://dali.dianchejie.cn/Article/details/gtpwyntaem.html

Java: System.exit(1)
来源：http://dali.nanxinkj.top/Article/details/gtgtgxrkyh.html

Go:   os.Exit(1)
来源：http://dali.jyoumei.cn/Article/details/gtwnomzffb.html

Ruby: exit 1
来源：http://dali.ybcxt.top/Article/details/gtwkfjupmw.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.cdnleiting.top/Article/details/gtnpwhcjwt.html

[M06] 向标准错误输出
来源：http://dali.gzhubu.top/Article/details/gtzqkbfymh.html

Py:   print("err", file=sys.stderr)
来源：http://dali.snrcjt.cn/Article/details/gtwnbebnyy.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.birdmap.top/Article/details/gtijgbwqau.html

JS:   console.error("err")
来源：http://dali.jinqigfzy.top/Article/details/gtulakttyu.html

TS:   console.error("err")
来源：http://dali.tianlin.xyz/Article/details/gtniboxmus.html

Java: System.err.println("err")
来源：http://dali.zycfv.cn/Article/details/gtnjsljrlc.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.gaohongyu789.top/Article/details/gtorvhykov.html

Ruby: warn "err"
来源：http://dali.jqgufenzy.top/Article/details/gtdkhqgtml.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.nwbrower.top/Article/details/gtspkouoor.html

[M07] 判断是否为主入口
来源：http://dali.pengpengdd.cyou/Article/details/gtqaczihif.html

Py:   if __name__ == "__main__":
来源：http://dali.316326.xyz/Article/details/gtupmkctzp.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.daxiang520.top/Article/details/gtglyjtkjm.html

JS:   require.main === module
来源：http://dali.jinghuilouyu.cn/Article/details/gthizzydao.html

TS:   require.main === module
来源：http://dali.shanyushiyangkeji.top/Article/details/gtudptaedm.html

Java: public static void main(String[] args)
来源：http://dali.xziqi.cn/Article/details/gtrblzggrj.html

Go:   func main()
来源：http://dali.birdmap.top/Article/details/gtczulltka.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.vqdsnc.cn/Article/details/gtwhnbdfno.html

C#:   static void Main(string[] args)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzuejrflc.html

[M08] 获取系统与运行时信息
来源：http://dali.c1oappe.top/Article/details/gtwgahkrug.html

Py:   platform.system();  platform.python_version()
来源：http://dali.shzxlz.cn/Article/details/gtitchsuoz.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.shangyingyoupin.top/Article/details/gtqvmhiduz.html

JS:   process.platform;  process.version
来源：http://dali.yj20258.top/Article/details/gtigwiklds.html

TS:   process.platform;  process.version
来源：http://dali.tanke756.top/Article/details/gtpxbzwnwm.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.xylfe.cn/Article/details/gtacfgmxgz.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.shzxlz.cn/Article/details/gtbojzqeao.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.yangfankeji.com/Article/details/gtaogudkaz.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.redwolf501.top/Article/details/gtfpdorelk.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtvtkcbeqk.html

N. 数据结构与算法
来源：http://dali.kuanghao11.cn/Article/details/gtlnyazhwl.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtsrnutmif.html

[N01] 二分查找（有序数组）
来源：http://dali.xinyue.icu/Article/details/gtjygeajne.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.tanke756.top/Article/details/gtxprelqgw.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.hfpthk.cn/Article/details/gtypfhyjuc.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.bjfxy.top/Article/details/gtcvqjixck.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.gotoacloud.top/Article/details/gtshvfarrv.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyjwvlhfm.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.xinyue.icu/Article/details/gtffqnwhdx.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.nanxuanxn.top/Article/details/gtbmtirwxk.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.feifeiyinyue.top/Article/details/gtstxrttta.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.sysykeji.top/Article/details/gtruriziea.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yongpay.top/Article/details/gtramkdvjl.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.ehwqpu.com/Article/details/gtfkepdmbl.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jinghuilouyu.cn/Article/details/gtzgeozvfn.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yuanzhike.top/Article/details/gtkoilxxiw.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.jinqigfzy.top/Article/details/gtxfxsofdp.html

Go:   slices.Sort(arr)
来源：http://dali.hongshengwenyu.top/Article/details/gtdlzdncqb.html

Ruby: arr.sort
来源：http://dali.yj20258.top/Article/details/gtiwqnxtza.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhongyouzk.top/Article/details/gtcpgltehb.html

[N03] 快速排序（分治示例）
来源：http://dali.xuanzx.com/Article/details/gtdeenfysk.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.wangshuangyany.cn/Article/details/gtwinggles.html

PHP:  // 递归实现，或用 usort
来源：http://dali.jinghuilouyu.cn/Article/details/gtxoapggzv.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yuxming.cn/Article/details/gtwewpqsqi.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.pycfn.com/Article/details/gtuqeggdru.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.gaohongyu789.top/Article/details/gtwwyagfud.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.jyoumei.cn/Article/details/gtvmpineli.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.ivvv.top/Article/details/gtnfytnvyk.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.sxryk.cn/Article/details/gtthjablfo.html

[N04] 斐波那契数列
来源：http://dali.daria6918.cn/Article/details/gtfchumgsf.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.chenlongwang.top/Article/details/gtgwnsglrj.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.sysykeji.top/Article/details/gtoivxsgmj.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.cashguo.top/Article/details/gtqejywleh.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yj202588.top/Article/details/gtlzyliixz.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gthvfmueqr.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.haohaochexian.top/Article/details/gtljwkyegp.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.316326.xyz/Article/details/gtulvhkwck.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.yuxming.cn/Article/details/gtegtipopt.html

[N05] 最大公约数
来源：http://dali.shuidangran.top/Article/details/gtjafnyiqi.html

Py:   math.gcd(a, b)
来源：http://dali.xziqi.cn/Article/details/gtundiethb.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.chenzaomai.com/Article/details/gtzxosisho.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.sweek.top/Article/details/gtqwrzidni.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.xylfe.cn/Article/details/gtjddmvphm.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.9152youxi.cn/Article/details/gtsflzukaz.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.yueranfly.top/Article/details/gtxgtmmwos.html

Ruby: a.gcd(b)
来源：http://dali.hnxiangtu.top/Article/details/gtkqisfomg.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.sweek.top/Article/details/gtglxezgtg.html

[N06] 判断回文字符串
来源：http://dali.hnxiangtu.top/Article/details/gtjdtdereq.html

Py:   s == s[::-1]
来源：http://dali.chenzaomai.com/Article/details/gthdfvmkwh.html

PHP:  $s === strrev($s);
来源：http://dali.wangshuangyany.cn/Article/details/gttwnftaig.html

JS:   s === [...s].reverse().join("")
来源：http://dali.c1oappe.top/Article/details/gtotnsmlal.html

TS:   s === [...s].reverse().join("")
来源：http://dali.quarkkingdee.top/Article/details/gtoyazsymm.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.nanxuanxn.top/Article/details/gttfsxqbsh.html

Go:   // 双指针从两端比较
来源：http://dali.jqgufenzy.top/Article/details/gtgasjhmap.html

Ruby: s == s.reverse
来源：http://dali.yj20258.top/Article/details/gtuvuiorgt.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhongyouzk.top/Article/details/gtpwlfldrm.html

[N07] 两数之和（返回下标）
来源：http://dali.ivvv.top/Article/details/gtkckripsa.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.yuxming.cn/Article/details/gtplhakgcb.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.0kj1m.cn/Article/details/gtscqgbmhz.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.haohaochexian.top/Article/details/gtpusltvtl.html

TS:   // 手写 Map<string, number>
来源：http://dali.cheryme.top/Article/details/gtqcsclvux.html

Java: // 手写 HashMap
来源：http://dali.nwbrower.top/Article/details/gtatgmznsc.html

Go:   // 手写 map[int]int
来源：http://dali.ehwqpu.com/Article/details/gtphagzfsf.html

Ruby: // 手写 Hash
来源：http://dali.jinghuilouyu.cn/Article/details/gtycjivgtk.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhiwuduotai.top/Article/details/gttmzkydqh.html

[N08] 生成全排列
来源：http://dali.hfpthk.cn/Article/details/gtneipyfqr.html

Py:   itertools.permutations(arr)
来源：http://dali.hongshengwenyu.top/Article/details/gtfcxsmjhx.html

PHP:  // 手写递归交换
来源：http://dali.zhixingplan.top/Article/details/gtvyonqeab.html

JS:   // 手写回溯递归
来源：http://dali.c1oappe.top/Article/details/gtkjpfdcsr.html

TS:   // 手写回溯递归
来源：http://dali.zycfv.cn/Article/details/gtiijygoyi.html

Java: // 手写回溯递归
来源：http://dali.yonumen.top/Article/details/gtakqmmxpd.html

Go:   // 手写回溯递归
来源：http://dali.meibo888.top/Article/details/gtheenklpi.html

Ruby: arr.permutation.to_a
来源：http://dali.sufxvd.cn/Article/details/gtryzfsefu.html

C#:   // 手写回溯递归
来源：http://dali.jinqigfzy.top/Article/details/gtdexcopgq.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gtngcwaduv.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.ydzc1.top/Article/details/gtcufmmidn.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.snrcjt.cn/Article/details/gtrmhuyevl.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.jlsjyb.cn/Article/details/gtxzyojefb.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zdqjudy.top/Article/details/gtqgcvbhlu.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.hnqzz.top/Article/details/gtvatdovfj.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.havefunace.top/Article/details/gttdvntwsp.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.sweek.top/Article/details/gttlqgpdgb.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.hnxiangtu.top/Article/details/gtxdbetcme.html

[N10] 链表节点定义
来源：http://dali.wangdashe.top/Article/details/gttxgwcwyu.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.sxryk.cn/Article/details/gtggcveiun.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.mhx1999.top/Article/details/gtuwfthumj.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.sxryk.cn/Article/details/gtqgzlizik.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.birdmap.top/Article/details/gtezvdoqpr.html

Java: class Node { int v; Node next; }
来源：http://dali.dashuyun.cn/Article/details/gtyfiuoqrs.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.havefunace.top/Article/details/gtpbfuqwgy.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.bjfxy.top/Article/details/gtflyqpzqg.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.jlsjyb.cn/Article/details/gtfeczkrly.html

[N11] 二叉树中序遍历
来源：http://dali.hywenlv.cn/Article/details/gtygudsgdw.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.tianlin.xyz/Article/details/gtzjzyfxlk.html

PHP:  // 手写递归函数
来源：http://dali.jinqigfzy.top/Article/details/gttubjfmkf.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jinghuilouyu.cn/Article/details/gtyclwdykl.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.hysaishi.cn/Article/details/gtzfefrqwm.html

Java: // 手写递归
来源：http://dali.quarkkingdee.top/Article/details/gtqqwgiiml.html

Go:   // 手写递归
来源：http://dali.yonumen.top/Article/details/gttutzgrlk.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteldoaram.html

C#:   // 手写递归
来源：http://dali.shangyingyoupin.top/Article/details/gtodpwphjg.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zdqjudy.top/Article/details/gttvhjtomj.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.xylfe.cn/Article/details/gtheyvgatw.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.cashguo.top/Article/details/gtqdusawmd.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.shuidangran.top/Article/details/gtxirkfghd.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.ppjwa.cn/Article/details/gtgedpikip.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.gzhubu.top/Article/details/gtbxbhwhqz.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.shanyushiyangtech.top/Article/details/gtonrpjxnb.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.jlsjyb.cn/Article/details/gtchxqzwkq.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.hywenlv.cn/Article/details/gthuatoecr.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfxyoilne.html

O. 并发与异步
来源：http://dali.ivvv.top/Article/details/gtpranpvhk.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtovxskbfp.html

[O01] 启动一个线程
来源：http://dali.jinghuilouyu.cn/Article/details/gtctohphfh.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.shuidangran.top/Article/details/gtiqgrbvns.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gttdfhuflf.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.nwbrower.top/Article/details/gtqikypxjf.html

TS:   // 同 JS
来源：http://dali.havefunace.top/Article/details/gtxerjrmkx.html

Java: new Thread(() -> f()).start()
来源：http://dali.jqgufenzy.top/Article/details/gteyucoexw.html

Go:   go f()
来源：http://dali.zdqjudy.top/Article/details/gtendvaldx.html

Ruby: Thread.new { f }
来源：http://dali.yueranfly.top/Article/details/gtpvwhslag.html

C#:   Task.Run(() => F());
来源：http://dali.zhiwuduotai.top/Article/details/gtoqegwsxm.html

[O02] 使用线程池
来源：http://dali.jinghuilouyu.cn/Article/details/gtmkmzzmbr.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfbtcdocl.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.gzhubu.top/Article/details/gthkdjsopb.html

JS:   // worker_threads 线程池
来源：http://dali.0kj1m.cn/Article/details/gtpucnwhgx.html

TS:   // worker_threads 线程池
来源：http://dali.jinqigufen.top/Article/details/gterpizcxg.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.xziqi.cn/Article/details/gtmnbiyvry.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.cheryme.top/Article/details/gtvamlqnqz.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.tanke756.top/Article/details/gtihbrklmc.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.hnxiangtu.top/Article/details/gtzdyrkojw.html

[O03] 加锁保护共享数据
来源：http://dali.nwbrower.top/Article/details/gtbkokvtre.html

Py:   with lock: shared += 1
来源：http://dali.dashuyun.cn/Article/details/gtrpgzvisk.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.gzhubu.top/Article/details/gtzjsigymc.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.yj20258.top/Article/details/gthmywmpyo.html

TS:   // 同 JS
来源：http://dali.tanke756.top/Article/details/gtgynmwiep.html

Java: synchronized (this) { shared++; }
来源：http://dali.cqqwz.cn/Article/details/gtdyuegcbh.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.mhx1999.top/Article/details/gtveemhfrl.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.shuidangran.top/Article/details/gtzrpruril.html

C#:   lock (gate) { shared++; }
来源：http://dali.316326.xyz/Article/details/gtheznftoe.html

[O04] 定义异步函数并等待
来源：http://dali.pengpengdd.cyou/Article/details/gtugfxomsa.html

Py:   async def f():⏎    await g()
来源：http://dali.xylfe.cn/Article/details/gtqipgjddm.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.sufxvd.cn/Article/details/gtpvsxjkgf.html

JS:   async function f() { await g(); }
来源：http://dali.jqgufenzy.top/Article/details/gtbxygukcl.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.tianlin.xyz/Article/details/gtuuqwhcil.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.jqgufenzy.top/Article/details/gtgzaimcdu.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.sysykeji.top/Article/details/gtoiwvjvjq.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.gaohongyu789.top/Article/details/gtnowcabaa.html

C#:   async Task F() { await G(); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyxmhncsg.html

[O05] 并发执行并等待全部完成
来源：http://dali.sufxvd.cn/Article/details/gtcybeyadn.html

Py:   asyncio.gather(*tasks)
来源：http://dali.sxryk.cn/Article/details/gtbvjeuxuu.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.sweek.top/Article/details/gtclfhrjzo.html

JS:   await Promise.all(tasks)
来源：http://dali.jinqigufen.top/Article/details/gtyvslarbt.html

TS:   await Promise.all(tasks)
来源：http://dali.yueranfly.top/Article/details/gtjafrkmov.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.mhx1999.top/Article/details/gtaycwsyas.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.haohaochexian.top/Article/details/gtxtdcqdsi.html

Ruby: threads.map(&:join)
来源：http://dali.cashguo.top/Article/details/gtxehauawh.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.jinqigfzy.top/Article/details/gtsdwyxbvp.html

[O06] 使用进程池
来源：http://dali.cdnleiting.top/Article/details/gtxjxcqene.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.jianghu66.top/Article/details/gtdpwjyefs.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.cdnleiting.top/Article/details/gtlycfifei.html

JS:   // child_process / cluster 模块
来源：http://dali.gzhubu.top/Article/details/gtbjhfavll.html

TS:   // child_process / cluster 模块
来源：http://dali.jianghu66.top/Article/details/gtikfgzxse.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.dianchejie.cn/Article/details/gtvrpkztms.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.yongpay.top/Article/details/gtyusuwzul.html

Ruby: // fork 块
来源：http://dali.xinyue.icu/Article/details/gtdjtisiaj.html

C#:   Parallel.For
来源：http://dali.xziqi.cn/Article/details/gtpucvuugi.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtbjaqpath.html

P. 常用工具函数
来源：http://dali.iojbl.cn/Article/details/gtnvkhrhwi.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtnycmluqv.html

[P01] 生成 UUID
来源：http://dali.sweek.top/Article/details/gtwmjhbixw.html

Py:   str(uuid.uuid4())
来源：http://dali.haohaochexian.top/Article/details/gtgzczzptc.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.hfpthk.cn/Article/details/gtnnludzeg.html

JS:   crypto.randomUUID()
来源：http://dali.vqdsnc.cn/Article/details/gthypimzwy.html

TS:   crypto.randomUUID()
来源：http://dali.cheryme.top/Article/details/gttpeotcwi.html

Java: UUID.randomUUID().toString()
来源：http://dali.ppjwa.cn/Article/details/gtsddkopvg.html

Go:   // 用 github.com/google/uuid
来源：http://dali.andypj.xyz/Article/details/gtzcxjbpbb.html

Ruby: SecureRandom.uuid
来源：http://dali.jinqigufen.top/Article/details/gtfmpooltv.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.sweek.top/Article/details/gtszlnkada.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zdqjudy.top/Article/details/gtrdpfajmj.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.yuanzhike.top/Article/details/gttjbqbjgn.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.gzhubu.top/Article/details/gtjuubynfn.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjaodmmtz.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.xuetiantiany.cn/Article/details/gtgqryrilh.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gtgbkuusri.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.hnqzz.top/Article/details/gtwqsmtorj.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.feifeiyinyue.top/Article/details/gtgutrvzpw.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.fengsongda.top/Article/details/gtyhichyso.html

[P03] 生成短随机字符串
来源：http://dali.shuidangran.top/Article/details/gtgvtzyouk.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.yangfankeji.com/Article/details/gtakoqtatb.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.tanke756.top/Article/details/gtosgizzyh.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.bjfxy.top/Article/details/gtfjfsuuph.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhongyouzk.top/Article/details/gtmknhsdei.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.jiagoushi.top/Article/details/gtrqrrcprc.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhongyouzk.top/Article/details/gtnibrkunp.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.nwbrower.top/Article/details/gtuwfswrky.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.cheryme.top/Article/details/gtgdklbxfc.html

[P04] 求长度
来源：http://dali.ydzc1.top/Article/details/gtxmjyzuxp.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.sufxvd.cn/Article/details/gtxpwiimnd.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.aibaodan.cn/Article/details/gtxlexbtca.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.birdmap.top/Article/details/gtvqbinedg.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.hysaishi.cn/Article/details/gtbqzzmmxe.html

Java: list.size();  map.size();  s.length()
来源：http://dali.daria6918.cn/Article/details/gtxwpygocn.html

Go:   len(arr);  len(m)
来源：http://dali.dashuyun.cn/Article/details/gtxsrtwmxu.html

Ruby: x.length;  x.size
来源：http://dali.yanxiufei.cn/Article/details/gtbvvbwstu.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.fengsongda.top/Article/details/gtcyelxthl.html

[P05] 判断两个对象内容是否相等
来源：http://dali.chenlongwang.top/Article/details/gtzshtxcys.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zycfv.cn/Article/details/gtaxzyztow.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.jyoumei.cn/Article/details/gtaefdvjde.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhiwuduotai.top/Article/details/gtkuugddft.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.jinghuilouyu.cn/Article/details/gtyjjfcasu.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.yuxming.cn/Article/details/gtovoyfnzp.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.yanxiufei.cn/Article/details/gtufqjbalk.html

Ruby: a == b
来源：http://dali.svipenyu.cn/Article/details/gtvqkcpzia.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.kuanghao11.cn/Article/details/gtadqrqwbv.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.havefunace.top/Article/details/gtobsjkcbl.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.shuidangran.top/Article/details/gtyhgohqoy.html

PHP:  if (empty($x)) {}
来源：http://dali.ybcxt.top/Article/details/gtipjrpuro.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.0kj1m.cn/Article/details/gtpkerycko.html

TS:   if (x == null) {}
来源：http://dali.pengpengdd.cyou/Article/details/gthyrikfzj.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.yuanzhike.top/Article/details/gtssfxjsjv.html

Go:   if x == nil {}
来源：http://dali.sysykeji.top/Article/details/gtaubztdvj.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.wangshuangyany.cn/Article/details/gtsyynrgjv.html

C#:   if (x is null) {}
来源：http://dali.chenjidiqi.icu/Article/details/gtgjqqogov.html

[P07] 防抖与节流
来源：http://dali.daria6918.cn/Article/details/gtedmoaatn.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.0kj1m.cn/Article/details/gttamipahj.html

PHP:  // 手写时间戳比较
来源：http://dali.jinghuilouyu.cn/Article/details/gtsnrhsxgv.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.nwbrower.top/Article/details/gtofievkmz.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yj20258.top/Article/details/gtkammbfqh.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.hysaishi.cn/Article/details/gtwmmvyhkn.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.jinqigufen.top/Article/details/gtsqmmlahf.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.tianlin.xyz/Article/details/gtagwpmlme.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.redwolf501.top/Article/details/gtcobrwwcz.html

[P08] 处理浮点精度问题
来源：http://dali.hnxiangtu.top/Article/details/gtzxnuslqu.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtahfjmhyv.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.jinqigufen.top/Article/details/gtkswxrmhh.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqwfwwrde.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.tian-w.cn/Article/details/gtxifbsckx.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.sweek.top/Article/details/gthdtelqrg.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.jyoumei.cn/Article/details/gtehipwoxt.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.havefunace.top/Article/details/gtophnujhy.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.sufxvd.cn/Article/details/gtutffwzlf.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtdbmwkqmx.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.0kj1m.cn/Article/details/gtetkbtbbn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtwsiqqzay.html

[Q01] 创建表
来源：http://dali.zhoulong.xyz/Article/details/gtfmzrgstf.html

CREATE TABLE users (
来源：http://dali.yvedp.cn/Article/details/gtmkodouja.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.nwbrower.top/Article/details/gtpeextwdq.html

name VARCHAR(50) NOT NULL,
来源：http://dali.zhixingplan.top/Article/details/gtbvdsvpuh.html

email VARCHAR(100) UNIQUE,
来源：http://dali.yueranfly.top/Article/details/gtvgbfmpjn.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.mhx1999.top/Article/details/gtwywtnyes.html

);
来源：http://dali.ybcxt.top/Article/details/gtxcljabxq.html

[Q02] 创建带外键的表
来源：http://dali.shanyushiyangtech.top/Article/details/gtuibnnjzk.html

CREATE TABLE orders (
来源：http://dali.jinqigufen.top/Article/details/gtamkrnved.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.yuanzhike.top/Article/details/gtakvipewk.html

user_id INT NOT NULL,
来源：http://dali.0kj1m.cn/Article/details/gtbcqbvqcu.html

amount DECIMAL(10, 2),
来源：http://dali.shanyushiyangtech.top/Article/details/gtbgndsets.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.quarkkingdee.top/Article/details/gtwuihfnna.html

);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxccxkdok.html

[Q03] 增加列
来源：http://dali.c1oappe.top/Article/details/gtegsjvzrq.html

ALTER TABLE users ADD COLUMN age INT DEFAULT 0;
来源：http://dali.sysykeji.top/Article/details/gtqflewdvl.html

[Q04] 修改列类型
来源：http://dali.zhijiandao.cn/Article/details/gtdlqodyqt.html


<!-- 参考信息 -->