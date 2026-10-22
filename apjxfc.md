代发 wailian999

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jbynvgzn.html

[M01] 读取命令行参数
来源：http://dali.316326.xyz/Article/details/gt2lmodghmt.html

Py:   sys.argv[1:]
来源：http://dali.xziqi.cn/Article/details/gt2izqcdfsb.html

PHP:  $argv;  $argc;
来源：http://dali.yj20258888.top/Article/details/gt2upqwgikt.html

JS:   process.argv.slice(2)
来源：http://dali.jiagoushi.top/Article/details/gt2udqbqjzr.html

TS:   process.argv.slice(2)
来源：http://dali.wangdashe.top/Article/details/gt2fmqeshxk.html

Java: args 数组（main 方法参数）
来源：http://dali.cucudq.cn/Article/details/gt2zdsjvnhu.html

Go:   os.Args[1:]
来源：http://dali.cashguo.top/Article/details/gt2gmeiicux.html

Ruby: ARGV
来源：http://dali.shuidangran.top/Article/details/gt2vedndysy.html

C#:   args 数组（Main 方法参数）
来源：http://dali.shuidangran.top/Article/details/gt2fzfxajtn.html

[M02] 读取环境变量
来源：http://dali.bjfxy.top/Article/details/gt2tqwaknao.html

Py:   os.environ.get("HOME")
来源：http://dali.nwbrower.top/Article/details/gt2mczaedyv.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zycfv.cn/Article/details/gt2titzcyzd.html

JS:   process.env.HOME
来源：http://dali.xuetiantiany.cn/Article/details/gt2diskftce.html

TS:   process.env.HOME
来源：http://dali.iojbl.cn/Article/details/gt2ahjjulph.html

Java: System.getenv("HOME")
来源：http://dali.jqgufenzy.top/Article/details/gt2cywzhkry.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.jlsjyb.cn/Article/details/gt2yjoqkdsr.html

Ruby: ENV["HOME"]
来源：http://dali.gogol.net.cn/Article/details/gt2rxyhjzro.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.jinqigufen.top/Article/details/gt2nrapixud.html

[M03] 执行外部命令
来源：http://dali.shuidangran.top/Article/details/gt2xwopmdhi.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhengqikj.top/Article/details/gt2cbhxetbd.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.jianghu66.top/Article/details/gt2ihnxhiou.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.yanxiufei.cn/Article/details/gt2sjrjkexe.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.yj20258888.top/Article/details/gt2ukgvsauo.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.gzhubu.top/Article/details/gt2zdcwtkch.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.tian-w.cn/Article/details/gt2lfvbuuxb.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.yangfankeji.com/Article/details/gt2yeqgovla.html

C#:   Process.Start("ls", "-l");
来源：http://dali.quarkkingdee.top/Article/details/gt2ccvgutdp.html

[M04] 获取当前工作目录
来源：http://dali.316326.xyz/Article/details/gt2axumdzel.html

Py:   os.getcwd()
来源：http://dali.aizwys.cn/Article/details/gt2owkhrtqn.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2wpdhxvqc.html

JS:   process.cwd()
来源：http://dali.fengsongda.top/Article/details/gt2nuoctnkk.html

TS:   process.cwd()
来源：http://dali.sysykeji.top/Article/details/gt2xvzgigxk.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.yj20258888.top/Article/details/gt2uwvtokpb.html

Go:   os.Getwd()
来源：http://dali.dashuyun.cn/Article/details/gt2rpgyohqx.html

Ruby: Dir.pwd
来源：http://dali.yuanzhike.top/Article/details/gt2ortemvjx.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.xinyue.icu/Article/details/gt2vchaqtjd.html

[M05] 设置退出码
来源：http://dali.chenlongwang.top/Article/details/gt2yulfnkev.html

Py:   sys.exit(1)
来源：http://dali.gzhubu.top/Article/details/gt2sdbgrcmu.html

PHP:  exit(1);
来源：http://dali.vqdsnc.cn/Article/details/gt2iyoxffip.html

JS:   process.exit(1)
来源：http://dali.zhiwuduotai.top/Article/details/gt2igiqezdr.html

TS:   process.exit(1)
来源：http://dali.ybcxt.top/Article/details/gt2alatykrl.html

Java: System.exit(1)
来源：http://dali.svipenyu.cn/Article/details/gt2jsmvttlw.html

Go:   os.Exit(1)
来源：http://dali.ppjwa.cn/Article/details/gt2mhwpppnf.html

Ruby: exit 1
来源：http://dali.mhx1999.top/Article/details/gt2pinihxwy.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.dashuyun.cn/Article/details/gt2yschvaso.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2wyedoppj.html

Py:   print("err", file=sys.stderr)
来源：http://dali.chenlongwang.top/Article/details/gt2yuhcspvq.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.iojbl.cn/Article/details/gt2euylxiiy.html

JS:   console.error("err")
来源：http://dali.kuanghao11.cn/Article/details/gt2qydrxojl.html

TS:   console.error("err")
来源：http://dali.hfpthk.cn/Article/details/gt2yaqbdici.html

Java: System.err.println("err")
来源：http://dali.sufxvd.cn/Article/details/gt2uqkikytn.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.redwolf501.top/Article/details/gt2zqmdblyn.html

Ruby: warn "err"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ucdoiazc.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.chenzaomai.com/Article/details/gt2iyirxzsf.html

[M07] 判断是否为主入口
来源：http://dali.9152youxi.cn/Article/details/gt2eytjllut.html

Py:   if __name__ == "__main__":
来源：http://dali.sweek.top/Article/details/gt2narrfxer.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.xinyue.icu/Article/details/gt2ssrnclge.html

JS:   require.main === module
来源：http://dali.cucudq.cn/Article/details/gt2leughpwf.html

TS:   require.main === module
来源：http://dali.nanxinkj.top/Article/details/gt2xltmzsxf.html

Java: public static void main(String[] args)
来源：http://dali.aizwys.cn/Article/details/gt2tluhrlyr.html

Go:   func main()
来源：http://dali.jinqigfzy.top/Article/details/gt2dlxyrkkm.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.smart0.xyz/Article/details/gt2zovexlrj.html

C#:   static void Main(string[] args)
来源：http://dali.cdnleiting.top/Article/details/gt2qceeekgp.html

[M08] 获取系统与运行时信息
来源：http://dali.guowangkeji.top/Article/details/gt2zdhoswvs.html

Py:   platform.system();  platform.python_version()
来源：http://dali.yuxming.cn/Article/details/gt2bbptmlkg.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.hfpthk.cn/Article/details/gt2pwegymgz.html

JS:   process.platform;  process.version
来源：http://dali.xuetiantiany.cn/Article/details/gt2zogqxrqw.html

TS:   process.platform;  process.version
来源：http://dali.tian-w.cn/Article/details/gt2yntcpgnm.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.cucudq.cn/Article/details/gt2lgeixmob.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.gzhubu.top/Article/details/gt2uiysfsqp.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.yongpay.top/Article/details/gt2pjgclafg.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.0kj1m.cn/Article/details/gt2osdxyzli.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gt2npucammv.html

N. 数据结构与算法
来源：http://dali.fzhhl.top/Article/details/gt2ornoucde.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gt2ycjzmfit.html

[N01] 二分查找（有序数组）
来源：http://dali.daxiang520.top/Article/details/gt2uqsjjqdw.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.ybcxt.top/Article/details/gt2saqxmlis.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.c1oappe.top/Article/details/gt2xsohkeso.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jinqigfzy.top/Article/details/gt2oydjnoml.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jinqigufen.top/Article/details/gt2usfbpcku.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhixingplan.top/Article/details/gt2yusxfilo.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.hnqzz.top/Article/details/gt2wyrttlqz.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhongyouzk.top/Article/details/gt2wdzucjxv.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.jqgfzy.top/Article/details/gt2fpidydem.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zdqjudy.top/Article/details/gt2uaavaeqi.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.chenlongwang.top/Article/details/gt2nrpaaljt.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.ehwqpu.com/Article/details/gt2xtncvurg.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.aizwys.cn/Article/details/gt2gvdfckdp.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2venyzmel.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.snrcjt.cn/Article/details/gt2ggortazx.html

Go:   slices.Sort(arr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2spkiimat.html

Ruby: arr.sort
来源：http://dali.shzxlz.cn/Article/details/gt2xtkirsqu.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qlindbic.html

[N03] 快速排序（分治示例）
来源：http://dali.cdnleiting.top/Article/details/gt2dkynbwdf.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.yuxming.cn/Article/details/gt2gjcdgpyr.html

PHP:  // 递归实现，或用 usort
来源：http://dali.guannengcc.top/Article/details/gt2uroeowsq.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.shuidangran.top/Article/details/gt2yeunqdxn.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.cqqwz.cn/Article/details/gt2sxeguivs.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.yongpay.top/Article/details/gt2gzzqtexd.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.guowangkeji.top/Article/details/gt2xttprbup.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.shangyingyoupin.top/Article/details/gt2awemhtqu.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.cucudq.cn/Article/details/gt2sobjximy.html

[N04] 斐波那契数列
来源：http://dali.shanyushiyangtech.top/Article/details/gt2poiswcbe.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.tianlin.xyz/Article/details/gt2naywrhac.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.haohaochexian.top/Article/details/gt2pojbhgmw.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.hnxiangtu.top/Article/details/gt2maxjvedv.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jianghu66.top/Article/details/gt2jrjaztgx.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.havefunace.top/Article/details/gt2sbxqdejf.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.jqgfzy.top/Article/details/gt2gaxnvkot.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.yj20258.top/Article/details/gt2tuagwghw.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.cdnleiting.top/Article/details/gt2qmlgkvtk.html

[N05] 最大公约数
来源：http://dali.ivvv.top/Article/details/gt2tnubcbrp.html

Py:   math.gcd(a, b)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fojihyoi.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.svipenyu.cn/Article/details/gt2adobvnso.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.birdmap.top/Article/details/gt2kiapuzgx.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.ivvv.top/Article/details/gt2ixshebre.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.cashguo.top/Article/details/gt2xbmhzval.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhoulong.xyz/Article/details/gt2beositdx.html

Ruby: a.gcd(b)
来源：http://dali.tanke756.top/Article/details/gt2ecaxocar.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.aibaodan.cn/Article/details/gt2hsdqjwri.html

[N06] 判断回文字符串
来源：http://dali.dianchejie.cn/Article/details/gt2cqqybglj.html

Py:   s == s[::-1]
来源：http://dali.ydzc1.top/Article/details/gt2jmpckqvt.html

PHP:  $s === strrev($s);
来源：http://dali.shuidangran.top/Article/details/gt2iofbmilq.html

JS:   s === [...s].reverse().join("")
来源：http://dali.guowangkeji.top/Article/details/gt2rtpherrc.html

TS:   s === [...s].reverse().join("")
来源：http://dali.jinqigufen.top/Article/details/gt2wwjvsnfy.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhiwuduotai.top/Article/details/gt2bfmgcekx.html

Go:   // 双指针从两端比较
来源：http://dali.ybcxt.top/Article/details/gt2wevnbpbx.html

Ruby: s == s.reverse
来源：http://dali.fzhhl.top/Article/details/gt2jmvjihoh.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.xylfe.cn/Article/details/gt2ttscknmk.html

[N07] 两数之和（返回下标）
来源：http://dali.pycfn.com/Article/details/gt2kqfcndyf.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.yanxiufei.cn/Article/details/gt2crudcfwh.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.nanxinkj.top/Article/details/gt2utbtlpze.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.guannengcc.top/Article/details/gt2hhujukqz.html

TS:   // 手写 Map<string, number>
来源：http://dali.kuanghao11.cn/Article/details/gt2deekqctn.html

Java: // 手写 HashMap
来源：http://dali.jqgufenzy.top/Article/details/gt2upkcqloc.html

Go:   // 手写 map[int]int
来源：http://dali.yj20258888.top/Article/details/gt2vqqcwewi.html

Ruby: // 手写 Hash
来源：http://dali.gotoacloud.top/Article/details/gt2tisnaefg.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.iojbl.cn/Article/details/gt2fksuervy.html

[N08] 生成全排列
来源：http://dali.zhongyouzk.top/Article/details/gt2juwmjzzp.html

Py:   itertools.permutations(arr)
来源：http://dali.zhengqikj.top/Article/details/gt2shqvvgwm.html

PHP:  // 手写递归交换
来源：http://dali.feifeiyinyue.top/Article/details/gt2khgfdgah.html

JS:   // 手写回溯递归
来源：http://dali.yj20258888.top/Article/details/gt2cqnxloqm.html

TS:   // 手写回溯递归
来源：http://dali.yueranfly.top/Article/details/gt2lglpdmav.html

Java: // 手写回溯递归
来源：http://dali.shzxlz.cn/Article/details/gt2ggqbcszb.html

Go:   // 手写回溯递归
来源：http://dali.guowangkeji.top/Article/details/gt2lihjtwoh.html

Ruby: arr.permutation.to_a
来源：http://dali.gotoacloud.top/Article/details/gt2wpwbzyww.html

C#:   // 手写回溯递归
来源：http://dali.yuanzhike.top/Article/details/gt2jcflybsr.html

[N09] 栈与队列
来源：http://dali.jinqigufen.top/Article/details/gt2srcopugu.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.yanxiufei.cn/Article/details/gt2njqtbvbf.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.ehwqpu.com/Article/details/gt2hwcaiamz.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.daxiang520.top/Article/details/gt2piauexnv.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.chenjidiqi.icu/Article/details/gt2smstfcmo.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.hfpthk.cn/Article/details/gt2zeiokiws.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.jinqigufen.top/Article/details/gt2rnasaefk.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.hnqzz.top/Article/details/gt2wyicmmhk.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.tianlin.xyz/Article/details/gt2yarktboq.html

[N10] 链表节点定义
来源：http://dali.yuanzhike.top/Article/details/gt2sjvnvqrc.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kqlsevce.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhengqikj.top/Article/details/gt2nzdqeros.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.kuanghao11.cn/Article/details/gt2gqvnuhsu.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nhegpdih.html

Java: class Node { int v; Node next; }
来源：http://dali.zycfv.cn/Article/details/gt2nzcyzotf.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.guowangkeji.top/Article/details/gt2bsgmlvbw.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.yangfankeji.com/Article/details/gt2yusdxafh.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zdqjudy.top/Article/details/gt2lxsoqwua.html

[N11] 二叉树中序遍历
来源：http://dali.quarkkingdee.top/Article/details/gt2obwidpqo.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhoulong.xyz/Article/details/gt2pqknmzup.html

PHP:  // 手写递归函数
来源：http://dali.quarkkingdee.top/Article/details/gt2usdbfpys.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.ydzc1.top/Article/details/gt2dujsrtiz.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.svipenyu.cn/Article/details/gt2pijohxlh.html

Java: // 手写递归
来源：http://dali.quarkkingdee.top/Article/details/gt2xeporieh.html

Go:   // 手写递归
来源：http://dali.0kj1m.cn/Article/details/gt2smlyiwnd.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.bjfxy.top/Article/details/gt2chrfrpyt.html

C#:   // 手写递归
来源：http://dali.316326.xyz/Article/details/gt2ranlqvyt.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhiwuduotai.top/Article/details/gt2alobtzbk.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.nanxuanxn.top/Article/details/gt2gdchzgkb.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.meibo888.top/Article/details/gt2zsxrnfhz.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.hnqzz.top/Article/details/gt2qftsurak.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yanxiufei.cn/Article/details/gt2xoxluukq.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.316326.xyz/Article/details/gt2uowaxexp.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.svipenyu.cn/Article/details/gt2wmasrvkl.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.jinqigufen.top/Article/details/gt2nyctckto.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yvedp.cn/Article/details/gt2vksstuqr.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gt2pjhgsvan.html

O. 并发与异步
来源：http://dali.yanxiufei.cn/Article/details/gt2vnrcldup.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gt2fkvnybfa.html

[O01] 启动一个线程
来源：http://dali.cheryme.top/Article/details/gt2avdavrqe.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2okgbtwqt.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zycfv.cn/Article/details/gt2agmxvltn.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.fzhhl.top/Article/details/gt2wufvjxoq.html

TS:   // 同 JS
来源：http://dali.yvedp.cn/Article/details/gt2lvgufcqh.html

Java: new Thread(() -> f()).start()
来源：http://dali.jlsjyb.cn/Article/details/gt2gysmbkjz.html

Go:   go f()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2datidyfo.html

Ruby: Thread.new { f }
来源：http://dali.jqgufenzy.top/Article/details/gt2hzmrynoa.html

C#:   Task.Run(() => F());
来源：http://dali.zhengqikj.top/Article/details/gt2irxlylfc.html

[O02] 使用线程池
来源：http://dali.havefunace.top/Article/details/gt2uwncjgun.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.haohaochexian.top/Article/details/gt2fulhremx.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.hysaishi.cn/Article/details/gt2vyqamqvc.html

JS:   // worker_threads 线程池
来源：http://dali.chenlongwang.top/Article/details/gt2qwwclkgf.html

TS:   // worker_threads 线程池
来源：http://dali.gaohongyu789.top/Article/details/gt2alclsvtz.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.sysykeji.top/Article/details/gt2kyknfudi.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.xinyue.icu/Article/details/gt2slrxfktl.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.daxiang520.top/Article/details/gt2zjhcrfut.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.haohaochexian.top/Article/details/gt2jroyfneb.html

[O03] 加锁保护共享数据
来源：http://dali.yvedp.cn/Article/details/gt2sxdmeoeg.html

Py:   with lock: shared += 1
来源：http://dali.fengsongda.top/Article/details/gt2ackxccgz.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.xylfe.cn/Article/details/gt2zmqkivvj.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.fengsongda.top/Article/details/gt2fchhkupp.html

TS:   // 同 JS
来源：http://dali.snrcjt.cn/Article/details/gt2pmiezllb.html

Java: synchronized (this) { shared++; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vgubiibg.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.xylfe.cn/Article/details/gt2vogqfruo.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.shuidangran.top/Article/details/gt2ixskelum.html

C#:   lock (gate) { shared++; }
来源：http://dali.quarkkingdee.top/Article/details/gt2rzgsowoo.html

[O04] 定义异步函数并等待
来源：http://dali.wangshuangyany.cn/Article/details/gt2ilwgmauk.html

Py:   async def f():⏎    await g()
来源：http://dali.shzxlz.cn/Article/details/gt2rcssgwyk.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.jiagoushi.top/Article/details/gt2pbzjctjc.html

JS:   async function f() { await g(); }
来源：http://dali.yuanzhike.top/Article/details/gt2stbkzndo.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.ydzc1.top/Article/details/gt2ysbqxkwn.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.jqgufenzy.top/Article/details/gt2piuhuuel.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.snrcjt.cn/Article/details/gt2xepjwpmc.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.sysykeji.top/Article/details/gt2xpzanzlj.html

C#:   async Task F() { await G(); }
来源：http://dali.ydzc1.top/Article/details/gt2hxurffjv.html

[O05] 并发执行并等待全部完成
来源：http://dali.nwbrower.top/Article/details/gt2tpmkylnk.html

Py:   asyncio.gather(*tasks)
来源：http://dali.cdnleiting.top/Article/details/gt2rwivhhxu.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.xinyue.icu/Article/details/gt2slywlptf.html

JS:   await Promise.all(tasks)
来源：http://dali.pycfn.com/Article/details/gt2gxgpxvgf.html

TS:   await Promise.all(tasks)
来源：http://dali.yonumen.top/Article/details/gt2qbfshunp.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhixingplan.top/Article/details/gt2sohoirvc.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.sysykeji.top/Article/details/gt2iyijzbhr.html

Ruby: threads.map(&:join)
来源：http://dali.zhengqikj.top/Article/details/gt2abrpqtxb.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.tianlin.xyz/Article/details/gt2xcuvqmcg.html

[O06] 使用进程池
来源：http://dali.dianchejie.cn/Article/details/gt2xcdmynly.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.daria6918.cn/Article/details/gt2ezibohpl.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.smart0.xyz/Article/details/gt2yhxzplei.html

JS:   // child_process / cluster 模块
来源：http://dali.jqgfzy.top/Article/details/gt2espkhfhs.html

TS:   // child_process / cluster 模块
来源：http://dali.gotoacloud.top/Article/details/gt2icxodjqo.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.jiagoushi.top/Article/details/gt2pwlzivwu.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.yvedp.cn/Article/details/gt2zqeyoizv.html

Ruby: // fork 块
来源：http://dali.jinqigufen.top/Article/details/gt2sctcwvwl.html

C#:   Parallel.For
来源：http://dali.0kj1m.cn/Article/details/gt2qpggsryc.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gt2dnfnfjnn.html

P. 常用工具函数
来源：http://dali.jianghu66.top/Article/details/gt2fkpdtoeb.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gt2ieygndsp.html

[P01] 生成 UUID
来源：http://dali.xylfe.cn/Article/details/gt2vupgpdqi.html

Py:   str(uuid.uuid4())
来源：http://dali.ppjwa.cn/Article/details/gt2ebydqkrm.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.yueranfly.top/Article/details/gt2yudxblwm.html

JS:   crypto.randomUUID()
来源：http://dali.gogol.net.cn/Article/details/gt2lnbtybiu.html

TS:   crypto.randomUUID()
来源：http://dali.sxryk.cn/Article/details/gt2kxdhdboa.html

Java: UUID.randomUUID().toString()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mwwnoqlu.html

Go:   // 用 github.com/google/uuid
来源：http://dali.cashguo.top/Article/details/gt2reppomop.html

Ruby: SecureRandom.uuid
来源：http://dali.dashuyun.cn/Article/details/gt2idtkdgxp.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.redwolf501.top/Article/details/gt2hyozphcy.html

[P02] MD5 / SHA256 摘要
来源：http://dali.sweek.top/Article/details/gt2grevhxrv.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2aikjfkmk.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.cqqwz.cn/Article/details/gt2yfbmlbfm.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.jinqigfzy.top/Article/details/gt2yazbhcke.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zdqjudy.top/Article/details/gt2gwzurnhx.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.iojbl.cn/Article/details/gt2nhuhvegh.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.gogol.net.cn/Article/details/gt2abrrhngr.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.meibo888.top/Article/details/gt2sfhmmsxw.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.jqgfzy.top/Article/details/gt2kyluboyn.html

[P03] 生成短随机字符串
来源：http://dali.vqdsnc.cn/Article/details/gt2sbzqichw.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.pengpengdd.cyou/Article/details/gt2xsfjzjvt.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.cqqwz.cn/Article/details/gt2fckutlfp.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gvdbpmsd.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.smart0.xyz/Article/details/gt2ffleuqbn.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.tian-w.cn/Article/details/gt2ljbbjtkr.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.yueranfly.top/Article/details/gt2luyaufxr.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.xinyue.icu/Article/details/gt2fftarnlc.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.jinqigufen.top/Article/details/gt2hhtlldrt.html

[P04] 求长度
来源：http://dali.hnqzz.top/Article/details/gt2ovbgrzhs.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.0kj1m.cn/Article/details/gt2ijjjprjq.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.kuanghao11.cn/Article/details/gt2gxmretuo.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.chenjidiqi.icu/Article/details/gt2cakwngxs.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yonumen.top/Article/details/gt2oqziuhtr.html

Java: list.size();  map.size();  s.length()
来源：http://dali.hnxiangtu.top/Article/details/gt2cyradfoe.html

Go:   len(arr);  len(m)
来源：http://dali.daxiang520.top/Article/details/gt2rxxcqnnb.html

Ruby: x.length;  x.size
来源：http://dali.meibo888.top/Article/details/gt2lxqcpmwf.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.yuxming.cn/Article/details/gt2ujngkqxq.html

[P05] 判断两个对象内容是否相等
来源：http://dali.guowangkeji.top/Article/details/gt2cxuqznnh.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.haohaochexian.top/Article/details/gt2ckmvlhqt.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cuqqxjxx.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.c1oappe.top/Article/details/gt2exbftpuh.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.andypj.xyz/Article/details/gt2zufszejc.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.cheryme.top/Article/details/gt2woitulks.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.andypj.xyz/Article/details/gt2txesayxw.html

Ruby: a == b
来源：http://dali.hammf.cn/Article/details/gt2fhwyejfy.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.cheryme.top/Article/details/gt2jnpkygzl.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.yanxiufei.cn/Article/details/gt2jputzjpc.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.xinyue.icu/Article/details/gt2jcepwaga.html

PHP:  if (empty($x)) {}
来源：http://dali.cucudq.cn/Article/details/gt2acobyzgf.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.yangfankeji.com/Article/details/gt2cixcpbet.html

TS:   if (x == null) {}
来源：http://dali.xinyue.icu/Article/details/gt2asaznakd.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.sysykeji.top/Article/details/gt2eljbznds.html

Go:   if x == nil {}
来源：http://dali.nwbrower.top/Article/details/gt2mkuhrala.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.yonumen.top/Article/details/gt2zlatbogd.html

C#:   if (x is null) {}
来源：http://dali.ydzc1.top/Article/details/gt2jcplqswd.html

[P07] 防抖与节流
来源：http://dali.sxryk.cn/Article/details/gt2xcddvtdd.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.quarkkingdee.top/Article/details/gt2mupvvqcn.html


<!-- 参考信息 -->