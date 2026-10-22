代发 wailian999

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtppuaxusm.html

[M01] 读取命令行参数
来源：http://dali.sxryk.cn/Article/details/gticdtovor.html

Py:   sys.argv[1:]
来源：http://dali.yueranfly.top/Article/details/gtmiobzaup.html

PHP:  $argv;  $argc;
来源：http://dali.yanxiufei.cn/Article/details/gtsukfrxjv.html

JS:   process.argv.slice(2)
来源：http://dali.shzxlz.cn/Article/details/gtxgcvbvwb.html

TS:   process.argv.slice(2)
来源：http://dali.gzhubu.top/Article/details/gtnnzxnxzf.html

Java: args 数组（main 方法参数）
来源：http://dali.jinqigfzy.top/Article/details/gteafqjamf.html

Go:   os.Args[1:]
来源：http://dali.316326.xyz/Article/details/gtynehcohc.html

Ruby: ARGV
来源：http://dali.ivvv.top/Article/details/gtkxvaxsya.html

C#:   args 数组（Main 方法参数）
来源：http://dali.0kj1m.cn/Article/details/gtqyqjpbpa.html

[M02] 读取环境变量
来源：http://dali.jinyuanbaomall.cn/Article/details/gttkanjerq.html

Py:   os.environ.get("HOME")
来源：http://dali.zdqjudy.top/Article/details/gtcdlaszlm.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.kuanghao11.cn/Article/details/gtvxalykpp.html

JS:   process.env.HOME
来源：http://dali.jqgufenzy.top/Article/details/gtztnousvu.html

TS:   process.env.HOME
来源：http://dali.yj20258.top/Article/details/gtabgogusi.html

Java: System.getenv("HOME")
来源：http://dali.dianchejie.cn/Article/details/gtgmtiuxyp.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.hywenlv.cn/Article/details/gtoyiqodcz.html

Ruby: ENV["HOME"]
来源：http://dali.gotoacloud.top/Article/details/gtcbfumrdu.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhixingplan.top/Article/details/gtatfvripq.html

[M03] 执行外部命令
来源：http://dali.hywenlv.cn/Article/details/gtwrivnmhw.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.shuidangran.top/Article/details/gtlcnbhjzx.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.chenzaomai.com/Article/details/gtdckkodhw.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.daxiang520.top/Article/details/gtohfwjesc.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.redwolf501.top/Article/details/gtcofgvsaz.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.tianlin.xyz/Article/details/gtlnjebagb.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.cashguo.top/Article/details/gtummknogw.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.wangdashe.top/Article/details/gthgnihyba.html

C#:   Process.Start("ls", "-l");
来源：http://dali.iojbl.cn/Article/details/gtvnnucqtc.html

[M04] 获取当前工作目录
来源：http://dali.cashguo.top/Article/details/gtiinqlexm.html

Py:   os.getcwd()
来源：http://dali.fzhhl.top/Article/details/gtpizluell.html

PHP:  getcwd();
来源：http://dali.gaohongyu789.top/Article/details/gtrfgqoctk.html

JS:   process.cwd()
来源：http://dali.c1oappe.top/Article/details/gtrlfbobkm.html

TS:   process.cwd()
来源：http://dali.xylfe.cn/Article/details/gtkcsrmbgp.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.hnqzz.top/Article/details/gtnckzuzfo.html

Go:   os.Getwd()
来源：http://dali.jqgufenzy.top/Article/details/gtpyatwyyx.html

Ruby: Dir.pwd
来源：http://dali.shzxlz.cn/Article/details/gtwpixnbzo.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuqvhtvlv.html

[M05] 设置退出码
来源：http://dali.yanxiufei.cn/Article/details/gtanclhsnp.html

Py:   sys.exit(1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsfcfwxnw.html

PHP:  exit(1);
来源：http://dali.jinghuilouyu.cn/Article/details/gtmodaotrb.html

JS:   process.exit(1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtshnrhrme.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gtqlbjybvv.html

Java: System.exit(1)
来源：http://dali.cheryme.top/Article/details/gtsfmjwerr.html

Go:   os.Exit(1)
来源：http://dali.ehwqpu.com/Article/details/gtuponvltn.html

Ruby: exit 1
来源：http://dali.cheryme.top/Article/details/gtywottlfv.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.yongpay.top/Article/details/gtgsyllzhm.html

[M06] 向标准错误输出
来源：http://dali.mhx1999.top/Article/details/gtfrmnscyx.html

Py:   print("err", file=sys.stderr)
来源：http://dali.jinqigfzy.top/Article/details/gtxcybbotr.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.wangshuangyany.cn/Article/details/gtsrsouhnt.html

JS:   console.error("err")
来源：http://dali.sweek.top/Article/details/gtqocvbuoi.html

TS:   console.error("err")
来源：http://dali.yonumen.top/Article/details/gteofsxuts.html

Java: System.err.println("err")
来源：http://dali.yuxming.cn/Article/details/gtvimqtvmt.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.andypj.xyz/Article/details/gtaekuxdnz.html

Ruby: warn "err"
来源：http://dali.guannengcc.top/Article/details/gtkqucwiro.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.daria6918.cn/Article/details/gtpcshjimz.html

[M07] 判断是否为主入口
来源：http://dali.fengsongda.top/Article/details/gtakzadoxm.html

Py:   if __name__ == "__main__":
来源：http://dali.ppjwa.cn/Article/details/gttmubnnhj.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvaofcpze.html

JS:   require.main === module
来源：http://dali.andypj.xyz/Article/details/gtthpjexpd.html

TS:   require.main === module
来源：http://dali.xuetiantiany.cn/Article/details/gtjhiswkoh.html

Java: public static void main(String[] args)
来源：http://dali.andypj.xyz/Article/details/gttduolqkh.html

Go:   func main()
来源：http://dali.cheryme.top/Article/details/gtpddxjxas.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.yuanzhike.top/Article/details/gtcjnqeihg.html

C#:   static void Main(string[] args)
来源：http://dali.guannengcc.top/Article/details/gtbwgsopgg.html

[M08] 获取系统与运行时信息
来源：http://dali.yongpay.top/Article/details/gthxrsxtng.html

Py:   platform.system();  platform.python_version()
来源：http://dali.gzhubu.top/Article/details/gttaqgxigt.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.dianchejie.cn/Article/details/gtsilyzryr.html

JS:   process.platform;  process.version
来源：http://dali.hnqzz.top/Article/details/gtolqmgfzm.html

TS:   process.platform;  process.version
来源：http://dali.guannengcc.top/Article/details/gtwqrbvbyd.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.yuxming.cn/Article/details/gtpscoovni.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.guannengcc.top/Article/details/gtcgesjoir.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.xylfe.cn/Article/details/gttciiuyjy.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.havefunace.top/Article/details/gtrwhclfto.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtnszotrer.html

N. 数据结构与算法
来源：http://dali.shanyushiyangtech.top/Article/details/gtxalgooli.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtdwgupcyh.html

[N01] 二分查找（有序数组）
来源：http://dali.hammf.cn/Article/details/gthpxcvoim.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.xziqi.cn/Article/details/gthnwrruoa.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.gogol.net.cn/Article/details/gtvmreadrm.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yj20258.top/Article/details/gtdvpzbfim.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.cucudq.cn/Article/details/gtqlqbyfmf.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zdqjudy.top/Article/details/gtgujzflee.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.hnqzz.top/Article/details/gtncjmcmlo.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.wangshuangyany.cn/Article/details/gtdftnygtu.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.redwolf501.top/Article/details/gthntkenfl.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.gzhubu.top/Article/details/gttbssuopv.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.andypj.xyz/Article/details/gtvkgvigds.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.0kj1m.cn/Article/details/gtlcqorssa.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.shanyushiyangtech.top/Article/details/gtnfcrpvob.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yj20258888.top/Article/details/gtstugfxmt.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsiidfvfv.html

Go:   slices.Sort(arr)
来源：http://dali.hammf.cn/Article/details/gtihwjziib.html

Ruby: arr.sort
来源：http://dali.mhx1999.top/Article/details/gtoyomkyxx.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.jyoumei.cn/Article/details/gtngcducgp.html

[N03] 快速排序（分治示例）
来源：http://dali.nanxuanxn.top/Article/details/gteyqauqzz.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.yangfankeji.com/Article/details/gtxpieofqm.html

PHP:  // 递归实现，或用 usort
来源：http://dali.hfpthk.cn/Article/details/gtyoqizzui.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.svipenyu.cn/Article/details/gtelolggzs.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.nwbrower.top/Article/details/gterjyucqb.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.mhx1999.top/Article/details/gtddbmtceq.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.daria6918.cn/Article/details/gtsclejlqu.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhengqikj.top/Article/details/gtgalgdfkn.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkilxgkts.html

[N04] 斐波那契数列
来源：http://dali.gogol.net.cn/Article/details/gtiqttkdkg.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.fengsongda.top/Article/details/gtikocsszz.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.jqgfzy.top/Article/details/gtmzdxlmkf.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.gotoacloud.top/Article/details/gtjdlsufsh.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.svipenyu.cn/Article/details/gtoytahaul.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.jqgfzy.top/Article/details/gtumktivbj.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.vqdsnc.cn/Article/details/gtenmctwsv.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.feifeiyinyue.top/Article/details/gtscbtwzqc.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.hnxiangtu.top/Article/details/gtwispuflh.html

[N05] 最大公约数
来源：http://dali.meibo888.top/Article/details/gtoeqliptl.html

Py:   math.gcd(a, b)
来源：http://dali.yj20258888.top/Article/details/gtkytofpty.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.sweek.top/Article/details/gtaelfojwi.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.dianchejie.cn/Article/details/gtbzbcevum.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.gaohongyu789.top/Article/details/gtqkfbkcgj.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.pycfn.com/Article/details/gtungivcwn.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.smart0.xyz/Article/details/gtgmulkgib.html

Ruby: a.gcd(b)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtudfkouly.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.yvedp.cn/Article/details/gttsjtszzt.html

[N06] 判断回文字符串
来源：http://dali.guannengcc.top/Article/details/gtvawmzdzm.html

Py:   s == s[::-1]
来源：http://dali.hysaishi.cn/Article/details/gtgnmwikiv.html

PHP:  $s === strrev($s);
来源：http://dali.jqgfzy.top/Article/details/gtvgepngln.html

JS:   s === [...s].reverse().join("")
来源：http://dali.andypj.xyz/Article/details/gtkbltavwd.html

TS:   s === [...s].reverse().join("")
来源：http://dali.pycfn.com/Article/details/gtzoldlnpr.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.yanxiufei.cn/Article/details/gtakkevwsa.html

Go:   // 双指针从两端比较
来源：http://dali.yj20258.top/Article/details/gtcphuvpkb.html

Ruby: s == s.reverse
来源：http://dali.ppjwa.cn/Article/details/gtrhajzhny.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.ehwqpu.com/Article/details/gtljdougqr.html

[N07] 两数之和（返回下标）
来源：http://dali.chenlongwang.top/Article/details/gtmptamshb.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.pycfn.com/Article/details/gthadipfzb.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.shanyushiyangtech.top/Article/details/gtmnaciuol.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.pengpengdd.cyou/Article/details/gtngrqfunf.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhoulong.xyz/Article/details/gtpsprpnur.html

Java: // 手写 HashMap
来源：http://dali.zhaomingkeji.xyz/Article/details/gteamyqzsc.html

Go:   // 手写 map[int]int
来源：http://dali.hongshengwenyu.top/Article/details/gtpavostot.html

Ruby: // 手写 Hash
来源：http://dali.ivvv.top/Article/details/gtsogzkapg.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.nanxuanxn.top/Article/details/gtnrxtyaqj.html

[N08] 生成全排列
来源：http://dali.c1oappe.top/Article/details/gtychfixkf.html

Py:   itertools.permutations(arr)
来源：http://dali.shanyushiyangtech.top/Article/details/gtvxtlywnj.html

PHP:  // 手写递归交换
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtobdrwijd.html

JS:   // 手写回溯递归
来源：http://dali.zhiwuduotai.top/Article/details/gthcgrpgoq.html

TS:   // 手写回溯递归
来源：http://dali.cdnleiting.top/Article/details/gtnfrhrjsl.html

Java: // 手写回溯递归
来源：http://dali.quarkkingdee.top/Article/details/gtjwgnasjv.html

Go:   // 手写回溯递归
来源：http://dali.daria6918.cn/Article/details/gtwxzfewrc.html

Ruby: arr.permutation.to_a
来源：http://dali.pengpengdd.cyou/Article/details/gthutofhhs.html

C#:   // 手写回溯递归
来源：http://dali.smart0.xyz/Article/details/gtqzihygoc.html

[N09] 栈与队列
来源：http://dali.yvedp.cn/Article/details/gtqyyykbzq.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.shuidangran.top/Article/details/gtwlzabybl.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.aibaodan.cn/Article/details/gtmvanznfe.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.tianlin.xyz/Article/details/gtwnkdukee.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhiwuduotai.top/Article/details/gtjtmjvipd.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.yonumen.top/Article/details/gtoebncops.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.yuanzhike.top/Article/details/gttckadzxw.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.wangdashe.top/Article/details/gtiffsptau.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.jlsjyb.cn/Article/details/gtltgadmmd.html

[N10] 链表节点定义
来源：http://dali.svipenyu.cn/Article/details/gtbpngqqno.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.hysaishi.cn/Article/details/gtgewqtasg.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.jqgfzy.top/Article/details/gtnttaxjhx.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.yueranfly.top/Article/details/gtrygnoqug.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.daxiang520.top/Article/details/gtnojvhljt.html

Java: class Node { int v; Node next; }
来源：http://dali.chenzaomai.com/Article/details/gtmuqeocka.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zdqjudy.top/Article/details/gtmzxwskgi.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.shangyingyoupin.top/Article/details/gtrmsndhtq.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.havefunace.top/Article/details/gtncrvfcjd.html

[N11] 二叉树中序遍历
来源：http://dali.redwolf501.top/Article/details/gttclxkili.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwxqeysks.html

PHP:  // 手写递归函数
来源：http://dali.yj20258.top/Article/details/gtrfncrwzt.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.hnqzz.top/Article/details/gtmdxbvqlo.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.gogol.net.cn/Article/details/gtqharxunc.html

Java: // 手写递归
来源：http://dali.zycfv.cn/Article/details/gtfhacfxfg.html

Go:   // 手写递归
来源：http://dali.yj20258888.top/Article/details/gtzpcugoud.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.yanxiufei.cn/Article/details/gtjgxjymco.html

C#:   // 手写递归
来源：http://dali.jinqigufen.top/Article/details/gtsptykwsg.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkhzjcyna.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.yongpay.top/Article/details/gtvmildobx.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.yueranfly.top/Article/details/gtquouomeu.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.hywenlv.cn/Article/details/gtpotegxzi.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.gogol.net.cn/Article/details/gtipbsxaix.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.snrcjt.cn/Article/details/gtqiqndcni.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.dashuyun.cn/Article/details/gtmlhiolmm.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.meibo888.top/Article/details/gttqkbgamd.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.wangshuangyany.cn/Article/details/gtckakhoqg.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtymchroux.html

O. 并发与异步
来源：http://dali.mhx1999.top/Article/details/gthamzkarp.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtdocyexpx.html

[O01] 启动一个线程
来源：http://dali.cqqwz.cn/Article/details/gtoezrpwgn.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.hfpthk.cn/Article/details/gtzzkzgkrf.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.quarkkingdee.top/Article/details/gtgfnkhwiw.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.jinqigufen.top/Article/details/gtrzdtcnym.html

TS:   // 同 JS
来源：http://dali.sufxvd.cn/Article/details/gtrbeusqcr.html

Java: new Thread(() -> f()).start()
来源：http://dali.chenzaomai.com/Article/details/gtnuewucfa.html

Go:   go f()
来源：http://dali.bjfxy.top/Article/details/gtxrpclrfq.html

Ruby: Thread.new { f }
来源：http://dali.yonumen.top/Article/details/gtgletxiem.html

C#:   Task.Run(() => F());
来源：http://dali.quarkkingdee.top/Article/details/gtgppwctba.html

[O02] 使用线程池
来源：http://dali.zhengqikj.top/Article/details/gtfmhtsgug.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhengqikj.top/Article/details/gtttbclvkl.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.dianchejie.cn/Article/details/gtucmutwbk.html

JS:   // worker_threads 线程池
来源：http://dali.sweek.top/Article/details/gtpjisqeby.html

TS:   // worker_threads 线程池
来源：http://dali.havefunace.top/Article/details/gtlmhljwpb.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.aibaodan.cn/Article/details/gtysoxvcgd.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.feifeiyinyue.top/Article/details/gtktxmxkux.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.fzhhl.top/Article/details/gtgnagepwb.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.jyoumei.cn/Article/details/gtiaszflmy.html

[O03] 加锁保护共享数据
来源：http://dali.haohaochexian.top/Article/details/gtxuvswkrt.html

Py:   with lock: shared += 1
来源：http://dali.ybcxt.top/Article/details/gtmieuvpxe.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.pengpengdd.cyou/Article/details/gtvffgsgev.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.quarkkingdee.top/Article/details/gtddbmwrca.html

TS:   // 同 JS
来源：http://dali.hfpthk.cn/Article/details/gtyowmefxg.html

Java: synchronized (this) { shared++; }
来源：http://dali.pycfn.com/Article/details/gtffxqhxzc.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.bjfxy.top/Article/details/gtljgskexa.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.ywan-chungtsiang.top/Article/details/gthamnvumg.html

C#:   lock (gate) { shared++; }
来源：http://dali.iojbl.cn/Article/details/gtfuewzclg.html

[O04] 定义异步函数并等待
来源：http://dali.xinyue.icu/Article/details/gtdqmqddum.html

Py:   async def f():⏎    await g()
来源：http://dali.svipenyu.cn/Article/details/gtzfjzlzgv.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.jlsjyb.cn/Article/details/gtcriyflnp.html

JS:   async function f() { await g(); }
来源：http://dali.daxiang520.top/Article/details/gtsugwhrif.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.quarkkingdee.top/Article/details/gtuoixewtf.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.pycfn.com/Article/details/gtnexoduam.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.pengpengdd.cyou/Article/details/gtppzisbeg.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.0kj1m.cn/Article/details/gtiohdvsnm.html

C#:   async Task F() { await G(); }
来源：http://dali.yanxiufei.cn/Article/details/gtcdivsvmo.html

[O05] 并发执行并等待全部完成
来源：http://dali.daxiang520.top/Article/details/gtfmmekgxk.html

Py:   asyncio.gather(*tasks)
来源：http://dali.hongshengwenyu.top/Article/details/gtmrzttwkm.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.gotoacloud.top/Article/details/gtkjfbnded.html

JS:   await Promise.all(tasks)
来源：http://dali.jinqigfzy.top/Article/details/gtgigieyod.html

TS:   await Promise.all(tasks)
来源：http://dali.zhaomingkeji.xyz/Article/details/gthqdevkaa.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.havefunace.top/Article/details/gtzhufuvdd.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.shanyushiyangtech.top/Article/details/gtrtkzyxfc.html

Ruby: threads.map(&:join)
来源：http://dali.iojbl.cn/Article/details/gtrmgghqqj.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zycfv.cn/Article/details/gttgkmiews.html

[O06] 使用进程池
来源：http://dali.xuetiantiany.cn/Article/details/gtxlqjaops.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.tianlin.xyz/Article/details/gtvqtdukzo.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.cucudq.cn/Article/details/gtdyccjfbr.html

JS:   // child_process / cluster 模块
来源：http://dali.jqgufenzy.top/Article/details/gtpbacxdzi.html

TS:   // child_process / cluster 模块
来源：http://dali.hywenlv.cn/Article/details/gttllfxeen.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.sxryk.cn/Article/details/gtcxjlcxzy.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.sxryk.cn/Article/details/gttdjckkpj.html

Ruby: // fork 块
来源：http://dali.wangshuangyany.cn/Article/details/gthrbgrixj.html

C#:   Parallel.For
来源：http://dali.zhaomingkeji.xyz/Article/details/gtncyoxqyy.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtnrmxxywd.html

P. 常用工具函数
来源：http://dali.zdqjudy.top/Article/details/gtmvjohsfg.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtyayirfaz.html

[P01] 生成 UUID
来源：http://dali.hnxiangtu.top/Article/details/gtltppsotf.html

Py:   str(uuid.uuid4())
来源：http://dali.xziqi.cn/Article/details/gtejuouyen.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.yj20258888.top/Article/details/gtelevfrip.html

JS:   crypto.randomUUID()
来源：http://dali.chenlongwang.top/Article/details/gtmjmiicaw.html

TS:   crypto.randomUUID()
来源：http://dali.yueranfly.top/Article/details/gtnzqtfnnr.html

Java: UUID.randomUUID().toString()
来源：http://dali.sxryk.cn/Article/details/gtcngsunxp.html

Go:   // 用 github.com/google/uuid
来源：http://dali.ehwqpu.com/Article/details/gtyuqwkuiu.html

Ruby: SecureRandom.uuid
来源：http://dali.daxiang520.top/Article/details/gthdovzxex.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.yj20258888.top/Article/details/gttlwhwugv.html

[P02] MD5 / SHA256 摘要
来源：http://dali.birdmap.top/Article/details/gtlurlergb.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.hammf.cn/Article/details/gtlscamnsu.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.shanyushiyangtech.top/Article/details/gtwlqblubc.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.mhx1999.top/Article/details/gttppuqsqc.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.yuanzhike.top/Article/details/gtdzwiudca.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.sxryk.cn/Article/details/gtfggtrfww.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.aizwys.cn/Article/details/gtyvusolro.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.daria6918.cn/Article/details/gttzdueztl.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.bjfxy.top/Article/details/gtimuynxqh.html

[P03] 生成短随机字符串
来源：http://dali.jianghu66.top/Article/details/gtwnabqcpt.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.jlsjyb.cn/Article/details/gtocdfyhtt.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.hysaishi.cn/Article/details/gtysadliob.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhijiandao.cn/Article/details/gtnnhcuedp.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.mhx1999.top/Article/details/gtojxgncvo.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.jqgfzy.top/Article/details/gtanjvzybc.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.shangyingyoupin.top/Article/details/gtoyjvkebp.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.cheryme.top/Article/details/gtnznnrrzc.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.chenzaomai.com/Article/details/gtghbixmlg.html

[P04] 求长度
来源：http://dali.iojbl.cn/Article/details/gtsxtxffst.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.cqqwz.cn/Article/details/gtcuxtfmjr.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgsyikxop.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.haohaochexian.top/Article/details/gtrkdtgzty.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yonumen.top/Article/details/gtssbgibjm.html

Java: list.size();  map.size();  s.length()
来源：http://dali.yonumen.top/Article/details/gtbqzgiucb.html

Go:   len(arr);  len(m)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkvrnhrhp.html

Ruby: x.length;  x.size
来源：http://dali.ivvv.top/Article/details/gtyhsagvkq.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.dashuyun.cn/Article/details/gtgtjxuvdh.html

[P05] 判断两个对象内容是否相等
来源：http://dali.iojbl.cn/Article/details/gtwzbuyquq.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.cdnleiting.top/Article/details/gtzcslcofr.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.yanxiufei.cn/Article/details/gtpwtfhdpa.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.snrcjt.cn/Article/details/gtwhstmxnq.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.sysykeji.top/Article/details/gtzdjglulv.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.yj20258888.top/Article/details/gtzrdsjqwy.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.gaohongyu789.top/Article/details/gteemesnzw.html

Ruby: a == b
来源：http://dali.mhx1999.top/Article/details/gtusuqdjhc.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.andypj.xyz/Article/details/gtqbxaglyl.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.hnqzz.top/Article/details/gtkixhiuxg.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.xuanzx.com/Article/details/gtrfjybljl.html

PHP:  if (empty($x)) {}
来源：http://dali.zhiwuduotai.top/Article/details/gttcbiigfs.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.hongshengwenyu.top/Article/details/gtducwzfhz.html

TS:   if (x == null) {}
来源：http://dali.pycfn.com/Article/details/gtnucnbedp.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.gaohongyu789.top/Article/details/gtqmdnhcsh.html

Go:   if x == nil {}
来源：http://dali.vqdsnc.cn/Article/details/gtaeahxwvj.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.xinyue.icu/Article/details/gtwodhwxck.html

C#:   if (x is null) {}
来源：http://dali.nanxinkj.top/Article/details/gtpuozigfx.html

[P07] 防抖与节流
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmmoimush.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.hfpthk.cn/Article/details/gtagmnwvxg.html


<!-- 参考信息 -->