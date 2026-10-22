代发 wailian999

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.hnxiangtu.top/Article/details/gtwvdvdbdk.html

JS:   process.env.HOME
来源：http://dali.zycfv.cn/Article/details/gtqymzxbjn.html

TS:   process.env.HOME
来源：http://dali.birdmap.top/Article/details/gtrtpurrnr.html

Java: System.getenv("HOME")
来源：http://dali.hnqzz.top/Article/details/gtoliosmxc.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.xinyue.icu/Article/details/gtrypnufps.html

Ruby: ENV["HOME"]
来源：http://dali.xinyue.icu/Article/details/gtehskdqnv.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.xuetiantiany.cn/Article/details/gtldwnceok.html

[M03] 执行外部命令
来源：http://dali.yj20258.top/Article/details/gtqplsvmrx.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.xylfe.cn/Article/details/gthzeymvrf.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.daxiang520.top/Article/details/gtddaofeqp.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.jianghu66.top/Article/details/gtznmwcauw.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.guannengcc.top/Article/details/gtbugwitac.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.yj20258.top/Article/details/gtigmuerak.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.guannengcc.top/Article/details/gtbbzupxbh.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.hywenlv.cn/Article/details/gtdsbrlest.html

C#:   Process.Start("ls", "-l");
来源：http://dali.jlsjyb.cn/Article/details/gtdrsbmjnx.html

[M04] 获取当前工作目录
来源：http://dali.shanyushiyangtech.top/Article/details/gtyltegizi.html

Py:   os.getcwd()
来源：http://dali.fengsongda.top/Article/details/gtvjhbqggb.html

PHP:  getcwd();
来源：http://dali.aibaodan.cn/Article/details/gtakkrxpyz.html

JS:   process.cwd()
来源：http://dali.xziqi.cn/Article/details/gtesqdgsxs.html

TS:   process.cwd()
来源：http://dali.gaohongyu789.top/Article/details/gtxueqqkwu.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.birdmap.top/Article/details/gtwgqjyanr.html

Go:   os.Getwd()
来源：http://dali.gogol.net.cn/Article/details/gtqfncgjhv.html

Ruby: Dir.pwd
来源：http://dali.quarkkingdee.top/Article/details/gtplysyckl.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.sweek.top/Article/details/gtxqxcjqoq.html

[M05] 设置退出码
来源：http://dali.cqqwz.cn/Article/details/gteidrzkpj.html

Py:   sys.exit(1)
来源：http://dali.fzhhl.top/Article/details/gtwjyshjhx.html

PHP:  exit(1);
来源：http://dali.shzxlz.cn/Article/details/gtttonjcrq.html

JS:   process.exit(1)
来源：http://dali.daxiang520.top/Article/details/gtokowkrtw.html

TS:   process.exit(1)
来源：http://dali.316326.xyz/Article/details/gtbxjiiczt.html

Java: System.exit(1)
来源：http://dali.zycfv.cn/Article/details/gtwtmixndq.html

Go:   os.Exit(1)
来源：http://dali.ybcxt.top/Article/details/gtqqxaeyal.html

Ruby: exit 1
来源：http://dali.shuidangran.top/Article/details/gtmjwgdviu.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhoulong.xyz/Article/details/gtmtzdsbxh.html

[M06] 向标准错误输出
来源：http://dali.havefunace.top/Article/details/gtcsixanfq.html

Py:   print("err", file=sys.stderr)
来源：http://dali.xinyue.icu/Article/details/gtssojlkul.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.shuidangran.top/Article/details/gtsutyaxcv.html

JS:   console.error("err")
来源：http://dali.birdmap.top/Article/details/gtkvqipnxp.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gtoinawoei.html

Java: System.err.println("err")
来源：http://dali.yanxiufei.cn/Article/details/gtudrueexz.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.gogol.net.cn/Article/details/gtohmthmzh.html

Ruby: warn "err"
来源：http://dali.gzhubu.top/Article/details/gtnisfqhys.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhoulong.xyz/Article/details/gtkihguijy.html

[M07] 判断是否为主入口
来源：http://dali.sxryk.cn/Article/details/gtudaoartl.html

Py:   if __name__ == "__main__":
来源：http://dali.svipenyu.cn/Article/details/gtxwswvmgf.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.ehwqpu.com/Article/details/gtebnxwpvh.html

JS:   require.main === module
来源：http://dali.iojbl.cn/Article/details/gtkezjaoyv.html

TS:   require.main === module
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqcdagxzl.html

Java: public static void main(String[] args)
来源：http://dali.fengsongda.top/Article/details/gtdibsagob.html

Go:   func main()
来源：http://dali.fengsongda.top/Article/details/gtfgeffgyx.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.xylfe.cn/Article/details/gtlgdlmhnn.html

C#:   static void Main(string[] args)
来源：http://dali.andypj.xyz/Article/details/gtbluqwiul.html

[M08] 获取系统与运行时信息
来源：http://dali.gaohongyu789.top/Article/details/gtymjaeovw.html

Py:   platform.system();  platform.python_version()
来源：http://dali.chenzaomai.com/Article/details/gtdqwtfcvh.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.smart0.xyz/Article/details/gtuintvdoh.html

JS:   process.platform;  process.version
来源：http://dali.daxiang520.top/Article/details/gtfgzvqmhi.html

TS:   process.platform;  process.version
来源：http://dali.xziqi.cn/Article/details/gtopmpktcw.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.jlsjyb.cn/Article/details/gtkhjrkkdx.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhiwuduotai.top/Article/details/gtrervaift.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.jiagoushi.top/Article/details/gtantsfegp.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.aizwys.cn/Article/details/gtjwnbpuhf.html

================================================================================
来源：http://dali.sweek.top/Article/details/gttqaxatlg.html

N. 数据结构与算法
来源：http://dali.kuanghao11.cn/Article/details/gtmbfenmoo.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtsafbsrpe.html

[N01] 二分查找（有序数组）
来源：http://dali.dianchejie.cn/Article/details/gtgapnmrdk.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.jyoumei.cn/Article/details/gtovrjnlqp.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.hnqzz.top/Article/details/gtsvvcdaef.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hywenlv.cn/Article/details/gteprxlkfv.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.ydzc1.top/Article/details/gtpybyopkp.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.andypj.xyz/Article/details/gtyimfmvod.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.ivvv.top/Article/details/gtgytntjzl.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.aizwys.cn/Article/details/gtqmcilvcr.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.dianchejie.cn/Article/details/gtehjbcfmr.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhoulong.xyz/Article/details/gtngepdbwz.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.iojbl.cn/Article/details/gtggyoczeq.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtijwetxmn.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.snrcjt.cn/Article/details/gtxhilgfyx.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.mhx1999.top/Article/details/gtsdpzffki.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.jinqigufen.top/Article/details/gtxwmlpoys.html

Go:   slices.Sort(arr)
来源：http://dali.jinqigfzy.top/Article/details/gtzyzdnubd.html

Ruby: arr.sort
来源：http://dali.yongpay.top/Article/details/gtycdjwofs.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.sufxvd.cn/Article/details/gtfbdfqngl.html

[N03] 快速排序（分治示例）
来源：http://dali.aibaodan.cn/Article/details/gtvyebeldn.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.jinqigufen.top/Article/details/gtalwcdwfd.html

PHP:  // 递归实现，或用 usort
来源：http://dali.yueranfly.top/Article/details/gtgsauvxbc.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.xuanzx.com/Article/details/gtqeovrhlu.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.andypj.xyz/Article/details/gtowlevcsb.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.yangfankeji.com/Article/details/gtivrrwiuc.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.aibaodan.cn/Article/details/gtovqwtikm.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.tian-w.cn/Article/details/gttjckuksw.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.yj20258.top/Article/details/gtsaiburot.html

[N04] 斐波那契数列
来源：http://dali.nanxinkj.top/Article/details/gthgkeeqie.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.redwolf501.top/Article/details/gtrpknmgpm.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.cashguo.top/Article/details/gtmhylgwwh.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jinqigfzy.top/Article/details/gtbdozqpyn.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.guannengcc.top/Article/details/gtoerluyhl.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.ybcxt.top/Article/details/gtzwfnwfui.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.tianlin.xyz/Article/details/gtluivwikp.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.hongshengwenyu.top/Article/details/gtzznhzhsn.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.nwbrower.top/Article/details/gtojrplwha.html

[N05] 最大公约数
来源：http://dali.hysaishi.cn/Article/details/gtsadnnxws.html

Py:   math.gcd(a, b)
来源：http://dali.vqdsnc.cn/Article/details/gtzqvefxki.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.svipenyu.cn/Article/details/gtlnmlmwjp.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.tianlin.xyz/Article/details/gtggggzyak.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jiagoushi.top/Article/details/gtxvucuttd.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.gogol.net.cn/Article/details/gthjpawmze.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.jinqigufen.top/Article/details/gtzwaazlkz.html

Ruby: a.gcd(b)
来源：http://dali.jinqigfzy.top/Article/details/gtkizyoeca.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.ehwqpu.com/Article/details/gtzmpxxzhb.html

[N06] 判断回文字符串
来源：http://dali.tian-w.cn/Article/details/gtidtnxqxh.html

Py:   s == s[::-1]
来源：http://dali.hywenlv.cn/Article/details/gtuublxyba.html

PHP:  $s === strrev($s);
来源：http://dali.yuxming.cn/Article/details/gtwiwrrprw.html

JS:   s === [...s].reverse().join("")
来源：http://dali.jianghu66.top/Article/details/gtidyxecaz.html

TS:   s === [...s].reverse().join("")
来源：http://dali.hysaishi.cn/Article/details/gtyanjomre.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.dashuyun.cn/Article/details/gtuedyfped.html

Go:   // 双指针从两端比较
来源：http://dali.cucudq.cn/Article/details/gtdeuhigar.html

Ruby: s == s.reverse
来源：http://dali.zhixingplan.top/Article/details/gtoqimolcl.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.redwolf501.top/Article/details/gtplvxwwhq.html

[N07] 两数之和（返回下标）
来源：http://dali.jlsjyb.cn/Article/details/gthisldgkj.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.hammf.cn/Article/details/gtptronyld.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.hfpthk.cn/Article/details/gtxijqmwvb.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.pengpengdd.cyou/Article/details/gtqrnihpkb.html

TS:   // 手写 Map<string, number>
来源：http://dali.gaohongyu789.top/Article/details/gtraueaqyg.html

Java: // 手写 HashMap
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdeufadjb.html

Go:   // 手写 map[int]int
来源：http://dali.chenjidiqi.icu/Article/details/gtyeuateui.html

Ruby: // 手写 Hash
来源：http://dali.xinyue.icu/Article/details/gtoihvfvwa.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.yueranfly.top/Article/details/gthvzjctrr.html

[N08] 生成全排列
来源：http://dali.nanxuanxn.top/Article/details/gtiphkkzti.html

Py:   itertools.permutations(arr)
来源：http://dali.gaohongyu789.top/Article/details/gtxtdhkolf.html

PHP:  // 手写递归交换
来源：http://dali.gaohongyu789.top/Article/details/gtnwrabked.html

JS:   // 手写回溯递归
来源：http://dali.guannengcc.top/Article/details/gtzvpflldf.html

TS:   // 手写回溯递归
来源：http://dali.hfpthk.cn/Article/details/gtirvdcaqj.html

Java: // 手写回溯递归
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcthffcne.html

Go:   // 手写回溯递归
来源：http://dali.jinghuilouyu.cn/Article/details/gtikhwhmdg.html

Ruby: arr.permutation.to_a
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkxnhzlrb.html

C#:   // 手写回溯递归
来源：http://dali.aibaodan.cn/Article/details/gtxobxjvqk.html

[N09] 栈与队列
来源：http://dali.tian-w.cn/Article/details/gtptcjfwwf.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.ppjwa.cn/Article/details/gtmwmopowj.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.bjfxy.top/Article/details/gtaayednqd.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.9152youxi.cn/Article/details/gtlgcqcnlr.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.nanxuanxn.top/Article/details/gtswbycjzq.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.sysykeji.top/Article/details/gtuptlvrfo.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.cqqwz.cn/Article/details/gtaekuctmf.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.haohaochexian.top/Article/details/gtgxbeqaal.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.daxiang520.top/Article/details/gttcfujqyp.html

[N10] 链表节点定义
来源：http://dali.nanxinkj.top/Article/details/gtpvgmxiea.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.daria6918.cn/Article/details/gtefcnuxmu.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.gzhubu.top/Article/details/gtdetwossb.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.yongpay.top/Article/details/gtmfjiilun.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhongyouzk.top/Article/details/gtkwutzgzf.html

Java: class Node { int v; Node next; }
来源：http://dali.quarkkingdee.top/Article/details/gtvylyhcku.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.jiagoushi.top/Article/details/gtsvlcwbae.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.chenzaomai.com/Article/details/gtvravhehc.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.cheryme.top/Article/details/gthuqnttoj.html

[N11] 二叉树中序遍历
来源：http://dali.sweek.top/Article/details/gtwpyxbzlf.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxykfvojv.html

PHP:  // 手写递归函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gthhgvkmfc.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.pengpengdd.cyou/Article/details/gtyrywicke.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jqgufenzy.top/Article/details/gtykqkevsr.html

Java: // 手写递归
来源：http://dali.sysykeji.top/Article/details/gtvkfldnux.html

Go:   // 手写递归
来源：http://dali.hnxiangtu.top/Article/details/gtaozeuzrn.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.316326.xyz/Article/details/gtdspkodkw.html

C#:   // 手写递归
来源：http://dali.cheryme.top/Article/details/gtboyefibk.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.fengsongda.top/Article/details/gtyagsltef.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.ydzc1.top/Article/details/gtcmggnvsl.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.nanxinkj.top/Article/details/gtiyvxoqav.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.hongshengwenyu.top/Article/details/gtvebyncuy.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.aibaodan.cn/Article/details/gtvkfwknjn.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.bjfxy.top/Article/details/gtynduorgx.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.chenzaomai.com/Article/details/gtycpqctpu.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzmjciosn.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.xuetiantiany.cn/Article/details/gtzhhiqcld.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtyftsvyog.html

O. 并发与异步
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkhjxmjpq.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gttvgywfez.html

[O01] 启动一个线程
来源：http://dali.nanxinkj.top/Article/details/gtxrjnuvlj.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.haohaochexian.top/Article/details/gtkqdvhmvn.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.havefunace.top/Article/details/gtrwqfcyxp.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.kuanghao11.cn/Article/details/gtlxzzudro.html

TS:   // 同 JS
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpxkdypnn.html

Java: new Thread(() -> f()).start()
来源：http://dali.ivvv.top/Article/details/gtkvdekqeo.html

Go:   go f()
来源：http://dali.feifeiyinyue.top/Article/details/gtmhbfmntn.html

Ruby: Thread.new { f }
来源：http://dali.jqgfzy.top/Article/details/gtzsjnrkww.html

C#:   Task.Run(() => F());
来源：http://dali.cheryme.top/Article/details/gtecvnnkhf.html

[O02] 使用线程池
来源：http://dali.yuanzhike.top/Article/details/gtyecmjcok.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.cheryme.top/Article/details/gtuzirngpa.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkvzyxyxy.html

JS:   // worker_threads 线程池
来源：http://dali.daria6918.cn/Article/details/gtmvxgrayp.html

TS:   // worker_threads 线程池
来源：http://dali.shangyingyoupin.top/Article/details/gtpnnevtfe.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.yj20258.top/Article/details/gthwhuqcfm.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.sufxvd.cn/Article/details/gtlzpsnpzk.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zdqjudy.top/Article/details/gttrkxhaiu.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.iojbl.cn/Article/details/gtyamrshlg.html

[O03] 加锁保护共享数据
来源：http://dali.ybcxt.top/Article/details/gtoaaszlbu.html

Py:   with lock: shared += 1
来源：http://dali.pycfn.com/Article/details/gtbrtxeypo.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.hysaishi.cn/Article/details/gtalixnghn.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.svipenyu.cn/Article/details/gtuvbtnaan.html

TS:   // 同 JS
来源：http://dali.nanxinkj.top/Article/details/gtqcnizivk.html

Java: synchronized (this) { shared++; }
来源：http://dali.ybcxt.top/Article/details/gtlkagepnz.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.hammf.cn/Article/details/gtdczbzrnn.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.meibo888.top/Article/details/gtamtcunwu.html

C#:   lock (gate) { shared++; }
来源：http://dali.havefunace.top/Article/details/gtrhagnjfz.html

[O04] 定义异步函数并等待
来源：http://dali.wangdashe.top/Article/details/gtojjpfiqv.html

Py:   async def f():⏎    await g()
来源：http://dali.ybcxt.top/Article/details/gtdxlkxbhc.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.andypj.xyz/Article/details/gtpxaieohv.html

JS:   async function f() { await g(); }
来源：http://dali.xziqi.cn/Article/details/gtozwsmwws.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.yuanzhike.top/Article/details/gtgmxkrejt.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.shzxlz.cn/Article/details/gtwcgkmjxr.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.hnqzz.top/Article/details/gtrhfowpfi.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.shangyingyoupin.top/Article/details/gtsajyfiqh.html

C#:   async Task F() { await G(); }
来源：http://dali.gotoacloud.top/Article/details/gtqabgpmkm.html

[O05] 并发执行并等待全部完成
来源：http://dali.feifeiyinyue.top/Article/details/gtcmbsrtge.html

Py:   asyncio.gather(*tasks)
来源：http://dali.shuidangran.top/Article/details/gtrlwzwzdy.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhoulong.xyz/Article/details/gtsxnepsws.html

JS:   await Promise.all(tasks)
来源：http://dali.guowangkeji.top/Article/details/gternmixpi.html

TS:   await Promise.all(tasks)
来源：http://dali.chenzaomai.com/Article/details/gtvjlllwwo.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.yangfankeji.com/Article/details/gtnavstghb.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.cucudq.cn/Article/details/gthyahmjzt.html

Ruby: threads.map(&:join)
来源：http://dali.xuanzx.com/Article/details/gtzptuhvhm.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.dianchejie.cn/Article/details/gtuxemakmj.html

[O06] 使用进程池
来源：http://dali.cqqwz.cn/Article/details/gtxxfonlhz.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.jinghuilouyu.cn/Article/details/gtayilaiwr.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.yuxming.cn/Article/details/gtdkhdlxid.html

JS:   // child_process / cluster 模块
来源：http://dali.ybcxt.top/Article/details/gteebivmpj.html

TS:   // child_process / cluster 模块
来源：http://dali.sufxvd.cn/Article/details/gtgelwajmh.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.c1oappe.top/Article/details/gtfpayqlvc.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.yanxiufei.cn/Article/details/gtdoopbtwg.html

Ruby: // fork 块
来源：http://dali.chenjidiqi.icu/Article/details/gtsvfwszov.html

C#:   Parallel.For
来源：http://dali.xziqi.cn/Article/details/gtfpaqzbvi.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtculazxwr.html

P. 常用工具函数
来源：http://dali.cdnleiting.top/Article/details/gtguyfwlgw.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtpeirxlme.html

[P01] 生成 UUID
来源：http://dali.guannengcc.top/Article/details/gtivdqedhl.html

Py:   str(uuid.uuid4())
来源：http://dali.nanxinkj.top/Article/details/gtlnaeexxu.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.ybcxt.top/Article/details/gtvjgujyir.html

JS:   crypto.randomUUID()
来源：http://dali.cheryme.top/Article/details/gtoiiqtmqn.html

TS:   crypto.randomUUID()
来源：http://dali.iojbl.cn/Article/details/gthlwrydzb.html

Java: UUID.randomUUID().toString()
来源：http://dali.yonumen.top/Article/details/gtvksvmcfd.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhengqikj.top/Article/details/gtyvhphbkk.html

Ruby: SecureRandom.uuid
来源：http://dali.pycfn.com/Article/details/gtudcqxxmm.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.tian-w.cn/Article/details/gtkihjmjpl.html

[P02] MD5 / SHA256 摘要
来源：http://dali.meibo888.top/Article/details/gtcdaooiat.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.birdmap.top/Article/details/gtqkvkdahv.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.svipenyu.cn/Article/details/gtapzyqsxl.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zdqjudy.top/Article/details/gtfnyhnios.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.jinghuilouyu.cn/Article/details/gtsvcsxurn.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.redwolf501.top/Article/details/gtdkghkamm.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.sysykeji.top/Article/details/gtxkbllniz.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtesirrysk.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.pycfn.com/Article/details/gtsnuktgdq.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gtuvtrhkrn.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.zhiwuduotai.top/Article/details/gtrasoymcx.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.shanyushiyangtech.top/Article/details/gttwjdkewq.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.chenlongwang.top/Article/details/gttxwojxuz.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yj20258.top/Article/details/gteljltwsr.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.iojbl.cn/Article/details/gtiainkqxu.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.zhiwuduotai.top/Article/details/gtetixuwts.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.jianghu66.top/Article/details/gtydbskque.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.xinyue.icu/Article/details/gtvyhuiiga.html

[P04] 求长度
来源：http://dali.yj20258888.top/Article/details/gtevdfeuny.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.hongshengwenyu.top/Article/details/gtijyrjiuk.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtouuplubc.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.pycfn.com/Article/details/gtjcljyzhn.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.zdqjudy.top/Article/details/gtqjjscgxh.html

Java: list.size();  map.size();  s.length()
来源：http://dali.hywenlv.cn/Article/details/gtnibaaihw.html

Go:   len(arr);  len(m)
来源：http://dali.sysykeji.top/Article/details/gtokumckvt.html

Ruby: x.length;  x.size
来源：http://dali.xylfe.cn/Article/details/gtefrlgbjn.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.cucudq.cn/Article/details/gtqaezmwek.html

[P05] 判断两个对象内容是否相等
来源：http://dali.wangshuangyany.cn/Article/details/gtxbwhaswm.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.shanyushiyangtech.top/Article/details/gtvoltnlkz.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.meibo888.top/Article/details/gtrtoznoxx.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.c1oappe.top/Article/details/gtkvbvsnra.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.hywenlv.cn/Article/details/gtdvzkpdrx.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.vqdsnc.cn/Article/details/gtlitlzvya.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.hnqzz.top/Article/details/gtidksrhvr.html

Ruby: a == b
来源：http://dali.yonumen.top/Article/details/gtzrkamrqe.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.sxryk.cn/Article/details/gtnwzylafd.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.feifeiyinyue.top/Article/details/gtymhjhlvd.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.andypj.xyz/Article/details/gtwoynofgs.html

PHP:  if (empty($x)) {}
来源：http://dali.yuanzhike.top/Article/details/gtbmgdqxqw.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.xylfe.cn/Article/details/gtwodpspfa.html

TS:   if (x == null) {}
来源：http://dali.xinyue.icu/Article/details/gtwwwyecog.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.cdnleiting.top/Article/details/gtlkiegnse.html

Go:   if x == nil {}
来源：http://dali.chenjidiqi.icu/Article/details/gtapjdrirb.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.yongpay.top/Article/details/gtgecicuvb.html

C#:   if (x is null) {}
来源：http://dali.aibaodan.cn/Article/details/gtlqmlwhla.html

[P07] 防抖与节流
来源：http://dali.hfpthk.cn/Article/details/gtwlbavgbx.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.jianghu66.top/Article/details/gtownwoagb.html

PHP:  // 手写时间戳比较
来源：http://dali.hfpthk.cn/Article/details/gtvwcddwwg.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.pengpengdd.cyou/Article/details/gtikkebefp.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.shanyushiyangtech.top/Article/details/gtgvzvohjx.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.kuanghao11.cn/Article/details/gtkpbwftdy.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.cheryme.top/Article/details/gtpsxtozgt.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.0kj1m.cn/Article/details/gtomscywfc.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.nwbrower.top/Article/details/gttuybdpig.html

[P08] 处理浮点精度问题
来源：http://dali.fengsongda.top/Article/details/gthmvtgwed.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.hysaishi.cn/Article/details/gtqvjxypte.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.jinghuilouyu.cn/Article/details/gthckdfjtb.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.zhixingplan.top/Article/details/gtnzwkntno.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.jyoumei.cn/Article/details/gtaydrjiyp.html


<!-- 参考信息 -->