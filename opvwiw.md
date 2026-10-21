代发 wailian999

Ruby: ARGV
来源：http://dali.hammf.cn/Article/details/gtoqayhayq.html

C#:   args 数组（Main 方法参数）
来源：http://dali.cucudq.cn/Article/details/gtiqagbyba.html

[M02] 读取环境变量
来源：http://dali.zhiwuduotai.top/Article/details/gtahqlporw.html

Py:   os.environ.get("HOME")
来源：http://dali.sufxvd.cn/Article/details/gtzqjmhviq.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.smart0.xyz/Article/details/gtxqcmhzsb.html

JS:   process.env.HOME
来源：http://dali.wangshuangyany.cn/Article/details/gtjbqdvkmt.html

TS:   process.env.HOME
来源：http://dali.xziqi.cn/Article/details/gtikuxsskv.html

Java: System.getenv("HOME")
来源：http://dali.cheryme.top/Article/details/gtshdgggvk.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.yangfankeji.com/Article/details/gtwjawcmkv.html

Ruby: ENV["HOME"]
来源：http://dali.ybcxt.top/Article/details/gtflquxhcr.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.dashuyun.cn/Article/details/gtbnpqqyql.html

[M03] 执行外部命令
来源：http://dali.vqdsnc.cn/Article/details/gtjkzwmrok.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.cucudq.cn/Article/details/gtyvczjzet.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.sysykeji.top/Article/details/gtwwvpecoz.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrntbsjfi.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.tian-w.cn/Article/details/gtyucaezrc.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.xziqi.cn/Article/details/gtblxhcytd.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.yuanzhike.top/Article/details/gtvyelijdr.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.hysaishi.cn/Article/details/gtqdalhdwm.html

C#:   Process.Start("ls", "-l");
来源：http://dali.shzxlz.cn/Article/details/gtexzabupq.html

[M04] 获取当前工作目录
来源：http://dali.kuanghao11.cn/Article/details/gtawcuqwqz.html

Py:   os.getcwd()
来源：http://dali.chenjidiqi.icu/Article/details/gtqymletwa.html

PHP:  getcwd();
来源：http://dali.xuetiantiany.cn/Article/details/gtizaoxiii.html

JS:   process.cwd()
来源：http://dali.pengpengdd.cyou/Article/details/gtykrnivga.html

TS:   process.cwd()
来源：http://dali.zhiwuduotai.top/Article/details/gtejaugkbr.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.ehwqpu.com/Article/details/gtqoxxnowh.html

Go:   os.Getwd()
来源：http://dali.hnxiangtu.top/Article/details/gtvwhvylhb.html

Ruby: Dir.pwd
来源：http://dali.havefunace.top/Article/details/gtyfqwsapg.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.gaohongyu789.top/Article/details/gtgkusswil.html

[M05] 设置退出码
来源：http://dali.yangfankeji.com/Article/details/gtkgzgunep.html

Py:   sys.exit(1)
来源：http://dali.iojbl.cn/Article/details/gttbopvhfc.html

PHP:  exit(1);
来源：http://dali.jqgfzy.top/Article/details/gtiejukyzx.html

JS:   process.exit(1)
来源：http://dali.aibaodan.cn/Article/details/gtesjkhkzf.html

TS:   process.exit(1)
来源：http://dali.shangyingyoupin.top/Article/details/gtycbagiyd.html

Java: System.exit(1)
来源：http://dali.andypj.xyz/Article/details/gtspyvsghl.html

Go:   os.Exit(1)
来源：http://dali.jiagoushi.top/Article/details/gttsicvdix.html

Ruby: exit 1
来源：http://dali.jianghu66.top/Article/details/gtpcoubzyr.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtckndlhds.html

[M06] 向标准错误输出
来源：http://dali.ivvv.top/Article/details/gtnbvmwdaa.html

Py:   print("err", file=sys.stderr)
来源：http://dali.meibo888.top/Article/details/gtliyjqntw.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.yj20258888.top/Article/details/gtygyupoya.html

JS:   console.error("err")
来源：http://dali.jinqigfzy.top/Article/details/gtnzfulxlx.html

TS:   console.error("err")
来源：http://dali.hongshengwenyu.top/Article/details/gtulrhyavp.html

Java: System.err.println("err")
来源：http://dali.hongshengwenyu.top/Article/details/gtankobgqt.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.gzhubu.top/Article/details/gtbojdfamu.html

Ruby: warn "err"
来源：http://dali.ybcxt.top/Article/details/gthltptbqp.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.chenjidiqi.icu/Article/details/gtbllnbcfw.html

[M07] 判断是否为主入口
来源：http://dali.zycfv.cn/Article/details/gtgbmkdkjs.html

Py:   if __name__ == "__main__":
来源：http://dali.yonumen.top/Article/details/gtxjsfiacp.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zdqjudy.top/Article/details/gtbximpuyu.html

JS:   require.main === module
来源：http://dali.yongpay.top/Article/details/gtxiphaols.html

TS:   require.main === module
来源：http://dali.zdqjudy.top/Article/details/gtmlajrzpv.html

Java: public static void main(String[] args)
来源：http://dali.shuidangran.top/Article/details/gtftdhsshj.html

Go:   func main()
来源：http://dali.yueranfly.top/Article/details/gtavrufxwe.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.guowangkeji.top/Article/details/gtrwizgyyl.html

C#:   static void Main(string[] args)
来源：http://dali.dianchejie.cn/Article/details/gtzrzlcuqg.html

[M08] 获取系统与运行时信息
来源：http://dali.cqqwz.cn/Article/details/gtyruodlik.html

Py:   platform.system();  platform.python_version()
来源：http://dali.daxiang520.top/Article/details/gtsxxuvjwn.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.tanke756.top/Article/details/gtoirqipcs.html

JS:   process.platform;  process.version
来源：http://dali.9152youxi.cn/Article/details/gtdwsvwyyd.html

TS:   process.platform;  process.version
来源：http://dali.sysykeji.top/Article/details/gtelafxxbg.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.yongpay.top/Article/details/gtofuozgxk.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.0kj1m.cn/Article/details/gtjedlqrhp.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.pengpengdd.cyou/Article/details/gtihunbmqw.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.wangshuangyany.cn/Article/details/gtleovvlwe.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtucxklmxl.html

N. 数据结构与算法
来源：http://dali.hongshengwenyu.top/Article/details/gtrlgoilfx.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtmidfluzt.html

[N01] 二分查找（有序数组）
来源：http://dali.sxryk.cn/Article/details/gtaffwzhmx.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.yuxming.cn/Article/details/gtfgwkcwvl.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.sweek.top/Article/details/gtjxpuomxn.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.snrcjt.cn/Article/details/gtkxzksxqq.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuillcsns.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.smart0.xyz/Article/details/gtyojoznme.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.yj20258.top/Article/details/gtgypijagl.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.wangdashe.top/Article/details/gtxofrofok.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.yanxiufei.cn/Article/details/gtqqulidgb.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.gaohongyu789.top/Article/details/gtrcohdest.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.fzhhl.top/Article/details/gtpteluqql.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.nwbrower.top/Article/details/gtxnmyubhb.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhongyouzk.top/Article/details/gtalovzbfz.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.havefunace.top/Article/details/gthzdabnrf.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.wangshuangyany.cn/Article/details/gtgmvnjglo.html

Go:   slices.Sort(arr)
来源：http://dali.ybcxt.top/Article/details/gtgmdsuyvw.html

Ruby: arr.sort
来源：http://dali.mhx1999.top/Article/details/gthptndzyg.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.hongshengwenyu.top/Article/details/gtkeaofbsa.html

[N03] 快速排序（分治示例）
来源：http://dali.andypj.xyz/Article/details/gtmhmcqcht.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.jlsjyb.cn/Article/details/gtpgrorqcv.html

PHP:  // 递归实现，或用 usort
来源：http://dali.shanyushiyangtech.top/Article/details/gtpmfxzxsb.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.svipenyu.cn/Article/details/gtqkzhwzxa.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.tian-w.cn/Article/details/gttddeedrb.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhoulong.xyz/Article/details/gtrizmbipp.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhoulong.xyz/Article/details/gthelstlwe.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.pycfn.com/Article/details/gtnatpicjk.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.gotoacloud.top/Article/details/gtmfcnczgw.html

[N04] 斐波那契数列
来源：http://dali.dashuyun.cn/Article/details/gtjtugulqg.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.tian-w.cn/Article/details/gtxqfnwawm.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.vqdsnc.cn/Article/details/gtijmzxcqh.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.xziqi.cn/Article/details/gtomdbpeec.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.nanxinkj.top/Article/details/gtrvlmltyq.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.wangdashe.top/Article/details/gtenyvmrna.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.nwbrower.top/Article/details/gtbjzrixpi.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.hywenlv.cn/Article/details/gtnojwnqig.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.yj20258888.top/Article/details/gtkbptpmln.html

[N05] 最大公约数
来源：http://dali.yuanzhike.top/Article/details/gtkuenhrvz.html

Py:   math.gcd(a, b)
来源：http://dali.xuetiantiany.cn/Article/details/gtcygtamot.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.wangshuangyany.cn/Article/details/gthshdzxsp.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhixingplan.top/Article/details/gtvfmcmaha.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.chenjidiqi.icu/Article/details/gtqrfcaavi.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhiwuduotai.top/Article/details/gtyrdmdzva.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.yj20258.top/Article/details/gtbadyyxjw.html

Ruby: a.gcd(b)
来源：http://dali.jiagoushi.top/Article/details/gtrwlycznh.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.yuanzhike.top/Article/details/gtwywsmwyo.html

[N06] 判断回文字符串
来源：http://dali.snrcjt.cn/Article/details/gtvdrfhmar.html

Py:   s == s[::-1]
来源：http://dali.aizwys.cn/Article/details/gtrfukyxwo.html

PHP:  $s === strrev($s);
来源：http://dali.fzhhl.top/Article/details/gtxnmwjmar.html

JS:   s === [...s].reverse().join("")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkwngupjc.html

TS:   s === [...s].reverse().join("")
来源：http://dali.quarkkingdee.top/Article/details/gtucuwxwdr.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.smart0.xyz/Article/details/gtlcfqsusy.html

Go:   // 双指针从两端比较
来源：http://dali.jinqigfzy.top/Article/details/gtbdbrjxcb.html

Ruby: s == s.reverse
来源：http://dali.haohaochexian.top/Article/details/gtrijqlhuh.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.jianghu66.top/Article/details/gtvxpzdzew.html

[N07] 两数之和（返回下标）
来源：http://dali.9152youxi.cn/Article/details/gtjrphqrwx.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.chenjidiqi.icu/Article/details/gtognkcxcl.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.jianghu66.top/Article/details/gtqssduebp.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.c1oappe.top/Article/details/gtujvfwcwd.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gthzqoodlc.html

Java: // 手写 HashMap
来源：http://dali.zhengqikj.top/Article/details/gtdfcxrswb.html

Go:   // 手写 map[int]int
来源：http://dali.wangdashe.top/Article/details/gturgltjlk.html

Ruby: // 手写 Hash
来源：http://dali.iojbl.cn/Article/details/gtivhcecqk.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.ywan-chungtsiang.top/Article/details/gtugxitqmy.html

[N08] 生成全排列
来源：http://dali.9152youxi.cn/Article/details/gthqocpulb.html

Py:   itertools.permutations(arr)
来源：http://dali.jinqigfzy.top/Article/details/gtvoqufhpj.html

PHP:  // 手写递归交换
来源：http://dali.c1oappe.top/Article/details/gtwyfenpfc.html

JS:   // 手写回溯递归
来源：http://dali.gaohongyu789.top/Article/details/gtbluppooo.html

TS:   // 手写回溯递归
来源：http://dali.zdqjudy.top/Article/details/gtjvahbofa.html

Java: // 手写回溯递归
来源：http://dali.wangshuangyany.cn/Article/details/gtocjdkazq.html

Go:   // 手写回溯递归
来源：http://dali.yueranfly.top/Article/details/gtbzgwfsgp.html

Ruby: arr.permutation.to_a
来源：http://dali.guowangkeji.top/Article/details/gtqbhfoeaf.html

C#:   // 手写回溯递归
来源：http://dali.feifeiyinyue.top/Article/details/gtryslhnbg.html

[N09] 栈与队列
来源：http://dali.wangdashe.top/Article/details/gtxgkdzegz.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.nwbrower.top/Article/details/gthbytrgzt.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.svipenyu.cn/Article/details/gtrsaqfphq.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.ehwqpu.com/Article/details/gtcnbbymhu.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.tanke756.top/Article/details/gtwbwviljz.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.hysaishi.cn/Article/details/gtwdrpgbvn.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqowrpolw.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhixingplan.top/Article/details/gtdaptnccz.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.pycfn.com/Article/details/gtsllvpvzg.html

[N10] 链表节点定义
来源：http://dali.jyoumei.cn/Article/details/gtuglutqnp.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.gotoacloud.top/Article/details/gtqcwxqnck.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.gzhubu.top/Article/details/gtqlegpxdg.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.iojbl.cn/Article/details/gtsnkmpwbb.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.aizwys.cn/Article/details/gtkefermxu.html

Java: class Node { int v; Node next; }
来源：http://dali.chenlongwang.top/Article/details/gtdhhzywbd.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.snrcjt.cn/Article/details/gtlqhfjgms.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.kuanghao11.cn/Article/details/gtmlyhqvsx.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.jyoumei.cn/Article/details/gtpnnzixof.html

[N11] 二叉树中序遍历
来源：http://dali.xziqi.cn/Article/details/gtlhqghlhk.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.haohaochexian.top/Article/details/gtlasmsdjq.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gtrlkhfaba.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.havefunace.top/Article/details/gtultvazkc.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yuxming.cn/Article/details/gthfacouib.html

Java: // 手写递归
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpqcuvgei.html

Go:   // 手写递归
来源：http://dali.ybcxt.top/Article/details/gtyjmhyzgn.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.tanke756.top/Article/details/gtvcyzfrkd.html

C#:   // 手写递归
来源：http://dali.cdnleiting.top/Article/details/gtxnpgcahm.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.snrcjt.cn/Article/details/gtwgvdsbzw.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.tianlin.xyz/Article/details/gtsdjkuuzl.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.hywenlv.cn/Article/details/gtijgikqyh.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.shuidangran.top/Article/details/gtcbjtkmyd.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zdqjudy.top/Article/details/gtyusfhzsk.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yueranfly.top/Article/details/gtdpuupudw.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.nwbrower.top/Article/details/gtgelsubxh.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.gogol.net.cn/Article/details/gtwymlzrbm.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.shuidangran.top/Article/details/gtfghyizfr.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gthxcwwmem.html

O. 并发与异步
来源：http://dali.ydzc1.top/Article/details/gtvuyxdvue.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtmhzxukhs.html

[O01] 启动一个线程
来源：http://dali.cqqwz.cn/Article/details/gtqgsvjsti.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.andypj.xyz/Article/details/gtpunetsda.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.pycfn.com/Article/details/gtzqfmamfh.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhengqikj.top/Article/details/gtpmthqczz.html

TS:   // 同 JS
来源：http://dali.quarkkingdee.top/Article/details/gtgrkbzylx.html

Java: new Thread(() -> f()).start()
来源：http://dali.gaohongyu789.top/Article/details/gtcwhvudyy.html

Go:   go f()
来源：http://dali.xuanzx.com/Article/details/gtjclaucpa.html

Ruby: Thread.new { f }
来源：http://dali.yuanzhike.top/Article/details/gtbszfacqi.html

C#:   Task.Run(() => F());
来源：http://dali.haohaochexian.top/Article/details/gtvkarjvdp.html

[O02] 使用线程池
来源：http://dali.xuanzx.com/Article/details/gtmiozmafo.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.cucudq.cn/Article/details/gtqjjsqojw.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.chenjidiqi.icu/Article/details/gtidotpplb.html

JS:   // worker_threads 线程池
来源：http://dali.bjfxy.top/Article/details/gtgmchpgwl.html

TS:   // worker_threads 线程池
来源：http://dali.zycfv.cn/Article/details/gtmmpfodee.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.meibo888.top/Article/details/gtnxmyinyp.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.jqgufenzy.top/Article/details/gthifnbsxg.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.kuanghao11.cn/Article/details/gthybdkyys.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.tianlin.xyz/Article/details/gtybjpmmlv.html

[O03] 加锁保护共享数据
来源：http://dali.feifeiyinyue.top/Article/details/gtobkexktt.html

Py:   with lock: shared += 1
来源：http://dali.chenjidiqi.icu/Article/details/gtdzrjwjwj.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.birdmap.top/Article/details/gtznysqlae.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.redwolf501.top/Article/details/gtcgujaazd.html

TS:   // 同 JS
来源：http://dali.9152youxi.cn/Article/details/gtvmmouwef.html

Java: synchronized (this) { shared++; }
来源：http://dali.fzhhl.top/Article/details/gthevvaeqy.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.guowangkeji.top/Article/details/gtcenrhfqb.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.bjfxy.top/Article/details/gtdmzbmimb.html

C#:   lock (gate) { shared++; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtemvviuam.html

[O04] 定义异步函数并等待
来源：http://dali.iojbl.cn/Article/details/gtdpknhnqr.html

Py:   async def f():⏎    await g()
来源：http://dali.jqgufenzy.top/Article/details/gtrlhnuzhg.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.iojbl.cn/Article/details/gttpeggptl.html

JS:   async function f() { await g(); }
来源：http://dali.hammf.cn/Article/details/gttjlzgfws.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.snrcjt.cn/Article/details/gtmmtolqir.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.yongpay.top/Article/details/gttbscgkbg.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.xziqi.cn/Article/details/gtpmzoqsoj.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.ivvv.top/Article/details/gtkejvfhyi.html

C#:   async Task F() { await G(); }
来源：http://dali.gotoacloud.top/Article/details/gtxjdhfurr.html

[O05] 并发执行并等待全部完成
来源：http://dali.wangshuangyany.cn/Article/details/gtujibnkpj.html

Py:   asyncio.gather(*tasks)
来源：http://dali.guannengcc.top/Article/details/gtxttxouxs.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.quarkkingdee.top/Article/details/gtnzgzcaif.html

JS:   await Promise.all(tasks)
来源：http://dali.andypj.xyz/Article/details/gttkblufjr.html

TS:   await Promise.all(tasks)
来源：http://dali.haohaochexian.top/Article/details/gtvtxtgrzv.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.yueranfly.top/Article/details/gttiqpmgya.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.ehwqpu.com/Article/details/gthdfzvitd.html

Ruby: threads.map(&:join)
来源：http://dali.iojbl.cn/Article/details/gtupavpfat.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.0kj1m.cn/Article/details/gtvfqgkxtj.html

[O06] 使用进程池
来源：http://dali.birdmap.top/Article/details/gtboujwmwl.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.shzxlz.cn/Article/details/gtbxnpgcwu.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.shzxlz.cn/Article/details/gtcltlntmm.html

JS:   // child_process / cluster 模块
来源：http://dali.ehwqpu.com/Article/details/gtuqlaazvh.html

TS:   // child_process / cluster 模块
来源：http://dali.zhixingplan.top/Article/details/gtjuihrejn.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.daria6918.cn/Article/details/gtlzefivew.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.shangyingyoupin.top/Article/details/gtlocwkqzj.html

Ruby: // fork 块
来源：http://dali.nwbrower.top/Article/details/gtegcgxzbl.html

C#:   Parallel.For
来源：http://dali.tianlin.xyz/Article/details/gtggtliwlk.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtzpnicthf.html

P. 常用工具函数
来源：http://dali.shzxlz.cn/Article/details/gthupdlosa.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gttujjsagp.html

[P01] 生成 UUID
来源：http://dali.tian-w.cn/Article/details/gtxjxkhhqw.html

Py:   str(uuid.uuid4())
来源：http://dali.dianchejie.cn/Article/details/gtlflgrmea.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhoulong.xyz/Article/details/gtiwxtwjiz.html

JS:   crypto.randomUUID()
来源：http://dali.0kj1m.cn/Article/details/gtrkqpehey.html

TS:   crypto.randomUUID()
来源：http://dali.cheryme.top/Article/details/gtogmarfpi.html

Java: UUID.randomUUID().toString()
来源：http://dali.guannengcc.top/Article/details/gtgyqfjkvv.html

Go:   // 用 github.com/google/uuid
来源：http://dali.cucudq.cn/Article/details/gtprwkcoij.html

Ruby: SecureRandom.uuid
来源：http://dali.dashuyun.cn/Article/details/gtbaeozjaq.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.dianchejie.cn/Article/details/gtokzdekgk.html

[P02] MD5 / SHA256 摘要
来源：http://dali.yj202588.top/Article/details/gtojduqayx.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.ehwqpu.com/Article/details/gtvexlprvl.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.dianchejie.cn/Article/details/gtxfemuprk.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.shanyushiyangtech.top/Article/details/gtupbxlwcb.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.havefunace.top/Article/details/gtgmynsuoc.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.kuanghao11.cn/Article/details/gthlrumuqf.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.cheryme.top/Article/details/gtqgcuzdci.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.yuxming.cn/Article/details/gteiochxzp.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.9152youxi.cn/Article/details/gtmoupmvzg.html

[P03] 生成短随机字符串
来源：http://dali.zhoulong.xyz/Article/details/gternccbmb.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.birdmap.top/Article/details/gtckfcnizx.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.cdnleiting.top/Article/details/gtcddgxglz.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.hywenlv.cn/Article/details/gtknbisail.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.cheryme.top/Article/details/gtfbdslixh.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.jiagoushi.top/Article/details/gtxzvcbagi.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.jinyuanbaomall.cn/Article/details/gtafuziigk.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.ybcxt.top/Article/details/gtwxiopsme.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.vqdsnc.cn/Article/details/gtcyqbffow.html

[P04] 求长度
来源：http://dali.hysaishi.cn/Article/details/gtdstjdoha.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.jiagoushi.top/Article/details/gtabebubja.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yongpay.top/Article/details/gtlntkmgep.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.cdnleiting.top/Article/details/gttuyqteco.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.nanxuanxn.top/Article/details/gthbjdsiig.html

Java: list.size();  map.size();  s.length()
来源：http://dali.svipenyu.cn/Article/details/gtvbcwwgqk.html

Go:   len(arr);  len(m)
来源：http://dali.9152youxi.cn/Article/details/gtsislidbj.html

Ruby: x.length;  x.size
来源：http://dali.zhiwuduotai.top/Article/details/gtabccvhli.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.sufxvd.cn/Article/details/gtinxsuhau.html

[P05] 判断两个对象内容是否相等
来源：http://dali.gaohongyu789.top/Article/details/gtuefgvsgm.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.yueranfly.top/Article/details/gtlqksgvoc.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.ehwqpu.com/Article/details/gthwezaiuz.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhongyouzk.top/Article/details/gtkqrngmna.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.fzhhl.top/Article/details/gtupzbilvj.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.zdqjudy.top/Article/details/gtevamqcsg.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.yanxiufei.cn/Article/details/gtwugprwmo.html

Ruby: a == b
来源：http://dali.hnqzz.top/Article/details/gtvttogrdh.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.bjfxy.top/Article/details/gtzrurgjoy.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtufolwasb.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.chenzaomai.com/Article/details/gtvcifvylt.html

PHP:  if (empty($x)) {}
来源：http://dali.daxiang520.top/Article/details/gtcrekcouu.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.jianghu66.top/Article/details/gteobwfcqe.html

TS:   if (x == null) {}
来源：http://dali.smart0.xyz/Article/details/gtaakyrqtm.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.sxryk.cn/Article/details/gtrlkbgioi.html

Go:   if x == nil {}
来源：http://dali.gzhubu.top/Article/details/gtpokdquzy.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.9152youxi.cn/Article/details/gtzvvaoojr.html

C#:   if (x is null) {}
来源：http://dali.bjfxy.top/Article/details/gtnbjfudga.html

[P07] 防抖与节流
来源：http://dali.yonumen.top/Article/details/gtpsogenbe.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.chenzaomai.com/Article/details/gtjtsbbhoj.html

PHP:  // 手写时间戳比较
来源：http://dali.ydzc1.top/Article/details/gtyspubmnv.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.zycfv.cn/Article/details/gtylwazaav.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.haohaochexian.top/Article/details/gtfnkhmmzq.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.chenlongwang.top/Article/details/gtbmvtneju.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.nanxinkj.top/Article/details/gtqiqzkami.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.c1oappe.top/Article/details/gtajoeoete.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.yonumen.top/Article/details/gteizgmcba.html

[P08] 处理浮点精度问题
来源：http://dali.xinyue.icu/Article/details/gttedklsqg.html


<!-- 参考信息 -->