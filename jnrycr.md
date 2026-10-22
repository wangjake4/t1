代发 wailian999

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.xuanzx.com/Article/details/gt2wgfpqdjq.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.yuxming.cn/Article/details/gt2ttotwgmv.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.wangshuangyany.cn/Article/details/gt2szsjjkfi.html

C#:   Process.Start("ls", "-l");
来源：http://dali.xylfe.cn/Article/details/gt2vszexras.html

[M04] 获取当前工作目录
来源：http://dali.ppjwa.cn/Article/details/gt2podfqido.html

Py:   os.getcwd()
来源：http://dali.shzxlz.cn/Article/details/gt2abusjdjp.html

PHP:  getcwd();
来源：http://dali.snrcjt.cn/Article/details/gt2ggucmdrs.html

JS:   process.cwd()
来源：http://dali.yvedp.cn/Article/details/gt2zhymitro.html

TS:   process.cwd()
来源：http://dali.zdqjudy.top/Article/details/gt2etnifbgg.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.jinqigufen.top/Article/details/gt2aonncrtr.html

Go:   os.Getwd()
来源：http://dali.jqgufenzy.top/Article/details/gt2wkvqjmdj.html

Ruby: Dir.pwd
来源：http://dali.zhongyouzk.top/Article/details/gt2wsjgvubf.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.bjfxy.top/Article/details/gt2doskstgn.html

[M05] 设置退出码
来源：http://dali.bjfxy.top/Article/details/gt2rjyreegs.html

Py:   sys.exit(1)
来源：http://dali.yangfankeji.com/Article/details/gt2dyimlkww.html

PHP:  exit(1);
来源：http://dali.hammf.cn/Article/details/gt2dbddlouh.html

JS:   process.exit(1)
来源：http://dali.316326.xyz/Article/details/gt2zpwtshdj.html

TS:   process.exit(1)
来源：http://dali.nanxuanxn.top/Article/details/gt2cwmkonwx.html

Java: System.exit(1)
来源：http://dali.shzxlz.cn/Article/details/gt2uqhvmavh.html

Go:   os.Exit(1)
来源：http://dali.cheryme.top/Article/details/gt2zcdxceqm.html

Ruby: exit 1
来源：http://dali.jyoumei.cn/Article/details/gt2nzmjysyf.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.redwolf501.top/Article/details/gt2iwytaiqy.html

[M06] 向标准错误输出
来源：http://dali.gaohongyu789.top/Article/details/gt2hpiixpca.html

Py:   print("err", file=sys.stderr)
来源：http://dali.redwolf501.top/Article/details/gt2zsfdfhnp.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhixingplan.top/Article/details/gt2wyksyobh.html

JS:   console.error("err")
来源：http://dali.chenlongwang.top/Article/details/gt2rhqlweku.html

TS:   console.error("err")
来源：http://dali.hammf.cn/Article/details/gt2ydsuuglc.html

Java: System.err.println("err")
来源：http://dali.gzhubu.top/Article/details/gt2ziaqsuoo.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.chenlongwang.top/Article/details/gt2tveghvfg.html

Ruby: warn "err"
来源：http://dali.jyoumei.cn/Article/details/gt2xewgvzew.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.redwolf501.top/Article/details/gt2lzisbudx.html

[M07] 判断是否为主入口
来源：http://dali.ivvv.top/Article/details/gt2eqvxoptg.html

Py:   if __name__ == "__main__":
来源：http://dali.xziqi.cn/Article/details/gt2yizvpsfh.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.yvedp.cn/Article/details/gt2mkajqdkt.html

JS:   require.main === module
来源：http://dali.gaohongyu789.top/Article/details/gt2goejkmbv.html

TS:   require.main === module
来源：http://dali.tanke756.top/Article/details/gt2cpqjwcip.html

Java: public static void main(String[] args)
来源：http://dali.fengsongda.top/Article/details/gt2regsxjxf.html

Go:   func main()
来源：http://dali.316326.xyz/Article/details/gt2yywmcshy.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.nwbrower.top/Article/details/gt2fjaaabai.html

C#:   static void Main(string[] args)
来源：http://dali.yangfankeji.com/Article/details/gt2prqekydd.html

[M08] 获取系统与运行时信息
来源：http://dali.cheryme.top/Article/details/gt2wfqlltbf.html

Py:   platform.system();  platform.python_version()
来源：http://dali.sysykeji.top/Article/details/gt2bbhvalxl.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uqbfemfv.html

JS:   process.platform;  process.version
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jazrxzvr.html

TS:   process.platform;  process.version
来源：http://dali.tian-w.cn/Article/details/gt2vprrjkzl.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.c1oappe.top/Article/details/gt2agdmwszp.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.cashguo.top/Article/details/gt2guljjhbx.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.hfpthk.cn/Article/details/gt2prbgudde.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.birdmap.top/Article/details/gt2wtossruf.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gt2brfboryw.html

N. 数据结构与算法
来源：http://dali.cucudq.cn/Article/details/gt2yibpebfn.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gt2veeuozpt.html

[N01] 二分查找（有序数组）
来源：http://dali.c1oappe.top/Article/details/gt2equeqvrc.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.hongshengwenyu.top/Article/details/gt2hcwfvfvv.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.bjfxy.top/Article/details/gt2pcpskzdu.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jqgufenzy.top/Article/details/gt2bkvhdbdo.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.xylfe.cn/Article/details/gt2vybmlmxh.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.kuanghao11.cn/Article/details/gt2wwhgpxzw.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.xinyue.icu/Article/details/gt2mclvxdxc.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.hysaishi.cn/Article/details/gt2iueucryz.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhengqikj.top/Article/details/gt2rxnyncdp.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.cucudq.cn/Article/details/gt2kjbqnlpa.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zycfv.cn/Article/details/gt2bcrgxobn.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.fzhhl.top/Article/details/gt2arulvswh.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.gogol.net.cn/Article/details/gt2jdgrngzd.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.quarkkingdee.top/Article/details/gt2unrxuilj.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.tian-w.cn/Article/details/gt2tfkuxbud.html

Go:   slices.Sort(arr)
来源：http://dali.zhongyouzk.top/Article/details/gt2ackyoyxv.html

Ruby: arr.sort
来源：http://dali.birdmap.top/Article/details/gt2miyrxorh.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.ydzc1.top/Article/details/gt2iaroyktd.html

[N03] 快速排序（分治示例）
来源：http://dali.jinghuilouyu.cn/Article/details/gt2aciqrepq.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.birdmap.top/Article/details/gt2vcgxfsxb.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhengqikj.top/Article/details/gt2meldcsfj.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.gaohongyu789.top/Article/details/gt2znefvegj.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.nanxuanxn.top/Article/details/gt2uvrxalnj.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.aibaodan.cn/Article/details/gt2itxuzann.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.cqqwz.cn/Article/details/gt2jyfengwd.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.ydzc1.top/Article/details/gt2uhhiiwnf.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.andypj.xyz/Article/details/gt2aixvicsu.html

[N04] 斐波那契数列
来源：http://dali.sxryk.cn/Article/details/gt2tgsvrwvr.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.jqgfzy.top/Article/details/gt2zmsmbsso.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.xuanzx.com/Article/details/gt2htgdoszb.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.guowangkeji.top/Article/details/gt2radvouzl.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.nanxinkj.top/Article/details/gt2cftenwwt.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.meibo888.top/Article/details/gt2yrqclxzp.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.snrcjt.cn/Article/details/gt2hnxtkoga.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.yangfankeji.com/Article/details/gt2sbryicvp.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lftjshug.html

[N05] 最大公约数
来源：http://dali.meibo888.top/Article/details/gt2qghgosmp.html

Py:   math.gcd(a, b)
来源：http://dali.hongshengwenyu.top/Article/details/gt2scbdrstt.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.iojbl.cn/Article/details/gt2bhazxhlo.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zycfv.cn/Article/details/gt2uktuarrq.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yj202588.top/Article/details/gt2lcwtjbnc.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.dashuyun.cn/Article/details/gt2ljijozro.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.yueranfly.top/Article/details/gt2qvemtfcp.html

Ruby: a.gcd(b)
来源：http://dali.yuxming.cn/Article/details/gt2gcapnsoo.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.cucudq.cn/Article/details/gt2yrormoej.html

[N06] 判断回文字符串
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jnfszlhj.html

Py:   s == s[::-1]
来源：http://dali.yonumen.top/Article/details/gt2tvsvrefx.html

PHP:  $s === strrev($s);
来源：http://dali.hysaishi.cn/Article/details/gt2tomfxvmh.html

JS:   s === [...s].reverse().join("")
来源：http://dali.gogol.net.cn/Article/details/gt2dubtwvxu.html

TS:   s === [...s].reverse().join("")
来源：http://dali.shuidangran.top/Article/details/gt2qoptvjty.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.xziqi.cn/Article/details/gt2ppugleqi.html

Go:   // 双指针从两端比较
来源：http://dali.ehwqpu.com/Article/details/gt2uolqceky.html

Ruby: s == s.reverse
来源：http://dali.tian-w.cn/Article/details/gt2iugyoahr.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.yuanzhike.top/Article/details/gt2cbwkawyt.html

[N07] 两数之和（返回下标）
来源：http://dali.chenjidiqi.icu/Article/details/gt2zvinwgvw.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.ivvv.top/Article/details/gt2ycbuzvow.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.0kj1m.cn/Article/details/gt2bibhxotn.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.snrcjt.cn/Article/details/gt2topzocvu.html

TS:   // 手写 Map<string, number>
来源：http://dali.9152youxi.cn/Article/details/gt2aslrfmmm.html

Java: // 手写 HashMap
来源：http://dali.cdnleiting.top/Article/details/gt2esjzsjnl.html

Go:   // 手写 map[int]int
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bovlepyo.html

Ruby: // 手写 Hash
来源：http://dali.meibo888.top/Article/details/gt2ivxvtdne.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.mhx1999.top/Article/details/gt2exokcevz.html

[N08] 生成全排列
来源：http://dali.cucudq.cn/Article/details/gt2dzqtcbph.html

Py:   itertools.permutations(arr)
来源：http://dali.shzxlz.cn/Article/details/gt2yqzdfgnj.html

PHP:  // 手写递归交换
来源：http://dali.xuetiantiany.cn/Article/details/gt2cswxqhqb.html

JS:   // 手写回溯递归
来源：http://dali.aibaodan.cn/Article/details/gt2vmobvjsl.html

TS:   // 手写回溯递归
来源：http://dali.zhoulong.xyz/Article/details/gt2iluheoly.html

Java: // 手写回溯递归
来源：http://dali.hysaishi.cn/Article/details/gt2tmwvwlqp.html

Go:   // 手写回溯递归
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wszgxtby.html

Ruby: arr.permutation.to_a
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kcbufdlt.html

C#:   // 手写回溯递归
来源：http://dali.nwbrower.top/Article/details/gt2smtgvitk.html

[N09] 栈与队列
来源：http://dali.cheryme.top/Article/details/gt2bzmwtjmj.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.jinqigufen.top/Article/details/gt2crkkmovl.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.yuanzhike.top/Article/details/gt2ldqorauy.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.quarkkingdee.top/Article/details/gt2pzujbkxf.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.yj20258.top/Article/details/gt2kipqdzcf.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.chenzaomai.com/Article/details/gt2zgweeumg.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.jinqigufen.top/Article/details/gt2xcemuwfa.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.vqdsnc.cn/Article/details/gt2ckqmrgnu.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.jyoumei.cn/Article/details/gt2gqomrihm.html

[N10] 链表节点定义
来源：http://dali.mhx1999.top/Article/details/gt2pzowwooj.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.bjfxy.top/Article/details/gt2cvaxxixm.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.cashguo.top/Article/details/gt2fywpyizh.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.bjfxy.top/Article/details/gt2qbilocxr.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.jianghu66.top/Article/details/gt2cveujvwk.html

Java: class Node { int v; Node next; }
来源：http://dali.chenzaomai.com/Article/details/gt2ckqiulpi.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhengqikj.top/Article/details/gt2lsguuagc.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.jqgufenzy.top/Article/details/gt2xqhyqrzw.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.cashguo.top/Article/details/gt2oqbmlhkr.html

[N11] 二叉树中序遍历
来源：http://dali.aizwys.cn/Article/details/gt2gocnxvvf.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.gzhubu.top/Article/details/gt2ogxaxmux.html

PHP:  // 手写递归函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wdvlddfi.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.shangyingyoupin.top/Article/details/gt2fnkqehho.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.vqdsnc.cn/Article/details/gt2nsmcxyxj.html

Java: // 手写递归
来源：http://dali.havefunace.top/Article/details/gt2tploalgz.html

Go:   // 手写递归
来源：http://dali.quarkkingdee.top/Article/details/gt2dxkecwvz.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.cdnleiting.top/Article/details/gt2anktbxfe.html

C#:   // 手写递归
来源：http://dali.ybcxt.top/Article/details/gt2alyqptmm.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.dashuyun.cn/Article/details/gt2vgvkkstc.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.chenlongwang.top/Article/details/gt2qkeezrlr.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.yangfankeji.com/Article/details/gt2hifsqpcm.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.vqdsnc.cn/Article/details/gt2ooiyuzlj.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.0kj1m.cn/Article/details/gt2rrvrgspt.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tiwtcipd.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.hywenlv.cn/Article/details/gt2jgylklny.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.cheryme.top/Article/details/gt2bboczpqu.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.cucudq.cn/Article/details/gt2xlrllnrb.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yaedrqse.html

O. 并发与异步
来源：http://dali.tian-w.cn/Article/details/gt2egbcofyf.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gt2gmfkufnh.html

[O01] 启动一个线程
来源：http://dali.yanxiufei.cn/Article/details/gt2nghmawah.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.xuetiantiany.cn/Article/details/gt2lrjoreck.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.cdnleiting.top/Article/details/gt2mkiaqkms.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.hongshengwenyu.top/Article/details/gt2fyfmokep.html

TS:   // 同 JS
来源：http://dali.tanke756.top/Article/details/gt2lnxfoqif.html

Java: new Thread(() -> f()).start()
来源：http://dali.aizwys.cn/Article/details/gt2okrfqnkx.html

Go:   go f()
来源：http://dali.zhiwuduotai.top/Article/details/gt2yunnocho.html

Ruby: Thread.new { f }
来源：http://dali.yongpay.top/Article/details/gt2ukhaqlbt.html

C#:   Task.Run(() => F());
来源：http://dali.shuidangran.top/Article/details/gt2ebcbibem.html

[O02] 使用线程池
来源：http://dali.gotoacloud.top/Article/details/gt2xwveqypb.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zycfv.cn/Article/details/gt2dolqexta.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.yangfankeji.com/Article/details/gt2nymagwdf.html

JS:   // worker_threads 线程池
来源：http://dali.mhx1999.top/Article/details/gt2hrcmvjbi.html

TS:   // worker_threads 线程池
来源：http://dali.cheryme.top/Article/details/gt2islktxmd.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zycfv.cn/Article/details/gt2zpehwkzg.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.cqqwz.cn/Article/details/gt2pjvpusaa.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.fengsongda.top/Article/details/gt2ogkccgqk.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.ehwqpu.com/Article/details/gt2tpbmprrq.html

[O03] 加锁保护共享数据
来源：http://dali.pycfn.com/Article/details/gt2siksszmq.html

Py:   with lock: shared += 1
来源：http://dali.guowangkeji.top/Article/details/gt2ewvgjdfa.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.nwbrower.top/Article/details/gt2bfrrjkin.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.haohaochexian.top/Article/details/gt2danhcsbg.html

TS:   // 同 JS
来源：http://dali.shanyushiyangtech.top/Article/details/gt2svumlndy.html

Java: synchronized (this) { shared++; }
来源：http://dali.tanke756.top/Article/details/gt2gvupjhbe.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fppmqjpu.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.jqgfzy.top/Article/details/gt2dmtcydqz.html

C#:   lock (gate) { shared++; }
来源：http://dali.smart0.xyz/Article/details/gt2xcezkaaa.html

[O04] 定义异步函数并等待
来源：http://dali.tian-w.cn/Article/details/gt2nttcojga.html

Py:   async def f():⏎    await g()
来源：http://dali.chenlongwang.top/Article/details/gt2lgwesuuk.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tujougkb.html

JS:   async function f() { await g(); }
来源：http://dali.dianchejie.cn/Article/details/gt2chwnqsvg.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.jiagoushi.top/Article/details/gt2xklruvmx.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.cucudq.cn/Article/details/gt2oicbteta.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.snrcjt.cn/Article/details/gt2yqoifnte.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.hfpthk.cn/Article/details/gt2oudkxoxz.html

C#:   async Task F() { await G(); }
来源：http://dali.chenzaomai.com/Article/details/gt2iliwmfjm.html

[O05] 并发执行并等待全部完成
来源：http://dali.xziqi.cn/Article/details/gt2pmykoepy.html

Py:   asyncio.gather(*tasks)
来源：http://dali.fengsongda.top/Article/details/gt2eyrbsovr.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.iojbl.cn/Article/details/gt2hpsddaeq.html

JS:   await Promise.all(tasks)
来源：http://dali.meibo888.top/Article/details/gt2kihwqmnn.html

TS:   await Promise.all(tasks)
来源：http://dali.dashuyun.cn/Article/details/gt2zpwnomae.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.yvedp.cn/Article/details/gt2ldephxqe.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.cqqwz.cn/Article/details/gt2sjrgqnzr.html

Ruby: threads.map(&:join)
来源：http://dali.sxryk.cn/Article/details/gt2odthljcu.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.shangyingyoupin.top/Article/details/gt2cpvpbnsw.html

[O06] 使用进程池
来源：http://dali.guowangkeji.top/Article/details/gt2mhipbmid.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.wangdashe.top/Article/details/gt2obifgfmz.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.xziqi.cn/Article/details/gt2drfonkov.html

JS:   // child_process / cluster 模块
来源：http://dali.cucudq.cn/Article/details/gt2mdmpmpyi.html

TS:   // child_process / cluster 模块
来源：http://dali.sweek.top/Article/details/gt2pplnzxqq.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.cashguo.top/Article/details/gt2uuycwfrn.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.cheryme.top/Article/details/gt2zxcisydj.html

Ruby: // fork 块
来源：http://dali.cqqwz.cn/Article/details/gt2xxzkbeud.html

C#:   Parallel.For
来源：http://dali.jqgfzy.top/Article/details/gt2kcrwjuhi.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gt2sqwihqbz.html

P. 常用工具函数
来源：http://dali.hnqzz.top/Article/details/gt2bwkulrka.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gt2gqlfyzxm.html

[P01] 生成 UUID
来源：http://dali.zhengqikj.top/Article/details/gt2tzasrbax.html

Py:   str(uuid.uuid4())
来源：http://dali.hnqzz.top/Article/details/gt2jdeaizpn.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.yongpay.top/Article/details/gt2mhgtxevj.html

JS:   crypto.randomUUID()
来源：http://dali.ybcxt.top/Article/details/gt2fdmfqain.html

TS:   crypto.randomUUID()
来源：http://dali.nanxinkj.top/Article/details/gt2hqyutlys.html

Java: UUID.randomUUID().toString()
来源：http://dali.gaohongyu789.top/Article/details/gt2ebrhzlfq.html

Go:   // 用 github.com/google/uuid
来源：http://dali.meibo888.top/Article/details/gt2ymvopofn.html

Ruby: SecureRandom.uuid
来源：http://dali.chenjidiqi.icu/Article/details/gt2jotwypxn.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.feifeiyinyue.top/Article/details/gt2zjkjqwcf.html

[P02] MD5 / SHA256 摘要
来源：http://dali.jqgufenzy.top/Article/details/gt2nkapejpg.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.vqdsnc.cn/Article/details/gt2rsvoxtqw.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.0kj1m.cn/Article/details/gt2fukvcbbj.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.mhx1999.top/Article/details/gt2xapnssrb.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.birdmap.top/Article/details/gt2mrldzmds.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.cdnleiting.top/Article/details/gt2aqqpluwn.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.birdmap.top/Article/details/gt2ksmhpgus.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.yangfankeji.com/Article/details/gt2xvtsiktr.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.zhiwuduotai.top/Article/details/gt2mtjimwce.html

[P03] 生成短随机字符串
来源：http://dali.svipenyu.cn/Article/details/gt2fiimldea.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.nanxuanxn.top/Article/details/gt2kjdeteex.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.wangdashe.top/Article/details/gt2qmhztned.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.hongshengwenyu.top/Article/details/gt2hbxyqwuz.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.daxiang520.top/Article/details/gt2kladlaue.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fwsmtril.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.xziqi.cn/Article/details/gt2sdjbcoji.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.guannengcc.top/Article/details/gt2ultlociv.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.ydzc1.top/Article/details/gt2azpbacxo.html

[P04] 求长度
来源：http://dali.havefunace.top/Article/details/gt2sqjuewtl.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.jinqigufen.top/Article/details/gt2dvrgdhjf.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.ivvv.top/Article/details/gt2hvmqhoql.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.cqqwz.cn/Article/details/gt2hxubvtsb.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.0kj1m.cn/Article/details/gt2ufwimzmr.html

Java: list.size();  map.size();  s.length()
来源：http://dali.xinyue.icu/Article/details/gt2txpoofvn.html

Go:   len(arr);  len(m)
来源：http://dali.haohaochexian.top/Article/details/gt2etjrowql.html

Ruby: x.length;  x.size
来源：http://dali.yj202588.top/Article/details/gt2wpkabbnh.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.snrcjt.cn/Article/details/gt2rtrlcrpd.html

[P05] 判断两个对象内容是否相等
来源：http://dali.ydzc1.top/Article/details/gt2ixjyaacu.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.xuanzx.com/Article/details/gt2agjcuhvi.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.hongshengwenyu.top/Article/details/gt2kltvwqru.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.yvedp.cn/Article/details/gt2bouyeqvg.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.yuxming.cn/Article/details/gt2auzkzshl.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.yj20258888.top/Article/details/gt2cabdgcjp.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.tanke756.top/Article/details/gt2fhocgemv.html

Ruby: a == b
来源：http://dali.bjfxy.top/Article/details/gt2ixmidkrt.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.cdnleiting.top/Article/details/gt2fubjlxqd.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.nanxuanxn.top/Article/details/gt2ptutpuxl.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ngvrkter.html

PHP:  if (empty($x)) {}
来源：http://dali.jqgfzy.top/Article/details/gt2yoymorqj.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.tianlin.xyz/Article/details/gt2jywwoifq.html

TS:   if (x == null) {}
来源：http://dali.redwolf501.top/Article/details/gt2bxkxykxu.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.nwbrower.top/Article/details/gt2ddgtxtcy.html

Go:   if x == nil {}
来源：http://dali.meibo888.top/Article/details/gt2fuwkrbsr.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.tian-w.cn/Article/details/gt2zvgwikob.html

C#:   if (x is null) {}
来源：http://dali.xziqi.cn/Article/details/gt2bvdhfyqg.html

[P07] 防抖与节流
来源：http://dali.cqqwz.cn/Article/details/gt2ownlfehg.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.zhiwuduotai.top/Article/details/gt2hntjytmt.html

PHP:  // 手写时间戳比较
来源：http://dali.xuanzx.com/Article/details/gt2trvcfpfk.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bpltgpec.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hnqzz.top/Article/details/gt2nxssfxbr.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.pengpengdd.cyou/Article/details/gt2vllrheyt.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.birdmap.top/Article/details/gt2baxartuv.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.dashuyun.cn/Article/details/gt2muggkdkl.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lcqotqhx.html

[P08] 处理浮点精度问题
来源：http://dali.ybcxt.top/Article/details/gt2ssfvrtdb.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.nanxuanxn.top/Article/details/gt2emuffppz.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.9152youxi.cn/Article/details/gt2rviixvdq.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.snrcjt.cn/Article/details/gt2zvbfilee.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.guowangkeji.top/Article/details/gt2yjvgfvbn.html

Java: BigDecimal.valueOf(0.1).add(BigDecimal.valueOf(0.2))
来源：http://dali.xylfe.cn/Article/details/gt2wqvhqnum.html

Go:   math/big.Float，或全部换算成整数分再算
来源：http://dali.hnqzz.top/Article/details/gt2deorjvjh.html

Ruby: BigDecimal("0.1") + BigDecimal("0.2")
来源：http://dali.dianchejie.cn/Article/details/gt2hexcjygt.html

C#:   decimal d = 0.1m + 0.2m;      // decimal 为精确十进制
来源：http://dali.chenzaomai.com/Article/details/gt2adepnyhf.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gt2cjvoxivn.html

Q. SQL 专题（以 MySQL 8 为主，附 PostgreSQL 差异）
来源：http://dali.yueranfly.top/Article/details/gt2lqfpbgah.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gt2qseoxcyv.html

[Q01] 创建表
来源：http://dali.ydzc1.top/Article/details/gt2fqwvvgqk.html

CREATE TABLE users (
来源：http://dali.bjfxy.top/Article/details/gt2hslcqjhu.html

id INT PRIMARY KEY AUTO_INCREMENT,
来源：http://dali.redwolf501.top/Article/details/gt2mowkyzcv.html

name VARCHAR(50) NOT NULL,
来源：http://dali.kuanghao11.cn/Article/details/gt2snypsujp.html

email VARCHAR(100) UNIQUE,
来源：http://dali.jianghu66.top/Article/details/gt2eacrefgt.html


<!-- 参考信息 -->