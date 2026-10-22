代发 wailian999

================================================================================
来源：http://dali.xinyue.icu/Article/details/gt2xuwpnhko.html

[M01] 读取命令行参数
来源：http://dali.fengsongda.top/Article/details/gt2mvdrahyn.html

Py:   sys.argv[1:]
来源：http://dali.yueranfly.top/Article/details/gt2izqwvyvs.html

PHP:  $argv;  $argc;
来源：http://dali.snrcjt.cn/Article/details/gt2zswmhvcm.html

JS:   process.argv.slice(2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tlracguu.html

TS:   process.argv.slice(2)
来源：http://dali.shuidangran.top/Article/details/gt2wuayndkr.html

Java: args 数组（main 方法参数）
来源：http://dali.ivvv.top/Article/details/gt2vdkxrddg.html

Go:   os.Args[1:]
来源：http://dali.jianghu66.top/Article/details/gt2ucndzcvw.html

Ruby: ARGV
来源：http://dali.haohaochexian.top/Article/details/gt2ywmfxqnv.html

C#:   args 数组（Main 方法参数）
来源：http://dali.shzxlz.cn/Article/details/gt2aaqdsewy.html

[M02] 读取环境变量
来源：http://dali.shangyingyoupin.top/Article/details/gt2omhmqohu.html

Py:   os.environ.get("HOME")
来源：http://dali.bjfxy.top/Article/details/gt2dqpbxnhf.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.yanxiufei.cn/Article/details/gt2jygqohes.html

JS:   process.env.HOME
来源：http://dali.hnxiangtu.top/Article/details/gt2qkicjefv.html

TS:   process.env.HOME
来源：http://dali.jqgufenzy.top/Article/details/gt2veyswgla.html

Java: System.getenv("HOME")
来源：http://dali.yuxming.cn/Article/details/gt2cdwjlhkd.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zycfv.cn/Article/details/gt2hkdtuclk.html

Ruby: ENV["HOME"]
来源：http://dali.shzxlz.cn/Article/details/gt2qpqfwwmu.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.hnxiangtu.top/Article/details/gt2rpiwuqvk.html

[M03] 执行外部命令
来源：http://dali.guannengcc.top/Article/details/gt2fpaifaer.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wezgvbqu.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.pengpengdd.cyou/Article/details/gt2lqwzgwlj.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.jlsjyb.cn/Article/details/gt2duxrkpps.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mhgmvuvk.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gt2mwzhhvxh.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.daria6918.cn/Article/details/gt2veuoiaxv.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ofmgbdox.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gt2pgxnepgo.html

[M04] 获取当前工作目录
来源：http://dali.jianghu66.top/Article/details/gt2sbgwxlbq.html

Py:   os.getcwd()
来源：http://dali.cucudq.cn/Article/details/gt2gwqfmukq.html

PHP:  getcwd();
来源：http://dali.pengpengdd.cyou/Article/details/gt2ujboapas.html

JS:   process.cwd()
来源：http://dali.guannengcc.top/Article/details/gt2atkuqwzz.html

TS:   process.cwd()
来源：http://dali.hysaishi.cn/Article/details/gt2phwivscf.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.wangdashe.top/Article/details/gt2zcexmesg.html

Go:   os.Getwd()
来源：http://dali.jqgfzy.top/Article/details/gt2nbqmcmlk.html

Ruby: Dir.pwd
来源：http://dali.yj202588.top/Article/details/gt2kmfcwerr.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.sufxvd.cn/Article/details/gt2vjyxuboe.html

[M05] 设置退出码
来源：http://dali.gzhubu.top/Article/details/gt2icdxfyva.html

Py:   sys.exit(1)
来源：http://dali.zhixingplan.top/Article/details/gt2wvrocxlr.html

PHP:  exit(1);
来源：http://dali.iojbl.cn/Article/details/gt2nibxuspu.html

JS:   process.exit(1)
来源：http://dali.hysaishi.cn/Article/details/gt2cupcujdp.html

TS:   process.exit(1)
来源：http://dali.cdnleiting.top/Article/details/gt2qghkiiuk.html

Java: System.exit(1)
来源：http://dali.jinqigfzy.top/Article/details/gt2swqlfalu.html

Go:   os.Exit(1)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dknchazp.html

Ruby: exit 1
来源：http://dali.guowangkeji.top/Article/details/gt2tdagofne.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.redwolf501.top/Article/details/gt2lqewflha.html

[M06] 向标准错误输出
来源：http://dali.fzhhl.top/Article/details/gt2gailqpjj.html

Py:   print("err", file=sys.stderr)
来源：http://dali.aibaodan.cn/Article/details/gt2gymvgpdo.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2glfhaswq.html

JS:   console.error("err")
来源：http://dali.9152youxi.cn/Article/details/gt2ielnpirb.html

TS:   console.error("err")
来源：http://dali.yuanzhike.top/Article/details/gt2zboapthl.html

Java: System.err.println("err")
来源：http://dali.hongshengwenyu.top/Article/details/gt2vjxlaaip.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.hfpthk.cn/Article/details/gt2wnujrsdf.html

Ruby: warn "err"
来源：http://dali.zhiwuduotai.top/Article/details/gt2vpuoiplb.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.yj202588.top/Article/details/gt2tadsckra.html

[M07] 判断是否为主入口
来源：http://dali.cheryme.top/Article/details/gt2uhtmgzhw.html

Py:   if __name__ == "__main__":
来源：http://dali.yj20258888.top/Article/details/gt2ryyusuok.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2jontivww.html

JS:   require.main === module
来源：http://dali.guannengcc.top/Article/details/gt2rjissleh.html

TS:   require.main === module
来源：http://dali.nanxinkj.top/Article/details/gt2jocmquqv.html

Java: public static void main(String[] args)
来源：http://dali.gaohongyu789.top/Article/details/gt2gyxletig.html

Go:   func main()
来源：http://dali.cashguo.top/Article/details/gt2ulqkcleg.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.yueranfly.top/Article/details/gt2hwnfuhjp.html

C#:   static void Main(string[] args)
来源：http://dali.zhoulong.xyz/Article/details/gt2skkemiee.html

[M08] 获取系统与运行时信息
来源：http://dali.hywenlv.cn/Article/details/gt2eodsljmx.html

Py:   platform.system();  platform.python_version()
来源：http://dali.guowangkeji.top/Article/details/gt2mincqxts.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.aizwys.cn/Article/details/gt2akegtwid.html

JS:   process.platform;  process.version
来源：http://dali.jyoumei.cn/Article/details/gt2jbisypgk.html

TS:   process.platform;  process.version
来源：http://dali.kuanghao11.cn/Article/details/gt2lqrebmtt.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.guowangkeji.top/Article/details/gt2qhrjkpwt.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhongyouzk.top/Article/details/gt2sqshyflo.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhongyouzk.top/Article/details/gt2etoirxdb.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.redwolf501.top/Article/details/gt2mtwvhvss.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gt2csetqfin.html

N. 数据结构与算法
来源：http://dali.cdnleiting.top/Article/details/gt2qxfmogmv.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gt2gidyxqrs.html

[N01] 二分查找（有序数组）
来源：http://dali.chenlongwang.top/Article/details/gt2fewtwljs.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhoulong.xyz/Article/details/gt2agyybugd.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.hongshengwenyu.top/Article/details/gt2wqsduvsy.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.redwolf501.top/Article/details/gt2brbxmmlv.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.xuanzx.com/Article/details/gt2muwkhrhr.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhengqikj.top/Article/details/gt2kehybidj.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.xuanzx.com/Article/details/gt2ktoqobim.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.hysaishi.cn/Article/details/gt2lazvfzos.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.chenlongwang.top/Article/details/gt2vuxlvcni.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.c1oappe.top/Article/details/gt2tepsxbfw.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.xylfe.cn/Article/details/gt2rhidyxwm.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.jianghu66.top/Article/details/gt2tuzgttcs.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.dashuyun.cn/Article/details/gt2eiwkehlv.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.pengpengdd.cyou/Article/details/gt2lmpapktv.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zdqjudy.top/Article/details/gt2gwswbjix.html

Go:   slices.Sort(arr)
来源：http://dali.kuanghao11.cn/Article/details/gt2mvsvwfyb.html

Ruby: arr.sort
来源：http://dali.9152youxi.cn/Article/details/gt2csthobeo.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhengqikj.top/Article/details/gt2cvfenmhq.html

[N03] 快速排序（分治示例）
来源：http://dali.chenjidiqi.icu/Article/details/gt2jmskcooy.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.xziqi.cn/Article/details/gt2ypkrnlif.html

PHP:  // 递归实现，或用 usort
来源：http://dali.wangdashe.top/Article/details/gt2wieymdvh.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.iojbl.cn/Article/details/gt2xjxazhnf.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.cqqwz.cn/Article/details/gt2brpvdjve.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.jqgufenzy.top/Article/details/gt2txawcpyb.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.xylfe.cn/Article/details/gt2vdifzgjb.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.jinqigufen.top/Article/details/gt2qmagildv.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.xylfe.cn/Article/details/gt2tyzibeer.html

[N04] 斐波那契数列
来源：http://dali.hnxiangtu.top/Article/details/gt2ateqfoag.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.xziqi.cn/Article/details/gt2hoakkmxb.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ekajccru.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.gogol.net.cn/Article/details/gt2mqfjjqnf.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.birdmap.top/Article/details/gt2ghzzdzoh.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.gzhubu.top/Article/details/gt2kedpmzvy.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.yonumen.top/Article/details/gt2wpqxqkhr.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.shuidangran.top/Article/details/gt2rusfgkwh.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.hnxiangtu.top/Article/details/gt2mqnfoeak.html

[N05] 最大公约数
来源：http://dali.guannengcc.top/Article/details/gt2opgjcaqs.html

Py:   math.gcd(a, b)
来源：http://dali.dashuyun.cn/Article/details/gt2ydlpxvcz.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.jqgufenzy.top/Article/details/gt2stvnrfbt.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hammf.cn/Article/details/gt2ifndojmu.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hammf.cn/Article/details/gt2uxmrbzeg.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhongyouzk.top/Article/details/gt2dvmginwv.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2lbsjcweb.html

Ruby: a.gcd(b)
来源：http://dali.zhixingplan.top/Article/details/gt2gybmsesd.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kenirsoj.html

[N06] 判断回文字符串
来源：http://dali.gaohongyu789.top/Article/details/gt2uqfcvugl.html

Py:   s == s[::-1]
来源：http://dali.shangyingyoupin.top/Article/details/gt2pcuougxw.html

PHP:  $s === strrev($s);
来源：http://dali.yuanzhike.top/Article/details/gt2kjooknhh.html

JS:   s === [...s].reverse().join("")
来源：http://dali.yangfankeji.com/Article/details/gt2pcayktts.html

TS:   s === [...s].reverse().join("")
来源：http://dali.c1oappe.top/Article/details/gt2ddyejber.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.nanxinkj.top/Article/details/gt2vucgnyyt.html

Go:   // 双指针从两端比较
来源：http://dali.pycfn.com/Article/details/gt2ytbcwlsa.html

Ruby: s == s.reverse
来源：http://dali.aizwys.cn/Article/details/gt2axvqqzqb.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.havefunace.top/Article/details/gt2vkypzofa.html

[N07] 两数之和（返回下标）
来源：http://dali.9152youxi.cn/Article/details/gt2vcxluylz.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.jqgufenzy.top/Article/details/gt2kjaqpsrl.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.jinqigfzy.top/Article/details/gt2yqgwlczq.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.gogol.net.cn/Article/details/gt2bpcooqxv.html

TS:   // 手写 Map<string, number>
来源：http://dali.nanxuanxn.top/Article/details/gt2oohxzfbf.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2efpvpbyy.html

Go:   // 手写 map[int]int
来源：http://dali.zhoulong.xyz/Article/details/gt2xfsldjmq.html

Ruby: // 手写 Hash
来源：http://dali.shangyingyoupin.top/Article/details/gt2zudnxluz.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.mhx1999.top/Article/details/gt2vvgbtuyv.html

[N08] 生成全排列
来源：http://dali.smart0.xyz/Article/details/gt2ffddmppf.html

Py:   itertools.permutations(arr)
来源：http://dali.yongpay.top/Article/details/gt2svigzgal.html

PHP:  // 手写递归交换
来源：http://dali.0kj1m.cn/Article/details/gt2fwliwgxd.html

JS:   // 手写回溯递归
来源：http://dali.shzxlz.cn/Article/details/gt2lbvappti.html

TS:   // 手写回溯递归
来源：http://dali.hongshengwenyu.top/Article/details/gt2tpaajdjr.html

Java: // 手写回溯递归
来源：http://dali.hnqzz.top/Article/details/gt2sbeltaja.html

Go:   // 手写回溯递归
来源：http://dali.shzxlz.cn/Article/details/gt2ngxdlqhp.html

Ruby: arr.permutation.to_a
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mrxnzvdp.html

C#:   // 手写回溯递归
来源：http://dali.tianlin.xyz/Article/details/gt2rhgittkr.html

[N09] 栈与队列
来源：http://dali.mhx1999.top/Article/details/gt2lbgqajtn.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ekpqyoch.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.bjfxy.top/Article/details/gt2cphclwhc.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.hongshengwenyu.top/Article/details/gt2lhojwgxk.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.sufxvd.cn/Article/details/gt2onhhhiup.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.jlsjyb.cn/Article/details/gt2cddejopd.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.hongshengwenyu.top/Article/details/gt2kkdjzjvd.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.sweek.top/Article/details/gt2tzmiuziy.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.sweek.top/Article/details/gt2qfxszvsw.html

[N10] 链表节点定义
来源：http://dali.sysykeji.top/Article/details/gt2rkyezjhi.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.meibo888.top/Article/details/gt2xsaqrwei.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.xylfe.cn/Article/details/gt2tlgtwwjj.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.gogol.net.cn/Article/details/gt2vtrwnylg.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.hnxiangtu.top/Article/details/gt2mlndwhsj.html

Java: class Node { int v; Node next; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2yrvjbuhy.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.meibo888.top/Article/details/gt2hnxivugb.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.0kj1m.cn/Article/details/gt2dckiruzm.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.cashguo.top/Article/details/gt2rrpolttc.html

[N11] 二叉树中序遍历
来源：http://dali.chenjidiqi.icu/Article/details/gt2yubjoqqk.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.sysykeji.top/Article/details/gt2rqcejwnu.html

PHP:  // 手写递归函数
来源：http://dali.yvedp.cn/Article/details/gt2ggboqrof.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.c1oappe.top/Article/details/gt2hyyhokqm.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jqgufenzy.top/Article/details/gt2wuavuziw.html

Java: // 手写递归
来源：http://dali.zycfv.cn/Article/details/gt2flxafvab.html

Go:   // 手写递归
来源：http://dali.jinqigfzy.top/Article/details/gt2aictwzlq.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.hnqzz.top/Article/details/gt2olvhtsrx.html

C#:   // 手写递归
来源：http://dali.chenlongwang.top/Article/details/gt2aiyqutsj.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.smart0.xyz/Article/details/gt2xqatitvf.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.feifeiyinyue.top/Article/details/gt2ibnmklih.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.ybcxt.top/Article/details/gt2koynxrsj.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.svipenyu.cn/Article/details/gt2jwjacrlu.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.guowangkeji.top/Article/details/gt2rsjwfxha.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.cashguo.top/Article/details/gt2cjpmgmmx.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2usgnclpg.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.nwbrower.top/Article/details/gt2zssjjfhm.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.fzhhl.top/Article/details/gt2pdeptxin.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gt2zlohvvwm.html

O. 并发与异步
来源：http://dali.feifeiyinyue.top/Article/details/gt2eniabzgc.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tkxoaxan.html

[O01] 启动一个线程
来源：http://dali.zhixingplan.top/Article/details/gt2gpotchqy.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.yj20258.top/Article/details/gt2japxgagv.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.tianlin.xyz/Article/details/gt2ecnyftil.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.sweek.top/Article/details/gt2npmvywus.html

TS:   // 同 JS
来源：http://dali.shuidangran.top/Article/details/gt2cqjssqrv.html

Java: new Thread(() -> f()).start()
来源：http://dali.sxryk.cn/Article/details/gt2iscsdgce.html

Go:   go f()
来源：http://dali.nanxuanxn.top/Article/details/gt2jqqiukwr.html

Ruby: Thread.new { f }
来源：http://dali.aizwys.cn/Article/details/gt2hbwzazsr.html

C#:   Task.Run(() => F());
来源：http://dali.yj202588.top/Article/details/gt2cyklzbol.html

[O02] 使用线程池
来源：http://dali.gaohongyu789.top/Article/details/gt2ptppkctr.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.wangdashe.top/Article/details/gt2juxzbnhr.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kvxetgtk.html

JS:   // worker_threads 线程池
来源：http://dali.wangdashe.top/Article/details/gt2iwjjncam.html

TS:   // worker_threads 线程池
来源：http://dali.jinghuilouyu.cn/Article/details/gt2awccvbyh.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.kuanghao11.cn/Article/details/gt2ioteklpx.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhongyouzk.top/Article/details/gt2vxmmkjzi.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.jinqigufen.top/Article/details/gt2houbzfxg.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.cheryme.top/Article/details/gt2obhqrfwk.html

[O03] 加锁保护共享数据
来源：http://dali.sweek.top/Article/details/gt2nhbfuisu.html

Py:   with lock: shared += 1
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lchsbdle.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.havefunace.top/Article/details/gt2qqydfung.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.cdnleiting.top/Article/details/gt2cqemhslu.html

TS:   // 同 JS
来源：http://dali.cucudq.cn/Article/details/gt2upzovhjp.html

Java: synchronized (this) { shared++; }
来源：http://dali.aibaodan.cn/Article/details/gt2nuzwyver.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fcbbmnfq.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.daxiang520.top/Article/details/gt2voqsnihs.html

C#:   lock (gate) { shared++; }
来源：http://dali.yuxming.cn/Article/details/gt2wmyamltw.html

[O04] 定义异步函数并等待
来源：http://dali.gotoacloud.top/Article/details/gt2xanfikkn.html

Py:   async def f():⏎    await g()
来源：http://dali.snrcjt.cn/Article/details/gt2zzicxbih.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.andypj.xyz/Article/details/gt2yprtkgcn.html

JS:   async function f() { await g(); }
来源：http://dali.shangyingyoupin.top/Article/details/gt2dryovjxs.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.jlsjyb.cn/Article/details/gt2egzycpdn.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.yj20258888.top/Article/details/gt2mctmvjwp.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.cdnleiting.top/Article/details/gt2sqtxkplq.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.ydzc1.top/Article/details/gt2syyofmua.html

C#:   async Task F() { await G(); }
来源：http://dali.guowangkeji.top/Article/details/gt2qjtkszxo.html

[O05] 并发执行并等待全部完成
来源：http://dali.yj202588.top/Article/details/gt2evwrqupp.html

Py:   asyncio.gather(*tasks)
来源：http://dali.fengsongda.top/Article/details/gt2ytzckjiy.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.chenzaomai.com/Article/details/gt2tehuxptf.html

JS:   await Promise.all(tasks)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zbeddbbd.html

TS:   await Promise.all(tasks)
来源：http://dali.yj20258888.top/Article/details/gt2nhrpdtlc.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.cucudq.cn/Article/details/gt2jsfxilub.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.gotoacloud.top/Article/details/gt2jytrdrxi.html

Ruby: threads.map(&:join)
来源：http://dali.gotoacloud.top/Article/details/gt2loarajst.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qlrffkxg.html

[O06] 使用进程池
来源：http://dali.nwbrower.top/Article/details/gt2akpcodme.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.316326.xyz/Article/details/gt2hxemzeqc.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.xylfe.cn/Article/details/gt2dqicodlt.html

JS:   // child_process / cluster 模块
来源：http://dali.ivvv.top/Article/details/gt2ysjsomxj.html

TS:   // child_process / cluster 模块
来源：http://dali.vqdsnc.cn/Article/details/gt2qxkmxmvf.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhengqikj.top/Article/details/gt2xygfybyh.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.316326.xyz/Article/details/gt2kofrsdsu.html

Ruby: // fork 块
来源：http://dali.yanxiufei.cn/Article/details/gt2yphmpetn.html

C#:   Parallel.For
来源：http://dali.aizwys.cn/Article/details/gt2rxavavwc.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gt2wgcmdwin.html

P. 常用工具函数
来源：http://dali.dashuyun.cn/Article/details/gt2ceczqhus.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gt2hetwxlwt.html

[P01] 生成 UUID
来源：http://dali.kuanghao11.cn/Article/details/gt2yvdswnby.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2yvbchpur.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.svipenyu.cn/Article/details/gt2yhsemkpa.html

JS:   crypto.randomUUID()
来源：http://dali.yueranfly.top/Article/details/gt2fxtizunu.html

TS:   crypto.randomUUID()
来源：http://dali.chenjidiqi.icu/Article/details/gt2zoxmmqqq.html

Java: UUID.randomUUID().toString()
来源：http://dali.guowangkeji.top/Article/details/gt2pxtguphv.html

Go:   // 用 github.com/google/uuid
来源：http://dali.yj20258888.top/Article/details/gt2cetkxrdr.html

Ruby: SecureRandom.uuid
来源：http://dali.guowangkeji.top/Article/details/gt2ckhxnokq.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.ybcxt.top/Article/details/gt2gmpnodjq.html

[P02] MD5 / SHA256 摘要
来源：http://dali.xylfe.cn/Article/details/gt2wthbqnom.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.hnxiangtu.top/Article/details/gt2gmjgntgs.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.jyoumei.cn/Article/details/gt2cpxmqmzi.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.hywenlv.cn/Article/details/gt2ybvllico.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.hongshengwenyu.top/Article/details/gt2vcekicfj.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.xylfe.cn/Article/details/gt2jtxovlms.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.redwolf501.top/Article/details/gt2nedssicv.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.sufxvd.cn/Article/details/gt2ngadkqhj.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.daria6918.cn/Article/details/gt2seuxufpp.html

[P03] 生成短随机字符串
来源：http://dali.hywenlv.cn/Article/details/gt2qyjwadmf.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.316326.xyz/Article/details/gt2snihksvp.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.cashguo.top/Article/details/gt2xnsbcked.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.hnqzz.top/Article/details/gt2boczahgh.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.wangdashe.top/Article/details/gt2pqqdmkeo.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.hnqzz.top/Article/details/gt2yfqeckar.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yodxdrmi.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.birdmap.top/Article/details/gt2wzczphzq.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.zhixingplan.top/Article/details/gt2pqnadady.html

[P04] 求长度
来源：http://dali.aibaodan.cn/Article/details/gt2qurhxlib.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.daxiang520.top/Article/details/gt2nkagjfqm.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.tianlin.xyz/Article/details/gt2wgnkakvz.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yuxming.cn/Article/details/gt2vtvtpytq.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.ppjwa.cn/Article/details/gt2mjnsdhmi.html

Java: list.size();  map.size();  s.length()
来源：http://dali.svipenyu.cn/Article/details/gt2khdcveip.html

Go:   len(arr);  len(m)
来源：http://dali.jinqigufen.top/Article/details/gt2nfwnlbqt.html

Ruby: x.length;  x.size
来源：http://dali.xinyue.icu/Article/details/gt2wcgwtiri.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.wangshuangyany.cn/Article/details/gt2wcddryfo.html

[P05] 判断两个对象内容是否相等
来源：http://dali.sysykeji.top/Article/details/gt2wanzzqkf.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.hammf.cn/Article/details/gt2dulrltyf.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.guowangkeji.top/Article/details/gt2ijumwhar.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.sysykeji.top/Article/details/gt2dhykcsnt.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.hammf.cn/Article/details/gt2ytwxcfnh.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.xuanzx.com/Article/details/gt2ohinhgwu.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.ppjwa.cn/Article/details/gt2okmvhvwj.html

Ruby: a == b
来源：http://dali.wangshuangyany.cn/Article/details/gt2qzsfbfod.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.zhiwuduotai.top/Article/details/gt2ekvxlrzl.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.sysykeji.top/Article/details/gt2qiwexlwd.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lzyxabvr.html

PHP:  if (empty($x)) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hqpicndq.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.iojbl.cn/Article/details/gt2pkazomrj.html

TS:   if (x == null) {}
来源：http://dali.aizwys.cn/Article/details/gt2dldnzmwt.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.dashuyun.cn/Article/details/gt2vmupdazd.html

Go:   if x == nil {}
来源：http://dali.wangdashe.top/Article/details/gt2fbeuhldm.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.mhx1999.top/Article/details/gt2zspxoqvp.html

C#:   if (x is null) {}
来源：http://dali.hnxiangtu.top/Article/details/gt2srikfyxl.html

[P07] 防抖与节流
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2olvgnooh.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.birdmap.top/Article/details/gt2qepdjujn.html


<!-- 参考信息 -->