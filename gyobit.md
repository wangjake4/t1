代发 wailian999

TS:   process.cwd()
来源：http://dali.bjfxy.top/Article/details/gtorrrttlr.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.daria6918.cn/Article/details/gtkzsydstg.html

Go:   os.Getwd()
来源：http://dali.sxryk.cn/Article/details/gtpukkvdvu.html

Ruby: Dir.pwd
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnhxwmdvv.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.shangyingyoupin.top/Article/details/gtajlqealv.html

[M05] 设置退出码
来源：http://dali.havefunace.top/Article/details/gtvgxtmxrb.html

Py:   sys.exit(1)
来源：http://dali.cheryme.top/Article/details/gtvpyotjlg.html

PHP:  exit(1);
来源：http://dali.ybcxt.top/Article/details/gtcewaritb.html

JS:   process.exit(1)
来源：http://dali.hnqzz.top/Article/details/gtjmmowiyr.html

TS:   process.exit(1)
来源：http://dali.jlsjyb.cn/Article/details/gthknptpyn.html

Java: System.exit(1)
来源：http://dali.mhx1999.top/Article/details/gtjufzlkhu.html

Go:   os.Exit(1)
来源：http://dali.yuxming.cn/Article/details/gtgtsoqxpb.html

Ruby: exit 1
来源：http://dali.svipenyu.cn/Article/details/gtjzrlqjrw.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.jiagoushi.top/Article/details/gtfrikictb.html

[M06] 向标准错误输出
来源：http://dali.hnxiangtu.top/Article/details/gtyxehwjir.html

Py:   print("err", file=sys.stderr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjthewdri.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.hnxiangtu.top/Article/details/gtwbicwmuy.html

JS:   console.error("err")
来源：http://dali.ybcxt.top/Article/details/gtvdwcshoc.html

TS:   console.error("err")
来源：http://dali.yj202588.top/Article/details/gtexbsrnga.html

Java: System.err.println("err")
来源：http://dali.zhiwuduotai.top/Article/details/gthqvdvuig.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.dashuyun.cn/Article/details/gtxhlcipry.html

Ruby: warn "err"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmykokohh.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.jyoumei.cn/Article/details/gtajhjkxwv.html

[M07] 判断是否为主入口
来源：http://dali.hongshengwenyu.top/Article/details/gthvnsfotv.html

Py:   if __name__ == "__main__":
来源：http://dali.iojbl.cn/Article/details/gtcqrghejj.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.jinyuanbaomall.cn/Article/details/gtejdktezd.html

JS:   require.main === module
来源：http://dali.nwbrower.top/Article/details/gtlozmsblv.html

TS:   require.main === module
来源：http://dali.shangyingyoupin.top/Article/details/gtaoxffggh.html

Java: public static void main(String[] args)
来源：http://dali.nanxinkj.top/Article/details/gtgfsqnidr.html

Go:   func main()
来源：http://dali.yj20258.top/Article/details/gtzfxumdhj.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.shanyushiyangtech.top/Article/details/gtsovmjclq.html

C#:   static void Main(string[] args)
来源：http://dali.nwbrower.top/Article/details/gtvwvigesg.html

[M08] 获取系统与运行时信息
来源：http://dali.hysaishi.cn/Article/details/gtsjysftoa.html

Py:   platform.system();  platform.python_version()
来源：http://dali.fzhhl.top/Article/details/gtmivyhnrq.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.yj20258.top/Article/details/gtirszjhbc.html

JS:   process.platform;  process.version
来源：http://dali.jinyuanbaomall.cn/Article/details/gtohsavfci.html

TS:   process.platform;  process.version
来源：http://dali.cdnleiting.top/Article/details/gtonpcvqlw.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.ivvv.top/Article/details/gtppspmhrv.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjajizbya.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.sweek.top/Article/details/gtasckjwim.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.yj202588.top/Article/details/gtvpzxhzhn.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtdilcrxfr.html

N. 数据结构与算法
来源：http://dali.ivvv.top/Article/details/gtfcoufaxy.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtevilhblu.html

[N01] 二分查找（有序数组）
来源：http://dali.shzxlz.cn/Article/details/gtiwhyyige.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.sxryk.cn/Article/details/gtdqpxpkip.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.ybcxt.top/Article/details/gteslpjvvd.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hongshengwenyu.top/Article/details/gtmgdwbolm.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.daxiang520.top/Article/details/gtmrwludhk.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.jinqigfzy.top/Article/details/gtksnfcjoh.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.daxiang520.top/Article/details/gtrfukchzl.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.jinqigfzy.top/Article/details/gtlxqardfb.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.daxiang520.top/Article/details/gtvwjkcqox.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.aibaodan.cn/Article/details/gtbfyquoiz.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.gzhubu.top/Article/details/gtkqtzzxag.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.tanke756.top/Article/details/gtfstiroen.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yangfankeji.com/Article/details/gtvhpxsxgm.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.nanxinkj.top/Article/details/gtcpekdyml.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.hysaishi.cn/Article/details/gttrudgnxy.html

Go:   slices.Sort(arr)
来源：http://dali.snrcjt.cn/Article/details/gtmzqrxkmk.html

Ruby: arr.sort
来源：http://dali.cheryme.top/Article/details/gtswfukpib.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.ehwqpu.com/Article/details/gtauyycpan.html

[N03] 快速排序（分治示例）
来源：http://dali.zdqjudy.top/Article/details/gtiptcpsan.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.quarkkingdee.top/Article/details/gtgqvplboc.html

PHP:  // 递归实现，或用 usort
来源：http://dali.dashuyun.cn/Article/details/gtmemxmvco.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.ppjwa.cn/Article/details/gttfwxnpxc.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.9152youxi.cn/Article/details/gttlvbqoge.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zycfv.cn/Article/details/gtiphfagpr.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.yongpay.top/Article/details/gtuenabsxi.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.bjfxy.top/Article/details/gtmxfrapoi.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.jlsjyb.cn/Article/details/gtjjtaiuwj.html

[N04] 斐波那契数列
来源：http://dali.aizwys.cn/Article/details/gtrymuulrn.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.9152youxi.cn/Article/details/gtsjafrzby.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.sysykeji.top/Article/details/gtagsodjpq.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.iojbl.cn/Article/details/gtdiegumid.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.snrcjt.cn/Article/details/gtbldsyuho.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zycfv.cn/Article/details/gtbvdipndi.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.316326.xyz/Article/details/gtsdenbysz.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.yanxiufei.cn/Article/details/gtfkqxcizb.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.dianchejie.cn/Article/details/gttemgiect.html

[N05] 最大公约数
来源：http://dali.tanke756.top/Article/details/gtcunwjorh.html

Py:   math.gcd(a, b)
来源：http://dali.andypj.xyz/Article/details/gtkmxvqsvv.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.xuetiantiany.cn/Article/details/gtsnjfmuvq.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yuanzhike.top/Article/details/gtpufdjjvl.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.shzxlz.cn/Article/details/gtxkumtwdr.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.snrcjt.cn/Article/details/gttbyfoljl.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.bjfxy.top/Article/details/gtmdmelebh.html

Ruby: a.gcd(b)
来源：http://dali.zycfv.cn/Article/details/gttijqppqx.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.cdnleiting.top/Article/details/gtsttwsawt.html

[N06] 判断回文字符串
来源：http://dali.jinqigufen.top/Article/details/gtdlbwzoqd.html

Py:   s == s[::-1]
来源：http://dali.hywenlv.cn/Article/details/gtagxfjcih.html

PHP:  $s === strrev($s);
来源：http://dali.yongpay.top/Article/details/gtrrsddzgw.html

JS:   s === [...s].reverse().join("")
来源：http://dali.jinqigfzy.top/Article/details/gtfwdwwcwf.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhongyouzk.top/Article/details/gtkublkxgr.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.gzhubu.top/Article/details/gtkqfcrywa.html

Go:   // 双指针从两端比较
来源：http://dali.tianlin.xyz/Article/details/gthyvejjyh.html

Ruby: s == s.reverse
来源：http://dali.gogol.net.cn/Article/details/gtgwbldnnn.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhongyouzk.top/Article/details/gtwjbyrijk.html

[N07] 两数之和（返回下标）
来源：http://dali.9152youxi.cn/Article/details/gtzkxbjcrl.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.sxryk.cn/Article/details/gttncwxyao.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxlzizdbp.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.pycfn.com/Article/details/gtniabsdhl.html

TS:   // 手写 Map<string, number>
来源：http://dali.ehwqpu.com/Article/details/gtlrgzbogo.html

Java: // 手写 HashMap
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlomllcyp.html

Go:   // 手写 map[int]int
来源：http://dali.xinyue.icu/Article/details/gtxpogqqgs.html

Ruby: // 手写 Hash
来源：http://dali.nanxinkj.top/Article/details/gtrfheityv.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.jinqigfzy.top/Article/details/gtspzcqqpp.html

[N08] 生成全排列
来源：http://dali.xuetiantiany.cn/Article/details/gtrwwmgttl.html

Py:   itertools.permutations(arr)
来源：http://dali.yueranfly.top/Article/details/gtqjryfkqm.html

PHP:  // 手写递归交换
来源：http://dali.mhx1999.top/Article/details/gtnwdhtqvi.html

JS:   // 手写回溯递归
来源：http://dali.xinyue.icu/Article/details/gtmkssqoze.html

TS:   // 手写回溯递归
来源：http://dali.gogol.net.cn/Article/details/gthoofqhld.html

Java: // 手写回溯递归
来源：http://dali.tianlin.xyz/Article/details/gtgigshmhz.html

Go:   // 手写回溯递归
来源：http://dali.gzhubu.top/Article/details/gtelfscerh.html

Ruby: arr.permutation.to_a
来源：http://dali.dashuyun.cn/Article/details/gttwtlkxnn.html

C#:   // 手写回溯递归
来源：http://dali.hnxiangtu.top/Article/details/gtzxlqubaz.html

[N09] 栈与队列
来源：http://dali.sweek.top/Article/details/gtacefejpz.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.daria6918.cn/Article/details/gtibyouvgq.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.hysaishi.cn/Article/details/gtvcvxeiwt.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.yvedp.cn/Article/details/gtymcuaymo.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.hongshengwenyu.top/Article/details/gtoeoyzoso.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.yuxming.cn/Article/details/gttbniuosa.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.xuetiantiany.cn/Article/details/gtbqqnwwta.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.meibo888.top/Article/details/gtbvhigzqg.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.hongshengwenyu.top/Article/details/gtcngewtos.html

[N10] 链表节点定义
来源：http://dali.pengpengdd.cyou/Article/details/gtgcbtdrmu.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.jyoumei.cn/Article/details/gtxckjgsns.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.daria6918.cn/Article/details/gtnxexbdqo.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmpqnntwq.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.shuidangran.top/Article/details/gtjbjthsex.html

Java: class Node { int v; Node next; }
来源：http://dali.guowangkeji.top/Article/details/gtbexevrlo.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.cheryme.top/Article/details/gtqfaadrlg.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.cucudq.cn/Article/details/gtaqebwkpe.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.ybcxt.top/Article/details/gtsfuhdhqx.html

[N11] 二叉树中序遍历
来源：http://dali.yangfankeji.com/Article/details/gtkzmxswzs.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.gzhubu.top/Article/details/gtmdjkayjz.html

PHP:  // 手写递归函数
来源：http://dali.ppjwa.cn/Article/details/gtljnvaadd.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.chenzaomai.com/Article/details/gtwtncjzcq.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.shanyushiyangtech.top/Article/details/gthgrqpclj.html

Java: // 手写递归
来源：http://dali.jinqigufen.top/Article/details/gtzgafzhkq.html

Go:   // 手写递归
来源：http://dali.iojbl.cn/Article/details/gtcfyvehhy.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.redwolf501.top/Article/details/gtzuuruwpn.html

C#:   // 手写递归
来源：http://dali.wangshuangyany.cn/Article/details/gtioscuhsb.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.jiagoushi.top/Article/details/gtiazdgvvm.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhaomingkeji.xyz/Article/details/gtksqeqvox.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.jinqigufen.top/Article/details/gtzwlsnbst.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.hongshengwenyu.top/Article/details/gtenietlfp.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jianghu66.top/Article/details/gteyzapjsh.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yanxiufei.cn/Article/details/gtyvqsllad.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.chenjidiqi.icu/Article/details/gtvpgzivzo.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gtzajabqgn.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.haohaochexian.top/Article/details/gtajtsdfxf.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtdlsmllwx.html

O. 并发与异步
来源：http://dali.zhengqikj.top/Article/details/gtyfirnrek.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtwnftunvs.html

[O01] 启动一个线程
来源：http://dali.ywan-chungtsiang.top/Article/details/gtculjffvv.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.birdmap.top/Article/details/gtugvptbjz.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.dianchejie.cn/Article/details/gtvzgrybfk.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gtdplfeagf.html

TS:   // 同 JS
来源：http://dali.ybcxt.top/Article/details/gtpsjvbspm.html

Java: new Thread(() -> f()).start()
来源：http://dali.haohaochexian.top/Article/details/gtvjjffpup.html

Go:   go f()
来源：http://dali.ppjwa.cn/Article/details/gtuorgilql.html

Ruby: Thread.new { f }
来源：http://dali.pengpengdd.cyou/Article/details/gtqdictsgy.html

C#:   Task.Run(() => F());
来源：http://dali.yj202588.top/Article/details/gtdrygospv.html

[O02] 使用线程池
来源：http://dali.daxiang520.top/Article/details/gtkuvspnwv.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.yj20258.top/Article/details/gtobhcgpjq.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.ehwqpu.com/Article/details/gtfvzstbdj.html

JS:   // worker_threads 线程池
来源：http://dali.chenzaomai.com/Article/details/gtfczgufei.html

TS:   // worker_threads 线程池
来源：http://dali.birdmap.top/Article/details/gtopxxmfxk.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.chenjidiqi.icu/Article/details/gtmjoecwrg.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.cashguo.top/Article/details/gtiewvjjts.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.xziqi.cn/Article/details/gtmhynpete.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.chenlongwang.top/Article/details/gtpduztiae.html

[O03] 加锁保护共享数据
来源：http://dali.zdqjudy.top/Article/details/gtysrnexbu.html

Py:   with lock: shared += 1
来源：http://dali.ybcxt.top/Article/details/gtkxqzvzyr.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zdqjudy.top/Article/details/gtbprzrqrh.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.havefunace.top/Article/details/gtbjagynfk.html

TS:   // 同 JS
来源：http://dali.xuanzx.com/Article/details/gtobpqahnh.html

Java: synchronized (this) { shared++; }
来源：http://dali.feifeiyinyue.top/Article/details/gtmhkjmodh.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.xuetiantiany.cn/Article/details/gtqrlbvhue.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.svipenyu.cn/Article/details/gtskhefauz.html

C#:   lock (gate) { shared++; }
来源：http://dali.gogol.net.cn/Article/details/gtknxunllm.html

[O04] 定义异步函数并等待
来源：http://dali.dashuyun.cn/Article/details/gtinmaeqgt.html

Py:   async def f():⏎    await g()
来源：http://dali.yvedp.cn/Article/details/gtwumjsgtz.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.fzhhl.top/Article/details/gtkomrudfy.html

JS:   async function f() { await g(); }
来源：http://dali.gotoacloud.top/Article/details/gtyuzjmzmc.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.ybcxt.top/Article/details/gtcslqoext.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.tanke756.top/Article/details/gtfdtfalui.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.yonumen.top/Article/details/gtftyhgznd.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.jiagoushi.top/Article/details/gtulvmwvdj.html

C#:   async Task F() { await G(); }
来源：http://dali.gzhubu.top/Article/details/gtloethyrn.html

[O05] 并发执行并等待全部完成
来源：http://dali.jinqigfzy.top/Article/details/gtscvjssov.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gtbebmremj.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.havefunace.top/Article/details/gtmbhuklka.html

JS:   await Promise.all(tasks)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrxqwyrla.html

TS:   await Promise.all(tasks)
来源：http://dali.feifeiyinyue.top/Article/details/gtanxeonez.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.yongpay.top/Article/details/gtagwjccns.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.0kj1m.cn/Article/details/gtzhsvrogc.html

Ruby: threads.map(&:join)
来源：http://dali.gzhubu.top/Article/details/gtaupmcdkl.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.jianghu66.top/Article/details/gtpwvvkyyc.html

[O06] 使用进程池
来源：http://dali.hysaishi.cn/Article/details/gtwqzevnok.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.svipenyu.cn/Article/details/gtxtesqoij.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.jlsjyb.cn/Article/details/gtstdtzrzg.html

JS:   // child_process / cluster 模块
来源：http://dali.zdqjudy.top/Article/details/gtllxnwgug.html

TS:   // child_process / cluster 模块
来源：http://dali.zhixingplan.top/Article/details/gtqyisgdim.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.tanke756.top/Article/details/gtxkhfpjtj.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.svipenyu.cn/Article/details/gtltrijexz.html

Ruby: // fork 块
来源：http://dali.cucudq.cn/Article/details/gtqyxdbysy.html

C#:   Parallel.For
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxreolopv.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtcyzvzhxx.html

P. 常用工具函数
来源：http://dali.yj202588.top/Article/details/gthshyzfhb.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtwsvrtsfd.html

[P01] 生成 UUID
来源：http://dali.yongpay.top/Article/details/gtfgnnltcs.html

Py:   str(uuid.uuid4())
来源：http://dali.sxryk.cn/Article/details/gtkxxsnjvx.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.xylfe.cn/Article/details/gtdqkpvhut.html

JS:   crypto.randomUUID()
来源：http://dali.shzxlz.cn/Article/details/gtefpdaplj.html

TS:   crypto.randomUUID()
来源：http://dali.zycfv.cn/Article/details/gtytumfqvr.html

Java: UUID.randomUUID().toString()
来源：http://dali.andypj.xyz/Article/details/gtkdfzjrkl.html

Go:   // 用 github.com/google/uuid
来源：http://dali.yj202588.top/Article/details/gtokuzslqr.html

Ruby: SecureRandom.uuid
来源：http://dali.jlsjyb.cn/Article/details/gtjytgcnnl.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.yongpay.top/Article/details/gtiryusxaj.html

[P02] MD5 / SHA256 摘要
来源：http://dali.aizwys.cn/Article/details/gtgicyztcj.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.fzhhl.top/Article/details/gtfcgawxcb.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfqxeaevi.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.tanke756.top/Article/details/gtgjvzpscu.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.nanxuanxn.top/Article/details/gtvwlzvckv.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.haohaochexian.top/Article/details/gtsfeqlyax.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.mhx1999.top/Article/details/gtfmhxauoz.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.gaohongyu789.top/Article/details/gtfjgnidsd.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.dashuyun.cn/Article/details/gtbcamkrkz.html

[P03] 生成短随机字符串
来源：http://dali.snrcjt.cn/Article/details/gtsarynvoc.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.dashuyun.cn/Article/details/gtmkwmefet.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.zhijiandao.cn/Article/details/gtazjrvsiu.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.guowangkeji.top/Article/details/gttkhhetrt.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.ivvv.top/Article/details/gtegpoufpq.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.yanxiufei.cn/Article/details/gtsreczgem.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.yanxiufei.cn/Article/details/gtzddwlimx.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.jinqigufen.top/Article/details/gtuwdkrnyk.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.xylfe.cn/Article/details/gtqversmxs.html

[P04] 求长度
来源：http://dali.yj20258.top/Article/details/gtkvtncnef.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.shangyingyoupin.top/Article/details/gtavhoplak.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.hfpthk.cn/Article/details/gtfqqoqlxc.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jianghu66.top/Article/details/gtyvabqdld.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jlsjyb.cn/Article/details/gtthxssidg.html

Java: list.size();  map.size();  s.length()
来源：http://dali.shuidangran.top/Article/details/gtzjimuysy.html

Go:   len(arr);  len(m)
来源：http://dali.sweek.top/Article/details/gtammwppit.html

Ruby: x.length;  x.size
来源：http://dali.aizwys.cn/Article/details/gttijchdme.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.xuetiantiany.cn/Article/details/gtlmjshjkm.html

[P05] 判断两个对象内容是否相等
来源：http://dali.svipenyu.cn/Article/details/gtwhbglaqt.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.cqqwz.cn/Article/details/gtrdrkmmld.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.cucudq.cn/Article/details/gtzhumnodd.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.svipenyu.cn/Article/details/gtnilvharq.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.sufxvd.cn/Article/details/gtyothyvlx.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.ybcxt.top/Article/details/gttllvvcwm.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.jqgfzy.top/Article/details/gtmjweluha.html

Ruby: a == b
来源：http://dali.sxryk.cn/Article/details/gtqqwhglnu.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.jianghu66.top/Article/details/gtxrokaorf.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.hfpthk.cn/Article/details/gtrkfdxern.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.fengsongda.top/Article/details/gtitctzbmy.html

PHP:  if (empty($x)) {}
来源：http://dali.yueranfly.top/Article/details/gtgqktyvvp.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.xylfe.cn/Article/details/gtsyopawyx.html

TS:   if (x == null) {}
来源：http://dali.hnxiangtu.top/Article/details/gttievckqn.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zdqjudy.top/Article/details/gtdrdlxtto.html

Go:   if x == nil {}
来源：http://dali.gzhubu.top/Article/details/gtmrlpxrzx.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.jinqigufen.top/Article/details/gtarmispmj.html

C#:   if (x is null) {}
来源：http://dali.sxryk.cn/Article/details/gthllfuwui.html

[P07] 防抖与节流
来源：http://dali.jinghuilouyu.cn/Article/details/gtfmuzrcfi.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.yanxiufei.cn/Article/details/gtsrqyliuf.html

PHP:  // 手写时间戳比较
来源：http://dali.xylfe.cn/Article/details/gtekrminbl.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jlsjyb.cn/Article/details/gtsjpehald.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.shangyingyoupin.top/Article/details/gtpiccsotz.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.sufxvd.cn/Article/details/gtgzssmsfi.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.sweek.top/Article/details/gtzmpmdbdk.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zycfv.cn/Article/details/gtghrdiyer.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.jqgfzy.top/Article/details/gtzprzfgtf.html

[P08] 处理浮点精度问题
来源：http://dali.sxryk.cn/Article/details/gtugzjhdzp.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.c1oappe.top/Article/details/gtqjtjnltb.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiaxqhhwc.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.guowangkeji.top/Article/details/gtyfmuhsvi.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.aizwys.cn/Article/details/gtgkaywqwp.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.hnqzz.top/Article/details/gtoltapqbp.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.daria6918.cn/Article/details/gtkwdkshab.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.jlsjyb.cn/Article/details/gtixezmncv.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.c1oappe.top/Article/details/gtpahyeuzh.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtayhpzcab.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.gaohongyu789.top/Article/details/gtwlupkqan.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtnkhiudru.html

[Q01] 创建表
来源：http://dali.daxiang520.top/Article/details/gtelabxslr.html

CREATE TABLE users (
来源：http://dali.sweek.top/Article/details/gtjhpyqdfi.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zdqjudy.top/Article/details/gtzkvwgluj.html

name VARCHAR(50) NOT NULL,
来源：http://dali.yonumen.top/Article/details/gtplilghso.html

email VARCHAR(100) UNIQUE,
来源：http://dali.fzhhl.top/Article/details/gtxaywirlg.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.hfpthk.cn/Article/details/gtixmjcuqh.html

);
来源：http://dali.meibo888.top/Article/details/gtpydwmasf.html

[Q02] 创建带外键的表
来源：http://dali.yj202588.top/Article/details/gtqbbaxxlu.html

CREATE TABLE orders (
来源：http://dali.yangfankeji.com/Article/details/gtffbbipgx.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.zhijiandao.cn/Article/details/gtjodwnsqp.html

user_id INT NOT NULL,
来源：http://dali.cashguo.top/Article/details/gteemxmnws.html

amount DECIMAL(10, 2),
来源：http://dali.bjfxy.top/Article/details/gtaordkmtv.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.hysaishi.cn/Article/details/gtqnuyqxtw.html


<!-- 参考信息 -->