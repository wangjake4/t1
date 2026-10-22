代发 wailian999

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.chenzaomai.com/Article/details/gt2wsjizxob.html

JS:   process.env.HOME
来源：http://dali.jinqigfzy.top/Article/details/gt2jvybrtwd.html

TS:   process.env.HOME
来源：http://dali.jqgfzy.top/Article/details/gt2tmvhsyui.html

Java: System.getenv("HOME")
来源：http://dali.gaohongyu789.top/Article/details/gt2ckndgzps.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.sufxvd.cn/Article/details/gt2enhupwoo.html

Ruby: ENV["HOME"]
来源：http://dali.daria6918.cn/Article/details/gt2cooauezr.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.xuanzx.com/Article/details/gt2nkvdhugb.html

[M03] 执行外部命令
来源：http://dali.zhiwuduotai.top/Article/details/gt2ybavemfx.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.jianghu66.top/Article/details/gt2htmaxqcm.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.jianghu66.top/Article/details/gt2blpsuvmf.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.chenjidiqi.icu/Article/details/gt2jhfkdszb.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.jyoumei.cn/Article/details/gt2ebfcsccr.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.tian-w.cn/Article/details/gt2kuyiawed.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.feifeiyinyue.top/Article/details/gt2jlfuesos.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.dashuyun.cn/Article/details/gt2gikwvmoc.html

C#:   Process.Start("ls", "-l");
来源：http://dali.ydzc1.top/Article/details/gt2czplaqlt.html

[M04] 获取当前工作目录
来源：http://dali.yangfankeji.com/Article/details/gt2bhapajye.html

Py:   os.getcwd()
来源：http://dali.gaohongyu789.top/Article/details/gt2tlkgsyay.html

PHP:  getcwd();
来源：http://dali.sweek.top/Article/details/gt2drsonhay.html

JS:   process.cwd()
来源：http://dali.chenzaomai.com/Article/details/gt2aalkrzql.html

TS:   process.cwd()
来源：http://dali.hnqzz.top/Article/details/gt2abgxkoqx.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.chenzaomai.com/Article/details/gt2yniwvpqr.html

Go:   os.Getwd()
来源：http://dali.kuanghao11.cn/Article/details/gt2lpyvakeh.html

Ruby: Dir.pwd
来源：http://dali.zhixingplan.top/Article/details/gt2acssxmla.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.daxiang520.top/Article/details/gt2lyxkzjdu.html

[M05] 设置退出码
来源：http://dali.chenlongwang.top/Article/details/gt2dupdsrpp.html

Py:   sys.exit(1)
来源：http://dali.ppjwa.cn/Article/details/gt2ykpfkqoi.html

PHP:  exit(1);
来源：http://dali.shangyingyoupin.top/Article/details/gt2jikdtbmh.html

JS:   process.exit(1)
来源：http://dali.ehwqpu.com/Article/details/gt2bexvjohx.html

TS:   process.exit(1)
来源：http://dali.xuanzx.com/Article/details/gt2epwwivuz.html

Java: System.exit(1)
来源：http://dali.zdqjudy.top/Article/details/gt2xrughvce.html

Go:   os.Exit(1)
来源：http://dali.yongpay.top/Article/details/gt2acnsdfkd.html

Ruby: exit 1
来源：http://dali.zhengqikj.top/Article/details/gt2gsihzphx.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.havefunace.top/Article/details/gt2hkzztnab.html

[M06] 向标准错误输出
来源：http://dali.hfpthk.cn/Article/details/gt2mgtuvtbh.html

Py:   print("err", file=sys.stderr)
来源：http://dali.nwbrower.top/Article/details/gt2bcokvbcu.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.cucudq.cn/Article/details/gt2lolaykdu.html

JS:   console.error("err")
来源：http://dali.bjfxy.top/Article/details/gt2xtfsdkys.html

TS:   console.error("err")
来源：http://dali.zycfv.cn/Article/details/gt2dpojizhx.html

Java: System.err.println("err")
来源：http://dali.jianghu66.top/Article/details/gt2vfhdpsvl.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.yueranfly.top/Article/details/gt2rjcsgbvb.html

Ruby: warn "err"
来源：http://dali.chenzaomai.com/Article/details/gt2gtjlepcr.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.quarkkingdee.top/Article/details/gt2wpetblsl.html

[M07] 判断是否为主入口
来源：http://dali.dashuyun.cn/Article/details/gt2ivtglbmn.html

Py:   if __name__ == "__main__":
来源：http://dali.quarkkingdee.top/Article/details/gt2sscmcchd.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.yj20258888.top/Article/details/gt2tlqayqof.html

JS:   require.main === module
来源：http://dali.sxryk.cn/Article/details/gt2ztjtnego.html

TS:   require.main === module
来源：http://dali.zhengqikj.top/Article/details/gt2zslmohrr.html

Java: public static void main(String[] args)
来源：http://dali.kuanghao11.cn/Article/details/gt2bnvxxjlz.html

Go:   func main()
来源：http://dali.tianlin.xyz/Article/details/gt2aehvkgii.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2ntespcsu.html

C#:   static void Main(string[] args)
来源：http://dali.guowangkeji.top/Article/details/gt2wjfqiext.html

[M08] 获取系统与运行时信息
来源：http://dali.meibo888.top/Article/details/gt2fslybteo.html

Py:   platform.system();  platform.python_version()
来源：http://dali.bjfxy.top/Article/details/gt2aldjcxmq.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.sufxvd.cn/Article/details/gt2pxnfmqfo.html

JS:   process.platform;  process.version
来源：http://dali.jyoumei.cn/Article/details/gt2ycgijvnl.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2hrvedlvw.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.ybcxt.top/Article/details/gt2naihbejx.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.aizwys.cn/Article/details/gt2sqlydmoi.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.havefunace.top/Article/details/gt2vmczbgwn.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.wangshuangyany.cn/Article/details/gt2fcfjliju.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gt2kmxjbkxr.html

N. 数据结构与算法
来源：http://dali.9152youxi.cn/Article/details/gt2hqyprfuy.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gt2tzzbpsbi.html

[N01] 二分查找（有序数组）
来源：http://dali.haohaochexian.top/Article/details/gt2dqchwvvz.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhiwuduotai.top/Article/details/gt2fmibzjmh.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.nwbrower.top/Article/details/gt2sknnjeik.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.fzhhl.top/Article/details/gt2qumcmfzn.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.sufxvd.cn/Article/details/gt2httjneca.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.mhx1999.top/Article/details/gt2frwadjdz.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.xuanzx.com/Article/details/gt2qtqbtjtl.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.hywenlv.cn/Article/details/gt2pfoblvru.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.xuanzx.com/Article/details/gt2arkervye.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.c1oappe.top/Article/details/gt2upwzktgj.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.chenzaomai.com/Article/details/gt2brvmqdcp.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.ivvv.top/Article/details/gt2fdthubdv.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.wangshuangyany.cn/Article/details/gt2bpfnedmi.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yueranfly.top/Article/details/gt2zpqrjcwp.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.tian-w.cn/Article/details/gt2tsjnazqb.html

Go:   slices.Sort(arr)
来源：http://dali.hongshengwenyu.top/Article/details/gt2uiliybgo.html

Ruby: arr.sort
来源：http://dali.ybcxt.top/Article/details/gt2bttijxjs.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.tian-w.cn/Article/details/gt2aaowbvzo.html

[N03] 快速排序（分治示例）
来源：http://dali.cheryme.top/Article/details/gt2iolmufxp.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.fengsongda.top/Article/details/gt2mscwzdgi.html

PHP:  // 递归实现，或用 usort
来源：http://dali.yj20258.top/Article/details/gt2nswbtvit.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhixingplan.top/Article/details/gt2fyrsqdad.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.hnxiangtu.top/Article/details/gt2ljmwaxqd.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.jlsjyb.cn/Article/details/gt2sgijxyrs.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.fengsongda.top/Article/details/gt2qjztgvtv.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.xuanzx.com/Article/details/gt2rrnimekr.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.cdnleiting.top/Article/details/gt2wshhuags.html

[N04] 斐波那契数列
来源：http://dali.xuanzx.com/Article/details/gt2jgzintma.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.yangfankeji.com/Article/details/gt2mqpzxbfj.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.mhx1999.top/Article/details/gt2rbwuuogo.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.sweek.top/Article/details/gt2qggatyej.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.sxryk.cn/Article/details/gt2acuhxkmp.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.hongshengwenyu.top/Article/details/gt2qudkqvmw.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.316326.xyz/Article/details/gt2koqetywq.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.nwbrower.top/Article/details/gt2gxnqogkv.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.yuxming.cn/Article/details/gt2xbmgyszu.html

[N05] 最大公约数
来源：http://dali.hongshengwenyu.top/Article/details/gt2vljycetu.html

Py:   math.gcd(a, b)
来源：http://dali.dianchejie.cn/Article/details/gt2dvenhtrs.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.haohaochexian.top/Article/details/gt2xdhzbphj.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.andypj.xyz/Article/details/gt2couwwklg.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.xinyue.icu/Article/details/gt2kpzrdhva.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2avznwroh.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.cashguo.top/Article/details/gt2eaccwaic.html

Ruby: a.gcd(b)
来源：http://dali.zhongyouzk.top/Article/details/gt2hfxzmvpp.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.hongshengwenyu.top/Article/details/gt2fjokegpl.html

[N06] 判断回文字符串
来源：http://dali.yj20258.top/Article/details/gt2xbnqeqxf.html

Py:   s == s[::-1]
来源：http://dali.jinqigufen.top/Article/details/gt2mvqgpzgr.html

PHP:  $s === strrev($s);
来源：http://dali.cucudq.cn/Article/details/gt2cphrwwsd.html

JS:   s === [...s].reverse().join("")
来源：http://dali.pengpengdd.cyou/Article/details/gt2rdrdtzbi.html

TS:   s === [...s].reverse().join("")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yavvfayb.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.smart0.xyz/Article/details/gt2owmdbujp.html

Go:   // 双指针从两端比较
来源：http://dali.wangshuangyany.cn/Article/details/gt2nrttybbn.html

Ruby: s == s.reverse
来源：http://dali.ppjwa.cn/Article/details/gt2tfaoycyt.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.yanxiufei.cn/Article/details/gt2bwrmbmbe.html

[N07] 两数之和（返回下标）
来源：http://dali.yanxiufei.cn/Article/details/gt2lsgwsuyo.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.nanxinkj.top/Article/details/gt2shllgscf.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.ydzc1.top/Article/details/gt2yhugqfuw.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.jianghu66.top/Article/details/gt2pccmybsu.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2lukndsfz.html

Java: // 手写 HashMap
来源：http://dali.316326.xyz/Article/details/gt2falzxudq.html

Go:   // 手写 map[int]int
来源：http://dali.hywenlv.cn/Article/details/gt2inkfsgpg.html

Ruby: // 手写 Hash
来源：http://dali.xziqi.cn/Article/details/gt2qqxlrraf.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.jyoumei.cn/Article/details/gt2awdlvskc.html

[N08] 生成全排列
来源：http://dali.shzxlz.cn/Article/details/gt2cmzjjlzw.html

Py:   itertools.permutations(arr)
来源：http://dali.smart0.xyz/Article/details/gt2frgjaafh.html

PHP:  // 手写递归交换
来源：http://dali.gogol.net.cn/Article/details/gt2qzpsbsqf.html

JS:   // 手写回溯递归
来源：http://dali.ivvv.top/Article/details/gt2yusibxlv.html

TS:   // 手写回溯递归
来源：http://dali.gaohongyu789.top/Article/details/gt2qyyqujsj.html

Java: // 手写回溯递归
来源：http://dali.9152youxi.cn/Article/details/gt2fyjfdjmg.html

Go:   // 手写回溯递归
来源：http://dali.yuxming.cn/Article/details/gt2lanrboyw.html

Ruby: arr.permutation.to_a
来源：http://dali.sufxvd.cn/Article/details/gt2ksadrice.html

C#:   // 手写回溯递归
来源：http://dali.xuanzx.com/Article/details/gt2lvnmfxzw.html

[N09] 栈与队列
来源：http://dali.yuxming.cn/Article/details/gt2lqmhqwyh.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.ydzc1.top/Article/details/gt2sfkctdnz.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.wangshuangyany.cn/Article/details/gt2qtxspzun.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.nanxuanxn.top/Article/details/gt2yvetwbha.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.cdnleiting.top/Article/details/gt2axpukeuo.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.nanxuanxn.top/Article/details/gt2pfbikdzf.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.cheryme.top/Article/details/gt2jcbpdjdy.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.ehwqpu.com/Article/details/gt2ngqajlcw.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.gzhubu.top/Article/details/gt2jwaypsoe.html

[N10] 链表节点定义
来源：http://dali.smart0.xyz/Article/details/gt2xsflfosu.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.haohaochexian.top/Article/details/gt2bbdzrxsd.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.hammf.cn/Article/details/gt2jsgdxvuw.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yifmbnge.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.xuanzx.com/Article/details/gt2zzbeqzaz.html

Java: class Node { int v; Node next; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2timmaisl.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.nanxuanxn.top/Article/details/gt2wovwwusr.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.smart0.xyz/Article/details/gt2diiwrzwd.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhixingplan.top/Article/details/gt2sysqayuk.html

[N11] 二叉树中序遍历
来源：http://dali.yueranfly.top/Article/details/gt2qbjeavfl.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.vqdsnc.cn/Article/details/gt2vzpsodkf.html

PHP:  // 手写递归函数
来源：http://dali.sysykeji.top/Article/details/gt2iodshwvs.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.aibaodan.cn/Article/details/gt2syhyocur.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.tianlin.xyz/Article/details/gt2ksrssutp.html

Java: // 手写递归
来源：http://dali.yvedp.cn/Article/details/gt2arlgmkib.html

Go:   // 手写递归
来源：http://dali.andypj.xyz/Article/details/gt2voomxcql.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.guannengcc.top/Article/details/gt2whcscevj.html

C#:   // 手写递归
来源：http://dali.fzhhl.top/Article/details/gt2egejtpuk.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.shuidangran.top/Article/details/gt2ixmqmcar.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.iojbl.cn/Article/details/gt2kqosbish.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.cheryme.top/Article/details/gt2xivzljzk.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.shangyingyoupin.top/Article/details/gt2rifsbrff.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.dashuyun.cn/Article/details/gt2bdqoonuv.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhixingplan.top/Article/details/gt2xayxegmo.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bcrdygyu.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.redwolf501.top/Article/details/gt2nisbetra.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.guannengcc.top/Article/details/gt2ohjjdyez.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gt2bbptjojx.html

O. 并发与异步
来源：http://dali.tanke756.top/Article/details/gt2nrtvvfpi.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gt2mdbsangk.html

[O01] 启动一个线程
来源：http://dali.mhx1999.top/Article/details/gt2outolgvq.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.nanxinkj.top/Article/details/gt2erlgeblj.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.aibaodan.cn/Article/details/gt2sdzphefa.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.jqgfzy.top/Article/details/gt2qoyqrpur.html

TS:   // 同 JS
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fvpewyck.html

Java: new Thread(() -> f()).start()
来源：http://dali.aizwys.cn/Article/details/gt2wyuogmkm.html

Go:   go f()
来源：http://dali.aibaodan.cn/Article/details/gt2nszthxlf.html

Ruby: Thread.new { f }
来源：http://dali.yj20258.top/Article/details/gt2rgnwbucr.html

C#:   Task.Run(() => F());
来源：http://dali.snrcjt.cn/Article/details/gt2zuivvuis.html

[O02] 使用线程池
来源：http://dali.hnqzz.top/Article/details/gt2aaubjcmn.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.tianlin.xyz/Article/details/gt2cgxermbu.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.birdmap.top/Article/details/gt2etggfhpn.html

JS:   // worker_threads 线程池
来源：http://dali.xziqi.cn/Article/details/gt2gbeeofnp.html

TS:   // worker_threads 线程池
来源：http://dali.chenzaomai.com/Article/details/gt2hjbdwzgf.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.ppjwa.cn/Article/details/gt2pnxenyzl.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.yvedp.cn/Article/details/gt2juiliqoo.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.yj20258.top/Article/details/gt2ndooowwk.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.cucudq.cn/Article/details/gt2infidelf.html

[O03] 加锁保护共享数据
来源：http://dali.iojbl.cn/Article/details/gt2rpeekgxd.html

Py:   with lock: shared += 1
来源：http://dali.jianghu66.top/Article/details/gt2rpurhlbx.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zycfv.cn/Article/details/gt2imhlkdiz.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.wangdashe.top/Article/details/gt2rvmoguxn.html

TS:   // 同 JS
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vnzdnynh.html

Java: synchronized (this) { shared++; }
来源：http://dali.hnqzz.top/Article/details/gt2jnfseolw.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.jlsjyb.cn/Article/details/gt2scwjghtm.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mwvupgor.html

C#:   lock (gate) { shared++; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qjsrbvuv.html

[O04] 定义异步函数并等待
来源：http://dali.yuanzhike.top/Article/details/gt2wodzdehi.html

Py:   async def f():⏎    await g()
来源：http://dali.jinqigfzy.top/Article/details/gt2mqwfrqrh.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.yueranfly.top/Article/details/gt2potuzaed.html

JS:   async function f() { await g(); }
来源：http://dali.meibo888.top/Article/details/gt2ihssohwp.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.c1oappe.top/Article/details/gt2ikxqyrwk.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.daxiang520.top/Article/details/gt2fcslehin.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.jqgfzy.top/Article/details/gt2dgcejjxs.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.vqdsnc.cn/Article/details/gt2iirjdffk.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2offovwkj.html

[O05] 并发执行并等待全部完成
来源：http://dali.shanyushiyangtech.top/Article/details/gt2adctqzdm.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2mifoxyup.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.fengsongda.top/Article/details/gt2nhmjxxjb.html

JS:   await Promise.all(tasks)
来源：http://dali.hywenlv.cn/Article/details/gt2pwmkcctf.html

TS:   await Promise.all(tasks)
来源：http://dali.dashuyun.cn/Article/details/gt2ghwgwejq.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.cdnleiting.top/Article/details/gt2nhzmyvry.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rjojjamp.html

Ruby: threads.map(&:join)
来源：http://dali.sufxvd.cn/Article/details/gt2issuyivd.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.vqdsnc.cn/Article/details/gt2cqqxiknh.html

[O06] 使用进程池
来源：http://dali.gaohongyu789.top/Article/details/gt2xmcivbwb.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.yangfankeji.com/Article/details/gt2ytvlgrfd.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.ppjwa.cn/Article/details/gt2ysngbqnm.html

JS:   // child_process / cluster 模块
来源：http://dali.shzxlz.cn/Article/details/gt2ejuebwcw.html

TS:   // child_process / cluster 模块
来源：http://dali.nanxinkj.top/Article/details/gt2eghzmkou.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.ppjwa.cn/Article/details/gt2zozpkqxm.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.andypj.xyz/Article/details/gt2dluvolvm.html

Ruby: // fork 块
来源：http://dali.gogol.net.cn/Article/details/gt2unbhyaqy.html

C#:   Parallel.For
来源：http://dali.zhiwuduotai.top/Article/details/gt2dboronic.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wltxdqmy.html

P. 常用工具函数
来源：http://dali.yj20258888.top/Article/details/gt2jpdewqvo.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gt2nndqulxy.html

[P01] 生成 UUID
来源：http://dali.hywenlv.cn/Article/details/gt2cdctziyq.html

Py:   str(uuid.uuid4())
来源：http://dali.yongpay.top/Article/details/gt2iwovyzus.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2tsinkmnz.html

JS:   crypto.randomUUID()
来源：http://dali.yvedp.cn/Article/details/gt2ojrtnqrz.html

TS:   crypto.randomUUID()
来源：http://dali.xziqi.cn/Article/details/gt2kgltcyfd.html

Java: UUID.randomUUID().toString()
来源：http://dali.jinqigufen.top/Article/details/gt2vzlwhzaz.html

Go:   // 用 github.com/google/uuid
来源：http://dali.dianchejie.cn/Article/details/gt2gbgcckjp.html

Ruby: SecureRandom.uuid
来源：http://dali.gzhubu.top/Article/details/gt2xfmgbrxi.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.birdmap.top/Article/details/gt2owxzhrcq.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zhoulong.xyz/Article/details/gt2tdlpfbsf.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.wangshuangyany.cn/Article/details/gt2uryrgzyu.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.snrcjt.cn/Article/details/gt2zmniucyx.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.yuanzhike.top/Article/details/gt2pdiehucx.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.jianghu66.top/Article/details/gt2tkgjrcir.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zdqjudy.top/Article/details/gt2qokvxhtl.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.hammf.cn/Article/details/gt2sdgoslbu.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.hammf.cn/Article/details/gt2bpdxabmj.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.yonumen.top/Article/details/gt2rjdwdrkw.html

[P03] 生成短随机字符串
来源：http://dali.yanxiufei.cn/Article/details/gt2hhvvarov.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.hnxiangtu.top/Article/details/gt2sjrjzruv.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2swnokjtp.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.nanxuanxn.top/Article/details/gt2kxtnbdvw.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhoulong.xyz/Article/details/gt2grzavxss.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.guannengcc.top/Article/details/gt2ezakaigr.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.hnxiangtu.top/Article/details/gt2fjvciwxn.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.jinqigufen.top/Article/details/gt2qtogxaqm.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.shuidangran.top/Article/details/gt2vwnaczqe.html

[P04] 求长度
来源：http://dali.dashuyun.cn/Article/details/gt2lfabnyhq.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhongyouzk.top/Article/details/gt2ubtneoku.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.sxryk.cn/Article/details/gt2iwdwqthn.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.daxiang520.top/Article/details/gt2utgjxnos.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yj20258.top/Article/details/gt2vjqttxzq.html

Java: list.size();  map.size();  s.length()
来源：http://dali.wangdashe.top/Article/details/gt2htdkabfy.html

Go:   len(arr);  len(m)
来源：http://dali.yonumen.top/Article/details/gt2lxojqcys.html

Ruby: x.length;  x.size
来源：http://dali.yj20258888.top/Article/details/gt2onjalanc.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.sweek.top/Article/details/gt2crindvso.html

[P05] 判断两个对象内容是否相等
来源：http://dali.mhx1999.top/Article/details/gt2bbjcnccx.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.gotoacloud.top/Article/details/gt2qrhoflnm.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.snrcjt.cn/Article/details/gt2pxbjzelr.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.xinyue.icu/Article/details/gt2twxkwuuw.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2fiodbljn.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zdqjudy.top/Article/details/gt2cjicfsrn.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.sweek.top/Article/details/gt2smdcbari.html

Ruby: a == b
来源：http://dali.vqdsnc.cn/Article/details/gt2ecpjqbbc.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.meibo888.top/Article/details/gt2fqzoibbg.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.sxryk.cn/Article/details/gt2xszdhvip.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.hysaishi.cn/Article/details/gt2gghslxdy.html

PHP:  if (empty($x)) {}
来源：http://dali.yuxming.cn/Article/details/gt2cmfhpmee.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.jqgufenzy.top/Article/details/gt2svunmkof.html

TS:   if (x == null) {}
来源：http://dali.dashuyun.cn/Article/details/gt2kycdqifb.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.nanxuanxn.top/Article/details/gt2eijmccki.html

Go:   if x == nil {}
来源：http://dali.hywenlv.cn/Article/details/gt2hvfenjbe.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.yuxming.cn/Article/details/gt2mboizejz.html

C#:   if (x is null) {}
来源：http://dali.yangfankeji.com/Article/details/gt2ycfmtuyb.html

[P07] 防抖与节流
来源：http://dali.316326.xyz/Article/details/gt2dyqakhlj.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.yvedp.cn/Article/details/gt2tfibaqbp.html

PHP:  // 手写时间戳比较
来源：http://dali.guowangkeji.top/Article/details/gt2xcbefxcd.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.9152youxi.cn/Article/details/gt2qvnjuich.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.mhx1999.top/Article/details/gt2pkctauvv.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.nwbrower.top/Article/details/gt2ukpfzujy.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xfbcydgl.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.tian-w.cn/Article/details/gt2qrmrorqd.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.sysykeji.top/Article/details/gt2efsdrbsn.html

[P08] 处理浮点精度问题
来源：http://dali.jinqigufen.top/Article/details/gt2qrcqbttj.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.snrcjt.cn/Article/details/gt2mdpclfbg.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.hongshengwenyu.top/Article/details/gt2pozanqfj.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.gotoacloud.top/Article/details/gt2guvzefci.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.shangyingyoupin.top/Article/details/gt2dacdejkz.html


<!-- 参考信息 -->