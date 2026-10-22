代发 wailian999

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.havefunace.top/Article/details/gt2gfajbnjr.html

JS:   process.env.HOME
来源：http://dali.meibo888.top/Article/details/gt2tctglfgm.html

TS:   process.env.HOME
来源：http://dali.daria6918.cn/Article/details/gt2xzlevala.html

Java: System.getenv("HOME")
来源：http://dali.sxryk.cn/Article/details/gt2bsginrdv.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.hnqzz.top/Article/details/gt2vwwgqgir.html

Ruby: ENV["HOME"]
来源：http://dali.hywenlv.cn/Article/details/gt2vwcbtywf.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mgfjoauj.html

[M03] 执行外部命令
来源：http://dali.andypj.xyz/Article/details/gt2zetrjcbb.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.jqgufenzy.top/Article/details/gt2ygstmhzq.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.yj20258.top/Article/details/gt2khrjtuhv.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.nanxuanxn.top/Article/details/gt2ozkwxrvc.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhongyouzk.top/Article/details/gt2iglmzprc.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.haohaochexian.top/Article/details/gt2agdrkuah.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.nanxuanxn.top/Article/details/gt2jfpibeck.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.snrcjt.cn/Article/details/gt2dxtdzeaz.html

C#:   Process.Start("ls", "-l");
来源：http://dali.gzhubu.top/Article/details/gt2nrcqckzy.html

[M04] 获取当前工作目录
来源：http://dali.ivvv.top/Article/details/gt2nnijttft.html

Py:   os.getcwd()
来源：http://dali.shuidangran.top/Article/details/gt2oigfzmpo.html

PHP:  getcwd();
来源：http://dali.svipenyu.cn/Article/details/gt2jmukoorp.html

JS:   process.cwd()
来源：http://dali.shangyingyoupin.top/Article/details/gt2xinkmxqz.html

TS:   process.cwd()
来源：http://dali.c1oappe.top/Article/details/gt2wnggxszu.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.cashguo.top/Article/details/gt2rxztrqmq.html

Go:   os.Getwd()
来源：http://dali.redwolf501.top/Article/details/gt2noxmwudo.html

Ruby: Dir.pwd
来源：http://dali.ehwqpu.com/Article/details/gt2ubekrjtz.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.pengpengdd.cyou/Article/details/gt2wncqspir.html

[M05] 设置退出码
来源：http://dali.yueranfly.top/Article/details/gt2kpdtkkwe.html

Py:   sys.exit(1)
来源：http://dali.tian-w.cn/Article/details/gt2twfkcxyv.html

PHP:  exit(1);
来源：http://dali.xuetiantiany.cn/Article/details/gt2vmjwwuds.html

JS:   process.exit(1)
来源：http://dali.jyoumei.cn/Article/details/gt2ktodgltl.html

TS:   process.exit(1)
来源：http://dali.hnqzz.top/Article/details/gt2qakjddhr.html

Java: System.exit(1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wuoihfhf.html

Go:   os.Exit(1)
来源：http://dali.yanxiufei.cn/Article/details/gt2cwrxjpkd.html

Ruby: exit 1
来源：http://dali.daxiang520.top/Article/details/gt2kmpilwbe.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.shzxlz.cn/Article/details/gt2pofowpyq.html

[M06] 向标准错误输出
来源：http://dali.zdqjudy.top/Article/details/gt2ebybnesp.html

Py:   print("err", file=sys.stderr)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2oogamnib.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.shzxlz.cn/Article/details/gt2essvlfqt.html

JS:   console.error("err")
来源：http://dali.andypj.xyz/Article/details/gt2zhputjsu.html

TS:   console.error("err")
来源：http://dali.sysykeji.top/Article/details/gt2ktdkxfcs.html

Java: System.err.println("err")
来源：http://dali.xuetiantiany.cn/Article/details/gt2lwvrdpmx.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2slojnxsv.html

Ruby: warn "err"
来源：http://dali.aizwys.cn/Article/details/gt2atriizbq.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.nanxuanxn.top/Article/details/gt2qjdfiydz.html

[M07] 判断是否为主入口
来源：http://dali.redwolf501.top/Article/details/gt2vbrcspub.html

Py:   if __name__ == "__main__":
来源：http://dali.ydzc1.top/Article/details/gt2gwafkyot.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zdqjudy.top/Article/details/gt2sganzvtt.html

JS:   require.main === module
来源：http://dali.guowangkeji.top/Article/details/gt2wqacllgn.html

TS:   require.main === module
来源：http://dali.nanxinkj.top/Article/details/gt2hlgqlncp.html

Java: public static void main(String[] args)
来源：http://dali.aibaodan.cn/Article/details/gt2kquvydsh.html

Go:   func main()
来源：http://dali.ppjwa.cn/Article/details/gt2bqywndmm.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.9152youxi.cn/Article/details/gt2yptermnd.html

C#:   static void Main(string[] args)
来源：http://dali.xuetiantiany.cn/Article/details/gt2lytxwhqp.html

[M08] 获取系统与运行时信息
来源：http://dali.xylfe.cn/Article/details/gt2zrhnwasx.html

Py:   platform.system();  platform.python_version()
来源：http://dali.chenzaomai.com/Article/details/gt2wdpyhvwj.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.wangdashe.top/Article/details/gt2earipgmg.html

JS:   process.platform;  process.version
来源：http://dali.yanxiufei.cn/Article/details/gt2itdzmfig.html

TS:   process.platform;  process.version
来源：http://dali.xylfe.cn/Article/details/gt2aboulmsw.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2eddinftu.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.pycfn.com/Article/details/gt2vvjptaep.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.dianchejie.cn/Article/details/gt2rdszvgat.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.gzhubu.top/Article/details/gt2slawuzvm.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nlbirnbm.html

N. 数据结构与算法
来源：http://dali.yuanzhike.top/Article/details/gt2xvrxeyzq.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2kwszohpq.html

[N01] 二分查找（有序数组）
来源：http://dali.ybcxt.top/Article/details/gt2wkiueple.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.vqdsnc.cn/Article/details/gt2fschiblz.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.jianghu66.top/Article/details/gt2rgkwcgkh.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xemijsqo.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhixingplan.top/Article/details/gt2wwxxdezu.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.cheryme.top/Article/details/gt2hkcirofq.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.aizwys.cn/Article/details/gt2minvzyyp.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.smart0.xyz/Article/details/gt2xfnvdksa.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.wangshuangyany.cn/Article/details/gt2wmiqwppp.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.hnqzz.top/Article/details/gt2dwfbglsu.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhongyouzk.top/Article/details/gt2rnigahoc.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.shuidangran.top/Article/details/gt2pyodmspz.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.hywenlv.cn/Article/details/gt2vcegbnma.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.ppjwa.cn/Article/details/gt2uxiwsmnb.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.xuetiantiany.cn/Article/details/gt2doufpvjm.html

Go:   slices.Sort(arr)
来源：http://dali.gzhubu.top/Article/details/gt2vedhuhtx.html

Ruby: arr.sort
来源：http://dali.c1oappe.top/Article/details/gt2pvjiqyvq.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.aibaodan.cn/Article/details/gt2pdktzkjb.html

[N03] 快速排序（分治示例）
来源：http://dali.zhongyouzk.top/Article/details/gt2kapqjgnu.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.yueranfly.top/Article/details/gt2fvlabhrb.html

PHP:  // 递归实现，或用 usort
来源：http://dali.0kj1m.cn/Article/details/gt2lopnruyk.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.aizwys.cn/Article/details/gt2uobgence.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.andypj.xyz/Article/details/gt2ggcxaiyy.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.smart0.xyz/Article/details/gt2aduqbdey.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ujskglqr.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.c1oappe.top/Article/details/gt2tatigsqi.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.guowangkeji.top/Article/details/gt2btzoqfzy.html

[N04] 斐波那契数列
来源：http://dali.nanxuanxn.top/Article/details/gt2abvmwqxw.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2airgahff.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.havefunace.top/Article/details/gt2tihdztsv.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.hnqzz.top/Article/details/gt2yamyfzjr.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.xylfe.cn/Article/details/gt2nyekjnem.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.chenjidiqi.icu/Article/details/gt2mwciecqo.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.hywenlv.cn/Article/details/gt2cdtvtmwc.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.jinqigfzy.top/Article/details/gt2roqbrhvs.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.jinqigfzy.top/Article/details/gt2uwmliaeb.html

[N05] 最大公约数
来源：http://dali.hfpthk.cn/Article/details/gt2nrlaamhf.html

Py:   math.gcd(a, b)
来源：http://dali.guannengcc.top/Article/details/gt2rolffaap.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.mhx1999.top/Article/details/gt2vznqxbue.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.ydzc1.top/Article/details/gt2kkbptgne.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.smart0.xyz/Article/details/gt2xgmtoqsi.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.xylfe.cn/Article/details/gt2vzmmwisr.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.nwbrower.top/Article/details/gt2gdqshvoo.html

Ruby: a.gcd(b)
来源：http://dali.nwbrower.top/Article/details/gt2bucapakh.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.chenjidiqi.icu/Article/details/gt2pwmseqzm.html

[N06] 判断回文字符串
来源：http://dali.hysaishi.cn/Article/details/gt2kyfjhvpm.html

Py:   s == s[::-1]
来源：http://dali.pengpengdd.cyou/Article/details/gt2qbgtcpuc.html

PHP:  $s === strrev($s);
来源：http://dali.c1oappe.top/Article/details/gt2pdytrbwj.html

JS:   s === [...s].reverse().join("")
来源：http://dali.hywenlv.cn/Article/details/gt2euxmucuw.html

TS:   s === [...s].reverse().join("")
来源：http://dali.ivvv.top/Article/details/gt2yvesrkbi.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.yonumen.top/Article/details/gt2xukdbbej.html

Go:   // 双指针从两端比较
来源：http://dali.smart0.xyz/Article/details/gt2yspcpigd.html

Ruby: s == s.reverse
来源：http://dali.quarkkingdee.top/Article/details/gt2wohtfjqh.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.jinghuilouyu.cn/Article/details/gt2iqglzljq.html

[N07] 两数之和（返回下标）
来源：http://dali.dianchejie.cn/Article/details/gt2qwqjpslb.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.xinyue.icu/Article/details/gt2oktxrjit.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.jlsjyb.cn/Article/details/gt2qehedgoq.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.pycfn.com/Article/details/gt2euoevgen.html

TS:   // 手写 Map<string, number>
来源：http://dali.feifeiyinyue.top/Article/details/gt2ropvphvt.html

Java: // 手写 HashMap
来源：http://dali.yangfankeji.com/Article/details/gt2zuyvkgmj.html

Go:   // 手写 map[int]int
来源：http://dali.tanke756.top/Article/details/gt2rkcxjgwc.html

Ruby: // 手写 Hash
来源：http://dali.xziqi.cn/Article/details/gt2anohwojg.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.chenzaomai.com/Article/details/gt2mtzhhxfl.html

[N08] 生成全排列
来源：http://dali.nanxuanxn.top/Article/details/gt2bqqtvjfr.html

Py:   itertools.permutations(arr)
来源：http://dali.chenjidiqi.icu/Article/details/gt2errdspve.html

PHP:  // 手写递归交换
来源：http://dali.gzhubu.top/Article/details/gt2yuuwmusj.html

JS:   // 手写回溯递归
来源：http://dali.wangdashe.top/Article/details/gt2dshjkgkf.html

TS:   // 手写回溯递归
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cfbyzydd.html

Java: // 手写回溯递归
来源：http://dali.birdmap.top/Article/details/gt2wohgulvq.html

Go:   // 手写回溯递归
来源：http://dali.gotoacloud.top/Article/details/gt2etggysgp.html

Ruby: arr.permutation.to_a
来源：http://dali.yvedp.cn/Article/details/gt2wybozoop.html

C#:   // 手写回溯递归
来源：http://dali.zhengqikj.top/Article/details/gt2tjxxgcqb.html

[N09] 栈与队列
来源：http://dali.xziqi.cn/Article/details/gt2cgnoogpv.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.yongpay.top/Article/details/gt2ykqmgzen.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhongyouzk.top/Article/details/gt2uduzaocy.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.jqgufenzy.top/Article/details/gt2yogqptun.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.sweek.top/Article/details/gt2xdjxcica.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.tianlin.xyz/Article/details/gt2aticdpfg.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.shangyingyoupin.top/Article/details/gt2apzqfwwb.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.nanxuanxn.top/Article/details/gt2kngnqqkq.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.sweek.top/Article/details/gt2zebbylym.html

[N10] 链表节点定义
来源：http://dali.haohaochexian.top/Article/details/gt2sdamtlql.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.shuidangran.top/Article/details/gt2jjikcusc.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.xylfe.cn/Article/details/gt2vvhphzeq.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.dianchejie.cn/Article/details/gt2hgputina.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.gogol.net.cn/Article/details/gt2tbvwhtex.html

Java: class Node { int v; Node next; }
来源：http://dali.9152youxi.cn/Article/details/gt2wcwyosxt.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.aibaodan.cn/Article/details/gt2yitmuzns.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.yuxming.cn/Article/details/gt2fnoiibaa.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.redwolf501.top/Article/details/gt2upqqlubu.html

[N11] 二叉树中序遍历
来源：http://dali.yanxiufei.cn/Article/details/gt2zvimqrdr.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.fzhhl.top/Article/details/gt2ymnvszma.html

PHP:  // 手写递归函数
来源：http://dali.jlsjyb.cn/Article/details/gt2mygfpfbz.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.shuidangran.top/Article/details/gt2atawdclz.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jpwsfppb.html

Java: // 手写递归
来源：http://dali.0kj1m.cn/Article/details/gt2azpacjip.html

Go:   // 手写递归
来源：http://dali.sufxvd.cn/Article/details/gt2uwnfcxnw.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.yj202588.top/Article/details/gt2cqdwbfqx.html

C#:   // 手写递归
来源：http://dali.chenlongwang.top/Article/details/gt2mvpklxzg.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.birdmap.top/Article/details/gt2tdgghkvs.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhixingplan.top/Article/details/gt2nmdtdqza.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lqbbmdoq.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.tanke756.top/Article/details/gt2zyuwiagz.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.cqqwz.cn/Article/details/gt2slsztiqe.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.aizwys.cn/Article/details/gt2qvfpytrm.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.xylfe.cn/Article/details/gt2wewjktlv.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.smart0.xyz/Article/details/gt2lhrbtvsr.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.wangshuangyany.cn/Article/details/gt2tooktmot.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gt2mtdajrbt.html

O. 并发与异步
来源：http://dali.sweek.top/Article/details/gt2goypehbp.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gt2xmdhdydl.html

[O01] 启动一个线程
来源：http://dali.jiagoushi.top/Article/details/gt2jtgajxfc.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tjtflqgt.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gydxxzru.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nppgwwlt.html

TS:   // 同 JS
来源：http://dali.9152youxi.cn/Article/details/gt2ijamerut.html

Java: new Thread(() -> f()).start()
来源：http://dali.yj20258.top/Article/details/gt2hnqzgnlk.html

Go:   go f()
来源：http://dali.yj20258.top/Article/details/gt2ibihgklg.html

Ruby: Thread.new { f }
来源：http://dali.jianghu66.top/Article/details/gt2bauqggzl.html

C#:   Task.Run(() => F());
来源：http://dali.sufxvd.cn/Article/details/gt2tzinchzl.html

[O02] 使用线程池
来源：http://dali.guowangkeji.top/Article/details/gt2lvkujoac.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.ybcxt.top/Article/details/gt2dscptdqq.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.jyoumei.cn/Article/details/gt2mezczzhu.html

JS:   // worker_threads 线程池
来源：http://dali.pengpengdd.cyou/Article/details/gt2kvukjsxt.html

TS:   // worker_threads 线程池
来源：http://dali.tianlin.xyz/Article/details/gt2wivqtyrz.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.ydzc1.top/Article/details/gt2tcotdrfp.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.jianghu66.top/Article/details/gt2pccflhmu.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.tianlin.xyz/Article/details/gt2kayaxbnl.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.gzhubu.top/Article/details/gt2hgtpdlel.html

[O03] 加锁保护共享数据
来源：http://dali.sysykeji.top/Article/details/gt2ocatultm.html

Py:   with lock: shared += 1
来源：http://dali.chenlongwang.top/Article/details/gt2kzjzvndv.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhengqikj.top/Article/details/gt2lyoojoqv.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.dashuyun.cn/Article/details/gt2wialhisn.html

TS:   // 同 JS
来源：http://dali.snrcjt.cn/Article/details/gt2heszmvtr.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tieebrsd.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.meibo888.top/Article/details/gt2xcxlxkdc.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.guowangkeji.top/Article/details/gt2ttbijksd.html

C#:   lock (gate) { shared++; }
来源：http://dali.jqgufenzy.top/Article/details/gt2apfnndfv.html

[O04] 定义异步函数并等待
来源：http://dali.ppjwa.cn/Article/details/gt2lnskcjcj.html

Py:   async def f():⏎    await g()
来源：http://dali.jinqigufen.top/Article/details/gt2tknpvcfx.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.pengpengdd.cyou/Article/details/gt2groyeocu.html

JS:   async function f() { await g(); }
来源：http://dali.redwolf501.top/Article/details/gt2yseslwte.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.yuanzhike.top/Article/details/gt2edmnzmtr.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.ybcxt.top/Article/details/gt2kxxcaydu.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.yvedp.cn/Article/details/gt2xacnfjqt.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.haohaochexian.top/Article/details/gt2ftyjvjnt.html

C#:   async Task F() { await G(); }
来源：http://dali.havefunace.top/Article/details/gt2jcjxodmt.html

[O05] 并发执行并等待全部完成
来源：http://dali.chenzaomai.com/Article/details/gt2hnuslqav.html

Py:   asyncio.gather(*tasks)
来源：http://dali.jianghu66.top/Article/details/gt2ykqabymh.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.ydzc1.top/Article/details/gt2cgfgwkau.html

JS:   await Promise.all(tasks)
来源：http://dali.9152youxi.cn/Article/details/gt2fcdkljtl.html

TS:   await Promise.all(tasks)
来源：http://dali.andypj.xyz/Article/details/gt2urmuauos.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.tian-w.cn/Article/details/gt2dasudsyf.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.316326.xyz/Article/details/gt2unzaqtkt.html

Ruby: threads.map(&:join)
来源：http://dali.mhx1999.top/Article/details/gt2sfjzgvif.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.quarkkingdee.top/Article/details/gt2tllywykw.html

[O06] 使用进程池
来源：http://dali.c1oappe.top/Article/details/gt2zqnndqie.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.sysykeji.top/Article/details/gt2kfemmwny.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.chenjidiqi.icu/Article/details/gt2bktmfmdy.html

JS:   // child_process / cluster 模块
来源：http://dali.jlsjyb.cn/Article/details/gt2uqeusmsw.html

TS:   // child_process / cluster 模块
来源：http://dali.yj20258.top/Article/details/gt2zrlwhhfk.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.fzhhl.top/Article/details/gt2xpoehraq.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.xziqi.cn/Article/details/gt2cfymwqkb.html

Ruby: // fork 块
来源：http://dali.zhongyouzk.top/Article/details/gt2miixbole.html

C#:   Parallel.For
来源：http://dali.316326.xyz/Article/details/gt2sctzklhu.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gt2opxstyem.html

P. 常用工具函数
来源：http://dali.jinqigufen.top/Article/details/gt2curqyuza.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lonqwrlr.html

[P01] 生成 UUID
来源：http://dali.mhx1999.top/Article/details/gt2gtkiltdn.html

Py:   str(uuid.uuid4())
来源：http://dali.hongshengwenyu.top/Article/details/gt2fyldxnup.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.shzxlz.cn/Article/details/gt2oubxirna.html

JS:   crypto.randomUUID()
来源：http://dali.hnqzz.top/Article/details/gt2icqykfvn.html

TS:   crypto.randomUUID()
来源：http://dali.snrcjt.cn/Article/details/gt2cfcgwgbk.html

Java: UUID.randomUUID().toString()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fmcqvxki.html

Go:   // 用 github.com/google/uuid
来源：http://dali.ivvv.top/Article/details/gt2jydifwlm.html

Ruby: SecureRandom.uuid
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nufmkbav.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.shuidangran.top/Article/details/gt2ebxpkpaw.html

[P02] MD5 / SHA256 摘要
来源：http://dali.zycfv.cn/Article/details/gt2kxpdfmxm.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.hnqzz.top/Article/details/gt2ggravsiv.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.daxiang520.top/Article/details/gt2egsydlqn.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.wangshuangyany.cn/Article/details/gt2zpappzgl.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.zhengqikj.top/Article/details/gt2dwynnfch.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.jianghu66.top/Article/details/gt2yrncgcyy.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.jiagoushi.top/Article/details/gt2opajylbl.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zycfv.cn/Article/details/gt2oybisgid.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.aibaodan.cn/Article/details/gt2crgvwgpg.html

[P03] 生成短随机字符串
来源：http://dali.daria6918.cn/Article/details/gt2ygdixvvs.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2blgzkqdh.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.cheryme.top/Article/details/gt2hcavieih.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jqgfzy.top/Article/details/gt2quawlihm.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jlsjyb.cn/Article/details/gt2ljlmpndi.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.sxryk.cn/Article/details/gt2pjvhmuce.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.yj20258888.top/Article/details/gt2osgrjmdn.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.hammf.cn/Article/details/gt2byjfxwmq.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.aizwys.cn/Article/details/gt2dlhuenvf.html

[P04] 求长度
来源：http://dali.fzhhl.top/Article/details/gt2aocbluqg.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.nwbrower.top/Article/details/gt2bexyvpdk.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.hammf.cn/Article/details/gt2zsssncpx.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.wangshuangyany.cn/Article/details/gt2qwuffhqi.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.hywenlv.cn/Article/details/gt2bjsqstnl.html

Java: list.size();  map.size();  s.length()
来源：http://dali.yj20258.top/Article/details/gt2tatupxju.html

Go:   len(arr);  len(m)
来源：http://dali.snrcjt.cn/Article/details/gt2psputifu.html

Ruby: x.length;  x.size
来源：http://dali.gzhubu.top/Article/details/gt2sgcwociv.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.chenjidiqi.icu/Article/details/gt2okrtpqlm.html

[P05] 判断两个对象内容是否相等
来源：http://dali.guowangkeji.top/Article/details/gt2fgcfwymf.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.guannengcc.top/Article/details/gt2akefmabd.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.cqqwz.cn/Article/details/gt2qqdmyxes.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.xylfe.cn/Article/details/gt2cywrjhbq.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.yueranfly.top/Article/details/gt2gmbdnqam.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.gogol.net.cn/Article/details/gt2igwcjfbj.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.hfpthk.cn/Article/details/gt2bxtvhwox.html

Ruby: a == b
来源：http://dali.yj20258888.top/Article/details/gt2vdlotnzq.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.jlsjyb.cn/Article/details/gt2wyiwugul.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.sxryk.cn/Article/details/gt2gguvoann.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.pycfn.com/Article/details/gt2cmsujghk.html

PHP:  if (empty($x)) {}
来源：http://dali.aizwys.cn/Article/details/gt2vjckvljw.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.jiagoushi.top/Article/details/gt2spwgbgsc.html

TS:   if (x == null) {}
来源：http://dali.zdqjudy.top/Article/details/gt2vdwgezgz.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.cqqwz.cn/Article/details/gt2vbycmeqt.html

Go:   if x == nil {}
来源：http://dali.xziqi.cn/Article/details/gt2blzrrsud.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.xuanzx.com/Article/details/gt2wdxvzazd.html

C#:   if (x is null) {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2wzpkzixp.html

[P07] 防抖与节流
来源：http://dali.andypj.xyz/Article/details/gt2aveiimnw.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.hongshengwenyu.top/Article/details/gt2nbtycoin.html

PHP:  // 手写时间戳比较
来源：http://dali.gaohongyu789.top/Article/details/gt2jwvbgnpd.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.0kj1m.cn/Article/details/gt2hgifvygk.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.dashuyun.cn/Article/details/gt2bcagprla.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.9152youxi.cn/Article/details/gt2rxbxqdqh.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhongyouzk.top/Article/details/gt2fttiglmq.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.zhiwuduotai.top/Article/details/gt2lefhutlo.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.nanxuanxn.top/Article/details/gt2wcztswab.html

[P08] 处理浮点精度问题
来源：http://dali.dianchejie.cn/Article/details/gt2xxspziho.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.ybcxt.top/Article/details/gt2erjlofkd.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.tian-w.cn/Article/details/gt2duwkmzgz.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.yangfankeji.com/Article/details/gt2fugttkxc.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.xuanzx.com/Article/details/gt2bhrkvwbi.html


<!-- 参考信息 -->