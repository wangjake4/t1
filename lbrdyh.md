代发 wailian999

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.pycfn.com/Article/details/gtanxozwpe.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.ydzc1.top/Article/details/gtlvulcbqx.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtnhfiaeih.html

M. 命令行 / 进程 / 环境
来源：http://dali.gzhubu.top/Article/details/gtsyvghres.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtsohnplqh.html

[M01] 读取命令行参数
来源：http://dali.haohaochexian.top/Article/details/gtnalpfril.html

Py:   sys.argv[1:]
来源：http://dali.gogol.net.cn/Article/details/gtavamueob.html

PHP:  $argv;  $argc;
来源：http://dali.zycfv.cn/Article/details/gtvczussof.html

JS:   process.argv.slice(2)
来源：http://dali.jiagoushi.top/Article/details/gtcpyvzsoo.html

TS:   process.argv.slice(2)
来源：http://dali.shzxlz.cn/Article/details/gtinkawsdx.html

Java: args 数组（main 方法参数）
来源：http://dali.aibaodan.cn/Article/details/gthyzgchfk.html

Go:   os.Args[1:]
来源：http://dali.xinyue.icu/Article/details/gtefpcwlki.html

Ruby: ARGV
来源：http://dali.gaohongyu789.top/Article/details/gtukmlzhou.html

C#:   args 数组（Main 方法参数）
来源：http://dali.cqqwz.cn/Article/details/gtjqmygglm.html

[M02] 读取环境变量
来源：http://dali.jianghu66.top/Article/details/gtseptwpzn.html

Py:   os.environ.get("HOME")
来源：http://dali.cucudq.cn/Article/details/gthiztcxaj.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.haohaochexian.top/Article/details/gtlcxmujke.html

JS:   process.env.HOME
来源：http://dali.sxryk.cn/Article/details/gtvplnbfbc.html

TS:   process.env.HOME
来源：http://dali.nanxinkj.top/Article/details/gtzhbgdxhc.html

Java: System.getenv("HOME")
来源：http://dali.yuanzhike.top/Article/details/gtgdmvmmer.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.aizwys.cn/Article/details/gtdfnkljmj.html

Ruby: ENV["HOME"]
来源：http://dali.iojbl.cn/Article/details/gtcwqfunqh.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.daxiang520.top/Article/details/gthxopfrqp.html

[M03] 执行外部命令
来源：http://dali.bjfxy.top/Article/details/gttxhstipc.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.gaohongyu789.top/Article/details/gttmcgugwz.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.nanxuanxn.top/Article/details/gtghieyuhz.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.vqdsnc.cn/Article/details/gtcfonbifj.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.tian-w.cn/Article/details/gtwnnbpacd.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.tian-w.cn/Article/details/gtzhaodnbi.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.redwolf501.top/Article/details/gtyuoghgug.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.kuanghao11.cn/Article/details/gtzdsugtbx.html

C#:   Process.Start("ls", "-l");
来源：http://dali.xziqi.cn/Article/details/gtxpahkurx.html

[M04] 获取当前工作目录
来源：http://dali.sweek.top/Article/details/gtoxlroqfa.html

Py:   os.getcwd()
来源：http://dali.gaohongyu789.top/Article/details/gtxgndcrcx.html

PHP:  getcwd();
来源：http://dali.tianlin.xyz/Article/details/gtthypwhyx.html

JS:   process.cwd()
来源：http://dali.jqgfzy.top/Article/details/gtdfhogvqu.html

TS:   process.cwd()
来源：http://dali.birdmap.top/Article/details/gthurwkcmo.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.chenjidiqi.icu/Article/details/gtaihiogkb.html

Go:   os.Getwd()
来源：http://dali.jlsjyb.cn/Article/details/gtmmtpmryu.html

Ruby: Dir.pwd
来源：http://dali.zhengqikj.top/Article/details/gthkktpion.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.dianchejie.cn/Article/details/gtrpiungoo.html

[M05] 设置退出码
来源：http://dali.yvedp.cn/Article/details/gtyfcxyfzb.html

Py:   sys.exit(1)
来源：http://dali.gaohongyu789.top/Article/details/gthwstdkhd.html

PHP:  exit(1);
来源：http://dali.yangfankeji.com/Article/details/gtttwwjsgr.html

JS:   process.exit(1)
来源：http://dali.xuanzx.com/Article/details/gtsmhvdvhn.html

TS:   process.exit(1)
来源：http://dali.xinyue.icu/Article/details/gtopqbmrwx.html

Java: System.exit(1)
来源：http://dali.tanke756.top/Article/details/gtjrbpwzbo.html

Go:   os.Exit(1)
来源：http://dali.gaohongyu789.top/Article/details/gtcujpmxnz.html

Ruby: exit 1
来源：http://dali.hammf.cn/Article/details/gtmgmtnevs.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.fzhhl.top/Article/details/gtjuxoskep.html

[M06] 向标准错误输出
来源：http://dali.mhx1999.top/Article/details/gtgaptqove.html

Py:   print("err", file=sys.stderr)
来源：http://dali.daria6918.cn/Article/details/gtrnfdghxr.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.sweek.top/Article/details/gtvpmukdxn.html

JS:   console.error("err")
来源：http://dali.daria6918.cn/Article/details/gtrbipriff.html

TS:   console.error("err")
来源：http://dali.ppjwa.cn/Article/details/gtxukmzthx.html

Java: System.err.println("err")
来源：http://dali.svipenyu.cn/Article/details/gtugrnpqzp.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkmqoncrj.html

Ruby: warn "err"
来源：http://dali.jinghuilouyu.cn/Article/details/gtnqwchyuk.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.gaohongyu789.top/Article/details/gtlbuonjxo.html

[M07] 判断是否为主入口
来源：http://dali.zhoulong.xyz/Article/details/gtdnajuhtl.html

Py:   if __name__ == "__main__":
来源：http://dali.cucudq.cn/Article/details/gtahzyldzr.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.tian-w.cn/Article/details/gtycipkwwi.html

JS:   require.main === module
来源：http://dali.sweek.top/Article/details/gtaisewzgp.html

TS:   require.main === module
来源：http://dali.tianlin.xyz/Article/details/gtzsumuvqm.html

Java: public static void main(String[] args)
来源：http://dali.hongshengwenyu.top/Article/details/gthhyqmftj.html

Go:   func main()
来源：http://dali.jqgufenzy.top/Article/details/gtqydmpgll.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.shzxlz.cn/Article/details/gtonyqwozm.html

C#:   static void Main(string[] args)
来源：http://dali.jqgufenzy.top/Article/details/gtfpaokxzc.html

[M08] 获取系统与运行时信息
来源：http://dali.pycfn.com/Article/details/gtbjlazmil.html

Py:   platform.system();  platform.python_version()
来源：http://dali.guannengcc.top/Article/details/gtedwgttae.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.yvedp.cn/Article/details/gtbgrhrwgd.html

JS:   process.platform;  process.version
来源：http://dali.ivvv.top/Article/details/gtexfikboi.html

TS:   process.platform;  process.version
来源：http://dali.yuanzhike.top/Article/details/gtjvlgwrja.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnlinndvq.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.gaohongyu789.top/Article/details/gttnbwkuhm.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.sysykeji.top/Article/details/gtduivgchq.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.gzhubu.top/Article/details/gtcgskhywv.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtwprxuxxk.html

N. 数据结构与算法
来源：http://dali.yonumen.top/Article/details/gtifashkde.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gteggaaqkh.html

[N01] 二分查找（有序数组）
来源：http://dali.aizwys.cn/Article/details/gteagpnfzh.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.wangdashe.top/Article/details/gtseuiwhhm.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.cheryme.top/Article/details/gtdeutezhr.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yangfankeji.com/Article/details/gtsxxacdtk.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.xuetiantiany.cn/Article/details/gtjzznlmze.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.chenzaomai.com/Article/details/gtbpykansc.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.316326.xyz/Article/details/gtxmyfjmdw.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zdqjudy.top/Article/details/gtkbotrcqg.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.yonumen.top/Article/details/gtolvvhids.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.cqqwz.cn/Article/details/gtxapkajvv.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhengqikj.top/Article/details/gtxjzxojwi.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.dianchejie.cn/Article/details/gtkgczulsi.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.snrcjt.cn/Article/details/gtfgidztpl.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gtilwzqmrx.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.sufxvd.cn/Article/details/gthkblndaj.html

Go:   slices.Sort(arr)
来源：http://dali.pycfn.com/Article/details/gtxulwenif.html

Ruby: arr.sort
来源：http://dali.cucudq.cn/Article/details/gtcbiilbal.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.guowangkeji.top/Article/details/gtylekqmsb.html

[N03] 快速排序（分治示例）
来源：http://dali.sysykeji.top/Article/details/gtuhlgmthx.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.hywenlv.cn/Article/details/gtubelbadg.html

PHP:  // 递归实现，或用 usort
来源：http://dali.sxryk.cn/Article/details/gtfwqduoje.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.xziqi.cn/Article/details/gtxrvppffc.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.haohaochexian.top/Article/details/gtqnctmkrh.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.guowangkeji.top/Article/details/gtdgmqxoyb.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.shuidangran.top/Article/details/gtesuvvfip.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.yvedp.cn/Article/details/gtujlbdavw.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.jyoumei.cn/Article/details/gtilvctift.html

[N04] 斐波那契数列
来源：http://dali.chenjidiqi.icu/Article/details/gtwqaqyeys.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.shzxlz.cn/Article/details/gtxvqfhdyq.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.cqqwz.cn/Article/details/gtdwibtwag.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.shzxlz.cn/Article/details/gtslwqfsmh.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.smart0.xyz/Article/details/gtixjicfox.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.guowangkeji.top/Article/details/gtmqovphpw.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.hysaishi.cn/Article/details/gtrqedjuzq.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.vqdsnc.cn/Article/details/gteqswuucx.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.tian-w.cn/Article/details/gtgohxbdlu.html

[N05] 最大公约数
来源：http://dali.jianghu66.top/Article/details/gtlubaykuu.html

Py:   math.gcd(a, b)
来源：http://dali.hysaishi.cn/Article/details/gtcgxadoih.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.hfpthk.cn/Article/details/gtmpyvwild.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yonumen.top/Article/details/gtaztbfulg.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.haohaochexian.top/Article/details/gtpuglxkfs.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.quarkkingdee.top/Article/details/gtnwwzrypx.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhongyouzk.top/Article/details/gtcshlzmhi.html

Ruby: a.gcd(b)
来源：http://dali.ivvv.top/Article/details/gtjycvskuj.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.shuidangran.top/Article/details/gtxyhwvfkv.html

[N06] 判断回文字符串
来源：http://dali.xuanzx.com/Article/details/gtghbrkegd.html

Py:   s == s[::-1]
来源：http://dali.zhongyouzk.top/Article/details/gtxflpszcc.html

PHP:  $s === strrev($s);
来源：http://dali.jiagoushi.top/Article/details/gtygrforjv.html

JS:   s === [...s].reverse().join("")
来源：http://dali.hfpthk.cn/Article/details/gthbeewzgv.html

TS:   s === [...s].reverse().join("")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxzajlvyt.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.cdnleiting.top/Article/details/gtwrwamfzj.html

Go:   // 双指针从两端比较
来源：http://dali.kuanghao11.cn/Article/details/gtzuehpzhm.html

Ruby: s == s.reverse
来源：http://dali.havefunace.top/Article/details/gttvpjgtqd.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.jinyuanbaomall.cn/Article/details/gthdbclwjr.html

[N07] 两数之和（返回下标）
来源：http://dali.c1oappe.top/Article/details/gtbydzuifx.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.jinqigufen.top/Article/details/gtwugzetfy.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.dashuyun.cn/Article/details/gtsppfrnuv.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.jinqigufen.top/Article/details/gttkinnelm.html

TS:   // 手写 Map<string, number>
来源：http://dali.jinqigufen.top/Article/details/gteqvdsekn.html

Java: // 手写 HashMap
来源：http://dali.cdnleiting.top/Article/details/gtvwajmqrj.html

Go:   // 手写 map[int]int
来源：http://dali.jyoumei.cn/Article/details/gtjmwsnjxv.html

Ruby: // 手写 Hash
来源：http://dali.gotoacloud.top/Article/details/gtirbqgfmb.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.andypj.xyz/Article/details/gtjzlhedqu.html

[N08] 生成全排列
来源：http://dali.pycfn.com/Article/details/gtjtnjkvoe.html

Py:   itertools.permutations(arr)
来源：http://dali.cdnleiting.top/Article/details/gtmeezjgle.html

PHP:  // 手写递归交换
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwdossdbj.html

JS:   // 手写回溯递归
来源：http://dali.yj20258888.top/Article/details/gtbirgqhvc.html

TS:   // 手写回溯递归
来源：http://dali.ivvv.top/Article/details/gtwymsohpf.html

Java: // 手写回溯递归
来源：http://dali.xuetiantiany.cn/Article/details/gtqvhbegpf.html

Go:   // 手写回溯递归
来源：http://dali.0kj1m.cn/Article/details/gtotexoqri.html

Ruby: arr.permutation.to_a
来源：http://dali.havefunace.top/Article/details/gtdybwzodc.html

C#:   // 手写回溯递归
来源：http://dali.zhixingplan.top/Article/details/gtxljfgxab.html

[N09] 栈与队列
来源：http://dali.hfpthk.cn/Article/details/gtdhxgbmbe.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.yuanzhike.top/Article/details/gtjjknwkzl.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.xuanzx.com/Article/details/gtksggzsjg.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.ydzc1.top/Article/details/gtrpqyfncj.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.svipenyu.cn/Article/details/gtjhajsdqm.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.andypj.xyz/Article/details/gtigcbcxfm.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.cucudq.cn/Article/details/gtthzyznop.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zycfv.cn/Article/details/gtcymrvcmv.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.guannengcc.top/Article/details/gtwvlftqjo.html

[N10] 链表节点定义
来源：http://dali.aibaodan.cn/Article/details/gtidozkhia.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.iojbl.cn/Article/details/gtaimljsny.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.chenzaomai.com/Article/details/gtbbiytlay.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.xuetiantiany.cn/Article/details/gtxvxlopia.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.jiagoushi.top/Article/details/gtllsoyyxo.html

Java: class Node { int v; Node next; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzjmilunu.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.fengsongda.top/Article/details/gthdpnlugw.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.xylfe.cn/Article/details/gtuwbunzul.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.xuanzx.com/Article/details/gtuxcitdhl.html

[N11] 二叉树中序遍历
来源：http://dali.chenlongwang.top/Article/details/gtintsoqvh.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.pengpengdd.cyou/Article/details/gtmxvlfczt.html

PHP:  // 手写递归函数
来源：http://dali.chenlongwang.top/Article/details/gtfbwcacft.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jianghu66.top/Article/details/gtipzutfyx.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.shuidangran.top/Article/details/gtrauvlsth.html

Java: // 手写递归
来源：http://dali.chenzaomai.com/Article/details/gtoktykhwf.html

Go:   // 手写递归
来源：http://dali.chenlongwang.top/Article/details/gtopiutrtk.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.guannengcc.top/Article/details/gtwlzuikmz.html

C#:   // 手写递归
来源：http://dali.aizwys.cn/Article/details/gtdolljwyl.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.daxiang520.top/Article/details/gtasoyjtjk.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.wangdashe.top/Article/details/gtkiuinuyd.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.hnqzz.top/Article/details/gtunxxvkpv.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.xziqi.cn/Article/details/gtnxhudzwn.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhengqikj.top/Article/details/gtpwrqemjh.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.guannengcc.top/Article/details/gtsitgqrum.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.9152youxi.cn/Article/details/gtizouqgvs.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.gogol.net.cn/Article/details/gthlybpsuy.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.shangyingyoupin.top/Article/details/gtmjmpgkkn.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtboedonti.html

O. 并发与异步
来源：http://dali.yueranfly.top/Article/details/gtgmgbvyru.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtgfjguvrp.html

[O01] 启动一个线程
来源：http://dali.hnxiangtu.top/Article/details/gtsxuwlafv.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.jinghuilouyu.cn/Article/details/gteftrchmd.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.0kj1m.cn/Article/details/gtftbrqyeu.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.aizwys.cn/Article/details/gtjgewvfgj.html

TS:   // 同 JS
来源：http://dali.guannengcc.top/Article/details/gtcyfilvhf.html

Java: new Thread(() -> f()).start()
来源：http://dali.hongshengwenyu.top/Article/details/gthqioodhy.html

Go:   go f()
来源：http://dali.fengsongda.top/Article/details/gtbpjidveq.html

Ruby: Thread.new { f }
来源：http://dali.chenzaomai.com/Article/details/gttanwynlt.html

C#:   Task.Run(() => F());
来源：http://dali.mhx1999.top/Article/details/gtyclumxvs.html

[O02] 使用线程池
来源：http://dali.bjfxy.top/Article/details/gtugofksca.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.guannengcc.top/Article/details/gtmpxacnkf.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.vqdsnc.cn/Article/details/gtvjqqhilx.html

JS:   // worker_threads 线程池
来源：http://dali.daria6918.cn/Article/details/gtsrjjgqst.html

TS:   // worker_threads 线程池
来源：http://dali.havefunace.top/Article/details/gtcztzomto.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsuezjgww.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.bjfxy.top/Article/details/gtsivtqvsb.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.chenzaomai.com/Article/details/gtzonbpigi.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.nwbrower.top/Article/details/gtzqaeaonj.html

[O03] 加锁保护共享数据
来源：http://dali.hfpthk.cn/Article/details/gtdbygrrly.html

Py:   with lock: shared += 1
来源：http://dali.andypj.xyz/Article/details/gtysyhucnz.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.nwbrower.top/Article/details/gtwepgcyud.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.sxryk.cn/Article/details/gtlnmowerv.html

TS:   // 同 JS
来源：http://dali.cheryme.top/Article/details/gtmbrwdpso.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gtjhfddqjs.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsiuoahik.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.pycfn.com/Article/details/gtnhiigevw.html

C#:   lock (gate) { shared++; }
来源：http://dali.xuanzx.com/Article/details/gteurbzpyc.html

[O04] 定义异步函数并等待
来源：http://dali.jinqigufen.top/Article/details/gtainbzkqi.html

Py:   async def f():⏎    await g()
来源：http://dali.gogol.net.cn/Article/details/gtcbqwxgax.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.birdmap.top/Article/details/gtcdovzozs.html

JS:   async function f() { await g(); }
来源：http://dali.tianlin.xyz/Article/details/gtgwxkbinc.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.gogol.net.cn/Article/details/gtrvhsxmtb.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.dashuyun.cn/Article/details/gtkctygbec.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.c1oappe.top/Article/details/gtslphrgwh.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.pengpengdd.cyou/Article/details/gtsdzqlgmk.html

C#:   async Task F() { await G(); }
来源：http://dali.yueranfly.top/Article/details/gtwtpjtzxl.html

[O05] 并发执行并等待全部完成
来源：http://dali.guannengcc.top/Article/details/gtpcpfemqx.html

Py:   asyncio.gather(*tasks)
来源：http://dali.sysykeji.top/Article/details/gtnlnnnugl.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.sxryk.cn/Article/details/gtwgxnxxoa.html

JS:   await Promise.all(tasks)
来源：http://dali.wangdashe.top/Article/details/gtalijejuo.html

TS:   await Promise.all(tasks)
来源：http://dali.cdnleiting.top/Article/details/gtghftzytz.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.meibo888.top/Article/details/gtfxyiacjr.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.ivvv.top/Article/details/gtojkmuabh.html

Ruby: threads.map(&:join)
来源：http://dali.jinqigufen.top/Article/details/gtstmhvucc.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.hywenlv.cn/Article/details/gtrkjhytya.html

[O06] 使用进程池
来源：http://dali.chenzaomai.com/Article/details/gtfqswbwgf.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.birdmap.top/Article/details/gthymzwejh.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.gzhubu.top/Article/details/gtffbujmbq.html

JS:   // child_process / cluster 模块
来源：http://dali.tanke756.top/Article/details/gtrzlvpswu.html

TS:   // child_process / cluster 模块
来源：http://dali.hongshengwenyu.top/Article/details/gttrhpdgib.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.sysykeji.top/Article/details/gtojccshce.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.ppjwa.cn/Article/details/gtqvauwuwk.html

Ruby: // fork 块
来源：http://dali.guannengcc.top/Article/details/gttppnpwkt.html

C#:   Parallel.For
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoyopsqfl.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtttomcbog.html

P. 常用工具函数
来源：http://dali.xziqi.cn/Article/details/gtgyrqvfuc.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtsznpmagt.html

[P01] 生成 UUID
来源：http://dali.sysykeji.top/Article/details/gtcoxxwfum.html

Py:   str(uuid.uuid4())
来源：http://dali.jianghu66.top/Article/details/gtvigreflp.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.fengsongda.top/Article/details/gtmagyglvq.html

JS:   crypto.randomUUID()
来源：http://dali.quarkkingdee.top/Article/details/gtgnjshxlt.html

TS:   crypto.randomUUID()
来源：http://dali.jyoumei.cn/Article/details/gtqbdteepl.html

Java: UUID.randomUUID().toString()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqdxvrrzo.html

Go:   // 用 github.com/google/uuid
来源：http://dali.ehwqpu.com/Article/details/gtrnihrgsu.html

Ruby: SecureRandom.uuid
来源：http://dali.dianchejie.cn/Article/details/gtybcffvbb.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtacbgqvwg.html

[P02] MD5 / SHA256 摘要
来源：http://dali.cdnleiting.top/Article/details/gtfvykjhpj.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.xylfe.cn/Article/details/gtewqcqckx.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.hfpthk.cn/Article/details/gtnwfksype.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.shangyingyoupin.top/Article/details/gtsjdhkzkm.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.xylfe.cn/Article/details/gtyjosemcg.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.nanxuanxn.top/Article/details/gtgmrrvakj.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.iojbl.cn/Article/details/gtcakuvyot.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.haohaochexian.top/Article/details/gtxlcfanys.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.chenzaomai.com/Article/details/gtadsatdkg.html

[P03] 生成短随机字符串
来源：http://dali.iojbl.cn/Article/details/gtpendndpt.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhongyouzk.top/Article/details/gtjsmqugof.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.chenzaomai.com/Article/details/gtgsmjrmfy.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.shuidangran.top/Article/details/gtalcdsrju.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.c1oappe.top/Article/details/gtetpfyzhu.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlarzhvsa.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.ehwqpu.com/Article/details/gtfepupunj.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.jinqigufen.top/Article/details/gtjbzlgimm.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.haohaochexian.top/Article/details/gtejwgjfzv.html

[P04] 求长度
来源：http://dali.jqgufenzy.top/Article/details/gtafxkpncv.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.zhongyouzk.top/Article/details/gtjzqwqpvg.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yuanzhike.top/Article/details/gthqxovssn.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.cheryme.top/Article/details/gtyvneniek.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxugwdhqq.html

Java: list.size();  map.size();  s.length()
来源：http://dali.yonumen.top/Article/details/gtemvmmspd.html

Go:   len(arr);  len(m)
来源：http://dali.gotoacloud.top/Article/details/gtkgtwxurk.html

Ruby: x.length;  x.size
来源：http://dali.tianlin.xyz/Article/details/gtvenkouqf.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.cheryme.top/Article/details/gtttqnaczv.html

[P05] 判断两个对象内容是否相等
来源：http://dali.andypj.xyz/Article/details/gttblbrnab.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.sxryk.cn/Article/details/gtxnkjihfw.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.hywenlv.cn/Article/details/gtfephpcsq.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.chenlongwang.top/Article/details/gtzwjcsjud.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.tanke756.top/Article/details/gttxnzwwju.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.sweek.top/Article/details/gtbptmiuou.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.shzxlz.cn/Article/details/gtwgrkcxzi.html

Ruby: a == b
来源：http://dali.yuanzhike.top/Article/details/gtnpydzyoa.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.cucudq.cn/Article/details/gtquipudcf.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.gaohongyu789.top/Article/details/gtcryqcqsh.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.ydzc1.top/Article/details/gtolgpdshh.html

PHP:  if (empty($x)) {}
来源：http://dali.jlsjyb.cn/Article/details/gtsobdmbde.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.jianghu66.top/Article/details/gtrdfbryvi.html

TS:   if (x == null) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtafedqeve.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.zhengqikj.top/Article/details/gtibtbdumm.html

Go:   if x == nil {}
来源：http://dali.yueranfly.top/Article/details/gtvxnddnkn.html


<!-- 参考信息 -->