代发 wailian999

JS:   process.argv.slice(2)
来源：http://dali.ivvv.top/Article/details/gt2elflnyrm.html

TS:   process.argv.slice(2)
来源：http://dali.jqgfzy.top/Article/details/gt2agerlzuh.html

Java: args 数组（main 方法参数）
来源：http://dali.9152youxi.cn/Article/details/gt2qqclmukc.html

Go:   os.Args[1:]
来源：http://dali.kuanghao11.cn/Article/details/gt2wuuaphqv.html

Ruby: ARGV
来源：http://dali.jqgfzy.top/Article/details/gt2knxmtqid.html

C#:   args 数组（Main 方法参数）
来源：http://dali.9152youxi.cn/Article/details/gt2avezvdcm.html

[M02] 读取环境变量
来源：http://dali.ivvv.top/Article/details/gt2ulutvfsw.html

Py:   os.environ.get("HOME")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vgifgqyb.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.dianchejie.cn/Article/details/gt2lxywijsw.html

JS:   process.env.HOME
来源：http://dali.zycfv.cn/Article/details/gt2cyifotnz.html

TS:   process.env.HOME
来源：http://dali.sysykeji.top/Article/details/gt2bhzmqknn.html

Java: System.getenv("HOME")
来源：http://dali.nanxinkj.top/Article/details/gt2tmzbdwjh.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.316326.xyz/Article/details/gt2oplrrhba.html

Ruby: ENV["HOME"]
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bkuxcjlk.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.shangyingyoupin.top/Article/details/gt2iztbeqgy.html

[M03] 执行外部命令
来源：http://dali.pengpengdd.cyou/Article/details/gt2wwbvuizu.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhiwuduotai.top/Article/details/gt2oowjkmuw.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.jqgufenzy.top/Article/details/gt2retwxiom.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.gotoacloud.top/Article/details/gt2nustljwu.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.ehwqpu.com/Article/details/gt2ewjcetau.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.cdnleiting.top/Article/details/gt2epdnbihz.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.hysaishi.cn/Article/details/gt2cumdilxp.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.yj202588.top/Article/details/gt2cbeyvlwq.html

C#:   Process.Start("ls", "-l");
来源：http://dali.pengpengdd.cyou/Article/details/gt2zutwwrob.html

[M04] 获取当前工作目录
来源：http://dali.pycfn.com/Article/details/gt2gfvqrwgy.html

Py:   os.getcwd()
来源：http://dali.hnxiangtu.top/Article/details/gt2mgkqngat.html

PHP:  getcwd();
来源：http://dali.nanxuanxn.top/Article/details/gt2trfvcgps.html

JS:   process.cwd()
来源：http://dali.gaohongyu789.top/Article/details/gt2qblleolq.html

TS:   process.cwd()
来源：http://dali.quarkkingdee.top/Article/details/gt2ccdpbuiq.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhixingplan.top/Article/details/gt2bmwtrbaw.html

Go:   os.Getwd()
来源：http://dali.kuanghao11.cn/Article/details/gt2dapellxa.html

Ruby: Dir.pwd
来源：http://dali.zhongyouzk.top/Article/details/gt2otsivgmp.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhoulong.xyz/Article/details/gt2haemojyd.html

[M05] 设置退出码
来源：http://dali.yuxming.cn/Article/details/gt2hpzsqnfq.html

Py:   sys.exit(1)
来源：http://dali.yueranfly.top/Article/details/gt2iicuvzsx.html

PHP:  exit(1);
来源：http://dali.wangshuangyany.cn/Article/details/gt2shfheyrq.html

JS:   process.exit(1)
来源：http://dali.pycfn.com/Article/details/gt2rdcevhlp.html

TS:   process.exit(1)
来源：http://dali.nanxinkj.top/Article/details/gt2bjlyrsdv.html

Java: System.exit(1)
来源：http://dali.chenzaomai.com/Article/details/gt2kbizatrx.html

Go:   os.Exit(1)
来源：http://dali.hammf.cn/Article/details/gt2rwohlujq.html

Ruby: exit 1
来源：http://dali.gogol.net.cn/Article/details/gt2tsladnpc.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.svipenyu.cn/Article/details/gt2epzybtxu.html

[M06] 向标准错误输出
来源：http://dali.fzhhl.top/Article/details/gt2gsgkndxf.html

Py:   print("err", file=sys.stderr)
来源：http://dali.birdmap.top/Article/details/gt2uthouigd.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.wangdashe.top/Article/details/gt2jnbbmujn.html

JS:   console.error("err")
来源：http://dali.ydzc1.top/Article/details/gt2hridpnjs.html

TS:   console.error("err")
来源：http://dali.wangshuangyany.cn/Article/details/gt2kpbpkres.html

Java: System.err.println("err")
来源：http://dali.shzxlz.cn/Article/details/gt2wsvtbqxg.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.svipenyu.cn/Article/details/gt2rgajbijx.html

Ruby: warn "err"
来源：http://dali.hnqzz.top/Article/details/gt2tabgiwwk.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.cashguo.top/Article/details/gt2hioodcwj.html

[M07] 判断是否为主入口
来源：http://dali.nanxinkj.top/Article/details/gt2efbvlaaw.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2rvrrofur.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.svipenyu.cn/Article/details/gt2tupcwwln.html

JS:   require.main === module
来源：http://dali.sxryk.cn/Article/details/gt2wbrvlgsv.html

TS:   require.main === module
来源：http://dali.iojbl.cn/Article/details/gt2edknxpiy.html

Java: public static void main(String[] args)
来源：http://dali.chenzaomai.com/Article/details/gt2dsxcziow.html

Go:   func main()
来源：http://dali.xuetiantiany.cn/Article/details/gt2kzajtfro.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.9152youxi.cn/Article/details/gt2juxlszjl.html

C#:   static void Main(string[] args)
来源：http://dali.jinqigufen.top/Article/details/gt2uvaijwpa.html

[M08] 获取系统与运行时信息
来源：http://dali.c1oappe.top/Article/details/gt2lcnhqjfu.html

Py:   platform.system();  platform.python_version()
来源：http://dali.cashguo.top/Article/details/gt2kqxwndsp.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.ehwqpu.com/Article/details/gt2ytuwkgax.html

JS:   process.platform;  process.version
来源：http://dali.jqgfzy.top/Article/details/gt2hjfyruwl.html

TS:   process.platform;  process.version
来源：http://dali.c1oappe.top/Article/details/gt2hdxzfoxs.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhongyouzk.top/Article/details/gt2wqowcdnv.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.cqqwz.cn/Article/details/gt2gkccizsd.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.yuanzhike.top/Article/details/gt2kulynmbh.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zdqjudy.top/Article/details/gt2bjnjxznh.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gt2jcmcgbyw.html

N. 数据结构与算法
来源：http://dali.hnqzz.top/Article/details/gt2rkswuysu.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gt2bcjnifoa.html

[N01] 二分查找（有序数组）
来源：http://dali.zhixingplan.top/Article/details/gt2iouzrfqp.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.nanxuanxn.top/Article/details/gt2mlpjpqdg.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.ydzc1.top/Article/details/gt2bwnvvklc.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhoulong.xyz/Article/details/gt2mmfrrjzh.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.pengpengdd.cyou/Article/details/gt2xwsrxhrc.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.yj20258888.top/Article/details/gt2izsqxrpm.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.nanxuanxn.top/Article/details/gt2aoquvxad.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.wangdashe.top/Article/details/gt2fvkitezg.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.smart0.xyz/Article/details/gt2umdfqxoa.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.wangdashe.top/Article/details/gt2zfsagxjr.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.tian-w.cn/Article/details/gt2kihvwgpz.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.pengpengdd.cyou/Article/details/gt2wwagjqdn.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.gzhubu.top/Article/details/gt2krwzrppt.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.dashuyun.cn/Article/details/gt2mebshbfo.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.hywenlv.cn/Article/details/gt2ltmkmjpr.html

Go:   slices.Sort(arr)
来源：http://dali.fengsongda.top/Article/details/gt2rlhlrwti.html

Ruby: arr.sort
来源：http://dali.haohaochexian.top/Article/details/gt2uofekdvp.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.smart0.xyz/Article/details/gt2ejymbdya.html

[N03] 快速排序（分治示例）
来源：http://dali.haohaochexian.top/Article/details/gt2wddiunmc.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.ehwqpu.com/Article/details/gt2bdjedgjx.html

PHP:  // 递归实现，或用 usort
来源：http://dali.cheryme.top/Article/details/gt2wqzndlak.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.ivvv.top/Article/details/gt2aepbdyri.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.dashuyun.cn/Article/details/gt2tlcnzpod.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nzfymuhx.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cjhzadxh.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.hammf.cn/Article/details/gt2wvgsllhp.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.hongshengwenyu.top/Article/details/gt2bzpehewj.html

[N04] 斐波那契数列
来源：http://dali.yonumen.top/Article/details/gt2hrtibkof.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.redwolf501.top/Article/details/gt2hhixsvjx.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.gaohongyu789.top/Article/details/gt2toxvgrfl.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.wangshuangyany.cn/Article/details/gt2gsfzabpv.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.cheryme.top/Article/details/gt2nwftbwph.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.daxiang520.top/Article/details/gt2sacmyrce.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.cheryme.top/Article/details/gt2lhocllmy.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.yangfankeji.com/Article/details/gt2xhpenays.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.andypj.xyz/Article/details/gt2thsylgxb.html

[N05] 最大公约数
来源：http://dali.meibo888.top/Article/details/gt2khimpasz.html

Py:   math.gcd(a, b)
来源：http://dali.chenlongwang.top/Article/details/gt2iqpqevbu.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.chenlongwang.top/Article/details/gt2lvmhilul.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hnqzz.top/Article/details/gt2kdteaxfk.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jyoumei.cn/Article/details/gt2zkdwilln.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.jiagoushi.top/Article/details/gt2vhxkixoi.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.smart0.xyz/Article/details/gt2hvbagirl.html

Ruby: a.gcd(b)
来源：http://dali.shuidangran.top/Article/details/gt2trdsveum.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nqrwmjji.html

[N06] 判断回文字符串
来源：http://dali.jqgufenzy.top/Article/details/gt2zvugklnf.html

Py:   s == s[::-1]
来源：http://dali.svipenyu.cn/Article/details/gt2logezcdj.html

PHP:  $s === strrev($s);
来源：http://dali.dashuyun.cn/Article/details/gt2axnryhwp.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zdqjudy.top/Article/details/gt2vzponqbw.html

TS:   s === [...s].reverse().join("")
来源：http://dali.xuetiantiany.cn/Article/details/gt2qlofyopw.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.0kj1m.cn/Article/details/gt2cdqlbjpz.html

Go:   // 双指针从两端比较
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nxyfjmoj.html

Ruby: s == s.reverse
来源：http://dali.chenzaomai.com/Article/details/gt2lltdfsjf.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mpitckbw.html

[N07] 两数之和（返回下标）
来源：http://dali.shuidangran.top/Article/details/gt2vdfapmft.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.daria6918.cn/Article/details/gt2hddcnyfs.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.feifeiyinyue.top/Article/details/gt2wttyplni.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.yj20258888.top/Article/details/gt2ixcjbqcc.html

TS:   // 手写 Map<string, number>
来源：http://dali.vqdsnc.cn/Article/details/gt2wvvwrrhv.html

Java: // 手写 HashMap
来源：http://dali.meibo888.top/Article/details/gt2erwdbppw.html

Go:   // 手写 map[int]int
来源：http://dali.wangshuangyany.cn/Article/details/gt2xiqwqucf.html

Ruby: // 手写 Hash
来源：http://dali.cashguo.top/Article/details/gt2tblbtmlq.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.fzhhl.top/Article/details/gt2rhpgldvk.html

[N08] 生成全排列
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fktxcsnc.html

Py:   itertools.permutations(arr)
来源：http://dali.cashguo.top/Article/details/gt2smzbgamj.html

PHP:  // 手写递归交换
来源：http://dali.cucudq.cn/Article/details/gt2lzhswtgj.html

JS:   // 手写回溯递归
来源：http://dali.haohaochexian.top/Article/details/gt2kbleedyn.html

TS:   // 手写回溯递归
来源：http://dali.xylfe.cn/Article/details/gt2jsvorrsv.html

Java: // 手写回溯递归
来源：http://dali.chenlongwang.top/Article/details/gt2vtlyklry.html

Go:   // 手写回溯递归
来源：http://dali.jinqigufen.top/Article/details/gt2hnkvajfh.html

Ruby: arr.permutation.to_a
来源：http://dali.quarkkingdee.top/Article/details/gt2ljumyydx.html

C#:   // 手写回溯递归
来源：http://dali.ivvv.top/Article/details/gt2vkgncyoo.html

[N09] 栈与队列
来源：http://dali.guannengcc.top/Article/details/gt2ssmgyhel.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.daria6918.cn/Article/details/gt2jexezcsl.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.fengsongda.top/Article/details/gt2oysmfzfb.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.xziqi.cn/Article/details/gt2tmctgvku.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.gogol.net.cn/Article/details/gt2vhebjwqy.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhongyouzk.top/Article/details/gt2bikagsio.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.ppjwa.cn/Article/details/gt2izxxvqfi.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.tianlin.xyz/Article/details/gt2ynhvpqqt.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.jqgfzy.top/Article/details/gt2rhkgaucz.html

[N10] 链表节点定义
来源：http://dali.dianchejie.cn/Article/details/gt2liqatils.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.xuanzx.com/Article/details/gt2xngqodnd.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.jqgfzy.top/Article/details/gt2wlfjnynq.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.sxryk.cn/Article/details/gt2zkmjduee.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.mhx1999.top/Article/details/gt2sbfocaek.html

Java: class Node { int v; Node next; }
来源：http://dali.shuidangran.top/Article/details/gt2qiekhuzi.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pvlwjbuq.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhengqikj.top/Article/details/gt2osuieemw.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.chenlongwang.top/Article/details/gt2ugvahehe.html

[N11] 二叉树中序遍历
来源：http://dali.zhongyouzk.top/Article/details/gt2znogpmcz.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.xziqi.cn/Article/details/gt2phyakben.html

PHP:  // 手写递归函数
来源：http://dali.aibaodan.cn/Article/details/gt2cczlkbzu.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.chenlongwang.top/Article/details/gt2rfcamlqb.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.gaohongyu789.top/Article/details/gt2mvutlvlx.html

Java: // 手写递归
来源：http://dali.hammf.cn/Article/details/gt2qrgncnxg.html

Go:   // 手写递归
来源：http://dali.yvedp.cn/Article/details/gt2jtulgzfx.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.daxiang520.top/Article/details/gt2iiatbbxn.html

C#:   // 手写递归
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uzwsgvym.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.redwolf501.top/Article/details/gt2vvxrfztv.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.ybcxt.top/Article/details/gt2nlgxzxyx.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.daxiang520.top/Article/details/gt2yibcthmn.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.chenzaomai.com/Article/details/gt2ywqekcld.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.snrcjt.cn/Article/details/gt2laonhlgk.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.pengpengdd.cyou/Article/details/gt2yjvdwhbk.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.hammf.cn/Article/details/gt2rqigyzjo.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.xinyue.icu/Article/details/gt2rkgzemmp.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhengqikj.top/Article/details/gt2yjawvwre.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gt2gmyhwwns.html

O. 并发与异步
来源：http://dali.yvedp.cn/Article/details/gt2hzxtyryd.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gt2aflwcgwz.html

[O01] 启动一个线程
来源：http://dali.yuanzhike.top/Article/details/gt2cqotubag.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.ehwqpu.com/Article/details/gt2kvkspzta.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.316326.xyz/Article/details/gt2tqydhyua.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.yj202588.top/Article/details/gt2eipkwcfj.html

TS:   // 同 JS
来源：http://dali.sufxvd.cn/Article/details/gt2bktjcyvv.html

Java: new Thread(() -> f()).start()
来源：http://dali.yanxiufei.cn/Article/details/gt2clyvtcah.html

Go:   go f()
来源：http://dali.sweek.top/Article/details/gt2mkscjuyz.html

Ruby: Thread.new { f }
来源：http://dali.0kj1m.cn/Article/details/gt2wkyqjgzg.html

C#:   Task.Run(() => F());
来源：http://dali.jiagoushi.top/Article/details/gt2kyxhgjgn.html

[O02] 使用线程池
来源：http://dali.shzxlz.cn/Article/details/gt2makvfrxm.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.pengpengdd.cyou/Article/details/gt2czhpjkfr.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.tanke756.top/Article/details/gt2dkgxpgkp.html

JS:   // worker_threads 线程池
来源：http://dali.yanxiufei.cn/Article/details/gt2dhvqjfeg.html

TS:   // worker_threads 线程池
来源：http://dali.jyoumei.cn/Article/details/gt2epygfimo.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.jqgfzy.top/Article/details/gt2crqefpga.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.xylfe.cn/Article/details/gt2febbilyk.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.hnqzz.top/Article/details/gt2wokwsssr.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.gogol.net.cn/Article/details/gt2fwichuqt.html

[O03] 加锁保护共享数据
来源：http://dali.zhixingplan.top/Article/details/gt2ivufgwdo.html

Py:   with lock: shared += 1
来源：http://dali.cucudq.cn/Article/details/gt2lzstqhvi.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.aizwys.cn/Article/details/gt2ecpnmypl.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.jianghu66.top/Article/details/gt2jodgvmkz.html

TS:   // 同 JS
来源：http://dali.ydzc1.top/Article/details/gt2bezhguuw.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhengqikj.top/Article/details/gt2wgksnfke.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.hywenlv.cn/Article/details/gt2opevyvzp.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.vqdsnc.cn/Article/details/gt2jqghppxq.html

C#:   lock (gate) { shared++; }
来源：http://dali.c1oappe.top/Article/details/gt2yyrgtxat.html

[O04] 定义异步函数并等待
来源：http://dali.guannengcc.top/Article/details/gt2cyzwzuvz.html

Py:   async def f():⏎    await g()
来源：http://dali.hongshengwenyu.top/Article/details/gt2jdqrbpjo.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.gotoacloud.top/Article/details/gt2osdyunpv.html

JS:   async function f() { await g(); }
来源：http://dali.pengpengdd.cyou/Article/details/gt2bggooiks.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.yueranfly.top/Article/details/gt2tmtbwafa.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.jinqigufen.top/Article/details/gt2lhrsrrpn.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.hongshengwenyu.top/Article/details/gt2imofivqk.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.daxiang520.top/Article/details/gt2epaoufvu.html

C#:   async Task F() { await G(); }
来源：http://dali.haohaochexian.top/Article/details/gt2uhriczih.html

[O05] 并发执行并等待全部完成
来源：http://dali.316326.xyz/Article/details/gt2mrooefjb.html

Py:   asyncio.gather(*tasks)
来源：http://dali.cdnleiting.top/Article/details/gt2gbtecgjg.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.iojbl.cn/Article/details/gt2qapnnbup.html

JS:   await Promise.all(tasks)
来源：http://dali.andypj.xyz/Article/details/gt2fppbltgp.html

TS:   await Promise.all(tasks)
来源：http://dali.meibo888.top/Article/details/gt2irplbsim.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhoulong.xyz/Article/details/gt2srvflfjq.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.hongshengwenyu.top/Article/details/gt2jcjanpjp.html

Ruby: threads.map(&:join)
来源：http://dali.chenzaomai.com/Article/details/gt2fxcmvvwh.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.snrcjt.cn/Article/details/gt2vydfcgut.html

[O06] 使用进程池
来源：http://dali.daxiang520.top/Article/details/gt2tvoehodt.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.yuxming.cn/Article/details/gt2ucstyfbv.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.yuanzhike.top/Article/details/gt2gwfmdhby.html

JS:   // child_process / cluster 模块
来源：http://dali.guowangkeji.top/Article/details/gt2zivwiifi.html

TS:   // child_process / cluster 模块
来源：http://dali.9152youxi.cn/Article/details/gt2tfpxxtrg.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.ehwqpu.com/Article/details/gt2idlixchn.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.guowangkeji.top/Article/details/gt2dzcvunaw.html

Ruby: // fork 块
来源：http://dali.iojbl.cn/Article/details/gt2wpgnejhz.html

C#:   Parallel.For
来源：http://dali.redwolf501.top/Article/details/gt2yntuleke.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gt2jelssbno.html

P. 常用工具函数
来源：http://dali.gotoacloud.top/Article/details/gt2ovtlcpnr.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gt2qjabvbtg.html

[P01] 生成 UUID
来源：http://dali.jqgufenzy.top/Article/details/gt2wdpgmovh.html

Py:   str(uuid.uuid4())
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dbjgfyvo.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.haohaochexian.top/Article/details/gt2jwvgmbnn.html

JS:   crypto.randomUUID()
来源：http://dali.cqqwz.cn/Article/details/gt2tivtwpit.html

TS:   crypto.randomUUID()
来源：http://dali.yj202588.top/Article/details/gt2ylumxmmq.html

Java: UUID.randomUUID().toString()
来源：http://dali.xziqi.cn/Article/details/gt2fvqkdgoc.html

Go:   // 用 github.com/google/uuid
来源：http://dali.yuxming.cn/Article/details/gt2vybogaqh.html

Ruby: SecureRandom.uuid
来源：http://dali.shangyingyoupin.top/Article/details/gt2ubzffokp.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.dianchejie.cn/Article/details/gt2nupenytu.html

[P02] MD5 / SHA256 摘要
来源：http://dali.mhx1999.top/Article/details/gt2yxvckdqy.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.9152youxi.cn/Article/details/gt2lsmasxjt.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ovqtfssf.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.yongpay.top/Article/details/gt2pzeexoyh.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.hfpthk.cn/Article/details/gt2ndlesrwc.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.jyoumei.cn/Article/details/gt2puifhzum.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.ivvv.top/Article/details/gt2hvgpyivf.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.dashuyun.cn/Article/details/gt2hcrdqpdn.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.sysykeji.top/Article/details/gt2dviwzrdm.html

[P03] 生成短随机字符串
来源：http://dali.hongshengwenyu.top/Article/details/gt2sdxltolm.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.yonumen.top/Article/details/gt2sgwtrnic.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.nanxinkj.top/Article/details/gt2kauacwdg.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.smart0.xyz/Article/details/gt2mhofsvuj.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.quarkkingdee.top/Article/details/gt2sdprphgy.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.gzhubu.top/Article/details/gt2urjingom.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.ehwqpu.com/Article/details/gt2qlgwvxww.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.gzhubu.top/Article/details/gt2zqgcgydh.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.xuetiantiany.cn/Article/details/gt2knrubypv.html

[P04] 求长度
来源：http://dali.sxryk.cn/Article/details/gt2rfqxmsdv.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.cucudq.cn/Article/details/gt2dhozpted.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jqgfzy.top/Article/details/gt2qhyqlbge.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.gaohongyu789.top/Article/details/gt2uwicdgfi.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.jqgufenzy.top/Article/details/gt2bfoenzxa.html

Java: list.size();  map.size();  s.length()
来源：http://dali.andypj.xyz/Article/details/gt2recohngc.html

Go:   len(arr);  len(m)
来源：http://dali.hongshengwenyu.top/Article/details/gt2bwutkcmc.html

Ruby: x.length;  x.size
来源：http://dali.xylfe.cn/Article/details/gt2yoqepdbx.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.316326.xyz/Article/details/gt2nqlmnhyc.html

[P05] 判断两个对象内容是否相等
来源：http://dali.yj20258.top/Article/details/gt2mqvnuqab.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.birdmap.top/Article/details/gt2kozblzto.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.shanyushiyangtech.top/Article/details/gt2payjdbmv.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.sxryk.cn/Article/details/gt2cofwvsrf.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.tianlin.xyz/Article/details/gt2ymupicrv.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.cashguo.top/Article/details/gt2srrntkhd.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.shangyingyoupin.top/Article/details/gt2coevklmh.html

Ruby: a == b
来源：http://dali.birdmap.top/Article/details/gt2fwcpeuhx.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.hfpthk.cn/Article/details/gt2zcptqqia.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.yj202588.top/Article/details/gt2tmcetqsq.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.shangyingyoupin.top/Article/details/gt2azmmlzae.html

PHP:  if (empty($x)) {}
来源：http://dali.sufxvd.cn/Article/details/gt2ugdajryl.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.sxryk.cn/Article/details/gt2kqeuowrs.html

TS:   if (x == null) {}
来源：http://dali.xylfe.cn/Article/details/gt2spintykn.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2hnovaujy.html

Go:   if x == nil {}
来源：http://dali.hammf.cn/Article/details/gt2xclzpfxc.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.cucudq.cn/Article/details/gt2kwziszgh.html

C#:   if (x is null) {}
来源：http://dali.gogol.net.cn/Article/details/gt2pclamaee.html

[P07] 防抖与节流
来源：http://dali.tanke756.top/Article/details/gt2zyjdohyw.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.pycfn.com/Article/details/gt2ixqhodll.html

PHP:  // 手写时间戳比较
来源：http://dali.ydzc1.top/Article/details/gt2bexxqkav.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.guowangkeji.top/Article/details/gt2jvtcatzk.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yvedp.cn/Article/details/gt2oyuqxbgf.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.snrcjt.cn/Article/details/gt2cdmrglpc.html


<!-- 参考信息 -->