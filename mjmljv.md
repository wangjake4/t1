代发 wailian999

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtlgqzkfln.html

[M01] 读取命令行参数
来源：http://dali.shangyingyoupin.top/Article/details/gtkmmefajc.html

Py:   sys.argv[1:]
来源：http://dali.haohaochexian.top/Article/details/gtfywrpwns.html

PHP:  $argv;  $argc;
来源：http://dali.zhengqikj.top/Article/details/gtfsnjfxyn.html

JS:   process.argv.slice(2)
来源：http://dali.chenjidiqi.icu/Article/details/gtpzdpkgzs.html

TS:   process.argv.slice(2)
来源：http://dali.jinqigufen.top/Article/details/gtywrmyviy.html

Java: args 数组（main 方法参数）
来源：http://dali.hnxiangtu.top/Article/details/gtjtvxqpcq.html

Go:   os.Args[1:]
来源：http://dali.zhoulong.xyz/Article/details/gtobbtckao.html

Ruby: ARGV
来源：http://dali.ydzc1.top/Article/details/gtoamicdpg.html

C#:   args 数组（Main 方法参数）
来源：http://dali.yj20258888.top/Article/details/gthmixnnfp.html

[M02] 读取环境变量
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvdzpipsx.html

Py:   os.environ.get("HOME")
来源：http://dali.ybcxt.top/Article/details/gtlaxyepbz.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.316326.xyz/Article/details/gtnfrxryby.html

JS:   process.env.HOME
来源：http://dali.guowangkeji.top/Article/details/gtscvuqykf.html

TS:   process.env.HOME
来源：http://dali.bjfxy.top/Article/details/gtlvmsnsez.html

Java: System.getenv("HOME")
来源：http://dali.cashguo.top/Article/details/gtnzpihokf.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhaomingkeji.xyz/Article/details/gticiivkok.html

Ruby: ENV["HOME"]
来源：http://dali.guowangkeji.top/Article/details/gthintsylk.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.sufxvd.cn/Article/details/gtfkqhxrcw.html

[M03] 执行外部命令
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvtgasefz.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhiwuduotai.top/Article/details/gtwltltour.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.wangshuangyany.cn/Article/details/gtiaxydznn.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhoulong.xyz/Article/details/gthmptyjls.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.shzxlz.cn/Article/details/gtvqvjrwdj.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gtrkknqurd.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.yueranfly.top/Article/details/gtyjqljpys.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.jiagoushi.top/Article/details/gtcemzxqlu.html

C#:   Process.Start("ls", "-l");
来源：http://dali.gaohongyu789.top/Article/details/gtigusneee.html

[M04] 获取当前工作目录
来源：http://dali.nanxuanxn.top/Article/details/gtkbppdmyp.html

Py:   os.getcwd()
来源：http://dali.hnqzz.top/Article/details/gtxqzaloex.html

PHP:  getcwd();
来源：http://dali.hammf.cn/Article/details/gtyboknyat.html

JS:   process.cwd()
来源：http://dali.birdmap.top/Article/details/gtdurazrxf.html

TS:   process.cwd()
来源：http://dali.shzxlz.cn/Article/details/gtrthlisms.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.chenzaomai.com/Article/details/gtyqpdlspv.html

Go:   os.Getwd()
来源：http://dali.nanxinkj.top/Article/details/gtxrhcntgf.html

Ruby: Dir.pwd
来源：http://dali.hnxiangtu.top/Article/details/gtalkmfpdd.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.0kj1m.cn/Article/details/gtgfrtrbrx.html

[M05] 设置退出码
来源：http://dali.snrcjt.cn/Article/details/gthdaevatp.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gtkhgxtfeb.html

PHP:  exit(1);
来源：http://dali.fengsongda.top/Article/details/gtlrklndgp.html

JS:   process.exit(1)
来源：http://dali.tianlin.xyz/Article/details/gtuvqbjhpx.html

TS:   process.exit(1)
来源：http://dali.hywenlv.cn/Article/details/gttnfndjmy.html

Java: System.exit(1)
来源：http://dali.cqqwz.cn/Article/details/gtuxecsgqy.html

Go:   os.Exit(1)
来源：http://dali.hywenlv.cn/Article/details/gtitaadzzo.html

Ruby: exit 1
来源：http://dali.cqqwz.cn/Article/details/gtulwettsr.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.snrcjt.cn/Article/details/gtjcauyjbx.html

[M06] 向标准错误输出
来源：http://dali.tanke756.top/Article/details/gtougglrri.html

Py:   print("err", file=sys.stderr)
来源：http://dali.chenzaomai.com/Article/details/gtmiciedey.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.jyoumei.cn/Article/details/gtcejgdpey.html

JS:   console.error("err")
来源：http://dali.nanxuanxn.top/Article/details/gtihrlzzim.html

TS:   console.error("err")
来源：http://dali.gogol.net.cn/Article/details/gtaprvhizm.html

Java: System.err.println("err")
来源：http://dali.yuanzhike.top/Article/details/gtdftobhib.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.hammf.cn/Article/details/gtikidhvrh.html

Ruby: warn "err"
来源：http://dali.shangyingyoupin.top/Article/details/gtxtcogwtw.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.birdmap.top/Article/details/gtyuudekmx.html

[M07] 判断是否为主入口
来源：http://dali.zhongyouzk.top/Article/details/gtpjsluuvp.html

Py:   if __name__ == "__main__":
来源：http://dali.zdqjudy.top/Article/details/gtlhopexpt.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.dashuyun.cn/Article/details/gtrsxwabdn.html

JS:   require.main === module
来源：http://dali.gaohongyu789.top/Article/details/gtoceatmyk.html

TS:   require.main === module
来源：http://dali.shanyushiyangkeji.top/Article/details/gthwqzfbia.html

Java: public static void main(String[] args)
来源：http://dali.yj20258888.top/Article/details/gtjlvzifus.html

Go:   func main()
来源：http://dali.hnqzz.top/Article/details/gtjcuojlbp.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.chenjidiqi.icu/Article/details/gthsfamajy.html

C#:   static void Main(string[] args)
来源：http://dali.daria6918.cn/Article/details/gtgtdsncif.html

[M08] 获取系统与运行时信息
来源：http://dali.gotoacloud.top/Article/details/gtufkbthrw.html

Py:   platform.system();  platform.python_version()
来源：http://dali.gaohongyu789.top/Article/details/gtpuhjymff.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.feifeiyinyue.top/Article/details/gtuxxuwolk.html

JS:   process.platform;  process.version
来源：http://dali.nanxuanxn.top/Article/details/gtmkazlvlh.html

TS:   process.platform;  process.version
来源：http://dali.quarkkingdee.top/Article/details/gtzonddenv.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.yvedp.cn/Article/details/gtdohoqded.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.jinqigfzy.top/Article/details/gtduaxegkb.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvlfvqrnr.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.ivvv.top/Article/details/gtcpxbygir.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtsanvyrgg.html

N. 数据结构与算法
来源：http://dali.meibo888.top/Article/details/gtvbfcbdkl.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtnxuusvtt.html

[N01] 二分查找（有序数组）
来源：http://dali.jinghuilouyu.cn/Article/details/gtbnxdzlye.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhongyouzk.top/Article/details/gtberijdxv.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcqnptoil.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfauctjse.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.chenlongwang.top/Article/details/gtxcojrbjw.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.yonumen.top/Article/details/gtqscsmnud.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.hammf.cn/Article/details/gtmieeyusm.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.gaohongyu789.top/Article/details/gtagkpzqgs.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.birdmap.top/Article/details/gtyeowecat.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnpxitomv.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.nanxuanxn.top/Article/details/gtbbzbzbph.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.tian-w.cn/Article/details/gtdsxyrubc.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhixingplan.top/Article/details/gtwistotry.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jqgufenzy.top/Article/details/gtsfjsuhvd.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.cashguo.top/Article/details/gtxghyxkat.html

Go:   slices.Sort(arr)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnbljkdsr.html

Ruby: arr.sort
来源：http://dali.fengsongda.top/Article/details/gttyzrontg.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.dashuyun.cn/Article/details/gtykqpcjsi.html

[N03] 快速排序（分治示例）
来源：http://dali.jinqigfzy.top/Article/details/gtmkpuckwi.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.kuanghao11.cn/Article/details/gtwxvtidwj.html

PHP:  // 递归实现，或用 usort
来源：http://dali.dashuyun.cn/Article/details/gtujjszgct.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.guowangkeji.top/Article/details/gtiaqtmgeh.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.hammf.cn/Article/details/gtyjoblefi.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.haohaochexian.top/Article/details/gtnzqhjiof.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.sxryk.cn/Article/details/gtstisluax.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.pycfn.com/Article/details/gtnnkhprgz.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.gaohongyu789.top/Article/details/gtkrejsyxg.html

[N04] 斐波那契数列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthkdtjroi.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.andypj.xyz/Article/details/gtwbqkvxaf.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.yueranfly.top/Article/details/gtwddhcilh.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.meibo888.top/Article/details/gthvavbrhw.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zdqjudy.top/Article/details/gtuyjhgbkn.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.xuetiantiany.cn/Article/details/gtsxfipezw.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.chenlongwang.top/Article/details/gtveayhngx.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.cqqwz.cn/Article/details/gtuiibnikp.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.nwbrower.top/Article/details/gtvbikobgp.html

[N05] 最大公约数
来源：http://dali.yongpay.top/Article/details/gtskbkiqfs.html

Py:   math.gcd(a, b)
来源：http://dali.guannengcc.top/Article/details/gtlirulpar.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.yuxming.cn/Article/details/gtlhlpuqic.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.feifeiyinyue.top/Article/details/gtqrekgknp.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hnxiangtu.top/Article/details/gthmgljsxv.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.aizwys.cn/Article/details/gtajafosye.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.nwbrower.top/Article/details/gtodofamfu.html

Ruby: a.gcd(b)
来源：http://dali.yj20258.top/Article/details/gtlhrbrjsb.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.jqgfzy.top/Article/details/gtkcvxeiyo.html

[N06] 判断回文字符串
来源：http://dali.jqgufenzy.top/Article/details/gtgfezwzys.html

Py:   s == s[::-1]
来源：http://dali.tanke756.top/Article/details/gtvfxensii.html

PHP:  $s === strrev($s);
来源：http://dali.yueranfly.top/Article/details/gtjnnlsydi.html

JS:   s === [...s].reverse().join("")
来源：http://dali.tianlin.xyz/Article/details/gtkombxkij.html

TS:   s === [...s].reverse().join("")
来源：http://dali.chenjidiqi.icu/Article/details/gthokykrsy.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.shuidangran.top/Article/details/gtuhnvcctu.html

Go:   // 双指针从两端比较
来源：http://dali.pengpengdd.cyou/Article/details/gtixdxjhii.html

Ruby: s == s.reverse
来源：http://dali.tianlin.xyz/Article/details/gtvlxcdoxs.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.redwolf501.top/Article/details/gtwiqhbxio.html

[N07] 两数之和（返回下标）
来源：http://dali.guannengcc.top/Article/details/gttbkxqnka.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.chenlongwang.top/Article/details/gtgcihslpd.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.tanke756.top/Article/details/gtvrussnew.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.jinqigfzy.top/Article/details/gthuczjifa.html

TS:   // 手写 Map<string, number>
来源：http://dali.nanxuanxn.top/Article/details/gtvaphsacq.html

Java: // 手写 HashMap
来源：http://dali.sweek.top/Article/details/gtjgjldxds.html

Go:   // 手写 map[int]int
来源：http://dali.ppjwa.cn/Article/details/gtxnsbyvpt.html

Ruby: // 手写 Hash
来源：http://dali.yongpay.top/Article/details/gtiyolwcyw.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.havefunace.top/Article/details/gtdduwigtd.html

[N08] 生成全排列
来源：http://dali.hnxiangtu.top/Article/details/gtpgzjumyd.html

Py:   itertools.permutations(arr)
来源：http://dali.vqdsnc.cn/Article/details/gtahqnuskh.html

PHP:  // 手写递归交换
来源：http://dali.shanyushiyangkeji.top/Article/details/gttuuivyjy.html

JS:   // 手写回溯递归
来源：http://dali.shanyushiyangtech.top/Article/details/gtwneticiv.html

TS:   // 手写回溯递归
来源：http://dali.xylfe.cn/Article/details/gtkxawtzqz.html

Java: // 手写回溯递归
来源：http://dali.xuetiantiany.cn/Article/details/gtadoifxqf.html

Go:   // 手写回溯递归
来源：http://dali.pycfn.com/Article/details/gtgyatojiv.html

Ruby: arr.permutation.to_a
来源：http://dali.hnqzz.top/Article/details/gtfoheqjpu.html

C#:   // 手写回溯递归
来源：http://dali.hongshengwenyu.top/Article/details/gtbbhnykao.html

[N09] 栈与队列
来源：http://dali.kuanghao11.cn/Article/details/gtceouwofj.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.cucudq.cn/Article/details/gtukluzyou.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.gaohongyu789.top/Article/details/gtavukuyel.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.smart0.xyz/Article/details/gtqwjicmjl.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.cqqwz.cn/Article/details/gtnqfaopeg.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.xinyue.icu/Article/details/gtopdkxjdg.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.kuanghao11.cn/Article/details/gtjjjuilpd.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.nwbrower.top/Article/details/gtzoyozdkj.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.yuxming.cn/Article/details/gtibogtqjj.html

[N10] 链表节点定义
来源：http://dali.tianlin.xyz/Article/details/gtcoalouhg.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.hysaishi.cn/Article/details/gtcirawtde.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.aizwys.cn/Article/details/gtiubdpesy.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.cucudq.cn/Article/details/gtdxbqucod.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.yj202588.top/Article/details/gtochfjxcg.html

Java: class Node { int v; Node next; }
来源：http://dali.tian-w.cn/Article/details/gtmkcotjjd.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.jinqigfzy.top/Article/details/gtcaydgkkp.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.ivvv.top/Article/details/gtyzzhdwnn.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.cucudq.cn/Article/details/gtscbejdpj.html

[N11] 二叉树中序遍历
来源：http://dali.ivvv.top/Article/details/gtotxyrpse.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.sxryk.cn/Article/details/gtpkrokepv.html

PHP:  // 手写递归函数
来源：http://dali.jiagoushi.top/Article/details/gtnxrjlqtm.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.hnqzz.top/Article/details/gtnxuxruqh.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.guannengcc.top/Article/details/gtrankzrur.html

Java: // 手写递归
来源：http://dali.gotoacloud.top/Article/details/gtyiaaxsje.html

Go:   // 手写递归
来源：http://dali.yj20258888.top/Article/details/gtehnmbxdz.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.wangdashe.top/Article/details/gtgzcibjka.html

C#:   // 手写递归
来源：http://dali.daria6918.cn/Article/details/gtgbcukvhm.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.nanxuanxn.top/Article/details/gtehjixcfz.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.yueranfly.top/Article/details/gtrbrvqsyw.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.birdmap.top/Article/details/gtywabyfgp.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.chenlongwang.top/Article/details/gtqufdkghg.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yj20258888.top/Article/details/gtuqwyokiy.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.cheryme.top/Article/details/gtyvjsuyzm.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.guannengcc.top/Article/details/gtdsmdutss.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.smart0.xyz/Article/details/gtnsacrqja.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.gzhubu.top/Article/details/gtuuusnwpi.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtkwnwffdo.html

O. 并发与异步
来源：http://dali.sufxvd.cn/Article/details/gtejyvnnyu.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtgjjgjvkf.html

[O01] 启动一个线程
来源：http://dali.hfpthk.cn/Article/details/gtsreybqoz.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.smart0.xyz/Article/details/gtbhzhnmfk.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.hongshengwenyu.top/Article/details/gtwhvbplxz.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.jinghuilouyu.cn/Article/details/gtknlipxid.html

TS:   // 同 JS
来源：http://dali.chenjidiqi.icu/Article/details/gtpxoglycr.html

Java: new Thread(() -> f()).start()
来源：http://dali.guannengcc.top/Article/details/gtrwvhxhkr.html

Go:   go f()
来源：http://dali.pengpengdd.cyou/Article/details/gttvsflkfg.html

Ruby: Thread.new { f }
来源：http://dali.havefunace.top/Article/details/gtmsliimxu.html

C#:   Task.Run(() => F());
来源：http://dali.xuetiantiany.cn/Article/details/gtzkmrwttq.html

[O02] 使用线程池
来源：http://dali.nwbrower.top/Article/details/gtfnhrjklp.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.gotoacloud.top/Article/details/gttddoaqgj.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.tianlin.xyz/Article/details/gtmnszxknd.html

JS:   // worker_threads 线程池
来源：http://dali.hongshengwenyu.top/Article/details/gtnsueqfmj.html

TS:   // worker_threads 线程池
来源：http://dali.ywan-chungtsiang.top/Article/details/gtygsdjrsr.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.meibo888.top/Article/details/gtbkxlzkjc.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.jinghuilouyu.cn/Article/details/gtfycupqxi.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.ehwqpu.com/Article/details/gtmkwixilr.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.wangdashe.top/Article/details/gtdwhdcytg.html

[O03] 加锁保护共享数据
来源：http://dali.meibo888.top/Article/details/gtcsocnbnq.html

Py:   with lock: shared += 1
来源：http://dali.yueranfly.top/Article/details/gtfssuiych.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.cashguo.top/Article/details/gtyatwmbfp.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gtvftxzwwt.html

TS:   // 同 JS
来源：http://dali.sweek.top/Article/details/gtfkjaqudj.html

Java: synchronized (this) { shared++; }
来源：http://dali.tanke756.top/Article/details/gtypmcelri.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.iojbl.cn/Article/details/gtxfscditf.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.jqgufenzy.top/Article/details/gtqiawlocg.html

C#:   lock (gate) { shared++; }
来源：http://dali.guannengcc.top/Article/details/gtwcxltema.html

[O04] 定义异步函数并等待
来源：http://dali.tanke756.top/Article/details/gtyxxfrjck.html

Py:   async def f():⏎    await g()
来源：http://dali.xziqi.cn/Article/details/gtxvswvpqb.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.ybcxt.top/Article/details/gttgwmqyfe.html

JS:   async function f() { await g(); }
来源：http://dali.nanxuanxn.top/Article/details/gtogbtaimq.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.316326.xyz/Article/details/gtomttpwbw.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.mhx1999.top/Article/details/gtnebjmurv.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gtcojzddip.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.gzhubu.top/Article/details/gtzebrugcn.html

C#:   async Task F() { await G(); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpisibxvb.html

[O05] 并发执行并等待全部完成
来源：http://dali.hnqzz.top/Article/details/gtjdpvifwf.html

Py:   asyncio.gather(*tasks)
来源：http://dali.yangfankeji.com/Article/details/gtnlmvbdln.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.yangfankeji.com/Article/details/gtfujrpzdq.html

JS:   await Promise.all(tasks)
来源：http://dali.ivvv.top/Article/details/gtsojhjqzk.html

TS:   await Promise.all(tasks)
来源：http://dali.0kj1m.cn/Article/details/gtlmoldqqk.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.yuanzhike.top/Article/details/gtenoakqqw.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.nwbrower.top/Article/details/gtghppyrys.html

Ruby: threads.map(&:join)
来源：http://dali.aibaodan.cn/Article/details/gtjylyhkpl.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.sufxvd.cn/Article/details/gttebosacz.html

[O06] 使用进程池
来源：http://dali.yvedp.cn/Article/details/gtauxlgeou.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.ehwqpu.com/Article/details/gtrgspmjnl.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhixingplan.top/Article/details/gtumlehxkg.html

JS:   // child_process / cluster 模块
来源：http://dali.gaohongyu789.top/Article/details/gtgwpmzrpy.html

TS:   // child_process / cluster 模块
来源：http://dali.xylfe.cn/Article/details/gtzhwujgnp.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.c1oappe.top/Article/details/gtmxayoxdj.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.hongshengwenyu.top/Article/details/gtklvadlcf.html

Ruby: // fork 块
来源：http://dali.xziqi.cn/Article/details/gtekhkjiev.html

C#:   Parallel.For
来源：http://dali.jlsjyb.cn/Article/details/gtkhoaqlcw.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtjrqteoru.html

P. 常用工具函数
来源：http://dali.jlsjyb.cn/Article/details/gtjgzdtmrk.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtlalkcpak.html

[P01] 生成 UUID
来源：http://dali.wangdashe.top/Article/details/gtniecxxeo.html

Py:   str(uuid.uuid4())
来源：http://dali.jyoumei.cn/Article/details/gtrwqtnuin.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.sufxvd.cn/Article/details/gtyjslacmd.html

JS:   crypto.randomUUID()
来源：http://dali.yanxiufei.cn/Article/details/gtoxskwumh.html

TS:   crypto.randomUUID()
来源：http://dali.jinghuilouyu.cn/Article/details/gtfjpbgzir.html

Java: UUID.randomUUID().toString()
来源：http://dali.yuanzhike.top/Article/details/gtwxmtnbbf.html

Go:   // 用 github.com/google/uuid
来源：http://dali.feifeiyinyue.top/Article/details/gtifwftlix.html

Ruby: SecureRandom.uuid
来源：http://dali.hywenlv.cn/Article/details/gthkpnssex.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhoulong.xyz/Article/details/gtsfhoxqpb.html

[P02] MD5 / SHA256 摘要
来源：http://dali.feifeiyinyue.top/Article/details/gtymyovgvw.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.daxiang520.top/Article/details/gtfwaelirg.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.ywan-chungtsiang.top/Article/details/gttyusjigv.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.yj20258.top/Article/details/gtbpsiybto.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.cdnleiting.top/Article/details/gtqewaxbkx.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.xinyue.icu/Article/details/gtwoeaabew.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.gzhubu.top/Article/details/gtnswxwpof.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.316326.xyz/Article/details/gtndkvgtam.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.snrcjt.cn/Article/details/gterscatze.html

[P03] 生成短随机字符串
来源：http://dali.cqqwz.cn/Article/details/gtgixpoxkp.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.chenzaomai.com/Article/details/gthnyldiwj.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.smart0.xyz/Article/details/gtkmiuxgfi.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.birdmap.top/Article/details/gtwkztzlnp.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhixingplan.top/Article/details/gtrmalvngq.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.bjfxy.top/Article/details/gtaocaapmo.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.cucudq.cn/Article/details/gtknqupcxz.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.xuetiantiany.cn/Article/details/gtmfyitobg.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.nwbrower.top/Article/details/gtttsaqgjz.html

[P04] 求长度
来源：http://dali.cheryme.top/Article/details/gtcqdfvjzo.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.yvedp.cn/Article/details/gtxemalsit.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.sysykeji.top/Article/details/gtgceatelj.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.c1oappe.top/Article/details/gtlnzvpggd.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.0kj1m.cn/Article/details/gtglfgvjen.html

Java: list.size();  map.size();  s.length()
来源：http://dali.nanxuanxn.top/Article/details/gtzuetihrd.html

Go:   len(arr);  len(m)
来源：http://dali.snrcjt.cn/Article/details/gtzncpuqem.html

Ruby: x.length;  x.size
来源：http://dali.jianghu66.top/Article/details/gtnigqzgtw.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.kuanghao11.cn/Article/details/gtcxzssdxn.html

[P05] 判断两个对象内容是否相等
来源：http://dali.jiagoushi.top/Article/details/gtbozqrpns.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.svipenyu.cn/Article/details/gtwhhibtzz.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.chenjidiqi.icu/Article/details/gtcxypuofd.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.shanyushiyangtech.top/Article/details/gtgkuffuey.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.shuidangran.top/Article/details/gtkgcxhqnl.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.daria6918.cn/Article/details/gterketkas.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.wangshuangyany.cn/Article/details/gtzxgvfwkh.html

Ruby: a == b
来源：http://dali.cheryme.top/Article/details/gtweynfhsa.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.andypj.xyz/Article/details/gtbyzswrqz.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.yj20258888.top/Article/details/gtmgkqlpun.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.mhx1999.top/Article/details/gtremgyeuk.html

PHP:  if (empty($x)) {}
来源：http://dali.cqqwz.cn/Article/details/gtebtlyhve.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.cheryme.top/Article/details/gtgcmpdmsw.html

TS:   if (x == null) {}
来源：http://dali.vqdsnc.cn/Article/details/gtncmbemwn.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.hammf.cn/Article/details/gtmebavqie.html

Go:   if x == nil {}
来源：http://dali.sxryk.cn/Article/details/gtreubnzix.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhongyouzk.top/Article/details/gtvxfdqidg.html

C#:   if (x is null) {}
来源：http://dali.zhongyouzk.top/Article/details/gtdzlhspsj.html

[P07] 防抖与节流
来源：http://dali.feifeiyinyue.top/Article/details/gtmzmiqspz.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.shuidangran.top/Article/details/gtfqsaxiif.html


<!-- 参考信息 -->