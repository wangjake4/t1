代发 wailian999

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.316326.xyz/Article/details/gtmiyvjqkq.html

JS:   process.env.HOME
来源：http://dali.gotoacloud.top/Article/details/gtwokrmbhq.html

TS:   process.env.HOME
来源：http://dali.jinghuilouyu.cn/Article/details/gthjuxctpn.html

Java: System.getenv("HOME")
来源：http://dali.xziqi.cn/Article/details/gtmivehngs.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.hywenlv.cn/Article/details/gtkfglekhi.html

Ruby: ENV["HOME"]
来源：http://dali.xinyue.icu/Article/details/gtjmbpxbjp.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.shzxlz.cn/Article/details/gtaypfbcfs.html

[M03] 执行外部命令
来源：http://dali.yj20258888.top/Article/details/gthtcazgnu.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.fengsongda.top/Article/details/gtswyvckzz.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.yj202588.top/Article/details/gtxnjbqejx.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.yvedp.cn/Article/details/gtpntcretc.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zycfv.cn/Article/details/gtbvvnbrfk.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.cdnleiting.top/Article/details/gtweogpvec.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrapqcafh.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.yueranfly.top/Article/details/gtrzdqenvy.html

C#:   Process.Start("ls", "-l");
来源：http://dali.vqdsnc.cn/Article/details/gtzsjanoqj.html

[M04] 获取当前工作目录
来源：http://dali.jqgufenzy.top/Article/details/gtlqhyarvl.html

Py:   os.getcwd()
来源：http://dali.gogol.net.cn/Article/details/gtrxqatkwy.html

PHP:  getcwd();
来源：http://dali.daria6918.cn/Article/details/gtjxexfnwn.html

JS:   process.cwd()
来源：http://dali.zhaomingkeji.xyz/Article/details/gthmaqgnaj.html

TS:   process.cwd()
来源：http://dali.sweek.top/Article/details/gtwztifudl.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.yonumen.top/Article/details/gtifvxkjug.html

Go:   os.Getwd()
来源：http://dali.jinqigfzy.top/Article/details/gtgbqjjqnz.html

Ruby: Dir.pwd
来源：http://dali.daxiang520.top/Article/details/gtmlgohrqq.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgrbdkqrx.html

[M05] 设置退出码
来源：http://dali.yj202588.top/Article/details/gtyqhsuqhp.html

Py:   sys.exit(1)
来源：http://dali.quarkkingdee.top/Article/details/gtombeuorw.html

PHP:  exit(1);
来源：http://dali.hysaishi.cn/Article/details/gtzjctgqsy.html

JS:   process.exit(1)
来源：http://dali.redwolf501.top/Article/details/gtiwlqqqnc.html

TS:   process.exit(1)
来源：http://dali.bjfxy.top/Article/details/gtwujyjyjn.html

Java: System.exit(1)
来源：http://dali.xuetiantiany.cn/Article/details/gtyydoxjqg.html

Go:   os.Exit(1)
来源：http://dali.nwbrower.top/Article/details/gtfpiovbsi.html

Ruby: exit 1
来源：http://dali.tianlin.xyz/Article/details/gtusxofmbr.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.hysaishi.cn/Article/details/gtppplugte.html

[M06] 向标准错误输出
来源：http://dali.nwbrower.top/Article/details/gtouopdouh.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zdqjudy.top/Article/details/gteuuvhyka.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.yuxming.cn/Article/details/gtdikmgmwi.html

JS:   console.error("err")
来源：http://dali.shangyingyoupin.top/Article/details/gtnlydfklb.html

TS:   console.error("err")
来源：http://dali.fengsongda.top/Article/details/gtfluslras.html

Java: System.err.println("err")
来源：http://dali.jinghuilouyu.cn/Article/details/gtvvwsnfgu.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.guannengcc.top/Article/details/gtrxugskjh.html

Ruby: warn "err"
来源：http://dali.chenzaomai.com/Article/details/gtnrnunmpy.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.jianghu66.top/Article/details/gtojjccqff.html

[M07] 判断是否为主入口
来源：http://dali.pengpengdd.cyou/Article/details/gtplvtcpia.html

Py:   if __name__ == "__main__":
来源：http://dali.meibo888.top/Article/details/gtrytdfksu.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.0kj1m.cn/Article/details/gtrlzqwbfr.html

JS:   require.main === module
来源：http://dali.chenzaomai.com/Article/details/gtdzhcpooh.html

TS:   require.main === module
来源：http://dali.hnqzz.top/Article/details/gtrxtttfiv.html

Java: public static void main(String[] args)
来源：http://dali.wangshuangyany.cn/Article/details/gtexahmugf.html

Go:   func main()
来源：http://dali.tanke756.top/Article/details/gtcvrbatkm.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.shzxlz.cn/Article/details/gtkmxejjvc.html

C#:   static void Main(string[] args)
来源：http://dali.jyoumei.cn/Article/details/gtvkrklcdo.html

[M08] 获取系统与运行时信息
来源：http://dali.guowangkeji.top/Article/details/gtzcchaavd.html

Py:   platform.system();  platform.python_version()
来源：http://dali.yongpay.top/Article/details/gtarimpwcn.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.gzhubu.top/Article/details/gtakphamip.html

JS:   process.platform;  process.version
来源：http://dali.feifeiyinyue.top/Article/details/gtvoygcbov.html

TS:   process.platform;  process.version
来源：http://dali.shangyingyoupin.top/Article/details/gtfmhatsxa.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.gogol.net.cn/Article/details/gtoxuucbzp.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhengqikj.top/Article/details/gtjgjbjnhp.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.yongpay.top/Article/details/gtvqnhqevj.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.smart0.xyz/Article/details/gtmzxsmlck.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtcidilrmm.html

N. 数据结构与算法
来源：http://dali.ppjwa.cn/Article/details/gtvoezyrft.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtwetooihf.html

[N01] 二分查找（有序数组）
来源：http://dali.hongshengwenyu.top/Article/details/gtnlrrcyrq.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrrsudxjr.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.svipenyu.cn/Article/details/gtxmnvneuy.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.0kj1m.cn/Article/details/gtbvfacurm.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jinqigfzy.top/Article/details/gtactomhrw.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.feifeiyinyue.top/Article/details/gtlwkpbjhq.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.hywenlv.cn/Article/details/gtgmpogxfv.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.jianghu66.top/Article/details/gtxfxodgpp.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gtjhxgnjxz.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.pycfn.com/Article/details/gtpryncjzz.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.hongshengwenyu.top/Article/details/gtzcmjmbup.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zdqjudy.top/Article/details/gtcimjjprh.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.ehwqpu.com/Article/details/gtpjrgmjwp.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yangfankeji.com/Article/details/gtpnzrtpbi.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.yongpay.top/Article/details/gtykrqutum.html

Go:   slices.Sort(arr)
来源：http://dali.tian-w.cn/Article/details/gtpoohygki.html

Ruby: arr.sort
来源：http://dali.gogol.net.cn/Article/details/gtrvsiuihu.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.feifeiyinyue.top/Article/details/gtarjekisn.html

[N03] 快速排序（分治示例）
来源：http://dali.tanke756.top/Article/details/gtayjlgedx.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.xuetiantiany.cn/Article/details/gtyylxdxal.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhoulong.xyz/Article/details/gtfyfmtgmo.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.shzxlz.cn/Article/details/gttbmnmgob.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.nwbrower.top/Article/details/gtwvlnberv.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.hnqzz.top/Article/details/gttmubjjfl.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zycfv.cn/Article/details/gtkpekeixq.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.jiagoushi.top/Article/details/gtmfokmbxl.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.xziqi.cn/Article/details/gtcismobwt.html

[N04] 斐波那契数列
来源：http://dali.jinghuilouyu.cn/Article/details/gtphmkiczz.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhixingplan.top/Article/details/gtkupkhfki.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.gogol.net.cn/Article/details/gtnadcsthg.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.wangdashe.top/Article/details/gtpwdgkmpf.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.pengpengdd.cyou/Article/details/gtzpjcoomq.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.jqgufenzy.top/Article/details/gtasjnoetv.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.aizwys.cn/Article/details/gtdcfcreyz.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhengqikj.top/Article/details/gtkpjpnmtl.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.0kj1m.cn/Article/details/gtzvqzozhx.html

[N05] 最大公约数
来源：http://dali.mhx1999.top/Article/details/gtqiuszsna.html

Py:   math.gcd(a, b)
来源：http://dali.jqgufenzy.top/Article/details/gtfyrqwtun.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zdqjudy.top/Article/details/gtbvfvqvwy.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.sxryk.cn/Article/details/gtufcibmfr.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzhqqiflg.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.cheryme.top/Article/details/gtalhxpxfn.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.c1oappe.top/Article/details/gtudqgiwbn.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gtebkhmptn.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.yuanzhike.top/Article/details/gtlxlkwjoi.html

[N06] 判断回文字符串
来源：http://dali.zhengqikj.top/Article/details/gtlxbexvqw.html

Py:   s == s[::-1]
来源：http://dali.sxryk.cn/Article/details/gtokatorrc.html

PHP:  $s === strrev($s);
来源：http://dali.dashuyun.cn/Article/details/gtevteqqty.html

JS:   s === [...s].reverse().join("")
来源：http://dali.hywenlv.cn/Article/details/gtzpsjsgdp.html

TS:   s === [...s].reverse().join("")
来源：http://dali.cucudq.cn/Article/details/gtbuhdgxgx.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.guannengcc.top/Article/details/gtzuvvbpjf.html

Go:   // 双指针从两端比较
来源：http://dali.birdmap.top/Article/details/gtxpyczpde.html

Ruby: s == s.reverse
来源：http://dali.wangshuangyany.cn/Article/details/gtrdwbbuvz.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.hongshengwenyu.top/Article/details/gtgkegtbyn.html

[N07] 两数之和（返回下标）
来源：http://dali.andypj.xyz/Article/details/gtzjfepwhq.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zycfv.cn/Article/details/gtpjggqujp.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.ywan-chungtsiang.top/Article/details/gtanvzvmqs.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.tianlin.xyz/Article/details/gtzrxvmyqg.html

TS:   // 手写 Map<string, number>
来源：http://dali.dianchejie.cn/Article/details/gtabpnmlyd.html

Java: // 手写 HashMap
来源：http://dali.pengpengdd.cyou/Article/details/gtxwvmbctv.html

Go:   // 手写 map[int]int
来源：http://dali.cdnleiting.top/Article/details/gtslxqeofu.html

Ruby: // 手写 Hash
来源：http://dali.jianghu66.top/Article/details/gtsjcryarv.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.chenlongwang.top/Article/details/gtsdepmtey.html

[N08] 生成全排列
来源：http://dali.zhengqikj.top/Article/details/gtgcptqtxu.html

Py:   itertools.permutations(arr)
来源：http://dali.hnqzz.top/Article/details/gtgzvxzdtv.html

PHP:  // 手写递归交换
来源：http://dali.cqqwz.cn/Article/details/gtbxvmocoq.html

JS:   // 手写回溯递归
来源：http://dali.quarkkingdee.top/Article/details/gtmniyvxae.html

TS:   // 手写回溯递归
来源：http://dali.wangshuangyany.cn/Article/details/gtiasarylr.html

Java: // 手写回溯递归
来源：http://dali.yuanzhike.top/Article/details/gtpdcstqyc.html

Go:   // 手写回溯递归
来源：http://dali.guowangkeji.top/Article/details/gthrnzysrj.html

Ruby: arr.permutation.to_a
来源：http://dali.tianlin.xyz/Article/details/gtgsrtotek.html

C#:   // 手写回溯递归
来源：http://dali.havefunace.top/Article/details/gtcpmttfbt.html

[N09] 栈与队列
来源：http://dali.ivvv.top/Article/details/gtjnmwoltn.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.chenlongwang.top/Article/details/gtwztsyppt.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.tanke756.top/Article/details/gtkxiuroku.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.jiagoushi.top/Article/details/gttbovhekj.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.xziqi.cn/Article/details/gtgghrujfc.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.meibo888.top/Article/details/gtjbalpfdm.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.nanxinkj.top/Article/details/gtfbowbolx.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.yueranfly.top/Article/details/gtoqrasyun.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.hfpthk.cn/Article/details/gtvcodrkbv.html

[N10] 链表节点定义
来源：http://dali.redwolf501.top/Article/details/gtxjyaanaw.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.hnqzz.top/Article/details/gtrzedqnhf.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.fengsongda.top/Article/details/gtiqpiwykl.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.xuanzx.com/Article/details/gtrqpkabto.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.xuetiantiany.cn/Article/details/gtmeqrjsrj.html

Java: class Node { int v; Node next; }
来源：http://dali.chenlongwang.top/Article/details/gtgfvrrlei.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.feifeiyinyue.top/Article/details/gtgeewoklw.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.ivvv.top/Article/details/gtxrorvnwy.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.shuidangran.top/Article/details/gtysztwptd.html

[N11] 二叉树中序遍历
来源：http://dali.zycfv.cn/Article/details/gtvgjypcod.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.gotoacloud.top/Article/details/gtpsciemee.html

PHP:  // 手写递归函数
来源：http://dali.pycfn.com/Article/details/gtqirdkyeo.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yvedp.cn/Article/details/gtbnyeyemb.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.gotoacloud.top/Article/details/gtgsjhvpis.html

Java: // 手写递归
来源：http://dali.wangdashe.top/Article/details/gttqipsjuv.html

Go:   // 手写递归
来源：http://dali.ywan-chungtsiang.top/Article/details/gtalkasvan.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhengqikj.top/Article/details/gtenyusfxh.html

C#:   // 手写递归
来源：http://dali.ppjwa.cn/Article/details/gthdsruwrz.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.daxiang520.top/Article/details/gtwaibnkze.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.shuidangran.top/Article/details/gtikzbilco.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.smart0.xyz/Article/details/gtsxdoldyu.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.nanxinkj.top/Article/details/gtcodnfizy.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.cheryme.top/Article/details/gtcxifvnpz.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.andypj.xyz/Article/details/gtbyzljpda.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.guowangkeji.top/Article/details/gtgmnhoowr.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.snrcjt.cn/Article/details/gtfglmpsuj.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.shuidangran.top/Article/details/gtlllffziu.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtavfchqbu.html

O. 并发与异步
来源：http://dali.shangyingyoupin.top/Article/details/gtvnmuagiz.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtcnaovvzb.html

[O01] 启动一个线程
来源：http://dali.jqgufenzy.top/Article/details/gtrtxsnxrp.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.gotoacloud.top/Article/details/gtiunemdjt.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.yj202588.top/Article/details/gtssimuzgq.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.vqdsnc.cn/Article/details/gtpvvjivjy.html

TS:   // 同 JS
来源：http://dali.tian-w.cn/Article/details/gtzgjzzdkf.html

Java: new Thread(() -> f()).start()
来源：http://dali.nwbrower.top/Article/details/gthxhdgwtg.html

Go:   go f()
来源：http://dali.yongpay.top/Article/details/gtwhyletnp.html

Ruby: Thread.new { f }
来源：http://dali.pycfn.com/Article/details/gttgzmcdwq.html

C#:   Task.Run(() => F());
来源：http://dali.zhaomingkeji.xyz/Article/details/gtheoxkiqm.html

[O02] 使用线程池
来源：http://dali.jinqigfzy.top/Article/details/gtxuepvqnf.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.hysaishi.cn/Article/details/gthwyuddqw.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfbkxrdsc.html

JS:   // worker_threads 线程池
来源：http://dali.hnxiangtu.top/Article/details/gtpolmhsiy.html

TS:   // worker_threads 线程池
来源：http://dali.shzxlz.cn/Article/details/gtdxoeipen.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrhkdwpie.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.jiagoushi.top/Article/details/gtitjqvetx.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.havefunace.top/Article/details/gtylozfmdi.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.0kj1m.cn/Article/details/gtrvgqwuwb.html

[O03] 加锁保护共享数据
来源：http://dali.yj202588.top/Article/details/gtojofmfrx.html

Py:   with lock: shared += 1
来源：http://dali.9152youxi.cn/Article/details/gtfxhonzjj.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.sufxvd.cn/Article/details/gtmyaswdlg.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.gogol.net.cn/Article/details/gtnxrhvfoh.html

TS:   // 同 JS
来源：http://dali.redwolf501.top/Article/details/gtukrbuptr.html

Java: synchronized (this) { shared++; }
来源：http://dali.nanxuanxn.top/Article/details/gtjrdgmurr.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.kuanghao11.cn/Article/details/gtsxntlwfl.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.jinqigfzy.top/Article/details/gtubhwbdii.html

C#:   lock (gate) { shared++; }
来源：http://dali.daxiang520.top/Article/details/gtmtbxogza.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gtrgqpeadg.html

Py:   async def f():⏎    await g()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtecifdoxa.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.yvedp.cn/Article/details/gtynrhyapd.html

JS:   async function f() { await g(); }
来源：http://dali.shangyingyoupin.top/Article/details/gtdxaskhtd.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.c1oappe.top/Article/details/gtzzklksdl.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.chenzaomai.com/Article/details/gtodleewan.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.xinyue.icu/Article/details/gtrjubzpqr.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.havefunace.top/Article/details/gtabusgdew.html

C#:   async Task F() { await G(); }
来源：http://dali.wangshuangyany.cn/Article/details/gthjbggxpu.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gtrkhhoovh.html

Py:   asyncio.gather(*tasks)
来源：http://dali.ydzc1.top/Article/details/gtwrtkhthc.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.snrcjt.cn/Article/details/gtjvnlovei.html

JS:   await Promise.all(tasks)
来源：http://dali.haohaochexian.top/Article/details/gtecgugrqe.html

TS:   await Promise.all(tasks)
来源：http://dali.yuanzhike.top/Article/details/gtqkwzjzsz.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtswiehhkx.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.guannengcc.top/Article/details/gtnaclcebc.html

Ruby: threads.map(&:join)
来源：http://dali.cdnleiting.top/Article/details/gtwbnyiygk.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.yangfankeji.com/Article/details/gtwejbmqwy.html

[O06] 使用进程池
来源：http://dali.zycfv.cn/Article/details/gthwpdmqdu.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.fzhhl.top/Article/details/gtrpubhzte.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.birdmap.top/Article/details/gtiksiyfdv.html

JS:   // child_process / cluster 模块
来源：http://dali.quarkkingdee.top/Article/details/gtmrcyxkrc.html

TS:   // child_process / cluster 模块
来源：http://dali.jinqigufen.top/Article/details/gtaowoduhq.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.tanke756.top/Article/details/gtpptzrtcx.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.yueranfly.top/Article/details/gtfzldgugn.html

Ruby: // fork 块
来源：http://dali.guannengcc.top/Article/details/gtfladpwhn.html

C#:   Parallel.For
来源：http://dali.meibo888.top/Article/details/gtbsywzeub.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtnbnrosye.html

P. 常用工具函数
来源：http://dali.nanxuanxn.top/Article/details/gtkmohyckq.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtsaqrwtdo.html

[P01] 生成 UUID
来源：http://dali.ydzc1.top/Article/details/gtvuemycmo.html

Py:   str(uuid.uuid4())
来源：http://dali.xuanzx.com/Article/details/gtqtpsssmp.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.fzhhl.top/Article/details/gtpeeqxehh.html

JS:   crypto.randomUUID()
来源：http://dali.daxiang520.top/Article/details/gtltwckoxx.html

TS:   crypto.randomUUID()
来源：http://dali.daxiang520.top/Article/details/gtuogvggym.html

Java: UUID.randomUUID().toString()
来源：http://dali.havefunace.top/Article/details/gteokjvhda.html

Go:   // 用 github.com/google/uuid
来源：http://dali.haohaochexian.top/Article/details/gtynrqcbxf.html

Ruby: SecureRandom.uuid
来源：http://dali.dashuyun.cn/Article/details/gtpyeoojzx.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.ehwqpu.com/Article/details/gtbglzekha.html

[P02] MD5 / SHA256 摘要
来源：http://dali.mhx1999.top/Article/details/gttqqlaukw.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.vqdsnc.cn/Article/details/gtaayyzvyp.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.sweek.top/Article/details/gtkhwvtexp.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.hysaishi.cn/Article/details/gtinxwqqil.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.aibaodan.cn/Article/details/gtzpvatqxr.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.xuanzx.com/Article/details/gteqrldgtq.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.yuxming.cn/Article/details/gtpnlanlyp.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.hysaishi.cn/Article/details/gtkdbcoulo.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.jinqigfzy.top/Article/details/gtkllbqmea.html

[P03] 生成短随机字符串
来源：http://dali.ehwqpu.com/Article/details/gtyheiiugs.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.xziqi.cn/Article/details/gtirfqvqcr.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.xylfe.cn/Article/details/gtsqzwebcz.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.aizwys.cn/Article/details/gtzdqcacnl.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.0kj1m.cn/Article/details/gtywbcgsje.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.sxryk.cn/Article/details/gtqcewsqif.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.yj20258888.top/Article/details/gtqrshmhur.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.jinqigfzy.top/Article/details/gtcxvamvhz.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.jinghuilouyu.cn/Article/details/gthlvdmyot.html

[P04] 求长度
来源：http://dali.xziqi.cn/Article/details/gtubegysxk.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.quarkkingdee.top/Article/details/gtpnjonzjc.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.ivvv.top/Article/details/gtkgvzozus.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.ivvv.top/Article/details/gtnejpyajv.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.yuanzhike.top/Article/details/gtbfvazlyp.html

Java: list.size();  map.size();  s.length()
来源：http://dali.ppjwa.cn/Article/details/gtpyofcfzs.html

Go:   len(arr);  len(m)
来源：http://dali.cashguo.top/Article/details/gtlywqsaet.html

Ruby: x.length;  x.size
来源：http://dali.hammf.cn/Article/details/gtjilvpytd.html

C#:   list.Count;  dict.Count;  s.Length
来源：http://dali.snrcjt.cn/Article/details/gtfdyydltk.html

[P05] 判断两个对象内容是否相等
来源：http://dali.gzhubu.top/Article/details/gtvfkihpkb.html

Py:   a == b              # 列表与字典递归比较内容
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlpictrvj.html

PHP:  $a == $b            // 值比较；$a === $b 要求顺序与类型一致
来源：http://dali.snrcjt.cn/Article/details/gtrhpfmfyx.html

JS:   JSON.stringify(a) === JSON.stringify(b)   // 简单场景；复杂用深比较库
来源：http://dali.tanke756.top/Article/details/gtrsqbozpg.html

TS:   JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.gzhubu.top/Article/details/gtxeiipcwx.html

Java: a.equals(b)         // 需正确实现 equals；数组用 Arrays.equals
来源：http://dali.meibo888.top/Article/details/gteykfqwnd.html

Go:   reflect.DeepEqual(a, b)
来源：http://dali.daria6918.cn/Article/details/gtrylxoxwr.html

Ruby: a == b
来源：http://dali.zhongyouzk.top/Article/details/gtveejnfhb.html

C#:   Equals(a, b)  或 StructuralComparisons
来源：http://dali.jinqigfzy.top/Article/details/gtafzaytfq.html

[P06] 综合判空（null / 空串 / 空集合）
来源：http://dali.cdnleiting.top/Article/details/gtpwgrgwhm.html

Py:   if not x:           # None、""、[]、{}、0 均为假
来源：http://dali.hnxiangtu.top/Article/details/gtzueerkdq.html

PHP:  if (empty($x)) {}
来源：http://dali.yueranfly.top/Article/details/gtwqpalpas.html

JS:   if (x == null) {}    // 同时覆盖 null 与 undefined
来源：http://dali.cheryme.top/Article/details/gteyntxmpg.html

TS:   if (x == null) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtekpkgwsm.html

Java: if (x == null || x.isEmpty()) {}
来源：http://dali.xuetiantiany.cn/Article/details/gtwrgvlevh.html

Go:   if x == nil {}
来源：http://dali.smart0.xyz/Article/details/gtxibemjtg.html

Ruby: if x.nil? || (x.respond_to?(:empty?) && x.empty?)
来源：http://dali.zhoulong.xyz/Article/details/gtubxrxtdt.html

C#:   if (x is null) {}
来源：http://dali.jlsjyb.cn/Article/details/gtyujhgxca.html

[P07] 防抖与节流
来源：http://dali.daria6918.cn/Article/details/gtgebvzcgk.html

Py:   # 用装饰器 + threading.Timer 实现；或 functools.lru_cache 做缓存
来源：http://dali.jqgfzy.top/Article/details/gtfvsxlxmt.html

PHP:  // 手写时间戳比较
来源：http://dali.zhoulong.xyz/Article/details/gthbdvkxgm.html

JS:   const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.gzhubu.top/Article/details/gthxononsm.html

TS:   const debounce = <A extends unknown[]>(fn: (...a: A) => void, ms: number) => { let t: ReturnType<typeof setTimeout>; return (...a: A) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yueranfly.top/Article/details/gtsbloaufp.html

Java: long last = 0;  if (now - last > ms) { last = now; run(); }
来源：http://dali.ydzc1.top/Article/details/gtsrtbbasp.html

Go:   time.AfterFunc 实现，或用带缓冲 channel 丢弃
来源：http://dali.zhixingplan.top/Article/details/gtliuikfqp.html

Ruby: // 手写闭包 + Time.now 判断
来源：http://dali.mhx1999.top/Article/details/gtlghotopw.html

C#:   // 用 System.Timers.Timer 重置实现
来源：http://dali.iojbl.cn/Article/details/gtojioivgl.html

[P08] 处理浮点精度问题
来源：http://dali.yanxiufei.cn/Article/details/gtloxnkjwj.html

Py:   Decimal("0.1") + Decimal("0.2");  round(0.1 + 0.2, 10)
来源：http://dali.jinghuilouyu.cn/Article/details/gthnsqydci.html

PHP:  bcadd("0.1", "0.2", 2);
来源：http://dali.vqdsnc.cn/Article/details/gtztyadwtr.html

JS:   (0.1 + 0.2).toFixed(2);  Math.round((0.1 + 0.2) * 100) / 100
来源：http://dali.xylfe.cn/Article/details/gtjdjtaeby.html

TS:   (0.1 + 0.2).toFixed(2)
来源：http://dali.chenlongwang.top/Article/details/gtaxgjkesa.html


<!-- 参考信息 -->