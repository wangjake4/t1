代发 wailian999

TS:   process.cwd()
来源：http://dali.yanxiufei.cn/Article/details/gt2gcqafsvo.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.xuanzx.com/Article/details/gt2mpzaticf.html

Go:   os.Getwd()
来源：http://dali.haohaochexian.top/Article/details/gt2eznlumix.html

Ruby: Dir.pwd
来源：http://dali.gotoacloud.top/Article/details/gt2ariybjmn.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.sweek.top/Article/details/gt2wiihwwmx.html

[M05] 设置退出码
来源：http://dali.fzhhl.top/Article/details/gt2mggtayoh.html

Py:   sys.exit(1)
来源：http://dali.tanke756.top/Article/details/gt2kajlsgkz.html

PHP:  exit(1);
来源：http://dali.nanxuanxn.top/Article/details/gt2qzxduehe.html

JS:   process.exit(1)
来源：http://dali.zdqjudy.top/Article/details/gt2gleuzdrv.html

TS:   process.exit(1)
来源：http://dali.jiagoushi.top/Article/details/gt2zjwbqbsa.html

Java: System.exit(1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cxxfcbcl.html

Go:   os.Exit(1)
来源：http://dali.9152youxi.cn/Article/details/gt2qagkncnm.html

Ruby: exit 1
来源：http://dali.zhixingplan.top/Article/details/gt2xeugeypk.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.ehwqpu.com/Article/details/gt2ortftwza.html

[M06] 向标准错误输出
来源：http://dali.cqqwz.cn/Article/details/gt2axgmoqst.html

Py:   print("err", file=sys.stderr)
来源：http://dali.aizwys.cn/Article/details/gt2estskkyz.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.hywenlv.cn/Article/details/gt2aoonltov.html

JS:   console.error("err")
来源：http://dali.hnqzz.top/Article/details/gt2uzpxnhax.html

TS:   console.error("err")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xvcvbsmg.html

Java: System.err.println("err")
来源：http://dali.jqgufenzy.top/Article/details/gt2zddiloum.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.haohaochexian.top/Article/details/gt2canukucz.html

Ruby: warn "err"
来源：http://dali.hfpthk.cn/Article/details/gt2hptorbvu.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.hywenlv.cn/Article/details/gt2zevfaqiw.html

[M07] 判断是否为主入口
来源：http://dali.hongshengwenyu.top/Article/details/gt2hgtrtjaz.html

Py:   if __name__ == "__main__":
来源：http://dali.ivvv.top/Article/details/gt2aldnvcho.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.shzxlz.cn/Article/details/gt2eaadbrxt.html

JS:   require.main === module
来源：http://dali.ppjwa.cn/Article/details/gt2aausfiad.html

TS:   require.main === module
来源：http://dali.sweek.top/Article/details/gt2ppufudhj.html

Java: public static void main(String[] args)
来源：http://dali.0kj1m.cn/Article/details/gt2koojaezt.html

Go:   func main()
来源：http://dali.nanxuanxn.top/Article/details/gt2pgpamdjb.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.hnxiangtu.top/Article/details/gt2wikphqdi.html

C#:   static void Main(string[] args)
来源：http://dali.smart0.xyz/Article/details/gt2newcnupk.html

[M08] 获取系统与运行时信息
来源：http://dali.sxryk.cn/Article/details/gt2rdszxqhh.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gzikvsuj.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.bjfxy.top/Article/details/gt2rzyqkhpi.html

JS:   process.platform;  process.version
来源：http://dali.jianghu66.top/Article/details/gt2bovojzku.html

TS:   process.platform;  process.version
来源：http://dali.yvedp.cn/Article/details/gt2vavoaewv.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.jinqigfzy.top/Article/details/gt2ecajjobr.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.nanxinkj.top/Article/details/gt2inufaqgn.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2axceieff.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.aibaodan.cn/Article/details/gt2xsmzchqn.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gt2frmizboi.html

N. 数据结构与算法
来源：http://dali.jlsjyb.cn/Article/details/gt2wrfnubas.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gt2mdrkungv.html

[N01] 二分查找（有序数组）
来源：http://dali.wangshuangyany.cn/Article/details/gt2srheikrs.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.cheryme.top/Article/details/gt2jkyjdxgy.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.jqgufenzy.top/Article/details/gt2goojpjns.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.chenlongwang.top/Article/details/gt2thumeelo.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.ivvv.top/Article/details/gt2sqiygtuz.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.snrcjt.cn/Article/details/gt2ilwgwtuh.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.fengsongda.top/Article/details/gt2qoqgtzgu.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.gzhubu.top/Article/details/gt2nuwomlzl.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.yj202588.top/Article/details/gt2ovcduwaz.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.daxiang520.top/Article/details/gt2awhacaas.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yanxiufei.cn/Article/details/gt2zqdtvjls.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.pycfn.com/Article/details/gt2mqioyxkw.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yuanzhike.top/Article/details/gt2qpventac.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.nanxinkj.top/Article/details/gt2xqtsivpc.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hdzdixzn.html

Go:   slices.Sort(arr)
来源：http://dali.shzxlz.cn/Article/details/gt2uwklqzsl.html

Ruby: arr.sort
来源：http://dali.meibo888.top/Article/details/gt2mpgvrsbu.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.hfpthk.cn/Article/details/gt2owqcawna.html

[N03] 快速排序（分治示例）
来源：http://dali.hammf.cn/Article/details/gt2pkdrddmc.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.nwbrower.top/Article/details/gt2fjnpuomi.html

PHP:  // 递归实现，或用 usort
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lawmoidh.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.xuetiantiany.cn/Article/details/gt2xxfnbaeh.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.shuidangran.top/Article/details/gt2upsvedqh.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.jinghuilouyu.cn/Article/details/gt2juyeqlkc.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.chenlongwang.top/Article/details/gt2uqdoogqm.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qfaocofd.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.nwbrower.top/Article/details/gt2vraytgij.html

[N04] 斐波那契数列
来源：http://dali.dashuyun.cn/Article/details/gt2tcgwkslu.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.haohaochexian.top/Article/details/gt2aubbhaja.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.jqgfzy.top/Article/details/gt2vqpldgjk.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2btbgdsbr.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yanxiufei.cn/Article/details/gt2lyhcysih.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.c1oappe.top/Article/details/gt2pnyaguci.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.ivvv.top/Article/details/gt2weemipoc.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.chenzaomai.com/Article/details/gt2zjbyghnz.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.sufxvd.cn/Article/details/gt2zdlsfqtw.html

[N05] 最大公约数
来源：http://dali.zdqjudy.top/Article/details/gt2eeibubxi.html

Py:   math.gcd(a, b)
来源：http://dali.guannengcc.top/Article/details/gt2rhrtexkx.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2toygzcuf.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.gzhubu.top/Article/details/gt2tjxmjolq.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.quarkkingdee.top/Article/details/gt2ldflzexq.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ezbwkhmz.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.wangshuangyany.cn/Article/details/gt2hzycjitc.html

Ruby: a.gcd(b)
来源：http://dali.xziqi.cn/Article/details/gt2pzvyadnl.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.hywenlv.cn/Article/details/gt2llqaaqqn.html

[N06] 判断回文字符串
来源：http://dali.cqqwz.cn/Article/details/gt2zxeujslg.html

Py:   s == s[::-1]
来源：http://dali.bjfxy.top/Article/details/gt2taaiqkpl.html

PHP:  $s === strrev($s);
来源：http://dali.redwolf501.top/Article/details/gt2hljscdua.html

JS:   s === [...s].reverse().join("")
来源：http://dali.yangfankeji.com/Article/details/gt2nugjcgvc.html

TS:   s === [...s].reverse().join("")
来源：http://dali.9152youxi.cn/Article/details/gt2ztknfchz.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mfdrbvzh.html

Go:   // 双指针从两端比较
来源：http://dali.sxryk.cn/Article/details/gt2hzrokurc.html

Ruby: s == s.reverse
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mrsgnrtd.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.chenlongwang.top/Article/details/gt2ssogiomp.html

[N07] 两数之和（返回下标）
来源：http://dali.wangshuangyany.cn/Article/details/gt2ajcqeqvn.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.0kj1m.cn/Article/details/gt2hzrvevns.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.xinyue.icu/Article/details/gt2ttikembq.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.ybcxt.top/Article/details/gt2tkwlbqya.html

TS:   // 手写 Map<string, number>
来源：http://dali.zdqjudy.top/Article/details/gt2tscjckld.html

Java: // 手写 HashMap
来源：http://dali.zhongyouzk.top/Article/details/gt2ebhysbdc.html

Go:   // 手写 map[int]int
来源：http://dali.jqgufenzy.top/Article/details/gt2ghkxmgsr.html

Ruby: // 手写 Hash
来源：http://dali.ybcxt.top/Article/details/gt2ytmhjhxo.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.ybcxt.top/Article/details/gt2tuykpaco.html

[N08] 生成全排列
来源：http://dali.quarkkingdee.top/Article/details/gt2ichibmef.html

Py:   itertools.permutations(arr)
来源：http://dali.jinqigufen.top/Article/details/gt2lgimfeev.html

PHP:  // 手写递归交换
来源：http://dali.yangfankeji.com/Article/details/gt2xaaiknmi.html

JS:   // 手写回溯递归
来源：http://dali.jlsjyb.cn/Article/details/gt2wvpfarbi.html

TS:   // 手写回溯递归
来源：http://dali.zhoulong.xyz/Article/details/gt2toxbzruu.html

Java: // 手写回溯递归
来源：http://dali.zhengqikj.top/Article/details/gt2dzlawwpc.html

Go:   // 手写回溯递归
来源：http://dali.cdnleiting.top/Article/details/gt2erhbjlgm.html

Ruby: arr.permutation.to_a
来源：http://dali.shzxlz.cn/Article/details/gt2dktakfdx.html

C#:   // 手写回溯递归
来源：http://dali.cqqwz.cn/Article/details/gt2llcjeuko.html

[N09] 栈与队列
来源：http://dali.shuidangran.top/Article/details/gt2ernnuido.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhoulong.xyz/Article/details/gt2evnnaikr.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.ivvv.top/Article/details/gt2okyuwczj.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.guowangkeji.top/Article/details/gt2mqieawiw.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.pycfn.com/Article/details/gt2vabogngn.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.xuanzx.com/Article/details/gt2mgaaixra.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.ybcxt.top/Article/details/gt2vpizkckq.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.c1oappe.top/Article/details/gt2usbkjsar.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.yvedp.cn/Article/details/gt2ltdmlmqu.html

[N10] 链表节点定义
来源：http://dali.xinyue.icu/Article/details/gt2gmslccxy.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.snrcjt.cn/Article/details/gt2ukglgvmk.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.dianchejie.cn/Article/details/gt2uzunkfde.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.cucudq.cn/Article/details/gt2fgcegmuh.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.daria6918.cn/Article/details/gt2mbedmsxk.html

Java: class Node { int v; Node next; }
来源：http://dali.hywenlv.cn/Article/details/gt2eykyqkcz.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.iojbl.cn/Article/details/gt2ltfxfvjx.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.xinyue.icu/Article/details/gt2vfkdyfxz.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.nanxuanxn.top/Article/details/gt2jowbqlvz.html

[N11] 二叉树中序遍历
来源：http://dali.gzhubu.top/Article/details/gt2rhkzhaur.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.redwolf501.top/Article/details/gt2bcrrusoi.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ffqeejfp.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.cqqwz.cn/Article/details/gt2khdcyabm.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.xziqi.cn/Article/details/gt2royevhlj.html

Java: // 手写递归
来源：http://dali.pycfn.com/Article/details/gt2nfxsbynb.html

Go:   // 手写递归
来源：http://dali.yj20258888.top/Article/details/gt2tnjrucjy.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.yonumen.top/Article/details/gt2ikyjuket.html

C#:   // 手写递归
来源：http://dali.fzhhl.top/Article/details/gt2lxmelkzb.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.yongpay.top/Article/details/gt2mouprjbp.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.jianghu66.top/Article/details/gt2dqtsrqpm.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.hfpthk.cn/Article/details/gt2kjlryuan.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.kuanghao11.cn/Article/details/gt2evfahxud.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jinqigfzy.top/Article/details/gt2qfqvzffx.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.guowangkeji.top/Article/details/gt2brxroudz.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.jinqigfzy.top/Article/details/gt2tdyvplmc.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.meibo888.top/Article/details/gt2rhcvpgoj.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.aizwys.cn/Article/details/gt2niaefmms.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gt2iinalxed.html

O. 并发与异步
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pdciufpu.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gt2pmfpxfqm.html

[O01] 启动一个线程
来源：http://dali.chenlongwang.top/Article/details/gt2ntbhjlsy.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.smart0.xyz/Article/details/gt2mzovdvaf.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.aizwys.cn/Article/details/gt2svxnfpoq.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.hnqzz.top/Article/details/gt2vchwnijm.html

TS:   // 同 JS
来源：http://dali.bjfxy.top/Article/details/gt2bhgtbmzy.html

Java: new Thread(() -> f()).start()
来源：http://dali.bjfxy.top/Article/details/gt2xvqltyjt.html

Go:   go f()
来源：http://dali.xziqi.cn/Article/details/gt2stdogajo.html

Ruby: Thread.new { f }
来源：http://dali.nwbrower.top/Article/details/gt2nmhdgxwm.html

C#:   Task.Run(() => F());
来源：http://dali.smart0.xyz/Article/details/gt2elimjblw.html

[O02] 使用线程池
来源：http://dali.nanxuanxn.top/Article/details/gt2cbqpnzsu.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.cashguo.top/Article/details/gt2alpcerkd.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.guowangkeji.top/Article/details/gt2hnyycvqg.html

JS:   // worker_threads 线程池
来源：http://dali.shzxlz.cn/Article/details/gt2kpcczbgb.html

TS:   // worker_threads 线程池
来源：http://dali.zhengqikj.top/Article/details/gt2zgulrxgu.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.gaohongyu789.top/Article/details/gt2tgxxmhia.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.hnxiangtu.top/Article/details/gt2pzxykfod.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.yonumen.top/Article/details/gt2ckvcsrjk.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.cqqwz.cn/Article/details/gt2wanpzjru.html

[O03] 加锁保护共享数据
来源：http://dali.ivvv.top/Article/details/gt2fpxbjgam.html

Py:   with lock: shared += 1
来源：http://dali.jqgufenzy.top/Article/details/gt2yjbqduxm.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhongyouzk.top/Article/details/gt2fotmxtts.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhengqikj.top/Article/details/gt2iuzkyqxr.html

TS:   // 同 JS
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lhfcjnbi.html

Java: synchronized (this) { shared++; }
来源：http://dali.guowangkeji.top/Article/details/gt2rtdiwdrm.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2eqkalbff.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.daria6918.cn/Article/details/gt2bwahluug.html

C#:   lock (gate) { shared++; }
来源：http://dali.daria6918.cn/Article/details/gt2bnfnxdco.html

[O04] 定义异步函数并等待
来源：http://dali.xuetiantiany.cn/Article/details/gt2tlkeeves.html

Py:   async def f():⏎    await g()
来源：http://dali.yuanzhike.top/Article/details/gt2jxdvpngj.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.chenzaomai.com/Article/details/gt2yvgebbhu.html

JS:   async function f() { await g(); }
来源：http://dali.ppjwa.cn/Article/details/gt2evstzvap.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.sysykeji.top/Article/details/gt2tlfympht.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.shuidangran.top/Article/details/gt2hypbnfmd.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.hongshengwenyu.top/Article/details/gt2dwnnrbpu.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.jinqigufen.top/Article/details/gt2qhwkjjgy.html

C#:   async Task F() { await G(); }
来源：http://dali.feifeiyinyue.top/Article/details/gt2caudpeun.html

[O05] 并发执行并等待全部完成
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bbzjtigi.html

Py:   asyncio.gather(*tasks)
来源：http://dali.yuxming.cn/Article/details/gt2oxrctavk.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.havefunace.top/Article/details/gt2bubdmyit.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2ozlcbtzk.html

TS:   await Promise.all(tasks)
来源：http://dali.quarkkingdee.top/Article/details/gt2porfpzgj.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.fengsongda.top/Article/details/gt2eevujljc.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.havefunace.top/Article/details/gt2stkzabpx.html

Ruby: threads.map(&:join)
来源：http://dali.yanxiufei.cn/Article/details/gt2qbdsxpdq.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.hammf.cn/Article/details/gt2yoltjpbt.html

[O06] 使用进程池
来源：http://dali.iojbl.cn/Article/details/gt2mtwsqomx.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.yvedp.cn/Article/details/gt2ixjznhwa.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.sufxvd.cn/Article/details/gt2wdoamqqv.html

JS:   // child_process / cluster 模块
来源：http://dali.fengsongda.top/Article/details/gt2gfymiojq.html

TS:   // child_process / cluster 模块
来源：http://dali.andypj.xyz/Article/details/gt2bwzlhzoq.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhixingplan.top/Article/details/gt2jzxoyarr.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.hnxiangtu.top/Article/details/gt2fdxumtzk.html

Ruby: // fork 块
来源：http://dali.daxiang520.top/Article/details/gt2yhduvvui.html

C#:   Parallel.For
来源：http://dali.jiagoushi.top/Article/details/gt2wkwdunqc.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gt2zhhqkvdw.html

P. 常用工具函数
来源：http://dali.chenzaomai.com/Article/details/gt2piinmzud.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gt2usseuxgr.html

[P01] 生成 UUID
来源：http://dali.vqdsnc.cn/Article/details/gt2csxilxxn.html

Py:   str(uuid.uuid4())
来源：http://dali.yanxiufei.cn/Article/details/gt2hwvzydvr.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.quarkkingdee.top/Article/details/gt2llkkxrdk.html

JS:   crypto.randomUUID()
来源：http://dali.wangdashe.top/Article/details/gt2ukvpndbc.html

TS:   crypto.randomUUID()
来源：http://dali.xinyue.icu/Article/details/gt2uwsewxcs.html

Java: UUID.randomUUID().toString()
来源：http://dali.bjfxy.top/Article/details/gt2edbqsnhn.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhongyouzk.top/Article/details/gt2glznxbyj.html

Ruby: SecureRandom.uuid
来源：http://dali.jqgfzy.top/Article/details/gt2drirdpiy.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.hnxiangtu.top/Article/details/gt2omlareui.html

[P02] MD5 / SHA256 摘要
来源：http://dali.shuidangran.top/Article/details/gt2vadrzdrz.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.guannengcc.top/Article/details/gt2gijqpqaq.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.jqgufenzy.top/Article/details/gt2fdpgjjyy.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhoulong.xyz/Article/details/gt2utrnbibi.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.andypj.xyz/Article/details/gt2juzueprq.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.redwolf501.top/Article/details/gt2uzdrqgox.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.nanxuanxn.top/Article/details/gt2gvgcdpzk.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.nanxinkj.top/Article/details/gt2ygyqsnas.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.meibo888.top/Article/details/gt2pexzdced.html

[P03] 生成短随机字符串
来源：http://dali.jiagoushi.top/Article/details/gt2bahoqihm.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.yanxiufei.cn/Article/details/gt2krvvhtlo.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.yongpay.top/Article/details/gt2doabflny.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yuxming.cn/Article/details/gt2cuqvaklz.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.chenlongwang.top/Article/details/gt2fttoaaes.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.sweek.top/Article/details/gt2elwmzjlz.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.316326.xyz/Article/details/gt2wijldpks.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.haohaochexian.top/Article/details/gt2qgdxckby.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.yj202588.top/Article/details/gt2baxqyibu.html

[P04] 求长度
来源：http://dali.zhoulong.xyz/Article/details/gt2kwyhfvqs.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zycfv.cn/Article/details/gt2oydfusbf.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.xylfe.cn/Article/details/gt2kwwbvefg.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yueranfly.top/Article/details/gt2mwgqpemv.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jianghu66.top/Article/details/gt2aonbtzya.html

Java: list.size();  map.size();  s.length()
来源：http://dali.zhixingplan.top/Article/details/gt2hiihgudf.html

Go:   len(arr);  len(m)
来源：http://dali.nanxinkj.top/Article/details/gt2uospvled.html

Ruby: x.length;  x.size
来源：http://dali.nwbrower.top/Article/details/gt2lnezlvet.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.xinyue.icu/Article/details/gt2vsrphsix.html

[P05] 判断两个对象内容是否相等
来源：http://dali.gzhubu.top/Article/details/gt2lgogykwi.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zhengqikj.top/Article/details/gt2qegqogpc.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.chenzaomai.com/Article/details/gt2thcexbir.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uplbmhuo.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.chenjidiqi.icu/Article/details/gt2uozssrub.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.hnxiangtu.top/Article/details/gt2kransjbt.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.jlsjyb.cn/Article/details/gt2hgxnlqwi.html

Ruby: a == b
来源：http://dali.xylfe.cn/Article/details/gt2vbulipcl.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zdqjudy.top/Article/details/gt2chkkysuf.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.yvedp.cn/Article/details/gt2akhnxyxh.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.chenlongwang.top/Article/details/gt2frfkhsze.html

PHP:  if (empty($x)) {}
来源：http://dali.hywenlv.cn/Article/details/gt2sfrdafik.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.jiagoushi.top/Article/details/gt2jabfgzfj.html

TS:   if (x == null) {}
来源：http://dali.chenlongwang.top/Article/details/gt2tcpmmvza.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.yongpay.top/Article/details/gt2brkdimkf.html

Go:   if x == nil {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2sigpvdum.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.sysykeji.top/Article/details/gt2hsyfskts.html

C#:   if (x is null) {}
来源：http://dali.yongpay.top/Article/details/gt2odjazcmi.html

[P07] 防抖与节流
来源：http://dali.9152youxi.cn/Article/details/gt2wnagmyll.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.fengsongda.top/Article/details/gt2vppywxmr.html

PHP:  // 手写时间戳比较
来源：http://dali.aibaodan.cn/Article/details/gt2tablvgnq.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hfpthk.cn/Article/details/gt2ixapqbwh.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.9152youxi.cn/Article/details/gt2ldrsqyxi.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.sweek.top/Article/details/gt2xmpvkddh.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhiwuduotai.top/Article/details/gt2xbuyezjr.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.cqqwz.cn/Article/details/gt2qzcbkprt.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.shzxlz.cn/Article/details/gt2ugnjviiy.html

[P08] 处理浮点精度问题
来源：http://dali.feifeiyinyue.top/Article/details/gt2aipeijql.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pbytlatz.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.yongpay.top/Article/details/gt2nfzfjvsl.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.bjfxy.top/Article/details/gt2wfuwwhis.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.yuxming.cn/Article/details/gt2xpcjjzkn.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.nanxinkj.top/Article/details/gt2jfmkmbho.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.tanke756.top/Article/details/gt2dwysvbxq.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.316326.xyz/Article/details/gt2yrxhvyxm.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.yanxiufei.cn/Article/details/gt2zfbdexpf.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gt2otlggkzy.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bpktmtoc.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gt2pprbndpk.html

[Q01] 创建表
来源：http://dali.birdmap.top/Article/details/gt2ucudwylq.html

CREATE TABLE users (
来源：http://dali.gaohongyu789.top/Article/details/gt2oynwmllh.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.iojbl.cn/Article/details/gt2gjhlezrr.html

name VARCHAR(50) NOT NULL,
来源：http://dali.cheryme.top/Article/details/gt2akwordhy.html

email VARCHAR(100) UNIQUE,
来源：http://dali.ydzc1.top/Article/details/gt2vcmqlayt.html

created_at DATETIME DEFAULT CURRENT_TIMESTAMP
来源：http://dali.daria6918.cn/Article/details/gt2ywiglmfd.html

);
来源：http://dali.xinyue.icu/Article/details/gt2botzviyv.html

[Q02] 创建带外键的表
来源：http://dali.andypj.xyz/Article/details/gt2vuxkcwbt.html

CREATE TABLE orders (
来源：http://dali.aibaodan.cn/Article/details/gt2yokgcxal.html

id BIGINT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.hfpthk.cn/Article/details/gt2olxptfot.html

user_id INT NOT NULL,
来源：http://dali.meibo888.top/Article/details/gt2mnxfmcob.html

amount DECIMAL(10, 2),
来源：http://dali.feifeiyinyue.top/Article/details/gt2yoygklqs.html

FOREIGN KEY (user_id) REFERENCES users(id)
来源：http://dali.xziqi.cn/Article/details/gt2uktgiwru.html


<!-- 参考信息 -->