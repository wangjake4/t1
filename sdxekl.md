代发 wailian999

JS:   process.argv.slice(2)
来源：http://dali.yj202588.top/Article/details/gt2tfcmizdy.html

TS:   process.argv.slice(2)
来源：http://dali.ybcxt.top/Article/details/gt2vfalyxpp.html

Java: args 数组（main 方法参数）
来源：http://dali.feifeiyinyue.top/Article/details/gt2yohqqrbh.html

Go:   os.Args[1:]
来源：http://dali.jianghu66.top/Article/details/gt2ekvwneis.html

Ruby: ARGV
来源：http://dali.chenzaomai.com/Article/details/gt2zjjzkfkl.html

C#:   args 数组（Main 方法参数）
来源：http://dali.jianghu66.top/Article/details/gt2jawlmrub.html

[M02] 读取环境变量
来源：http://dali.jqgfzy.top/Article/details/gt2fqufudmw.html

Py:   os.environ.get("HOME")
来源：http://dali.quarkkingdee.top/Article/details/gt2oiukyrol.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhixingplan.top/Article/details/gt2jjqxgvlo.html

JS:   process.env.HOME
来源：http://dali.yongpay.top/Article/details/gt2milypumc.html

TS:   process.env.HOME
来源：http://dali.sufxvd.cn/Article/details/gt2mtqzcmxh.html

Java: System.getenv("HOME")
来源：http://dali.daria6918.cn/Article/details/gt2knoqgwul.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.shzxlz.cn/Article/details/gt2pobmuafn.html

Ruby: ENV["HOME"]
来源：http://dali.havefunace.top/Article/details/gt2htydmqni.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.jiagoushi.top/Article/details/gt2lqpcqvdx.html

[M03] 执行外部命令
来源：http://dali.xinyue.icu/Article/details/gt2jlknrumr.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.bjfxy.top/Article/details/gt2ldradfup.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.jiagoushi.top/Article/details/gt2sqicfcyj.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.316326.xyz/Article/details/gt2yobrafro.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.jyoumei.cn/Article/details/gt2mkokjnzd.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qzdvzsts.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.cashguo.top/Article/details/gt2ntdaaoah.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.jianghu66.top/Article/details/gt2xqbrapmx.html

C#:   Process.Start("ls", "-l");
来源：http://dali.c1oappe.top/Article/details/gt2jecqmvut.html

[M04] 获取当前工作目录
来源：http://dali.chenjidiqi.icu/Article/details/gt2rihqbbjt.html

Py:   os.getcwd()
来源：http://dali.kuanghao11.cn/Article/details/gt2gmmgpnux.html

PHP:  getcwd();
来源：http://dali.redwolf501.top/Article/details/gt2gpvufnit.html

JS:   process.cwd()
来源：http://dali.chenlongwang.top/Article/details/gt2fgtcozqw.html

TS:   process.cwd()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qzsxsygr.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.shzxlz.cn/Article/details/gt2cayjcnjp.html

Go:   os.Getwd()
来源：http://dali.sufxvd.cn/Article/details/gt2ynlwatdw.html

Ruby: Dir.pwd
来源：http://dali.havefunace.top/Article/details/gt2nxtdpred.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.hongshengwenyu.top/Article/details/gt2zcluvwwd.html

[M05] 设置退出码
来源：http://dali.shuidangran.top/Article/details/gt2prigibzt.html

Py:   sys.exit(1)
来源：http://dali.ydzc1.top/Article/details/gt2lmavublp.html

PHP:  exit(1);
来源：http://dali.yj20258888.top/Article/details/gt2tsbophci.html

JS:   process.exit(1)
来源：http://dali.tian-w.cn/Article/details/gt2amhydxpp.html

TS:   process.exit(1)
来源：http://dali.ppjwa.cn/Article/details/gt2qbehwtok.html

Java: System.exit(1)
来源：http://dali.shangyingyoupin.top/Article/details/gt2vypeeubn.html

Go:   os.Exit(1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pqwnzain.html

Ruby: exit 1
来源：http://dali.bjfxy.top/Article/details/gt2nowyeliz.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.xylfe.cn/Article/details/gt2fqflqwdb.html

[M06] 向标准错误输出
来源：http://dali.shzxlz.cn/Article/details/gt2guxjkwzm.html

Py:   print("err", file=sys.stderr)
来源：http://dali.yj20258.top/Article/details/gt2bjmjjbav.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.ybcxt.top/Article/details/gt2qrxokgqc.html

JS:   console.error("err")
来源：http://dali.hywenlv.cn/Article/details/gt2bpshoscs.html

TS:   console.error("err")
来源：http://dali.havefunace.top/Article/details/gt2vamxmauj.html

Java: System.err.println("err")
来源：http://dali.kuanghao11.cn/Article/details/gt2pdxzvinx.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.nanxuanxn.top/Article/details/gt2plgcavln.html

Ruby: warn "err"
来源：http://dali.cucudq.cn/Article/details/gt2sqtopthg.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.hywenlv.cn/Article/details/gt2kbynwohw.html

[M07] 判断是否为主入口
来源：http://dali.haohaochexian.top/Article/details/gt2iodiazqo.html

Py:   if __name__ == "__main__":
来源：http://dali.gaohongyu789.top/Article/details/gt2gugoobcm.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.cucudq.cn/Article/details/gt2fsotpzug.html

JS:   require.main === module
来源：http://dali.smart0.xyz/Article/details/gt2rwlputcq.html

TS:   require.main === module
来源：http://dali.andypj.xyz/Article/details/gt2pcusqoks.html

Java: public static void main(String[] args)
来源：http://dali.chenjidiqi.icu/Article/details/gt2hrjgilqm.html

Go:   func main()
来源：http://dali.yueranfly.top/Article/details/gt2vzawikva.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.cdnleiting.top/Article/details/gt2uzxjkkhz.html

C#:   static void Main(string[] args)
来源：http://dali.yanxiufei.cn/Article/details/gt2fxhabcvy.html

[M08] 获取系统与运行时信息
来源：http://dali.cdnleiting.top/Article/details/gt2prknbmae.html

Py:   platform.system();  platform.python_version()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xchlubll.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.wangdashe.top/Article/details/gt2phyxvvro.html

JS:   process.platform;  process.version
来源：http://dali.smart0.xyz/Article/details/gt2hqsargsb.html

TS:   process.platform;  process.version
来源：http://dali.jiagoushi.top/Article/details/gt2fhcwyncf.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.gzhubu.top/Article/details/gt2pqddtzuu.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.hfpthk.cn/Article/details/gt2hkylwxrs.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.sufxvd.cn/Article/details/gt2zftjcjzi.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.316326.xyz/Article/details/gt2mswwrepo.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gt2uiqopfjs.html

N. 数据结构与算法
来源：http://dali.sxryk.cn/Article/details/gt2rzdzzeup.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gt2tfkfpihh.html

[N01] 二分查找（有序数组）
来源：http://dali.ybcxt.top/Article/details/gt2brbcklmd.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dypzdwii.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.svipenyu.cn/Article/details/gt2teaxyqci.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.sufxvd.cn/Article/details/gt2ilhstdnt.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jianghu66.top/Article/details/gt2aisylswo.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.chenzaomai.com/Article/details/gt2atyxtvxx.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.yj202588.top/Article/details/gt2dwlxqlqd.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.aizwys.cn/Article/details/gt2vrislqtu.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.quarkkingdee.top/Article/details/gt2aokmcdfr.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.yj20258.top/Article/details/gt2icjrlyvg.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.tanke756.top/Article/details/gt2jcoifzmg.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.hfpthk.cn/Article/details/gt2tvagadph.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.sweek.top/Article/details/gt2goxlzmmo.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.nwbrower.top/Article/details/gt2eiozebon.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.sysykeji.top/Article/details/gt2fgupicgn.html

Go:   slices.Sort(arr)
来源：http://dali.yueranfly.top/Article/details/gt2valifanj.html

Ruby: arr.sort
来源：http://dali.zhoulong.xyz/Article/details/gt2njqzocec.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.fengsongda.top/Article/details/gt2cbbtenqs.html

[N03] 快速排序（分治示例）
来源：http://dali.yj202588.top/Article/details/gt2zqpyznbo.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.meibo888.top/Article/details/gt2ydvbqxjg.html

PHP:  // 递归实现，或用 usort
来源：http://dali.sufxvd.cn/Article/details/gt2xnjnuilb.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yuanzhike.top/Article/details/gt2bawjjhnk.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.daxiang520.top/Article/details/gt2fdllnzlg.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2wthqmlso.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.yj202588.top/Article/details/gt2qyijvwze.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.jiagoushi.top/Article/details/gt2xwizuejj.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.yvedp.cn/Article/details/gt2pdfqpllh.html

[N04] 斐波那契数列
来源：http://dali.xziqi.cn/Article/details/gt2fibizxjc.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.xylfe.cn/Article/details/gt2okxqvdof.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.jianghu66.top/Article/details/gt2ciigttrq.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.iojbl.cn/Article/details/gt2fqtfomid.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.andypj.xyz/Article/details/gt2gophgprh.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.cucudq.cn/Article/details/gt2plrmshdv.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.316326.xyz/Article/details/gt2nretsxda.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.xziqi.cn/Article/details/gt2agdwetvz.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.jyoumei.cn/Article/details/gt2xiyudjwn.html

[N05] 最大公约数
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2btrrmsve.html

Py:   math.gcd(a, b)
来源：http://dali.aizwys.cn/Article/details/gt2idszszmv.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.ivvv.top/Article/details/gt2orlxpfwe.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yangfankeji.com/Article/details/gt2xivqlbaw.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.ydzc1.top/Article/details/gt2qmoqrvqf.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.hammf.cn/Article/details/gt2dyjojbid.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.ydzc1.top/Article/details/gt2tglgcroz.html

Ruby: a.gcd(b)
来源：http://dali.jqgfzy.top/Article/details/gt2cxjylshn.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.jinqigfzy.top/Article/details/gt2nnnayszh.html

[N06] 判断回文字符串
来源：http://dali.jlsjyb.cn/Article/details/gt2nzjhxhoh.html

Py:   s == s[::-1]
来源：http://dali.smart0.xyz/Article/details/gt2uonsnhiq.html

PHP:  $s === strrev($s);
来源：http://dali.smart0.xyz/Article/details/gt2gefsiyvu.html

JS:   s === [...s].reverse().join("")
来源：http://dali.cashguo.top/Article/details/gt2vaaphqid.html

TS:   s === [...s].reverse().join("")
来源：http://dali.cucudq.cn/Article/details/gt2qcsybtpa.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.hfpthk.cn/Article/details/gt2pvtuzkch.html

Go:   // 双指针从两端比较
来源：http://dali.aizwys.cn/Article/details/gt2wyshlnsw.html

Ruby: s == s.reverse
来源：http://dali.yj20258888.top/Article/details/gt2qkfykdze.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.birdmap.top/Article/details/gt2hxwpcrxa.html

[N07] 两数之和（返回下标）
来源：http://dali.svipenyu.cn/Article/details/gt2ijvmbgun.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.nanxuanxn.top/Article/details/gt2pjmkzrnl.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2svsdsvrp.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2avltqzal.html

TS:   // 手写 Map<string, number>
来源：http://dali.guannengcc.top/Article/details/gt2hudzvxtt.html

Java: // 手写 HashMap
来源：http://dali.pycfn.com/Article/details/gt2tismzrzp.html

Go:   // 手写 map[int]int
来源：http://dali.shzxlz.cn/Article/details/gt2unagydbu.html

Ruby: // 手写 Hash
来源：http://dali.zhoulong.xyz/Article/details/gt2dbkfkvrb.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.bjfxy.top/Article/details/gt2hgmbyosm.html

[N08] 生成全排列
来源：http://dali.316326.xyz/Article/details/gt2iernqkex.html

Py:   itertools.permutations(arr)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pbupvbsc.html

PHP:  // 手写递归交换
来源：http://dali.redwolf501.top/Article/details/gt2sbogdtdh.html

JS:   // 手写回溯递归
来源：http://dali.chenlongwang.top/Article/details/gt2afekctvo.html

TS:   // 手写回溯递归
来源：http://dali.quarkkingdee.top/Article/details/gt2aonoaaug.html

Java: // 手写回溯递归
来源：http://dali.ivvv.top/Article/details/gt2ixnrothp.html

Go:   // 手写回溯递归
来源：http://dali.c1oappe.top/Article/details/gt2cpwehkzn.html

Ruby: arr.permutation.to_a
来源：http://dali.hammf.cn/Article/details/gt2kgpyeswy.html

C#:   // 手写回溯递归
来源：http://dali.redwolf501.top/Article/details/gt2peqkhkrl.html

[N09] 栈与队列
来源：http://dali.daxiang520.top/Article/details/gt2xcgigldh.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.yangfankeji.com/Article/details/gt2xjhogcqd.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.jiagoushi.top/Article/details/gt2tdoncghg.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.daria6918.cn/Article/details/gt2fuswnuni.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.andypj.xyz/Article/details/gt2clwsxaru.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.jinqigfzy.top/Article/details/gt2yhhgmduh.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.cheryme.top/Article/details/gt2vrzysyir.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.cheryme.top/Article/details/gt2ncikuieq.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.daxiang520.top/Article/details/gt2emcscznn.html

[N10] 链表节点定义
来源：http://dali.haohaochexian.top/Article/details/gt2dnbkkylp.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.xziqi.cn/Article/details/gt2mvtduwfs.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.hysaishi.cn/Article/details/gt2tgeqgaws.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.sweek.top/Article/details/gt2tszwofjc.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.svipenyu.cn/Article/details/gt2qmecdumw.html

Java: class Node { int v; Node next; }
来源：http://dali.cucudq.cn/Article/details/gt2hcogbptx.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.havefunace.top/Article/details/gt2thnponwy.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.gaohongyu789.top/Article/details/gt2qbwpjyaj.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhixingplan.top/Article/details/gt2rmwtizsk.html

[N11] 二叉树中序遍历
来源：http://dali.meibo888.top/Article/details/gt2orszdzyq.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhixingplan.top/Article/details/gt2uzmvusyl.html

PHP:  // 手写递归函数
来源：http://dali.jqgufenzy.top/Article/details/gt2qbbsznys.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.quarkkingdee.top/Article/details/gt2hbmvzyjn.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jqgufenzy.top/Article/details/gt2jroixyyg.html

Java: // 手写递归
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2usngzdbo.html

Go:   // 手写递归
来源：http://dali.yueranfly.top/Article/details/gt2uvagarhw.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.hnxiangtu.top/Article/details/gt2isjskpgm.html

C#:   // 手写递归
来源：http://dali.chenlongwang.top/Article/details/gt2rwkdhlhd.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.pycfn.com/Article/details/gt2pjvlvbcu.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.yj202588.top/Article/details/gt2vgxltcys.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jovpxfxl.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jianghu66.top/Article/details/gt2mlqmozuh.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.meibo888.top/Article/details/gt2cwtvvcsx.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2tamlswec.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.yj20258.top/Article/details/gt2noniyjgq.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.wangdashe.top/Article/details/gt2snoslaof.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhixingplan.top/Article/details/gt2adgybcmc.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gt2neivexja.html

O. 并发与异步
来源：http://dali.sweek.top/Article/details/gt2jegoccfr.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gt2fydpwpos.html

[O01] 启动一个线程
来源：http://dali.gzhubu.top/Article/details/gt2evdpdyvc.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.sysykeji.top/Article/details/gt2tjndcqsu.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.cashguo.top/Article/details/gt2bvauogiy.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.jinqigfzy.top/Article/details/gt2yiongtpx.html

TS:   // 同 JS
来源：http://dali.chenlongwang.top/Article/details/gt2qckctlxh.html

Java: new Thread(() -> f()).start()
来源：http://dali.yongpay.top/Article/details/gt2ywqllgkm.html

Go:   go f()
来源：http://dali.dashuyun.cn/Article/details/gt2ugspfvyj.html

Ruby: Thread.new { f }
来源：http://dali.jqgufenzy.top/Article/details/gt2yvexgafj.html

C#:   Task.Run(() => F());
来源：http://dali.ehwqpu.com/Article/details/gt2jsoqmbux.html

[O02] 使用线程池
来源：http://dali.dashuyun.cn/Article/details/gt2tkueukjw.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.cucudq.cn/Article/details/gt2gzhljqut.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.jyoumei.cn/Article/details/gt2cgkleqfi.html

JS:   // worker_threads 线程池
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nrtiscdw.html

TS:   // worker_threads 线程池
来源：http://dali.ybcxt.top/Article/details/gt2lshvykyh.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.jianghu66.top/Article/details/gt2qfldwpqo.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zwblxtnr.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.sxryk.cn/Article/details/gt2qrceeuoz.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.vqdsnc.cn/Article/details/gt2tllxpemz.html

[O03] 加锁保护共享数据
来源：http://dali.9152youxi.cn/Article/details/gt2olauhnus.html

Py:   with lock: shared += 1
来源：http://dali.meibo888.top/Article/details/gt2tazxkzzi.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.gzhubu.top/Article/details/gt2hckqrcca.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.wangshuangyany.cn/Article/details/gt2kpzysobb.html

TS:   // 同 JS
来源：http://dali.aibaodan.cn/Article/details/gt2jdqzqwpg.html

Java: synchronized (this) { shared++; }
来源：http://dali.jiagoushi.top/Article/details/gt2irhubodd.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.hammf.cn/Article/details/gt2kwmzazhv.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.sweek.top/Article/details/gt2dmsqxzyo.html

C#:   lock (gate) { shared++; }
来源：http://dali.dashuyun.cn/Article/details/gt2nnocgtdu.html

[O04] 定义异步函数并等待
来源：http://dali.yuxming.cn/Article/details/gt2ceiijsoa.html

Py:   async def f():⏎    await g()
来源：http://dali.zhoulong.xyz/Article/details/gt2okzictip.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.pycfn.com/Article/details/gt2wbwbkulz.html

JS:   async function f() { await g(); }
来源：http://dali.chenjidiqi.icu/Article/details/gt2yvhhwdug.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vpqdfeks.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.kuanghao11.cn/Article/details/gt2levhzukh.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.daxiang520.top/Article/details/gt2dplelcaf.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.jinqigufen.top/Article/details/gt2tiuoidbz.html

C#:   async Task F() { await G(); }
来源：http://dali.svipenyu.cn/Article/details/gt2jvjljqzw.html

[O05] 并发执行并等待全部完成
来源：http://dali.ybcxt.top/Article/details/gt2tcedqxww.html

Py:   asyncio.gather(*tasks)
来源：http://dali.svipenyu.cn/Article/details/gt2ttxtfwob.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.dianchejie.cn/Article/details/gt2iybhqnts.html

JS:   await Promise.all(tasks)
来源：http://dali.sweek.top/Article/details/gt2ddehsdrd.html

TS:   await Promise.all(tasks)
来源：http://dali.yanxiufei.cn/Article/details/gt2ridnlafg.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.jinqigfzy.top/Article/details/gt2liooptcb.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.wangdashe.top/Article/details/gt2aqnhhwmg.html

Ruby: threads.map(&:join)
来源：http://dali.meibo888.top/Article/details/gt2gtvcjhwp.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.shuidangran.top/Article/details/gt2heiqhywq.html

[O06] 使用进程池
来源：http://dali.cdnleiting.top/Article/details/gt2sxqkbusv.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.pycfn.com/Article/details/gt2kccqyuko.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.jqgfzy.top/Article/details/gt2afeznzrc.html

JS:   // child_process / cluster 模块
来源：http://dali.shanyushiyangtech.top/Article/details/gt2devtzpqa.html

TS:   // child_process / cluster 模块
来源：http://dali.shuidangran.top/Article/details/gt2ttehayog.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zdqjudy.top/Article/details/gt2dsspupyp.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.gzhubu.top/Article/details/gt2skdxyimv.html

Ruby: // fork 块
来源：http://dali.xuetiantiany.cn/Article/details/gt2ylqpdcwq.html

C#:   Parallel.For
来源：http://dali.xuetiantiany.cn/Article/details/gt2vneyjsou.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gt2tjcfekbm.html

P. 常用工具函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kyftjrdu.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gt2pxpwvbuu.html

[P01] 生成 UUID
来源：http://dali.sufxvd.cn/Article/details/gt2xmblibai.html

Py:   str(uuid.uuid4())
来源：http://dali.xziqi.cn/Article/details/gt2obrzwyhf.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhixingplan.top/Article/details/gt2mibxlome.html

JS:   crypto.randomUUID()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2sjwfvile.html

TS:   crypto.randomUUID()
来源：http://dali.ppjwa.cn/Article/details/gt2zqayovdr.html

Java: UUID.randomUUID().toString()
来源：http://dali.0kj1m.cn/Article/details/gt2yjrmdsyc.html

Go:   // 用 github.com/google/uuid
来源：http://dali.tianlin.xyz/Article/details/gt2wejgwhxz.html

Ruby: SecureRandom.uuid
来源：http://dali.guannengcc.top/Article/details/gt2upbzlzjw.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.gaohongyu789.top/Article/details/gt2enajkvtc.html

[P02] MD5 / SHA256 摘要
来源：http://dali.ybcxt.top/Article/details/gt2oglnpijk.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.kuanghao11.cn/Article/details/gt2czbhbfgr.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.gzhubu.top/Article/details/gt2zphakeli.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.pycfn.com/Article/details/gt2hbyvhueu.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.nanxuanxn.top/Article/details/gt2ctdnobpv.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jatpqdhl.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.tanke756.top/Article/details/gt2mvlgrozz.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.hongshengwenyu.top/Article/details/gt2rtwcdyqp.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.nwbrower.top/Article/details/gt2eosnfoqa.html

[P03] 生成短随机字符串
来源：http://dali.feifeiyinyue.top/Article/details/gt2sogfcjcw.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhixingplan.top/Article/details/gt2mqbenehj.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.jyoumei.cn/Article/details/gt2wpjrbehw.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.daria6918.cn/Article/details/gt2vzvttoax.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.guowangkeji.top/Article/details/gt2ztdkngfq.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.vqdsnc.cn/Article/details/gt2hioepjrw.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.tianlin.xyz/Article/details/gt2gcunwlcg.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.hywenlv.cn/Article/details/gt2lpnmerif.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.xylfe.cn/Article/details/gt2uwlvvgxi.html

[P04] 求长度
来源：http://dali.shangyingyoupin.top/Article/details/gt2bdpisxfx.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.xuanzx.com/Article/details/gt2ziciqnup.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.gzhubu.top/Article/details/gt2mgobboiy.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mlomrygb.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.dashuyun.cn/Article/details/gt2hevooxnm.html

Java: list.size();  map.size();  s.length()
来源：http://dali.yonumen.top/Article/details/gt2ktccmnda.html

Go:   len(arr);  len(m)
来源：http://dali.chenzaomai.com/Article/details/gt2etyepjeb.html

Ruby: x.length;  x.size
来源：http://dali.dashuyun.cn/Article/details/gt2glrcxtwo.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.yj202588.top/Article/details/gt2ojycjjaw.html

[P05] 判断两个对象内容是否相等
来源：http://dali.feifeiyinyue.top/Article/details/gt2txcpldlf.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.gaohongyu789.top/Article/details/gt2cpocjvnd.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.zhoulong.xyz/Article/details/gt2kdlogzai.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.cashguo.top/Article/details/gt2sugelitl.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.sweek.top/Article/details/gt2hwemadyk.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.xuanzx.com/Article/details/gt2yegniiiz.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.xinyue.icu/Article/details/gt2kcpqvaoe.html

Ruby: a == b
来源：http://dali.cashguo.top/Article/details/gt2vsfbonnc.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.hnqzz.top/Article/details/gt2xppumefn.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.wangdashe.top/Article/details/gt2ewxuoxsg.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.daria6918.cn/Article/details/gt2apmfsxhl.html

PHP:  if (empty($x)) {}
来源：http://dali.yj202588.top/Article/details/gt2fcfcklkv.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.aizwys.cn/Article/details/gt2tzvnetsj.html

TS:   if (x == null) {}
来源：http://dali.cheryme.top/Article/details/gt2tyqypkgv.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.xinyue.icu/Article/details/gt2sleawrgv.html

Go:   if x == nil {}
来源：http://dali.yvedp.cn/Article/details/gt2bwdfltsu.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.fzhhl.top/Article/details/gt2ydytkcyk.html

C#:   if (x is null) {}
来源：http://dali.vqdsnc.cn/Article/details/gt2jszmpqgo.html

[P07] 防抖与节流
来源：http://dali.guowangkeji.top/Article/details/gt2enyqojsu.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.gzhubu.top/Article/details/gt2epbvwxox.html

PHP:  // 手写时间戳比较
来源：http://dali.gogol.net.cn/Article/details/gt2ulddfzja.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jqgfzy.top/Article/details/gt2whewctzb.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hammf.cn/Article/details/gt2evtczwrq.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wjdrnito.html


<!-- 参考信息 -->