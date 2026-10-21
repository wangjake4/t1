代发 wailian999

Ruby: ARGV
来源：http://dali.dianchejie.cn/Article/details/gtwansxkna.html

C#:   args 数组（Main 方法参数）
来源：http://dali.shanyushiyangtech.top/Article/details/gtouhmecys.html

[M02] 读取环境变量
来源：http://dali.ppjwa.cn/Article/details/gtrtybrtmm.html

Py:   os.environ.get("HOME")
来源：http://dali.ybcxt.top/Article/details/gtoxkiuupr.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.haohaochexian.top/Article/details/gtqobpcsan.html

JS:   process.env.HOME
来源：http://dali.aizwys.cn/Article/details/gtygicjuhn.html

TS:   process.env.HOME
来源：http://dali.yj20258.top/Article/details/gtienbvmkc.html

Java: System.getenv("HOME")
来源：http://dali.dashuyun.cn/Article/details/gtvhzhpuij.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.ivvv.top/Article/details/gtbxudwvxi.html

Ruby: ENV["HOME"]
来源：http://dali.dashuyun.cn/Article/details/gtfyrhgagg.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.aizwys.cn/Article/details/gttjnmljet.html

[M03] 执行外部命令
来源：http://dali.iojbl.cn/Article/details/gtxcoafbgg.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.xylfe.cn/Article/details/gtlllaiigo.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.xuanzx.com/Article/details/gtfeejqfge.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.c1oappe.top/Article/details/gttcbxifax.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhixingplan.top/Article/details/gtlncpvbwv.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.birdmap.top/Article/details/gtpxsjkavj.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.jqgufenzy.top/Article/details/gtprtbkkyk.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.wangdashe.top/Article/details/gtwzwptebq.html

C#:   Process.Start("ls", "-l");
来源：http://dali.wangdashe.top/Article/details/gtuveqartv.html

[M04] 获取当前工作目录
来源：http://dali.hnqzz.top/Article/details/gtnwnttwrz.html

Py:   os.getcwd()
来源：http://dali.wangshuangyany.cn/Article/details/gtqlfxqtad.html

PHP:  getcwd();
来源：http://dali.wangshuangyany.cn/Article/details/gtobrjpfsn.html

JS:   process.cwd()
来源：http://dali.shzxlz.cn/Article/details/gtraindepz.html

TS:   process.cwd()
来源：http://dali.jqgfzy.top/Article/details/gtrernsxxf.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.chenlongwang.top/Article/details/gtsjhzzvht.html

Go:   os.Getwd()
来源：http://dali.svipenyu.cn/Article/details/gtfqtbqwbe.html

Ruby: Dir.pwd
来源：http://dali.yueranfly.top/Article/details/gtenurwfmx.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpkaqhhrk.html

[M05] 设置退出码
来源：http://dali.yuanzhike.top/Article/details/gtmcwyyyvh.html

Py:   sys.exit(1)
来源：http://dali.yj202588.top/Article/details/gtiwymlywi.html

PHP:  exit(1);
来源：http://dali.kuanghao11.cn/Article/details/gtaxuftqme.html

JS:   process.exit(1)
来源：http://dali.sxryk.cn/Article/details/gtgipabkch.html

TS:   process.exit(1)
来源：http://dali.tanke756.top/Article/details/gtetadrqqe.html

Java: System.exit(1)
来源：http://dali.xylfe.cn/Article/details/gtlnobwpkc.html

Go:   os.Exit(1)
来源：http://dali.0kj1m.cn/Article/details/gtjwtdytgt.html

Ruby: exit 1
来源：http://dali.vqdsnc.cn/Article/details/gtfnhbgjnu.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.vqdsnc.cn/Article/details/gtlvtcaitc.html

[M06] 向标准错误输出
来源：http://dali.guowangkeji.top/Article/details/gtemfckndx.html

Py:   print("err", file=sys.stderr)
来源：http://dali.fengsongda.top/Article/details/gtnvlqohki.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.9152youxi.cn/Article/details/gtaiifubfv.html

JS:   console.error("err")
来源：http://dali.fzhhl.top/Article/details/gtnljledop.html

TS:   console.error("err")
来源：http://dali.shuidangran.top/Article/details/gtuxoplmlv.html

Java: System.err.println("err")
来源：http://dali.hnqzz.top/Article/details/gtuhvtzzxl.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.haohaochexian.top/Article/details/gtummwltwo.html

Ruby: warn "err"
来源：http://dali.bjfxy.top/Article/details/gtmawhppjm.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.vqdsnc.cn/Article/details/gttbmcrhxf.html

[M07] 判断是否为主入口
来源：http://dali.zhoulong.xyz/Article/details/gtuzxxkkab.html

Py:   if __name__ == "__main__":
来源：http://dali.nwbrower.top/Article/details/gtpdytbsmz.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.tanke756.top/Article/details/gttcyetfio.html

JS:   require.main === module
来源：http://dali.gzhubu.top/Article/details/gtvkylcqrx.html

TS:   require.main === module
来源：http://dali.quarkkingdee.top/Article/details/gtaibnyzny.html

Java: public static void main(String[] args)
来源：http://dali.kuanghao11.cn/Article/details/gtwelnnick.html

Go:   func main()
来源：http://dali.hfpthk.cn/Article/details/gtohmdpsyh.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.0kj1m.cn/Article/details/gtprsuapfi.html

C#:   static void Main(string[] args)
来源：http://dali.zycfv.cn/Article/details/gtcsevfhrw.html

[M08] 获取系统与运行时信息
来源：http://dali.yj20258.top/Article/details/gtxecrgfxj.html

Py:   platform.system();  platform.python_version()
来源：http://dali.daxiang520.top/Article/details/gtybarbmey.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.jqgfzy.top/Article/details/gtgnjiiqxy.html

JS:   process.platform;  process.version
来源：http://dali.birdmap.top/Article/details/gteosczehl.html

TS:   process.platform;  process.version
来源：http://dali.gotoacloud.top/Article/details/gtgahfwlqz.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhaomingkeji.xyz/Article/details/gteoqpwvyk.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.jyoumei.cn/Article/details/gtmtttxpfz.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.hnqzz.top/Article/details/gtksfohfor.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.yanxiufei.cn/Article/details/gtftpyspwi.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtbcavgmqv.html

N. 数据结构与算法
来源：http://dali.quarkkingdee.top/Article/details/gtbefijtbw.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtgleeafvm.html

[N01] 二分查找（有序数组）
来源：http://dali.zhoulong.xyz/Article/details/gtxpidkwkt.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhongyouzk.top/Article/details/gtelqtuvcr.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.hfpthk.cn/Article/details/gtkoiphyxh.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zdqjudy.top/Article/details/gtfkukqikl.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.kuanghao11.cn/Article/details/gtvltiardw.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.guowangkeji.top/Article/details/gtesfexqoi.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.shangyingyoupin.top/Article/details/gtlnhnpqov.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.hnqzz.top/Article/details/gtooxegkuj.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.xuanzx.com/Article/details/gtoshputvb.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.yuxming.cn/Article/details/gtokouigho.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.xuetiantiany.cn/Article/details/gtexcvdzpf.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.meibo888.top/Article/details/gtayqwghug.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.daxiang520.top/Article/details/gtiobcamvc.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zycfv.cn/Article/details/gtomwypnou.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.cashguo.top/Article/details/gtabqbayln.html

Go:   slices.Sort(arr)
来源：http://dali.xziqi.cn/Article/details/gtaexsrlyu.html

Ruby: arr.sort
来源：http://dali.zhongyouzk.top/Article/details/gtkabouuix.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.ydzc1.top/Article/details/gtznjwojhx.html

[N03] 快速排序（分治示例）
来源：http://dali.pycfn.com/Article/details/gtlqcpqdle.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.guannengcc.top/Article/details/gtbbyrdotw.html

PHP:  // 递归实现，或用 usort
来源：http://dali.shangyingyoupin.top/Article/details/gtrzkwcrma.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.xuanzx.com/Article/details/gthxrqbakd.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.gogol.net.cn/Article/details/gtzzxjistk.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.daria6918.cn/Article/details/gtnxrlpshz.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.c1oappe.top/Article/details/gttoomgkzi.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnosxakzo.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.yvedp.cn/Article/details/gtcabopitn.html

[N04] 斐波那契数列
来源：http://dali.yueranfly.top/Article/details/gtqlfqomkw.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.wangshuangyany.cn/Article/details/gtleptjicj.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.gaohongyu789.top/Article/details/gtdnxukjnc.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.redwolf501.top/Article/details/gtnnhyqmtg.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.9152youxi.cn/Article/details/gtljmmmauw.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtvxipfuxm.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.gaohongyu789.top/Article/details/gtozulwsbk.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.316326.xyz/Article/details/gtywxmhfct.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.gzhubu.top/Article/details/gtyrnuwazn.html

[N05] 最大公约数
来源：http://dali.aibaodan.cn/Article/details/gtrdslhkza.html

Py:   math.gcd(a, b)
来源：http://dali.hongshengwenyu.top/Article/details/gtqnjzmuhl.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjdbaxhdk.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yvedp.cn/Article/details/gtjaxcwzyr.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.sxryk.cn/Article/details/gtdztyekee.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.xinyue.icu/Article/details/gtrkztidtz.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.jinqigufen.top/Article/details/gtfkxtvybq.html

Ruby: a.gcd(b)
来源：http://dali.sweek.top/Article/details/gtvzndoyfj.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.tian-w.cn/Article/details/gtclxastzx.html

[N06] 判断回文字符串
来源：http://dali.ppjwa.cn/Article/details/gtsnnbpkvc.html

Py:   s == s[::-1]
来源：http://dali.jqgufenzy.top/Article/details/gtmbajcouf.html

PHP:  $s === strrev($s);
来源：http://dali.yangfankeji.com/Article/details/gtufuymmpy.html

JS:   s === [...s].reverse().join("")
来源：http://dali.xylfe.cn/Article/details/gtxmmdonoo.html

TS:   s === [...s].reverse().join("")
来源：http://dali.quarkkingdee.top/Article/details/gtndzyxquk.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.sxryk.cn/Article/details/gtvxllgtqd.html

Go:   // 双指针从两端比较
来源：http://dali.zhengqikj.top/Article/details/gtmvpsngrr.html

Ruby: s == s.reverse
来源：http://dali.chenlongwang.top/Article/details/gtjfewsheu.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.xinyue.icu/Article/details/gttakbwpdf.html

[N07] 两数之和（返回下标）
来源：http://dali.guowangkeji.top/Article/details/gtoohzveiq.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.tian-w.cn/Article/details/gtjksrkefo.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.yj20258888.top/Article/details/gtentnpuwc.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.hysaishi.cn/Article/details/gtilqkavqc.html

TS:   // 手写 Map<string, number>
来源：http://dali.gogol.net.cn/Article/details/gtrxbhnphk.html

Java: // 手写 HashMap
来源：http://dali.jinqigfzy.top/Article/details/gtgaqcngas.html

Go:   // 手写 map[int]int
来源：http://dali.meibo888.top/Article/details/gttpstikqw.html

Ruby: // 手写 Hash
来源：http://dali.jinqigufen.top/Article/details/gtmyvjjhur.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.hywenlv.cn/Article/details/gtyxzyygao.html

[N08] 生成全排列
来源：http://dali.ybcxt.top/Article/details/gtkqkgnnqf.html

Py:   itertools.permutations(arr)
来源：http://dali.sweek.top/Article/details/gtlxzhvxmg.html

PHP:  // 手写递归交换
来源：http://dali.nanxuanxn.top/Article/details/gtafyqkjbf.html

JS:   // 手写回溯递归
来源：http://dali.mhx1999.top/Article/details/gtdwhcdcmv.html

TS:   // 手写回溯递归
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxnnguozn.html

Java: // 手写回溯递归
来源：http://dali.hammf.cn/Article/details/gtjkgvhxqn.html

Go:   // 手写回溯递归
来源：http://dali.hnxiangtu.top/Article/details/gtgtzoyrer.html

Ruby: arr.permutation.to_a
来源：http://dali.zhengqikj.top/Article/details/gtlgnjnfey.html

C#:   // 手写回溯递归
来源：http://dali.haohaochexian.top/Article/details/gtekkikubw.html

[N09] 栈与队列
来源：http://dali.zhiwuduotai.top/Article/details/gtmbmndjdk.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.xylfe.cn/Article/details/gtngenbxdb.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhixingplan.top/Article/details/gtibiepsvz.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.cheryme.top/Article/details/gtmezkotpb.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.aibaodan.cn/Article/details/gtqqjjtbus.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.aibaodan.cn/Article/details/gtizafotqk.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.andypj.xyz/Article/details/gtndrrcytr.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.yj20258.top/Article/details/gtegokbpgi.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.shuidangran.top/Article/details/gtnqywujjd.html

[N10] 链表节点定义
来源：http://dali.cucudq.cn/Article/details/gttbdsvviv.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.daxiang520.top/Article/details/gtjoubdxyt.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.c1oappe.top/Article/details/gtotznugxy.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.dianchejie.cn/Article/details/gttbpfghhl.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhoulong.xyz/Article/details/gtnqzpvvjq.html

Java: class Node { int v; Node next; }
来源：http://dali.aibaodan.cn/Article/details/gturufowgm.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.snrcjt.cn/Article/details/gtkxibearu.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.c1oappe.top/Article/details/gtetbwavqo.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.ivvv.top/Article/details/gtkwkjzrxw.html

[N11] 二叉树中序遍历
来源：http://dali.hnxiangtu.top/Article/details/gthvfwcooc.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.sweek.top/Article/details/gtowlzhquf.html

PHP:  // 手写递归函数
来源：http://dali.nwbrower.top/Article/details/gtecuveqhp.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jinqigfzy.top/Article/details/gtjpzapxye.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.hammf.cn/Article/details/gtosxowbju.html

Java: // 手写递归
来源：http://dali.yongpay.top/Article/details/gtblfghwvp.html

Go:   // 手写递归
来源：http://dali.xylfe.cn/Article/details/gtjxlsqkbd.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.aizwys.cn/Article/details/gtbptgqost.html

C#:   // 手写递归
来源：http://dali.mhx1999.top/Article/details/gtebsazfjw.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.sysykeji.top/Article/details/gtonnqnllh.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.sysykeji.top/Article/details/gtgtznpeia.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.kuanghao11.cn/Article/details/gtijoyiyzo.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.nwbrower.top/Article/details/gtmgnpfrac.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.nanxinkj.top/Article/details/gtvnugvziv.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yuanzhike.top/Article/details/gtgxteiqxw.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gtcmdqeady.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.havefunace.top/Article/details/gtkphpkekw.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jyoumei.cn/Article/details/gtvzdtzcpx.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtnxlzpxgc.html

O. 并发与异步
来源：http://dali.fzhhl.top/Article/details/gtaazzeqra.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gthlpwjifl.html

[O01] 启动一个线程
来源：http://dali.jqgfzy.top/Article/details/gtjmoqcmbm.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.fzhhl.top/Article/details/gthsalvtlx.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.chenlongwang.top/Article/details/gtxrtixhrx.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.sufxvd.cn/Article/details/gtvtgqmwwn.html

TS:   // 同 JS
来源：http://dali.birdmap.top/Article/details/gtejyvjnnu.html

Java: new Thread(() -> f()).start()
来源：http://dali.aibaodan.cn/Article/details/gtfdpbjqeh.html

Go:   go f()
来源：http://dali.yongpay.top/Article/details/gtjgkeolhe.html

Ruby: Thread.new { f }
来源：http://dali.yonumen.top/Article/details/gtpshouvir.html

C#:   Task.Run(() => F());
来源：http://dali.wangshuangyany.cn/Article/details/gtkjwdvapx.html

[O02] 使用线程池
来源：http://dali.daxiang520.top/Article/details/gtxovrgzjc.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zdqjudy.top/Article/details/gtfszomjdl.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.kuanghao11.cn/Article/details/gtbhpojljq.html

JS:   // worker_threads 线程池
来源：http://dali.gogol.net.cn/Article/details/gtjvfkfsvw.html

TS:   // worker_threads 线程池
来源：http://dali.cashguo.top/Article/details/gteowobkkl.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.xinyue.icu/Article/details/gtpnkrzrzn.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.pengpengdd.cyou/Article/details/gtxhsnlopu.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.feifeiyinyue.top/Article/details/gtyfddnvfy.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhixingplan.top/Article/details/gtkvjlrowi.html

[O03] 加锁保护共享数据
来源：http://dali.yuxming.cn/Article/details/gtzqqscwah.html

Py:   with lock: shared += 1
来源：http://dali.aibaodan.cn/Article/details/gtosppbbbs.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.dianchejie.cn/Article/details/gtzrzlxnwe.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.ivvv.top/Article/details/gttrfpvwot.html

TS:   // 同 JS
来源：http://dali.hnxiangtu.top/Article/details/gtgalgwzdy.html

Java: synchronized (this) { shared++; }
来源：http://dali.jianghu66.top/Article/details/gtbfftmzhv.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.pycfn.com/Article/details/gtvkfasjky.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.wangshuangyany.cn/Article/details/gtvvzkicjc.html

C#:   lock (gate) { shared++; }
来源：http://dali.vqdsnc.cn/Article/details/gtlksbbewk.html

[O04] 定义异步函数并等待
来源：http://dali.yangfankeji.com/Article/details/gtuznzrpzm.html

Py:   async def f():⏎    await g()
来源：http://dali.pycfn.com/Article/details/gtwqmyofae.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.birdmap.top/Article/details/gtrzeiuvez.html

JS:   async function f() { await g(); }
来源：http://dali.iojbl.cn/Article/details/gtqlcozbfd.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.xylfe.cn/Article/details/gtiegollnl.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.havefunace.top/Article/details/gtiaktrkqn.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpkhzvfhv.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.daxiang520.top/Article/details/gtmdwxkkms.html

C#:   async Task F() { await G(); }
来源：http://dali.yueranfly.top/Article/details/gttdgwuerz.html

[O05] 并发执行并等待全部完成
来源：http://dali.jlsjyb.cn/Article/details/gtqmzdfnsz.html

Py:   asyncio.gather(*tasks)
来源：http://dali.hammf.cn/Article/details/gtsgyndsha.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.316326.xyz/Article/details/gtgznsogsa.html

JS:   await Promise.all(tasks)
来源：http://dali.jinqigfzy.top/Article/details/gtxzwpebym.html

TS:   await Promise.all(tasks)
来源：http://dali.yj20258888.top/Article/details/gtvggrhodv.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.redwolf501.top/Article/details/gtxyuczbmi.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.ybcxt.top/Article/details/gtjlagixrx.html

Ruby: threads.map(&:join)
来源：http://dali.ehwqpu.com/Article/details/gtkoznzshu.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.tian-w.cn/Article/details/gtbapsqiie.html

[O06] 使用进程池
来源：http://dali.meibo888.top/Article/details/gtcgawbnhj.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.wangshuangyany.cn/Article/details/gtebgnhsnm.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.gaohongyu789.top/Article/details/gtkwzxqvrz.html

JS:   // child_process / cluster 模块
来源：http://dali.jyoumei.cn/Article/details/gtfcktstmr.html

TS:   // child_process / cluster 模块
来源：http://dali.nanxinkj.top/Article/details/gtymkkrvdk.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.tian-w.cn/Article/details/gtwppusosr.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.gzhubu.top/Article/details/gtsrglfwbl.html

Ruby: // fork 块
来源：http://dali.zhoulong.xyz/Article/details/gtxoxwxqvw.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gtghruzkrf.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtzpfojtvq.html

P. 常用工具函数
来源：http://dali.xinyue.icu/Article/details/gtnowfgjes.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtmzsshibo.html

[P01] 生成 UUID
来源：http://dali.zhoulong.xyz/Article/details/gtdushpngw.html

Py:   str(uuid.uuid4())
来源：http://dali.xylfe.cn/Article/details/gtdnfumqsv.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.ppjwa.cn/Article/details/gtxvtihirm.html

JS:   crypto.randomUUID()
来源：http://dali.tianlin.xyz/Article/details/gtdekhcrvn.html

TS:   crypto.randomUUID()
来源：http://dali.xuanzx.com/Article/details/gtwfytoowv.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhiwuduotai.top/Article/details/gthqwjoghi.html

Go:   // 用 github.com/google/uuid
来源：http://dali.cucudq.cn/Article/details/gtjilpwmoa.html

Ruby: SecureRandom.uuid
来源：http://dali.cucudq.cn/Article/details/gtflzpdvtc.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.hnxiangtu.top/Article/details/gtrcitaanp.html

[P02] MD5 / SHA256 摘要
来源：http://dali.yangfankeji.com/Article/details/gtvchtkiue.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.dashuyun.cn/Article/details/gtuynjwjyw.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.tanke756.top/Article/details/gtjeubklee.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.yanxiufei.cn/Article/details/gtztqqlsle.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwhemmrxw.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zycfv.cn/Article/details/gtzljjepkq.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdrfdsojk.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtkfqjczir.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.ydzc1.top/Article/details/gtqemgltjg.html

[P03] 生成短随机字符串
来源：http://dali.bjfxy.top/Article/details/gtmdurxtat.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.snrcjt.cn/Article/details/gtbjjsjtgu.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.daxiang520.top/Article/details/gtvissyham.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhongyouzk.top/Article/details/gtxucfhids.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.hfpthk.cn/Article/details/gtuhyjmyue.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.nanxuanxn.top/Article/details/gtvhuyxbyh.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.shuidangran.top/Article/details/gtaixzrlxw.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.hammf.cn/Article/details/gtmcgnjxsj.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.quarkkingdee.top/Article/details/gtsagwgckr.html

[P04] 求长度
来源：http://dali.cashguo.top/Article/details/gtyfxjfzur.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhijiandao.cn/Article/details/gtlcfblxub.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsirxkpev.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.hywenlv.cn/Article/details/gtevohgzbu.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.ehwqpu.com/Article/details/gtygxlbsgm.html

Java: list.size();  map.size();  s.length()
来源：http://dali.iojbl.cn/Article/details/gtebjbhajk.html

Go:   len(arr);  len(m)
来源：http://dali.fzhhl.top/Article/details/gtcvkkltja.html

Ruby: x.length;  x.size
来源：http://dali.dashuyun.cn/Article/details/gthfhejcaz.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.ivvv.top/Article/details/gtrvnlqtet.html

[P05] 判断两个对象内容是否相等
来源：http://dali.hysaishi.cn/Article/details/gtjpeikbhc.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.hywenlv.cn/Article/details/gtsvlehtqv.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.dianchejie.cn/Article/details/gtehbozodr.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.zhijiandao.cn/Article/details/gtgvxnorjt.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.xuanzx.com/Article/details/gttnabkcog.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.havefunace.top/Article/details/gtfukvxfna.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.pycfn.com/Article/details/gtkujblkhp.html

Ruby: a == b
来源：http://dali.hywenlv.cn/Article/details/gthzmkkqzv.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.shangyingyoupin.top/Article/details/gtgkissbwc.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.wangdashe.top/Article/details/gtbjesdevu.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.wangshuangyany.cn/Article/details/gtsnibnotl.html

PHP:  if (empty($x)) {}
来源：http://dali.9152youxi.cn/Article/details/gtmdagcvoi.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.yj202588.top/Article/details/gtbykpqsao.html

TS:   if (x == null) {}
来源：http://dali.nanxinkj.top/Article/details/gttxaiheex.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.sxryk.cn/Article/details/gtwumdvqjb.html

Go:   if x == nil {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwzyuqgcq.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.chenjidiqi.icu/Article/details/gtybrjvjnq.html

C#:   if (x is null) {}
来源：http://dali.chenzaomai.com/Article/details/gtkzcmzmbc.html

[P07] 防抖与节流
来源：http://dali.yongpay.top/Article/details/gtcuzzhtfi.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.0kj1m.cn/Article/details/gtyaboqgrw.html

PHP:  // 手写时间戳比较
来源：http://dali.nwbrower.top/Article/details/gtwegypazq.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.ydzc1.top/Article/details/gtfrqeyjdb.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hongshengwenyu.top/Article/details/gtncicoovp.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjgayleky.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrnfhgvpk.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.mhx1999.top/Article/details/gteeuuihde.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.zycfv.cn/Article/details/gtjyfwvvqe.html

[P08] 处理浮点精度问题
来源：http://dali.yj20258.top/Article/details/gtbvueukeu.html


<!-- 参考信息 -->