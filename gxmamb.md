代发 wailian999

Ruby: ARGV
来源：http://dali.redwolf501.top/Article/details/gteoeckuhv.html

C#:   args 数组（Main 方法参数）
来源：http://dali.jqgufenzy.top/Article/details/gtxwjdricf.html

[M02] 读取环境变量
来源：http://dali.dashuyun.cn/Article/details/gtenzebuib.html

Py:   os.environ.get("HOME")
来源：http://dali.cashguo.top/Article/details/gtoffmulbd.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.daxiang520.top/Article/details/gtcnnzpdnc.html

JS:   process.env.HOME
来源：http://dali.smart0.xyz/Article/details/gtqshmrjal.html

TS:   process.env.HOME
来源：http://dali.gzhubu.top/Article/details/gtcltxctcb.html

Java: System.getenv("HOME")
来源：http://dali.jlsjyb.cn/Article/details/gtyrbxrknd.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.yj20258888.top/Article/details/gtznqsgmwy.html

Ruby: ENV["HOME"]
来源：http://dali.dianchejie.cn/Article/details/gtgzrtyngo.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.hnxiangtu.top/Article/details/gtwgsyrebt.html

[M03] 执行外部命令
来源：http://dali.jqgfzy.top/Article/details/gtkyzykylp.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.tanke756.top/Article/details/gtnsqfjgvl.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.ivvv.top/Article/details/gtnqhhblvt.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.hywenlv.cn/Article/details/gtedxtgxzy.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gtovorovxn.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.jinghuilouyu.cn/Article/details/gthlaovzly.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.jinqigufen.top/Article/details/gtbkqmehbm.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.pycfn.com/Article/details/gtyuosqxel.html

C#:   Process.Start("ls", "-l");
来源：http://dali.xinyue.icu/Article/details/gtyfvwwsqv.html

[M04] 获取当前工作目录
来源：http://dali.yanxiufei.cn/Article/details/gtqpsitvil.html

Py:   os.getcwd()
来源：http://dali.redwolf501.top/Article/details/gttcoldyjd.html

PHP:  getcwd();
来源：http://dali.andypj.xyz/Article/details/gtendlezrb.html

JS:   process.cwd()
来源：http://dali.hfpthk.cn/Article/details/gtotlubsgt.html

TS:   process.cwd()
来源：http://dali.shzxlz.cn/Article/details/gtgufvxjku.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zdqjudy.top/Article/details/gtpjlmgunk.html

Go:   os.Getwd()
来源：http://dali.daxiang520.top/Article/details/gtgknmrqeg.html

Ruby: Dir.pwd
来源：http://dali.dashuyun.cn/Article/details/gtayzdebvv.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.aizwys.cn/Article/details/gtxmadlpqg.html

[M05] 设置退出码
来源：http://dali.xuanzx.com/Article/details/gthyphovsx.html

Py:   sys.exit(1)
来源：http://dali.andypj.xyz/Article/details/gtfbwdlsxt.html

PHP:  exit(1);
来源：http://dali.hnxiangtu.top/Article/details/gtjlohcmmt.html

JS:   process.exit(1)
来源：http://dali.hfpthk.cn/Article/details/gthaiqlndv.html

TS:   process.exit(1)
来源：http://dali.wangdashe.top/Article/details/gtfrqqatkt.html

Java: System.exit(1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuiksmphu.html

Go:   os.Exit(1)
来源：http://dali.hnqzz.top/Article/details/gtdkdjgnpv.html

Ruby: exit 1
来源：http://dali.c1oappe.top/Article/details/gtpgikfjwd.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.smart0.xyz/Article/details/gtydzmhcxs.html

[M06] 向标准错误输出
来源：http://dali.jinqigfzy.top/Article/details/gtshusfzwe.html

Py:   print("err", file=sys.stderr)
来源：http://dali.wangshuangyany.cn/Article/details/gtbepaafzw.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.kuanghao11.cn/Article/details/gtyaeonpof.html

JS:   console.error("err")
来源：http://dali.cheryme.top/Article/details/gtsxnaxglj.html

TS:   console.error("err")
来源：http://dali.guowangkeji.top/Article/details/gtqbtdjgst.html

Java: System.err.println("err")
来源：http://dali.yuanzhike.top/Article/details/gtqrysghgk.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhiwuduotai.top/Article/details/gtratfsgxw.html

Ruby: warn "err"
来源：http://dali.kuanghao11.cn/Article/details/gtaqmkloyy.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.hysaishi.cn/Article/details/gtouhwqwzy.html

[M07] 判断是否为主入口
来源：http://dali.zycfv.cn/Article/details/gtksbcxnnr.html

Py:   if __name__ == "__main__":
来源：http://dali.9152youxi.cn/Article/details/gtutcgfxgw.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.tanke756.top/Article/details/gtakpsjrli.html

JS:   require.main === module
来源：http://dali.dashuyun.cn/Article/details/gtejtuxfrk.html

TS:   require.main === module
来源：http://dali.havefunace.top/Article/details/gtkjcgsbgp.html

Java: public static void main(String[] args)
来源：http://dali.fzhhl.top/Article/details/gtaicrkvdd.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gtwjknicix.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.sysykeji.top/Article/details/gtmrklwtxk.html

C#:   static void Main(string[] args)
来源：http://dali.hammf.cn/Article/details/gtktwdbxxr.html

[M08] 获取系统与运行时信息
来源：http://dali.shzxlz.cn/Article/details/gtvnxbibtm.html

Py:   platform.system();  platform.python_version()
来源：http://dali.yongpay.top/Article/details/gtfcrmixay.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.cashguo.top/Article/details/gtrtygxlpf.html

JS:   process.platform;  process.version
来源：http://dali.jyoumei.cn/Article/details/gtxdcdiepb.html

TS:   process.platform;  process.version
来源：http://dali.jianghu66.top/Article/details/gtkdrphple.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.hnqzz.top/Article/details/gtaoeummye.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.andypj.xyz/Article/details/gtntfuqglp.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhiwuduotai.top/Article/details/gtbrvkxqlk.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.cucudq.cn/Article/details/gtxwjskbtr.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtqcldepbw.html

N. 数据结构与算法
来源：http://dali.haohaochexian.top/Article/details/gtsvnwbpvg.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtleuimhiq.html

[N01] 二分查找（有序数组）
来源：http://dali.yj202588.top/Article/details/gtqbghtfnt.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.fzhhl.top/Article/details/gtiqunwqzw.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.shuidangran.top/Article/details/gtoixehkml.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.sysykeji.top/Article/details/gtutgyilwo.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.chenzaomai.com/Article/details/gtrlwlkthm.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.smart0.xyz/Article/details/gteuosbhob.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.pycfn.com/Article/details/gticcgxrvy.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.tian-w.cn/Article/details/gtfdkzxvqq.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.nwbrower.top/Article/details/gtwmwnmjdi.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.shuidangran.top/Article/details/gtylbfgtcm.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.ehwqpu.com/Article/details/gtkomerbvp.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.chenzaomai.com/Article/details/gtywysizad.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.ehwqpu.com/Article/details/gttsdidcoa.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.sufxvd.cn/Article/details/gtkxqgozuy.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.9152youxi.cn/Article/details/gtickswzzl.html

Go:   slices.Sort(arr)
来源：http://dali.zhoulong.xyz/Article/details/gtqqazmoej.html

Ruby: arr.sort
来源：http://dali.c1oappe.top/Article/details/gtdkebkwvi.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.kuanghao11.cn/Article/details/gtjopnrpcz.html

[N03] 快速排序（分治示例）
来源：http://dali.cqqwz.cn/Article/details/gtzoepklfr.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.cheryme.top/Article/details/gtwabinhpv.html

PHP:  // 递归实现，或用 usort
来源：http://dali.chenlongwang.top/Article/details/gtgvgzbryw.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.xuanzx.com/Article/details/gtpprlzybf.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yonumen.top/Article/details/gtqniqkptc.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.yj20258.top/Article/details/gtdaqimcjo.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.shuidangran.top/Article/details/gttoxmhttp.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.xuetiantiany.cn/Article/details/gtiagpdxut.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.wangshuangyany.cn/Article/details/gtkdaxytlz.html

[N04] 斐波那契数列
来源：http://dali.zhiwuduotai.top/Article/details/gtwzrwhldp.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.kuanghao11.cn/Article/details/gthvgixbph.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.dianchejie.cn/Article/details/gtsdiunufu.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.snrcjt.cn/Article/details/gtcxpuyssr.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.ydzc1.top/Article/details/gtnclhdlkj.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.sweek.top/Article/details/gtgyafqxaq.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.ehwqpu.com/Article/details/gtaziibuys.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.yuxming.cn/Article/details/gtcjeldjmf.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.gogol.net.cn/Article/details/gtstqxxpio.html

[N05] 最大公约数
来源：http://dali.sysykeji.top/Article/details/gtwrsduwnw.html

Py:   math.gcd(a, b)
来源：http://dali.sufxvd.cn/Article/details/gtguurwesp.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.cqqwz.cn/Article/details/gtazpdwagy.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.c1oappe.top/Article/details/gtzsyqxjqg.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yuanzhike.top/Article/details/gtxlrlwwej.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.hnqzz.top/Article/details/gtqtyrovul.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.daria6918.cn/Article/details/gtgmmwanil.html

Ruby: a.gcd(b)
来源：http://dali.hywenlv.cn/Article/details/gtruzmmhoe.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.yangfankeji.com/Article/details/gtzzgmswzx.html

[N06] 判断回文字符串
来源：http://dali.tian-w.cn/Article/details/gtxnxedtrf.html

Py:   s == s[::-1]
来源：http://dali.jianghu66.top/Article/details/gtznfdwjsx.html

PHP:  $s === strrev($s);
来源：http://dali.gaohongyu789.top/Article/details/gtdttczrlc.html

JS:   s === [...s].reverse().join("")
来源：http://dali.9152youxi.cn/Article/details/gtfopwjhdg.html

TS:   s === [...s].reverse().join("")
来源：http://dali.gzhubu.top/Article/details/gtzxtknfyk.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gtaudxhdan.html

Go:   // 双指针从两端比较
来源：http://dali.cashguo.top/Article/details/gtlqxnmyxy.html

Ruby: s == s.reverse
来源：http://dali.hongshengwenyu.top/Article/details/gtlqidfmlz.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.xziqi.cn/Article/details/gtsydvykas.html

[N07] 两数之和（返回下标）
来源：http://dali.hongshengwenyu.top/Article/details/gtpudiwxks.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.guowangkeji.top/Article/details/gtxcldjtoh.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.dianchejie.cn/Article/details/gtyddwajlo.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.cucudq.cn/Article/details/gtgmmtbyma.html

TS:   // 手写 Map<string, number>
来源：http://dali.bjfxy.top/Article/details/gthusmsrym.html

Java: // 手写 HashMap
来源：http://dali.fzhhl.top/Article/details/gteljnfkyi.html

Go:   // 手写 map[int]int
来源：http://dali.shuidangran.top/Article/details/gthoirxgss.html

Ruby: // 手写 Hash
来源：http://dali.hnxiangtu.top/Article/details/gtgpjvjaeu.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.yj202588.top/Article/details/gtepwcgwkt.html

[N08] 生成全排列
来源：http://dali.0kj1m.cn/Article/details/gtcjkzwbuy.html

Py:   itertools.permutations(arr)
来源：http://dali.cdnleiting.top/Article/details/gtcuxcysyc.html

PHP:  // 手写递归交换
来源：http://dali.xziqi.cn/Article/details/gtvbzyszhj.html

JS:   // 手写回溯递归
来源：http://dali.zhengqikj.top/Article/details/gtrkeyeaya.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gtifnxytxv.html

Java: // 手写回溯递归
来源：http://dali.zhixingplan.top/Article/details/gtwqpdezje.html

Go:   // 手写回溯递归
来源：http://dali.yj202588.top/Article/details/gtwxufjyko.html

Ruby: arr.permutation.to_a
来源：http://dali.jiagoushi.top/Article/details/gtdnimtmus.html

C#:   // 手写回溯递归
来源：http://dali.zhiwuduotai.top/Article/details/gtygdxllwx.html

[N09] 栈与队列
来源：http://dali.sxryk.cn/Article/details/gtpnpezpjl.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhongyouzk.top/Article/details/gtbdafgxgq.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.chenlongwang.top/Article/details/gtamchvkje.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.jinghuilouyu.cn/Article/details/gtxqwxxtng.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.nanxinkj.top/Article/details/gtuzslxwjq.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.jinyuanbaomall.cn/Article/details/gtghwjfvix.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.pycfn.com/Article/details/gthhoqrhie.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.shuidangran.top/Article/details/gtojuncrth.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.ybcxt.top/Article/details/gtrxyoznlo.html

[N10] 链表节点定义
来源：http://dali.snrcjt.cn/Article/details/gtixrotraz.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.feifeiyinyue.top/Article/details/gtrbgszgts.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.ybcxt.top/Article/details/gtqlfsmepy.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.daria6918.cn/Article/details/gtvwgbipiu.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.nanxinkj.top/Article/details/gtndrnnomb.html

Java: class Node { int v; Node next; }
来源：http://dali.yonumen.top/Article/details/gtcucenvrn.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.yonumen.top/Article/details/gtcxcgakvs.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.cucudq.cn/Article/details/gtxmvxmusm.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.smart0.xyz/Article/details/gtqbcdjeew.html

[N11] 二叉树中序遍历
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqpwoheps.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.sufxvd.cn/Article/details/gtjlsrudbe.html

PHP:  // 手写递归函数
来源：http://dali.smart0.xyz/Article/details/gtvbwpzglh.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.cdnleiting.top/Article/details/gtrlkdrncf.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.shuidangran.top/Article/details/gtjwdcsqds.html

Java: // 手写递归
来源：http://dali.tanke756.top/Article/details/gtfeztsbkl.html

Go:   // 手写递归
来源：http://dali.yj20258.top/Article/details/gtpzeagwps.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.cashguo.top/Article/details/gtskoxtzly.html

C#:   // 手写递归
来源：http://dali.pengpengdd.cyou/Article/details/gtussuyjkm.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.xylfe.cn/Article/details/gtmupkxbjx.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.gzhubu.top/Article/details/gtqrufabzb.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.aibaodan.cn/Article/details/gtjsxbhbie.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgujmaujz.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.hywenlv.cn/Article/details/gtmmlvourt.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.wangshuangyany.cn/Article/details/gtckseiuff.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhiwuduotai.top/Article/details/gtypsuzorn.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.gotoacloud.top/Article/details/gtkcfqmiqu.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.andypj.xyz/Article/details/gtujolwgda.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtstrlamhk.html

O. 并发与异步
来源：http://dali.tianlin.xyz/Article/details/gthlfijbwn.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtxmvznddr.html

[O01] 启动一个线程
来源：http://dali.hnqzz.top/Article/details/gtosomougv.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.cdnleiting.top/Article/details/gthlzpayan.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.gotoacloud.top/Article/details/gtejsjpypk.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.ybcxt.top/Article/details/gttuyvtuob.html

TS:   // 同 JS
来源：http://dali.shanyushiyangtech.top/Article/details/gtvohdwaua.html

Java: new Thread(() -> f()).start()
来源：http://dali.fzhhl.top/Article/details/gtunplhehc.html

Go:   go f()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxyptdxfu.html

Ruby: Thread.new { f }
来源：http://dali.yonumen.top/Article/details/gtnkwnoxzg.html

C#:   Task.Run(() => F());
来源：http://dali.jianghu66.top/Article/details/gtxvhylbga.html

[O02] 使用线程池
来源：http://dali.hfpthk.cn/Article/details/gttxecxffd.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.ppjwa.cn/Article/details/gtwtpxtmrl.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.yonumen.top/Article/details/gtwgyetbtz.html

JS:   // worker_threads 线程池
来源：http://dali.svipenyu.cn/Article/details/gtoubfjdof.html

TS:   // worker_threads 线程池
来源：http://dali.yuanzhike.top/Article/details/gtbfozmuly.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.fengsongda.top/Article/details/gtorqkgwqt.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.chenzaomai.com/Article/details/gtzxrvletg.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.jyoumei.cn/Article/details/gtgrhhduat.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.kuanghao11.cn/Article/details/gtsplvrrzx.html

[O03] 加锁保护共享数据
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdusrfpzn.html

Py:   with lock: shared += 1
来源：http://dali.gaohongyu789.top/Article/details/gtxnyrygsp.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.jqgfzy.top/Article/details/gtqayytvsl.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvwfyxxxm.html

TS:   // 同 JS
来源：http://dali.dianchejie.cn/Article/details/gttbrybtlj.html

Java: synchronized (this) { shared++; }
来源：http://dali.xziqi.cn/Article/details/gtvwysuibv.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.havefunace.top/Article/details/gtdiuojtck.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.yanxiufei.cn/Article/details/gtzcdjuwpu.html

C#:   lock (gate) { shared++; }
来源：http://dali.sufxvd.cn/Article/details/gtvvybfkpb.html

[O04] 定义异步函数并等待
来源：http://dali.hongshengwenyu.top/Article/details/gtzlraqvbk.html

Py:   async def f():⏎    await g()
来源：http://dali.wangshuangyany.cn/Article/details/gtxkbedtqw.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.tanke756.top/Article/details/gtqmzerjjg.html

JS:   async function f() { await g(); }
来源：http://dali.fzhhl.top/Article/details/gtlwnqjpab.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.jinqigufen.top/Article/details/gtzaaxpsxm.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.daxiang520.top/Article/details/gthdtsecet.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.yangfankeji.com/Article/details/gtmjdyyojn.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.snrcjt.cn/Article/details/gtjifzarpv.html

C#:   async Task F() { await G(); }
来源：http://dali.chenjidiqi.icu/Article/details/gtoisrakmg.html

[O05] 并发执行并等待全部完成
来源：http://dali.jlsjyb.cn/Article/details/gtmkmvjnlx.html

Py:   asyncio.gather(*tasks)
来源：http://dali.sufxvd.cn/Article/details/gtogeuqato.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.iojbl.cn/Article/details/gtpkhesqat.html

JS:   await Promise.all(tasks)
来源：http://dali.dashuyun.cn/Article/details/gtxhoeoaxx.html

TS:   await Promise.all(tasks)
来源：http://dali.guowangkeji.top/Article/details/gtlnapxyed.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkymwucek.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.vqdsnc.cn/Article/details/gtufeqzxgd.html

Ruby: threads.map(&:join)
来源：http://dali.ivvv.top/Article/details/gtjriujeim.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.svipenyu.cn/Article/details/gtjlaxizot.html

[O06] 使用进程池
来源：http://dali.dianchejie.cn/Article/details/gtvnjaiyfa.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.sysykeji.top/Article/details/gtezsqsofh.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhengqikj.top/Article/details/gtjyqzfurj.html

JS:   // child_process / cluster 模块
来源：http://dali.dianchejie.cn/Article/details/gtbjhedjwb.html

TS:   // child_process / cluster 模块
来源：http://dali.pengpengdd.cyou/Article/details/gtgpwpphwb.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.hammf.cn/Article/details/gtbxziqhel.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gtvytkgpbu.html

Ruby: // fork 块
来源：http://dali.dashuyun.cn/Article/details/gtdzdvuzvg.html

C#:   Parallel.For
来源：http://dali.nwbrower.top/Article/details/gtcckyqtyt.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtlvlhgtan.html

P. 常用工具函数
来源：http://dali.smart0.xyz/Article/details/gtnnpmpgfd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtcjaqbbdx.html

[P01] 生成 UUID
来源：http://dali.cashguo.top/Article/details/gttdkxmvng.html

Py:   str(uuid.uuid4())
来源：http://dali.gotoacloud.top/Article/details/gthuqzgavu.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.havefunace.top/Article/details/gtxwwtcpgk.html

JS:   crypto.randomUUID()
来源：http://dali.shzxlz.cn/Article/details/gtpacobzbq.html

TS:   crypto.randomUUID()
来源：http://dali.gotoacloud.top/Article/details/gtyvtpzeuo.html

Java: UUID.randomUUID().toString()
来源：http://dali.yj202588.top/Article/details/gtdnzwoqvd.html

Go:   // 用 github.com/google/uuid
来源：http://dali.0kj1m.cn/Article/details/gtbbctqqyy.html

Ruby: SecureRandom.uuid
来源：http://dali.cucudq.cn/Article/details/gtzhfkyexs.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.chenlongwang.top/Article/details/gtnwzkgcww.html

[P02] MD5 / SHA256 摘要
来源：http://dali.sysykeji.top/Article/details/gtuzekdyhw.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.vqdsnc.cn/Article/details/gtgmmxzscb.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.fengsongda.top/Article/details/gtycyzdkxe.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.aizwys.cn/Article/details/gtngimbbhi.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.cashguo.top/Article/details/gtyaeqeits.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.chenzaomai.com/Article/details/gtlvznahau.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.jianghu66.top/Article/details/gtlkjyutsj.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.yongpay.top/Article/details/gtriphkybd.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.yuxming.cn/Article/details/gtrdwwwvtx.html

[P03] 生成短随机字符串
来源：http://dali.zhaomingkeji.xyz/Article/details/gtocsnzsqy.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.havefunace.top/Article/details/gthqlohoxu.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.cheryme.top/Article/details/gtobculnby.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.birdmap.top/Article/details/gtoizbmqmo.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.cheryme.top/Article/details/gtpocenign.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.cdnleiting.top/Article/details/gtcqeiiiwt.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.bjfxy.top/Article/details/gtmmvagyka.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.hfpthk.cn/Article/details/gttsydmfvw.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhoulong.xyz/Article/details/gtvkwphguu.html

[P04] 求长度
来源：http://dali.jiagoushi.top/Article/details/gtwzgzjzpp.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.hfpthk.cn/Article/details/gtaandofrk.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhongyouzk.top/Article/details/gtzdtajyte.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.0kj1m.cn/Article/details/gtwxcotuoa.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.chenjidiqi.icu/Article/details/gtnalefepd.html

Java: list.size();  map.size();  s.length()
来源：http://dali.yonumen.top/Article/details/gtbzglsffy.html

Go:   len(arr);  len(m)
来源：http://dali.andypj.xyz/Article/details/gtrgoahobd.html

Ruby: x.length;  x.size
来源：http://dali.mhx1999.top/Article/details/gtqwftnqat.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.pycfn.com/Article/details/gtijaehonl.html

[P05] 判断两个对象内容是否相等
来源：http://dali.ehwqpu.com/Article/details/gtggmdtugy.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.zycfv.cn/Article/details/gtqmtfpzix.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.ppjwa.cn/Article/details/gtvjbxwaop.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.guannengcc.top/Article/details/gtjtdhoesx.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.cdnleiting.top/Article/details/gtniupxddp.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.mhx1999.top/Article/details/gtxnchcmah.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.feifeiyinyue.top/Article/details/gtpnkvbfms.html

Ruby: a == b
来源：http://dali.wangshuangyany.cn/Article/details/gteamigoju.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.hfpthk.cn/Article/details/gtthzephhc.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.gaohongyu789.top/Article/details/gtealqqiwk.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.316326.xyz/Article/details/gtkrtqcllq.html

PHP:  if (empty($x)) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtcafbtwos.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.pycfn.com/Article/details/gthhqpnpam.html

TS:   if (x == null) {}
来源：http://dali.nanxinkj.top/Article/details/gtihoqirww.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.yonumen.top/Article/details/gtwljjbcmk.html

Go:   if x == nil {}
来源：http://dali.jyoumei.cn/Article/details/gtofyijegj.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.yvedp.cn/Article/details/gtdsrnaitg.html

C#:   if (x is null) {}
来源：http://dali.mhx1999.top/Article/details/gtgheoeufi.html

[P07] 防抖与节流
来源：http://dali.ehwqpu.com/Article/details/gtzxparctd.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.jiagoushi.top/Article/details/gtolqaupfd.html

PHP:  // 手写时间戳比较
来源：http://dali.fengsongda.top/Article/details/gtqxdoorva.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.shangyingyoupin.top/Article/details/gtptvkbnap.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zhiwuduotai.top/Article/details/gturlmhjed.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.mhx1999.top/Article/details/gtoddctmei.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.316326.xyz/Article/details/gtprmxggqb.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhengqikj.top/Article/details/gtpztcdurk.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.gotoacloud.top/Article/details/gtiegmeseq.html

[P08] 处理浮点精度问题
来源：http://dali.bjfxy.top/Article/details/gtuheopfod.html


<!-- 参考信息 -->